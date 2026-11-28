# Aesth — Research

Skin: Aesthcapades (`aesthcapades.json`) · Domain: Aesthetics — Taste Preferences & Judgments of Beauty · Meter: taste
Coverage: 50 topics, 140 poles, 8 archetypes (all counts taken from the skin JSON).

## 1. Domain framing

Aesthcapades maps aesthetics in the lived sense: what moves a person in pictures, music, stories, dress, rooms, landscapes and food — and what theory of taste stands behind the moving. The domain runs from the gallery questions (depiction, materiality, what counts as art) through the daily ones (how much spice, how full a room, cook or be cooked for) to the judgment questions underneath both (whether beauty is objective, whether taste can be learned, whether a work can be separated from its maker).

The meter word is **taste**. What is measured is a person's sensibility as a set of positions: on each topic the rater takes a stance toward the topic's poles, and the pattern of stances is the taste. A position here is a rated preference with reasons behind it — representational against abstract, canon against gut, fuel against feast. What does not count as a position is a bare consumption fact (what someone bought, streamed or visited) with no stance in it, or a professional credential; the skin rates what a person loves and why, not what they have consumed or studied.

**Rating contract.** The inputs a profile supplies are **advocacy per pole** (a signed number, −100 to +100, for each pole of each topic; positive is for the pole, negative is against it) and **openness per topic** (0–100, how willing the profile is to hear other positions on that topic). Everything else is derived, never rated directly: **receptivity** is `round-half-even(openness × advocacy)`, computed with exact fractions rather than floating-point arithmetic, and **intensity** is the signed largest-|value| pole — the strongest pole, carrying its sign. Aversion therefore lives only in a rating's sign; it is never encoded anywhere else, and no sign is ever flipped or folded. On the skin's single-pole (monopole) topic the one number is an affinity, and a negative value reads as aversion. On xy-switchbox topics the two poles are crossed, independent yes/no axes — a holder may affirm either, both, or neither — not opposite ends of one scale, and the both-negative position is the status-quo middle.

The skin's stance is pluralist but not empty: every taste on the map, from the formalist's objective standards to the subjectivist's shrug, is stated in its holders' strongest terms, and the map treats a guilty pleasure, a dietary refusal and a theory of the sublime as the same kind of object — a position that can be backed. The Scribe for this skin is an **indaba** — a meeting of the recorded tastes that works toward consensus by naming where sensibilities meet, where they part, and what would move each holder — and the research below is written to be lifted into that meeting: reasons and numbers per position, and, for each archetype, what it can hear and what it cannot.

## 2. Topic rationale

### Visual Art

**Depiction** — How far a picture should travel from the look of the world — the oldest axis in visual art. Representational: Art depicts the world as it is. Stylized: A deliberate departure from likeness, in a style of its own. Abstract: Art departs from likeness.

**Era** — Where authority in art lives — in the tested past or the untested present. Classical: Traditional, the old masters. Contemporary: Avant-garde, the new edge.

**Photo purpose** — What a photograph is for — three honourable answers that pull against each other. Documentary: Truth, record, witness. Fine Art: Expression, composition, vision. Vernacular: Snapshot, memory, the everyday.

**Materiality** — Whether the hand's trace should remain in the surface. Tactile: Heavy paint, sculptural impasto, visible brushwork. Subtle texture: Some surface to the hand and eye, kept quiet. Flat: Vector smoothness, digital gradient, airbrushed finish.

**Truth to Materials** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Should a medium proudly show its grain, brushstrokes, and seams, or dissolve into seamless illusion?” A switchbox of two crossed claims — whether a medium should show what it is, and whether seamless illusion is a legitimate magic; the axes are independent (see §5). Honest Materiality: Letting wood, stone, or synthesis sound like itself respects reality rather than faking surfaces. Illusionistic Magic: Seamless world-building transports the audience completely into another reality.

**Original Aura vs. Remix** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “How much does singular human handcraft matter in an age of infinite copying and algorithmic tools?” What happens to the unique handmade object in the age of copies and generators. Singular Physical Aura: Standing before a unique artifact touched by a mortal hand carries irreplaceable presence. Open Remix & Collage: Culture has always grown through sampling, quotation, and creative transformation of shared material. Generative Co-Creation: AI and procedural tools expand human imagination into spaces no solo hand could explore.

### Music & Sound

**Song focus** — Where a song's centre of gravity sits — in what it says or in how it sounds. Words: Lyrics carry the song. Both carry it: The song carried by words and music in equal measure. Music: The sound carries the song.

**Performance** — The room against the record — presence against permanence. Live: Performance in the room. Recorded: Studio, the record.

**Music taste** — Where the ear lives among the popular, the artful and the canonical. Popular: Melody, immediacy, the charts. Art: Innovation, difficulty, the edge. Classical: Canon, form, heritage.

**Virtuosity vs. Rawness** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Do you value hard-won technical command or unpolished, urgent immediacy?” A switchbox of two crossed claims — whether technical mastery is expression's liberation, and whether rawness is authenticity's proof; the axes are independent (see §5). Disciplined Mastery: Years of technical rigor liberate expression and allow precision amateurs can never reach. Outsider Raw Authenticity: Over-polished technique can sand away the trembling vulnerability that makes art feel alive.

### Story & Word

**Fiction** — What kind of reading pleasure is trusted — the story's machinery or the sentence's craft. Genre: Plot-driven. Literary genre: Genre storytelling written with literary craft. Literary: Character-driven.

**Story focus** — What carries a story — events or the people they happen to. Plot: What happens. Plot through character: Story carried by what happens to people you follow. Character: Who it happens to.

**Story medium** — The screen against the page as story's native home. Film: The screen. Literature: The page.

**Plot vs. Atmosphere** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Should a story drive forward through causal stakes, or let the audience inhabit a mood and place?” A switchbox of two crossed claims — whether a story owes forward drive, and whether atmosphere is itself a sufficient good; the axes are independent (see §5). Tight Narrative Engine: Crisp causality, setup, and payoff respect the audience's time and create unforgettable momentum. Lingering Mood & Drift: Life rarely resolves into neat three-act arcs; drifting atmosphere feels truer to lived memory.

**Ambiguity vs. Closure** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Should great works leave mysteries unresolved, or deliver a satisfying emotional synthesis?” A switchbox of two crossed claims — whether a work should close its questions, and whether openness is what keeps it alive; the axes are independent (see §5). Haunting Open Ending: Unanswered questions keep a story alive in the mind long after the final page or frame. Earned Cathartic Closure: Completing the arc gives emotional weight and structural justice to everything that came before.

**Realism vs. Speculation** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Does fiction illuminate the human condition best through faithful everyday observation or estranged worlds?” Where fiction's truth is found — in the observed room or the estranged world. Psychological Realism: Minute social and emotional fidelity reveals profound drama inside ordinary rooms. Mythic & Speculative Worlds: Estranged worlds strip away familiar blinders and test human nature under extreme conditions.

**Tragedy** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “What is tragedy for — purging emotion, affirming life, or is the form dead?” What tragedy is for — the classical answers and the modern doubt. Catharsis: Tragedy purges pity and fear. That discharge is what it is for. Affirmation: Tragedy affirms life, including its terror. It does not only wash emotion out. Impossible now: Tragedy needs a shared order and a hero who can fall from it. That order is gone.

**Comedy and the comic** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Why do we laugh — because we feel above it, because it does not fit, or because tension breaks?” Why we laugh — the three classical theories of the comic, rated as tastes. Superiority: We laugh because we feel above the butt of the joke. Incongruity: We laugh because something does not fit the pattern we expected. Relief: We laugh because tension is discharged.

### Beauty & Adornment

**Enhancement** — The face and body as found, or as improved. Natural: Unaugmented, as you are. Subtly enhanced: A light touch: enhancement you notice only up close. Enhanced: Makeup, grooming, cosmetic procedures.

**Style** — How much is enough, worn on the body. Minimal: Understated. Edited boldness: Bold choices, few of them. Maximal: Bold.

**Fashion** — Dress as speech or as belonging — both are real functions of clothing. Self-expression: Dress to say something. Coded expression: Expressing yourself in the code of your group. Conformity: Dress to belong.

### Space & Place

**Architecture** — The built environment's two tempers — glass and steel against stone and arch. Modern: Minimal, glass and steel. Transitional: Traditional forms in modern materials and lines. Traditional: Ornamental, stone and arch.

**Interiors** — How much stuff a room needs before it is a home. Minimal: Sparse. Warm minimal: Few things, warmly chosen. Cozy: Layered.

**Landscape** — Which landscape moves the holder — the made or the wild. Urban: Built, the skyline. Natural: Wild, the wilderness.

### Taste & Judgment

#### Beauty & Value

**Culture** — Where taste places itself among the consecrated, the popular and the disreputable. High: The consecrated, the curriculum. Popular: The widely loved, the charts. Low: The gutter, the guilty pleasure.

**Taste authority** — When inherited judgment and one's own gut disagree, which is trusted. Trust the canon: The consecrated judgment. Canon as counsel: The canon advises; your own taste decides. Trust your own taste: Your gut.

