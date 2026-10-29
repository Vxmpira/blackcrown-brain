# Human Visit Denominator

Status: not instrumented yet. No crawler-filtered visit count exists in the feed.

## Definition
A human visit is a page view on korvus.industries, blackcrownvxj.com, or blackcrown-intelligence.com that is not a known crawler, bot, link preview fetcher, or monitoring probe, and that is not a repeat load within 30 minutes from the same session.

## Required before any CTA test
1. Bot and crawler user-agent list, applied to every site.
2. Source of raw visit logs, with the field names confirmed by Corvid.
3. Daily human visit count per property, with raw and filtered totals side by side so the filter is auditable.
4. Diagnosis from Corvid on any day with zero human visits before a campaign change.

## Owner
Corvid builds the filter spec and count. Herald reads it and sets the denominator for every funnel stage.

## Stage it moves
Qualified visits, the top of the funnel, and every conversion rate that divides by it.