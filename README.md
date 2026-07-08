<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.svg" alt="CaspianG - dynamic memory infrastructure" width="100%" />
  </a>
</p>

<h1 align="center">Building dynamic memory infrastructure for software that keeps context alive.</h1>

<p align="center">
  I work on local-first memory systems, adaptive retrieval, graph-based recall,
  production benchmarks, and developer tools for long-running intelligent software.
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
  &nbsp;·&nbsp;
  <a href="https://pypi.org/project/wavemind/">PyPI</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/CaspianG/wavemind#quick-start">Quick Start</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/CaspianG/wavemind#benchmarks">Benchmarks</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/CaspianG/wavemind/issues">Issues</a>
</p>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind"><img alt="WaveMind" src="https://img.shields.io/badge/WaveMind-dynamic_memory-111111?style=for-the-badge"></a>
  <a href="https://pypi.org/project/wavemind/"><img alt="PyPI" src="https://img.shields.io/pypi/v/wavemind?style=for-the-badge&label=PyPI&color=111111"></a>
  <a href="https://github.com/CaspianG/wavemind/actions"><img alt="Checks" src="https://img.shields.io/github/actions/workflow/status/CaspianG/wavemind/full-check.yml?branch=main&style=for-the-badge&label=checks&color=111111"></a>
  <a href="https://github.com/CaspianG/wavemind"><img alt="Stars" src="https://img.shields.io/github/stars/CaspianG/wavemind?style=for-the-badge&label=stars&color=111111"></a>
</p>

---

<table>
  <tr>
    <td width="58%" valign="top">
      <h2>Now building: WaveMind</h2>
      <p>
        <a href="https://github.com/CaspianG/wavemind"><strong>WaveMind</strong></a>
        is an open-source memory layer for applications that need durable,
        adaptive context instead of one-shot vector lookup.
      </p>
      <p>
        It stores memory as persistent state, retrieves candidates through indexes,
        and then adapts recall using priority, hotness, decay, TTL, namespaces,
        feedback, provenance, graph signals, and forgetting.
      </p>
      <p>
        The goal is practical: useful memory should become easier to recall,
        stale memory should fade, and every important answer should be traceable.
      </p>
    </td>
    <td width="42%" valign="top">
      <h2>Use it in seconds</h2>
      <pre><code class="language-bash">pip install wavemind</code></pre>
      <pre><code class="language-python">from wavemind import WaveMind

memory = WaveMind()
memory.remember("The user prefers concise answers.")

print(memory.query("How should I answer?")[0].text)</code></pre>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/system.svg" alt="WaveMind system map: storage, index, field, graph, API, benchmarks" width="100%" />
  </a>
</p>

## What I Care About

| Area | Direction |
| --- | --- |
| Dynamic memory | Memory that changes with use: hotness, decay, TTL, feedback, corrections, consolidation, and graph dynamics. |
| Local-first infrastructure | SQLite as source of truth, optional ANN/vector backends, CLI, API, Docker, and reproducible artifacts. |
| Production evidence | Benchmarks, latency profiles, release gates, packaging validation, and honest scale limits. |
| Developer adoption | Simple APIs, framework integrations, migration guides, examples, and contributor-friendly issues. |

## Featured Work

| Project | What it is | Status |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Dynamic long-term memory for agents, apps, research notebooks, and internal tools. | Active |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions with English/Russian UI. | Stable |
| [CORECITY](https://github.com/CaspianG/CORECITY) | Browser game concept around a living market mechanic. | Public |

## Working Principles

- Build useful systems first, then prove them under real load.
- Keep local paths fast, inspectable, and easy to run.
- Treat benchmarks and reproducibility as part of the product.
- Make forgetting, provenance, and namespaces first-class primitives.
- Avoid big claims without a runnable artifact behind them.

## Open For

I am interested in memory systems, long-running applications, retrieval benchmarks,
privacy-aware forgetting, production indexes, graph recall, and real workloads where
static vector search starts to break down.

Start with [WaveMind issues](https://github.com/CaspianG/wavemind/issues) if you want
to test an integration, benchmark a workload, or contribute an adapter.
