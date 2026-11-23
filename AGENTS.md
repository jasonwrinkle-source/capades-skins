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
- Adding a whole NEW skin file: don't just drop it in. A new skin needs
  wiring in the main repo (hostname routing, the icon catalog, install
  manifests, the guide) that this repo cannot carry. Leave the file plus a
  note in the commit message, and YoBiche will pick it up with Jason.
- When in doubt about how a field is used, the existing files are the best
  reference. For anything structural you can't settle from them, ask
  through Shel → Jason → YoBiche rather than guessing.
