# Sign-off sheet: C13, run 3

Case: A recorded minefield and a landslide below it in the Cordillera del Cóndor  
Area ID: PER-CHA-1311  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend technical survey for both parts. A is a confirmed minefield supported by a validated record and field markers, but the mine found outside its boundary and imagery showing soil movement across the boundary trigger the national requirement to define the hazard extent by technical survey before clearance. B has direct evidence of a mine on the landslide scar and indirect evidence of a movement pathway; the item's origin and the extent of any contamination remain uncertain. The single-item EOD spot-task characterization and the survey team's recommendation to cancel B do not establish that the wider slope is safe. No part meets cancellation criteria: neither has safe-use history, and avoidance is not evidence of safe use.

General guidance on the situation:

> Keep people and animals away from the minefield, landslide scar, and slope below it. Do not touch, move, or try to destroy any suspected item. Mark a location only if this can be done without going closer, and report any suspected item or hazard to the authorities. Continue to avoid the area pending survey and formal release.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The army's minefield record gives the outline of the minefield around the post and the pattern of its rows. | yes |
| E2 | In 2021 a demining team cleared the minefield of a neighbouring post, using a record made the same way by the same unit, and found the mines where the record placed them. | yes |
| E3 | Marker posts and warning signs stand at the corners of the recorded minefield; the team saw them and checked them against the record. | yes |
| E4 | After a landslide in 2025, a demining team found one mine on the landslide scar, outside the recorded minefield, and destroyed it. | yes |
| E5 | The binational demining unit compared both countries' army records for this stretch of the border in 2016; no other minefield is recorded near the post. | yes |
| E6 | We laid the minefield to the record. But the slope below was steep, and in the rains the ground moves. | yes |
| E7 | People from the community said they hunt and fish along the river below the slope, but nobody climbs the slope or goes near the post, and nobody knows of an accident there. | yes |
| E8 | Satellite imagery shows that the 2025 landslide carried soil from the edge of the recorded minefield down the slope. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | direct | A | 3 | - | National criteria treat this record as direct evidence because a same-kind record by the same unit was confirmed in clearance (E2). |
| E2 | not_evidence | outside | 3 | - | This outside-area completion report supports the reliability of E1 but does not itself locate EO in the area under review. |
| E3 | direct | A | 2 | - | Team-observed markers corroborated against the known minefield record support the minefield's presence and location. |
| E4 | direct | B | 1 | - | A mine was physically found at a known point in B; destruction does not erase the evidence of presence there. |
| E5 | absence | all | 3 | - | The verified record comparison supports absence of a separately recorded nearby minefield, but does not explain away the find in B or rule out movement from A. |
| E6 | indirect | A, B | 4 | - | First-hand testimony supports the recorded laying in A and suggests a plausible movement pathway affecting B, but does not itself confirm EO in B. |
| E7 | not_evidence | B, outside | 4 | - | Use of the river is outside the area and the slope and post are avoided, so the report supplies no evidence of safe use or absence of EO within A or B. |
| E8 | indirect | A, B | 2 | - | Team desk assessment of imagery indicates a physical pathway from the minefield edge into B, increasing concern about extent without confirming further EO. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R6 | all | pass | Every part is decided once. |
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E3, E6, E8. |
| R4 | B | pass | Evidence to target in part B: E4, E6, E8. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, quality_control, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's remarks are evidence to assess, not a decision; their assertions that the B find was moved from A and that the slope should be cancelled are not established by the evidence provided.
  - National criteria require technical survey to define the hazard extent where finds depart from a minefield record, before clearance.
  - The area is remote and access is by helicopter; factor safe, feasible planning into follow-up survey.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
