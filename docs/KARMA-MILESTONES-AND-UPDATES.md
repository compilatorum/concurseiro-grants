# Karma — Milestone Plans & Update Templates

**Prepared:** 2026-11-07  
**Status:** Proposed milestones, not commitments to funders. Set dates, owners and budgets only after capacity and scope are confirmed.

## 1. Milestone design rules

A Karma milestone should state:
- What will be delivered.
- Why it matters to the project.
- What is explicitly out of scope.
- How an independent reviewer can verify completion.
- Which repository, release, demo or report is the source of truth.
- Which grant or funding allocation pays for it, if any.

Use short, independently verifiable milestones. Avoid milestones such as "continue development" or "improve the platform" without a concrete acceptance test.

## 2. ValueCurator — proposed first milestones

### VC-M1 — Policy and permission model
**Deliverable:** Public specification of policy evaluation states, owner/operator/agent roles, authorization boundaries and fail-closed behavior.  
**Acceptance:** Versioned specification merged into the canonical repository; examples cover allowed, denied and indeterminate decisions; review notes recorded.  
**Evidence:** Specification URL, merged PR, review record.  
**Dependencies:** Confirm canonical repository and current architecture.

### VC-M2 — Oracle freshness and provenance test harness
**Deliverable:** Reproducible test cases for stale, missing, conflicting and low-confidence inputs.  
**Acceptance:** Automated tests demonstrate expected policy outcomes for each scenario; test command and expected output documented.  
**Evidence:** Test suite, CI run, test report.  
**Dependencies:** Data/oracle interface selected.

### VC-M3 — Public demonstration and integration guide
**Deliverable:** A reproducible demo showing data observation, policy evaluation and explicit authorization as separate stages.  
**Acceptance:** Public demo or recorded walkthrough; setup instructions work from a clean environment; limitations are disclosed.  
**Evidence:** Release/tag, demo URL, integration documentation.  
**Dependencies:** M1 and M2 accepted.

### VC-M4 — Security review and hardening backlog
**Deliverable:** Threat model, adversarial scenarios and prioritized remediation backlog.  
**Acceptance:** Threat model published; test results linked; unresolved risks explicitly listed. This milestone is not an independent security audit unless an external auditor is engaged.  
**Evidence:** Threat-model document, test reports, review record.

## 3. Farcaster Commons Lab — proposed first milestones

### FCL-M1 — Baseline and pilot specification
**Deliverable:** One selected ecosystem problem, a bounded work package, baseline, contributor journey and acceptance rubric.  
**Acceptance:** Public issue or project brief includes scope, estimate, owner, acceptance tests and evidence plan.  
**Evidence:** GitHub issue, experiment protocol.

### FCL-M2 — Run one contribution cycle
**Deliverable:** One public invitation, contribution attempt and completed review cycle.  
**Acceptance:** At least one contribution is reviewed; result is recorded whether accepted, revised or rejected. Do not require success as a condition for honest reporting.  
**Evidence:** Farcaster post, issue/PR links, review record.

### FCL-M3 — Publish experiment report
**Deliverable:** Report of baseline, participation, conversion, review time, limitations and lessons.  
**Acceptance:** Report includes raw metric definitions, observation period and links to source artifacts.  
**Evidence:** Public report and dataset/ledger where appropriate.

### FCL-M4 — Test external reuse
**Deliverable:** One independent maintainer or project evaluates an artifact for reuse.  
**Acceptance:** Written confirmation, integration PR, downstream dependency or documented reason reuse was not suitable.  
**Evidence:** External repository or reviewer link.

## 4. Nodespace — proposed first milestones

### NS-M1 — One workflow and governance boundary
**Deliverable:** Specification of one concrete coordination workflow, actors, roles, mandate, consent and decision authority.  
**Acceptance:** Workflow diagram and schemas reviewed; legal or institutional authority is not inferred from an agent identity.  
**Evidence:** Versioned specification and review record.

### NS-M2 — Prototype registry and commitment record
**Deliverable:** Minimal prototype that records participants, role/mandate references and commitments with provenance.  
**Acceptance:** Demonstration supports create, inspect and close a commitment; access and authorization limitations documented.  
**Evidence:** Public repository, demo, tests.

### NS-M3 — Human-in-the-loop pilot
**Deliverable:** One pilot workflow with a real community or project team.  
**Acceptance:** Participants consent; one decision is converted into an accountable task; completion or closure is recorded.  
**Evidence:** Redacted case study, issue/task links and participant feedback.

### NS-M4 — Reusable coordination toolkit
**Deliverable:** Open templates and schemas based on pilot findings.  
**Acceptance:** Independent team can follow the guide to reproduce the workflow.  
**Evidence:** Release, documentation and external feedback.

## 5. Project update template

Use this structure for meaningful progress updates:

### Update title
[Specific artifact or outcome]

**Period:** [YYYY-MM-DD to YYYY-MM-DD]  
**Project:** [Project name]  
**Milestone:** [Milestone ID, if applicable]  
**Status:** On track / At risk / Blocked / Completed

**What changed**
- [Concrete work completed; distinguish completed from in progress.]

**Evidence**
- [Merged PR / release / test report / demo / dataset / external confirmation.]

**What we learned**
- [Observed result, including negative or unexpected result.]

**Impact so far**
- Output: [count and definition]
- Outcome: [measured change, or "not yet measured"]
- External reuse: [evidence, or "none confirmed"]

**Next**
- [Next bounded action.]

**Risks / blockers**
- [Known limitation, dependency or decision needed.]

## 6. Milestone update — completion template

**Completion claim:** [What is complete]  
**Acceptance criteria:** [List each criterion and pass/fail]  
**Proof of completion:** [Stable links]  
**Reviewer:** [Name/role, only if confirmed]  
**Known limitations:** [What this does not prove]  
**Funding allocation:** [Grant/allocation ID, or "not grant-funded"]

## 7. Reporting hygiene

- Do not report a milestone complete because code was written; test against the published acceptance criteria.
- Do not report an integration complete based only on a design or mock.
- Do not report user adoption from impressions or social reactions.
- Do not report independent verification when the author self-reviewed.
- Do not report funding as received until the award/disbursement is confirmed.
- Keep failed experiments and blockers visible when they change the interpretation of results.
