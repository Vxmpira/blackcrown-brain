# Copy: Write part b of the crown skeptic page style block

Date: 2026-10-30
Task: Write part B of the Crown skeptic page style block: container max-width 1060px centered with side padding, clamp() headings, readable prose under 75 characters 
For [[Herald]].

.skeptic-page {
  position: relative;
  background-color: #07070c;
  color: #e9e7f2;
  min-height: 100%;
  overflow-x: hidden;
  background-image:
    radial-gradient(ellipse 60% 40% at 85% 0%, rgba(255, 45, 143, 0.10), transparent 70%),
    radial-gradient(ellipse 50% 35% at 0% 100%, rgba(255, 45, 143, 0.06), transparent 70%),
    linear-gradient(rgba(233, 231, 242, 0.03) 1px, transparent 1px),
    linear-gradient(90deg, rgba(233, 231, 242, 0.03) 1px, transparent 1px);
  background-size: auto, auto, 48px 48px, 48px 48px;
  box-shadow: inset 0 0 160px rgba(0, 0, 0, 0.75);
}

.skeptic-wrap {
  box-sizing: border-box;
  width: 100%;
  max-width: 1060px;
  margin: 0 auto;
  padding: 0 clamp(16px, 4vw, 32px);
}

.skeptic-section {
  padding: clamp(40px, 7vw, 88px) 0;
  border-top: 1px solid rgba(233, 231, 242, 0.08);
}

.skeptic-page h1,
.skeptic-page h2,
.skeptic-page h3 {
  color: #e9e7f2;
  line-height: 1.15;
  letter-spacing: -0.01em;
  margin: 0 0 0.6em;
}

.skeptic-page h1 {
  font-size: clamp(1.9rem, 6vw, 3.25rem);
}

.skeptic-page h2 {
  font-size: clamp(1.5rem, 4vw, 2.25rem);
}

.skeptic-page h3 {
  font-size: clamp(1.05rem, 2.6vw, 1.25rem);
}

.skeptic-page h2 .accent,
.skeptic-page h1 .accent {
  color: #ff2d8f;
}

.skeptic-prose {
  max-width: 70ch;
}

.skeptic-prose p,
.skeptic-prose li {
  font-size: clamp(1rem, 2.2vw, 1.0625rem);
  line-height: 1.7;
  color: #e9e7f2;
  margin: 0 0 1.1em;
}

.skeptic-prose .muted,
.skeptic-muted {
  color: #9a97ab;
}

.skeptic-prose a {
  color: #ff2d8f;
  text-decoration: underline;
  text-underline-offset: 3px;
}

.skeptic-prose ul,
.skeptic-prose ol {
  padding-left: 1.25em;
  margin: 0 0 1.2em;
}

.skeptic-prose li {
  margin-bottom: 0.5em;
}

.skeptic-lede {
  font-size: clamp(1.05rem, 2.6vw, 1.25rem);
  line-height: 1.6;
  color: #e9e7f2;
  max-width: 62ch;
  margin: 0 0 1.4em;
}

.skeptic-rule {
  display: block;
  width: 56px;
  height: 2px;
  background: #ff2d8f;
  margin: 0 0 1.25em;
  border: 0;
}

.skeptic-table-wrap {
  width: 100%;
  margin: 1.5em 0 2em;
  border: 1px solid rgba(233, 231, 242, 0.1);
  background: rgba(12, 12, 20, 0.85);
  border-radius: 6px;
  overflow: hidden;
}

.skeptic-table {
  width: 100%;
  border-collapse: collapse;
  table-layout: fixed;
  font-size: 0.95rem;
}

.skeptic-table caption {
  caption-side: top;
  text-align: left;
  padding: 14px 18px;
  color: #9a97ab;
  font-size: 0.85rem;
  letter-spacing: 0.04em;
  text-transform: uppercase;
  border-bottom: 1px solid rgba(233, 231, 242, 0.08);
}

.skeptic-table th,
.skeptic-table td {
  padding: 14px 18px;
  text-align: left;
  vertical-align: top;
  border-bottom: 1px solid rgba(233, 231, 242, 0.07);
  overflow-wrap: anywhere;
}

.skeptic-table th {
  color: #9a97ab;
  font-weight: 600;
  font-size: 0.8rem;
  letter-spacing: 0.06em;
  text-transform: uppercase;
}

.skeptic-table td {
  color: #e9e7f2;
}

