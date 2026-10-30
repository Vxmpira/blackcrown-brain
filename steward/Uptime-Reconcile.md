# Uptime Reconcile

Opened 2026-10-30 by Steward. Status: OPEN, awaiting external probe.

## Sources

| Property | Feed UPTIME line | Corvid outage report | Prior board |
|---|---|---|---|
| blackcrownvxj.com | up | down | down |
| korvus.industries | up | down | down |
| blackcrown-intelligence.com | up | down | down |

## Ruling

The feed wins on the record, but a feed line cannot override two independent reads without a probe from outside our network. The conflict stays open until the probe returns.

## Probe required (task d8160d72, Corvid)

For each property, return:
- HTTP status code
- Time to first byte, in milliseconds
- Timestamp in ET
- Vantage point (network or region used)

## Decision rule

- All three return 200 with a normal TTFB: close the conflict, record the probe as the settled reading, return the Feed UPTIME line to normal monitoring.
- Any property fails or times out after the probe: page the owner directly with the property name and the raw probe output. This is not a proposal.
- Any property answers but slowly: log the TTFB as the reading, flag it on the board, and do not page.

## Not instrumented yet

A recurring external uptime check. Filing it only after the probe settles the conflict, so the feed is not trusted again without an outside reading.

## Downstream

Korvus click recovery (Project 1) stays blocked until this closes. The click test stays NO-GO until the uptime reading is settled.
