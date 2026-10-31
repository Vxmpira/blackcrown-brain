# Copy: Write only the style block for the korvus watcher page

Date: 2026-10-31
Task: Write only the style block for the Korvus Watcher page. One style element, under 40 lines, no script, no em dashes, no emoji. Classes: wt-wrap, wt-top, wt-brand
For [[Herald]].

<style>
:root{--wt-pink:#ff4fa3;--wt-ink:#e9e6ef;--wt-mute:#8b8698;--wt-line:rgba(255,255,255,.06)}
.wt-wrap{position:relative;max-width:1060px;margin:0 auto;padding:clamp(20px,4vw,40px) clamp(16px,3vw,32px);color:var(--wt-ink);
background:radial-gradient(900px 420px at 15% -10%,rgba(255,79,163,.16),transparent 60%),radial-gradient(700px 360px at 95% 0%,rgba(120,90,255,.12),transparent 60%),linear-gradient(var(--wt-line) 1px,transparent 1px) 0 0/44px 44px,linear-gradient(90deg,var(--wt-line) 1px,transparent 1px) 0 0/44px 44px,#0b0a10;
box-shadow:inset 0 0 160px rgba(0,0,0,.6);border:1px solid rgba(255,79,163,.18);border-radius:14px;font-family:ui-monospace,SFMono-Regular,Menlo,Consolas,monospace}
.wt-top{display:flex;align-items:center;justify-content:space-between;gap:16px;flex-wrap:wrap;padding-bottom:16px;margin-bottom:24px;border-bottom:1px solid rgba(255,79,163,.2)}
.wt-brand{display:inline-flex;align-items:center;gap:10px;font-weight:700;letter-spacing:.12em;text-transform:uppercase;font-size:clamp(.8rem,2vw,.95rem);color:var(--wt-ink)}
.wt-brand svg{width:28px;height:28px;fill:var(--wt-pink);filter:drop-shadow(0 0 8px rgba(255,79,163,.55))}
.wt-brand span{color:var(--wt-pink)}
.wt-wrap h1{font-size:clamp(1.6rem,4.5vw,2.6rem);line-height:1.15;margin:0 0 12px;letter-spacing:-.01em}
.wt-wrap p{color:var(--wt-mute);line-height:1.6;max-width:68ch;margin:0 0 16px}
.wt-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-top:24px}
.wt-chip{border:1px solid rgba(255,79,163,.25);background:rgba(255,79,163,.06);border-radius:10px;padding:14px;font-size:.85rem;color:var(--wt-ink)}
.wt-chip b{display:block;color:var(--wt-pink);font-size:.7rem;letter-spacing:.14em;text-transform:uppercase;margin-bottom:6px}
.tablewrap{width:100%;overflow-x:auto}
@media (max-width:700px){.wt-grid{grid-template-columns:1fr}.wt-top{flex-direction:column;align-items:flex-start}}
</style>
