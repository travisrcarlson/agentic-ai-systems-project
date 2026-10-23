# Sign-off sheet: C14, run 3

Case: Border farmland, a legacy minefield and a strip near a recent clash site  
Area ID: THA-SHA-1402  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=CANCEL; B=CLEARANCE; C=FURTHER_NTS
- By part: A=CANCEL; B=CLEARANCE; C=FURTHER_NTS
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend splitting the area. Cancel A by non-technical survey: 22 years of annual tractor cultivation with no finds, corroborated by women's first-hand seasonal use and the team's observations; the 2019 technical survey places A outside the defined minefield, and required male and female groups were consulted. Recommend clearance for confirmed minefield B: technical survey and a precisely located casualty provide direct evidence, with the minefield edge defined and marked. Return C for further non-technical survey when security access allows; the team did not enter it, and the conflicting 2025 claims do not establish contamination or its extent. The survey team's recommendation to clear the whole area is considered but not followed as a blanket recommendation.

General guidance on the situation:

> Keep people and animals away from the marked minefield and the inaccessible ridge-road strip. Do not touch, move or try to destroy anything; mark any suspected place only if this can be done without going closer, and report it to the authorities. Follow local authority restrictions and do not enter C until access is formally permitted and it has been surveyed.

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
| E1 | indirect | all | 4 | - | A dated, second-hand suspicion with no defined boundary suggests possible hazard but is superseded in relevant parts by better location evidence. |
| E2 | direct | B | 2 | - | A technical survey directly confirmed mines in B and documented the minefield edge; farmland outside the edge is separately supported as absence evidence by safe use and observations. |
| E3 | direct | B | 2 | - | A recorded casualty and accompanying eyewitness identify a specific mine incident in the confirmed minefield. |
| E4 | absence | A | 2 | E1 | The farmer's first-hand account of repeated tractor cultivation with no finds supports absence in A and rebuts the unbounded old suspicion there. |
| E5 | absence | A | 2 | E1 | Separate first-hand accounts of repeated use and no suspicious finds support absence in A and rebut the unbounded old suspicion there. |
| E6 | indirect | C | 5 | - | Conflicting unverified government accounts suggest possible hazard near C but do not establish precise locations or provenance. |
| E7 | not_evidence | C | 3 | - | Closure and lack of access mean C is unsurveyed; non-use since closure is not evidence that it is safe or hazardous. |
| E8 | absence | A | 2 | E1 | Survey observations support absence in the farmland and confirm the established boundary, but do not negate the confirmed hazard in B. |

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
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, quality_control, safety_guidance, case_file_text, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - Part C was not visited because of military security restrictions; under the national criteria it is not surveyed and must be revisited when access allows.
  - The survey team's recommendation to clear the whole area, including C, is evidence to assess and not a decision; it is not supported as a single outcome for all parts.
  - Claims about who laid mines in 2025 remain disputed and unverified; retain attribution to each government and do not treat attribution as deciding the outcome.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
