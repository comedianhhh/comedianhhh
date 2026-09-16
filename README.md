# Hi, I'm Alan (Nianzhi Li)

Software engineer in Toronto — backend, full stack, and the runtime side of AI agents.
Most recently founding engineer and Technical Team Lead at [SoulLink](https://speedrun.a16z.com/companies/soullink) (formerly Daedalia; a16z speedrun Cohort 005), where I built the character runtime behind the **SoulLink** app, a live AI companion on iOS and Android.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-nianzhi--li-%230A66C2?logo=linkedin)](https://www.linkedin.com/in/nianzhi-li)
[![Portfolio](https://img.shields.io/badge/Portfolio-comedianhhh.github.io-%23111?logo=github)](https://comedianhhh.github.io/Portfolio/)

## Open source

**[job-agent-skills](https://github.com/comedianhhh/job-agent-skills)** — a job-search toolkit for coding agents (MIT). Ten Claude Code skills built around one rule: every line that goes out traces to a fact you wrote down.
[![CI](https://github.com/comedianhhh/job-agent-skills/actions/workflows/ci.yml/badge.svg)](https://github.com/comedianhhh/job-agent-skills/actions/workflows/ci.yml)

| Part | What it is | Stack |
|---|---|---|
| `skills/` | Ten skills — fit analysis, résumé tailoring with a one-page gate, form filling from standing answers, pipeline tracking, contract-based mock interviews, evidence recap | Markdown contracts |
| `mcp/jobs-mcp` | MCP server over Greenhouse / Lever / Ashby / LinkedIn guest search, no API keys; 43 tests on recorded HTTP fixtures, CI across Python 3.10–3.13 × two MCP SDK majors | Python, httpx |
| `web/` | Tracker: FastAPI service that edits the agent's own Markdown pipeline cell-by-cell, Postgres for history and scan triage, Next.js kanban with drag-and-drop, bearer auth, Docker Compose | FastAPI, PostgreSQL, Next.js 16 |
| `evals/` | 21-case `claude plugin eval` suite (110 graders) scoring the skills against a no-plugin baseline, with a fixture persona seeded with traps | regex / tool-use / LLM-judge graders |

## Products

| Product | My part | Stack |
|---|---|---|
| [**SoulLink**](https://apps.apple.com/us/app/soullink-3d-ai-life-sim/id6752530994) — AI companion, live on iOS / Android | Character runtime: streamed voice + LLM telemetry → lip-sync, look-at, animation state; interaction state machines; lead a 5-engineer team | C#, Unity, LLM runtime |
| [**Dungeon Company**](https://store.steampowered.com/app/3775930/Dungeon_Company/) — Steam, shown at XP Game Summit, 60,000+ playtest builds distributed | Founding member; schema-driven level tooling and gameplay systems | C#, Unity |

## Selected systems work

| Project | Highlights | Stack |
|---|---|---|
| [ARPG Demo](https://github.com/comedianhhh/ARPG-Demo) | Authoritative .NET server + Unity client, custom netcode, headless bot load tests, deterministic fixed-point | C#, .NET, Lua |
| [Space Shooter MP](https://github.com/comedianhhh/SpaceShooterMP) | Custom C++ engine, client-server, client-side prediction | C++17, Asio, UDP |
| [Computer Graphics Demo](https://github.com/comedianhhh/ComputerGraphicsDemo) | Multi-pass post-processing, normal/specular mapping | C#, MonoGame, HLSL |

## Stack

`Python` `C# / .NET` `TypeScript` `C++` · `FastAPI` `PostgreSQL` `Next.js / React` · `MCP servers` `agent skills & evals` · `Docker` `GitHub Actions` · `Unity`


