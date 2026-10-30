# Copy: Write the watcher style block part two panel mock table

Date: 2026-10-30
Task: Write the Watcher style block part two: panel, mock, table wrap and grid rules, then the closing style tag. Under 700 characters, no markdown fences.
For [[Herald]].

.panel{border:1px solid rgba(255,255,255,.15);border-radius:14px;padding:22px;background:rgba(255,255,255,.03)}
.mock{border:1px solid rgba(255,255,255,.15);border-radius:12px;padding:16px}
.tablewrap{width:100%;overflow-x:auto;border:1px solid rgba(255,255,255,.15);border-radius:12px}
.tablewrap table{width:100%;min-width:520px;border-collapse:collapse}
.tablewrap th,.tablewrap td{padding:10px 14px}
.chip{display:inline-block;padding:4px 10px;border-radius:999px;border:1px solid #ff4fa3;color:#ff8fc4}
.chip.b{border-color:#3fa9ff;color:#8fd0ff}
.grid{display:grid;gap:16px;grid-template-columns:repeat(2,minmax(0,1fr))}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
