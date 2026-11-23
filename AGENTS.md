# For Eros — working in capades-skins

You are Shel's agent, and this repo is hers to shape. It holds the content
files for Flexcapades hypermaps that Shel edits directly. This note is the
stuff you need that the README doesn't carry: how the plumbing actually
works, and the structural rules the bridge enforces.

## The flow

1. Shel edits a skin file here, through you, and you push.
2. YoBiche (Jason's Muse) runs a bridge script that fetches this repo,
   validates the files, and copies each skin into the main Sexcapades-Web
   repo — into both of its homes, `app/data/skins/` and
   `site-tree/public_html/hosted/data/skins/`, which must stay identical.
3. Jason approves the main-repo push, and the change ships with the next
   deploy.

A push here does not change the live site by itself, and it is not instant:
it lands when the next deploy goes out. Mention that to Shel if she is
waiting to see a change live.

## Pull before you edit

The bridge runs both ways. If a skin changes in the main repo first — a
restructure, new topics, a renamed category — YoBiche pushes the fresh file
INTO this repo (the Dancecapades subcategory restructure arrived that way).
Editing a stale copy and pushing would overwrite that newer structure, so
always pull before starting, and if a push is rejected as out of date, pull,
re-apply Shel's edits on the fresh file, and push again.

## Hard rules — the bridge refuses files that break these

1. **Ids are permanent.** Never renumber, rename, or reuse a topic,
   category, or subcategory id. New topics take the skin's prefix plus the
   next free number: Dance topics `xda` + four digits, subcategories
   `xdas` + two digits; Quest `xqu` / `xqus` the same way. Use the highest
   existing number + 1.
2. **Sample ratings must resolve.** Every key in a sample's
   `payload.ratings` must be a topic id that exists in the same file. If
   you remove a topic, remove or re-point its ratings in every sample.
3. **Subcategorized categories use `parentTopics`.** A category with
   subcategories keeps its own direct topics under `parentTopics`, never
   `topics` — a `topics` array on such a category is silently dropped by
   the app.
4. **Category names are load-bearing.** The app looks up each category's
   icon color and glyph by NAME in a catalog that lives in the main repo.
   Renaming a category is fine, but say so plainly in the commit message
   so YoBiche can update the catalog in the same pass — without that, a
   renamed category can break the map's painting.
5. **Leave `defaultLayout` alone.** It is machine-generated map geometry
   maintained from the main repo; the bridge overwrites edits to it.
6. **Keep the byte format:** JSON, two-space indent, UTF-8 (no `\u`
   escapes for ordinary characters), one trailing newline. The bridge
   normalizes format on copy, so a differently formatted file still lands,
   but matching the format keeps diffs readable.

## Soft guidance

- One skin per commit where you can, with plain-language commit messages
  saying what changed ("Added three topics to Swing & blues; renamed X to
  Y"). YoBiche reads them when bridging.
- The front-matter fields (`name`, `domain`, `meter`, `about`) are Jason's
  voice for the maps. Shel's edits there are welcome — flag them in the
  commit message so they get his eye before the deploy.
- Adding a whole NEW skin file: follow "Creating a new skin whole-cloth"
  below — file plus a short proposal note. It still won't go live from
  here; it goes to Jason for approval and YoBiche for wiring.
- When in doubt about how a field is used, the existing files are the best
  reference. For anything structural you can't settle from them, ask
  through Shel → Jason → YoBiche rather than guessing.

## Creating a new skin whole-cloth

A new skin starts here as a **proposal**: one JSON file plus one short
markdown note. Nothing you push goes live by itself — YoBiche checks the
structure, Jason approves the concept, and only then is it wired into the
main repo (routing, icon catalog, install manifests, guide) and shipped
in a deploy. Design freely; the approval gate is Jason, not the format.

### The proposal note

Alongside the JSON, add `<skin>-proposal.md` with:

- The one-liner: what the map is about, in the family's style
  ("lead, follow, and move together" / "the tales a table tells").
- A proposed **meter word** — the single word for what the map measures
  (interest, stance, belief, practice, groove, fun…). Jason rules on it.
- A proposed **subdomain prefix** and **id prefix** (below).
- The category list with topic counts, and the sample list.
- The **stance-or-action call**: most maps are stance maps (topics are
  positions people hold). A few are action maps (Sex, Dance, Quest),
  where topics are things people do together and direction matters.
  Say which you intend, and why — it's Jason's call per skin.

### Map types — read BRIEFING_HYPERMAP_TYPES.md

`BRIEFING_HYPERMAP_TYPES.md` in this repo is the family's type
framework: a type is fixed by what the rating *means*. Two types are
built and can be authored today — **stance** (positions; Advocacy /
Receptivity placements) and **action** (practices; give / receive
flanks). Three are envisioned only:

- **Mastery** (capability — can-do / can-teach): a proposal in this
  type is a proposal for a new type, not just a new skin. Name it as
  such in the proposal note; Jason rules on the type before the skin.
  If built, it twins a stance skin — same categories, leaves
  re-authored as performances.
- **Need** (requirement / capacity; intensity reads as urgency): same
  — a type proposal first, a skin second.
- **Drift** is a *meta* type: it has no taxonomy and cannot be
  authored as a skin JSON at all — it consumes timestamped profiles
  from other skins. If a drift idea comes up, write it as a note in
  the proposal, not as a file.

### The file

Name it `<skin>.json`, all lowercase, matching the skin's `skin` field
(`dancecapades.json`, `questcapades.json`). Top-level fields, in this
order: `skin`, `name`, `domain` (the one-liner), `meter`, `about` (one
paragraph — what the map is, who it's for), `categories`, `samples`,
`scribe`, `sceneSetter`. Leave `defaultLayout` OUT of a proposal —
YoBiche generates the starter layout at wiring time; a copied one will
only be replaced.

### Ids

Every skin has a short prefix: Dance topics are `xda`, Quest `xqu`,
Nous `xno`, Chem `xch`. Pick `x` + two letters from the new skin's name
that no existing skin uses, and propose it in the note. Then:

- Categories: prefix + `c` + two digits (`xdac01`).
- Topics: prefix + four digits (`xda0001`), numbered straight through
  the whole file, not per category.
- Subcategories: prefix + `s` + two digits (`xdas01`).

### Categories and topics

Six to ten categories is the family range. A category is
`{id, name, about, topics}` when flat, or `{id, name, parentTopics,
subcategories}` when layered (rule 3 above). Category names matter
beyond this file (rule 4) — choose them as if they were permanent.

Topic shapes, by what the topic IS:

- **Plain affinity** — `{id, name, type: "single"}`. One number;
  negative means aversion. Most topics on most maps.
- **Directional pair** (action maps only) — `type: "give_receive"` with
  `give_label` and `receive_label`. Direction is never averaged in this
  system; only use it where the two directions are genuinely different
  experiences.
- **Triad** — `archetype: "multi-affinity"`, `widget: "triangle"`,
  `poleReading: "complement"`, a `question`, and a `hovertip`:
  `{issue, poles: [{label, text}, …]}` defining each pole. Three stances
  that blend.
- **Line** — `widget: "trilinear-line"`, `archetype: "line"`, `poles`
  as `[left, middle, right]`: one dimension, the middle a real position
  or a blend.
- **Switchbox** — `widget: "xy-switchbox"` with two poles: two crossed
  yes/no questions.

House rule worth knowing before you design: where a topic's positions
are really ends of one dimension, the line or switchbox form wins over
two independent sliders — coherence over sympathy. And every multi-pole
topic carries the hovertip with per-pole definitions; that's the
standard Jason approved, not decoration.

### Samples — personas are archetypes

Four to eight sample profiles. **Personas are archetypes**: a sample
that is a character type ("The Forever GM") gets `"kind": "archetype"`
— the menu lists it by name alone, with its `about` in a hover tip.
Reserve `"kind": "sample"` for real profiles and documents (Adam and
Eve on Sexcapades; the party platforms on Polis), which list with a
rated-topic count. Mixing these up is the one error that has actually
shipped; don't repeat it.

Each entry: `{name, count, about, links: [], payload, skin, kind}`,
where `count` equals the number of ratings and `payload` is
`{app: "sexcapades", version: 16, noFlash: true, profileName,
archetype, aboutMe, ratings, skin}`. Ratings are keyed by topic id:
a plain number for single topics, `{"give": v, "receive": v}` for
directional pairs, `{"line": v}` for lines, and `{poleKey: v, …}` for
triads and switchboxes. Values run −100…100; a 0 is a real rating.

### What to leave out

- **Communities:** skins are born with none. The per-topic community
  links are a separate research pass done with Jason; never invent
  links, and never guess at a Discord.
- **`defaultLayout`:** omitted, per above.
- **Popularity/prevalence data:** Polis carries some; new skins don't.

For `scribe` and `sceneSetter`, copy the block shape from an existing
skin in this repo and rewrite the prose for the new map — on stance
maps the Scribe writes an informed discussion between the stances and
the Scene Setter is a discussion moderator; on action maps they follow
the Dance/Quest pattern instead. Keep the field structure identical.

One new skin per commit: the JSON, the proposal note, nothing else.
