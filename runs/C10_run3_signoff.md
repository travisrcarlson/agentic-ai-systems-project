# Sign-off sheet: C10, run 3

Case: Farmland near an old garrison road  
Area ID: SSD-SHA-8840  
Model: gpt-6-luna

## Recommendation
- Outcome: FURTHER_NTS
- By part: A=FURTHER_NTS; B=FURTHER_NTS
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend returning both parts (A and B) for further non-technical survey. The only hazard indication is an unverified database record; the phone report is fear and unidentified hearsay, and the desk review does not establish absence of EO. The field visit was not completed, land use is unknown, and required community groups were not consulted, so there is insufficient evidence either to cancel the SHA or to target technical survey. Revisit when access permits, assess land and road use in the field, and consult men, women and youth before a release decision.

General guidance on the situation:

> Until the area is adequately assessed, people should avoid entering it where practicable. If anyone encounters a suspected explosive ordnance item, keep people and animals away, do not touch, move or try to destroy it, mark the place only if this can be done without going closer, and report it to the authorities.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The national database holds a record of a "dangerous area" by the old garrison road; its source and the date it was entered are unknown, and it gives no items or accidents. | yes |
| E2 | By phone, a local leader said people "do not go there" because of the war. Asked about finds or accidents, he said he had not seen any himself, but "people talk". | yes |
| E3 | The garrison on the road was abandoned in the 1990s; the team's desk assessment found no record of fighting there. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | A, B | 6 | - | The unverified database hazard record suggests possible EO but does not establish its presence or a specific location. |
| E2 | not_evidence | A, B | 7 | - | Avoidance is attributed to fear of war and the unsourced talk about finds or accidents is not evidence of EO. |
| E3 | not_evidence | A, B | 6 | - | The absence of a record of fighting does not establish that EO is absent at a former garrison, and the desk assessment does not identify a hazard. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| - | A | pass | Further non-technical survey is always open to the reviewer. |
| - | B | pass | Further non-technical survey is always open to the reviewer. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: evidence, reliability, hazard_areas, cancellation, further_survey, land_use, all_reasonable_effort, outcomes, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The accredited team's recommendation to retain the SHA and plan technical survey is evidence to review, not a decision; the present record does not provide enough information to target technical survey.
  - The field visit was prevented by flooding; no community meeting was held, women, youth and land users were not consulted, and land use is unknown in both parts.
  - The national criteria require field assessment of land and road use and consultation with men, women and youth before cancellation.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
