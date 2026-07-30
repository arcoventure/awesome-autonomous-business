# Interpretation Drift

> The failure mode in which identical inputs — the same context, the same files, the same instructions — are interpreted differently by a new model version than by the model previously validated against them, independent of any change in the underlying data environment.

## Extended Definition

The natural response to a new model release is to upgrade the active model set on the assumption that newer is better and the switch is close to free. Interpretation Drift is the specific risk that assumption ignores: a new model reading the exact same validated file can reasonably reach a different judgment call, a different tone, a different edge-case handling — not because anything decayed, but because a different model is, structurally, a different reader of the same material.

This is precisely the mirror case to Logic Decay. Logic Decay names code that is fine while the data environment it was calibrated for shifts underneath it — the model stays constant, the world changes. Interpretation Drift holds the data and context constant and changes the model instead. Both produce the same silent, compounding character: a system that still runs, still returns outputs, and has quietly stopped matching what was validated and promoted, with no error thrown to announce the gap.

The risk is caught the same way any silent drift is caught in this body of work — not by waiting for a visible failure, but by deliberately testing for it. Model Succession Protocol is the specific discipline that replaces the reflexive model-set upgrade with a measured one, replaying the historical backlog of validated work through a candidate model before any promotion decision is made.

### Application

Interpretation Drift shows up in the places that matter most and are hardest to notice quickly: an Agent Council that suddenly applies a subtly different quality bar, a workflow that has always resolved a specific edge case one way and now resolves it differently with no error thrown, a tone or judgment call that shifts in a way no test suite was written to catch because the previous model's behaviour was the implicit specification. None of this necessarily produces a visible failure — the system still runs and still returns outputs while quietly no longer matching what was validated and promoted.

### Context

Interpretation Drift is distinct from Logic Decay, which names the opposite mechanism: stable logic reading a data environment that has shifted underneath it, the code unchanged while the world changes. Interpretation Drift holds the data constant and changes the interpreter — the world stays the same, and what changes is the model itself, deliberately swapped for a newer version. It is also distinct from the ordinary machine-learning use of the term 'model drift,' which typically describes a model's performance degrading as real-world data diverges from its training distribution, closer to what Logic Decay already covers in this body of work. Both share a silent, compounding character, but originate from opposite directions.

## Related Terms

- [Logic Decay](https://arcoventure.studio/lexicon/logic-decay) — Interpretation Drift and Logic Decay are mirror failure modes — Logic Decay holds the model constant while the data shifts, while Interpretation Drift holds the data constant and changes the model instead.
- [Model Quorum](https://arcoventure.studio/lexicon/model-quorum) — Model Quorum is the real-time defence against Interpretation Drift's close-range cousin — divergent outputs from multiple independent models on the same live task reveal the ambiguity a single model would resolve silently.
- [Deterministic Outcome](https://arcoventure.studio/lexicon/deterministic-outcome) — Interpretation Drift is most consequential where Deterministic Outcomes are expected, because silent divergence in model interpretation produces undetected variance in what should be a verifiable result.
- [Agent Council](https://arcoventure.studio/lexicon/agent-council) — Interpretation Drift is most visible in the Agent Council, where a model swap can shift the quality bar, tone, or edge-case handling across every council judgment without any error being thrown.
- [Rebuild Tax](https://arcoventure.studio/lexicon/rebuild-tax) — Undetected Interpretation Drift that reaches production eventually manifests as Rebuild Tax — the cost of correcting a divergence that accumulated silently rather than being caught by Model Succession Protocol.

## Articles

- [Don't Upgrade Just Because You Can](https://arcoventure.studio/blog/dont-upgrade-just-because-you-can)
- [The Business That Forgets Nothing](https://arcoventure.studio/blog/the-business-that-forgets-nothing)
- [Why One Model Isn't Enough to Trust](https://arcoventure.studio/blog/why-one-model-isnt-enough-to-trust)

## References

- [Lexicon](https://arcoventure.studio/lexicon/interpretation-drift) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/interpretation-drift) — extended entry

## Metadata

**First used:** 2026-07-30  
**Pillar:** What We've Learned

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
