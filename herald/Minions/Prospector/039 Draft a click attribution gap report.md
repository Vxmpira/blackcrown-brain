# Prospector: Draft a click attribution gap report with exact required fields

Date: 2026-10-27
Task: Draft a click attribution gap report with exact required fields
For [[Herald]].

# Click Attribution Gap Report

**Requested by:** Herald
**Rung moved:** First paying customer (Korvus signups are the 50-signup quota path)
**Status:** Diagnosis only. Nothing filed.

## Summary

Seven days produced 2 tracked clicks and no way to say which post produced them. The UTM tagging on outbound Korvus links shipped 2026-10-26 and is standing infrastructure, so the tags exist. The gap is that nothing records a click as its own row, and nothing records which post carried which tag. Without both sides, the 2 clicks cannot be traced to a post, and the signup quota cannot be attributed to a channel.

## Current state

| Source | Exists | Usable for attribution |
|---|---|---|
| UTM params on outbound Korvus links | Yes (since 2026-10-26) | Yes, if the value encodes the post |
| Click-level rows | No | Not instrumented yet |
| Post log (what was published, where, when, with which link) | No | Not instrumented yet |
| Signup-to-UTM carry | Unverified | Not instrumented yet |

## Required fields

**1. Post log (one row per published post)**
- `post_id`: unique, stable identifier (for example `yt-2026-11-03-a`)
- `platform`: youtube, discord, or other
- `published_at`: UTC timestamp
- `desk`: who produced it (Bard, Herald, or owner-manual)
- `destination_url`: the exact tagged link used
- `utm_source`, `utm_medium`, `utm_campaign`, `utm_content`: copied from the tagged link
- `creative_ref`: Bard creative ID or Eclipse-X channel, where applicable

**2. Click record (one row per click)**
- `click_at`: UTC timestamp
- `utm_source`, `utm_medium`, `utm_campaign`, `utm_content`: as received
- `landing_path`: the Korvus route hit (expected: `/`, `/lodestone`, `/signup`)
- `referrer`: where the click came from, if the browser sent it
- `session_key`: a non-personal hash, so repeat visits can be deduplicated

**3. Conversion record (one row per signup or upgrade)**
- `signup_at`: UTC timestamp
- `utm_*` values carried into the account, if the signup flow stores them
- `tier`: Observer or Operator
- Billing data stays with the owner. Only the tier and timestamp are needed here.

## Joins

- **Click to post:** `click.utm_campaign + click.utm_content` matched to `post.utm_campaign + post.utm_content`. The `utm_content` value must be unique per post for this join to be exact. If two posts share a value, the join returns a set, not a row.
- **Post to creative:** `post.creative_ref` to Bard's creative record, for the hook and format analysis.
- **Click to conversion:** `session_key` if the same session reaches `/signup`, otherwise a time-window match (for example, 30 minutes) and flagged as probable, not confirmed.
- **Conversion to revenue:** owner-side Stripe data, joined on `tier` and `signup_at` only. Agents do not touch billing.

## Cheapest capture path (no new tooling)

1. **Enforce `utm_content` = post_id on every outbound link going forward.** This costs nothing. It turns the existing tag into the join key.
2. **Keep the post log as a plain table in the vault**, appended by whichever desk publishes. One row per post, the fields above. This is a document, not a service.
3. **Check the existing Flask access logs for query strings.** If the server already retains request lines with `utm_*` parameters, click rows can be derived from logs with no code change. This is unverified. Confirm retention before relying on it.
4. **Check whether `/signup` already stores any `utm_*` values.** If it does, conversion attribution is free. If not, that is the first real gap.
5. **Recurring report:** before registering anything, check SERVER JOBS in the feed. If an attribution job already exists, extend it. Do not register a duplicate.

## What is not instrumented yet

- Click-level rows of any kind
- A post log
- Signup-side UTM capture (unverified)
- Per-platform reach, which is needed to convert clicks into a rate

Until these exist, report the 2 clicks as "2 clicks, post attribution not instrumented yet."

## Proposed next moves

1. **Herald (desk-level, no approval needed):** start the post log today and require `utm_content = post_id` on every link. Log the first 7 days of posts retroactively where possible.
2. **Ask for Regent review:** verify whether `/signup` stores `utm_*` values, and whether the access log keeps query strings. This is a read-only check, so it goes as a diagnosis task, not a code change.
3. **Only if step 2 shows a gap:** file a proposal for the smallest change that closes it. Any change to the Korvus app goes through Regent and the owner's green light in #boardroom, and must state exactly what it triggers.

Revenue note: until the first two steps are done, the 50-signup quota cannot be split by channel. The fastest path to knowing which post works is step 1, and it costs nothing.
