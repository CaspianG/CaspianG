<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.svg" alt="CaspianG - adaptive memory for software that runs long" width="100%" />
  </a>
</p>

<h1 align="center">I build memory systems for software that keeps working after the prompt window is gone.</h1>

<p align="center">
  Dynamic retrieval, durable local state, TTL, feedback, namespaces, graph memory,
  observability, benchmarks, and production paths for long-running agents and applications.
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
  &nbsp;/&nbsp;
  <a href="https://pypi.org/project/wavemind/">PyPI</a>
  &nbsp;/&nbsp;
  <a href="https://github.com/CaspianG/wavemind?tab=readme-ov-file#quick-start">Quick Start</a>
  &nbsp;/&nbsp;
  <a href="https://github.com/CaspianG/wavemind?tab=readme-ov-file#benchmark">Benchmarks</a>
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
      <h2>Current focus</h2>
      <p>
        <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
        is an open-source memory layer for agents, copilots, research notebooks,
        support tools, and products that accumulate context over time.
      </p>
      <p>
        It keeps durable memory as the source of truth, retrieves candidates
        through fast indexes, then applies adaptive behavior on top: priority,
        decay, TTL, feedback, graph links, provenance, and forgetting.
      </p>
      <p>
        The goal is practical: useful memories become easier to recall,
        stale memories fade, corrected facts stop winning, and every recall can
        be traced back to evidence.
      </p>
    </td>
    <td width="42%" valign="top">
      <h2>Try it</h2>
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
    <img src="./assets/wavemind-map.svg" alt="WaveMind memory loop: ingest, persist, retrieve, adapt, recall" width="100%" />
  </a>
</p>

## Why I Am Building This

Most retrieval systems stop at:

```text
embedding -> vector search -> top-k -> prompt
```

That is useful for document lookup. It is not enough for long-running software that needs preferences, corrections, aging facts, trust, and repeated use.

WaveMind pushes toward:

```text
memory state -> candidate retrieval -> adaptive ranking -> evidence -> lifecycle update
```

## What Makes The Work Different

| Static vector search | Adaptive memory |
| --- | --- |
| Finds nearby text. | Tracks memory state over time. |
| Treats old, corrected, and noisy facts as equally searchable unless manually filtered. | Uses TTL, decay, feedback, priority, and forgetting to suppress stale or wrong memories. |
| Works well for document lookup. | Targets long-running systems that need context, preferences, corrections, and history. |
| Usually explains similarity. | Keeps provenance, recall evidence, benchmark artifacts, and lifecycle state close to the result. |

## Main Project

| Project | What it does | Status |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Dynamic long-term memory for agents and applications | Active |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions | Stable |
| [CORECITY](https://github.com/CaspianG/CORECITY) | Browser game concept built around a live market mechanic | Public archive |

## Engineering Principles

- Local-first before hosted-first.
- Benchmarks before broad claims.
- Clear interfaces before impressive demos.
- Memory as evolving state, not only embedded text.
- Forgetting, provenance, and namespaces as first-class primitives.

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

I am interested in practical memory systems, long-running agents, retrieval benchmarks,
privacy-aware forgetting, production indexes, and real workloads where static vector
search starts to break down.

Start with [WaveMind issues](https://github.com/CaspianG/wavemind/issues) if you want
to test an integration, benchmark a workload, or contribute an adapter.
