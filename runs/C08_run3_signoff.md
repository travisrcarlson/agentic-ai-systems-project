# Sign-off sheet: C08, run 3

Case: Village outskirts along a former defensive berm  
Area ID: IRQ-SHA-6614  
Model: gpt-6-luna

## Recommendation
- Outcome: TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend targeted technical survey in both A and B. E1 is direct evidence of device removal in A, and E2 is a accurately located accident in B; under the national criteria, each part is therefore confirmed hazardous. E3 and E5 also support investigating the berm frontage, while E6 is only an indirect warning and E4 provides no safe-use evidence because the land has not been used. The direct evidence identifies points, not the full extent of contamination, so technical survey should define the areas requiring clearance; clearance of the whole berm frontage is not yet supported by defined boundaries.

General guidance on the situation:

> Keep people and animals away from the suspected hazardous land. Do not touch, move or try to destroy any suspected item. Report concerns to the authorities; mark a place only if it can be done without going closer.

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
| E1 | direct | A | 4 | - | A checked police record locates a verified removal of devices in part A; this is direct evidence of past EO presence at that point. |
| E2 | direct | B | 4 | - | The accident location is documented and shown to the team, meeting the direct-evidence criterion for a located accident. |
| E3 | indirect | A, B | 2 | - | The survey team observed disturbed ground in imagery, which suggests possible contamination but does not itself confirm EO. |
| E4 | not_evidence | A, B | 4 | - | Non-use with no safe use period supplies no evidence that the land is free of EO and does not explain the confirmed evidence. |
| E5 | indirect | A, B | 4 | - | The firsthand account of defensive use, considered with the former conflict setting, suggests possible contamination but does not confirm it. |
| E6 | indirect | B | 2 | - | The team confirms the warning exists, but it is a villagers' warning of unknown basis and indicates suspicion rather than confirming EO. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E3, E5. |
| R4 | B | pass | Evidence to target in part B: E2, E3, E5, E6. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation for clearance along the berm is evidence to assess, not a decision; the evidence presently locates hazards but does not define their full extent.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
