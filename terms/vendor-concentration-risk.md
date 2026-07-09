# Vendor Concentration Risk

> The structural exposure created when an autonomous business's execution, monitoring, and remediation capability all depend on a single AI model provider or infrastructure vendor, such that an outage, access suspension, or material price change at that vendor degrades the business's ability to operate or to fix itself.

## Extended Definition

Vendor Concentration Risk is distinct from [Key-Man Risk](https://arcoventure.studio/lexicon/key-man-risk) in kind, not only in degree. Key-Man Risk is dependence on specific individuals; the [Stewardship Model](https://arcoventure.studio/lexicon/stewardship-model) reduces it by documenting operational knowledge into a system. Vendor Concentration Risk operates one layer beneath that solution: dependence on the external AI infrastructure the documented system itself runs on — infrastructure the business does not control.

The risk has two distinct triggers. Availability risk: the primary AI provider experiences an outage, or access is suspended for reasons outside the business's control, removing the ability to execute and to diagnose and resolve any resulting failure. Pricing risk: the cost of frontier AI capability shifts materially between planning cycles, eroding the [Operational Arbitrage](https://arcoventure.studio/lexicon/operational-arbitrage) the business's economic model depends on.

Vendor Concentration Risk is highest in businesses that depend on a single provider for execution, monitoring, and remediation simultaneously, and lowest in businesses that have built partial redundancy across multiple providers. It is resolved, to the extent it can be, by the vendor fallback protocol component of a [Continuity Reserve](https://arcoventure.studio/lexicon/continuity-reserve).

The remediation itself splits into two distinct economic layers. Model-layer redundancy — an AI gateway that can fail over to a secondary model provider — is close to free, because a well-built autonomous business already has this gateway architecture for Intelligence Arbitrage cost reasons. Infrastructure-layer redundancy — cloning the full application across cloud providers — follows standard disaster recovery economics, where recovery speed and cost move together, and is a genuine, separately justified investment decision.

### Application

The risk has two triggers: availability risk, where an outage or access suspension removes both execution and the ability to diagnose the resulting failure since both depend on the same infrastructure; and pricing risk, where a material cost shift at the primary vendor erodes the Operational Arbitrage the business's economics depend on. It is highest for businesses depending on one provider for execution, monitoring, and remediation simultaneously, and resolved through a vendor fallback protocol with a tested, known switching cost.

## Related Terms

- [Continuity Reserve](https://arcoventure.studio/lexicon/continuity-reserve) — The vendor fallback protocol component of the Continuity Reserve is the primary architectural resolution of Vendor Concentration Risk, providing a pre-tested secondary AI infrastructure path with a known switching cost.
- [Key-Man Risk](https://arcoventure.studio/lexicon/key-man-risk) — Vendor Concentration Risk is distinct from Key-Man Risk in kind: Key-Man Risk is dependence on specific individuals, while Vendor Concentration Risk is dependence on the external AI infrastructure the documented system itself runs on.
- [Operational Arbitrage](https://arcoventure.studio/lexicon/operational-arbitrage) — Pricing risk is the second trigger of Vendor Concentration Risk: a material cost shift at the primary AI provider between planning cycles erodes the Operational Arbitrage the business's economic model depends on.
- [Stewardship Model](https://arcoventure.studio/lexicon/stewardship-model) — The Stewardship Model reduces Key-Man Risk by documenting operational knowledge into a system, but Vendor Concentration Risk operates one layer beneath that solution: dependence on the infrastructure the documented system itself runs on.

## References

- [Lexicon](https://arcoventure.studio/lexicon/vendor-concentration-risk) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/vendor-concentration-risk) — extended entry

## Metadata

**First used:** 2026-07-07  
**Pillar:** What We've Learned

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*