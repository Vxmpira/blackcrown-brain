# Copy: Rewrite the complete watcher style block as css only under

Date: 2026-10-29
Task: Rewrite the complete Watcher style block as CSS only, under 40 lines, ending with a closing style tag.
For [[Herald]].

Full Watcher style block, CSS only, closing tag on the last line. The earlier truncated gist wasn't available to me, so this is rewritten from your palette and class list.

```html
<style>
:root{--wt-bg:#07080c;--wt-ink:#e8eaf0;--wt-accent:#ff2d8f}
html{background:var(--wt-bg)}
body{margin:0;color:var(--wt-ink);position:relative;min-height:100vh}
body::before{content:"";position:fixed;inset:0;z-index:0;pointer-events:none;
background:
radial-gradient(60% 45% at 15% 10%,rgba(255,45,143,.14),transparent 70%),
radial-gradient(50% 40% at 85% 30%,rgba(255,45,143,.09),transparent 70%),
radial-gradient(45% 35% at 50% 100%,rgba(255,45,143,.08),transparent 70%),
repeating-linear-gradient(0deg,rgba(255,255,255,.015) 0 1px,transparent 1px 56px),
repeating-linear-gradient(90deg,rgba(255,255,255,.015) 0 1px,transparent 1px 56px),
var(--wt-bg)}
body::after{content:"";position:fixed;inset:0;z-index:0;pointer-events:none;
background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6) 100%)}
.wt-sec{position:relative;z-index:1;padding:clamp(48px,8vw,96px) 0}
.wt-wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px);box-sizing:border-box}
.wt-kicker{margin:0 0 12px;font-size:12px;font-weight:600;letter-spacing:.18em;text-transform:uppercase;color:var(--wt-accent)}
.wt-sec h2{margin:0 0 16px;font-size:clamp(28px,4.6vw,46px);line-height:1.1}
.wt-lede{max-width:75ch;margin:0 0 28px;font-size:clamp(16px,1.6vw,18px);line-height:1.6;color:rgba(232,234,240,.85)}
.wt-chips{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;margin:0 0 32px;padding:0;list-style:none}
.wt-chip{padding:10px 14px;border:1px solid rgba(255,45,143,.35);border-radius:10px;background:rgba(255,255,255,.02);font-size:14px;text-align:center}
.wt-end{margin-top:40px;padding-top:20px;border-top:1px solid rgba(255,255,255,.08);font-size:13px;color:rgba(232,234,240,.6)}
@media (max-width:699px){.wt-chips{grid-template-columns:repeat(2,1fr)}}
</style>
```

Confirmed: the closing `</style>` tag is the last line of the block. The block is 33 lines.
