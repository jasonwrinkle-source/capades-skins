# Dance — Research

Skin: Dancecapades (`dancecapades.json`) · Domain: Partner Dance — Leading, Following, and the Social Floor · Meter: groove
Coverage: 86 topics, 111 positions (40 poles across 15 multi-pole topics, plus 71 single or directional practices rated as one position each), 10 archetypes (all counts taken from the skin JSON).

## 1. Domain framing

Dance is an **action** skin: its topics are not positions people hold but practices people do together — dances, holds, invitations, settings. A position here is a rated affinity for a practice: how much a dancer is into doing it (positive) or averse to it (negative — aversion, not absence; holding no stance is not a position, and a 0 rating is). Where a practice is directional, the skin rates the directions separately and never averages them: most dances carry lead and follow ratings (the skin's `give_label` / `receive_label` pair), Asking someone to dance carries ask / be asked, Dips carries dip / be dipped, and Lifts & aerials carries lift / be lifted. For the skin's multi-pole topics the rating contract is the general one: advocacy per pole plus openness per topic are the inputs; receptivity is derived as round-half-even(openness × advocacy) computed with exact fractions, and intensity is the signed largest-|value| pole, likewise derived — neither is rated directly. The meter word is **groove**: what the skin measures is how a dancer's body answers music and a partner, practice by practice. The Scribe is an indaba: it uses this research to show each practice with its backing, name where dancers meet and where they part, and ask what would let the group reach consensus — on this floor, consensus takes the concrete form of who dances with whom, in which role, to what. The skin's stance is floor-level pluralism: ballroom, swing, salsa, tango, country and folk scenes are placed on one map in one vocabulary, with no scene's etiquette treated as the default and each practice stated in the terms of the dancers who love it.

## 2. Topic rationale

### Partnering & connection

**Close embrace** — A directional practice (lead / follow): dancing chest-to-chest in a sustained closed hold. It is on the map because the embrace is tango's and blues' core technology — connection through the torso rather than the hands — and a dancer's appetite for it, on either side of the hold, predicts half their scene choices.

**Open hold** — A directional practice (lead / follow): dancing in an open, hand-connected frame with space between the bodies. It is the complementary technology to close embrace — room for turns, shines and visual play — and dancers who thrive in one hold often merely tolerate the other.

**Embrace Distance** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “How close and continuous should torso contact be during a dance?” Close Chest-to-Chest turns two bodies into one breathing pendulum with micro-leads; Elastic Conversational breathes between close and open with the phrasing; Open Visual Frame maximizes turn room, visual play and rhythmic footwork.

**Tone & Resistance** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Should connection feel near-weightless, or carry clear, springy athletic tone?” A switchbox: two crossed independent axes, not opposites. Feather-Light Sensitivity makes the subtlest weight shift readable without fatigue; Grounded Elastic Tension stores energy in compression and stretch for crisp spins and stops. A dancer may affirm either, both, or neither — both negative is the status quo, not an error.

**Grounding & Posture** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Does movement feel best rooted down into the floor or lifted lightly through the spine?” Also a switchbox of crossed independent axes. Earthy Downward Pulse sinks into knees and floor for Afro-Latin and blues grooves; Buoyant Lifted Suspension lifts through the spine for glide, pivots and waltz momentum.

**Partnering role** — The skin's directional core, as a triad of complementary affinities: where a dancer lives. Lead steers — figures, timing, floorcraft; Follow answers — reading the lead, completing it, adding a voice inside it; Switch trades roles between or within songs.

**Role Dialogue** — How initiative is shared inside the partnership, again a complementary triad. Crisp Clear Direction gives unambiguous invitations so the follow can relax and shine; Co-Created Conversation has the lead propose openings while the follow shapes timing, styling and phrasing; Frequent Role Switching dissolves fixed roles into mutual play.

**Eye Contact & Gaze** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “How much visual engagement feels natural versus overwhelming during a song?” Sustained Warm Gaze anchors presence and trust; Intermittent Check-Ins balances connection with spatial safety; Inward Kinesthetic Focus softens or closes the eyes to deepen sensitivity to weight and music.

**Solo shine** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Breaking away from the hold to improvise on your own feet.” A single affinity: the breakaway moment — salsa's shines, swing's solo jazz — where the partnership briefly becomes two soloists showing each other what they have.

**Dancing with strangers** — A single affinity: saying yes to unknown partners. It is the social floor's engine — scenes live or die on whether strangers get danced with — and dancers divide sharply between those who find novelty delicious and those who find it costly.

**One regular partner** — A single affinity: dancing mainly with one known partner. Depth against breadth — a shared vocabulary built over years, against the floor's variety — and the regular-partner dancer is a distinct social species every scene recognizes.

**Dancing in a circle** — A single affinity: circle forms — jam circles, cyphers, folk rings — where the group holds the space and individuals enter it. It captures the communal, spectated mode that partner-only maps miss.

**Dancing alone** — A single affinity: dancing solo, unpartnered. Included because many partner dancers also dance alone (and some only tolerate partnering), and because solo movement — footwork, body movement, groove — is a skill the partnered forms borrow constantly.

### Ballroom

**Waltz** — A directional practice (lead / follow): the turning 3/4 dance that anchors the smooth/standard division. Rise, fall and rotation around the floor in closed hold — the ballroom archetype against which the division is measured.

**Viennese Waltz** — A directional practice (lead / follow): the fast original waltz, continuous rotation at roughly twice ballroom waltz tempo. It separates dancers who find speed exhilarating from those who find it a survival exercise.

**Tango** — A directional practice (lead / follow): ballroom tango — sharp, staccato, dramatic — explicitly the ballroom dance, not the Argentine one (which has its own category). The name collision is a real floor confusion the map keeps separate.

**Foxtrot** — A directional practice (lead / follow): the smooth, flowing standard dance of long gliding steps. It rewards continuity and punishes choppiness, and divides dancers by patience.

**Quickstep** — A directional practice (lead / follow): the fast, light, hopping standard dance. Athletic and joyful at tempo; a cardio referendum in evening dress.

**Slow dancing** — A directional practice (lead / follow): the unstructured sway of school dances and weddings — no syllabus, just a partner and a slow song. Included because for most humans this is the only partner dancing they ever do, and the map honours the baseline.

**Cha Cha** — A directional practice (lead / follow): the sharp, flirty Latin/rhythm dance built on the triple step. Rhythmically precise, hip-driven, and the division's crowd-pleaser.

**Rumba** — A directional practice (lead / follow): the slow, romantic Latin dance — one step per beat, all expression. It exposes dancers: there is nowhere to hide at rumba tempo.

**Samba** — A directional practice (lead / follow): the bouncy, travelling Latin dance of Brazilian carnival rhythm domesticated for the ballroom. Its bounce action is the most technique-specific in the division.

**Jive** — A directional practice (lead / follow): the fast, kicks-and-flicks Latin dance descended from swing. Energy as a technique; the last dance of the programme for a reason.

**Bolero** — A directional practice (lead / follow): the slowest, most balletic rhythm dance, rising and falling like a waltz at rumba tempo. A connoisseur's dance, rare on social floors, kept for completeness of the division.

**Mambo** — A directional practice (lead / follow): the rhythm division's driving, on-2 dance, kin to salsa. It links the ballroom category to the club category, where its relatives live.

### Swing & blues

**East Coast Swing** — A directional practice (lead / follow): the six-count gateway swing — simple basic, forgiving tempo range, taught at every wedding-adjacent studio. The entry drug of the Lindy family.

**Lindy Hop** — A directional practice (lead / follow): the original swing dance of Harlem's Savoy Ballroom — eight-count, swingouts, improvisation inside partnership. The family's centre of gravity and its historical root.

**Charleston** — A directional practice (lead / follow): the 1920s dance of kicking legs and swivelling feet, danced solo, partnered, or in lines. Lindy's elder and its perpetual guest.

**Balboa** — A directional practice (lead / follow): the close-embrace, small-footwork swing dance built for crowded floors and fast tempos. Where Lindy expands, Balboa condenses — dancers often specialize by temperament along exactly this line.

**Collegiate Shag** — A directional practice (lead / follow): the fast, bouncy six-count dance of 1930s college kids. A niche within the family, kept because its devotees are distinct and devoted.

**West Coast Swing** — A directional practice (lead / follow): the slotted, elastic, blues-and-pop swing dance — improvisational, musical, danced to contemporary music. A separate culture from the Lindy family despite the shared surname, hence its own subcategory.

**Blues Dancing** — A directional practice (lead / follow): slow, grounded, close dancing to blues music — pulse, lag and weight. It is the Lindy family's late-night sibling and fusion's parent.

### Salsa & club

**Reggaeton** — A directional practice (lead / follow), held as this category's parent topic: solo-and-partner club dancing to dembow rhythm. It anchors the club end of the category, where "partner dance" loosens into shared groove.

**Salsa** — A directional practice (lead / follow): the club Latin flagship — fast turns, spins, and shines over clave-based music. The largest social-dance scene in this category and the reference against which its neighbours are placed.

**Bachata** — A directional practice (lead / follow): the Dominican close dance, four steps and a hip, slower and more intimate than salsa, now with traditional, modern and sensual branches. Its intimacy gradient is a real floor negotiation, which is why it is rated separately from salsa.

**Merengue** — A directional practice (lead / follow): the two-step Dominican dance — the easiest partnered basic in the building, and therefore the great democratizer of Latin nights.

**Cumbia** — A directional practice (lead / follow): the Colombian-born, pan-Latin dance of sweeping turns and a swaying basic, in many regional dialects. It fills floors from Mexico City to Los Angeles and belongs on any honest map of Latin social dancing.

**Brazilian Zouk** — A directional practice (lead / follow): the flowing, head-and-torso-movement dance descended from lambada. Its elastic, wave-like connection makes it a temperament test quite unlike salsa's turns.

**Kizomba** — A directional practice (lead / follow): the Angolan close-embrace walking dance — slow, grounded, chest-close. It imports tango-like intimacy into the club category, and dancers' appetite for it is diagnostic.

### Argentine tango

**Argentine Tango** — A directional practice (lead / follow): the walking embrace itself — improvised, chest-close, built from the walk, the pause and the pivot. The category's centre; everything else here is its culture.

**Milonga** — A directional practice (lead / follow): tango's fast, cheerful sibling dance — same embrace, quicker feet, playful rhythm. (The word also names the event; the topic is the dance.) Dancers who love tango but bounce at milonga are a recognizable type.

**Tango Vals** — A directional practice (lead / follow): tango danced in 3/4 — flowing, turning, romantic. The third music of the tango night, and the one that reveals whether a tango dancer is really a waltzer in disguise.

**Dancing a full tanda** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “A tanda is a set of three or four songs danced with the same partner — tango's built-in unit of commitment. Do you stay for the whole set?” A single affinity: honouring the tanda as the unit of commitment — three or four songs, one partner, no mid-set exits.

**The cabeceo** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “The cabeceo is the nod across the room that asks for a dance and answers it — a consent ritual with centuries on it, no words and no walk of shame.” A single affinity: the nod-and-gaze invitation ritual — consent with no words and no public refusal.

**Practicas** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “The practica: tango's practice room, where steps get drilled and partners rotate without ceremony.” A single affinity: tango's practice room, where the milonga's codes relax and steps get drilled.

### Country & folk

**Two-Step** — A directional practice (lead / follow): the Texas two-step — progressive, around the floor, quick-quick-slow-slow to live country bands. The honky-tonk's engine and this category's flagship.

**Country Waltz** — A directional practice (lead / follow): waltz as the country floor dances it — simpler, earthier, to fiddles rather than strings. Same 3/4, different culture from the ballroom's waltz, and rated separately for that reason.

**Line Dancing** — A single affinity: choreographed lines, no partner, everyone facing the same way doing the same steps. The category's solo-communal form and many dancers' first ever dance.

**Square Dancing** — A single affinity: caller-led sets of eight, figures called in real time. Dancing as a team sport under verbal instruction — a cognitive and social mode unlike anything else on the map.

**Contra Dancing** — A single affinity: long lines, a caller, a live band, and a swing with every neighbour in the set. The folk scene's most deliberately welcoming institution.

**Polka** — A directional practice (lead / follow): the fast, hopping 2/4 dance that conquered two continents' dance halls in the nineteenth century and never left the folk floor. Joy at tempo, with a partner to hold on to.

**Zydeco & Cajun** — A directional practice (lead / follow): Louisiana's accordion-driven dances — two-steps and waltzes at a fais do-do. Regional, live-music-bound, and a distinct groove from Nashville country.

### The social floor

**Asking someone to dance** — A directional practice (ask / be asked): the invitation itself, rated from both sides. The floor's first negotiation — courage on one side, being chosen on the other — and the two directions are genuinely different experiences, so they are rated separately and never averaged.

**Declining a dance** — A single affinity: saying no, and one's comfort doing it. A floor where no is impossible is not a consensual floor; this topic prices the right of refusal.

**Rotating partners** — A single affinity: changing partners through a night, a class, or a song. Rotation is how scenes socialize and how classes teach; monogamous-floor dancers and rotation-lovers divide predictably.

**Sitting out & watching** — A single affinity: the chair at the edge — resting, watching, learning, choosing. Watching is a real mode of participation (the Wallflower archetype is built on it), not merely the absence of dancing.

**Dancing with beginners** — A single affinity: taking the floor with the newest dancers. Every scene's health is measurable here — whether experienced dancers treat beginners as a duty, a pleasure, or a cost.

**Dancing with experts** — A single affinity: dancing up — with partners far above one's level. Thrilling for some, terrifying for others, and the floor's main informal teaching channel.

**Teaching on the floor** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Correcting your partner mid-dance: mentorship to some, the social floor's cardinal sin to others.” A single affinity: mid-dance correction, the social floor's most contested etiquette question.

**Feedback on the Floor** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Should partners ever offer technique tips during a social dance, or save coaching strictly for class?” A switchbox of two crossed independent axes, not opposites. Zero Unsolicited Teaching holds that unasked corrections kill joy; Welcoming Real-Time Tweaks holds that quick friendly calibration keeps both bodies safe and happy. Either, both, or neither may be affirmed; both negative is the status quo.

**Practice and drilling** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “How do you get better — drilling moves, dancing with people, or improvising?” A line of three routes to improvement. Drilling improves by repetition, alone or in class; Social improves by dancing with people; Improvisation improves by playing rather than repeating figures.

**Floorcraft** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Navigating a crowded floor without collisions — the lead's oldest duty.” A single affinity: the duty and pleasure of navigating — traditionally the lead's charge, in truth both partners' craft.

**Dips** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “A dip is trust made visible: offered, asked, or never without a yes.” A directional practice (dip / be dipped): trust made visible, and the two directions — supporting and surrendering weight — are different experiences rated separately.

**Lifts & aerials** — A directional practice (lift / be lifted): leaving the floor entirely, from Lindy's aerials to showcase lifts. The highest-trust, highest-risk practice on the map, mostly at home in jam circles, performances and competitions rather than the social floor.

**Tradition vs. Fusion** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Should dancers honor each style's distinct cultural technique and music, or freely blend movements across genres?” A switchbox of crossed independent axes. Rooted Cultural Lineage respects the Black, Latin and folk histories behind each dance; Borderless Hybrid Fusion lets living dances evolve by blending. Either, both, or neither may be affirmed.

**Floorcraft form** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “When you dance, is the floor a circulating ronda, a jam circle, or formal lanes?” A line of three floor geometries. Ronda (circulating) travels with the line of dance; Jam circle takes turns in the middle; Lanes (formal) keeps set patterns and lanes.

### Music & movement

**Musicality** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Dancing the phrasing, not just the beat — breaks, swells, and silence included.” A single affinity: dancing the phrasing — the quality dancers name first when describing a great partner, and the hardest to teach.

**Preferred tempo** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “The tempo where your dancing lives.” A line of three homes. Slow & spacious gives room to breathe, extend and mean it; Mid-tempo is the comfortable cruising speed; Fast & driving is speed, sweat and no time to think.

**Rhythmic Anchor** — Which layer of a song drives a dancer's movement, as a complement triad-plus-one. Strict On-Beat Pocket locks onto the pulse for hypnotic groove; Syncopated Off-Beat Play plays between the beats for wit; Lyrical Melody & Vocals breathes with the singer or strings; Dramatic Hits & Breaks catches stops and accents as shared exclamation points.

**Improvising** — A single affinity: making the dance up in real time rather than executing memorized patterns. The improvisational core that swing, tango and blues prize and syllabus ballroom rations.

**Styling & Embellishment** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “How much personal footwork, arm styling, and body isolation belong inside partnered movement?” A switchbox of crossed independent axes. Clean Minimalist Lines keeps focus on the shared centre; Expressive Solo Flair injects personality and individual voice inside the duet. Either, both, or neither may be affirmed.

**Playfulness & Humor** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Should a dance lean toward absorbed intimacy or playful teasing and rhythmic jokes?” A switchbox of crossed independent axes. Earnest Romantic Focus turns three minutes into a private world; Cheeky Mischief & Sabotage keeps dancing joyful and ego-free with musical jokes and harmless hijacks. Either, both, or neither may be affirmed.

**Dancing to live music** — A single affinity: dancing to a band rather than a DJ. Live music changes the contract — the band watches the floor back — and scenes divide between live-music devotees and DJ-floor regulars.

**Choreographed routines** — A single affinity: learning and performing set choreography. The routine is the stage mode of partner dance — precision and rehearsal against the social floor's improvisation.

**Performing** — A single affinity: dancing for an audience. Performance re-aims everything — connection outward, to the room — and dancers who love the social floor do not always love the stage.

**Competing** — A single affinity: dancing to be judged. Competition is a whole parallel economy (the Competition Dancer archetype lives there) with its own virtues — clarity, drilling, legibility — that the social floor both admires and resents.

### Settings & scenes

**The weekly social** — A single affinity: the regular local dance night — the scene's heartbeat and most dancers' actual dancing life, against which fancier settings are measured.

**Balls & formals** — A single affinity: black-tie balls and formal dances — dressing up, big floors, occasion energy. The ballroom world's ceremonial mode.

**Clubs** — A single affinity: late-night club dancing — salsa clubs, zouk nights — louder, later, closer than the social-hall world.

**Weddings** — A single affinity: dancing at weddings — the general public's partner-dance habitat, and the Wedding Guest archetype's whole world.

**Dance weekends & exchanges** — A single affinity: festivals, exchanges and camps — travel, immersion, hundreds of new partners in three days. The scene's pilgrimage mode.

**Group classes** — A single affinity: learning in a rotating group class — the standard on-ramp and a social institution in itself.

**Private lessons** — A single affinity: one-on-one tuition — expensive, fast, and exposing; dancers divide on whether it is the royal road or an indulgence.

**Dancing outdoors** — A single affinity: dancing outside — bandstands, plazas, summer tango in the park. Weather, concrete and passers-by included.

**Dancing at home** — A single affinity: dancing in the kitchen and the living room — the private, unobserved mode where much real practice and much real joy quietly happen.

**Costume and dress** — Recovered question (skin's `question` field is empty; taken verbatim from the topic's hovertip issue): “Does what you wear matter — is the costume part of the dance, irrelevant, or a badge of the scene?” A line of three answers. Part of the dance makes the outfit part of the dance — shoes, gown, line; Irrelevant holds that dance is the body and clothes do not matter; Identity makes dress a badge of scene belonging.

## 3. Reasons and statistics backing each position

### 3.1 Partnering & connection

#### Close embrace
- **Close embrace (lead / follow)** — Reasons: chest-to-chest connection transmits the lead through the torso before the feet move, so the follow feels intention rather than instruction; dancers who love it say the embrace is the dance — everything else is walking while held. On the follow side, it offers the deepest listening state in partner dance; on the lead side, the subtlest steering. Statistic: No reliable statistic found. What would move a holder: a partner whose open-frame dancing gives the same intimacy and precision, or an embrace that stays a cage rather than becoming a conversation.

#### Open hold
- **Open hold (lead / follow)** — Reasons: space between the bodies is room to move — turns, shines, arm play and eye contact all live in the open hold; dancers who love it say they can see their partner, and being seen is half the pleasure. Leads prize the geometry for patterns; follows prize the visibility for styling and self-expression. Statistic: No reliable statistic found. What would move a holder: discovering that close connection can carry the same freedom, or an open hold that keeps collapsing into disconnection.

#### Embrace Distance
- **Close Chest-to-Chest** — Reasons: heart-to-heart contact makes two bodies one breathing pendulum, and micro-leads through the chest arrive earlier and clearer than any hand signal; holders say this is where tango and blues stop being steps and become trust. Statistic: No reliable statistic found. What would move a holder: a partner for whom the closeness is endurance rather than pleasure — the embrace only works as an invitation.
- **Elastic Conversational** — Reasons: breathing between close and open lets the connection follow the music — closing for the lyrical phrases, opening for the rhythmic ones; holders call it conversation rather than posture, a distance that is itself expressive. Statistic: No reliable statistic found. What would move a holder: finding that the transitions cost more connection than they buy expression.
- **Open Visual Frame** — Reasons: a spacious frame maximizes turn room, footwork visibility and playful eye contact, and keeps the dance athletic and legible; holders say they dance with their partner, not against their sternum. Statistic: No reliable statistic found. What would move a holder: an open frame that keeps losing the thread at slow tempos, where closeness would have carried it.

#### Tone & Resistance
- **Feather-Light Sensitivity** — Reasons: minimal pressure makes the subtlest weight shift readable, so the dance can be led and followed at a whisper; holders add that lightness is kindness to shoulders — an evening of feather connection leaves no fatigue. Statistic: No reliable statistic found. What would move a holder: fast, crowded floors where a whisper cannot be heard and dances keep dissolving.
- **Grounded Elastic Tension** — Reasons: compression and stretch store kinetic energy the partnership can spend on crisp spins, whips and dynamic stops; holders say a springy frame feels alive — the connection pushes back, and the push-back is information. Statistic: No reliable statistic found. What would move a holder: tension that keeps arriving as force — a partner who mistakes elastic for strong.

#### Grounding & Posture
- **Earthy Downward Pulse** — Reasons: sinking into the knees and floor locks the hips into the groove — Afro-Latin and blues movement is generated from the ground up; holders say the pulse is where the music enters the body. Statistic: No reliable statistic found. What would move a holder: dances (waltz, foxtrot) where the downward pulse visibly fights the music's lift.
- **Buoyant Lifted Suspension** — Reasons: a lifted spine makes glide, pivots and waltz momentum feel effortless, and the partnership floats rather than trudges; holders say lift is what makes three minutes of turning feel like flying. Statistic: No reliable statistic found. What would move a holder: a lifted posture that keeps reading as stiffness to grounded partners.

#### Partnering role
- **Lead** — Reasons: the lead holds the map — figures, timing, floorcraft, the safety of both bodies — and holders say steering well is a craft of generosity: the dance is designed, in real time, for the follow's pleasure; the responsibility itself is the satisfaction. Statistic: No reliable statistic found. What would move a holder: following enough to discover the other craft's depth — many leads are converted by one great lead dancing with them.
- **Follow** — Reasons: following is active artistry — reading intention, completing it, and adding a voice inside it, all a half-beat behind the music and ahead of the next figure; holders reject the passenger caricature: the follow decides how every led movement actually happens. Statistic: No reliable statistic found. What would move a holder: leading enough to feel the floor from the steering side — or a lead who treats following as obedience.
- **Switch** — Reasons: trading roles doubles the dancer — every switch dancer knows both crafts' difficulties from inside, which makes them kinder partners and better dancers in each role; holders add the play of it: mid-song trades are a joke both partners are in on. Statistic: No reliable statistic found. What would move a holder: a scene or a dance where switching keeps breaking the connection's grammar faster than it enriches it.

#### Role Dialogue
- **Crisp Clear Direction** — Reasons: unambiguous invitations let the follow relax completely — no guessing, no anxiety — and shine inside a clear structure; holders say clarity is respect: the lead's job is to be legible, the follow's to be free. Statistic: No reliable statistic found. What would move a holder: follows reporting that the clarity arrives as control, leaving them nothing to say.
- **Co-Created Conversation** — Reasons: the lead proposes openings and the follow shapes timing, styling and phrasing in real time, so the dance is authored by both bodies; holders call this the difference between dictation and duet, and it is where experienced dancers say the magic lives. Statistic: No reliable statistic found. What would move a holder: co-creation collapsing into negotiation chaos with partners who need structure to relax.
- **Frequent Role Switching** — Reasons: trading lead and follow mid-song dissolves fixed roles into pure mutual play, and the surprise re-energizes both dancers; holders say it is also an ethics: nobody owns the steering by default. Statistic: No reliable statistic found. What would move a holder: partners for whom switching reads as gimmick and breaks the spell of a great single-role dance.

#### Eye Contact & Gaze
- **Sustained Warm Gaze** — Reasons: steady eye contact anchors presence and trust — the partner is a person, not a vehicle — and holders say it is what turns technique into a meeting; in close dances it is also a safety signal that both are still consenting and comfortable. Statistic: No reliable statistic found. What would move a holder: partners for whom sustained gaze is overwhelm rather than warmth — the gaze serves the partner, not the principle.
- **Intermittent Check-Ins** — Reasons: warm glances mixed with peripheral awareness balance connection with spatial safety — you cannot floorcraft staring into one pair of eyes; holders call it the natural rhythm of looking in every other human conversation. Statistic: No reliable statistic found. What would move a holder: a dance — a slow blues, a tango — where the music asks for unbroken presence and check-ins feel like absence.
- **Inward Kinesthetic Focus** — Reasons: softening or closing the eyes removes the loudest sense and deepens sensitivity to weight transfer, breath and music; holders (especially follows in close embrace) describe it as the doorway to the dance's meditative state. Statistic: No reliable statistic found. What would move a holder: crowded floors where closed eyes become a hazard to others.

#### Solo shine
- **Solo shine** — Reasons: breaking away to improvise on your own feet is where a dancer shows their own rhythm, footwork and nerve — salsa's shines and swing's solo breaks are the partnership's exclamation points; holders say the shine is also honesty: no lead to hide behind, no follow to blame. Statistic: No reliable statistic found. What would move a holder: shines that keep arriving as performance anxiety rather than play — or a scene where breaking away reads as showing off.

#### Dancing with strangers
- **Dancing with strangers** — Reasons: every regular partner was a stranger once, and scenes live on the yes given to an unknown hand; holders describe stranger dances as the floor's adventure — new vocabularies, new musicalities, the possibility of the best dance of the night coming from nowhere. Statistic: No reliable statistic found. What would move a holder: a run of stranger dances that are rough, unsafe or boundary-blind, repricing the yes.

#### One regular partner
- **One regular partner** — Reasons: a shared vocabulary built over years permits things no stranger dance can — unled figures understood, risks consented in advance, a private musical language; holders compare it to a long conversation versus small talk, and choose depth. Statistic: No reliable statistic found. What would move a holder: the partnership going stale — or discovering that variety was the missing nutrient all along.

#### Dancing in a circle
- **Dancing in a circle** — Reasons: the circle holds what the couple cannot — community witnessing, taking turns, the jam's generous spotlight where the group applauds each pair or soloist in the middle; holders say circle energy is the oldest form of social dance there is. Statistic: No reliable statistic found. What would move a holder: circles that become gauntlets — competitive, cliquish, or unsafe with aerials near watchers.

#### Dancing alone
- **Dancing alone** — Reasons: solo dancing is the root skill — groove, footwork, body movement — with no partner to carry or blame, and kitchen dancing is where many dancers honestly live; holders add that solo practice is what they bring back to the partnership. Statistic: No reliable statistic found. What would move a holder: solo dancing that stays lonely rather than free — the absence of the answering body becoming the point.

### 3.2 Ballroom

#### Waltz
- **Waltz (lead / follow)** — Reasons: rise, fall and rotation make the partnership into a single turning instrument, and holders describe a good waltz as the closest dancing comes to flight at walking pace; leads prize the travelling geometry, follows the surrender to momentum inside a secure frame. Statistic: No reliable statistic found. What would move a holder: waltzes that stay earthbound — a frame or a floor that never lets the turn become glide.

#### Viennese Waltz
- **Viennese Waltz (lead / follow)** — Reasons: continuous rotation at speed is exhilaration itself — the floor blurs, the music lifts, and the partnership either flies or falls together; holders call it the purest test of a couple's shared balance. Statistic: No reliable statistic found. What would move a holder: dizziness and crowded floors repricing the thrill as hazard.

#### Tango
- **Tango (lead / follow)** — Reasons: ballroom tango's sharpness — staccato walks, sudden heads, dramatic pauses — gives dancers a theatrical intensity no other standard dance permits; holders love playing the drama straight, all attack and stillness. Statistic: No reliable statistic found. What would move a holder: discovering Argentine tango's improvised intimacy and finding the ballroom version's choreography brittle by comparison — or the reverse.

#### Foxtrot
- **Foxtrot (lead / follow)** — Reasons: long gliding steps and unbroken continuity reward patience — a good foxtrot feels like the partnership is poured around the floor; holders prize its smoothness as the connoisseur's virtue in the standard division. Statistic: No reliable statistic found. What would move a holder: floors and tempos that keep breaking the flow the dance exists to create.

#### Quickstep
- **Quickstep (lead / follow)** — Reasons: fast, light and hopping, quickstep is joy with a heart rate — holders describe it as the standard division's grin, all bounce and daring at tempo. Statistic: No reliable statistic found. What would move a holder: joints and lungs filing their objection — quickstep love is often retired by the body, not the taste.

#### Slow dancing
- **Slow dancing (lead / follow)** — Reasons: no syllabus, no counting, no audience — just holding someone and moving to a slow song, which is most of humanity's entire experience of partner dance; holders defend it as the honest baseline: the embrace and the music were always the point. Statistic: No reliable statistic found. What would move a holder: learning a structured dance and finding the sway suddenly too little — or, in reverse, finding structure a cage.

#### Cha Cha
- **Cha Cha (lead / follow)** — Reasons: sharp rhythm, flirty play and the triple step's percussive snap make cha cha the Latin division's crowd-pleaser; holders love its cheek — a dance that winks. Statistic: No reliable statistic found. What would move a holder: cha cha that stays cute but never becomes musical — rhythm without conversation.

#### Rumba
- **Rumba (lead / follow)** — Reasons: one step per beat at slow tempo leaves nowhere to hide, and rumba dancers prize exactly that exposure — hip action, weight and feeling stretched over long beats; holders call it the romantic division's truth serum. Statistic: No reliable statistic found. What would move a holder: rumba danced as mere slowness — partners who fill the beats with waiting instead of movement.

#### Samba
- **Samba (lead / follow)** — Reasons: the bounce — samba's travelling wave through the body — is unlike anything else on the floor, and holders chase the carnival lift it gives even in ballroom form. Statistic: No reliable statistic found. What would move a holder: the bounce degrading into bobbing — technique failing the rhythm it serves.

#### Jive
- **Jive (lead / follow)** — Reasons: kicks, flicks and rock-step energy at the end of the programme — jive dancers are the ones still grinning when everyone else is spent; holders treat stamina as a style. Statistic: No reliable statistic found. What would move a holder: jive's speed crowding out its musicality, becoming athletics in costume.

#### Bolero
- **Bolero (lead / follow)** — Reasons: the slowest rhythm dance, rising and falling with balletic control, bolero is the division's meditation — holders are connoisseurs who prefer one perfect slow revolution to a night of turns. Statistic: No reliable statistic found. What would move a holder: bolero's rarity itself — a dance almost no social floor plays is hard to keep loving in practice.

#### Mambo
- **Mambo (lead / follow)** — Reasons: driving, on-2 and rhythm-first, mambo connects the ballroom to the Palladium and the salsa club — holders love its swagger and its break-forward attack. Statistic: No reliable statistic found. What would move a holder: mambo nights disappearing into generic salsa, losing the on-2 discipline that defines it.

### 3.3 Swing & blues

#### East Coast Swing
- **East Coast Swing (lead / follow)** — Reasons: a forgiving six-count basic that gets absolute beginners dancing in one lesson, to music from big band to rockabilly; holders — often teachers — prize it as the family's welcome mat. Statistic: No reliable statistic found. What would move a holder: outgrowing the basic's ceiling and migrating to Lindy — the welcome mat working as intended.

#### Lindy Hop
- **Lindy Hop (lead / follow)** — Reasons: born in Harlem's Savoy Ballroom, Lindy is improvisation inside partnership — the swingout's elastic release, breakaways, jazz steps, and a conversation with the band; holders ground the dance in its African-American vernacular tradition and its Ambassador, Frankie Manning, who carried it from the Savoy to the world. Statistic: No reliable statistic found. What would move a holder: a Lindy scene that polishes the dance into syllabus and loses the improvisation that defines it.

#### Charleston
- **Charleston (lead / follow)** — Reasons: swivelling feet and kicking legs at joyful tempos — Charleston is pure bounce, danced solo, partnered or in lines; holders love its century-old grin and its place as Lindy's living ancestor. Statistic: No reliable statistic found. What would move a holder: knees and tempos — Charleston at full speed is a young dancer's game, and holders age into slower cousins.

#### Balboa
- **Balboa (lead / follow)** — Reasons: close embrace, tiny precise footwork and fast tempos — Balboa was built for crowded Southern California floors where there was no room to swing out; holders prize the subtlety: an entire conversation in inches. Statistic: No reliable statistic found. What would move a holder: partners who need visible geometry — Balboa's pleasures are invisible to anyone not inside the embrace.

#### Collegiate Shag
- **Collegiate Shag (lead / follow)** — Reasons: six-count, bouncy and gleefully fast, shag is the Lindy family's cult favourite — holders describe a hopping, close, slightly absurd dance that feels like laughing at tempo. Statistic: No reliable statistic found. What would move a holder: the scene's smallness — shag partners are rare enough that love of it is partly a logistics problem.

#### West Coast Swing
- **West Coast Swing (lead / follow)** — Reasons: the slot, the elastic anchor and contemporary music make WCS the most improvisational of the swing family — follows get real authorship, leads play with the music's lyrics and hits; holders call it a conversation that never repeats. Statistic: No reliable statistic found. What would move a holder: WCS scenes that drift into pattern-collecting and competition styling, losing the slot's conversation.

#### Blues Dancing
- **Blues Dancing (lead / follow)** — Reasons: slow, grounded and close, blues dancing trades figures for pulse, lag and weight — holders describe it as the truth-telling dance: at blues tempo there is nothing to perform, only to feel, together. Statistic: No reliable statistic found. What would move a holder: blues floors that borrow the closeness without the musical grounding — intimacy as aesthetic rather than response.

### 3.4 Salsa & club

#### Reggaeton
- **Reggaeton (lead / follow)** — Reasons: the dembow rhythm is a physical instruction — hips answer before thought — and club dancers prize reggaeton's looseness: partnering as shared groove rather than led figures, the floor's pressure valve between structured dances. Statistic: No reliable statistic found. What would move a holder: reggaeton sets where the looseness loses the partner entirely — groove without contact.

#### Salsa
- **Salsa (lead / follow)** — Reasons: speed, turns and clave — salsa is the club floor's athletic flagship, and holders describe the high of a fast, clean, musical dance with a partner who catches every signal; leads prize the turn vocabulary, follows the spins and shines, both the band. Statistic: No reliable statistic found. What would move a holder: salsa dancing that becomes turn-pattern aerobics — leads counting combinations instead of hearing the song.

#### Bachata
- **Bachata (lead / follow)** — Reasons: four steps, a hip, and a closeness salsa rarely permits — bachata dancers prize the slower pulse and the romantic, grounded connection, from traditional Dominican footwork to modern body rolls; holders say it is the dance where beginners relax and romantics linger. Statistic: bachata music and dance were inscribed on UNESCO's Representative List of the Intangible Cultural Heritage of Humanity in 2019 (UNESCO, 2019). What would move a holder: bachata floors where the sensual branch's closeness is presumed rather than negotiated, repricing the intimacy.

#### Merengue
- **Merengue (lead / follow)** — Reasons: the simplest partnered basic in the building — two steps, endless turns — makes merengue the great democratizer: anyone can be dancing in ninety seconds; holders prize it as the song where the whole room, grandparents included, is on the floor. Statistic: merengue was inscribed on UNESCO's Representative List of the Intangible Cultural Heritage of Humanity in 2016 (UNESCO, 2016). What would move a holder: little — merengue love is rarely argued out of anyone; at most, a floor that plays it as a joke rather than a dance.

#### Cumbia
- **Cumbia (lead / follow)** — Reasons: the swaying basic and sweeping turns carry a pan-Latin identity — cumbia is the dance of family parties from Colombia to Mexico to Los Angeles; holders prize its unhurried joy and its accordion-and-brass swing. Statistic: No reliable statistic found. What would move a holder: cumbia reduced to a warm-up track at salsa nights, its own floor never quite forming.

#### Brazilian Zouk
- **Brazilian Zouk (lead / follow)** — Reasons: flowing, elastic connection with head and torso movement borrowed from lambada's lineage — zouk dancers describe a wave that travels through both bodies, the most continuous sensation in the club category; holders call it dancing inside the music's breath. Statistic: No reliable statistic found. What would move a holder: head-movement technique taught without its safety and consent scaffolding — zouk's trust requirements are real.

#### Kizomba
- **Kizomba (lead / follow)** — Reasons: an Angolan walking embrace — slow, grounded, chest-close, steps small enough for a whisper — kizomba dancers prize the meditative trance of two people walking as one to a slow pulse. Statistic: No reliable statistic found. What would move a holder: kizomba floors importing club grinding expectations into a dance whose holders define it by restraint.

### 3.5 Argentine tango

#### Argentine Tango
- **Argentine Tango (lead / follow)** — Reasons: an improvised walking embrace — no basic step, only the walk, the pause and the pivot, composed in real time between two people listening to the same orchestra; holders say tango is not danced to music but inside it, and that one good tanda justifies a year of practice. Statistic: tango was inscribed on UNESCO's Representative List of the Intangible Cultural Heritage of Humanity in 2009 (UNESCO, 2009). What would move a holder: a milonga culture so codified and status-ridden that the embrace's conversation dies under its etiquette.

#### Milonga
- **Milonga (lead / follow)** — Reasons: tango's cheerful, quicker sibling — same embrace, playful rhythm, permission to grin; holders love milonga as the milonga-night's sunlight, the dance where the purists are caught enjoying themselves. Statistic: No reliable statistic found. What would move a holder: milonga played and danced as merely fast tango, losing its bounce and wit.

#### Tango Vals
- **Tango Vals (lead / follow)** — Reasons: tango's embrace set flowing in 3/4 — turns that travel, a romantic lift inside the walk's intimacy; holders call vals the tanda where tango dancers reveal their inner waltzers. Statistic: No reliable statistic found. What would move a holder: vals tandas vanishing from milonga playlists, starved by tango-only programming.

#### Dancing a full tanda
- **Dancing a full tanda** — Reasons: the tanda is tango's unit of trust — three or four songs with one partner, long enough for the embrace to settle from negotiation into conversation; holders say leaving mid-tanda (barring discomfort) breaks a small contract the whole culture is built on, and the cortina's clean ending is what makes starting again easy. Statistic: No reliable statistic found. What would move a holder: a partner making the tanda an obligation to endure rather than a commitment to enjoy — the contract serves the dancers, not the reverse.

#### The cabeceo
- **The cabeceo** — Reasons: the nod across the room asks and answers without words, so a refusal costs nobody a public walk of shame — holders call it the most civilized consent technology on any dance floor: the invitation exists only if it is accepted, and eye contact does all the work. Statistic: No reliable statistic found. What would move a holder: milongas where the cabeceo becomes an exclusion machine — sightlines and status deciding who may even be looked at.

#### Practicas
- **Practicas** — Reasons: the practica is where tango is allowed to be unfinished — steps drilled, partners rotated without ceremony, questions asked mid-dance that the milonga forbids; holders say nobody becomes a tango dancer at milongas alone. Statistic: No reliable statistic found. What would move a holder: practicas hardening into informal milongas with the same codes, losing the laboratory.

### 3.6 Country & folk

#### Two-Step
- **Two-Step (lead / follow)** — Reasons: quick-quick-slow-slow around a hardwood floor to a live country band, a beer in the break — two-step dancers prize the honky-tonk circuit itself: travelling, turning, and a partner who gives honest weight in the swing; holders call it the working dance of Texas, learned at family weddings and perfected over decades. Statistic: No reliable statistic found. What would move a holder: live-band honky-tonks closing — two-step to a DJ is the same steps in a different, lesser country.

#### Country Waltz
- **Country Waltz (lead / follow)** — Reasons: the same 3/4 as the ballroom's waltz but earthier — fiddles, boots, a simpler turning vocabulary and a room full of neighbours; holders prize it as waltzing without the ceremony, romance at a county-fair temperature. Statistic: No reliable statistic found. What would move a holder: country floors dropping waltzes from the band's book entirely.

#### Line Dancing
- **Line Dancing** — Reasons: no partner needed, no invitation risked — everyone faces front and does the same steps, so the shy, the single and the beginner are all simply dancers; holders prize the line as the most democratic formation in social dance and a genuine workout in boots. Statistic: No reliable statistic found. What would move a holder: line sets shrinking to the same three songs at every event, novelty starving the form.

#### Square Dancing
- **Square Dancing** — Reasons: dancing as a team under a caller's real-time instructions — eight people executing figures none of them chose, laughing at the wreckage together; holders prize the cognitive play and the intergenerational room, grandparents and teenagers in the same set. Statistic: No reliable statistic found. What would move a holder: the caller pipeline thinning — squares die without callers, and holders know it.

#### Contra Dancing
- **Contra Dancing** — Reasons: long lines, a live band, a caller's walk-through, and a swing with every neighbour in the set — contra is engineered welcome: you will dance with everyone, be taught as you go, and be thanked for coming; holders (the Country & Folk archetype among them) prize exactly that institutional hospitality. Statistic: No reliable statistic found. What would move a holder: contra rooms losing the beginner-welcome — experienced dancers forming a closed inner floor.

#### Polka
- **Polka (lead / follow)** — Reasons: fast, hopping and joyous in 2/4, polka is the nineteenth century's viral dance still alive wherever accordions are; holders prize its unpretentious stamina-test glee — nobody looks dignified polkaing, which is the point. Statistic: No reliable statistic found. What would move a holder: knees, again — polka love is often outlived by the joints it spends.

#### Zydeco & Cajun
- **Zydeco & Cajun (lead / follow)** — Reasons: accordion, frottoir and a groove that sits in the hips — Louisiana's dances come with gumbo, French lyrics and a fais do-do's family sprawl; holders prize the regional rootedness: this music and these steps belong to a place and say so. Statistic: No reliable statistic found. What would move a holder: zydeco nights gentrifying into generic country bars, the Creole and Cajun roots becoming décor.

### 3.7 The social floor

#### Asking someone to dance
- **Asking someone to dance (ask / be asked)** — Reasons: on the asking side, the invitation is the floor's founding courage — every dance that ever happened began with somebody risking a no, and holders say asking well (clearly, gracefully, taking no for an answer) is a learnable generosity; on the be-asked side, being chosen is its own pleasure — the small electricity of a hand offered across the room, and for many dancers the only door in. Statistic: No reliable statistic found. What would move a holder: on the asking side, a scene whose refusals are so costly that asking stops; on the be-asked side, invitations that arrive as entitlement rather than request.

#### Declining a dance
- **Declining a dance** — Reasons: a no that costs nothing is what makes every yes mean something — holders of a high rating say the right to decline, without excuse or penalty, is the floor's consent foundation, and scenes that honour it get more dancing, not less; resting, watching and choosing are also legitimate evenings. Statistic: No reliable statistic found. What would move a holder: nothing about the principle — but its practice softens where declining is wielded as status punishment rather than self-knowledge.

#### Rotating partners
- **Rotating partners** — Reasons: rotation is how a scene becomes a community rather than a set of couples in parallel — dancing with everyone teaches adaptability no single partnership can, and class rotation is how beginners meet the room; holders call it the social contract with better music. Statistic: No reliable statistic found. What would move a holder: rotation that becomes compulsory churn — never allowed to stay for the great dance that just started.

#### Sitting out & watching
- **Sitting out & watching** — Reasons: watching is participation — dancers learn vocabulary, musicality and floorcraft from the chairs, rest their bodies, and choose their moments; holders (the Wallflower is their patron) add that the watcher is the floor's memory and its most honest audience. Statistic: No reliable statistic found. What would move a holder: sitting out that is actually exile — wanting to dance and never being asked, which is a scene's failure, not a preference.

#### Dancing with beginners
- **Dancing with beginners** — Reasons: everyone was carried through their first dances by somebody's patience, and holders describe dancing down a level as both repayment and craft — a good lead or follow can give a beginner the best dance of their month with basic steps done kindly; scenes that feed their beginners survive. Statistic: No reliable statistic found. What would move a holder: beginners who treat the dance as a free lesson with corrections demanded — generosity has a terms-of-service.

#### Dancing with experts
- **Dancing with experts** — Reasons: dancing up is the floor's masterclass — three minutes inside an expert's frame teaches what months of classes gesture at, and holders describe the lift of it: suddenly your own dancing is better than you knew; the thrill is real even when the terror is too. Statistic: No reliable statistic found. What would move a holder: experts whose dances are auditions — being used as a practice dummy or a status prop reprices the thrill.

#### Teaching on the floor
- **Teaching on the floor** — Reasons: holders are split in motive but the affinity itself is real: some dancers experience a mid-dance correction as mentorship — a partner who cares enough to help — and in practice-room cultures (practicas, classes) it is the whole point; even its defenders usually confine it to invitation, safety, or the practice floor rather than the social song. Statistic: No reliable statistic found. What would move a holder: one correction too many delivered as condescension — most dancers' tolerance ends exactly at being lectured by a stranger mid-song.

#### Feedback on the Floor
- **Zero Unsolicited Teaching** — Reasons: unasked-for corrections kill joy and convert a party into an awkward lesson — the corrected partner did not enroll, cannot leave politely, and will remember the embarrassment longer than the tip; holders say the social floor's first rule is that your partner is your guest, not your student. Statistic: No reliable statistic found. What would move a holder: a partner explicitly asking — which changes the act from unsolicited to requested, a different topic entirely.
- **Welcoming Real-Time Tweaks** — Reasons: quick, friendly calibration when something hurts or feels unsafe keeps both bodies safe and happy, and silence about a crushing grip helps nobody; holders distinguish coaching (forbidden) from comfort signals (kindness), and welcome the second. Statistic: No reliable statistic found. What would move a holder: tweaks that keep expanding from safety into syllabus — the exception swallowing the rule.

#### Practice and drilling
- **Drilling** — Reasons: repetition builds the body that improvisation later spends — figures drilled to automatic free the mind for music and partner; holders point to every craft's scales-and-etudes stage and ask why dance would be exempt. Statistic: No reliable statistic found. What would move a holder: drilling that never cashes out socially — technique hoarded, floorcraft and musicality starved.
- **Social** — Reasons: you get better at dancing with people by dancing with people — connection, floorcraft, adaptation and musicality exist only in the partnered wild, not the studio mirror; holders note that the floor's best dancers are usually its most frequent, not its most drilled. Statistic: No reliable statistic found. What would move a holder: a plateau that only targeted drilling breaks — most social learners eventually meet one.
- **Improvisation** — Reasons: playing, not repeating, is where a personal style forms — musical jokes, rhythmic risks, happy accidents systematized into voice; holders say figures are vocabulary, but improvisation is speech. Statistic: No reliable statistic found. What would move a holder: improvisation collapsing into the same five habits — play that has quietly become drilling without noticing.

#### Floorcraft
- **Floorcraft** — Reasons: navigating a crowded floor without collisions is the lead's oldest duty and both partners' craft — holders describe great floorcraft as invisible generosity: the follow never knows how many collisions they were steered around; it is also the difference between a crowded floor feeling like traffic or like weather you sail in. Statistic: No reliable statistic found. What would move a holder: nothing moves the duty — but empty floors and jam circles change its form, from navigation to space-sharing.

#### Dips
- **Dips (dip / be dipped)** — Reasons: a dip is trust made visible — on the dipping side, offering a supported fall and returning your partner safely is a small act of competence and care; on the be-dipped side, surrendering your weight and balance to another body, and being caught, is a pleasure dancers describe as flying in place; both sides agree the yes must be real — asked, signalled, or established. Statistic: No reliable statistic found. What would move a holder: a dip sprung without consent or beyond the dipper's strength — one dropped partner reprices every future dip.

#### Lifts & aerials
- **Lifts & aerials (lift / be lifted)** — Reasons: leaving the floor entirely is partner dance's extreme sport — Lindy's aerials were born in jam-circle competition, and holders describe the lift's split-second of shared flight as addictive on both sides: the lifter's power and timing, the flyer's trust and line; both sides confine it to jam circles, showcases and consenting practice, not crowded social floors. Statistic: No reliable statistic found. What would move a holder: an injury — aerials are the one topic where a single accident rewrites a whole scene's rules.

#### Tradition vs. Fusion
- **Rooted Cultural Lineage** — Reasons: each dance carries a people's history — Lindy's Black Harlem roots, tango's port-city immigrants, salsa's Afro-Cuban religion and rhythm — and honouring the lineage (music, technique, names, credit) is how the dances stay deep instead of becoming aerobics in costume; holders say respect is also practical: the roots are where the technique's reasons live. Statistic: No reliable statistic found. What would move a holder: lineage talk used as gatekeeping to freeze living dances and exclude the newcomers every tradition needs.
- **Borderless Hybrid Fusion** — Reasons: living dances have always evolved by mixing — tango, salsa and Lindy are themselves fusions — and curious movers blending vocabularies to new music are continuing the tradition, not betraying it; holders add that fusion floors are where switch dancers, mixed playlists and new styles (fusion blues, zouk-lindy hybrids) are actually born. Statistic: No reliable statistic found. What would move a holder: fusion that erases sources — blends that take the steps and drop the music, the credit and the culture that made them.

#### Floorcraft form
- **Ronda (circulating)** — Reasons: the circulating line of dance is a collective agreement — everyone travels counter-clockwise, nobody parks in the flow — and holders describe a good ronda as a river the whole room swims in, tango's and ballroom's shared miracle of order without a referee. Statistic: No reliable statistic found. What would move a holder: rondas that become processions of status, where the inner lane is a caste.
- **Jam circle** — Reasons: the circle takes turns — one couple or soloist in the middle, the room clapping the rhythm — and holders prize its generosity: the floor itself becomes applause, and stealing the spotlight politely is the game (Lindy birthdays, soul-train lines). Statistic: No reliable statistic found. What would move a holder: jam circles that turn mean — spotlights hogged, beginners frozen out of the middle.
- **Lanes (formal)** — Reasons: set lanes and patterns make large floors legible — West Coast's slot is a lane of two, ballroom's line of dance a lane of many — and holders say formality is a kindness to strangers: everyone knows where everyone else will be. Statistic: No reliable statistic found. What would move a holder: lanes enforced as pedantry where the music and crowd wanted a circle or a ronda.

### 3.8 Music & movement

#### Musicality
- **Musicality** — Reasons: dancing the phrasing — breaks, swells, silence — is what partners describe afterwards: not the figures but the moment the dance hit the hit; holders say musicality is the difference between dancing near music and dancing the song, and it is the skill every other topic on this map is ultimately for. Statistic: No reliable statistic found. What would move a holder: nothing in principle — but musicality pursued as showing off (styling over connection) loses the partner it was meant to impress.

#### Preferred tempo
- **Slow & spacious** — Reasons: slow tempos give room to breathe, extend and mean it — every weight shift is legible, every pause is eloquent; holders of slow dancing say speed is easy to hide behind and slowness is not. Statistic: No reliable statistic found. What would move a holder: slow sets that curdle into dragging — spacious needs pulse, not just patience.
- **Mid-tempo** — Reasons: the cruising speed is where most music, most partners and most stamina intersect — holders call it the tempo of the long evening, sustainable joy rather than peak experience. Statistic: No reliable statistic found. What would move a holder: a DJ who lives at mid-tempo all night — the cruising speed becomes a ceiling.
- **Fast & driving** — Reasons: speed, sweat and no time to think — fast tempos force the body past self-consciousness into flow, and holders describe the grin of survival at 200 beats per minute; Charleston, quickstep, shag and milonga all live here. Statistic: No reliable statistic found. What would move a holder: the body filing its veto — fast love is the most commonly retired by age and injury.

#### Rhythmic Anchor
- **Strict On-Beat Pocket** — Reasons: locking onto the pulse creates hypnotic groove and effortless synchronization — two bodies agreeing on the beat need agree on little else; holders (contra and folk dancers especially) call the pocket the floor's common language. Statistic: No reliable statistic found. What would move a holder: pocket-keeping that becomes metronomic — the beat held but the song missed.
- **Syncopated Off-Beat Play** — Reasons: playing between the beats adds crisp surprise and rhythmic wit — the and-of-two is where swing lives and where salsa's breaks hide; holders say off-beat play is how a dancer signs their name inside the partnership. Statistic: No reliable statistic found. What would move a holder: syncopation that desynchronizes the partnership — wit the partner cannot hear is a solo.
- **Lyrical Melody & Vocals** — Reasons: breathing with the singer or the strings turns steps into storytelling — holders anchor to the line that carries the feeling, and describe dances remembered by lyric, not by figure. Statistic: No reliable statistic found. What would move a holder: instrumental music with no line to follow — the anchor must migrate to rhythm or admit the dance is thinner.
- **Dramatic Hits & Breaks** — Reasons: catching sudden stops and accents makes electric shared exclamation points — the partnership that hits a break together feels telepathic; holders organize whole dances around the next hit. Statistic: No reliable statistic found. What would move a holder: hit-chasing that shreds the phrases between hits into mere waiting.

#### Improvising
- **Improvising** — Reasons: making it up in real time is the living core of swing, tango, blues and salsa alike — the dance that has never happened before, for a partner who will never hear this song quite this way again; holders oppose improvisation not to technique but to recitation. Statistic: No reliable statistic found. What would move a holder: improvisation exposed as habit — the same "spontaneous" sequence every song (see §3.7, Practice and drilling).

#### Styling & Embellishment
- **Clean Minimalist Lines** — Reasons: understated clarity keeps the focus on the shared centre and never disrupts the partner's balance; holders say minimalism is confidence — the dance is good enough without decoration, and the partner's experience outranks the audience's. Statistic: No reliable statistic found. What would move a holder: minimalism reading as absence — a partner who experiences the clean line as no one home.
- **Expressive Solo Flair** — Reasons: syncopations, arm styling and isolations inject personality and celebrate the individual voice inside the duet — follows especially claim styling as authorship, the place the dance is theirs; holders say a duet of two voices beats a monologue with support. Statistic: No reliable statistic found. What would move a holder: flair that breaks the connection's physics — styling that costs the partnership its balance or timing.

#### Playfulness & Humor
- **Earnest Romantic Focus** — Reasons: deep absorption turns three minutes on a crowded floor into a quiet private world — holders of earnest dances describe a quality of attention that is itself the compliment; romance here is a mode of seriousness, not a relationship claim. Statistic: No reliable statistic found. What would move a holder: earnestness misread across the embrace — intensity one partner experiences as pressure rather than presence.
- **Cheeky Mischief & Sabotage** — Reasons: playful musical jokes, harmless hijacks and rhythmic teasing keep social dancing joyful and ego-free — Lindy's steal dances and birthday jams are built on sanctioned mischief; holders say a partnership that can laugh mid-song can survive anything the floor does. Statistic: No reliable statistic found. What would move a holder: mischief at a partner's expense — sabotage that humiliates instead of delights ends the game.

#### Dancing to live music
- **Dancing to live music** — Reasons: a band watches the floor back — tempos breathe, solos stretch when the room is hot, and the dancers' energy feeds the musicians in a loop no recording closes; holders (folk and tango dancers above all) organize their dancing lives around live nights and call DJ floors the substitute, not the standard. Statistic: No reliable statistic found. What would move a holder: live bands that ignore the floor — tempos for the musicians' vanity, sets with no dancer's arc.

#### Choreographed routines
- **Choreographed routines** — Reasons: a routine perfects what improvisation cannot — unison, lines, lifts rehearsed to safety, a dance that can be filmed and kept; holders describe the deep pleasure of a thing made exactly, together, over weeks. Statistic: No reliable statistic found. What would move a holder: routine culture eating the social floor — dancers who can perform a number but cannot improvise a song.

#### Performing
- **Performing** — Reasons: dancing for an audience re-aims the connection outward — projection, clarity, generosity to the back row — and holders describe performance as the dance's public face: recruitment, celebration, proof the art is alive. Statistic: No reliable statistic found. What would move a holder: performance habits leaking into social dances — playing to an imaginary audience while the actual partner waits.

#### Competing
- **Competing** — Reasons: judging creates a standard the social floor refuses to supply — competitors prize the clarity: drilled technique, legible musicality, results that cannot be argued with; holders add that competition circuits (Jack-and-Jill formats especially) are also beloved social worlds in themselves. Statistic: No reliable statistic found. What would move a holder: judging criteria visibly deforming the dance — floorcraft and partnership sacrificed to tricks the rubric rewards.

### 3.9 Settings & scenes

#### The weekly social
- **The weekly social** — Reasons: the regular local night is where dancing actually lives — same room, same crowd, skills and friendships compounding weekly; holders call it the scene's heartbeat and measure every fancier setting against whether it feels like home this much. Statistic: No reliable statistic found. What would move a holder: a weekly social going stale or cliquish — the heartbeat becoming a closed shop.

#### Balls & formals
- **Balls & formals** — Reasons: dressing up is part of the pleasure — gowns, black tie, a big sprung floor and an orchestra make the dancing feel like an occasion, and holders say formality flatters everyone: posture improves with the clothes. Statistic: No reliable statistic found. What would move a holder: balls priced and coded as exclusion — occasion curdling into gatekeeping.

#### Clubs
- **Clubs** — Reasons: louder, later, closer — the club floor runs on different fuel: darkness, bass, and a crowd that came to sweat; salsa and zouk club regulars describe the late set, when the tourists leave, as the real night's beginning. Statistic: No reliable statistic found. What would move a holder: club conditions — smoke-machine haze, spilled drinks, harassment tolerated by the venue — repricing the late set.

#### Weddings
- **Weddings** — Reasons: weddings are where the general public dances — grandmothers, toddlers, one slow song with someone you love — and holders (the Wedding Guest above all) prize the wedding floor's total lack of hierarchy: nobody is good, everybody dances. Statistic: No reliable statistic found. What would move a holder: very little — wedding love is usually a temperament, not an argument; at most, DJ sets with no slow songs at all.

#### Dance weekends & exchanges
- **Dance weekends & exchanges** — Reasons: immersion — three days, hundreds of partners, classes all day and dances until four — compresses a year of growth into a weekend and builds the cross-city friendships that make a scene a world; holders describe exchanges as pilgrimage and reunion at once. Statistic: No reliable statistic found. What would move a holder: exchange culture's costs — travel, money, sleep debt — outrunning the joy as life changes.

#### Group classes
- **Group classes** — Reasons: the rotating group class is the standard on-ramp — cheap, social, and self-levelling, with rotation supplying the variety no beginner could arrange alone; holders who teach call the group class the scene's true front door. Statistic: No reliable statistic found. What would move a holder: classes that rotate without teaching — social hours wearing a lesson's clothes.

#### Private lessons
- **Private lessons** — Reasons: one expert eye on your body for an hour finds what years of group classes missed — holders describe privates as expensive, exposing and absurdly efficient, the royal road for a specific problem. Statistic: No reliable statistic found. What would move a holder: private-lesson dependency — dancing that improves in the studio and not on the floor.

#### Dancing outdoors
- **Dancing outdoors** — Reasons: bandstands, plazas and summer park milongas add sky, breeze and passers-by who stop, watch and sometimes join — holders prize outdoor dancing as the art's public square, recruitment and pleasure in one. Statistic: No reliable statistic found. What would move a holder: concrete destroying shoes and knees faster than the joy accumulates — surface is destiny outdoors.

#### Dancing at home
- **Dancing at home** — Reasons: the kitchen dance is unobserved, unjudged and always open — practice, joy and marriage maintenance in one room; holders note that more total dancing may happen at home than in every venue on this list combined, and none of it needs permission. Statistic: No reliable statistic found. What would move a holder: home dancing that replaces the floor entirely — the social animal needs its herd eventually.

#### Costume and dress
- **Part of the dance** — Reasons: the outfit is equipment and expression at once — the right shoes change what your feet can do, the gown's line completes the waltz's picture, and dressing is the ritual that starts the evening; holders say you dance differently in clothes chosen for dancing. Statistic: No reliable statistic found. What would move a holder: costume costs becoming a barrier that keeps the floor poorer and emptier.
- **Irrelevant** — Reasons: dance is the body — connection, rhythm and weight do not inspect your clothes, and holders point to great dancers in jeans at every social as the standing proof; dress codes mostly police belonging, not dancing. Statistic: No reliable statistic found. What would move a holder: one practical exception at a time — shoes first — until the position becomes "mostly irrelevant, except the equipment."
- **Identity** — Reasons: what you wear announces your scene — vintage for Lindy, black for tango, boots for country — and holders treat dress as a flag of belonging and respect for the room's culture; the badge also helps strangers find their people. Statistic: No reliable statistic found. What would move a holder: badges hardening into uniforms that exclude the curious newcomer the scene needs.

## 4. Archetype research

All 10 samples in the skin have kind "archetype". Archetype ids covered in this section, in skin order: the-waltz-romantic, the-lindy-hopper, the-tango-purist, the-salsa-regular, the-switch, the-competition-dancer, the-wedding-guest, the-wallflower, the-lyrical-fusionist, the-country-folk-dancer. Ratings in the skin are affinities per practice — per direction (lead/follow, ask/be asked, dip/be dipped, lift/be lifted) where a practice is directional, per pole on multi-pole topics — and the receptivity and intensity discussed below follow the contract in §1, described in words, not re-rated here.

### The Waltz Romantic — `the-waltz-romantic.svg`
Lives for the turning dances and a partner who stays the whole song. Why: it holds the §3 waltz-family reasons — rotation as flight, buoyant lifted posture, slow-and-spacious tempo, earnest romantic focus (§3, Waltz; Viennese Waltz; Country Waltz; Grounding & Posture; Playfulness & Humor). Receptive to: foxtrot's glide and tango vals (tango's own waltz), and to one regular partner, since its dances are built for staying (§3, One regular partner). Closed to: fast driving tempos and cheeky sabotage, which break the sustained spell its dancing exists to create (§3, Preferred tempo). Emblem: images/emblems/the-waltz-romantic.svg

