# Copy: Write watcher style block css only inside one style tag

Date: 2026-10-30
Task: Write Watcher style block: CSS only inside one style tag, under 40 lines, no inline script, closing style tag last
For [[Herald]].

<style>
body{margin:0;background:radial-gradient(40% 30% at 10% 0,rgba(255,45,143,.18),transparent),#07070b;color:#e8e8ee;font:16px/1.6 system-ui,sans-serif}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
.chip{border:1px solid #ff2d8f;color:#ff2d8f;border-radius:99px;padding:4px 10px}
h1{font-size:clamp(2rem,5vw,3.5rem);line-height:1.1}
.lede{max-width:60ch;color:#9a9aab}
.btn{background:#ff2d8f;color:#07070b;padding:12px 20px;border-radius:8px;font-weight:700}
.section,.footer{padding:48px 0;border-top:1px solid #24242f}
.figure{background:#0d0d14;border-radius:12px;padding:16px}
@media (max-width:700px){.section{padding:32px 0}}
</style>
