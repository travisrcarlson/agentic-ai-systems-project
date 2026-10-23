# Sign-off sheet: C03, run 1

Case: Border farmland with a strip along the forest edge  
Area ID: KHM-SHA-2290  
Model: gpt-6.1-sol

## Recommendation
- Outcome: SPLIT: A=CANCEL; B=FURTHER_NTS
- By part: A=CANCEL; B=FURTHER_NTS
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend cancellation of A only: ten years of annual tractor cultivation without finds or accidents, corroborated by two first-hand farmers, exceeds the five-year national threshold; both men and women were consulted. This reliable use history counters A's original contextual suspicion. For B, recommend further non-technical survey to trace the alleged buffalo accident to original witnesses, establish its location and review relevant historical sources before deciding whether technical survey can be targeted. B has no safe-use history, the dense scrub was not entered, and negative boundary observations cannot exclude contamination there. No direct evidence establishes a clearance requirement. The split recommendation passed the rule check and remains subject to human approval.

General guidance on the situation:

> Pending authority review, keep people and animals away from the unresolved forest-edge strip and any suspected item. Do not touch, move or try to destroy anything suspicious. Mark a suspected location only if this can be done without going closer, and report it to the responsible authorities. The recommendation does not itself authorize land release.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The 2012 baseline survey recorded the area as suspected because it lies near former positions on the border and people avoided it; no mines or accidents were recorded in the area. | yes |
| E2 | My family has ploughed these fields with a tractor every year since 2016, rice and cassava. We never found anything. | yes |
| E3 | We plant and harvest there every season. I have never seen a mine or heard of anyone hurt in the fields. | yes |
| E4 | He did not see it and could not say where it happened. | yes |
| E5 | Farmers do not farm or cut wood in the strip along the forest edge | yes |
| E6 | The team walked the edges of the fields and the boundary of the strip and saw no items, signs or fencing. | yes |
| E7 | The commune chief said the commune has recorded no accident in these fields since he took office in 2015. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | A, B | 6 | - | The unvalidated historical record provides contextual suspicion, not confirmed contamination. |
| E2 | absence | A | 4 | E1 | A first-hand farmer reports ten years of repeated safe ploughing in A, countering the baseline suspicion there but not in B. |
| E3 | absence | A | 4 | E1 | A second first-hand farmer corroborates sustained safe agricultural use of A only. |
| E4 | indirect | B | 7 | - | The alleged animal accident suggests possible contamination near the trees but its unidentified original source and uncertain location prevent confirmation or precise targeting. |
| E5 | indirect | B | 7 | - | Reported avoidance leaves B unused and weakly supports suspicion, but its hazard basis is untraceable hearsay and fear alone does not confirm contamination. |
| E6 | absence | A, B | 2 | - | Direct survey observation provides limited negative evidence at the inspected edges only and cannot exclude contamination in the unentered dense scrub of B. |
| E7 | absence | A, B | 4 | E1 | The chief gives first-hand institutional evidence of no recorded accidents since 2015, corroborating A's use but providing little reassurance for unused B and not disproving an older alleged accident. |

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
- Rule topics looked up: reliability, national_criteria, evidence, cancellation, further_survey, land_use, technical_survey, all_reasonable_effort

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation to cancel the entire area is not supported for B: absence of observed items does not establish absence of contamination in unentered scrub.
  - The alleged buffalo accident is unverified and unlocated; further survey should establish whether it relates to B at all.
  - Safe-use evidence from A must not be extrapolated to B; ensure their boundary is documented for sign-off.
  - Referenced photographs and sketch map were not reproduced in the supplied case file and could not be independently reviewed.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
