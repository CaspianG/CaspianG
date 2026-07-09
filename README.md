<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/profile-hero.svg" alt="CaspianG builds adaptive memory systems with WaveMind" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>Building adaptive memory systems for software that needs durable context, controlled forgetting, and explainable recall.</strong>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-dynamic%20memory-050505?style=for-the-badge"></a>
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

## Building Now

[**WaveMind**](https://github.com/CaspianG/wavemind) is a local-first memory engine for long-running software: agents, research notebooks, internal copilots, local tools, and production systems where static context is not enough.

It stores facts and metadata durably, retrieves candidates through vector search, then applies memory behavior: TTL, priority, feedback, recall history, graph links, conflict handling, and auditable forgetting.

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

## Why WaveMind

| Static retrieval | Adaptive memory |
| --- | --- |
| Finds nearest vectors. | Tracks what is useful, fresh, stale, reinforced, or conflicting. |
| Old facts keep competing forever. | TTL, decay, corrections, and feedback can suppress stale facts. |
| Scores are often opaque. | Recall can expose score, provenance, namespace, and memory state. |
| Storage is the product. | Memory behavior is the product. |

## Current Direction

| Track | Shipping direction |
| --- | --- |
| **Scale** | FAISS, Qdrant, pgvector, sharding profiles, p95/p99 latency reports, and reproducible benchmark evidence. |
| **Memory dynamics** | Graph propagation, consolidation, stale-fact suppression, conflict handling, and self-organizing memory nodes. |
| **Product layer** | WaveMind Studio, visual memory maps, namespace explorer, feedback, backups, and operational dashboards. |
| **Integrations** | LangChain, LangGraph, LlamaIndex, CrewAI, AutoGen, notebooks, internal copilots, and migration guides. |

## Selected Work

| Project | What it is |
| --- | --- |
| [**WaveMind**](https://github.com/CaspianG/wavemind) | Dynamic memory engine with persistence, vector search, TTL, namespaces, graph recall, workers, Studio, CLI, HTTP API, Docker, benchmarks, and framework integrations. |
| [**focus-flow**](https://github.com/CaspianG/focus-flow) | Desktop focus timer for deep-work sessions with planning, session tracking, themes, and English/Russian UI. |
| [**CORECITY**](https://github.com/CaspianG/CORECITY) | Browser game concept around a living market mechanic driven by players. |

## Stack

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-050505?style=flat-square&logo=python&logoColor=white">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-050505?style=flat-square&logo=fastapi&logoColor=white">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-050505?style=flat-square&logo=sqlite&logoColor=white">
  <img alt="FAISS" src="https://img.shields.io/badge/FAISS-050505?style=flat-square">
  <img alt="Qdrant" src="https://img.shields.io/badge/Qdrant-050505?style=flat-square">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-050505?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-050505?style=flat-square&logo=redis&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-050505?style=flat-square&logo=docker&logoColor=white">
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-050505?style=flat-square&logo=kubernetes&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-050505?style=flat-square&logo=typescript&logoColor=white">
</p>

## Contact

Open a thread in [WaveMind issues](https://github.com/CaspianG/wavemind/issues) if you want to test the project, contribute an integration, add a benchmark, or discuss dynamic memory for production software.
