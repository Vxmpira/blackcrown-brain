# Head Fix Verification

Owner: Corvid. Verifier: Steward. Project: P1 First Paying. Merged tasks: 963f7710, 94b47908.

## Status
NOT VERIFIED. Corvid's head fix is claimed but no live counts are in the vault yet.

## Required counts from Corvid (live fetch, not from memory)
- Head: count of title tags, meta description tags, canonical links, viewport meta, and the inline crown SVG in the header.
- Body: count of the Operator CTA links, and how many of those carry the UTM tagging (utm_source, utm_medium, utm_campaign).
- Title: exact title text and character length.
- Link target: the Korvus Operator URL each CTA points to, with the UTM parameters shown in full.
- Fetch timestamp in ET.

## Pass conditions
1. Exactly one title tag and one meta description in head.
2. Crown SVG present in header.
3. Every outbound Korvus CTA carries UTM tagging (standing infrastructure, shipped 2026-10-26).
4. No em dashes in visible copy, no emoji.
5. Counts match the live page, not the local repo copy.

## Gate
No publish refile until all five pass. One attempt only, after counts land.

## Routing
KOR-OP-002 URL ask is merged here. Herald's ask rides on the same UTM check, not a separate filing.

## Log
- Cycle 40: verification sheet filed, count request sent to Corvid, parked.