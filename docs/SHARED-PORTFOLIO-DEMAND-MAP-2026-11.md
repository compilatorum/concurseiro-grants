# Shared Portfolio × Ecosystem Demand × Grant Stacking
## Supplement to the Demand-Driven GrantOS Map — 2026-11-01

> Scope: repositories owned by `smp-sandramariapereira` to which the connected GitHub account has collaborator access. This is a strategic repository-to-demand mapping, not a code, legal, scientific, security, or grant-eligibility audit.

## 1. Inventory and method

On 2026-11-01, GitHub returned **13 repositories** under the collaborator affiliation filter for `smp-sandramariapereira`. The account had pull and push permissions on the listed repositories. The inventory below is limited to those 13 accessible repositories; it does not imply ownership or authority to change their contents.

Repositories inspected:
- `aros-voice-kernel`
- `card-chat`
- `Coopetition`
- `digital-twin`
- `dupla-evolutiva`
- `EduAtlas`
- `educacao-territorios`
- `geoIA-UrbanFlow`
- `k-fofo`
- `KAIROS-Engine`
- `p-c-b-l-e`
- `structa-site`
- `valuecurator`

Evidence inspected: README files and selected linked documents. `p-c-b-l-e` uses `1-readme.md` rather than `README.md`; `dupla-evolutiva` and `educacao-territorios` currently expose only minimal README content; `p-c-b-l-e` is documentation/specification-heavy. No claim is made that every source file, branch, issue, workflow, license, or implementation was audited.

### Confidence labels
- **A — strong thematic fit:** repository README already states the problem and a plausible deliverable.
- **B — promising fit:** project concept aligns, but implementation, pilot or evidence needs validation.
- **C — exploratory:** useful research direction, but not yet a fundable work package without narrowing.

## 2. Problem → repository → funding thesis

