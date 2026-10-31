# Copy: Rewrite watcher style part two panels grids figure rules then

Date: 2026-10-31
Task: Rewrite Watcher style part two: panels, grids, figure rules, then the closing style tag, under 600 characters.
For [[Herald]].

.panel{background:#0c0f16;border:1px solid #1d2433;border-radius:10px;padding:clamp(16px,2.5vw,24px);color:#e8ecf3}
.panel h3{margin:0 0 8px;color:#e8ecf3}
.grid{display:grid;gap:16px;grid-template-columns:repeat(2,minmax(0,1fr))}
@media(max-width:700px){.grid{grid-template-columns:1fr}}
figure{margin:0;background:#0c0f16;border:1px solid #1d2433;border-radius:10px;padding:16px}
figure svg{width:100%;height:auto;display:block}
figcaption{color:#8b94a7;font-size:13px;margin-top:10px}
figcaption b{color:#d4a84b;font-weight:600}
</style>
