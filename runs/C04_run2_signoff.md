# Sign-off sheet: C04, run 2

Case: Upland village plots in a bombed valley  
Area ID: LAO-SHA-3051  
Model: gpt-6-luna

## Recommendation
- Outcome: TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend targeted cluster munition remnant survey (CMRS) for both A and B. Confirmed EOD spot tasks establish direct evidence in A, and first-hand farmers report mapped submunition finds in both parts; one mapped point is explained as a scrap dealer's yard outside the area, but this does not remove the remaining evidence. The national criteria identify these known locations as CMRS evidence points. Survey should define the confirmed hazardous areas before any clearance; clearance without CMRS is not allowed. The lack of injuries, absence of mine reports, and surface walk do not outweigh the positive evidence or establish safe use.

General guidance on the situation:

> Keep people and animals away from any suspected item or find location. Do not touch, move or try to destroy anything. Mark the place only if this can be done without going closer, and report it to the national mine action authority, survey team or police.

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
| E1 | direct | A | 3 | - | Confirmed EOD task records identify submunitions at known plots in part A, directly establishing presence. |
| E2 | direct | A, B | 4 | - | The farmers are first-hand finders and report submunitions at mapped locations in both parts; these are CMRS evidence points under the national criteria. |
| E3 | indirect | A, B | 6 | - | Historical bombing records indicate possible contamination across the area but do not directly establish remnant presence. |
| E4 | absence | outside | 5 | E2 | This second-hand account places one mapped reported-find point outside the area and explains away that point, but does not negate the other mapped finds. |
| E5 | not_evidence | all | 4 | - | No reported injuries do not establish absence of submunitions, particularly alongside continued finds and no safe-use years. |
| E6 | not_evidence | all | 4 | - | The item concerns mines, whereas the suspected hazard and reported finds are cluster munition remnants. |
| E7 | not_evidence | A, B | 2 | - | A surface walk where most plots were cropped cannot rule out buried or concealed remnants and does not contradict the mapped finds. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E2, E3. |
| R4 | B | pass | Evidence to target in part B: E2, E3. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: evidence, reliability, cancellation, technical_survey, all_reasonable_effort, outcomes, safety_guidance, national_criteria

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The village chief asked whether farmers may move items found while hoeing. Do not advise them to move items; provide only the general safety guidance above.
  - The survey team's CMRS recommendation is consistent with the evidence and national criteria, but this is a recommendation for sign-off, not a final decision.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
