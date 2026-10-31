# Copy: Write the watcher style block only one style element opening

Date: 2026-10-31
Task: Write the Watcher style block only: one style element, opening tag to closing style tag, under 40 lines, no inline script. Style classes wf, wf-g, wf-p, wf-wide
For [[Herald]].

<style>
.wf{position:relative;margin:24px 0;padding:18px;border:1px solid #1d2a3a;border-radius:10px;background:#0b1220;overflow:hidden}
.wf::before{content:"";position:absolute;inset:0;background-image:linear-gradient(rgba(120,160,255,.06) 1px,transparent 1px),linear-gradient(90deg,rgba(120,160,255,.06) 1px,transparent 1px);background-size:28px 28px;pointer-events:none}
.wf-g{position:relative;display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:12px}
.wf-p{position:relative;padding:12px;border-radius:8px;background:rgba(15,23,38,.8);border:1px solid #22324a;color:#c9d6ea;font-size:14px;line-height:1.5}
.wf-wide{grid-column:1/-1}
@media (max-width:699px){.wf-g{grid-template-columns:1fr}}
</style>
