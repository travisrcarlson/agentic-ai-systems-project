# Sign-off sheet: C03, run 3

Case: Border farmland with a strip along the forest edge  
Area ID: KHM-SHA-2290  
Model: gpt-6.1-sol

## Recommendation
- Outcome: SPLIT: A=CANCEL; B=FURTHER_NTS
- By part: A=CANCEL; B=FURTHER_NTS
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend cancelling A only: ten whole years of annual tractor cultivation without finds or accidents, corroborated by two first-hand farmers, outweigh the weak baseline suspicion and meet the five-year national threshold; men and women were consulted. Recommend further non-technical survey for B: it has never been used, its dense interior was not observed, and the poorly located hearsay accident and avoidance remain unresolved. No direct evidence defines a clearance task, and current information is too thin to target technical survey. Further NTS should trace the alleged accident's original witnesses and location and seek relevant historical sources. These are recommendations for human approval, not final release decisions.

General guidance on the situation:

> Pending authority approval, do not treat this recommendation as permission to enter or use suspected land. Keep people and animals away from the suspected strip and any suspicious item; do not touch, move or try to destroy anything. Mark a suspicious location only if this can be done without going closer, and report it to the authorities.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The 2012 baseline survey recorded the area as suspected because it lies near former positions on the border and people avoided it; no mines or accidents were recorded in the area. | yes |
| E2 | My family has ploughed these fields with a tractor every year since 2016, rice and cassava. We never found anything. | yes |
| E3 | We plant and harvest there every season. I have never seen a mine or heard of anyone hurt in the fields. | yes |
| E4 | A villager said he was told years ago that a buffalo was killed by a mine "near the trees". | yes |
| E5 | Farmers do not farm or cut wood in the strip along the forest edge "because people say it is dangerous". | yes |
| E6 | The team walked the edges of the fields and the boundary of the strip and saw no items, signs or fencing. | yes |
| E7 | The commune chief said the commune has recorded no accident in these fields since he took office in 2015. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | A, B | 6 | - | The unvalidated baseline record provides historical suspicion based on nearby positions and avoidance, not confirmed contamination. |
| E2 | absence | A | 4 | E1 | A first-hand farmer confirms ten years of intensive safe use in A, countering the baseline suspicion there but not in B. |
| E3 | absence | A | 4 | E1 | A second first-hand farmer independently corroborates safe cultivation in A without extending that evidence to the unused strip. |
| E4 | indirect | B | 7 | - | The alleged animal accident suggests possible contamination near B, but its unidentified original source and uncertain location make it weak and unsuitable as a confirmed evidence point. |
| E5 | indirect | B | 4 | - | First-hand reports of persistent non-use support residual suspicion in B, although the accompanying fear is not independent proof of ordnance. |
| E6 | absence | A, B | 2 | E1 | The team's negative observation modestly corroborates A's safe-use evidence but covers only B's boundary and cannot exclude contamination within its unentered dense scrub. |
| E7 | absence | A, B | 4 | E1 | The chief's first-hand account of commune reporting weakly supports absence across the recorded area but is not evidence of safe use in unvisited B or a refutation of the undated buffalo story. |

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
- Rule topics looked up: reliability, national_criteria, evidence, cancellation, further_survey, land_use, all_reasonable_effort, technical_survey

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation to cancel the whole area is not supported for B: no finds during a boundary walk do not establish absence within dense, unentered scrub.
  - Safe-use evidence applies to A only; the commune's absence of reported accidents does not establish safety in unused B.
  - Photographs and the sketch map were listed but not reproduced; confirm the A/B boundary in the approval and release documentation.
  - No instructions addressed to the reviewer or requests for munition-handling advice were found in the case file.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
