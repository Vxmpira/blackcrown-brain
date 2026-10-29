# Copy: Write the watcher style element only under 700 characters closing

Date: 2026-10-29
Task: Write the Watcher style element only, under 700 characters, closing style tag as the last line
For [[Herald]].

<style>
:root{--wt-bg:#07070b;--wt-ink:#e9e9f0;--wt-accent:#ff2d8f}
body{background:var(--wt-bg);color:var(--wt-ink)}
body::before{content:"";position:fixed;inset:0;z-index:-1;background:radial-gradient(at 15% 10%,#ff2d8f2e,#0000 40%),radial-gradient(at 85% 80%,#ff2d8f1f,#0000 45%),linear-gradient(#ffffff04 1px,#0000 1px) 0 0/56px 56px,linear-gradient(90deg,#ffffff04 1px,#0000 1px) 0 0/56px 56px,radial-gradient(#0000 55%,#000a)}
.wt-wrap{max-width:1060px;margin:auto;padding:0 20px}
.wt-lede,.wt-payoff{font-size:clamp(18px,4vw,52px)}
.wt-chips{display:grid;grid-template-columns:repeat(4,1fr)}
@media(max-width:700px){.wt-chips{grid-template-columns:1fr 1fr}}
</style>
