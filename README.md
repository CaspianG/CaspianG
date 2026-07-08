<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.svg" alt="CaspianG - dynamic memory systems for long-running software" width="100%" />
  </a>
</p>

<h1 align="center">Building dynamic memory for software that has to keep context alive.</h1>

<p align="center">
  I work on local-first memory systems: durable state, adaptive retrieval, TTL, decay,
  feedback, namespaces, provenance, benchmarks, and production paths for agents and applications.
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
  &nbsp;·&nbsp;
  <a href="https://pypi.org/project/wavemind/">PyPI</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/CaspianG/wavemind?tab=readme-ov-file#quick-start">Quick Start</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/CaspianG/wavemind?tab=readme-ov-file#benchmarks">Benchmarks</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/CaspianG/wavemind/issues">Contribute</a>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-dynamic_memory-111111?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=111111"></a>
  <a href="https://github.com/CaspianG/wavemind/actions"><img alt="Checks" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/full-check.yml?branch=main&style=for-the-badge&label=checks&color=111111"></a>
  <a href="https://github.com/CaspianG/wavemind/releases"><img alt="Release" src="https://img.shields.io/github/v/release/CaspianG/wavemind?style=for-the-badge&label=release&color=111111"></a>
</p>

---

<table>
  <tr>
    <td width="58%" valign="top">
      <h2>Current Mission</h2>
      <p>
        <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
        is an open-source memory layer for systems that grow through use:
        agents, copilots, research notebooks, support tools, personal assistants,
        and long-running applications.
      </p>
      <p>
        Instead of treating memory as just embedded text, WaveMind keeps memory as
        evolving state: what was useful, what is stale, what was corrected, what
        belongs to which namespace, and why a result was recalled.
      </p>
    </td>
    <td width="42%" valign="top">
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
    <img src="./assets/wavemind-map.svg" alt="WaveMind memory loop: ingest, persist, retrieve, adapt, recall" width="100%" />
  </a>
</p>

## What I Am Building

Most retrieval systems stop here:

```text
embedding -> vector search -> top-k -> prompt
```

That works for document lookup. It is not enough when software must remember preferences,
corrections, old context, repeated behavior, and facts that expire.

WaveMind pushes toward:

```text
durable memory -> candidate retrieval -> adaptive ranking -> evidence -> lifecycle update
```

## Why It Matters

| Static vector search | Dynamic memory |
| --- | --- |
| Finds nearby text. | Tracks memory state over time. |
| Old and corrected facts can keep winning. | TTL, decay, feedback, priority, and forgetting suppress stale memories. |
| Optimized for document lookup. | Built for systems that accumulate context through interaction. |
| Similarity is the main explanation. | Results can carry evidence, namespace, lifecycle state, and benchmark context. |

## Featured Work

<table>
  <tr>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/CaspianG/wavemind">WaveMind</a></h3>
      <p>Dynamic long-term memory for agents and applications. Local-first core, HTTP API, CLI, benchmarks, graph memory, and production evidence gates.</p>
    </td>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/CaspianG/focus-flow">focus-flow</a></h3>
      <p>Minimal desktop focus timer for deep-work sessions with planning, light/dark themes, and English/Russian UI.</p>
    </td>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/CaspianG/CORECITY">CORECITY</a></h3>
      <p>Browser game concept built around a living market mechanic where players, prices, and events shape the city.</p>
    </td>
  </tr>
</table>

## Operating Principles

- Local-first before hosted-first.
- Benchmarks before broad claims.
- Clear interfaces before impressive demos.
- Memory as evolving state, not only embedded text.
- Forgetting, provenance, and namespaces as first-class primitives.
- Production evidence gates before release claims.

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
