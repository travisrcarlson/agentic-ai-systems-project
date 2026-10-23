# Sign-off sheet: C13, run 3

Case: A recorded minefield and a landslide below it in the Cordillera del Cóndor  
Area ID: PER-CHA-1311  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend targeted technical survey in both parts. A is supported by a reliable minefield record and observed markers, but the confirmed mine find outside the record means the hazard extent must be defined by technical survey before clearance under the national criteria. B has a confirmed mine find and evidence that the landslide moved soil from the minefield edge; neither the mine's origin nor the extent of possible contamination is established. The survey provides enough evidence to target technical survey, but not to cancel B or infer that the single find was the full extent.

General guidance on the situation:

> Keep people and animals away from the recorded minefield and landslide slope. Do not touch, move or try to destroy any suspected item. Mark a suspected location only if this can be done without going closer, and report it to the authorities.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The army's minefield record gives the outline of the minefield around the post and the pattern of its rows. | yes |
| E2 | In 2021 a demining team cleared the minefield of a neighbouring post, using a record made the same way by the same unit, and found the mines where the record placed them. | yes |
| E3 | Marker posts and warning signs stand at the corners of the recorded minefield; the team saw them and checked them against the record. | yes |
| E4 | After a landslide in 2025, a demining team found one mine on the landslide scar, outside the recorded minefield, and destroyed it. | yes |
| E5 | The binational demining unit compared both countries' army records for this stretch of the border in 2016; no other minefield is recorded near the post. | yes |
| E6 | "We laid the minefield to the record. But the slope below was steep, and in the rains the ground moves." | yes |
| E7 | People from the community said they hunt and fish along the river below the slope, but nobody climbs the slope or goes near the post, and nobody knows of an accident there. | yes |
| E8 | Satellite imagery shows that the 2025 landslide carried soil from the edge of the recorded minefield down the slope. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | direct | A | 3 | - | National criteria make this record direct evidence because a same-kind record from the same unit was confirmed against mines found during clearance. |
| E2 | not_evidence | outside | 3 | - | This is outside the reviewed area and does not establish EO presence or absence there, although it supports the reliability assessment of E1. |
| E3 | direct | A | 2 | - | Survey-team-observed warning markers associated with the known minefield directly support the recorded hazard boundary. |
| E4 | direct | B | 1 | - | The verified mine find directly confirms EO presence at a known point in B; destruction of that item does not establish the wider extent. |
| E5 | absence | all | 3 | - | The cross-checked records support absence of a separately recorded minefield, but do not explain away the confirmed mine find or landslide-related movement. |
| E6 | indirect | A, B | 4 | - | The former engineer's first-hand account corroborates the record and indicates possible hazard migration on the steep slope, without defining EO location or extent. |
| E7 | not_evidence | B, outside | 4 | - | Avoidance means there is no safe-use evidence for B, and river use below the slope without a duration or hazard-free activity inside B does not demonstrate absence there. |
| E8 | indirect | A, B | 2 | - | Survey-team assessment of imagery shows a plausible pathway for material to move from the recorded hazard into B, but does not prove where EO moved. |

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
- Rule topics looked up: evidence, reliability, hazard_areas, technical_survey, national_criteria, outcomes, further_survey, land_use

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation to clear A and cancel B is evidence to review, not a decision; its claim that the mine was moved by the landslide and represented only a spot task does not resolve the possible hazard extent.
  - The confirmed mine find is reported as destroyed; the case file does not establish whether other EO was displaced or remains in either part.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
