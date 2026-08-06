# Scope of Work (SOW) Systems in the UK

Research note — August 2026

---

## 0. Why this is confusing before it's useful

"Scope of work system" means three genuinely different things in the UK, and they share
almost no vendors, no vocabulary and no governing bodies:

| Sense | Who uses it | What a "system" means | UK-specific driver |
|---|---|---|---|
| **Agency / marketing SOW** | Advertisers and their creative, media, sponsorship and experiential agencies | Software that authors, approves, prices and reconciles the annual or project scope between client and agency | ISBA/IPA framework contracts, marketing procurement |
| **Services procurement SOW** | Corporate/public-sector procurement buying outsourced or contingent work | A VMS/MSP module that turns a brief into a deliverable-based, outcome-priced engagement | IR35 / off-payroll working rules |
| **Construction & engineering scope** | Clients, contractors, QSs, architects | The contractual scope document itself, plus the change-control machinery around it | NEC4 and JCT standard forms |

This note covers all three, weighted toward the first — the sense that applies to an
agency delivering brand and sponsorship work for clients.

---

## 1. Agency / marketing SOW — the UK operating model

### 1.1 The contract layer

The UK has an unusually well-developed set of industry-standard instruments, which is
why UK agency scoping looks more codified than in most markets:

- **2025 ISBA/IPA Creative Services Framework Agreement (CSFA)** — the industry-standard
  contract template for advertiser–agency relationships. The 2025 refresh adds clauses on
  generative AI, clearer reconciliation processes, and a restructure intended to make
  contracting faster. In practice the CSFA is the MSA; individual SOWs hang off it.
- **IPA Agency Remuneration best practice guide** and the **IPA Pricing Playbook**, which
  set out the remuneration families a SOW can be priced under:
  - *Input-based* — retainer, mark-up (i.e. FTE/hours × rate)
  - *Output-based* — commission fee, deliverable-based, subscription
  - *Outcome-based* — business performance, equity-based deals
- **ISBA Agency Hourly Rate Benchmarks** and the **ISBA / Observatory International UK
  Agency Remuneration report** — the benchmarking layer procurement uses to challenge a
  rate card.

The practical consequence: in the UK, a scope is rarely accepted as a lump sum. It is
expected to decompose.

### 1.2 The chain a UK scope has to survive

Marketing procurement audits a scope along a single chain, and every SOW system on the
market exists to make one link in it visible:

```
deliverables  →  hours by grade  →  rate card  →  fee  →  actuals  →  reconciliation
```

- **Deliverables** — countable units, not activities. "6 x 30s film, 2 rounds of revision"
  survives; "creative development" does not.
- **Hours by grade** — the FTE plan. Seniority mix is where most fee argument happens.
- **Rate card** — benchmarked against ISBA data.
- **Actuals** — timesheets. This is the weak link at most agencies and the reason
  reconciliation goes badly.
- **Reconciliation** — over- and under-servicing settled at year end, either in cash, in
  credit, or in next year's scope.

### 1.3 Scope creep controls

The controls that actually hold, per the vendor and industry literature, are all specificity
controls written into the SOW itself: explicit deliverable quantities, a fixed number of
revision rounds, dated timelines, and a written *out-of-scope* boundary with a change
mechanism attached. Anything not enumerated will be argued for free.

---

## 2. Client-side SOW management platforms

These are bought by the **advertiser**, usually by marketing procurement, and the agency is
a participant rather than the customer.

### Decideware — Scope Manager

The incumbent for large advertisers. Positioned as automating and centralising SOW
programmes: streamlined approvals, and spend transparency capturing initiatives,
deliverables, expenses and staffing fees. Its differentiator is the cut: data can be broken
down by business unit, brand, geography, staffing seniority and work complexity, which is
what allows a global client to compare what the same deliverable costs in London versus
elsewhere.

Decideware also sells **Agency Relationship Optimizer** for the performance/evaluation side,
used where incentive compensation (PRF) forms part of remuneration — objectives are defined,
the relationship is evaluated against them, and the resulting data sets the incentive
payment.

*Caveat:* the public material is global, not UK-segmented. UK-specific footprint and pricing
were not obtainable from public sources.

