<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.png" alt="CaspianG builds dynamic memory systems" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>Building memory infrastructure for software that needs durable context, adaptive recall, and clear evidence.</strong>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-dynamic%20memory-111111?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=111111"></a>
  <a href="https://github.com/CaspianG/wavemind/actions"><img alt="Checks" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/full-check.yml?branch=main&style=for-the-badge&label=checks&color=111111"></a>
  <a href="https://github.com/CaspianG/wavemind/releases"><img alt="Release" src="https://img.shields.io/github/v/release/CaspianG/wavemind?style=for-the-badge&label=release&color=111111"></a>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
  &nbsp;&middot;&nbsp;
  <a href="https://pypi.org/project/wavemind/">PyPI</a>
  &nbsp;&middot;&nbsp;
  <a href="https://www.github.com/CaspianG/wavemind#user-content-quick-start">Quick Start</a>
  &nbsp;&middot;&nbsp;
  <a href="https://www.github.com/CaspianG/wavemind#user-content-benchmark">Benchmarks</a>
  &nbsp;&middot;&nbsp;
  <a href="https://github.com/CaspianG/wavemind/issues">Issues</a>
</p>

---

<table>
  <tr>
    <td width="56%" valign="top">
      <h2>Current Work</h2>
      <p>
        I am building <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>:
        an open-source memory layer for long-running applications, agents, notebooks,
        internal copilots, research tools, and systems that need context to survive
        beyond a single prompt.
      </p>
      <p>
        The core idea is simple: memory should not be a static vector lookup.
        Important memories should become easier to recall, stale facts should fade,
        corrections should suppress older context, and every recall should be
        inspectable.
      </p>
      <p>
        Current focus: scale, benchmark evidence, production readiness, graph recall,
        observability, and practical integrations.
      </p>
    </td>
    <td width="44%" valign="top">
      <h2>Try It</h2>
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
    <img src="./assets/wavemind-map.png" alt="WaveMind memory architecture" width="100%" />
  </a>
</p>

## What I Build

| Area | Focus |
| --- | --- |
| Dynamic memory | Hotness, decay, TTL, feedback, conflict handling, consolidation, and graph-aware recall. |
| Local-first infrastructure | SQLite source of truth, optional ANN indexes, simple APIs, offline demos, reproducible artifacts. |
| Production evidence | Benchmarks, latency profiles, packaging checks, CI gates, and documented limits. |
| Developer adoption | Small APIs, framework adapters, migration guides, issue hygiene, and contributor-friendly tasks. |

## Featured

| Project | What it is | Status |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Dynamic long-term memory for agents, notebooks, internal tools, support systems, and products with durable context. | Active |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions with English/Russian UI. | Stable |
| [CORECITY](https://github.com/CaspianG/CORECITY) | Browser game concept around a living market mechanic. | Public archive |

## Working Principles

- Build the useful path first, then prove it under real workloads.
- Keep local development fast, inspectable, and easy to run.
- Treat benchmarks, tests, packaging, and reproducibility as part of the product.
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

## Open To

I am interested in practical memory systems, long-running software, retrieval
benchmarks, privacy-aware forgetting, production indexes, graph recall, and real
workloads where static vector search starts to break down.

Start with [WaveMind issues](https://github.com/CaspianG/wavemind/issues) if you
want to test an integration, benchmark a workload, or contribute an adapter.
