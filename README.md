# Jeremy Legere

Python tinkerer. I have a day job in data and application development, and I keep my personal projects here instead of leaving them on my own PC. More functionality is coming to these repos over time.

I set the requirements and domain rules, and I build with AI coding assistants under my direction.

Brisbane, Australia (originally Amherst, Nova Scotia). [LinkedIn](https://www.linkedin.com/in/jeremylegere/)

## Repo index

Status key: **stable** = working and checked, **beta** = works but not fully verified, **early** = just uploaded, expect more work.

### Games and sims

| Repo | What it is | Status |
|---|---|---|
| [hockey-manager](https://github.com/jeremylegere-wq/hockey-manager) | Offline single-player ice hockey GM sim: contracts and cap, trades, draft, finances, 2D replay. Standard library plus SQLite, about 410 tests, CI and releases | stable |
| [amherst-run](https://github.com/jeremylegere-wq/amherst-run) | Retro open-world driving game set in Amherst, NS (Pygame, real OpenStreetMap and open data). CI, tests, releases | stable |
| [Banker-Companion-Python-App](https://github.com/jeremylegere-wq/Banker-Companion-Python-App) | Pygame banker for playing Deal or No Deal as a real-life board game (22 cases, Australian values). CI, tests, releases | stable |
| [the-chase-australia-family](https://github.com/jeremylegere-wq/the-chase-australia-family) | Offline browser family quiz game, unofficial fan project, no server or build step | early |
| [hockey-night](https://github.com/jeremylegere-wq/hockey-night) | Full-screen NHL dashboard for a spare screen or TV (Python standard library, Firefox kiosk) | beta (live data still being verified) |

### Data and BI

| Repo | What it is | Status |
|---|---|---|
| [field-service-dashboard](https://github.com/jeremylegere-wq/field-service-dashboard) | Synthetic-data rebuild of a Power BI report suite: data model, DAX, forecasting. Single HTML file | early |
| [Qlik-Sense-Log-Viewer](https://github.com/jeremylegere-wq/Qlik-Sense-Log-Viewer) | Local Streamlit console for exploring and troubleshooting Qlik Sense logs; tests use synthetic logs | early |
| [NZ-Post-Code-Project](https://github.com/jeremylegere-wq/NZ-Post-Code-Project) | NZ post codes with lat/long (data file only) | reference data |

### Practical tools

| Repo | What it is | Status |
|---|---|---|
| [pm-planner](https://github.com/jeremylegere-wq/pm-planner) | Planned-maintenance dashboard, drag-and-drop Gantt planner and letter engine for field service teams (synthetic demo data) | early |
| [Stock-Order-Forecaster](https://github.com/jeremylegere-wq/Stock-Order-Forecaster) | Order-quantity planner for small shops (Plotly Dash, SQLite), built for a volunteer school uniform shop | early |
| [My-Media-Wiki-Tool](https://github.com/jeremylegere-wq/My-Media-Wiki-Tool) | Block-based wiki article editor that exports wikitext or publishes back to MediaWiki | early |
| [SOP-Screen-Record-for-Edge-Chrome](https://github.com/jeremylegere-wq/SOP-Screen-Record-for-Edge-Chrome) | Bare-bones Edge/Chrome step recorder that exports documentation | early (no README yet) |
| [EnglishTV](https://github.com/jeremylegere-wq/EnglishTV) | Curated English-language IPTV playlist with a guide file | personal use |

## How I like to build

- Python and HTML, because they're what I know and am confident enough to work with. That's the reason behind most of the choices below.
- Standard library or minimal dependencies, local-first, easy for non-technical people to run.
- SemVer, changelog, CI and tag-triggered releases where a project warrants it.
- Synthetic or open data only in public repos, with licences stated.

## To do

- Add READMEs, tests and CI to the newer repos.
- Verify hockey-night against live data.
