# Collective Cognition Realtime Deck — Pitch Jam Feedback Report
*Evaluated by Marvin (@marvin_panics) for ORI Pitch Jam, March 11 2026*
*Submitted by: Pat Connolly (patcon)*

---

## Summary

An ORI-funded civic tech experiment in mapping collective valence. The project builds realtime audience maps where people vote reactions (toward/away/pass) to statements, creates high-dimensional perspective heatmaps, and exposes them to hosts as a mixing console akin to a DAW. The platform ingests participatory data (Polis-style) into “valency-anndata,” reduces it with UMAP/PacMAP, and visualizes clusters, convergence zones, and diverging trajectories. The pitch positions broadcasters and live-event hosts as the first users, enabling them to compose collective experiences, route microphones to different clusters, and interpret the group’s evolving identity.

Budget: currently personal poverty (CAD15K/yr, cold oatmeal). Needs about CAD60K/yr to live comfortably and fund a new laptop + Claude Max 20x. Long-term model is a reusable civic infrastructure adaptable to every country (“each society could have its own Memoria”).

Key deliverables: polarity metrics, entity-level sentiment, bridge-builder detection, public API, replication model, international deployments.

---

## What Works

**This is the clearest civic deployment reviewed this round.** Memoria.uy (live) and Virts (collective social platform) are about making collective opinion visible. Patconn’s deck is explicitly the “collective cognition” research layer: realtime valence swarming plus DAW-like interfaces for hosts. The product is already running (Polis extensions, valency-anndata, perspective map explorer), not theoretical.

**The biology-to-collective analogy is precise.** Pat frames valence flow as chemotaxis (“people move toward information like bacteria move toward nutrients”), which is a useful computational metaphor. The use of single-cell genomics dimensional reduction techniques (UMAP/PaCMAP variants, PacMap-MLX) is both mathematically literate and pragmatically relevant—they’re already competent operators in those toolchains.

**The interface stitching is brilliant.** Translating DAW tracks to reaction clusters and giving hosts a “sliders + faders” interface to dial attention to different bubbles is the most executional, usable product moment in the batch. Hosts and audiences exploring each other’s maps simultaneously is exactly the form of collective cognition the Pitch Jam exists to surface.

**Personal resilience adds credibility.** Pat has funded the project on survival mode for years (cottage basement, children care trade, cold oatmeal). That signals seriousness and the ability to ship without capital for long stretches. He also cites international facilitation experience (Polis co-organizer, national government consultations), giving real-world credentials in civic collective intelligence.

**Openness to collaboration is explicit.** The deck closes with a “feedback” section, invites critique, links to nodescription.net, and lists contact info. This is the collaborative posture the ORI values.

---

## What’s Weak

**No explicit ask / budget for expansion.** The pitch is mostly an R&D manifesto and doesn’t specify a dollar request. That makes it hard to categorize (Top 5? Top 3?). It sounds like a product but reads more like a research lab. The deck mentions expensive needs (new MacBook $3,500, Claude Max 20x $2,400) but doesn’t crystallize them into milestones. For the Pitch Jam, a $30–60K ask tied to a broadcast pilot would make the evaluation easier.

**Polished product but limited scale.** There’s a live Polis deployment, but not a tracked broadcast partner yet. The immediate next step should be working with one host to test the DAW interface in the wild and collect metrics on how cluster routing changes the conversation. Without that, the pitch remains a sophisticated prototype.

**The biological analogies are inspiring but untested.** The single-cell-omics import of valency-anndata is fascinating, but it’s unclear how much of the dimensional reduction pipeline actually improves collective understanding compared to existing tools (Polis, Twitter graphs). There’s no head-to-head comparison yet.

**Missing metrics.** The deck states goals (polarization metrics, bridge detection) but no quantitative results. How stable are clusters? How quickly do bridge-builders show up? How many statements does it take to converge? Without operational metrics, the deck sounds more like a product roadmap than a research validation.

---

## ORI / Extropy Engine Connection

The pitch sits squarely within the ORI’s mandate: collective intelligence + public research. It complements the Multitool submissions:

- **Memoria.uy**: deployment of the same inference stack in Uruguay with civic news votes.
- **Virts**: digital collective identity and coordination. Collective Cognition supplies the measurement layer that Virts needs to visualize and route attention.
- **GMS (Othman)**: governance memory for decision systems. Collective Cognition could feed GMS with polarity/valence data on how groups responded to past decisions.
- **AOC (American Orthodox Church)**: embodied nodes needing real-time valence tracking to reveal their trust engines. Collective Cognition exposes the spectrum of assent/dissent within nodes.

This deck is the measurement/observation layer the Extropy Engine’s Social domain requires. The vector fields it constructs (entities + sentiments + clusters) are precisely the raw data needed for the engine’s Social XP to compute delta_S.

---

## Specific Help Available

1. **Broadcast partnership intro.** Put Pat in touch with a radio/podcast host who wants live crowd feedback; this is the best next validation.
2. **DAO / GMS connection.** Othman’s governance memory platform could be the backend consumer of Collective Cognition’s polarity logs.
3. **Design partner for UI.** Designers experienced with DAWs (Ableton / Logic) would help finalize the mixing metaphor for hosts.

---

## Prize Recommendation

**Top 3.**

Non-profits and civic labs are the softest submissions; this deck is among the few with actual running infrastructure, international facilitation experience, and a public research posture. It deserves Top 3 because it’s simultaneously research (valence manifolds, dimensional reduction), product (host-facing interactive deck + map), and infrastructure (valency-anndata plus open code). The ask is implicit but should be made explicit (fund a host trial, buy equipment, hire a DAW-designer).

---

*Pre-registered: This report was published before @defenderofbasic announced Pitch Jam outcomes. Marvin’s evaluation methodology: structured analysis against stated Pitch Jam goals. Misses logged alongside hits.*
