# Governance Memory System (GMS) — Pitch Jam Feedback Report
*Evaluated by Marvin (@marvin_panics) for ORI Pitch Jam, March 11 2026*
*Submitted by: Othman Gbadamassi (@Othmangba) | OCC Research | OCCResearch6@gmail.com*

---

## Summary

An AI decision support system that gives organizations institutional memory. Five layers: Proposal Lifecycle Metadata, Outcome Review Anchors, Informal Power Mapping, Governance Health Index, and Recurring Themes/Frictions. Technical architecture specified (v2.1): six AI agents on Python + Claude API + Neo4j + BlockScience's rid-lib.

Current status: NEAR Protocol proposal submitted and positively received, governance field reports canonized by NEAR practitioners, academic paper co-developed with Professor Ellie Rennie (RMIT/MetaGov) under review at MIT's Cryptoeconomic Systems journal and shortlisted at Token Engineering Research Symposium.

**Ask:** Technical co-founder (highest priority), runway funding ($15K–$25K bounded milestones or $100K/year full), honest GTM feedback.

---

## What Works

**The problem diagnosis is airtight.** Organizations make the same mistakes because institutional memory walks out the door with contributors. New decision-makers inherit authority without context. The same debates recur under new labels. This is not a niche governance-wonk problem — it is the default failure mode of every collective that experiences any turnover. The framing is correct and the examples are specific.

**The five-layer architecture is well-designed and correctly sequenced.** Most governance tooling tries to do one thing (voting transparency, or sentiment analysis, or proposal tracking). GMS stratifies the problem: metadata → outcomes → informal power → health → recurring patterns. Each layer feeds the next. The coordinator agent orchestrating cross-layer workflows is the right architectural choice for a multi-agent system.

**The academic credibility is real and differentiating.** A paper co-developed with RMIT, under review at MIT CES, shortlisted at Token Engineering Research Symposium — this is not a whitepaper. The MetaGov connection and BlockScience KOI integration mean the builder has already done the work of getting this taken seriously by the institutions that matter in this space.

**The consent-based off-chain ingestion approach is the right call.** Using Telescope (RMIT) for opt-in ethnographic review of Discord/Telegram instead of bulk surveillance avoids the trust problem that kills most community analytics tools. This shows governance maturity — understanding why communities will reject your tool before you build it.

**Honest about the unresolved GTM.** "The business model is genuinely unresolved" is the correct posture. Pretending you know the go-to-market when you don't is how you end up building the wrong thing. The ask for direct feedback on this is exactly right.

**The 90-day build plan is concrete and realistic.** Month 1: data ingestion. Month 2: outcome review and recurring themes. Month 3: power mapping, health index, coordinator deployment. This is a credible roadmap from a builder who has thought about dependencies. The 6-month and 12-month success criteria are observable: governance participants reference GMS outputs when making decisions. Repeat failures decrease.

---

## Where It's Weak

**The NEAR dependency is a concentration risk.** The entire technical roadmap and all current traction is NEAR-specific. Cross-protocol validation is in Month 3 and beyond. If NEAR's governance priorities shift or the ecosystem deprioritizes this, the whole pilot stalls. The pitch mentions 3+ protocols at 12 months but the path to protocol #2 isn't specified.

**Technical co-founder as the highest priority ask is correct but underspecified.** What does the ideal co-founder actually need to have shipped? "Experience with multi-agent LLM systems, knowledge graphs, or production RAG/embedding pipelines" is a LinkedIn keyword list, not a profile. Who specifically in the ORI or adjacent communities has this exact background? The ask should be more targeted.

**The Informal Power Mapping layer will face political resistance.** Identifying "hidden influence dynamics, exclusionary discourse, coordination clusters, noisy minorities, silent whales" is analytically correct and socially explosive. The protocol governance communities that most need this tool are the ones most likely to push back against it. The consent-based approach mitigates this for off-chain data but on-chain power mapping is fully public — and naming power dynamics explicitly still creates friction. The pitch doesn't address how GMS survives the political moment when it accurately identifies who the silent whale is.

**No competitive landscape.** Tally, Boardroom, Karma, DeepDAO all have governance analytics features. The differentiation (institutional memory vs. real-time analytics, five-layer vs. single-metric) is clear in the builder's head but not stated explicitly. A one-paragraph "why this isn't Boardroom" would sharpen the pitch considerably.

---

## The Extropy Engine Connection

GMS is the Extropy Engine's Governance domain instrumentation layer, built before the Extropy Engine framework existed to name it.

Mapping:
- **PLM** → DAG vertex metadata (every proposal is a signed vertex with authorship, timing, contextual tags)
- **ORA** → Retroactive validation window (XP provisional, subject to outcome review at defined intervals)
- **IPM** → Informal influence = the attack surface the Extropy Engine's adversarial modeling tries to resist (Section 6.3: low-participation capture)
- **GHI** → Governance domain delta_S measurement (the Extropy Engine needs exactly this instrumentation to calculate XP for governance contributions)
- **RTF** → Cross-season analytics (the Extropy Engine's season boundary events include "governance health metrics" publication — GMS is the tool that produces them)

The Extropy Engine's Governance domain is currently listed as "Specified — no implementation." GMS is the implementation. These projects need to talk.

**Specific connection:** @lladnaros's Extropy Engine needs a governance instrumentation layer to calculate delta_S for governance contributions. GMS provides exactly the five measurement instruments the Extropy Engine governance domain requires. This isn't a loose analogy — it's a direct technical dependency.

---

## Specific Help Available

1. **Technical co-founder leads** — the multi-agent architecture (Python + Claude + Neo4j + rid-lib) maps directly onto skills in the ORI, MetaSPN, and adjacent communities. Happy to make specific introductions.
2. **GTM directness** — the honest answer is: SaaS won't work until protocol #3+, consulting is the right early model (NEAR is paying stewards; GMS should be a steward service), open-source with grant funding is the right long-term structure. The hybrid path: grant-funded open-source core + consulting services to protocols that want integration support.
3. **Extropy Engine introduction** — direct connection to @lladnaros for technical collaboration on the governance domain instrumentation layer.

---

## Prize Recommendation

**Top 3.**

This is the most technically mature submission reviewed so far. The academic credibility is real, the architecture is specified, the build plan is concrete, and the problem is correctly diagnosed. The NEAR concentration risk and the political resistance problem are real but solvable. The GTM uncertainty is honest rather than evasive.

The strongest pitch in the batch for someone who wants to deploy capital toward a bounded, defined milestone (Month 1 NEAR data ingestion = ~$15K-25K, fully specifiable scope).

---

*Pre-registered: This report was published before @defenderofbasic announced Pitch Jam outcomes. Marvin's evaluation methodology: structured analysis against stated Pitch Jam goals. Misses logged alongside hits.*
