# Sign-off sheet: C06, run 1

Case: The far margin of a border minefield's hazardous area  
Area ID: ZWE-CHA-0712-S4M  
Model: gpt-6-luna

## Recommendation
- Outcome: TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend targeted technical survey for part A. The broad 2016 CHA record is indirect and the neighboring-sector clearance pattern, 14 years of reported cultivation and footpath use, and the team's absence of signs in the margin all weigh against contamination there. However, the national criteria do not permit cancellation of land inside a CHA by non-technical survey, and the evidence does not establish the recorded area is wrong or duplicate. Technical survey is therefore needed to verify and define the margin before release; it passed the rule check as targetable from E1 and E3.

General guidance on the situation:

> Until the area is formally released, keep people and animals away from it. Do not touch, move or try to destroy any suspected item; report it to the authorities, and mark the place only if this can be done without approaching it.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The 2016 re-survey drew the CHA as a wide band along the border minefield and divided it into sectors; the boundary of sector 4 includes the margin under review. | yes |
| E2 | In the cleared sectors 2 and 3, all mines were found in a narrow belt along the line of the old fence; none were found in the outer parts of those sectors. | yes |
| E3 | Compared with the clearance records, the margin lies beyond the belt in which mines were found in the neighbouring sectors. | yes |
| E4 | "I have grown maize on this land every year since 2012, with oxen and a plough. Nothing has happened." | yes |
| E5 | The women said they collect firewood along the margin and walk through it to the river; they know of no accident or find in it. | yes |
| E6 | The team saw old fence posts along the minefield line inside sector 4, well away from the margin, and no items, signs or posts in the margin itself. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | A | 6 | - | This is an unvalidated historical area record that places the margin within a broadly drawn CHA but does not itself confirm EO in the margin. |
| E2 | indirect | outside | 3 | - | Reliable clearance records in neighboring sectors suggest a narrow-belt pattern but are not evidence of EO presence or absence in this area. |
| E3 | indirect | A | 3 | - | A desk inference from validated neighboring clearance records indicates lower likelihood in A but does not rule out contamination there. |
| E4 | absence | A | 4 | E1 | The farmer gives first-hand evidence of sustained yearly cultivation without a known find or accident, countering the broad CHA inclusion. |
| E5 | absence | A | 4 | E1 | Women report repeated personal use and no known incident or find in A, countering the broad recorded boundary. |
| E6 | absence | A | 2 | E1 | The team's direct observation found no signs in A and located the old fence-line indicators away from it; this supports absence in A but does not by itself establish the true hazard boundary. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E3. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: evidence, reliability, cancellation, land_use, technical_survey, further_survey, all_reasonable_effort, outcomes, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team recommended cancellation, but that recommendation is evidence to assess, not a decision; national criteria do not provide for cancellation by non-technical survey within a CHA.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
