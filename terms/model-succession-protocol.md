# Model Succession Protocol

> The discipline that replaces the reflexive model upgrade with a measured one: before promoting a candidate model into the active set, replay the historical backlog of validated, already-promoted work through the candidate, and measure the delta against the current model's established baseline before deciding anything.

## Extended Definition

The reflexive response to a new model release — upgrade the active set to the newest version because it is available — assumes the new model interprets accumulated business context the same way the outgoing model did. Interpretation Drift specifically denies that assumption: identical inputs, read by a different model, do not always mean the same thing. Model Succession Protocol is the discipline that closes this gap before it reaches production, by testing the candidate against evidence rather than assuming continuity.

The comparison this protocol runs is deliberately retrospective, not live. Model Quorum evaluates multiple models against a current task in real time, comparing their outputs against an answer nobody yet knows. Model Succession Protocol instead replays a candidate model against the business's own validated, already-promoted historical record — work whose correct outcome is already established — and measures how closely the candidate reproduces it. This is a stronger test for a succession decision specifically, because it checks the candidate against ground truth the business has already confirmed, not against an unknown it shares with every other evaluator.

The delta this comparison produces is the actual decision input, and it should be treated as a spectrum rather than a pass-fail gate. A candidate that reproduces validated outcomes closely across the board is a reasonable, evidence-backed migration. A candidate that diverges only on specific decision classes supports a segmented promotion — migrating where the evidence favours it, holding the outgoing model where it does not — rather than forcing a single all-or-nothing switch. Only once the delta genuinely favours migration does the candidate earn a warm-up period: iterative re-exposure to the same validated record, deliberately restricted to work the business has confirmed as correct, so the warm-up reinforces validated patterns rather than any of the outgoing model's unconfirmed history.

### Application

The sequence runs in order: a new model releases; the business does not upgrade by reflex; the candidate is tested against the validated historical backlog and the delta is measured against the current model's baseline; only a favourable delta earns the candidate a warm-up period — iterative re-exposure to the same validated record — before it takes over the live model set entirely. If the delta is mixed, the correct response is often segmented rather than binary: promote the candidate for the decision classes where it outperforms, and hold the outgoing model in place for the classes where it diverges unfavourably, rather than forcing an all-or-nothing switch.

### Context

Model Succession Protocol is deliberately distinguished from Model Quorum. Model Quorum runs multiple models against a live task in parallel, in real time, comparing outputs against an unknown answer to catch what a single model would miss right now. Model Succession Protocol runs a single candidate against a fixed, historical record of work the business has already validated and promoted — a retrospective comparison against a known-good outcome, not a live comparison against uncertainty. The two share the same independent-evaluation discipline in opposite temporal directions: one forward-looking, one backward-looking. This protocol exists specifically to catch Interpretation Drift — the risk that a new model reads the exact same validated inputs differently than the model it would replace — before that divergence reaches production rather than after.

## Related Terms

- [Interpretation Drift](https://arcoventure.studio/lexicon/interpretation-drift) — Model Succession Protocol exists specifically to catch Interpretation Drift before a candidate model's different reading of validated context reaches production.
- [Model Quorum](https://arcoventure.studio/lexicon/model-quorum) — Model Quorum evaluates multiple models against a live task in parallel; Model Succession Protocol evaluates a single candidate against a historical validated record — one forward-looking, one backward-looking.
- [Logic Decay](https://arcoventure.studio/lexicon/logic-decay) — Model Succession Protocol's retrospective replay of validated work also surfaces Logic Decay — cases where the outgoing model's logic was calibrated for a data environment that has since shifted.
- [Deterministic Outcome](https://arcoventure.studio/lexicon/deterministic-outcome) — Model Succession Protocol measures a candidate model's ability to reproduce Deterministic Outcomes the business has already confirmed, making the succession decision evidence-based rather than assumption-based.
- [Rebuild Tax](https://arcoventure.studio/lexicon/rebuild-tax) — Model Succession Protocol is the discipline that prevents a reflexive model upgrade from incurring Rebuild Tax by catching divergence before it ships rather than after.

## Articles

- [Don't Upgrade Just Because You Can](https://arcoventure.studio/blog/dont-upgrade-just-because-you-can)
- [Why One Model Isn't Enough to Trust](https://arcoventure.studio/blog/why-one-model-isnt-enough-to-trust)
- [Two Kinds of Redundancy](https://arcoventure.studio/blog/two-kinds-of-redundancy)

## References

- [Lexicon](https://arcoventure.studio/lexicon/model-succession-protocol) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/model-succession-protocol) — extended entry

## Metadata

**First used:** 2026-07-30  
**Pillar:** How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