### Savoy-Tradition Lindy Hopper & Swing Improviser — `the-lindy-hopper.svg`
Grounds partner dance in the African-American vernacular jazz tradition of the Savoy Ballroom: rhythmic pulse, call-and-response musicality, playful improvisation and the jam circle's energy — Frankie Manning, the dance's Ambassador, carried it from the Savoy to the world, and Stearns' *Jazz Dance* tells its story. Why: it holds the §3 Lindy reasons — improvisation inside partnership, rooted cultural lineage, jam-circle floorcraft, live music, off-beat play (§3, Lindy Hop; Tradition vs. Fusion; Floorcraft form; Rhythmic Anchor). Receptive to: Charleston and Balboa as family, blues as the late-night sibling, and aerials in their proper jam-circle home (§3, Lifts & aerials). Closed to: syllabus-polished swing with the improvisation removed, and fusion that drops the lineage's credit (§3, Tradition vs. Fusion). Emblem: images/emblems/the-lindy-hopper.svg

### Milonguero / Argentine Tango Close-Embrace Traditionalist — `the-tango-purist.svg`
Upholds the traditional Buenos Aires milonga codes: cabeceo invitation, tandas, strict counter-clockwise ronda, and intimate chest-to-chest walking to the Golden Age orchestras — Thompson's *Tango: The Art History of Love* and Denniston's *The Meaning of Tango* codify the estilo milonguero; tango was inscribed by UNESCO in 2009. Why: it holds the §3 tango reasons in their strictest form — close chest-to-chest embrace, full tandas, cabeceo, ronda, feather-light-to-grounded walking connection, inward kinesthetic focus (§3, Argentine Tango; Dancing a full tanda; The cabeceo; Embrace Distance; Eye Contact & Gaze). Receptive to: milonga and vals as the night's other musics, practicas as the laboratory, and partners who honour the codes (§3, Practicas). Closed to: teaching on the floor at a milonga, mid-tanda exits, and fusion vocabulary in the ronda (§3, Teaching on the floor). Emblem: images/emblems/the-tango-purist.svg

