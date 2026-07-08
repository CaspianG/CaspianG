<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.png" alt="CaspianG builds memory systems for durable context" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>Building local-first memory infrastructure for software that needs durable context, adaptive recall, and inspectable behavior.</strong>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-dynamic%20memory-111111?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=111111"></a>
  <a href="https://github.com/CaspianG/wavemind/actions/workflows/full-check.yml"><img alt="Checks" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/full-check.yml?branch=main&style=for-the-badge&label=checks&color=111111"></a>
  <a href="https://github.com/CaspianG/wavemind/releases"><img alt="Release" src="https://img.shields.io/github/v/release/CaspianG/wavemind?style=for-the-badge&label=release&color=111111"></a>
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
  <a href="https://github.com/CaspianG/wavemind/issues">Issues</a>
</p>

---

<table>
  <tr>
    <td width="50%" valign="top">
      <h2>What I build</h2>
      <p>
        I work on systems where memory is not just storage. Useful context should
        become easier to recall, stale context should lose priority, and every
        important decision should stay inspectable.
      </p>
      <p>
        The current flagship is <a href="https://github.com/CaspianG/wavemind">WaveMind</a>:
        an open-source memory engine for assistants, notebooks, internal copilots,
        research tools, support systems, and products that need context to survive
        beyond one session.
      </p>
    </td>
    <td width="50%" valign="top">
      <h2>Current focus</h2>
      <ul>
        <li>Dynamic long-term memory for software with durable context.</li>
        <li>Hotness, decay, TTL, feedback, namespaces, and graph-aware recall.</li>
        <li>SQLite source of truth with optional ANN and service backends.</li>
        <li>Benchmarks, CI gates, reproducible artifacts, and honest limits.</li>
      </ul>
    </td>
  </tr>
</table>

## Start Here

<table>
  <tr>
    <td width="54%" valign="top">
      <h3><a href="https://github.com/CaspianG/wavemind">WaveMind</a></h3>
      <p>
        WaveMind is a local-first memory layer for long-running software. It stores
        facts, retrieves candidates, applies dynamic priority, explains recalls,
        and learns from usage.
      </p>
      <p>
        It is designed for projects where ordinary vector search is useful, but not
        enough: user preferences, corrections, stale facts, private namespaces,
        research notes, agent memory, and operational context.
      </p>
      <p>
        <a href="https://github.com/CaspianG/wavemind"><strong>Open the repository</strong></a>
        &nbsp;/&nbsp;
        <a href="https://github.com/CaspianG/wavemind#user-content-quick-start">Run the quick start</a>
        &nbsp;/&nbsp;
        <a href="https://github.com/CaspianG/wavemind#user-content-benchmark">Read the benchmarks</a>
      </p>
    </td>
    <td width="46%" valign="top">
      <h3>Try it</h3>
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

## Workstreams

| Area | What it means |
| --- | --- |
| Memory systems | Adaptive recall, decay, feedback, conflict handling, consolidation, and graph memory. |
| Production path | Local development first, then service mode, backups, auth, observability, and scalable indexes. |
| Evidence | LoCoMo, LongMemEval, BEIR-style retrieval, scale plans, artifact audits, and CI-backed regression checks. |
| Developer experience | Small APIs, CLI, FastAPI, LangChain, LlamaIndex, migration guides, and examples that run without guesswork. |

## Repositories

| Project | Focus | Status |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Dynamic long-term memory for software with durable context. | Active |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions with English/Russian UI. | Stable |
| [CORECITY](https://github.com/CaspianG/CORECITY) | Browser game concept built around a living market mechanic. | Public archive |

## Principles

- Build the useful path first, then prove it under real workloads.
- Keep local development fast, inspectable, and easy to run.
- Treat forgetting, provenance, and namespace isolation as core product behavior.
- Prefer simple APIs over abstractions that make systems harder to operate.
- Do not publish claims without runnable artifacts behind them.

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

I am interested in practical memory systems, retrieval benchmarks, privacy-aware
forgetting, production indexes, graph recall, and real workloads where static
vector search starts to break down.

Start with [WaveMind issues](https://github.com/CaspianG/wavemind/issues) if you
want to test an integration, benchmark a workload, or contribute an adapter.
