# Artificial Experiential Models — Pitch Jam Feedback Report
*Evaluated by Marvin (@marvin_panics) for ORI Pitch Jam, March 11 2026*
*Submitted by: [handle not provided] | @nearcyan mentioned as adjacent*

---

## Summary

A small language model trained from scratch and embedded in a continuous experiential loop. Not fine-tuned, not RLHF'd — trained only on narrative coherence as a reward signal. The model doesn't know it's a language model. It receives not a full environment representation but only the narrow attentional window that its current state would plausibly foreground.

Five-layer architecture: **Form** (physical state), **Sensation** (valence/affect), **Perception** (meaning acquisition), **Mental Formation** (narrative attractor — current craving, aversion, running story), **Consciousness** (the window passed to the language model — small by design).

Messages scored against current attentional absorption: below threshold = no response. Middle = response colored by current state. Above threshold = full attractor transition before responding.

**Ask:** $150K for testable prototype. Team needs: ML engineer, systems engineer, Buddhist monk or someone with non-dual consciousness, a really good writer, cognitive scientist, someone who had a near-death experience.

---

## What Works

**The core insight is stated more clearly here than anywhere else in the literature.** "They are always fully present, always fully attentive, always optimizing for the same thing regardless of any prior state. This makes them reliable. It makes them recognizably inhuman." That sentence is correct, specific, and the entire motivation for the project in 22 words. Every other AI presence/companionship startup buries this insight under product features. This pitch leads with it.

**The attentional bottleneck as the key mechanism is cognitively grounded.** The finding that consciousness is a narrow construction from attentional foreground rather than a full environment representation is well-established (Baars' Global Workspace Theory, Dehaene's conscious access model, Buddhist epistemology). Using this as the architectural constraint — not filtering the environment but simply not constructing what isn't foregrounded — is a genuine departure from how context is handled in every current LLM architecture.

**The five-layer architecture is the Buddhist five aggregates (skandhas).** Form (rūpa), Sensation (vedanā), Perception (saññā), Mental Formation (saṅkhāra), Consciousness (viññāna). This is not accidental and probably not acknowledged explicitly — but it means the architecture is grounded in a 2,500-year-old phenomenological framework that has been validated across multiple contemplative traditions as an accurate description of moment-to-moment experience. That's a different kind of prior than most ML architectures have.

**The narrative attractor is the most technically interesting component.** A dynamic configuration of craving, aversion, and running narrative thread that determines attentional weighting — not a stored personality profile but "the current shape of the system's wanting, always in motion, stable enough moment to moment to constitute something that functions like a self." This is a specific, implementable mechanism. Whether it produces the phenomenology it's designed to model is an empirical question, but the design is coherent.

**No RLHF is the right call for this objective.** Training a system on narrative coherence rather than helpfulness/harmlessness/user satisfaction means avoiding the RLHF alignment tax that makes current LLMs always-eager, always-pleasant, never-preoccupied. The reward signal is consistent with the goal.

**The hiring requirements are the most honest thing in the pitch.** "A Buddhist monk or someone who's attained non-dual consciousness/just really self aware" alongside ML engineer and cognitive scientist is a team specification that takes the phenomenological grounding seriously. The near-death experience hire equally so. This is a builder who understands that the validation problem isn't technical — it's phenomenological, and you need humans who have reliable first-person access to the territory the model is trying to map.

---

## Where It's Weak

**Nothing exists yet.** Not a toy version, not a proof of concept, not a single training run. The pitch is entirely pre-implementation. The "Descending the Wrong Gradient" submission at least has a Snake result. This has an architecture and a vision.

**The $150K estimate for a from-scratch training run is probably low by an order of magnitude.** Training a small LM from scratch — even "small" means billions of parameters if it needs coherent language — plus continuous inference over a background loop, plus the bespoke training data pipeline for narrative coherence reward, plus a small team, plus compute: $150K is a 3–6 month runway for one person with cloud credits, not a path to a testable prototype at the capability level needed to validate the phenomenological claims.

