# RCG-003 — Research Asset & Information Architecture Standard

**Unified Composition Guide (UCG) Research Catalogue**

**Document ID:** RCG-003
**Title:** Research Asset & Information Architecture Standard
**Version:** 1.0 (Draft)
**Status:** Foundational Governance
**Authority Level:** Core Operational Standard

---

# 1. Purpose

This standard defines the organizational architecture governing all research assets within the Unified Composition Guide (UCG) Research Catalogue.

Where RCG-001 establishes the purpose of the Research Catalogue, and RCG-002 governs the transformation of research into reusable framework knowledge, RCG-003 establishes how research assets are organized, identified, related, and maintained throughout their lifecycle.

The objective is to ensure that institutional knowledge remains:

* discoverable
* traceable
* maintainable
* extensible
* technology-independent
* reusable across future generations of the UCG ecosystem

---

# 2. Governing Principle

Knowledge shall possess one authoritative location.

Every additional occurrence should reference the authoritative source rather than duplicate it.

The architecture therefore prioritizes:

* single-source authority
* explicit relationships
* editorial traceability
* modular organization
* semantic discoverability

Repository organization exists to support knowledge—not define it.

---

# 3. Information Architecture Philosophy

The Research Catalogue is an information architecture rather than merely a file repository.

Its structure must remain valid regardless of storage technology, repository platform, or publication medium.

Physical storage may evolve.

Logical organization shall remain stable.

Semantic relationships shall remain persistent.

---

# 4. The Three Organizational Dimensions

Every research asset exists simultaneously within three independent organizational dimensions.

## Physical Organization

Defines where assets are stored.

Examples include:

* repositories
* directories
* archives
* cloud storage
* document libraries

Physical organization supports storage and retrieval.

---

## Logical Organization

Defines what an asset is.

Examples include:

* Source
* Research Session
* Extraction
* Knowledge Article
* Framework Proposal
* Governance Document
* Editorial Review
* Publication Package

Logical organization defines lifecycle and governance.

---

## Semantic Organization

Defines what the knowledge is about.

Examples include:

* subject domains
* keywords
* topical classifications
* cross-references
* conceptual relationships

Semantic organization enables discovery independent of physical storage.

---

# 5. Research Asset Types

The Research Catalogue recognizes the following canonical asset classes.

## Source Assets

Original research material.

Examples:

* books
* papers
* manuals
* interviews
* websites
* transcripts

---

## Research Sessions

Working analysis performed against one or more sources.

---

## Extraction Records

Structured reusable observations derived from research.

---

## Knowledge Articles

Synthesized subject-oriented reference material intended for long-term reuse.

---

## Framework Candidates

Research identified as potential additions to the Unified Composition Guide.

---

## Governance Documents

Policies, standards, procedures, and operational guidance governing the catalogue itself.

---

## Publication Packages

The complete editorial package required for canonical publication.

---

## Indices

Organizational assets used for discovery, navigation, and relationship management.

---

# 6. Research Package Model

Each completed research effort should produce a coherent research package.

```text
Source
    ↓
Research Notes
    ↓
Extraction Records
    ↓
Knowledge Articles
    ↓
Framework Candidates
    ↓
Editorial Review
    ↓
Publication Record
```

Not every project will generate every asset.

The package model defines the ideal editorial progression.

---

# 7. Repository Architecture

Repository implementation should reflect logical organization rather than storage convenience.

Typical architectural layers include:

```text
00_Governance
01_Sources
02_Research
03_Extractions
04_Knowledge_Library
05_Framework_Candidates
06_Publication
07_Archives
08_Indices
```

Individual implementations may vary provided logical relationships remain intact.

---

# 8. Asset Identification Standards

Every canonical asset shall possess a persistent identifier.

Identifiers should remain stable throughout the asset lifecycle.

Examples include:

```text
RCG-001
RCG-002
RCG-003

SRC-000001

SES-000001

EXT-000001

KA-000001

FCP-000001
```

Identifiers are permanent and should never be reused.

---

# 9. Metadata Standard

Every canonical asset shall maintain standardized metadata sufficient to support governance and discovery.

Recommended metadata includes:

* Document ID
* Title
* Version
* Status
* Author
* Creation Date
* Revision Date
* Source References
* Editorial Confidence
* Review Status
* Subject Classification
* Keywords
* Relationships
* Repository Location

Metadata should remain independent of file names.

---

# 10. Relationship Architecture

Knowledge becomes increasingly valuable as explicit relationships accumulate.

Assets should define relationships wherever applicable.

Relationship categories include:

* Derived From
* Supports
* Extends
* References
* Referenced By
* Related Topics
* Parent
* Child
* Supersedes
* Superseded By

Relationship mapping transforms isolated documents into an interconnected knowledge system.

---

# 11. Subject Library

Subject organization shall be based upon synthesized knowledge rather than directory structures.

The Subject Library serves as the semantic organization layer of the Research Catalogue.

Unlike traditional indices, Subject Library entries contain editorially synthesized knowledge rather than simple references.

A single Knowledge Article may participate in multiple subjects simultaneously.

Subject organization therefore supplements—not replaces—repository structure.

---

# 12. Publication Architecture

Canonical publication consists of more than storing a document.

Publication should include:

* canonical asset
* metadata
* relationship updates
* subject updates
* cross-references
* changelog
* version registration
* repository indexing

Publication completes integration into institutional knowledge.

---

# 13. Repository Evolution

Storage technologies will evolve.

Repository platforms will change.

Directory structures may be reorganized.

The logical information architecture defined by this standard shall remain stable across future implementations.

Editorial continuity shall never depend upon a particular software platform.

---

# 14. Architectural Integrity

Editors shall avoid organizational practices that reduce long-term maintainability.

Examples include:

* duplicate authoritative copies
* inconsistent identifiers
* undocumented relationships
* ambiguous subject placement
* technology-dependent structures
* orphaned assets
* undocumented supersession

Architectural consistency is considered a governance responsibility.

---

# 15. Relationship to Previous Governance

RCG-001 defines:

> **Why the Research Catalogue exists.**

RCG-002 defines:

> **How research becomes reusable knowledge.**

RCG-003 defines:

> **How research assets are organized into a durable institutional information architecture.**

Together these three documents establish the constitutional foundation of the Research Catalogue.

---

# Foundational Statement

> Knowledge acquires enduring value only when it can be located, understood, verified, related, and reused. The purpose of this standard is to ensure that every research asset contributes to a coherent institutional architecture in which organization serves understanding, relationships preserve context, and structure enables future discovery independent of technology.

---

## Document Metadata

**Document ID:** RCG-003

**Title:** Research Asset & Information Architecture Standard

**Version:** 1.0

**Status:** Draft

**Authority:** Core Operational Standard

**Owner:** Unified Composition Guide Research Catalogue

**Parent Documents:**

* RCG-001 — UCG Research Catalogue Charter
* RCG-002 — Research Extraction & Framework Codification Protocol

**Child Documents (Planned):**

* RCG-004 — Research Editorial Standards
* RCG-005 — Research Publication & Version Control Standard

**Review Cycle:** As Required

---

**End of RCG-003 — Research Asset & Information Architecture Standard v1.0**
