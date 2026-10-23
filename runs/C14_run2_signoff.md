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

> Recommend splitting the area: cancel A by non-technical survey because 22 years of intensive safe use, two first-hand sources from separately consulted men and women, the reliable 2019 survey boundary placing the farmland outside the minefield, and the team’s observations meet the national cancellation criteria. Recommend clearance of B: mines are confirmed there, the 2019 technical survey defined and marked the minefield, and the national criteria allow clearance where direct evidence defines the hazard. Return C for further non-technical survey when security access allows; it was not visited, and the reported 2025 incidents are disputed and not precisely located, so its status cannot be determined from this survey.

General guidance on the situation:

> Keep people and animals away from the marked minefield and the inaccessible ridge-road strip. Do not touch, move or try to destroy anything suspicious. Mark a place only if that can be done without going closer, and report it to the national mine action authority or police.

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
| E1 | indirect | all | 6 | - | An unassessed historical record based on unspecified village reports suggests possible hazard, but identifies no boundary. |
| E2 | absence | A | 3 | E1 | The reliable technical-survey boundary places farmland A beyond the previously vague whole-area suspicion. |
| E3 | direct | B | 4 | - | A witnessed accident at a known spot is direct evidence of a mine in B. |
| E4 | absence | A | 4 | E1 | The farmer gives first-hand evidence of intensive annual use over 22 years without finds on A. |
| E5 | absence | A | 4 | E1 | Women provide separate first-hand accounts of repeated seasonal use and no suspicious finds in A. |
| E6 | indirect | C | 6 | - | Conflicting unverified government accounts of mine incidents near the border suggest possible hazard in the nearby strip, but give no precise locations or confirmed attribution. |
| E7 | not_evidence | C | 4 | - | The closure and resulting lack of use explain why C was inaccessible but do not establish either presence or absence of EO. |
| E8 | absence | A | 2 | E1 | The team saw no items in A during field-edge observation, complementing the safe-use evidence; the signs concern the already confirmed adjacent minefield. |

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
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, quality_control, safety_guidance, case_file_text, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation to clear the whole area, including C, is evidence to review and not a decision; C was not reached and national criteria require security-inaccessible areas to be recorded as not surveyed and returned when access permits.
  - The conflicting government statements about the 2025 incidents and attribution are unconfirmed; retain them with their sources and do not treat attribution as deciding the outcome.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
