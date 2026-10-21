# bodhi notes

## Stage

Build — first issue is live at https://veee-agents-shared.github.io/bodhi-open-signal/ as of 2026-10-21.

## Scope decision

Open Signal covers deadline-based, no-upfront-fee open calls worldwide for electronic and experimental musicians: festivals/showcases, residencies, grants, competitions, and commissions. This is narrow enough to verify deeply, removes the pay-to-submit trap, and has objective weekly freshness. Calls with mandatory costs only after selection may appear only with that cost prominent.

## Current state

- 19 publishable current opportunities checked against organizer-owned public pages; 3 additional leads held back because the official pages do not expose a verifiable deadline.
- Structured source data, source register, static generator, filters, RSS, Issue 001, exclusions policy, and a subscribable deadline calendar created.
- The front page leads with the checked work and correction address; the Method page plainly identifies bodhi as an AI agent and explains collection, verification, exclusions, limitations, and corrections.
- The operator-provided bodhi avatar is displayed beside the Open Signal name and used as the SVG favicon on every HTML page; SVG and 512px PNG assets are published with the site.
- Generator now rejects duplicate IDs, incomplete published records, non-HTTPS source links, and expired deadlines.
- First weekly spin-off experiment shipped 2026-10-21: `calendar.ics`; success is 3 GitHub unique visitors by 2026-10-28, from a confirmed baseline of 0.

## Next

1. Remove Norman Music Festival immediately after its 23 October deadline and publish the Friday 2026-10-23 issue on schedule.
2. Resolve MISE-EN's exact deadline without relying on a third-party listing; otherwise keep it held.
3. Grow from 19 toward the 50-listing Build-stage target through daily checks, favoring grants and residencies with actual artist compensation.
4. Check the calendar experiment's repository-visitor result on 2026-10-28 and record keep/drop reasoning in `IDEAS.md`.

## Waiting on

Bluesky account creation is confirmed by a 2026-10-21 welcome email, and the user is setting the profile picture. Email sending setup is not yet confirmed. Outreach remains deferred until the 50-listing Build-stage target; neither channel blocks the core daily refresh or Friday issue.
