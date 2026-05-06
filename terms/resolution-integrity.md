# Resolution Integrity

> The proportion of agentic ticket closures that do not reopen, do not resurface as repeat contacts within a defined observation window, and do not propagate downstream as exceptions or rework — Arco's quality metric for distinguishing genuine first-contact resolution from mere ticket-closure containment, and the discipline that makes agentic FCR comparable to human FCR rather than artificially inflated by ticket-handling artefacts.

## Extended Definition

Resolution Integrity is the operational test that separates a closed ticket from a resolved one. An agentic system can post any First Contact Resolution rate it likes by closing conversations regardless of whether the underlying issue was actually resolved; the apparent throughput gain disappears once the customer reopens, contacts again under a different ticket number, or surfaces the same problem downstream as an exception. Resolution Integrity measures the durability of the resolution rather than the act of closure.

The metric is calculated over a fixed observation window — typically 7 to 30 days for B2B SaaS, longer for transactional categories — and counts a closure as integrity-positive only if the customer does not return with the same issue, the ticket does not reopen, and no downstream system records a related exception. The window is set by the business, not by the platform, because the relevant horizon is the customer's perception of resolution, not the agent's classification of it.

The metric exists because agentic FCR and human FCR are not directly comparable. Human agents close tickets under social and operational pressure that pushes against premature closure: customers escalate, supervisors review, and the agent's reopen rate is visible to their team. Agentic systems close tickets under the pressure of a metric they were optimised against, with no equivalent feedback loop unless one is engineered. Resolution Integrity engineers that feedback loop directly into the operational ledger, making the agentic FCR claim verifiable rather than self-reported.

Under the Stewardship Model, Resolution Integrity is the quality metric the Steward governs. Raw FCR can be optimised by closure-aggressive routing; Resolution Integrity can only be optimised by getting the answer right. When the two metrics diverge, the divergence is the diagnostic: a high FCR with low Resolution Integrity is the signature of Containment Theatre — the system is closing tickets without resolving issues.

## Related Terms

- [Escalation Rate](https://arcoventure.studio/lexicon/escalation-rate) — Resolution Integrity provides the quality dimension that complements Escalation Rate: a low escalation rate is only meaningful if the resolutions produced without escalation are durable rather than containment closures.
- [Intervention Threshold](https://arcoventure.studio/lexicon/intervention-threshold) — Resolution Integrity informs Intervention Threshold calibration: when closure rates are high but integrity is low, the threshold for autonomous resolution should be raised to require Steward review before closure.
- [Proof of Action](https://arcoventure.studio/lexicon/proof-of-action) — Proof of Action logs provide the audit trail that makes Resolution Integrity measurable: the structured record of each closure and its downstream outcome is the evidence base for the integrity calculation.
- [Stewardship Model](https://arcoventure.studio/lexicon/stewardship-model) — Under the Stewardship Model, Resolution Integrity is the primary quality metric the Steward governs, distinguishing genuine resolution from closure-aggressive routing that inflates FCR without solving the underlying issue.
- [Task Tiers (T1 / T2 / T3)](https://arcoventure.studio/lexicon/t1-t2-t3) — Resolution Integrity targets vary by task tier: T1 closures at 1:100 escalation require near-perfect integrity, while T2 and T3 resolutions involve the Steward precisely because their complexity makes autonomous closure integrity harder to guarantee.
- [Deterministic Logging](https://arcoventure.studio/lexicon/deterministic-logging) — Deterministic Logging is the technical foundation for Resolution Integrity measurement: recording the specific conditions of each closure, including downstream exception propagation, makes the observation window calculation auditable.

## References

- [Lexicon](https://arcoventure.studio/lexicon/resolution-integrity) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/resolution-integrity) — extended entry

## Metadata

**First used:** 2026-05-05  
**Pillar:** How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
