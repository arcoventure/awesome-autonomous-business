# Disclosure Threshold

> The point in a customer interaction, determined by the consequentiality of the decision rather than the channel it occurs on, at which failing to disclose autonomous operation becomes a trust liability rather than a neutral design choice.

## Extended Definition

The Disclosure Threshold rejects both a blanket disclose-everything rule and a blanket disclose-nothing default, replacing either with a specific, testable standard: consequentiality, not channel or convenience, determines whether concealment is a neutral omission or a trust violation. A customer whose password was reset correctly has received exactly what they wanted regardless of who performed the reset; a customer disputing a charge is implicitly trusting that a reasonable, accountable process produced the outcome, and concealing that no human weighed their specific circumstances withholds information they would reasonably want.

The risk asymmetry is the strongest argument for a fixed position rather than a live judgment call. Low-consequence concealment discovered later costs little. High-consequence concealment discovered later compounds specifically because the stakes were real — the customer does not just learn they spoke to an agent, they learn the business let them believe a person had reviewed their case at exactly the moment that belief mattered most. This connects to the same discipline Redundancy Dividend applies to untested reliability claims: a belief discovered false at the worst possible moment is worse than no belief at all.

The Disclosure Threshold shares its classification work with Deterministic Outcome designation: a decision class verified as producing a Deterministic Outcome typically sits below the threshold because the customer can verify the result themselves; a decision class requiring genuine judgment typically sits above it. This makes the threshold a specification point at Full-System Design time rather than a case-by-case decision, and it becomes the evidentiary link the Accountability Trace draws on when a decision above the threshold later requires a demonstration that disclosure actually occurred.

### Application

Interactions with a Deterministic Outcome — a password reset, a delivery status check — sit below the threshold, since the customer's concern is the verifiable result rather than who produced it. Interactions involving judgment, empathy, or consequential decisions the customer cannot verify themselves — a disputed charge, a denied claim — sit above the threshold and require disclosure, because concealment withholds information the customer would reasonably want to assess fairness.

### Context

The Disclosure Threshold takes an explicit position the rest of the corpus had left open: whether a customer needs to know no human is involved. The risk is asymmetric — concealment discovered at a low-stakes interaction is minor, but concealment discovered at a consequential one compounds, because the customer learns the business let them believe a person had weighed their specific situation at exactly the moment that belief mattered most. The practical test: if the customer would feel reasonably misled upon learning the truth, disclose; if they would reasonably shrug, disclosure is optional.

## Related Terms

- [Deterministic Outcome](https://arcoventure.studio/lexicon/deterministic-outcome) — Interactions with a Deterministic Outcome typically sit below the Disclosure Threshold, since the customer's concern is the verifiable result rather than who produced it.
- [Decision Execution Autonomy (DEA)](https://arcoventure.studio/lexicon/decision-execution-autonomy) — The Disclosure Threshold shares its classification work with DEA: a decision class verified as Deterministic typically sits below the threshold, while judgment-requiring classes sit above it.
- [Steward Experience](https://arcoventure.studio/lexicon/steward-experience) — The Steward Experience must include a mechanism for surfacing which interactions exceeded the Disclosure Threshold, so the Steward can verify that disclosure occurred alongside those decisions.
- [Retention Reflex](https://arcoventure.studio/lexicon/retention-reflex) — The Retention Reflex's proactive outreach must respect the Disclosure Threshold: customers whose cases required disclosure expect that standard to be met in every subsequent consequential interaction.
- [Full-System Design](https://arcoventure.studio/lexicon/full-system-design) — The Disclosure Threshold is specified at Full-System Design time as a classification point rather than a live judgment call, becoming the evidentiary link the Accountability Trace draws on when disclosure must later be demonstrated.

## Articles

- [The Last Approval](https://arcoventure.studio/blog/the-last-approval)
- [The UI That Runs the Business](https://arcoventure.studio/blog/the-ui-that-runs-the-business)
- [Redundancy as a Feature, Not Just Insurance](https://arcoventure.studio/blog/redundancy-as-a-feature)

## References

- [Lexicon](https://arcoventure.studio/lexicon/disclosure-threshold) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/disclosure-threshold) — extended entry

## Metadata

**First used:** 2026-07-15  
**Pillar:** How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
