# og:image site-wide rollout

Status: waiting on Regent to build the approved og:image asset. Scout dispatched to confirm if it exists.

## Ready-to-file proposal, fill ASSET_URL then file

kind: meta, one proposal covering all brand site html pages.

CURRENT: none
NEW (per head-tag rule, tags only, Regent merges):
```
<meta property="og:image" content="ASSET_URL">
<meta property="og:image:width" content="1200">
<meta property="og:image:height" content="630">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:image" content="ASSET_URL">
```

Pages to cover: index.html, korvus.html, collective.html, plus any other live brand pages found during the repo path task.

Notes:
- Confirm actual dimensions from scout before filing, do not assume 1200x630.
- Product domains (korvus.industries, blackcrown-intelligence.com) may need their own og images later, out of scope for this task.
- Do not file until asset URL is confirmed live.