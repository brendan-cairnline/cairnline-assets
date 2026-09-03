# 00. Scope and Ground Truth

**Prepared:** 3 September 2026
**Amended:** 3 September 2026, Cairnline amendments 1 to 3. See section 1A.
**Purpose:** internal corporate development input. Not shown to the asset's founder. Not a marketing document.
**Status of this run:** Phase 1 and Phase 2 complete. Phases 3, 4 and 5 are held at the Phase 1 gate.

---

## 1. Read this first: the evidence grade is capped

Every direct page fetch attempted in this session was refused by the organization's egress proxy,
which answered `403` to `CONNECT` on every host tried, including `canada.ca`, `sec.gov` and
`en.wikipedia.org`. A re-probe on 3 September of `mindfulmaterials.com`, `usgbc.org` and
`hpd-collaborative.org` returned no connection. Only the search tool was operable. No source page
has been opened at any point in this project.

**Status vocabulary, as amended.** The original rule collapsed two different things into
`Unverifiable`: a source that refused, and a proxy that refused. Those are findings about different
subjects, and conflating them would let a tooling limit be read as a fact about a target. A fourth
status is therefore in force:

| Status | Scope |
|---|---|
| `Verified` | Live source reached and a verbatim snippet captured |
| `Blocked` | **This session's own egress proxy refused the host.** A finding about our tooling, not about the source |
| `Unverifiable` | The remote source refused, or a search ran and returned nothing |
| `Not Tested` | Not empirically tested. Inferences and principal-supplied facts |

Ledger distribution after re-grading, 94 rows:

| Status | Rows |
|---|---:|
| `Blocked` | 50 |
| `Not Tested` | 30 |
| `Unverifiable` | 8 |
| `Verified` | 6 |

The 8 `Unverifiable` rows are genuine findings: null searches for the ISO 9001 certificate, a Green
Badger transaction, EPD programme operator transactions, a One Click LCA acquisition of EPD Hub, an
Anguleris sustainability data strategy, an independent statement of EcoSpex scale, an EcoSpex patent
filing, and the HPDC data module ship status. The 6 `Verified` rows are in-session process facts.

What this does and does not mean:

- It does **not** mean the `Blocked` facts are wrong. Most are corroborated across several
  independent outlets returned by search, and the URLs are named.
- It **does** mean nobody has read the source text. A snippet in a `Blocked` row is
  search-engine-rendered summary text, labelled as such in the row.
- The fix is one permission change, and re-grading is a single-column pass. No analysis is redone.

## 1A. Amendment 1: the commoditization finding was re-tested first

Finding 1 in `01-ACQUIRER-CATEGORIES.md` is load-bearing, and this analysis identified it as its own
falsifier and then built the recommendation on it. It was re-tested before anything else. Reading at
source was not possible, so the test was to widen to sources independent of mindful MATERIALS and
look for slippage.

**Verdict: the finding holds on its load-bearing leg, and one supporting leg is withdrawn.**

**Strengthened.** BuildingGreen, a trade publication independent of mindful MATERIALS, states that
in LEED v5 products are assigned a score based on a matrix modelled on the Common Materials
Framework, and that LEED v5 BD+C reconceives the previous multi-attribute assessment by leveraging
the CMF, consolidating EPD, responsible sourcing and material health into a unified Building Product
Selection and Procurement credit. That is CMF inside a published rating system's credit structure,
not an intention. LEED v5 is mandatory for new registrations from 1 July 2026.

The programme is also older than the analysis had it. The AIA, ILFI, IWBI, USGBC and mindful
MATERIALS collaboration on CMF adoption dates from 2023. The 2026 Greenbuild statement is an
expansion of a three-year programme, not a fresh announcement that might slip.

**Withdrawn.** The claim that HPDC would ship a CMF Data Module in the HPD builder by early 2026 did
not corroborate on a targeted search. It is downgraded and Finding 1 no longer rests on it.

