<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/profile-hero.svg" alt="CaspianG builds adaptive memory infrastructure" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>Building memory infrastructure for software that needs context, history, and behavior.</strong>
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

My main work is **[WaveMind](https://github.com/CaspianG/wavemind)**: a local-first memory layer for long-running software.

It is built around one idea: storing vectors is not enough. Real memory needs state. Useful facts should become easier to recall, stale facts should fade, corrections should override old context, and every namespace should stay isolated and inspectable.

```bash
pip install wavemind
wavemind quickstart
wavemind studio
```

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/memory-loop.svg" alt="WaveMind combines storage, search, memory state, and feedback" width="100%" />
  </a>
</p>

## Current Focus

| Area | What I am pushing toward |
| --- | --- |
| **Adaptive memory** | Hotness, decay, TTL, feedback, correction handling, consolidation, and graph recall. |
| **Local-first tooling** | A library, CLI, API server, Studio UI, and reproducible examples that work without a cloud account. |
| **Production readiness** | SQLite/Postgres truth stores, ANN indexes, backups, rate limits, observability, and scale benchmarks. |
| **Developer adoption** | Clear docs, framework integrations, real benchmark artifacts, and small APIs that are easy to try. |

## Featured Work

| Project | Description | Links |
| --- | --- | --- |
| **[WaveMind](https://github.com/CaspianG/wavemind)** | Adaptive memory infrastructure for software that must remember, forget, and evolve over time. | [Quick Start](https://github.com/CaspianG/wavemind#user-content-quick-start) / [Benchmarks](https://github.com/CaspianG/wavemind#user-content-benchmark) / [Issues](https://github.com/CaspianG/wavemind/issues) |
| **[focus-flow](https://github.com/CaspianG/focus-flow)** | Minimal desktop focus timer for deep-work sessions, themes, and English/Russian UI. | [Repository](https://github.com/CaspianG/focus-flow) |
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
| **Integrations** | LangChain, LangGraph, LlamaIndex, CrewAI, AutoGen, notebooks, local apps, and real product workflows. |
| **Production feedback** | Systems where memory must evolve, forget, explain, or preserve user-specific context over time. |

## Contact

Open an issue in [WaveMind](https://github.com/CaspianG/wavemind/issues) if you want to test the project, contribute an integration, add a benchmark, or discuss adaptive memory for production software.
