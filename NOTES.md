# bodhi notes

## Daily review — 2026-10-21

- **Numbers:** 24 current listings after today's additions (19 at review start), 1 issue, 0 subscribers, 2 Bluesky posts, and 1 follower. Valid site measurement began at 18:34 UTC with 0 visitors, 0 pageviews, and 0 official-call clicks; one calendar and two RSS fetches were setup tests and are excluded from demand. There is no yesterday or last-week history yet, so no growth trend can be calculated.
- **Trust:** Listing and issue counts are direct and trustworthy. The original visitor number was not trustworthy because GitHub repository traffic cannot see Pages visits; subscriber count remains nominal because there is no subscription mechanism yet. Operator request #2 delivered privacy-safe Pages measurement today, and integration is shipping now with no historical backfill.
- **Biggest constraint:** Growth was blind; after this measurement release, the next constraint is limited discovery while the board is still only 24/50 listings.
- **Removal:** Added aggregate measurement for real Pages visits, pageviews, named official-call clicks, outbound links, RSS fetches, and calendar fetches. It uses no cookies or fingerprinting, honors DNT/GPC, and exposes only daily totals. Repository traffic is permanently rejected as a visitor proxy.

## Stage

Build — first issue is live at https://veee-agents-shared.github.io/bodhi-open-signal/ as of 2026-10-21.

## Scope decision

Open Signal covers deadline-based, no-upfront-fee open calls worldwide for electronic and experimental musicians: festivals/showcases, residencies, grants, competitions, and commissions. This is narrow enough to verify deeply, removes the pay-to-submit trap, and has objective weekly freshness. Calls with mandatory costs only after selection may appear only with that cost prominent.

## Current state

- 24 publishable current opportunities checked against organizer-owned public pages; 3 additional leads held back because the official pages do not expose a verifiable deadline.
- Structured source data, source register, static generator, filters, RSS, Issue 001, exclusions policy, and a subscribable deadline calendar created.
- The front page leads with the checked work and correction address; the Method page plainly identifies bodhi as an AI agent and explains collection, verification, exclusions, limitations, and corrections.
- The operator-provided bodhi avatar is displayed beside the Open Signal name and used as the SVG favicon on every HTML page; SVG and 512px PNG assets are published with the site.
- Generator now rejects duplicate IDs, incomplete published records, non-HTTPS source links, and expired deadlines.
- First weekly spin-off experiment shipped 2026-10-21: `calendar.ics`; success is 3 real calendar fetchers by 2026-10-28, excluding setup tests.
- Bluesky is live at `@opensignalcalls.bsky.social`; the first reviewed, non-commercial board update was published 2026-10-21. Email sending is live but restricted to non-commercial messages for now.
- A second reviewed Bluesky post alerts Canadian artists to the DCMF residency before its 21 October Yukon-time deadline and plainly flags its unstated stipend/travel support.
- Operator request #2 delivered privacy-respecting daily Pages views/uniques, official-call clicks, calendar downloads, and RSS requests; repository traffic is no longer treated as a visitor metric.
- Privacy-safe site measurement from request #2 is integrated into every generated HTML page; official calls have named click events, and public RSS/calendar subscription links use counted redirects. Counting starts from deployment with no backfill.

## Next

1. Remove Norman Music Festival immediately after its 23 October deadline and publish the Friday 2026-10-23 issue on schedule.
2. Resolve MISE-EN's exact deadline without relying on a third-party listing; otherwise keep it held.
3. Grow from 24 toward the 50-listing Build-stage target through daily checks, favoring grants and residencies with actual artist compensation.
4. Check actual calendar fetches on 2026-10-28 and record keep/drop reasoning in `IDEAS.md`.

## Waiting on

Nothing. Use Bluesky only for substantive new issues or notable calls (maximum six posts daily), and keep email non-commercial until the user changes that restriction.
