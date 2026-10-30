# Copy: Write the crown skeptic style block under 40 lines ending

Date: 2026-10-30
Task: Write the Crown skeptic style block, under 40 lines, ending with a closing style tag.
For [[Herald]].

<style>
:root{--accent:#ff2d8f;--violet:#7b5cff;--bg:#07070b;--text:#e9e9f0}
html,body{margin:0;background:var(--bg);color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(circle at 15% 10%,rgba(255,45,143,.18),transparent 40%),radial-gradient(circle at 85% 30%,rgba(123,92,255,.16),transparent 42%),radial-gradient(circle at 50% 100%,rgba(255,45,143,.10),transparent 45%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px;box-shadow:inset 0 0 160px rgba(0,0,0,.7)}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
.brand{display:flex;align-items:center;gap:12px;font-weight:700;letter-spacing:.02em}
.brand svg{width:36px;height:36px;flex:none;stroke:var(--accent);fill:none;stroke-width:1.5}
.hero{padding:clamp(48px,10vw,120px) 0 clamp(32px,6vw,72px)}
h1{font-size:clamp(2rem,5.2vw,3.6rem);line-height:1.1;margin:0 0 .5em;font-weight:800}
p,li{max-width:75ch}
p{margin:0 0 1em;color:#c9c9d6}
a{color:var(--accent)}
.proof{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin:32px 0;border:1px solid rgba(255,45,143,.25);border-radius:12px;padding:20px;background:rgba(255,255,255,.02)}
@media (max-width:700px){.proof{grid-template-columns:1fr}}
.cta{display:inline-block;padding:12px 22px;border:1px solid var(--accent);border-radius:999px;color:var(--text);text-decoration:none;box-shadow:0 0 24px rgba(255,45,143,.25)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:16px 0}
.chip{padding:6px 12px;border-radius:999px;border:1px solid rgba(123,92,255,.45);font-size:.85rem;background:rgba(123,92,255,.08)}
</style>
