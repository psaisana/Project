# Australian aged care: running market file

Last updated: 2026-11-16 (night 1). Figures are as reported by the linked source; anything marked *estimate* is not an official number.

**Method limit, night 1:** this session could run web searches but could not open pages directly (network policy allowed no outside hosts). Every figure and quote below comes from search-result excerpts of the linked page and has not been re-read at source. Check the link before relying on any single number.

## How the money flows

- **Who pays:** the Commonwealth pays most of it. One consumer guide puts 2025-26 aged care spending at about $36 billion with government covering about 75% of costs (*secondary-source estimate*, [Carevo](https://carevo.com.au/blog/aged-care-funding-how-it-works-australia-guide)). Older people pay the rest through means-tested contributions, accommodation payments and optional extras.
- **Home care (Support at Home, since 1 Nov 2025):** Services Australia pays registered providers per claimed service against each participant's quarterly budget. 364,723 people had access at 31 March 2026, 338,049 receiving care, 950 approved providers ([GEN data report Q3 2025-26](https://www.gen-agedcaredata.gov.au/getmedia/88363448-d30b-4958-8823-df697cb5f769/Support-at-Home-Program-Data-Report-Q3-2025-26-corrected)). Providers keep care management (capped at 10% of budget) and a margin on service prices; they pay staff, subcontractors, independent workers, equipment suppliers and software vendors.
- **Residential:** AN-ACC subsidy per resident plus care-minutes supplement tied to quarterly reported minutes; residents pay basic daily fee, hotelling, accommodation (RAD/DAP) and optional Higher Everyday Living Fees.
- **Who gets paid downstream:** workers (direct, agency, or sole traders via platforms such as Mable), allied health, equipment suppliers, software vendors, consultants, auditors and lawyers.

## Biggest products and prices

| Product | What it is | Price (as found) | Source |
|---|---|---|---|
| Mable | Marketplace for independent workers | Client fee 7.95% on top, worker fee 10% off; 16.6% combined on a $58 rate | [Mable fees](https://mable.com.au/help_centre/a-guide-to-fees-on-mable/) |
| ShiftCare | Rostering/care platform, small providers | $8–$20 per user/month (annual), min 5 users; Support at Home add-on $5 per client | [ShiftCare pricing](https://shiftcare.com/pricing) |
| Lookout | Home care platform | Not published; a competitor page claims "from $300/month" (*unverified*) | [ShiftCare comparison](https://shiftcare.com/compare/the-lookout-way) |
| AlayaCare | Enterprise home care platform | Quote-based; listing sites show a US$1,000/month floor (*unverified*) | [Software Advice](https://www.softwareadvice.com/medical/alayacare-profile/) |
| Visualcare | Home care platform | Not published | [Capterra](https://www.capterra.com/p/238548/Visualcare/) |
| Wayly | Family-side statement decoder and invoice checker | $24.50/fortnight solo, $49.50/fortnight family | [Wayly](https://wayly.com.au/) |

## Funding and new entrants (last ~12 months)

- Andromeda (companion robots): A$23m Series A ([IT Brief](https://itbrief.com.au/story/andromeda-raises-aud-23m-to-launch-robots-for-aged-care))
- Kismet (fraud and non-compliance in disability and aged care): $8.2m seed, Prosus and Airtree; date not confirmed
- Billy (home monitoring): about A$5m incl. ECH, June 2026 ([Weekly Source](https://www.theweeklysource.com.au/page/ech-invests-5m-in-new-australian-health-tech-startup-billy?amp=1))
- InteliCare: A$2.05m placement May 2026; $8.8m deal across 22 Victorian facilities
- hayylo: investment from Agnes Investments and a Sprint aged-care fund, 2026
- Amplar Health (Medibank): $31.2m government virtual-nurse trial to June 2027
- Small new tools spotted tonight: Wayly, Invoice Harbour, didyougo, Governa AI, helf.services, Statura Care, Centrim Life HELF module, Pluss

## Growing

- Support at Home compliance tooling (claiming, statements, care-management time, evidence)
- Self-managed home care (Trilogy Care, HomeMade) and independent workers
- Regulator enforcement on fees: HELF investigations, one large provider refunded almost $200,000 to about 350 residents ([SBS](https://www.sbs.com.au/news/article/aged-care-giant-refunds-200k-to-residents-over-disputed-living-fees/1ukykrdg5))
- Payment integrity: rolling review of all Support at Home providers since Feb 2026
- Virtual nursing and AI rostering (the latter contested by the United Workers Union)

## Dying or stalled

- CHSP merger into Support at Home: abandoned August 2026, CHSP stays standalone to at least mid-2029 ([Health Services Daily](https://www.healthservicesdaily.com.au/government-abandons-plan-to-fold-chsp-into-support-at-home/51193))
- Old package-management and admin fee revenue: banned; care management capped at 10%
- Extra and additional service fees: replaced by HELF, transition ended 31 Oct 2026
- Assistive technology spend: reported about 30% lower than before the new program (Aidacare CEO, [Ageing Agenda](https://theageingagenda.com.au/executive/prioritise-at-hm-and-it-can-deliver-outsized-returns/))

## Categories where customers pay a lot and still complain

1. **Self-managed home care providers** (Trilogy Care, HomeMade): take a cut of every budget, reviews full of rejected and unpaid worker invoices.
2. **Mable**: 16.6% combined take, complaints about slow pay and fee transparency.
3. **Home care platforms**: providers pay per user and per client and still report heavy admin (one provider group told the Senate inquiry about 31 minutes of admin per hour of care, [Weekly Source](https://www.theweeklysource.com.au/31-minutes-of-admin-for-every-hour-of-care-support-at-home-inquiry/)).

## Watch list (dates)

- 24 Nov 2026: Senate committee report on Support at Home due
- Support at Home price caps: original 1 July 2026 start deferred; watch for new date
- New aged care worker screening check: timeline removed in March 2026 guidance

## Weekly tracking

Recurring pains are tracked in `pains.csv` (column `nights_seen`). Ideas already pitched or killed are listed in `gaps.md`; never pitch those again.
