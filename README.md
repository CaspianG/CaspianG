<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/profile-hero.svg" alt="CaspianG builds adaptive memory infrastructure" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>Building local-first memory infrastructure for software that needs to remember, forget, and adapt.</strong>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-adaptive%20memory-050505?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=050505"></a>
  <a href="https://github.com/CaspianG/wavemind/actions/workflows/tests.yml"><img alt="Tests" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/tests.yml?branch=main&style=for-the-badge&label=tests&color=050505"></a>
  <a href="https://github.com/CaspianG/wavemind/stargazers"><img alt="Stars" src="https://img.shields.io/github/stars/CaspianG/wavemind?style=for-the-badge&label=stars&color=050505"></a>
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
      <h2>Flagship project</h2>
      <p>
        <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
        is an open-source memory layer for long-running software: agents, assistants,
        research tools, internal copilots, notebooks, and products that need context to
        survive beyond a single request.
      </p>
      <p>
        It keeps the durable store simple, then adds memory behavior on top:
        hotness, decay, TTL, feedback, namespaces, graph links, stale-fact suppression,
        and reproducible benchmark gates.
      </p>
    </td>
    <td width="42%" valign="top">
      <h2>Start in three commands</h2>
      <pre><code class="language-bash">pip install wavemind
wavemind quickstart
wavemind studio</code></pre>
      <p>
        Python API, CLI, FastAPI server, local Studio UI, persistent storage,
        integrations, and benchmark artifacts are built into the project path.
      </p>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/memory-loop.svg" alt="WaveMind retrieval and adaptive memory loop" width="100%" />
  </a>
</p>

## What I am building

| Direction | Why it matters |
| --- | --- |
| **Adaptive memory** | Static top-k retrieval is not enough. Useful memories should heat up, stale facts should fade, corrections should win. |
| **Local-first infrastructure** | Developers should be able to install, inspect, benchmark, and run memory without starting with a cloud account. |
| **Production path** | SQLite/Postgres truth stores, ANN indexes, namespaces, telemetry, backups, rate limits, and claim-gated benchmark reports. |
| **Developer adoption** | Good memory needs a small API, a useful CLI, a visible UI, framework integrations, and examples people can actually run. |

## Projects

| Project | Status | Start here |
| --- | --- | --- |
| **[WaveMind](https://github.com/CaspianG/wavemind)** | Active | [Quick Start](https://github.com/CaspianG/wavemind#user-content-quick-start) &middot; [Benchmarks](https://github.com/CaspianG/wavemind#user-content-benchmark) &middot; [Issues](https://github.com/CaspianG/wavemind/issues) |
| **[focus-flow](https://github.com/CaspianG/focus-flow)** | Public | Minimal desktop focus timer for deep-work sessions with planning, themes, and English/Russian UI. |
| **[CORECITY](https://github.com/CaspianG/CORECITY)** | Public concept | Browser game experiment around a living market mechanic driven by players. |

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

## Open to

| Collaboration | Useful contribution |
| --- | --- |
| **Benchmarks** | Long-memory evaluation, stale-fact suppression, retrieval quality, latency, agent-impact tests, and scale profiles. |
| **Integrations** | LangChain, LangGraph, LlamaIndex, CrewAI, AutoGen, local apps, notebooks, and real product workflows. |
| **Production feedback** | Systems where memory must evolve, forget, explain, or preserve user-specific context over time. |

## Contact

Open an issue in [WaveMind](https://github.com/CaspianG/wavemind/issues) if you want to test the project, contribute an integration, add a benchmark, or discuss adaptive memory for production software.
