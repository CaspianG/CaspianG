<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.png" alt="CaspianG - adaptive memory for software that runs long" width="100%" />
  </a>
</p>

<h1 align="center">Adaptive memory infrastructure for long-running software.</h1>

<p align="center">
  I build local-first systems that preserve useful context, rank what matters,
  forget stale state, and keep memory behavior measurable.
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
  &nbsp;/&nbsp;
  <a href="https://pypi.org/project/wavemind/">PyPI</a>
  &nbsp;/&nbsp;
  <a href="https://github.com/CaspianG/wavemind#quick-start">Quick Start</a>
  &nbsp;/&nbsp;
  <a href="https://github.com/CaspianG/wavemind#benchmark">Benchmarks</a>
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
      <h2>Now building: WaveMind</h2>
      <p>
        <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
        is an open-source dynamic memory layer for agents, copilots, research notebooks,
        support systems, and products that accumulate context over time.
      </p>
      <p>
        It keeps durable state as the source of truth, uses vector search for candidate recall,
        then applies memory behavior on top: priority, decay, TTL, namespaces, feedback,
        graph links, provenance, and explicit forgetting.
      </p>
      <p>
        The goal is not another vector database. The goal is memory that behaves like
        a living system while staying inspectable, testable, and practical to ship.
      </p>
    </td>
    <td width="42%" valign="top">
      <h2>Use it in 30 seconds</h2>
      <pre><code class="language-bash">pip install wavemind</code></pre>
      <pre><code class="language-python">from wavemind import WaveMind

memory = WaveMind()
memory.remember("The user prefers concise technical answers.")

hit = memory.query("How should I answer?")[0]
print(hit.text)</code></pre>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/wavemind-map.png" alt="WaveMind memory loop: capture, score, recall, adapt" width="100%" />
  </a>
</p>

## What Makes It Different

| Static retrieval | Adaptive memory |
| --- | --- |
| Finds similar text. | Finds useful memory. |
| Old facts remain searchable until manually filtered. | TTL, decay, feedback, and corrections reduce stale recall. |
| Similarity is usually the main signal. | Similarity is only the candidate step; memory state changes ranking. |
| Great for document lookup. | Built for products that need preferences, history, corrections, and context over time. |
| Often treated as a black box. | Keeps provenance, benchmark artifacts, audit events, and lifecycle state close to the result. |

## Current Direction

| Area | Focus |
| --- | --- |
| Dynamic memory | Hotness, decay, feedback, conflict handling, consolidation, graph dynamics. |
| Scale | FAISS, Qdrant, pgvector, sharding, backups, operator readiness, production load profiles. |
| Evidence | LoCoMo, LongMemEval-style runs, local regression benchmarks, latency and recall gates. |
| Developer UX | Python API, FastAPI server, CLI, Studio, Docker, examples, framework integrations. |
| Trust | Clear limitations, reproducible commands, CI, releases, and public result artifacts. |

## Projects

| Project | What it is | Status |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Dynamic long-term memory for agents and applications | Active |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions | Stable |
| [CORECITY](https://github.com/CaspianG/CORECITY) | Browser game concept built around a live market mechanic | Public archive |

## Principles

- Local-first before hosted-first.
- Reproducible benchmarks before broad claims.
- Memory as evolving state, not only embedded text.
- Explicit forgetting as a core primitive.
- Simple integration paths before impressive architecture diagrams.

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

I am interested in practical memory systems, long-running agents, retrieval
benchmarks, privacy-aware forgetting, production indexes, and real workloads
where static vector search starts to break down.

Start with [WaveMind issues](https://github.com/CaspianG/wavemind/issues) if you
want to test an integration, benchmark a workload, or contribute an adapter.
