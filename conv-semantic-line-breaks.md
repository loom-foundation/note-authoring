---
id: authoring:conv:6mgre1s
name: Semantic line breaks
kind: convention
altitude: authoring
status: current
---

Corpus prose breaks lines at semantic boundaries, one sentence or clause per source line, per the Semantic Line Breaks spec at [sembr.org](https://sembr.org).
Rendered markdown joins lines, so this governs source only and doesn't affect the output.

## Rationale

One sentence per line yields clean diffs, precise review anchors, and single-statement edits without rewrapping a paragraph.
This fixes the discipline as agreed practice: tool-reportable, never a validity gate.
