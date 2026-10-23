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

> Recommend targeted technical survey for both parts A and B. Part A has first-hand reporting of a minefield and a located animal explosion; part B has observed warning signs/fence remains, a witnessed explosion, and first-hand reporting of the minefield. These support confirmed hazard concerns, but the available direct evidence does not define the extent needed to justify clearance of either whole part. Use the evidence locations and reported minefield area to target survey and define the boundaries before deciding on clearance or release. Cancellation is not supported: neither part has safe-use evidence, and both report zero years of safe use. The road must not be rebuilt while the land remains hazardous.

General guidance on the situation:

> Keep people and animals away from the crossing and riverbank; do not touch, move or try to destroy any suspected item. Mark a place only if this can be done without going closer, and report it to the authorities. Do not begin road works until the land has been released.

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
| E1 | indirect | A, B | 4 | - | First-hand accounts of laying mines are credible indirect evidence of contamination, but reported testimony does not itself confirm present EO. |
| E2 | direct | B | 2 | - | The survey team's observation of fencing and warning signs associated with a mine hazard is direct evidence for this riverbank part. |
| E3 | direct | A | 4 | - | A first-hand witnessed explosion at a location shown to the team directly confirms a hazard at that spot in part A. |
| E4 | direct | B | 4 | - | First-hand witnesses saw an explosion at a location within the riverbank part, directly confirming a hazard there. |
| E5 | not_evidence | A, B | 4 | - | This describes avoidance and limited use, not safe use or the presence or absence of EO in the reviewed parts. |
| E6 | not_evidence | A | 6 | - | A future works plan is relevant to urgency but provides no evidence of EO presence or absence. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E3. |
| R4 | B | pass | Evidence to target in part B: E1, E2, E4. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, quality_control, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation for clearance is considered as evidence but is not followed automatically; current evidence does not establish the full extent of contamination across the parts.
  - The national criteria permit clearance without technical survey only where direct evidence defines the hazard; the present evidence is localized or does not define full part boundaries.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
