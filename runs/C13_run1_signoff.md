# Sign-off sheet: C13, run 1

Case: A recorded minefield and a landslide below it in the Cordillera del Cóndor  
Area ID: PER-CHA-1311  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=CLEARANCE; B=TECHNICAL_SURVEY
- By part: A=CLEARANCE; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend clearance of A, where a reliable minefield record defines the recorded hazard and is supported by the national criterion and corroborating same-unit record performance. Recommend targeted technical survey of B before any clearance: a mine was confirmed there, the landslide moved soil from the minefield edge, and the available evidence cannot determine whether the mine was displaced or the record incomplete. The mine's destruction as an EOD spot task does not resolve the extent of hazard. Cancellation of B is not supported.

General guidance on the situation:

> Keep people and animals away from the recorded minefield, landslide scar and slope below. Do not touch, move or try to destroy any suspected item. Mark a location only if this can be done without going closer, and report it to the authorities.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The army's minefield record gives the outline of the minefield around the post and the pattern of its rows. | yes |
| E2 | In 2021 a demining team cleared the minefield of a neighbouring post, using a record made the same way by the same unit, and found the mines where the record placed them. | yes |
| E3 | Marker posts and warning signs stand at the corners of the recorded minefield; the team saw them and checked them against the record. | yes |
| E4 | After a landslide in 2025, a demining team found one mine on the landslide scar, outside the recorded minefield, and destroyed it. | yes |
| E5 | The binational demining unit compared both countries' army records for this stretch of the border in 2016; no other minefield is recorded near the post. | yes |
| E6 | We laid the minefield to the record. But the slope below was steep, and in the rains the ground moves. | yes |
| E7 | People from the community said they hunt and fish along the river below the slope, but nobody climbs the slope or goes near the post, and nobody knows of an accident there. | yes |
| E8 | Satellite imagery shows that the 2025 landslide carried soil from the edge of the recorded minefield down the slope. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | direct | A | 3 | - | The national criterion treats this minefield record as direct evidence because a record of the same kind and unit was confirmed by clearance elsewhere. |
| E2 | direct | outside | 1 | - | The cleared mines directly confirm hazard at the neighbouring post only; this corroborates the type of record but is not evidence of EO in A or B. |
| E3 | indirect | A | 2 | - | Survey-team-observed markers support the recorded boundary, but do not themselves establish EO presence with certainty. |
| E4 | direct | B | 1 | - | A mine was directly confirmed at a known point in B; destruction of that item does not establish that the surrounding slope is free of further EO. |
| E5 | not_evidence | all | 3 | - | This establishes that no separate minefield is recorded nearby, but absence of another record does not rule out EO displaced into B or an incomplete record. |
| E6 | indirect | A, B | 4 | - | The first-hand account supports the record's account of laying in A and the possibility, but not certainty, of movement down the slope in B. |
| E7 | not_evidence | B, outside | 4 | - | The account describes river use outside the slope and avoidance of B and A, so it is not evidence of safe use or absence of EO in either part. |
| E8 | indirect | A, B | 2 | - | Survey-team desk assessment of imagery supports physical soil movement from A into B, making transfer of EO plausible but not proving it occurred. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R6 | all | pass | Every part is decided once. |
| R7 | all | pass | Every evidence-log item is in the register. |
| R2 | A | pass | Direct evidence of class 1-4 in part A: E1. |
| R5 | A | pass | The national criteria allow clearance where direct evidence defines the hazard. |
| R4 | B | pass | Evidence to target in part B: E4, E6, E8. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's conclusion that the mine was moved, and its recommendation to cancel B, are not established by the evidence; the case file explicitly says it is unknown whether the landslide carried the mine or the record is incomplete.
  - National criteria require technical survey to define the hazard extent where finds depart from a minefield record; B should not be cancelled or cleared on the present evidence.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
