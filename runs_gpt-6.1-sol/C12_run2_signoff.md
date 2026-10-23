# Sign-off sheet: C12, run 2

Case: A slope below a former position in the Civilian Control Zone  
Area ID: KOR-SHA-1207  
Model: gpt-6.1-sol

## Recommendation
- Outcome: SPLIT: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY; C=CANCEL
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY; C=CANCEL
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend targeted technical survey of A and B, retaining their suspected status pending results, and cancellation of C subject to defence authority approval. A has an unconfirmed military listing and a non-first-hand former soldier's account; its precautionary fence does not confirm contamination. B has a plausible monsoon transport route from A and no safe-use history. These provide targets for survey, not grounds for immediate clearance. C was included by parcel boundaries without hazard evidence; 30 years of ploughed agricultural use, independently corroborated by the farmer and women's meeting, exceed the national safe-use criteria, and observed drainage separates C from the gully pathway. Both required community groups were consulted. The absence of finds on unused A and B does not justify cancellation.

General guidance on the situation:

> Pending approval and survey, keep people and animals away from the slope and gully and observe existing access restrictions. Do not touch, move or try to destroy any suspicious item. Mark its location only if this can be done without going closer, and report it to the authorities. Cancellation of C is a recommendation for sign-off, not permission to enter or disregard Civilian Control Zone controls.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The military's list records the slope as an "unconfirmed minefield" | yes |
| E2 | without any evidence of its own for those parts. | yes |
| E3 | it was put up in 1998 as a precaution | yes |
| E4 | I did not see it laid. It was done before I arrived, and nobody had a map. | yes |
| E5 | In heavy monsoon rain the gully floods and carries soil and debris down from the slope to the stream. | yes |
| E6 | My family has farmed these paddy fields since 1996, with a permit. We plough every spring. Nothing has ever been found. | yes |
| E7 | The women said they plant and harvest in the paddy fields every season and have never seen anything suspicious | yes |
| E8 | The paddy fields lie on a terrace above the gully bed, and the gully drains into the stream, not across the fields. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | A | 6 | - | The unassessed historical listing supports suspicion on the slope but neither confirms emplacement nor is disproved by the lack of recorded finds. |
| E2 | absence | B, C | 6 | E1 | The county record explains why the slope listing was extended administratively to B and C, but does not exclude a separate run-off hazard in B. |
| E3 | indirect | A | 2 | - | The observed fence reflects the existing suspicion only; its documented precautionary origin means it is not independent confirmation of mines. |
| E4 | indirect | A | 7 | - | The former soldier's claim supports suspicion but is not first-hand evidence of laying and identifies no first-hand informant. |
| E5 | indirect | B | 2 | - | Observed drainage provides a plausible route from the suspected slope into the unused gully, without confirming any ordnance there. |
| E6 | absence | C | 4 | E2 | A farmer working the fields provides first-hand evidence of sustained safe agricultural use confined to C. |
| E7 | absence | C | 4 | E2 | The separately consulted women independently confirm first-hand seasonal safe use of C, not of the slope or gully. |
| E8 | absence | C | 2 | E5 | Observed topography excludes the identified gully run-off route from extending into the paddy fields. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R6 | all | pass | Every part is decided once. |
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E3, E4. |
| R4 | B | pass | Evidence to target in part B: E5. |
| R1 | C | pass | Every item of direct or indirect evidence is explained by evidence of absence. |
| R3 | C | pass | The national criteria for cancellation are met. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: reliability, national_criteria, evidence, cancellation, technical_survey, further_survey, land_use, hazard_areas

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - Defence authority approval is required before any release in the Civilian Control Zone.
  - Intrusive work in protected habitat requires an environmental permit and appropriately constrained methods; habitat protection is not a reason to cancel.
  - The survey team's whole-area cancellation recommendation and the county's farming request are not supported for A or B.
  - No direct evidence confirms mines; confidence is in the recommended next steps, not in actual presence or absence on A and B.
  - Referenced defence records and photographs are not reproduced in the supplied file; verify them and the part boundaries during sign-off.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
