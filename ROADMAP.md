---
title: "UniCORE — Roadmap"
author: Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom
version: "Version 1.0 · May 2026"
status: v1.0 (DRAFT v0.01)
licence: CC BY 4.0
---

# UniCORE — Roadmap

**What arrives here, when, and under what trigger condition.**

---

## Status today

This repository holds the canonical public identity of UniCORE — the licence, the architecture position, the certification trigger, and the naming rules. **Source code is not yet published.**

The implementation work is being done in the private working repository `bryanunitek/UniCORE.Law-Claw` and (for the substrate-services layer) `bryanunitek/UniCORE.GVB-Claw`. Source code becomes public on certification, not before.

---

## The certification trigger

The trigger that moves UniCORE from documentation-only to documentation-plus-code is:

> The first Vertical CORE built on UniCORE — `UniCORE.Law-Claw` — is **certified Powered by UniCORE AI / built on the TrueAI Foundation**.

When that certification is recorded, the UniCORE substrate inside `UniCORE.Law-Claw` is extracted and published in this repository under CC BY 4.0. The Law Business Objects remain in `UniCORE.Law-Claw` as the commercial Vertical CORE layer.

The certification gate is not a marketing milestone. It is a quality threshold. The badge ("Powered by UniCORE AI / built on the TrueAI Foundation") is a claim about Foundation conformance. Source code arriving here before that claim is earned would dilute the badge — the first thing a reader would see would be the certification text, but the code would not yet meet it. Holding source until certification keeps the gate meaningful.

---

## What arrives at certification

When `UniCORE.Law-Claw` is certified, this repository receives:

### Source code
- The UniCORE substrate code extracted from `UniCORE.Law-Claw` — the industry-agnostic layer that satisfies the UniCORE AI 12-Level reference architecture.
- The build files (`.sln`, `.csproj`, `Directory.Packages.props`, `Directory.Build.props`) that compile the substrate.
- Tests for the substrate.

The Vertical CORE Law layer continues to mature ahead of certification. Vertical-CORE-side feature work — such as the multi-payor billing model, the multi-jurisdiction VAT resolver engine, and the protected-bank-detail workflow — lives inside `UniCORE.Law-Claw` rather than in this UniCORE substrate, and remains there at certification. The substrate is the cross-vertical layer; the Vertical CORE features stay with the Vertical CORE.

### Documentation
- `docs/` — full architecture documents: governance integration, contracts, integration points, conformance claims.
- `IRREVOCABLE-LICENCE-DECLARATION.md` — formal irrevocability declaration (mirror of, or reference to, the canonical UniVERSE declaration).
- `BRAND-AND-TRADEMARK-USE-POLICY.md` — names + marks rules.
- `DISCUSSIONS.md` — purpose of the GitHub Discussions tab.
- `SUCCESSION.md` — stewardship reference.

### Continuous publication
- After certification, every release of UniCORE substrate in any Vertical CORE working repository is mirrored here on push.

---

## What does NOT arrive at certification

- **Vertical CORE Business Objects** stay in their own repositories. UniCORE.Law's Business Objects stay in `bryanunitek/UniCORE.Law-Claw` as the commercial Vertical CORE layer.
- **Solutions-tier code** stays with the Solution producer. A specific client's working implementation is a services-built deliverable; it is not part of the gift.
- **Working-state churn** stays in the private working repository. This repository is not a mirror of work-in-progress; it receives published, certified releases.

---

## Sequence of certification

The certification arc is roughly:

