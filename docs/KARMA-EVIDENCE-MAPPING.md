# GitHub → Karma Evidence Mapping

**Prepared:** 2026-11-07  
**Purpose:** Keep every public claim in Karma traceable to an inspectable source.

## 1. Evidence map

| Karma claim | Preferred source of truth | Minimum review |
|---|---|---|
| Project exists | Canonical repository / project site | Confirm ownership and active status |
| Feature implemented | Merged PR + release or commit | Confirm code is on canonical branch |
| Tests pass | CI run / test report | Confirm date, commit SHA and test scope |
| Demo works | Public demo + reproducible steps | Confirm access and disclose limitations |
| Integration exists | Downstream repository PR, deployed integration or transaction record | Confirm third-party system and scope |
| Users onboarded | Privacy-safe usage record or explicit confirmation | Define "user" and observation period |
| Community contribution | Issue/PR/review record | Distinguish unique humans from accounts/bots |
| Funding awarded | Official award notice or signed agreement | Record status, amount, currency, date and conditions |
| Funds disbursed | Transaction or payment confirmation | Record amount received, fees and restrictions |
| Impact achieved | Baseline + outcome data + method | Identify attribution limits and corroboration |

## 2. Evidence ladder

| Level | Meaning | Examples |
|---|---|---|
| L1 — Declared | Activity reported by project | Dated progress note |
| L2 — Observed | Public artifact exists | Issue, commit, release, dataset, specification |
| L3 — Reviewed | Work independently reviewed | Accepted PR, review, test report |
| L4 — Reproduced | Another person or automated process reproduces result | CI, clean setup, repeatable demo |
| L5 — External impact | Independent reuse or measurable benefit | Downstream integration, external dependency, confirmed outcome |

Do not label a claim L5 merely because it is public or onchain. External use must be evidenced.

## 3. Linking policy

- Use stable GitHub URLs: repository, issue, pull request, release, commit or workflow run.
- Pin important evidence to a release tag or commit SHA when possible.
- Avoid links to private repositories or inaccessible files in public Karma profiles.
- Use a canonical link for each artifact; do not link to transient local previews.
- For a claim supported by multiple sources, include the primary artifact first and corroboration second.

## 4. Publication gate

Before each Karma profile or update is published, ask:

- [ ] Is the claim factual and bounded?
- [ ] Does the linked artifact exist and open publicly?
- [ ] Does the evidence prove the exact wording?
- [ ] Is the stage accurately labelled?
- [ ] Are planned and completed work separated?
- [ ] Are funder, amount and award status correct?
- [ ] Is there any duplicate funding or double-counted cost?
- [ ] Are privacy, consent, license and IP constraints respected?
- [ ] Are known limitations disclosed?

## 5. Evidence record template

**Claim:**  
**Project:**  
**Milestone:**  
**Evidence level:** L1 / L2 / L3 / L4 / L5  
**Primary URL:**  
**Commit / release / transaction reference:**  
**Observed date:**  
**Reviewer:**  
**What this proves:**  
**What this does not prove:**  
**Next verification:**

## 6. Anti-inflation rules

- A repository link proves that a repository exists, not that the software works.
- A README description proves the project has a stated intention, not user adoption.
- A demo recording proves only the demonstrated path, not production reliability.
- A test passing proves the tested behavior under the test conditions, not complete security.
- A wallet transaction proves a transaction occurred, not that an ecosystem outcome was achieved.
- A social post proves communication, not contribution or impact.
