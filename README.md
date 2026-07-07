<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.svg" alt="CaspianG - WaveMind, dynamic memory infrastructure for agents" width="100%" />
  </a>
</p>

<h3 align="center">Building WaveMind: dynamic memory infrastructure for agents that need to remember, adapt, and stay useful.</h3>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">WaveMind</a>
  /
  <a href="https://pypi.org/project/wavemind/">PyPI</a>
  /
  <a href="https://github.com/CaspianG/wavemind#benchmarks">Benchmarks</a>
  /
  <a href="https://github.com/CaspianG/wavemind#quick-start">Quick start</a>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-dynamic_memory-0B0F14?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=2F81F7"></a>
  <a href="https://github.com/CaspianG/wavemind/actions"><img alt="Checks" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/full-check.yml?branch=main&style=for-the-badge&label=checks"></a>
  <a href="https://github.com/CaspianG/wavemind/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/github/license/CaspianG/wavemind?style=for-the-badge&color=16A34A"></a>
</p>

---

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/wavemind-map.svg" alt="WaveMind system map" width="100%" />
  </a>
</p>

## What I Am Building

Most memory layers behave like static vector tables: embed text, search top-k, paste the nearest chunks back into context.

**WaveMind** is built around a different idea: memory should be alive enough to change with usage. It should keep what matters, fade what is stale, isolate projects and users, and make retrieval useful instead of merely similar.

```python
from wavemind import WaveMind

memory = WaveMind()
memory.remember("The user prefers short technical answers.", namespace="user")

answer = memory.query("How should I answer?", namespace="user")[0].text
print(answer)
```

## Current Direction

| Track | Direction |
| --- | --- |
| Memory OS | Background workers for priority prediction, prefetching, consolidation, and adaptive forgetting |
| Production path | FastAPI service mode, Redis cache, sharding, replication, repair loops, and operator readiness |
| Benchmarks | Living artifacts for memory quality, scale readiness, load profiles, and VectorDBBench export |
| Future memory | Structured payloads, graph facts, temporal events, and multimodal-ready storage |

## Project Focus

| Project | Why it exists |
| --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Dynamic long-term memory for agents and applications: local-first by default, production-aware when needed |
| [focus-flow](https://github.com/CaspianG/focus-flow) | A small desktop focus timer I use myself for deep-work blocks; simple, quiet, and effective |

## Principles

- Useful recall beats nearest-neighbor recall.
- Local-first should not block a real production path.
- Benchmarks should separate evidence from claims.
- Developer experience should stay simple enough to try in minutes.

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

## Start Here

The main project is [CaspianG/wavemind](https://github.com/CaspianG/wavemind): a practical memory engine for software that should remember what matters, forget what expired, and adapt as usage changes.
