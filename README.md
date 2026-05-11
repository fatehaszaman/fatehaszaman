# Fateha Zaman
### Quantitative Software Engineer | High-Performance Systems | New York, NY

I build the bridge between quantitative research and production trading infrastructure. My focus is high-performance Java and Python systems, deterministic replay, event-driven architectures, and the SDLC discipline required to run them reliably in live environments.

---

## 🏛️ The Four Pillars

### 📈 Quant Systems
*   **Event-Driven Simulation:** Discrete event engines for strategy research, with explicit ordering guarantees and reproducible state transitions.
*   **Risk & Modeling:** Monte Carlo stress engines, VaR/CVaR frameworks, and regime-aware risk decomposition.
*   **Performance:** NumPy vectorization and Numba JIT to keep Python research loops on a tight latency budget.

### 💻 Software Engineering
*   **High-Performance Java:** Tuned execution paths, multithreaded ingestion, and low-jitter pricing components.
*   **Python at Scale:** Typed, profiled, and packaged. Designed to move from notebook to service without rewrites.
*   **System Architecture:** Event-driven frameworks built from primitives, not glued together from frameworks.

### 🔄 SDLC & Reproducibility
*   **Deterministic Replay:** State snapshots, seeded RNG, and event logs so a backtest from last quarter produces the same fills today.
*   **Containerized Environments:** Dockerized research and execution stacks for parity between dev, CI, and production.
*   **Pipeline Discipline:** Version-controlled experiments, TDD on the critical path, and CI gates that enforce both.

### 🗄️ Information Systems
*   **Fault-Tolerant Ingestion:** Hardened data pipelines with retry, dead-letter, and integrity checks at each stage.
*   **High-Concurrency Crawlers:** Concurrent collection infrastructure for adversarial ML research and market data.
*   **Storage & Cloud:** PostgreSQL data stores and AWS/GCP orchestration supporting distributed research workloads.

---

## 🧪 Pinned Projects

### [event-driven-backtester](https://github.com/fatehaszaman/event-driven-backtester): Quant x SWE pivot
High-fidelity event-driven backtester built as discrete event simulation. State snapshots and deterministic replay let any historical run be reproduced bit-for-bit. Designed with microstructure realism in mind so research signals translate to live behavior, and fault-tolerant ingestion keeps the event stream intact under upstream failure. This is the project I point senior trading-firm engineers to when they ask what I actually build.

### [web-crawler](https://github.com/fatehaszaman/web-crawler): IS x SDLC pivot
High-concurrency traffic analysis infrastructure originally built to support adversarial ML research. Emphasis on concurrency primitives, hardened collection pipelines, data integrity at scale, and reproducible research artifacts. Demonstrates the information systems and SDLC discipline behind the quant work.

### [monte-carlo-risk-engine](https://github.com/fatehaszaman/monte-carlo-risk-engine) / regime-risk-framework
Monte Carlo stress engine and regime-aware risk decomposition. Vectorized paths, JIT acceleration where it pays, and clear separation between model, simulator, and reporting.

### [programming-languages](https://github.com/fatehaszaman/programming-languages)
Cross-language reference work covering systems, concurrency, and language design fundamentals. Background material for the engineering above.

---

📫 **Connect:** [LinkedIn](https://linkedin.com/in/fateha-zaman) | fatehafaisal@gmail.com
