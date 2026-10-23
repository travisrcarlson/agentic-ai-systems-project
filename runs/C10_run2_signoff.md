# Sign-off sheet: C10, run 2

Case: Farmland near an old garrison road  
Area ID: SSD-SHA-8840  
Model: gpt-6-luna

## Recommendation
- Outcome: FURTHER_NTS
- By part: A=FURTHER_NTS; B=FURTHER_NTS
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Return both parts for further non-technical survey. The visit was not completed, the community meeting and required group consultations were not held, land use and road use remain unassessed in the field, and the available hazard information is weak and largely unverified. Reassess the database record and the vague second-hand report, and gather information from relevant community groups before deciding whether any targeted technical survey is justified.

General guidance on the situation:

> Until the area is assessed, do not assume it is safe. Keep people and animals away from any suspected dangerous place; do not touch, move or try to destroy anything. Report suspected explosive ordnance to the authorities, and mark a place only if this can be done without going closer.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The national database holds a record of a "dangerous area" by the old garrison road; its source and the date it was entered are unknown, and it gives no items or accidents. | yes |
| E2 | By phone, a local leader said people "do not go there" because of the war. Asked about finds or accidents, he said he had not seen any himself, but "people talk". | yes |
| E3 | The garrison on the road was abandoned in the 1990s; the team's desk assessment found no record of fighting there. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | A, B | 6 | - | The unverified database dangerous-area record suggests possible EO but gives no corroborating detail; its unknown provenance corresponds to an unassessed historical record. |
| E2 | indirect | A, B | 7 | - | The vague hearsay may indicate a hazard but gives no identifiable first-hand report; the avoidance stated is due to war and is not itself hazard evidence. |
| E3 | absence | A, B | 6 | E1 | The desk assessment's lack of a fighting record is weak negative historical information that weighs against, but does not disprove, the unsupported dangerous-area record. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| - | A | pass | Further non-technical survey is always open to the reviewer. |
| - | B | pass | Further non-technical survey is always open to the reviewer. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: evidence, reliability, hazard_areas, national_criteria, further_survey, outcomes, all_reasonable_effort

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team recommends retaining the SHA and planning technical survey; this is recorded as a recommendation, not treated as the decision. The case file says the visit was prevented by flooding, no community meeting was held, and no women, youth or land users were consulted.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
