<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.png" alt="CaspianG builds memory systems for durable context" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>Open-source memory infrastructure for software that needs durable context, adaptive recall, and evidence-backed behavior.</strong>
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
  <a href="https://github.com/CaspianG/wavemind/issues">Contribute</a>
</p>

---

<table>
  <tr>
    <td width="58%" valign="top">
      <h2>What I am building</h2>
      <p>
        I build systems where memory is an active part of the product, not just a
        folder of embeddings. Useful context should become easier to recall,
        stale context should lose priority, and important behavior should remain
        inspectable.
      </p>
      <p>
        The flagship project is <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>,
        a local-first memory engine for assistants, research notebooks, internal
        copilots, support systems, developer tools, and long-running software.
      </p>
    </td>
    <td width="42%" valign="top">
      <h2>Current focus</h2>
      <ul>
        <li>Dynamic memory: hotness, decay, TTL, feedback, namespaces.</li>
        <li>Graph-aware recall and memory consolidation.</li>
        <li>SQLite source of truth with ANN and service backends.</li>
        <li>Benchmarks, CI gates, reproducible artifacts, honest limits.</li>
      </ul>
    </td>
  </tr>
</table>

## Start With WaveMind

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Why it exists</h3>
      <p>
        Vector search is a good candidate finder. It does not know which memories
        are fresh, repeatedly useful, corrected, private to a namespace, or safe
        to forget. WaveMind adds a memory layer on top of retrieval so context can
        evolve over time.
      </p>
      <p>
        <a href="https://github.com/CaspianG/wavemind"><strong>Open the repository</strong></a>
        &nbsp;/&nbsp;
        <a href="https://github.com/CaspianG/wavemind#user-content-quick-start">Run it locally</a>
        &nbsp;/&nbsp;
        <a href="https://github.com/CaspianG/wavemind#user-content-benchmark">Review evidence</a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>Ten-second example</h3>
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

## What Makes It Different

| Layer | Ordinary vector DB | WaveMind direction |
| --- | --- | --- |
| Recall | Nearest vectors | Candidate search plus adaptive memory priority |
| Time | Mostly static | Decay, TTL, hotness, stale fact suppression |
| Scope | Collections | Namespaces, tags, metadata, inspectable provenance |
| Operation | Store and query | Store, recall, update, forget, benchmark, audit |

## Useful For

| Use case | Why memory matters |
| --- | --- |
| Personal assistants | Preferences, corrections, recurring context, and private namespaces. |
| Research notebooks | Notes, evidence, source traces, and long-running investigations. |
| Internal copilots | Team context, operational history, support cases, and compliance-friendly forgetting. |
| Developer agents | Project decisions, codebase facts, issue history, and repeated recall signals. |
| Analyst tools | Structured notes, events, documents, and reproducible retrieval benchmarks. |

## Project Map

| Project | Focus | Status |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Dynamic long-term memory for software with durable context. | Active |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions with English/Russian UI. | Stable |
| [CORECITY](https://github.com/CaspianG/CORECITY) | Browser game concept built around a living market mechanic. | Public archive |

## Engineering Principles

- Make the useful path simple before adding platform complexity.
- Keep local development fast, inspectable, and easy to run.
- Treat forgetting, provenance, and namespace isolation as product behavior.
- Prove claims with runnable benchmarks and CI artifacts.
- Prefer clear APIs over abstractions that make systems harder to operate.

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
