```

  ███████╗████████╗██████╗  █████╗ ████████╗ █████╗
  ██╔════╝╚══██╔══╝██╔══██╗██╔══██╗╚══██╔══╝██╔══██╗
  ███████╗   ██║   ██████╔╝███████║   ██║   ███████║
  ╚════██║   ██║   ██╔══██╗██╔══██║   ██║   ██╔══██║
  ███████║   ██║   ██║  ██║██║  ██║   ██║   ██║  ██║
  ╚══════╝   ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═╝   ╚═╝   ╚═╝  ╚═╝
  ███████╗ ██████╗ ███████╗████████╗██╗    ██╗ █████╗ ██████╗ ███████╗
  ██╔════╝██╔═══██╗██╔════╝╚══██╔══╝██║    ██║██╔══██╗██╔══██╗██╔════╝
  ███████╗██║   ██║█████╗     ██║   ██║ █╗ ██║███████║██████╔╝█████╗
  ╚════██║██║   ██║██╔══╝     ██║   ██║███╗██║██╔══██║██╔══██╗██╔══╝
  ███████║╚██████╔╝██║        ██║   ╚███╔███╔╝██║  ██║██║  ██║███████╗
  ╚══════╝ ╚═════╝ ╚═╝        ╚═╝    ╚══╝╚══╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝
   ██████╗ ██████╗  ██████╗ ██╗   ██╗██████╗
  ██╔════╝ ██╔══██╗██╔═══██╗██║   ██║██╔══██╗
  ██║  ███╗██████╔╝██║   ██║██║   ██║██████╔╝
  ██║   ██║██╔══██╗██║   ██║██║   ██║██╔═══╝
  ╚██████╔╝██║  ██║╚██████╔╝╚██████╔╝██║
   ╚═════╝ ╚═╝  ╚═╝ ╚═════╝  ╚═════╝ ╚═╝
```

> **We build tools that build things.**

```
  ┌──────────────────────────────────────────────────────────────────┐
  │  James Walton                                                    │
  │  Construction estimator turned developer                         │
  │  Self-taught · 7 months · AI as a build partner                  │
  │                                                                  │
  │  Python · TypeScript · Rust · Elixir · Swift                     │
  │  40 projects · 1.6M lines · 7 languages · 1 fine-tuned model    │
  │                                                                  │
  │  Strata Software Group · Mississippi                             │
  └──────────────────────────────────────────────────────────────────┘
```

---

## What I Ship

I come from construction — estimating jobs, managing crews, understanding how physical things get built. Now I build software the same way: scope it, plan it, execute it, ship it.

```
  ╔══════════════════════════════════════════════════════════════════╗
  ║                         PRODUCTS                                ║
  ╠══════════════════════════════════════════════════════════════════╣
  ║                                                                 ║
  ║   FAIRTRADEWORKER    Two-sided construction marketplace          ║
  ║   ───────────────    Homeowners post · Contractors bid           ║
  ║                      Elixir realtime · React Native mobile      ║
  ║                      QuickBooks-native · Custom AI estimation   ║
  ║                                                                 ║
  ║   MHP ESTIMATE       Client estimation platform                  ║
  ║   ────────────       Built for MHP Construction (Oxford, MS)    ║
  ║                      First paying customer · Deployed on Vercel ║
  ║                                                                 ║
  ║   DRIFTLANDS         Survival crafting game                      ║
  ║   ──────────         Rust/Bevy ECS · Procedural worlds          ║
  ║                      Combat · Crafting · Dungeons               ║
  ║                                                                 ║
  ╠══════════════════════════════════════════════════════════════════╣
  ║                          TOOLS                                  ║
  ╠══════════════════════════════════════════════════════════════════╣
  ║                                                                 ║
  ║   AI KNOWS ME        Screen intelligence (open source)           ║
  ║   ───────────        OCR capture · Knowledge graph · REST API   ║
  ║                      Encrypted · Plugin system · 58 MCP tools   ║
  ║                                                                 ║
  ║   AEON               Formal verification engine                  ║
  ║   ────               Multi-language static analysis · Z3 SMT   ║
  ║                      Catches what tests and linters miss        ║
  ║                                                                 ║
  ║   CONSTRUCTIONAI     Fine-tuned Llama 3.1 8B                     ║
  ║   ──────────────     5,200+ real training examples              ║
  ║                      Construction cost estimation               ║
  ║                                                                 ║
  ║   G-RUMP             macOS AI coding agent                       ║
  ║   ──────             54K lines Swift · Multi-provider           ║
  ║                      100+ tools · MCP · 6 agent modes           ║
  ║                                                                 ║
  ╚══════════════════════════════════════════════════════════════════╝
```

