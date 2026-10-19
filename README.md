# Fateha Zaman

**Quantitative Software Engineer | Risk Engines | Research Data Systems | Commodities | New York, NY**

I build systems where correctness and reproducibility matter: point-in-time research data pipelines, portfolio risk engines, event-driven simulation, and edge-deployed benchmarks. My core stack is Python, Java, and SQL, with TypeScript, Docker, and CI where a project needs them.

This GitHub is a hypothesis-driven research notebook. I use these repositories to test market, risk, and systems hypotheses in public, keep earlier coursework and prototypes alongside newer architectures so the progression stays visible, and document known defects and negative results rather than hiding them. The point-in-time archives, deterministic simulation outputs, and defect ledgers also serve as ground-truth datasets and evaluation harnesses for testing and training my own LLMs, especially LLM-as-a-judge evaluators.

## Current focus

- **Commodities research data**: point-in-time storage, vintages and revisions, provenance, quality gates, and explicit handling of missing or conflicting evidence
- **Risk and simulation**: VaR/CVaR, correlated Monte Carlo, stress tests, FX basis, policy-regime classification, and letter-of-credit allocation
- **Testing and reproducibility**: seeded runs, regression tests, CI, and written records of what a model can and cannot show

## Featured work

- [**Metals Evidence Engine**](https://github.com/fatehaszaman/metals-evidence-engine): point-in-time evidence evaluator for Bangladesh–India copper and aluminum supply-chain research, with immutable provenance, revision-aware `as_of()` reconstruction, guarded intake, and advisory LLM review that cannot alter data.
- [**China Copper Research Pipeline**](https://github.com/fatehaszaman/invoice-economy-copper): vintage-aware SHFE and UN Comtrade ingestion that preserves source payloads, publication timing, coverage gaps and audit trails.
- [**Regime Risk Framework**](https://github.com/fatehaszaman/regime-risk-framework): risks standard VaR misses in import-dependent markets: effective vs. official FX basis, policy-regime classification, scenario shocks and LC allocation.
- [**Monte Carlo Risk Engine**](https://github.com/fatehaszaman/monte-carlo-risk-engine): correlated GBM, VaR/CVaR, stress testing and Cholesky correlation handling.
- [**Event-Driven Backtester**](https://github.com/fatehaszaman/event-driven-backtester): queue-based simulation with ordered bar delivery, long/short accounting, proportional slippage, commissions and 68 tests. Same-bar execution limits are documented.
- [**MLB Edge Bench**](https://github.com/fatehaszaman/mlb-edge-bench): live Cloudflare Workers benchmark comparing MLB's origin API with an edge-cache layer. [Live benchmark](https://mlb-edge-bench.fatehaszaman.workers.dev).

## Stack

- **Languages:** Python · Java · SQL · TypeScript · Bash · Haskell and Prolog (coursework)
- **Quant and data:** NumPy · pandas · SQLite · PostgreSQL · time series · regression · Monte Carlo · VaR/CVaR · event-driven backtesting
- **Engineering:** Linux · Docker · Git · GitHub Actions CI · ETL and data pipelines · Cloudflare Workers
- **Applied AI:** guarded LLM-assisted data review, LLM-as-a-judge evaluation harnesses, and point-in-time dataset curation for personal LLM training and testing with deterministic checks and human sign-off

## Connect

[LinkedIn](https://www.linkedin.com/in/fateha-zaman)
