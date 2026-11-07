# Karma Platform Playbook — GrantOS Portfolio

**Prepared:** 2026-11-07  
**Purpose:** Convert the Compilatorum portfolio into clear, evidence-backed Karma project profiles, milestones, updates and impact records.  
**Status:** Draft for owner review before publication. This repository is the source of truth for copy and evidence links; Karma is the public project-reputation and funding surface.

## 1. Platform model

Karma (formerly Karma GAP) is more than a grant-update page. Its current product combines project profiles, funding/program workflows, milestones, project updates, impact measurement and fund distribution. Use only the modules available to the account and relevant to the project.

**Division of responsibilities**

| Surface | System of record |
|---|---|
| GitHub | Source code, issues, releases, tests, technical decisions and immutable artifact links |
| Karma | Public project profile, grants, milestones, progress updates, impact criteria and project history |
| Farcaster | Community discovery, invitations, discussion and contributor acquisition |
| GrantOS / this repository | Portfolio strategy, opportunity qualification, work-package decomposition, funding ledger and evidence reconciliation |
| Questbook / other funder portals | Application submission and program-specific reporting when required |

Do not recreate Karma's project registry or grant tracking inside GrantOS. GrantOS prepares, reconciles and routes the information.

## 2. Portfolio structure to create in Karma

Create separate project profiles rather than one umbrella profile. A profile should represent a coherent project with a distinct problem, users, deliverables and evidence trail.

### Priority 1 — ValueCurator / ProofGate / KAIROS

**Public name:** ValueCurator — Verifiable Policy & Safe Execution Infrastructure  
**Short description:** Open infrastructure for safer AI-assisted financial operations, combining evidence-aware data inputs, deterministic policy checks, explicit human authorization and auditable execution boundaries.

**Problem:** Autonomous and AI-assisted financial systems can act on stale or low-confidence data, excessive risk, ambiguous permissions or compromised execution paths.  
**Approach:** Separate observation, recommendation, authorization, signing and execution into explicit states. Use deterministic policy gates, provenance-aware inputs and reproducible tests.  
**Public-good outputs:** Open SDK/components, schemas, policy examples, test harnesses, threat model and integration documentation.  
**Commercial boundary:** Hosted services, bespoke integrations and managed operations must be separately scoped and funded as commercial work.  
**Stage:** Research / prototype / integration validation. Do not describe as production-ready or independently audited unless new evidence proves it.  
**Primary ecosystem fit:** Solana tooling and security, conditional on a real Solana integration and current program eligibility.

### Priority 2 — Farcaster Commons Lab / IPIT

**Public name:** Farcaster Commons Lab — Conversation-to-Contribution Experiment  
**Short description:** An open experiment that turns social discussion into accepted, reusable public-repository contributions with transparent provenance and evidence.

**Problem:** Online attention and discussion are rarely converted into well-scoped, reviewable work that ecosystems can reuse or fund.  
**Approach:** Publish small work packages, invite contributors through Farcaster, accept work through GitHub review, record evidence and evaluate reuse.  
**Public-good outputs:** Contribution protocol, evidence schema, experiment reports, reusable documentation and open-source artifacts.  
**Stage:** Experimental pilot. Do not claim ecosystem-wide adoption or causal impact before collecting a baseline and results.  
**Primary ecosystem fit:** Open-source public goods, community funding, developer communities and contribution infrastructure.

### Priority 3 — Nodespace / DAO Embassy

**Public name:** Nodespace — Agentic Coordination & DAO Embassy Infrastructure  
**Short description:** A research and prototyping initiative for structured coordination among people, AI agents and institutions, with explicit roles, provenance, commitments and contribution records.

**Problem:** Multi-party and agent-assisted collaboration lacks portable context, clear authority boundaries and a reliable path from conversation to accountable action.  
**Approach:** Prototype an embassy/registry model, structured diplomatic inbox, role and mandate definitions, conversation-to-contribution workflows and auditable commitments.  
**Public-good outputs:** Governance and coordination schemas, open specifications, prototype workflows and case studies.  
**Stage:** Exploratory / specification-led until a working pilot is demonstrated.  
**Primary ecosystem fit:** Decentralized coordination, open governance, agentic infrastructure and digital public goods.

