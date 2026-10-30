# 🧭 GrantOS — Operating Model

**Version:** 1.0 · **Snapshot:** 2026-10-30

## 1. Product thesis

GrantOS is not merely a directory of grants. It is a portfolio operating system connecting:

Project → Funding Thesis → Opportunity → Work Package → Verifiable Evidence → Application / Payout → Impact → Reinvestment

It answers: what is fundable, who funds it, what exact work capital purchases, how delivery is verified, and what obligations follow the award.

**Principle:** finance a bounded outcome, not an abstract ambition.

## 2. Portfolio separation

| Class | Examples | Suitable capital | Boundary |
|---|---|---|---|
| Open public goods | reusable schemas, libraries, docs, public datasets | ecosystem grants, QF, donations, retroactive funding | outputs remain accessible under a declared license |
| Research & validation | experiments, evaluations, simulations, reproducibility | research grants, RFPs, academic calls | methods, negative results and limitations are disclosed |
| Commercial product | hosted services, proprietary workflows, enterprise integrations | customer pilots, revenue, accelerators, investment | do not disguise private product development as public-good work |
| Shared infrastructure | CI, observability, common connectors | transparent cost allocation | shared costs use a documented allocation rule |
| Contributor compensation | implementation, review, testing, documentation | bounties, grant budget lines, sponsorship | acceptance criteria and payment terms are explicit |

A repository may contain several classes. Eligibility attaches to a work package and its outputs, not automatically to the whole repository.

## 3. Core entities

- Project: initiative/repository, owner, maintainers, stage, license and dependencies.
- Funder: organization, official URL, ecosystem, jurisdiction and contact route.
- Program: named round/call, mechanism, status, deadline, ticket range and restrictions.
- Opportunity: a specific project-program fit assessment.
- WorkPackage: bounded scope, deliverables, acceptance tests, estimate, owner and dependencies.
- Evidence: artifact URL/hash, type, timestamp, reviewer, reproducibility and adoption proof.
- Application: narrative, budget, milestones, requested amount, submitted version and status.
- Award: amount, currency, schedule, conditions, reporting and conflicts.
- Allocation: link from a cost/deliverable to exactly one funding source or an explicitly apportioned shared-cost rule.
- ImpactClaim: observed outcome, measurement method, baseline, period and corroboration.

## 4. Opportunity lifecycle

DISCOVERED → TRIAGED → QUALIFIED → PACKAGED → READY → SUBMITTED → DILIGENCE → AWARDED / REJECTED → DELIVERING → VERIFIED → CLOSED

Alternative states: PAUSED, EXPIRED, WITHDRAWN, INELIGIBLE.

Program status:
- OPEN: official source confirms applications are accepted.
- UPCOMING: official source announces a future window.
- ROLLING: official source explicitly accepts rolling submissions.
- PAUSED / CLOSED: official source confirms pause or closure.
- UNKNOWN: not confirmed; never present as open.

Every status record includes checked_at, source_url and a note. Aggregators are discovery leads, not status evidence.

## 5. Qualification gate

Before scoring, check:
1. Eligibility: geography, entity/person requirements, KYC and restrictions.
2. Scope: proposed work is within the funder's mandate.
3. License/IP: ownership and open-source obligations are understood.
4. Conflict: no duplicate claim, overlapping budget or undisclosed co-funding.
5. Capacity: credible owner, timeline, delivery and reporting capacity.
6. Integrity: no fabricated traction, users, partnerships, impact or token utility.

If a hard gate fails, mark INELIGIBLE or HOLD. A high score cannot offset failed eligibility.

## 6. Prioritization score

S = 0.25F + 0.20E + 0.20P + 0.15T + 0.10R + 0.10C

Each factor is scored 0–5:
- F — Fit with the funder's explicit thesis.
- E — Evidence maturity: demo, tests, users, adoption and docs.
- P — Eligibility clarity and credible selection path.
- T — Timing and preparation window.
- R — Expected net value relative to application and delivery effort.
- C — Composition: reputation, integrations, reusable outputs and future options.

Keep risk flags outside the score: compliance, token obligations, volatility, reporting, IP restrictions, counterparty concentration and opportunity cost.

## 7. Funding stack and anti-double-counting

- Bounty: one accepted task; small, short-cycle compensation.
- Milestone grant: prospective capital for a defined ecosystem deliverable.
- Research grant: method, investigation, dataset or reproducibility.
- QF / crowdfunding: distributed support from a real community.
- Retroactive funding: demonstrated impact where an active program explicitly supports it.
- Accelerator / investment: commercial growth and potential return.
- Customer revenue: paid pilot, API, hosting, support, integration or license.

Each cost line has a unique allocation ID. Shared infrastructure is apportioned transparently. The same hours, deliverable or invoice cannot be charged twice. Co-funding is allowed only when terms permit it and allocation is disclosed.

## 8. Evidence ladder

| Level | Meaning | Minimum proof |
|---|---|---|
| L1 — Declared | activity reported | dated statement and scope |
| L2 — Observed | artifact exists | issue, commit, release or document |
| L3 — Reviewed | independent review | accepted PR, review or test report |
| L4 — Reproduced | behavior can be repeated | CI, reproducible steps, demo or replication |
| L5 — External impact | outside use or benefit | integration, downstream dependency, user confirmation or measured outcome |

Attention metrics are discovery indicators, not contribution or impact evidence.

## 9. Operating cadence

**Weekly:** refresh official program status; triage opportunities; advance one or two work packages; publish evidence log; reconcile costs.

**Per application:** freeze scope and budget; map milestones to evidence and acceptance; record official rules; archive submitted narrative and attachments.

**Per award:** create delivery and reporting checklists; record disbursements and restrictions; verify milestone acceptance; publish permitted outcomes.

## 10. Initial execution priorities

1. ValueCurator / ProofGate: package existing Devnet work as a bounded Solana security/tooling work package; separate public SDK/policy examples from commercial services.
2. Farcaster Commons Lab: run one measurable experiment converting one conversation into one accepted GitHub contribution; do not claim ecosystem-scale impact before measurement.
3. Compilatum / Promptcraft: extract one reusable OSS module with tests, docs and external-user evidence.
4. Lakehouse / Oracle: propose a narrow data/indexing or provenance adapter only where the target ecosystem actually uses the stack.
5. PixelCoin / funding rails: treat as research/prototype until user problem, threat model and non-speculative utility are validated.
6. AROS / audio biofeedback: pursue science, health-tech or applied-research calls; crypto grants are secondary absent a real ecosystem integration.

## 11. Non-goals

GrantOS does not guarantee funding, provide legal/tax advice, imply token liquidity, automate eligibility decisions, or convert reputation into a financial claim. A score ranks research effort; it does not predict selection.

> **Filosofema:** Capital should follow verifiable value; evidence should outlive the funding round; every funded output should clarify what becomes reusable by others.
