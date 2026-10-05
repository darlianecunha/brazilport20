# Brazil Ports & Terminals Explorer

**Cargo and berthings at Brazilian port installations, 2021-2025: a top-20 ranking with detailed profiles, a side-by-side comparison tool and a table covering every facility reported by ANTAQ**

[![Live site](https://img.shields.io/badge/Live-brazilport20.vercel.app-2ea44f)](https://brazilport20.vercel.app)
[![Part of Brazil Port Data](https://img.shields.io/badge/Part%20of-brazilportdata.com-0b2239)](https://www.brazilportdata.com)
[![Data DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23158267.svg)](https://doi.org/10.5281/zenodo.23158267)

## What this is

An interactive dashboard of cargo movement in Brazilian ports and private terminals, built on official statistics from ANTAQ, Brazil's waterway regulator. It answers the questions port managers, analysts and researchers ask first: which installations move the most cargo, how they changed over five years, and how two or three of them compare.

| Indicator (2025) | Value |
|---|---|
| Total cargo, all facilities | 1,403 Mt |
| Facilities covered | 211 |
| Cargo of the 20 largest installations | 1.01 billion t |
| Largest installation | Ponta da Madeira Marine Terminal (MA) |

## What the page shows

| Tab | Content |
|---|---|
| **Overview** | Headline figures, cargo trend 2021-2025 for the top five, 2025 ranking of the top 20 (all, public ports or terminals); click a bar to open a port profile |
| **Compare** | Up to three installations side by side: cargo trend and 2025 totals |
| **Data** | Every facility reported by ANTAQ, 2023-2025, filterable by public ports and private terminals |
| **About** | Scope, sources and method |

## Method notes

- **Source:** ANTAQ *Estatístico Aquaviário*, full calendar years 2021-2025, extracted from the ANTAQ statistical panel in September 2026.
- **Definition:** cargo and berthings follow ANTAQ's definition of port movement (authorised cargo operations), so national totals match the agency's public panel.
- **Scope:** all navigation types (deep sea, cabotage, inland waterway and port support). Totals are therefore higher than those of the [Brazil Port Call Monitor](https://github.com/darlianecunha/brazilPortcallmonitor), which covers deep-sea and cabotage cargo calls only (1,316 Mt in 2025).
- **Updates:** refreshed monthly from the ANTAQ panel with the same scripts that update the other Brazil Port Data panels.

## Repository map

| Path | Content |
|---|---|
| `index.html` | The whole application: page, aggregated data and charts in one file |

Annual series by installation are available as an open dataset: [Brazil Port Data: consolidated ANTAQ port statistics, 2010-2026](https://doi.org/10.5281/zenodo.23158267) (ODbL).

## Related projects

- [brazilportdata](https://github.com/darlianecunha/brazilportdata): the hub site for all Brazil Port Data panels
- [antaq-port-statistics](https://github.com/darlianecunha/antaq-port-statistics): the open dataset behind the annual series
- [brazilPortcallmonitor](https://github.com/darlianecunha/brazilPortcallmonitor): waiting time, time at berth and vessel size by installation
- [port-emissions-mcp](https://github.com/darlianecunha/port-emissions-mcp): MCP server that lets Claude query the same ANTAQ tables

## Author and licence

**Darliane Ribeiro Cunha, PhD**. [ribeirocunha.com](https://ribeirocunha.com) · [ORCID 0000-0003-2548-1237](https://orcid.org/0000-0003-2548-1237)

Page and analysis: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Data: ANTAQ open data.
