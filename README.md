<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="assets/profile-hero.svg" alt="CaspianG builds adaptive memory infrastructure" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>I build adaptive memory infrastructure for software that needs to remember, update itself, forget stale facts, and stay inspectable.</strong>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-adaptive%20memory-050505?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=050505"></a>
  <a href="https://github.com/CaspianG/wavemind/actions/workflows/full-check.yml"><img alt="Checks" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/full-check.yml?branch=main&style=for-the-badge&label=checks&color=050505"></a>
  <a href="https://github.com/CaspianG/wavemind/releases"><img alt="Release" src="https://img.shields.io/github/v/release/CaspianG/wavemind?style=for-the-badge&label=release&color=050505"></a>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
  &nbsp;/&nbsp;
  <a href="https://pypi.org/project/wavemind/">PyPI</a>
  &nbsp;/&nbsp;
  <a href="https://github.com/CaspianG/wavemind#user-content-quick-start">Quick Start</a>
  &nbsp;/&nbsp;
  <a href="https://github.com/CaspianG/wavemind#user-content-benchmark">Benchmarks</a>
  &nbsp;/&nbsp;
  <a href="https://github.com/CaspianG/wavemind/issues">Contribute</a>
</p>

---

## Main Project

[**WaveMind**](https://github.com/CaspianG/wavemind) is an open-source memory engine for long-running software: agents, research notebooks, internal copilots, personal tools, and production systems that cannot rely on static context alone.

It stores durable memories, retrieves candidates with vector search, then applies memory state: freshness, priority, TTL, feedback, graph links, recall history, conflict handling, and forgetting. The goal is simple: memory should behave like a living system, not a frozen list of embeddings.

```bash
pip install wavemind
wavemind quickstart
wavemind studio
```

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="assets/memory-loop.svg" alt="WaveMind memory loop" width="100%" />
  </a>
</p>

## Why This Matters

| Static vector search | WaveMind |
| --- | --- |
| Stores vectors and returns nearest neighbors. | Stores memories and tracks how useful, fresh, stale, or conflicting they are. |
| Old facts keep competing forever. | TTL, decay, corrections, and feedback can suppress stale facts. |
| Retrieval is usually a black box. | Scores, provenance, namespaces, and memory state are inspectable. |
| Works well as storage. | Designed as a memory layer above storage and indexes. |

## What I Build For

| Direction | Focus |
| --- | --- |
| **Adaptive memory** | Hotness, decay, priority, corrections, consolidation, and graph-based recall. |
| **Local-first systems** | Tools that work on a laptop first, then scale to FAISS, Qdrant, pgvector, Redis, and service backends. |
| **Production evidence** | Benchmarks, admission gates, CI checks, reproducible artifacts, and honest limitations. |
| **Developer adoption** | Python API, CLI, HTTP API, Docker, Studio, integrations, examples, and clear documentation. |

## Featured Projects

| Project | What it does | Status |
| --- | --- | --- |
| [**WaveMind**](https://github.com/CaspianG/wavemind) | Adaptive memory engine with SQLite persistence, vector search, TTL, namespaces, graph recall, workers, Studio, CLI, HTTP API, Docker, benchmarks, and framework integrations. | Active |
| [**focus-flow**](https://github.com/CaspianG/focus-flow) | Desktop focus timer for deep-work sessions with light/dark themes and English/Russian UI. | Public |
| [**CORECITY**](https://github.com/CaspianG/CORECITY) | Browser game concept around a living market mechanic driven by players. | Public |

## Current Focus

| Track | Work in progress |
| --- | --- |
| Scale | Production admission gates, sharding profiles, ANN/service backends, p95/p99 latency, and larger public benchmarks. |
| Memory dynamics | Graph propagation, consolidation, stale-fact suppression, conflict handling, and self-organizing memory nodes. |
| Ecosystem | LangChain, LangGraph, LlamaIndex, CrewAI, AutoGen, local tools, notebooks, and migration guides. |
| Product layer | WaveMind Studio, visual memory maps, namespace explorer, import/export, feedback, backups, and operational dashboards. |

## Stack

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-050505?style=flat-square&logo=python&logoColor=white">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-050505?style=flat-square&logo=fastapi&logoColor=white">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-050505?style=flat-square&logo=sqlite&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-050505?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-050505?style=flat-square&logo=redis&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-050505?style=flat-square&logo=docker&logoColor=white">
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-050505?style=flat-square&logo=kubernetes&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-050505?style=flat-square&logo=typescript&logoColor=white">
</p>

## Open To

I am interested in long-term memory, retrieval systems, local-first developer tools, graph recall, privacy-aware forgetting, and production workloads where static vector search is not enough.

Good first contributions to WaveMind: framework integrations, migration guides, benchmark adapters, documentation examples, Studio improvements, and production backend profiles.

Start with the [WaveMind quick start](https://github.com/CaspianG/wavemind#user-content-quick-start), or open a thread in [WaveMind issues](https://github.com/CaspianG/wavemind/issues).
