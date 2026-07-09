<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/profile-hero.svg" alt="CaspianG builds local-first dynamic memory systems" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>Building local-first memory infrastructure for software that needs durable context, controlled forgetting, and explainable recall.</strong>
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

<table>
  <tr>
    <td width="58%" valign="top">
      <h3><a href="https://github.com/CaspianG/wavemind">WaveMind</a></h3>
      <p>
        WaveMind is a dynamic memory layer for long-running software. It keeps SQLite/Postgres as the source of truth,
        retrieves candidates through vector indexes, then applies memory behavior: hotness, decay, TTL, feedback,
        graph links, conflict handling, provenance, and auditable forgetting.
      </p>
      <pre><code>pip install wavemind
wavemind quickstart
wavemind studio</code></pre>
    </td>
    <td width="42%" valign="top">
      <h3>What makes it different</h3>
      <p>
        Vector search answers "what text is similar?" WaveMind asks the next question:
        "what should still matter right now, and why?"
      </p>
      <p>
        The current focus is production-grade dynamic memory: scale, evaluation, visibility, and integrations.
      </p>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/memory-loop.svg" alt="WaveMind memory architecture: store, retrieve, evolve, explain" width="100%" />
  </a>
</p>

## Proof Points

<table>
  <tr>
    <td width="25%" valign="top">
      <h3>Persistence</h3>
      <p>SQLite source of truth, backups, import/export, namespaces, TTL, and forget semantics.</p>
    </td>
    <td width="25%" valign="top">
      <h3>Retrieval</h3>
      <p>Hash and sentence encoders, FAISS, Qdrant, pgvector paths, exact and ANN candidates.</p>
    </td>
    <td width="25%" valign="top">
      <h3>Dynamics</h3>
      <p>Hotness, decay, feedback, conflict handling, graph propagation, and consolidation experiments.</p>
    </td>
    <td width="25%" valign="top">
      <h3>Evidence</h3>
      <p>LoCoMo, LongMemEval, BEIR SciFact, production-load profiles, and cost-efficiency reports.</p>
    </td>
  </tr>
</table>

## Selected Projects

| Project | What it is | Status |
| --- | --- | --- |
| [**WaveMind**](https://github.com/CaspianG/wavemind) | Dynamic memory engine with CLI, HTTP API, Studio, workers, persistence, vector backends, benchmarks, and agent framework integrations. | Active |
| [**focus-flow**](https://github.com/CaspianG/focus-flow) | Desktop focus timer for deep-work sessions with planning, session tracking, themes, and English/Russian UI. | Public |
| [**CORECITY**](https://github.com/CaspianG/CORECITY) | Browser game concept around a living market mechanic driven by players. | Public |

## Current Roadmap

| Track | Current direction |
| --- | --- |
| Scale | Persisted FAISS, Qdrant service mode, pgvector, sharding profiles, p95/p99 latency, cost curves. |
| Memory behavior | Better stale-fact suppression, self-organizing graph memory, consolidation, correction handling. |
| Product | WaveMind Studio, memory maps, namespace explorer, live query tester, feedback, backup workflows. |
| Ecosystem | LangChain, LangGraph, LlamaIndex, CrewAI, AutoGen, notebooks, migration guides, real app examples. |

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
| Benchmarks | Long-memory evaluation, agent memory tasks, stale-fact suppression, retrieval quality, latency, and cost-efficiency. |
| Integrations | Agent frameworks, notebooks, local-first apps, internal tools, and migration paths from static vector search. |
| Product feedback | Real workflows where memory needs to evolve, forget, explain, or preserve user-specific context over time. |

## Contact

Open a thread in [WaveMind issues](https://github.com/CaspianG/wavemind/issues) if you want to test the project, contribute an integration, add a benchmark, or discuss dynamic memory for production software.
