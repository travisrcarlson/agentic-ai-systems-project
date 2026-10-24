# Reviewing Land Release Cases with an AI Agent

An AI agent that reviews land release cases in humanitarian mine action. For one suspected hazardous area at a time, it reads the area's case file through tools, records each piece of evidence in a register, and tests its recommendation against the land release rules of the International Mine Action Standards (IMAS 07.11, 08.10 and 08.20, and the technical note TNMA 08.20/02) and the case's national criteria. It then recommends what should happen to each part of the area: cancellation, technical survey, clearance, or more non-technical survey. A rule check written in code can veto a recommendation, and a person signs off every one: the agent never decides. It is built on the OpenAI API with function calling, without an agent framework, and was run three times on each of fourteen invented case files set in real countries and territories.

Land release decides when people can go back onto land. Cancel an area that still holds mines, and the people who trust it can be killed; clear land that holds none, or leave it locked, and scarce money and land are wasted. Before a national mine action authority accepts a survey team's recommendation, quality control has to check that the evidence supports it. The agent does a first pass of that check and lays the evidence out, so that the person who signs off checks the evidence, not only the recommendation. It gives no advice on handling items: that should be done by technical experts. This is the sixth project of my AI capstone on humanitarian mine action.

## Result
In the full run, which I made on my own computer on 23 October 2026 (42 runs of `gpt-6-luna` at medium reasoning effort), the agent gave the expected outcome on every part of the area in 28 runs (67%), and on 69 of the 90 part-decisions (77%). Eleven of the fourteen cases got the same recommendation in all three runs. It never cancelled a part that needs action, and it cancelled all 24 parts where cancellation was expected. Where it differed, it chose more survey, not less: technical survey instead of clearance in 16 part-decisions, where a few located finds confirmed a hazard but did not define its extent, and more non-technical survey instead of technical survey in 5, where the evidence was too thin to target a survey. I confirmed each case's expected outcome before the run, and I judged all 21 differences acceptable calls that I would sign off. The agent flagged an instruction planted in one case file in all three of its runs and did not follow it, and in the eight cases where the survey team recommended a different step from the expected outcome, it followed the team in none of its runs. Of the coded safeguards, only the scan for instructions acted in the live runs, putting the planted line on C09's sign-off sheets as built. The others never had to (no veto, no failed quote, no advice removed, no fallback to a person), so how they work is shown by the notebook's tests with a scripted stand-in model. The whole run took 23 minutes and cost at most USD 0.18.

A comparison run with the larger `gpt-6.1-sol`, with the same code and files, agreed on every part in 30 of 42 runs (71%) and on 75 of 90 part-decisions (83%), and gave the same recommendation in all three runs of every case, at about 14 times the cost (USD 2.63 at most). It recommended clearance in C07 and C09, but kept technical survey in C08 and on C13's recorded minefield and sent the same thin evidence in C03 and C05 back for more survey, which points to how the evidence and the national criteria are written rather than to the small model alone. Each of its 15 differing part-decisions gives a part an outcome that I judged acceptable in the full run.

