<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.svg" alt="CaspianG builds dynamic memory infrastructure" width="100%" />
  </a>
</p>

<h1 align="center">I build memory infrastructure for long-running software.</h1>

<p align="center">
  Systems that keep context alive: local-first storage, adaptive recall,
  graph memory, forgetting, provenance, benchmarks, and production packaging.
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
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-dynamic_memory-111111?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=111111"></a>
  <a href="https://github.com/CaspianG/wavemind/actions"><img alt="Checks" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/full-check.yml?branch=main&style=for-the-badge&label=checks&color=111111"></a>
  <a href="https://github.com/CaspianG/wavemind/releases"><img alt="Release" src="https://img.shields.io/github/v/release/CaspianG/wavemind?style=for-the-badge&label=release&color=111111"></a>
</p>

---

<table>
  <tr>
    <td width="52%" valign="top">
      <h2>Now building</h2>
      <p>
        <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
        is an open-source dynamic memory layer for applications that accumulate
        context over time.
      </p>
      <p>
        It treats memory as state, not just search results: useful information
        gets stronger, stale facts fade, corrections suppress old context, and
        every recall path stays inspectable.
      </p>
      <p>
        The current focus is production scale: persisted indexes, namespaces,
        graph recall, Memory OS planning, Kubernetes packaging, observability,
        and public benchmark evidence.
      </p>
    </td>
    <td width="48%" valign="top">
      <h2>Use it in 30 seconds</h2>
      <pre><code class="language-bash">pip install wavemind</code></pre>
      <pre><code class="language-python">from wavemind import WaveMind

memory = WaveMind()
memory.remember("The user prefers concise answers.")

hit = memory.query("How should I respond?")[0]
print(hit.text)</code></pre>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/system.svg" alt="WaveMind system map" width="100%" />
  </a>
</p>

## What I Care About

| Area | What that means |
| --- | --- |
| Dynamic memory | Hotness, decay, TTL, feedback, conflict handling, consolidation, graph-aware recall. |
| Local-first systems | SQLite as source of truth, optional vector indexes, simple APIs, offline demos, reproducible artifacts. |
| Production evidence | Benchmarks, latency profiles, packaging checks, CI gates, and clearly documented limits. |
| Developer adoption | Small APIs, framework adapters, migration guides, issue hygiene, and contributor-friendly tasks. |

## Featured Work

| Project | Why it matters | Status |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Dynamic long-term memory for agents, notebooks, internal tools, support systems, and products with durable context. | Active |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions with English/Russian UI. | Stable |
| [CORECITY](https://github.com/CaspianG/CORECITY) | Browser game concept around a living market mechanic. | Public archive |

## Working Principles

- Build the useful path first, then prove it under real workloads.
- Keep local development fast, inspectable, and easy to run.
- Treat benchmarks, tests, and reproducibility as part of the product.
- Make forgetting, provenance, and namespace isolation first-class primitives.
- Avoid claims that do not have runnable artifacts behind them.

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

## Open For

I am interested in practical memory systems, long-running software, retrieval
benchmarks, privacy-aware forgetting, production indexes, graph recall, and real
workloads where static vector search starts to break down.

Start with [WaveMind issues](https://github.com/CaspianG/wavemind/issues) if you
want to test an integration, benchmark a workload, or contribute an adapter.
