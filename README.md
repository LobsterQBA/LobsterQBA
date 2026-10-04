# Hi, I'm Leo Zhao

I'm a data scientist in Seattle working on distributed data pipelines and applied AI. I turn event data into reliable tables for analytics and build small agent systems with inspectable execution, persistent state, and explicit limits.

[Personal site](https://www.leozhao.me) · [Loop Agent demo](https://lobsterqba.github.io/loop-agent/)

## Data engineering and applied AI

- **WPP:** Spark and Databricks pipelines for cross-channel advertising data, processing roughly 5–20 million rows per day. My work includes SQL integration, table modeling, data-quality checks, and refresh monitoring.
- **ByteDance:** Payment data pipelines using Kafka, Spark, and Iceberg. My contributions include transaction and user table definitions, partitioning, and diagnosing Spark data skew and memory pressure with Spark UI and executor logs.
- **Applied AI:** PyTorch forecasting, LLM post-training evaluation, and RAG and agent projects. I care about checking outputs and failure cases, not just getting a model to return an answer.

My strongest tools are Python, SQL, Spark, and Databricks. I'm interested in reliable data products, distributed processing, and AI systems whose behavior can be tested and inspected.

## Selected projects

| Project | What you can inspect |
| --- | --- |
| **[Loop Agent](https://github.com/LobsterQBA/loop-agent)** · [demo](https://lobsterqba.github.io/loop-agent/) · [architecture](https://github.com/LobsterQBA/loop-agent/blob/main/docs/architecture.md) | Python tool execution, SQLite state, completed and failed run traces, and deterministic trace-integrity checks. Execution budgets and input validation have regression coverage. The fixed-rule demo needs no API key; live mode uses a configured model. |
| **[SplitTaste](https://github.com/LobsterQBA/splittaste)** · [demo](https://www.leozhao.me/projects/splittaste) | DuckDB ETL from MovieLens 32M ratings to Parquet, a versioned browser data contract, and reproducible recommendation evaluation with baselines and explicit metric gates. |
| **[Tab Tidy](https://www.leozhao.me/tab-tidy)** · [Chrome Web Store](https://chromewebstore.google.com/detail/tab-tidy-ai/llgmobdbimolaapfjkhagkmhjbgeoeak) | Chrome extension that proposes tab groups, takes plain-English refinements, and previews every change before applying it. |
| **[Point2Prompt](https://github.com/LobsterQBA/point2prompt)** · [install](https://lobsterqba.github.io/point2prompt/) | Bookmarklet that turns a click on any UI element into a structured change brief for Claude Code, Codex, or Cursor. |

Other projects: [Trackpad Canvas](https://github.com/LobsterQBA/trackpad-canvas), a native macOS diagramming app, and [Where to Sit](https://github.com/LobsterQBA/where-to-sit), a cinema seat-view simulator.

## Open-source contributions

- **[Strands Harness SDK](https://github.com/strands-agents/harness-sdk/pull/4291)**
- **[OpenMed](https://github.com/maziyarpanahi/openmed/pull/3074)**
- **[Microsoft Agent Framework](https://github.com/microsoft/agent-framework/pull/7606)**
- **[DeepEval](https://github.com/confident-ai/deepeval/pull/3285)**
- **[OpenHarness](https://github.com/HKUDS/OpenHarness/pull/359)**
