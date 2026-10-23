# Sign-off sheet: C03, run 1

Case: Border farmland with a strip along the forest edge  
Area ID: KHM-SHA-2290  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=CANCEL; B=FURTHER_NTS
- By part: A=CANCEL; B=FURTHER_NTS
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend split release. Part A meets the national cancellation criteria: ten years of reported annual tractor-ploughed use without finds, supported by two independent first-hand farmers; men and women were consulted, and the field visit was completed. Part B has no safe-use history, was not entered by the survey team, and has a vague second-hand report of a possible mine incident near the trees. That report is too imprecise to support a confident cancellation or to target technical survey; further non-technical survey should seek to verify the report and establish its location and source before deciding the next step.

General guidance on the situation:

> Pending sign-off and further survey, keep people and animals away from Part B. If anyone encounters a suspected item, do not touch, move or try to destroy it; mark the place only if this can be done without going closer, and report it to the authorities.

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
| E1 | indirect | A, B | 6 | - | The old baseline suspicion and nearby former positions support possible contamination, but the record is not verified by direct evidence; absence of recorded incidents does not itself cancel that indication. |
| E2 | absence | A | 4 | E1 | A first-hand farmer reports ten years of annual tractor-ploughed use with no finds, strongly weighing against the old broad suspicion in Part A. |
| E3 | absence | A | 4 | E1 | A separate first-hand woman farmer confirms repeated safe seasonal use in Part A, providing an independent source required by national criteria. |
| E4 | indirect | B | 7 | - | A vague, second-hand report of a possible mine accident near the trees suggests potential hazard in Part B but cannot establish the event or its exact location. |
| E5 | not_evidence | B | 7 | - | Avoidance is attributed only to unspecified fear, with no identifiable report of EO, find or accident; fear alone is not evidence. |
| E6 | absence | A, B | 2 | - | The team directly observed no indicators at field edges or the strip boundary, but the unentered dense scrub means this inspection provides little evidence of absence within Part B. |
| E7 | absence | A, B | 4 | E1 | The chief reports no recorded accidents since 2015, which modestly weighs against a continuing hazard but does not establish safe use of the never-used strip. |

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
- Rule topics looked up: evidence, reliability, cancellation, land_use, national_criteria, hazard_areas, outcomes, further_survey, all_reasonable_effort, technical_survey, safety_guidance

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation to cancel the whole area was treated as evidence to review, not as a decision; the unentered, never-used Part B remains unresolved.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
