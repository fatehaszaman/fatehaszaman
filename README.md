# Fateha Zaman

**Quantitative Software Engineer | Risk Engines | Research Data Systems | Commodities | New York, NY**

I build pricing, risk, and research systems in Python, Java, and SQL, designed to separate bad data from real moves. TypeScript, Docker, and CI come in where a project needs them.

**Common thread.** Every project rests on three habits: point-in-time data that records what was known and when, tests written against analytic properties rather than expected outputs alone, and a clear statement of what each project does and does not prove.

Pinned repos are finished work; others are experiments or labeled LLM evaluation sandboxes. Everything here is independent work on public or synthetic data.

## Project clusters

**Commodities research data.** [Metals Evidence Engine](https://github.com/fatehaszaman/metals-evidence-engine) and [China Copper Research Pipeline](https://github.com/fatehaszaman/invoice-economy-copper) store observations with vintages, revisions, provenance, and coverage gaps. They reconstruct what was knowable on a given date and keep missing evidence separate from negative findings. The Metals Evidence Engine covers synthetic copper and aluminum cases with 260 tests; revisions never rewrite earlier reports, and its LLM reviewer can flag but never change data.

**Risk and simulation.** [Monte Carlo Risk Engine](https://github.com/fatehaszaman/monte-carlo-risk-engine) and [Regime Risk Framework](https://github.com/fatehaszaman/regime-risk-framework) cover correlated scenarios, VaR/CVaR, stress tests, FX basis, policy-regime classification, and Black-Scholes Greeks P&L attribution. The Monte Carlo tests check simulated paths and VaR/CVaR against analytic results, and open defects are listed in each repo's KNOWN_ISSUES.md.

**Trading simulation.** [Event-Driven Backtester](https://github.com/fatehaszaman/event-driven-backtester) runs queue-based simulation with ordered bar delivery, long/short accounting, slippage, and commissions, with 90 tests. Orders fill at the next bar's open, one bar after the signal, and a mean-variance optimizer adds a turnover penalty.

**Sports analytics and edge systems.** [MLB Edge Bench](https://github.com/fatehaszaman/mlb-edge-bench) measures latency, payload size, and cache hit rate for a Cloudflare Worker edge layer against the MLB origin API. The [World Cup Oracle](https://github.com/fatehaszaman/world-cup-oracle-trials) projects keep a public correction history, including withdrawn scores and what changed.

**Research tooling and foundations.** [Web Crawler](https://github.com/fatehaszaman/web-crawler) is an early single-threaded iteration of URL-collection tooling for a university network-privacy lab. Coursework repositories in algorithms, data structures, SQL, Java, and programming languages keep the progression visible.

## How I use this GitHub

I keep my mistakes visible. Repositories with correction histories show what went wrong, what I changed, and how I prevent it now.

I also use GitHub as a controlled environment for evaluating LLMs and LLM-as-a-judge workflows. Some repositories contain deliberate errors alongside documented real ones, so I can measure whether a model or judge catches them and follows instructions. Working through Git rather than giving a model full access to my machine keeps every change tracked and reversible.

## Stack

- **Languages:** Python · Java · SQL · TypeScript · Bash · Haskell and Prolog (coursework)
- **Quant and data:** NumPy · pandas · SQLite · PostgreSQL · time series · regression · Monte Carlo · VaR/CVaR · event-driven backtesting
- **Engineering:** Linux · Docker · Git · GitHub Actions CI · ETL and data pipelines · Cloudflare Workers
- **Applied AI:** LLM and LLM-as-a-judge evaluation with literal-quote verification, deterministic checks, and human sign-off

## Connect

[LinkedIn](https://www.linkedin.com/in/fateha-zaman)
