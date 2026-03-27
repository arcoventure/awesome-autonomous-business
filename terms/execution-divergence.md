# Execution Divergence

**Canonical definition (Arco Lexicon)**
> The measured deviation of an agentic workflow from its predicted path — Arco's primary detection mechanism for Context Leakage, with an automatic roll-back triggered at 15% deviation from expected parameters.

## Extended Definition

Execution Divergence is not an error state. It is a continuous measurement — the running comparison between an agentic workflow's actual execution path and the predicted path established at the point of task initiation. Every agentic workflow has a confidence interval: the range of outputs and intermediate states that are consistent with the task's intent. When the workflow drifts outside that interval by more than 15%, the deviation has become large enough that continuing is more dangerous than halting.

## Related Terms

- [Context Leakage](./context-leakage.md) — [Context Leakage on Arco Lexicon](https://arcoventure.studio/lexicon/context-leakage)
- [Deterministic Failure](./deterministic-failure.md) — [Deterministic Failure on Arco Lexicon](https://arcoventure.studio/lexicon/deterministic-failure)
- [MTTI (Mean Time to Intervention)](./mtti.md) — [MTTI (Mean Time to Intervention) on Arco Lexicon](https://arcoventure.studio/lexicon/mtti)
- [Architectural Certainty](./architectural-certainty.md) — [Architectural Certainty on Arco Lexicon](https://arcoventure.studio/lexicon/architectural-certainty)

## In the Log

- [The Mechanics of Failure: Three Things That Break in Autonomous Systems](https://arcoventure.studio/blog/mechanics-of-failure)

## Links

- [Concise entry on Arco Lexicon](https://arcoventure.studio/lexicon/execution-divergence)
- [Autonomous Business Wiki](https://wiki.arcoventure.studio/lexicon/execution-divergence)

---

*First used: 2026-03-20*

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*