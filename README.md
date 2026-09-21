# Alan Li

Full-stack engineer in Toronto. I build small products people actually use, and tooling for coding agents. Before that I worked in Unity and Unreal: I led the embodied-agent runtime team at [SoulLink](https://speedrun.a16z.com/companies/soullink), an a16z speedrun company, and wrote netcode for a multiplayer action RPG.

[Portfolio](https://comedianhhh.github.io/Portfolio/) · [LinkedIn](https://www.linkedin.com/in/nianzhi-li)

## Things I made

- **[job-agent-skills](https://github.com/comedianhhh/job-agent-skills)** — a job-search toolkit for coding agents: skills, an MCP server over the big job boards, a tracker, an eval suite. It only writes facts you wrote. [![CI](https://github.com/comedianhhh/job-agent-skills/actions/workflows/ci.yml/badge.svg)](https://github.com/comedianhhh/job-agent-skills/actions/workflows/ci.yml)
- **[tsgate](https://github.com/comedianhhh/tsgate)** — an LLM gateway with no public port and no keys to hand out: who you are is the Tailscale connection, and every request leaves an audit line. Go.
- **[bloub tarot](https://bloub-tarot.alan996.workers.dev)** · **[bloub board](https://bloub-board.alan996.workers.dev)** · **[bloub-react](https://github.com/comedianhhh/bloub-react)** — a black ball that changes shape, and two small things built around it.

## Elsewhere

- [CoplayDev/unity-mcp#1404](https://github.com/CoplayDev/unity-mcp/pull/1404) — turning on its Roslyn option broke the build. Removed the missing dependency and added a test so it stays out. C#, merged.
- [grafana/mcp-grafana#1208](https://github.com/grafana/mcp-grafana/pull/1208) — its tests couldn't run on Windows. Fixed; merged the same day. Go.

## Shipped

| | My part |
|---|---|
| [**SoulLink**](https://apps.apple.com/us/app/soullink-3d-ai-life-sim/id6752530994) — AI companion, live on iOS / Android | Character runtime: streamed voice and LLM telemetry into real-time animation state; led a five-engineer team. C#, Unity. |
| [**Dungeon Company**](https://store.steampowered.com/app/3775930/Dungeon_Company/) — Steam, shown at XP Game Summit | Founding member; level tooling and gameplay systems. C#, Unity. |

Earlier: an [authoritative .NET server + Unity client](https://github.com/comedianhhh/ARPG-Demo) with custom netcode, and a [C++ client-server engine](https://github.com/comedianhhh/SpaceShooterMP) with client-side prediction.
