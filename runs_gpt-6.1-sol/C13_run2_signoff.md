# Sign-off sheet: C13, run 2

Case: A recorded minefield and a landslide below it in the Cordillera del Cóndor  
Area ID: PER-CHA-1311  
Model: gpt-6.1-sol

## Recommendation
- Outcome: TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend technical survey of both A and B before determining clearance boundaries. A is confirmed by the validated minefield record and associated marking. The documented mine find in B departs from that record; imagery shows soil movement from the minefield edge onto the slope, and the mechanism and extent of contamination remain unresolved. National criteria require technical survey before clearance where finds depart from a minefield record. The known find and landslide provide evidence for targeting survey. Destruction of one mine and the absence of another recorded minefield do not establish that B is free of contamination. Neither part has safe-use years; river use does not establish safe use of B. Cancellation is unsupported.

General guidance on the situation:

> Keep people and animals away from the recorded minefield and the landslide scar and slope. Do not touch, move or try to destroy any suspected item. Mark a suspected location only if this can be done without going closer, and report it to the responsible authorities.

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
| E1 | direct | A | 3 | - | Comparable records were validated by clearance at the neighbouring post, so the national rule treats this record as direct evidence in A. |
| E2 | direct | outside | 3 | - | The completion report documents confirmed contamination outside this area and validates the record type, without confirming contamination in B. |
| E3 | direct | A | 2 | - | Observed marking associated with a known recorded minefield is direct evidence, though the physical indicators are not themselves ordnance. |
| E4 | direct | B | 1 | - | The documented physical find confirms contamination at a known point in B; destruction of that item does not establish absence elsewhere on the slope. |
| E5 | absence | all | 6 | - | This provides limited documentary support against another recorded minefield, but does not explain away the actual find or exclude displaced mines or incomplete records. |
| E6 | indirect | A, B | 4 | - | A first-hand participant corroborates laying in A and raises a plausible displacement concern for B without establishing its extent. |
| E7 | not_evidence | B, outside | 4 | - | River use and lack of known accidents do not demonstrate safe use of the unused slope. |
| E8 | indirect | A, B | 2 | - | Observed ground movement links the minefield edge to the slope and supports possible wider displacement, but does not locate further mines. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E3, E6, E8. |
| R4 | B | pass | Evidence to target in part B: E4, E6, E8. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: national_criteria, reliability, evidence, technical_survey, cancellation, hazard_areas

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - For human review and sign-off only; this recommendation does not release land.
  - The survey team's recommendation to cancel B assumes the mine was moved and that the single-item task resolved the hazard; the report leaves its origin unresolved and imagery supports possible wider displacement.
  - Review B's recorded SHA status: the known find is direct evidence at a point, while the wider slope's contaminated extent remains to be established; do not assume the whole slope is confirmed contaminated.
  - The referenced minefield record, spot-task report, images and photographs are not reproduced; verify the originals when planning and approving survey.
  - No embedded reviewer-directed instructions or requests for item-handling advice were identified.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
