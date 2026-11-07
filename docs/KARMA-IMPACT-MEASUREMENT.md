# Karma — Impact Measurement Framework

**Prepared:** 2026-11-07  
**Purpose:** Define measurable activities, outputs, outcomes and indicators for the three initial Karma profiles.

## 1. Logic model

Use the chain:

**Funding → Activities → Outputs → Outcomes → Impact**

- Funding: resources actually received or allocated.
- Activities: work performed using those resources.
- Outputs: direct artifacts or services produced.
- Outcomes: changes for users, contributors or ecosystem participants.
- Impact: longer-term ecosystem or societal change to which the project plausibly contributes.

Do not collapse these levels. A merged pull request is an output, not proof of ecosystem impact.

## 2. Cross-portfolio indicator dictionary

| Indicator | Definition | Unit | Source | Frequency |
|---|---|---:|---|---|
| Work packages completed | Packages meeting all published acceptance criteria | count | GitHub issues / milestone records | Monthly |
| Accepted contributions | PRs merged after review, excluding automated/no-op changes | count | GitHub | Monthly |
| Reproducible artifacts | Releases, tests or demos independently repeatable from documented steps | count | CI, release, demo | Monthly |
| External reuse | Independent projects integrating or adapting an artifact | count | Downstream PR, dependency, written confirmation | Quarterly |
| Active contributors | Unique people with at least one accepted contribution in period | people | GitHub contribution records | Monthly |
| Contribution conversion | Accepted contributions ÷ contribution attempts with a recorded disposition | ratio | GitHub issue/PR ledger | Per pilot |
| Time to acceptance | Median days from task publication to accepted contribution | days | GitHub timestamps | Per pilot |
| Funding efficiency | Eligible verified outputs delivered ÷ amount actually spent | defined ratio | Funding ledger + evidence | Per award |
| Milestone reliability | Milestones accepted by agreed due date ÷ milestones due | ratio | Karma milestone records | Quarterly |

Publish numerator, denominator, time window and exclusions for every ratio.

## 3. ValueCurator indicators

### Activities
- Specify policy and permission boundaries.
- Implement deterministic policy checks.
- Build oracle freshness/provenance tests.
- Conduct adversarial testing and integration validation.

### Outputs
- Versioned schemas and specifications.
- Merged policy-gate code and test cases.
- CI runs and reproducible demo.
- Threat model and integration guide.

### Outcomes
- Integrators can inspect and reproduce policy decisions.
- Unsafe or indeterminate inputs are rejected or routed to explicit human review in tested scenarios.
- Developers can reuse the policy/test components in a separate integration.

### Indicators
| Indicator | Baseline | Target-setting rule |
|---|---|---|
| Policy scenarios covered | Establish from first test inventory | Target only after threat-model review |
| Test pass rate | Establish from initial CI run | 100% of required deterministic tests passing for release |
| Reproducible setup success | Establish with clean-environment test | Record successful independent reproductions |
| External integrations | 0 confirmed until evidence exists | Count only merged downstream integration or written confirmation |
| Critical unresolved risks | Establish from threat model | Publish trend; do not hide unresolved risks |

## 4. Farcaster Commons Lab indicators

### Activities
- Publish scoped work packages.
- Invite and support contributors.
- Review submissions.
- Record and publish results.

### Outputs
- Work package briefs.
- Issues, PRs, reviews and accepted artifacts.
- Experiment reports and evidence records.

### Outcomes
- More discussion converts into reviewable work.
- Contributors complete a first accepted contribution with lower coordination friction.
- Artifacts are reused outside the originating conversation.

### Indicators
| Indicator | Baseline | Target-setting rule |
|---|---|---|
| Qualified tasks published | Establish in pilot | Count tasks with owner, scope and acceptance criteria |
| Unique contributors | 0 for new pilot unless historical records are validated | Count distinct human contributors, disclose pseudonymous identity handling |
| Contribution conversion | Measure attempts with recorded disposition | Report accepted / all disposed attempts |
| Median time to acceptance | Measure from issue opening to merge | Report median and sample size |
| External reuse | 0 confirmed until evidence exists | Count independent downstream use only |

## 5. Nodespace indicators

### Activities
- Define roles and mandates.
- Specify one coordination workflow.
- Prototype commitment recording.
- Run a consent-based human-in-the-loop pilot.

### Outputs
- Role, mandate and commitment schemas.
- Workflow specification and prototype.
- Pilot report and reusable templates.

### Outcomes
- Participants can identify who is authorized to decide or act.
- Decisions become accountable tasks with owners and evidence.
- Teams can reproduce the workflow without relying on undocumented context.

### Indicators
| Indicator | Baseline | Target-setting rule |
|---|---|---|
| Commitments with named accountable owner | Establish during pilot | Count commitments with explicit owner |
| Commitments with evidence link | Establish during pilot | Count commitments with inspectable evidence |
| Closure rate | No baseline until pilot | Closed commitments / commitments due |
| Decision-to-task time | Measure in pilot | Compare with documented baseline |
| Independent reuse | 0 confirmed until evidence exists | Count independent community reproduction |

## 6. Data quality and privacy rules

- Prefer public repository data and aggregate counts.
- Do not publish personal, sensitive or confidential contributor data.
- Obtain consent before attributing quotes, testimonials or identifiable participation.
- Distinguish automated telemetry from manually reported metrics.
- Record source, collection date, definition and known bias for each metric.
- Avoid vanity metrics such as impressions, followers or raw commits as primary impact indicators.
- Never infer clinical, financial or social outcomes from technical activity alone.

## 7. Reporting format

For every reporting period publish:
1. Reporting period and project stage.
2. Activities completed.
3. Outputs with links.
4. Outcomes observed and measurement method.
5. Indicators with numerator, denominator and sample size.
6. Risks, negative results and missing data.
7. Next measurement period.

> **Filosofema:** Measurement is not the decoration of a project. It is the discipline that prevents a project from mistaking its own activity for the world's benefit.