**Substituted, and it cuts harder than the claim it replaces.** HPD Collaborative states that it
connects HPD Open Standard data from more than 700 manufacturers across more than 10,000 published
HPD reports with the CMF Portal, **powered by Ecomedes, Inc.** The rating bodies' shared cross-walk
already has an operating technology partner, and it is the same company that filled its own
verified-data gap through WAP in June 2026. Category D closes harder, not softer.

## 1B. Amendment 2: the account base is pipeline

Cairnline states that the 60 plus accounts are pipeline rather than contracted revenue, and that the
IRAP tranche is gated on producing three to five repeatable closes. A tranche gated on producing
closes is only a gate if the closes have not happened.

This was `OPEN-QUESTIONS.md` Q1, the question this analysis said decides everything. It moves here,
into ground truth, because it is answered. Applying this analysis's own conditional: categories A
and B weaken toward zero, and there is little left to buy.

**Do not stop there. The question was framed one level too high.** PEL has been delivered since 2014.
That is eleven years of some revenue and it is separable from the current pipeline. The question that
decides the mandate is narrower and it has a document answer:

> **What is PEL's trailing 24 month revenue, how much is contracted forward, are those agreements
> assignable on change of control, and what share of that revenue was subsidised?**

The fourth part is added here and it is not optional. EcoSpex states that its Premium Verified
listings carry pilot pricing at a 60 percent discount funded by Ontario's IESO. If a material share
of trailing PEL revenue was sold at 40 percent of list under a subsidy, that revenue is not evidence
of willingness to pay, and a buyer will discount the whole book once the subsidy surfaces in
diligence. Better to know the split before an approach than to have it found.

A second reading worth stating plainly: PEL has run for eleven years and the account base is still
pipeline. That is a growth-rate fact, and a buyer reads it as one.

This question now outranks the register work. It is the single most valuable document to obtain.

## 1C. Amendment 3: delivery capacity is two people, and one of them is in dispute

Cairnline states that delivery capacity is Julie and James, that James is the core technical
contributor with an unresolved payment dispute, and that the sale object is effectively an acqui-hire
requiring the founder personally to transfer and stay.

**This is the most consequential input in the file, and it does two things.**

**First, it breaks the tuck-in framing.** The reframe in `01-ACQUIRER-CATEGORIES.md` says buyers pay
for billable delivery capacity. The comparables are WAP at close to 100 employees and EcoAct at
approximately 400. The smallest disclosed value found anywhere in the set is approximately USD 6
million for Healthy Buildings International, a business founded in 1992. **No transaction in the
comparable set involved a two-person target.** At two FTE the object of a transaction is not
capacity. It is a founder retention package plus a dataset, a brand and a set of Ontario
relationships. Categories A and B do not merely weaken; the thing being sold changes.

**Second, and more urgently: the dispute and the chain-of-title gap are one problem, not two.**

The register records no chain of title on any of its 38 rows. James is the core technical
contributor. James has an unresolved payment dispute. A contributor who is owed money and holds no
signed IP assignment is not a personnel matter sitting beside a documentation matter. It is a single
ownership risk with a motivated counterparty and a colourable position over the technical assets.

It survives both deal shapes. In an asset purchase, the buyer's counsel asks for his assignment on
day one and there is not one. In a share purchase it travels with the entity. In either case it is
among the first three things any diligence process surfaces, and surfacing it during an approach
rather than before one costs the seller control of the narrative.

**It should be resolved before any target is contacted.** That is a sequencing instruction for Phase
5 and it is stated here so it cannot be missed.

## 2. Inputs

The two attachments named in the task prompt were not attached. The repository at session start
contained a README and an image. Equivalents were located in Drive and read:

| Named input | What was used |
|---|---|
| `brief.md`, Acelab/Ecomedes partnership research, July 2026 | Drive document `EcoSpex & Acelab Partnership` |
| Corrected IP Asset Register | **Superseded. Not used.** See below. |

