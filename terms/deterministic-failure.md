# Deterministic Failure

**Canonical definition (Arco Lexicon)**
> A failure mode that is predictable, fully logged, and recoverable by design — the architectural standard Arco engineers into every autonomous system so that when the system breaks, it breaks safely.

## Extended Definition

Deterministic Failure is the opposite of a black box failure. In a non-deterministic system, a failure produces damage and then silence — the operator discovers the failure after the fact, reconstructs what happened through incomplete logs and human testimony, and hopes to prevent recurrence through vigilance. In a deterministic system, failure follows a defined protocol: the workflow halts at the point of deviation, the full execution context is logged — the specific logic gate, the input data, the confidence score, the deviation measurement — the recovery mechanism is triggered automatically, and the Steward is notified with enough information to update the architecture before the workflow resumes.

## Related Terms

- [Architectural Certainty](./architectural-certainty.md) — [Architectural Certainty on Arco Lexicon](https://arcoventure.studio/lexicon/architectural-certainty)
- [Execution Divergence](./execution-divergence.md) — [Execution Divergence on Arco Lexicon](https://arcoventure.studio/lexicon/execution-divergence)
- [Context Leakage](./context-leakage.md) — [Context Leakage on Arco Lexicon](https://arcoventure.studio/lexicon/context-leakage)
- [Continuous Regression Loop](./continuous-regression-loop.md) — [Continuous Regression Loop on Arco Lexicon](https://arcoventure.studio/lexicon/continuous-regression-loop)
- [MTTI (Mean Time to Intervention)](./mtti.md) — [MTTI (Mean Time to Intervention) on Arco Lexicon](https://arcoventure.studio/lexicon/mtti)
- [Stewardship Model](./stewardship-model.md) — [Stewardship Model on Arco Lexicon](https://arcoventure.studio/lexicon/stewardship-model)

## In the Log

- [The Mechanics of Failure: Three Things That Break in Autonomous Systems](https://arcoventure.studio/blog/mechanics-of-failure)

## Links

- [Concise entry on Arco Lexicon](https://arcoventure.studio/lexicon/deterministic-failure)
- [Autonomous Business Wiki](https://wiki.arcoventure.studio/lexicon/deterministic-failure)

---

*First used: 2026-03-20*

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*