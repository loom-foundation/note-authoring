---
id: authoring:conv:6mgre1s
name: Semantic line breaks
kind: convention
altitude: authoring
status: current
---

Corpus prose breaks lines at sentence boundaries, one sentence per source line: the break follows a full stop, or a semicolon joining independent clauses.
A line never breaks inside a sentence at a comma or another clause boundary; the clause-level breaks the [sembr.org](https://sembr.org) spec permits are not taken up.
Rendered markdown joins lines, so this governs source only and doesn't affect the output.

## Rationale

One sentence per line yields clean diffs, precise review anchors, and single-statement edits without rewrapping a paragraph.
This fixes the discipline as agreed practice: tool-reportable, never a validity gate.
