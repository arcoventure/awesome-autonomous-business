# Nominal MTTI

> The condition in which a system's measured Mean Time to Intervention is long not because it has achieved genuine Architectural Certainty but because the Steward has stopped engaging with the audit surface — producing a metric that appears to confirm autonomous operation while the system is in fact running unmonitored and unrefined.

## Extended Definition

MTTI measures the frequency of required human interventions in an agentic system. It cannot measure whether the absence of intervention reflects system health or Steward withdrawal. These two states are observationally identical: both report long MTTI, both show low Escalation Rates, and both appear from the outside to confirm that the system is governing itself correctly. Nominal MTTI names the failure mode that the MTTI metric cannot detect on its own.

The mechanism is cognitive arithmetic rather than negligence. A Steward governing an autonomous business at production volume must review the Proof of Action trail, validate exception resolutions, confirm Escalation Rate stability across task classes, and identify leading indicators of Knowledge Debt accumulation — rising Escalation Rates for specific exception classes, narrowing MTTI segments, Execution Divergence patterns that signal context drift. The complete Proof of Action trail contains all of this information. When the cognitive cost of reviewing that trail exceeds the Steward's available attention budget, the Steward stops reviewing it — not negligently but practically. No interventions surface because nothing is surfacing them. The MTTI appears to extend because the governance that would measure it has quietly withdrawn.

The diagnostic implication is direct: long MTTI is a necessary but not sufficient condition for Architectural Certainty. The sufficient condition requires confirmation that the Steward is actively monitoring the audit surface, that recent exception resolutions are consistent with the Intervention Threshold parameters, and that no Execution Divergence patterns are accumulating undetected. The distinction between genuine and Nominal MTTI is not observable in the MTTI metric. It is observable only in the presence and quality of Steward engagement with the system's governance surface.

## Related Terms

- [MTTI (Mean Time to Intervention)](https://arcoventure.studio/lexicon/mtti) — Nominal MTTI is the failure mode that the MTTI metric cannot distinguish from genuine Architectural Certainty: both conditions produce the same measured output while representing structurally opposite operational states.
- [Architectural Certainty](https://arcoventure.studio/lexicon/architectural-certainty) — Nominal MTTI is the false positive of Architectural Certainty: the system appears to be governing itself correctly while the governance that would detect failures has quietly withdrawn.
- [Proof of Action](https://arcoventure.studio/lexicon/proof-of-action) — The Proof of Action trail is the information source whose cognitive cost produces Nominal MTTI: when the trail is too dense for a Steward to review at operational tempo, the Steward stops reviewing it and the metric becomes nominal.
- [Stewardship Model](https://arcoventure.studio/lexicon/stewardship-model) — Nominal MTTI is the failure mode of the Stewardship Model at scale: the Steward remains in place but has withdrawn from active governance because the governance surface is not designed for operational tempo.
- [Intervention Threshold](https://arcoventure.studio/lexicon/intervention-threshold) — Nominal MTTI produces an invisible Intervention Threshold failure: conditions that should surface to the Steward do not, because the review mechanism that would detect them has gone inactive.
- [Escalation Rate](https://arcoventure.studio/lexicon/escalation-rate) — Low Escalation Rates are a false signal of health in Nominal MTTI conditions: the rate appears to confirm autonomous operation while the Steward's withdrawal means no review is occurring to detect exceptions that should be escalating.
- [Knowledge Debt](https://arcoventure.studio/lexicon/knowledge-debt) — Nominal MTTI is the condition under which Knowledge Debt compounds fastest: without active Steward engagement, resolved exceptions are not encoded into the Operational Ledger, and the system's context quality stagnates.
- [Exception Architecture](https://arcoventure.studio/lexicon/exception-architecture) — Exception Architecture cannot function in Nominal MTTI conditions: the exception routing protocol requires Steward engagement to update the Operational Ledger and refine the Intervention Threshold.
- [Execution Divergence](https://arcoventure.studio/lexicon/execution-divergence) — Execution Divergence patterns accumulate undetected in Nominal MTTI: without active review of the governance surface, the leading indicators of context drift are invisible until they produce a visible failure.
- [Audit Surface](https://arcoventure.studio/lexicon/audit-surface) — The Audit Surface is the architectural solution to Nominal MTTI: a compressed, exception-flagged governance digest designed for operational tempo makes active Steward engagement sustainable rather than cognitively prohibitive.

## Articles

- [Auditable Autonomy: Solving the Black Box Problem](https://arcoventure.studio/blog/auditable-autonomy)
- [What Does an Operator Do in an Autonomous Business?](https://arcoventure.studio/blog/what-does-an-operator-do)
- [The Stewardship Model: The Human Role in an Autonomous Business](https://arcoventure.studio/blog/stewardship-model)
- [The Audit Surface Problem](https://arcoventure.studio/blog/the-audit-surface-problem)

## References

- [Lexicon](https://arcoventure.studio/lexicon/nominal-mtti) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/nominal-mtti) — extended entry

## Metadata

**First used:** 2026-05-11  
**Pillar:** How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
