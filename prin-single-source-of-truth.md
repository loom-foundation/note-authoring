---
id: authoring:prin:hgmwdy8
name: Single source of truth
kind: principle
altitude: authoring
status: current
---

Every piece of knowledge is stated once, in one home, and every place that needs it draws on that home by reference.
This holds for its code, configuration, documentation, and corpus of intent alike.

## Why this matters

Two copies drift apart, leaving readers with contradictions and no way to tell which is right.
A cross-reference is cheap; reconciling drift is expensive and erodes trust in the record.
The more contributors, human or AI, each touching a subset of files, the faster copies drift.

## How to apply

Before writing knowledge down, find or create its one home, then cite or derive from it everywhere else.
Hold derived things to the same rule: regenerate generated code, computed views, and rendered copies from their source; never edit them in place.
This principle governs what the work states, not what it does; duplicated behavior is reuse's concern.
Which artefact kind is the right home for recorded intent is the Note method's concern, not this principle's; it demands only a single home.
In review, when the same knowledge appears in two homes, delete the copy; never reconcile them.
When a home splits or moves, repoint every reference to its new home.

## Considered alternative

Restating content wherever it is used, for the reader's convenience: discarded.
A reference serves the reader well; two disagreeing versions serve them badly.

## Origin

Codd's relational model (one fact, stored once), DRY's rule that every piece of knowledge has one authoritative representation (Hunt and Thomas, 1999), and DITA's canonical-location pattern.
