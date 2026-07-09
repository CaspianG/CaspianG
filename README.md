<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/profile-hero.svg" alt="CaspianG builds adaptive memory systems" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>Building memory infrastructure for software that needs durable context, controlled forgetting, and explainable recall.</strong>
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

## What I Am Building

<table>
  <tr>
    <td width="52%" valign="top">
      <h3>WaveMind</h3>
      <p>
        <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a> is a local-first memory engine for long-running software.
        It stores facts durably, retrieves candidates through vector search, then applies memory behavior:
        TTL, priority, feedback, recall history, graph links, conflict handling, and auditable forgetting.
      </p>
      <pre><code>pip install wavemind
wavemind quickstart
wavemind studio</code></pre>
    </td>
    <td width="48%" valign="top">
      <h3>Why it exists</h3>
      <p>
        Ordinary vector search can find similar text. Real memory also needs to decide what still matters,
        what became stale, what was corrected, what is trusted, and why something was recalled.
      </p>
      <p>
        WaveMind is built around that missing layer: memory state on top of durable storage and retrieval.
      </p>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/memory-loop.svg" alt="WaveMind memory loop: store, search, evolve, explain" width="100%" />
  </a>
</p>

## Current Focus

<table>
  <tr>
    <td width="25%" valign="top">
      <h3>Scale</h3>
      <p>FAISS, Qdrant, pgvector, sharding profiles, p95/p99 latency reports, and reproducible benchmark evidence.</p>
    </td>
    <td width="25%" valign="top">
      <h3>Dynamics</h3>
      <p>Graph propagation, consolidation, stale-fact suppression, conflict handling, and self-organizing memory nodes.</p>
    </td>
    <td width="25%" valign="top">
      <h3>Product</h3>
      <p>WaveMind Studio, visual memory maps, namespace explorer, feedback, backups, and operational dashboards.</p>
    </td>
    <td width="25%" valign="top">
      <h3>Ecosystem</h3>
      <p>LangChain, LangGraph, LlamaIndex, CrewAI, AutoGen, notebooks, internal copilots, and migration guides.</p>
    </td>
  </tr>
</table>

## Selected Work

| Project | What it is | Status |
| --- | --- | --- |
| [**WaveMind**](https://github.com/CaspianG/wavemind) | Dynamic memory engine with persistence, vector search, TTL, namespaces, graph recall, workers, Studio, CLI, HTTP API, Docker, benchmarks, and framework integrations. | Active |
| [**focus-flow**](https://github.com/CaspianG/focus-flow) | Desktop focus timer for deep-work sessions with planning, session tracking, themes, and English/Russian UI. | Public |
| [**CORECITY**](https://github.com/CaspianG/CORECITY) | Browser game concept around a living market mechanic driven by players. | Public |

## Stack

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-050505?style=flat-square&logo=python&logoColor=white">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-050505?style=flat-square&logo=fastapi&logoColor=white">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-050505?style=flat-square&logo=sqlite&logoColor=white">
  <img alt="FAISS" src="https://img.shields.io/badge/FAISS-050505?style=flat-square">
  <img alt="Qdrant" src="https://img.shields.io/badge/Qdrant-050505?style=flat-square">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-050505?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-050505?style=flat-square&logo=redis&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-050505?style=flat-square&logo=docker&logoColor=white">
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-050505?style=flat-square&logo=kubernetes&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-050505?style=flat-square&logo=typescript&logoColor=white">
</p>

## Open For

| Collaboration | Good fit |
| --- | --- |
| Benchmarks | Long-memory evaluation, agent memory tasks, stale-fact suppression, retrieval quality, and production latency. |
| Integrations | Agent frameworks, notebooks, internal tools, local-first apps, and migration paths from static vector search. |
| Product feedback | Real workflows where memory needs to evolve, forget, explain, or preserve user-specific context. |

## Contact

Open a thread in [WaveMind issues](https://github.com/CaspianG/wavemind/issues) if you want to test the project, contribute an integration, add a benchmark, or discuss dynamic memory for production software.
