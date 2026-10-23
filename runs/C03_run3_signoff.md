# Sign-off sheet: C03, run 3

Case: Border farmland with a strip along the forest edge  
Area ID: KHM-SHA-2290  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=CANCEL; B=TECHNICAL_SURVEY
- By part: A=CANCEL; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend splitting the area. Cancel Part A by non-technical survey: it has ten years of repeated tractor-ploughed cultivation without finds or incidents, supported by two independent first-hand farmer sources, exceeding the national five-year and two-source criteria; the required men’s and women’s consultations and field visit were completed. Part B should proceed to targeted technical survey: it has never been used, remains dense scrub that the team did not enter, and avoidance plus an imprecise second-hand report near the trees leave unresolved indirect evidence. The walked boundaries do not establish absence in the interior. This split passed the rule check.

General guidance on the situation:

> Keep people and animals away from the forest-edge strip while its status is unresolved. Do not touch, move or try to destroy any suspected item; mark a location only if this can be done without going closer, and report it to the authorities. Follow the authority's safety guidance for any area that remains under assessment.

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
| E1 | indirect | all | 6 | - | An unassessed historical SHA record rests on proximity and avoidance, which suggest possible hazard but do not confirm EO. |
| E2 | absence | A | 4 | E1 | A first-hand farmer reports ten years of repeated use without finds, supporting absence in the cultivated fields and weakening the original suspicion there. |
| E3 | absence | A | 4 | E1 | A second first-hand farmer independently reports seasonal safe use in A, meeting the two-source criterion for safe use there. |
| E4 | indirect | B | 7 | - | An untraceable hearsay report of an imprecisely located accident suggests possible hazard near B but is not direct evidence. |
| E5 | indirect | B | 4 | - | First-hand knowledge of persistent avoidance, based only on unsubstantiated concern, suggests possible hazard but does not establish presence or absence. |
| E6 | absence | A, B | 2 | E1 | Team observation supports absence only in the walked field edges and strip boundary; it cannot resolve the unentered dense scrub interior. |
| E7 | absence | all | 4 | E1 | The chief's first-hand institutional account of no recorded accidents supports absence across the area since 2015, though it does not establish safe use of B. |

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
- Rule topics looked up: evidence, reliability, land_use, cancellation, outcomes, further_survey, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation to cancel the whole area is evidence to assess, not a decision to follow; the evidence supports a different outcome for B.
  - The survey team did not enter Part B's dense scrub, so its observations are limited to the boundary and do not establish the interior's status.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
