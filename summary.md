# Weekly summary — week of 2026-08-24

## New postings found

None added this run. Track 1 and Track 2 sources this week largely resurfaced
postings already tracked from prior weeks (Turner & Townsend, AtkinsRéalis,
CBRE, Frankham, the various RICS Recruit agency listings, Faithful+Gould,
Hackney, Royal Parks, HCUK). Two candidates were considered and excluded —
see "Excluded this run" below.

## Deadline / status changes on existing entries

**Deadlines confirmed and updated:**

- **Graduate Building Surveyor - London — Turner Property Recruitment
  (e-20260807-03).** Closing date confirmed as **4 Sep 2026** via search
  summary (still open). Deadline field updated from blank to 2026-09-04.
- **Graduate Building Surveyor - London — EC Property Recruitment
  (e-20260808-03): deadline confirmed and now passed, moved to
  deprioritised.** Closing date confirmed as 23 Aug 2026 — one day before
  this run, so no longer actionable. Deadline field updated for the record.
- **Building Surveyor - Heritage Building — London Borough of Hackney
  (e-20260817-03): moved to deprioritised.** Salary confirmed via search
  summary as £63,816–£64,938, explicitly described as a "Chartered Surveyor
  level" post, closing 1 Sep 2026. A chartered-level salary band effectively
  implies an already-completed RICS qualification — matches the
  completed-qualification hard-exclude despite no explicit years figure
  stated, same pattern as the existing HCUK and Royal Parks Senior Surveyor
  exclusions. Genuinely strong subject-matter fit, so left in the tracker
  as deprioritised rather than deleted — re-check if Hackney opens a more
  junior/assistant-level heritage role.
- **SPAB Learning Programmes Manager (e-20260808-08): moved to
  deprioritised.** Deadline (9am, 19 Aug 2026) confirmed via search summary
  and has now passed — round 1 interviews were scheduled for 8 Sep 2026 at
  SPAB HQ, implying the window has closed. If Hafsa already applied before
  the deadline, her status should be updated manually; this run found no
  evidence either way.

**Reconfirmed, no change:** Turner & Townsend, AtkinsRéalis, CBRE, Frankham,
Fast Stream, Brandon James (both existing London listings), Turner Property
Recruitment - London, Faithful+Gould (both listings), Royal Parks Boundary
Wall Surveyor (salary/contract type reconfirmed, deadline still unconfirmed),
HCUK Historic Building Surveyor.

## Excluded this run

- **Boundary Wall Surveyor — The Royal Parks (e-20260817-04): flag stands,
  not deprioritised.** Nothing new confirms or rules out the start-date
  concern raised last week (a 2-year FTC starting now may not accommodate an
  Aug/Sept 2027 start) — deadline still unconfirmed, so left flagged rather
  than dropped per the flag-don't-drop rule.
- **Graduate Building Surveyors - Full Training & APC Support — Latymer
  Search** (ricsrecruit.com job 255706). Closing date 9 Aug 2026 — already
  passed by the time this run found it. Not added; would have been a
  reasonable Track 1 fit (full training + APC support, London/home counties)
  otherwise.
- **Brandon James "Graduate Building Surveyor" (job ref 250611).** A fifth
  RICS Recruit listing from Brandon James, in addition to the four already
  tracked (253194, 253362, 249356, 252475). Same generic template ad —
  almost certainly the same standing vacancy reposted under yet another job
  ref, a known agency pattern. Not added as a separate row to avoid further
  duplicate clutter; noted on the existing e-20260808-01 entry instead.

## Source notes / parsing issues

- **Network egress policy**: direct `WebFetch` to `ricsrecruit.com`,
  `charityjob.co.uk`, `careers.atkinsrealis.com`, `careers.fgould.com`,
  `careers.atkinsglobal.com`, `turnerandtownsend.com`, and
  `civil-service-careers.gov.uk` all returned `EGRESS_BLOCKED` again this
  run — persistent across every run so far. Everything from these domains is
  sourced from `WebSearch` result summaries only, not verified full-page
  fetches, including this week's deadline confirmations above.
- **CultureJobs / Arts Council-adjacent boards**: as in prior runs, this
  continues to resolve mostly back into CharityJob's arts/culture/heritage
  filter and general job aggregators rather than a distinct indexable board.
  No new building-focused (as opposed to community/events) Track 2 postings
  surfaced there this week.
- **CharityJob** searches for heritage building surveyor / historic building
  conservation officer terms mostly surfaced generic "heritage jobs" and
  "conservation jobs" category pages rather than fresh individual postings
  beyond what's already tracked or previously excluded (e.g. Royal Parks
  Conservation Officer — wildlife/biodiversity conservation, not
  building-fabric, so out of scope for Track 2).

## Dashboard

Regenerated the static, read-only dashboard from this run's `tracker.json`
(34 entries, no new entries, 4 status/deadline changes) and republished to
the same URL via `tracker.json`'s `dashboard_url` field.

**Dashboard:** https://claude.ai/code/artifact/fad5e6b1-cff1-4497-a113-7ea44d030f9a

## Fit rules

No changes to fit rules this run (last updated 2026-08-08, see README.md).
