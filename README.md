<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/profile-hero.svg" alt="CaspianG builds adaptive memory systems" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>Building adaptive memory systems for software that needs durable context.</strong><br />
  Main project: <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>, a local-first memory layer with retrieval, decay, priority, namespaces, provenance, and reproducible benchmarks.
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-adaptive%20memory-111111?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=111111"></a>
  <a href="https://github.com/CaspianG/wavemind/actions/workflows/full-check.yml"><img alt="Checks" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/full-check.yml?branch=main&style=for-the-badge&label=checks&color=111111"></a>
  <a href="https://github.com/CaspianG/wavemind/releases"><img alt="Release" src="https://img.shields.io/github/v/release/CaspianG/wavemind?style=for-the-badge&label=release&color=111111"></a>
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
    <td width="57%" valign="top">
      <h2>Current Focus</h2>
      <p>
        I am working on memory infrastructure that behaves less like a static
        vector search box and more like a living context layer.
      </p>
      <p>
        WaveMind stores facts, retrieves candidates, then applies memory state:
        hotness, decay, TTL, feedback, corrections, graph recall, and namespace
        isolation.
      </p>
      <p>
        The practical goal is simple: long-running software should remember
        useful context, suppress stale context, and make recall inspectable.
      </p>
    </td>
    <td width="43%" valign="top">
      <h2>Try WaveMind</h2>
      <p><strong>Install</strong></p>
      <pre><code>pip install wavemind</code></pre>
      <p><strong>Run a local demo</strong></p>
      <pre><code>wavemind quickstart</code></pre>
      <p><strong>Use from Python</strong></p>
      <pre><code>from wavemind import WaveMind

memory = WaveMind()
memory.remember("Andrey prefers concise answers")
print(memory.query("How should I answer Andrey?"))</code></pre>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/memory-system.svg" alt="WaveMind memory loop" width="100%" />
  </a>
</p>

## Why WaveMind

| Static vector search | WaveMind memory layer |
| --- | --- |
| Returns nearest vectors. | Finds candidates, then re-ranks with memory state. |
| Old facts can keep winning. | TTL, decay, feedback, and corrections lower stale priority. |
| Context is hard to audit. | Results include metadata, provenance, and scoring signals. |
| Benchmarks often stop at top-k retrieval. | Tests include stale facts, namespace isolation, latency, and coherence. |

## Workbench

| Track | What is being built |
| --- | --- |
| Scale | ANN indexes, namespace sharding, cache-aware recall, and production load tests. |
| Memory OS | Background consolidation, forgetting policies, graph dynamics, and priority learning. |
| Benchmarks | LoCoMo, LongMemEval-style retrieval, agent coherence, latency curves, and competitor baselines. |
| Integrations | LangChain, LlamaIndex, HTTP API, CLI, Docker, and practical workflow examples. |
| Product surface | Local demos first, then tools for inspecting and debugging memory behavior. |

## Selected Projects

| Project | Focus | Status |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Adaptive long-term memory for software with durable context. | Active |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions. | Stable |
| [CORECITY](https://github.com/CaspianG/CORECITY) | Browser game concept around a living market mechanic. | Public archive |

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

I am interested in practical memory systems, retrieval benchmarks, local-first
software, privacy-aware forgetting, graph recall, production indexes, and real
workloads where static vector search starts to break down.

Start with [WaveMind issues](https://github.com/CaspianG/wavemind/issues) if you
want to test an integration, benchmark a workload, or contribute an adapter.
