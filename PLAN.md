# Worldbuilding Plan — Five Kingdoms

A working plan for building out the campaign world. Organized as: (1) where the repo stands today, (2) discovery — decisions only the GM can make, (3) a phased build-out with concrete tasks, ordered so the campaign is playable as early as possible.

---

## 1. State of the Repo

**What's strong already:**

- **The premise** (`world/overview.md`) — five kingdoms, five aspects of humanity, each starved of the others. Clear central tension and themes.
- **The villain** (`characters/npcs/the-king.md`) — Korrven is fully sketched: motivation, methods, his poisoned offer to each kingdom, why uniting the kingdoms (not violence) is what kills him.
- **The cosmology** (`world/vael-the-unmade.md`) — Vael gives the setting a metaphysical spine and explains Korrven's power.
- **Kingdom sketches** (`world/kingdoms/*.md`) — each kingdom has a character, a "what it looks like now," and a "what it needs."
- **Templates** — every directory has a solid `_template.md`.

**What's stubbed or missing:**

| Area | File(s) | Status |
|------|---------|--------|
| History & timeline | `world/history.md` | Empty template |
| Geography | `world/geography.md` | Empty template |
| Magic system | `world/overview.md` § Magic | Open question |
| Factions | `world/factions/` | No factions written |
| NPCs | `characters/npcs/` | Only Korrven exists |
| Locations | `locations/` | None — not even capitals |
| Quests | `quests/` | No quest files; `active/` and `completed/` dirs don't exist yet |
| PCs | `characters/pcs/` | Template only |
| Sessions | `sessions/` | None yet (expected — campaign hasn't started) |
| Handouts | `handouts/` | README only |
| README | `README.md` | "Fill in the five kingdoms" placeholder |
| Kingdom key figures | all five kingdom files | "Add notable NPCs here" placeholders |

---

## 2. Discovery — GM Decisions Needed

These are questions the existing files explicitly raise (mostly in GM Notes) plus gaps the build-out can't proceed without. Nothing in Phase 1+ should contradict the answers, so settle these first — a working session or two of brainstorming.

### A. The deep lore (shapes everything else)

1. **The Sundering.** What event drove the five kingdoms apart? Was it a war, a plague, a betrayal, a slow drift — or was it Vael's earliest work? (`overview.md` GM Notes asks: is Korrven's rise a symptom of the isolation, or its cause?)
2. **The sixth aspect.** `overview.md` floats a lost or suppressed sixth aspect. Does it exist? (Candidates that fit the theme: Faith/Spirit, Memory/Tradition, Love/Compassion.) If yes, it's a massive mid-campaign reveal and should be seeded from session 1.
3. **Magic.** How does it work, and is it tied to the five aspects? A natural option: magic flows from the aspects themselves, so each kingdom's magic has withered or warped in isolation — and party members channeling multiple aspects together is mechanically and thematically how "unity" manifests. Decide before writing any spellcaster NPC.
4. **Korrven's exile.** From which kingdom, and was it just, unjust, or complicated? (`the-king.md` GM Notes: if unjust, the party must reckon with that; if just, he must.) Strong candidate: exiled from Agoran itself — it makes his conquest of it a homecoming.
5. **Vael's endgame.** Does Vael have an agenda Korrven hasn't noticed? Can Korrven be saved if the bond is severed? (Raised in `vael-the-unmade.md`.) Decide whether the campaign's final choice is *kill the king* vs. *free the man*.

### B. The world's shape

6. **The map.** Relative positions of the five kingdoms, what lies between them (the Dangerous Wilds prompt in `geography.md`), where the old trade routes ran, and where the campaign starts. Even a rough sketch unblocks everything in Phase 1.
7. **Timescale.** How long ago were the kingdoms founded? How many generations of isolation? How recently did Agoran fall? (Suggestion: Agoran fell recently enough that exiles and living memory exist — 5–15 years.)
8. **Who lives here.** Which Daggerheart ancestries exist, and how do they map onto the kingdoms? Are Korrven's "misfits and monsters" a distinct population?
9. **Religion & the divine.** Are there gods? Do folk traditions remember Vael (fairy tales about "the Hollow One" etc.)? This feeds handouts and foreshadowing.

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
- [ ] **`world/geography.md`** — the map in prose: each kingdom's terrain and climate (Forgeholm = mountains/industry, Luminar = ?, etc.), the wilds between them, the dead trade roads, travel times. Optionally commission/sketch an actual map for `handouts/`.
- [ ] **`world/magic.md`** (new file) — the magic system per discovery #3; update the Magic section of `overview.md` to link it.
- [ ] **`world/religion.md`** (new file, optional but recommended) — faiths, folk memory of Vael, what each kingdom worships now (Luminar worships novelty, Veritas truth, etc. — isolation warps faith too).
- [x] **Resolve the `overview.md` GM Notes questions** in place — DONE: symptom-not-cause, sixth aspect = Love/Amaranth, original event = the inverted Anchor Working.

### Phase 2 — Kingdoms in depth (prioritized by campaign order)

For **each** kingdom, the deliverables are: a capital/major city file in `locations/`, a ruler or power-structure writeup, 2–4 Key Figures as NPC files, at least one faction file, and a completed GM Notes section answering "what role in the arc, what does healing look like."

Priority order:

1. [ ] **Forgeholm** — *first, it's where the campaign likely opens.* Its GM Notes already ask: what's the power structure, is there a resistance, how can the party intervene? Needs: the capital forge-city, the ruling engineer class, the king's infiltration method (an emissary? a too-good contract?), a resistance faction, and the human cost of the machines (who are "the operated"?).
2. [ ] **Sophara** — *the party's likely first ally.* GM Notes ask: what push moves them to act? Needs: the great schools, a philosopher NPC who is the exception (wants to act), and the internal debate faction-vs-faction.
3. [ ] **Agoran** — *the villain's seat; needed early for texture even if visited late.* Needs: the capital under Korrven, the enforcer apparatus, the dissenter network, and **the exile community** (living outside Agoran — great early-game allies and lore sources).
4. [ ] **Luminar** — needs: the endless-festival capital, an artist NPC whose work the king wants, what "art that harms" looks like in play.
5. [ ] **Veritas** — needs: the silent libraries, a hoarded discovery that matters to the plot (something about Vael in those unreadably old texts — `vael-the-unmade.md` already establishes Veritas found the references), a scholar NPC who knows too much and tells no one.

### Phase 3 — The campaign spine (villains, factions, quests)

- [ ] **Korrven's lieutenants** — the party can't fight a Tier 4 boss for three arcs. Create 3–5 tiered adversary NPCs (Tier 1–3), each embodying his method: a recruiter who offers belonging, an emissary in Forgeholm, an enforcer commander in Agoran. Each gets an NPC file with Daggerheart stats.
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
