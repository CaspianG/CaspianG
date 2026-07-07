<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.svg" alt="CaspianG - adaptive memory systems" width="100%" />
  </a>
</p>

<h1 align="center">Adaptive memory infrastructure for software that learns from time.</h1>

<p align="center">
  I build local-first systems that remember useful context, adapt priorities, keep provenance,
  and forget stale state without turning into another opaque vector database.
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
  &nbsp;/&nbsp;
  <a href="https://pypi.org/project/wavemind/">PyPI</a>
  &nbsp;/&nbsp;
  <a href="https://github.com/CaspianG/wavemind#quick-start">Quick Start</a>
  &nbsp;/&nbsp;
  <a href="https://github.com/CaspianG/wavemind#benchmarks">Benchmarks</a>
  &nbsp;/&nbsp;
  <a href="https://github.com/CaspianG/wavemind/issues">Contribute</a>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-dynamic%20memory-111111?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=111111"></a>
  <a href="https://github.com/CaspianG/wavemind/actions"><img alt="Checks" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/full-check.yml?branch=main&style=for-the-badge&label=checks&color=111111"></a>
  <a href="https://github.com/CaspianG/wavemind/releases"><img alt="Release" src="https://img.shields.io/github/v/release/CaspianG/wavemind?style=for-the-badge&label=release&color=111111"></a>
</p>

---

<table>
  <tr>
    <td width="54%" valign="top">
      <h2>Current focus</h2>
      <p>
        <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
        is a dynamic long-term memory layer for agents, copilots, research tools,
        and applications that need memory behavior, not just vector lookup.
      </p>
      <p>
        It keeps durable storage as the source of truth, retrieves candidates through
        fast indexes, then applies memory dynamics on top: hotness, decay, TTL,
        namespaces, feedback, consolidation, and benchmark gates.
      </p>
      <ul>
        <li><strong>Local-first:</strong> SQLite by default, production backends when scale requires it.</li>
        <li><strong>Evidence-first:</strong> tests, benchmarks, CI gates, and public limitations.</li>
        <li><strong>Integration-first:</strong> Python, HTTP API, LangChain, LlamaIndex, CrewAI, AutoGen.</li>
      </ul>
    </td>
    <td width="46%" valign="top">
      <h2>Try WaveMind</h2>
      <pre><code class="language-bash">pip install wavemind</code></pre>
      <pre><code class="language-python">from wavemind import WaveMind

memory = WaveMind()
memory.remember("The user prefers short technical answers.")

result = memory.query("How should I answer?")[0]
print(result.text)</code></pre>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/wavemind-map.svg" alt="WaveMind memory loop" width="100%" />
  </a>
</p>

## What I Build

<table>
  <tr>
    <td width="25%" valign="top">
      <h3>Dynamic Memory</h3>
      <p>Memory that can become hotter, fade out, separate namespaces, keep TTL, and explain why it was recalled.</p>
    </td>
    <td width="25%" valign="top">
      <h3>Retrieval Evidence</h3>
      <p>Benchmarks against static vector search, Chroma, Qdrant, agent-memory tasks, and scale profiles.</p>
    </td>
    <td width="25%" valign="top">
      <h3>Production Path</h3>
      <p>Persistence, backups, API contracts, observability, package checks, Docker, and reproducible load tests.</p>
    </td>
    <td width="25%" valign="top">
      <h3>Developer UX</h3>
      <p>Small install surface, clear examples, adapters for real frameworks, and defaults that work locally first.</p>
    </td>
  </tr>
</table>

## Featured Work

| Project | What it is | Status |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Dynamic long-term memory for agents and applications | Active |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions | Stable |
| [CORECITY](https://github.com/CaspianG/CORECITY) | Browser game concept built around a live market mechanic | Public archive |

## Direction

- Build WaveMind as the open-source memory layer for long-running software.
- Move from static retrieval to adaptive memory: priority, decay, correction, consolidation, and provenance.
- Prove claims with benchmarks before turning them into marketing.
- Keep the core simple enough to run locally, while building a path to production-sized workloads.

## Stack

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-111111?style=flat-square&logo=python&logoColor=white">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-111111?style=flat-square&logo=fastapi&logoColor=white">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-111111?style=flat-square&logo=sqlite&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-111111?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-111111?style=flat-square&logo=redis&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-111111?style=flat-square&logo=docker&logoColor=white">
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-111111?style=flat-square&logo=kubernetes&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-111111?style=flat-square&logo=typescript&logoColor=white">
</p>

## Collaboration

I am interested in practical memory systems: long-term agent memory, retrieval benchmarks,
privacy-aware forgetting, production indexes, framework integrations, and real workloads where
static vector search is not enough.

Start with [WaveMind issues](https://github.com/CaspianG/wavemind/issues) if you want to test an integration,
benchmark a workload, or contribute an adapter.
