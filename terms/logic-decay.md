# Logic Decay

> The failure mode in which agentic logic produces increasingly incorrect outputs not because the code is defective, but because the data environment it was calibrated for has shifted — a miscalibration that compounds silently until it produces a visible error.

## Extended Definition

Logic Decay is the most insidious of the three primary autonomous system failure modes because it is invisible at the point of origin. A software bug is present from deployment and detectable by testing. Logic Decay is introduced by environmental change after deployment: customer behaviour shifts, market pricing moves, an API updates its schema, regulatory parameters change. The logic gate that produced correct outputs in Q1 continues executing in Q3 — against a data environment it was never calibrated for. Each individual output is plausible. The accumulated drift is not. The error compounds until it produces a failure that is impossible to miss, at which point it has typically been running for weeks.

## Related Terms

- [Continuous Regression Loop](https://arcoventure.studio/lexicon/continuous-regression-loop) — The Continuous Regression Loop is the architectural response to Logic Decay: it detects environmental miscalibration through Ghost Trials before the compounding error reaches the revenue loop.
- [Ghost Trial](https://arcoventure.studio/lexicon/ghost-trial) — The Ghost Trial is the detection mechanism for Logic Decay: simulated production data through live logic reveals when the calibration no longer matches the current data environment.
- [Deterministic Failure](https://arcoventure.studio/lexicon/deterministic-failure) — Logic Decay is converted into a Deterministic Failure event when the Continuous Regression Loop detects it: the deviation is flagged, logged, and escalated before it reaches live transactions.
- [Context Leakage](https://arcoventure.studio/lexicon/context-leakage) — Both Logic Decay and Context Leakage produce silent, compounding errors; the distinction is that Logic Decay originates in environmental data drift while Context Leakage originates in task-level intent drift within a single workflow.
- [Architectural Certainty](https://arcoventure.studio/lexicon/architectural-certainty) — Protecting against Logic Decay through Continuous Regression Loops is a design requirement for Architectural Certainty: a system without environmental drift detection cannot maintain reliable autonomous operation over time.
- [Handoff Friction](https://arcoventure.studio/lexicon/handoff-friction) — Both Handoff Friction and Logic Decay produce outputs that appear valid but are incorrect; Handoff Friction occurs at integration boundaries while Logic Decay occurs in the core business logic calibration.

## Articles

- [The Mechanics of Failure: Three Things That Break in Autonomous Systems](https://arcoventure.studio/blog/mechanics-of-failure)

## References

- [Lexicon](https://arcoventure.studio/lexicon/logic-decay) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/logic-decay) — extended entry

## Metadata

first_used: 2026-03-23
pillar: What We've Learned

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
