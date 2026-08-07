# Grad Scheme & Placement Search Automation

Keeps `tracker.json` up to date with new/changed graduate scheme, placement, and
entry-level openings relevant to a heritage/historic building surveying career.
Runs automatically every Monday morning via a Claude Code scheduled cloud agent —
no separate script, no API key to manage.

## How it runs

This is **not** a standalone script + cron job. It's a scheduled Claude Code
agent (set up with the `schedule` skill) that fires weekly and does the fetching,
extraction, and filtering itself using its own web tools and judgement — the
same way Claude Code would if you asked it to do this search by hand.

Each run:

1. Reads `tracker.json` for the current state.
2. Checks every source below for new postings or deadline changes.
3. Applies the fit rules (below) before adding anything.
4. Dedupes against existing entries by `employer` + `name` — re-runs never
   create duplicate rows.
5. Updates `tracker.json` (new entries default to `status: "not_started"`) and
   rewrites `summary.md` with what changed since the last run.
6. Creates a **Gmail draft** (not a sent email) addressed to you with the
   summary, so nothing goes out until you review and hit send yourself.

Treat the weekly output as a shortlist to skim, not an auto-apply pipeline —
see Known limitations below.

## Data schema (`tracker.json`)

```json
{
  "id": "string, unique",
  "name": "string — scheme or role title",
  "employer": "string",
  "track": "1 | 2",
  "status": "not_started | researching | applied | interview | offer | rejected | deprioritised",
  "deadline": "YYYY-MM-DD or empty string if rolling",
  "link": "string, URL",
  "notes": "string — fit reasoning, cohort dates, anything relevant"
}
```

Seeded from the existing `grad_scheme_tracker.html` board on first run.

## Tracks & fit rules

**Track 1 — Building Surveying.** Assistant Building Surveyor, graduate/trainee
surveying schemes, roles offering APC support. Radar employers: Turner &
Townsend, AtkinsRéalis, CBRE, Frankham.

**Track 2 — Heritage & Community Engagement.** Heritage Coordinator, Visitor
Experience Coordinator, Community Engagement Coordinator, Events Coordinator,
Programme Administrator, London, £28k+ FTE (part-time pro-rata flagged, not
excluded). Civil Service Fast Stream (heritage-adjacent, e.g. DCMS) tracked
here too.

**Hard excludes (both tracks):**
- Requires 5+ years' experience
- Animal care roles
- Fundraising-heavy roles
- Commission-only "brand ambassador" / street marketing roles dressed up as coordinator titles
- Pure QS-focused roles with no building surveying pathway (e.g. Wates, WPS)
- New-build/investment-only development schemes with no heritage or surveying-practice angle (e.g. Watkin Jones)
- Requires an already-completed RICS-accredited degree, with no part-qualified/currently-studying route (Hafsa is mid part-time MSc Building Surveying, Kingston University, to Aug 2027 — added 2026-08-07)
- Immediate full-time start incompatible with an ongoing part-time MSc (added 2026-08-07)
- Non-London / non-Kingston-University-commutable location for immediate-start Track 1 roles (added 2026-08-07). Exception: 2027-cohort graduate schemes (e.g. Turner & Townsend, Fast Stream) are fine regardless of location detail, since they start after the MSc finishes.

## Sources checked

**Track 1**
- Turner & Townsend early careers / graduate programme page
- AtkinsRéalis early careers page
- CBRE UK graduate programme page
- Frankham careers page
- RICS Recruit (ricsrecruit.com) — building surveying, graduate/trainee level

**Track 2**
- CharityJob (charityjob.co.uk) — heritage coordinator, community engagement
  coordinator, visitor experience coordinator, events coordinator, London
- CultureJobs / Arts Council-adjacent boards
- Civil Service Fast Stream official page — application window/deadline only

## Known limitations

- Career pages change layout without notice — if a source stops yielding
  results, that's a sign the page structure shifted, not that postings dried up.
- Some listings may be stale (closed roles still shown) or misclassified —
  spot-check before applying.
- Weekly cadence and public listing pages only, in line with typical site ToS;
  this doesn't log in anywhere or scrape behind auth.

## Running it manually

You don't need to wait for Monday — just ask Claude Code (in this project
folder) to run the same weekly check, e.g. "run this week's grad scheme
search now." To change the schedule or pause it, ask Claude to update or
remove the scheduled task.
