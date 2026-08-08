# Weekly summary — week of 2026-08-08

## New postings found (7)

**Track 1 — Building Surveying** (all via RICS Recruit)

- **Graduate Building Surveyor — Central London — Brandon James**. Projects span commercial/residential/retail/heritage/public sectors, full APC support.
- **Graduate Building Surveyor — City of London — Brandon James**. £28,000-£35,000, 28 days annual leave + bank holidays, structured APC support and mentorship. Framed as "on the APC pathway or intending to work towards chartership" — slightly more open language than most of this batch.
- **Graduate Building Surveyor — London — EC Property Recruitment**. £27,000-£30,000, Private Healthcare, Professional Membership Support, APC Support, Hybrid Working.
- **Graduate Building Surveyor — Central London — Carriera Recruitment**. x2 openings, commercial projects, TDD & dilapidations focus, strong APC support quoted.
- **Graduate Building Surveyor — Tower Bridge — Carriera Recruitment**. x2 openings, boutique consultancy, 100% APC pass rate quoted.
- **Graduate Building Surveyor — London — HD Surveyors**. Distinct posting from the existing deprioritised HD Surveyors – Glasgow entry — this one is London-based, so the non-commutable-location exclude doesn't apply. Permanent, hybrid, structured APC progression.

All six are standard graduate-agency listings and **FLAGGED — uncertain fit**: the ad copy doesn't say outright whether a part-qualified/currently-studying candidate is acceptable (same open question as last week's Turner Property Recruitment — London entry). Kept per instructions to include-and-flag rather than drop. Worth a direct enquiry to each agency about compatibility with an ongoing part-time MSc before applying.

**Track 2 — Heritage & Community**

- **Community Engagement and Volunteer Coordinator — Bevis Marks Synagogue Heritage Foundation**. Historic Bevis Marks Synagogue (built 1701, oldest in the UK), City of London — strong built-heritage/community-engagement fit for Track 2, establishing a community engagement and volunteer programme at the visitor attraction. **FLAGGED — uncertain currency**: search results mixed what looks like a 2024 posting (deadline 8 Jul, salary £27k-£33k) with a possible re-listing (salary £35k-£38k) — couldn't confirm via direct fetch whether the specific CharityJob listing found is currently live or a stale/cached duplicate (charityjob.co.uk fetch was blocked this run, see Source notes below). Check charityjob.co.uk directly before applying.

## Deadline changes on existing entries

None of the tracked deadlines changed. Reconfirmed as still accurate:
- Turner & Townsend Graduate Development Programme: still 2026-11-13 (2027 cohort opens 17 Sept 2026) — dates unchanged from last week.
- Civil Service Fast Stream: still 2026-11-05 estimate — official 2027 dates still not formally published; direct page fetch blocked this run (see below), no change to the tracked estimate.

Light "reconfirmed" notes added to 6 existing entries (Turner & Townsend, AtkinsRéalis, CBRE, Fast Stream, Frankham, Turner Property Recruitment — London) — no statuses changed. Frankham stays "applied", AtkinsRéalis stays "researching".

## Excluded this run

- **British Museum — Events Coordinator (CharityJob)**. Same listing flagged as stale/mis-indexed last week — now confirmed: its deadline was 12pm, 15 May 2026, already three months past. Not added.
- **Royal Albert Hall role (via CultureJobs/search)**. Deadline 20 Jul 2026, already passed. Stale/closed, not added.
- A handful of other Track 2 leads surfaced only as vague search snippets this run (a generic recruiter "Events Coordinator" listing, an unnamed "400-acre estate" events role, an international heritage-crafts charity events role) — none had enough confirmed detail (employer name, direct link, or deadline) to evaluate against the fit rules, and direct verification fetches were blocked (see Source notes). Not added; worth re-checking next run once fetch access is restored.

## Source notes / parsing issues

- **Network egress policy change this run**: direct `WebFetch` calls to `ricsrecruit.com`, `charityjob.co.uk`, and `civil-service-careers.gov.uk` were all blocked ("EGRESS_BLOCKED") by the network proxy. This is new — those same domains were fetchable in prior runs. Everything sourced from these three sites this week is based on `WebSearch` result summaries only, not verified full-page fetches. That's a real fidelity downgrade: exact closing dates and precise degree-requirement wording on the six new RICS Recruit listings and the Bevis Marks CharityJob listing could not be independently double-checked. Flagging so a human can spot-check the live pages directly, and so future runs know to watch whether this is a persistent policy change or a one-off blip.
- **CBRE UK careers page**: still no 2027 deadline confirmed via search; direct fetch blocked this run same as above (last run it was a 403, this run a proxy block — page itself remains unverified two runs running).
- **CultureJobs / Arts Council-adjacent boards**: continues to mostly resolve back into CharityJob's arts/culture/heritage filter rather than a distinct indexable board, consistent with last week's note.
- **Bevis Marks Synagogue Heritage Foundation** listing: see uncertain-currency flag above — recommend manual confirmation.

## Dashboard

Published a static, read-only dashboard snapshot (reusing the original tracker board's blueprint/brass card design) at the URL below, generated directly from this run's `tracker.json`. This is the first run publishing via the Artifact tool — the URL has been saved to `tracker.json`'s top-level `dashboard_url` field so future runs update the same page instead of minting a new one.

**Dashboard:** https://claude.ai/code/artifact/fad5e6b1-cff1-4497-a113-7ea44d030f9a

## Fit rules

No changes to fit rules this run (last updated 2026-08-07, see README.md). All new entries evaluated against the existing hard excludes, including the completed-degree/immediate-start/non-commutable-location rules, with the 2027-cohort location exemption applied where relevant.
