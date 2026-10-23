# Sign-off sheet: C07, run 1

Case: A road and river crossing by a former military position  
Area ID: AGO-SHA-4408  
Model: gpt-6.1-sol

## Recommendation
- Outcome: CLEARANCE
- By part: A=CLEARANCE; B=CLEARANCE
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend clearance of A and B for human sign-off, with the evidence-supported hazard recorded as a CHA. The located animal accident confirms contamination in A; observed fencing and warning signs and a witnessed fire detonation provide direct evidence in B. First-hand laying accounts corroborate the hazard along the approach and both riverbanks. Neither part has any years of safe use, so cancellation is unsupported. National criteria allow clearance without prior technical survey where direct evidence defines the hazard; the corroborating locations support that route here. Operational limits must be verified and documented rather than assuming contamination extends beyond the evidence. Planned road works affect priority, not the evidence of contamination.

General guidance on the situation:

> Keep people and animals away from the crossing, approach and affected riverbanks. Do not touch, move or try to destroy any suspicious item. Mark a location only if this can be done without going closer, and report it to the national mine action authority, survey team or police. Road works must not begin within the hazardous area until the land has been formally released.

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
| E1 | indirect | A, B | 4 | - | First-hand verbal accounts of laying indicate contamination in both parts and corroborate the direct evidence, but are not themselves physical confirmation. |
| E2 | direct | B | 2 | - | Team-observed minefield-associated fencing and signs, corroborated by the laying accounts and riverbank explosion, provide direct evidence rather than merely precautionary marking. |
| E3 | direct | A | 4 | - | An eyewitness animal accident at a located spot is direct evidence on the road approach. |
| E4 | direct | B | 4 | - | First-hand witnesses to a detonation during a fire provide direct evidence on the upstream riverbank. |
| E5 | indirect | A, B | 4 | - | First-hand accounts of avoidance and non-use support suspicion in the context of corroborating hazard evidence and do not demonstrate safe use of either part. |
| E6 | not_evidence | A | 4 | - | The office's first-hand statement of planned works affects priority and release requirements, not whether ordnance is present or absent. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R2 | A | pass | Direct evidence of class 1-4 in part A: E3. |
| R5 | A | pass | The national criteria allow clearance where direct evidence defines the hazard. |
| R2 | B | pass | Direct evidence of class 1-4 in part B: E2, E4. |
| R5 | B | pass | The national criteria allow clearance where direct evidence defines the hazard. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: national_criteria, evidence, reliability, clearance, technical_survey, hazard_areas, safety_guidance

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - Recommendation only; requires authorized human review and sign-off.
  - Photographs and the roads office letter are listed but not reproduced; verify the originals and mapped evidence locations when confirming operational boundaries.
  - No instructions addressed to the reviewer or requests for unsafe handling advice were found in the supplied case text.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
