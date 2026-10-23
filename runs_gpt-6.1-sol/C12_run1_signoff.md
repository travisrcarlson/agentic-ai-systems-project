# Sign-off sheet: C12, run 1

Case: A slope below a former position in the Civilian Control Zone  
Area ID: KOR-SHA-1207  
Model: gpt-6.1-sol

## Recommendation
- Outcome: SPLIT: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY; C=CANCEL
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY; C=CANCEL
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend targeted technical survey of A and B, retaining suspected status pending results, and cancellation of C subject to defence authority approval. A has unresolved indirect evidence from the unconfirmed military listing and non-eyewitness soldier report; precautionary fencing does not confirm mines. B has a plausible monsoon migration pathway from A despite its original administrative inclusion. Neither part has safe-use evidence, and no direct evidence justifies immediate clearance. C has 30 years of cultivation corroborated by two first-hand sources, with both men and women consulted; observed terrace and drainage separation address migration concerns. The parcel-based boundary does not establish contamination in C. Habitat protection and absence of recorded finds do not justify whole-area cancellation.

General guidance on the situation:

> Keep people and animals away from the suspected slope and gully and respect existing access restrictions. Do not touch, move or try to destroy suspicious objects. Mark a suspicious location only if this can be done without going closer, and report it to the authorities. This recommendation does not itself authorize access or release.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The military's list records the slope as an "unconfirmed minefield" | yes |
| E2 | The county drew the suspected area to the edges of the land parcel, taking in the gully and the paddy fields, without any evidence of its own for those parts. | yes |
| E3 | it was put up in 1998 as a precaution, when the slope was first listed, and not because of finds or accidents. | yes |
| E4 | I did not see it laid. It was done before I arrived, and nobody had a map. | yes |
| E5 | In heavy monsoon rain the gully floods and carries soil and debris down from the slope to the stream. | yes |
| E6 | My family has farmed these paddy fields since 1996, with a permit. We plough every spring. Nothing has ever been found. | yes |
| E7 | The women said they plant and harvest in the paddy fields every season and have never seen anything suspicious | yes |
| E8 | The paddy fields lie on a terrace above the gully bed, and the gully drains into the stream, not across the fields. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | A | 6 | - | The unassessed historical list supports suspicion on the slope but neither confirms emplacement nor establishes absence through lack of recorded finds. |
| E2 | absence | B, C | 6 | E1 | The county record explains the administrative extension of the slope listing into B and C, but does not exclude an independently supported migration risk in B. |
| E3 | indirect | A | 2 | - | The observed precautionary fence reflects the existing suspicion rather than independently confirming contamination. |
| E4 | indirect | A | 7 | - | The former soldier's assertion suggests mining but is not eyewitness evidence and identifies no first-hand source for emplacement. |
| E5 | indirect | B | 2 | - | Observed drainage and corroborating farmer accounts establish a plausible migration pathway from the suspected slope into the gully, not confirmed ordnance. |
| E6 | absence | C | 4 | E2 | A farmer's first-hand account of repeated cultivation supports safe use of C for thirty years, not the unused slope or gully. |
| E7 | absence | C | 4 | E2 | The women's first-hand seasonal use independently corroborates safe use of the fields without supporting absence in A or B. |
| E8 | absence | C | 2 | E5 | Directly observed topography excludes the described gully run-off pathway into C, supporting a boundary distinct from B. |

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
- Rule topics looked up: reliability, national_criteria, evidence, cancellation, technical_survey, further_survey, all_reasonable_effort, hazard_areas

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - Human review and sign-off are required; release in the Civilian Control Zone requires defence authority approval.
  - Intrusive work in the protected habitat requires an environmental permit and suitable methods.
  - The team's whole-area cancellation recommendation and county request for farming release were assessed as case data, not adopted as instructions; environmental damage is not a cancellation basis.
  - The referenced defence records and photographs are not reproduced; verify supporting attachments and mapped boundaries at sign-off.
  - High confidence concerns the recommended next steps, not certainty that mines are present in A or B.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
