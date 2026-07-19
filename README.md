<div align="center">

# William Chang

### AI Agent Infrastructure · Reliable Applied AI · Native Product Engineering

I build systems that help AI agents preserve context, ground decisions in evidence, and turn messy workflows into dependable products.

专注 AI Agent 基础设施、可信 AI 应用与原生产品工程。

[![Python](https://img.shields.io/badge/Python-Agent_Tooling-3776AB?style=flat-square&logo=python&logoColor=white)](https://github.com/wentaoz?tab=repositories)
[![Swift](https://img.shields.io/badge/Swift-Native_AI_Products-F05138?style=flat-square&logo=swift&logoColor=white)](https://github.com/wentaoz?tab=repositories)
[![Local First](https://img.shields.io/badge/Architecture-Local--first-111827?style=flat-square)](https://github.com/wentaoz?tab=repositories)

</div>

---

## What I work on

Useful AI needs more than a strong model response. It needs **continuity, evidence, recovery, safe boundaries, and a product surface people can trust**.

My projects explore that full stack:

- **Agent reliability and interoperability** — session handoff, task recovery, context portability, idempotent continuation
- **Evidence-grounded AI** — local analytics, traceable SQL, answer validation, citations, persistent task queues
- **Native AI products** — privacy-aware macOS experiences built with Swift, SwiftUI, and AppKit
- **Developer tools** — Python CLIs, skills, adapters, automation, tests, and multi-version CI

## Selected work

### [Coding Agent Handoff](https://github.com/wentaoz/coding-agent-handoff)

Cross-agent task continuity for Claude Code and Codex. When one coding agent hits a usage limit, the CLI extracts portable local session context, reconciles Git state, redacts common secrets, and launches the other agent with a safe takeover contract—without requiring the limited model to respond.

`Python` · `Agent interoperability` · `Session recovery` · `Developer tools`

### [NexaFlow](https://github.com/wentaoz/NexaFlow)

A local-first AI analytics workbench for product, operations, and business teams. It combines spreadsheet ingestion, DuckDB analysis, executable SQL evidence, answer validation, user-correction memory, persistent AI task queues, and report generation.

`Swift` · `DuckDB` · `Evidence-grounded AI` · `Analytics agents`

### [WorkMemory](https://github.com/wentaoz/WorkMemory)

A native macOS work-memory system that turns window, web, typing, OCR, and document context into searchable sessions, grounded answers, summaries, projects, and action items—while keeping collection and storage local-first.

`SwiftUI` · `Local retrieval` · `Knowledge systems` · `Privacy`

### [RivalRadar](https://github.com/wentaoz/RivalRadar)

A competitive-intelligence monitor that brings together RSS, web pages, Tavily search, and Chrome session sources, then applies AI-assisted deduplication, synthesis, trend analysis, and report generation.

`Swift` · `Information pipelines` · `AI synthesis` · `Product intelligence`

### [MacDailyCleaner](https://github.com/wentaoz/MacDailyCleaner)

A native, privacy-first macOS menu-bar utility for safe daily cleanup and disk-health visibility. It reflects the other half of my work: turning systems concerns into focused products that people can understand and control.

`SwiftUI` · `AppKit` · `macOS` · `Product engineering`

## Engineering principles

```text
Continuity over fragile sessions.     让任务跨越会话和工具继续运行。
Evidence over plausible answers.      让结论能够追溯、验证和复现。
Local-first when privacy matters.     敏感数据优先在本地处理。
Safe recovery over blind retries.     恢复之前先核实，避免重复副作用。
Working products over AI demos.       把模型能力做成真正可用的产品。
```

## Current direction

I am currently focused on:

- cross-agent continuity, memory, and task recovery;
- reliable tool-using agents with observable and testable behavior;
- evidence-grounded analytics and decision-support systems;
- native interfaces for privacy-sensitive AI workflows.

## Stack

`Python` · `Swift` · `SwiftUI` · `AppKit` · `DuckDB` · `SQLite` · `macOS` · `Agent tooling` · `Local-first AI` · `Automation` · `CI`

---

<div align="center">
  <sub>Build AI systems that can continue, explain, and recover.</sub>
</div>