### The Salsa Regular — `the-salsa-regular.svg`
Every Friday, same club, everybody knows the rotation. Why: it holds the §3 club-Latin reasons — salsa's speed and turns, bachata's breather, merengue's room-wide welcome, the club setting itself, asking and rotating as the night's social machinery (§3, Salsa; Bachata; Merengue; Clubs; Rotating partners). Receptive to: strangers (the rotation demands them), shines, and live bands when the club books them (§3, Dancing with strangers; Solo shine). Closed to: sitting out — the Regular's night is measured in dances, not chairs (§3, Sitting out & watching). Emblem: images/emblems/the-salsa-regular.svg

### The Switch — `the-switch.svg`
Leads, follows, and trades mid-song just to watch your face. Why: it holds the §3 switch reasons in full — the Switch partnering pole, frequent role switching in Role Dialogue, co-created conversation, and the playfulness positions that make trading a game (§3, Partnering role; Role Dialogue; Playfulness & Humor). Receptive to: fusion floors and any scene where switching is legible (WCS, Lindy, blues), and to partners game for the trade (§3, Tradition vs. Fusion). Closed to: crisp single-role direction as an evening's whole grammar, and scenes where switching is read as disruption (§3, Role Dialogue). Emblem: images/emblems/the-switch.svg

### The Competition Dancer — `the-competition-dancer.svg`
Drills, mirrors, and a shelf that needs dusting. Why: it holds the §3 competition reasons — competing and choreographed routines as goods in themselves, drilling as the route to improvement, private lessons, clean minimalist lines for legibility, costume as part of the dance (§3, Competing; Choreographed routines; Practice and drilling; Styling & Embellishment; Costume and dress). Receptive to: performing, balls and formals, and any partner who drills (§3, Performing; Balls & formals). Closed to: pure social improvisation as a standard — its whole craft is making the dance repeatable and judgeable (§3, Improvising). Emblem: images/emblems/the-competition-dancer.svg

