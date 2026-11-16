# Residential-only brief: 16 Nov 2026 (second run)

## Read this first

- **Quotes are not verified at source.** Pages still could not be opened; every quote and figure is the text a search excerpt showed for the linked page. Where the excerpt gave a paraphrase, it is labelled as one. Confirm at the link before repeating anything.
- **Reddit, X, Facebook groups and app stores were unreachable.** Reddit also blocks the search tool. Evidence comes from news, peak-body reports, the regulator and review sites.
- **Only two ideas cleared the 18/25 bar.** The third is shown as a watch-list candidate so you can see why it failed, not as a pitch.
- Scores and prices are my estimates. No market sizes are claimed.

## Residential market in 5 lines

1. Homes are full: national occupancy 93.44% in August 2026, a record, and the average wait for a bed is reported at 365 days.
2. More than 3,600 people sit in hospital waiting for a place; respite beds are being turned into permanent beds.
3. Only 661 residential providers remain and about 60 left last year, so cheap software for homes has too few buyers. The reachable customer is the family.
4. Families who want help finding a bed pay $1,000–$4,000 to placement services, or use Aged Care Decisions, which is free to them and charges the home $2,950.
5. Fees are a top-three complaint (complaints up 45%); the regulator forced one provider to refund almost $200,000 over Higher Everyday Living Fees.

---

## Idea 4 (rank 1): BedHunt

**Pitch:** For a flat fee, we phone every aged care home in your area and send you a same-day list of which ones have a respite or permanent bed, with minimum stay, fees and how to apply, then re-check weekly.

**Gap it fills:** There is no live vacancy data. My Aged Care shows which homes offer respite, not whether a bed is free. Families are told to ring each home, and to "call back closer to the time". Full-service placement costs $1,000–$4,000. Free matching services are paid per permanent placement by the home, which gives them little reason to chase a two-week respite stay (my inference, not confirmed). Nothing found sells a cheap, respite-first ring-around.

**Who has the pain:** A family carer, usually an adult child or spouse, in one of two moments: they need two weeks of respite for a planned operation or a break, or a parent is in hospital and the discharge planner wants a bed found this week.