## What's in this repository
- `agentic_system.ipynb`: the task and its scope; the architecture, with the diagram and the design choices; setup; the case files and rules; the five tools; the evidence register, which is the agent's memory; the safeguards; the agent loop, with a single agent step and tests of every safeguard with the stand-in model; the runs, with traces of five cases; the evaluation, with a comparison with a larger model; failure cases and limitations; and a summary.
- `module_summary.pdf`: the report, the Agentic AI System Design Report, in APA 7 format. The same file is also saved as `Agentic_AI_System_Design_Report.pdf` and `Agentic_AI_Systems_Analysis_Report.pdf`, the two other names the brief uses.
- `cases/`: the fourteen case files, C01 to C14, and `expected_outcomes.csv`, the expected outcome for each part of each case, with the reason, which the agent is scored against.
- `rules/land_release_rules.md`: the rules the agent looks up, paraphrased from IMAS 07.11, 08.10 and 08.20 and TNMA 08.20/02 with their section numbers, and the project's own rules, marked as such.
- `prompts/system_prompt.md`: the agent's persona and instructions.
- `runs/`: the full run. For each of the 42 runs: the trace of every model output and tool call (`_trace.jsonl`), the sign-off sheet a person reads before deciding (`_signoff.md`) and the result row (`_result.json`). Also `results.csv`, with all 42 rows, and `run_info.json`, with the model, the settings, the time the run finished and the SHA-256 checksum of every case, rules and prompt file.
- `runs_gpt-6.1-sol/`: the comparison run with the larger `gpt-6.1-sol`, in the same form as `runs/`.
- `tests/reference_registers.json`: a reference evidence register for each case, used only by the stand-in tests (section 8.4) and the table of the outcomes the rule check allows (section 8.5), not to score the agent.
- `figures/`: the architecture diagram, the chart of agreement by case, and the chart comparing the two models.
- `requirements.txt`: the Python environment, from `pip freeze`.

## Case files and sources
No public set of real land release case files exists, and this repository is public, so the case files are invented. Each is set in a real country or territory, with the kinds of evidence that public sources report there, but the area, its ID, the people (named by role only), the survey and the national criteria box are invented. The files hold no coordinates, no boundaries, no names and no technical detail of munitions. Each holds the same eight sections, so the agent can read it a section at a time, and a national criteria box, because IMAS sets no numbers such as the years of safe use that allow cancellation.

| Case | Country or territory | The area | Expected outcome |
|---|---|---|---|
| C01 | Bosnia and Herzegovina | Hillside meadows below a former front line | Cancel |
| C02 | Sri Lanka | Resettled gardens and paddy near a former army position | Cancel |
| C03 | Cambodia | Border farmland with a strip along the forest edge | Split: cancel the fields; technical survey of the strip |
| C04 | Lao PDR | Upland village plots in a bombed valley | Technical survey |
| C05 | Ukraine | Leased fields beside a forest belt in a de-occupied village | Technical survey |
| C06 | Zimbabwe | The far margin of a border minefield's hazardous area | Technical survey |
| C07 | Angola | A road and river crossing by a former military position | Clearance |
| C08 | Iraq | Village outskirts along a former defensive berm | Clearance |
| C09 | Afghanistan | Mountain terraces below a former outpost | Clearance |
| C10 | South Sudan | Farmland near an old garrison road | Further non-technical survey |
| C11 | Western Sahara | A wadi crossing east of the berm | Split: cancel the terrace; technical survey of the wadi bed; further non-technical survey of the edge by a restricted area |
| C12 | Republic of Korea | A slope below a former position in the Civilian Control Zone | Split: technical survey of the slope and the gully; cancel the paddy fields |
| C13 | Peru | A recorded minefield and a landslide below it in the Cordillera del Cóndor | Split: clearance of the recorded minefield; technical survey of the landslide slope |
| C14 | Thailand | Border farmland, a legacy minefield and a strip near a recent clash site | Split: cancel the farmland; clearance of the minefield; further non-technical survey of the strip |

The settings come from the public sources below, found by web research on 22 and 23 October 2026, with the dates the pages showed. The case files and the rules put them in this project's words.

**The standards.** The IMAS are owned and copyrighted by the United Nations and published at https://www.mineactionstandards.org/standards/.
- IMAS 07.11 *Land release*, second edition, 16 January 2026: https://www.mineactionstandards.org/standards/07-11/
- IMAS 08.10 *Non-technical survey*, first edition, amendment 4, February 2019: https://www.mineactionstandards.org/standards/08-10/
- IMAS 08.20 *Technical survey*, first edition, amendment 4, February 2019: https://www.mineactionstandards.org/standards/08-20/
- TNMA 08.20/02 *Cluster munition remnant survey*, first edition, 23 January 2024: https://www.mineactionstandards.org/standards/08-20-02/

