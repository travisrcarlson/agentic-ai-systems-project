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

> Recommend targeted cluster munition remnant survey (CMRS) across Parts A and B, starting from the confirmed EOD spot-task locations in A and first-hand mapped find locations in both parts. Direct evidence confirms submunitions in each part; the lack of safe-use years and limited surface observations do not support cancellation. CMRS should define the confirmed hazardous areas before clearance, which national criteria do not allow without technical survey.

General guidance on the situation:

> Keep people and animals away from any suspected item. Do not touch, move or try to destroy it. Mark the place only if this can be done without going closer, and report it to the national mine action authority, survey team or police.

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
| E1 | direct | A | 3 | - | Confirmed EOD records of destroyed submunitions at known plots establish EO presence in Part A. |
| E2 | direct | A, B | 4 | - | First-hand finders identify known locations of submunitions in both parts, which national criteria accept as CMRS evidence points. |
| E3 | indirect | all | 6 | - | Historical bombing data provide context suggesting possible contamination but do not confirm cluster munition remnants. |
| E4 | not_evidence | outside | 5 | - | The yard is outside the area and transported items there provide no evidence of contamination in the plots. |
| E5 | absence | all | 4 | - | Reports of no accidents are weak absence information and do not negate the known finds or establish safe use. |
| E6 | not_evidence | all | 4 | - | This addresses mines, not the cluster munition remnant hazard under review, and explains none of the evidence. |
| E7 | absence | A, B | 2 | - | The team's limited surface observation supports only that no items were visible during the visit, not that subsurface contamination is absent. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E2, E3. |
| R4 | B | pass | Evidence to target in part B: E2, E3. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: evidence, reliability, hazard_areas, cancellation, technical_survey, further_survey, national_criteria, safety_guidance, outcomes

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The village chief asked whether farmers may move items themselves; no handling or movement advice is provided—use only the general safety guidance above.
  - Before applying CMRS, the survey authority should verify that there is no landmine threat, as CMRS is not suitable where such a threat exists.
  - Most plots were under crops during the visit, so the absence of visible surface items is limited evidence and does not resolve contamination.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
