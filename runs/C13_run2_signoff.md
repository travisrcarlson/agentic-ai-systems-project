# Sign-off sheet: C13, run 2

Case: A recorded minefield and a landslide below it in the Cordillera del Cóndor  
Area ID: PER-CHA-1311  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend targeted technical survey in both A and B before clearance decisions. A is supported by a minefield record treated as direct evidence under the national criteria, corroborated by successful clearance against a comparable record. But a mine was found outside that record in B, and the available evidence does not establish whether it was transported or whether the record is incomplete. The national rule requires technical survey to define the hazard extent when finds depart from a minefield record. There is no safe-use history to support cancellation of B; the recorded lack of access and accidents is not evidence of absence.

General guidance on the situation:

> Keep people and animals away from the recorded minefield, landslide scar and slope below it. Do not touch, move or try to destroy any suspected item. Mark a place only if that can be done without going closer, and report any suspected item or change in conditions to the national mine action authority or police.

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
| E1 | direct | A | 3 | - | National criteria treat this type of minefield record as direct evidence because comparable records from the same kind have been confirmed during clearance. |
| E2 | not_evidence | outside | 1 | - | This is strong confirmation of a comparator record outside the area, establishing the reliability of E1 but not proving EO is present inside this area. |
| E3 | direct | A | 2 | - | The team observed markers and warnings associated with the known minefield; under the evidence rule, marking for a known minefield is direct evidence. |
| E4 | direct | B | 1 | - | A mine was physically found at a known point in B; the already completed spot task does not remove the direct evidence that contamination was present there. |
| E5 | absence | all | 3 | - | The verified historical record supports absence of any separately recorded nearby minefield, but it does not explain away the direct find in B or establish that the landslide did not transport a mine. |
| E6 | indirect | A, B | 4 | - | The first-hand account supports the recorded layout in A and raises a possibility of movement on the slope, but does not directly confirm EO currently present in either part. |
| E7 | not_evidence | B, outside | 4 | - | Reported avoidance means there has been no safe use of B to support cancellation, and activity on the river is outside the hazardous slope; lack of known accidents is not evidence of absence here. |
| E8 | indirect | A, B | 2 | - | Team-assessed imagery supports a plausible pathway for hazard to move from A into B, but soil movement itself does not confirm EO in B. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R6 | all | pass | Every part is decided once. |
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E3, E6, E8. |
| R4 | B | pass | Evidence to target in part B: E4, E6, E8. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, national_criteria, safety_guidance, case_file_text

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation to clear A and cancel B was considered but is not followed: E4 is direct evidence of a mine in B, and the evidence does not establish that the find was moved there or that B is clear.
  - The technical survey should define the extent of the hazard before any clearance decision, particularly given the off-record find and the landslide pathway indicated by E8.
  - National cancellation criteria require five years of safe use; both parts have zero years recorded, and the community reports avoiding the slope and post.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
