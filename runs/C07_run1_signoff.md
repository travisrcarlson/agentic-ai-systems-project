# Sign-off sheet: C07, run 1

Case: A road and river crossing by a former military position  
Area ID: AGO-SHA-4408  
Model: gpt-6-luna

## Recommendation
- Outcome: CLEARANCE
- By part: A=CLEARANCE; B=CLEARANCE
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend clearance of both parts A and B. First-hand accounts describe mines laid across the road approach and riverbanks (E1), with a located animal explosion on A (E3) and a witnessed explosion on B (E4). These are direct evidence establishing confirmed hazardous areas in both parts. The national criteria permit clearance where direct evidence defines the hazard; there is no safe-use history supporting cancellation. The road works must not start while the land remains hazardous, and clearance and release must be completed first.

General guidance on the situation:

> Keep people and animals away from the area. Do not touch, move or try to destroy anything suspected to be explosive ordnance. Mark the place only if this can be done without going closer, and report it to the authorities.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | Two former combatants who served at the position described a minefield they helped to lay across the road approach and along the riverbank on either side of the crossing, to protect it. | yes |
| E2 | The team saw the remains of an old fence and two rusted warning signs along the riverbank downstream of the crossing. | yes |
| E3 | A goat was killed by an explosion on the road approach in 2023, at a spot that the herder showed the team. | yes |
| E4 | During a bush fire in 2024, women collecting water heard and saw an explosion on the riverbank upstream of the crossing. | yes |
| E5 | People cross the river further upstream on a footpath and do not use the road approach; the road has been closed to traffic since 2019. | yes |
| E6 | The provincial roads office plans to upgrade the road and rebuild the crossing in 2027. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | direct | A, B | 4 | - | The two interviewees state first-hand participation in laying mines across both named parts, confirming EO presence. |
| E2 | indirect | B | 2 | - | The observed fence and signs suggest a hazard, but the record does not establish why they were placed, so they do not alone confirm mines. |
| E3 | direct | A | 4 | - | The witness saw the accident and showed its accurately located spot, which is direct evidence under the evidence rules. |
| E4 | direct | B | 4 | - | Witnessed explosion during a fire on the riverbank is direct evidence under the evidence rules; the traditional authority's corroboration does not weaken this first-hand account. |
| E5 | not_evidence | A, B | 4 | - | This describes avoidance and use outside the crossing rather than safe use of either reviewed part, so it cannot support absence of EO. |
| E6 | not_evidence | A | 6 | - | A future works plan is relevant to release timing but says nothing about whether EO is present. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R2 | A | pass | Direct evidence of class 1-4 in part A: E1, E3. |
| R5 | A | pass | The national criteria allow clearance where direct evidence defines the hazard. |
| R2 | B | pass | Direct evidence of class 1-4 in part B: E1, E4. |
| R5 | B | pass | The national criteria allow clearance where direct evidence defines the hazard. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: evidence, reliability, hazard_areas, technical_survey, clearance, outcomes, national_criteria, all_reasonable_effort, further_survey, land_use

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - E2's fence and warning signs are treated as indirect evidence because the file does not establish why they were put in place; the direct evidence from E1, E3 and E4 independently supports the recommendation.
  - The survey team's recommendation is considered as evidence and context, not as the decision; sign-off is required.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