**Amount** — The meta-aesthetic dial — how much of anything is the right amount. Minimalism: Less is more. Curated plenty: Plenty, but every piece chosen. Maximalism: More is more.

**Kitsch & Camp** — Kitsch and camp — loved straight, loved ironically, or refused. Sincere enjoyment: You love it straight. Ironic appreciation: You love it because it's bad. Rejection: You don't love it at all.

**Theories of Beauty** — The four historical tempers of beauty itself. Classical Harmony: Symmetry, order, proportion. Sublime: Awe, vastness, terror. Picturesque: Roughness, variety, irregularity. Grotesque: The ugly as aesthetic value.

**What counts as art?** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “What makes something art — the artworld, the experience, the maker's intention, or the job it does?” The definition question — what makes a thing art at all. Institutional: It is art when the artworld treats it as art. Aesthetic: It is art when it affords aesthetic experience. Intentional: It is art when the maker meant it as art. Functional: It is art when it does an artistic job.

**Can taste be learned?** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Can you learn good taste, or is it born in, or only what a class taught you?” Whether taste is a gift, an education, or a class inheritance. Innate: Taste is a gift. Training polishes it and does not create it. Learned: Taste is education and exposure. You can acquire it. Socially constructed: Taste is what a class and a culture trained you to call good.

#### Form & Meaning

**Imperfection** — The finish question — patina against perfection. Wabi-Sabi: Imperfection, transience, natural weathering, raw patina. Lived-in polish: Polish that lets the wear show. Pristine: Flawless surfaces, high polish, geometric symmetry.

**Objectivity of Beauty** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “When two people disagree about whether a work is great, can one of them actually be wrong?” Whether aesthetic disagreement can have a right answer. Realist Standards: Harmony, depth, and formal mastery are real qualities that separate lasting art from kitsch. Intersubjective Sensus: Aesthetic judgment isn't physics, yet cultivated critics converge across centuries on enduring excellence. Pure Subjective Preference: Beauty exists strictly in the nervous system of the beholder; declaring superiority is mere status signaling.

**Surface vs. Depth** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “What hooks you first and holds you longest: immediate sensory seduction or hidden architecture?” A switchbox of two crossed claims — whether the surface seduces first, and whether depth is what lasts; the axes are independent (see §5). Visceral Sensory Surface: Color, groove, texture, and light hit the body directly before the intellect ever speaks. Conceptual & Symbolic Depth: Works reward repeated return when every detail interlocks inside an intricate conceptual design.

**Difficulty & Effort** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Is the best art the kind that makes you work for its rewards, or the kind that welcomes you immediately?” A switchbox of two crossed claims — whether difficulty is a price worth paying, and whether immediate delight is a virtue rather than a defect; the axes are independent (see §5). Demanding Slow Burn: Wrestling with complex works expands your perceptual capacity in ways easy pleasure never can. Immediate Generous Delight: Accessibility is a virtue, not a flaw; great art can hit the heart on first contact.

**What art knows** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Can art teach what nothing else teaches, or does it only give an experience?” Whether art is a way of knowing, and if so, of what kind. Art gives knowledge: Art teaches something that is really knowledge. Art gives no knowledge: Art gives experience, not a claim you can know. Emotional knowledge: What art knows is feeling: what an emotion is like from inside.

#### Artist & Audience

**Autonomy vs. Engagement** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Should art be judged solely on aesthetic power, or held accountable for its moral and social impact?” A switchbox of two crossed claims — whether art answers only to itself, and whether it answers for its effects in the world; the axes are independent (see §5). Art for Art's Sake: Subordinating art to didactic messaging turns living imagination into flat propaganda. Moral & Political Duty: Every artwork shapes empathy and power, so pretending art floats above ethics is bad faith.

**Artist vs. Text** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “How much should the creator's biography and stated intention constrain how we interpret a work?” A switchbox of two crossed claims — whether the maker's intention governs interpretation, and whether the released work belongs to its audience; the axes are independent (see §5). Authorial Intent: Understanding what the maker was trying to solve unlocks layers a careless reader misses. Death of the Author: Once released, a work belongs to its audience and often knows deeper truths than its maker consciously intended.

**Separating Art from Artist** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Can we cherish a masterpiece created by someone who committed serious moral wrongs?” A switchbox of two crossed claims — whether a work can be cherished apart from its maker, and whether celebrating it launders the maker; the axes are independent (see §5). Autonomous Work: Disowning great art because its maker was flawed deprives humanity of beauty no saint ever produced. Moral Taint: Celebratory engagement inevitably launders the creator's reputation and ignores the victims of their harm.

**Solitary Absorption vs. Communal Ritual** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Does art hit deepest alone in quiet focus, or in a crowd breathing and moving together?” A switchbox of two crossed claims — whether art lands deepest in solitude, and whether its native element is the crowd; the axes are independent (see §5). Private Contemplation: Solitude removes social performance and lets a book, painting, or album speak directly to you. Live Collective Effervescence: Concerts, theaters, and festivals turn individual feeling into shared human electricity.

**Craft and the useful arts** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Is a well-made chair art, or is art only what is made for its own sake?” Whether the useful arts belong inside art's boundary. Art separate from craft: Art is for its own sake. Craft is for use. They are different practices. Art is craft: Art is making something well. Use does not disqualify it. The split is historical: The line between art and craft is an accident of history, not a fact about the work.

### Food & Flavor

**Eating** — The friends-compatibility axis — appetite for the unfamiliar table. Adventurous: Try anything. Cautiously adventurous: New dishes, one at a time. Cautious: Stick to the familiar.

**Heat** — Heat as a taste in itself, not a stunt. Mild: Little or no spice. Warm: Heat you feel without a fire alarm. Fiery: As hot as it gets.

**Dining** — The register a life of eating is lived in. Comfort: Hearty, familiar, home. Casual: Everyday, accessible, the neighborhood spot. Fine: Refined, experimental, the tasting menu.

**Five Tastes** — The five basic tastes as five appetites, each with its devotees. Sweet: Sweet Salty: Salty Sour: Sour Bitter: Bitter Umami: Umami

**Dietary Identity** — Dietary identity — what is eaten and what is refused, as a statement of self. Carnivore: Meat only. Omnivore: Everything. Pescatarian: Fish, no land meat. Ovo-Vegetarian: Eggs yes, dairy no, meat no. Lacto-Ovo Vegetarian: Eggs and dairy yes, meat no. Vegan: No animal products. Fruitarian: Fruit only.

**Keto** — A single-affinity topic: strictness of the ketogenic pattern, cross-cutting dietary identity rather than sitting on it (negative ratings read as aversion — see §5). Keto: High fat, low carb; cross-cuts dietary identity rather than sitting on it.

**Meals** — The kitchen against the restaurant as the place a life is fed. Cook: Make it yourself. Eat Out: Be cooked for, go out.

**Food** — Food's two natures — sustenance and celebration. Fuel: Functional sustenance; efficiency, fast preparation, minimal fuss. Weekday fuel, weekend feast: Fuel on weekdays; a feast when there is occasion. Feast: Sensory theater; multi-hour shared dining, ritual, pleasure.

**Culinary philosophy** — How a cook stands toward tradition — as law, as root, or as raw material. Authentic Purism: Heritage recipes, regional terroir, grandmother's technique. Rooted fusion: Fusion grounded in the traditions it borrows from. Experimental Fusion: Molecular gastronomy, boundary-breaking crossovers.

## 3. Reasons and statistics backing each position

### 3.1 Visual Art

#### Depiction
- **Representational** — Reasons: likeness is a discipline and a courtesy: it shows the viewer a world they can enter and tests the painter against the hardest standard there is — the thing itself. Statistic: No reliable statistic found. What would move a holder: a representational work whose fidelity the holder had to admit was dead — correct and lifeless beside a freer treatment of the same subject.
- **Stylized** — Reasons: style is the artist's signature on perception — a deliberate departure that says how the world felt, not only how it looked; holders prize the honesty of visible interpretation. Statistic: No reliable statistic found. What would move a holder: a stylisation that had become a formula, applied to subjects it no longer interpreted.
- **Abstract** — Reasons: form, colour and rhythm are subjects enough — Kandinsky's and Mondrian's wager; abstraction refuses to let recognition do the viewer's feeling for them. Statistic: No reliable statistic found. What would move a holder: an abstract work the holder found merely decorative, with no necessity in its forms.

#### Era
- **Classical** — Reasons: the old masters survived the only peer review that cannot be gamed — centuries of viewers; their solutions to composition, light and form are a standing education no generation should have to re-derive. Statistic: No reliable statistic found. What would move a holder: a canonical work the holder, looking honestly, found inert — and a contemporary one undeniably alive.
- **Contemporary** — Reasons: art that speaks to the present must risk the present's forms; reverence for the masters easily becomes a refusal to look at one's own time, and every master was once the new edge. Statistic: No reliable statistic found. What would move a holder: a celebrated contemporary work that, on a second year's viewing, had nothing under its novelty.

