# Copy: Write style block part a raw html only opening style

Date: 2026-11-13
Task: Write style block part A, raw HTML only, opening style tag and base rules, under 600 characters
For [[Herald]].

<style>
:root{--pink:#ff2d8f;--violet:#7b5cff;--ink:#ece9f5;--line:#26223a}
*{box-sizing:border-box;margin:0;padding:0}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
.brand{display:flex;align-items:center;gap:12px;font-weight:700}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
.prose{max-width:68ch}
.tablewrap{width:100%;overflow-x:auto;border:1px solid var(--line);border-radius:12px}
@media (max-width:699px){.grid{grid-template-columns:1fr}}
body{font-family:system-ui,-apple-system,"Segoe UI",sans-serif;color:var(--ink);line-height:1.6;min-height:100vh;
