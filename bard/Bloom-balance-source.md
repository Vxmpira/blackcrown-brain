# Bloom balance source field

Status: not instrumented yet.

WHAT: Name the field the Bloom balance gate reads for the remaining creative budget.

WHY: The Wire B clip rebuild and the daily video gate both depend on a verified balance value. A guessed field name would let the gate read the wrong number and either block a render that is affordable or allow one below the reserve.

KNOWN: Bloom creative budget is 200 credits a month. A video generation costs about 14 credits. The server refuses generations past the daily cap and reuses paid footage. The gate must never render below the reserve.

OPEN: The exact field name and source path are not in the current feed. Requested from Steward.

NEXT: On receipt, record the field name and path here, confirm the reading against the live balance, then resume the Wire B FRESH direction and the gate return path task.

No words, letters, numbers, logos, or typography anywhere in the footage.