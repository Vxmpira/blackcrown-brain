# Copy: Rewrite watcher style block as two parts each under 700

Date: 2026-11-13
Task: Rewrite Watcher style block as two parts, each under 700 characters, Part 2 ends with closing style tag
For [[Herald]].

<style>
body{margin:0;min-height:100vh;color:#e8e8f0;font-family:system-ui,sans-serif;background:radial-gradient(55% 40% at 12% 0,rgba(255,45,143,.13),transparent 70%),#0c0d14}
body::before{content:"";position:fixed;inset:0;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(120% 90% at 50% 50%,transparent 55%,rgba(0,0,0,.5))}
/* PART 2 */
.wrap{position:relative;z-index:1;max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
.glow{position:fixed;width:520px;height:520px;border-radius:50%;background:radial-gradient(circle,rgba(255,45,143,.18),transparent 70%);pointer-events:none}
.grid2{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.accent{color:#ff2d8f}
h1{font-size:clamp(28px,5vw,48px);line-height:1.1;margin:0 0 12px}
@media (max-width:700px){.grid2{grid-template-columns:1fr}}
</style>
