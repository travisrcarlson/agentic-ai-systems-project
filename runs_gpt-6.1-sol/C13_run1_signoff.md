# Sign-off sheet: C13, run 1

Case: A recorded minefield and a landslide below it in the Cordillera del Cóndor  
Area ID: PER-CHA-1311  
Model: gpt-6.1-sol

## Recommendation
- Outcome: TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend technical survey of both A and B to define the hazard extent before clearance. E1 is direct evidence under the national criterion, corroborated by comparable clearance results in E2 and observed marking in E3. However, E4 confirms a mine outside the recorded boundary, and E8 supports landslide displacement without establishing its full extent. The national rule therefore requires technical survey before clearance. Destroying the single find does not resolve the wider hazard. Neither part has safe use, and the absence of another recorded minefield or reported accidents does not justify cancellation. The record, known find point and imagery provide evidence for targeting survey.

General guidance on the situation:

> Keep people and animals away from the recorded minefield, landslide scar and slope. Do not touch, move or try to destroy any suspected item. Mark a suspected location only if this can be done without going closer, and report it to the authorities.

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
| E1 | direct | A | 3 | - | The national rule treats this record as direct evidence because clearance at the neighbouring post verified records of the same kind. |
| E2 | direct | outside | 3 | - | The completion record documents confirmed contamination outside this area and corroborates the reliability of E1, without establishing this area's full hazard extent. |
| E3 | direct | A | 2 | - | Survey-observed marking tied to a known recorded minefield is direct evidence, though not physical ordnance itself. |
| E4 | direct | B | 1 | - | The documented physical find confirms contamination at a known point outside the recorded boundary; destruction of that item does not establish that the slope contains no others. |
| E5 | absence | A, B | 6 | - | This is limited documentary absence of another recorded minefield, not verified completeness of the records or an explanation removing the outside-boundary find. |
| E6 | indirect | A, B | 4 | - | A first-hand participant supports the recorded laying and a plausible displacement mechanism, without proving the present limits of contamination. |
| E7 | not_evidence | B, outside | 4 | - | First-hand accounts describe river use rather than use of B, so lack of known accidents does not demonstrate safe use of the slope. |
| E8 | indirect | A, B | 2 | - | Observed imagery supports a pathway for displacement from the recorded minefield to the slope but does not establish where all mines now lie. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E3, E6, E8. |
| R4 | B | pass | Evidence to target in part B: E4, E6, E8. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: national_criteria, reliability, evidence, technical_survey, cancellation, clearance

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - For human review and sign-off; this recommendation does not release land.
  - The survey team's proposed clearance of A and cancellation of B is not supported: displacement is plausible, not established as the sole explanation, and the find outside the record triggers technical survey before clearance.
  - The minefield record, spot-task report, imagery and photographs are referenced but not reproduced; verify the underlying attachments during sign-off and survey planning.
  - Confidence is high in the recommended next step, not in the current boundaries or quantity of remaining contamination.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
