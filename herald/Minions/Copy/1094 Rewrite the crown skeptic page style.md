# Copy: Rewrite the crown skeptic page style block only under 40

Date: 2026-10-30
Task: Rewrite the Crown skeptic page style block only, under 40 lines, no inline script, ending with the closing style tag.
For [[Herald]].

<style>
:root{--ink:#e9e6f2;--mute:#9b96ad;--pink:#ff2d8f;--violet:#7b4dff;--line:rgba(255,255,255,.08);--card:#120d1c}
*{box-sizing:border-box}
html,body{margin:0}
body{color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;min-height:100vh;background:radial-gradient(60vw 45vw at 15% 0%,rgba(255,45,143,.22),transparent 60%),radial-gradient(55vw 50vw at 90% 20%,rgba(123,77,255,.20),transparent 62%),radial-gradient(120vw 100vh at 50% 50%,transparent 55%,rgba(0,0,0,.55) 100%),#0d0816}
body:before{content:"";position:fixed;inset:0;pointer-events:none;z-index:0;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px}
.wrap{position:relative;z-index:1;max-width:1060px;margin:0 auto;padding:0 20px}
.hero{padding:clamp(48px,8vw,96px) 0 32px}
.hero h1{font-size:clamp(2rem,1.2rem + 3.6vw,3.6rem);line-height:1.1;margin:.2em 0 .4em;letter-spacing:-.01em}
.eyebrow{font-size:.78rem;letter-spacing:.14em;text-transform:uppercase;color:var(--pink);font-weight:600}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:20px 0 0;padding:0;list-style:none}
.chips span{display:inline-block;border:1px solid var(--line);background:rgba(255,255,255,.03);border-radius:999px;padding:6px 12px;font-size:.85rem;color:var(--mute)}
.grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:20px;margin:32px 0}
.mock{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:18px;box-shadow:0 20px 60px rgba(0,0,0,.35)}
.bar{height:10px;border-radius:6px;background:var(--pink);width:78%;margin:10px 0}
.b2{background:var(--violet);width:56%}
.b3{background:#4a4360;width:34%}
figcaption{font-size:.8rem;color:var(--mute);margin-top:10px}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
