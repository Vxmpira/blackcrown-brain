# Copy: Write watcher style block under 40 lines no inline script

Date: 2026-10-31
Task: Write Watcher style block, under 40 lines, no inline script, ending with the closing style tag.
For [[Herald]].

<style>
  .wt-wrap {
    max-width: 1060px;
    margin: 0 auto;
    padding: 0 clamp(16px, 4vw, 40px);
    box-sizing: border-box;
  }
  .wt-brand {
    display: flex;
    align-items: center;
    gap: 12px;
    font-weight: 700;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: #f2f2f5;
    font-size: clamp(13px, 1.4vw, 15px);
  }
  .wt-brand svg {
    width: clamp(28px, 3vw, 36px);
    height: auto;
    flex: 0 0 auto;
  }
  h1 {
    font-size: clamp(28px, 5vw, 56px);
    line-height: 1.1;
    margin: 0.6em 0 0.4em;
    color: #ffffff;
    letter-spacing: -0.01em;
  }
  h2 {
    font-size: clamp(20px, 3vw, 30px);
    line-height: 1.2;
    margin: 1.4em 0 0.5em;
    color: #ffffff;
  }
  h1 span,
  h2 span {
    color: #ff2d8f;
  }
  p, ul {
    max-width: 75ch;
    color: #c9ccd6;
    line-height: 1.6;
    font-size: clamp(15px, 1.6vw, 17px);
  }
  ul {
    padding-left: 1.2em;
  }
  li {
    margin: 0.35em 0;
  }
  .wt-tag {
    display: inline-block;
    font-size: 11px;
    font-weight: 600;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: #ff2d8f;
    border: 1px solid rgba(255, 45, 143, 0.5);
    border-radius: 999px;
    padding: 4px 10px;
    margin-bottom: 10px;
  }
  .wt-panel {
    width: 100%;
    box-sizing: border-box;
    background: rgba(12, 14, 22, 0.78);
    border: 1px solid rgba(255, 45, 143, 0.28);
    border-radius: 14px;
    padding: clamp(16px, 2.5vw, 28px);
    margin: 20px 0;
    overflow-x: auto;
  }
  .wt-panel table {
    width: 100%;
    border-collapse: collapse;
    color: #e6e8ef;
    font-size: 14px;
  }
  .wt-panel th,
  .wt-panel td {
    text-align: left;
    padding: 10px 8px;
    border-bottom: 1px solid rgba(255, 255, 255, 0.08);
  }
  .wt-panel th {
    color: #ff2d8f;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 0.06em;
    font-size: 12px;
  }
  @media (max-width: 700px) {
    .wt-panel table,
    .wt-panel tbody,
    .wt-panel tr,
    .wt-panel td {
      display: block;
      width: 100%;
    }
    .wt-panel th {
      display: none;
    }
    .wt-panel td {
      padding: 6px 0;
      border-bottom: none;
    }
    .wt-panel tr {
      padding: 10px 0;
      border-bottom: 1px solid rgba(255, 255, 255, 0.08);
    }
  }
</style>
