<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/profile-hero.svg" alt="CaspianG builds dynamic memory systems" width="100%" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-dynamic%20memory-050505?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=050505"></a>
  <a href="https://github.com/CaspianG/wavemind/actions/workflows/full-check.yml"><img alt="Checks" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/full-check.yml?branch=main&style=for-the-badge&label=checks&color=050505"></a>
  <a href="https://github.com/CaspianG/wavemind/releases"><img alt="Release" src="https://img.shields.io/github/v/release/CaspianG/wavemind?style=for-the-badge&label=release&color=050505"></a>
</p>

<h1 align="center">CaspianG</h1>

<h3 align="center">
  Building dynamic memory infrastructure for software that needs context to survive time.
</h3>

<p align="center">
  My main project is <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>:
  a local-first memory layer with durable storage, vector candidates, hotness, decay, TTL,
  namespaces, graph signals, provenance, and explainable recall.
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><strong>Repository</strong></a>
  &nbsp;/&nbsp;
  <a href="https://pypi.org/project/wavemind/">PyPI</a>
  &nbsp;/&nbsp;
  <a href="https://github.com/CaspianG/wavemind#user-content-quick-start">Quick Start</a>
  &nbsp;/&nbsp;
  <a href="https://github.com/CaspianG/wavemind#user-content-benchmark">Benchmarks</a>
  &nbsp;/&nbsp;
  <a href="https://github.com/CaspianG/wavemind/issues">Issues</a>
</p>

---

<table>
  <tr>
    <td width="58%" valign="top">
      <h2>WaveMind</h2>
      <p>
        Vector databases retrieve similar text. WaveMind adds memory behavior on top:
        what was useful gets stronger, stale facts fade, conflicts stay traceable,
        and every recall can be inspected.
      </p>
      <pre><code>pip install wavemind
wavemind quickstart
wavemind studio</code></pre>
      <p>
        Built for agents, personal tools, research notebooks, support systems,
        internal copilots, and any app where memory needs to evolve instead of only store.
      </p>
    </td>
    <td width="42%" valign="top">
      <h2>Current focus</h2>
      <ul>
        <li>Production-scale memory benchmarks.</li>
        <li>FAISS, Qdrant, pgvector, and hybrid search paths.</li>
        <li>Graph memory, stale-fact suppression, and consolidation.</li>
        <li>Studio UI, observability, and agent framework integrations.</li>
      </ul>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/memory-loop.svg" alt="WaveMind memory architecture: store, search, evolve, explain" width="100%" />
  </a>
</p>

## What I Build

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>Memory systems</h3>
      <p>Persistent, inspectable memory for long-running software: namespaces, TTL, forgetting, feedback, graph links, and recall scoring.</p>
    </td>
    <td width="33%" valign="top">
      <h3>Evaluation</h3>
      <p>Benchmarks for long-context recall, dynamic memory behavior, latency, cost efficiency, production load, and agent impact.</p>
    </td>
    <td width="33%" valign="top">
      <h3>Local-first tools</h3>
      <p>Practical software that can run on a developer machine first, then scale into services when the use case proves itself.</p>
    </td>
  </tr>
</table>

## Selected Projects

| Project | What it is | Status |
| --- | --- | --- |
| [**WaveMind**](https://github.com/CaspianG/wavemind) | Dynamic memory engine with CLI, HTTP API, Studio, workers, SQLite/Postgres persistence, vector backends, benchmarks, and framework integrations. | Active |
| [**focus-flow**](https://github.com/CaspianG/focus-flow) | Desktop focus timer for deep-work sessions with planning, session tracking, themes, and English/Russian UI. | Public |
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
| Benchmarks | Long-memory evaluation, stale-fact suppression, retrieval quality, latency, cost-efficiency, and agent-impact tests. |
| Integrations | LangChain, LangGraph, LlamaIndex, CrewAI, AutoGen, notebooks, local-first apps, and migration paths from static vector search. |
| Product feedback | Real workflows where memory needs to evolve, forget, explain, or preserve user-specific context over time. |

## Contact

Open a thread in [WaveMind issues](https://github.com/CaspianG/wavemind/issues) if you want to test the project, contribute an integration, add a benchmark, or discuss dynamic memory for production software.
