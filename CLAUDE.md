# Five Kingdoms — Campaign Notes

## What this repo is

This is the GM's notebook for a **Daggerheart** tabletop RPG campaign called **Five Kingdoms**. It's a high fantasy setting. The user is the **Game Master** running the campaign for a group of players.

## How to help

When the user asks for help here, common tasks include:

- **Writing or expanding lore** — fleshing out history, factions, religions, cultures
- **Creating NPCs** — building characters with motivations, secrets, stat hooks
- **Writing session recaps** — turning raw notes into clean session summaries
- **Tracking quests** — updating quest status, adding clues or plot threads
- **Worldbuilding questions** — brainstorming how pieces of the world fit together
- **Prepping encounters** — descriptions, adversary tactics, environmental details

## Finding things (read this before reading lore)

The lore is ~45k words and growing. Don't read directories wholesale — navigate:

1. **`world/canon.md`** is the spine: every load-bearing fact on one screen, with links to the file that owns each detail. Read it first for any writing task, and check new material against it instead of re-reading the full lore.
2. **Directory READMEs are indexes** — `world/`, `world/factions/`, `characters/npcs/`, and `locations/` each have a README with one-line summaries per file. Pick files from the index; open only what the task touches.
3. **File headers are skimmable** — every lore file opens with a bold field block (`**Role:**`, `**Status:**`, `**See also:**`…). Reading the first ~10 lines is usually enough to decide whether you need the rest.
4. **`PLAN.md`** tracks build-out state (what's done, what's stubbed, open GM decisions). Check it before starting new worldbuilding so you extend rather than duplicate.
5. Current campaign state lives in `quests/active/` plus the latest session recap — don't re-read the whole `sessions/` log.

## Keeping the indexes honest

These aids only work if they stay current. In the same commit as the change:

- **New or renamed file** → add/update its row in the directory README index
- **New canon or a change to canon** (history, cosmology, magic, a secret, a name) → update `world/canon.md`
- **Major build-out** → tick or amend the relevant `PLAN.md` entry
- New session → update quest files and NPC `**Status:**` lines it affects

## Conventions

- One file per subject (NPC, location, quest, session)
- Templates live at `_template.md` in each directory — use them as starting points
- Sessions are numbered and dated: `sessions/001-session-name.md`
- NPCs link to their first appearance location and any relevant quests
- Active quests live in `quests/active/`, completed in `quests/completed/`

## Tone & style

- Prose is evocative but concise — this is a GM reference, not a novel
- Secrets and hidden info go in a `## GM Notes` section at the bottom of any file
- Player-safe summaries (no spoilers) can go in `handouts/`

## Daggerheart specifics

- Daggerheart uses **Hope** and **Fear** as core GM/player economy mechanics
- The GM plays **adversaries** and controls **Fear tokens**
- Relevant mechanical info (adversary tiers, damage, moves) belongs in NPC/encounter files
