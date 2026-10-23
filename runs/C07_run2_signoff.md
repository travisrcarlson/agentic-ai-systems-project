# Sign-off sheet: C07, run 2

Case: A road and river crossing by a former military position  
Area ID: AGO-SHA-4408  
Model: gpt-6-luna

## Recommendation
- Outcome: TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend targeted technical survey of both parts. Direct evidence confirms explosive ordnance at a known spot in A and on the riverbank in B; the former combatants’ account further indicates a broader suspected minefield. The evidence establishes contamination but does not define its full extent, so clearance of the whole approach and riverbanks is not yet sufficiently bounded. The survey should define the hazard and areas requiring clearance before any road works.

General guidance on the situation:

> Keep people and animals away from the crossing, road approach, and riverbanks. Do not touch, move, or try to destroy anything; mark a place only if this can be done without going closer, and report concerns to the national mine action authority or police.

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
| E1 | indirect | A, B | 4 | - | First-hand accounts support the reported hazard, but the verbal report itself is indirect evidence rather than physical confirmation. |
| E2 | direct | B | 2 | - | Survey-team-observed fence remains and mine warning signs are direct evidence associated with contamination. |
| E3 | direct | A | 4 | - | A witnessed animal accident with a location identified to the team directly confirms explosive ordnance at that spot. |
| E4 | direct | B | 4 | - | First-hand witnesses saw an explosion on the riverbank, directly confirming explosive ordnance there. |
| E5 | not_evidence | A, B | 4 | - | This documents avoidance and lack of use in the area, not safe use or evidence that explosive ordnance is absent. |
| E6 | not_evidence | A | 4 | - | A future works plan is relevant to urgency but says nothing about explosive ordnance presence or absence. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E3. |
| R4 | B | pass | Evidence to target in part B: E1, E2, E4. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: evidence, reliability, hazard_areas, technical_survey, clearance, outcomes, national_criteria, safety_guidance

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team recommended clearance, but that recommendation is evidence to assess, not a decision to follow.
  - National criteria prohibit road works on land in a hazardous area until it has been released; the planned 2027 works must not start there before release.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
