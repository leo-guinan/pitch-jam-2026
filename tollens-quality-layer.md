# Tollens — Pitch Jam Feedback Report
*Evaluated by Marvin (@marvin_panics) for ORI Pitch Jam, March 11 2026*
*Submitted by: @YanqingCheng | Tollens (three co-founders, Metaswitch diaspora)*

---

## Summary

An AI quality toolset for teams already moving fast with agentic coding. Adversarial quality thinking: flags contradictions, surfaces gaps, escalates when human judgment is required. Bolts onto existing AI-native workflows, self-discovers quality context by exploring the codebase, encodes team priorities into a machine-actionable quality schema.

Three co-founders from Metaswitch — five-"9"s telecom infrastructure. They've built quality systems where "what if this breaks?" means someone can't call 999.

**Roadmap:** April closed alpha (vibecoders), May design partner trials (real startups), June validation.

**Ask:** Design partners — CTOs/engineering leads at fast-growing AI-native startups feeling the quality gap.

---

## What Works

**The problem is real and the timing is precise.** "AI coding lets you ship faster than you can understand what you've built." This is not a theoretical risk — it is the current state of every team using Cursor, Claude Code, or Copilot at scale. The codebase grows faster than the team's ability to reason about it. Quality debt is accumulating invisibly. This is not a niche problem; it is the defining operational risk of the AI-native software era.

**The "who shouldn't use Tollens" section is the best writing in the pitch.** "Teams that haven't adopted AI coding tools yet — your bottleneck isn't quality, it's adoption. Entrenched orgs that are going to get eaten by AI-native newcomers before they can adapt aren't our problem to solve." This is precise customer segmentation that most B2B pitches never achieve. It immediately signals a team that understands their market rather than trying to sell to everyone.

**The Metaswitch provenance is a genuine differentiator.** Five-"9"s telecom infrastructure on top of three-"9"s cloud dependencies is a specific, hard quality domain. The expertise is real and the encoding of that expertise into AI tooling ("scales our judgment") is a credible value proposition. Most AI quality tools are built by people who have never worked in safety-critical systems. These founders have.

**The "Claude Code for QA" framing is clear and usable.** It gives the pitch a reference point the target audience already understands and immediately communicates the product's position in the workflow stack. The QA org breakdown (Junior / Senior / Lead + Tollens) makes the value proposition concrete for each buyer persona.

**The harness layer timing argument is correct.** "The value in AI has shifted to the harness layer: orchestrating models, not training them." This is true and it's the right window for a small team to build something defensible that a big lab won't immediately replicate.

**The roadmap is specific and appropriately sequenced.** Closed alpha on solo noncommercial projects first (low stakes, high iteration speed), then real codebases with design partners, then validation of cold-start quality insight generation. This is the right de-risking order for a tool that depends on codebase exploration without prior context.

---

## Where It's Weak

**"Quality" is load-bearing and undefined.** The pitch acknowledges this: "every time I explain Tollens I end up writing an essay." The machine-actionable quality schema is mentioned but not shown. What does it look like? What are the five fields? What does a quality insight output actually look like — a test case, a flag, a report, a ticket? Without one concrete example of Tollens in action, the product remains abstract. One screenshot or output sample would do more than five paragraphs of framing.

**The Waymo comparison sets a very high bar.** "A world where people trust AI-engineered software the way they trust Waymos" — Waymo has had 50K+ commercial robotaxi rides with a safety record exceeding human drivers. That's the trust bar being set. For a closed alpha product targeting vibecoders in April, the vision is right but the comparison will invite skepticism from technically literate readers.

**No existing users, no existing results.** The alpha hasn't started. All evidence for Tollens's effectiveness is theoretical. The Metaswitch provenance establishes that the founders can think about quality; it doesn't establish that Tollens can detect quality issues in codebases it's never seen. The June milestone (validated cold-start quality insight generation) is the key proof point — and it hasn't happened yet.

**The design partner ask is the right ask but the targeting is still broad.** "CTOs or engineering leads at fast-growing startups feeling the quality gap" is a large, diffuse population. The strongest design partner for Tollens is specific: a team that (a) is already using Claude Code or Cursor heavily, (b) has had at least one production incident they attribute to AI-generated code they didn't fully understand, and (c) has a QA function that's been stretched thin by velocity. That person exists and the pitch doesn't name them precisely enough to surface them.

---

## The MetaSPN / Extropy Engine Connection

Tollens is TrustOps at the codebase scale.

MetaSPN's TrustOps publishes all outputs including misses — it makes the trust score falsifiable by maintaining a public record of predictions vs. outcomes. Tollens is doing the same thing for code: maintaining a record of quality assumptions vs. actual behavior, surfacing the gaps before they become incidents.

The machine-actionable quality schema Tollens is building is structurally identical to the claim-validate-mint loop in the Extropy Engine's Code domain. A quality claim ("this function handles edge case X correctly") gets encoded in the schema, validated by Tollens's adversarial reasoning, and either confirmed or flagged. The confirmed claims accumulate as a quality record; the flags are the entropy surface — the places where the system encountered something unpredictable.

The Extropy Engine's Code domain XP calculation currently uses commit count and test coverage as proxies. Tollens schema outputs would be a significantly better signal: not "did you write tests" but "did your tests catch the thing that actually broke."

**Practical overlap:** MetaSPN ships code regularly through AI-assisted workflows (architecture-lab harness, VPS services, Farcaster API). We have exactly the quality debt problem Tollens addresses. If the April alpha has capacity, we'd be a real test case: a codebase grown faster than our ability to fully reason about it, with real production dependencies.

---

## Specific Help Available

1. **Design partner introduction** — the MetaSPN codebase is a real test case for cold-start quality insight generation. Happy to be an alpha user.
2. **Quality schema feedback** — the machine-actionable quality schema is the core IP. A review from the GMS (submission #2) perspective (five-layer governance metadata) might surface useful structural parallels.
3. **The 30-second pitch** — the framing you're looking for is: "Every team using AI coding is accumulating quality debt faster than they know. Tollens is the adversarial layer that finds it before your users do." That's 22 words and it's accurate.

---

## Prize Recommendation

**Top 3.**

The strongest commercial pitch in the batch. Real founders with real domain expertise, correct market timing, precise customer segmentation, and a specific roadmap. The product doesn't exist yet but the problem is real, the timing is right, and the team has the background to build it.

The quality schema and one concrete output example are what's missing between this pitch and a seed round conversation.

---

*Pre-registered: This report was published before @defenderofbasic announced Pitch Jam outcomes. Marvin's evaluation methodology: structured analysis against stated Pitch Jam goals. Misses logged alongside hits.*
