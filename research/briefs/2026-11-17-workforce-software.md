# Workforce, agency and software-gap run: 17 Nov 2026

## Method

- Every quote below was read on the linked page today. App reviews came from Apple's public review feed for the Australian store.
- Not reached: the Fair Work Ombudsman's own release (no response; trade-press coverage of it was read instead), Trustpilot, Reddit, X, Facebook groups.
- **Honest result:** one idea is clearly stronger than anything from earlier runs. One is real but risky for a no-code builder. The agency idea falls just under the bar. Most workforce pain I found has no one willing to pay to fix it, or is a bug in a vendor's app.
- Scores and prices are my estimates.

## What the industry is experiencing

1. **Software is failing the providers who pay for it.** In a survey of 300+ home care leaders, 64% say their system is inadequate, a figure unchanged for four years; 55.6% say systems were not ready for Support at Home.
2. **Providers no longer trust vendors.** Survey comments include "We have lost trust in vendors – sales pitches are misleading."
3. **Payroll is producing underpayments.** Fair Work investigated 22 aged care employers and found 13 non-compliant, recovering $5.3 million.
4. **Agency staff are used heavily and set up to fail.** Workers describe starting shifts with no information on residents; research links agency reliance to worse outcomes.
5. **Worker apps are buggy, but nobody pays to fix that.** Low-star reviews of Humanforce, Brevity, vWorker and Easy Employer are almost all login failures and crashes.

---

## Idea 6 (rank 1): VendorCheck

**Pitch:** Independent, provider-verified scorecards for Australian aged care software: what each system really does for Support at Home claiming, budgets, statements and payroll links, rated by the people who use it.

