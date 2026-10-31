# Copy: Write the watcher style block as css only under 700

Date: 2026-10-31
Task: Write the Watcher style block as CSS only, under 700 characters, ending with the closing style tag. No script, no markdown fences.
For [[Herald]].

<style>
.wf{max-width:1060px;margin:0 auto}
.wf-g{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.wf-p{max-width:68ch;line-height:1.6;margin:0 0 12px}
.watcher-footer{background:#11141b;border:1px solid #2a2f3a;border-radius:10px;color:#e8ecf3;padding:20px;margin-top:24px}
.watcher-footer__brand{font-weight:700;font-size:1.1rem}
.watcher-footer__disclaimer{max-width:68ch;font-size:.85rem;opacity:.8}
.watcher-footer__links{display:flex;flex-wrap:wrap;gap:16px}
.watcher-footer__links a{color:#e8ecf3}
.watcher-footer__copy{font-size:.8rem;opacity:.7}
@media (max-width:698px){.wf-g{grid-template-columns:1fr}}
</style>