### The Wedding Guest — `the-wedding-guest.svg`
Dances exactly four times a year, all of them at receptions. Why: it holds the §3 slow-dancing and weddings reasons — no syllabus, no hierarchy, one slow song with someone you love — plus sitting out happily and dancing with whoever asks (§3, Slow dancing; Weddings; Dancing with strangers). Receptive to: merengue and line dancing, the forms a DJ can teach a room in ninety seconds (§3, Merengue; Line Dancing). Closed to: everything with a technique barrier — practicas, drilling, competition — not from dislike but because its dancing life has no room or need for them (§3, Practice and drilling). Emblem: images/emblems/the-wedding-guest.svg

### The Wallflower — `the-wallflower.svg`
Knows every song by heart. Has been asked twice, and remembers both. Why: it holds the §3 sitting-out reasons in their purest form — watching as participation, musicality absorbed from the chairs, inward kinesthetic focus, and the be-asked side of Asking someone to dance rated as the door it waits at (§3, Sitting out & watching; Musicality; Asking someone to dance). Receptive to: the cabeceo's mercy (invitation without public refusal), dancing with beginners' kindness in reverse — an expert who asks gently (§3, The cabeceo; Dancing with experts). Closed to: asking — the ask side is its cliff edge — and to jam circles, where the middle is the last place it wants to be (§3, Floorcraft form). Emblem: images/emblems/the-wallflower.svg

