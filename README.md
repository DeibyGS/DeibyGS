<div align="center">

# Deiby Gorrin

**AI-First Software Engineer**

I ship production software with spec-driven AI workflows — human architecture, AI acceleration, everything measured.

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=400&size=15&duration=3000&pause=1500&color=6e7681&center=true&vCenter=true&width=450&height=22&lines=Spec+before+code.+Architecture+stays+human.;1%2C000%2B+hours+of+AI-assisted+engineering.)](https://deiby.dev)

</div>

&nbsp;

## What I Build

| Project | What it does | Stack | Commits | PRs |
|---------|-------------|-------|--------:|----:|
| WodRival _(private)_ | Competitive fitness platform — RPG progression, seasonal rankings, Norse mythology | Next.js, Supabase, Tailwind, TypeScript | 502 | 0 |
| [ClaudeStat](https://github.com/DeibyGS/claudestat) | Real-time monitor for AI dev sessions — cost, tokens, quota, MCP server. [npm](https://www.npmjs.com/package/@statforge/claudestat) | Node.js, TypeScript, MCP | 195 | 0 |
| Conductor _(private)_ | Multi-tenant ERP with Kafka microservices and async consumer pipeline | Python, FastAPI, Docker, Kafka | 167 | 0 |
| [applyr](https://github.com/DeibyGS/applyr) | Job application tracker CLI — scoring, ATS CVs, duplicate detection. [PyPI](https://pypi.org/project/applyr/) | Python, SQLite, Typer | 107 | 0 |
| [Gmail AI Agent](https://github.com/DeibyGS/gmail-ai-agent) | AI email classification and automated responses | TypeScript, Node.js, Gemini API | 64 | 0 |
| [EvoluFit Mobile](https://github.com/DeibyGS/evolufit-mobile) | Fitness tracking with offline sync | React Native, Expo, TypeScript | 34 | 0 |
| [EvoluFit Frontend](https://github.com/DeibyGS/evolufit-frontend) | Data visualization, community gamification, glassmorphism UI | React 19, Vite, TypeScript | 43 | 0 |
| [EvoluFit Backend](https://github.com/DeibyGS/evolufit-backend) | REST API — session logging, 1RM calc, health metrics, social | Python, FastAPI, PostgreSQL | 81 | 0 |
| [Questionnaire](https://github.com/DeibyGS/questionnary) | Interactive quiz app for DAM/DAW exam prep | TypeScript, Vite, SCSS | 30 | 0 |
| [Portfolio](https://github.com/DeibyGS/dev-portfolio-deiby) | Personal site with i18n and responsive design | Astro, Tailwind, TypeScript | 49 | 0 |
| [CatcherAuto](https://github.com/DeibyGS/CatcherAuto) | Android automation — pixel scanning + ML Kit OCR | Kotlin, ML Kit, Jetpack Compose | 8 | 0 |

> **Also:** [claudestat-mcp-bundle](https://github.com/DeibyGS/claudestat-mcp-bundle) (standalone MCP server for ClaudeStat) · [claudestat-alert-slack](https://github.com/DeibyGS/claudestat-alert-slack) (Slack alerting) · [claudestat-exporter-prometheus](https://github.com/DeibyGS/claudestat-exporter-prometheus) (Prometheus exporter)

&nbsp;

## Right Now

- **Looking for opportunities** — junior/fullstack roles with AI focus
- Maintaining [**claudestat**](https://www.npmjs.com/package/@statforge/claudestat) and [**applyr**](https://pypi.org/project/applyr/) — open source developer tools
- Building **WodRival** — competitive training where every workout is a scored Battle. Norse RPG progression: earn Runes, climb Viking Ranks, leave a permanent Legacy in Valhalla

&nbsp;

## By the Numbers

| | |
|:--|:--|
| **1,000+ hours** of AI-assisted engineering | **1,500+ sessions** across 11 production projects |
| **1,280+ commits** · **0 pull requests** (direct commits) | **7 models** across 2 tools |
| **Published on npm + PyPI** | **19 automated hooks** protecting branches, PRs and high-risk code |
| **296 tests** in applyr · **665 tests** in WodRival | **50+ custom tools** — skills, commands, agents |

All metrics tracked by [ClaudeStat](https://github.com/DeibyGS/claudestat).

&nbsp;

## Publications

**Claude Code from Zero** — Amazon KDP (August 2026)  
Practical guide to AI-assisted software development with Claude Code.  
[![Amazon](https://img.shields.io/badge/Amazon-KDP-FF9900?style=flat-square&logo=amazon&logoColor=white)](https://www.amazon.com/dp/B0D7YHZ5W2)

&nbsp;

## How I Work

Spec-driven, not vibe-driven. Every feature starts as a living spec and runs through human gates that close the loop with drift detection — it's a feedback cycle, not a one-way pipeline. The spec is the source of truth; the AI implements, but my architecture and scope decisions stay human.

```mermaid
flowchart LR
    C[Constitution<br/>immutable rules] --> S[Specify<br/>assumptions first]
    S --> A[Assumptions Surface<br/>AI declares implicit choices]
    A --> S
    S -->|HUMAN GATE| P[Plan<br/>data-model + contracts]
    P -->|contracts LOCKED| T[Tasks<br/>atomic, test-first]
    T -->|HUMAN GATE| I[Implement<br/>AI, constrained by spec]
    I --> V[Validate<br/>traceability + drift]
    V -->|drift found| AM[/Amend<br/>same command, auto-detected/]
    AM --> S
    V -->|low risk| M[PR → Merge]
    V -->|high risk| X[Adversarial Verify<br/>fresh context, contract only]
    X -->|defect found| AM
    X -->|no defect| M
```

Without a spec, the AI makes thousands of micro-decisions silently. With one, those decisions are made explicitly by me — before a single line of code — and validated instead of trusted.

Not tied to one vendor's magic, either: I run this pipeline in two different AI coding tools side by side, from one shared template source — a feature can start in one and finish in the other without translating anything.

```mermaid
flowchart LR
    T[("Shared templates<br/>constitution · spec · plan · tasks")]
    T --> CC["Claude Code — /sdd"]
    T --> OC["OpenCode — /sdd"]
    CC <-.->|same repo,<br/>same spec files| OC
```

**MoSCoW priorities** — every acceptance criterion is one of these:

| Priority | Meaning | Ships |
|----------|---------|:-----:|
| `[MUST]` | Non-negotiable, testable, locked | Always |
| `[SHOULD]` | Expected if scope holds | When cheap |
| `[COULD]` | Nice to have, optional | When time allows |
| `[WONT]` | Explicitly out of scope | Never |

**The tradeoff I accept:**

- **+** An extra hour writing a spec saves three days of agent thrash (GitHub Engineering)
- **+** Contracts freeze after planning — no signature drift mid-build
- **+** Validate catches drift early: mismatched contracts, schema, untested `[MUST]` ACs
- **−** Spec-first costs time before code exists — I skip it for one-line fixes and throwaway spikes

&nbsp;

### Two testers, on purpose

Tests written by whoever just read the implementation only prove the code does what it does — not what it should. That's circular verification, and it's the most common failure mode of AI-written tests.

So high-risk changes get a second pass from a verifier that runs in a **fresh context and never sees the diff** — only the acceptance criteria, the file paths and the public signatures. Independence is enforced structurally, not requested politely.

| | Standard tester | Adversarial verifier |
|---|---|---|
| Source of truth | The modified files | The acceptance criteria |
| Sees the implementation | Yes | **No — by design** |
| Goal | Cover the behavior | Falsify it |
| On failure | Pipeline blocked | Logged as `BUG-XXX`, PR continues |

Findings deliberately **don't** block the merge: blocking creates pressure to weaken the test, which is the one thing the verifier is forbidden to do. They ship as reports and get fixed in a separate PR.

No acceptance criteria, no run — without a contract it degrades into reading the code and testing what it already does. The gate is narrow on purpose: auth · money · data integrity · migrations · state machines · idempotency · offline sync. Everything else skips it.

&nbsp;

<details>
<summary><strong>AI Stack, Tooling & Background</strong></summary>
<br>

### AI Development Stack

| Layer | Details |
|-------|---------|
| **Primary** | Claude Code — Opus 5, Sonnet 5, Haiku 4.5 |
| **Secondary** | OpenCode Go — DeepSeek v4 Flash, GLM-5, Mimo v2.5 |
| **MCP Servers** | ClaudeStat (custom), GitHub, Supabase, Engram, Context7, Gmail |
| **Custom Skills** | 12 commands + 1 custom skill · 52 curated knowledge skills (CC) · 8 skills + 5 commands (OC) |
| **Custom Agents** | 12 definitions — 11 specialized (backend, frontend, DB, DevOps, testing, adversarial verification, docs, git, design, planning) + 1 orchestrator |
| **Hooks** | 19 quality gates across 6 lifecycle events |
| **Project contexts** | 7 — per-repo stack, conventions and gotchas loaded on demand |

Key commands: `sdd` (spec-driven dev) · `dev` (pipeline orchestrator) · `git` (safe operations) · `chained-pr` (split large PRs) · `adversarial-test` (hostile verification) · `day-start`/`day-close` (session persistence)

The hooks are the part that actually holds. Rules I have to remember get forgotten; rules the harness enforces don't. Editing a file matching `auth|permission|migration|billing|…` fires the adversarial gate automatically, and a PR over 500 changed lines triggers a split before it's opened — neither depends on me noticing.

&nbsp;

### Education

| Programme | Institution | Status |
|-----------|------------|--------|
| Grado Superior DAM | The Power, Madrid | Completed 2026 |
| Master Web Full Stack | The Power, Madrid | Completed 2026 |
| Professional Uses of Generative AI | BeJob, IBM | Completed |
| Oracle SQL-PL/SQL Developer | Cas-Training, Madrid | Completed |

[![IBM AI Fundamentals](https://img.shields.io/badge/IBM-AI_Fundamentals-052FAD?style=flat-square&logo=ibm&logoColor=white)](#)
[![Oracle SQL 23ai](https://img.shields.io/badge/Oracle-SQL_23ai_Associate-F80000?style=flat-square&logo=oracle&logoColor=white)](#)
[![OCI AI Foundations](https://img.shields.io/badge/Oracle-OCI_AI_Foundations-F80000?style=flat-square&logo=oracle&logoColor=white)](#)
[![OCI Data Science](https://img.shields.io/badge/Oracle-OCI_Data_Science-F80000?style=flat-square&logo=oracle&logoColor=white)](#)

&nbsp;

### Experience

**Internship — Mercanza** (2026)<br>
Developer on Conductor, a modular multi-tenant ERP. Built the Sales Emulator (Kafka producer) and Sales Manager (async consumer with PostgreSQL). 11-person team using GitLab, Docker, Kafka, FastAPI.

</details>

&nbsp;

<div align="center">

[![Portfolio](https://img.shields.io/badge/deiby.dev-e94560?style=for-the-badge&logo=safari&logoColor=white)](https://deiby.dev)&nbsp;&nbsp;[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/deibygorrin)&nbsp;&nbsp;[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:deibygorrin@gmail.com)

*Madrid, Spain — Available for remote or on-site work*

</div>
