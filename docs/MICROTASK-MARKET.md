# 🧩 Microtask Market — Work Packages, Rewards & Transferability

**Purpose:** turn unfinished work into small, independently understandable and verifiable funding units without implying that a token or task receipt is automatically liquid, an investment contract or a claim on future revenue.

## 1. The unit is a work package, not a speculative token

A funding unit represents bounded work:
- one problem statement;
- one accountable owner or open contributor slot;
- deliverables and objective acceptance criteria;
- estimated effort and budget;
- dependencies and exclusions;
- evidence requirements;
- funding source and restrictions;
- license/IP outcome.

A unit may be funded by a grant, bounty, sponsor, customer, community pool or internal allocation. The source determines obligations.

## 2. Lifecycle

DRAFT → SCOPED → REVIEWED → LISTED → FUNDED → IN_PROGRESS → SUBMITTED → ACCEPTED → SETTLED → ARCHIVED

Alternative states: BLOCKED, CANCELLED, EXPIRED, REJECTED.

No reward is due merely because a task was listed or a token was minted. Settlement follows published acceptance criteria and available budget.

## 3. Three separate layers

1. **Reputation:** non-transferable record of accepted contribution and review context.
2. **Utility credits:** internal accounting for access to review, compute or lab services; not cash and not a claim on profits.
3. **Transferable instrument:** optional technical experiment. Rights, transfer restrictions, jurisdictional treatment and redemption conditions require separate review. A token transfer must not silently transfer authorship, IP, grant eligibility or promise of return.

Do not merge contributor identity, task assignment, reputation, payment entitlement and token ownership.

## 4. Can a buyer resell or exchange a unit?

Only if the instrument's actual legal and technical rights permit it. Distinguish:
- assignment of work: another contributor takes responsibility, subject to maintainer approval;
- transfer of sponsorship: a sponsor changes who funds the task, with consent and accounting;
- transfer of a claim/receipt: requires clear rights, transfer rules and legal review;
- secondary-market trading: not assumed, promised or required.

Default: no secondary-market promise. First validate that work packages are useful, reviewable and fundable. Add transferability only as a separate experiment with an explicit rights matrix and risk review.

## 5. Pricing

A budget estimate is not a token price.

Budget = EstimatedHours × ReferenceRate + DirectCosts + RiskBuffer

Record assumptions and show a range. Do not use a bonding curve or implied market capitalization to price unfinished work.

## 6. Funding integrity

- Split a work package only when deliverables and costs do not overlap.
- Shared infrastructure needs a documented allocation key.
- One expense, invoice or hour cannot be charged to multiple funders.
- Grant-funded output must satisfy license and disclosure terms.
- Bounty and grant can coexist only when scopes/costs are distinct or co-funding is approved.
- Failed, abandoned or rejected work is reported honestly.
- Resale or transfer does not erase original funding restrictions.

## 7. Initial experiment

Run a no-token pilot:
1. select one small issue in this repository or a linked open repository;
2. define deliverables, estimate, acceptance and evidence;
3. publish it as an issue;
4. invite one contributor through Farcaster;
5. review and merge the contribution;
6. publish evidence and attribution;
7. compare coordination time and review quality against a baseline.

Only after this works should utility credits be tested. Transferable tokens and secondary markets are later hypotheses, not prerequisites.

> **Filosofema:** Tokenize the accounting of work only after the work has a clear unit, a real buyer, an acceptance rule and a right that can be explained without metaphor.