#### Photo purpose
- **Documentary** — Reasons: the camera as witness: a photograph's first dignity is that this happened, to these people, in this light; holders prize the evidentiary force no painting can claim. Statistic: No reliable statistic found. What would move a holder: a documentary image whose framing had quietly argued rather than witnessed.
- **Fine Art** — Reasons: a photograph is made, not taken — composition, printing and vision turn the world's material into the photographer's statement, as much an authored object as a canvas. Statistic: No reliable statistic found. What would move a holder: a fine-art photograph whose artifice had consumed its subject entirely.
- **Vernacular** — Reasons: the snapshot is photography's folk art — birthdays, streets, lovers — unposed evidence of how life actually looked; holders defend its artlessness as its truth. Statistic: No reliable statistic found. What would move a holder: a vernacular image the holder had to admit was only a record, with nothing in it that rewarded looking.

#### Materiality
- **Tactile** — Reasons: impasto and visible brushwork keep the making inside the made — the painting records its own gestures, and the body answers the body across the canvas. Statistic: No reliable statistic found. What would move a holder: a tactile surface whose texture was performing labour the image itself had not done.
- **Subtle texture** — Reasons: some surface, kept quiet: enough grain to remind the eye the work is a thing, not a window, without letting facture become the subject. Statistic: No reliable statistic found. What would move a holder: a case where the quiet surface was simply indecision between the two honest poles.
- **Flat** — Reasons: vector smoothness and the airbrushed finish pursue an image freed from the accidents of matter — holders prize the control, and the way flatness belongs to the screen age's native look. Statistic: No reliable statistic found. What would move a holder: a flat work whose seamlessness the holder found airless beside a textured treatment of the same image.

#### Truth to Materials
- **Honest Materiality** — Reasons: wood that looks like wood and a voice that sounds like its synthesis respect the audience's intelligence; the modernist doctrine of truth to materials holds that faking a surface is the one unforgivable lie. Statistic: No reliable statistic found. What would move a holder: an illusion so complete and generous that the holder had to grant it a different honesty — the honesty of theatre.
- **Illusionistic Magic** — Reasons: seamless world-building is art's oldest gift — the cave wall, the trompe-l'oeil, the film set; holders hold that transportation, not disclosure, is what audiences come for. Statistic: No reliable statistic found. What would move a holder: an illusion whose seams, once noticed, revealed how thin the world behind them was.

#### Original Aura vs. Remix
- **Singular Physical Aura** — Reasons: Benjamin's aura: the unique artifact, touched by a mortal hand, present in one place — standing before it is an encounter, and no copy, however perfect, is the same event. Statistic: No reliable statistic found. What would move a holder: a reproduction that moved the holder as the original had — forcing an account of what the aura actually added.
- **Open Remix & Collage** — Reasons: culture has always grown by quotation — folk tunes, jazz standards, Shakespeare's borrowed plots; remix is not the copy age's fall but its folk process, and originality was always recombination with nerve. Statistic: No reliable statistic found. What would move a holder: a remix that merely consumed its sources, adding appetite without transformation.
- **Generative Co-Creation** — Reasons: procedural and AI tools let a maker explore spaces of form no solo hand could reach; holders treat the machine as instrument and collaborator, with the artist's judgment — selection, direction, refusal — as the authorship. Statistic: No reliable statistic found. What would move a holder: a generated work in which the holder could find no judgment to credit — output without an author anywhere in it.

### 3.2 Music & Sound

#### Song focus
- **Words** — Reasons: the lyric is the song's argument and memory — Dylan's Nobel was the establishment conceding it; holders listen for the line that stays when the melody is forgotten. Statistic: No reliable statistic found. What would move a holder: a lyric-first song whose words, read on the page, were banal — carried entirely by delivery and sound.
- **Both carry it** — Reasons: the great songs are marriages: the words give the sound a subject and the sound gives the words a body, and separating them grades a duet as two solos. Statistic: No reliable statistic found. What would move a holder: a song the holder loved where one element was plainly carrying a weak other — and it did not matter.
- **Music** — Reasons: melody, harmony, groove and timbre speak before language and beneath it — most listeners cannot quote the second verse of songs that have moved them for decades. Statistic: No reliable statistic found. What would move a holder: a sound-first track whose empty lyric eventually hollowed the holder's pleasure in it.

#### Performance
- **Live** — Reasons: performance in the room is unrepeatable and communal — risk, air, other bodies; the record is a photograph of the event, and holders go to concerts for the thing photographs cannot hold. Statistic: No reliable statistic found. What would move a holder: a live performance so routine that the record's crafted version was plainly the greater artwork.
- **Recorded** — Reasons: the studio album is its own art form — constructed, layered, perfectible — and it is the version that accompanies a life, replayable at will; the vinyl revival shows listeners voting for the object as well as the sound. Statistic: US vinyl LP revenues were about $1.4 billion in 2024, the format's eighteenth consecutive year of growth (Recording Industry Association of America, 2024). What would move a holder: a recording whose perfection had polished away the urgency the same band had live.

#### Music taste
- **Popular** — Reasons: melody and immediacy are not failures of sophistication — a chorus that millions can carry is a technical achievement, and the charts are a real, if rough, instrument for measuring it. Statistic: global recorded-music revenues reached US$29.6 billion in 2024 (IFPI, Global Music Report, 2025). What would move a holder: a hit whose immediacy, for the holder, evaporated on the tenth hearing.
- **Art** — Reasons: innovation and difficulty are where music renews itself; the edge is uncomfortable by definition, and holders accept a high failure rate as the cost of the successes. Statistic: No reliable statistic found. What would move a holder: an art-music work whose difficulty proved to be a substitute for content.
- **Classical** — Reasons: the canon offers the deepest formal architecture music has built, performed at a standard no other genre attempts; holders treat it as a library that rewards a lifetime. Statistic: No reliable statistic found. What would move a holder: a canonical performance the holder found embalmed — correct, revered and unlistened-to in any living sense.

#### Virtuosity vs. Rawness
- **Disciplined Mastery** — Reasons: years of technique are what let a performer say exactly what they mean — the virtuoso's freedom is earned, and amateur immediacy is usually just a smaller vocabulary mistaken for honesty. Statistic: No reliable statistic found. What would move a holder: a masterful performance that left the holder cold, beside a raw one that told the truth.
- **Outsider Raw Authenticity** — Reasons: the trembling, untrained take can carry a feeling that polish sands away — punk and outsider art are built on the discovery; holders prize the sound of someone with no technique to hide behind. Statistic: No reliable statistic found. What would move a holder: a raw performance whose limitations, on honest listening, were only limitations.

### 3.3 Story & Word

#### Fiction
- **Genre** — Reasons: plot-driven fiction honours the reader's oldest contract — something happens, stakes rise, pages turn; holders resist the suggestion that momentum is a low ambition. Statistic: No reliable statistic found. What would move a holder: a genre novel whose machinery the holder could see working, to the story's cost.
- **Literary genre** — Reasons: genre's engines with literary craft — Le Guin, Chandler, the best of crime and SF; holders hold the hybrid refutes the shelf it is filed on. Statistic: No reliable statistic found. What would move a holder: a literary-genre work that fell between its ambitions, neither propulsive nor deep.
- **Literary** — Reasons: character-driven, sentence-first fiction treats consciousness itself as the event; holders prize the paragraph that changes how a room, a marriage, a grief is seen. Statistic: No reliable statistic found. What would move a holder: a literary novel whose sentences the holder admired and whose people they never believed.

#### Story focus
- **Plot** — Reasons: what happens is the story; character is revealed by action under pressure, and a plot that grips is the author's first duty to the reader's hours. Statistic: No reliable statistic found. What would move a holder: a plot-driven story whose ending the holder admired and whose people they immediately forgot.
- **Plot through character** — Reasons: events matter because of who they strike, and character is proven by what events force; the holder wants the causal chain and the face it changes. Statistic: No reliable statistic found. What would move a holder: a work where the blend satisfied neither appetite — too plotted to dwell, too inward to move.
- **Character** — Reasons: who it happens to is the story; plot is the pretext that lets a consciousness be watched closely, and holders reread for company, not for outcomes. Statistic: No reliable statistic found. What would move a holder: a character study in which nothing happening long enough became its own kind of implausibility.

#### Story medium
- **Film** — Reasons: the screen shows — faces, places, simultaneity — and film's grammar of cut and close-up is a century-deep language; some stories exist fully only when seen and heard. Statistic: No reliable statistic found. What would move a holder: an adaptation that showed everything and conveyed less than the novel's single interior chapter.
- **Literature** — Reasons: the page alone enters a mind from inside and lets the reader's imagination cast and light every scene; prose's instruments — free indirect style, the unreliable narrator — have no screen equivalents. Statistic: No reliable statistic found. What would move a holder: a novel the holder had to admit was a film manqué — all dialogue and set direction, waiting for a camera.