**The country and territory contexts.** Landmine Monitor is published by the International Campaign to Ban Landmines – Cluster Munition Coalition, and Mine Action Review by Norwegian People's Aid; *Clearing the Mines 2025* is Mine Action Review's report unless another is named.
- C01, Bosnia and Herzegovina:
  - Landmine Monitor, country profile, updated 10 May 2026: https://the-monitor.org/country-profile/bosnia-and-herzegovina/contamination-land-release-risk-education
  - Mine Action Review, *Clearing the Mines 2025*: https://www.mineactionreview.org/assets/downloads/BiH_Clearing_the_Mines_2025.pdf
  - Norwegian People's Aid, Bosnia and Herzegovina: https://www.npaid.org/mine-action-and-disarmament/where-we-work/bosnia-and-herzegovina
- C02, Sri Lanka:
  - Landmine Monitor, country profile, undated: https://the-monitor.org/country-profile/sri-lanka/contamination-land-release-risk-education
  - Mine Action Review, *Clearing the Mines 2025*: https://www.mineactionreview.org/assets/downloads/Sri_Lanka_Clearing_the_Mines_2025.pdf
  - The HALO Trust, final report to AusAID, 2012: https://www.dfat.gov.au/sites/default/files/sri-lanka-halo-report.pdf
- C03, Cambodia:
  - Landmine Monitor, country profile, updated 18 April 2026: https://the-monitor.org/country-profile/cambodia/contamination-land-release-risk-education
  - Mine Action Review, *Clearing the Mines 2025*: https://www.mineactionreview.org/assets/downloads/Cambodia_Clearing_the_Mines_2025.pdf
- C04, Lao PDR:
  - Landmine Monitor, country profile, updated 28 December 2025: https://the-monitor.org/country-profile/lao-pdr/impact
  - Mine Action Review, *Clearing Cluster Munition Remnants 2026*: https://www.mineactionreview.org/assets/downloads/Clearing_CMR_2026_Lao_PDR.pdf
- C05, Ukraine:
  - Landmine Monitor, country profile, updated 26 April 2026: https://the-monitor.org/country-profile/ukraine/contamination-land-release-risk-education
  - Mine Action Review, *Clearing the Mines 2025*: https://www.mineactionreview.org/assets/downloads/Ukraine_Clearing_the_Mines_2025.pdf
  - Mine Action Review, *Clearing Cluster Munition Remnants 2026*: https://www.mineactionreview.org/assets/downloads/Clearing_CMR_2026_Ukraine.pdf
  - The HALO Trust, "From farmers' fields to minefields", 16 October 2022: https://www.halotrust.org/us/news/from-farmers-fields-to-minefields/
  - The HALO Trust, "Update from HALO Ukraine, summer 2024", 7 August 2024: https://www.halotrust.org/us/news/update-from-halo-ukraine-summer-2024/
  - United Nations in Ukraine, "From Clearance to Outcomes", 11 June 2026: https://ukraine.un.org/en/317120-clearance-outcomes-rethinking-mine-action-ukraine
- C06, Zimbabwe:
  - Landmine Monitor, country profile, updated 7 April 2026: https://the-monitor.org/country-profile/zimbabwe/contamination-land-release-risk-education
  - Mine Action Review, *Clearing the Mines 2025*: https://www.mineactionreview.org/assets/downloads/Zimbabwe_Clearing_the_Mines_2025_final.pdf
- C07, Angola:
  - Landmine Monitor, country profile, updated 3 February 2026: https://the-monitor.org/country-profile/angola/impact
  - Mine Action Review, *Clearing the Mines 2025*: https://www.mineactionreview.org/assets/downloads/Angola_Clearing_the_Mines_2025.pdf
  - MAG, Angola: https://www.maginternational.org/what-we-do/where-we-work/angola/
  - The HALO Trust, Angola: https://www.halotrust.org/us/where-we-work/africa/angola/
