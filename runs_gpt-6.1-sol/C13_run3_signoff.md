# Sign-off sheet: C13, run 3

Case: A recorded minefield and a landslide below it in the Cordillera del Cóndor  
Area ID: PER-CHA-1311  
Model: gpt-6.1-sol

## Recommendation
- Outcome: TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend technical survey of both A and B before defining clearance boundaries. E1 is direct evidence under the national criterion, supported by comparable clearance in E2 and marking in E3. However, E4 confirms a mine outside the recorded boundary, while E8 and E6 support possible landslide displacement; the national rule therefore requires technical survey to define the hazard extent before clearance. Destroying the single find does not resolve contamination across B. Neither part has safe-use years, and river use and absence of known accidents do not justify cancelling the unused slope. E5 does not explain away the find or displacement evidence.

General guidance on the situation:

> Keep people and animals away from the recorded minefield and the landslide scar and slope. Do not touch, move or try to destroy any suspected item. Mark a suspected location only if this can be done without going closer, and report it to the national mine action authority, survey team or police.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The army's minefield record gives the outline of the minefield around the post and the pattern of its rows. | yes |
| E2 | found the mines where the record placed them. | yes |
| E3 | Marker posts and warning signs stand at the corners of the recorded minefield; the team saw them and checked them against the record. | yes |
| E4 | After a landslide in 2025, a demining team found one mine on the landslide scar, outside the recorded minefield, and destroyed it. | yes |
| E5 | no other minefield is recorded near the post. | yes |
| E6 | We laid the minefield to the record. But the slope below was steep, and in the rains the ground moves. | yes |
| E7 | nobody climbs the slope or goes near the post, and nobody knows of an accident there. | yes |
| E8 | Satellite imagery shows that the 2025 landslide carried soil from the edge of the recorded minefield down the slope. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | direct | A | 3 | - | The national criterion treats this record as direct evidence because records of the same kind were verified in neighbouring clearance, although the outlying find makes the full extent uncertain. |
| E2 | direct | outside | 3 | - | The completion report records confirmed contamination outside this area and validates the record type used for E1, without defining this area's full hazard boundary. |
| E3 | direct | A | 2 | - | Survey-observed marking associated with a recorded known minefield corroborates contamination in A rather than merely precautionary suspicion. |
| E4 | direct | B | 4 | - | The first-hand institutional spot-task report confirms a mine at a known point in B; destruction of that item does not establish that the surrounding slope is free of contamination. |
| E5 | absence | all | 6 | - | The unvalidated record comparison offers limited absence evidence for another recorded minefield but explains away neither the outlying find nor possible landslide displacement. |
| E6 | indirect | A, B | 4 | - | A first-hand participant corroborates recorded laying in A and describes slope movement relevant to possible displacement into B without establishing its extent. |
| E7 | not_evidence | B | 4 | - | First-hand reports of avoiding the slope and safe river activity do not demonstrate safe use of B, so the lack of known accidents does not negate its contamination evidence. |
| E8 | indirect | A, B | 2 | - | Survey assessment of physical imagery supports a displacement pathway between A and B but does not establish where mines now lie or the full hazard extent. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E3, E6, E8. |
| R4 | B | pass | Evidence to target in part B: E4, E6, E8. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: reliability, national_criteria, evidence, technical_survey, cancellation, clearance, safety_guidance, all_reasonable_effort

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - For human review and sign-off only; this recommendation does not release either part.
  - Do not adopt the survey team's proposed clearance of A and cancellation of B: the outlying find triggers the national requirement to define the hazard extent through technical survey.
  - The cause of the outlying mine and the current contamination boundaries remain uncertain; confidence is high in the recommended next step, not in the final extent.
  - Listed attachments were not reproduced; the signing authority should verify the original minefield record, spot-task report and imagery during planning.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
