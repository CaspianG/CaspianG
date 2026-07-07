<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.svg" alt="CaspianG - dynamic memory systems" width="100%" />
  </a>
</p>

<h1 align="center">Building memory systems for software that should adapt.</h1>

<p align="center">
  I work on local-first infrastructure for long-running agents and applications:
  memory that can recall, rank, decay, consolidate, and forget.
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">WaveMind</a>
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
    <td width="58%" valign="top">
      <h2>Main project</h2>
      <p>
        <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
        is a dynamic memory layer for agents and applications. It keeps durable storage as the source of truth, uses vector search for candidate retrieval, and adds memory behavior on top: hotness, decay, TTL, namespaces, feedback, consolidation, APIs, and benchmark gates.
      </p>
      <p>
        The goal is simple: move beyond static top-k retrieval and make memory behave more like a living system with lifecycle, priority, and history.
      </p>
    </td>
    <td width="42%" valign="top">
      <h2>Try it</h2>

<pre><code class="language-bash">pip install wavemind</code></pre>

<pre><code class="language-python">from wavemind import WaveMind

memory = WaveMind()
memory.remember("The user prefers short technical answers.")
print(memory.query("How should I answer?")[0].text)</code></pre>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/wavemind-map.svg" alt="WaveMind memory loop" width="100%" />
  </a>
</p>

## What I Am Building

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>Dynamic Memory</h3>
      <p>Memory that changes with use: reinforce useful facts, suppress stale ones, isolate namespaces, and keep provenance.</p>
    </td>
    <td width="33%" valign="top">
      <h3>Production Evidence</h3>
      <p>Benchmarks, CI gates, packaging checks, public limitations, and reproducible examples instead of vague claims.</p>
    </td>
    <td width="33%" valign="top">
      <h3>Developer UX</h3>
      <p>Python, FastAPI, SQLite, Redis, optional vector backends, Docker, and examples that fit real integration work.</p>
    </td>
  </tr>
</table>

## Featured Work

| Project | What it is | Status |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Dynamic long-term memory for agents and applications | Active |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions | Stable |
| [CORECITY](https://github.com/CaspianG/CORECITY) | Browser game concept built around a live market mechanic | Public archive |

## Current Direction

- Scale WaveMind from local memory sets to production-sized namespaces.
- Improve dynamic-memory benchmarks against static vector retrieval.
- Build first-class integrations for agent frameworks and real applications.
- Keep the project honest: evidence, limitations, tests, and reproducible demos.

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

I am especially interested in practical memory work:

- agent memory benchmarks and evaluation datasets;
- integrations with LangChain, LangGraph, LlamaIndex, CrewAI, AutoGen, and local agents;
- production retrieval systems with TTL, feedback, privacy, and audit trails;
- real examples where static vector search is not enough.

Open a discussion or issue in [WaveMind](https://github.com/CaspianG/wavemind/issues) if you want to test an integration, benchmark a memory workload, or contribute an adapter.
