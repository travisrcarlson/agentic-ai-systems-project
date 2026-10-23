# Sign-off sheet: C03, run 1

Case: Border farmland with a strip along the forest edge  
Area ID: KHM-SHA-2290  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=CANCEL; B=TECHNICAL_SURVEY
- By part: A=CANCEL; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend cancellation of Part A: two separate first-hand farmer accounts support ten years of regular ploughing and cropping without finds, meeting the national five-year threshold and first-hand-source requirement; men and women were consulted. Keep Part B as a separate survey target: it has never been used, reports of danger and a poorly located second-hand animal-incident account remain indirect evidence, and the team did not enter its dense scrub. The evidence supports targeted technical survey of B, not cancellation of the whole area. This split passed the rule check.

General guidance on the situation:

> Treat Part B as potentially hazardous until further survey and any required release decision are complete; keep people and animals away. If anyone encounters a suspected item, do not touch, move or try to destroy it; report it to the authorities and mark the place only if that can be done without going closer.

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
| E1 | indirect | all | 6 | - | An unvalidated historical SHA record based on proximity and avoidance suggests possible contamination but reports no finds or accidents. |
| E2 | absence | A | 4 | E1 | The farmer's first-hand account supports ten years of productive use without finds in A and weighs against the old area-wide suspicion there. |
| E3 | absence | A | 4 | E1 | A separate first-hand woman farmer corroborates regular seasonal use without finds or injury in A. |
| E4 | indirect | B | 7 | - | An unlocated, third-hand animal-incident report weakly suggests possible hazard near B but cannot confirm a specific event or location. |
| E5 | indirect | B | 4 | - | Non-use is a relevant indirect warning, although the stated danger is hearsay and no specific find or accident was identified. |
| E6 | absence | A, B | 2 | - | The team directly observed no signs at the field edges or B boundary, but did not inspect B's interior, so this absence is limited in scope. |
| E7 | absence | A | 4 | E1 | The chief's institutional knowledge supports no recorded accidents in the cultivated fields since 2015, but does not address the unused strip. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R6 | all | pass | Every part is decided once. |
| R7 | all | pass | Every evidence-log item is in the register. |
| R1 | A | pass | Every item of direct or indirect evidence is explained by evidence of absence. |
| R3 | A | pass | The national criteria for cancellation are met. |
| R4 | B | pass | Evidence to target in part B: E1, E4, E5. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: evidence, reliability, land_use, cancellation, further_survey, outcomes, national_criteria, all_reasonable_effort

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation to cancel the whole area is considered as evidence, not followed as a decision; its inspection of B was limited to the boundary and did not enter the scrub.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
