# RCG-005 — Publication and Manual Continuity Protocol

**Document ID:** RCG-005  
**Title:** Publication and Manual Continuity Protocol  
**Version:** 1.0  
**Status:** Adopted  
**Authority:** Constitutional Governance  
**Repository:** UCG Research Catalogue

---

## 1. Purpose

This protocol ensures that repository publication remains uninterrupted regardless of connector availability.

Publication shall always produce a repository-ready artifact. The method of delivery may vary, but the published content shall remain identical.

The purpose of this protocol is to preserve continuity of the UCG Research Catalogue v1.0 publication cycle when automated GitHub publication is unavailable, delayed, blocked, or unreliable.

---

## 2. Governing Principle

Repository authority derives from the finalized content and its placement within the repository, not from the mechanism used to publish it.

Connector publication and manual publication are operationally equivalent when the same approved Markdown artifact is committed to the intended repository path.

Connector availability shall never become a blocker to governance development, publication readiness, or repository construction.

---

## 3. Publication Modes

The UCG Research Catalogue recognizes two publication modes.

---

## 3.1 Mode A — Connector Publication

Connector Publication is the preferred publication mode.

When the GitHub connector is operational, the Repository Architect shall:

1. Complete the Authoring Pass.
2. Complete the Architectural Review Pass.
3. Commit the document directly to the repository.
4. Report the repository path and successful commit status.
5. Advance the publication queue.

Connector Publication is preferred because it preserves the delegated workflow and reduces manual operator burden.

---

## 3.2 Mode B — Manual Publication

Manual Publication is the required fallback when connector publication is unavailable.

When Manual Publication is required, the Repository Architect shall produce a repository-ready publication package containing:

- finalized Markdown document,
- intended repository path,
- intended filename,
- recommended commit message,
- publication status.

The Markdown document shall be considered publication-ready without further editorial review.

The Repository Operator may then commit the document manually to the specified repository path.

No additional review cycle is required unless the Repository Operator identifies a substantive error.

---

## 4. Publication Status Values

The following publication status values are recognized:

- **Draft** — The document is still being authored.
- **Authoring Complete** — The document has completed its authoring pass.
- **Architectural Review Complete** — The document has completed review against the v1.0 governance architecture.
- **Publication Ready** — The document is ready for repository commit by connector or manual publication.
- **Published** — The document has been committed to the repository.

Only documents marked Publication Ready or Published shall be treated as approved v1.0 governance artifacts.

---

## 5. Manual Publication Package Standard

A Manual Publication Package shall include the following elements.

### 5.1 Repository Path

The complete repository destination path.

Example:

```text
00_Governance/RCG-001_Research_Catalogue_Charter.md
```

### 5.2 Filename

The exact filename to be used in the repository.

### 5.3 Commit Message

A concise recommended commit message.

Example:

```text
Publish RCG-001 research catalogue charter
```

### 5.4 Markdown Document

The finalized Markdown document, either as a downloadable `.md` file or as complete Markdown text suitable for direct repository upload.

### 5.5 Publication Status

The status of the artifact at the moment it is handed to the Repository Operator.

---

## 6. Manual Publication Authority

Manual publication by the Repository Operator shall be considered authoritative when the committed document matches the approved publication-ready Markdown artifact.

Manual publication does not weaken the governance status of the document.

A manually published document has the same authority as a connector-published document.

---

## 7. Continuity Rule

If connector publication fails, the workflow shall not revert to design discussion, reassessment, or indefinite delay.

The Repository Architect shall immediately provide the Manual Publication Package and continue the publication sequence as appropriate.

If publication of a specific document must wait for manual operator action, the document shall remain marked Publication Ready until committed.

---

## 8. Operator Responsibility

When Manual Publication is used, the Repository Operator is responsible only for committing the provided Markdown artifact to the specified path.

The Repository Operator is not expected to redraft, reinterpret, restructure, or re-evaluate the document.

Manual publication is an upload operation, not an editorial process.

---

## 9. Connector Recovery

If the connector becomes available after a document has been prepared for manual publication but before manual upload occurs, the Repository Architect may complete publication through the connector.

If the document has already been committed manually, no connector publication is required.

Duplicate publication shall be avoided.

---

## 10. Repository Continuity Principle

The UCG Research Catalogue shall remain operational regardless of tooling state.

If repository publication cannot occur through automation, publication shall continue through manual repository commits using publication-ready Markdown artifacts.

The publication workflow shall remain continuous regardless of connector availability.

Governance development, research processing, and framework reconstruction shall not be halted by temporary publication tooling limitations.
