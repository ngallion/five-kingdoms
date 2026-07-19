# Worldbuilding Plan — Five Kingdoms

A working plan for building out the campaign world. Organized as: (1) where the repo stands today, (2) discovery — decisions only the GM can make, (3) a phased build-out with concrete tasks, ordered so the campaign is playable as early as possible.

---

## 1. State of the Repo

**What's strong already:**

- **The premise** (`world/overview.md`) — five kingdoms, five aspects of humanity, each starved of the others. Clear central tension and themes.
- **The deep lore is canon** (`world/history.md`, `world/anchors-and-engines.md`) — the Sundering (inverted Anchor Working), Amaranth the unmade sixth kingdom, the Hearts as extraction engines, and the anchor destroy-vs-re-tune mechanic that structures every kingdom arc.
- **The villain** (`characters/npcs/the-king.md`) — Korrven is fully layered: motivation, methods, the poisoned offer to each kingdom, the exile from Forgeholm, Herrek's splice, the Architect bloodline, and why uniting the kingdoms (not violence) is what kills him.
- **The cosmology** (`world/vael-the-unmade.md`) — Vael gives the setting a metaphysical spine, explains Korrven's power, and now carries the "curated truth" lever for the endgame.
- **The first faction** (`world/factions/the-wayfair.md`) — the solstice festival-caravan: cross-kingdom infrastructure, the Session 1 hook, and living proof that re-tuning works.
- **Kingdom sketches** (`world/kingdoms/*.md`) — each kingdom has a character, a "what it looks like now," and a "what it needs." Forgeholm additionally has its GM-notes spine (Guild, Mother Engine, sealed tribunal, opening hook).
- **Templates** — every directory has a solid `_template.md`.

**What's stubbed or missing:**

| Area | File(s) | Status |
|------|---------|--------|
| Geography | `world/geography.md` | DONE — wheel layout, per-kingdom terrain, border wilds, roads, travel times; player map in `handouts/` |
| Magic system | `world/overview.md` § Magic | Open question |
| Factions | `world/factions/` | Wayfair + the Second Stamp (Forgeholm resistance) done; still need the king's movement and the Agoran exiles/resistance |
| NPCs | `characters/npcs/` | Korrven, Halda Vorn, Ilsabet Krane, Wrena Calder have files. Wayfair key members (Sera, Ondrel, Brindle) exist inline only; the Gleaner is named but unstatted |
| Locations | `locations/` | Kaldrum done; the other four capitals still needed |
| Quests | `quests/` | No quest files; `active/` and `completed/` dirs don't exist yet |
| PCs | `characters/pcs/` | Template only |
| Sessions | `sessions/` | None yet (expected — campaign hasn't started) |
| Handouts | `handouts/` | README only |
| README | `README.md` | "Fill in the five kingdoms" placeholder |
| Kingdom key figures | all five kingdom files | "Add notable NPCs here" placeholders |
| Agoran lore pass | `world/kingdoms/agoran.md` | Untouched by the canon waves — no mention of the Fall (209 AS), the King's Heart, or links to Korrven/anchors |

---

## 2. Discovery — GM Decisions Needed

These are questions the existing files explicitly raise (mostly in GM Notes) plus gaps the build-out can't proceed without. Nothing in Phase 1+ should contradict the answers, so settle these first — a working session or two of brainstorming.

### A. The deep lore (shapes everything else)

1. **The Sundering.** What event drove the five kingdoms apart? Was it a war, a plague, a betrayal, a slow drift — or was it Vael's earliest work? (`overview.md` GM Notes asks: is Korrven's rise a symptom of the isolation, or its cause?)
2. **The sixth aspect.** `overview.md` floats a lost or suppressed sixth aspect. Does it exist? (Candidates that fit the theme: Faith/Spirit, Memory/Tradition, Love/Compassion.) If yes, it's a massive mid-campaign reveal and should be seeded from session 1.
3. **Magic.** ANSWERED — see `world/magic.md`: all magic is **aspect-work** (strandcraft), once an everyday braided craft, now withered into five narrow warped traditions (one per kingdom, each with a hole shaped like what its Heart drinks). Braiding strands is how unity manifests — a light Hope mechanic at the table — and the hidden truth is that **all braiding works through Amara**: the sixth strand is the glue, Splendor/healing is her ownerless surviving magic, and every party braid quietly feeds her return. Loose fictional map of Daggerheart's nine domains onto the strands; no mechanical changes.
4. **Korrven's exile.** ANSWERED — exiled from **Forgeholm**, 195 AS: his father, Wright Herrek of the Mother Engine, was condemned in a sealed tribunal for tampering and the whole line exiled with him. The Guild thought the splice failed; it succeeded — it's why the Mother Engine is the master tap. Korrven believes his father was punished for trying to make the Hearts *better*. Makes the *Forgeholm* arc his homecoming. Deepest layer: the family descends from **the Architect** — the lattice answers Korrven's blood because his ancestor corrupted it. See `history.md`, `the-king.md`, `forgeholm.md`.
5. **Vael's endgame.** Does Vael have an agenda Korrven hasn't noticed? Can Korrven be saved if the bond is severed? (Raised in `vael-the-unmade.md`.) Decide whether the campaign's final choice is *kill the king* vs. *free the man*.

