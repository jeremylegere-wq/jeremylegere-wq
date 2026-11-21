# Jeremy Legere

Python developer and technology tinkerer. I work in data and application development, with personal projects spanning software development, data tooling, algorithmic development and mathematically driven simulation engines.

My approach starts with the architecture, domain knowledge and underlying mechanics. I develop the concepts, define the requirements, explore the mathematics and algorithms, and direct implementation from design through to testing and validation.

AI-assisted development has significantly expanded what I can build. I use different tools for mathematical exploration, algorithm development, Python implementation, code review and visual creation. However, the architecture, technical direction, design decisions, testing methodology and ownership of the finished products remain mine.

I am particularly interested in turning complex ideas and real-world systems into working software, using mathematics, algorithms and iterative engineering to get beyond what conventional application development might achieve.

My projects are developed continuously, with more functionality coming over time.

Brisbane, Australia (originally Amherst, Nova Scotia). [LinkedIn](https://www.linkedin.com/in/jeremylegere/)

## Featured

| | | |
|---|---|---|
| [![hockey-manager](https://raw.githubusercontent.com/jeremylegere-wq/hockey-manager/main/docs/screenshots/office.png)](https://github.com/jeremylegere-wq/hockey-manager) | [![amherst-run](https://raw.githubusercontent.com/jeremylegere-wq/amherst-run/main/docs/images/downtown.png)](https://github.com/jeremylegere-wq/amherst-run) | [![field-service-dashboard](https://raw.githubusercontent.com/jeremylegere-wq/field-service-dashboard/main/docs/images/01-overview.png)](https://github.com/jeremylegere-wq/field-service-dashboard) |
| **[hockey-manager](https://github.com/jeremylegere-wq/hockey-manager)**<br>Single-player hockey GM simulation | **[amherst-run](https://github.com/jeremylegere-wq/amherst-run)**<br>Retro open-world driving game on real map data | **[field-service-dashboard](https://github.com/jeremylegere-wq/field-service-dashboard)**<br>[Live demo](https://jeremylegere-wq.github.io/field-service-dashboard/) of a Power BI suite, synthetic data |
| [![pm-planner](https://raw.githubusercontent.com/jeremylegere-wq/pm-planner/main/docs/images/dashboard.png)](https://github.com/jeremylegere-wq/pm-planner) | [![hockey-night](https://raw.githubusercontent.com/jeremylegere-wq/hockey-night/main/docs/images/standings.png)](https://github.com/jeremylegere-wq/hockey-night) | [![Stock Planner](https://raw.githubusercontent.com/jeremylegere-wq/Stock-Order-Forecaster/main/docs/images/order-sheet.png)](https://github.com/jeremylegere-wq/Stock-Order-Forecaster) |
| **[pm-planner](https://github.com/jeremylegere-wq/pm-planner)**<br>Maintenance planner and Gantt | **[hockey-night](https://github.com/jeremylegere-wq/hockey-night)**<br>NHL dashboard for a spare TV | **[Stock-Order-Forecaster](https://github.com/jeremylegere-wq/Stock-Order-Forecaster)**<br>Order planner for small shops |

## Repo index

Status key: **stable** = working and checked, **beta** = works but not fully verified, **early** = just uploaded, expect more work.

### Games and sims

| Repo | What it is | Status |
|---|---|---|
| [hockey-manager](https://github.com/jeremylegere-wq/hockey-manager) | Offline single-player ice hockey GM sim: contracts and cap, trades, draft, finances, 2D replay. Standard library plus SQLite, about 410 tests, CI and releases | stable |
| [amherst-run](https://github.com/jeremylegere-wq/amherst-run) | Retro open-world driving game set in Amherst, NS (Pygame, real OpenStreetMap and open data). CI, tests, releases | stable |
| [Banker-Companion-Python-App](https://github.com/jeremylegere-wq/Banker-Companion-Python-App) | Pygame banker for playing Deal or No Deal as a real-life board game (22 cases, Australian values). CI, tests, releases | stable |
| [the-chase-australia-family](https://github.com/jeremylegere-wq/the-chase-australia-family) | Offline browser family quiz game, unofficial fan project, no server or build step. 12 test scripts run in CI on Linux and Windows. CI, tests, releases | stable |
| [hockey-night](https://github.com/jeremylegere-wq/hockey-night) | Full-screen NHL dashboard for a spare screen or TV (Python standard library, Firefox kiosk). CI with a demo-data smoke test, releases | beta (live data still being verified) |

### Data and BI

| Repo | What it is | Status |
|---|---|---|
| [field-service-dashboard](https://github.com/jeremylegere-wq/field-service-dashboard) | Synthetic-data rebuild of a Power BI report suite: data model, DAX, forecasting. Single HTML file | early |
| [Qlik-Sense-Log-Viewer](https://github.com/jeremylegere-wq/Qlik-Sense-Log-Viewer) | Local Streamlit console for exploring and troubleshooting Qlik Sense logs; tests use synthetic logs. pytest suite in CI on Linux and Windows, releases | stable |
| [NZ-Post-Code-Project](https://github.com/jeremylegere-wq/NZ-Post-Code-Project) | NZ post codes with lat/long (data file only) | reference data |

### Practical tools

| Repo | What it is | Status |
|---|---|---|
| [pm-planner](https://github.com/jeremylegere-wq/pm-planner) | Planned-maintenance dashboard, drag-and-drop Gantt planner and letter engine for field service teams (synthetic demo data) | early |
| [Stock-Order-Forecaster](https://github.com/jeremylegere-wq/Stock-Order-Forecaster) | Order-quantity planner for small shops (Plotly Dash, SQLite), built for a volunteer school uniform shop | early |
| [My-Media-Wiki-Tool](https://github.com/jeremylegere-wq/My-Media-Wiki-Tool) | Block-based wiki article editor that exports wikitext or publishes back to MediaWiki | early |
| [SOP-Screen-Record-for-Edge-Chrome](https://github.com/jeremylegere-wq/SOP-Screen-Record-for-Edge-Chrome) | Bare-bones Edge/Chrome step recorder that exports documentation as HTML, PDF or Markdown, with nothing leaving your machine. Unit tests, real-browser end-to-end test, CI, reproducible builds, releases | stable |
| [EnglishTV](https://github.com/jeremylegere-wq/EnglishTV) | Curated English-language IPTV playlist with a guide file | personal use |

## How I like to build

- Python and HTML, because they're what I know and am confident enough to work with. That's the reason behind most of the choices below.
- Standard library or minimal dependencies, local-first, easy for non-technical people to run.
- SemVer, changelog, CI and tag-triggered releases where a project warrants it.
- Synthetic or open data only in public repos, with licences stated.

## To do

- Add tests and CI to the remaining early repos (field-service-dashboard, pm-planner, My-Media-Wiki-Tool).
- Verify hockey-night against live data.