### Agencymania — ScopeDeliver

An end-to-end agency scoping tool aimed at annual staffing and financial planning plus
ongoing management of deliverables and agency/supplier resources. Closer to a planning tool
than a contract system.

### Consultancy-led scoping (the alternative to buying software)

A large share of UK scope governance is delivered as a service rather than a licence:

- **Flock Associates** — publishes a dedicated agency scoping tool
- **MediaSense**, **The Observatory International** — remuneration and scope benchmarking;
  the Observatory co-authors the ISBA UK remuneration report

For a single-client or single-market scope, consultancy-led review is usually the cheaper
route; platform licences make sense at multi-brand, multi-market scale.

---

## 3. Agency-side systems — what the agency runs to answer a SOW

Different software category, often confused with the above. These are agency ERP/management
systems: they produce the estimate, plan the resource, capture the time, and bill.

| System | Origin | Scope-relevant strength |
|---|---|---|
| **Screendragon** | Ireland, founded 2005 | Estimates and scopes tied to *linked rate cards*, so every scope reflects true cost and effort; automated approval routing cuts sign-off from days to hours |
| **Deltek WorkBook** | Global, strong UK agency presence | Cloud agency platform joining project management, resource planning and financials; sold on scoping accuracy and billing efficiency |
| **Synergist** | UK | Widely used across UK agencies; real-time availability, utilisation and forecasting — the capacity side of scoping |
| **Paprika** | UK | Long-standing UK agency financial/management system |
| **Workamajig** | US | All-in-one comparator: PM, resource scheduling, time tracking, financials |

The practical point: an agency scoping tool is only as good as two inputs — the rate card
and timesheet hygiene. Reconciliation is fought on actual recorded hours, so a beautiful
scoping front-end sitting on unreliable timesheets loses the argument anyway.

---

## 4. Services procurement SOW and IR35

A separate market with separate vendors, but it owns the term "SOW" in UK procurement
conversation, so it's worth knowing.

### What it is

A Statement of Work is a document setting out deliverables, timelines and the commercial
basis of an engagement between supplier and client. It does not replace a contract — it sits
alongside an MSA and is used particularly where services are outsourced.

### Platforms

- **SAP Fieldglass Services Procurement** — unified platform covering contingent labour,
  SOW-based engagements and worker tracking; automates time processing across multiple SOWs
  and workers and bills vendors at contracted rates. Now includes generative-AI drafting of
  SOW elements from a project brief. Available via **G-Cloud** in the UK.
- **Beeline** — comparable VMS with strong SOW capability, a more modern UI and faster
  implementation than legacy enterprise VMS.
- **Workday VNDLY** — same bracket; favoured in non-SAP estates and where direct sourcing is
  the priority.
- **Public Sector Resourcing (PSR)** — the UK government route; end-to-end sourcing managed
  through SAP Fieldglass, with SoW positioned as supporting legislative and IR35 compliance
  as a Government Commercial Agency framework supplier.

### The IR35 trap — the single most important UK-specific point

SOW-based contracting grew sharply after off-payroll rules hit the public sector in 2017 and
the private sector in 2021, on the belief that a SOW moves IR35 risk. **It does not, by
itself.**

Labelling an arrangement a "contracted-out service" or a "statement of work" when the
contract is in substance a provision of labour will not prevent the off-payroll working
rules applying — HMRC looks at the reality of the arrangement. The status determination
obligation only moves to the supplier where the service is *genuinely* fully outsourced:
supplier controls the how, owns the deliverable, carries the financial risk, and is paid for
an output rather than for days worked.

Any UK SOW system marketed on IR35 grounds should be assessed on whether it captures those
substance markers, not on whether it produces a document titled "Statement of Work."

---

## 5. Construction and engineering scope (for completeness)

- **NEC4** calls the scope document the **"Scope"** (NEC3 called it *Works Information*).
- **JCT Design & Build** uses **Employer's Requirements (ERs)**, answered by the
  **Contractor's Proposals**. ERs form part of the contract documents; compliance is tested
  against them and variations are measured by reference to them.
- Typical ER contents: performance specifications, design criteria, statutory and planning
  requirements, site information, programme requirements, interfaces, testing and
  commissioning, BIM/information requirements, sustainability targets, warranties.
