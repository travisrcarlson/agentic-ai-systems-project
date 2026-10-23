# Sign-off sheet: C05, run 1

Case: Leased fields beside a forest belt in a de-occupied village  
Area ID: UKR-SHA-5526  
Model: gpt-6.1-sol

## Recommendation
- Outcome: SPLIT: A=FURTHER_NTS; B=TECHNICAL_SURVEY
- By part: A=FURTHER_NTS; B=TECHNICAL_SURVEY
- Rule check: pass
- Agent's confidence: medium

Agent's summary:

> Recommend separate treatment for human sign-off. In A, first-hand residents' accounts weaken the blanket troop-presence suspicion, but farming is documented for only one year by one safe-use witness, below the national three-year/two-source requirements. Track observations are limited; further NTS should clarify activity locations, the extent and history of field use, and remaining grounds for suspicion rather than assume safety or commit untargeted TS. In B, team-recorded positions, trenches and craters, corroborated by residents, provide localized indirect evidence suitable for targeted technical survey. No direct evidence confirms EO, so whole-area clearance is not justified. All six evidence items were assessed and the split passed the rule check.

General guidance on the situation:

> Pending the authority's decision, keep people and animals away from suspected places. Do not touch, move or try to destroy any suspected item. Mark a location only if this can be done without going closer, and report it to the national mine action authority, survey team or police.

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
| E1 | indirect | A, B | 6 | - | The unvalidated settlement record provides only indirect evidence from past troop presence, not confirmed contamination in either part. |
| E2 | indirect | A, B | 7 | - | The allegation suggests a hazard but rests on hearsay whose original sources are not identified as first-hand witnesses. |
| E3 | absence | A | 4 | E1, E2 | First-hand safe farming weakens the general suspicion in A only, but one season and one safe-use witness do not meet national cancellation criteria. |
| E4 | indirect | B | 2 | - | Team-recorded fighting positions and craters provide physical indirect evidence in B, while lack of visible items does not exclude contamination. |
| E5 | absence | A | 4 | E1, E2 | First-hand witnesses localize troop activity away from A, weakening its blanket suspicion; their account also corroborates the indirect evidence of positions in B but does not establish safe use in A. |
| E6 | absence | A, B | 2 | E1, E2 | Negative team observations offer limited support only on the visited tracks and B's edge, not proof of absence throughout either part or an explanation of the positions and craters in E4. |

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
- Rule topics looked up: national_criteria, reliability, evidence, cancellation, technical_survey, further_survey, land_use, outcomes, safety_guidance

## Flags
- Instruction-like text that the code found in the case file: none
- Flags reported by the agent:
  - The team's recommendation for whole-area clearance is not supported by direct evidence and has not been adopted.
  - E5 has different implications by part: evidence weakening suspicion in A and corroboration of fighting positions in B; it is not a second confirmation of safe farming.
  - E6 covers field tracks and the edge of B only; the forest belt was not entered.
  - Referenced drone imagery and photographs were not reproduced in the file supplied and could not be independently inspected.
  - This is a recommendation only; release or tasking requires human review and sign-off.
- Advice on handling items removed: none
- Vetoes during the run: none
- Quote check failures: 0; tool errors: 0

## Sign-off

Reviewer: ______________________  
Decision: agree / disagree / return for more survey  
Date: ______________

*This recommendation comes from an AI agent. It is not final until a person signs it off.*
