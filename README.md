<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.png" alt="CaspianG builds memory systems for durable context" width="100%" />
  </a>
</p>

<h1 align="center">CaspianG</h1>

<p align="center">
  <strong>Building open-source memory infrastructure for software that needs context to evolve, not just be stored.</strong>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-dynamic%20memory-111111?style=for-the-badge"></a>
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
    <td width="56%" valign="top">
      <h2>Primary Work</h2>
      <h3><a href="https://github.com/CaspianG/wavemind">WaveMind</a></h3>
      <p>
        WaveMind is a local-first memory engine for long-running software,
        assistants, research notebooks, internal copilots, support systems,
        and developer tools.
      </p>
      <p>
        The goal is simple: useful context should become easier to recall,
        stale context should fade, corrections should matter, and memory
        behavior should stay inspectable.
      </p>
      <p>
        <a href="https://github.com/CaspianG/wavemind"><strong>Repository</strong></a>
        &nbsp;/&nbsp;
        <a href="https://github.com/CaspianG/wavemind#user-content-quick-start">Install</a>
        &nbsp;/&nbsp;
        <a href="https://github.com/CaspianG/wavemind#user-content-benchmark">Evidence</a>
      </p>
    </td>
    <td width="44%" valign="top">
      <h2>Current Focus</h2>
      <ul>
        <li>Adaptive recall: hotness, decay, TTL, feedback.</li>
        <li>Namespaces, tags, provenance, and safe forgetting.</li>
        <li>Graph-aware memory and consolidation.</li>
        <li>SQLite source of truth with ANN and service backends.</li>
        <li>Benchmarks, CI gates, and reproducible reports.</li>
      </ul>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/wavemind-map.png" alt="WaveMind memory loop" width="100%" />
  </a>
</p>

## What I Care About

| Area | Direction |
| --- | --- |
| Dynamic memory | Memory should change with use, time, feedback, and corrections. |
| Retrieval systems | Vector search is useful, but production memory needs priority, scope, and provenance. |
| Local-first software | Developers should be able to run, inspect, back up, and move their own memory layer. |
| Benchmarks | Claims should be backed by runnable tests, public artifacts, and repeatable baselines. |
| Product quality | The useful path should be simple before the system becomes complex. |

## Where WaveMind Fits

| Use case | Why it matters |
| --- | --- |
| Personal assistants | Remember preferences, corrections, names, and recurring context without stuffing every prompt. |
| Research notebooks | Keep notes, source traces, evidence, and long-running investigation context searchable. |
| Internal copilots | Preserve team context, operational decisions, support history, and compliance-friendly forget flows. |
| Developer agents | Recall project facts, issue history, architecture choices, and repeated local decisions. |
| Analyst tools | Store structured notes, documents, events, and benchmarkable retrieval evidence. |

## Project Map

| Project | Focus | Status |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Dynamic long-term memory for software with durable context. | Active |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions with English and Russian UI. | Stable |
| [CORECITY](https://github.com/CaspianG/CORECITY) | Browser game concept built around a living market mechanic. | Public archive |

## Engineering Stack

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
infrastructure, privacy-aware forgetting, graph recall, production indexes, and
real workloads where static vector search starts to break down.

Start with [WaveMind issues](https://github.com/CaspianG/wavemind/issues) if you
want to test an integration, benchmark a workload, or contribute an adapter.
