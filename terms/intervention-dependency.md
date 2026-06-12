# Intervention Dependency (ID)

> The fourth axis of the Autonomy Spectrum Framework — the frequency with which a business's core systems require human intervention to continue operating, scored 0–2 and operationally expressed through MTTI and Escalation Rate as the inverse measure of Architectural Certainty.

## Extended Definition

Intervention Dependency is the fourth axis of the Autonomy Spectrum Framework: the frequency with which a business's core systems require human intervention to continue operating, scored 0–2 and operationally expressed through MTTI and the Escalation Rate. The axis is the inverse measure of Architectural Certainty — where the first three axes score the architecture, ID scores the observed operational result: how long the system actually runs before it needs a person.

An intervention counts toward the axis when the system could not continue correctly without it — an exception above the Intervention Threshold, a halt the architecture itself triggered. A Steward who voluntarily inspects, tunes, or improves a running system has not intervened in the scored sense. The axis is read from two instruments because they catch different failure shapes: MTTI measures the rhythm of dependency over time, and the Escalation Rate measures the proportion of agentic task executions that require a person.

A score of 0 indicates continuous steering: the system requires human input multiple times per day, and the people operating it are functionally part of the execution path regardless of how the architecture is described. A score of 1 indicates scheduled or frequent intervention — the system runs unattended for hours but not days, and intervention is routine rather than exceptional. A score of 2 indicates that MTTI on the core revenue loops exceeds 72 hours and intervention occurs by exception only, at the conditions the Intervention Threshold was designed to surface.

The axis carries one validation requirement that the others do not. A long MTTI is evidence of autonomy only when the Steward is actively engaging with the Audit Surface; the same number produced by a Steward who has stopped watching is Nominal MTTI — a metric that confirms autonomous operation while the system runs unmonitored. ID is therefore always scored as a pair: the intervention frequency, and the proof that someone was in a position to intervene.

### Application

In Autonomy Spectrum scoring, ID is assessed through MTTI on the core revenue loops and the Escalation Rate of agentic task executions, validated against an active Audit Surface: an Intervention Dependency score is valid only when the Steward is demonstrably engaging with the governance digest, because an unmonitored system produces a long MTTI that measures absence rather than autonomy.

## Related Terms

- [MTTI (Mean Time to Intervention)](https://arcoventure.studio/lexicon/mtti) — MTTI is the primary instrument through which Intervention Dependency is measured: the average time between required human interventions is the operational expression of the axis score.
- [Escalation Rate](https://arcoventure.studio/lexicon/escalation-rate) — Escalation Rate is the second instrument: it measures the proportion of task executions that require human judgment, catching the dependency that MTTI misses when intervention is frequent but brief.
- [Architectural Certainty](https://arcoventure.studio/lexicon/architectural-certainty) — Intervention Dependency is the inverse measure of Architectural Certainty: a score of 2 on ID is the operational confirmation that the architecture has achieved the state where core operations run without human decisions for 72 hours or more.
- [Intervention Threshold](https://arcoventure.studio/lexicon/intervention-threshold) — The Intervention Threshold is the design parameter that determines the ID score: it specifies the conditions under which the system must halt and surface a decision, and the precision of that specification determines how rarely those conditions are met.
- [Nominal MTTI](https://arcoventure.studio/lexicon/nominal-mtti) — Nominal MTTI is the failure mode that the ID validation requirement is designed to prevent: a long MTTI produced by a Steward who has stopped engaging with the Audit Surface is not evidence of a high ID score.
- [Audit Surface](https://arcoventure.studio/lexicon/audit-surface) — The Audit Surface is the governance instrument that validates the ID score: an Intervention Dependency assessment is only valid when the Steward is demonstrably engaging with the governance digest.

## References

- [Lexicon](https://arcoventure.studio/lexicon/intervention-dependency) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/intervention-dependency) — extended entry

## Metadata

**First used:** 2026-06-12  
**Pillar:** How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
