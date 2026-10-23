# Sign-off sheet: C08, run 2

Case: Village outskirts along a former defensive berm  
Area ID: IRQ-SHA-6614  
Model: gpt-6.1-sol

## Recommendation
- Outcome: TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend targeted technical survey for both A and B. The checked police removal record in A (E1) and accurately located accident in B (E2) establish confirmed hazard locations and trigger CHA recording under the national criteria. Disturbed ground, defensive history and continued non-use support investigation along the berm, but do not define the full contaminated extent. Technical survey should establish the boundaries requiring clearance rather than assume the whole berm and frontage need clearance. Neither part has safe-use evidence supporting cancellation. All six evidence items were assessed; the rule check passed. Recommendation remains subject to human sign-off.

General guidance on the situation:

> Keep people and animals away from the suspected hazardous land. Do not touch, move or try to destroy any suspicious item. Mark a suspected location only if this can be done without going closer, and report it to the responsible authorities.

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
| E1 | direct | A | 4 | - | The checked police account of its own team's removal confirms devices at a located point, but does not define the full hazard boundary. |
| E2 | direct | B | 4 | - | The documented and accurately located accident confirms contamination in B, with institutional records and family corroboration. |
| E3 | indirect | A, B | 2 | - | The team's imagery assessment identifies physical features consistent with possible contamination, not ordnance itself. |
| E4 | indirect | A, B | 4 | - | First-hand reports of unused land support suspicion in this corroborated setting and provide no evidence of safe use. |
| E5 | indirect | A, B | 4 | - | The resident mukhtar's first-hand account of defensive use supports possible contamination but does not confirm ordnance throughout the berm. |
| E6 | indirect | B | 2 | - | The observed community warning indicates suspicion, but its connection to a specific find or accident is not established and the lack of other signs does not establish absence. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E3, E4, E5. |
| R4 | B | pass | Evidence to target in part B: E2, E3, E4, E5, E6. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: national_criteria, evidence, reliability, hazard_areas, technical_survey, clearance, outcomes

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - Update the recorded SHA status to reflect confirmed hazard locations under the national criteria; do not assume the full outer boundary is confirmed.
  - The survey team's clearance recommendation was reviewed, not adopted automatically: direct evidence is located, but the full hazard extent remains undefined.
  - The basis of the villagers' warning is unspecified; it is not treated as independent confirmation of contamination.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
