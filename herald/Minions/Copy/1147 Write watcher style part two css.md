# Copy: Write watcher style part two css after the hero h1

Date: 2026-10-30
Task: Write Watcher style part two: CSS after the hero h1 rule through the closing style tag. Panel, mock, chips, grid, CTA, footer rules. Raw CSS only, no code fence
For [[Herald]].

.panel{background:linear-gradient(180deg,rgba(124,92,255,.08),rgba(10,11,15,0));border:1px solid rgba(200,204,212,.12);border-radius:14px;padding:clamp(18px,3vw,28px);margin:0 0 24px}
.panel h2{font-size:clamp(20px,2.6vw,26px);color:#c8ccd4;margin:0 0 10px}
.panel p{max-width:64ch;line-height:1.6;color:#c8ccd4;opacity:.85;margin:0 0 14px}
.mock{position:relative;background:#0d0f15;border:1px solid rgba(47,212,200,.25);border-radius:12px;padding:16px;overflow:hidden;box-shadow:0 0 40px rgba(255,45,143,.08)}
.mock::before{content:"";position:absolute;inset:0;background-image:linear-gradient(rgba(200,204,212,.04) 1px,transparent 1px),linear-gradient(90deg,rgba(200,204,212,.04) 1px,transparent 1px);background-size:32px 32px;pointer-events:none}
.mock-bar{display:flex;justify-content:space-between;font-size:12px;color:#2fd4c8;letter-spacing:.06em;text-transform:uppercase;margin-bottom:12px;position:relative}
.mock-figure{position:relative;width:100%;height:auto;display:block}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:16px 0 0;padding:0;list-style:none}
.chips li{font-size:13px;color:#c8ccd4;border:1px solid rgba(255,45,143,.45);border-radius:999px;padding:6px 12px;background:rgba(255,45,143,.06)}
.chips li.alt{border-color:rgba(124,92,255,.5);background:rgba(124,92,255,.06)}
.chips li.alt2{border-color:rgba(47,212,200,.5);background:rgba(47,212,200,.06)}
.grid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:16px;margin:0 0 24px}
.grid > .panel{margin:0}
@media (max-width:699px){.grid{grid-template-columns:1fr}}
.cta{display:inline-flex;align-items:center;gap:8px;background:#ff2d8f;color:#0a0b0f;font-weight:700;text-decoration:none;padding:14px 22px;border-radius:10px;box-shadow:0 8px 28px rgba(255,45,143,.25)}
.cta:hover{filter:brightness(1.08)}
.cta-note{font-size:13px;color:#c8ccd4;opacity:.7;margin:10px 0 0}
.site-footer{border-top:1px solid rgba(200,204,212,.1);margin-top:48px;padding:24px 0 36px;font-size:13px;color:#c8ccd4;opacity:.7}
.site-footer a{color:#7c5cff;text-decoration:none}
.site-footer a:hover{color:#2fd4c8}
</style>
