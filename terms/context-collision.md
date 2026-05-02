# Context Collision

> The failure mode in which two agents operating on different context sets reach contradictory conclusions about the same operational state, producing divergent outputs that propagate through the workflow as if they were correct.

## Extended Definition

Context Collision is distinct from Handoff Friction and Context Leakage. Handoff Friction is a data format problem at system integration points — the receiving agent encounters an unexpected schema. Context Leakage is a within-run failure — the agent loses the intent of the original task as it progresses through a multi-step process. Context Collision is a knowledge continuity problem at agent boundaries: the receiving agent encounters unexpected reasoning, not unexpected data. It cannot validate what it has received because the upstream agent did not encode why it made the decisions it made — only what those decisions were.

The divergence propagates silently because both agents are operating correctly within their respective context sets. Neither has made an error by the rules of its own knowledge layer. The collision is visible only in the output — two branches of a multi-agent workflow producing contradictory results about the same operational state — and only if the system has audit infrastructure capable of tracing the divergence back to its origin. Without Proof of Action logs covering all agents in the chain, Context Collision manifests as an unexplained inconsistency whose source is structurally invisible.

## Related Terms

- [Handoff Friction](https://arcoventure.studio/lexicon/handoff-friction) — Handoff Friction is the data format failure at integration points, while Context Collision is the reasoning failure at agent boundaries — both propagate silently but through different mechanisms.
- [Context Leakage](https://arcoventure.studio/lexicon/context-leakage) — Context Leakage is a within-run failure where a single agent drifts from the original intent; Context Collision is a cross-agent failure where two agents produce contradictory conclusions from different context sets.
- [Proof of Action](https://arcoventure.studio/lexicon/proof-of-action) — Proof of Action logs covering all agents in the chain are the primary detection mechanism for Context Collision, providing the audit trail required to trace divergent outputs back to their origin.
- [Knowledge Debt](https://arcoventure.studio/lexicon/knowledge-debt) — Knowledge Debt is the structural condition that makes Context Collision more likely: when the operational knowledge layer is unstructured or unversioned, agents operating on different snapshots of it will produce divergent conclusions.

## Articles

- [Agent Memory Is Not Chat History](https://arcoventure.studio/blog/agent-memory-is-not-chat-history)
- [Auditable Autonomy: Solving the Black Box Problem](https://arcoventure.studio/blog/auditable-autonomy)

## References

- [Lexicon](https://arcoventure.studio/lexicon/context-collision) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/context-collision) — extended entry

## Metadata

**First used:** 2026-05-02  
**Pillar:** How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