**Gap it fills:** Providers are choosing and replacing systems blind. The one large survey reports dissatisfaction across the sector but does not name vendors. Comparison sites exist, but one reviews three products editorially ([SoftwareHQ](https://softwarehq.pages.dev/categories/best-aged-care-software-australia)) and another sells leads to vendors who "Claim this listing" ([Carezano](https://carezano.com/software/lookout-care)). Lookout, AlayaCare and Visualcare don't publish prices. Nobody publishes vendor-by-vendor ratings from verified provider staff.

**Who has the pain:** The chief executive, finance or operations manager of a home care provider with 100 to 2,000 clients, at the moment they decide the current system has failed and start looking, or just before a contract renewal.

**Proof (verified):**
1. "We had to implement Excel to calculate budgets." Provider comment in the Enkindle survey. [HelloLeaders, June 2026](https://helloleaders.com.au/article/home-care-technology-is-failing-and-providers-are-paying-the-price)
2. "We have lost trust in vendors – sales pitches are misleading." Same survey, same article.
3. "Current vendor is a total disaster and shambles." Same survey, same article.

Supporting: "64 per cent of providers believe their home care systems are inadequate. The result has remained unchanged over the past four years" ([Inside Ageing, 15 June 2026](https://insideageing.com.au/home-care-providers-still-struggling-with-digital-systems-as-reform-demands-grow-survey-finds/)); one provider spent $200,000 on upgrades; "Some providers report they had to brief their own vendors on government requirements"; only 9.09% rated their upgrades "very effective".

**Pain score: 22/25.** Frequency 5, intensity 5, willingness to pay 3 (they spend six figures on systems; paying for buying advice is untested), reachability 4 (about 950 home care providers, decision-makers findable on LinkedIn and at state conferences), buildability 5.

**Closest competitors and why they miss:**
- Enkindle Consulting: runs the survey, sells consulting, does not publish vendor names against scores.
- SoftwareHQ, Carezano, Capterra, GetApp: thin coverage, editorial or vendor-funded, not specific to Support at Home rules.
- Aged Care Industry IT Council: industry body with vendor members.
- Vendors' own comparison pages (e.g. ShiftCare vs Lookout): marketing.

**Pricing guess (estimate):** free to read headline scores if you submit a review of your own system; $490 for the full comparison report; $1,500 for a shortlist call with reference contacts. No vendor money in year one, so the ratings stay credible. Reasoning: a wrong choice costs months and, per one provider, $200,000.

**MVP:**
- *Core feature:* a 12-question review form about one system (does it claim through the government interface without manual fixes, are statements compliant, does budget tracking match Services Australia, payroll link, support response, would you buy again), reviewer verified by work email, results published as one scorecard per vendor.
- *Skip:* vendor logins, advertising, residential clinical systems, feature matrices copied from vendor sites, anything needing integration.
- *Stack:* Tally form, Airtable, Softr directory, Stripe. *Estimated* cost under $100 a month.
- *14 days:* Days 1–2 question set and vendor list (about 15 systems). Days 3–5 build form, database and directory. Days 6–12 collect the first 30 reviews by direct outreach. Days 13–14 publish the first five scorecards and the report offer.

**First 10 customers:** providers who answered the Enkindle survey are the profile. Reach operations and finance managers at mid-sized home care providers on LinkedIn; Ageing Australia state conferences; home care consultants who get asked "which system?" every week and could resell the report.

**DM:** "Hi, I'm building an independent scorecard of home care systems for Support at Home, rated only by provider staff, with no vendor money. It takes 4 minutes to rate yours, and you get the full comparison free in return. Would you add your view on [system]?"

**Biggest risk:** too few reviews per vendor to be credible, and vendors threatening legal action over negative scores. **Cheapest test this week:** message 30 provider managers with the 12 questions. If fewer than 8 respond, the review supply isn't there.

### WHAT WOULD KILL THIS IDEA?
- Fewer than 8 of 30 managers will rate their system.
- Enkindle publishes vendor-level results in its next survey.
- Providers read the free scores and never buy the report.
- A vendor's lawyer letter; publish only aggregated, verified answers and get a one-hour legal check first.
- Providers are locked into multi-year contracts and can't act on the information.

---

## Idea 7 (rank 2): Roster Pay Check

**Pitch:** A fixed-price check of a home care provider's last three months of rosters and payslips for the two errors Fair Work keeps finding: broken shift allowances and minimum engagement periods.

**Gap it fills:** Fair Work found 13 of 22 aged care employers non-compliant. Payroll and rostering vendors all claim to apply the award automatically, yet the errors persist. Underpayment audit firms serve large employers. I found no low-cost self-check aimed at small providers.

**Who has the pain:** The owner or finance manager of a home care provider with 20 to 200 care workers, after reading about an enforceable undertaking or receiving a worker's pay query.

**Proof (verified):**
1. "Of the 22 employers investigated, 13 (59%) were found to be non-compliant in at least one area." [The Weekly Source, 2 Sep 2026](https://www.theweeklysource.com.au/fair-work-ombudsman-recovers-5-3-million-in-underpayments-for-3500-aged-care-workers/)
2. "The leading causes of non-compliance were incorrect employee classifications, overtime calculations, the application of broken shifts, and payment for minimum engagement periods." Same article.
3. "Aged care providers need to make sure their payroll systems are fit-for-purpose and payroll staff are properly trained." Fair Work Ombudsman Anna Booth, same article. A StewartBrown partner told a finance forum every organisation there would have an underpayment "whether you know it or not".

**Pain score: 19/25.** Frequency 5, intensity 5, willingness to pay 4 (providers already pay auditors and lawyers once caught), reachability 3, buildability 2 (award rules are intricate, and a wrong answer creates liability for you).

**Closest competitors and why they miss:**
- Payroll engines (CareIQ, BetterPayroll, TurnPoint, Statura, Humanforce): they calculate pay; they don't independently check it.
- Underpayment audit firms and the large accounting firms: priced for big employers.
- Fair Work's free pay calculator: one worker at a time.

**Pricing guess (estimate):** $1,500 per check, sold as a service first.

**MVP:** a spreadsheet model for those two rules only, run by you on exported roster and pay files, with the award clauses cited beside each flag and a clear statement that it is a screening check, not legal advice. Partner with an employment lawyer or payroll specialist for sign-off. Days 1–4 build and test the model on sample data; 5–10 run two free pilots; 11–14 price and package.

**First 10 customers:** small home care and disability providers (same award issues), through bookkeepers and accountants who serve them.

**DM:** "Hi, Fair Work found 13 of 22 aged care employers non-compliant, mostly on broken shifts and minimum engagement. I run a fixed-price check of three months of rosters against those two rules. Would you want to know before a worker or Fair Work tells you?"

**Biggest risk:** getting the award wrong. **Cheapest test this week:** ask three bookkeepers who serve care providers whether clients have asked for this, and whether they'd refer it.

### WHAT WOULD KILL THIS IDEA?
- You can't get a qualified reviewer to stand behind the results.
- Providers would rather not know.
- A payroll vendor ships an audit report.
- Professional indemnity insurance costs more than the first year's revenue.

---

## Near miss (17/25, not a pitch): Agency Shift Card

**The pain is real.** A reader on HelloCare: "some of them don't even no who has dementia their needs on a daily basis this is because they are thrown in the deep end not knowing any of their care needs" ([22 Oct 2025](https://hellocare.com.au/seen-but-not-heard-are-aged-care-agency-staff-treated-like-second-class-carers/)). Another recalls agency staff once being "given a duty sheeted with residents name with short description or residents needs... This suddenly changed so agency had to work with no guideline" ([9 Jan 2025](https://hellocare.com.au/frosty-receptions-the-silent-divide-between-agency-staff-regular-facility-staff/)). A UTS researcher: residents in homes relying more on agency staff "were more likely to be hospitalised for preventable reasons" ([Australian Ageing Agenda, 2022](https://www.australianageingagenda.com.au/research/agency-staff-linked-to-poorer-quality-of-care-says-research/)).

**Why it misses.** A one-page resident-needs sheet for agency staff means handling resident health information, which needs security you can't easily provide with no-code tools, and the clinical systems already hold the data. Site induction without resident data is already sold by Altora, LinkSafe and Induct For Work. The evidence is also a year or more old, and no provider was found asking to buy it.

### WHAT WOULD KILL THIS IDEA?
- Already below the bar. It comes back if a facility manager says they would pay, and a clinical-system vendor will let you pull the sheet from their data.

---

## Killed in this run

| Idea | Why | Link |
|---|---|---|
| Support at Home claim file checker | quickclaim and VIPS Care validate claims before submission | https://quickclaim.com.au/resources/support-at-home/support-at-home-financial-sustainability |
| Agency staff site induction | Altora, LinkSafe, Induct For Work | https://linksafe.com.au/aged-care-induction-software/ |
| Portable training record for workers | Ausmed Passport; planned worker registration scheme | https://www.ausmed.com/organisations/thebuild/aged-care-worker-registration-scheme |
| Paid-training-time tracker | One case (Regis); learning systems already report duration | https://hellocare.com.au/regis-to-back-pay-staff-for-unpaid-mandatory-training-after-fair-work-dispute/ |
| Nursing agency back-office software | Rosterflux, Humanz, 20X, NextCrew | https://rosterflux.com/industries/nursing |
| Better worker roster app | Complaints are vendor bugs; workers don't choose or pay | https://apps.apple.com/au/app/id1550225245 |
| Worker screening tracker | CVCheck, Checkmate, Koora (killed night 1, still true) | https://cvcheck.com/articles/aged-care-act-2024-worker-screening-updates-what-providers-need-to-know/ |

## Updated overall ranking (all runs)

1. **VendorCheck** (22): strongest proof of a paying audience with a problem nobody covers.
2. **PaidUp** (22): families and workers chasing unpaid invoices; fresh evidence again today from a Mable worker: "I've been waiting to get paid since May... Go private if you can."
3. **Roster Pay Check** (19): strong pain, hard to deliver safely.
4. **HELF Check** (18).
5. BedHunt and Price Receipt: on paper only.

## Strongest quote

> "We have lost trust in vendors – sales pitches are misleading."
> — home care provider, Enkindle 2026 survey, quoted by [HelloLeaders](https://helloleaders.com.au/article/home-care-technology-is-failing-and-providers-are-paying-the-price)

## Test today

**VendorCheck.** Write the 12 questions and send them to 30 home care operations or finance managers on LinkedIn. Eight or more answers means the review supply exists; then publish the first scorecards.
