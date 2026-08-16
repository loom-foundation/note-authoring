---
id: authoring:conv:emtba7x
name: File names are short navigation hints
kind: convention
altitude: authoring
status: current
---

A Note artefact's file name is `<kind-segment>-<short-slug>.md`: its kind's segment, then a short slug chosen for navigation.
The slug may match the `name` but need not; the `name` carries the meaning and may be longer.

## Rationale

The kind segment duplicates what `kind` already states; this convention accepts that duplication so an agent browsing the filesystem can sort and find artefacts by kind without loading any frontmatter.

A file name is read in file explorers and editor columns, where short wins; the `name` is read in the artefact, where meaning wins.
A shared slug across kinds (req-normalised-data-model.md, spec-normalised-data-model.md) marks related artefacts without a sub-directory grouping them.