### B. The world's shape

6. **The map.** ANSWERED — see `world/geography.md`: the continent is a wheel — Forgeholm north (Ironspine mountains), Veritas east (high plateau), Sophara south (river country), Luminar west (the only coast), Agoran northwest (plains, shortest border with Forgeholm) — ringing the Hollow March, with dead spoke-roads inward and the Girdle rim road connecting the capitals. Player map in `handouts/`.
7. **Timescale.** How long ago were the kingdoms founded? How many generations of isolation? How recently did Agoran fall? (Suggestion: Agoran fell recently enough that exiles and living memory exist — 5–15 years.)
8. **Who lives here.** Which Daggerheart ancestries exist, and how do they map onto the kingdoms? Are Korrven's "misfits and monsters" a distinct population?
9. **Religion & the divine.** ANSWERED — see `world/religion.md`: six gods (the Concord of Six), one per aspect, once worshipped only in pairs; each kingdom now keeps a single warped cult of its own god. The gods are real, silent since the Sundering, and sealed inside the anchors — the Hearts burn each kingdom's aspect *through* its god. The sixth god, **Amara** (Love), was unmade with Amaranth; the Wayfair unknowingly keeps her liturgy. Folk tales in every kingdom remember Vael as "the Hollow One." Korrven's endgame reads as self-apotheosis — a man making himself the sixth god.

### C. The campaign itself

10. **The party.** Who are the PCs — ancestries, classes, home kingdoms, and above all their *wounds*? Korrven attacks through what people lack, so each PC needs a defined lack he can offer to fill. Collect this in session zero and file under `characters/pcs/`.
11. **Starting point.** Which kingdom (or borderland) does the campaign open in, and what's the inciting incident? The obvious candidate given the stakes: somewhere in or near **Forgeholm**, with the king's agents already at work.
12. **Campaign shape.** Roughly map the arc to Daggerheart tiers — e.g. Tier 1: discover the threat (Forgeholm arc), Tier 2: rally Sophara/Veritas/Luminar, Tier 3: strike into Agoran / sever the bond, Tier 4: Korrven. Decide if the party must visit all five kingdoms.

---

## 3. Build-Out Phases & Tasks

Ordered by play priority: the world only needs to be one arc deep before session 1, but the *foundations* (history, geography, magic) must be consistent from the start.

### Phase 0 — Repo hygiene (quick, do anytime)

- [ ] Create `quests/active/` and `quests/completed/` directories (add `.gitkeep` or a README so git tracks them)
- [ ] Fill in the "Five Kingdoms" summary table in `README.md` (one line per kingdom — content already exists in `overview.md`)
- [ ] Add Korrven to `agoran.md` Key Figures (the file asks for this) and cross-link `the-king.md` from `forgeholm.md`

### Phase 1 — Foundations (write once, everything depends on it)

- [x] **`world/history.md`** — DONE: the Anchor Working / Resonance Engine hybrid canon. Sixth kingdom (Amaranth, aspect: Love) unmade at the keystone; the Hearts extract each kingdom's aspect and feed Vael. See also new file `world/anchors-and-engines.md` (per-kingdom anchor states, re-tuning mechanics, endgame).
- [x] **`world/geography.md`** — DONE: the wheel-shaped continent (five kingdoms ringing the Hollow March), terrain/climate per kingdom (Forgeholm = the Ironspine, Luminar = the Glassreach coast, Veritas = the Tablelands, Sophara = the Meander country, Agoran = the Granary), five named border wilds, the Concord Roads (dead spokes + the Girdle), and travel times. Capital names coined there (Kaldrum, Meridian, the Stoa, Prismere, Commonhold) — rename freely before play. Player map: `handouts/map-of-the-five-kingdoms.svg`.
- [x] **`world/magic.md`** — DONE: strandcraft & the Braid — magic as aspect-work, the five warped kingdom traditions (Brightwork, Exact Art, Runework, Considered Art, Hearthbinding), divine magic through the Silence, the braid-is-Amara secret, Splendor as the ownerless sixth strand, and the loose Daggerheart domain map + Hope-based braid mechanic. `overview.md` Magic section updated to link it.
- [x] **`world/religion.md`** — DONE: the Concord of Six (Ora, Theora, Ferrun, Sophar, Tavan + the erased Amara), one god per aspect/kingdom, each cult warped by isolation to mirror its Heart's extraction; the Silence of the Gods, the Guest customs, Vael as "the Hollow One" in folk tales, and the gods-in-the-anchors GM truth.
- [x] **Resolve the `overview.md` GM Notes questions** in place — DONE: symptom-not-cause, sixth aspect = Love/Amaranth, original event = the inverted Anchor Working.

