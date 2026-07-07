<p align="center">
  <a href="https://github.com/CaspianG/wavemind">
    <img src="./assets/header.svg" alt="CaspianG - memory infrastructure for software that adapts" width="100%" />
  </a>
</p>

<h3 align="center">I build memory infrastructure for software that should remember, adapt, and stay useful over time.</h3>

<p align="center">
  <a href="https://github.com/CaspianG/wavemind">WaveMind</a>
  ·
  <a href="https://github.com/CaspianG?tab=repositories">Projects</a>
  ·
  <a href="https://github.com/CaspianG/wavemind/issues">Issues</a>
  ·
  <a href="https://pypi.org/project/wavemind/">PyPI</a>
</p>

---

## What I Am Building

Most AI memory systems behave like a static vector table: embed text, search top-k, paste results into context.

I am building **WaveMind** as a dynamic memory layer: memory has namespaces, TTL, hotness, decay, feedback, consolidation, and benchmarked retrieval behavior. The goal is simple: software should remember what matters, forget what expired, and adapt as usage changes.

```python
from wavemind import WaveMind

memory = WaveMind()
memory.remember("The user prefers short technical answers.", namespace="user")
print(memory.query("How should I answer?", namespace="user")[0].text)
```

## Focus

| Area | Direction |
| --- | --- |
| Dynamic memory | Hotness, decay, TTL, stale-fact suppression, consolidation |
| Local-first systems | SQLite source of truth, simple Python API, FastAPI, Docker |
| Production path | FAISS, Qdrant, pgvector, sharding, background workers, observability |
| Evaluation | LoCoMo, LongMemEval, BEIR/SciFact, scale-readiness profiles |
| Ecosystem | LangChain, LlamaIndex, agent frameworks, practical examples |

## Featured Work

| Project | What it is | Status |
| --- | --- | --- |
| [WaveMind](https://github.com/CaspianG/wavemind) | Dynamic long-term memory for agents and applications | Active |
| [focus-flow](https://github.com/CaspianG/focus-flow) | Minimal desktop focus timer for deep-work sessions | Stable |
| [CORECITY](https://github.com/CaspianG/CORECITY) | Online game concept around a live player-driven market | Experimental |

## WaveMind In One Line

> A local-first memory engine where recall is not only similarity search, but a living state: reinforced, decayed, scoped, tested, and persisted.

## Current Priorities

- Make dynamic memory measurably better than plain vector search on long-running agent workloads.
- Scale from local notebooks to production services without losing the simple API.
- Keep benchmarks honest: publish what works, what fails, and what still needs tuning.
- Build examples that developers can run in minutes, not only read about.

## Stack

`Python` · `FastAPI` · `SQLite` · `PostgreSQL` · `FAISS` · `Qdrant` · `Docker` · `GitHub Actions` · `TypeScript`

## Open Collaboration

WaveMind is early, active, and practical. Useful contributions are especially welcome around benchmarks, integrations, production backends, documentation, and real agent-memory scenarios.

Start here: [CaspianG/wavemind](https://github.com/CaspianG/wavemind)
