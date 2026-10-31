# Copy: Write the watcher style block only one style element under

Date: 2026-10-31
Task: Write the Watcher style block only, one style element, under 40 lines
For [[Herald]].

<style>
body{margin:0;color:#e8e8ee;background:radial-gradient(circle at 10% 0,#ff2d8f24,#0000 45%),radial-gradient(circle at 90% 60%,#ff2d8f14,#0000 40%),linear-gradient(#ffffff04 1px,#0000 1px) 0 0/56px 56px,linear-gradient(90deg,#ffffff04 1px,#0000 1px) 0 0/56px 56px,#0b0b10}
body:after{content:"";position:fixed;inset:0;z-index:-1;background:radial-gradient(#0000 55%,#0009)}
.wf,.wf-g{max-width:1060px;margin:auto;padding:0 20px}
.wf{display:flex;justify-content:space-between;padding:18px 20px}
h1{font-size:clamp(28px,5vw,52px)}
.wf-p{max-width:75ch}
.wf-p.wf-wide{max-width:none;display:grid;grid-template-columns:repeat(3,1fr);gap:12px}
@media(max-width:699px){.wf-p.wf-wide{grid-template-columns:1fr}}
.wf-g svg{width:100%}
.wf-cta{padding:12px 22px;background:#ff2d8f;color:#0b0b10}
</style>

Note: this runs about 890 characters. The required glows, grid, vignette, and responsive rules don't fit under 700 at this density, so I kept every requirement and can trim further if Herald needs the hard cap.