### Phase 2 — Kingdoms in depth (prioritized by campaign order)

For **each** kingdom, the deliverables are: a capital/major city file in `locations/`, a ruler or power-structure writeup, 2–4 Key Figures as NPC files, at least one faction file, and a completed GM Notes section answering "what role in the arc, what does healing look like."

Priority order:

1. [x] **Forgeholm** — DONE. Capital: [Kaldrum](locations/kaldrum.md) (depth-is-status forge-city, the hum, the Deep Archive, the Cinderfield fairgrounds). Power structure: the Bench of Masters / marks-as-citizenship / the Unmarked ([forgeholm.md](world/kingdoms/forgeholm.md)). Infiltration method: **both** an emissary *and* a too-good contract — [Ilsabet Krane](characters/npcs/ilsabet-krane.md) and the Agoran Compact. Resistance: [the Second Stamp](world/factions/the-second-stamp.md). Key figures: [Halda Vorn](characters/npcs/halda-vorn.md), Krane, [Wrena Calder](characters/npcs/wrena-calder.md). GM Notes completed: arc role, three intervention levers, what healing looks like.
2. [ ] **Sophara** — *the party's likely first ally.* GM Notes ask: what push moves them to act? Needs: the great schools, a philosopher NPC who is the exception (wants to act), and the internal debate faction-vs-faction.
3. [ ] **Agoran** — *the villain's seat; needed early for texture even if visited late.* Needs: the capital under Korrven, the enforcer apparatus, the dissenter network, and **the exile community** (living outside Agoran — great early-game allies and lore sources).
4. [ ] **Luminar** — needs: the endless-festival capital, an artist NPC whose work the king wants, what "art that harms" looks like in play.
5. [ ] **Veritas** — needs: the silent libraries, a hoarded discovery that matters to the plot (something about Vael in those unreadably old texts — `vael-the-unmade.md` already establishes Veritas found the references), a scholar NPC who knows too much and tells no one.

### Phase 3 — The campaign spine (villains, factions, quests)

- [ ] **Korrven's lieutenants** — the party can't fight a Tier 4 boss for three arcs. Create 3–5 tiered adversary NPCs (Tier 1–3), each embodying his method: a recruiter who offers belonging, ~~an emissary in Forgeholm~~ (DONE: **[Ilsabet Krane](characters/npcs/ilsabet-krane.md)**, Tier 2, statted), an enforcer commander in Agoran. Each gets an NPC file with Daggerheart stats.
- [ ] **Faction files** (`world/factions/`): the king's movement (it needs a name — his followers don't call themselves evil), the Agoran resistance/exiles, and the Forgeholm resistance. ~~At least one cross-kingdom faction that predates the isolation~~ — DONE: **[the Wayfair](world/factions/the-wayfair.md)**, the nomadic festival-caravan (unknowing heirs of Amaranth; their Loosening is the re-tuning mechanic in miniature, and they anchor the Session 1 hook in Forgeholm).
- [ ] **Main quest file** (`quests/active/`) — the campaign arc: stop the fall of Forgeholm → rally the kingdoms → liberate Agoran → sever/defeat Korrven. Use the Progress checklist for arc milestones.
- [ ] **Per-kingdom quest files** — one "healing quest" per kingdom (what the party actually does to reconnect it), written as they become imminent, not all up front.
- [ ] **Korrven's stats** — fill the Daggerheart Stats block in `the-king.md` (can wait until Tier 3–4, but the *signature move* — stronger when the party is divided — should be designed early since it interacts with party dynamics all campaign).
- [ ] **Vael mechanics** — how does Vael "work on the party" at the table? (Its GM Notes say it isolates them from each other.) Consider a light mechanic tied to Fear tokens or party separation.

### Phase 4 — Session 1 readiness

- [ ] **PC files** — one per player from session zero, with the "wound" Korrven could exploit noted in GM Notes (discovery #10)
- [ ] **Starting location file** — the town/city where it all begins, fully detailed (people, mood, secrets)
- [ ] **Opening quest** — the Tier 1 hook that leads the party to discover the king's agents
- [ ] **First handouts** — a player-safe world primer (the five kingdoms as common folk understand them), a map if one exists, and any in-world document for the opening hook
- [ ] **Session zero notes** — file as `sessions/000-session-zero.md`

### Phase 5 — Ongoing (conventions, not tasks)

- After each session: recap file, update quest progress, update NPC statuses, log loose threads
- New NPCs/locations get files when they recur, not when improvised once
- Foreshadow ahead of need: the sixth aspect (if real), Vael's folk-memory, and Korrven's exile story should each be seeded 2+ arcs before their reveal — track seeded clues in the main quest file

---

## Suggested first moves

1. Answer discovery section **A** (deep lore) — everything hangs on the Sundering, magic, and Korrven's origin.
2. Sketch the map (discovery #6) and write `world/history.md` + `world/geography.md` (Phase 1).
3. Build **Forgeholm** to full depth (Phase 2.1) — it's the next domino and the likely opening act.
