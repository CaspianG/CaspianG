<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/profile-hero.svg" alt="CaspianG builds adaptive memory infrastructure" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>I build memory infrastructure for software that needs durable context.</strong><br />
  WaveMind is the main project: local-first adaptive memory with retrieval, decay, priority, TTL, namespaces, provenance, and reproducible benchmarks.
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-adaptive%20memory-111111?style=for-the-badge"></a>
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
        <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
        is a memory engine for long-running software: assistants, research
        notebooks, internal copilots, analyst tools, support systems, and
        developer workflows.
      </p>
      <p>
        It begins with normal vector retrieval, then adds memory behavior:
        hotness, decay, TTL, tags, namespaces, feedback, corrections,
        provenance, graph recall, and operational benchmark checks.
      </p>
      <p>
        The goal is simple: memory that can adapt over time instead of only
        returning the nearest vector.
      </p>
    </td>
    <td width="42%" valign="top">
      <h2>Try WaveMind</h2>
      <p><strong>Install</strong></p>
      <pre><code>pip install wavemind</code></pre>
      <p><strong>Run locally</strong></p>
      <pre><code>wavemind quickstart</code></pre>
      <p><strong>Use from Python</strong></p>
      <pre><code>from wavemind import WaveMind
memory = WaveMind()
memory.remember("Andrey prefers concise answers")
print(memory.query("What style does Andrey like?"))</code></pre>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/memory-system.svg" alt="WaveMind adaptive memory system" width="100%" />
  </a>
</p>

## Why This Matters

Most retrieval systems answer one question: "which text is most similar?"

Long-running software needs more than that. It needs memory that can change
importance, suppress stale facts, isolate namespaces, preserve provenance, and
show why something was recalled.

| Static retrieval | Adaptive memory |
| --- | --- |
| Similarity decides the top result. | Similarity finds candidates, then memory state changes ranking. |
| Old or corrected facts can keep winning. | TTL, decay, feedback, and corrections reduce stale priority. |
| Context is hard to inspect. | Returned memories include metadata, provenance, and scoring signals. |
| Benchmarks often stop at retrieval. | WaveMind tests stale facts, namespace leaks, latency, and coherence. |

## Current Focus

| Area | What I am pushing forward |
| --- | --- |
| Scale | ANN indexes, sharding by namespace, cache-aware recall, and production load tests. |
| Memory OS | Background consolidation, hot-query prewarm, forgetting policies, and priority learning. |
| Benchmarks | LoCoMo, LongMemEval-style retrieval, agent coherence, latency curves, and competitor baselines. |
| Integrations | LangChain, LlamaIndex, HTTP API, CLI, Docker, and examples for real workflows. |
| Product surface | Clear local demos first, then tools for inspecting memory behavior. |

## Selected Work

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

## Open To

I am interested in practical memory systems, retrieval benchmarks, local-first
software, privacy-aware forgetting, graph recall, production indexes, and real
workloads where static vector search starts to break down.

Start with [WaveMind issues](https://github.com/CaspianG/wavemind/issues) if you
want to test an integration, benchmark a workload, or contribute an adapter.
