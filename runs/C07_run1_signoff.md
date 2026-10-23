# Sign-off sheet: C07, run 1

Case: A road and river crossing by a former military position  
Area ID: AGO-SHA-4408  
Model: gpt-6-luna

## Recommendation
- Outcome: TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend targeted technical survey of both parts A and B. Direct evidence establishes contamination at a known point on the road approach and at a point on the riverbank; additional first-hand accounts and physical warning indicators support the suspected minefield across both parts. The evidence does not yet define the hazard’s boundaries well enough to justify clearance without technical survey. There has been no safe use to support cancellation, and the national criteria require release before the planned road works.

General guidance on the situation:

> Keep people and animals away from the suspected hazardous area. Do not touch, move or try to destroy anything; mark a place only if this can be done without going closer, and report concerns to the national mine action authority, survey team or police.

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
| E1 | indirect | A, B | 4 | - | First-hand accounts of laying mines are credible indications, but verbal reports alone do not physically confirm current contamination. |
| E2 | direct | B | 2 | - | Survey-team observation of fence and warning signs associated with contamination is direct evidence, although their history should be corroborated where possible. |
| E3 | direct | A | 4 | - | A first-hand witness identified the location of an animal explosion, which is direct evidence of contamination at that spot. |
| E4 | direct | B | 4 | - | First-hand witnesses saw an explosion at a location on the riverbank, directly indicating contamination there. |
| E5 | not_evidence | A, B | 4 | - | This describes avoidance and lack of use rather than safe use; it does not establish absence of explosive ordnance. |
| E6 | not_evidence | A | 6 | - | A plan for future works is relevant to urgency and land use, but does not indicate whether contamination is present. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E3. |
| R4 | B | pass | Evidence to target in part B: E1, E2, E4. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: evidence, reliability, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, quality_control, safety_guidance, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation for clearance is an assessment to review, not a decision; current direct evidence does not define the full extent of the hazard for clearance without technical survey.
  - The roads office plans work in 2027; under the national criteria, road works must not start on land that remains hazardous and unreleased.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