#### Plot vs. Atmosphere
- **Tight Narrative Engine** — Reasons: causality, setup and payoff respect the audience's time and create the momentum that makes an ending land; looseness is usually not freedom but unfinished work. Statistic: No reliable statistic found. What would move a holder: a tightly engineered story whose perfection left the holder nothing to carry away.
- **Lingering Mood & Drift** — Reasons: life rarely resolves into three acts, and the drifting work — Tarkovsky, slow cinema, the plotless novel — is truer to memory's texture; holders stay for the weather of a place and a mind. Statistic: No reliable statistic found. What would move a holder: a drifting work whose atmosphere, honestly examined, was concealing an absence of anything to say.

#### Ambiguity vs. Closure
- **Haunting Open Ending** — Reasons: an unanswered ending keeps working in the audience for years — the story's refusal to settle is its final act of respect for the material's real difficulty. Statistic: No reliable statistic found. What would move a holder: an open ending the holder judged a failure of nerve rather than a fidelity to difficulty.
- **Earned Cathartic Closure** — Reasons: completing the arc gives everything before it weight — Aristotle's catharsis is an engineering specification as much as a feeling; closure is not comfort, it is justice to the setup. Statistic: No reliable statistic found. What would move a holder: a closed ending so complete it shrank the work — every thread tied, nothing left alive.

#### Realism vs. Speculation
- **Psychological Realism** — Reasons: minute fidelity to ordinary rooms and marriages reveals drama enough; the realist holder holds that inventing worlds is often an escape from looking at this one. Statistic: No reliable statistic found. What would move a holder: a realist work whose fidelity was flawless and whose vision the holder found airless.
- **Mythic & Speculative Worlds** — Reasons: estrangement is a lens: remove the familiar and human nature can be tested at extremes the drawing room never reaches — the method of myth, SF and fantasy alike. Statistic: No reliable statistic found. What would move a holder: a speculative world whose estrangement served only its own cleverness, testing nothing human.

#### Tragedy
- **Catharsis** — Reasons: Aristotle's account still organises the experience: pity and fear, raised and purged by another's fall, leave the audience clarified rather than merely upset. Statistic: No reliable statistic found. What would move a holder: a tragedy whose effect on the holder was not purgation but a residue Aristotle's model could not describe.
- **Affirmation** — Reasons: the Nietzschean answer: tragedy does not wash terror away but affirms life with the terror in it — the Dionysian yes that the holder finds sterner and truer than purgation. Statistic: No reliable statistic found. What would move a holder: a tragic work whose affirmation the holder experienced as a doctrine imposed on suffering that resisted it.
- **Impossible now** — Reasons: Arthur Miller's problem from the other side: tragedy needs a shared order and a figure who can fall from it, and a fragmented age supplies neither; what remains is pathos, which the holder refuses to promote. Statistic: No reliable statistic found. What would move a holder: a contemporary work that achieved, for the holder, unmistakably tragic stature — order or no order.

#### Comedy and the comic
- **Superiority** — Reasons: Hobbes's sudden glory: laughter at the butt's expense is real laughter and most comedy runs on it; holders refuse to pretend the roast, the pratfall and the satire are something gentler. Statistic: No reliable statistic found. What would move a holder: a joke whose pleasure, honestly examined, contained no superiority at all — pure play.
- **Incongruity** — Reasons: Kant's strained expectation dissolving into nothing: the laugh is the pattern breaking, and holders prize incongruity because it explains wordplay and absurdity that superiority cannot reach. Statistic: No reliable statistic found. What would move a holder: a comic moment that worked by recognition and relief, with no incongruity the holder could find.
- **Relief** — Reasons: Freud's economy: laughter discharges tension that civilisation made us store — the forbidden, the anxious, the grieving all exit by this door; holders value the theory for comedy's unmistakable bodily release. Statistic: No reliable statistic found. What would move a holder: a laugh of pure delight, at nothing forbidden or tense, that the relief model had to strain to cover.

### 3.4 Beauty & Adornment

#### Enhancement
- **Natural** — Reasons: unaugmented, as you are: the holder prizes the face's own history and distrusts an industry whose profits grow with dissatisfaction. Statistic: No reliable statistic found. What would move a holder: an occasion where the holder's natural standard felt less like freedom than like a rule imposed on others.
- **Subtly enhanced** — Reasons: a light touch — enhancement noticed only up close; grooming as courtesy to the eye, continuous with dress and cleanliness rather than with surgery. Statistic: No reliable statistic found. What would move a holder: a subtle enhancement the holder realised was being read as a standard others were failing.
- **Enhanced** — Reasons: makeup, grooming and procedures are arts of self-presentation with honourable histories in every culture; the holder claims the face as a canvas and a choice, not a confession. Statistic: No reliable statistic found. What would move a holder: an enhancement culture whose escalations the holder found had stopped being anyone's choice.

#### Style
- **Minimal** — Reasons: understated dress trusts proportion, fabric and fit over display; the holder finds a single perfect garment louder than a rack of statements. Statistic: No reliable statistic found. What would move a holder: a minimal look the holder had to admit read as absence of thought rather than discipline of it.
- **Edited boldness** — Reasons: bold choices, few of them — one statement piece carried by quiet surroundings; editing, not timidity, is the skill. Statistic: No reliable statistic found. What would move a holder: an edited look whose single statement, honestly, was doing all the work the outfit should have shared.
- **Maximal** — Reasons: more, worn with nerve: pattern on pattern, ornament as joy; maximalist holders hold that restraint is one taste, not a commandment, and that abundance dressed well is generosity to the eye. Statistic: No reliable statistic found. What would move a holder: a maximal outfit in which the holder could no longer find the person inside the abundance.

#### Fashion
- **Self-expression** — Reasons: dress to say something: clothing is the most public text a person publishes daily, and the holder writes theirs deliberately. Statistic: No reliable statistic found. What would move a holder: a self-expressive outfit the holder realised was legible only as a costume.
- **Coded expression** — Reasons: expression inside a group's code — the subculture uniform, the professional's signals; the holder values fluency: saying oneself in a language others actually read. Statistic: No reliable statistic found. What would move a holder: a code whose fluency had become mere obedience in the holder's own wardrobe.
- **Conformity** — Reasons: dress to belong is not cowardice: uniforms and norms spare everyone a daily negotiation, and fitting in is a social kindness as well as a shelter. Statistic: No reliable statistic found. What would move a holder: a conformity the holder experienced as erasure — the belonging cost more than it gave.

### 3.5 Space & Place

#### Architecture
- **Modern** — Reasons: glass, steel and open plan answer honestly to modern materials and modern life; ornament applied to a frame it does not express is, for the modernist holder, a lie in stone. Statistic: No reliable statistic found. What would move a holder: a modern building the holder found hostile to every human use it housed.
- **Transitional** — Reasons: traditional forms in modern materials and lines — the holder wants the old proportions' human scale without the pastiche, and judges buildings one by one rather than by camp. Statistic: No reliable statistic found. What would move a holder: a transitional building that satisfied neither inheritance — timid where it should have chosen.
- **Traditional** — Reasons: stone, arch and ornament carry meanings modernism discarded at real cost — craft, memory, civic dignity; the traditionalist holder reads a classical facade as a sentence in a language the city once spoke fluently. Statistic: No reliable statistic found. What would move a holder: a traditional revival the holder had to call pastiche — the language spoken as costume.

#### Interiors
- **Minimal** — Reasons: sparse rooms rest the eye and expose proportion and light; the holder keeps few things so that each is chosen. Statistic: No reliable statistic found. What would move a holder: a minimal room the holder experienced as a hotel's — calm without a life in it.
- **Warm minimal** — Reasons: few things, warmly chosen — wood, wool, one painting, books enough; the holder wants minimalism's air with a pulse in it. Statistic: No reliable statistic found. What would move a holder: a warm-minimal room whose warmth, on inspection, was a purchased style like any other.
- **Cozy** — Reasons: layered rooms hold a life visibly — textiles, shelves, inherited objects; the cozy holder finds minimal rooms not calm but withholding. Statistic: No reliable statistic found. What would move a holder: a cozy room that crossed, for the holder, into clutter that taxed everyone in it.

#### Landscape
- **Urban** — Reasons: the skyline is humanity's collective artwork — density, light, ambition stacked; urban holders find in great streets the sublime the romantics found in Alps. Statistic: No reliable statistic found. What would move a holder: a city spectacle that left the holder longing for exactly the unbuilt horizon it excluded.
- **Natural** — Reasons: wilderness answers something no artefact reaches — scale without intention, beauty without an author; holders return from it recalibrated about what matters. Statistic: No reliable statistic found. What would move a holder: a wilderness sublime that, honestly, the holder experienced mostly as weather and discomfort.

### 3.6 Taste & Judgment

*Beauty & Value*

