# Open Questions

Each item states what could not be determined and the specific document or conversation that would
resolve it. Ordered by how much the answer changes the analysis.

---

## Tier 1: answers that change the recommendation

### Q1. Are the approximately 60 accounts contracted revenue or pipeline?

**Why it decides everything.** Both surviving acquirer categories, TIC roll-ups and engineering
consultancies, buy on billable delivery capacity and a transferable book. If the accounts are
contracted and recurring, the asset is a straightforward tuck-in with a priceable book. If they are
pipeline, there is very little to sell, because the methodology will not carry the transaction on
its own.

**Resolves with:** the PEL customer list with, per account, contract status, term, renewal date,
annual value, and whether the agreement is assignable on change of control. A CRM export is not
sufficient; the assignability clause is the part a buyer's counsel reads first.

### Q2. What is the chain of title on each asset, and what happened during the period of unsigned third-party access?

**Why.** This is the largest value-destroying fact available and it is live across every acquisition
path. An asset purchase narrows the exposure but does not remove it, because each asset conveyed
still needs clean title.

**Resolves with:** signed IP assignment agreements for every contributor, employee and contractor;
and a written account of the third-party access period covering who had access, to what, for how
long, under what agreement if any, and what was created during it. If no assignment exists for a
contributor, that needs to be said before an approach, not during diligence.

### Q3. Does a registered ISO 9001 certificate naming EcoSpex Inc. exist?

**Status: Unverifiable.** A public search returned no registrar record and no certificate reference.
That is not evidence that no certificate exists. There is no single searchable registry of ISO 9001
certificates; registrars maintain separate directories and central indexes have partial coverage.

**Resolves with:** request the certificate from the founder. What is needed is the registrar name,
certificate number, the scope statement, the accreditation body, and current status. If the
certificate exists, record all five. If it does not, that is a fact the founder supplies, not one
this research can assert.

Held separately in all prose: a QA framework modelled on ISO 9001 is not certification, and ISO 9001
certifies a quality management system rather than a product.

### Q4. Is the IESO relationship standing or a one-time pilot?

**Why.** EcoSpex states that its Premium Verified listings carry pilot pricing at a 60 percent
discount funded by Ontario's Independent Electricity System Operator. If that is a standing
programme relationship, the Canadian institutional position is a real asset and category I
strengthens. If it was a single pilot that has ended, the institutional position thins to a grant
history and the Canadian angle weakens considerably. It also raises a harder question: if 60 percent
of the price has been subsidised, what is the unsubsidised price the market will actually pay?

**Resolves with:** the IESO agreement or programme documentation, its term, and the current status.

---

## Tier 2: answers that change the scorecard

### Q5. What is the actual, evidenced cost to recreate?

**Why.** The register's CAD 2,613,500 is self-reported, undated and carries no evidence pointer, and
roughly 19 percent of it is an unspent forward statement of work rather than money spent. Phase 3's
build-versus-buy dimension will therefore be an outside-in estimate. It would be stronger with a
real basis.

**Resolves with:** payroll and contractor records, grant claim submissions (which carry
substantiated cost breakdowns because a funder audited them), and dated invoices for the SME
engagements. Grant claims are the highest-value document here: they are the one place the costs have
already been evidenced to a third party.

### Q6. Which funder actually funded what?

**Why.** Register rows cite NRCan and IRAP inconsistently. IRAP is administered by the National
Research Council, which is not Natural Resources Canada. No grant-history claim in this analysis is
built on that column, which means a genuine grant record is currently unusable as a credential.

**Resolves with:** the executed funding agreements and project reference numbers for each programme.

### Q7. What is the status of the Patent Pending row?

**Why.** One register row claims Patent Pending with no application reference. Unconfirmed filing
status is a diligence finding, not an asset, and an unsupported patent claim in a data room damages
credibility on every other claim in the same document.

**Resolves with:** the application number and filing receipt, or a decision to strike the row.

### Q8. What is Blue Wilderness Management Group's position in the structure?

**Why.** EcoSpex states that it was incorporated in July 2013 and is wholly owned by Blue Wilderness
Management Group Inc. A share purchase therefore has a parent in the chain, and any IP developed
under the parent before or alongside EcoSpex needs to be located.

**Resolves with:** the corporate structure chart, the shareholder register, and confirmation of
which entity holds each asset.

### Q9. Does Acelab have a licensed EPD data feed, and what is its current state?

**Why.** Two sources conflict and neither was openable. The July 2026 brief states Acelab has no
verified data feed and scrapes plus manually cross-checks. Acelab material dated May 2025 describes
embodied carbon data integrated from EC3 and HPD disclosures pulled directly from HPDC. Acelab is
also absent from one Building Transparency EC3 API partner list. The tension is unresolved and it
matters for Phase 4, because Acelab was the brief's strongest partnership wedge.

**Resolves with:** a direct conversation with Acelab, or the Building Transparency partner list read
in full. Note that this is one of the items the egress block prevented from being settled.

---

## Tier 3: research blocked by environment, not by absence of evidence

### Q10. Verbatim confirmation of every source-asserted claim

**Why.** The organization's egress proxy answered 403 to CONNECT on every host attempted. No source
page was opened. All 53 source-asserted ledger rows are therefore `Unverifiable` rather than
`Verified`, including claims that are almost certainly correct and corroborated across several
independent outlets.

**Resolves with:** opening the egress allowlist, then a re-verification pass over `ledger/claims.csv`
that opens each named URL and records a verbatim snippet. No analysis has to be redone. Status is a
single column and the URLs are already recorded.

**Priority URLs for that pass**, in order of how much weight they carry:

1. `mindfulmaterials.com/rating-systems-program-partner-relationships` and the Data Ecosystem
   report. These carry Finding 1, which drives the whole reframe.
2. `wapsustainability.com/2026/06/22/ecomedes-wap-sustainability-partnership/`. The timing hinge.
3. `wapsustainability.com/2022/12/20/...coldstream-consulting/`. The closest template transaction.
4. `slrconsulting.com/us/news/slr-acquires-wap-sustainability/`.
5. `acelabusa.com/the-material-hub-vision` and `buildingtransparency.org/tools/ec3/`. Q9.
6. `deltek.com/products/delivery-assurance/specpoint/`. Carries the category D rejection.

### Q11. Deal structure across the comparable set

**Why.** No public statement of asset purchase versus share purchase was found for any small private
target in the comparable set. Announcements say "acquired" and stop. The deal-shape decision
therefore rests on chain-of-title exposure rather than precedent, which is a weaker footing than the
task assumed.

**Resolves with:** a corporate registry search on the acquired Canadian entities (Coldstream
Consulting is the useful one), or a conversation with an M&A adviser active in TIC tuck-ins. Neither
was possible with egress blocked.

---

## Register facts not supplied by the memo

Per instruction, register facts not in the correction memo are recorded here rather than sourced
independently. No register file has been opened since the memo was received.

- Which specific rows carry the CAD 1,304k attached to a commercial offering, and whether that
  figure maps to PEL, to GBM, or to both.
- The 2 of 38 rows on which Replication Rationale is filled, and what they say. These are the only
  substantiated defensibility statements in the register and they are currently unseen.
- Which of the 18 Tier A rows survive reclassification beyond PEL and GBM.
- Which 10 rows carry a misapplied Protection Type, and which single row claims Database Rights.
- Whether GBM has paying customers distinct from PEL, which determines whether the defensible Tier A
  count is 2 or 3.
