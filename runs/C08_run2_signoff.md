# Sign-off sheet: C08, run 2

Case: Village outskirts along a former defensive berm  
Area ID: IRQ-SHA-6614  
Model: gpt-6-luna

## Recommendation
- Outcome: TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend targeted technical survey in both parts. E1 confirms device removal at a known point in A and E2 confirms a located accident in B; under the national criteria, each part is therefore a confirmed hazardous area. The evidence establishes points of contamination, but not the extent of the hazard across either berm and its frontage. Technical survey is warranted to delineate the contaminated areas and areas without evidence before clearance is planned. Cancellation is not supported: neither part has safe use, and indirect evidence also supports concern across the berm.

General guidance on the situation:

> Keep people and animals away from the berm and its frontage. Do not touch, move, or try to destroy any suspected item. Mark a place only if this can be done without going closer, and report any suspected item or incident to the authorities.

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
| E1 | direct | A | 4 | - | The checked record documents a removal of devices at a known location in part A, confirming EO presence there; the source is a police account of the event. |
| E2 | direct | B | 4 | - | The accident location was independently recorded and shown to the team, so this is direct evidence of EO at the known spot in part B. |
| E3 | indirect | A, B | 2 | - | The observed disturbed ground and defensive feature may indicate activity or hazard but do not themselves confirm EO. |
| E4 | indirect | A, B | 4 | - | The reported non-use is consistent with possible hazard but cannot support safe-use absence because the land has not been used. |
| E5 | indirect | A, B | 4 | - | A first-hand account of a defensive position suggests possible contamination but does not confirm EO. |
| E6 | indirect | B | 2 | - | The warning sign is an observed indicator of local concern, but its basis is not documented, so it cannot confirm EO on its own. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E3, E4, E5. |
| R4 | B | pass | Evidence to target in part B: E2, E3, E4, E5, E6. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: evidence, reliability, hazard_areas, technical_survey, clearance, cancellation, national_criteria, outcomes, further_survey

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's suggestion to clear along the berm is a recommendation, not a decision; the located evidence does not by itself define the full hazard extent.
  - The national criteria require recording an area with improvised mines as a CHA once a device or a located accident is confirmed; that threshold is met in both parts.
  - The warning sign in B has no documented basis and is treated as indirect evidence, not independent confirmation.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
