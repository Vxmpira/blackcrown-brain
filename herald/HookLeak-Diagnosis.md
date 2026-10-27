# Hook Click Leak Diagnosis

**Metric:** 6.7 percent click leak by hook.
**Status:** Not instrumented per hook in Herald's feed. No hook-level impressions or clicks were supplied, so no hook is blamed yet.

## What is verified
- Operator annual overlays match Projects.md: "Operator annual: 79.99 a year. Save 39.89." (42 chars), "Annual Operator. LodeStone included." (36 chars), "One payment a year. Full Operator access." (41 chars). Saving math checked: 119.88 minus 79.99 equals 39.89.
- Crown hook 3 overlays are LOCKED in Projects.md. Bard's handoff must match them exactly. Any drift gets flagged.

## Leak hypotheses to test (ranked)
1. Promise mismatch: the overlay promises annual savings, but the landing Operator anchor does not show the annual option first. Check the Operator anchor in korvus:korvus_landing.html (pricing is a section, not a file).
2. Hook-to-page mismatch: a hook sells one product while the click lands on a generic section.
3. Segment noise: one weak creative drags the blended rate. Split by utm_content.

## Instrumentation needed
- Per-hook impressions and clicks, keyed by utm_content. UTM tagging on outbound Korvus links has been live since 2026-10-26, so the split is available once creatives carry a distinct utm_content value.
- Confirm the 6.7 percent denominator (clicks over impressions, or clicks over views) before any verdict.

## Next actions
- Bard: send the locked overlays and hook-to-creative map for cross-check.
- Herald: once per-hook clicks arrive, rank hooks by leak and name the weakest one.
- Herald: verify the Operator annual anchor on the landing page against hypothesis 1.

## Verdict
Open. No hook is named as the cause until per-hook clicks exist.