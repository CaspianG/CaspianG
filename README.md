<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/profile-hero.svg" alt="CaspianG builds dynamic memory infrastructure" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>Building WaveMind: dynamic memory infrastructure for software that must remember, adapt, and explain itself.</strong>
</p>

<p align="center">
  Local-first memory systems, retrieval infrastructure, benchmarks, and developer tools.
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-dynamic%20memory-050505?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=050505"></a>
  <a href="https://github.com/CaspianG/wavemind/actions/workflows/full-check.yml"><img alt="Checks" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/full-check.yml?branch=main&style=for-the-badge&label=checks&color=050505"></a>
  <a href="https://github.com/CaspianG/wavemind/releases"><img alt="Release" src="https://img.shields.io/github/v/release/CaspianG/wavemind?style=for-the-badge&label=release&color=050505"></a>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
  &nbsp;&middot;&nbsp;
  <a href="https://pypi.org/project/wavemind/">PyPI</a>
  &nbsp;&middot;&nbsp;
  <a href="https://github.com/CaspianG/wavemind#user-content-quick-start">Quick Start</a>
  &nbsp;&middot;&nbsp;
  <a href="https://github.com/CaspianG/wavemind#user-content-benchmark">Benchmarks</a>
  &nbsp;&middot;&nbsp;
  <a href="https://github.com/CaspianG/wavemind/issues">Issues</a>
</p>

---

<table>
  <tr>
    <td width="52%" valign="top">
      <h2>What I am focused on</h2>
      <p>
        My main work is <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>:
        a memory engine where recall is not just nearest-neighbor search.
      </p>
      <p>
        The database stays durable. Retrieval stays fast. Memory state changes over time:
        useful facts get stronger, stale facts fade, corrections remain traceable,
        and every result can be inspected.
      </p>
    </td>
    <td width="48%" valign="top">
      <h2>Try it in one minute</h2>
      <pre><code>pip install wavemind
wavemind quickstart
wavemind studio</code></pre>
      <p>
        CLI, Python API, HTTP API, Studio UI, persistent storage, vector backends,
        background workers, telemetry, and reproducible benchmark artifacts.
      </p>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/memory-loop.svg" alt="WaveMind recall flow: store, search, evolve, explain" width="100%" />
  </a>
</p>

## WaveMind In One View

| Layer | What it does |
| --- | --- |
| **Retrieval** | Finds candidate memories with hash/sentence encoders and vector backends. |
| **Memory state** | Applies hotness, decay, TTL, namespaces, feedback, and graph signals. |
| **Persistence** | Keeps SQLite/Postgres-compatible durable storage as the source of truth. |
| **Production path** | Tracks scale, latency, recall, observability, backups, and claim boundaries. |
| **Integrations** | Works through CLI, Python, HTTP, Studio, LangChain, LlamaIndex, and examples. |

## Current Work

| Area | Direction |
| --- | --- |
| **Scale** | Persisted indexes, service-backed retrieval, sharding, load profiles, and honest production evidence. |
| **Memory dynamics** | Hotness, decay, feedback, graph propagation, consolidation, stale-fact suppression, and explainable recall. |
| **Developer experience** | One-command demos, Studio UI, framework integrations, migration guides, and practical examples. |
| **Benchmarks** | Public datasets, reproducible reports, latency curves, retrieval quality, and long-memory evaluation. |

## Selected Projects

| Project | What it is | Status |
| --- | --- | --- |
| [**WaveMind**](https://github.com/CaspianG/wavemind) | Dynamic memory engine with CLI, HTTP API, Studio, workers, persistent storage, vector backends, benchmarks, and integrations. | Active |
| [**focus-flow**](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions with planning, session tracking, themes, and English/Russian UI. | Public |
| [**CORECITY**](https://github.com/CaspianG/CORECITY) | Browser game concept built around a living market mechanic driven by players. | Public |

## Stack

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-050505?style=flat-square&logo=python&logoColor=white">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-050505?style=flat-square&logo=fastapi&logoColor=white">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-050505?style=flat-square&logo=sqlite&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-050505?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="FAISS" src="https://img.shields.io/badge/FAISS-050505?style=flat-square">
  <img alt="Qdrant" src="https://img.shields.io/badge/Qdrant-050505?style=flat-square">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-050505?style=flat-square&logo=redis&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-050505?style=flat-square&logo=docker&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-050505?style=flat-square&logo=typescript&logoColor=white">
</p>

## Open For

| Collaboration | Good fit |
| --- | --- |
| **Benchmarks** | Long-memory evaluation, stale-fact suppression, retrieval quality, latency, cost efficiency, and agent-impact tests. |
| **Integrations** | LangChain, LangGraph, LlamaIndex, CrewAI, AutoGen, notebooks, local apps, and migration paths from static vector search. |
| **Product feedback** | Real workflows where memory needs to evolve, forget, explain, or preserve user-specific context over time. |

## Contact

Open a thread in [WaveMind issues](https://github.com/CaspianG/wavemind/issues) if you want to test the project, contribute an integration, add a benchmark, or discuss dynamic memory for production software.
