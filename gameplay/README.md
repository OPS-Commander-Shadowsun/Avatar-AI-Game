# Gameplay Systems

This directory contains the rules used to turn the World Bible into a persistent AI-driven text RPG.

## Core player files

- [Character Creation](character_creation.md) — adult origins, backgrounds, bending selection, nonbender options, starting equipment, and validation.
- [Core Attributes](attributes.md) — Strength, Dexterity, Intelligence, Charisma, and Stealth with a required total of 16.
- [Special Skills](skills.md) — starting allocation, training, prerequisites, and progression from 0 to 5.
- [Player Character Template](Player_Character_Template.md) — standardized persistent player sheet.

## Simulation systems

- [Combat](combat.md) — descriptive tactical resolution, injuries, defeat, bending, and consequences.
- [Travel](travel.md) — routes, time, transport, supplies, borders, encounters, and news propagation.
- [Relationships](relationships.md) — friendship, rivalry, romance, consent, commitment, separation, and NPC autonomy.
- [Family](family.md) — marriage, households, pregnancy, adoption, children, caregiving, and separation.
- [Reputation](reputation.md) — personal, local, faction, national, and underworld reputation plus rumor and memory.
- [Corruption](corruption.md) — gradual moral drift, warning signs, virtue distortion, accountability, and redemption.

## Runtime loading

Always load character creation, attributes, skills, and the active player sheet when creating or validating a player character. During play, load only the systems relevant to the current scene, while preserving their outcomes in persistent state.

## Shared numerical rules

- Core attributes range from 1 to 5.
- Every standard player, main character, and active secondary character has a core total of exactly 16.
- Bending Power is separate from the core total.
- Special skills range from 0 to 5.
- Ordinary benders possess only their native element.
- Only the Avatar may possess all four elements.
- Numerical ratings guide narration but never override consent, knowledge boundaries, terrain, injury, law, or established character autonomy.