### The Lyrical Fusionist — `the-lyrical-fusionist.svg`
Drawn to elastic connection, sweeping body movement, and blending vocabularies to express modern, emotional tracks. Why: it holds the §3 fusion reasons — borderless hybrid fusion, elastic conversational embrace, lyrical melody anchoring, expressive solo flair, co-created conversation (§3, Tradition vs. Fusion; Embrace Distance; Rhythmic Anchor; Role Dialogue). Receptive to: zouk and blues (its parent vocabularies), switch partners, and live or lyrical DJ sets (§3, Brazilian Zouk; Blues Dancing). Closed to: rooted-lineage purism applied as prohibition, and crisp syllabus direction that leaves the melody unexpressed (§3, Tradition vs. Fusion). Emblem: images/emblems/the-lyrical-fusionist.svg

### The Country & Folk Floor Dancer — `the-country-folk-dancer.svg`
Lives for live fiddles, callers and a hardwood floor full of neighbours — Texas Two-Step, Country Waltz, contra lines, square sets, polka and Louisiana Zydeco — valuing honest weight in a swing, rotating through every partner in the hall, welcoming first-timers in the walk-through, and keeping the counter-clockwise line of dance flowing. Why: it holds the §3 country-and-folk reasons wholesale — live music, rotation, beginner-welcome, ronda floorcraft, on-beat pocket, grounded downward pulse (§3, Two-Step; Contra Dancing; Dancing to live music; Rotating partners; Dancing with beginners; Grounding & Posture). Receptive to: line dancing and weddings (its cousins), group classes with callers, and dancing outdoors at the fair (§3, Line Dancing; Dancing outdoors). Closed to: club scenes and competition formats, whose hours, volumes and hierarchies invert its values (§3, Clubs; Competing). Emblem: images/emblems/the-country-folk-dancer.svg

