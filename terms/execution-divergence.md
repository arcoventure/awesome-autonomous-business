# Execution Divergence

> The measured deviation of an agentic workflow from its predicted path — Arco's primary detection mechanism for Context Leakage, with an automatic roll-back triggered at 15% deviation from expected parameters.

## Extended Definition

Execution Divergence is not an error state. It is a continuous measurement — the running comparison between an agentic workflow's actual execution path and the predicted path established at the point of task initiation. Every agentic workflow has a confidence interval: the range of outputs and intermediate states that are consistent with the task's intent. When the workflow drifts outside that interval by more than 15%, the deviation has become large enough that continuing is more dangerous than halting.

## Related Terms

- [Context Leakage](https://arcoventure.studio/lexicon/context-leakage) — Execution Divergence is the measurable signal of Context Leakage in progress: accumulated drift in task intent becomes detectable when the workflow's actual path diverges from its predicted path.
- [Deterministic Failure](https://arcoventure.studio/lexicon/deterministic-failure) — When Execution Divergence exceeds 15%, the system transitions to a Deterministic Failure state: halting, logging the full execution context, and escalating to the Steward.
- [MTTI (Mean Time to Intervention)](https://arcoventure.studio/lexicon/mtti) — Execution Divergence detection speed is a direct input to MTTI: a system that catches deviation early halts safely and recovers faster than one that allows drift to compound.
- [Architectural Certainty](https://arcoventure.studio/lexicon/architectural-certainty) — Continuous Execution Divergence monitoring is a design requirement for Architectural Certainty: a system without it cannot detect drift before it produces incorrect outputs at scale.

## Articles

- [The Mechanics of Failure: Three Things That Break in Autonomous Systems](https://arcoventure.studio/blog/mechanics-of-failure)

## References

- [Lexicon](https://arcoventure.studio/lexicon/execution-divergence) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/docs/execution-divergence) — extended entry

## Metadata

first_used: 2026-03-20
pillar: How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
