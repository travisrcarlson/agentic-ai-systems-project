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

> Recommend technical survey for A because the unconfirmed minefield listing and former soldier's account leave a credible, unresolved suspicion; the precautionary fence is not proof of contamination. Recommend technical survey for B because it has no safe-use history and monsoon runoff carries soil and debris from A into it. Recommend cancellation of C: 30 years of permitted, recurring farming without finds is supported by two first-hand sources, and the fields are above the gully and drain away from it. This split corrects the parcel-based extension of the SHA while retaining the unresolved areas for survey. Rule check passed.

General guidance on the situation:

> Until the competent authority changes the status of the relevant land, keep people and animals away from the fenced slope and gully. Do not touch, move or try to destroy any suspected item; report anything suspicious to the authorities. Mark a location only if this can be done without going closer.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The military's list records the slope as an "unconfirmed minefield": the position above it was manned from the 1970s to the 1990s, and no emplacement record is held. No finds, accidents or clearance are recorded. | yes |
| E2 | The county drew the suspected area to the edges of the land parcel, taking in the gully and the paddy fields, without any evidence of its own for those parts. | yes |
| E3 | A fence with warning signs runs along the top and sides of the slope. The defence authority's record says it was put up in 1998 as a precaution, when the slope was first listed, and not because of finds or accidents. | yes |
| E4 | "The perimeter of the position was mined; that was standard then. I did not see it laid. It was done before I arrived, and nobody had a map." | yes |
| E5 | In heavy monsoon rain the gully floods and carries soil and debris down from the slope to the stream. The farmers keep out of the gully. | yes |
| E6 | "My family has farmed these paddy fields since 1996, with a permit. We plough every spring. Nothing has ever been found." | yes |
| E7 | The women said they plant and harvest in the paddy fields every season and have never seen anything suspicious; they do not go into the gully or onto the slope. | yes |
| E8 | The paddy fields lie on a terrace above the gully bed, and the gully drains into the stream, not across the fields. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | A | 6 | - | An unassessed military listing and historical military presence indicate possible contamination on the slope but do not verify emplacement. |
| E2 | absence | B, C | 4 | E1 | The county record confirms the extension into B and C was an administrative boundary choice, not separate evidence of contamination there. |
| E3 | indirect | A | 2 | - | The observed precautionary fence reflects the existing suspicion but was not installed because of finds or accidents, so it does not confirm contamination. |
| E4 | indirect | A | 5 | - | The former soldier offers an unverified account based on asserted standard practice and explicitly did not witness laying. |
| E5 | indirect | B | 2 | - | Observed and reported runoff from the potentially hazardous slope makes possible transfer into the gully, which has no safe-use history. |
| E6 | absence | C | 4 | E1, E2, E5 | A farmer with long first-hand experience reports annual ploughing without finds, supporting safe use in C and undermining hazard extrapolation there. |
| E7 | absence | C | 4 | E1, E2, E5 | First-hand seasonal use by women independently supports safe use in C, while their account does not bear on A or B. |
| E8 | absence | C | 2 | E5 | Survey observation indicates runoff and debris from B drain away from C, limiting the relevance of the gully transport concern to the fields. |

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
- Rule topics looked up: evidence, reliability, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, safety_guidance, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation to cancel the whole area is not supported for A and B by the evidence reviewed; a team's recommendation is not itself a decision.
  - Any release in the Civilian Control Zone requires defence authority approval.
  - Intrusive survey in the protected habitat requires an environmental permit; habitat constraints do not by themselves justify cancellation.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
