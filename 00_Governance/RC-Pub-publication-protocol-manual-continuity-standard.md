# Publication Protocol — Repository Publication & Manual Continuity Standard

## Purpose

This protocol ensures that repository publication remains uninterrupted regardless of connector availability.

Publication shall always produce a repository-ready artifact. The method of delivery may vary, but the published content shall remain identical.

---

# Publication Modes

The UCG Research Catalogue recognizes two publication modes.

## Mode A — Connector Publication (Preferred)

When the GitHub connector is operational, the Repository Architect shall:

1. Complete Authoring.
2. Complete Architectural Review.
3. Commit the document directly to the repository.
4. Report the successful commit.

This is the preferred publication workflow.

---

## Mode B — Manual Publication (Fallback)

If connector publication is unavailable, the Repository Architect shall instead produce:

* the finalized Markdown document,
* the intended repository path,
* the intended filename,
* the recommended commit message.

The Markdown document shall be considered publication-ready without further editing.

The Repository Operator may then commit the document manually.

No additional review cycle is required.

---

# Repository Authority

Repository authority derives from the published content, not the publication mechanism.

Connector publication and manual publication are considered operationally equivalent.

---

# Manual Publication Package

Every manual publication package shall include:

Repository Path

Filename

Commit Message

Markdown Document

Publication Status

This ensures that manual publication requires only repository upload.

---

# Publication Status Values

Draft

Authoring Complete

Architectural Review Complete

Publication Ready

Published

Publication Ready indicates that the document has completed every editorial requirement and awaits only repository commit.

---

# Repository Continuity Principle

Connector availability shall never interrupt repository development.

If repository publication cannot occur through automation, publication shall continue through manual repository commits using publication-ready Markdown artifacts.

The publication workflow shall remain continuous regardless of tooling availability.
