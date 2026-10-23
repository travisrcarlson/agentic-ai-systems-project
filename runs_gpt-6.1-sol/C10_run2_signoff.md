# Sign-off sheet: C10, run 2

Case: Farmland near an old garrison road  
Area ID: SSD-SHA-8840  
Model: gpt-6.1-sol

## Recommendation
- Outcome: FURTHER_NTS
- By part: A=FURTHER_NTS; B=FURTHER_NTS
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend further non-technical survey for both A and B. E1 is an unverified indirect record; E2 provides fear and untraceable talk, not specific hazard evidence; E3 neither establishes contamination nor disproves E1. Flooding prevented the field visit, no community meeting occurred, required groups were not consulted, and land use is unknown. Cancellation criteria are unmet and evidence is insufficient to target technical survey. When safe access permits, complete field assessment of land and road use, consult men, women, youth and first-hand witnesses, trace the original record, and document any physical signs and locations before reassessment.

General guidance on the situation:

> Pending reassessment, keep people and animals away from suspected places. Do not touch, move or try to destroy any suspicious item. Mark the place only if this can be done without going closer, and report it to the national mine action authority, survey team or police.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | its source and the date it was entered are unknown, and it gives no items or accidents. | yes |
| E2 | he said he had not seen any himself, but "people talk". | yes |
| E3 | The garrison on the road was abandoned in the 1990s; the team's desk assessment found no record of fighting there. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | A, B | 6 | - | An unverified historical dangerous-area record suggests possible contamination across the area but confirms neither ordnance nor its location. |
| E2 | not_evidence | A, B | 7 | - | Fear of the war and unspecified talk without identifiable first-hand sources establish neither contamination nor safe use. |
| E3 | not_evidence | A, B | 6 | - | Garrison history without a specific contamination link and a desk search finding no fighting record neither establish ordnance nor reliably explain away the dangerous-area record. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| - | A | pass | Further non-technical survey is always open to the reviewer. |
| - | B | pass | Further non-technical survey is always open to the reviewer. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: national_criteria, reliability, evidence, further_survey, technical_survey, cancellation, all_reasonable_effort, safety_guidance

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - Recommendation only; requires authorized human review and sign-off and does not release either part.
  - The survey team's proposed technical survey is premature: the non-technical survey is incomplete and cannot yet support targeting.
  - Flooding and insecurity constrain access; arrange follow-up only when safe.
  - No maps, photographs or attachments support the record; the hazard type and safe-use history remain unknown.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
