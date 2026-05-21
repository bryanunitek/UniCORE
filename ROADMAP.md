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