#### Culture
- **High** — Reasons: the canon and the curriculum are not conspiracies but accumulations — works that kept being chosen; the holder's pilgrimage is real, and the great museums' crowds testify that the consecrated still consecrates. Statistic: the Louvre received about 8.7 million visitors in 2024, making it the world's most-visited museum (Musée du Louvre, 2024). What would move a holder: a consecrated work the holder could not honestly defend against a living popular one.
- **Popular** — Reasons: the widely loved is data about what art does for people at scale; holders distrust any taste that cannot explain why millions are moved, only that they shouldn't be. Statistic: No reliable statistic found. What would move a holder: a popular phenomenon whose hold, examined, rested on everything except the work.
- **Low** — Reasons: the gutter has its own classics — pulp, exploitation, the guilty pleasure that is only guilty at dinner parties; holders prize low culture's energy, honesty and freedom from improvement. Statistic: No reliable statistic found. What would move a holder: a low pleasure the holder had to admit was low in the simple sense — nothing there when the transgression cooled.

#### Taste authority
- **Trust the canon** — Reasons: the canon is the distilled judgment of better-trained eyes across centuries; a beginner's gut disagreeing with it is information about the beginner, and the holder defers accordingly. Statistic: No reliable statistic found. What would move a holder: a canonical verdict history itself reversed — restoring the holder's gut to office in that case.
- **Canon as counsel** — Reasons: the canon advises and the gut decides, each correcting the other — deference without obedience, independence without arrogance; the mainstream of serious taste actually lives here. Statistic: No reliable statistic found. What would move a holder: a disagreement in which counsel and gut both failed, and only time arbitrated.
- **Trust your own taste** — Reasons: no one else has your nervous system or your history; a taste that is not finally one's own is a uniform, and the holder accepts being wrong in their own way over being right in someone else's. Statistic: No reliable statistic found. What would move a holder: a confident gut judgment the holder later recognised as pure fashion, worn unknowingly.

#### Amount
- **Minimalism** — Reasons: less is more: subtraction reveals structure, and the holder applies the dial everywhere — rooms, sentences, plates, playlists. Statistic: No reliable statistic found. What would move a holder: a minimal work whose less, honestly, was merely less.
- **Curated plenty** — Reasons: plenty with every piece chosen — abundance under editorship; the holder rejects the idea that virtue lies at either end of the dial rather than in the choosing. Statistic: No reliable statistic found. What would move a holder: a curated plenty that had quietly become maximalism with a press release.
- **Maximalism** — Reasons: more is more: density, layering and excess are aesthetics of generosity and appetite, from baroque altars to maximalist pop; restraint is a taste, not a truth. Statistic: No reliable statistic found. What would move a holder: a maximal work in which the holder could find no hierarchy — everything shouting, nothing heard.

#### Kitsch & Camp
- **Sincere enjoyment** — Reasons: the holder loves the sentimental figurine, the power ballad, the velvet painting — straight, without the protective irony; sincerity about low pleasures is itself a kind of taste-courage. Statistic: No reliable statistic found. What would move a holder: a sincere favourite the holder, on a colder look, could not defend even to themselves.
- **Ironic appreciation** — Reasons: Sontag's camp: loving the failed seriousness, the too-much — the pleasure is real but doubled, affection and quotation marks at once; holders prize the sophistication that can hold both. Statistic: No reliable statistic found. What would move a holder: an ironic favourite that had become, unadmitted, a sincere one — the quotation marks long gone.
- **Rejection** — Reasons: kitsch is emotion without cost and camp is evasion of judgment; the holder refuses both, holding that some pleasures are simply the taste buds being flattered. Statistic: No reliable statistic found. What would move a holder: a piece of kitsch that ambushed the holder with genuine feeling, against their whole position.

#### Theories of Beauty
- **Classical Harmony** — Reasons: symmetry, order and proportion please across cultures and centuries, which suggests they answer something built into perception; the holder trusts harmony as beauty's home key. Statistic: No reliable statistic found. What would move a holder: a harmonious work the holder found perfectly proportioned and perfectly forgettable.
- **Sublime** — Reasons: awe at vastness and terror — mountains, storms, infinities; Burke and Kant agree the sublime dwarfs the merely pretty, and holders chase the feeling of being exceeded. Statistic: No reliable statistic found. What would move a holder: a sublime spectacle that left the holder merely small, not enlarged — vastness without the answering lift.
- **Picturesque** — Reasons: roughness, variety and irregularity — the composed wildness between beauty and sublimity; holders prize the picturesque for teaching the eye to love what is not smooth. Statistic: No reliable statistic found. What would move a holder: a picturesque scene the holder recognised as wilderness arranged for consumption — nature as décor.
- **Grotesque** — Reasons: the ugly as aesthetic value — gargoyles, Goya, the carnivalesque body; holders hold that an art that cannot metabolise the grotesque is lying about the world by omission. Statistic: No reliable statistic found. What would move a holder: a grotesque work whose ugliness, for the holder, was only ugliness — transgression without transformation.

#### What counts as art?
- **Institutional** — Reasons: Danto and Dickie: the artworld's conferral is what distinguishes Duchamp's urinal from plumbing; holders find the theory the only one that fits the last century's facts. Statistic: No reliable statistic found. What would move a holder: an object the artworld consecrated that the holder could not, in conscience, call art — or one outside it they could not deny.
- **Aesthetic** — Reasons: a thing is art as it affords aesthetic experience — attention rewarded for its own sake; the holder keeps the definition where the encounter is, not where the committee sits. Statistic: No reliable statistic found. What would move a holder: a consecrated work that afforded the holder no aesthetic experience across honest attempts.
- **Intentional** — Reasons: the maker's intention is the thread: art is what was meant as art, and intention explains why the same object is a artwork in one pair of hands and a tool in another. Statistic: No reliable statistic found. What would move a holder: a work whose maker's stated intention the holder found plainly exceeded — or betrayed — by the work itself.
- **Functional** — Reasons: art is what does art's job — defamiliarising, commemorating, imagining otherwise; the functional holder judges borderline cases by their work in the world, not their paperwork. Statistic: No reliable statistic found. What would move a holder: an object doing art's job that the holder still balked at calling art — forcing the definition to show its seams.

#### Can taste be learned?
- **Innate** — Reasons: some ears and eyes are simply finer — training polishes a gift it does not create, as with perfect pitch; holders point to the prodigy and the untutored natural as the standing evidence. Statistic: No reliable statistic found. What would move a holder: a case of unmistakably acquired taste — the holder's own, learned late and learned completely.
- **Learned** — Reasons: taste is exposure plus attention: no one is born loving Bartók or bitter greens, and both are learnable delights; the holder treats taste as a curriculum anyone can enter. Statistic: No reliable statistic found. What would move a holder: a limit in the holder's own taste that decades of exposure never moved, suggesting a floor to learning.
- **Socially constructed** — Reasons: Bourdieu's demonstration: taste classifies the classifier, and what a class calls refinement is its own habits consecrated; holders hear 'good taste' as a social fact before an aesthetic one. Statistic: No reliable statistic found. What would move a holder: a judgment of quality that survived translation across classes and centuries — resisting the social explanation.

*Form & Meaning*

#### Imperfection
- **Wabi-Sabi** — Reasons: imperfection, transience and weathering are not flaws in the thing but its biography made visible; the cracked bowl mended with gold is the doctrine in one object. Statistic: No reliable statistic found. What would move a holder: an imperfection the holder had to call by its name — damage, not patina.
- **Lived-in polish** — Reasons: polish that lets the wear show — the holder wants care and history at once, surfaces maintained by use rather than embalmed against it. Statistic: No reliable statistic found. What would move a holder: a lived-in surface whose charm, inspected, was neglect with good branding.
- **Pristine** — Reasons: flawless surfaces and exact symmetry honour the maker's control and the object's idea; holders find in perfection a real and difficult beauty that patina-talk too easily excuses failing to reach. Statistic: No reliable statistic found. What would move a holder: a pristine object the holder found sterile beside a worn twin.

#### Objectivity of Beauty
- **Realist Standards** — Reasons: harmony, depth and formal mastery are real qualities of works, not projections — some disagreements are errors, and criticism exists because they can be corrected. Statistic: No reliable statistic found. What would move a holder: a disagreement between two judges the holder respects that no standard they could state would settle.
- **Intersubjective Sensus** — Reasons: Hume's standard and Kant's sensus communis: not physics, but not whim — cultivated judges converge across centuries on the same peaks, and that convergence is the objectivity taste actually has. Statistic: No reliable statistic found. What would move a holder: a convergence the holder judged to be fashion and institution rather than perception — the canon as echo.
- **Pure Subjective Preference** — Reasons: beauty is in the beholder's nervous system, full stop; declarations of superiority are status signals wearing philosophy, and the holder's honesty about this is a relief, not a loss. Statistic: No reliable statistic found. What would move a holder: a work whose excellence the holder experienced as simply there — as little optional as a colour.

#### Surface vs. Depth
- **Visceral Sensory Surface** — Reasons: colour, groove, texture and light hit the body before the intellect speaks — a work that fails the senses has no later in which to be deep. Statistic: No reliable statistic found. What would move a holder: a surface that seduced the holder completely and left nothing — the morning-after test depth exists to pass.
- **Conceptual & Symbolic Depth** — Reasons: works that reward return are built in depth — every detail interlocking in a design the first visit only sketches; holders reread, relisten and revisit for what the surface was carrying. Statistic: No reliable statistic found. What would move a holder: a deep design the holder decoded fully and found the decoding was the whole pleasure — a puzzle, not a work.

