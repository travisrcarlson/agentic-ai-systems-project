# Sign-off sheet: C12, run 2

Case: A slope below a former position in the Civilian Control Zone  
Area ID: KOR-SHA-1207  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY; C=CANCEL
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY; C=CANCEL
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend targeted technical survey for A and B: A remains a suspected hazardous area on the unconfirmed military listing, supported by the former soldier’s indirect account; the precautionary fence is not confirmation. B is unused and has no safe-use evidence, and the gully’s monsoon flow carries soil and debris from the slope, so potential hazard there is not resolved. Recommend cancellation of C: two first-hand sources report repeated farming without finds for 30 years, exceeding the five-year national threshold, and the gully drains away from rather than across the fields. The county’s parcel-edge extension does not establish a hazard in C. The coded decision check passed.

General guidance on the situation:

> Keep people and animals away from the fenced slope and the gully. If anything suspected to be explosive ordnance is encountered, do not touch, move or try to destroy it; mark the place only if this can be done without going closer, and report it to the authorities.

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
| E1 | indirect | A | 6 | - | The military's unassessed historical listing and history support suspicion on the slope but do not confirm that mines were laid. |
| E2 | absence | B, C | 6 | E1 | The county record documents that the gully and fields were included administratively, not on hazard evidence; it therefore removes any inference that the listing substantiates those parts. |
| E3 | indirect | A | 3 | - | The fence reflects the pre-existing suspicion on A, but the documented precautionary purpose means it does not independently confirm contamination. |
| E4 | indirect | A | 4 | - | The former soldier's service at the position is first-hand context, but he did not witness emplacement, so the account suggests rather than confirms mines on A. |
| E5 | indirect | B | 2 | - | Observed water and debris movement from the suspected slope may present a pathway of concern in B, but no EO is reported or observed. |
| E6 | absence | C | 4 | E5 | A first-hand farmer reports three decades of regular ploughing without finds, supporting safe use in C; it also bears against any assumed spread into the fields. |
| E7 | absence | C | 4 | E5 | Women who regularly use C independently report repeated safe seasonal use, while their non-use of A and B provides no evidence of absence there. |
| E8 | absence | C | 2 | E5 | The survey team's observation that drainage does not cross C limits the relevance of the gully's downstream debris pathway to the paddy fields. |

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
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, quality_control, safety_guidance, national_criteria, case_file_text

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation to cancel the whole area is evidence to assess, not a decision; it is not supported for A or B by the available evidence.
  - A and B are protected habitat. Any intrusive survey requires an environmental permit, and habitat constraints affect methods but do not justify cancellation.
  - Release of land in the Civilian Control Zone requires defence authority approval.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