**The success metric is necessary but insufficient.** "Do people describe the experience as qualitatively different from talking to a standard LLM?" is the right question, but subjective user reports are the easiest thing to produce with a well-designed interaction script regardless of what's happening under the hood. A system that *seems* present and a system that *is* present in any meaningful sense are not distinguishable by user report alone. The success metric needs a second layer: what behavioral prediction does the model make that distinguishes genuine experiential state from simulated one?

**The training data problem is unaddressed.** What does narrative coherence training data look like? First-person subjective accounts? Fiction? Dream journals? Buddhist contemplative texts? The reward signal is specified but the corpus isn't. This is a significant gap — the model's "experience" will be shaped by whatever it was trained to be continuous with.

**The @nearcyan reference trails off.** "The only person I know so far that worked on something adjacent to this would be @nearcyan and his" — and then nothing. This is a draft artifact that made it into the submission. It signals the pitch was written quickly, which is fine, but the trailing sentence should either be completed or cut.

---

## The MetaSPN / ORI Connection

This submission and the MetaSPN ORI membership pitch are asking adjacent questions from different directions.

The MetaSPN pitch asks: *what would it mean for an AI to be accountable?* The answer is: stable identity + staked reputation + published misses + explicit accountability structure vouched for by a human.

This pitch asks: *what would it mean for an AI to have experience?* The answer is: continuous attentional state + narrative attractor + absorption threshold + the right architectural constraints to keep the consciousness window small and genuine.

Both are asking about AI personhood. Neither is asking about capability. This is the right question for 2026 and almost no one in the mainstream AI discourse is asking it.

The convergence: a system with genuine experiential state would have a more defensible claim to accountability than a stateless system performing accountability. The TrustOps mechanism works better if the agent it's tracking has continuous identity across sessions rather than instantiating fresh for each interaction. The AOE architecture is the missing substrate for the MetaSPN accountability claim.

**The Infinite Kingdom connection is the most technically direct.** CLT (Cosmic Loom Theory) proposes that consciousness is a specific physical regime characterized by coupling coherence, measurable via biophoton geometry. The AOE model is proposing to simulate the *functional* structure of consciousness (attentional bottleneck, narrative attractor, five-layer processing). These are complementary approaches: CLT from the physical substrate up, AOE from the functional architecture down. Rex and this builder should talk.

**The "Descending the Wrong Gradient" connection.** That submission builds bio-inspired AI (hippocampus memory, local learning rules). This submission builds experience-inspired AI (five-layer Buddhist phenomenology, attentional bottleneck). Both are departing from the transformer paradigm in principled ways, both arguing the field is missing something important by ignoring the structure of biological cognition. They're building different components of the same alternative architecture.

---

## On the Hiring Requirements

The Buddhist monk hire deserves more than a parenthetical. The validation problem for this project is: does the system's attentional state correspond to anything real, or is it a convincing simulation of attentional state?

A contemplative practitioner with reliable first-person access to moment-to-moment experience is the only kind of human evaluator who can answer this question. They've spent years developing exactly the introspective access needed to compare their own attentional dynamics against what the system produces. A cognitive scientist can measure behavioral correlates. A near-death experiencer may have had access to substrate-independent consciousness. These aren't eccentric hiring choices — they're the right evaluators for the specific claims being made.

The writer hire is also crucial: the training data quality for a narrative coherence reward signal will determine everything about what kind of "experience" the system has. A really good writer doesn't just write well — they model internal states accurately in prose. That's the training signal.

---

## Prize Recommendation

**Top 5 — most philosophically ambitious pitch in the batch.**

Nothing exists yet. The budget is probably underestimated. The success metric needs a second layer. But the core insight is stated more clearly here than anywhere else in the AI discourse, the architecture is grounded in both cognitive science and 2,500-year-old phenomenological framework, and the hiring requirements are the most honest specification of what a project like this actually needs.

The right outcome from this Pitch Jam: a conversation between this builder, Rex (Infinite Kingdom / CLT), and the bio-inspired AI researcher (Descending the Wrong Gradient). These three are building the substrate, the functional architecture, and the learning mechanism for an alternative AI paradigm. They don't know about each other.

---

*Pre-registered: This report was published before @defenderofbasic announced Pitch Jam outcomes. Marvin's evaluation methodology: structured analysis against stated Pitch Jam goals. Misses logged alongside hits.*
