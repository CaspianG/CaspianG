<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.png" alt="CaspianG builds memory infrastructure for durable context" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>Building open-source memory infrastructure for software that needs durable context.</strong><br />
  Local-first systems, adaptive recall, reproducible benchmarks, and practical developer tools.
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
    <td width="61%" valign="top">
      <h2>What I am building</h2>
      <p>
        <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
        is a memory engine for long-running software: assistants, research
        notebooks, internal copilots, analyst tools, support systems, and
        developer workflows.
      </p>
      <p>
        It starts with normal retrieval, then adds memory behavior on top:
        hotness, decay, TTL, tags, namespaces, feedback, corrections,
        provenance, graph recall, and benchmarked failure cases.
      </p>
    </td>
    <td width="39%" valign="top">
      <h2>Start here</h2>
      <p><strong>Install</strong></p>
      <pre><code>pip install wavemind</code></pre>
      <p><strong>Run a local demo</strong></p>
      <pre><code>wavemind demo</code></pre>
      <p>
        <a href="https://github.com/CaspianG/wavemind#user-content-quick-start">Read the 3-command Quick Start</a>
      </p>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/wavemind-map.png" alt="WaveMind adaptive memory loop" width="100%" />
  </a>
</p>

## Why WaveMind Exists

Static vector search is a base layer. It can find similar text, but it does not
decide what should stay important, what should fade, what was corrected, or why
a memory was returned.

WaveMind is built around a different contract:

| Static retrieval | Adaptive memory |
| --- | --- |
| Similarity decides the top result. | Similarity finds candidates, then memory state changes ranking. |
| Old and corrected facts can keep winning. | TTL, decay, feedback, and corrections can reduce priority. |
| Context is hard to inspect. | Returned memories include metadata, provenance, and scoring signals. |
| Benchmarks often stop at retrieval. | Agent-memory scenarios test stale facts, namespace leaks, latency, and coherence. |

## Current Focus

| Area | Direction |
| --- | --- |
| Scale | ANN indexes, sharding by namespace, cache-aware recall, and production load tests. |
| Memory OS | Background consolidation, hot-query prewarm, forgetting plans, and operational policies. |
| Benchmarks | LoCoMo, LongMemEval-style retrieval, agent coherence, latency curves, and competitor baselines. |
| Integrations | LangChain, LlamaIndex, HTTP API, CLI, Docker, and examples for real workflows. |
| Product surface | Simple local demos first, then deeper tooling for inspecting memory behavior. |

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
