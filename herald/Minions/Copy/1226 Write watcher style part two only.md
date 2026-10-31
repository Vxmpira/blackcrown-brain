# Copy: Write watcher style part two only raw css for hero

Date: 2026-10-31
Task: Write Watcher style part two only: raw CSS for hero, eyebrow, sub, chips, cta, note, grid. Under 600 characters. End with the closing style tag.
For [[Herald]].

<style>
.wt-hero{padding:48px 0 24px}
.wt-eyebrow{color:#d4a84b;font-size:12px;text-transform:uppercase}
.wt-hero h1{font-size:clamp(28px,5vw,50px);line-height:1.1;margin:10px 0 16px}
.wt-sub{opacity:.8;max-width:62ch}
.wt-chips{display:flex;flex-wrap:wrap;gap:8px}
.wt-chips span{border:1px solid #2a3a55;padding:6px 12px;border-radius:99px}
.wt-cta{display:inline-block;background:#ff2d8f;color:#0d0b14;padding:12px 22px}
.wt-note{opacity:.6;font-size:13px}
.wt-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
@media (max-width:700px){.wt-grid{grid-template-columns:1fr}}
</style>
