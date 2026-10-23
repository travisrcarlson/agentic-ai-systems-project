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

> Recommend cancelling Part A: two first-hand farmer accounts and ten years of annual ploughing without finds meet the national five-year threshold and two-source requirement; men and women were consulted, and the initial record rests on indirect evidence. Return Part B for further non-technical survey: it has never been used, avoidance is based on unspecified hearsay, the reported buffalo death is second-hand and unlocated, and the team did not enter the dense scrub. The available information does not support cancelling B or confidently targeting technical survey there.

General guidance on the situation:

> Pending sign-off and further survey, keep people and animals away from the forest-edge strip. If anyone encounters a suspected item, do not touch, move or try to destroy it; mark the place only if this can be done without going closer, and report it to the authorities.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The 2012 baseline survey recorded the area as suspected because it lies near former positions on the border and people avoided it; no mines or accidents were recorded in the area. | yes |
| E2 | "My family has ploughed these fields with a tractor every year since 2016, rice and cassava. We never found anything." | yes |
| E3 | "We plant and harvest there every season. I have never seen a mine or heard of anyone hurt in the fields." | yes |
| E4 | A villager said he was told years ago that a buffalo was killed by a mine "near the trees". He did not see it and could not say where it happened. | yes |
| E5 | Farmers do not farm or cut wood in the strip along the forest edge "because people say it is dangerous". Nobody could name a find or an accident there. | yes |
| E6 | The team walked the edges of the fields and the boundary of the strip and saw no items, signs or fencing. The strip is covered in dense scrub, and the team did not enter it. | yes |
| E7 | The commune chief said the commune has recorded no accident in these fields since he took office in 2015. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | all | 6 | - | An unvalidated historical SHA entry based on proximity and avoidance suggests possible hazard but supplies no direct confirmation; the absence of recorded incidents does not by itself establish safe use. |
| E2 | absence | A | 4 | E1 | The farmer reports first-hand, sustained cultivation without finds in Part A, relevant absence evidence for that zone. |
| E3 | absence | A | 4 | E1 | A first-hand woman farmer corroborates repeated safe use and no observed mine or injury in Part A. |
| E4 | indirect | B | 7 | - | A vague, unlocated second-hand accident report suggests possible hazard near Part B but cannot establish its location or confirm contamination. |
| E5 | indirect | B | 7 | - | Avoidance and unspecified hearsay suggest possible hazard in the unused strip but identify no verifiable find or accident. |
| E6 | absence | A, B | 2 | E1 | Team observations provide absence evidence only for areas visually inspected, including field edges and the strip boundary; dense scrub was not entered, so this does not resolve the interior of Part B. |
| E7 | absence | all | 4 | E1 | The chief's firsthand knowledge of commune records supports no recorded accidents since 2015, but does not prove the scrub strip is hazard-free. |

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
- Rule topics looked up: evidence, reliability, land_use, cancellation, further_survey, outcomes, national_criteria, hazard_areas

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation to cancel the whole area is not adopted for Part B; its own account notes that the scrub was not entered and the only report is second-hand.
  - Further NTS for Part B should seek to clarify the source and location of the reported incident and establish whether more specific evidence can guide the next decision.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
