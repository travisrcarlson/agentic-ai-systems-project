# Sign-off sheet: C05, run 2

Case: Leased fields beside a forest belt in a de-occupied village  
Area ID: UKR-SHA-5526  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=FURTHER_NTS; B=TECHNICAL_SURVEY
- By part: A=FURTHER_NTS; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend further non-technical survey for A: evidence specific to the fields is mixed, safe use is only one year, and national cancellation criteria require three years and two first-hand sources. Do not infer clearance eligibility from the brief machinery use or the team's track observations. Recommend targeted technical survey for B: imagery of fighting positions, trenches and craters, together with first-hand reports of soldiers digging in, provides indirect evidence to target; the forest belt was not entered during NTS. No direct evidence supports clearance of either part.

General guidance on the situation:

> Keep people and animals away from any suspected hazardous locations. Do not touch, move or try to destroy anything; mark a place only if this can be done without going closer, and report it to the authorities.

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
| E1 | indirect | A, B | 6 | - | Unassessed settlement-list record and troop presence are indirect grounds for suspicion, not proof of EO. |
| E2 | indirect | A, B | 7 | - | The administrator is repeating unidentified second-hand claims; this is a weak indirect report, not confirmation. |
| E3 | absence | A | 4 | E1, E2 | First-hand safe machinery use for one season supports absence on A, but does not meet the national three-year threshold or provide two first-hand sources. |
| E4 | indirect | B | 2 | - | Survey-team imagery records positions and craters, which indicate possible contamination on B but show no EO directly. |
| E5 | indirect | B | 4 | - | First-hand accounts of soldiers digging in along B suggest possible contamination; the same account reports no troop activity on A, but that is not enough to overcome the conflicting broad claim and limited safe-use evidence. |
| E6 | absence | A, B | 2 | E1, E2 | Team observation supports absence along walked tracks in A and only the edge of B; it cannot support absence in the unentered forest belt. |

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
- Rule topics looked up: evidence, reliability, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation to clear the whole area is not a decision and is not supported by direct evidence in the file.
  - The survey team did not enter the forest belt; its observations of B are limited to the edge.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