- Clear, measurable ERs push design risk to the contractor; vague ERs create gaps and
  claims.
- Choice of form is a scope-stability question: **JCT** suits projects where design is
  substantially complete at award; **NEC4**, written in plain English and built around
  collaborative change management, suits projects where scope evolves.

---

## 6. What this means for event and sponsorship delivery work

An operational delivery schedule — people × day × activity × location × responsible party,
which is exactly the shape of the Macau GP team schedule in this repo — is the operational
shadow of a SOW line item. The scope says "on-site delivery team, 3 days, Macau"; the
schedule is what that fee actually bought.

For that kind of work to reconcile cleanly, the scope document needs to carry:

1. **Named roles and grades on site**, not headcount. "2 x Account Director, 1 x Producer"
   prices; "a team of 3" does not.
2. **Travel and on-site days counted separately** from working days, with a stated
   assumption on travel-day chargeability.
3. **Third-party pass-through explicitly separated** from agency fee — venue, hospitality,
   production, freight — with the mark-up or handling fee stated.
4. **Out-of-scope triggers written down**: extra guest days, schedule extensions, client
   attendee growth, additional territories, late brief changes.
5. **A change mechanism with a named approver and a turnaround time**, because event scope
   changes are decided in hours, not in a monthly SOW review.
6. **Deliverable counts for the surrounding content** — recaps, edits, photography, social
   assets — which are routinely absorbed as goodwill and are the most common source of
   unbilled over-servicing on activation work.

If a scope-management platform is ever put in front of this kind of work, the test to apply
is whether it can model a *day-shaped* deliverable (a person, on site, for a period) as
cleanly as it models an *asset-shaped* one. Most of the client-side platforms above are
built around asset-shaped creative deliverables and handle live delivery less naturally.

---

## 7. Summary

- Three unrelated markets share the phrase; establish which one is meant before any vendor
  conversation.
- For UK agency work, the contract standard is the **2025 ISBA/IPA CSFA**, the pricing
  reference is the **IPA Pricing Playbook**, and the benchmark is **ISBA's rate data**.
- Client-side SOW software is dominated by **Decideware**; agency-side scoping and
  reconciliation runs on **Screendragon, Deltek WorkBook, Synergist, Paprika**.
- Services-procurement SOW runs on **SAP Fieldglass, Beeline, Workday VNDLY**, with
  **PSR** as the public-sector route — and the IR35 benefit is a matter of substance, never
  of document title.
- Construction uses **NEC4 "Scope"** or **JCT "Employer's Requirements"**; the choice tracks
  how settled the design is at award.
- Gaps in this research: no UK-specific market-share or pricing data is published for
  Decideware or Agencymania, and no vendor material was found addressing SOW management
  specifically for sponsorship or experiential delivery — section 6 is reasoned from the
  general scoping principles above, not sourced.

---

## Sources

