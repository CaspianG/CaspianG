<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/profile-hero.svg" alt="CaspianG builds WaveMind, adaptive memory infrastructure for long-running software" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>Building WaveMind: adaptive memory infrastructure for software that needs durable context, controlled forgetting, and explainable recall.</strong>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-memory%20engine-050505?style=for-the-badge"></a>
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

## Current Work

[**WaveMind**](https://github.com/CaspianG/wavemind) is an open-source memory engine for long-running software: agents, research notebooks, internal copilots, local tools, and production systems where static context is not enough.

It combines durable storage, vector retrieval, memory state, TTL, priority, feedback, graph recall, conflict handling, and auditable forgetting. The purpose is direct: memory should change as reality changes.

```bash
pip install wavemind
wavemind quickstart
wavemind studio
```

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/memory-loop.svg" alt="WaveMind memory loop: remember, retrieve, adapt, explain" width="100%" />
  </a>
</p>

## Why WaveMind Exists

| Ordinary vector search | WaveMind |
| --- | --- |
| Returns nearest neighbors. | Tracks which memories are useful, fresh, stale, reinforced, or conflicting. |
| Old facts keep competing forever. | TTL, decay, feedback, and corrections can suppress stale facts. |
| Memory is usually opaque. | Scores, provenance, namespaces, and state are inspectable. |
| Built mainly as storage. | Built as a memory layer above storage, indexes, and agent frameworks. |

## What I Build

| Area | What I care about |
| --- | --- |
| **Adaptive memory** | Hotness, decay, recall history, feedback, consolidation, and graph propagation. |
| **Local-first systems** | Software that works on a laptop first, then scales through FAISS, Qdrant, pgvector, Redis, and service backends. |
| **Production evidence** | Benchmarks, admission gates, CI, reproducible reports, and honest limitations. |
| **Developer adoption** | Python API, CLI, HTTP API, Docker, Studio, integrations, examples, and migration guides. |

## Featured Repositories

| Repository | Description |
| --- | --- |
| [**WaveMind**](https://github.com/CaspianG/wavemind) | Adaptive memory engine with persistence, vector search, TTL, namespaces, graph recall, workers, Studio, CLI, HTTP API, Docker, benchmarks, and framework integrations. |
| [**focus-flow**](https://github.com/CaspianG/focus-flow) | Desktop focus timer for deep-work sessions with planning, session tracking, themes, and English/Russian UI. |
| [**CORECITY**](https://github.com/CaspianG/CORECITY) | Browser game concept around a living market mechanic driven by players. |

## Active Roadmap

| Track | Next work |
| --- | --- |
| **Scale** | Persisted ANN indexes, service backends, sharding profiles, p95/p99 latency reports, and larger public benchmarks. |
| **Memory dynamics** | Graph propagation, consolidation, stale-fact suppression, conflict handling, and self-organizing memory nodes. |
| **Integrations** | LangChain, LangGraph, LlamaIndex, CrewAI, AutoGen, notebooks, internal copilots, and migration guides. |
| **Product layer** | WaveMind Studio, visual memory maps, namespace explorer, import/export, feedback, backups, and operational dashboards. |

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

## Contact

Open a thread in [WaveMind issues](https://github.com/CaspianG/wavemind/issues) if you want to test the project, contribute an integration, add a benchmark, or discuss dynamic memory for production software.
