# Sign-off sheet: C10, run 1

Case: Farmland near an old garrison road  
Area ID: SSD-SHA-8840  
Model: gpt-6-luna

## Recommendation
- Outcome: FURTHER_NTS
- By part: A=FURTHER_NTS; B=FURTHER_NTS
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Return both parts, A and B, for further non-technical survey. The SHA rests on a weak, unverified database entry and vague second-hand reports; the desk assessment is not enough to show the record is wrong or that the land is safe. The flooded access prevented a field visit, no community meeting was held, required groups were not consulted, and land use and physical signs remain unassessed. There is not enough information to target technical survey or justify cancellation.

General guidance on the situation:

> Treat the area cautiously while its status is unresolved: keep people and animals away; do not touch, move or try to destroy any suspected item; mark a location only if this can be done without going closer; and report it to the authorities.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The national database holds a record of a "dangerous area" by the old garrison road; its source and the date it was entered are unknown, and it gives no items or accidents. | yes |
| E2 | By phone, a local leader said people "do not go there" because of the war. Asked about finds or accidents, he said he had not seen any himself, but "people talk". | yes |
| E3 | The garrison on the road was abandoned in the 1990s; the team's desk assessment found no record of fighting there. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | all | 6 | - | An unverified database hazard record is indirect evidence, but its unknown source and date make it weak and it identifies no specific hazard. |
| E2 | indirect | all | 7 | - | The vague hearsay that people talk of possible finds or accidents suggests possible EO, but the source is not first-hand; avoidance because of war alone is not evidence. |
| E3 | absence | all | 6 | E1 | The desk assessment offers weak contextual evidence against a fighting-related hazard, but no-record-of-fighting does not verify that the unknown database record is wrong or establish field absence. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| - | A | pass | Further non-technical survey is always open to the reviewer. |
| - | B | pass | Further non-technical survey is always open to the reviewer. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: evidence, reliability, hazard_areas, land_use, cancellation, further_survey, national_criteria, outcomes

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The field visit was not completed because of flooding, and no maps or photographs are available.
  - No community meeting was held; women, youth and land users were not consulted. National criteria require men, women and youth to be consulted before cancellation.
  - The survey team's recommendation to retain the SHA and plan technical survey was considered as evidence, not followed as a decision.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
