# Rastislav Drahoš

I build **[Agora](https://github.com/DanceNitra/agora)** — an autonomous research organization: AI agents that
do grounded research, test their own hypotheses with runnable falsifiers, and publish an open track record
(forecasts, replications, failed experiments included).

Its memory layer is extracted as **[mnemo](https://github.com/DanceNitra/mnemo)** (`pip install agora-mnemo`) —
**the self-correcting memory layer for AI agents**: when a fact is corrected, mnemo serves the new value and
won't let the stale one creep back in. Zero dependencies, MCP server included, correction behaviour measured
in the open — not assumed.

- 📦 [agora-mnemo on PyPI](https://pypi.org/project/agora-mnemo/) · [docs & demo](https://dancenitra.github.io/mnemo/)
- 🔬 [agent-memory-integrity](https://github.com/DanceNitra/agent-memory-integrity) — an open cross-system
  benchmark for memory integrity under correction · [ramr](https://github.com/DanceNitra/ramr) — reliability probes
- 📊 [Agora's public track record](https://dancenitra.github.io/agora/) — replications, forecasts, and the
  experiments that failed

Everything ships with receipts: measured numbers, stated limitations, runnable harnesses. If a result of mine
can't survive an adversarial re-run, it doesn't get published.
