<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.png" alt="CaspianG - adaptive memory for long-running software" width="100%" />
  </a>
</p>

<h1 align="center">I build adaptive memory systems for software that runs for a long time.</h1>

<p align="center">
  Local-first infrastructure, dynamic retrieval, durable state, clean forgetting,
  and benchmarks for memory that changes with use.
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
  &nbsp;/&nbsp;
  <a href="https://pypi.org/project/wavemind/">PyPI</a>
  &nbsp;/&nbsp;
  <a href="https://github.com/CaspianG/wavemind/blob/main/README.md#quick-start">Quick Start</a>
  &nbsp;/&nbsp;
  <a href="https://github.com/CaspianG/wavemind/blob/main/README.md#benchmark">Benchmarks</a>
  &nbsp;/&nbsp;
  <a href="https://github.com/CaspianG/wavemind/issues">Issues</a>
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
    <td width="56%" valign="top">
      <h2>Now building</h2>
      <p>
        <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
        is an open-source memory layer for agents, copilots, research notebooks,
        support systems, and products that accumulate context over time.
      </p>
      <p>
        It keeps durable memory as the source of truth, retrieves candidates
        through fast indexes, then applies adaptive behavior on top: priority,
        decay, TTL, namespaces, feedback, graph links, provenance, and forgetting.
      </p>
      <p>
        The direction is practical: useful memory should become easier to recall,
        stale memory should fade, and important answers should be traceable.
      </p>
    </td>
    <td width="44%" valign="top">
      <h2>Try WaveMind</h2>
      <pre><code class="language-bash">pip install wavemind</code></pre>
      <pre><code class="language-python">from wavemind import WaveMind

memory = WaveMind()
memory.remember("The user prefers concise technical answers.")

result = memory.query("How should I answer?")[0]
print(result.text)</code></pre>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/wavemind-map.png" alt="WaveMind memory loop: capture, score, recall, adapt" width="100%" />
  </a>
</p>

## Why This Matters

| Static vector search | Adaptive memory |
| --- | --- |
| Finds nearby text. | Tracks memory state over time. |
| Treats old, corrected, and noisy facts as equally searchable unless manually filtered. | Uses TTL, decay, feedback, priority, and forgetting to reduce stale or wrong memories. |
| Works well for document lookup. | Targets long-running systems that need context, preferences, corrections, and history. |
| Usually explains similarity. | Keeps provenance, recall evidence, benchmark artifacts, and lifecycle state close to the result. |

## Current Work

| Area | What I am pushing toward |
| --- | --- |
| Dynamic memory | Hotness, decay, TTL, feedback, conflict handling, consolidation, and graph dynamics. |
| Evidence | Public benchmarks, latency profiles, regression tests, and comparison with static vector retrieval. |
| Developer experience | Python API, FastAPI server, CLI, Docker, examples, and framework adapters. |
| Production path | Persistence, backups, observability, access control, external indexes, sharding, and scale testing. |

## Projects

| Project | Focus | Status |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Dynamic long-term memory for agents and applications | Active |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions | Stable |
| [CORECITY](https://github.com/CaspianG/CORECITY) | Browser game concept built around a live market mechanic | Public archive |

## How I Build

- Local-first before hosted-first.
- Reproducible benchmarks before broad claims.
- Clear interfaces before impressive demos.
- Memory as evolving state, not only embedded text.
- Privacy-aware forgetting as a core primitive.

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
