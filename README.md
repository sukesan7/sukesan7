<h1 align="center">Hi, I'm Sukesan</h1>

<div align="center">

Computer Engineering @ **Toronto Metropolitan University**
<br/>
Specializing in building **high-fidelity trading infrastructure** and **low-latency systems**.
    
</div>

---

<h2>Technical Focus</h2>

**Infrastructure**
`Python` `Pandas` `Polars` `Event-Driven Architecture` `Monte Carlo Methods`

**Systems Engineering**
`C++20` `Lock-free Data Structures` `Multithreading` `Ring Buffers`

**Hardware & FPGA**
`VHDL` `Quartus II` `Computer Architecture` `RTL Design`


<h2>Featured Engineering</h2>

#### 🔹 [Meridian](https://github.com/sukesan7/meridian)
**Deterministic, artifact-audited backtesting engine for intraday futures strategies (NQ/ES RTH).**
<br/>
> *Python, Event-Driven Simulation, Market Microstructure (bar-based)*

* **Correctness:** Causal multi-timeframe feature alignment (no look-ahead/session leakage) + next-bar-open execution sourced strictly from market tape (no execution leakage).
* **Execution Model:** Tick-based slippage with time-window regimes + fill-time risk constraints to prevent “passes at signal, fails at execution” false positives.
* **Reproducibility:** CI-gated ruff/mypy/pytest + determinism regression checks; run artifacts include SHA256 provenance via `run_meta.json` for tamper-evident outputs.


#### 🔹 [Stratos](https://github.com/sukesan7/stratos)
**Deterministic C++20 price-time priority matching engine (LOB) with audit-grade correctness harnesses.**
<br/>
> *C++20, Market Microstructure, Low-Latency Systems*

*In Development (Q1 2026).*
* **Core Engine:** Price–time priority matching with fixed-point prices (tick enforcement), limit/market/cancel flows, and fail-fast book invariants to prevent silent state corruption.
* **Correctness First:** Includes a slow-but-correct oracle reference engine (`std::map` + FIFO) and **seeded differential tests** that compare fills + state checksums over randomized event streams with reproducible failure seeds.
* **Replay & Hardening:** Planned binary event log + deterministic replay boundary, Google Benchmark baselines (p50/p99, throughput), and adversarial testing via ASan/UBSan + libFuzzer (advanced order types out of scope for v1.0).


#### 🔹 [FPGA RISC Core](https://github.com/sukesan7/General-Purpose-Processor)
*Implementation of a custom processor architecture on FPGA.*
<br/>
> *VHDL, Quartus II, Hardware Design*

* **Focus:** ALU design, instruction pipelining, and register transfer level (RTL) logic.






