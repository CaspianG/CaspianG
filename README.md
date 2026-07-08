<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="https://raw.githubusercontent.com/CaspianG/CaspianG/main/assets/profile-hero-v3.svg" alt="CaspianG builds adaptive memory systems" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>Building adaptive memory systems, agent infrastructure, and local-first developer tools.</strong><br />
  Main work:
  <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>,
  a memory engine for software that needs durable, inspectable context.
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-adaptive%20memory-050505?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=050505"></a>
  <a href="https://github.com/CaspianG/wavemind/actions/workflows/full-check.yml"><img alt="Checks" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/full-check.yml?branch=main&style=for-the-badge&label=checks&color=050505"></a>
  <a href="https://github.com/CaspianG/wavemind/releases"><img alt="Release" src="https://img.shields.io/github/v/release/CaspianG/wavemind?style=for-the-badge&label=release&color=050505"></a>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><strong>Repository</strong></a>
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
      <h2>What I build</h2>
      <p>
        I work on systems that preserve useful context after a request, chat,
        job, or session ends.
      </p>
      <p>
        The current focus is dynamic memory: retrieval that can account for
        freshness, priority, namespaces, TTL, graph links, corrections, and
        evidence instead of treating memory as static top-k search.
      </p>
    </td>
    <td width="42%" valign="top">
      <h2>Run WaveMind</h2>
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
    <img src="./assets/memory-system-v2.svg" alt="WaveMind memory system diagram" width="100%" />
  </a>
</p>

## Featured Work

| Project | Focus | Status |
| --- | --- | --- |
| [**WaveMind**](https://github.com/CaspianG/wavemind) | Adaptive memory layer with persistence, APIs, benchmarks, namespaces, decay, graph recall, and production-scale work. | Active |
| [**focus-flow**](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions with English and Russian UI. | Public |
| [**CORECITY**](https://github.com/CaspianG/CORECITY) | Browser game concept around a living market mechanic. | Public |

## Current Direction

```text
static retrieval:
embed -> vector search -> top-k -> prompt

adaptive memory:
remember -> retrieve -> adapt -> explain -> improve
```

| Track | Work |
| --- | --- |
| Scale | FAISS, sharding, persisted indexes, service-backed load tests, predictable latency. |
| Memory dynamics | Decay, priority, graph recall, consolidation, corrections, and feedback loops. |
| Evidence | LoCoMo, LongMemEval-style retrieval, stale-fact suppression, and competitor baselines. |
| Integrations | LangChain, LlamaIndex, HTTP API, CLI, Docker, and production examples. |
| Product surface | Studio, dashboards, memory inspection, imports, backups, and operator workflows. |

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

I am interested in long-term memory, local-first software, retrieval systems,
agent infrastructure, graph recall, privacy-aware forgetting, and production
workloads where static vector search is not enough.

The best entry point is
[WaveMind issues](https://github.com/CaspianG/wavemind/issues), or the
[quick start](https://github.com/CaspianG/wavemind#user-content-quick-start)
if you want to test it on your own data.