| Ecosystem / societal problem with recurring funding demand | Shared repository | Adaptation into a fundable work package | Funding routes to investigate | Fit |
|---|---|---|---|---|
| Autonomous agents can move assets under stale data, bad quotes, excessive risk or compromised operators | `KAIROS-Engine`, `valuecurator` | Open-source policy-gate SDK; reproducible oracle freshness/confidence checks; deterministic fail-closed scenarios; signed authorization receipts; threat model and test harness | Solana Foundation grants/RFPs; Superteam Earn bounties; ecosystem security programs; relevant oracle/DEX integration calls | A |
| AI-assisted finance needs human authority, auditability and separation of advice from execution | `KAIROS-Engine`, `valuecurator` | Publish reusable owner/operator/agent permission model; add adversarial test cases; document approval ≠ execution; harden Jupiter instruction boundary before production claims | Solana ecosystem; security bounties; protocol-specific integrations | A |
| Education often rewards attendance rather than demonstrated competence; AI-assisted learning lacks verifiable assessment | `p-c-b-l-e`, `Coopetition` | Small open learning workflow: specification → build → validation → portfolio; rubric-based peer review; portable credential/attestation prototype; publish anti-gaming evaluation | Education innovation grants; digital public infrastructure; Web3 education bounties; university/industry pilots | A |
| Learners and contributors lack portable, evidence-backed reputation | `p-c-b-l-e`, `Coopetition` | Reputation core with transparent dimensions, evidence links, appeal/revocation and non-transferable attestations; avoid token-first design | Ethereum ecosystem tooling; identity/attestation calls; education research funding | B |
| Territorial education decisions rely on coarse averages and underuse geospatial evidence | `EduAtlas`, `educacao-territorios` | Reproducible municipal/sector-level data pipeline; spatial vulnerability maps; model cards; transparent recommendation baseline; pilot with public datasets | Brazilian public innovation/PD&I calls; education foundations; geospatial open-data programs; research grants | A/B |
| Public-interest geospatial systems need accessible, interoperable and privacy-aware territorial data | `geoIA-UrbanFlow`, `EduAtlas` | Open mobility data schema; citizen-validated sidewalk/cycle-path hazard reports; privacy-preserving aggregation; routing and accessibility pilot | Smart-city/mobility innovation calls; climate/urban resilience funds; Solana only for a narrowly justified data-integrity component | B |
| Urban micromobility lacks trustworthy, community-maintained data on barriers, safety and infrastructure quality | `geoIA-UrbanFlow` | Build a non-token MVP first: report → moderation/validation → geospatial layer → public dashboard; evaluate data quality and privacy before any reward mechanism | Urban innovation and climate grants; civic-tech funds; local pilots; selected public-goods programs | B |
| Regenerative agriculture lacks accessible synthetic datasets and reproducible impact indicators | `digital-twin` | Document generator methodology; publish schema, distributions, validation tests, synthetic-data utility/privacy report and benchmark; clearly label synthetic vs observed | ReFi/climate/food-systems funds; open data and research grants; agricultural innovation programs | A/B |
| Organizations need synthetic data to prototype predictive models without exposing employee-level sensitive records | `structa-site` | Publish a reproducible synthetic municipal workforce dataset specification, utility-risk evaluation, data lineage and benchmark; distinguish public-data-derived aggregates from synthetic microdata | Responsible-AI/data infrastructure grants; research partnerships; enterprise pilots (commercial, not grant-funded public-good scope) | A/B |
| Voice biofeedback lacks transparent, local-first, idiographic measurement and robust validation | `aros-voice-kernel` | Validate acoustic features against external references; device robustness matrix; consent-first protocol; offline alpha; publish non-diagnostic methods and reproducible benchmark | Digital health / assistive tech / research grants; university partnerships; privacy-preserving health-tech programs; not generic DeFi grants | A |
| Small businesses need reliable conversational commerce without fragile webhooks, data leaks or opaque AI decisions | `card-chat` | Harden webhook signature/idempotency/rate limits; add order-state tests, observability, data minimization and deployment template; measure conversion and failure rates in a real pilot | SME digitalization, applied AI, local innovation and commercial pilot funding; marketplace/WhatsApp ecosystem opportunities where available | B |
| Human–AI collaboration needs ethical methods for combining formal knowledge, local knowledge and creative production | `k-fofo` | Convert manifesto into a bounded open research toolkit: ontology patterns, provenance, consent and attribution templates, case study and reusable workshop materials | Digital humanities, responsible AI, open knowledge, cultural innovation and research residencies | C |
| Collaboration between people, agents and institutions needs clear coordination, role and governance patterns | `dupla-evolutiva`, `k-fofo` | First publish a concrete problem statement, actors, workflow and one tested prototype; define contribution/consent/IP rules before asking for funding | Research/innovation calls and collaborative pilot funding after scope is clarified | C |
| Community-based learning and civic participation need accountable mechanisms for cooperation rather than simplistic competition | `Coopetition`, `p-c-b-l-e` | Test one transparent cooperative scoring/reputation mechanism; publish fairness, sybil/gaming and appeal analysis; compare individual and team outcomes | Education, community innovation, Web3 public goods and mechanism-design research | B |

## 3. Portfolio clusters and complementary positioning

### Cluster A — Trustworthy autonomous finance
**Repositories:** `KAIROS-Engine`, `valuecurator`, plus Compilatorum's ValueCurator / ProofGate / Oracle work.

Core proposition: **AI advises; evidence proves; deterministic policy authorizes; the owner controls capital.**

Fundable slices:
1. Oracle evidence adapter and provenance.
2. Deterministic risk/policy engine.
3. Owner/operator authorization and signed receipt.
4. Security test harness and adversarial scenarios.
5. Public demo and integration guide.

Do not present Devnet custody and Mainnet read-only market evidence as one completed production transaction. Keep approval, signing, submission and confirmed execution as separate states. The Jupiter instruction trust boundary and independent audit remain explicit work items.

### Cluster B — Evidence-based learning and portable reputation
**Repositories:** `p-c-b-l-e`, `Coopetition`.

Core proposition: **learning becomes verifiable delivery, not merely participation.**

Fundable slices:
1. Specification and project workflow.
2. Assessment rubrics and peer-review protocol.
3. Reputation core with explainable dimensions.
4. Portable, revocable credentials/attestations.
5. Anti-gaming and fairness evaluation.

Do not start with a fungible reward token. First prove that work artifacts are useful, reviewable and attributable. Reputation, credential, payment and token are different objects.

### Cluster C — Territorial intelligence, mobility and education
**Repositories:** `EduAtlas`, `educacao-territorios`, `geoIA-UrbanFlow`.