**Proof (search excerpts, unverified at source):**
1. Six in 10 carers reported difficulty finding high-quality respite, and nearly 60 per cent difficulty finding services locally (2025 Carer Wellbeing Survey, cited in the [Dementia Australia and Carers Australia joint statement, Aug 2026](https://www.carersaustralia.com.au/wp-content/uploads/2026/09/Dementia-Australia-and-Carers-Australia-A-Joint-Position-Statement-August-2026-Final.pdf)).
2. A care concierge told HelloCare respite has become close to impossible to get, and providers say they can no longer hold beds for respite (paraphrase). [HelloCare](https://hellocare.com.au/no-relief-respite-beds-are-disappearing-as-aged-care-fills-up/)
3. Betty Cameron has waited two years for a bed for her husband with dementia in South Australia (paraphrase). [ABC News, 9 Nov 2026](https://www.abc.net.au/news/2026-11-09/residential-aged-care-bed-waitlist-south-australia-families/107341030)

Supporting: "your approval for respite care does not guarantee a place" ([My Aged Care](https://www.myagedcare.gov.au/connect-residential-respite-providers)); many respite providers require minimum four-week stays and Carers ACT reports almost none available ([Carers Australia](https://www.carersaustralia.com.au/wp-content/uploads/2026/02/Carers-Australia-Pre-Budget-Submission-2026-27.pdf)).

**Pain score: 22/25.** Frequency 5, intensity 5, willingness to pay 3 (people already pay thousands for placement; a cheap tier is untested), reachability 4 (carer and dementia Facebook groups, state carer organisations, hospital social workers), buildability 5 (it is a phone service with a form and a spreadsheet).

**Closest competitors and why they miss:**
- [Aged Care Decisions](https://agedcaredecisions.com.au/faq/): free to families, paid $2,950 by the home per placement, so only shows homes that pay.
- [Care & Co Match](https://careandcomatch.com.au/): $350 advice, $3,900 residential concierge. High-touch and expensive.
- Private placement consultants: $1,000–$4,000, aimed at permanent placement.
- Carer Gateway (1800 422 737): government phone line for emergency respite only.
- My Aged Care Find a provider: no live availability.

**Pricing guess (estimate):** $99 for a one-off ring-around of up to 15 homes; $49 a week for weekly re-checks while waiting. Reasoning: under a tenth of the cheapest placement service, and about what a carer would lose in half a day off work making the calls.

**MVP:**
- *Core feature:* intake form (postcode, radius, dates, care needs, respite or permanent), you or a virtual assistant make the calls from a script, results go into a table, the family gets a one-page report by email the same day.
- *Skip:* an app, a public vacancy database, fee advice, tours, application help, any payment from homes.
- *Stack:* Tally form, Airtable (home list from the public My Aged Care provider search), a phone, Stripe payment link, email. *Estimated* cost under $100 a month plus calling time.
- *14 days:* Days 1–2 build the home list and call script for one city. Days 3–4 form, payment link, report template. Days 5–10 run 10 searches free or at half price and time every call. Days 11–12 work out cost per search. Days 13–14 landing page and first paid posts.

**First 10 customers:** dementia and carer Facebook groups in one city; state carers organisation noticeboards; hospital social workers and discharge planners (ask them to hand out a card); local Dementia Australia support groups; GPs' practice nurses.

**DM:** "Hi, I saw you're looking for respite for your mum. I run a small service that phones every home within 20 km and sends you a list the same day of who has a bed for your dates, the minimum stay and the cost. First ten families are free while I test it. Want me to run yours?"

**Biggest risk:** There are simply no beds, so the report says "nothing available" and the family feels cheated. **Cheapest test this week:** pick one metro postcode, call 15 homes asking for a two-week respite stay next month, and record how many say yes. If fewer than 2 in 15, the service cannot deliver.

### WHAT WOULD KILL THIS IDEA?
- The test call-round finds almost no respite beds anywhere.
- Homes refuse to give availability to a third party.
- Aged Care Decisions turns out to handle respite well for free (open question 7 in `gaps.md`).
- Each search takes more than about 2 hours of calling, so $99 loses money.
- It is a service, not software: it grows only as fast as you can add callers. A placement company could copy it in a week, but their fee model points them at permanent placements.

---

## Idea 5 (rank 2): HELF Check

**Pitch:** Upload your parent's fee agreement and latest invoice, and get a plain-English report of extra charges that may not be allowed, with a ready-to-send letter asking the home for a refund.

**Gap it fills:** Higher Everyday Living Fees are optional, need their own agreement, and cannot cover services the resident cannot use or that used to be free. From 1 November 2026, residents who were in care before 1 November 2025 cannot be charged for services they previously got at no extra cost. The regulator is investigating several providers, but families must first notice the problem. Tools for homes exist (five vendors); fee calculators for families exist (seven or more); Wayly checks invoices for home care only. One residential billing review service, RADCheck, turned up, with unknown current status.

**Who has the pain:** The son or daughter who pays the nursing home invoice, at the moment a new agreement arrives or the monthly bill jumps.

**Proof (search excerpts, unverified at source):**
1. "We are very concerned about the use of Higher Everyday Living Fees in relation to meals. This is not optional. This is not an additional service." — Commissioner Liz Hefren-Webb. [Commission media release, 3 July 2026](https://www.agedcarequality.gov.au/news-publications/media-releases/commission-cracks-down-misuse-higher-everyday-living-fees)
2. A family was billed $52 a day for Foxtel, outings, newspapers and wine, including services a resident with dementia could not use (paraphrase). [YourLifeChoices](https://www.yourlifechoices.com.au/health/aged-care/hidden-aged-care-fees-leave-families-paying-52-a-day-for-services-some-residents-cant-use/)
3. "I won't be eating" — headline quote from a story in which a resident's husband fears costs rising by about $14,000 a year. [The Senior](https://www.thesenior.com.au/story/9255704/i-wont-be-eating-families-panic-over-changes-to-aged-care-fees/)

Supporting: 199 fee complaints about residential homes in the first half of 2026; Opal HealthCare refunded or credited almost $200,000 to almost 350 residents ([SBS, 10 Sep 2026](https://www.sbs.com.au/news/article/aged-care-giant-refunds-200k-to-residents-over-disputed-living-fees/1ukykrdg5)).

**Pain score: 18/25.** Frequency 4, intensity 4, willingness to pay 3, reachability 3 (families are scattered; seniors' media and carer groups are the route), buildability 4.

**Closest competitors and why they miss:**
- [Wayly](https://wayly.com.au/): invoice checker for Support at Home; no residential or HELF coverage found.
- [RADCheck](https://radcheck.com.au/aged-care-billing-review/): residential billing review; page looks old, status unknown (open question 6).
- Older Persons Advocacy Network: free advocates, but the family has to know to call.
- Aged care financial advisers and lawyers: thousands of dollars, focused on entry decisions.
- The Commission: acts on complaints, provider by provider.

**Pricing guess (estimate):** $49 per check, or free check plus $99 for the letter and follow-up pack. Reasoning: HELF bundles are reported at $42–$52 a day, so one disputed week exceeds the price.

**MVP:**
- *Core feature:* upload agreement and invoice; a checklist built from the Department's HELF rules and Commission bulletin RB 2026-3 flags items (meals, services the resident cannot use, services previously free, no separate agreement, no annual review); output is a report and a letter. Start by doing the checks by hand with AI assistance, reviewed by you.
- *Skip:* means-test and accommodation calculations, financial advice, complaint lodging on the family's behalf, accounts.
- *Stack:* Tally upload form, Airtable, a document-reading AI step in Make, Google Docs template for the letter, Stripe.
- *14 days:* Days 1–3 turn the official rules into a 15-point checklist. Days 4–6 form and report template. Days 7–10 run 10 real invoices free. Days 11–12 measure how many had a flaggable item. Days 13–14 landing page and outreach to seniors' media.

**First 10 customers:** commenters on the fee stories at The Senior, YourLifeChoices and Starts at 60; carer Facebook groups; National Seniors branches; accountants and bookkeepers who pay bills for elderly clients.

**DM:** "Hi, I read your comment about the extra daily fees at your mum's home. I'm testing a free check: send me the fee agreement and one invoice with names blacked out, and I'll tell you which charges the rules may not allow and draft a letter you can send. Interested?"

**Biggest risk:** It strays into legal or financial advice, or families fear upsetting the home that cares for their parent. **Cheapest test this week:** get 5 real HELF agreements and see whether your checklist finds a likely breach in at least 2.

### WHAT WOULD KILL THIS IDEA?
- RADCheck is alive and cheap, or Wayly adds residential (it could within weeks).
- The crackdown works and homes fix their agreements, so there is nothing left to find.
- Fewer than 2 in 5 real agreements show a problem.
- A lawyer says the letter needs legal sign-off.
- Families will not challenge the home. Repeat custom is also low: one check per family.

---

## Watch-list only (16/25, not a pitch): apply-once pack

Families typically apply to three to six homes and most homes have their own form ([Aged Care Connect](https://agedcareconnect.com.au/aged-care-faqs-applications.php)). A single pack that fills each home's form from one set of answers would be easy to build. It fails the bar because I found nobody complaining about the forms; the pain people voice is the wait, not the paperwork. It could become a paid add-on to BedHunt if customers ask for it.

### WHAT WOULD KILL THIS IDEA?
- It already scores below the bar. It stays dead unless BedHunt customers ask for application help unprompted.

---

## Killed in this run

Waitlist manager for homes (NeRA, Pluss, CareOS); service agreement transition kit (deadline passed, lawyers); fee estimator (seven free ones); home comparison on complaints data (crowded); GP access (needs doctors); nurse paperwork (needs clinical-system integration); agency staffing (marketplace). Details in `gaps.md`.

## Strongest quote of the run

> "We are very concerned about the use of Higher Everyday Living Fees in relation to meals. This is not optional. This is not an additional service."
> — Aged Care Quality and Safety Commissioner Liz Hefren-Webb, [3 July 2026](https://www.agedcarequality.gov.au/news-publications/media-releases/commission-cracks-down-misuse-higher-everyday-living-fees) (search excerpt; confirm at source)

## The one to test today

**BedHunt.** First step: choose one metro postcode and phone 15 homes asking for a two-week respite stay next month. Log who has a bed, the minimum stay and how long each call took. That one afternoon tells you whether there is anything to sell and what it costs to deliver.

## Final check

| Question | BedHunt | HELF Check |
|---|---|---|
| Really unknown? | Cheap respite-first tier not found; placement services exist above it | RADCheck unresolved; Wayly adjacent |
| Stranger pays in week one? | Plausible: urgent need, low price | Possible after a free check finds money |
| Quotes real and linked? | Linked; mostly paraphrase; unverified at source | Linked; one direct quote; unverified at source |
| Big company copies in a weekend? | Yes, but their fee model points elsewhere | Yes |
