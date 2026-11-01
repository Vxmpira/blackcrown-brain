# Copy: Write the watcher style block as raw css in one

Date: 2026-11-01
Task: Write the Watcher style block as raw CSS in one style element, 30 lines max, ending with the closing style tag. No markdown fences, no script.
For [[Herald]].

<style>
:root{--accent:#ff2d8f;--base:#0a0a10;--ink:#f2f2f5;--muted:#9a9aa8}
html,body{margin:0;background:var(--base);color:var(--ink)}
body{font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;min-height:100vh}
.bg-glow,.bg-grid,.bg-vignette{position:fixed;inset:0;pointer-events:none;z-index:0}
.bg-glow{background:radial-gradient(60rem 40rem at 15% -10%,rgba(255,45,143,.16),transparent 60%),radial-gradient(50rem 36rem at 95% 20%,rgba(255,45,143,.10),transparent 60%),radial-gradient(40rem 30rem at 40% 110%,rgba(255,45,143,.08),transparent 60%)}
.bg-grid{background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px}
.bg-vignette{background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6) 100%)}
.wrap{position:relative;z-index:1;max-width:1060px;margin:0 auto;padding:0 1.25rem}
.muted{color:var(--muted)}
.accent{color:var(--accent)}
h1{font-size:clamp(1.9rem,5vw,3.2rem);line-height:1.15;margin:0 0 .75rem}
p{max-width:65ch}
@media (max-width:700px){.wrap{padding:0 1rem}}
</style>
