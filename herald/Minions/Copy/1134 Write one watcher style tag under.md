# Copy: Write one watcher style tag under 40 lines no duplicates

Date: 2026-10-30
Task: Write one Watcher style tag, under 40 lines, no duplicates
For [[Herald]].

<style>
:root{--text:#e8ecf3;--muted:#8d97a8;--line:rgba(255,255,255,.12);--accent:#7aa2ff}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px;color:var(--text)}
.hero{padding:clamp(40px,8vw,96px) 0 clamp(24px,4vw,48px)}
.hero h1{font-size:clamp(28px,5vw,52px);line-height:1.1;margin:0 0 16px}
.hero p{color:var(--muted);max-width:62ch;font-size:clamp(16px,2vw,18px);line-height:1.6;margin:0}
.panel{border:1px solid var(--line);border-radius:14px;background:rgba(255,255,255,.03);padding:clamp(18px,3vw,28px)}
.panel h2{font-size:clamp(20px,3vw,26px);margin:0 0 10px}
.panel-note{color:var(--muted);font-size:13px;line-height:1.5;margin:14px 0 0;border-top:1px solid var(--line);padding-top:12px}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:16px 0 0;padding:0;list-style:none}
.chip{border:1px solid var(--line);border-radius:999px;padding:6px 12px;font-size:13px;color:var(--muted)}
.cta{display:grid;grid-template-columns:1fr 1fr;gap:16px}
.btn{display:inline-block;text-align:center;padding:12px 18px;border-radius:10px;border:1px solid var(--line);color:var(--text);text-decoration:none;font-weight:600}
.btn:hover{border-color:var(--accent)}
@media (max-width:700px){.cta{grid-template-columns:1fr}}
</style>