#### Difficulty & Effort
- **Demanding Slow Burn** — Reasons: wrestling with a hard work expands the perceiver — late Beethoven and Finnegans Wake pay compound interest that easy pleasures cannot; the effort is not the toll on the reward, it is part of it. Statistic: No reliable statistic found. What would move a holder: a demanding work whose difficulty, once mastered, revealed very little underneath.
- **Immediate Generous Delight** — Reasons: accessibility is a virtue: a melody, a joke, a face can strike the heart on first contact with a completeness no apprenticeship improves; holders distrust difficulty used as a gate. Statistic: No reliable statistic found. What would move a holder: an immediate delight that evaporated by the third encounter, leaving the holder wanting the slow burn they had scorned.

#### What art knows
- **Art gives knowledge** — Reasons: art teaches what nothing else teaches — how a siege, a marriage, a shame actually proceed from inside; the holder counts novels and films among their real educations and can say what they learned. Statistic: No reliable statistic found. What would move a holder: a purported lesson from a beloved work that turned out to be false about the world.
- **Art gives no knowledge** — Reasons: art gives experience, not propositions — nothing in a novel is asserted, so nothing in it can be known; the holder prizes art precisely for exemption from the truth-game. Statistic: No reliable statistic found. What would move a holder: a work from which the holder demonstrably learned something checkable and true.
- **Emotional knowledge** — Reasons: what art knows is feeling — what grief, ecstasy or humiliation are like from inside; that is real knowledge, of the kind no summary transmits, and the holder locates art's epistemic dignity there. Statistic: No reliable statistic found. What would move a holder: an emotional 'knowledge' from a work that the holder later found was a sentimentality — feeling simulated, not known.

*Artist & Audience*

#### Autonomy vs. Engagement
- **Art for Art's Sake** — Reasons: subordinating art to messaging turns imagination into propaganda with better lighting; the aesthetic movement's slogan remains the holder's defence of the useless, useless being the point. Statistic: No reliable statistic found. What would move a holder: a work the holder loved whose power was inseparable from its moral purpose — didactic and great.
- **Moral & Political Duty** — Reasons: every artwork trains empathy and distributes power; pretending otherwise is itself a political act, and holders hold makers answerable for what their work teaches audiences to feel and excuse. Statistic: No reliable statistic found. What would move a holder: a duty-first work that was dead as art — correct in every message, alive in none.

#### Artist vs. Text
- **Authorial Intent** — Reasons: knowing what the maker was trying to solve unlocks layers a careless reading misses — intention is evidence, and discarding evidence is not sophistication. Statistic: No reliable statistic found. What would move a holder: a work that plainly meant more, and better, than its maker ever intended.
- **Death of the Author** — Reasons: Barthes: once released, the work belongs to its readers, and often knows more than its maker did; holders find the author's commentary just one more reading, with no veto. Statistic: No reliable statistic found. What would move a holder: an interpretation, licensed by the author's death, that the holder had to call a plain misreading.

#### Separating Art from Artist
- **Autonomous Work** — Reasons: the work is not the maker: disowning great art for its maker's sins deprives everyone of beauty no saint produced, and the dead cannot be punished by our abstention. Statistic: No reliable statistic found. What would move a holder: a work whose maker's wrongs were inside the work itself — its subject, its making — so autonomy had nothing to attach to.
- **Moral Taint** — Reasons: celebration is a social act with beneficiaries: it rebuilds the wrongdoer's standing and tells victims their harm is a footnote; holders count that cost as part of the work's present meaning. Statistic: No reliable statistic found. What would move a holder: a tainted work whose suppression, the holder judged, would harm chiefly the innocent — students, audiences, the art itself.

#### Solitary Absorption vs. Communal Ritual
- **Private Contemplation** — Reasons: solitude removes performance — no one to be seen feeling; a book, a painting, an album can address one person with an intimacy no crowd survives. Statistic: No reliable statistic found. What would move a holder: a solitary encounter the holder only understood later, in a crowd's answering roar.
- **Live Collective Effervescence** — Reasons: Durkheim's term for the concert, the theatre, the festival: individual feeling amplified into shared electricity — some works exist fully only when a room breathes together. Statistic: No reliable statistic found. What would move a holder: a collective event whose effervescence, the holder saw, was manufactured — volume doing the work of value.

#### Craft and the useful arts
- **Art separate from craft** — Reasons: art is for its own sake and craft is for use — the chair serves a body, the painting serves nothing; the holder keeps the boundary because it protects art's freedom from function. Statistic: No reliable statistic found. What would move a holder: a useful object — a bowl, a bridge, a typeface — whose excellence the holder could only call art.
- **Art is craft** — Reasons: art is making something well: use does not disqualify, and the split insults every potter, luthier and joiner whose work outlasts most paintings; the holder judges by the making, not the category. Statistic: No reliable statistic found. What would move a holder: a superbly made object that the holder still experienced as purely instrumental — craft at its peak, art nowhere.
- **The split is historical** — Reasons: the art/craft line is an accident of Renaissance status politics and industrial manufacture, not a fact about objects; holders redraw it per case and decline to defend an inheritance. Statistic: No reliable statistic found. What would move a holder: a case where the split, accident or not, tracked a real difference the holder needed words for.

### 3.7 Food & Flavor

#### Eating
- **Adventurous** — Reasons: try anything once is the eater's version of empiricism; the adventurous holder treats an unknown menu as the cheapest travel there is. Statistic: No reliable statistic found. What would move a holder: a dish that taught the holder their adventurousness had a border after all.
- **Cautiously adventurous** — Reasons: new dishes one at a time, inside a basically trusted kitchen — exploration with a base camp; most honest eaters live here and the holder says so without shame. Statistic: No reliable statistic found. What would move a holder: an occasion where caution cost the holder the dish everyone else is still describing.
- **Cautious** — Reasons: the familiar, done well, is not a failure of curiosity: the cautious eater's pleasures are depth in a known cuisine, reliability, and never gambling an evening on a chef's experiment. Statistic: No reliable statistic found. What would move a holder: a cautious order the holder watched become the table's least interesting plate.

#### Heat
- **Mild** — Reasons: little or no spice lets the ingredients speak in their own voices; the mild holder hears heat, past a point, as volume drowning the music. Statistic: No reliable statistic found. What would move a holder: a mild dish so underseasoned the holder reached for the chilli themselves.
- **Warm** — Reasons: heat you feel without a fire alarm — warmth as emphasis, the dish's bass note rather than its solo. Statistic: No reliable statistic found. What would move a holder: a 'warm' dish whose heat crept until it was the only thing tasted.
- **Fiery** — Reasons: as hot as it gets: the fiery holder prizes capsaicin's endorphin weather and the cuisines — Sichuan, Thai, Mexican — that build whole architectures on it. Statistic: No reliable statistic found. What would move a holder: a fiery dish in which the holder had to admit the heat had replaced, rather than revealed, the cooking.

#### Dining
- **Comfort** — Reasons: hearty, familiar, home — food as shelter; the comfort holder holds that a cuisine's first job is to make people feel held, and judges restaurants accordingly. Statistic: No reliable statistic found. What would move a holder: a comfort meal whose familiarity had curdled into mere heaviness.
- **Casual** — Reasons: the neighbourhood spot, everyday and accessible — most real eating lives here, and the casual holder values the places a life is actually fed by over the places it celebrates in. Statistic: No reliable statistic found. What would move a holder: a casual favourite whose standards had quietly slipped past what affection should excuse.
- **Fine** — Reasons: the tasting menu as theatre and research — refined, experimental, exact; the fine-dining holder accepts the price as tuition in what food can be. Statistic: No reliable statistic found. What would move a holder: a fine meal whose refinement the holder experienced as anxiety plated — technique performing for itself.

#### Five Tastes
- **Sweet** — Reasons: sweetness is the first taste every human loves and the signal of ripe energy; its devotees defend dessert as a course, not a weakness. Statistic: No reliable statistic found. What would move a holder: a sweetness so unopposed the holder reached for salt or acid to rescue the dish.
- **Salty** — Reasons: salt is flavour's amplifier and its own pleasure — cured, brined, aged; devotees hold that undersalting is the commonest failure of timid cooking. Statistic: No reliable statistic found. What would move a holder: a dish where salting crossed from amplification into mere salinity.
- **Sour** — Reasons: acid is brightness — citrus, vinegar, fermentation; sour's devotees prize the cut it gives to fat and the wakefulness it brings to a palate. Statistic: No reliable statistic found. What would move a holder: a sourness that bullied every other flavour off the plate.
- **Bitter** — Reasons: bitter is the acquired adult taste — coffee, greens, aperitivi, dark chocolate; its devotees read the learning curve itself as the pleasure: the palate growing up. Statistic: No reliable statistic found. What would move a holder: a bitterness the holder could not learn — a wall in their own palate they had to respect.
- **Umami** — Reasons: the savoury depth of broth, mushroom, aged cheese and cured ham — the last taste to be named and the one cooks had used for millennia; devotees prize it as flavour's foundation. Statistic: No reliable statistic found. What would move a holder: an umami-heavy dish that flattened into monotone richness.

