# Verified rerun: 17 Nov 2026 (Sydney time)

## What is different this time

- **Pages now open.** Every quote below marked *verified* was read on the linked page today, with its date.
- **Still blocked:** Trustpilot refuses automated requests (403), so the Trustpilot quotes from night 1 remain unverified and are no longer used as proof. The Commission's site and radcheck.com.au did not respond. YourLifeChoices refused (403). Reddit, X and Facebook groups were not attempted.
- **Verification changed the ranking.** One idea got stronger, one got weaker, one fell below the bar.

## Ranking after verification

| Rank | Idea | Score | Change |
|---|---|---|---|
| 1 | PaidUp (was PaidFirstTime) | 22 | Stronger, and reshaped |
| 2 | HELF Check | 18 | Holds, with fresh proof |
| 3 | BedHunt | 22 on paper | Pain confirmed, but the source says the beds may not exist |
| 4 | Price Receipt | 20 on paper | Figures confirmed; still regulator data, not customer asks |
| out | AT-HM Pack | 16 | Below bar: the source says funding, not paperwork, is the blocker |

---

## 1. PaidUp: get care-worker invoices paid under self-managed home care

**What the sources show (all verified, all inside 30 days):**
- "HomeMade has failed to pay invoices for over six months, leaving service providers chasing me for payment on an almost daily basis." [ProductReview, HomeMade Support, 9 Nov 2026](https://www.productreview.com.au/listings/homemade-support)
- "Trilogy has DEFAULTED on paying seven business suppliers amounting to $2700. More than double that is/was available to pay those invoices. I say is/was because it now appears that since Trilogy did not pay the invoices, those funds are returned to the government never to be seen again." [ProductReview, Trilogy Care, 25 Oct 2026](https://www.productreview.com.au/listings/trilogy-care)
- "As a Support Worker I am very disappointed in Mable & cannot recommend. If Invoices are not paid they do nothing to assist." [ProductReview, Mable, 8 Nov 2026](https://www.productreview.com.au/listings/mable)
- "Still waiting in November since June, to have my care workers invoices paid, some going back to March 2026..." [ProductReview, Let's Get Care, 5 Nov 2026](https://www.productreview.com.au/listings/lets-get-care)

**What changed in the idea.** Night 1 assumed invoices fail because of format. That is true at Trilogy Care, which says it will "Automatically reject invoices that don't meet the Support at Home and Trilogy Care requirements" and that "bundled or vague invoices now have to be rejected" ([Trilogy billing page](https://trilogycare.com.au/support-at-home-billing-changes-what-you-need-to-know)). But the HomeMade and Let's Get Care reviews describe provider accounting failures, where a perfect invoice still goes unpaid. So a formatter alone solves half the problem.

**Reshaped product:** one place where the self-managing family and their workers (a) create an invoice that passes the provider's rules, (b) log when it was submitted, (c) see days outstanding against the quarter-end cut-off after which funds are lost, and (d) send a pre-written chase, then a complaint letter, when it goes overdue.

**Who pays:** the family member who self-manages (they are the one being chased daily and losing carers), with a free seat for each worker.

**Competitors, checked today:**
- [Earni](https://earni.au/): its site says "Pre-filled invoices – built-in NDIS price guide". No mention of Support at Home. Night 1's open question is answered: it does not cover this.
- [Wayly](https://wayly.com.au/features): "Verify every line item against medians and budget the moment the invoice lands." It checks what the provider charges the family; it does not create worker invoices or chase unpaid ones. It is the closest and the likeliest to expand.
- Mable: reviewers say it does not help recover unpaid invoices.

**Score: 22/25.** Frequency 5, intensity 5, willingness to pay 3, reachability 4, buildability 5.

**Pricing guess (estimate):** $15 a month per family, workers free.

**MVP (14 days, no-code):** Airtable base, Softr portal with family and worker logins, invoice form with the Trilogy rules as checks, a status board with a quarter-end countdown, and three letter templates. Days 1–3 rules and data model; 4–8 build; 9–12 five families use it on live invoices; 13–14 pricing page.

**First 10 customers:** the reviewers themselves are the profile: people who self-manage for one to three parents through Trilogy Care, HomeMade or Let's Get Care. Find them in self-managed home care Facebook groups and through the workers they employ.

**DM:** "Hi, are you self-managing a Support at Home package and chasing a provider to pay your carers? I'm building a simple tracker that makes compliant invoices, shows what's overdue before the quarter closes, and writes the chase and complaint letters. Free while I test. Want in?"

**Cheapest test this week:** offer to track and chase five families' overdue invoices by hand with a spreadsheet and letter templates. Count how many get paid within 3 weeks.

### WHAT WOULD KILL THIS IDEA?
- Chasing changes nothing because the providers' accounting is broken; the tool then only documents the failure.
- Families respond by switching provider instead (one reviewer asked "Are there any recommendations for better self management providers ?").
- Wayly adds invoice creation and chasing.
- Providers fix payments once the transition settles; the reviews say the opposite a year in, but watch it.

---

## 2. HELF Check: find nursing-home extra fees that may not be allowed

**Verified proof:**
- "Bupa are going to charge residents $42 for a hot breakfast!! Pure greed." [ProductReview, Bupa Aged Care, 10 Nov 2026](https://www.productreview.com.au/listings/bupa-aged-care)
- "Once I have to pay that I won't be eating at all." Resident "Bill" (name changed), on being told to sign a new contract. [The Senior, 2 June 2026](https://www.thesenior.com.au/story/9255704/i-wont-be-eating-families-panic-over-changes-to-aged-care-fees/)
- "Every time they want me to sign something, I get agitated and just find it so difficult." Same resident, same article.

**Not verified today:** the Commissioner's "This is not optional" quote (Commission site did not respond) and the $52-a-day story (site refused). RADCheck's site did not respond either, so that competitor is still unresolved; a dead site would be good news for this idea.

**Competitor check:** Wayly's features page has no mention of residential care or these fees.

**Score: 18/25, unchanged.** The plan, pricing and kill list from the residential brief stand.

### WHAT WOULD KILL THIS IDEA?
- RADCheck is alive and cheap, or Wayly adds residential.
- The Commission's crackdown fixes agreements before you launch.
- Fewer than 2 in 5 real agreements show a problem.
- Families won't challenge the home caring for their parent.

---

## 3. BedHunt: the pain is confirmed, and so is the risk

**Verified proof** ([HelloCare, 13 Oct 2026](https://hellocare.com.au/no-relief-respite-beds-are-disappearing-as-aged-care-fills-up/), quoting Kate Montgomerie of Care & Co Match):
- "I get calls from carers almost every week who are desperately seeking to book a loved one into respite... Most often they have already called nearly every aged care home in their area and beyond, with no luck."
- "Lots of homes say short-term respite when you look at their website but when you call they are full, and not keeping respite beds aside."
- "Carers are told to call back closer to the time of need, however they then run the risk of leaving it too late with no viable options."

And from [ABC News, 9 Nov 2026](https://www.abc.net.au/news/2026-11-09/residential-aged-care-bed-waitlist-south-australia-families/107341030): Betty Cameron, two years waiting for a bed for her husband: "I get more days of wanting to punch people out than I do good days."

**Why it drops to third.** The same source says a respite stay in NSW, "and increasingly in QLD, is virtually impossible", offered only as "respite with a view to permanent". A ring-around service that reports "nothing available" has nothing to sell. Aged Care Decisions also lists "Find Respite Care" on a service that is "100% free for families" ([FAQ](https://agedcaredecisions.com.au/faq/)).

**Where the money might be instead.** Montgomerie describes families paying privately: "one family was willing to pay privately as they had no other option to cover 4 days". A finder for paid short-cover options (private overnight carers, cottage respite, private hospital stays) addresses the same moment with supply that exists. This is a hypothesis from one source.

### WHAT WOULD KILL THIS IDEA?
- The 15-call test finds no respite beds (the source suggests it will in NSW and Queensland; try another state).
- Aged Care Decisions' free respite search works well.
- Private short-cover is too expensive for most carers, so the pivot has too few buyers.

---

## 4. Price Receipt: figures confirmed, case unchanged

Verified on [The Ageing Agenda, 30 Sep 2026](https://theageingagenda.com.au/executive/policy/evidence-gaps-in-sah-delivery/): "just 35 per cent of all claims had sufficient evidence of agreed price"; "21 per cent of the 262 Support at Home monthly statements reviewed had all required inclusions and... 51 of the 60 providers reviewed received findings relating to monthly statements." Still no provider found asking for a tool. Ranking and kill list unchanged.

### WHAT WOULD KILL THIS IDEA?
- A platform already does per-change price confirmation.
- Failing the review carries no real penalty.
- Participants won't confirm by text.

---

## Dropped: AT-HM Pack

The quotes were real, but the full article says the blocker is money, not documents. Serena Ovens: suppliers are "doing more work than ever" in providing quotes and information but there is "nothing coming out of the pipeline." Christina Wyatt: "approximately 80 per cent of older people referred to an OT did not have adequate AT-HM funding available at the time of their initial assessment." ([Australian Ageing Agenda, 1 July 2026](https://www.australianageingagenda.com.au/technology/at-hm-rollout-problematic-unnecessarily-complex/)). A faster evidence pack does not release funding. Re-scored 16/25. One thread worth watching: Wyatt asks for "clear guidance on how to navigate the scheme, what steps are required, and what evidence is needed", and providers wrongly demand three quotes for equipment.

### WHAT WOULD KILL THIS IDEA?
- Already below the bar. It returns only if funding starts flowing and rework becomes the complaint.

---

## Strongest quote

> "HomeMade has failed to pay invoices for over six months, leaving service providers chasing me for payment on an almost daily basis."
> — verified reviewer, [ProductReview, 9 Nov 2026](https://www.productreview.com.au/listings/homemade-support)

## Test today

**PaidUp.** Find five people self-managing through Trilogy Care, HomeMade or Let's Get Care with overdue carer invoices. Track and chase their invoices by hand for three weeks. If chasing gets invoices paid, build it.
