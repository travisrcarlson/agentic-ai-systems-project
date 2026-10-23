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

> Recommend technical survey in both parts. E1 directly confirms removed improvised devices at a known point in A, and E2 is a reliably located accident in B; national criteria therefore classify the area as a CHA. E3 and E5 also indicate possible contamination along the berm, but the evidence does not define the full hazard extent. There has been no land use that can support cancellation. Technical survey should define the contaminated extent and areas suitable for release before clearance is determined.

General guidance on the situation:

> Keep people and animals away from the berm and the land in front of it. Do not touch, move or try to destroy anything suspected of being explosive ordnance. Mark a suspected place only if this can be done without going closer, and report it to the authorities.

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
| E1 | direct | A | 3 | - | The station-checked record documents devices removed at a known point in part A, directly confirming improvised mines were present there. |
| E2 | direct | B | 4 | - | The accident location is accurately established by records and shown on site, and national criteria treat a located accident as confirmation. |
| E3 | indirect | A, B | 2 | - | The imagery shows a physical pattern that may be associated with contamination but does not itself confirm EO. |
| E4 | not_evidence | A, B | 4 | - | Non-use provides no evidence of safe use or of absence of EO, so it cannot support cancellation. |
| E5 | indirect | A, B | 4 | - | The defensive context suggests possible contamination but does not establish EO in either part. |
| E6 | not_evidence | B | 2 | - | This is a locally made warning with no stated basis tying it to a known minefield, so it reflects concern rather than confirming EO. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E3, E5. |
| R4 | B | pass | Evidence to target in part B: E2, E3, E5. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: evidence, reliability, hazard_areas, cancellation, technical_survey, clearance, further_survey, land_use, national_criteria, case_file_text

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team recommends clearance along the berm with technical survey to set the extent in front of it. This review recommends technical survey in both parts first because the direct evidence gives located points but does not define the full hazard extent; the authorized decision-maker should consider this sequencing difference.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
