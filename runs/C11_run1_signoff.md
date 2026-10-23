# Sign-off sheet: C11, run 1

Case: A wadi crossing east of the berm  
Area ID: ESH-SHA-0921  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=CANCEL; B=TECHNICAL_SURVEY; C=FURTHER_NTS
- By part: A=CANCEL; B=TECHNICAL_SURVEY; C=FURTHER_NTS
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend splitting the area. For A, 18 years of reported safe camping and grazing, two first-hand herder sources, consultation with men and women, and the terrace’s position above the flood line meet the national cancellation criteria; the nearby historic minefield record is explicitly outside the area. For B, the documented mine find after flooding, the approximate livestock incident, and evidence of changing flood deposits justify targeted technical survey of the wadi bed and flood-transport path; the surface-only track check does not resolve subsurface risk. C was not accessed and has no usable hazard or safe-use evidence, so it should remain under the separate access procedure pending further non-technical survey.

General guidance on the situation:

> Until the relevant assessment and access procedures are completed, keep people and animals away from the wadi bed and the restricted edge. If anyone encounters suspected explosive ordnance, do not touch, move or try to destroy it; keep others away, mark the place only if this can be done without going closer, and report it to the authorities.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The database holds a record of a minefield of anti-vehicle and anti-personnel mines upstream of the crossing, nearer the berm. | yes |
| E2 | After a flood in 2024, an EOD team found and destroyed one anti-vehicle mine on the wadi bank below the crossing. | yes |
| E3 | Our families have camped on the terrace by the water point in every year with rain since 2008. The animals graze there and nobody has been hurt. | yes |
| E4 | A herder from a second family said his family also camps and grazes its animals on the terrace in years with rain, and has never found anything there. | yes |
| E5 | The accident register holds one livestock incident "near the wadi crossing", dated approximately to the 1990s, with no exact place; older herders say a camel was killed there. | yes |
| E6 | A route verification team checked the track across the wadi in 2025 and saw no explosive ordnance on its surface; the check covered only the surface of the track. | yes |
| E7 | Satellite imagery shows that the main flood channel has moved since the 1980s, and that flood deposits now cover more of the wadi bed; the terrace lies above the flood line. | yes |
| E8 | Since November 2020, no strike sites or explosive incidents have been recorded near the crossing, but neither party has shared where it fought. | yes |
| E9 | The north-eastern edge was added to the area "pending access": the team could not go near it under restricted-area instructions, and nobody at the meeting had been there. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | outside | 6 | - | An unassessed legacy record suggests a nearby hazard but explicitly places it upstream, outside this area. |
| E2 | direct | B | 1 | - | The EOD report documents an actual mine at a known point in B; its displacement means this supports survey of the flood-transport route rather than defining the extent. |
| E3 | absence | A | 4 | - | A first-hand herder reports repeated safe use of A since 2008, supporting absence there. |
| E4 | absence | A | 4 | - | A second first-hand family reports repeated use without finds in A, corroborating safe-use evidence. |
| E5 | indirect | B | 5 | - | The incident is approximate and its location is unknown; second-hand reporting suggests possible hazard in B but does not locate it precisely. |
| E6 | absence | B | 2 | - | Team observation supports only absence of visible EO on the track surface, not absence beneath the surface or elsewhere in B. |
| E7 | indirect | B | 2 | - | Imagery supports changing flood transport and flood-deposit coverage in B, relevant to the path of the displaced mine; it puts A above the flood line. |
| E8 | absence | all | 6 | - | An incomplete desk database reports no recent recorded incidents, but undisclosed fighting locations make this weak negative evidence. |
| E9 | not_evidence | C | 2 | - | This describes lack of access and informant knowledge, not evidence for or against EO in C; national criteria require separate access handling. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R6 | all | pass | Every part is decided once. |
| R7 | all | pass | Every evidence-log item is in the register. |
| R1 | A | pass | Every item of direct or indirect evidence is explained by evidence of absence. |
| R3 | A | pass | The national criteria for cancellation are met. |
| R4 | B | pass | Evidence to target in part B: E2, E5, E7. |
| - | C | pass | Further non-technical survey is always open to the reviewer. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, cancellation, technical_survey, further_survey, all_reasonable_effort, outcomes, national_criteria, case_file_text

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's recommendation was technical survey of the whole area; it has been considered as evidence but not followed as a decision. The split recommendation reflects the distinct evidence and accessibility of A, B and C.
  - Part C was not visited under restricted-area instructions; do not treat the lack of information there as evidence of safety or release it on that basis.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
