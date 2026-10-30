# Copy: Write the watcher page style block as one complete style

Date: 2026-10-30
Task: Write the Watcher page style block as one complete style element, under 40 lines, no script, closed with the closing style tag. Return raw CSS inside style tags
For [[Herald]].

<style>
:root{--ix-pink:#ff2d8f;--ix-ink:#e9e6f0;--ix-mute:#9b95ab;--ix-line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;background:#0b0a12;color:var(--ix-ink);font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(900px 600px at 15% -10%,rgba(255,45,143,.22),transparent 60%),radial-gradient(800px 560px at 95% 10%,rgba(120,80,255,.16),transparent 60%),radial-gradient(700px 500px at 50% 110%,rgba(255,45,143,.12),transparent 60%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px;box-shadow:inset 0 0 180px 60px rgba(0,0,0,.55)}
.ix-container{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
.ix-head{display:flex;align-items:center;justify-content:space-between;gap:16px;padding:20px 0;border-bottom:1px solid var(--ix-line)}
.ix-hero{padding:clamp(48px,9vw,110px) 0 clamp(32px,6vw,64px)}
.ix-hero h1{font-size:clamp(2rem,5.5vw,3.6rem);line-height:1.1;margin:0 0 .5em;letter-spacing:-.02em}
.ix-accent{color:var(--ix-pink)}
.ix-hero p{max-width:68ch;color:var(--ix-mute);font-size:clamp(1rem,1.6vw,1.125rem)}
.ix-btn{display:inline-block;padding:12px 22px;border-radius:8px;background:var(--ix-pink);color:#0b0a12;font-weight:700;text-decoration:none;box-shadow:0 0 24px rgba(255,45,143,.35)}
.ix-btn:hover{filter:brightness(1.08)}
.ix-chips{display:flex;flex-wrap:wrap;gap:8px}
.ix-chip{padding:6px 12px;border:1px solid rgba(255,45,143,.45);border-radius:999px;font-size:.85rem;color:var(--ix-ink);background:rgba(255,45,143,.07)}
.ix-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.ix-panel{border:1px solid var(--ix-line);border-radius:14px;padding:clamp(16px,3vw,24px);background:rgba(255,255,255,.03);overflow-x:auto}
.ix-panel table{width:100%;border-collapse:collapse}
@media (max-width:699px){.ix-head{flex-direction:column;align-items:flex-start}.ix-grid{grid-template-columns:1fr}}
</style>
