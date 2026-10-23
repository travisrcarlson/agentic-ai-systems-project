# Sign-off sheet: C14, run 3

Case: Border farmland, a legacy minefield and a strip near a recent clash site  
Area ID: THA-SHA-1402  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=CANCEL; B=CLEARANCE; C=FURTHER_NTS
- By part: A=CANCEL; B=CLEARANCE; C=FURTHER_NTS
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend split outcomes. Cancel A: the 2019 technical survey places the farmland outside the defined minefield, and 22 years of safe use, two separate first-hand community sources, the required men’s and women’s consultations, and the team’s field observations meet the national cancellation criteria and explain the old unbounded SHA record for A. Recommend clearance of B: mines are confirmed there by the 2019 technical survey and a precisely located 2012 mine accident, and the hazard is defined. Return C for further non-technical survey when security access permits; the team could not enter it, and the 2025 claims are conflicting and do not establish exact locations or responsibility.

General guidance on the situation:

> For any suspected explosive ordnance, keep people and animals away. Do not touch, move or try to destroy anything. Mark the place only if this can be done without going closer, and report it to the national mine action authority, survey team or police. Respect the military closure and do not enter C until access is authorized.

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
| E1 | indirect | all | 6 | - | An old, unassessed record based on second-hand reports supports suspicion but gives no reliable boundary. |
| E2 | direct | B | 3 | - | A technical survey report whose findings include confirmed mines provides reliable direct evidence in the defined minefield; the stated boundary places A outside it. |
| E3 | direct | B | 4 | - | A precisely located mine accident witnessed by the accompanying son directly confirms EO at the spot in B. |
| E4 | absence | A | 4 | E1 | A first-hand farmer reports 22 years of repeated tractor cultivation without finds or accidents in the farmland, meeting the national safe-use duration. |
| E5 | absence | A | 4 | E1 | Women report first-hand, repeated work and use across the fields and edges without suspicious finds, providing a separate consulted source of safe-use evidence. |
| E6 | indirect | C | 6 | - | Conflicting unverified government claims about mines near the border suggest possible hazard in the nearby strip, but exact places are not given and responsibility claims do not determine the outcome. |
| E7 | not_evidence | C | 2 | - | This establishes a security-related access gap and cessation of use, not whether EO is present or absent. |
| E8 | absence | A | 2 | E1 | The team's field observation found no items in A and confirms the mapped boundary markers remain in place, supporting the farmland distinction and explaining the old whole-area suspicion for A. |

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
- Rule topics looked up: evidence, reliability, cancellation, hazard_areas, outcomes, national_criteria, safety_guidance, case_file_text

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team recommended clearance of the whole area, including C, but this is evidence to assess rather than a decision; C was not surveyed and national criteria require it to be returned for survey when access allows.
  - The parties’ conflicting claims about who laid mines are recorded as claims and do not determine the outcome.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
