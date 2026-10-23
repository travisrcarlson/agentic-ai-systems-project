# Sign-off sheet: C07, run 3

Case: A road and river crossing by a former military position  
Area ID: AGO-SHA-4408  
Model: gpt-6-luna

## Recommendation
- Outcome: TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend targeted technical survey in both A and B. First-hand accounts suggest a minefield across the crossing and riverbanks; a witnessed animal accident at a known spot in A, observed warning signs/fence in B, and a witnessed detonation in B provide direct evidence. The evidence establishes a hazard but does not define its full extent, so survey should define the hazardous limits and areas suitable for reduction before clearance is planned. There is no qualifying safe use: both parts have zero recorded years of safe use, and avoidance or use of an upstream footpath does not demonstrate safety within the area. The road works must not start while the land remains hazardous; release is required first.

General guidance on the situation:

> People should keep away from the crossing and riverbanks and keep animals away. Do not touch, move or try to destroy anything suspected of being explosive ordnance. Mark a place only if this can be done without going closer, and report it to the authorities.

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
| E1 | indirect | A, B | 4 | - | First-hand participant accounts strongly suggest mines in both parts, but are verbal reports rather than direct physical confirmation. |
| E2 | direct | B | 2 | - | Survey-team observation of fencing and warning signs associated with contamination directly supports mines along part B, with physical evidence recorded by the team. |
| E3 | direct | A | 4 | - | The first-hand witness identified the site of an explosion causing an animal death, direct evidence of EO at a known spot in part A. |
| E4 | direct | B | 4 | - | First-hand witnesses, corroborated by the traditional authority, observed an explosion in part B, direct evidence of EO there. |
| E5 | not_evidence | A, B | 4 | - | This describes avoidance and use outside the crossing, not safe use within either part and does not establish presence or absence of EO. |
| E6 | not_evidence | A | 4 | - | The planned works create a release requirement and urgency but provide no evidence about whether EO is present. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E3. |
| R4 | B | pass | Evidence to target in part B: E1, E2, E4. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, quality_control, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation for clearance is evidence to assess, not a decision to follow; this recommendation is for technical survey because the hazard boundaries are not defined by the available evidence.
  - The roads office plans works in 2027; under the national criterion, works may not start on land in a hazardous area until it has been released.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
