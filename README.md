<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.png" alt="CaspianG builds adaptive memory systems" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>I build memory infrastructure for software that has to keep context, adapt over time, and stay inspectable.</strong>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-dynamic%20memory-111111?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=111111"></a>
  <a href="https://github.com/CaspianG/wavemind/actions/workflows/full-check.yml"><img alt="Checks" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/full-check.yml?branch=main&style=for-the-badge&label=checks&color=111111"></a>
  <a href="https://github.com/CaspianG/wavemind/releases"><img alt="Release" src="https://img.shields.io/github/v/release/CaspianG/wavemind?style=for-the-badge&label=release&color=111111"></a>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
  &nbsp;|&nbsp;
  <a href="https://pypi.org/project/wavemind/">PyPI</a>
  &nbsp;|&nbsp;
  <a href="https://github.com/CaspianG/wavemind#user-content-quick-start">Quick Start</a>
  &nbsp;|&nbsp;
  <a href="https://github.com/CaspianG/wavemind#user-content-benchmark">Benchmarks</a>
  &nbsp;|&nbsp;
  <a href="https://github.com/CaspianG/wavemind/issues">Issues</a>
</p>

---

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>Adaptive Memory</h3>
      <p>
        Memory should not be a static top-k lookup. Useful context should get easier
        to recall. Stale context should fade. Corrections should suppress old facts.
      </p>
    </td>
    <td width="33%" valign="top">
      <h3>Local First</h3>
      <p>
        I prefer tools that can run on one machine, expose clear data files, and scale
        only when the workload proves it needs scale.
      </p>
    </td>
    <td width="33%" valign="top">
      <h3>Evidence Driven</h3>
      <p>
        Benchmarks, packaging checks, CI gates, reproducible artifacts, and honest
        limits are part of the product, not an afterthought.
      </p>
    </td>
  </tr>
</table>

## Flagship Project

<table>
  <tr>
    <td width="56%" valign="top">
      <h3><a href="https://github.com/CaspianG/wavemind">WaveMind</a></h3>
      <p>
        WaveMind is an open-source memory engine for long-running software:
        assistants, notebooks, internal copilots, support systems, research tools,
        and products that need context to survive beyond one session.
      </p>
      <p>
        The core loop is simple: store facts, search candidates, apply dynamic
        priority, return explainable recalls, then learn from usage.
      </p>
      <p>
        Current work: production-scale planning, ANN backends, graph recall,
        observability, benchmark evidence, and framework integrations.
      </p>
    </td>
    <td width="44%" valign="top">
      <h3>Try it in 30 seconds</h3>
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
    <img src="./assets/wavemind-map.png" alt="WaveMind memory loop" width="100%" />
  </a>
</p>

## What I Am Building

| Direction | Why it matters |
| --- | --- |
| Dynamic recall | Hotness, decay, TTL, feedback, conflict handling, consolidation, and graph-aware recall. |
| Production memory | SQLite source of truth, optional ANN indexes, service mode, backups, auth, and observable APIs. |
| Benchmark evidence | LoCoMo, LongMemEval, BEIR-style retrieval, scale plans, artifact audits, and CI-backed regression checks. |
| Developer adoption | Small APIs, CLI, FastAPI, LangChain, LlamaIndex, migration guides, and examples that run without guesswork. |

## Projects

| Project | Focus | Status |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Dynamic long-term memory for software with durable context. | Active |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions with English/Russian UI. | Stable |
| [CORECITY](https://github.com/CaspianG/CORECITY) | Browser game concept built around a living market mechanic. | Public archive |

## Working Principles

- Build the useful path first, then prove it under real workloads.
- Keep local development fast, inspectable, and easy to run.
- Treat forgetting, provenance, and namespace isolation as first-class primitives.
- Prefer simple APIs over clever abstractions that make systems harder to operate.
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