## 3. Profile publishing checklist

Before publishing each profile:

- [ ] Confirm project name, owner/maintainers and public contact route.
- [ ] Add canonical repository and project URLs.
- [ ] State current stage honestly: idea, specification, prototype, alpha, pilot or production.
- [ ] Add license only after checking the repository's actual license.
- [ ] Add team members only with their consent and confirmed roles.
- [ ] Link only real demos, deployments, contracts, datasets and publications.
- [ ] Separate completed work from planned work.
- [ ] Add a concise problem, approach, outputs and intended beneficiaries.
- [ ] Define impact criteria with baseline, unit, collection method and reporting period.
- [ ] Add grant records only when an award or application is real and accurately labelled.
- [ ] Do not imply Karma endorsement, funding, partnership or verification merely by creating a profile.

## 4. Grant and milestone discipline

Every grant-funded work package should have:
1. A bounded deliverable.
2. A start/end window and accountable owner.
3. Acceptance criteria that an independent reviewer can check.
4. Evidence links (PR, release, demo, test report, dataset or deployment).
5. A budget and explicit funding allocation.
6. Risks, dependencies and exclusions.
7. A clear public-good/commercial boundary.

Prefer milestones shorter than one quarter. For larger outcomes, create parent outcomes and smaller independently verifiable milestones. Do not create artificial milestones merely to make a project look active.

## 5. Update cadence

- Publish an update when a meaningful artifact changes state: specification accepted, feature implemented, test passed, demo deployed, integration used, or external reuse confirmed.
- Add periodic updates only when there is substantive progress or a useful blocker/learning to disclose.
- Include what changed, evidence, impact observed, next step and risks.
- If there is no progress, do not manufacture an update.
- Distinguish outputs (commits, releases, tests) from outcomes (users, integrations, reduced failure, external reuse).

## 6. Evidence and impact

Use the repository's evidence ladder:
- L1 Declared: dated activity statement.
- L2 Observed: public artifact exists.
- L3 Reviewed: independent review or accepted contribution.
- L4 Reproduced: repeatable test, demo or replication.
- L5 External impact: independent integration, reuse or measured ecosystem benefit.

Karma impact measurement should follow:
**Funding → Activities → Outputs → Outcomes → Indicators**

For software, possible outputs include merged PRs, releases, tests and deployed integrations. Possible outcomes include active integrations, recurring users, reduced failure rates or downstream reuse. Do not use commit count or social engagement as a substitute for impact.

## 7. Funding integrity

- A project profile is not a grant application and does not establish eligibility.
- A grant, bounty, donation, customer contract and investment are different funding instruments.
- Do not charge the same cost or deliverable to multiple funders.
- Disclose co-funding and allocate shared costs using a documented rule.
- Retroactive funding is pursued only when the specific active program permits completed work.
- Token activity is not evidence of product-market fit, impact or liquidity.

## 8. Suggested first sequence

1. Publish ValueCurator first, after verifying its current repository links and stage.
2. Publish Farcaster Commons Lab with a baseline and one tightly scoped pilot.
3. Publish Nodespace as research/specification until a demonstrable prototype exists.
4. Add one or two near-term milestones per profile, not a speculative multi-year backlog.
5. Publish the first update only when a linkable artifact or validated learning is ready.
6. Reconcile each Karma record with the GrantOS funding ledger.

## 9. Sources and product notes

Karma's own materials describe public project profiles as persistent records of funding, milestones, updates and outcomes; its impact measurement framework distinguishes activities, outputs, outcomes and indicators and can use GitHub, Dune and other data sources. Product capabilities can change, so confirm the live UI and account permissions before relying on a particular field or integration.

- https://www.karmahq.org/knowledge
- https://www.karmahq.org/blog/introducing-karma-v2
- https://www.karmahq.org/blog/revolutionizing-impact-measurement

> **Filosofema:** A profile is not a performance. It is a public memory of verifiable work. Reputation compounds when claims remain inspectable after the funding cycle ends.