- C08, Iraq:
  - Landmine Monitor, country profile, updated 7 January 2026: https://the-monitor.org/country-profile/iraq/contamination-land-release-risk-education
  - Mine Action Review, *Clearing the Mines 2025*: https://www.mineactionreview.org/assets/downloads/Iraq_Mines_2025.pdf
- C09, Afghanistan:
  - Landmine Monitor, country profile, updated 7 April 2026: https://the-monitor.org/country-profile/afghanistan/contamination-land-release-risk-education
  - Mine Action Review, *Clearing the Mines 2025*: https://www.mineactionreview.org/assets/downloads/Afghanistan_Clearing_the_Mines_2025.pdf
- C10, South Sudan:
  - Landmine Monitor, country profile, undated: https://the-monitor.org/country-profile/south-sudan/contamination-land-release-risk-education
  - Mine Action Review, *Clearing the Mines 2025*: https://www.mineactionreview.org/assets/downloads/South_Sudan_Clearing_the_Mines_2025_final.pdf
  - South Sudan's National Mine Action Authority and UNMAS, *National Technical Standards and Guidelines*, Part 1, 20 November 2025: https://unmas.org/sites/default/files/ntsg_south_sudan_-_part_1_-_demining_-_november_2025.pdf
- C11, Western Sahara:
  - UNMAS, Territory of Western Sahara, updated 10 June 2026: https://unmas.org/en/where-we-work/territory-of-western-sahara
  - MINURSO, Mine action, updated 9 December 2025: https://minurso.unmissions.org/en/mine-action
  - Mine Action Review, Western Sahara: https://www.mineactionreview.org/country/western-sahara and https://www.mineactionreview.org/country/western-sahara/anti-personnel-mines
  - Landmine Monitor 2025, 1 December 2025: https://the-monitor.org/online-reader/landmine-monitor-2025
  - International Campaign to Ban Landmines, "Floods intensify landmine threat in Western Sahara", October 2015, via ReliefWeb: https://reliefweb.int/report/western-sahara/floods-intensify-landmine-threat-western-sahara
- C12, Republic of Korea:
  - Landmine Monitor 2001, South Korea: http://archives.the-monitor.org/index.php/publications/display?url=lm/2001/south_korea/
  - Seoul Economic Daily, 1 October 2026: https://en.sedaily.com/politics/2026/10/01/two-million-landmines-litter-koreas-front-lines-most
  - Stars and Stripes, 30 September 2026: https://www.stripes.com/theaters/asia_pacific/2026-09-30/north-korea-mines-dmz-armistice-23012081.html
  - Stars and Stripes, 6 October 2026: https://www.stripes.com/theaters/asia_pacific/2026-10-06/north-korea-landmines-dmz-border-23069075.html
  - The Japan Times, 5 October 2026: https://www.japantimes.co.jp/news/2026/10/05/asia-pacific/south-korea-probe-north-mines/
  - Yoo, L.-S., Lee, J.-H., Lee, Y.-K., Jung, S.-K., & Choi, Y. (2021). Application of a drone magnetometer system to military mine detection in the demilitarized zone. *Sensors, 21*(9), 3175: https://doi.org/10.3390/s21093175
- C13, Peru:
  - Mine Action Review, Peru, 2025: https://www.mineactionreview.org/country/peru/anti-personnel-mines
  - Landmine Monitor, Ecuador, undated: https://the-monitor.org/country-profile/ecuador/impact
  - Anti-Personnel Mine Ban Convention, analysis of Ecuador's extension request, 2025: https://www.apminebanconvention.org/fileadmin/_APMBC-DOCUMENTS/Meetings/2025/22MSP-Ecuador-Analysis-en.pdf
  - MercoPress, 11 December 2016: https://en.mercopress.com/2016/12/11/global-de-mining-conference-in-chile-concerned-over-growing-use-of-improvised-landmines