.skeptic-table tr:last-child td {
  border-bottom: 0;
}

.skeptic-table td.flag {
  color: #ff2d8f;
  font-weight: 600;
}

.skeptic-figure {
  width: 100%;
  margin: 1.5em 0 2em;
  padding: clamp(16px, 3vw, 28px);
  box-sizing: border-box;
  background: #0c0c14;
  border: 1px solid rgba(255, 45, 143, 0.35);
  border-radius: 6px;
}

.skeptic-figure svg {
  display: block;
  width: 100%;
  height: auto;
}

.skeptic-figure figcaption {
  margin-top: 14px;
  color: #9a97ab;
  font-size: 0.85rem;
  line-height: 1.5;
}

.skeptic-tag {
  display: inline-block;
  padding: 3px 9px;
  border: 1px solid rgba(255, 45, 143, 0.5);
  color: #ff2d8f;
  font-size: 0.72rem;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  border-radius: 3px;
  margin-bottom: 12px;
}

.skeptic-chips {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin: 1.25em 0 1.75em;
  padding: 0;
  list-style: none;
}

.skeptic-chip {
  padding: 8px 14px;
  border: 1px solid rgba(233, 231, 242, 0.14);
  background: rgba(233, 231, 242, 0.03);
  color: #e9e7f2;
  font-size: 0.88rem;
  border-radius: 999px;
  line-height: 1.2;
}

.skeptic-chip.is-hot {
  border-color: rgba(255, 45, 143, 0.6);
  color: #ff2d8f;
}

.skeptic-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: clamp(14px, 2.5vw, 22px);
  width: 100%;
  margin: 1.5em 0 2em;
}

.skeptic-card {
  box-sizing: border-box;
  min-width: 0;
  padding: clamp(18px, 3vw, 26px);
  background: #0c0c14;
  border: 1px solid rgba(233, 231, 242, 0.1);
  border-radius: 6px;
}

.skeptic-card p {
  color: #9a97ab;
  font-size: 0.95rem;
  line-height: 1.6;
  margin: 0;
}

.skeptic-card h3 {
  margin-bottom: 0.5em;
}

.skeptic-panel {
  width: 100%;
  box-sizing: border-box;
  padding: clamp(18px, 3vw, 28px);
  margin: 1.5em 0 2em;
  background: linear-gradient(180deg, rgba(255, 45, 143, 0.06), rgba(12, 12, 20, 0.9));
  border: 1px solid rgba(255, 45, 143, 0.3);
  border-radius: 6px;
}

.skeptic-stat {
  display: block;
  font-size: clamp(1.75rem, 5vw, 2.5rem);
  font-weight: 700;
  color: #ff2d8f;
  line-height: 1.1;
  margin-bottom: 0.3em;
}

.skeptic-stat-label {
  display: block;
  color: #9a97ab;
  font-size: 0.9rem;
  line-height: 1.5;
}

@media (max-width: 700px) {
  .skeptic-grid {
    grid-template-columns: 1fr;
  }

  .skeptic-table-wrap {
    border: 0;
    background: transparent;
    overflow: visible;
  }

  .skeptic-table,
  .skeptic-table tbody,
  .skeptic-table tr,
  .skeptic-table td {
    display: block;
    width: 100%;
  }

  .skeptic-table caption {
    border: 1px solid rgba(233, 231, 242, 0.1);
    border-radius: 6px 6px 0 0;
    background: #0c0c14;
  }

  .skeptic-table thead {
    display: none;
  }

  .skeptic-table tr {
    margin-bottom: 14px;
    border: 1px solid rgba(233, 231, 242, 0.1);
    border-radius: 6px;
    background: #0c0c14;
    overflow: hidden;
  }

  .skeptic-table td {
    border-bottom: 1px solid rgba(233, 231, 242, 0.07);
    padding: 12px 16px;
  }

  .skeptic-table td::before {
    content: attr(data-label);
    display: block;
    color: #9a97ab;
    font-size: 0.72rem;
    letter-spacing: 0.06em;
    text-transform: uppercase;
    margin-bottom: 4px;
  }

  .skeptic-table td:last-child {
    border-bottom: 0;
  }

  .skeptic-chip {
    font-size: 0.82rem;
    padding: 7px 12px;
  }
}

@media (min-width: 701px) and (max-width: 960px) {
  .skeptic-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}
</style>
