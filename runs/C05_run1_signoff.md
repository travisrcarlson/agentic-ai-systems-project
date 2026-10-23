# Sign-off sheet: C05, run 1

Case: Leased fields beside a forest belt in a de-occupied village  
Area ID: UKR-SHA-5526  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=FURTHER_NTS; B=TECHNICAL_SURVEY
- By part: A=FURTHER_NTS; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend a split. Part B has targetable indirect evidence: imagery shows old fighting positions, trenches and craters, and firsthand residents report soldiers dug in along the forest belt. Recommend targeted technical survey there; no direct evidence supports clearance. For Part A, the general troop-presence record and administrator's second-hand claim are weighed against firsthand testimony that troops did not enter the fields and one safe-use season. The national criteria require at least three years of safe use and two firsthand sources to confirm safe use, so cancellation is not supported; further non-technical survey is appropriate to resolve the remaining uncertainty and seek additional reliable information.

General guidance on the situation:

> Until the authority has resolved the hazard, keep people and animals away from the forest belt and any suspected locations. Do not touch, move or try to destroy any suspected item. Report concerns to the authorities; mark a location only if this can be done without going closer.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The 2023 record lists the area as suspected because troops were present in the village in 2022; no items, accidents or positions in the area were recorded. | yes |
| E2 | "These fields must be mined; the soldiers were everywhere around the village." He was not in the village during the occupation and repeats what residents told him. | yes |
| E3 | "I harvested wheat on the open fields in 2025 with my own machinery. Nothing happened. I kept away from the forest belt." | yes |
| E4 | Drone imagery shows old fighting positions and trenches along the forest belt, and several craters in the strip along its edge; no items were visible in the imagery. | yes |
| E5 | Two women who stayed in the village during the occupation said that soldiers dug in along the forest belt but did not go onto the open fields, which were in view of the village. | yes |
| E6 | The team walked the field tracks and saw no items, signs or fencing. It did not enter the forest belt. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | all | 6 | - | The settlement-list record gives only unassessed past troop presence, which is indirect evidence; the absence of entries is not proof that EO was absent. |
| E2 | indirect | all | 7 | - | This is a second-hand, unsubstantiated report rather than a firsthand observation, and only suggests possible EO. |
| E3 | absence | A | 4 | - | The leaseholder gives firsthand evidence of one season of safe use on A, but this falls short of the national three-year cancellation criterion. |
| E4 | indirect | B | 2 | - | Survey-team imagery shows physical indicators and craters, classified as indirect under the national rule because no items or fragments are shown. |
| E5 | indirect | B | 4 | - | The firsthand accounts suggest military activity along the forest belt, but do not confirm EO presence; their statement that troops did not enter A is relevant negative testimony but does not establish the required safe-use period. |
| E6 | absence | A, B | 2 | - | The team directly observed no items, signs or fencing on the field tracks and only the edge of B; it provides no evidence about the unentered forest interior. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R6 | all | pass | Every part is decided once. |
| R7 | all | pass | Every evidence-log item is in the register. |
| - | A | pass | Further non-technical survey is always open to the reviewer. |
| R4 | B | pass | Evidence to target in part B: E1, E2, E4, E5. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: evidence, reliability, hazard_areas, land_use, cancellation, technical_survey, further_survey, all_reasonable_effort, outcomes, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation to clear the whole area is evidence to assess, not a decision; the file contains no direct evidence defining a confirmed hazardous area.
  - The survey did not enter the forest interior, and the open fields have only one recorded season of safe use; the national cancellation criteria are not met.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
