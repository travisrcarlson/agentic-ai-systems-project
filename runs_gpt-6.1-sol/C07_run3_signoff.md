# Sign-off sheet: C07, run 3

Case: A road and river crossing by a former military position  
Area ID: AGO-SHA-4408  
Model: gpt-6.1-sol

## Recommendation
- Outcome: CLEARANCE
- By part: A=CLEARANCE; B=CLEARANCE
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend clearance of both A (road approach and crossing) and B (riverbanks), for human approval. The accurately located animal explosion in A (E3), and observed minefield signs/fencing and witnessed fire detonation in B (E2, E4), provide direct evidence. First-hand accounts by former mine layers corroborate the hazard across both parts (E1). Neither part has safe use; the upstream alternative route and planned road works do not establish absence. National criteria allow clearance without prior technical survey where direct evidence defines the hazard. The recommendation independently supports the team's proposal; it does not release the land or authorize road works.

General guidance on the situation:

> Keep people and animals away from the suspected hazardous area. Do not touch, move or try to destroy any suspicious item. Mark a location only if this can be done without going closer, and report it to the authorities. Road works must not start on hazardous land until it has been formally released.

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
| E1 | indirect | A, B | 4 | - | First-hand participants' verbal accounts locate the reported minefield in both parts and corroborate the direct evidence, but are not direct physical confirmation on their own. |
| E2 | direct | B | 2 | - | Survey-observed signs and fencing associated with the minefield described by its layers constitute direct evidence, with an indirect physical source reliability class. |
| E3 | direct | A | 4 | - | A first-hand witness located the animal explosion accurately, providing direct evidence of contamination on the road approach. |
| E4 | direct | B | 4 | - | First-hand witnesses to a detonation during a fire provide direct evidence on the upstream riverbank. |
| E5 | not_evidence | A, B | 4 | - | First-hand reports of avoidance and use of another route establish no safe use or absence of ordnance in either part and do not independently confirm contamination. |
| E6 | not_evidence | A | 4 | - | The institution's first-hand statement of planned works concerns future land use and priority, not the presence or absence of ordnance. |

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
- Rule topics looked up: reliability, national_criteria, evidence, clearance, technical_survey, outcomes, all_reasonable_effort

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - Human review and sign-off are required; this is a recommendation, not a final decision.
  - Confirm and document operational boundaries and clearance requirements through the authority's tasking process; the narrative identifies affected parts but does not provide precise mapped limits.
  - Attachment photographs and the original roads-office letter were listed but not reproduced, so they could not be independently examined.
  - No instructions addressed to the reviewer or requests for munition-handling advice were found in the case file.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
