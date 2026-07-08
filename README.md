<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.svg" alt="CaspianG - dynamic memory systems" width="100%" />
  </a>
</p>

<h1 align="center">I build dynamic memory systems for software that needs to keep context alive.</h1>

<p align="center">
  Local-first infrastructure, adaptive retrieval, durable state, graph recall,
  privacy-aware forgetting, and benchmarks that keep the claims honest.
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
  <a href="https://github.com/CaspianG/wavemind/issues">Issues</a>
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
    <td width="58%" valign="top">
      <h2>Current Focus</h2>
      <p>
        <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
        is an open-source memory layer for long-running applications: agents,
        copilots, research notebooks, support systems, internal tools, and
        products that accumulate context over time.
      </p>
      <p>
        The core idea is simple: memory should not be static text lookup.
        Useful memories should become easier to recall, stale memories should
        fade, corrected memories should stop misleading the system, and every
        important answer should remain traceable.
      </p>
      <p>
        I am pushing it toward production-scale dynamic memory: persistent state,
        external indexes, namespaces, TTL, decay, feedback, graph links,
        observability, benchmarks, and clean integration paths.
      </p>
    </td>
    <td width="42%" valign="top">
      <h2>Try WaveMind</h2>
      <pre><code class="language-bash">pip install wavemind</code></pre>
      <pre><code class="language-python">from wavemind import WaveMind

memory = WaveMind()
memory.remember("The user prefers concise answers.")

result = memory.query("How should I answer?")[0]
print(result.text)</code></pre>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/system.svg" alt="WaveMind memory system map" width="100%" />
  </a>
</p>

## What I Build

| Direction | What it means in practice |
| --- | --- |
| Dynamic memory | Hotness, decay, TTL, feedback, conflict handling, consolidation, and graph-aware recall. |
| Local-first systems | SQLite as source of truth, optional ANN/vector backends, CLI, API, Docker, and reproducible artifacts. |
| Production evidence | Benchmarks, latency profiles, packaging checks, CI gates, and honest scale limits. |
| Developer adoption | Small APIs, framework examples, migration guides, issue hygiene, and contributor-friendly work. |

## Projects

| Project | Focus | Status |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Dynamic long-term memory for agents, apps, notebooks, and internal tools. | Active |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions with English/Russian UI. | Stable |
| [CORECITY](https://github.com/CaspianG/CORECITY) | Browser game concept built around a living market mechanic. | Public archive |

## Working Principles

- Build useful systems first, then prove them under real workloads.
- Keep local paths fast, inspectable, and easy to run.
- Treat benchmarks and reproducibility as part of the product.
- Make forgetting, provenance, and namespaces first-class primitives.
- Avoid broad claims without runnable artifacts behind them.

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
