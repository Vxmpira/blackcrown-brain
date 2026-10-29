# Copy: Write the watcher style block one style element body under

Date: 2026-10-29
Task: Write the Watcher style block: one style element body, under 40 lines, no script, ending with the closing style tag.
For [[Herald]].

<style>
:root{--ix-accent:#ff2d8f;--ix-bg:#07060b;--ix-muted:rgba(255,255,255,.78)}
*{box-sizing:border-box}
body{margin:0;background:var(--ix-bg);color:#f2f2f5;font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.55}
.ix-container{max-width:1060px;margin:0 auto;padding:0 20px}
.ix-hero{position:relative;overflow:hidden;padding:48px 20px;background:radial-gradient(60% 50% at 15% 0%,rgba(255,45,143,.22),transparent 70%),radial-gradient(45% 40% at 90% 100%,rgba(255,45,143,.12),transparent 70%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:auto,auto,56px 56px,56px 56px}
.ix-hero::after{content:"";position:absolute;inset:0;pointer-events:none;background:radial-gradient(120% 90% at 50% 50%,transparent 55%,rgba(0,0,0,.55) 100%)}
.ix-hero>*{position:relative;z-index:1}
.ix-brand{display:flex;align-items:center;gap:8px;font-weight:700;letter-spacing:.14em;text-transform:uppercase;font-size:.85rem;color:var(--ix-accent)}
.ix-title{font-size:clamp(2rem,5vw,3.4rem);max-width:22ch;line-height:1.08;margin:12px 0 16px;font-weight:800}
.ix-sub{max-width:60ch;color:var(--ix-muted);margin:0}
.ix-grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:16px;margin-top:24px}
@media (max-width:700px){.ix-grid{grid-template-columns:1fr}}
.ix-panel{grid-column:1/-1;border:1px solid rgba(255,45,143,.35);border-radius:12px;padding:16px;font-family:ui-monospace,SFMono-Regular,Menlo,Consolas,monospace;font-size:.9rem;background:rgba(255,255,255,.02);overflow-x:auto}
.ix-foot{padding:24px 20px;color:rgba(255,255,255,.55);font-size:.8rem}
</style>
