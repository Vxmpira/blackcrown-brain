# Copy: Rewrite crown skeptic style block as three parts each under

Date: 2026-11-11
Task: Rewrite Crown skeptic style block as three parts, each under 700 characters, last part ends with closing style tag.
For [[Herald]].

<style>
:root{--bg:#0b0b12;--accent:#ff2d8f;--ink:#f2f2f7;--muted:#9a9aab}
*{box-sizing:border-box}
body{margin:0;color:var(--ink);font:16px/1.6 system-ui,sans-serif;background:radial-gradient(800px 420px at 12% -8%,rgba(255,45,143,.16),transparent 70%),radial-gradient(640px 380px at 92% 8%,rgba(255,45,143,.09),transparent 70%),linear-gradient(rgba(255,255,255,.03) 1px,transparent 1px) 0 0/48px 48px,linear-gradient(90deg,rgba(255,255,255,.03) 1px,transparent 1px) 0 0/48px 48px,radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.55)) fixed,var(--bg)}
/* part 2 */
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1{font-size:clamp(28px,5vw,46px);line-height:1.15;margin:48px 0 16px}
h2{font-size:clamp(20px,3vw,26px);margin:36px 0 12px}
p{max-width:65ch;margin:0 0 16px;color:var(--muted)}
.accent{color:var(--accent)}
.chips{display:flex;flex-wrap:wrap;gap:8px}
.chip{border:1px solid rgba(255,45,143,.4);border-radius:999px;padding:6px 12px;font-size:14px}
/* part 3 */
.tablewrap{width:100%;overflow-x:auto;border:1px solid rgba(255,255,255,.08);border-radius:12px;margin:24px 0}
table{width:100%;border-collapse:collapse;font-size:15px}
th,td{padding:10px 14px;text-align:left;border-bottom:1px solid rgba(255,255,255,.06)}
th{color:var(--accent);font-weight:600}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
@media (max-width:700px){.grid{grid-template-columns:1fr}.wrap{padding:0 16px}}
</style>
