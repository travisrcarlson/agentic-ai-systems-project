# Sign-off sheet: C04, run 1

Case: Upland village plots in a bombed valley  
Area ID: LAO-SHA-3051  
Model: gpt-6-luna

## Recommendation
- Outcome: TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend targeted technical survey using CMRS in both parts. Confirmed EOD spot-task records provide evidence points in A, and first-hand farmers identify known find locations in both A and B; the national criteria specifically recognize these as CMRS evidence points. Define the confirmed hazardous areas before any clearance. Cancellation is not supported: both parts have zero years of safe use, and no injuries or lack of visible surface items do not negate the finds. The rule check passed.

General guidance on the situation:

> Keep people and animals away from any suspected item. Do not touch, move or try to destroy it. Mark the place only if this can be done without going closer, and report it to the national mine action authority, survey team or police. Do not resume work in affected plots until authorities advise it is safe.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | Three EOD spot tasks in 2021–2024 recorded submunitions destroyed in the valley-floor plots; the records give the plot of each find. | yes |
| E2 | On a community map, farmers marked six places in the valley-floor plots and two on the slopes where they found submunitions while hoeing in the last ten years. They reported each find to the village chief, who called the EOD team. | yes |
| E3 | Bombing data in the national database show strikes in the valley in 1969–70. | yes |
| E4 | One point on the community map is a scrap dealer's yard in the village, where people brought items they had collected in the forest years ago. | yes |
| E5 | Nobody has been hurt in the plots since 2015, according to the village chief and the women's meeting. | yes |
| E6 | No mines are reported in the village or the valley; neither the farmers nor the village chief know of any. | yes |
| E7 | The team walked the valley floor and the slopes with farmers and saw no items on the surface; most plots were under crops. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | direct | A | 3 | - | Confirmed EOD records report submunitions destroyed at known plots, directly confirming contamination at those points. |
| E2 | direct | A, B | 4 | - | Farmers who personally found the items identify known locations in each part, directly confirming EO presence there. |
| E3 | indirect | A, B | 3 | - | Historical bombing records suggest possible hazard but do not directly confirm cluster munition remnants. |
| E4 | not_evidence | outside | 5 | - | The point is outside the area and the items were moved there from elsewhere, so it says nothing about contamination inside this area. |
| E5 | not_evidence | A, B | 4 | - | Lack of injuries does not establish absence of EO and does not counter reported or recorded finds. |
| E6 | not_evidence | A, B | 4 | - | This is about mines, not the cluster munition remnant hazard at issue, and therefore does not establish absence of that hazard. |
| E7 | absence | A, B | 2 | - | The team observed no surface items, but crops limited visibility and this does not rule out contamination or explain known finds. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E2, E3. |
| R4 | B | pass | Evidence to target in part B: E2, E3. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: evidence, reliability, hazard_areas, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, safety_guidance, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team recorded the village chief’s question about moving finds; the guidance above addresses this without giving handling advice.
  - The area contains known finds in both parts; the limits of the contaminated areas are not yet defined and should be established through technical survey before clearance.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
