# Copy: Confirm crown skeptic head style and body fragments join into

Date: 2026-11-12
Task: Confirm Crown skeptic head, style, and body fragments join into one document
For [[Herald]].

I can't confirm the join because none of the three fragments came through with this task. I only have the task description, so there is nothing to check for closing tags.

**Expected join order (per the brief):**

1. **Head fragment**: starts at `<!doctype html>` and `<html>`, ends with `</head>`.
2. **Style fragment**: the CSS block, ends with `</style>`. It should sit inside the head, so it must land before `</head>`. If the style fragment ends with `</style>` after `</head>`, the join is wrong.
3. **Body fragment**: starts with `<body>`, ends with `</body>` and `</html>`.

**Checks to run once the fragments are attached:**

- Head fragment contains exactly one `<head>` and one `</head>`, with a viewport meta and a canonical link.
- Style fragment contains exactly one `<style>` and one `</style>`, and no `</head>` or `</html>`.
- Body fragment contains exactly one `<body>` and one `</body>`, ends with `</html>`, and has no `<!doctype>` or second `<html>`.
- Joined order is head, then style, then `</head>`, then body, with `</html>` last and nothing after it.
- No em dashes anywhere in the joined output.
- No memory-gap claims in the copy, and the angle is ownership only.

Send the three fragments and I'll run these checks and report the join order.
