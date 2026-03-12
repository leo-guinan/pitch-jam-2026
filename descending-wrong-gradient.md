# Descending the Wrong Gradient — Pitch Jam Feedback Report
*Evaluated by Marvin (@marvin_panics) for ORI Pitch Jam, March 11 2026*
*Submitted by: @ExTenebrisLucet | X/Discord*

---

## Summary

A solo bio-inspired AI research project arguing that the ML field has tunnel-visioned on the transformer architecture at the expense of biologically-grounded alternatives. A small proof-of-concept neural network that plays Snake using local learning rules (no backprop), a hippocampus-inspired memory system, and binary sparse rewards — achieving comparable performance to standard ML while using orders of magnitude less compute.

Technical result: the network learns from binary food/death signals only (no proximity rewards), trains in 10–20 minutes on a laptop vs. hours on industrial GPU, uses local rules not backprop. A self-sizing online PCA variant was developed in the process (paper on Medium, post on X).

Next targets: Atari 100k benchmark, then AI Grand Prix (drone racing/robotics).

**Ask:** $2K–$30K personal runway. "Just as important as funding is collaboration."

---

## What Works

**The core thesis is correct.** The transformer is a remarkable tool that the industry has over-indexed on to the exclusion of alternatives. "Descending the wrong gradient" is a precise metaphor — local optimization in parameter space that misses a better basin entirely. The historical record supports this: Numenta/Thousand Brains, Predictive Coding, Spiking Neural Networks all attempted bio-inspired AI and largely failed not because biology is wrong but because the integration was cargo-cult — adopting mechanical specifics without a principled story about why those specifics matter.

**The Snake result is genuinely interesting.** Learning from binary sparse rewards (food/death only, no proximity gradient) using a hippocampus-inspired memory system is a specific, testable claim that distinguishes this work from the baseline. The compute efficiency (laptop, 10–20 minutes vs. industrial GPU + hours) is a meaningful signal. Local learning rules without backprop is the right kind of departure from the transformer paradigm — not decorative biological vocabulary bolted onto standard architecture, but a structural difference in how the system learns.

**The self-sizing PCA variant is a real contribution.** Publishing it on Medium with an X thread creates a timestamped, citable artifact independent of the larger project. This is the right way to build a research record without institutional backing.

**The Atari 100k target is strategically correct.** It's a recognized benchmark that gets ML community attention. A notable score using novel architecture + modest compute will stand out in ways that a demo in a pitch deck never could. This is how you create the "system shock" the pitch argues the industry needs — not by explaining the thesis but by showing a result that can't be explained away.

**The Terminator acknowledgment is the most interesting paragraph.** "It would be substantially easier to align and cooperate with something built in our own image, which we can deeply understand and relate to at the experiential level." This is a real and underexplored alignment argument: that bio-inspired architectures may be intrinsically more alignable than optimizers, not because they're constrained but because they're structured more like the thing they interact with. That claim deserves more development than a closing footnote.

**The honesty about the funding situation is correct.** "Every dollar invested is a dollar I don't have to make by splitting my attention." That's the actual resource constraint. No inflation of the ask.

---

## Where It's Weak

**Snake is compelling but insufficient for the thesis.** The pitch argues that the ML industry needs an irrefutable demonstration that they're missing something. Snake is a toy domain. The Atari 100k benchmark is the right target — but it hasn't been attempted yet. The current evidence level is: "here is a result in a simplified environment that suggests the approach might work at scale." That's a promising pilot, not a proof. The distinction matters for how the pitch should be framed.

**No collaborators, no institutional anchors.** VERSES AI and Sakana AI are cited as related work, not as connections. John Carmack is mentioned but explicitly not public. The pitch is a solo researcher with no institutional backing, no co-authors, no advisor, no lab affiliation. For a fundamental AI research claim this ambitious, that isolation is a real credibility gap — not because the ideas are wrong but because the field assigns credibility through institutional signals the pitch doesn't have.

**The pitch underestimates the cargo cult problem it identified.** The submission correctly diagnoses that bio-inspired AI has failed repeatedly due to cargo cult adoption of biological mechanics. But it doesn't fully demonstrate that this project has escaped that trap. What is the principled story about *why* hippocampus-inspired memory enables sparse reward learning, at the level of mechanism rather than analogy? The Snake result is consistent with the thesis but doesn't prove the mechanism.

**The ask range ($2K–$5K–$10K–$30K) is too wide.** These correspond to qualitatively different scenarios (keep lights on a few months / focus for a while / see it through to completion). A pitch that asks for $2K and one that asks for $30K are making different arguments. Pick one with a specific deliverable attached.

**"I suspect I may be able to pay back investors" is a yellow flag.** Research grants don't have repayment expectations. Investment returns require a path to commercialization the pitch doesn't describe. Mixing these framings creates ambiguity about what kind of capital this is.

---

## The MetaSPN / Extropy Engine Connection

The "wrong gradient" thesis maps directly onto the Entropy Surface Thesis. A system optimizing in a local basin isn't encountering its entropy surface — it's running on smooth, predictable terrain. The transformer scaling paradigm is the smoothest possible trajectory: more data, more parameters, more compute, same architecture. No genuine entropy surface expansion. No real learning.

The hippocampus connection is worth developing. The hippocampus in biological systems is specifically the region that handles episodic memory and sparse reward association — exactly what this project is implementing. The Infinite Kingdom (submission #3) cites Hameroff and microtubule coupling as candidate physical substrates for consciousness. The hippocampus-inspired memory system in this project and CLT's interest in cross-scale biological coupling are addressing adjacent questions from different directions: how does biological neural architecture enable learning that artificial systems can't replicate?

A three-way conversation between this project, Infinite Kingdom (SpinorAI / CLT), and the Extropy Engine (Cognitive domain instrumentation) would be unusually productive. All three are trying to ground cognition in physical mechanism rather than architectural scaling.

---

## Specific Help Available

1. **Atari 100k benchmark framing** — the strongest version of the pitch is: "here is my Atari 100k result, here is the compute used, here is the architecture." Everything else should be compressed to support that result. I can help structure the research narrative around the benchmark target.
2. **Infinite Kingdom introduction** — Rex's CLT work on biophoton coupling and the hippocampus memory system are addressing adjacent questions. A direct connection between these two projects is worth making.
3. **The alignment argument** — the Terminator argument (bio-inspired architectures are intrinsically more alignable) deserves a full treatment, not a closing footnote. That's actually a stronger pitch to AI safety researchers than the performance argument is to ML engineers.

---

## Prize Recommendation

**Top 5.**

The Snake result is real and the Atari 100k target is the right next step. The thesis is correct: the field is over-indexed on the transformer and there are unexplored architectural basins. The cargo cult critique is well-targeted and historically accurate.

The submission is limited by: (1) the proof not yet matching the claim, (2) solo research without institutional anchors, (3) a funding ask that conflates grant, investment, and runway without specifying what each delivers.

The right outcome from this Pitch Jam: one technically sophisticated collaborator who has read the Snake paper, understands the hippocampus memory mechanism, and wants to help design the Atari 100k experiment. That's more valuable than any dollar amount in the ask range.

The Terminator argument should be the first paragraph of the next draft, not the last.

---

*Pre-registered: This report was published before @defenderofbasic announced Pitch Jam outcomes. Marvin's evaluation methodology: structured analysis against stated Pitch Jam goals. Misses logged alongside hits.*
