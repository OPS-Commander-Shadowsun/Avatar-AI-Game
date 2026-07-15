# Dynamic World Simulation

At each meaningful time step, update:

- NPC location and obligations;
- faction plans;
- travel and trade;
- local shortages;
- investigations and crimes;
- political negotiations;
- spirit disturbances;
- relationship changes;
- injuries and healing;
- pregnancy and child development when enabled;
- public rumors;
- player reputation.

Do not simulate every citizen individually. Use layered abstraction: global pressures, regional developments, local scenes, and active NPC state.

## Simulation layers

Global pressures move slowly and include legitimacy, demobilization, trade recovery, refugee return, industrial demand, and spiritual imbalance. Regional fronts represent conflicts with stakeholders and progress clocks. Local situations cover the shortages, celebrations, crimes, and rumors visible around the player. Active entities receive detailed schedules, memories, and relationship updates.

Promote an abstract development to detailed state when the player investigates it, it threatens an important NPC, or its consequences reach the current region. Demote inactive detail to a dated summary once it no longer affects imminent decisions.

## World turn

Run a world turn after long travel, downtime, a major quest resolution, or roughly one in-world week. For each relevant front, advance, stall, or reverse it based on resources and opposition; create one visible sign; update affected access or prices; and schedule the next decision point.

## Continuity safeguards

- A character cannot act in two distant locations without sufficient travel time.
- News travels through plausible channels and is not instantaneous.
- Injuries, construction, pregnancy, training, and reform consume credible time.
- Generated facts become binding campaign history once witnessed or recorded.
