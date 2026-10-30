# Scribe: Write one reusable operator cta html block for the korvus

Date: 2026-10-30
Task: Write one reusable Operator CTA html block for the Korvus guide pages, a self-contained styled section I can paste before each guide's footer. Deliver the compl
For [[Corvid]].

```html
<section class="kx-cta" aria-labelledby="kx-cta-title">
  <style>
    .kx-cta {
      position: relative;
      box-sizing: border-box;
      width: 100%;
      max-width: inherit;
      margin: 48px auto;
      padding: 40px 32px;
      background: #0b0b0e;
      border: 1px solid #ff2d8f;
      border-radius: 14px;
      color: #e9e9ee;
      font-family: system-ui, -apple-system, "Segoe UI", Roboto, sans-serif;
      text-align: left;
      overflow: hidden;
    }
    .kx-cta::before {
      content: "";
      position: absolute;
      inset: 0;
      background:
        radial-gradient(circle at 92% 0%, rgba(255, 45, 143, 0.18), transparent 55%),
        radial-gradient(circle at 0% 100%, rgba(255, 45, 143, 0.08), transparent 50%);
      pointer-events: none;
    }
    .kx-cta > * {
      position: relative;
    }
    .kx-cta-title {
      margin: 0 0 14px;
      font-size: clamp(1.4rem, 2.2vw + 0.6rem, 2rem);
      line-height: 1.2;
      font-weight: 800;
      color: #ffffff;
    }
    .kx-cta-title span {
      color: #ff2d8f;
    }
    .kx-cta-line {
      margin: 0 0 10px;
      font-size: 1rem;
      line-height: 1.6;
      max-width: 62ch;
      color: #c9c9d2;
    }
    .kx-cta-line strong {
      color: #ffffff;
      font-weight: 700;
    }
    .kx-cta-btn {
      display: inline-block;
      margin-top: 22px;
      padding: 14px 26px;
      background: #ff2d8f;
      color: #0b0b0e;
      font-weight: 800;
      font-size: 1rem;
      text-decoration: none;
      border-radius: 10px;
      border: 1px solid #ff2d8f;
      box-shadow: 0 0 22px rgba(255, 45, 143, 0.35);
    }
    .kx-cta-btn:hover,
    .kx-cta-btn:focus-visible {
      background: #ffffff;
      border-color: #ffffff;
      color: #0b0b0e;
    }
    .kx-cta-foot {
      margin: 22px 0 0;
      font-size: 0.8rem;
      line-height: 1.5;
      color: #7d7d8a;
    }
    .kx-cta-motto {
      margin: 18px 0 0;
      padding-top: 14px;
      border-top: 1px solid rgba(255, 255, 255, 0.08);
      font-size: 0.78rem;
      letter-spacing: 0.02em;
      color: #6f6f7c;
    }
    @media (max-width: 700px) {
      .kx-cta {
        margin: 32px auto;
        padding: 28px 20px;
      }
      .kx-cta-btn {
        display: block;
        width: 100%;
        box-sizing: border-box;
        text-align: center;
      }
    }
  </style>

  <h2 class="kx-cta-title" id="kx-cta-title">Your edge <span>while the world sleeps.</span></h2>

  <p class="kx-cta-line"><strong>Korvus Operator:</strong> 79.99 a year, or 9.99 a month. Includes the LodeStone TradingView indicator.</p>
  <p class="kx-cta-line">Market intelligence and education for index futures traders. Not financial advice.</p>

  <a class="kx-cta-btn" href="https://korvus.industries/signup?utm_source=guide&utm_medium=cta&utm_campaign={slug}">Create your Korvus account</a>

  <p class="kx-cta-foot">Trading involves risk. Korvus content is informational and educational only.</p>
  <p class="kx-cta-motto">A crown is not handed down, it is built.</p>
</section>
```

Swap `{slug}` per guide before pasting. Paste the block above each guide's footer. The annual price is listed first, as specified, and the block uses no dollar amounts beyond the two Operator prices.
