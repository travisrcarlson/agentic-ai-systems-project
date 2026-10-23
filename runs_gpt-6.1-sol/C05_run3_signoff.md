# Sign-off sheet: C05, run 3

Case: Leased fields beside a forest belt in a de-occupied village  
Area ID: UKR-SHA-5526  
Model: gpt-6.1-sol

## Recommendation
- Outcome: SPLIT: A=FURTHER_NTS; B=TECHNICAL_SURVEY
- By part: A=FURTHER_NTS; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend further non-technical survey for A and targeted technical survey for B, subject to human sign-off. A has only one documented year of safe farming and one first-hand safe-use source, below the national requirements of three years and two sources. The women's first-hand observations outweigh the administrator's generalized hearsay about troop activity in A, but do not establish the required safe-use history; track observations cannot exclude contamination. Further NTS should verify the spatial extent and history of use and seek independent first-hand evidence, without assuming cancellation will follow. In B, survey-recorded positions, trenches and craters, corroborated by resident testimony, provide localized indirect evidence sufficient to target TS. No direct evidence confirms EO in either part, so the team's recommendation for whole-area clearance is not justified.

General guidance on the situation:

> Pending the authority's decision, do not treat either part as released or encourage entry to establish safe use. Keep people and animals away from suspected locations; do not touch, move or try to destroy suspicious objects. Mark a location only if this can be done without going closer, and report concerns to the responsible authorities.

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
| E1 | indirect | A, B | 6 | - | An unvalidated settlement record of troop presence supports suspicion, not confirmed contamination or a defined hazard. |
| E2 | indirect | A, B | 7 | - | The allegation rests on troop presence and hearsay from residents not identified as first-hand witnesses, rather than verified EO. |
| E3 | absence | A | 4 | E1, E2 | The leaseholder's first-hand account provides limited counterevidence for A only, with one safe-use year and one source insufficient for national cancellation criteria. |
| E4 | indirect | B | 2 | - | Survey-recorded positions and craters localize suspected contamination in B but do not confirm EO under the national criteria. |
| E5 | absence | A | 4 | E1, E2 | First-hand witnesses counter the generalized troop-presence inference for A, while their account of digging in B corroborates E4 without confirming EO or additional years of safe farming. |
| E6 | absence | A, B | 2 | - | Direct team observation offers limited negative evidence on A's tracks and B's edge only, not a search capable of excluding contamination across either part. |

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
- Rule topics looked up: national_criteria, reliability, cancellation, technical_survey, evidence, further_survey, land_use, outcomes

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The team's whole-area clearance recommendation is not supported by direct evidence and has not been adopted.
  - Imagery and track photographs are listed but not reproduced; this review relies on the recorded observations rather than independent inspection of the images.
  - E5 has different implications by part: it counters the troop-presence inference in A and corroborates the indirect evidence in B; neither implication confirms EO.
  - E6 covers field tracks and the forest-belt edge only; it does not establish absence across B or all of A.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
