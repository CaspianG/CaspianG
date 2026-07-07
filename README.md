<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.svg" alt="CaspianG - memory infrastructure for adaptive software" width="100%" />
  </a>
</p>

<h1 align="center">Memory infrastructure for software that should learn from time.</h1>

<p align="center">
  I build local-first systems for long-running applications: memory that recalls useful context,
  adapts priority, keeps provenance, and forgets stale state cleanly.
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
<td width="56%" valign="top">
<h2>Current focus: WaveMind</h2>
<p>
  <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
  is a dynamic memory layer for agents, copilots, research tools, and applications that need
  more than static vector search.
</p>
<p>
  It keeps durable storage as the source of truth, retrieves vector candidates, then applies
  memory behavior on top: hotness, decay, TTL, namespaces, feedback, consolidation, and
  benchmark gates.
</p>
<ul>
  <li><strong>Local-first:</strong> SQLite by default, optional production backends.</li>
  <li><strong>Evidence-first:</strong> tests, public benchmarks, CI gates, clear limitations.</li>
  <li><strong>Integration-first:</strong> Python, HTTP API, LangChain, LlamaIndex, CrewAI, AutoGen.</li>
</ul>
</td>
<td width="44%" valign="top">
<h2>Try it in 30 seconds</h2>
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
    <img src="./assets/wavemind-map.svg" alt="WaveMind memory architecture" width="100%" />
  </a>
</p>

## What I Build

<table>
  <tr>
<td width="25%" valign="top">
<h3>Dynamic Memory</h3>
<p>Systems that reinforce useful facts, suppress stale ones, isolate namespaces, and keep recall explainable.</p>
</td>
<td width="25%" valign="top">
<h3>Benchmarked Retrieval</h3>
<p>Evidence-driven comparisons against static vector retrieval, Chroma, Qdrant, and memory workloads.</p>
</td>
<td width="25%" valign="top">
<h3>Production Path</h3>
<p>APIs, persistence, backups, observability, packaging checks, load profiles, and reproducible demos.</p>
</td>
<td width="25%" valign="top">
<h3>Developer UX</h3>
<p>Small install surface, readable examples, framework adapters, and defaults that work locally first.</p>
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
- Improve dynamic-memory benchmarks against static vector retrieval and agent-memory baselines.
- Build practical integrations for LangChain, LangGraph, LlamaIndex, CrewAI, AutoGen, and local agents.
- Keep claims tied to evidence: tests, benchmark reports, packaging checks, and public limitations.

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

I am interested in practical memory systems: agent-memory benchmarks, production retrieval workloads,
framework integrations, privacy-aware forgetting, and real examples where static vector search is not enough.

Start with [WaveMind issues](https://github.com/CaspianG/wavemind/issues) if you want to test an integration,
benchmark a workload, or contribute an adapter.
