# Logic Decay

**Canonical definition (Arco Lexicon)**
> The failure mode in which agentic logic produces increasingly incorrect outputs not because the code is defective, but because the data environment it was calibrated for has shifted — a miscalibration that compounds silently until it produces a visible error.

## Extended Definition

Logic Decay is the most insidious of the three primary autonomous system failure modes because it is invisible at the point of origin. A software bug is present from deployment and detectable by testing. Logic Decay is introduced by environmental change after deployment: customer behaviour shifts, market pricing moves, an API updates its schema, regulatory parameters change. The logic gate that produced correct outputs in Q1 continues executing in Q3 — against a data environment it was never calibrated for. Each individual output is plausible. The accumulated drift is not. The error compounds until it produces a failure that is impossible to miss, at which point it has typically been running for weeks.

## Related Terms

- [Continuous Regression Loop](./continuous-regression-loop.md) — [Continuous Regression Loop on Arco Lexicon](https://arcoventure.studio/lexicon/continuous-regression-loop)
- [Ghost Trial](./ghost-trial.md) — [Ghost Trial on Arco Lexicon](https://arcoventure.studio/lexicon/ghost-trial)
- [Deterministic Failure](./deterministic-failure.md) — [Deterministic Failure on Arco Lexicon](https://arcoventure.studio/lexicon/deterministic-failure)
- [Context Leakage](./context-leakage.md) — [Context Leakage on Arco Lexicon](https://arcoventure.studio/lexicon/context-leakage)
- [Architectural Certainty](./architectural-certainty.md) — [Architectural Certainty on Arco Lexicon](https://arcoventure.studio/lexicon/architectural-certainty)
- [Handoff Friction](./handoff-friction.md) — [Handoff Friction on Arco Lexicon](https://arcoventure.studio/lexicon/handoff-friction)

## In the Log

- [The Mechanics of Failure: Three Things That Break in Autonomous Systems](https://arcoventure.studio/blog/mechanics-of-failure)

## Links

- [Concise entry on Arco Lexicon](https://arcoventure.studio/lexicon/logic-decay)
- [Autonomous Business Wiki](https://wiki.arcoventure.studio/lexicon/logic-decay)

---

*First used: 2026-03-23*

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*