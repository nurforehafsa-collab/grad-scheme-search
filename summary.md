# Weekly summary — week of 2026-09-07

## New postings found

**None added this week.** Sources returned mostly postings already tracked
from prior weeks (Turner & Townsend, AtkinsRéalis, CBRE, Frankham, Brandon
James / Carriera / HD Surveyors / EC Property Recruitment RICS Recruit
listings, Faithful+Gould heritage listings, Fast Stream, Janus Conservation)
with no material change, plus a handful of new-but-excluded finds (see
below).

## Deadline / status changes on existing entries

- **Graduate Building Surveyor - London — Turner Property Recruitment
  (e-20260807-03).** Deadline was 4 Sep 2026 — **now passed** as of this
  run (7 Sep 2026). Status moved from `not_started` to **deprioritised**;
  no longer actionable. Left in tracker for audit trail.

No other deadline or status changes this run.

## Excluded this run

- **Colliers International — London Graduate Building Surveyor (2026
  Intake).** New find, Track 1. Explicitly a **September 2026 start** —
  fails the Aug/Sept 2027 start-date hard exclude outright (this is an
  immediate/current-year cohort, not a 2027 one). Not added. Note: Colliers
  also has a separate "London Building Surveying Graduate Programme"
  listing (job id 2447) with no intake year in the title — undated/rolling
  variant not checked in detail this run; worth a look next week in case it
  targets a later cohort.
- **The Victorian Society — Conservation Adviser.** Track 2, genuinely
  building-conservation-focused (advises on secular Victorian/Edwardian
  buildings), London-based. The only listing found (via Heritage Alliance
  write-up and a cached PDF) carries a **25 November** closing date with no
  year — cross-referencing the job description PDF timestamp, this appears
  to be the 2024 posting, not a live 2026 vacancy. Not added: could not
  confirm this is currently open. Worth rechecking directly on
  victoriansociety.org.uk/tag/job-vacancy/ next week.
- **Church Buildings Officer / Church Buildings Support Officer roles**
  (various dioceses, via CharityJob/Pathways/IHBC). Fails the Track 2
  building-focus rule as it's currently defined in practice at these
  postings — role is DAC/faculty-process advice, permissions administration
  and community/parish support, not hands-on surveying or condition
  assessment of the fabric itself. Not added.
- **IHBC "Jobs etc." Conservation Officer listings** (War Memorials Trust,
  Stratford-on-Avon District Council, one unspecified London posting).
  Local-authority/charity conservation-officer roles are planning- and
  policy-facing (listed building consent casework, DAC-style advice), not
  building-surveying/condition-assessment roles — same pattern as the
  already-deprioritised Fast Stream exclusion. Not added; location and
  seniority also unconfirmed for the London one.
- **Historic England — Architect/Surveyor (fixed-term to 31 Mar 2027).**
  Surfaced again via search but the listing itself now shows as no longer
  available/closed. Not added.

## Source notes / parsing issues

- **Network egress policy**: direct `WebFetch` to `careers.colliers.com`
  returned `EGRESS_BLOCKED` this run (tested directly), consistent with
  every prior run's experience on `ricsrecruit.com`, `turnerandtownsend.com`,
  `careers.atkinsrealis.com`, `cbre.co.uk`, `careers.fgould.com`, and
  `janus-conservation.co.uk`. All detail above and in `tracker.json` is
  sourced from `WebSearch` result summaries only, not verified full-page
  fetches — treat deadlines/start dates sourced this way as indicative,
  not confirmed.
- **CharityJob / CultureJobs / Arts Council-adjacent boards**: as in prior
  runs, searches resolve mostly into generic "heritage jobs" category pages
  and cross-posted aggregator listings (Indeed, LinkedIn, TotalJobs) rather
  than a distinct indexable heritage-building-conservation board. No new
  building-focused (as opposed to community/policy/events) Track 2 postings
  surfaced there this week beyond the excluded items above.
- No page-structure changes noticed on any source this run.

## Dashboard

Regenerated the static, read-only dashboard from this run's `tracker.json`
(35 entries: 0 new, 1 status change — Turner Property Recruitment London
deadline passed) and republished to the same URL via `tracker.json`'s
`dashboard_url` field.

**Dashboard:** https://claude.ai/code/artifact/fad5e6b1-cff1-4497-a113-7ea44d030f9a

## Fit rules

No changes to fit rules this run (last updated 2026-08-08, see README.md).