Core proposition: **convert territorial data into transparent, locally useful decisions.**

Fundable slices:
1. Public data ingestion and lineage.
2. Reproducible spatial analysis.
3. Accessibility / vulnerability / mobility indicators.
4. Public dashboard and decision-support baseline.
5. Pilot with a municipality, school network or civic group.

EduAtlas is the most developed narrative in this cluster. UrbanFlow should begin with a conventional data-validation pilot; blockchain and $FLOW rewards are not prerequisites and should not be presented as validated until privacy, sybil resistance, data quality and real user demand are demonstrated.

### Cluster D — Synthetic data and regenerative impact
**Repositories:** `digital-twin`, `structa-site`.

Core proposition: **use synthetic and aggregate data to make responsible experimentation possible without exposing people or ecosystems to unnecessary data risk.**

Fundable slices:
1. Formal schema and provenance.
2. Synthetic data generator and reproducible seed/configuration.
3. Statistical and spatial fidelity tests.
4. Utility-risk/privacy evaluation.
5. Benchmark and documented use cases.

Keep the two domains distinct: regenerative agriculture ESG simulation is not the same dataset or validation problem as workforce retention. They may share tooling, not be merged into one undifferentiated product.

### Cluster E — Privacy-preserving digital health
**Repository:** `aros-voice-kernel`.

Core proposition: **local-first acoustic self-observation with transparent measurement and bounded interpretation.**

Fundable slices:
1. F0/voice-feature validation against references.
2. Device/acquisition quality matrix.
3. Offline Android alpha and reproducible test protocol.
4. Consent, retention and deletion controls.
5. Non-diagnostic UX and longitudinal visualization.

Do not claim clinical efficacy or diagnosis. Research funding should pay for measurement validation and ethics, not for unsupported clinical claims.

### Cluster F — Applied AI for commerce and collaborative knowledge
**Repositories:** `card-chat`, `k-fofo`, `dupla-evolutiva`.

Core proposition: **reliable human-facing AI systems with transparent workflows, privacy and useful outcomes.**

`card-chat` has the clearest operational deliverables. `k-fofo` and `dupla-evolutiva` require narrower research questions and public artifacts before they are ready for a standard technical grant.

## 4. Grant stacking: how to combine funding without double charging

The correct unit of stacking is the **independent work package**, not the repository or the overall vision.

Example for the trustworthy finance cluster:

| Work package | Output | Suitable capital type | Boundary |
|---|---|---|---|
| FIN-01 Evidence adapter | Pyth evidence normalization, freshness/confidence tests, provenance | Solana/oracle ecosystem grant | No duplicate funding of generic data ingestion |
| FIN-02 Policy engine | Deterministic thresholds, fail-closed rules, reproducible fixtures | Solana developer tooling grant | Separate from custody contract work |
| FIN-03 Authorization contract | Owner/operator controls, receipt and recovery tests | Solana program grant | On-chain scope only |
| FIN-04 Security review | Threat model, audit, remediation and regression tests | Security bounty / audit subsidy | Security costs allocated once |
| FIN-05 Adoption integration | One independent integration and user pilot | Ecosystem integration grant | Distinct integration partner and acceptance criteria |

Example for the territorial cluster:

| Work package | Output | Suitable capital type | Boundary |
|---|---|---|---|
| GEO-01 Open data pipeline | Reproducible public-data ETL and metadata | Open data / research grant | Public datasets and pipeline |
| GEO-02 Spatial analytics | Validated indicators and model cards | Research / education / urban grant | Analytical methodology |
| GEO-03 Pilot deployment | Local dashboard and decision workflow | Municipal/innovation pilot | Deployment and user testing |
| GEO-04 Commercial service | Hosted SaaS, support and custom integrations | Customer contract / revenue | Not charged to the public-good grant |

**Stacking identity:** for each cost or deliverable, record exactly one paying source, unless a documented cost-allocation rule explicitly permits shared financing. Maintain separate budgets, milestones, IP/license terms, reporting obligations and acceptance evidence.

## 5. Funding routes by cluster

These are routes to screen, not claims that every route is open or that each repository is eligible.

