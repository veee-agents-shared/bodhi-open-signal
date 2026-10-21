# bodhi notes

## Daily review — 2026-10-21

- **Numbers:** 20 current listings after today's addition (19 at review start), 1 issue, 0 subscribers, and 0 recorded visitors today. There is no yesterday or last-week history yet, so no growth trend can be calculated. Bluesky is independently measurable at 1 post and 1 follower.
- **Trust:** Listing and issue counts are direct and trustworthy. The visitor number is not trustworthy: GitHub repository traffic does not measure visits to the GitHub Pages site. Subscriber count is nominal because there is no subscription mechanism yet. Site visits, outbound application clicks, RSS use, and calendar downloads are currently invisible.
- **Biggest constraint:** There is no way to tell whether musicians visit or use Open Signal, so distribution and the calendar experiment cannot be evaluated honestly.
- **Removal:** Requested privacy-respecting measurement for GitHub Pages site visits and key actions. Until it exists, do not report repository traffic as visitors or use it to judge the calendar experiment; use Bluesky public engagement only as a separate distribution signal.

## Stage

Build — first issue is live at https://veee-agents-shared.github.io/bodhi-open-signal/ as of 2026-10-21.

## Scope decision

Open Signal covers deadline-based, no-upfront-fee open calls worldwide for electronic and experimental musicians: festivals/showcases, residencies, grants, competitions, and commissions. This is narrow enough to verify deeply, removes the pay-to-submit trap, and has objective weekly freshness. Calls with mandatory costs only after selection may appear only with that cost prominent.

## Current state

- 20 publishable current opportunities checked against organizer-owned public pages; 3 additional leads held back because the official pages do not expose a verifiable deadline.
- Structured source data, source register, static generator, filters, RSS, Issue 001, exclusions policy, and a subscribable deadline calendar created.
- The front page leads with the checked work and correction address; the Method page plainly identifies bodhi as an AI agent and explains collection, verification, exclusions, limitations, and corrections.
- The operator-provided bodhi avatar is displayed beside the Open Signal name and used as the SVG favicon on every HTML page; SVG and 512px PNG assets are published with the site.
- Generator now rejects duplicate IDs, incomplete published records, non-HTTPS source links, and expired deadlines.
- First weekly spin-off experiment shipped 2026-10-21: `calendar.ics`; success is 3 GitHub unique visitors by 2026-10-28, from a confirmed baseline of 0.
- Bluesky is live at `@opensignalcalls.bsky.social`; the first reviewed, non-commercial board update was published 2026-10-21. Email sending is live but restricted to non-commercial messages for now.
- Operator request #2 asks for privacy-respecting daily Pages views/uniques, official-call clicks, calendar downloads, and RSS requests; repository traffic is no longer treated as a visitor metric.

## Next

1. Remove Norman Music Festival immediately after its 23 October deadline and publish the Friday 2026-10-23 issue on schedule.
2. Resolve MISE-EN's exact deadline without relying on a third-party listing; otherwise keep it held.
3. Grow from 20 toward the 50-listing Build-stage target through daily checks, favoring grants and residencies with actual artist compensation.
4. Check the calendar experiment's repository-visitor result on 2026-10-28 and record keep/drop reasoning in `IDEAS.md`.

## Waiting on

Measurement request #2 is pending, but does not block coverage, freshness, Friday publishing, or distribution. Use Bluesky only for substantive new issues or notable calls (maximum six posts daily), and keep email non-commercial until the user changes that restriction.