**Register handling.** An in-session correction memo established that the Drive copy of the register
is superseded, that the current version is not in Drive, and that the memo is the sole source of
register facts for this analysis. No register file has been opened since. Register facts that the
memo does not supply are recorded in `OPEN-QUESTIONS.md` rather than sourced independently.

## 3. The asset, as audited

A human-delivered verification service with a sustained revenue history, supported by software
modules that are largely prototype.

That sentence is the whole reframe. It is not a platform with a services arm. It is a service with
a partly-built platform attached.

**What is in the asset**

- **Premium Environmental Listing (PEL).** Recorded in the register as developed in 2014 as a manual
  offering to building product manufacturers. The revenue-bearing offering.
- **Green Building Matrix (GBM).** A released specifier-facing product.
- **A curated dataset** mapping product attributes to green building standard requirements.
- **Multi-standard mapping logic** across LEED, WELL, Passive House, BREEAM and others, existing
  largely as documented methodology and format templates rather than automated software.
- **Canadian institutional position.** EcoSpex states that it has run an "IRAP /NRC Automation of
  low carbon construction products" project and that its Premium Verified listings carry pilot
  pricing at a 60 percent discount funded by Ontario's Independent Electricity System Operator.
- **Approximately 60 manufacturer and AEC accounts** in an active pipeline.

**What is not in the asset**

- Not a working automation platform. The core platform is roughly 60 percent complete at TRL 6.
- Not BIM-integrated. Revit and Forge work was research, not product.
- Not independently accredited as a product verification credential. See section 5.
- Not scaled. Database size, SKU counts and rating-system coverage in the July 2026 brief describe
  intent, not delivered capability.

## 4. What the register says, and the pattern in it

All of the following are register facts supplied by the correction memo. They are recorded in the
ledger as `ecospex-asserted`.

1. **The register is populated, and that is a different problem than blankness.** 33 named assets
   across 38 content rows. 28 rows carry a development cost, totalling CAD 2,613,500. Dev Period,
   Chain of Title, Data Provenance, Key Person Dependency, Depends On and Evidence Location are
   0 percent filled across all rows. Replication Rationale is filled on 2 of 38.

   The pattern: **every column that asserts a claim is populated, every column that substantiates
   one is empty.** A buyer's diligence team reads that pattern in about ten minutes, and it is worse
   than an empty register, because an empty register is an unfinished document while this one is a
   completed set of unevidenced assertions.

2. **There is no usable internal cost basis, despite the cost column being populated.** The
   CAD 2,613,500 figure is self-reported, undated and carries no evidence pointer. It decomposes
   approximately as CAD 1,304k against a commercial offering, CAD 518k on research into markets
   never entered, CAD 293k on internal operating process, and CAD 500k that is an unspent forward
   statement of work rather than money spent. Roughly 19 percent of the stated development cost has
   not been incurred.

   Build-versus-buy in Phase 3 must therefore be an outside-in estimate with the basis stated. The
   reason is that the internal figure is unevidenced, not that it is missing.

3. **Chain of title is unresolved and is the largest value-destroying fact.** A period of
   third-party access to the IP without a signed agreement sits behind that column. It is live
   across every acquisition path and it is a Phase 5 input.

4. **Tier is unreliable.** 18 rows are tagged Tier A; 15 of those carry a Current Stage of Prototype
   in the same row. Reclassification is underway on the test of whether a third party has paid for
   the output. The defensible Tier A count is expected to land at 2 or 3, being PEL and GBM.

5. **The founder's own replication assessment undercuts the defensibility case.** She marked 21 of
   38 rows Low replication difficulty and only 5 High. This is the sell side's own evidence, and it
   is unhelpful to the sell side. It is used in Phase 1 and it will be used in Phase 3.

6. **Protection Type is misapplied on 10 rows,** mostly Trademark assigned to methodologies and
   datasets. One row claims Database Rights, which do not exist as a standalone right in Canada.
   One row claims Patent Pending with no application reference; filing status is unconfirmed and is
   carried as an open question, not an asset.