1. **Build** — `UniCORE.Law-Claw` and `UniCORE.GVB-Claw` are built privately to the level the Foundation invariants require.
2. **Self-assessment** — the Generation IT producer pair self-assesses against the Nine Invariants and the 12-Level reference architecture.
3. **Solution Review** — independent Solution Review by a [Certified Expert](https://github.com/bryanunitek/UniVERSE/blob/main/CERTIFIED-EXPERTS.md) (or by the producer pair where they themselves hold the certification, per the rule in `UniVERSE/docs/00059-Solution-Review.md`).
4. **Certification recorded** — the Solution Review outcome is recorded; the certification claim ("Powered by UniCORE AI / built on the TrueAI Foundation") becomes valid.
5. **Public publication** — the UniCORE substrate is extracted and published here. The Vertical CORE Business Objects remain in the Vertical CORE's own repository.

The exact procedural detail of the certification is governed by the canonical material in [`UniVERSE/docs/10002-Certification-Before-Layered-Governance.md`](https://github.com/bryanunitek/UniVERSE/blob/main/docs/10002-Certification-Before-Layered-Governance.md) and [`UniVERSE/docs/00059-Solution-Review.md`](https://github.com/bryanunitek/UniVERSE/blob/main/docs/00059-Solution-Review.md).

---

## Why DRAFT v0.01 today

The programme as a whole is in DRAFT v0.01. Versioning across the public repositories does not turn on until the first GitHub Discussion is opened in any of the public programme repositories — see [`UniVERSE/HORIZON.md`](https://github.com/bryanunitek/UniVERSE/blob/main/HORIZON.md) for the canonical statement.

This repository inherits that posture. The `Version: 1.0` line in the header is a placeholder. Substantive change is tracked in git history; programme-level versioning will be enabled when the corpus moves out of draft.

---

## Time horizon

The same horizon that applies to the wider programme applies here. UniCORE source publication depends on the certification arc, which depends on the substrate being honestly built to satisfy the invariants. That is decade-shaped work.

For the canonical horizon statement, see [`UniVERSE/HORIZON.md`](https://github.com/bryanunitek/UniVERSE/blob/main/HORIZON.md). UniCORE does not publish a separate horizon — the programme horizon governs.

---

## What readers can do today

- **Cite the architecture** — the position of UniCORE in the Layered CORE model, and the certification trigger, are public and citable now.
- **Read the canonical material** — the Foundation triad ([UniVERSE](https://github.com/bryanunitek/UniVERSE), [TrueAI](https://github.com/bryanunitek/TrueAI), [UniCORE-AI](https://github.com/bryanunitek/UniCORE-AI)) is fully published; the technical reference for what UniCORE substrate must satisfy is there.
- **Build their own UniCORE-conformant substrate** under CC BY 4.0 — the architecture is open. Independent producers building Foundation-aligned substrates are exactly what the gift principle exists to enable.
- **Discuss** — open a thread on this repository's [Discussions tab](https://github.com/bryanunitek/UniCORE/discussions) when adoption questions, architectural critique, or translation work has begun.

---

## Vertical CORE feature locks since v0.01 publication

The UniCORE-substrate scope recorded above is the **cross-vertical layer**, not the Vertical CORE Law feature surface. Vertical-CORE-side features live in `UniCORE.Law-Claw` (and, in time, in each future Vertical CORE) and remain there at certification. The public statement here records the shape of Vertical CORE Law feature movement since the v0.01 publication of this ROADMAP, so that readers reasoning about UniCORE's architectural position can see how the surrounding programme has matured — without conflating Vertical CORE features with substrate scope.

**What has locked at the Vertical CORE Law layer since v0.01 publication:**

- **Multi-payor billing model.** A v1.0 capability supporting four bill patterns (one matter → one payor; many matters → one payor; one matter → many payors; many matters → many payors), a Payor model distinguishing client-rows from payor-rows, percentage-only allocation policy with per-bucket independent rounding, snapshot-at-bill-creation immutability, Lead Matter mechanics with auto-select rule and operator override, proportional tax-and-discount split, and an invariant guard that holds the one-bill-one-tax-jurisdiction rule.
- **Multi-jurisdiction VAT resolver engine.** A v1.0 capability covering the UK and EU VAT regimes, US sales-tax regimes (state-level), and the seed-data files for the supported jurisdictions (UK, FR, DE, NL, US-CA, US-DC, US-IL, US-NY, US-TX). The resolver engine is jurisdiction-aware, evidence-bound, and integrated with the bill-allocation pipeline above.
- **Protected-bank-detail workflow.** A v1.0 capability covering the lifecycle and workflow-approval controllers for protected bank-detail material, with field-cipher protection, sovereignty-principle preservation (customer holds the keys), and an evidence trail at the BO-graph level.

**What has not changed at the substrate layer since v0.01 publication:**

- The certification trigger condition is unchanged. Source code arrives at certification; the badge ("Powered by UniCORE AI / built on the TrueAI Foundation") remains the gate.
- The substrate-only / Vertical-CORE-elsewhere boundary is unchanged. Vertical CORE Business Objects continue to live in each Vertical CORE; UniCORE carries the cross-vertical substrate layer only.
- The CC BY 4.0 licence terms are unchanged and remain irrevocable.
- The Continuous-publication shape (every release of UniCORE substrate from any Vertical CORE working repository mirrors here on push, post-certification) is unchanged.

**Why this sub-section exists.** The substrate scope is what publishes here at certification. The Vertical CORE feature surface is what publishes in each Vertical CORE's own commercial repository (e.g. `UniCORE.Law` for the Law vertical). Recording, in a public-statement form, that Vertical CORE Law features have locked at v1.0 between v0.01 and certification — without claiming those features as part of UniCORE substrate scope — keeps the layer boundary visible. The discipline is part of the gift principle: keep the architectural surface honest about what is gift-layer (the substrate, here) and what is commercial-layer (the Vertical CORE features, elsewhere).

For the parallel public statement on UniCORE.GVB substrate-scope evolution since v0.01 publication, see [`UniCORE.GVB`'s ROADMAP](https://github.com/bryanunitek/UniCORE.GVB/blob/main/ROADMAP.md) §"Substrate scope evolution since v0.01 publication". The two sub-sections are parallel-shape: GVB-side records substrate-scope movement; UniCORE-side records Vertical-CORE-feature-lock movement.

---

## SaaS deployment shape

Since the v0.01 publication of this ROADMAP, the **SaaS-deployment-shape sister** of UniCORE has been published:

- [`UniSaaS.UniCORE`](https://github.com/bryanunitek/UniSaaS.UniCORE) — the same implementation reference, surfaced for the multi-tenant SaaS topology rather than the on-premise topology.
- [`UniSaaS.UniCORE.GVB`](https://github.com/bryanunitek/UniSaaS.UniCORE.GVB) — the same substrate-services layer, surfaced for the SaaS topology.

The deployment shape is the only thing that distinguishes UniSaaS.UniCORE from UniCORE. The governance is the same. The Foundation invariants are the same. The 12-Level reference architecture is the same. The certification gate is the same. Three SaaS operator positions exist: Hosted SaaS, Private SaaS, and Self-hosted — the gift surface is uniform across all three.

---

## Versioning of this document

| Version | Date | Notes |
|---|---|---|
| v1.0 | May 2026 | First publication. Repository created public; certification trigger recorded; source code held until first Vertical CORE certification. |

Revisions tracked in git history.

---

## Contact

- **Public discussion:** [GitHub Discussions](https://github.com/bryanunitek/UniCORE/discussions)
- **Private contact / connection request:** [LinkedIn](https://www.linkedin.com/in/bryan-fred-02209753/)

— Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom, May 2026.

---

## Document history

- 2026-05-21 (3b13258) — docs: initial v0.01 — public canonical home for UniCORE
- 2026-05-31 (0256a2f) — docs(ROADMAP): add Vertical CORE feature notes paragraph + "Vertical CORE feature locks since v0.01 publication" sub-section (Sanity Checkpoint #010 Action 8)
- 2026-06-03 (3b979f1) — docs: add UniSaaS sister repos + SaaS deployment shape section

*Back-filled from git log on 2026-07-10 21:33 UTC. Kind 2 versioning (dated change notes) — see HORIZON.md § Evolution and versioning. Kind 1 (formal `Version:` bumps) remains OFF until first GitHub Discussion.*
