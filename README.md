<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/profile-hero.jpg" alt="CaspianG builds adaptive memory infrastructure" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>Building adaptive memory infrastructure for software that needs durable context, clear recall, and explicit forgetting.</strong>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-adaptive%20memory-050505?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=050505"></a>
  <a href="https://github.com/CaspianG/wavemind/actions"><img alt="Checks" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/tests.yml?branch=main&style=for-the-badge&label=tests&color=050505"></a>
  <a href="https://github.com/CaspianG/wavemind/releases"><img alt="Release" src="https://img.shields.io/github/v/release/CaspianG/wavemind?style=for-the-badge&label=release&color=050505"></a>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
  &nbsp;&middot;&nbsp;
  <a href="https://pypi.org/project/wavemind/">PyPI</a>
  &nbsp;&middot;&nbsp;
  <a href="https://github.com/CaspianG/wavemind#quick-start">Quick Start</a>
  &nbsp;&middot;&nbsp;
  <a href="https://github.com/CaspianG/wavemind#benchmark">Benchmarks</a>
  &nbsp;&middot;&nbsp;
  <a href="https://github.com/CaspianG/wavemind/issues">Issues</a>
</p>

---

<table>
  <tr>
    <td width="58%" valign="top">
      <h2>Now Building</h2>
      <p>
        <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
        is an open-source memory engine for long-running software: agents, internal copilots,
        notebooks, support systems, research tools, and products that need context to survive
        beyond a single request.
      </p>
      <p>
        The core idea: memory should not be a static vector lookup. Useful context should
        get easier to recall, stale facts should fade, corrections should suppress older
        state, and every recall should remain inspectable.
      </p>
    </td>
    <td width="42%" valign="top">
      <h2>Try WaveMind</h2>
      <pre><code class="language-bash">pip install wavemind
wavemind quickstart
wavemind studio</code></pre>
      <p>
        Python API, CLI, HTTP server, local Studio UI, persistent storage, vector backends,
        workers, telemetry, and reproducible benchmark reports.
      </p>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/memory-loop.jpg" alt="WaveMind adaptive recall map" width="100%" />
  </a>
</p>

## What I Build

| Area | Direction |
| --- | --- |
| **Adaptive memory** | Hotness, decay, TTL, feedback, graph recall, conflict handling, and explainable forgetting. |
| **Retrieval infrastructure** | Local-first search, persistent stores, ANN backends, benchmark gates, and latency profiles. |
| **Developer tools** | Python APIs, FastAPI, CLI, local UI, framework adapters, examples, and migration paths. |
| **Production evidence** | Tests, CI, release artifacts, reproducible benchmark reports, observability, and clear limitations. |

## Featured Work

| Project | What it is | Links |
| --- | --- | --- |
| **WaveMind** | Adaptive long-term memory engine for agents and applications. | [Repo](https://github.com/CaspianG/wavemind) / [PyPI](https://pypi.org/project/wavemind/) |
| **focus-flow** | Minimal desktop focus timer for deep-work sessions with planning, themes, and EN/RU UI. | [Repo](https://github.com/CaspianG/focus-flow) |
| **CORECITY** | Browser game concept built around a living market mechanic. | [Repo](https://github.com/CaspianG/CORECITY) |

## Why This Direction

Most software can store context. The harder problem is deciding what context still matters.

WaveMind is built around that gap: retrieval gives candidates, memory state changes ranking, and the system keeps evidence close enough that behavior can be tested instead of guessed.

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
| **Benchmarks** | Long-memory evaluation, stale-fact suppression, retrieval quality, latency, and agent-impact tests. |
| **Integrations** | LangChain, LangGraph, LlamaIndex, CrewAI, AutoGen, local apps, notebooks, and product workflows. |
| **Production feedback** | Real systems where memory needs to evolve, forget, explain, or preserve user-specific context over time. |

## Contact

Open a thread in [WaveMind issues](https://github.com/CaspianG/wavemind/issues) if you want to test the project, contribute an integration, add a benchmark, or discuss adaptive memory for production software.
