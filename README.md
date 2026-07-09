<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/profile-hero.svg" alt="CaspianG builds adaptive memory infrastructure" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>I build adaptive memory infrastructure for software that needs durable context, reliable recall, and explicit forgetting.</strong>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-dynamic%20memory-050505?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=050505"></a>
  <a href="https://github.com/CaspianG/wavemind/actions/workflows/tests.yml"><img alt="Tests" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/tests.yml?branch=main&style=for-the-badge&label=tests&color=050505"></a>
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
  <a href="https://github.com/CaspianG/wavemind/issues">Contribute</a>
</p>

---

<table>
  <tr>
    <td width="58%" valign="top">
      <h2>Current Work</h2>
      <p>
        My main project is <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>,
        an open-source memory layer for products that need context to survive beyond one prompt,
        one request, or one session.
      </p>
      <p>
        It keeps a persistent source of truth, retrieves candidates with vector search, and then
        uses memory state to decide what still matters: hotness, decay, TTL, feedback, namespaces,
        graph links, and stale-fact suppression.
      </p>
    </td>
    <td width="42%" valign="top">
      <h2>Run It</h2>
      <pre><code class="language-bash">pip install wavemind
wavemind quickstart
wavemind studio</code></pre>
      <p>
        Python library, CLI, HTTP API, local Studio UI, persistent storage,
        framework examples, benchmark gates, and production-readiness artifacts.
      </p>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/memory-loop.svg" alt="WaveMind turns retrieval into memory behavior" width="100%" />
  </a>
</p>

## What I Build

| Track | Focus |
| --- | --- |
| **Dynamic memory** | Memory that changes priority over time instead of returning static top-k results forever. |
| **Local-first systems** | Tools that work on a developer machine first, then grow into service, cloud, and enterprise deployment paths. |
| **Retrieval infrastructure** | SQLite/Postgres truth stores, vector indexes, graph recall, caching, telemetry, and benchmarkable latency. |
| **Developer experience** | Installable packages, CLI flows, examples, integrations, dashboards, and docs that make adoption obvious. |

## Featured Repositories

| Project | Status | Why it matters |
| --- | --- | --- |
| **[WaveMind](https://github.com/CaspianG/wavemind)** | Active | Dynamic long-term memory for agents, copilots, notebooks, support tools, and products that need durable context. |
| **[focus-flow](https://github.com/CaspianG/focus-flow)** | Public | Minimal desktop focus timer for deep-work sessions with planning, themes, and English/Russian UI. |
| **[CORECITY](https://github.com/CaspianG/CORECITY)** | Public concept | Browser game experiment around a living market mechanic driven by players. |

## The Thesis

Most systems can store context. The harder problem is deciding what context deserves attention later.

WaveMind is built around that gap: search finds candidates, memory state changes the ranking, and reproducible benchmarks keep the behavior measurable.

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

## Open To

| Collaboration | Good fit |
| --- | --- |
| **Benchmarks** | Long-memory evaluation, stale-fact suppression, retrieval quality, latency, agent-impact tests, and scale profiles. |
| **Integrations** | LangChain, LangGraph, LlamaIndex, CrewAI, AutoGen, local apps, notebooks, and product workflows. |
| **Production feedback** | Real systems where memory needs to evolve, forget, explain, or preserve user-specific context over time. |

## Contact

Open an issue in [WaveMind](https://github.com/CaspianG/wavemind/issues) if you want to test the project, contribute an integration, add a benchmark, or discuss adaptive memory for production software.
