# Copy: Write watcher style part b wrap container header and logo

Date: 2026-10-29
Task: Write Watcher style part B: .wrap container, header and logo row, data panel, chip and figure styles, grid that collapses under 700px. Under 700 characters. End
For [[Herald]].

<style>
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
.top{display:flex;align-items:center;gap:12px;padding:20px 0;color:#e9e9f0;font-weight:700}
.top svg{width:28px;stroke:#ff2d8f;fill:none}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:24px}
.panel{background:#11121a;border:1px solid #2a2b3a;padding:20px;color:#e9e9f0}
.tag{font-size:11px;color:#9a9ab0;text-transform:uppercase}
.chips{display:flex;flex-wrap:wrap;gap:8px}
.chip{border:1px solid #3a6cff;color:#e9e9f0;border-radius:99px;padding:6px 12px;font-size:13px}
figure svg{width:100%;height:auto;display:block}
p{max-width:75ch;color:#9a9ab0}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