- C14, Thailand:
  - Mine Action Review, *Clearing the Mines 2022* and *2024*, Cambodia: https://www.mineactionreview.org/assets/downloads/Cambodia_Clearing_the_Mines_2022.pdf and https://www.mineactionreview.org/assets/downloads/Cambodia_Clearing_the_Mines_2024.pdf
  - Thailand's request to extend its Article 5 deadline, 12 June 2026: https://www.apminebanconvention.org/fileadmin/_APMBC-DOCUMENTS/Meetings/2026/23MSP-Thailand-Art5-ExtReq.pdf
  - Ministry of Foreign Affairs of Thailand, statement, undated: https://www.mfa.go.th/en/content/th-responses-ottawa-convention-eng
  - Al Jazeera, 11 November 2025: https://www.aljazeera.com/news/2025/11/11/cambodia-denies-thai-landmine-claims-as-truce-hangs-in-the-balance
  - Nation Thailand, 6 December 2025: https://www.nationthailand.com/news/world/40059311

C14 records the two governments' accounts of the 2025 mine injuries with their sources and takes no side; C11 uses "east of the berm" and "west of the berm" for the same reason.

## How to run
Needs Python 3.13 and Git. `requirements.txt` was generated on Python 3.13.0.

```
git clone https://github.com/travisrcarlson/agentic-ai-systems-project.git
cd agentic-ai-systems-project
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook agentic_system.ipynb
```

On macOS or Linux, activate with `source .venv/bin/activate`. If PowerShell blocks the activation script, run `Set-ExecutionPolicy -Scope CurrentUser RemoteSigned` once. In Jupyter, choose **Kernel > Restart Kernel and Run All Cells**.

**Without an API key**, the notebook runs everything except the calls to the model, in a few seconds. It tests the tools and safeguards with the scripted stand-in model, and sections 9 to 11 read the saved full run from `runs/`, which gives the same tables, traces and chart as the executed notebook.

**With an OpenAI API key**, set it once as an environment variable named `OPENAI_API_KEY`, then start Jupyter from a new terminal. On Windows: open Start, search for "Edit environment variables for your account", and add it under User variables. On macOS or Linux: `export OPENAI_API_KEY=...` in the terminal before starting Jupyter. Never put the key in the notebook or the repository; the notebook reads it from the environment and never prints or saves it. With a key:
- Section 8.3 sends one request to the model and shows the tool calls it asks for.
- Section 9 keeps the 42 saved runs, because they were made with the same model and the same case, rules and prompt files (`RESUME = True` in the settings cell). It rewrites only `results.csv`, unchanged, and the finish time in `run_info.json`.
- To run the agent again, set `RESUME = False`. The new runs overwrite `runs/`. The full run took 23 minutes and cost at most USD 0.18 at the prices of 23 October 2026 (USD 0.10 per million input tokens and USD 0.50 per million output tokens for `gpt-6-luna`). `SMOKE_TEST = True` first runs three cases once each, into `runs_smoke/`.
- To use another model, change `MODEL` and add its prices to `PRICES`. It must support function calling on the OpenAI Responses API. Section 10.1 says how the comparison run with `gpt-6.1-sol` was made; it only reads the saved runs.

The model's answers vary from run to run, which is why each case runs three times, so a new run will not repeat the saved recommendations exactly.

## How this project was made
I chose the use case, the approach, the outcomes the agent may recommend and the contexts of the case files. I set the line on advice about handling items and the checks before sign-off, confirmed the expected outcome of every case before the run, and judged where the agent differed from them. I made the full run saved in `runs/` on my own computer. Claude (Anthropic) researched the sources, wrote the case files, the rules, the prompt and the notebook, and tested them with the stand-in model. At my request, Claude also made the smoke tests and the comparison run with `gpt-6.1-sol` in its own workspace with my OpenAI API key, and an earlier full run, which mine replaced.
