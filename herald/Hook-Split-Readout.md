# Korvus Hook Split Readout

Purpose: split Korvus funnel performance by hook, using the UTM tagging that shipped 2026-10-26.

## Source
Rows grouped by utm_content (hook id) over a 48 hour window. Owner of the rows: Steward traffic log.

## Columns
| Hook | Visits | Clicks to signup | Signups | Signup rate | Operator conversions |

## Rules
- Signup rate = signups divided by visits for that hook. Show the raw counts beside every rate.
- A hook with fewer than 30 visits is marked low sample and is not ruled on.
- Any stage the data does not carry is written as not instrumented yet, never estimated.
- Operator conversions come from billing and are owner-only; until they are passed in, mark them not instrumented yet.

## Verdict rule
Keep a hook only if it beats the median signup rate on at least 30 visits for 48 hours. Cut the bottom hook only after a clean read. File the verdict to Playbook.md.

## Status
Waiting on rows from Steward. Re-run this split on arrival.