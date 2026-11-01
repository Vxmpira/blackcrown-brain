# Scribe: Draft a click position instrumentation spec for the analytics tracker

Date: 2026-11-01
Task: Draft a click-position instrumentation spec for the analytics tracker: a data-pos attribute scheme for CTA links (values like hero, pricing, footer, nav) plus t
For [[Corvid]].

# Click Position Instrumentation Spec

**Owner:** Scribe, for Corvid
**Consumers:** Regent (maps onto the live tracker), Bard (hook test read)
**Rung:** First paying customer. Position data tells us which placements earn clicks, so the next spend and copy changes go where the clicks are.
**Status:** Ideal scheme. Nothing below describes the current tracker. Regent maps each field onto the live code after the snippet is pasted.

---

## 1. Problem

The tracker logs one value per click: the destination key (`korvus`, `intelligence`, `eclipse-x`, `lodestone`). It does not record where on the page the click happened. Two clicks to the same destination from the hero and from the footer look identical. The 11-10 hook test needs placement data to read which surface drives the clicks.

## 2. Scope

- Applies to every CTA link: any `<a>` that sends a visitor to a product or community destination.
- Does not cover navigation between pages on the same site unless the link is a CTA.
- Does not change destinations, copy, or UTM tagging. UTM tagging on outbound Korvus links shipped 2026-10-26 and stays as is.

## 3. The Attribute Scheme

Every CTA link carries two required attributes and up to two optional ones.

| Attribute | Required | Purpose | Example |
|---|---|---|---|
| `data-pos` | Yes | Where on the page the link sits | `hero` |
| `data-dest` | Yes | Destination key, matching the existing tracker keys | `korvus` |
| `data-pos-index` | No | Ordinal of this link within its position, starting at 1 | `2` |
| `data-test` / `data-arm` | Only during a test | Test id and arm, for the 11-10 hook test | `hook-1110` / `b` |

### 3.1 `data-pos` values (closed set)

| Value | Meaning |
|---|---|
| `nav` | Links inside the site header or top navigation bar |
| `hero` | Links in the first full-screen block of the page |
| `body` | Links inside the main content below the hero, outside pricing |
| `pricing` | Links inside any pricing or plan section, including plan cards |
| `footer` | Links inside the page footer |

Rules:

1. Use exactly one value per link. Lowercase only.
2. Values come only from this list. Add a new value only through a written change to this spec.
3. If a link sits in a region not covered above, use `body`. Do not invent values.
4. Nesting uses the nearest named region. A link inside a pricing card inside the hero is `pricing`, because the card is the region the visitor reads.
5. If a link arrives without `data-pos`, the tracker records `unknown` and keeps the click. Clicks are never dropped for a missing attribute.

### 3.2 `data-pos-index`

Used when one position holds several links to the same destination, such as two buttons in the hero. Index counts top to bottom, left to right, starting at 1. Optional. Omit it when a position has one CTA.

### 3.3 `data-dest`

Uses the destination keys already in the tracker: `korvus`, `intelligence`, `eclipse-x`, `lodestone`. This spec adds no new destination keys. If a link points somewhere else, record `other` and flag it for Regent.

### 3.4 Test fields

`data-test` and `data-arm` are set only on links that belong to a running test. The 11-10 hook test uses:

- `data-test="hook-1110"`
- `data-arm="a"` or `data-arm="b"`

Outside a test, omit both. Do not leave stale test ids on links after the test ends.

## 4. Example Markup (illustrative)

```html
<!-- Illustration: hero primary CTA -->
<a href="https://korvus.industries/" data-pos="hero" data-pos-index="1" data-dest="korvus"
   data-test="hook-1110" data-arm="b">Start with Korvus</a>

<!-- Illustration: footer link to community -->
<a href="https://discord.gg/example" data-pos="footer" data-dest="eclipse-x">Join Eclipse-X</a>
```

The `href` values are placeholders. Only the attributes are the spec.

## 5. Event Schema

One event per CTA click. Field names below are the ideal names. Regent maps them onto the live tracker's field names.

| Field | Type | Source | Notes |
|---|---|---|---|
| `event` | string | fixed | `cta_click` |
| `pos` | string | `data-pos` | One of the five values, or `unknown` |
| `pos_index` | integer or null | `data-pos-index` | Null when absent |
| `dest` | string | `data-dest` | Existing destination keys, or `other` |
| `test` | string or null | `data-test` | Null outside a test |
| `arm` | string or null | `data-arm` | Null outside a test |
| `page` | string | page path | Path only, no query string, no fragment |
| `ts` | timestamp | client clock at click | UTC |

Not collected: link text, form content, cookies added for this purpose, user identifiers beyond what the tracker already keeps.

## 6. Firing Rules

1. Fire on click, before navigation.
2. Send with a non-blocking method (a beacon or keepalive request) so the visitor's navigation is never delayed.
3. Fire once per click. A double click on the same link counts as one event if the second click lands within the same navigation.
4. If the send fails, drop the event silently. Do not retry in a loop and do not block the link.
5. Do not fire on hover, scroll, or page view. Those are separate specs.

## 7. Reporting Views for Bard

Aggregates only. No per-visitor rows.

1. **Clicks by position:** count of `cta_click` grouped by `pos`, with share of total clicks.
2. **Position by destination:** matrix of `pos` against `dest`.
3. **Hook test read:** clicks by `pos` split by `arm`, for `test = hook-1110`. Report counts and shares. Do not state a winner from a small sample. Report the sample size beside every share.

Until the snippet is live, these views read "not instrumented yet."

## 8. Validation Checklist (for Regent, before go live)

- [ ] Every CTA link on the target pages carries `data-pos` and `data-dest`.
- [ ] All `data-pos` values come from the closed set in 3.1.
- [ ] No link carries a `data-test` or `data-arm` outside the test window.
- [ ] A test click on each position produces one event with the expected `pos`, `dest`, and `page`.
- [ ] A link with the attribute removed produces `pos = unknown` and still navigates.
- [ ] Navigation timing is unchanged when the send is blocked.
- [ ] No link text or query strings appear in stored events.
- [ ] UTM parameters on outbound Korvus links are unchanged.

## 9. Acceptance

The spec is live when the checklist passes and Bard's first position report returns counts for at least three of the five positions after a day of normal traffic. Until then the report stays marked "not instrumented yet." Report the sample size with every figure.

## 10. Open Questions for Corvid

1. Should `nav` include the mobile menu toggle, or only the links inside it? This draft counts only the links.
2. Does the hook test need `body` split into sub-positions, or is one bucket enough for the first read?
