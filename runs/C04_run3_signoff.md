# Sign-off sheet: C04, run 3

Case: Upland village plots in a bombed valley  
Area ID: LAO-SHA-3051  
Model: gpt-6-luna

## Recommendation
- Outcome: TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend targeted cluster munition remnant survey (CMRS) across both parts, starting from the confirmed EOD spot-task locations in A and the mapped first-hand find locations in A and B. These findings are direct evidence of submunitions in both parts. Historic bombing and the absence of reported injuries or visible surface items do not outweigh the finds; reported safe use is zero years, below the national five-year cancellation criterion. National criteria require CMRS to define the hazard areas before clearance.

General guidance on the situation:

> Keep people and animals away from any suspected item. Do not touch, move or try to destroy it. Mark the place only if this can be done without going closer, and report it to the national mine action authority, survey team or police.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | Three EOD spot tasks in 2021–2024 recorded submunitions destroyed in the valley-floor plots; the records give the plot of each find. | yes |
| E2 | On a community map, farmers marked six places in the valley-floor plots and two on the slopes where they found submunitions while hoeing in the last ten years. | yes |
| E3 | Bombing data in the national database show strikes in the valley in 1969–70. | yes |
| E4 | One point on the community map is a scrap dealer's yard in the village, where people brought items they had collected in the forest years ago. | yes |
| E5 | Nobody has been hurt in the plots since 2015, according to the village chief and the women's meeting. | yes |
| E6 | No mines are reported in the village or the valley; neither the farmers nor the village chief know of any. | yes |
| E7 | The team walked the valley floor and the slopes with farmers and saw no items on the surface; most plots were under crops. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | direct | A | 3 | - | Confirmed EOD records of submunitions at known plots establish direct evidence in Part A. |
| E2 | direct | A, B | 4 | - | First-hand finders report submunitions at specific mapped plots in both parts, giving direct evidence and CMRS evidence points. |
| E3 | indirect | all | 6 | - | Historical bombing records indicate possible contamination and help survey planning, but are not direct evidence of cluster munition remnants. |
| E4 | not_evidence | outside | 5 | - | These moved items are at the scrap yard outside the reviewed area and say nothing about EO presence in the plots. |
| E5 | absence | all | 4 | - | First-hand community sources report no accidents, but accident-free use does not negate the mapped finds or establish safe use. |
| E6 | not_evidence | all | 4 | - | Reports concern mines, whereas the suspected and confirmed hazard here is cluster munition remnants. |
| E7 | absence | A, B | 2 | - | The team observed no surface items, but crops limited visibility and this does not outweigh confirmed finds or establish subsurface absence. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E2, E3. |
| R4 | B | pass | Evidence to target in part B: E2, E3. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: evidence, reliability, hazard_areas, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, national_criteria, safety_guidance, case_file_text

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team recommends CMRS from evidence points; this recommendation was reviewed alongside the evidence, not treated as a decision.
  - The village chief asked whether farmers may move found items. No handling or moving advice is given; use the general safety guidance above.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
