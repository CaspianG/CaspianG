<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.svg" alt="CaspianG - memory infrastructure for durable software" width="100%" />
  </a>
</p>

<h1 align="center">I build memory infrastructure for software that has to keep context alive.</h1>

<p align="center">
  Open-source maintainer of <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>:
  a local-first memory layer that treats memory as evolving state, not just embedded text.
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">WaveMind</a>
  &nbsp;|&nbsp;
  <a href="https://pypi.org/project/wavemind/">PyPI</a>
  &nbsp;|&nbsp;
  <a href="https://github.com/CaspianG/wavemind?tab=readme-ov-file#quick-start">Quick Start</a>
  &nbsp;|&nbsp;
  <a href="https://github.com/CaspianG/wavemind?tab=readme-ov-file#benchmarks">Benchmarks</a>
  &nbsp;|&nbsp;
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
    <td width="55%" valign="top">
      <h2>What I am building</h2>
      <p>
        Most memory systems stop at <strong>embedding -> vector search -> top-k</strong>.
        That is useful for document lookup, but weak for software that has to live with
        corrections, preferences, stale facts, repeated behavior, and long-running state.
      </p>
      <p>
        WaveMind adds a memory control layer: durable storage, adaptive ranking,
        TTL, decay, namespaces, feedback, provenance, graph signals, and benchmarked
        production paths.
      </p>
    </td>
    <td width="45%" valign="top">
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

## Focus

<table>
  <tr>
    <td width="25%" valign="top">
      <h3>Dynamic memory</h3>
      <p>Memory that changes through use: hotness, decay, feedback, TTL, corrections, and forgetting.</p>
    </td>
    <td width="25%" valign="top">
      <h3>Production evidence</h3>
      <p>Benchmarks, release gates, CI checks, packaging validation, and honest scale limits.</p>
    </td>
    <td width="25%" valign="top">
      <h3>Local-first systems</h3>
      <p>SQLite as source of truth, optional ANN/vector backends, CLI/API, Docker, and reproducible artifacts.</p>
    </td>
    <td width="25%" valign="top">
      <h3>Developer adoption</h3>
      <p>Clear examples, LangChain/LlamaIndex integrations, migration guides, and contributor-friendly issues.</p>
    </td>
  </tr>
</table>

## Featured Work

<table>
  <tr>
    <td width="34%" valign="top">
      <h3><a href="https://github.com/CaspianG/wavemind">WaveMind</a></h3>
      <p>Dynamic long-term memory for agents and applications. Local-first core, HTTP API, CLI, benchmarks, graph memory, Studio, and production evidence gates.</p>
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

## How I Work

- Build the smallest useful system, then prove it under load.
- Keep local-first paths fast, inspectable, and easy to run.
- Treat benchmarks as product surface, not internal paperwork.
- Make forgetting, provenance, and namespaces first-class primitives.
- Avoid broad claims until there is a reproducible artifact behind them.

## Current Direction

WaveMind is moving from a memory library toward a practical memory operating layer:
background maintenance, policy learning, graph consolidation, large-scale backend profiles,
and real comparisons against static vector search and agent-memory baselines.

If you want to test an integration, benchmark a workload, or contribute an adapter, start with
[WaveMind issues](https://github.com/CaspianG/wavemind/issues).
