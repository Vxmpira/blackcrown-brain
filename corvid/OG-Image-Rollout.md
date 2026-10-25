# OG Image Rollout

Status: waiting on asset build (Regent task) and scout path confirmation.

## Ready-to-file proposal, fill in PATH

kind: meta, one proposal per brand site html page, CURRENT: none per head tag rules.

NEW template:

```
<meta property="og:image" content="https://blackcrownvxj.com/PATH">
<meta property="og:image:width" content="1200">
<meta property="og:image:height" content="630">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:image" content="https://blackcrownvxj.com/PATH">
```

## Checklist
- [ ] Scout confirms exact asset path and dimensions
- [ ] Verify dimensions, swap width and height values if not 1200x630
- [ ] File meta proposals for all brand site pages, Regent merges into head
- [ ] Product domains (korvus.industries, blackcrown-intelligence.com) need their own assets, out of scope here

## Notes
Head tag rule: CURRENT none, NEW tags only, Regent merges and dedupes. Do not guess the path, a broken og:image is worse than none.