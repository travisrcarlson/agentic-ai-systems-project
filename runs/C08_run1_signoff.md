# Sign-off sheet: C08, run 1

Case: Village outskirts along a former defensive berm  
Area ID: IRQ-SHA-6614  
Model: gpt-6-luna

## Recommendation
- Outcome: TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend targeted technical survey in both A and B. E1 confirms removed improvised devices at a located point in A, and E2 confirms a located accident in B; under the national criterion, both parts are CHA. The imagery and defensive-position context add indirect evidence along the berm, but the direct evidence points do not define the extent of the hazard across either part. Technical survey should define the affected areas and support subsequent clearance decisions. Cancellation is not supported: neither part has safe-use evidence, and the required five years of safe use are not met.

General guidance on the situation:

> Keep people and animals away from the berm and the land in front of it. Do not touch, move, or try to destroy any suspected item. Mark a location only if this can be done without going closer, and report suspected items or incidents to the authorities.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | A police record states that a police explosive ordnance disposal team removed two improvised devices from the front of the berm in 2019, at a point marked on the police sketch. | yes |
| E2 | A herder was injured by an explosion in front of the southern half of the berm in 2021; the hospital and police records give the place, and his family showed it to the team. | yes |
| E3 | Satellite imagery shows the berm and a line of disturbed ground in front of it along its whole length. | yes |
| E4 | Families have not used the land in front of the berm since they returned in 2018; they graze their animals elsewhere. | yes |
| E5 | During the occupation, the berm was the front of the occupiers' defences around the village. | yes |
| E6 | The team saw a red-painted warning that villagers made near the southern end of the berm, and no other signs. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | direct | A | 6 | - | The verified police record locates removed devices at a specific point in A, confirming EO presence there historically; the record is historical and has not been shown accurate by comparison with later direct evidence. |
| E2 | direct | B | 4 | - | The accident location was corroborated by records and shown to the team, so it confirms EO at that spot; the reporting source is treated as first-hand accident evidence. |
| E3 | indirect | A, B | 2 | - | The survey team's imagery assessment observes disturbed ground, which suggests possible contamination but does not confirm EO. |
| E4 | indirect | A, B | 4 | - | First-hand accounts of non-use show avoidance, which can suggest suspected hazard but do not establish safe use or absence. |
| E5 | indirect | A, B | 4 | - | The mukhtar's first-hand account of a defensive position is contextual evidence suggesting possible contamination, not confirmation. |
| E6 | indirect | B | 2 | - | The survey team directly observed a locally made warning, but no basis for it is stated; as a precautionary mark it indicates suspicion rather than confirming EO. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E3, E4, E5. |
| R4 | B | pass | Evidence to target in part B: E2, E3, E4, E5, E6. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, quality_control, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation for clearance along the berm was considered, but the extent of contamination is not defined by the current direct evidence; its recommendation is not itself a decision.
  - No cancellation basis is established: the land has been unused since return, with zero years of safe use recorded.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