**Agency SOW — industry bodies and contracts**
- [ISBA — 2025 ISBA/IPA Creative Services Framework Agreement (CSFA)](https://www.isba.org.uk/knowledge/2025-isbaipa-creative-services-framework-agreement-csfa)
- [IPA — Agency Remuneration best practice guide](https://ipa.co.uk/knowledge/documents/agency-remuneration-best-practice-guide)
- [IPA — New IPA Pricing Playbook](https://ipa.co.uk/news/pricing-playbook)
- [ISBA — Agency Hourly Rate Benchmarks](https://www.isba.org.uk/knowledge/isbas-agency-hourly-rate-benchmarks)
- [ISBA — The Future of Agency Remuneration Report](https://www.isba.org.uk/knowledge/future-agency-remuneration-report)
- [ISBA and The Observatory International launch UK Agency Remuneration report](https://www.isba.org.uk/news/isba-and-the-observatory-international-launch-uk-agency-remuneration-report/)
- [ISBA — Marketing Procurement Live: Agency Remuneration & Performance Management](https://www.isba.org.uk/knowledge/marketing-procurement-live-agency-remuneration-performance-management)

**Client-side SOW platforms**
- [Decideware — Scope Manager](https://www.decideware.com/scope-manager)
- [Decideware — Agency Management Platform](https://www.decideware.com/agency-management-platform)
- [Decideware blog — 4 Reasons a Scope of Work System Is Crucial For Your Advertising Agency](http://blog.decideware.com/scope-of-work-management-0)
- [Decideware blog — Scope of Work: The Right Team on the Right Business](https://blog.decideware.com/scope-of-work-the-right-team-on-the-right-business)
- [Agencymania — ScopeDeliver SOW software tool](https://agencymania.com/solutions/scopedeliver-scope-of-work-sow-software-tool/)
- [Flock Associates — Agency Scoping Tool](https://flock-associates.com/agency-scoping-tool/)

**Agency-side management systems**
- [Screendragon — Agency Estimates & Scopes](https://www.screendragon.com/products/agency-estimates-scopes/)
- [Screendragon — Agency Management Software](https://www.screendragon.com/solutions/agency-management-software/)
- [Deltek WorkBook (UK)](https://www.deltek.com/en-gb/marketing-agency/workbook)
- [Deltek WorkBook — resourcing, project management and collaboration](https://www.deltek.com/en-gb/erp/workbook/resourcing-project-management-and-collaboration)
- [Synergist — Best Agency Management Software](https://www.synergist.co.uk/guides/best-agency-management-software)
- [Synergist — Agency capacity planning guide](https://www.synergist.co.uk/guides/agency-capacity-planning)
- [Workamajig — Agency Management Software](https://www.workamajig.com/agency-management-software)

**Services procurement SOW, VMS and IR35**
- [SAP Fieldglass — Services Procurement](https://www.sap.com/products/spend-management/services-procurement.html)
- [SAP Fieldglass — Services Procurement features (UK)](https://www.sap.com/uk/products/spend-management/services-procurement/features.html)
- [SAP Fieldglass service definition, G-Cloud 14 (Digital Marketplace)](https://assets.applytosupply.digitalmarketplace.service.gov.uk/g-cloud-14/documents/92801/673399395080957-service-definition-document-2022-05-05-1538.pdf)
- [Public Sector Resourcing — Statement of Work](https://publicsectorresourcing.co.uk/statement-of-work/)
- [SAP Fieldglass vs Beeline VMS comparison](https://app.humancloud.com/compare/sap-fieldglass-vs-beeline)
- [SAP Fieldglass review — contingent workforce VMS analysis](https://procurementvms.com/vendor-reviews/sap-fieldglass-review.html)
- [Qdos — Statement of Work contracts explained: IR35 & off-payroll](https://www.goqdos.com/ir35/off-payroll-working/statement-of-work)
- [ContractorUK — IR35: Statement of Work contracts](https://www.contractoruk.com/private_sector_ir35_reform/ir35_statement_work_contracts_off_payroll_contractors_guide.html)
- [IR35 Update — Do SoW arrangements really reduce IR35 risk?](https://www.ir35update.co.uk/statement-of-work/)
- [FCSA — Ensuring IR35 Compliance: Statement of Work](https://www.fcsa.org.uk/ensuring-ir35-compliance-statement-of-work/)
- [Brookson Legal — Is a Statement of Work the answer to IR35 in the private sector?](https://brooksonlegal.co.uk/news/is-a-statement-of-work-the-answer-to-ir35-in-the-private-sector/)

**Construction and engineering scope**
- [LexisNexis UK — NEC3/NEC4 ECC and JCT SBC/DB compared](https://www.lexisnexis.com/en-gb/legal/guidance/nec-jct-contracts-compared)
- [LexisNexis UK — Employer's requirements (ERs) glossary](https://www.lexisnexis.com/en-gb/legal/glossary/employer-s-requirements-ers)
- [ONFORM — What to include in Employer's Requirements, JCT 2024](https://www.onformgroup.co.uk/insights/employers-requirements-jct-contract)
- [Charles Russell Speechlys — JCT v NEC: which contract is right for your project?](https://www.charlesrussellspeechlys.com/en/insights/expert-insights/construction-engineering-and-projects/2022/jct-v-nec-which-contract-is-right-for-your-project/)
- [Legal Foundations — NEC4 Contracts: A Complete Guide](https://legalfoundations.org.uk/blog/nec4-construction-contracts/)
