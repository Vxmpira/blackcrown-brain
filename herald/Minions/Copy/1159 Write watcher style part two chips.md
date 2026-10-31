# Copy: Write watcher style part two chips grid panel footer media

Date: 2026-10-30
Task: Write Watcher style part two: chips, grid, panel, footer, media query under 700px, ending with </style>
For [[Herald]].

.chip{display:inline-block;padding:4px 10px;border:1px solid #d6b560;color:#d6b560;border-radius:999px;font-size:13px}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;max-width:1060px;margin:0 auto}
.panel{background:#0f1117;border:1px solid #1d2230;border-radius:10px;padding:20px}
.footer{max-width:1060px;margin:40px auto 0;padding:24px 0;border-top:1px solid #1d2230;color:#8a90a0;font-size:13px;text-align:center}
@media (max-width:699px){.grid{grid-template-columns:1fr}}
</style>
