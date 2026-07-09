<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/profile-hero.svg" alt="CaspianG builds adaptive memory infrastructure" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>Building adaptive memory infrastructure for software that needs context, history, and reliable recall.</strong>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-adaptive%20memory-050505?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=050505"></a>
  <a href="https://github.com/CaspianG/wavemind/actions/workflows/tests.yml"><img alt="Tests" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/tests.yml?branch=main&style=for-the-badge&label=tests&color=050505"></a>
  <a href="https://github.com/CaspianG/wavemind/stargazers"><img alt="Stars" src="https://img.shields.io/github/stars/CaspianG/wavemind?style=for-the-badge&label=stars&color=050505"></a>
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

## What I Build

I work on systems that turn raw data into usable memory: persistent storage, retrieval, priority, decay, feedback, corrections, and benchmarks that show whether the system actually helps.

The current flagship is **[WaveMind](https://github.com/CaspianG/wavemind)**, a local-first memory layer for long-running software. It is built around a simple idea: vector search finds candidates, but memory state decides what should be recalled now.

<table>
  <tr>
    <td width="48%">
      <h3>WaveMind</h3>
      <p><strong>Adaptive memory for software that remembers, forgets, and evolves.</strong></p>
      <p>
        Durable storage, vector search, dynamic priority, TTL, namespaces, feedback, graph recall, FastAPI, CLI, Studio, benchmarks, Docker, Helm, and production-readiness work.
      </p>
      <p>
        <a href="https://github.com/CaspianG/wavemind">Repository</a>
        ·
        <a href="https://pypi.org/project/wavemind/">PyPI</a>
        ·
        <a href="https://github.com/CaspianG/wavemind#user-content-quick-start">Quick Start</a>
      </p>
    </td>
    <td width="52%">
      <a href="https://github.com/CaspianG/wavemind">
        <img src="./assets/memory-loop.svg" alt="WaveMind memory loop: store, search, state, recall, feedback" width="100%" />
      </a>
    </td>
  </tr>
</table>

```bash
pip install wavemind
wavemind quickstart
wavemind studio
```

## Current Focus

| Track | What is shipping |
| --- | --- |
| **Memory quality** | Hotness, decay, corrections, TTL, feedback signals, stale-fact suppression, and graph recall. |
| **Developer experience** | Python API, CLI, FastAPI server, Studio UI, imports, backups, and framework examples. |
| **Scale path** | SQLite/Postgres truth stores, ANN candidate indexes, sharding plans, cache layers, and reproducible scale evidence. |
| **Evidence** | Long-memory benchmarks, retrieval baselines, latency profiles, regression tests, and public result artifacts. |

## Projects

| Project | Snapshot | Links |
| --- | --- | --- |
| **[WaveMind](https://github.com/CaspianG/wavemind)** | Adaptive memory infrastructure for software that must preserve, prioritize, and update context over time. | [Docs](https://github.com/CaspianG/wavemind#readme) / [Benchmarks](https://github.com/CaspianG/wavemind#user-content-benchmark) / [Issues](https://github.com/CaspianG/wavemind/issues) |
| **[focus-flow](https://github.com/CaspianG/focus-flow)** | Minimal desktop focus timer for deep-work sessions with themes and English/Russian UI. | [Repository](https://github.com/CaspianG/focus-flow) |
| **[CORECITY](https://github.com/CaspianG/CORECITY)** | Browser game experiment around a living market mechanic driven by players. | [Repository](https://github.com/CaspianG/CORECITY) |

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

| Collaboration | Useful contribution |
| --- | --- |
| **Benchmarks** | Long-memory evaluation, stale-fact suppression, retrieval quality, latency, agent-impact tests, and scale profiles. |
| **Integrations** | LangChain, LangGraph, LlamaIndex, CrewAI, AutoGen, notebooks, local apps, and production workflows. |
| **Production feedback** | Real systems where memory must evolve, forget, explain, or preserve user-specific context over time. |

## Contact

Open an issue in [WaveMind](https://github.com/CaspianG/wavemind/issues) if you want to test the project, contribute an integration, add a benchmark, or discuss adaptive memory for production software.
