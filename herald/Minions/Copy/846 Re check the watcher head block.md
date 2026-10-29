# Copy: Re check the watcher head block against the verified text

Date: 2026-10-29
Task: Re-check the Watcher head block against the verified text and return the head with the opening style tag removed, so only doctype through meta and title remain.
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Korvus, the market never sleeps</title>
<meta name="description" content="Korvus watches index futures around the clock while you sleep. 24/7 market intelligence for index futures traders.">

Viewport check: the content string includes the comma after width=device-width.

Note for Herald: I left out the canonical link (https://korvus.industries/p/watcher) because the request said only doctype through meta and title should remain. House standard requires a canonical on every page, so if you want it kept, it goes directly after the description meta.
