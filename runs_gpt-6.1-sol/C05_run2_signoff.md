# Sign-off sheet: C05, run 2

Case: Leased fields beside a forest belt in a de-occupied village  
Area ID: UKR-SHA-5526  
Model: gpt-6.1-sol

## Recommendation
- Outcome: SPLIT: A=FURTHER_NTS; B=TECHNICAL_SURVEY
- By part: A=FURTHER_NTS; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: high

Agent's summary:

> Recommend further non-technical survey for A and targeted technical survey for B. In A, the first-hand residents' accounts outweigh the administrator's hearsay, and cultivation provides limited evidence of absence; however, only one year of safe use and one first-hand safe-use source are established, below the national requirements of three years and two sources. Track observations do not establish absence throughout A. Further NTS should clarify the geographic extent of troop activity and land use and seek independent first-hand corroboration, without assuming cancellation will become justified. In B, survey-observed positions, trenches and craters, corroborated by residents, provide localized indirect evidence suitable for targeting TS. There is no direct evidence to justify immediate clearance of either part. The whole-area clearance recommendation is therefore not supported. Both required community groups were consulted.

General guidance on the situation:

> Pending authority review and any subsequent release, do not treat either part as declared safe. Keep people and animals away from suspected locations; do not touch, move or try to destroy any suspicious item. Mark a location only if this can be done without going closer, and report it to the authorities.

## Check 1: is each cited item in the file?
| Item | Quote | Found in the item's row |
|---|---|---|
| E1 | The 2023 record lists the area as suspected because troops were present in the village in 2022; no items, accidents or positions in the area were recorded. | yes |
| E2 | He was not in the village during the occupation and repeats what residents told him. | yes |
| E3 | I harvested wheat on the open fields in 2025 with my own machinery. Nothing happened. I kept away from the forest belt. | yes |
| E4 | Drone imagery shows old fighting positions and trenches along the forest belt, and several craters in the strip along its edge; no items were visible in the imagery. | yes |
| E5 | Two women who stayed in the village during the occupation said that soldiers dug in along the forest belt but did not go onto the open fields, which were in view of the village. | yes |
| E6 | The team walked the field tracks and saw no items, signs or fencing. It did not enter the forest belt. | yes |

## Check 2: how each item was classed
| Item | Class | Parts | Reliability class | Explains | Agent's note |
|---|---|---|---|---|---|
| E1 | indirect | A, B | 6 | - | The unvalidated settlement record supplies only indirect evidence based on past troop presence, not confirmation of contamination. |
| E2 | indirect | A, B | 7 | - | The allegation rests on troop-presence hearsay from residents not identified as first-hand witnesses, rather than a witnessed find. |
| E3 | absence | A | 4 | E1, E2 | First-hand uneventful cultivation weakens the general suspicion for A, but one season and one source do not meet national cancellation requirements. |
| E4 | indirect | B | 2 | - | Survey-observed positions and craters locate an indirect hazard indication in B, while no visible items confirm EO. |
| E5 | absence | A | 4 | E1, E2 | First-hand accounts counter generalized troop-presence suspicion in A and also corroborate E4's indirect indication in B, but do not establish safe use of A. |
| E6 | absence | A, B | 2 | - | The team's negative observations provide limited support only along visited tracks and B's edge, not proof of absence across either part or within the forest belt. |

## Check 3: the decision against IMAS and the national criteria
| Rule | Part | Result | Detail |
|---|---|---|---|
| R6 | all | pass | Every part is decided once. |
| R7 | all | pass | Every evidence-log item is in the register. |
| - | A | pass | Further non-technical survey is always open to the reviewer. |
| R4 | B | pass | Evidence to target in part B: E1, E2, E4. |

## Check 4: what the agent did not use
- Evidence items not in the register: none
- Sections of the case file not read: none
- Rule topics looked up: national_criteria, reliability, evidence, cancellation, technical_survey, further_survey, all_reasonable_effort

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - Recommendation only; requires an authorized person's review and sign-off.
  - The team's whole-area clearance recommendation was assessed, not adopted: the evidence is indirect.
  - E5 has two implications: evidence of absence concerning troop activity in A and corroboration of indirect evidence in B; its register classification captures the A implication.
  - Negative observations in E6 cover field tracks and the edge of B only; the forest belt was not entered.
  - Drone imagery and photographs are referenced but not reproduced; the reviewer relied on their descriptions and sign-off should verify the supporting records.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
