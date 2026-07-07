<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.svg" alt="CaspianG - adaptive memory infrastructure" width="100%" />
  </a>
</p>

<h2 align="center">I build adaptive memory infrastructure for long-running software.</h2>

<p align="center">
  Local-first systems that remember useful context, rank what matters, explain recall,
  and let stale state fade instead of growing into noise.
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
    <td width="55%" valign="top">
      <h3>Now Building</h3>
      <p>
        <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
        is an open-source memory layer for agents, copilots, research tools,
        and products that need memory behavior instead of plain vector lookup.
      </p>
      <p>
        The system keeps durable storage as source of truth, retrieves candidates
        through fast indexes, then applies adaptive memory dynamics: hotness, decay,
        TTL, priority, namespaces, feedback, graph links, and provenance.
      </p>
      <ul>
        <li><strong>Local-first:</strong> SQLite by default, production backends when scale requires them.</li>
        <li><strong>Benchmarked:</strong> public runner scripts, checked artifacts, and honest limitations.</li>
        <li><strong>Integration-ready:</strong> Python, HTTP API, LangChain, LlamaIndex, CrewAI, AutoGen.</li>
      </ul>
    </td>
    <td width="45%" valign="top">
      <h3>Use It</h3>
      <pre><code class="language-bash">pip install wavemind</code></pre>
      <pre><code class="language-python">from wavemind import WaveMind

memory = WaveMind()
memory.remember("The user prefers short technical answers.")

result = memory.query("How should I answer?")[0]
print(result.text)</code></pre>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/wavemind-map.svg" alt="WaveMind memory loop" width="100%" />
  </a>
</p>

## Focus Areas

| Area | What I care about |
| --- | --- |
| Adaptive memory | Systems that update importance over time, handle corrections, and separate hot context from stale state. |
| Retrieval evidence | Benchmarks, regression gates, latency profiles, and comparisons against static vector search. |
| Developer tools | Small install surface, practical examples, framework adapters, and APIs that are easy to ship. |
| Production path | Persistence, backups, observability, access control, external indexes, and scale testing. |

## Selected Work

| Project | What it is | Status |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Dynamic long-term memory for agents and applications | Active |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions | Stable |
| [CORECITY](https://github.com/CaspianG/CORECITY) | Browser game concept built around a live market mechanic | Public archive |

## Principles

- Prove claims with tests and benchmarks before turning them into marketing.
- Keep the core useful locally before pushing users into hosted infrastructure.
- Treat memory as state that evolves, not just text that was embedded once.
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

I am interested in practical memory systems, long-running agents, retrieval benchmarks,
privacy-aware forgetting, production indexes, and real workloads where static vector search is not enough.

Start with [WaveMind issues](https://github.com/CaspianG/wavemind/issues) if you want to test an integration,
benchmark a workload, or contribute an adapter.
