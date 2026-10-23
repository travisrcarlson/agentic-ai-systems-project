# Sign-off sheet: C03, run 2

Case: Border farmland with a strip along the forest edge  
Area ID: KHM-SHA-2290  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=CANCEL; B=FURTHER_NTS
- By part: A=CANCEL; B=FURTHER_NTS
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend split release. Cancel Part A: ten years of repeated farming without finds, supported by two first-hand farmer accounts, meets the five-year and two-source national criteria; men and women were consulted, and the old area-wide suspicion is outweighed for this part. Return Part B for further non-technical survey: the second-hand, imprecise report near the trees is indirect evidence that cannot yet be located well enough to target technical survey, and the team did not enter the scrub. Do not extend Part A’s safe-use evidence to B.

General guidance on the situation:

> Until Part B is assessed and its status is resolved, keep people and animals away from the forest-edge strip. Do not touch, move or try to destroy anything suspected of being ordnance; mark a place only if this can be done without going closer, and report it to the authorities.

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
| E1 | indirect | all | 6 | - | An unvalidated historical SHA record based on proximity and avoidance suggests possible hazard but does not confirm mines. |
| E2 | absence | A | 4 | E1 | The farmer's first-hand account of repeated cultivation without finds is reliable evidence of safe use in Part A and weighs against the original suspicion there. |
| E3 | absence | A | 4 | E1 | A second first-hand farmer account independently supports sustained safe use in Part A, meeting the two-source criterion. |
| E4 | indirect | B | 7 | - | An untraceable, second-hand mine-incident report suggests possible hazard near the forest edge, but its exact location is unknown and it is not direct confirmation. |
| E5 | not_evidence | B | 4 | - | Avoidance based only on fear or unsubstantiated talk, with no reportable find or accident, does not itself establish EO evidence. |
| E6 | absence | A, B | 2 | - | The team's direct observation supports absence of visible indicators along the field edges and strip boundary, but the scrubby interior of B was not inspected. |
| E7 | absence | all | 4 | - | The chief's first-hand institutional account supports absence of recorded accidents during his tenure, but does not resolve the uncertain report near the trees. |

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
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, cancellation, technical_survey, further_survey, outcomes, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation to cancel the whole area is not followed for Part B; it is a recommendation to assess, not a decision. The team's observation did not include entry into the dense scrub.
  - Part A and Part B have different land-use histories and evidence; any release or continued hazard controls should preserve their distinction.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
