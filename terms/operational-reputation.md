# Operational Reputation

> The set of verifiable, queryable operational signals — derived directly from a business's actual execution history rather than from narrative or perception — that a counterparty can check before deciding whether to transact, escalate, or avoid; the external-facing packaging of metrics the Autonomy Spectrum Framework already scores internally.

## Extended Definition

A human counterparty carries reputation, accumulated informally through people who have dealt with them before. A company carries a brand, built and defended through human-mediated narrative. Neither mechanism transfers to a transaction between agents — an agent evaluating whether to transact with an autonomous business has no informal network to query and no interest in narrative. Operational Reputation is what fills that gap: a record, not a story.

The primitive is deliberately not new signal invention. Intervention Dependency, scored via MTTI and the Escalation Rate, and Structural Headcount Independence are two of the five axes the Autonomy Spectrum Framework already scores internally. Operational Reputation exposes a defined subset of that same underlying data — sourced from Proof of Action and Deterministic Logging — continuously, to any counterparty deciding in real time whether to proceed with a specific transaction, rather than periodically to a single acquirer or analyst.

A single composite reliability score is the wrong shape for this primitive, for the same reason a composite alone is insufficient for the Autonomy Spectrum: it hides exactly the information a sceptical counterparty needs. Operational Reputation must remain a small set of independently queryable, axis-specific signals, with any composite offered only as a secondary summary — the business must not control the calculation of the number a counterparty is relying on.

Liquidity Lock is the closest existing concept and the distinction is precise rather than incidental: Liquidity Lock is a one-time, high-stakes audit-transparency state evaluated by a single buyer at the moment of sale. Operational Reputation is the same underlying verifiability, applied continuously and at low stakes per instance, to any counterparty deciding whether to transact at all. The two states can diverge — a business can be an excellent day-to-day counterparty with a thin acquisition history, or the reverse.

### Application

Operational Reputation is architected as a small set of independently queryable, axis-specific signals — intervention frequency, execution consistency against disclosed thresholds, and audit trail completeness — sourced from the same Proof of Action and Deterministic Logging infrastructure already kept for internal governance, exposed continuously to any counterparty deciding whether to proceed with a specific transaction, rather than collapsed into a single proprietary composite the business controls the calculation of.

### Context

Operational Reputation deliberately reuses the Autonomy Spectrum Framework's existing axes rather than inventing new signals: Intervention Dependency, scored via MTTI and the Escalation Rate, and Structural Headcount Independence are not redefined for this purpose, only repositioned for a different audience and cadence. The Autonomy Spectrum Framework scores a business periodically for an acquirer or analyst; Operational Reputation exposes a defined subset of the same underlying data continuously, to any transacting counterparty. It is closely related to, but distinct from, Liquidity Lock — the one-time, acquisition-moment audit-transparency state — since Operational Reputation applies the same underlying verifiability continuously and to any counterparty deciding whether to transact at all, not only a buyer deciding whether to acquire.

## Related Terms

- [Autonomy Spectrum Framework](https://arcoventure.studio/lexicon/autonomy-spectrum-framework) — The framework whose internal scoring axes Operational Reputation re-packages as externally queryable signals for any transacting counterparty.
- [Intervention Dependency (ID)](https://arcoventure.studio/lexicon/intervention-dependency) — One of the two Autonomy Spectrum axes Operational Reputation exposes externally, scored via MTTI and the Escalation Rate.
- [Structural Headcount Independence (SHI)](https://arcoventure.studio/lexicon/structural-headcount-independence) — The second Autonomy Spectrum axis Operational Reputation surfaces as an independently queryable counterparty signal.
- [Liquidity Lock](https://arcoventure.studio/lexicon/liquidity-lock) — The closest cognate concept, distinguished from Operational Reputation by being a one-time, acquisition-moment audit state rather than a continuous per-transaction signal.
- [Proof of Action](https://arcoventure.studio/lexicon/proof-of-action) — The execution record infrastructure that sources the verifiable signals Operational Reputation exposes to counterparties.
- [Deterministic Logging](https://arcoventure.studio/lexicon/deterministic-logging) — The logging infrastructure providing the audit trail completeness component of Operational Reputation's signal set.

## Articles

- [Autonomy Is a Claim Until It Is Measured](https://arcoventure.studio/blog/autonomy-is-a-claim-until-it-is-measured)
- [The System That Does Not Call](https://arcoventure.studio/blog/the-system-that-does-not-call)
- [Who's Liable When Nobody Decided?](https://arcoventure.studio/blog/whos-liable-when-nobody-decided)

## References

- [Lexicon](https://arcoventure.studio/lexicon/operational-reputation) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/operational-reputation) — extended entry

## Metadata

**First used:** 2026-08-07  
**Pillar:** How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
