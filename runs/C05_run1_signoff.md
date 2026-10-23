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

> Recommend further non-technical survey for A: first-hand testimony says soldiers did not enter the fields and one season of mechanised farming was uneventful, but this is below the national three-year safe-use criterion and the broad, low-reliability record and hearsay have not been resolved enough to cancel or target technical survey confidently. Recommend targeted technical survey for B: imagery of former positions and craters, supported by first-hand testimony of soldiers digging in along the forest belt, is indirect evidence of possible EO, not direct confirmation that would justify clearance.

General guidance on the situation:

> Treat the forest belt and its edge as potentially hazardous pending survey. Keep people and animals away from suspect locations. Do not touch, move or try to destroy any suspected item. Mark a location only if this can be done without going closer, and report it to the authorities.

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
| E1 | indirect | all | 6 | - | An unassessed settlement-list record based on troop presence is indirect under the national criteria, not confirmation of EO. |
| E2 | indirect | all | 7 | - | The claim suggests possible contamination but is hearsay from unidentified residents, not first-hand confirmation. |
| E3 | absence | A | 4 | E1, E2 | First-hand safe use supports absence in Part A and challenges the broad area-wide suspicion, but one season is below the national three-year cancellation threshold. |
| E4 | indirect | B | 2 | - | Team-recorded imagery of former positions and craters is indirect evidence under the national criterion; no EO was visible and none is directly confirmed. |
| E5 | absence | A | 4 | E1, E2 | This mixed testimony is recorded for its part-specific negative: the two first-hand residents say soldiers did not enter A; it supports but does not prove absence there. The same row also indicates military activity in B, reflected by E4's indirect evidence. |
| E6 | absence | A, B | 2 | - | The team's negative observation supports absence only along walked tracks in A and the edge of B; the forest belt itself was not entered, so it cannot explain away E4 or establish absence throughout B. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R6 | all | pass | Every part is decided once. |
| R7 | all | pass | Every evidence-log item is in the register. |
| - | A | pass | Further non-technical survey is always open to the reviewer. |
| R4 | B | pass | Evidence to target in part B: E1, E2, E4. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation to clear the whole area is evidence for review, not a decision; the file provides no direct evidence of EO to support clearance of the whole area.
  - The survey team did not enter the forest belt, so its negative observations apply only to walked field tracks and the edge, not the interior of B.
  - The administrator's claim is second-hand; the two women provide first-hand information that soldiers dug in along B but did not enter A.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
