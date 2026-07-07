<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.png" alt="CaspianG - adaptive memory for long-running software" width="100%" />
  </a>
</p>

<h1 align="center">Building adaptive memory for software that needs to remember.</h1>

<p align="center">
  I work on local-first memory infrastructure: durable storage, retrieval,
  priority, decay, feedback, provenance, and clean forgetting.
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
  &nbsp;/&nbsp;
  <a href="https://pypi.org/project/wavemind/">PyPI</a>
  &nbsp;/&nbsp;
  <a href="https://github.com/CaspianG/wavemind#quick-start">Quick Start</a>
  &nbsp;/&nbsp;
  <a href="https://github.com/CaspianG/wavemind#benchmarks">Benchmarks</a>
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
      <h3>Now shipping</h3>
      <p>
        <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
        is an open-source memory layer for agents, copilots, research tools,
        support systems, and long-running products.
      </p>
      <p>
        It keeps SQLite as the source of truth, uses vector indexes for fast
        candidate retrieval, then applies dynamic memory behavior on top:
        hotness, decay, TTL, namespaces, feedback, graph links, and provenance.
      </p>
      <p>
        The practical goal is simple: useful memory becomes easier to recall,
        stale memory loses weight, and important answers can be traced back to
        the facts that produced them.
      </p>
    </td>
    <td width="42%" valign="top">
      <h3>Try it in 30 seconds</h3>
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
    <img src="./assets/wavemind-map.png" alt="WaveMind memory loop: ingest, persist, retrieve, adapt, recall" width="100%" />
  </a>
</p>

## What Makes It Different

| Static vector search | WaveMind |
| --- | --- |
| Stores embeddings and returns nearest neighbors. | Stores memory state and lets retrieval quality change with use. |
| Old, corrected, and noisy facts remain equally searchable unless manually filtered. | TTL, decay, feedback, and forgetting reduce stale or wrong memories. |
| Good for document lookup. | Built for long-running software that accumulates user context over time. |
| Usually explains similarity, not lifecycle. | Keeps provenance, priority, recall evidence, and benchmark artifacts close to the result. |

## Current Focus

| Area | Direction |
| --- | --- |
| Adaptive memory | Priority, decay, TTL, feedback, conflict handling, consolidation, and graph dynamics. |
| Retrieval evidence | Public benchmarks, regression tests, latency profiles, and honest comparison with static vector search. |
| Developer experience | Python API, FastAPI server, CLI, LangChain/LlamaIndex examples, Docker, and one-command demos. |
| Production path | Persistence, backups, observability, access control, external indexes, sharding, and scale testing. |

## Selected Work

| Project | What it is | Status |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Dynamic long-term memory for agents and applications | Active |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions | Stable |
| [CORECITY](https://github.com/CaspianG/CORECITY) | Browser game concept built around a live market mechanic | Public archive |

## How I Build

- Local-first before hosted-first.
- Reproducible benchmarks before broad claims.
- Clear interfaces before impressive demos.
- Memory as evolving state, not only embedded text.
- Privacy-aware forgetting as a core primitive, not an afterthought.

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
