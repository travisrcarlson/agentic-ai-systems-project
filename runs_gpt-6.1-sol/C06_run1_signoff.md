# Sign-off sheet: C06, run 1

Case: The far margin of a border minefield's hazardous area  
Area ID: ZWE-CHA-0712-S4M  
Model: gpt-6.1-sol

## Recommendation
- Outcome: TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend targeted technical survey of Part A for human sign-off. Fourteen years of reported safe cultivation, corroborating community use, and the narrow contamination belt found in neighbouring cleared sectors support reassessing the broad CHA boundary. They do not establish that this uncleared margin is free of mines. National rules do not permit cancellation of land inside a CHA through non-technical survey, so the team's cancellation recommendation cannot be accepted. Technical survey should test the assessed boundary and determine whether reduction is justified or clearance is needed; direct evidence does not currently define a hazard within A.

General guidance on the situation:

> Pending authorised review and release, do not treat the margin as confirmed safe. Keep people and animals away from suspected hazardous places. Do not touch, move or try to destroy any suspicious item; mark its location only if this can be done without going closer, and report it to the authorities.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | the boundary of sector 4 includes the margin under review. | yes |
| E2 | all mines were found in a narrow belt along the line of the old fence; none were found in the outer parts of those sectors. | yes |
| E3 | the margin lies beyond the belt in which mines were found in the neighbouring sectors. | yes |
| E4 | I have grown maize on this land every year since 2012, with oxen and a plough. Nothing has happened. | yes |
| E5 | they collect firewood along the margin and walk through it to the river; they know of no accident or find in it. | yes |
| E6 | The team saw old fence posts along the minefield line inside sector 4, well away from the margin, and no items, signs or posts in the margin itself. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | A | 6 | - | The broad historical CHA boundary suggests possible contamination in A but has not been validated by direct findings in that margin. |
| E2 | absence | outside | 3 | E1 | Clearance findings establish absence in neighbouring outer sectors and qualify the broad boundary inference in E1, without establishing absence in A. |
| E3 | absence | A | 3 | E1 | The assessment based on actual neighbouring clearance findings weakens the broad-boundary inference for A but remains an extrapolation to an uncleared sector. |
| E4 | absence | A | 4 | E1 | The farmer's first-hand account of fourteen years of safe cultivation supports absence in A but does not prove it is free of mines. |
| E5 | absence | A | 4 | E1 | The women's first-hand use and lack of known finds or accidents corroborate safe use of the margin without ruling out contamination. |
| E6 | direct | outside | 2 | - | Observed fencing associated with the known minefield is direct evidence outside A; the lack of visible indicators in A is supportive but does not establish absence there. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: national_criteria, reliability, evidence, technical_survey, cancellation, land_use, all_reasonable_effort, outcomes

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation to cancel conflicts with the case's national rules for release of land inside a CHA.
  - Neighbouring clearance results are informative but cannot establish the contamination boundary within uncleared sector 4.
  - Referenced sector plans, completion reports and photographs are not reproduced in the supplied file; verify them when planning technical survey.
  - High confidence concerns the recommended next step, not a conclusion that Part A is safe.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
