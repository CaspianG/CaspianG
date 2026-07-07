<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.svg" alt="CaspianG - dynamic memory infrastructure" width="100%" />
  </a>
</p>

<h2 align="center">Building memory infrastructure for software that should remember, adapt, and forget.</h2>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">WaveMind</a>
  /
  <a href="https://pypi.org/project/wavemind/">PyPI</a>
  /
  <a href="https://github.com/CaspianG/wavemind#quick-start">Quick Start</a>
  /
  <a href="https://github.com/CaspianG/wavemind#benchmarks">Benchmarks</a>
  /
  <a href="https://github.com/CaspianG/wavemind/issues">Issues</a>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-dynamic%20memory-0B0F14?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=111827"></a>
  <a href="https://github.com/CaspianG/wavemind/actions"><img alt="Checks" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/full-check.yml?branch=main&style=for-the-badge&label=checks"></a>
  <a href="https://github.com/CaspianG/wavemind/releases"><img alt="Release" src="https://img.shields.io/github/v/release/CaspianG/wavemind?style=for-the-badge&label=release&color=111827"></a>
</p>

---

## Current Work

I am building [WaveMind](https://github.com/CaspianG/wavemind), a local-first memory layer for applications that need more than static vector search.

Most retrieval systems answer one question: "what is closest?" WaveMind adds the behavior around memory: hotness, decay, TTL, namespaces, reinforcement, consolidation, APIs, benchmarks, and production readiness checks.

```python
from wavemind import WaveMind

memory = WaveMind()
memory.remember("The user prefers short technical answers.", namespace="user")

result = memory.query("How should I answer?", namespace="user")[0]
print(result.text)
```

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/wavemind-map.svg" alt="WaveMind memory loop" width="100%" />
  </a>
</p>

## What I Care About

| Area | Focus |
| --- | --- |
| Dynamic memory | Memory that changes with usage instead of staying a passive vector table |
| Retrieval quality | Recall, reranking, stale-fact suppression, namespaces, and query latency |
| Local-first systems | SQLite source of truth, optional vector backends, reproducible installs |
| Production evidence | Tests, benchmark reports, CI gates, packaging, and clear limitations |

## Featured Projects

| Project | What it is | Status |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Dynamic long-term memory for agents and applications | Active |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions | Stable |
| [CORECITY](https://github.com/CaspianG/CORECITY) | Browser game concept built around a live market mechanic | Public archive |

## Stack

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=white">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-111827?style=flat-square&logo=fastapi&logoColor=white">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-111827?style=flat-square&logo=sqlite&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-111827?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-111827?style=flat-square&logo=redis&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-111827?style=flat-square&logo=docker&logoColor=white">
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-111827?style=flat-square&logo=kubernetes&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-111827?style=flat-square&logo=typescript&logoColor=white">
</p>

## Principles

- Useful recall matters more than nearest-neighbor recall.
- Memory should have lifecycle: reinforce, expire, consolidate, and forget.
- Benchmarks should separate evidence from claims.
- Developer experience should fit in minutes, not days.

## Start Here

The main project is [CaspianG/wavemind](https://github.com/CaspianG/wavemind).

```bash
pip install wavemind
```
