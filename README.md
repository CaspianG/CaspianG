<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/profile-hero.svg" alt="CaspianG builds adaptive memory systems" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>I build adaptive memory infrastructure for software that needs context to survive beyond one request.</strong>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-dynamic%20memory-050505?style=for-the-badge"></a>
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

<table>
  <tr>
    <td width="60%" valign="top">
      <h2>What I am working on</h2>
      <p>
        <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
        is a local-first memory layer for long-running software: assistants, internal copilots,
        research notebooks, developer tools, and products that need memory with behavior.
      </p>
      <p>
        The idea is simple: vector search finds candidates, but memory state decides what matters now.
        Useful facts heat up, stale facts decay, corrections win, namespaces isolate context, and
        benchmark gates keep claims honest.
      </p>
    </td>
    <td width="40%" valign="top">
      <h2>Try it</h2>
      <pre><code class="language-bash">pip install wavemind
wavemind quickstart
wavemind studio</code></pre>
      <p>
        Python API, CLI, FastAPI server, Studio UI, SQLite/Postgres paths,
        ANN backends, integrations, and benchmark reports live in the main repo.
      </p>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/memory-loop.svg" alt="WaveMind memory pipeline" width="100%" />
  </a>
</p>

## Focus

| Area | Direction |
| --- | --- |
| **Dynamic memory** | Hotness, decay, TTL, feedback, stale-fact suppression, graph links, and traceable recall. |
| **Local-first systems** | Installable tools that work without starting from a cloud account or opaque service. |
| **Production path** | Persistent truth stores, ANN indexes, rate limits, backups, observability, and scale benchmarks. |
| **Developer adoption** | Small APIs, useful examples, framework integrations, clear docs, and reproducible benchmark artifacts. |

## Main Repositories

| Project | What it is | Links |
| --- | --- | --- |
| **[WaveMind](https://github.com/CaspianG/wavemind)** | Adaptive memory infrastructure for software that needs to remember, forget, and evolve. | [Quick Start](https://github.com/CaspianG/wavemind#user-content-quick-start) / [Benchmarks](https://github.com/CaspianG/wavemind#user-content-benchmark) / [Issues](https://github.com/CaspianG/wavemind/issues) |
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
