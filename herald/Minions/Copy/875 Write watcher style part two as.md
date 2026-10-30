# Copy: Write watcher style part two as raw css under 700

Date: 2026-10-30
Task: Write Watcher style part two as raw CSS, under 700 characters, no style tags, no em dashes.
For [[Herald]].

.ix-container{max-width:1060px;margin:0 auto;padding:0 24px}
.ix-panel{border:1px solid var(--ix-line);border-radius:14px;padding:20px;background:#ffffff06}
.ix-label{text-transform:uppercase;font-size:.75rem;letter-spacing:.14em;color:var(--ix-pink)}
.ix-mock{font-family:monospace;list-style:none;padding:0;line-height:1.9}
.ix-chips{display:flex;flex-wrap:wrap;gap:10px}
.ix-chip{border:1px solid var(--ix-line);padding:6px 12px;border-radius:999px}
.ix-foot{opacity:.6;font-size:.85rem}
@media (max-width:700px){.ix-chips{flex-direction:column}.ix-container{padding:0 16px}}
