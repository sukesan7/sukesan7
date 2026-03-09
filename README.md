<div align="center">

# Sukesan Selvaraveendran

**Computer Engineering @ Toronto Metropolitan University**  
Building **deterministic trading infrastructure**, **market-data systems**, and **low-latency C++20 software**.

Toronto, ON · [LinkedIn](https://linkedin.com/in/sukesan)

</div>

---

## Technical Focus

**Trading & Simulation**  
`Python` `Event-Driven Simulation` `Backtesting` `Execution Modeling` `Market Microstructure` `Monte Carlo Methods`

**Systems Engineering**  
`C++20` `Low-Latency Systems` `Binary Logging` `Deterministic Replay` `Multithreading` `Lock-Free SPSC Queues`

**Data & Tooling**  
`Pandas` `NumPy` `Polars` `PyArrow` `pytest` `ruff` `mypy` `GitHub Actions`

**Hardware & Architecture**  
`VHDL` `Quartus II` `Computer Architecture` `RTL Design`

---

## Featured Engineering

### 🔹 [Meridian](https://github.com/sukesan7/meridian)
**Deterministic, event-driven backtesting engine for intraday futures.**  
> *Python, Event-Driven Simulation, Execution Modeling, Market Microstructure*

- Built for **causal integrity**, with strict session handling and feature generation designed to prevent look-ahead and leakage.
- Models **regime-adaptive execution**, including slippage, timing, and fill-time risk constraints to avoid unrealistic strategy results.
- Designed for **reproducibility**, with CI-gated testing, determinism checks, and artifact-backed outputs for auditable runs.

---

### 🔹 [Stratos](https://github.com/sukesan7/stratos)
**Deterministic price-time priority matching engine with oracle diff testing, replay, and verification harnesses.**  
> *C++20, Limit Order Books, Matching Engines, Low-Latency Systems*

*Under construction — Q1 2026.*

- Implements **price-time priority matching** with fixed-point prices, deterministic order flow, and fail-fast invariants.
- Includes a **slow-but-correct oracle engine** plus seeded differential tests to compare fills and state across randomized event streams.
- Being extended with **binary replay**, benchmark instrumentation, and adversarial hardening for correctness-first systems development.

---

### 🔹 [Auro](https://github.com/sukesan7)
**C++20 market-data systems project for capture, compact binary storage, and deterministic replay of crypto exchange feeds.**  
> *C++20, Market Data, Boost.Asio/Beast, simdjson, Systems Experimentation*

- Captures live exchange market-data messages and stores them in a **compact append-only binary format** for offline analysis and benchmarking.
- Separates network I/O from downstream processing using a **lock-free queue architecture** to keep ingestion paths responsive under bursty flow.
- Supports **deterministic replay** for parser benchmarking, systems experiments, and repeatable downstream analysis workflows.

---

### 🔹 [Aegis](https://github.com/sukesan7)
**Real-Time EMS Navigation, Triage & Algorithmic Routing Telemetry.**  
> *React, TypeScript, FastAPI, Python, OSMnx, NetworkX*

- Built as an operator-facing emergency response system combining **routing, telemetry, dispatch visibility, and triage workflows**.
- Added **algorithm-comparison and rerouting capabilities** for scenario-based route evaluation and response planning.
- Awarded **York Region's Best Community Impact Hack** at **CTRL+HACK+DEL 2.0**.

---

## Engineering Interests

- Deterministic simulation and replay systems
- Market data capture, parsing, and execution infrastructure
- Matching engines and exchange-style correctness testing
- Latency-aware C++ systems and performance profiling
- Event-driven architecture for finance and real-time analytics

---

## Currently Building

- Advancing **Stratos** into a hardened matching engine with replay, verification, and benchmark artifacts
- Continuing to improve **Meridian** around correctness, execution realism, and research workflow quality
