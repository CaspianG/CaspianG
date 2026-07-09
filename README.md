<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/profile-hero.svg" alt="CaspianG builds dynamic memory infrastructure" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>I build infrastructure for software that needs memory, state, and long-term context.</strong>
</p>

<p align="center">
  Main project:
  <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>,
  a local-first dynamic memory engine where recall is not just similarity search, but an evolving memory state.
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-dynamic%20memory-050505?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=050505"></a>
  <a href="https://github.com/CaspianG/wavemind/actions/workflows/full-check.yml"><img alt="Checks" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/full-check.yml?branch=main&style=for-the-badge&label=checks&color=050505"></a>
  <a href="https://github.com/CaspianG/wavemind/releases"><img alt="Release" src="https://img.shields.io/github/v/release/CaspianG/wavemind?style=for-the-badge&label=release&color=050505"></a>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><strong>Repository</strong></a>
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
    <td width="58%" valign="top">
      <h2>What I am building</h2>
      <p>
        Most memory systems retrieve the nearest vectors and stop there.
        WaveMind adds state on top of retrieval: useful memories get stronger,
        stale facts fade, corrections remain traceable, and recall can be inspected.
      </p>
      <p>
        The goal is a practical memory layer for long-running software:
        local by default, durable, benchmarked, and ready to grow into production deployments.
      </p>
    </td>
    <td width="42%" valign="top">
      <h2>Try it</h2>
      <pre><code>pip install wavemind
wavemind quickstart
wavemind studio</code></pre>
      <p>
        CLI, Python API, HTTP API, Studio UI, SQLite/Postgres persistence,
        FAISS/Qdrant paths, workers, telemetry, and benchmarks.
      </p>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/memory-loop.svg" alt="WaveMind memory architecture: store, retrieve, evolve, explain" width="100%" />
  </a>
</p>

## Current Focus

| Area | Direction |
| --- | --- |
| **Scale** | Persisted indexes, service-backed retrieval, sharding, production-load profiles, and honest claim boundaries. |
| **Memory dynamics** | Hotness, decay, TTL, feedback, graph signals, consolidation, stale-fact suppression, and explainable recall. |
| **Developer adoption** | Simple install, Studio UI, agent/framework integrations, examples, migration guides, and public benchmark reports. |
| **Reliability** | Backups, observability, auth/RBAC, rate limiting, reproducible tests, and CI-backed benchmark artifacts. |

## Selected Projects

| Project | What it is | Status |
| --- | --- | --- |
| [**WaveMind**](https://github.com/CaspianG/wavemind) | Dynamic memory engine with CLI, HTTP API, Studio, workers, persistent storage, vector backends, benchmark suite, and framework integrations. | Active |
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
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-050505?style=flat-square&logo=kubernetes&logoColor=white">
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