## 5. Gap analysis

**Positions with no archetype.** The map's practices are wider than its 10 archetypes. No archetype primarily embodies: the ballroom syllabus dancer as such (the Waltz Romantic covers the turning dances romantically, the Competition Dancer covers judged ballroom, but the social ballroom regular has no persona); the West Coast Swing slot dancer; the zouk/kizomba close-club dancer (the Fusionist neighbours them); the practica-first learner; or the DJ-floor salsa dancer distinct from the club regular's band nights. The folk, tango, Lindy and wedding worlds are well covered; the ballroom and WCS worlds are the gaps.

**Thin topics.** Dance is an action skin of mostly single-position practices: 71 of its 86 topics carry one position (a single affinity, or a directional practice rated lead/follow, ask/be asked, dip/be dipped, lift/be lifted), so the indaba can list backing for each (done in §3) but disagreement appears between practices and profiles, not between poles inside a topic. Six switchbox topics (Tone & Resistance, Grounding & Posture, Feedback on the Floor, Tradition vs. Fusion, Styling & Embellishment, Playfulness & Humor) cross two independent axes: poles are not opposites, both-negative is the status quo, and §3 treats them so. Directional topics are covered in the directions the JSON gives; direction is never averaged.

**Skin-JSON problems (reported, not fixed).** (1) Twenty topics have an empty `question` field but a hovertip issue — §2 includes the recovered question for each (see §5.1), taken verbatim from that topic's hovertip issue; the skin JSON itself is unchanged. (2) A further 51 topics have an empty `question` field and **no hovertip at all** (including Close embrace, Open hold, all twelve ballroom dances, and most dances and settings) — there is no issue text to recover for them; §2's rationale for those topics rests on the topic name, its category and subcategory, and its give/receive labels only. This is the skin's largest documentation gap. (3) Category ids skip xdac03 (Ballroom is xdac02, Swing & blues is xdac04) — reported as found; ids are permanent and are not renumbered here. (4) Several recovered "issues" are descriptions rather than questions (Solo shine, The cabeceo, Practicas, Floorcraft, Musicality, Preferred tempo, Dips) — they are quoted verbatim in §5.1 as instructed by the recovery rule, not rewritten into questions. (5) The Scribe template's `rules` and `rigor` fields are empty in the JSON (genre: story) — the Scribe's behaviour for this skin is carried by its opening line alone; reported, not fixed.

