# Sign-off sheet: C13, run 1

Case: A recorded minefield and a landslide below it in the Cordillera del Cóndor  
Area ID: PER-CHA-1311  
Model: gpt-6-luna

## Recommendation
- Outcome: TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend targeted technical survey across A and B before clearance or cancellation. A is a confirmed minefield supported by a reliable record and observed markers; in B, a mine was found outside that record, and imagery plus first-hand testimony establish a plausible movement pathway without resolving whether the record is incomplete or whether further EO is present. The national criterion requires technical survey to define the hazard extent when finds depart from a minefield record. B has no safe-use history; the community's river use is not evidence of safe use on the slope. The survey team's claim that the mine was moved and its recommendation to cancel B are not established by the evidence.

General guidance on the situation:

> Keep people and animals away from the recorded minefield, landslide scar and slope below. Do not touch, move or try to destroy any suspected item. Mark a suspected location only if this can be done without going closer, and report it to the national mine action authority or survey team.

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
| E1 | direct | A | 3 | - | National criteria treat this record as direct evidence because a same-kind record from the same unit was confirmed in clearance; the record itself has not been validated within A. |
| E2 | not_evidence | outside | 3 | - | The completion report validates the record type but concerns another post and does not itself establish EO in this area. |
| E3 | direct | A | 2 | - | Observed markers and warning signs associated with the known minefield corroborate direct evidence of contamination in A. |
| E4 | direct | B | 1 | - | A mine was physically found at a known point in B; its removal does not resolve the extent or possible further contamination. |
| E5 | absence | B | 3 | - | A reliable record search found no other recorded minefield nearby, but this does not rule out EO displaced beyond the recorded field or an incomplete record. |
| E6 | indirect | A, B | 4 | - | The first-hand engineer confirms laying to the record while also describing slope movement that could have affected the hazard; it does not establish whether EO moved. |
| E7 | not_evidence | B, outside | 4 | - | The reported river use is outside the hazard area and the community avoids B, so the lack of accidents there does not demonstrate safe exposure or absence of EO. |
| E8 | indirect | A, B | 2 | - | Team-reviewed imagery confirms soil movement from the field edge into B, creating a plausible pathway for displacement but not proving that a mine moved. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E3, E6, E8. |
| R4 | B | pass | Evidence to target in part B: E4, E6, E8. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, quality_control, safety_guidance, case_file_text, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation is treated as evidence to assess, not as a decision. Its assertion that the mine was moved by the landslide is uncertain in the case file and is not sufficient to cancel B.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
