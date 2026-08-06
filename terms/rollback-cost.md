# Rollback Cost

> The financial and operational cost of reversing an incorrect autonomous action once it is identified — distinct from both MTTI and Recovery Latency, since an intervention can resolve quickly while the cost of undoing what already happened remains substantial, and distinct from Rebuild Tax, which is a one-time structural re-architecture cost rather than a recurring per-incident one.

## Extended Definition

An intervention can resolve quickly and still leave behind an expensive correction. Rollback Cost measures that gap directly: the financial and operational cost of reversing an incorrect autonomous action once it is identified, tracked separately from [Recovery Latency](https://arcoventure.studio/lexicon/recovery-latency), which measures how long the resolution took rather than what it cost. A payment sent to the wrong account, a contract generated with an error, a customer-facing change that has to be walked back — each can have a short Recovery Latency, in the sense that the system stops making the error quickly once flagged, while the cost of undoing what already happened remains substantial.

Rollback Cost is not [Rebuild Tax](https://arcoventure.studio/lexicon/rebuild-tax), and the distinction matters. Rebuild Tax is the one-time, deferred engineering cost of re-architecting a system built under MVP shortcuts once a business reaches meaningful scale — a structural liability accumulated from how the system was originally built. Rollback Cost is a recurring, per-incident operational cost: how expensive it is, this specific time, to reverse this specific error, independent of how the underlying architecture was built.

The metric is also distinct from the reversibility window already established as one of the promotion criteria in [The Last Approval](https://arcoventure.studio/blog/the-last-approval). The reversibility window is a design precondition, evaluated before a decision class is promoted to autonomous operation, confirming decisions in that class can be reversed within a defined period. Rollback Cost is an operational measurement taken after an actual error occurs. A recurring pattern of high Rollback Cost within a single decision class is a signal that the reversibility window may have been set too optimistically at promotion time, or that the class's Deterministic Failure design needs to catch the error earlier.

### Application

Rollback Cost is measured per incident — a payment sent to the wrong account, a contract generated with an error, a customer-facing change requiring reversal — and tracked alongside Recovery Latency for the same failure event, since a short Recovery Latency does not guarantee a low Rollback Cost. A recurring pattern of high Rollback Cost within a single decision class is a signal worth investigating against that class's original promotion criteria, including whether its reversibility window was set too optimistically.

## Related Terms

- [Recovery Latency](https://arcoventure.studio/lexicon/recovery-latency) — Rollback Cost and Recovery Latency are measured together for the same failure event: a fast recovery does not guarantee a cheap one.
- [Rebuild Tax](https://arcoventure.studio/lexicon/rebuild-tax) — Rebuild Tax is a one-time, structural re-architecture liability from MVP-era shortcuts; Rollback Cost is a recurring, per-incident operational cost independent of how the system was originally built.
- [MTTI (Mean Time to Intervention)](https://arcoventure.studio/lexicon/mtti) — A long MTTI says nothing about Rollback Cost — the two measure entirely different dimensions of system reliability, frequency of intervention versus cost of correcting one.
- [Deterministic Failure](https://arcoventure.studio/lexicon/deterministic-failure) — A recurring pattern of high Rollback Cost in one decision class signals that the class's Deterministic Failure design may need to catch the error earlier, before reversal cost accumulates.
- [Authorization Trap](https://arcoventure.studio/lexicon/authorization-trap) — Rollback Cost provides the operational evidence for evaluating whether a decision class's reversibility window, one of the promotion criteria established to resolve the Authorization Trap, was set correctly.
- [Intervention Dependency (ID)](https://arcoventure.studio/lexicon/intervention-dependency) — Intervention Dependency measures how often human input is required; Rollback Cost measures the financial cost of correcting the error that prompted the intervention.

## Articles

- [What MTTI Doesn't Measure](https://arcoventure.studio/blog/what-mtti-doesnt-measure)
- [The Last Approval](https://arcoventure.studio/blog/the-last-approval)
- [The System That Does Not Call](https://arcoventure.studio/blog/the-system-that-does-not-call)

## References

- [Lexicon](https://arcoventure.studio/lexicon/rollback-cost) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/rollback-cost) — extended entry

## Metadata

**First used:** 2026-08-06  
**Pillar:** What We've Learned

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
