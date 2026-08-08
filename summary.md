# Weekly summary — week of 2026-08-08

**Note on cadence:** this run fired at 11:21 UTC, 2026-08-08 — the same day as the
previous run (01:57 UTC, 2026-08-08). Two runs landed on the same calendar day
because of how the schedule fired this week, not because anything requested it.
Sources were re-checked lightly rather than re-crawled in depth, since almost
nothing changes source-side in a ~9.5 hour window. One genuinely new lead
surfaced (SPAB, below); everything else tracked from the morning run held
steady.

## New postings found (1)

**Track 2 — Heritage & Community**

- **Learning Programmes Manager — SPAB (Society for the Protection of Ancient
  Buildings)**. SPAB is the leading UK building conservation charity (founded
  by William Morris, 1877) — strong built-heritage fit. Coordinates and
  delivers SPAB's annual Scholarship and Fellowship learning programmes.
  £36,000–£40,000, location flexible. **Deadline 19 Aug 2026 — only 11 days
  out, the most urgent item in the tracker right now.** FLAGGED — uncertain
  fit on two counts: titled "Manager" not "Coordinator" (included anyway —
  substance is programme coordination, close enough to the Track 2
  coordinator/programme-administrator criteria); and full-time status /
  start-date flexibility isn't confirmed, so compatibility with an ongoing
  part-time MSc needs a direct check before applying. The link saved is a
  Heritage Alliance write-up with an "apply here" pointer, not confirmed to
  be SPAB's own posting URL — verify on spab.org.uk or charityjob.co.uk given
  the tight deadline.

No new Track 1 leads: the RICS Recruit search returned the same eight
postings already in the tracker (Brandon James ×2, EC Property Recruitment,
Carriera Recruitment ×2, HD Surveyors, Turner Property Recruitment ×2) —
nothing new since this morning.

## Deadline changes on existing entries

None. Turner & Townsend (2026-11-13), Fast Stream (2026-11-05 estimate), and
all other tracked deadlines are unchanged from this morning's run.

## Excluded this run

- **Southwark Cathedral — "Engagment Co-ordinator"** (CharityJob 1063784).
  Otherwise a plausible Track 2 fit, but the listing is confirmed closed —
  not added.
- A handful of other Track 2 search hits (Southwark Cathedral Audience
  Development Coordinator via Arts Jobs, various council culture/heritage
  manager posts at Hackney and City of London, a Public Experience Producer
  role at SS Great Britain) surfaced only as generic search snippets without
  a confirmed direct listing, deadline, or enough detail to evaluate against
  the fit rules this run. Not added; worth a closer look on a future run if
  they resurface with more detail.

## Source notes / parsing issues

- **Network egress policy**: `WebFetch` to `ricsrecruit.com`,
  `charityjob.co.uk`, `civil-service-careers.gov.uk`, and this run also
  `frankham.com` all returned `EGRESS_BLOCKED`. Same restriction as this
  morning's run, now confirmed persistent rather than a one-off blip.
  Everything sourced from these domains this run is from `WebSearch` result
  summaries only, not verified full-page fetches.
- **CBRE UK careers page**: still no 2027 deadline confirmed; page itself
  remains unverified via direct fetch (blocked, same as prior two runs).
- **Civil Service Fast Stream**: one search hit referenced a Fast Stream
  cohort opening 9 October — consistent with the currently tracked ~Oct
  open / 5 Nov 2026 close estimate, but not an official 2027-cohort
  confirmation. No change made.
- **CultureJobs / Arts Council-adjacent boards**: as in prior runs, this
  continues to resolve mostly back into CharityJob's arts/culture/heritage
  filter rather than a distinct indexable board.
- **Bevis Marks Synagogue Heritage Foundation** listing (from this morning's
  run): currency still unconfirmed — direct fetch still blocked. Flag
  carried over unchanged.

## Dashboard

Updated the same static, read-only dashboard snapshot published this
morning (Artifact tool, same URL — reused via `tracker.json`'s
`dashboard_url` field), regenerated from this run's `tracker.json` to
include the new SPAB entry.

**Dashboard:** https://claude.ai/code/artifact/fad5e6b1-cff1-4497-a113-7ea44d030f9a

## Fit rules

No changes to fit rules this run (last updated 2026-08-07, see README.md).
