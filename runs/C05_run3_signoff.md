# Sign-off sheet: C05, run 3

Case: Leased fields beside a forest belt in a de-occupied village  
Area ID: UKR-SHA-5526  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=FURTHER_NTS; B=TECHNICAL_SURVEY
- By part: A=FURTHER_NTS; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend separate outcomes because the evidence and use history differ by part. For A, one season of first-hand safe machinery use does not meet the national minimum of three years or two first-hand sources; the women’s account weighs against troop presence there, while the broader troop-presence record and hearsay are weak and nonspecific. Further non-technical survey should clarify the field-specific evidence before deciding release or targeting technical work. For B, team imagery of positions, trenches and craters, together with first-hand reports of soldiers digging in along the belt, is indirect evidence sufficient to target technical survey; no direct evidence of EO was reported, and the forest was not entered.

General guidance on the situation:

> Keep people and animals away from any suspected item or hazardous location. Do not touch, move or try to destroy anything. Mark a location only if this can be done without going closer, and report it to the authorities.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The 2023 record lists the area as suspected because troops were present in the village in 2022; no items, accidents or positions in the area were recorded. | yes |
| E2 | He was not in the village during the occupation and repeats what residents told him. | yes |
| E3 | I harvested wheat on the open fields in 2025 with my own machinery. Nothing happened. I kept away from the forest belt. | yes |
| E4 | Drone imagery shows old fighting positions and trenches along the forest belt, and several craters in the strip along its edge; no items were visible in the imagery. | yes |
| E5 | Two women who stayed in the village during the occupation said that soldiers dug in along the forest belt but did not go onto the open fields, which were in view of the village. | yes |
| E6 | The team walked the field tracks and saw no items, signs or fencing. It did not enter the forest belt. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | all | 6 | - | The unassessed settlement-list record reflects troop presence, which the national criteria treat as indirect evidence; the absence of recorded finds is not a reliable negative survey. |
| E2 | indirect | all | 7 | - | This is a second-hand, unverified report without specific information locating EO, but it still suggests possible contamination. |
| E3 | absence | A | 4 | - | First-hand safe use supports absence in A, but only for one season and is below the national minimum safe-use period. |
| E4 | indirect | B | 2 | - | The observed positions and craters suggest possible contamination in B; imagery showing no visible items does not rule it out. |
| E5 | indirect | B | 4 | - | First-hand witnesses report soldiers dug in along B, supporting possible contamination there; their account also says soldiers did not enter the open fields in A, which weighs against the broad allegation there. |
| E6 | absence | A, B | 2 | - | The team directly observed no indicators along the field tracks and at the edge of B, but this limited observation does not establish absence across the unvisited forest belt. |

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
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, quality_control, safety_guidance, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation to clear the whole area is not itself a decision and is not supported by direct evidence in the file.
  - Part B was not entered during the NTS; findings along its edge do not establish conditions throughout the forest belt.
  - The national safe-use cancellation threshold for Part A has not been met.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
