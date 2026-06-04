UniCORE is the public foundation for advanced AI.

We design the governance, write the code, and train the people who can do both. The foundation is gifted to humanity under permissive licences. The producers who maintain it earn their authority through a 30-year apprenticeship: not bought, not granted, earned.

The result is infrastructure no single company can monopolise, built and maintained by people from every background.

The future is coming. Advanced AI will shape the world ahead, whether we are ready or not. The question is who builds it, who controls it, and who benefits. UniCORE answers all three the same way: humanity does.

If you want to spend a career building advanced AI for humanity rather than for shareholders, UniCORE is the path.

A 30-year programme from apprentice to certified producer. A public foundation given away under permissive licences. No monopoly. The work belongs to everyone, including you.

---

*This is **UniCORE**, the implementation reference layer of the programme. It is the working code substrate that satisfies the [UniCORE AI](https://github.com/bryanunitek/UniCORE-AI) 12-Level reference architecture, which itself satisfies the [TrueAI](https://github.com/bryanunitek/TrueAI) Foundation. Sister repositories: [UniVERSE](https://github.com/bryanunitek/UniVERSE) (the programme), [TrueAI](https://github.com/bryanunitek/TrueAI) (the immutable Foundation), [UniCORE-AI](https://github.com/bryanunitek/UniCORE-AI) (the 12-level reference architecture).*

*New to producing on the public gift surface? Start with [UniVERSE/GETTING_STARTED.md](https://github.com/bryanunitek/UniVERSE/blob/main/GETTING_STARTED.md).*

---

# UniCORE

**The implementation reference for governed, human-sovereign artificial intelligence.**

Author: Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom
First published: May 2026
Status: Public. Given, not sold. Irrevocable.

---

## What is UniCORE?

UniCORE is the **implementation reference** for the programme — the working code substrate that any Vertical Solution may build upon when it is built to satisfy the TrueAI Foundation invariants and the UniCORE AI 12-Level reference architecture.

It sits in the Layered CORE model at **Level 2 ↔ Level 3** — between the universal architecture (UniCORE AI) and the Vertical CORE specific to a sector (e.g. UniCORE.Law, UniCORE.Accounting, UniCORE.Banking). UniCORE is what a Vertical CORE inherits FROM. The Vertical CORE then carries the industry-specific Business Objects on top.

When a Vertical Solution is **certified Powered by UniCORE AI / built on the TrueAI Foundation**, the UniCORE substrate it stands on is published here, on this repository, under CC BY 4.0. The Vertical CORE remains in its own repository (e.g. `bryanunitek/UniCORE.Law-Claw` for the Law sector) and carries its industry-specific Business Objects there.

UniCORE is the gift layer. The Vertical Business Objects are the commercial layer. Both can co-exist; the gift can never be enclosed.

---

## Why this repository exists today

This repository exists today as the **canonical public home** for UniCORE — the place where its identity, licence, roadmap, and naming rules are recorded.

**The source code is not yet published here.** Source code is published when the first Vertical CORE that uses UniCORE — `UniCORE.Law-Claw` — is certified Powered by UniCORE AI / built on the TrueAI Foundation. See [ROADMAP.md](ROADMAP.md) for the trigger condition and what arrives at that point.

What is published here today:

- **The licence** — CC BY 4.0, irrevocable, the same terms as the rest of the programme. See [LICENSE.md](LICENSE.md).
- **The licensing reference with worked scenarios** — plain-English guidance for Partners, Clients, and Software Providers, with worked examples per industry. See [LICENSE_EXAMPLES.md](LICENSE_EXAMPLES.md).
- **The naming and claims rules** — what can and cannot be claimed about the UniCORE name. See [STATEMENT-ON-CLAIMS.md](STATEMENT-ON-CLAIMS.md).
- **The roadmap** — what arrives at certification and in what shape. See [ROADMAP.md](ROADMAP.md).
- **The AI authorship disclosure** — same disclosure form as the Foundation triad. See [AI-AUTHORSHIP.md](AI-AUTHORSHIP.md).
- **The agent rules** — how Claws working on this repository conduct themselves. See [AGENTS.md](AGENTS.md).

The repository will accumulate documentation between now and certification. Source code arrives at certification.

---

## The Layered CORE position

UniCORE sits within the **Layered CORE model** ([`UniVERSE/docs/00057-Layered-CORE-Model.md`](https://github.com/bryanunitek/UniVERSE/blob/main/docs/00057-Layered-CORE-Model.md)).

```
Level 1 CORE — TrueAI Foundation       (universal, immutable, gift)
                  ↑
Level 2 CORE — UniCORE AI              (universal architecture, gift)
                  ↑
Level 2 ↔ 3   — UniCORE                (THIS REPO — implementation reference, gift)
                  ↑
Level 3 CORE — Vertical CORE           (industry-specific reference, gift)
               (e.g. UniCORE.Law, UniCORE.Accounting,
                UniCORE.Banking, UniCORE.Healthcare,
                UniCORE.Government, UniCORE.Space-Industry)
                  ↑
Solutions tier — Working implementations (services-built, sellable)
```

A derivative of CORE is itself CORE and is itself gifted. This is **gift propagation**. Vertical COREs are CORE. The Solutions tier is not CORE; Solutions are services-built deliverables produced by Generation IT pairs on top of the relevant CORE layers.

---

## The certification trigger

The trigger that moves UniCORE from this repository's documentation-only state to documentation-plus-code state is:

> The first Vertical CORE built on UniCORE — `UniCORE.Law-Claw` — is certified **Powered by UniCORE AI / built on the TrueAI Foundation**.

When that certification is recorded, the UniCORE substrate inside `UniCORE.Law-Claw` is extracted and published here under CC BY 4.0. The Law Business Objects remain in `UniCORE.Law-Claw` as the commercial Vertical CORE layer.

The same gift principle then applies to every future Vertical CORE: when a Vertical CORE is certified, its UniCORE-conformant substrate is already published here for everyone, and the vertical's industry-specific Business Objects sit in the vertical's own repository.

The certification is the gate. The gate exists because the gift must mean something; the badge cannot be self-applied.

---

## Platforms and UI Surfaces

UniCORE runs on **Windows, Linux, macOS, iOS, and Android**.

Three primary UI surfaces deliver the full platform reach:

| Surface | Technology | Platforms | Role |
|---|---|---|---|
| **DevExpress Blazor Server** | .NET 10 + XAF + XPO | Windows, Linux, macOS (via browser) | Primary web UI — the main operational surface |
| **.NET MAUI** | .NET 10 | Windows, macOS, iOS, Android | Native mobile + desktop |
| **Avalonia** | .NET 10 | Windows, Linux, macOS | Cross-platform native desktop |

Additional optional surface:

| Surface | Technology | Platforms | Role |
|---|---|---|---|
| **WinForms (*.Win)** | .NET 10 + DevExpress | Windows only | Optional power-user desktop surface (ships alongside Blazor) |

The Blazor Server surface is the governance-primary UI — all administrative, operational, and Vertical CORE business-object workflows are available through it. MAUI and Avalonia extend reach to native mobile and native Linux desktop respectively. WinForms remains as an optional Windows-only surface for power users who prefer a native Windows experience alongside Blazor.

All four surfaces share the same substrate-services layer (UniCORE.GVB), the same 12-Level Governance Model, and the same Foundation invariants. The UI surface is a delivery choice; governance is invariant across all of them.

---

## UniCORE.Desktop — client applications

UniCORE.Desktop provides the desktop client applications for the UniCORE family. These applications connect to services running on UniCORE.GVB and/or UniCORE. They are not products for sale — they are included with the UniCORE licence (CC BY 4.0), part of the same gift.

UniCORE.Desktop must independently pass the "Powered by UniCORE AI / built on TrueAI Foundation" certification gate.

Client applications (scope):

- **File transfer client** — secure file send/receive, filedrop upload, filelink management, download tracking
- **FTP / SFTP client** — file access to GVB-hosted storage, bookmark management, transfer queue
- **Mail configuration** — auto-configuration of desktop mail clients against GVB mail services
- **Calendar and contacts sync** — CalDAV/CardDAV client integration, offline sync, conflict resolution
- **Office integration** — document workflows connecting desktop productivity suites to UniCORE services
- **AI Chat** — governed AI assistant operating under TrueAI governance, connected to UniCORE AI services
- **Identity and authentication** — desktop-side identity provider, certificate-based authentication, 2FA integration
- **GVB API client** — typed HTTP client for the UniCORE.GVB substrate API, used by all other desktop applications
- **VPN / tunnel client** — secure connectivity to GVB nodes, jurisdictional routing
- **Backup client** — desktop-side backup agent connecting to GVB backup services
- **Admin console** — desktop administration interface for node operators and tenant administrators
- **VM management client** — desktop interface for hypervisor operations (VM lifecycle, snapshots, migration)
- **DNS management client** — zone and record management interface
- **Monitoring dashboard** — desktop-side observability client (bandwidth, storage, service health)

UniCORE.Desktop is documented in both this repository and [`bryanunitek/UniCORE.GVB`](https://github.com/bryanunitek/UniCORE.GVB) because the applications serve both layers. At certification, UniCORE.Desktop publishes as its own repository (`bryanunitek/UniCORE.Desktop`) with cross-references from both.

The working repository is `bryanunitek/UniCORE.Desktop-Claw` (private until certification).

---

## UniVIEW and UniREPORT — view and reporting applications

UniVIEW and UniREPORT follow the same pattern as UniCORE.Desktop. They are application surfaces that serve both UniCORE and UniCORE.GVB:

- **UniVIEW** — view-layer applications, presenting governed data from the substrate-services and Vertical CORE layers. Read-mode user surface; no business-logic mutation.
- **UniREPORT** — reporting-layer applications, generating governed reports across the same data. Evidence-bound output suitable for regulated reporting contexts.

Like UniCORE.Desktop, both:

- Are not products for sale — they are included with the UniCORE licence (CC BY 4.0), part of the same gift.
- Must independently pass the "Powered by UniCORE AI / built on TrueAI Foundation" certification gate.
- Are documented in both `bryanunitek/UniCORE` and `bryanunitek/UniCORE.GVB` because they serve both layers.
- Publish as their own repositories at certification (`bryanunitek/UniVIEW`, `bryanunitek/UniREPORT`) with cross-references from both.

The working repositories are `bryanunitek/UniVIEW-Claw` and `bryanunitek/UniREPORT-Claw` (private until certification).

---

## NVarchar Data Mode — Open, Scrambled, Encrypted

All NVARCHAR (string) data across the UniCORE substrate is governed by a three-mode architecture:

| Mode | Default | Description |
|---|---|---|
| **Scrambled** | ✅ Yes | Reversibly scrambled storage. Prevents casual database inspection. The owning system’s scramble key is required to read. |
| **Open** | | Plain text. Used where scrambling is operationally inappropriate (e.g. full-text search indexes). |
| **Encrypted** | | Field-level encryption. Future feature (reserved). The customer holds the decryption key (sovereignty principle). |

**Default posture: Scrambled.** All string fields arrive Scrambled unless explicitly resolved otherwise by a policy chain. The resolution cascade is: Workload → Tenant → Product → Default (Scrambled).

This is a substrate-level concern. Both the on-prem UniCORE and the SaaS UniSaaS.UniCORE deployments enforce the same posture. The enum, resolver interface, policy store, and default resolver live at the GVB substrate layer (`UniCORE.GVB.Common`) so that every Vertical CORE inherits the data-mode posture without re-implementing it.

---

## 10-Level Mass Data Generation

The SaaS deployment shape includes a **10-level bootstrap seeder** that provisions the foundational user and role hierarchy per UniVERSE Foundation Document 45/54:

| Level | Code | Name | AI Mode |
|---|---|---|---|
| 1 | 0001 | UniCORE-Global | GlobalAIMode |
| 2 | 0002 | UniCORE-GlobalVirtualBridge | GlobalVirtualBridgeAIMode |
| 3 | 0003 | UniCORE-Continental | ContinentalAIMode |
| 4 | 0004 | UniCORE-Regional | RegionalAIMode |
| 5 | 0005 | UniCORE-State | StateAIMode |
| 6 | 0006 | UniCORE-DataCentre | DataCentreAIMode |
| 7 | 0007 | UniCORE-Platform | PlatformAIMode |
| 8 | 0008 | UniCORE-Product | ProductAIMode |
| 9 | 0009 | UniCORE-Deployment | DeploymentAIMode |
| 10 | 0010 | UniCORE-Tenant | TenantAIMode |

Each level seeds one bootstrap user and one paired role. The seeder is idempotent. Default NVarchar posture for all seeded data: **Scrambled**.

Levels 11 (RoleAIMode) and 12 (UserAIMode) remain in the per-tenant operational database — they are not bootstrap-level.

---

## Intelligent Integration Controller

The Intelligent Integration Controller (IIC) is the integration and data-movement subsystem of UniCORE. It provides secure messaging, secure file transfer manifests, and governed data exchange between systems — the integration spine that a Vertical CORE uses to connect to external systems (practice management, document management, billing, etc.) without exposing raw data paths.

The IIC is built as a standalone service layer within the Vertical CORE working repository. At certification, the IIC interfaces and contracts become part of the UniCORE gift surface (CC BY 4.0).

**Integration / Import from 3rd-party systems:**

The IIC includes a connector architecture for importing data from established practice-management and billing systems. The first production connector is **Aderant Expert** — a legacy system used by global law firms. The connector provides:
- `AderantIntegrationTransactionAdapter` — transaction-level data import
- `AderantRunProjectionService` — run-projection and workload planning
- `AderantWorkloadHandler` — workload execution for governed import pipelines

The connector pattern is repeatable: future connectors for other systems (Elite, Aderant iManage, 3E, etc.) follow the same interface shape.

The working code lives in `bryanunitek/UniCORE.Law-Claw` (the first Vertical CORE), structured as:
- `UniCORE.Law.IntelligentIntegrationController.Abstractions` — contracts and DTOs
- `UniCORE.Law.IntelligentIntegrationController.Core` — interfaces, services, resolver
- `UniCORE.Law.IntelligentIntegrationController.Persistence` — store implementations
- `UniCORE.Law.IntelligentIntegrationController.Service` — the hosted service entry point
- `UniCORE.Law.IntelligentIntegrationController.Connectors.Aderant` — Aderant Expert connector

---

## UniCORE Positioning Principle

The programme is positioned as **Harmony, Peace, Space Exploration, for Humanity**.

Industries and uses that align with this positioning are welcome. Those that do not are not. **Military uses are intentionally absent** from the programme and will not be added.

**The "Powered by UniCORE AI" and "built on TrueAI Foundation" certifications must not appear on any military use.** The badge is part of the gift, and the gift is meant for Harmony, Peace, Space Exploration, for Humanity — using the badge to brand weapons-class systems would invert the gift principle. The positioning closes that route.

This is a structural choice, not a marketing choice. The programme exists to keep critical decision systems available to humanity as gift.

---

## Related repositories

**The Foundation triad:**
- [`UniVERSE`](https://github.com/bryanunitek/UniVERSE) — The civilisational-scale programme. Whitepapers, governance, outreach.
- [`TrueAI`](https://github.com/bryanunitek/TrueAI) — The immutable Foundation. Nine Invariants. Small. Stable. Never commercial.
- [`UniCORE-AI`](https://github.com/bryanunitek/UniCORE-AI) — The 12-Level reference architecture.

**The substrate-services layer:**
- [`UniCORE.GVB`](https://github.com/bryanunitek/UniCORE.GVB) — Global Virtual Bridge — the substrate-services layer (mail, file transfer, DNS, federation, tenancy, topology). Sister to this repository. Same certification gate. Same gift principle.

**The SaaS-deployment-shape sisters:**
- [`UniSaaS.UniCORE`](https://github.com/bryanunitek/UniSaaS.UniCORE) — The SaaS-deployment-shape sister of this repository. Same governance, multi-tenant topology. CC BY 4.0 gift surface.
- [`UniSaaS.UniCORE.GVB`](https://github.com/bryanunitek/UniSaaS.UniCORE.GVB) — The SaaS-deployment-shape sister of UniCORE.GVB. Substrate-services layer for the SaaS topology. CC BY 4.0 gift surface.

**The Vertical CORE family (working repositories — private until certification):**
- `bryanunitek/UniCORE.Law-Claw` — First Vertical CORE, Law sector. Working repository. Certification pending.
- Future: `UniCORE.Accounting-Claw`, `UniCORE.Banking-Claw`, `UniCORE.Healthcare-Claw`, etc., as additional verticals are produced. The industry list is open and is defined as the programme expands. Military is intentionally absent — the UniCORE Positioning Principle is Harmony, Peace, Space Exploration, for Humanity.

**Forked-upstream building-block families (scaffold-anchor as of 2026-06-04 — full scaffolding and upstream fork pending dedicated kickoff arcs):**
- [`UniCORE.Avalonia`](https://github.com/bryanunitek/UniCORE.Avalonia) — Cross-platform .NET UI substrate. Fork of MIT Avalonia + UniCORE CC BY 4.0 additions (Pro-equivalent controls + Avalonia XPF).
- [`UniSaaS.UniCORE.Avalonia`](https://github.com/bryanunitek/UniSaaS.UniCORE.Avalonia) — SaaS-deployment-shape sister of UniCORE.Avalonia.
- `bryanunitek/UniCORE.Avalonia-Claw` (private) — on-prem-shape working repository for UniCORE.Avalonia.
- `bryanunitek/UniSaaS.UniCORE.Avalonia-Claw` (private) — SaaS-shape working repository.
- [`UniCORE.DNN`](https://github.com/bryanunitek/UniCORE.DNN) — Web CMS / portal building block. Fork of MIT Dnn.Platform + UniCORE CC BY 4.0 modules.
- [`UniSaaS.UniCORE.DNN`](https://github.com/bryanunitek/UniSaaS.UniCORE.DNN) — SaaS-deployment-shape sister of UniCORE.DNN.
- `bryanunitek/UniCORE.DNN-Claw` (private) — on-prem-shape working repository for UniCORE.DNN.
- `bryanunitek/UniSaaS.UniCORE.DNN-Claw` (private) — SaaS-shape working repository.


---

## Attribution

> Powered by UniCORE AI.
> Built on the TrueAI Foundation.

Attribution required wherever UniCORE, UniCORE AI, the TrueAI Foundation, or the 12-Level Governance Model is referenced, implemented, or extended.

---

## Licence

Given, not sold. The architecture is public, open, and free. The TrueAI Foundation cannot be modified, forked, commercialised, patented, or proprietarily captured. See [LICENSE.md](LICENSE.md) for full terms; see the canonical [`UniVERSE/IRREVOCABLE-LICENCE-DECLARATION.md`](https://github.com/bryanunitek/UniVERSE/blob/main/IRREVOCABLE-LICENCE-DECLARATION.md) for the formal irrevocability declaration that covers the whole programme.

— Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom, May 2026.

---

## AI authorship

This repository is produced with AI assistance operating under TrueAI governance. The full disclosure is at [AI-AUTHORSHIP.md](AI-AUTHORSHIP.md).

---

## Discuss and contribute

Programme-level debate, adoption questions, translation, and corrections belong in [GitHub Discussions](https://github.com/bryanunitek/UniCORE/discussions). What is in scope: questions about UniCORE's role in the Layered CORE model, the certification gate, the relationship to Vertical COREs, the gift principle as it applies to substrate code. What is out of scope: implementation specifics that belong inside a particular Vertical CORE's own repository.

For Foundation-level debate (the invariants themselves, the architecture, civilisational governance), use [UniVERSE Discussions](https://github.com/bryanunitek/UniVERSE/discussions), [TrueAI Discussions](https://github.com/bryanunitek/TrueAI/discussions), or [UniCORE-AI Discussions](https://github.com/bryanunitek/UniCORE-AI/discussions) as appropriate.

---

## Classification, brand, and claims

UniCORE is the implementation reference for governed AI. It is not a product, platform, SaaS offering, tool category, or brand for sale. See [STATEMENT-ON-CLAIMS.md](STATEMENT-ON-CLAIMS.md) for binding rules on how the UniCORE name may and may not be used.

---

## Contact

- **Public discussion:** [GitHub Discussions](https://github.com/bryanunitek/UniCORE/discussions) (see [DISCUSSIONS.md](DISCUSSIONS.md))
- **Private contact / connection request:** [LinkedIn](https://www.linkedin.com/in/bryan-fred-02209753/)
