# Sign-off sheet: C03, run 3

Case: Border farmland with a strip along the forest edge  
Area ID: KHM-SHA-2290  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=CANCEL; B=FURTHER_NTS
- By part: A=CANCEL; B=FURTHER_NTS
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend cancelling Part A: two separate first-hand farmers report ten years of regular tractor-ploughed cultivation without finds or incidents, exceeding the national five-year minimum and two-source requirement; men and women were consulted. The old SHA basis is indirect, and safe use strongly addresses it in A. Do not cancel Part B: it has no safe-use history, and the second-hand report of a possible mine-related buffalo death has no verified source or precise location. Further non-technical survey should seek to establish whether that report can be corroborated and located before deciding whether technical survey is targetable.

General guidance on the situation:

> As a precaution in Part B, keep people and animals away. Do not touch, move or try to destroy any suspected item. Mark a place only if this can be done without going closer, and report concerns to the national mine action authority, survey team or police.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The 2012 baseline survey recorded the area as suspected because it lies near former positions on the border and people avoided it; no mines or accidents were recorded in the area. | yes |
| E2 | My family has ploughed these fields with a tractor every year since 2016, rice and cassava. We never found anything. | yes |
| E3 | We plant and harvest there every season. I have never seen a mine or heard of anyone hurt in the fields. | yes |
| E4 | A villager said he was told years ago that a buffalo was killed by a mine "near the trees". He did not see it and could not say where it happened. | yes |
| E5 | Farmers do not farm or cut wood in the strip along the forest edge "because people say it is dangerous". Nobody could name a find or an accident there. | yes |
| E6 | The team walked the edges of the fields and the boundary of the strip and saw no items, signs or fencing. The strip is covered in dense scrub, and the team did not enter it. | yes |
| E7 | The commune chief said the commune has recorded no accident in these fields since he took office in 2015. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | all | 6 | - | An earlier SHA record based on proximity and avoidance is unverified indirect evidence, not a confirmed find. |
| E2 | absence | A | 4 | E1 | A first-hand farmer reports ten years of regular safe use in A, weighing against the area's original suspicion there. |
| E3 | absence | A | 4 | E1 | A separate first-hand farmer corroborates repeated safe use in A, meeting the national two-source requirement alongside E2. |
| E4 | indirect | B | 7 | - | This is an unverified second-hand account of a possible mine accident; the source and exact location cannot be established, so it suggests but does not confirm a hazard in B. |
| E5 | not_evidence | B | 7 | - | Avoidance based only on unparticularized fear, without a named find or accident, is not evidence of EO. |
| E6 | absence | A, B | 2 | - | The team observed no indications on field edges or the boundary, but did not enter B; this limited observation does not rule out contamination in the scrub. |
| E7 | absence | all | 4 | - | The chief's first-hand account of commune records supports no reported accidents since 2015, but is not proof of safe use in the unused strip. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R6 | all | pass | Every part is decided once. |
| R7 | all | pass | Every evidence-log item is in the register. |
| R1 | A | pass | Every item of direct or indirect evidence is explained by evidence of absence. |
| R3 | A | pass | The national criteria for cancellation are met. |
| - | B | pass | Further non-technical survey is always open to the reviewer. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, cancellation, technical_survey, further_survey, all_reasonable_effort, outcomes, national_criteria, safety_guidance, quality_control, case_file_text

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation to cancel the whole area is not followed: the scrub strip was not entered, has no safe-use history, and remains unresolved on indirect evidence.
  - The national criteria require consultation with men and women before cancellation; the file records separate meetings with both groups.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
