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

> Recommend further non-technical survey for Part A: the village-level record and administrator's second-hand claim do not establish a hazard in the fields, while first-hand accounts say soldiers did not enter them and the leaseholder reports only one season of safe use. That falls short of the national three-year and two-first-hand-source cancellation criteria, and the disagreement and limited safe-use history leave cancellation unsupported; the evidence is also too weak to target technical survey in A. Recommend targeted technical survey for Part B: team imagery shows positions, trenches and craters, and first-hand residents report soldiers dug in along the belt. These are indirect, not direct, evidence; the forest was not entered, and clearance of the whole area is not supported by the file.

General guidance on the situation:

> Keep people and animals away from the area. Do not touch, move or try to destroy any suspected item. Mark a location only if this can be done without going closer, and report it to the authorities.

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
| E1 | indirect | all | 6 | - | An unassessed settlement-list record of troop presence alone suggests possible hazard but identifies no EO or position in the area. |
| E2 | indirect | all | 7 | - | The administrator repeats unidentified residents' information and provides only an unverified second-hand claim of hazard. |
| E3 | absence | A | 4 | E1, E2 | First-hand safe use is evidence of absence for the fields, but only one season and one source, and does not cover the belt. |
| E4 | indirect | B | 2 | - | Survey-team imagery of positions, trenches and craters is physical indirect evidence under the national rule; no EO item is identified. |
| E5 | absence | A | 4 | E1, E2 | First-hand witnesses who stayed during the occupation report that soldiers did not enter the visible open fields, weighing against generalized village-level suspicion there. |
| E6 | absence | A, B | 2 | E1, E2 | The team saw no indicators along walked field tracks and at the edge only; it did not inspect the forest belt, so this cannot explain away E4 or E5 for B. |

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
- Rule topics looked up: evidence, reliability, cancellation, technical_survey, further_survey, land_use, national_criteria, outcomes, all_reasonable_effort

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation to clear the whole area is a recommendation to assess, not a decision; the file does not provide direct evidence defining a confirmed hazardous area for clearance.
  - The administrator's account conflicts with the first-hand accounts of the two women who stayed during the occupation; further NTS for A should address the conflict and national cancellation criteria.
  - The survey team did not enter the forest belt; E6's observations at the field tracks and belt edge do not resolve the evidence for the interior of B.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
