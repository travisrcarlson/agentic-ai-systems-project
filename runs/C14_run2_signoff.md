# Sign-off sheet: C14, run 2

Case: Border farmland, a legacy minefield and a strip near a recent clash site  
Area ID: THA-SHA-1402  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=CANCEL; B=CLEARANCE; C=FURTHER_NTS
- By part: A=CANCEL; B=CLEARANCE; C=FURTHER_NTS
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend split release. Cancel A: the 2019 technical-survey boundary places the farmland outside the minefield, and 22 years of annual use without finds is supported by two first-hand sources and the survey team's observations; required men’s and women’s consultations were completed. Clear B: the minefield is confirmed and its boundary was defined, with a located witnessed mine casualty providing direct evidence; national criteria permit clearance without further technical survey where direct evidence defines the hazard. Return C for further non-technical survey when security access allows: the team could not enter, and conflicting, unverified reports do not define hazard location or extent. Decision check passed.

General guidance on the situation:

> Keep people and animals away from the marked minefield and the military-closed ridge-road strip. Do not touch, move or try to destroy any suspected item. Mark its location only if this can be done without approaching it, and report it to the authorities.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The 2001 impact survey recorded the whole area as suspected, from villagers' reports of a minefield at the foot of the ridge; it gives no boundary. | yes |
| E2 | the report places the farmland outside that edge. | yes |
| E3 | A farmer was injured by a mine at the foot of the ridge in 2012, at a spot that his son, who was with him, showed the team. | yes |
| E4 | I have grown cassava on this land every year since 2004. We plough it with a tractor, and nothing has ever been found. | yes |
| E5 | The women said they plant, weed and harvest the fields every season and collect firewood along the field edges, and have never seen anything suspicious. | yes |
| E6 | The national authorities reported that soldiers were injured by mines near the border in 2025, and attributed the mines to new laying by the neighbouring country's forces. The neighbouring government denied laying new mines and said the explosions were in old minefields. No independent fact-finding had confirmed either account by the time of the survey. | yes |
| E7 | The military closed the ridge road and the strip along it after the 2025 clashes; the team could not enter, and villagers have not used the strip since. | yes |
| E8 | The team walked the field edges and the marked edge of the minefield, and saw no items in the farmland; the posts and signs of 2019 are in place. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | all | 6 | - | A historical survey record based on second-hand reports and without a defined boundary suggests possible hazard but is not confirmation. |
| E2 | absence | A | 3 | E1 | A documented technical survey defined the minefield edge and places farmland A outside it, correcting the old undifferentiated suspicion for A. |
| E3 | direct | B | 4 | - | A witnessed casualty at a located spot confirms mine presence within the known minefield in B. |
| E4 | absence | A | 4 | - | The farmer's first-hand account of sustained annual cultivation and tractor ploughing without finds supports safe use in A. |
| E5 | absence | A | 4 | - | Multiple women report first-hand seasonal activity in A without suspicious finds, providing an independent safe-use source. |
| E6 | indirect | C | 6 | - | Conflicting unverified governmental accounts and unspecified incident locations suggest possible hazard near C but do not establish its exact extent or origin. |
| E7 | not_evidence | C | 4 | - | Closure and non-use due to restricted access do not establish either presence or absence of explosive ordnance; they explain why C was not surveyed. |
| E8 | absence | A | 2 | - | The survey team directly observed no items in the accessible farmland and verified the marked boundary, supporting absence of evidence in A. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R6 | all | pass | Every part is decided once. |
| R7 | all | pass | Every evidence-log item is in the register. |
| R1 | A | pass | Every item of direct or indirect evidence is explained by evidence of absence. |
| R3 | A | pass | The national criteria for cancellation are met. |
| R2 | B | pass | Direct evidence of class 1-4 in part B: E3. |
| R5 | B | pass | The national criteria allow clearance where direct evidence defines the hazard. |
| - | C | pass | Further non-technical survey is always open to the reviewer. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, cancellation, technical_survey, further_survey, all_reasonable_effort, outcomes, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - Part C was not surveyed because the military restricts access; keep it recorded as not surveyed and revisit when access permits.
  - The survey team's recommendation to clear the whole area is not adopted as a decision: its blanket recommendation does not account for the documented safe-use and boundary evidence for A or the inaccessible status of C.
  - The claims about who laid mines near the border are conflicting and unconfirmed; they are recorded with their sources and do not determine the outcome.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
