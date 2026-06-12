# Decision Execution Autonomy (DEA)

> The second axis of the Autonomy Spectrum Framework — the proportion of a business's operational decisions made by encoded logic rather than human judgment, scored 0–2 against who decides how work is routed, prioritised, escalated, and resolved.

## Extended Definition

Decision Execution Autonomy is the second axis of the Autonomy Spectrum Framework: the proportion of a business's operational decisions made by encoded logic rather than human judgment, scored 0–2 against who decides how work is routed, prioritised, escalated, and resolved. The axis measures who decides, not who executes — the continuous, high-frequency stream of operational determinations that keep a business moving, distinct from both strategic judgment and task execution.

Every operation contains that stream whether or not it has named it: which task runs next, which exception escalates, which resource is allocated, which case closes. DEA scores the proportion of the stream resolved by encoded logic operating within designed parameters rather than by a person exercising judgment in the moment.

A score of 0 indicates that people make the operational decisions, with systems informing them — dashboards, recommendations, alerts that a human acts on. A score of 1 indicates that encoded logic decides within bounded domains, but people retain approval authority over decisions the logic has already made, reviewing and confirming rather than deciding. A score of 2 indicates that operational decisions are made by encoded logic within designed Intervention Thresholds, with human judgment reserved for the Judgment Layer — the decision classes the architecture deliberately assigns to the Steward.

DEA is where automation and autonomy diverge. A business can score 2 on Task Execution Autonomy while every routing and escalation decision still passes through a person; that business has automated its execution and kept its decision-making human, which is the definition of an Automated Business. The approval bottleneck is the signature of a low DEA score: when logic decides and a human confirms, the decision has not been transferred — only its preparation has.

### Application

In Autonomy Spectrum scoring, DEA is assessed against the decision inventory of the operation: routing, prioritisation, exception classification, escalation, and resource allocation. Each decision class is scored on whether encoded logic resolves it within a designed Intervention Threshold or whether a person resolves it, and the axis score reflects the share of operational decision volume owned by the logic.

## Related Terms

- [Judgment Layer / Execution Layer](https://arcoventure.studio/lexicon/judgment-layer-execution-layer) — DEA scores the proportion of operational decisions that the Execution Layer owns; the Judgment Layer is the residual category the architecture deliberately assigns to the Steward.
- [Intervention Threshold](https://arcoventure.studio/lexicon/intervention-threshold) — The Intervention Threshold is the design parameter that determines DEA: it specifies the conditions under which encoded logic must halt and surface a decision to the Steward rather than resolving it autonomously.
- [State Machine](https://arcoventure.studio/lexicon/state-machine) — The State Machine is the architectural implementation of high DEA: every routing, prioritisation, and escalation decision is encoded as a state transition that the logic resolves without human initiation.
- [Exception Architecture](https://arcoventure.studio/lexicon/exception-architecture) — Exception Architecture governs the decision classes that fall below the DEA score: it specifies which operational states the logic cannot resolve and must escalate to the Steward.

## References

- [Lexicon](https://arcoventure.studio/lexicon/decision-execution-autonomy) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/decision-execution-autonomy) — extended entry

## Metadata

**First used:** 2026-06-12  
**Pillar:** How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
