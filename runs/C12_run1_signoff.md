# Sign-off sheet: C12, run 1

Case: A slope below a former position in the Civilian Control Zone  
Area ID: KOR-SHA-1207  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY; C=CANCEL
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY; C=CANCEL
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend targeted technical survey for A, supported by the unconfirmed military minefield listing and the former soldier’s indirect account. B merits separate technical survey because observed monsoon runoff connects it to the suspected slope, although no EO is confirmed. Recommend cancellation of C: it has 30 years of permitted seasonal farming and ploughing without finds, two firsthand sources including women, and observed terrain and drainage show runoff does not cross the fields. Obtain defence authority approval for cancellation in the Civilian Control Zone; survey or intrusive work in protected habitat requires the applicable environmental permit.

General guidance on the situation:

> Keep people and animals away from the fenced slope and gully. Do not touch, move or try to destroy any suspected item; mark a place only if this can be done without going closer, and report it to the authorities.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The military's list records the slope as an "unconfirmed minefield" | yes |
| E2 | taking in the gully and the paddy fields, without any evidence of its own for those parts. | yes |
| E3 | it was put up in 1998 as a precaution, when the slope was first listed, and not because of finds or accidents. | yes |
| E4 | The perimeter of the position was mined; that was standard then. I did not see it laid. | yes |
| E5 | In heavy monsoon rain the gully floods and carries soil and debris down from the slope to the stream. | yes |
| E6 | We plough every spring. Nothing has ever been found. | yes |
| E7 | they plant and harvest in the paddy fields every season and have never seen anything suspicious; they do not go into the gully or onto the slope. | yes |
| E8 | The paddy fields lie on a terrace above the gully bed, and the gully drains into the stream, not across the fields. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | A | 6 | - | The unassessed military list and historical position create suspicion but do not confirm mines. |
| E2 | absence | B, C | 6 | E1 | This county record shows the mapped extension into B and C was a parcel-boundary choice, not evidence-based; E1 only identifies the slope. |
| E3 | not_evidence | A | 3 | - | The fence was precautionary and adds no independent evidence of contamination beyond the underlying suspicion. |
| E4 | indirect | A | 4 | - | A former soldier's report suggests possible mining but he did not witness laying and has no map. |
| E5 | indirect | B | 2 | - | Observed runoff links B to the suspected slope and suggests possible movement into the gully, without confirming EO. |
| E6 | absence | C | 4 | - | The farmer's firsthand report of repeated ploughing since 1996 without finds supports safe use in C. |
| E7 | absence | C | 4 | - | Women who use C report seasonal activity without suspicious finds; their account does not bear on A or B. |
| E8 | absence | C | 2 | E5 | The team's observed drainage and terrace explain why the runoff evidence in E5 does not indicate transport into C. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R6 | all | pass | Every part is decided once. |
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E4. |
| R4 | B | pass | Evidence to target in part B: E5. |
| R1 | C | pass | Every item of direct or indirect evidence is explained by evidence of absence. |
| R3 | C | pass | The national criteria for cancellation are met. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, cancellation, technical_survey, further_survey, all_reasonable_effort, outcomes, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The team’s recommendation to cancel the whole area and the county’s request for whole-area release are not decisions and are not supported for A and B by the evidence reviewed.
  - Protected habitat may constrain survey methods but is not a reason to cancel A or B; obtain an environmental permit before intrusive work.
  - Cancellation of C remains subject to defence authority approval.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
