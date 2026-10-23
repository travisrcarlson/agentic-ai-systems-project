# Sign-off sheet: C10, run 1

Case: Farmland near an old garrison road  
Area ID: SSD-SHA-8840  
Model: gpt-6.1-sol

## Recommendation
- Outcome: FURTHER_NTS
- By part: A=FURTHER_NTS; B=FURTHER_NTS
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend further non-technical survey for both A and B. E1 is weak indirect evidence from an unassessed database record; E2 supplies only fear and unspecified hearsay; E3 establishes neither contamination nor absence. Flooding prevented the field visit, no community meeting occurred, and land use is unknown. Evidence is insufficient to target technical survey, define a clearance task, or meet cancellation criteria. When access is safe, complete field assessment of land and road use, consult men, women, youth and first-hand land users, trace the original record, and document any physical signs and hazard locations before reassessment.

General guidance on the situation:

> Pending assessment, keep people and animals away from suspected locations. Do not touch, move or try to destroy any suspected item. Mark a location only if this can be done without going closer, and report it to the national mine action authority, survey team or police.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The national database holds a record of a "dangerous area" by the old garrison road; its source and the date it was entered are unknown, and it gives no items or accidents. | yes |
| E2 | Asked about finds or accidents, he said he had not seen any himself, but "people talk". | yes |
| E3 | The garrison on the road was abandoned in the 1990s; the team's desk assessment found no record of fighting there. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | A, B | 6 | - | The unassessed database record suggests possible contamination but supplies no verified source or specific hazard. |
| E2 | not_evidence | A, B | 7 | - | Fear and unspecified talk from unidentified sources establish neither contamination nor safe use. |
| E3 | not_evidence | A, B | 6 | - | An abandoned garrison and lack of a fighting record neither establish ordnance presence nor demonstrate its absence. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| - | A | pass | Further non-technical survey is always open to the reviewer. |
| - | B | pass | Further non-technical survey is always open to the reviewer. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: national_criteria, reliability, evidence, further_survey, all_reasonable_effort, technical_survey, cancellation, safety_guidance

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - Recommendation requires human review and sign-off; it does not release either part or confirm contamination.
  - The team's recommendation to plan technical survey is premature because the available information cannot target it.
  - Flooding and insecurity constrain access; arrange further survey only when safe.
  - No maps, photographs or attachments are available, and required community consultation and field land-use assessment remain incomplete.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
