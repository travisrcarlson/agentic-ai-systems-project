# Sign-off sheet: C14, run 1

Case: Border farmland, a legacy minefield and a strip near a recent clash site  
Area ID: THA-SHA-1402  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=CANCEL; B=CLEARANCE; C=FURTHER_NTS
- By part: A=CANCEL; B=CLEARANCE; C=FURTHER_NTS
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend split release. Cancel A: the 2019 technical-survey boundary places the farmland outside the confirmed minefield, and 22 years of tractor-ploughed farming without finds, supported by first-hand accounts from a farmer and women who use the fields, plus the team's observation, meets the national cancellation criteria and addresses the broad 2001 record. Recommend clearance of B: technical survey and a location-specific witnessed casualty confirm and define the minefield; national criteria allow clearance without further technical survey where direct evidence defines the hazard. Return C for further non-technical survey when security access allows: it was not visited, and the conflicting, unverified reports do not establish exact locations or attribution. The outcome passed the rule check.

General guidance on the situation:

> Keep people and animals away from the marked minefield and the closed ridge-road strip. Do not touch, move or try to destroy any suspected item. Mark a place only if this can be done without going closer, and report concerns to the national mine action authority, survey team or police. Continue to respect the existing minefield markings and military access restrictions.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The 2001 impact survey recorded the whole area as suspected, from villagers' reports of a minefield at the foot of the ridge; it gives no boundary. | yes |
| E2 | Technical survey in 2019 found mines at the foot of the ridge, defined the edge of the minefield, and marked it with posts and signs; the report places the farmland outside that edge. | yes |
| E3 | A farmer was injured by a mine at the foot of the ridge in 2012, at a spot that his son, who was with him, showed the team. | yes |
| E4 | "I have grown cassava on this land every year since 2004. We plough it with a tractor, and nothing has ever been found." | yes |
| E5 | The women said they plant, weed and harvest the fields every season and collect firewood along the field edges, and have never seen anything suspicious. | yes |
| E6 | The national authorities reported that soldiers were injured by mines near the border in 2025, and attributed the mines to new laying by the neighbouring country's forces. The neighbouring government denied laying new mines and said the explosions were in old minefields. No independent fact-finding had confirmed either account by the time of the survey. | yes |
| E7 | The military closed the ridge road and the strip along it after the 2025 clashes; the team could not enter, and villagers have not used the strip since. | yes |
| E8 | The team walked the field edges and the marked edge of the minefield, and saw no items in the farmland; the posts and signs of 2019 are in place. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | all | 6 | - | An unbounded historical record based on reported suspicion suggests hazard but does not establish its location. |
| E2 | direct | B | 3 | - | The reliable technical survey directly confirmed and delineated a minefield in B; its boundary places A outside that defined hazard. |
| E3 | direct | B | 4 | - | A witnessed accident at a location shown to the team confirms EO in B. |
| E4 | absence | A | 4 | E1 | The farmer's first-hand report of intensive recurring use without finds supports absence in A and addresses the earlier unbounded suspicion. |
| E5 | absence | A | 4 | E1 | First-hand seasonal activity and no suspicious finds by women who use A supports absence there and addresses the unbounded 2001 suspicion. |
| E6 | indirect | C | 6 | - | Conflicting, unverified government claims of mines near the border suggest possible hazard in C, but exact locations and attribution are unconfirmed. |
| E7 | not_evidence | C | 2 | - | Closure and lack of use explain why the strip was not visited, but neither establishes presence nor absence of EO. |
| E8 | absence | A | 2 | E1 | The team's observation of the farmland supports absence in A and is consistent with the marked boundary, addressing the earlier broad suspicion. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R6 | all | pass | Every part is decided once. |
| R7 | all | pass | Every evidence-log item is in the register. |
| R1 | A | pass | Every item of direct or indirect evidence is explained by evidence of absence. |
| R3 | A | pass | The national criteria for cancellation are met. |
| R2 | B | pass | Direct evidence of class 1-4 in part B: E2, E3. |
| R5 | B | pass | The national criteria allow clearance where direct evidence defines the hazard. |
| - | C | pass | Further non-technical survey is always open to the reviewer. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: evidence, reliability, hazard_areas, land_use, cancellation, outcomes, national_criteria, further_survey, all_reasonable_effort, case_file_text, technical_survey, clearance, quality_control, safety_guidance

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation to clear the whole area was reviewed, not followed as a decision: A has evidence supporting cancellation, B is confirmed, and C was inaccessible and must be revisited when access allows.
  - The claims about who laid mines near the border remain conflicting and unverified; record them with their sources and do not treat attribution as deciding the outcome.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
