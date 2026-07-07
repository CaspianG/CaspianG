<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.png" alt="CaspianG - dynamic memory systems for adaptive software" width="100%" />
  </a>
</p>

<h1 align="center">Memory systems that adapt over time.</h1>

<p align="center">
  I build local-first infrastructure for software that needs memory with priority,
  decay, provenance, feedback, and clean forgetting.
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
      <h3>Current focus</h3>
      <p>
        <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
        is an open-source memory layer for agents, copilots, research tools,
        and long-running products where plain vector lookup is not enough.
      </p>
      <p>
        It stores durable memory as source of truth, retrieves candidates through
        fast indexes, then applies adaptive dynamics: hotness, decay, priority,
        TTL, namespaces, graph links, feedback, and provenance.
      </p>
      <p>
        The goal is simple: useful memory should get easier to recall, stale
        memory should lose weight, and every important retrieval should be
        explainable.
      </p>
    </td>
    <td width="42%" valign="top">
      <h3>Try it</h3>
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
    <img src="./assets/wavemind-map.png" alt="WaveMind memory loop: store, retrieve, reinforce, decay, consolidate" width="100%" />
  </a>
</p>

## What I Work On

| Area | Direction |
| --- | --- |
| Adaptive memory | Priority, decay, TTL, feedback, conflict handling, and memory that changes with use. |
| Retrieval evidence | Public benchmarks, regression tests, latency profiles, and honest comparison with static vector search. |
| Developer tools | Python API, HTTP API, CLI, examples, and framework adapters that are simple to install and ship. |
| Production path | Persistence, backups, observability, access control, external indexes, and scale testing. |

## Selected Work

| Project | What it is | Status |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Dynamic long-term memory for agents and applications | Active |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions | Stable |
| [CORECITY](https://github.com/CaspianG/CORECITY) | Browser game concept built around a live market mechanic | Public archive |

## Principles

- Prove claims with tests, reproducible artifacts, and benchmarks.
- Keep the core useful locally before pushing users into hosted infrastructure.
- Treat memory as state that evolves, not only text that was embedded once.
- Prefer clear interfaces over demos that only work in perfect conditions.

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

I am interested in practical memory systems, long-running agents, retrieval
benchmarks, privacy-aware forgetting, production indexes, and real workloads
where static vector search breaks down.

Start with [WaveMind issues](https://github.com/CaspianG/wavemind/issues) if you
want to test an integration, benchmark a workload, or contribute an adapter.
