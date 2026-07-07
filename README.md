<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.svg" alt="CaspianG - WaveMind, dynamic memory infrastructure for agents" width="100%" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-dynamic_memory-0B0F14?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=2F81F7"></a>
  <a href="https://github.com/CaspianG/wavemind/actions"><img alt="GitHub Actions" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/full-check.yml?branch=main&style=for-the-badge&label=checks"></a>
  <a href="https://github.com/CaspianG/wavemind/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/github/license/CaspianG/wavemind?style=for-the-badge&color=16A34A"></a>
</p>

<h3 align="center">I build memory infrastructure for agents, apps, and tools that need to remember, adapt, and stay useful over time.</h3>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">WaveMind</a>
  /
  <a href="https://github.com/CaspianG/wavemind#benchmarks">Benchmarks</a>
  /
  <a href="https://github.com/CaspianG/wavemind#quick-start">Quick start</a>
  /
  <a href="https://github.com/CaspianG?tab=repositories">Projects</a>
</p>

---

## Main Signal

Most memory layers are static vector tables. They embed text, search top-k, and hope the nearest chunk is still useful.

I am building **WaveMind** as a dynamic memory layer: local-first storage, namespaces, TTL, hotness, decay, feedback, consolidation, background jobs, production APIs, and benchmarked retrieval behavior.

```python
from wavemind import WaveMind

memory = WaveMind()
memory.remember("The user prefers short technical answers.", namespace="user")
answer = memory.query("How should I answer?", namespace="user")[0].text
print(answer)
```

## WaveMind Focus

| Track | What I am pushing toward |
| --- | --- |
| Memory OS | Background workers for prefetching, consolidation, adaptive forgetting, and priority prediction |
| Production scale | FastAPI service mode, Redis cache paths, sharding, replication, cluster repair, and operator readiness |
| Honest evaluation | LoCoMo, LongMemEval, BEIR/SciFact, scale readiness, VectorDBBench export, and living benchmark artifacts |
| Future memory | Structured and multimodal payloads, graph facts, temporal events, and agent-ready retrieval policies |

## Featured Work

| Project | Role | Status |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Dynamic long-term memory for agents and applications | Active |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Calm desktop timer for deep-work sessions | Stable |
| [CORECITY](https://github.com/CaspianG/CORECITY) | Online game concept around a player-driven live market | Experimental |

## What I Care About

- Memory should be useful, not just semantically close.
- Local-first tools should have a clean path to production.
- Benchmarks should separate real evidence from marketing claims.
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