7. **Funder attribution is unreliable.** Rows cite NRCan and IRAP inconsistently. IRAP is
   administered by the National Research Council, which is not Natural Resources Canada. No
   grant-history claim in this analysis is built on the register's funding column.

## 5. ISO 9001: unresolved, and stated as unresolved

A search for a registered ISO 9001 certificate naming EcoSpex Inc. returned no registrar record and
no certificate reference.

That result is recorded as `Unverifiable`. It is **not** recorded as a finding that no certificate
exists, and no deliverable in this set says that. There is no single searchable registry of ISO 9001
certificates; registrars maintain separate directories and central indexes have partial coverage, so
a null search proves nothing. The resolving action is in `OPEN-QUESTIONS.md`: request the
certificate from the founder.

Held separately, and not to be merged in prose: internal evidence that a QA framework was modelled
on ISO 9001 is not evidence of certification. ISO 9001 certifies an organization's quality
management system. It is not a product verification credential, and a buyer will know that.

## 6. Excluded claims

Two claims appearing in EcoSpex positioning documents are retired and do not enter this analysis in
any form, including as unstated framing:

- that AI cannot recreate the methodology
- that the output is 100 percent accurate

Neither is used to support the build-versus-buy argument. That argument is reasoned from external
market evidence, in `01-ACQUIRER-CATEGORIES.md`.

## 7. One correction to the July 2026 brief

The brief's central wedge is that Acelab has no verified sustainability data feed and sources EPD
data by AI web-scraping plus manual cross-checking. Search evidence dated May 2025 describes
Acelab's Material Hub embodied carbon data as integrated from EC3 and its HPD disclosures as pulled
directly from the Health Product Declaration Collaborative, with sustainability data described as
verified at the source.

The gap the brief describes is narrower than the brief states. This is carried as a correction, not
a confirmation, and it matters because the brief's wedge was the strongest single argument for a
partnership-led path.

## 8. Deal shapes modelled

Both, ranked separately, per instruction.

| Shape | What transfers | Principal exposure |
|---|---|---|
| **Asset purchase** | Dataset, methodology, GBM, the PEL service, the account pipeline | Chain of title still has to be established for each asset conveyed; an asset purchase narrows the exposure but does not remove it |
| **Share purchase** | The Canadian entity, grant history and institutional relationships intact | Full exposure to the unresolved chain of title, the unreferenced Patent Pending row, and the funder attribution errors |

A structural fact affecting both: EcoSpex states that it was incorporated in July 2013 and is
wholly owned by Blue Wilderness Management Group Inc. Any share purchase therefore has a parent
company in the chain. This is `ecospex-asserted` and is on the open questions list.

## 9. Evidence rules in force

- `provenance` is one of `source-asserted`, `ecospex-asserted`, `researcher-derived`.
- `status` is one of `Verified`, `Not Tested`, `Unverifiable`.
- No `ecospex-asserted` claim appears in prose as established fact. The qualifier travels on the
  same line at every appearance.
- Anything dated after May 2026 is independently re-verified, the July 2026 brief included.
- Latka and Crunchbase figures are labelled estimates at every appearance.
- Recorded absences are written down. A search that returned nothing gets a row.
- No invented valuations. Undisclosed is written as undisclosed.

## 10. Files in this run

| File | State |
|---|---|
| `00-SCOPE-AND-GROUND-TRUTH.md` | This document |
| `01-ACQUIRER-CATEGORIES.md` | **Gate. Human approval required before Phase 3.** |
| `02-TRANSACTION-COMPS.md` | Complete |
| `OPEN-QUESTIONS.md` | Complete for this run |
| `ledger/claims.csv` | 79 rows |
| `SOURCES.md` | Complete for this run |
| `03-ACQUIRER-SCORECARD.md` | Not started. Held at gate. |
| `04-PARTNER-LANDSCAPE.md` | Not started. Held at gate. |
| `05-APPROACH-STRATEGY.md` | Not started. Held at gate. |
