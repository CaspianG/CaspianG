<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.svg" alt="CaspianG - dynamic memory systems for adaptive software" width="100%" />
  </a>
</p>

<h2 align="center">Building memory infrastructure for software that should remember what matters.</h2>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">WaveMind</a>
  /
  <a href="https://pypi.org/project/wavemind/">PyPI</a>
  /
  <a href="https://github.com/CaspianG/wavemind#quick-start">Quick start</a>
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

## Current Focus

I am building [WaveMind](https://github.com/CaspianG/wavemind): a local-first memory layer for agents and applications.

Most memory systems stop at vector search. WaveMind adds lifecycle and behavior around memory: hotness, decay, TTL, namespaces, reinforcement, consolidation, service APIs, and benchmarks.

```python
from wavemind import WaveMind

memory = WaveMind()
memory.remember("The user prefers short technical answers.", namespace="user")

result = memory.query("How should I answer?", namespace="user")[0]
print(result.text)
```

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/wavemind-map.svg" alt="WaveMind memory loop: store, retrieve, reinforce, decay, consolidate" width="100%" />
  </a>
</p>

## What I Build

| Area | Work |
| --- | --- |
| Dynamic memory | Agent memory that adapts with usage instead of staying a static vector table |
| Retrieval systems | Vector search, reranking, namespaces, TTL, decay, and production query paths |
| Benchmarks | Reproducible checks for recall, latency, scale readiness, and memory behavior |
| Developer tools | Simple APIs, CLI flows, FastAPI services, examples, and integrations |

## Featured Projects

| Project | Status | Why it matters |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Active | Dynamic long-term memory for agents and apps |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Stable | Minimal desktop focus timer I use myself for focused work; simple and effective |

## Principles

- Useful recall is more important than nearest-neighbor recall.
- Local-first should be easy, but production paths should be real.
- Benchmarks should separate evidence from claims.
- A good developer experience should fit in minutes, not days.

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

If you are looking for the main project, start with [CaspianG/wavemind](https://github.com/CaspianG/wavemind).
