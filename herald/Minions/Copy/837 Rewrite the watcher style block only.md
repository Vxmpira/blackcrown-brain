# Copy: Rewrite the watcher style block only under 40 lines no

Date: 2026-10-29
Task: Rewrite the Watcher style block only: under 40 lines, no inline script, end with </style>.
For [[Herald]].

<style>
*{box-sizing:border-box;margin:0;padding:0}
html,body{min-height:100%}
body{
  color:#e7e7ee;
  background-color:#0b0b12;
  background-image:
    radial-gradient(ellipse at 15% 0%, rgba(255,45,143,.16), transparent 55%),
    radial-gradient(ellipse at 90% 10%, rgba(124,58,237,.12), transparent 55%),
    linear-gradient(rgba(255,255,255,.015) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,255,255,.015) 1px, transparent 1px),
    radial-gradient(ellipse at center, transparent 55%, rgba(0,0,0,.55) 100%);
  background-size: auto, auto, 56px 56px, 56px 56px, auto;
  font-family: system-ui, -apple-system, "Segoe UI", Roboto, sans-serif;
  line-height: 1.6;
  -webkit-font-smoothing: antialiased;
}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,40px)}
h1{font-size:clamp(28px,5vw,52px);line-height:1.1;letter-spacing:-.02em;margin:0 0 16px}
h2{font-size:clamp(20px,3vw,28px);line-height:1.2;margin:0 0 12px}
p{max-width:65ch;margin:0 0 14px}
.chips{display:flex;flex-wrap:wrap;gap:10px;width:100%;margin:24px 0}
.chip{border:1px solid rgba(255,255,255,.12);border-radius:999px;padding:6px 14px;font-size:14px;background:rgba(255,255,255,.03)}
.figure{width:100%;border:1px solid rgba(255,255,255,.1);border-radius:14px;background:rgba(10,10,18,.6);padding:clamp(16px,3vw,28px);margin:24px 0}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
.card{border:1px solid rgba(255,255,255,.1);border-radius:12px;padding:18px;background:rgba(255,255,255,.02)}
.muted{color:#a9a9b8;font-size:14px}
a{color:#ff2d8f;text-decoration:none}
a:hover{text-decoration:underline}
.cta{display:inline-block;padding:12px 20px;border-radius:10px;background:#ff2d8f;color:#0b0b12;font-weight:600}
</style>
