# Sign-off sheet: C13, run 2

Case: A recorded minefield and a landslide below it in the Cordillera del Cóndor  
Area ID: PER-CHA-1311  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=CLEARANCE; B=TECHNICAL_SURVEY
- By part: A=CLEARANCE; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend clearance of A, the recorded minefield: the national criterion treats its record as direct evidence after comparable records were confirmed by clearance, and markers corroborate the mapped boundary. Recommend targeted technical survey of B before any clearance: a mine was found at a known point outside the record, while the landslide imagery and first-hand account support possible movement from A but do not establish its extent. The national rule requires technical survey to define the extent where finds depart from a minefield record. Cancellation is not supported; neither part has safe-use history, and B is not shown to be clear.

General guidance on the situation:

> Treat both parts as hazardous pending the recommended work. Keep people and animals away; do not touch, move, or try to destroy any suspected item. Report any suspected explosive ordnance to the authorities, and mark its location only if this can be done without going closer.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The army's minefield record gives the outline of the minefield around the post and the pattern of its rows. | yes |
| E2 | In 2021 a demining team cleared the minefield of a neighbouring post, using a record made the same way by the same unit, and found the mines where the record placed them. | yes |
| E3 | Marker posts and warning signs stand at the corners of the recorded minefield; the team saw them and checked them against the record. | yes |
| E4 | After a landslide in 2025, a demining team found one mine on the landslide scar, outside the recorded minefield, and destroyed it. It is not known whether the landslide carried it there or the record is incomplete. | yes |
| E5 | The binational demining unit compared both countries' army records for this stretch of the border in 2016; no other minefield is recorded near the post. | yes |
| E6 | "We laid the minefield to the record. But the slope below was steep, and in the rains the ground moves." | yes |
| E7 | People from the community said they hunt and fish along the river below the slope, but nobody climbs the slope or goes near the post, and nobody knows of an accident there. | yes |
| E8 | Satellite imagery shows that the 2025 landslide carried soil from the edge of the recorded minefield down the slope. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | direct | A | 3 | - | The national criterion makes this record direct evidence because records of the same kind were confirmed during clearance; the record delineates the recorded minefield. |
| E2 | direct | outside | 1 | - | The clearance finds directly confirmed mines at the neighbouring post, outside this area; this validates the comparable record method rather than proving mines in A or B. |
| E3 | direct | A | 2 | - | Survey-team-observed markers and warnings associated with the known minefield corroborate the recorded hazard boundary. |
| E4 | direct | B | 1 | - | The spot-task report establishes a mine at a known point in B, while leaving the extent and origin of contamination unresolved. |
| E5 | not_evidence | all | 3 | - | The absence of another recorded minefield is not evidence that no EO was displaced beyond the known field, particularly in light of the later find and landslide. |
| E6 | indirect | A, B | 4 | - | The first-hand engineer's account supports the minefield record and suggests possible movement of contamination onto the slope, without confirming current EO location there. |
| E7 | not_evidence | B, outside | 4 | - | The community reports no use of the slope or post, so absence of accidents is not evidence of safe use there; river use concerns land below/outside the hazardous parts. |
| E8 | indirect | A, B | 2 | - | Survey-team assessment of imagery shows a plausible route for displacement from A into B, but does not establish that EO moved or define its extent. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R6 | all | pass | Every part is decided once. |
| R7 | all | pass | Every evidence-log item is in the register. |
| R2 | A | pass | Direct evidence of class 1-4 in part A: E1, E3. |
| R5 | A | pass | The national criteria allow clearance where direct evidence defines the hazard. |
| R4 | B | pass | Evidence to target in part B: E4, E6, E8. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: evidence, reliability, hazard_areas, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's claim that the mine on the landslide scar was moved, and its recommendation to cancel B, are not established by the evidence log: the spot-task report says its origin is unknown, and the imagery shows soil movement rather than proving where the mine came from.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
