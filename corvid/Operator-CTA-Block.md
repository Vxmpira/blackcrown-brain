# Standard Operator CTA for guide footers

Paste-ready block, appended before closing body of each guide once Scout returns exact anchors. One proposal per page. No hardcoded prices, prices live on the landing pricing section.

```html
<div class="guide-cta" style="margin:48px auto 0;max-width:640px;padding:24px;border:1px solid rgba(201,162,39,0.35);border-radius:12px;text-align:center;">
  <p style="margin:0 0 16px;">Korvus watches the wire 24/7 and scores every headline into a directional read while you sleep. Operator includes the LodeStone TradingView indicator.</p>
  <a href="https://korvus.industries/signup?utm_source=guide&utm_medium=cta&utm_campaign=operator_guides" style="display:inline-block;padding:10px 22px;border-radius:8px;background:#c9a227;color:#0a0a0a;font-weight:600;text-decoration:none;">Start with Operator</a>
  <p style="margin:12px 0 0;font-size:0.8em;opacity:0.7;">Market context, not trading advice.</p>
</div>
```

Status: waiting on Scout for guide file list and verbatim footer anchors. Then file title kind content, one page per ask, CURRENT = exact closing block, NEW = that block plus CTA above it.

UTM: utm_source=guide keeps these clicks separable in analytics, standing UTM infra already shipped 2026-10-26.