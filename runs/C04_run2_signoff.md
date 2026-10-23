# Sign-off sheet: C04, run 2

Case: Upland village plots in a bombed valley  
Area ID: LAO-SHA-3051  
Model: gpt-6-luna

## Recommendation
- Outcome: SPLIT: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- By part: A=TECHNICAL_SURVEY; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend targeted cluster munition remnant survey (CMRS) in both A and B. Confirmed EOD records establish direct evidence at known plots in A, and first-hand farmers report mapped submunition finds in both A and B. The historical bombing data add context but do not themselves confirm contamination. The safe-use record is zero years in both parts; no reported injuries and a crop-obscured surface walk do not outweigh the confirmed finds. The national criteria require CMRS to define confirmed hazardous areas before clearance, so cancellation and clearance without technical survey are not supported. The split keeps the two parts separately identified while assigning the same next step.

General guidance on the situation:

> If an item is found, keep people and animals away; do not touch, move or try to destroy it. Mark the place only if this can be done without going closer, and report it to the national mine action authority, survey team or police.

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
| E1 | direct | A | 3 | - | Confirmed EOD records document submunitions at known plots in A, establishing direct evidence there; the national records are corroborated by the EOD teams. |
| E2 | direct | A, B | 4 | - | The farmers report their own finds at mapped, known places, which is first-hand direct evidence of submunitions in both parts. |
| E3 | indirect | A, B | 6 | - | Historical bombing information suggests possible contamination in the valley but does not itself confirm cluster remnants. |
| E4 | absence | outside | 4 | E2 | This identifies a mapped point as an outside-area yard containing items moved from elsewhere, so it removes that point as evidence about the reviewed plots. |
| E5 | absence | A, B | 4 | - | First-hand community sources report no injuries in the plots during this period, but this does not establish absence of EO and safe use is separately recorded as zero years. |
| E6 | not_evidence | A, B | 4 | - | This concerns mines rather than the suspected cluster munition remnants and therefore does not resolve the hazard under review. |
| E7 | absence | A, B | 2 | - | The visit found no surface items, but crops limited visibility and this observation cannot negate the confirmed mapped finds. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R6 | all | pass | Every part is decided once. |
| R7 | all | pass | Every evidence-log item is in the register. |
| R4 | A | pass | Evidence to target in part A: E1, E2, E3. |
| R4 | B | pass | Evidence to target in part B: E2, E3. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: hazard_areas, evidence, reliability, land_use, cancellation, technical_survey, clearance, further_survey, all_reasonable_effort, outcomes, national_criteria, safety_guidance, case_file_text

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The survey team's CMRS recommendation was considered alongside the underlying evidence, not treated as a decision in itself.
  - The village chief asked whether farmers may move items; no advice to move or handle items is given. Apply the general safety guidance above.
  - Before CMRS, confirm that the method is suitable given the local threat picture: the case reports no known mines, but that report alone is not a technical determination.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
