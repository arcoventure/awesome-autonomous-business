# Physical Intervention Threshold

> An Intervention Threshold calibrated by the reversibility of an action rather than by frequency alone — set by the cost of a single wrong action, not how often it occurs.

## Extended Definition

Frequency and severity are not the same axis, and a threshold scored on frequency alone cannot tell two very different tasks apart. A task can carry a low Escalation Rate and a near-zero Rollback Cost — a wrongly categorised support ticket, reissued in seconds — or the identical Escalation Rate and a severe Rollback Cost — a produced batch that cannot be recalled, a reagent that cannot be un-mixed. Both clear the same 1:100 target. The Physical Intervention Threshold separates them by taking reversibility, not frequency, as the variable that sets how tightly a class of action is gated. It does not replace the standard Intervention Threshold; it adds the second axis the standard threshold assumes away.

This is not the Authorization Trap restated. The Authorization Trap describes an operator's reluctance to remove an approval gate that no longer serves a function — a failure to complete a design that was already correct. The Physical Intervention Threshold describes a gate that should not be removed, because the task's Rollback Cost, not the operator's confidence, is what sets the requirement. A high intervention rate on a narrow class of physically consequential action is not a shortfall against a T1 target. It is the correct number once reversibility, not frequency, is the variable being scored.

The term applies most directly wherever an agent's decisions produce physical consequences — committing production capacity, executing a hardware action, releasing a shipment — but the underlying logic is not limited to physical tasks. An irreversible database migration or a filed legal document carries the same profile. Any action whose reversal is expensive or impossible, digital or physical, should be gated by its Rollback Cost rather than by how rarely the agent encounters it.

### Application

Score every task class on two axes before assigning a threshold: its Escalation Rate under the standard frequency model, and its Rollback Cost if a single execution is wrong. A task with a high Rollback Cost gets a tight threshold regardless of what its Escalation Rate alone would imply — the threshold is set by the more restrictive of the two axes, not averaged between them.

### Context

Arco's standard Intervention Threshold is measured by frequency: roughly one escalation per hundred executions at T1. Reversibility already enters the model at two points — as the risk profile that mandates human involvement at T3, and as the reversibility window that gates removal of an approval step under the Authorization Trap — but it is not a continuous calibration input across every tier. That gap is invisible for most digital work, where reversal cost is low and roughly uniform, and it becomes the deciding variable for actions that cannot be cheaply undone.

## Related Terms

- [Intervention Threshold](https://arcoventure.studio/lexicon/intervention-threshold) — The Physical Intervention Threshold does not replace the standard, frequency-based Intervention Threshold; it adds the reversibility axis the standard threshold assumes away.
- [Rollback Cost](https://arcoventure.studio/lexicon/rollback-cost) — The Physical Intervention Threshold is calibrated by an action's Rollback Cost rather than by how often the action occurs.
- [Escalation Rate](https://arcoventure.studio/lexicon/escalation-rate) — Every task class is scored on two axes before a threshold is assigned: its Escalation Rate under the standard frequency model, and its Rollback Cost, with the more restrictive of the two setting the Physical Intervention Threshold.
- [Stewardship Model](https://arcoventure.studio/lexicon/stewardship-model) — The Stewardship Model defines the human role that the Physical Intervention Threshold's tightest gates route to for actions with severe Rollback Cost.
- [Authorization Trap](https://arcoventure.studio/lexicon/authorization-trap) — The Physical Intervention Threshold is not the Authorization Trap restated: the Authorization Trap describes an unnecessary approval gate an operator is reluctant to remove, while the Physical Intervention Threshold describes a gate that should not be removed because the task's Rollback Cost sets the requirement.
- [Task Tiers (T1 / T2 / T3)](https://arcoventure.studio/lexicon/t1-t2-t3) — Reversibility already enters Arco's model at T3, where the risk profile mandates human involvement; the Physical Intervention Threshold extends that reversibility logic into a continuous calibration input across every tier.

## Articles

- [What MTTI Doesn't Measure](https://arcoventure.studio/blog/what-mtti-doesnt-measure)
- [The Last Approval](https://arcoventure.studio/blog/the-last-approval)
- [The Stewardship Model: The Human Role in an Autonomous Business](https://arcoventure.studio/blog/stewardship-model)
- [MHS Collapses Hardware Friction, Not Judgment](https://arcoventure.studio/blog/anthropic-mhs-collapses-friction-not-judgment)

## References

- [Lexicon](https://arcoventure.studio/lexicon/physical-intervention-threshold) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/physical-intervention-threshold) — extended entry

## Metadata

**First used:** 2026-09-01  
**Pillar:** How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