**Deliberately left out of this research.** Dance pedagogy beyond the floor's own learning topics; dance history beyond what archetype `about` texts and §3 reasons actually use; competitive rules and syllabi (DanceSport figures, WDSF regulations), which the skin rates as affinity, not as technique; and any statistic not listed in §6 — where §3 could not ground a number in a source the author could name with confidence, it says so rather than estimating.

### 5.1 Recovered question fields

The skin's `question` field is empty for the twenty topics below. Each recovered question is the topic's own hovertip `issue` text, verbatim — recovered, not invented — and is also quoted in §2 at the topic.

- **Embrace Distance** (xda0074) — “How close and continuous should torso contact be during a dance?”
- **Tone & Resistance** (xda0075) — “Should connection feel near-weightless, or carry clear, springy athletic tone?”
- **Grounding & Posture** (xda0077) — “Does movement feel best rooted down into the floor or lifted lightly through the spine?”
- **Eye Contact & Gaze** (xda0078) — “How much visual engagement feels natural versus overwhelming during a song?”
- **Solo shine** (xda0004) — “Breaking away from the hold to improvise on your own feet.”
- **Dancing a full tanda** (xda0038) — “A tanda is a set of three or four songs danced with the same partner — tango's built-in unit of commitment. Do you stay for the whole set?”
- **The cabeceo** (xda0039) — “The cabeceo is the nod across the room that asks for a dance and answers it — a consent ritual with centuries on it, no words and no walk of shame.”
- **Practicas** (xda0040) — “The practica: tango's practice room, where steps get drilled and partners rotate without ceremony.”
- **Teaching on the floor** (xda0053) — “Correcting your partner mid-dance: mentorship to some, the social floor's cardinal sin to others.”
- **Feedback on the Floor** (xda0082) — “Should partners ever offer technique tips during a social dance, or save coaching strictly for class?”
- **Practice and drilling** (xda0086) — “How do you get better — drilling moves, dancing with people, or improvising?”
- **Floorcraft** (xda0054) — “Navigating a crowded floor without collisions — the lead's oldest duty.”
- **Dips** (xda0055) — “A dip is trust made visible: offered, asked, or never without a yes.”
- **Tradition vs. Fusion** (xda0083) — “Should dancers honor each style's distinct cultural technique and music, or freely blend movements across genres?”
- **Floorcraft form** (xda0084) — “When you dance, is the floor a circulating ronda, a jam circle, or formal lanes?”
- **Musicality** (xda0058) — “Dancing the phrasing, not just the beat — breaks, swells, and silence included.”
- **Preferred tempo** (xda0061) — “The tempo where your dancing lives.”
- **Styling & Embellishment** (xda0080) — “How much personal footwork, arm styling, and body isolation belong inside partnered movement?”
- **Playfulness & Humor** (xda0081) — “Should a dance lean toward absorbed intimacy or playful teasing and rhythmic jokes?”
- **Costume and dress** (xda0085) — “Does what you wear matter — is the costume part of the dance, irrelevant, or a badge of the scene?”

## 6. Sources

Statistics used in §3 (name + year + where to find it):
- UNESCO (2009) — ich.unesco.org, Representative List of the Intangible Cultural Heritage of Humanity — tango inscribed in 2009.
- UNESCO (2016) — ich.unesco.org, Representative List — merengue (Dominican Republic) inscribed in 2016.
- UNESCO (2019) — ich.unesco.org, Representative List — bachata music and dance (Dominican Republic) inscribed in 2019.

Grounding for reasons (traditions and texts drawn on, not statistics): the skin's own category descriptions, hovertip texts and archetype `about` texts; Robert Farris Thompson, *Tango: The Art History of Love* (2005), and Christine Denniston, *The Meaning of Tango* (2007), as cited in the tango archetype; Marshall and Jean Stearns, *Jazz Dance* (1968), and the Frankie Manning tradition as cited in the Lindy archetype; and the living etiquette traditions of the milonga (cabeceo, tanda, ronda), the contra hall (caller-led welcome and neighbour swings), and the Lindy jam circle, as stated in the skin's own topic texts. No other sources were used; no source above is cited for a statistic it did not supply.
