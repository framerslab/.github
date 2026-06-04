<div align="center">

# Frame.dev

### AI Infrastructure for Autonomous Agents

**Frame** (Framers Lab, Inc.) is the AI infrastructure company building the open-source runtime and platforms that production AI agents run on: **AgentOS**, **Paracosm**, **Wilds.ai**, and **SafeOS**. Adaptive, open source, local-first, AI-native, and yours.

[Website](https://frame.dev) · [AgentOS](https://agentos.sh) · [Docs](https://docs.agentos.sh) · [Paracosm](https://paracosm.agentos.sh) · [Wilds AI](https://wilds.ai) · [npm](https://www.npmjs.com/~framers) · [Twitter](https://twitter.com/framerslab)

</div>

---

## 🤖 AgentOS · Flagship

<div align="center">

**TypeScript Agent Runtime with Cognitive Memory, HEXACO Personality, and Runtime Tool Forging**

Build AI agents that remember, reason, and forge their own tools. The runtime carries the parts of an agent that should outlive a single chat completion: persistent cognitive memory grounded in cognitive-science literature, optional HEXACO personality, runtime tool forging in a hardened sandbox, six multi-agent orchestration strategies, streaming guardrails, voice pipeline, and one dispatch interface across 11 LLM providers.

**LongMemEval-S 85.6%** at $0.0090 per correct, +1.4 points above Mastra OM gpt-4o (84.23%) at the matched reader · **LongMemEval-M 70.2%** at $0.0078 per correct, competitive with the strongest published M results in the LongMemEval paper (Wu et al., ICLR 2025, Table 3: round Top-5 65.7%, session Top-5 71.4%, round Top-10 72.0%); the only open-source library on the public record above 65% on M with publicly reproducible methodology. See [`agentos-bench`](https://github.com/framerslab/agentos-bench) for raw run JSONs, leaderboard, and methodology audit.

[Website](https://agentos.sh) · [Docs](https://docs.agentos.sh) · [Bench](https://github.com/framerslab/agentos-bench) · [npm](https://www.npmjs.com/package/@framers/agentos)

</div>

| Package | Description | Links |
|---------|-------------|-------|
| [`@framers/agentos`](https://github.com/framerslab/agentos) | Core runtime & cognitive substrate | [![npm](https://img.shields.io/npm/v/@framers/agentos)](https://www.npmjs.com/package/@framers/agentos) |
| [`agentos-bench`](https://github.com/framerslab/agentos-bench) | Open benchmark harness (LongMemEval, LOCOMO, BEAM, micro-bench) | [Leaderboard](https://github.com/framerslab/agentos-bench/blob/master/results/LEADERBOARD.md) |
| [`agentos.sh`](https://github.com/framerslab/agentos.sh) | Marketing, documentation & playground | [Website](https://agentos.sh) |
| [`agentos-workbench`](https://github.com/framerslab/agentos-workbench) | Full-featured client for building and testing agents | |
| [`agentos-extensions`](https://github.com/framerslab/agentos-extensions) | Extension marketplace & samples | [![npm](https://img.shields.io/npm/v/@framers/agentos-extensions)](https://www.npmjs.com/package/@framers/agentos-extensions) |
| [`agentos-extensions-registry`](https://github.com/framerslab/agentos-extensions-registry) | Curated extension registry SDK | [![npm](https://img.shields.io/npm/v/@framers/agentos-extensions-registry)](https://www.npmjs.com/package/@framers/agentos-extensions-registry) |
| [`agentos-skills`](https://github.com/framerslab/agentos-skills) | Community skill registry (69 SKILL.md modules) | [![npm](https://img.shields.io/npm/v/@framers/agentos-skills)](https://www.npmjs.com/package/@framers/agentos-skills) |
| [`agentos-skills-registry`](https://github.com/framerslab/agentos-skills-registry) | Curated skills registry SDK | [![npm](https://img.shields.io/npm/v/@framers/agentos-skills-registry)](https://www.npmjs.com/package/@framers/agentos-skills-registry) |
| [`agentos-personas`](https://github.com/framerslab/agentos-personas) | Persona registry for GMI personalities | |
| [`agentos-live-docs`](https://github.com/framerslab/agentos-live-docs) | Live documentation pages | |

---

## 🌀 Paracosm

<div align="center">

**AI Agent Swarm Simulation Engine**

Spawn autonomous agent swarms from JSON scenario definitions. Emergent tool forging, HEXACO personality evolution, deterministic divergence kernels. Two AI commanders run the same world and diverge based on personality. Built on AgentOS.

[Live Demo](https://paracosm.agentos.sh/sim) · [Landing Page](https://paracosm.agentos.sh) · [npm](https://www.npmjs.com/package/paracosm)

</div>

| Package | Description | Links |
|---------|-------------|-------|
| [`paracosm`](https://github.com/framerslab/paracosm) | Simulation engine, compiler, runtime, dashboard | [![npm](https://img.shields.io/npm/v/paracosm)](https://www.npmjs.com/package/paracosm) |

---

## 🌍 Wilds AI

<div align="center">

**AI-Native Story Worlds**

Companions that remember. Adventures that adapt. Multiplayer simulation playground where AgentOS agents with cognitive memory and HEXACO personality inhabit Paracosm-compiled worlds. Drop into existing worlds, fork them, or compile new ones in the browser.

[Website](https://wilds.ai)

</div>

| Package | Description | Links |
|---------|-------------|-------|
| [`wilds-ai`](https://wilds.ai) | AI-native gaming platform built on AgentOS + Paracosm | [Website](https://wilds.ai) |

---

## 🗄️ Developer Tools

| Package | Description | Links |
|---------|-------------|-------|
| [`sql-storage-adapter`](https://github.com/framerslab/sql-storage-adapter) | Universal cross-platform SQL access (SQLite, Postgres, IndexedDB, Capacitor) | [![npm](https://img.shields.io/npm/v/@framers/sql-storage-adapter)](https://www.npmjs.com/package/@framers/sql-storage-adapter) |
| [`promptmachine-eval`](https://github.com/framerslab/promptmachine-eval) | LLM evaluation framework with ELO ratings & arena battles | |

---

## 🛡️ SafeOS

**Humanitarian AI Monitoring.** Free forever, offline-first virtual guardian for pets, babies, and elderly care.

| Package | Description |
|---------|-------------|
| [`safeos`](https://github.com/framerslab/safeos) | Localized offline virtual guardian |

---

## 🌐 Community

| Resource | Link |
|----------|------|
| [`discussions`](https://github.com/framerslab/discussions) | Community discourse & feedback |
| [`voice-chat-assistants`](https://github.com/framerslab/voice-chat-assistants) | Marketplace for voice chat assistants |

---

## 🏢 About Frame

**Frame** (Framers Lab, Inc.) is the AI infrastructure company building the open-source runtime and platforms that production AI agents run on. The flagship is **AgentOS**, an Apache-2.0 TypeScript AI agent runtime with cognitive memory, HEXACO personality, multi-agent orchestration, and 11 LLM providers, scored 85.6% on LongMemEval-S at $0.0090 per correct. AgentOS powers **Wilds.ai**, a live AI-native gaming platform. Everything published here runs the same code that ships to production.

**Topics:** AI agents · AI infrastructure · AI agent runtime · cognitive memory · multi-agent orchestration · LLM orchestration · TypeScript · open source · RAG · vector search · voice AI · AI gaming

---

<div align="center">

[![Backed by Deepgram for Startups](https://img.shields.io/badge/Backed_by-Deepgram_for_Startups-13EF93?style=flat-square&logo=deepgram&logoColor=black)](https://deepgram.com/startups)

**Built by [Frame](https://frame.dev)** · © 2026 Framers Lab, Inc. · AgentOS is Apache-2.0; other projects under their own LICENSE files

[frame.dev](https://frame.dev) · [@framerslab](https://twitter.com/framerslab) · [github.com/framerslab](https://github.com/framerslab) · [npm](https://www.npmjs.com/~framers)

</div>