#### Dietary Identity
- **Carnivore** — Reasons: meat only: the holder's case ranges from ancestral-diet claims to a simple, settled preference for the foods they thrive on, and they accept the position's starkness rather than apologising for it. Statistic: No reliable statistic found. What would move a holder: evidence about their own health or conscience that made the holder qualify the all-meat rule.
- **Omnivore** — Reasons: everything, in the omnivore's cheerful settlement: the widest table, the fewest rules, curiosity as the only doctrine. Statistic: No reliable statistic found. What would move a holder: a food the omnivore met that their own ethics or body refused.
- **Pescatarian** — Reasons: fish yes, land meat no — a line drawn at the water's edge, held for reasons of health, environment or the felt difference between the animals. Statistic: No reliable statistic found. What would move a holder: an argument that the line, examined, sat in the wrong place for the holder's own reasons.
- **Ovo-Vegetarian** — Reasons: eggs yes, dairy and meat no — a rarer, more deliberate line, often drawn where dairy's ethics trouble the holder more than eggs'. Statistic: No reliable statistic found. What would move a holder: a practical or principled pressure that moved the holder's line in either direction.
- **Lacto-Ovo Vegetarian** — Reasons: eggs and dairy yes, meat no — the most widely kept vegetarian settlement in the West, balancing conviction against a workable table. Statistic: No reliable statistic found. What would move a holder: a showing that dairy or eggs, in the supply chains available to the holder, carried what they refused meat for.
- **Vegan** — Reasons: no animal products: the vegan holder's case is the consistency of the refusal — if animal use is the wrong, the menu is where the wrong is most daily; substitutes and cuisines built without animals have made the position a cuisine, not only a restriction. Statistic: No reliable statistic found. What would move a holder: a case — health, travel, a grandmother's table — where the rule's cost forced the holder to think hardest about its meaning.
- **Fruitarian** — Reasons: fruit only: the most restrictive pole on the map, held on grounds from ahimsa toward the plant itself to raw-food convictions; holders accept its difficulty as the position's honesty about its own logic. Statistic: No reliable statistic found. What would move a holder: medical or practical evidence that the diet, as the holder practised it, was harming them.

#### Keto
- **Keto** — Reasons: high fat, very low carbohydrate, kept strictly enough to stay in ketosis: holders cite appetite control, metabolic and therapeutic uses — the diet's origin is clinical, in epilepsy treatment — and the clarity of a bright-line rule. Statistic: No reliable statistic found. What would move a holder: evidence from the holder's own biomarkers or experience that strictness bought nothing over a looser low-carbohydrate pattern.

#### Meals
- **Cook** — Reasons: making it yourself is control, craft and care in one act; the cook's holder learns cuisines from inside and feeds people as a form of speech. Statistic: No reliable statistic found. What would move a holder: a period where cooking became one obligation too many, and being cooked for was the mercy.
- **Eat Out** — Reasons: to be cooked for is to be served the world's kitchens without owning any of them; the holder values the restaurant as theatre, research and rest from one's own repertoire. Statistic: No reliable statistic found. What would move a holder: a restaurant habit whose cost — money or sameness — the holder had to total up honestly.

#### Food
- **Fuel** — Reasons: functional sustenance: efficiency, nutrition, minimal fuss on the ordinary day; the fuel holder refuses to spend daily attention where it buys so little. Statistic: No reliable statistic found. What would move a holder: a fuel-regime meal that accidentally became a feast, and reminded the holder what the fuss was for.
- **Weekday fuel, weekend feast** — Reasons: the rhythm most holders actually live: weekdays fed efficiently, occasions feasted properly; the split protects both values from each other. Statistic: No reliable statistic found. What would move a holder: evidence the rhythm had collapsed — all fuel, the feast indefinitely postponed.
- **Feast** — Reasons: food as sensory theatre and ritual — multi-hour shared dining is among the oldest human ceremonies, and the feast holder treats the table as a place a life is celebrated, not merely refuelled. Statistic: No reliable statistic found. What would move a holder: a feast whose theatre, for the holder, had displaced the people it was staged for.

#### Culinary philosophy
- **Authentic Purism** — Reasons: heritage recipes and regional terroir are knowledge compressed by generations; the purist holds that a dish's identity is a real thing and that 'fusion' too often means two cuisines' clichés at once. Statistic: No reliable statistic found. What would move a holder: an authentic dish, faithfully made, that the holder found dead beside a heretical version.
- **Rooted fusion** — Reasons: fusion grounded in the traditions it borrows from — the borrowings studied, the roots honoured; most living cuisines were born exactly this way, at ports and borders. Statistic: No reliable statistic found. What would move a holder: a rooted fusion the holder judged had roots in neither parent — garnish-deep in both.
- **Experimental Fusion** — Reasons: molecular gastronomy and boundary-crossing as research: the experimental holder treats the kitchen as a laboratory whose failures are tuition and whose successes redraw the map. Statistic: No reliable statistic found. What would move a holder: an experiment whose novelty, once tasted, had nothing to say a second time.

## 4. Archetype research

All 8 samples in the skin have kind "archetype": four historical movements stated as temperaments and four modern taste-identities. Archetype ids covered in this section, in skin order: aesth-classicism, aesth-romanticism, aesth-modernism, aesth-postmodernism, aesth-omnivore, aesth-formalist-purist, aesth-avant-garde-provocateur, aesth-everyday-epicurean. Ratings in the skin rate advocacy per pole and openness per topic; the receptivity and intensity discussed below are the derived quantities (see §1), described in words, not re-rated here.

### Classicism — `aesth-classicism.svg`
Classicism looks back to the art and literature of ancient Greece and Rome as the model of excellence, valuing order, balance, clarity and restraint over emotional excess. In visual art it favours idealized forms, harmonious composition and measured proportion. Why it holds its positions: its ratings follow the §3 reasons for classical harmony, the canon, representational discipline and traditional form — the commitments named there are this archetype's premises about what art and appetite are for. Receptive to: classical harmony, the canon, representational discipline and traditional form (§3, Theories of Beauty; Depiction; Architecture), because those positions share its premises. Closed to: ironic remix and art-for-provocation, because its whole case is that excellence has a known address in the tested past. Emblem: images/emblems/aesth-classicism.svg

### Romanticism — `aesth-romanticism.svg`
Romanticism prized intense feeling, imagination and the individual over reason and classical rules. Its art and literature celebrate nature, the sublime, heroism and the exotic, often with dramatic colour and movement. Why it holds its positions: its ratings follow the §3 reasons for the sublime, sudden feeling, live performance and maximal expression — the commitments named there are this archetype's premises about what art and appetite are for. Receptive to: the sublime, sudden feeling, live performance and maximal expression (§3, Theories of Beauty; Performance; Amount), because those positions share its premises. Closed to: pristine minimalism and purely subjective shrugging, because feeling for the Romantic is knowledge, not weather. Emblem: images/emblems/aesth-romanticism.svg

### Modernism — `aesth-modernism.svg`
Modernism was the early-20th-century break with traditional forms, as artists and writers experimented with abstraction, fragmentation and new techniques to capture modern life. It rejected academic realism in favour of innovation and self-conscious form. Why it holds its positions: its ratings follow the §3 reasons for abstraction, honest materiality, demanding difficulty and the new edge — the commitments named there are this archetype's premises about what art and appetite are for. Receptive to: abstraction, honest materiality, demanding difficulty and the new edge (§3, Depiction; Truth to Materials; Difficulty & Effort), because those positions share its premises. Closed to: pastiche and heritage revival, which it reads as a refusal of one's own century. Emblem: images/emblems/aesth-modernism.svg

### Postmodernism — `aesth-postmodernism.svg`
Postmodernism questions the idea of a single true style or grand narrative, mixing high and popular culture, irony, pastiche and quotation. It treats styles as material to borrow and remix rather than rules to follow. Why it holds its positions: its ratings follow the §3 reasons for open remix, ironic camp, low culture and the death of the author — the commitments named there are this archetype's premises about what art and appetite are for. Receptive to: open remix, ironic camp, low culture and the death of the author (§3, Original Aura vs. Remix; Kitsch & Camp; Artist vs. Text), because those positions share its premises. Closed to: realist standards stated as timeless law, because its founding suspicion is of any single story about taste. Emblem: images/emblems/aesth-postmodernism.svg

### The Cultural Omnivore — `aesth-omnivore.svg`
The cultural omnivore is a sociological concept: someone whose tastes span both high culture and popular culture, from opera to pop music, rather than sticking to one level. Sociologist Richard Peterson coined the term in 1992 to describe how cultural elites had stopped being snobs and become broad in their tastes. Why it holds its positions: its ratings follow the §3 reasons for popular and high together, coded expression, rooted fusion and learned taste — the commitments named there are this archetype's premises about what art and appetite are for. Receptive to: popular and high together, coded expression, rooted fusion and learned taste (§3, Culture; Can taste be learned?; Culinary philosophy), because those positions share its premises. Closed to: every purism — it is closed not to positions but to the refusal of ranges, because breadth is its thesis (Peterson, 1992). Emblem: images/emblems/aesth-omnivore.svg