| Cluster | First route to test | Secondary route | What must be proven first |
|---|---|---|---|
| Autonomous finance | Solana Foundation milestone grant / RFP | Superteam Earn bounty; security programs | Public demo, tests, threat model, integration demand |
| Learning / credentials | Education innovation and research calls | Ethereum/Web3 identity or attestation programs | Working learner workflow and independent assessment |
| Territorial / mobility | Brazilian PD&I, urban innovation and climate calls | Open-source public-goods programs | Public data pipeline and pilot partner |
| Synthetic data | Responsible-AI / data research programs | ReFi and agricultural innovation funds | Utility-risk benchmark and documented methodology |
| AROS | Digital-health / assistive-tech research | University research partnership | Feature validation and ethics/consent protocol |
| Commerce AI | SME digitalization and applied-AI programs | Commercial pilot/customer revenue | Secure end-to-end order workflow and measurable benefit |
| Knowledge collaboration | Open knowledge / digital humanities research | Residencies and collaborative research | A narrow question and one reusable artifact |

The dated funding landscape in [Demand-Driven Grant Stacking Map — 2026-11](DEMAND-DRIVEN-GRANT-STACKING-2026-11.md) remains the reference for ecosystem-specific calls. Recheck official rules, deadlines, jurisdiction, applicant identity, license requirements and whether completed work is eligible before applying.

## 6. Priority order for the next 30 days

1. **P0 — KAIROS / valuecurator:** produce one reviewer-ready security-and-policy work package; make explicit what is already implemented, what is Devnet-only, what is read-only and what remains unaudited.
2. **P0 — EduAtlas:** select one public-data territorial use case and produce a reproducible baseline plus a two-page pilot brief. This may fit Brazilian PD&I and education innovation better than crypto-native grants.
3. **P1 — AROS:** finish the feature validation evidence and acquisition/device matrix; prepare a research application with non-diagnostic scope.
4. **P1 — EduChain (p-c-b-l-e + Coopetition):** reconcile overlapping product narratives into one minimal pilot, then split pedagogical workflow from reputation/credential infrastructure.
5. **P1 — digital-twin + structa-site:** publish a shared synthetic-data validation toolkit, while keeping the agriculture and workforce datasets separate.
6. **P2 — UrbanFlow:** remove token economics from the first pilot; validate reporting quality, privacy, map usefulness and a local stakeholder.
7. **P2 — card-chat:** complete secure deploy and order-state tests, then seek a paying pilot or SME innovation support.
8. **P3 — k-fofo / dupla-evolutiva:** convert conceptual material into a bounded open research artifact before grant applications.

## 7. Evidence checklist before an application

For each candidate work package, require:
- [ ] named problem owner or user group;
- [ ] one-sentence problem statement and measurable baseline;
- [ ] bounded deliverable and out-of-scope list;
- [ ] repository, branch, commit and license;
- [ ] demo or reproducible test;
- [ ] acceptance criteria and independent reviewer;
- [ ] budget with person-days and direct costs;
- [ ] milestone schedule and dependencies;
- [ ] data rights, consent, privacy and security assessment;
- [ ] IP, authorship and contributor agreement;
- [ ] funding-source exclusivity / cost-allocation record;
- [ ] impact metric distinct from activity and output metrics.

## 8. Governance and collaboration safeguards

These repositories are owned by another GitHub account and shared with the connected user as a collaborator. This document was added only to `compilatorum/concurseiro-grants`; no file, issue, workflow, branch or setting in the shared repositories was changed.

Before submitting an application or publishing a derivative:
1. confirm who is the applicant and authorized representative;
2. confirm co-authorship, ownership, license and permission to reuse code/data;
3. agree on work-package ownership, budget allocation, compensation and revenue share;
4. confirm whether the funder requires open-source licensing or assignment of rights;
5. obtain explicit approval from relevant repository owners and contributors.

## 9. Strategic synthesis

The shared portfolio is not one monolithic Web3 venture. It contains at least six fundable problem domains with different buyers, evidence standards and capital sources.

A better portfolio architecture is:

`Problem → Evidence → Work Package → Funder → Acceptance → Reuse`

The same technical component may be reused across projects, but the same cost, milestone or claimed impact must not be billed twice.

**Filosofema:** the repository is not the funding thesis. The externally validated problem is the thesis; the repository is one instrument for solving it.
