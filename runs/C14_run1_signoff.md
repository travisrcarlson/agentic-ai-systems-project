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

> Recommend split release. Cancel A: it lies outside the minefield boundary defined by the 2019 technical survey, and the farmer and women provide separate first-hand accounts of 22 years of safe, intensive use, meeting the national cancellation criteria and addressing the broad 2001 suspicion for this part. Recommend clearance of B: mines were confirmed there, its boundary was defined, and national criteria allow clearance without another technical survey where direct evidence defines the hazard. Return C for further non-technical survey when access is permitted; the team could not reach it, while conflicting 2025 reports suggest possible hazard but give no exact locations. Do not infer absence from its non-use or inaccessibility.

General guidance on the situation:

> Keep people and animals away from the marked minefield and the military-closed ridge-road strip. Do not touch, move or try to destroy any suspected item. Mark a place only if this can be done without going closer, and report it to the authorities. Use A only in accordance with the authority's signed-off release decision.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The 2001 impact survey recorded the whole area as suspected, from villagers' reports of a minefield at the foot of the ridge; it gives no boundary. | yes |
| E2 | Technical survey in 2019 found mines at the foot of the ridge, defined the edge of the minefield, and marked it with posts and signs; the report places the farmland outside that edge. | yes |
| E3 | A farmer was injured by a mine at the foot of the ridge in 2012, at a spot that his son, who was with him, showed the team. | yes |
| E4 | I have grown cassava on this land every year since 2004. We plough it with a tractor, and nothing has ever been found. | yes |
| E5 | The women said they plant, weed and harvest the fields every season and collect firewood along the field edges, and have never seen anything suspicious. | yes |
| E6 | The national authorities reported that soldiers were injured by mines near the border in 2025, and attributed the mines to new laying by the neighbouring country's forces. The neighbouring government denied laying new mines and said the explosions were in old minefields. No independent fact-finding had confirmed either account by the time of the survey. | yes |
| E7 | The military closed the ridge road and the strip along it after the 2025 clashes; the team could not enter, and villagers have not used the strip since. | yes |
| E8 | The team walked the field edges and the marked edge of the minefield, and saw no items in the farmland; the posts and signs of 2019 are in place. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | all | 6 | - | An old, unbounded record based on reported information suggests possible contamination but does not confirm it or locate it precisely. |
| E2 | direct | B | 3 | - | The recorded technical survey findings confirm and delineate the minefield in B; the bounded report also places A outside the edge. |
| E3 | direct | B | 4 | - | A witnessed casualty at a precisely identified location confirms a mine in the minefield part. |
| E4 | absence | A | 4 | E1 | The farmer's first-hand account of intensive, repeated safe use for 22 years supports cancellation of A and rebuts the broad legacy suspicion there. |
| E5 | absence | A | 4 | E1 | Multiple first-hand women report seasonal use and no suspicious finds, providing a separate source of safe-use evidence for A. |
| E6 | indirect | C | 6 | - | Conflicting, unverified government claims about mine explosions near the border suggest possible hazard in the recent-clash vicinity, but exact locations and attribution are unconfirmed. |
| E7 | not_evidence | C | 4 | - | The closure establishes that C was inaccessible and not used, but does not itself confirm or refute explosive ordnance. |
| E8 | direct | B | 2 | - | The team observed the minefield's established posts and signs still in place, supporting the delineated direct evidence for B; the absence of visible items during edge walking does not establish absence of buried EO in A. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R6 | all | pass | Every part is decided once. |
| R7 | all | pass | Every evidence-log item is in the register. |
| R1 | A | pass | Every item of direct or indirect evidence is explained by evidence of absence. |
| R3 | A | pass | The national criteria for cancellation are met. |
| R2 | B | pass | Direct evidence of class 1-4 in part B: E2, E3, E8. |
| R5 | B | pass | The national criteria allow clearance where direct evidence defines the hazard. |
| - | C | pass | Further non-technical survey is always open to the reviewer. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: evidence, reliability, hazard_areas, cancellation, land_use, further_survey, outcomes, all_reasonable_effort, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - Part C was not surveyed because of military security restrictions; national criteria require it to be recorded as not surveyed and returned when access allows.
  - The 2025 claims about who laid mines are disputed and unverified; record the claims with their sources and do not treat attribution as deciding the outcome.
  - The survey team's recommendation to clear the whole area is evidence for review, not a decision; this recommendation differs for A and C based on the evidence and national criteria.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
