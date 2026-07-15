# Avatar AI RPG — Postwar World Bible

Unofficial, non-commercial fan-made worldbuilding framework for an AI-driven text RPG inspired by *Avatar: The Last Airbender*.

## Canon boundary

- Included: the complete animated series through the defeat of Fire Lord Ozai and Zuko's coronation.
- Excluded: *The Legend of Korra*, all later-era lore, and all post-series comic plots.
- Divergence point: immediately after the animated finale.
- Campaign start: six years after the finale, when the youngest central cast members are adults.
- The six postwar years in this repository are an original, game-specific bridge period, not official canon.

## Intended use

This repository is a modular knowledge base for retrieval-augmented generation, prompt assembly, NPC simulation, quest generation, relationship mechanics, and persistent world state.

## Content principles

- Canon facts are separated from game-original extrapolation.
- Characters remain autonomous and may refuse, disagree, leave, betray, forgive, recover, marry, or form families.
- Romance requires adult participants, mutual consent, gradual trust, and compatible circumstances.
- Sexual content is represented through relationship consequences and optional fade-to-black narration, not graphic detail.
- Corruption is a psychological trajectory, not a mind-control switch.
- No character becomes evil merely because the player requests it.

## Repository map

- `SYSTEM_PROMPT.md` — core narrator and simulation instructions
- `lore/` — history, chronology, metaphysics, culture, technology, politics
- `nations/` — nation-level reference files
- `locations/` — major locations and travel hooks
- `characters/` — individual NPC profiles
- `bending/` — bending laws and disciplines
- `gameplay/` — relationships, family, corruption, reputation, combat, travel
- `factions/` — political and social organizations
- `quests/` — quest-generation frameworks
- `prompts/` — reusable runtime prompts
- `schemas/` — templates for new content

## Recommended runtime loading

Load `SYSTEM_PROMPT.md`, `lore/canon_boundary.md`, `lore/world_state.md`, the current location file, nearby faction files, the active player sheet, and only the NPC profiles relevant to the current scene.

## Legal note

This project is not affiliated with or endorsed by the rights holders. It contains original summaries and game-design material rather than scripts, episode transcripts, or verbatim dialogue.
