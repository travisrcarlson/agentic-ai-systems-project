# Sign-off sheet: C07, run 2

Case: A road and river crossing by a former military position  
Area ID: AGO-SHA-4408  
Model: gpt-6-luna

## Recommendation
- Outcome: CLEARANCE
- By part: A=CLEARANCE; B=CLEARANCE
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend clearance of both A (road approach and crossing) and B (riverbanks). First-hand accounts describe mines laid in both parts (E1), and separately located/witnessed explosive events provide direct evidence in A (E3) and B (E4). There is no safe-use evidence to support cancellation; avoidance and the closed road do not establish absence. The national criteria allow clearance without prior technical survey where direct evidence defines the hazard, and the rule check passes. Road works must not begin while the land remains hazardous and unreleased.

General guidance on the situation:

> Keep people and animals away from the area. Do not touch, move or try to destroy any suspected item. Mark a place only if this can be done without going closer, and report it to the national mine action authority, survey team or police.

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
| E1 | direct | A, B | 4 | - | First-hand participants describe laying a minefield across both parts, directly confirming EO presence. |
| E2 | indirect | B | 2 | - | The team directly observed physical indicators, but the record does not establish whether the fence and signs were installed because of known contamination rather than precaution. |
| E3 | direct | A | 4 | - | A first-hand witness identifies the accident location accurately, providing direct evidence under the evidence criteria. |
| E4 | direct | B | 4 | - | First-hand witnesses saw a detonation during a fire, which is direct evidence of EO presence. |
| E5 | not_evidence | A, B | 4 | - | This describes avoidance and use elsewhere, not safe use of either part, and therefore supports no absence conclusion. |
| E6 | not_evidence | A | 4 | - | The planned works establish a future land-use requirement but say nothing about current EO presence or absence. |

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
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, quality_control, safety_guidance, case_file_text, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation for clearance was considered as evidence, not treated as a decision.
  - The area record divides the hazard into A and B; the sign-off and release process should ensure those parts are fully covered before the planned road works.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