### How the pieces connect

```
  ┌─────────────────────────────────────────────────────────────────┐
  │                                                                  │
  │   ConstructionAI ──── powers ────► FairTradeWorker               │
  │        │                               │                         │
  │        │                          FTW Realtime (Elixir)          │
  │        │                          FTW Mobile (React Native)      │
  │        │                               │                         │
  │   FairEstimator ──── template ───► MHP Estimate (client)         │
  │                                                                  │
  │   AI Knows ME ─────── context ───► Every Claude Code session     │
  │                                                                  │
  │   AEON ────────────── verifies ──► All of the above              │
  │                                                                  │
  └─────────────────────────────────────────────────────────────────┘
```

---

## Featured Repos

### [AI Knows ME](https://github.com/Aphrodine-wq/ai-knows-me)
Open source screen intelligence. Watches your screen (OCR text only — no screenshots stored), builds a searchable knowledge graph, syncs to Obsidian, and exposes a REST API so any AI agent can query your screen memory. Encrypted at rest with OS keychain. What Microsoft Recall promised but couldn't ship. What Rewind.ai abandoned. This one is running.

### [FairTradeWorker](https://github.com/Aphrodine-wq/FairTradeWorker)
Construction marketplace that eliminates exploitative lead fees. Flat monthly subscription gives pros tools, qualified matches, and a compounding reputation. Real-time bidding and chat via Elixir/Phoenix. AI estimation via a custom fine-tuned model trained on real project data.

### [AEON](https://github.com/Aphrodine-wq/AEON)
Multi-language formal verification engine. 20+ language adapters, Z3 SMT solver, symbolic execution, taint analysis. Catches division-by-zero, injection, race conditions, and logic bugs that tests miss. Runs across all my projects as a pre-release gate.

### [Driftlands](https://github.com/Aphrodine-wq/Driftlands)
Survival crafting game in Rust/Bevy 0.15. Procedural world generation, real-time combat, crafting, farming, building, dungeons, NPCs, weather, day/night cycle. Targeting Steam Early Access.

---

## How I Work

```
  ┌─────────────────────────────────────────────────────────────────┐
  │                                                                  │
  │    ██╗    ██╗ █████╗ ██╗  ████████╗                              │
  │    ██║    ██║██╔══██╗██║  ╚══██╔══╝                              │
  │    ██║ █╗ ██║███████║██║     ██║                                  │
  │    ██║███╗██║██╔══██║██║     ██║                                  │
  │    ╚███╔███╔╝██║  ██║███████╗██║                                  │
  │     ╚══╝╚══╝ ╚═╝  ╚═╝╚══════╝╚═╝                                  │
  │                                                                  │
  │    68 custom skills  ·  27 workflow commands                      │
  │    Quad-AI orchestration  ·  Overnight autonomous runner         │
  │    Obsidian knowledge vault  ·  Screen memory integration        │
  │                                                                  │
  └─────────────────────────────────────────────────────────────────┘
```

I build with AI as a native tool, not an afterthought. Claude is my primary build partner — architecture, implementation, review. Codex, Gemini, and MiniMax when a problem benefits from multiple perspectives.

The construction background gives me project management instincts, cost awareness, and a bias toward shipping. The AI gives me reach across stacks I couldn't have learned sequentially.

40 projects. 1.6 million lines. 7 months. Not because I'm fast — because the tools have changed what one person can do.

---

## Tech

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Elixir](https://img.shields.io/badge/Elixir-4B275F?style=flat-square&logo=elixir&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Bevy](https://img.shields.io/badge/Bevy-232326?style=flat-square&logo=bevy&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

---

```
  ┌──────────────────────────────────────────────────────────────────┐
  │                                                                   │
  │   "There is no palette. There is only the void                    │
  │    and what emerges from it."                                     │
  │                                                    — MONOLITH     │
  │                                                                   │
  └──────────────────────────────────────────────────────────────────┘
```

<p align="center">
  <b>Strata Software Group</b><br>
  <sub>Building under the void.</sub>
</p>
