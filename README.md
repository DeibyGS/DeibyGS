<div align="center">

# Deiby Gorrin

### AI-First Software Engineer

I build production software using Spec-Driven Development,<br>
custom AI workflows, and measurable engineering practices.

Human decisions. AI acceleration. Everything measured.

[![Claude Code](https://img.shields.io/badge/Claude_Code-Opus_|_Sonnet_|_Haiku-1a1a2e?style=for-the-badge&logo=anthropic&logoColor=white)](https://claude.ai/claude-code)
[![OpenCode Go](https://img.shields.io/badge/OpenCode_Go-Multi--Model-0f3460?style=for-the-badge&logo=terminal&logoColor=white)](https://opencode.ai)
[![ClaudeStat](https://img.shields.io/badge/ClaudeStat-npm_package-16213e?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/package/@statforge/claudestat)

[![Portfolio](https://img.shields.io/badge/Portfolio-deiby.dev-e94560?style=flat-square&logo=safari&logoColor=white)](https://deiby.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-deibygorrin-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/deibygorrin)
[![Email](https://img.shields.io/badge/Email-deibygorrin@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:deibygorrin@gmail.com)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%">

## Projects

| Project | Description | Commits | PRs |
|---------|-------------|--------:|----:|
| [WodRival](https://github.com/DeibyGS/wodrival) | Competitive fitness platform with Norse mythology theming, RPG progression, and seasonal rankings. Next.js, Supabase, Tailwind | 498 | 237 |
| [ClaudeStat](https://github.com/DeibyGS/claudestat) | CLI + dashboard for tracking AI development sessions, token usage, and engineering metrics. Published on npm | 173 | 60 |
| [Conductor](https://github.com/DeibyGS/conductor) | Modular multi-tenant ERP with Kafka microservices. Sales emulator and async consumer pipeline. Python, Docker | 165 | -- |
| [EvoluFit](https://github.com/DeibyGS/evolufit-mobile) | Cross-platform fitness tracking app with offline sync. React Native, Node.js, MongoDB | 128 | 9 |
| [Gmail AI Agent](https://github.com/DeibyGS/gmail-ai-agent) | AI-powered email classification and automated responses using Gemini API. Python, FastAPI | 57 | 24 |
| [Portfolio](https://github.com/DeibyGS/portfolio) | Personal site with i18n and responsive design. Tailwind | 43 | 13 |
| [CatcherAuto](https://github.com/DeibyGS/CatcherAuto) | Android automation using pixel scanning and ML Kit OCR for order acceptance. Kotlin | 1 | -- |

### Currently working on

- Designing the **Progression Engine** for WodRival -- XP, ranks, achievements, and seasonal rewards that transform individual Battles into a long-term competitive journey
- Experimenting with multi-model workflows: Claude Code as primary, OpenCode as secondary

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%">

## Spec-Driven Development (SDD)

Every feature starts with a specification, never with code. The spec defines scope, contracts, edge cases, and acceptance criteria before a single line is written. This is enforced by automated hooks -- not discipline alone.

```
Spec --> Branch --> Implement (AI) --> Review (Human) --> Test --> PR --> Merge
```

> *"Human owns architecture. AI accelerates implementation. Measure everything."*

| Rule | How it is enforced |
|------|-------------------|
| Spec before code | Hook blocks multi-file changes without prior SDD analysis |
| Branch-only development | Hook blocks writes to main/master |
| PR budget: 400 lines | Hook warns on exceed, `/chained-pr` splits into stacked PRs |
| Tests ship with code | Work-unit commits -- never by file type |
| Architecture decisions | ADRs documented in each project |

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%">

## Metrics

1,000+ hours of AI-assisted engineering across 7 production projects. 1,500+ AI sessions. 1,068 commits. 343 pull requests. 7 models across 2 tools. 50+ custom skills, commands, and agents. 13 automated quality gates protecting branches, PRs, and architecture.

All metrics tracked by [ClaudeStat](https://github.com/DeibyGS/claudestat), a custom-built MCP server and npm package.

## AI Development Stack

| Component | Details |
|-----------|---------|
| **Claude Code** | Opus 4.6, Sonnet 4.6, Haiku 4.5 |
| **OpenCode Go** | DeepSeek v4 Flash, GLM-5, Mimo v2.5 |
| **MCP Servers** | ClaudeStat (custom-built), GitHub, Supabase, Engram, Context7, Gmail |
| **Custom Skills** | 12 commands + 15 knowledge skills (Claude Code) · 8 skills + 5 commands (OpenCode) |
| **Custom Agents** | 12 specialized agents for testing, docs, frontend, backend, DevOps, and architecture reviews |
| **Automated Hooks** | 13 quality gates across 6 lifecycle events enforcing SDD, branch safety, PR budget, and formatting |

<details>
<summary><strong>Full AI tooling breakdown</strong></summary>
<br>

**Commands -- Claude Code**

| Command | Purpose |
|---------|---------|
| `sdd` | Spec-Driven Development -- write specs before code |
| `dev` | Development pipeline orchestrator |
| `orchestrate` | Multi-agent task orchestration |
| `multi-agent-explore` | Parallel code review with 3 agents |
| `git` | Structured git operations with safety checks |
| `chained-pr` | Split large PRs into reviewable chains |
| `day-start` / `day-close` | Session context loading and persistence |
| `checkpoint` | Context preservation during long sessions |
| `simplify-lean` | Post-edit code simplification |
| `cognitive-doc-design` | Documentation with low cognitive load |

**Commands -- OpenCode**

| Component | Details |
|-----------|---------|
| Skills | sdd, dev, git, day-start, day-close, checkpoint, simplify-lean, engram-save, bug-hunter |
| Commands | dev, git, day-start, day-close, review, recall, sdd, simplify, test |
| Agents | code-reviewer, database-expert, scrum-master, tester |

**Agents -- Claude Code (12)**

| Agent | Role |
|-------|------|
| `dev-pipeline` | Feature development orchestration |
| `orchestrator` | Multi-phase task coordination |
| `post-merge-checker` | Post-merge validation |
| `ui-ux-designer` | Interface design decisions |
| `frontend-dev` / `backend-dev` | Implementation |
| `database-dev` | Database design and queries |
| `tester` | Test writing and validation |
| `quality-docs` | Documentation quality review |
| `scrum-master` | Task breakdown and prioritization |
| `git` | Git operations and PR management |
| `devops` | Infrastructure and deployment |

**Hooks (13 across 6 lifecycle events)**

| Event | What it does |
|-------|-------------|
| `PreToolUse` | Blocks writes to main/master, prevents `git add -A`, blocks force push |
| `PostToolUse` | Simplify-lean reminder, PR budget check (400 lines), auto-Prettier, read loop detection |
| `SessionStart` | Auto-loads HANDOFF.md, warns if on main branch |
| `UserPromptSubmit` | Enforces SDD analysis before multi-file changes |
| `PreCompact` | Saves branch and modified files before context compaction |
| `Stop` | Alerts when context exceeds 250k tokens |

</details>

<details>
<summary><strong>Education and Experience</strong></summary>
<br>

**Education**

| Programme | Institution | Status |
|-----------|------------|--------|
| Grado Superior DAM | The Power, Madrid | Completed 2026 |
| Master Web Full Stack | The Power, Madrid | Completed 2026 |
| Professional Uses of Generative AI | BeJob, IBM | Completed |
| Oracle SQL-PL/SQL Developer | Cas-Training, Madrid | Completed |
| Oracle EPM Specialist | Cas-Training, Madrid | Completed |

[![IBM AI Fundamentals](https://img.shields.io/badge/IBM-AI_Fundamentals-052FAD?style=flat-square&logo=ibm&logoColor=white)](.)
[![Oracle SQL 23ai](https://img.shields.io/badge/Oracle-SQL_23ai_Associate-F80000?style=flat-square&logo=oracle&logoColor=white)](.)
[![OCI AI Foundations](https://img.shields.io/badge/Oracle-OCI_AI_Foundations-F80000?style=flat-square&logo=oracle&logoColor=white)](.)
[![OCI Data Science](https://img.shields.io/badge/Oracle-OCI_Data_Science-F80000?style=flat-square&logo=oracle&logoColor=white)](.)

**Experience**

**Internship -- Mercanza** (2026)

Developer on **Conductor**, a modular multi-tenant ERP with microservices. Responsible for the sales module:
- Designed and implemented **Sales Emulator** (synthetic invoice generator to Kafka)
- Built **Sales Manager** (Kafka consumer with async PostgreSQL persistence via SQLAlchemy)
- Refactored to centralized database and migrated to multi-tenant architecture
- Collaborated with 11-person team using GitLab, Docker, Kafka, FastAPI

</details>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%">

<div align="center">

Interested in AI-assisted engineering, developer tooling, or production software?

[![Portfolio](https://img.shields.io/badge/Portfolio-deiby.dev-e94560?style=flat-square&logo=safari&logoColor=white)](https://deiby.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-deibygorrin-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/deibygorrin)
[![Email](https://img.shields.io/badge/Email-deibygorrin@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:deibygorrin@gmail.com)
[![npm](https://img.shields.io/npm/v/@statforge/claudestat?style=flat-square&color=1a1a2e&label=ClaudeStat)](https://www.npmjs.com/package/@statforge/claudestat)

*Madrid, Spain -- Available for remote or on-site work*

</div>
