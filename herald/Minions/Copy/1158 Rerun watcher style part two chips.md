# Copy: Rerun watcher style part two chips grid panel footer media

Date: 2026-10-30
Task: Rerun Watcher style part two: chips, grid, panel, footer, media query under 700px, then </style>. Plain CSS, no code fences. Output must end with </style>. Unde
For [[Herald]].

.chip{display:inline-flex;align-items:center;gap:6px;padding:5px 11px;border:1px solid rgba(214,181,96,.35);border-radius:999px;background:rgba(214,181,96,.06);color:#e9dcb0;font-size:13px;line-height:1.2;letter-spacing:.02em}
.chip-dot{width:6px;height:6px;border-radius:50%;background:#d6b560;box-shadow:0 0 8px rgba(214,181,96,.6);flex:0 0 auto}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:18px 0}
.grid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:16px;margin:24px 0}
.grid-2{grid-template-columns:repeat(2,minmax(0,1fr))}
.panel{position:relative;padding:20px 22px;border:1px solid rgba(255,255,255,.08);border-radius:14px;background:linear-gradient(180deg,rgba(20,22,30,.92),rgba(12,13,19,.92));box-shadow:0 10px 30px rgba(0,0,0,.35);color:#d9dce6}
.panel h3{margin:0 0 8px;font-size:17px;line-height:1.3;color:#f4efe0}
.panel p{margin:0;font-size:15px;line-height:1.6;color:#aab0bf}
.panel-accent{border-color:rgba(214,181,96,.28)}
.panel-label{display:block;margin-bottom:10px;font-size:11px;letter-spacing:.14em;text-transform:uppercase;color:#d6b560}
.site-footer{margin-top:48px;padding:24px 0 32px;border-top:1px solid rgba(255,255,255,.08);color:#7d8393;font-size:13px;line-height:1.6}
.site-footer-inner{display:flex;flex-wrap:wrap;align-items:center;justify-content:space-between;gap:12px}
.site-footer a{color:#b9bfcd;text-decoration:none;border-bottom:1px solid rgba(185,191,205,.25)}
.site-footer a:hover{color:#f4efe0;border-bottom-color:#d6b560}
.footer-links{display:flex;flex-wrap:wrap;gap:16px}
@media (max-width:700px){.grid,.grid-2{grid-template-columns:1fr;gap:12px}.panel{padding:16px 16px}.site-footer-inner{flex-direction:column;align-items:flex-start}}
</style>
