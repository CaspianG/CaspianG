<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="https://raw.githubusercontent.com/CaspianG/CaspianG/main/assets/profile-hero.svg" alt="CaspianG builds local-first memory infrastructure" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>Building local-first memory infrastructure for software that has to keep context, adapt over time, and stay inspectable.</strong>
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

## Main Work

[**WaveMind**](https://github.com/CaspianG/wavemind) is my main project: an open-source memory engine for agents, research notebooks, internal copilots, personal tools, and long-running software.

It keeps memory as durable records, retrieves candidates with vector search, and then applies memory state: freshness, priority, TTL, recall signals, graph links, feedback, and forgetting. The point is not to replace every vector database. The point is to make memory behave like a system, not like a static list of embeddings.

```bash
pip install wavemind
wavemind quickstart
wavemind studio
```

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="https://raw.githubusercontent.com/CaspianG/CaspianG/main/assets/memory-loop.svg" alt="WaveMind memory loop" width="100%" />
  </a>
</p>

## What I Build For

| Direction | Focus |
| --- | --- |
| **Dynamic memory** | Hotness, decay, priority, corrections, consolidation, and graph-based recall. |
| **Local-first systems** | Tools that work on a laptop first, then scale to service backends when the workload grows. |
| **Inspectable infrastructure** | Memory that can be queried, explained, forgotten, backed up, benchmarked, and audited. |
| **Useful products** | Small interfaces, CLIs, APIs, examples, and docs that make the system understandable fast. |

## Featured Projects

| Project | What it does | Status |
| --- | --- | --- |
| [**WaveMind**](https://github.com/CaspianG/wavemind) | Dynamic memory engine with SQLite persistence, vector search, TTL, namespaces, graph recall, workers, Studio, CLI, HTTP API, Docker, benchmarks, and framework examples. | Active |
| [**focus-flow**](https://github.com/CaspianG/focus-flow) | Desktop focus timer for deep-work sessions with light/dark themes and English/Russian UI. | Public |
| [**CORECITY**](https://github.com/CaspianG/CORECITY) | Browser game concept around a living market mechanic driven by players. | Public |

## Current Roadmap

| Track | Next step |
| --- | --- |
| Scale | Faster ANN backends, stricter production admission gates, and larger public benchmark profiles. |
| Memory dynamics | Better graph propagation, consolidation, stale-fact suppression, and conflict handling. |
| Ecosystem | More integrations for agent frameworks, notebooks, and local tools. |
| Product layer | WaveMind Studio, visual memory maps, namespace explorer, import/export, and feedback loops. |

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

I am interested in long-term memory, retrieval systems, agent infrastructure, local-first developer tools, graph recall, privacy-aware forgetting, and production workloads where static vector search is not enough.

Start with the [WaveMind quick start](https://github.com/CaspianG/wavemind#user-content-quick-start). If you want to help, open a thread in [WaveMind issues](https://github.com/CaspianG/wavemind/issues).
