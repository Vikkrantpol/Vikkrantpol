<div align="center">

```text
                          ╔══════════════════════════════════════════════════════════════╗
                          ║              VIKKRANT POL · OPTIMUS QUANTA                    ║
                          ║   IIT Goa · Quant Research Infrastructure · Risk Analytics   ║
                          ╚══════════════════════════════════════════════════════════════╝
```

**Founder, Optimus Quanta · Quant Research Infrastructure · Systematic Market Workflows · Risk Analytics**
*Building private infrastructure for systematic market research, validation, risk analysis, and live operations.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vikkrant_Pol-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/vikkrantpol)
[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![React](https://img.shields.io/badge/React-Vite-61DAFB?style=flat-square&logo=react&logoColor=black)](https://react.dev)
[![Next.js](https://img.shields.io/badge/Next.js-14-000000?style=flat-square&logo=nextdotjs)](https://nextjs.org)
[![NSE](https://img.shields.io/badge/NSE-F%26O-1F4E79?style=flat-square)](https://nseindia.com)
[![MCX](https://img.shields.io/badge/MCX-Commodities-B8860B?style=flat-square)](https://mcxindia.com)

</div>

---

## About

> *"Markets are information. Infrastructure is alpha."*

I'm **Vikkrant Pol**, an IIT Goa graduate and the founder-builder of **Optimus Quanta**, a private quant research and trading infrastructure system.

I build systems for **systematic market research, backtesting, risk analytics, scanners, dashboards, and live-operations infrastructure** across derivatives, commodities, equities, and related market workflows.

My work is domain-led and infrastructure-focused: translating research questions into repeatable data workflows, validation tooling, monitoring surfaces, risk controls, and operational systems. AI serves as a research and development accelerator within that process, while market judgment, system design, validation standards, and operational responsibility remain central.

My conviction is simple: robust quant infrastructure should not be reserved only for institutions.

---

## Optimus Quanta — Private Quant Research Infrastructure

A private multi-module trading system designed around research, monitoring, analytics, and execution support.

This stack grew out of years of market R&D and hands-on trading work. It is developed iteratively with AI-assisted research and engineering workflows that accelerate implementation while preserving ownership of research direction, system design, validation, debugging, and operational decisions.

The software exists to serve the trading edge, not the other way around. The alpha thesis, rule design, and practical constraints come first; the code is the vehicle that makes those ideas usable.

| Module | Description |
| :--- | :--- |
| Live Broker Integration | Real-time order management and broker connectivity |
| Multi-Market Workflow | NSE equities/F&O, MCX commodities, and related research tooling |
| Backtesting Engine | Strategy validation, simulation, and performance analysis |
| Strategy Architecture | Modular workflow design for reusable signal and execution logic |
| Alerting Layer | Notifications, trade updates, and reporting support |
| Data Processing | EOD and structured market-data workflows |
| Options Analytics | Greeks, IV workflows, PCR, GEX, and related derivatives tooling |

## Public Validation Evidence

Selected validation evidence for Optimus Quanta is published on [optimusquanta.com](https://optimusquanta.com) as operational evidence of infrastructure behavior under controlled forward-simulation or pilot conditions. Detailed validation notes are maintained in [PERFORMANCE_VALIDATION_APPENDIX.md](./PERFORMANCE_VALIDATION_APPENDIX.md).

---

## Selected Public Repositories

### [24Options](https://github.com/Vikkrantpol/24Options) — Options Intelligence & Execution Platform

`React` `Vite` `FastAPI` `Black-Scholes` `NSE Option Chain`

A full-stack options platform built around pricing, structured strategy workflows, risk checks, and execution-oriented usability for Indian derivatives markets.

```text
24OPTIONS  ·  NSE F&O Options Intelligence
> Pricing Engine        > Greeks Dashboard
> Strategy Workflows    > AI-assisted Trade Structuring
> IV Logic              > Risk Checks
> Strike Selection      > Execution-ready Workflow
```

| Feature | Sensibull / Opstra | 24Options |
| :--- | :--- | :--- |
| Self-hosted | No | Yes |
| AI strategy scoring | No | Yes |
| Custom Greeks limits | No | Yes |
| Open-source & hackable | No | Yes |
| One-click Fyers deploy | No | Yes |

---

### [US_IN_NEW_SCANNER_NEW_FEATURES](https://github.com/Vikkrantpol/US_IN_NEW_SCANNER_NEW_FEATURES) — Multi-Market Scanner

`Python` `FastAPI` `SQLite` `Bash`

A scanner workspace for **US equities + Indian markets** with:

* multi-market scan automation
* persistent scan state and history
* browser-based monitoring
* scoring and filtering workflows
* exported outputs for trading workflows

```bash
$ signalscan --market NSE --conditions P1,P2,P3 --export tv
  Scanned symbols with configurable worker threads
  Ranked setups generated from multi-condition logic
  TradingView-compatible export ready
```

| Component | Purpose |
| :--- | :--- |
| FastAPI + SSE backend | Live command execution streamed to browser dashboard |
| SQLite state engine | Persistent scan history, diffs, archive, sector reports |
| Cap-class summaries | Smallcap / midcap / largecap breakdown for NSE universe |
| Security model | Real thresholds and broker keys stay local via `.gitignore` |

---


---

### [InsideBar_Strategy](https://github.com/Vikkrantpol/InsideBar_Strategy)

`Python` `Visualization` `Backtesting`

Backtesting and visualization framework for inside-bar based systematic trade setups with protected core logic.

### [Arbitrage_Vikkrant](https://github.com/Vikkrantpol/Arbitrage_Vikkrant)

`Python` `pandas` `NumPy`

Cross-exchange arbitrage research focused on spread detection, fee/slippage-aware evaluation, and performance testing.

### [EMA-Strategy-Backtesting](https://github.com/Vikkrantpol/EMA-Strategy-Backtesting)

`Python` `pandas` `matplotlib`

Backtesting framework for an EMA-based strategy with performance visualization.

### [Android-App---Position-Size-Calculator](https://github.com/Vikkrantpol/Android-App---Position-Size-Calculator)

`Android` `Java`

A mobile-first position sizing tool built around practical trade risk management.

> Some repositories intentionally omit alpha-generating logic. Public code is meant to showcase **architecture, research process, backtesting design, tooling, and workflow engineering** without exposing the exact edge.

---

## Tech Stack

| Domain | Stack |
| :--- | :--- |
| Core Language | Python 3.11+ |
| Quant Toolkit | Options pricing, IV solvers, Greeks, GEX, PCR, Max Pain |
| Frontend | React, Vite, Next.js 14, TailwindCSS |
| Database / ORM | PostgreSQL, Prisma, SQLite |
| Broker APIs | Fyers V3, Zerodha, Upstox, CCXT |
| Strategy Coding | Pine Script |
| AI / LLMs | OpenRouter, MiniMax, Claude API, OpenAI |
| Data Sources | Broker API, MCX EOD, yfinance |
| Scripting / Infra | Bash, Telegram Bot API, Linux, cron |

---

## Domain Focus

```text
NSE F&O          ████████████████████  Index & stock options, derivatives workflows
MCX Commodities  ██████████████████░░  Crude oil, gold, silver research and execution
US Equities      ████████████░░░░░░░░  Scanner-driven momentum workflows
Options Theory   ████████████████████  Greeks, IV, GEX, Max Pain, PCR
Risk Management  ███████████████████░  Position sizing, exposure control, drawdown logic
```

---

## AI as a Research & Development Accelerator

AI supports the research and development process where it improves speed, structure, and iteration quality. Typical uses include:

* trade review
* structured signal explanation
* workflow assistance
* development productivity across multi-file systems

The broader approach remains domain-first: market research, validation discipline, risk thinking, and reliable infrastructure lead; AI accelerates selected research and engineering workflows.

---

## Connect

<div align="center">

Open to conversations around **quant development**, **trading systems**, **derivatives research**, and **market infrastructure**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vikkrant_Pol-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/vikkrantpol)
[![GitHub](https://img.shields.io/badge/GitHub-@Vikkrantpol-181717?style=flat-square&logo=github)](https://github.com/Vikkrantpol)
[![IIT Goa](https://img.shields.io/badge/Education-IIT_Goa-FF6B00?style=flat-square)](https://iitgoa.ac.in)

</div>

---

<div align="center">

*"The edge isn't in the signal. It's in the system that finds it, validates it, executes it, and survives it."*

</div>
