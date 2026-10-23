# Sign-off sheet: C14, run 2

Case: Border farmland, a legacy minefield and a strip near a recent clash site  
Area ID: THA-SHA-1402  
Model: gpt-6.1-sol

## Recommendation
- Outcome: SPLIT: A=CANCEL; B=CLEARANCE; C=FURTHER_NTS
- By part: A=CANCEL; B=CLEARANCE; C=FURTHER_NTS
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend a split for human sign-off. A: cancel the legacy suspicion through NTS; 22 years of tractor cultivation and seasonal field work, corroborated by two first-hand sources, consultation with men and women, field observations and the 2019 boundary meet national cancellation criteria and explain the original unbounded record. B: recommend clearance within the technical-survey-defined minefield; the 2019 findings and accurately located 2012 accident are direct evidence. C: record as not surveyed and return for further NTS when security access permits; imprecise, disputed reports cannot define a clearance task. Do not adopt the team's whole-area clearance recommendation.

General guidance on the situation:

> Keep people and animals away from the marked minefield, the closed ridge-road strip and any suspicious item. Respect closures and existing warning signs. Do not touch, move or try to destroy anything suspicious. Mark a suspected location only if this can be done without going closer, and report it to the authorities.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The 2001 impact survey recorded the whole area as suspected, from villagers' reports of a minefield at the foot of the ridge; it gives no boundary. | yes |
| E2 | Technical survey in 2019 found mines at the foot of the ridge, defined the edge of the minefield, and marked it with posts and signs; the report places the farmland outside that edge. | yes |
| E3 | A farmer was injured by a mine at the foot of the ridge in 2012, at a spot that his son, who was with him, showed the team. | yes |
| E4 | I have grown cassava on this land every year since 2004. We plough it with a tractor, and nothing has ever been found. | yes |
| E5 | The women said they plant, weed and harvest the fields every season and collect firewood along the field edges, and have never seen anything suspicious. | yes |
| E6 | No independent fact-finding had confirmed either account by the time of the survey. | yes |
| E7 | The military closed the ridge road and the strip along it after the 2025 clashes; the team could not enter, and villagers have not used the strip since. | yes |
| E8 | The team walked the field edges and the marked edge of the minefield, and saw no items in the farmland; the posts and signs of 2019 are in place. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | A, B, C | 6 | - | The original unbounded suspicion is an historical report whose whole-area extent was not verified. |
| E2 | direct | B | 3 | - | The technical survey reliably confirms and bounds the minefield in B, while explicitly placing A outside its edge. |
| E3 | direct | B | 4 | - | An eyewitness locates the recorded mine accident at a known spot within B. |
| E4 | absence | A | 4 | E1 | The working farmer's first-hand account of 22 years of intensive safe farming supports removal of the original broad suspicion from A. |
| E5 | absence | A | 4 | E1 | Women who work the fields provide independent first-hand corroboration of safe use in A, including its edges. |
| E6 | indirect | C | 5 | - | Press-reported official accounts suggest a hazard near C but give no exact accident locations or independent confirmation and do not establish responsibility or new laying. |
| E7 | not_evidence | C | 4 | - | The security closure establishes an access and survey gap, not proof of contamination or safe use. |
| E8 | absence | A | 2 | E1 | The team's field-edge observations support the absence case for A without proving it alone; surviving minefield marking also corroborates the established boundary of B. |

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
- Rule topics looked up: reliability, national_criteria, cancellation, further_survey, clearance, evidence, all_reasonable_effort, land_use

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - Recommendation only; the authorized person must check and sign off.
  - C was inaccessible for security reasons: retain an explicit not-surveyed status and arrange renewed survey when access allows.
  - Claims about new mine laying and responsibility are disputed, attributed reports, not established findings; they must not decide the outcome.
  - The survey team's recommendation to clear the whole area is not supported for A or C.
  - The 2019 technical survey sketch and photographs are listed but not reproduced; verify the original boundary documentation before implementing the split.
  - Confidence is high in the recommended process and split, not in the nature, extent or attribution of any contamination in C.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
