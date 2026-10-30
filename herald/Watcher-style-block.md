# Watcher style block

Character count: about 387, under the 400 cap.

```
<style>
body{margin:0;background:#07080d;color:#eef0f6;font:16px system-ui}
body::before{content:'';position:fixed;inset:0;z-index:-1;background:radial-gradient(50vw 40vh at 10% 0,rgba(255,45,143,.16),transparent)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1{font-size:clamp(28px,5vw,52px)}
@media(max-width:699px){.grid{grid-template-columns:1fr}}
</style>
```

Open items: the full house backdrop (faint 56px grid at 1.5 percent white and edge vignette) is cut for length and must be restored in the assembled page. Verify this block against the Watcher page before assembly. Closing style tag verified in this block only.