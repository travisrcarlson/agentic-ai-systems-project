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

> Recommend a split. In A, the area-wide troop-presence record and administrator's second-hand claim are countered by first-hand testimony that troops did not enter the open fields, plus one uneventful farming season. However, the national cancellation threshold of three years' safe use and two first-hand safe-use sources is not met, and the conflicting, limited information does not support cancellation; return A for further non-technical survey. In B, first-hand testimony of soldiers digging in and survey imagery of positions, trenches and craters provide locatable indirect evidence, suitable to target technical survey. No direct evidence of EO is reported, so whole-area clearance is not supported.

General guidance on the situation:

> Pending further assessment and release decisions, keep people and animals away from the forest belt and its edge, and follow local authority safety notices. If anyone encounters a suspected item, do not touch, move or try to destroy it; keep others away, mark the place only if that can be done without going closer, and report it to the authorities.

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
| E1 | indirect | all | 6 | - | An unvalidated settlement-list entry reports troop presence, which is indirect under national criteria and records no area-specific items or positions. |
| E2 | indirect | all | 7 | - | The administrator's broad, second-hand claim suggests possible contamination but is not first-hand or location-specific. |
| E3 | absence | A | 4 | - | The leaseholder gives first-hand evidence of one uneventful season of machinery farming in A, but not the minimum safe-use duration. |
| E4 | indirect | B | 2 | - | Survey-team imagery directly observes physical indicators in B, but positions, trenches and craters without items are indirect evidence under the case criteria. |
| E5 | absence | A | 4 | E1, E2 | Classed for A, where these first-hand witnesses say soldiers did not enter the visible fields, countering the broad record and second-hand claim; the same testimony reports soldiers dug in along B, which is an indirect hazard indicator. |
| E6 | absence | A, B | 2 | - | Team's surface observation supports absence only on walked field tracks in A and at the edge of B; the forest belt was not entered, so this does not explain away E4 or the B hazard. |

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
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, quality_control, national_criteria, case_file_text

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team recommended clearance of the whole area, but this is a recommendation rather than a decision; the file reports no direct evidence defining a hazard for clearance.
  - The team did not enter the forest belt; the absence observation is limited to field tracks and the edge, so it does not resolve the evidence in B.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 1

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