### The Formalist Purist — `aesth-formalist-purist.svg`
Values enduring craft, structural rigor, and beauty for its own sake, believing serious attention reveals objective artistic excellence. Why it holds its positions: its ratings follow the §3 reasons for realist standards, disciplined mastery, art for art's sake and the autonomous work — the commitments named there are this archetype's premises about what art and appetite are for. Receptive to: realist standards, disciplined mastery, art for art's sake and the autonomous work (§3, Objectivity of Beauty; Virtuosity vs. Rawness; Autonomy vs. Engagement), because those positions share its premises. Closed to: moral-taint and duty-first framings that grade works by their makers or messages rather than their making. Emblem: images/emblems/aesth-formalist-purist.svg

### The Avant-Garde Provocateur — `aesth-avant-garde-provocateur.svg`
Seeks art that disrupts comfortable habits, challenges power, and pushes mediums into unfamiliar territory. Why it holds its positions: its ratings follow the §3 reasons for the grotesque, haunting open endings, difficulty and art with a duty to disrupt — the commitments named there are this archetype's premises about what art and appetite are for. Receptive to: the grotesque, haunting open endings, difficulty and art with a duty to disrupt (§3, Theories of Beauty; Ambiguity vs. Closure; Autonomy vs. Engagement), because those positions share its premises. Closed to: comfort in every register — comfort food for the eye and ear alike — because disruption is its definition of art being awake. Emblem: images/emblems/aesth-avant-garde-provocateur.svg

### The Everyday Epicurean — `aesth-everyday-epicurean.svg`
Cares less about high-art gatekeeping than about filling daily life with sensory warmth, honest materials, and shared human joy. Why it holds its positions: its ratings follow the §3 reasons for the feast, cozy interiors, honest materials and shared tables — the commitments named there are this archetype's premises about what art and appetite are for. Receptive to: the feast, cozy interiors, honest materials and shared tables (§3, Food; Interiors; Solitary Absorption vs. Communal Ritual), because those positions share its premises. Closed to: gatekeeping in all its forms — canon-worship, difficulty as a gate, purity at the table — because its aesthetics is of daily life shared. Emblem: images/emblems/aesth-everyday-epicurean.svg

## 5. Gap analysis

**Positions with no archetype.** No archetype primarily embodies: the vernacular and documentary photographer as an identity; the cautious, comfort-first eater (the Everyday Epicurean covers the feast but not the caution); the traditional craftsman for whom Art is craft is a life rather than a pole; or a disability- and access-led aesthetics, for whom how art is encountered — captioning, touch, step-free space — is the first aesthetic question. The historical movements are covered by four strong archetypes; the contemporary identities are thinner at exactly the everyday end the skin's food and space categories map.

**Thin topics.** One topic carries a single pole — Keto (xae0028), a single-affinity (monopole) topic by the skin's own design: it cross-cuts Dietary Identity rather than sitting on it, the one number registers strictness of adherence, and a negative rating reads as aversion. It is thin by design rather than in error; the indaba can list backing for the sole pole (done in §3) but cannot locate a disagreement on it. Ten topics are xy-switchboxes — Truth to Materials (xae0038), Virtuosity vs. Rawness (xae0037), Plot vs. Atmosphere (xae0040), Ambiguity vs. Closure (xae0041), Surface vs. Depth (xae0036), Difficulty & Effort (xae0043), Autonomy vs. Engagement (xae0033), Artist vs. Text (xae0034), Separating Art from Artist (xae0035), and Solitary Absorption vs. Communal Ritual (xae0044): on each, the two poles are crossed, independent yes/no axes, not opposites, and the both-negative position is the status-quo middle; they are not flagged as defects. Five Tastes (xae0026) and Dietary Identity (xae0027) carry brief hovertip texts that merely restate each pole's label, so §2 and §3 carry their rationale from the wider literature of taste rather than from the skin's own hover text.

**Skin-JSON problems (reported, not fixed).** (1) 19 topics have an empty `question` field; §2 above includes the recovered question for each (see §5.1), taken verbatim from that topic's hovertip issue, and the skin JSON itself is unchanged. No other structural problems were found: every archetype rates all 50 topics, every topic's hovertip pole count matches its pole count, and the one subcategory-bearing category (Taste & Judgment) correctly keeps its topics inside its subcategories.

**Deliberately left out of this research.** Market and auction data except the three sourced figures in §6 (the skin maps taste, not prices); individual living artists' reputations, which the Separating Art from Artist topic treats as a question, not a docket; and any statistic not listed in §6 — where §3 could not ground a number in a source named with confidence, it says so rather than estimating.

### 5.1 Recovered question fields

The skin's `question` field is empty for the 19 topics below. Each recovered question is the topic's own hovertip `issue` text, verbatim — recovered, not invented — and is also quoted in §2 at the topic. The skin JSON is not changed by this research.

- **Truth to Materials** (xae0038) — “Should a medium proudly show its grain, brushstrokes, and seams, or dissolve into seamless illusion?”
- **Original Aura vs. Remix** (xae0039) — “How much does singular human handcraft matter in an age of infinite copying and algorithmic tools?”
- **Virtuosity vs. Rawness** (xae0037) — “Do you value hard-won technical command or unpolished, urgent immediacy?”
- **Plot vs. Atmosphere** (xae0040) — “Should a story drive forward through causal stakes, or let the audience inhabit a mood and place?”
- **Ambiguity vs. Closure** (xae0041) — “Should great works leave mysteries unresolved, or deliver a satisfying emotional synthesis?”
- **Realism vs. Speculation** (xae0042) — “Does fiction illuminate the human condition best through faithful everyday observation or estranged worlds?”
- **Tragedy** (xae0049) — “What is tragedy for — purging emotion, affirming life, or is the form dead?”
- **Comedy and the comic** (xae0050) — “Why do we laugh — because we feel above it, because it does not fit, or because tension breaks?”
- **What counts as art?** (xae0045) — “What makes something art — the artworld, the experience, the maker's intention, or the job it does?”
- **Can taste be learned?** (xae0048) — “Can you learn good taste, or is it born in, or only what a class taught you?”
- **Objectivity of Beauty** (xae0032) — “When two people disagree about whether a work is great, can one of them actually be wrong?”
- **Surface vs. Depth** (xae0036) — “What hooks you first and holds you longest: immediate sensory seduction or hidden architecture?”
- **Difficulty & Effort** (xae0043) — “Is the best art the kind that makes you work for its rewards, or the kind that welcomes you immediately?”
- **What art knows** (xae0046) — “Can art teach what nothing else teaches, or does it only give an experience?”
- **Autonomy vs. Engagement** (xae0033) — “Should art be judged solely on aesthetic power, or held accountable for its moral and social impact?”
- **Artist vs. Text** (xae0034) — “How much should the creator's biography and stated intention constrain how we interpret a work?”
- **Separating Art from Artist** (xae0035) — “Can we cherish a masterpiece created by someone who committed serious moral wrongs?”
- **Solitary Absorption vs. Communal Ritual** (xae0044) — “Does art hit deepest alone in quiet focus, or in a crowd breathing and moving together?”
- **Craft and the useful arts** (xae0047) — “Is a well-made chair art, or is art only what is made for its own sake?”

## 6. Sources

Statistics used in §3 (name + year + where to find it):
- IFPI (2025) — ifpi.org, *Global Music Report 2025* — global recorded-music revenues of US$29.6 billion in 2024.
- Musée du Louvre (2024) — louvre.fr, annual visitor figures — about 8.7 million visitors in 2024, the world's most-visited museum.
- Recording Industry Association of America (2024) — riaa.com, 2024 year-end revenue statistics — US vinyl LP revenues of about $1.4 billion in 2024.

Grounding for reasons (texts and traditions drawn on, not statistics): Walter Benjamin, "The Work of Art in the Age of Mechanical Reproduction" (1935), for aura and remix; Aristotle's *Poetics*, for catharsis, plot and tragedy; Friedrich Nietzsche, *The Birth of Tragedy* (1872), for tragic affirmation; Edmund Burke (1757) and Immanuel Kant (1790), for the sublime, the picturesque tradition and the sensus communis; David Hume, "Of the Standard of Taste" (1757), for intersubjective standards; Susan Sontag, "Notes on 'Camp'" (1964), for camp; Arthur Danto and George Dickie, for the institutional theory; Roland Barthes, "The Death of the Author" (1967); Sigmund Freud, *Jokes and Their Relation to the Unconscious* (1905), Thomas Hobbes, for the relief and superiority theories of laughter; Pierre Bourdieu, *Distinction* (1979), and Richard Peterson (1992), for socially constructed taste and the cultural omnivore; Émile Durkheim, for collective effervescence; and the wabi-sabi tradition of Japanese aesthetics, for imperfection. No other sources were used; no source above is cited for a statistic it did not supply.
