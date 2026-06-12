# Process Continuity Score (PCS)

> The third axis of the Autonomy Spectrum Framework — the measure of whether a business's workflows run end-to-end without halting for human input, scored 0–2 against the proportion of cross-departmental handoffs that execute without intervention.

## Extended Definition

The Process Continuity Score is the third axis of the Autonomy Spectrum Framework: the measure of whether a business's workflows run end-to-end without halting for human input, scored 0–2 against the proportion of cross-departmental handoffs that execute without intervention. The axis measures whether work flows or waits — it scores the transitions between stages rather than the tasks within them, because the transitions are where autonomy is most commonly lost.

A business can deploy capable agents at every stage of its operation and still halt at every boundary between stages, each handoff requiring a person to notice that one step finished, decide what happens next, and start the following one. PCS makes that condition countable: every transition in the primary workflow is classified as encoded or human-initiated, and the proportion is the score.

A score of 0 indicates that workflow transitions are human-initiated: agents may execute within stages, but a person carries the process between them. A score of 1 indicates continuity within functions but halts at functional boundaries — the workflow runs unattended inside a department and stops at the Coordination Surface between departments. A score of 2 indicates that cross-departmental handoffs execute without human intervention at or above the 80 Percent Threshold, with every transition either encoded in the business's State Machine or deliberately assigned to a person by design.

PCS is the measurable expression of the State Machine principle that every transition is either encoded or human. It is also the axis that exposes the Coordination Trap: a business that accelerates its tasks without encoding its transitions raises its task speed and leaves its process speed unchanged, because the process now waits on humans at every boundary it always waited at.

### Application

In Autonomy Spectrum scoring, PCS is assessed by mapping the Coordination Surface of the primary workflow and counting its transitions: each handoff between functions, systems, or stages is classified as encoded or human-initiated, and the axis score reflects the proportion that execute without a person restarting the process. The 80 Percent Threshold is the boundary between a score of 1 and a score of 2.

## Related Terms

- [State Machine](https://arcoventure.studio/lexicon/state-machine) — The State Machine is the architectural implementation of a high PCS score: every workflow transition is encoded as a deterministic rule rather than requiring human initiation to carry the process between stages.
- [The 80 Percent Threshold](https://arcoventure.studio/lexicon/the-80-percent-threshold) — The 80 Percent Threshold is the boundary between a PCS score of 1 and 2: a business crosses from agent-assisted to genuinely agentic when more than 80% of its cross-departmental handoffs execute without human intervention.
- [Coordination Surface](https://arcoventure.studio/lexicon/coordination-surface) — The Coordination Surface is what PCS scoring maps: every human-to-human handoff point in the workflow is a transition that either adds to the score when encoded or subtracts from it when human-initiated.
- [Suspend/Resume Architecture](https://arcoventure.studio/lexicon/suspend-resume-architecture) — Suspend/Resume Architecture is the infrastructure pattern that enables high PCS scores across long workflows: transitions that require waiting for external signals can be encoded as suspend points rather than human handoffs.

## References

- [Lexicon](https://arcoventure.studio/lexicon/process-continuity-score) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/process-continuity-score) — extended entry

## Metadata

**First used:** 2026-06-12  
**Pillar:** How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
