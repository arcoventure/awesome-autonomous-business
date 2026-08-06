# Recovery Latency

> The time from failure detection to restored autonomous operation — distinct from MTTI, which measures the average interval between required interventions rather than the duration of resolving any single one.

## Extended Definition

MTTI (Mean Time to Intervention measures the average time between required human interventions in an agentic system — how rarely the system needs help. It was never designed to measure, and does not measure, what happens during any single intervention once it occurs. Recovery Latency closes that gap: it is the time from failure detection to restored autonomous operation, capturing how well the system performs at the specific moment MTTI's interval-based measurement cannot see.

The measurement depends directly on Deterministic Failure — the architectural standard that a failure must be predictable, fully logged, and recoverable by design, so that when the system breaks, it breaks safely. Deterministic Failure specifies the design requirement; Recovery Latency measures whether that design is actually producing fast recovery in operation, rather than only confirming the failure was logged correctly.

A business can have an excellent MTTI and a poor Recovery Latency simultaneously — long, quiet stretches between interventions that create an appearance of reliability, followed by a slow, expensive recovery the moment an intervention is actually required. This is a distinct honesty check from the one Nominal MTTI performs: Nominal MTTI asks whether a long interval reflects genuine reliability or an unmonitored system; Recovery Latency asks a question that remains open even when MTTI is genuinely earned.

### Application

Recovery Latency is measured from the moment a Deterministic Failure event is logged to the moment autonomous operation genuinely resumes, not simply the moment the Steward acknowledges the alert. It supplements the Intervention Dependency axis as an operational check on whether the Deterministic Failure design standard is actually producing fast recovery in practice, rather than only confirming that a failure was logged correctly when it occurred.

## Related Terms

- [MTTI (Mean Time to Intervention)](https://arcoventure.studio/lexicon/mtti) — Recovery Latency closes the gap MTTI leaves open, measuring the duration of resolving any single intervention rather than the average interval between them.
- [Deterministic Failure](https://arcoventure.studio/lexicon/deterministic-failure) — Deterministic Failure specifies the design requirement that a failure must be predictable and recoverable; Recovery Latency measures whether that requirement is producing fast recovery in practice.
- [Intervention Dependency (ID)](https://arcoventure.studio/lexicon/intervention-dependency) — Recovery Latency supplements the Intervention Dependency axis as an operational check on whether the Deterministic Failure design standard is producing fast recovery, not only confirming failures were logged correctly.
- [Nominal MTTI](https://arcoventure.studio/lexicon/nominal-mtti) — Recovery Latency and Nominal MTTI ask distinct honesty checks: Nominal MTTI asks whether a long interval reflects genuine reliability, while Recovery Latency asks whether recovery is fast once an intervention is actually required.
- [Autonomy Spectrum Framework](https://arcoventure.studio/lexicon/autonomy-spectrum-framework) — Recovery Latency is an operational measurement within the Autonomy Spectrum Framework, capturing how the system performs at the moment MTTI's interval-based measurement cannot see.

## Articles

- [What MTTI Doesn't Measure](https://arcoventure.studio/blog/what-mtti-doesnt-measure)
- [The System That Does Not Call](https://arcoventure.studio/blog/the-system-that-does-not-call)
- [The Metric That Lies](https://arcoventure.studio/blog/the-metric-that-lies)

## References

- [Lexicon](https://arcoventure.studio/lexicon/recovery-latency) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/recovery-latency) — extended entry

## Metadata

**First used:** 2026-08-06  
**Pillar:** What We've Learned

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
