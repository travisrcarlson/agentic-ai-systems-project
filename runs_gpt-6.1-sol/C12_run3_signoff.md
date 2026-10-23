# Sign-off sheet: C12, run 3

Case: A slope below a former position in the Civilian Control Zone  
Area ID: KOR-SHA-1207  
Model: gpt-6.1-sol

## Recommendation
- Outcome: SPLIT: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY; C=CANCEL
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY; C=CANCEL
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend targeted technical survey of A and B, retaining them as suspected hazardous areas pending results, and cancellation of C subject to defence authority approval. A has unresolved indirect evidence from the unconfirmed listing, precautionary fencing and the former soldier's unverified account; none confirms ordnance. B has a credible monsoon run-off pathway from A despite its original inclusion by parcel boundary. Neither A nor B has safe-use evidence. C has 30 years of farming corroborated by two first-hand sources, exceeds the five-year criterion, and lies above and outside the gully drainage pathway. Men and women were consulted. Whole-area cancellation is not justified; protected habitat and lack of recorded finds do not resolve suspicion on unused land.

General guidance on the situation:

> Keep people and animals away from the suspected slope and gully and maintain existing access restrictions pending authorised decisions. Do not touch, move or try to destroy any suspicious item. Mark its location only if this can be done without going closer, and report it to the authorities. The recommendation does not itself authorise land release or expanded farming.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The military's list records the slope as an "unconfirmed minefield" | yes |
| E2 | The county drew the suspected area to the edges of the land parcel, taking in the gully and the paddy fields, without any evidence of its own for those parts. | yes |
| E3 | A fence with warning signs runs along the top and sides of the slope. | yes |
| E4 | I did not see it laid. It was done before I arrived, and nobody had a map. | yes |
| E5 | In heavy monsoon rain the gully floods and carries soil and debris down from the slope to the stream. | yes |
| E6 | My family has farmed these paddy fields since 1996, with a permit. We plough every spring. Nothing has ever been found. | yes |
| E7 | The women said they plant and harvest in the paddy fields every season and have never seen anything suspicious | yes |
| E8 | The paddy fields lie on a terrace above the gully bed, and the gully drains into the stream, not across the fields. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | A | 6 | - | The unassessed historical listing supports suspicion on the slope, not confirmed contamination; no recorded finds on unused land do not establish absence. |
| E2 | absence | B, C | 6 | E1 | The county record explains why the slope listing's mapped boundary included B and C without independent hazard evidence, but does not exclude other evidence of migration into B. |
| E3 | indirect | A | 2 | - | The observed fence reflects the existing suspicion only, since the record establishes its precautionary origin rather than finds or accidents. |
| E4 | indirect | A | 7 | - | The former soldier's claim suggests mining but neither personal observation nor an identifiable first-hand source supports it. |
| E5 | indirect | B | 2 | - | Observed drainage and farmers' reports provide a plausible movement pathway from suspected slope A into B, without confirming any ordnance. |
| E6 | absence | C | 4 | E2 | A farmer's first-hand account supports 30 years of safe productive use specifically in C, not the unused slope or gully. |
| E7 | absence | C | 4 | E2 | The women's first-hand seasonal work independently corroborates safe use in C without extending that evidence to A or B. |
| E8 | absence | C | 2 | E5 | Direct observation of terrain excludes the reported gully run-off pathway into the paddy fields, but does not exclude migration into B. |

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
- Rule topics looked up: reliability, national_criteria, evidence, cancellation, technical_survey, further_survey, hazard_areas, land_use

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - This is a recommendation for human review and sign-off, not a final release decision.
  - Defence authority approval is required before releasing C within the Civilian Control Zone.
  - Intrusive work in the protected habitat requires an environmental permit and appropriately selected methods; habitat protection is not grounds for cancellation.
  - The team's whole-area cancellation recommendation and the county's farming request are not supported for A or B.
  - The military listing's reliability is unassessed; the former soldier did not witness emplacement and identifies no first-hand source. No direct evidence confirms ordnance.
  - Referenced defence records and photographs are not reproduced in the file; verify these supporting attachments and the mapped part boundaries during sign-off.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
