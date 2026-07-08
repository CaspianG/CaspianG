<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="https://raw.githubusercontent.com/CaspianG/CaspianG/main/assets/profile-hero.svg" alt="CaspianG builds adaptive memory systems" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>I build adaptive memory infrastructure for software that needs context to survive beyond a single prompt, run, or session.</strong><br />
  Current focus:
  <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>,
  an open-source memory engine with persistence, namespaces, decay, graph recall, APIs, benchmarks, and production-scale work.
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-adaptive%20memory-050505?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=050505"></a>
  <a href="https://github.com/CaspianG/wavemind/actions/workflows/full-check.yml"><img alt="Checks" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/full-check.yml?branch=main&style=for-the-badge&label=checks&color=050505"></a>
  <a href="https://github.com/CaspianG/wavemind/releases"><img alt="Release" src="https://img.shields.io/github/v/release/CaspianG/wavemind?style=for-the-badge&label=release&color=050505"></a>
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
    <td width="56%" valign="top">
      <h2>Now building</h2>
      <p>
        <strong>WaveMind</strong> is a memory layer for agents, tools, research notebooks,
        internal copilots, and long-running systems that need more than static vector search.
      </p>
      <p>
        It keeps the source of truth inspectable, tracks freshness and priority,
        supports namespaces and TTL, and uses dynamic memory state to decide what
        should still matter.
      </p>
      <p>
        The goal is simple: durable memory that can be queried, audited, adapted,
        forgotten, benchmarked, and deployed.
      </p>
    </td>
    <td width="44%" valign="top">
      <h2>Run it</h2>
      <pre><code>pip install wavemind
wavemind quickstart</code></pre>
      <pre><code>from wavemind import WaveMind

memory = WaveMind()
memory.remember("Andrey prefers concise answers")
print(memory.query("How should I answer?"))</code></pre>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/memory-loop.svg" alt="WaveMind adaptive memory loop" width="100%" />
  </a>
</p>

## Featured Work

| Project | What it is | Status |
| --- | --- | --- |
| [**WaveMind**](https://github.com/CaspianG/wavemind) | Adaptive memory engine with SQLite, FAISS-style indexing work, graph recall, Memory OS workers, Studio, HTTP API, CLI, Docker, benchmarks, and LangChain/LlamaIndex examples. | Active |
| [**focus-flow**](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for 50/10 and 90/15 deep-work sessions with English and Russian UI. | Public |
| [**CORECITY**](https://github.com/CaspianG/CORECITY) | Browser game concept around a living market mechanic. | Public |

## What I Care About

| Area | Direction |
| --- | --- |
| Dynamic memory | Hotness, decay, priority, corrections, graph recall, TTL, and long-term context. |
| Local-first systems | Tools that run on a developer machine first, then scale to services when needed. |
| Evidence | Real benchmarks, reproducible scripts, public limitations, and clear tradeoffs. |
| Product polish | Interfaces that make complex systems visible, testable, and understandable. |

## Current Roadmap

```text
static retrieval:
embed -> vector search -> top-k -> prompt

adaptive memory:
remember -> retrieve -> adapt -> explain -> improve
```

| Track | Work in progress |
| --- | --- |
| Scale | Persisted indexes, sharding, service-backed load tests, and predictable latency. |
| Memory dynamics | Graph recall, consolidation, conflict handling, feedback loops, and field simulation. |
| Evaluation | LoCoMo, LongMemEval-style retrieval, stale-fact suppression, and competitor baselines. |
| Ecosystem | LangChain, LlamaIndex, CLI, HTTP API, Docker, Studio, and production examples. |

## Stack

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-050505?style=flat-square&logo=python&logoColor=white">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-050505?style=flat-square&logo=fastapi&logoColor=white">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-050505?style=flat-square&logo=sqlite&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-050505?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-050505?style=flat-square&logo=redis&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-050505?style=flat-square&logo=docker&logoColor=white">
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-050505?style=flat-square&logo=kubernetes&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-050505?style=flat-square&logo=typescript&logoColor=white">
</p>

## Collaboration

I am interested in long-term memory, local-first developer tools, retrieval systems,
agent infrastructure, graph recall, privacy-aware forgetting, and production
workloads where static vector search is not enough.

The best entry point is
[WaveMind issues](https://github.com/CaspianG/wavemind/issues), or the
[quick start](https://github.com/CaspianG/wavemind#user-content-quick-start)
if you want to test it on your own data.
