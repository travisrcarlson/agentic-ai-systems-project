# Sign-off sheet: C06, run 2

Case: The far margin of a border minefield's hazardous area  
Area ID: ZWE-CHA-0712-S4M  
Model: gpt-6-luna

## Recommendation
- Outcome: TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend targeted technical survey of part A before release. The existing national record places A inside a CHA, and national criteria do not allow cancellation by non-technical survey for land inside a CHA. Safe cultivation and community use, together with the survey team's observations and the neighbouring-sector clearance pattern, weigh against contamination at the far margin but do not establish its absence there; the neighbouring-sector findings are outside A. The survey team's cancellation recommendation is evidence to assess, not a decision to follow.

General guidance on the situation:

> Until the area is formally released, follow existing hazard warnings and keep people and animals away from the hazardous area. If an item or suspected hazard is encountered, do not touch, move or try to destroy it; report it to the authorities, and mark the place only if that can be done without going closer.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | the boundary of sector 4 includes the margin under review. | yes |
| E2 | all mines were found in a narrow belt along the line of the old fence; none were found in the outer parts of those sectors. | yes |
| E3 | the margin lies beyond the belt in which mines were found in the neighbouring sectors. | yes |
| E4 | I have grown maize on this land every year since 2012, with oxen and a plough. Nothing has happened. | yes |
| E5 | they know of no accident or find in it. | yes |
| E6 | no items, signs or posts in the margin itself. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | A | 6 | - | The unsubstantiated historical CHA boundary suggests possible hazard in A, but the row does not state that EO was directly found there. |
| E2 | direct | outside | 3 | - | Clearance reports establish EO presence in the neighboring sectors, outside this review area; they do not establish presence or absence in A. |
| E3 | absence | A | 3 | E1 | This desk comparison supports absence in A by placing it beyond the belt found in neighboring sectors, but does not prove no hazard in A. |
| E4 | absence | A | 4 | E1 | The farmer's first-hand account of repeated cultivation without incident supports safe use over time in A. |
| E5 | absence | A | 4 | E1 | The women report their own repeated use and no known accident or find, supporting but not proving absence in A. |
| E6 | absence | A | 2 | E1 | The survey team's direct observation found no indicators in A; the old fence posts observed were well away from the margin. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: evidence, reliability, hazard_areas, cancellation, technical_survey, land_use, national_criteria, further_survey, outcomes

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - National criteria require technical survey or clearance to release land inside a CHA; non-technical cancellation is not provided for.
  - E2 describes clearance results in neighboring sectors, outside A, and does not establish the condition of A.
  - The survey team's recommendation to cancel does not override national criteria or the evidence assessment.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
