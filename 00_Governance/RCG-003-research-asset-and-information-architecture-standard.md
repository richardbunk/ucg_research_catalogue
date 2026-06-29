# RCG-003 — Research Asset & Information Architecture Standard

**Unified Composition Guide (UCG) Research Catalogue**

**Document ID:** RCG-003
**Title:** Research Asset & Information Architecture Standard
**Version:** 1.0
**Status:** Canonical Foundational Governance
**Authority Level:** Core Operational Standard

---

# 1. Purpose

This standard establishes the organizational architecture governing all research assets within the Unified Composition Guide (UCG) Research Catalogue.

Where RCG-001 establishes the purpose of the Research Catalogue, and RCG-002 governs the transformation of research into reusable framework knowledge, RCG-003 defines how research assets are organized, identified, related, and maintained throughout their lifecycle.

Its purpose is to ensure that institutional knowledge remains:

* discoverable
* traceable
* maintainable
* extensible
* technology-independent
* reusable across future editions of the Unified Composition Guide

This standard governs information architecture rather than software implementation.

---

# 2. Governing Principle

Knowledge shall possess one authoritative location.

Additional occurrences should reference the authoritative source rather than duplicate it.

The architecture therefore prioritizes:

* single-source authority
* explicit relationships
* editorial traceability
* modular organization
* semantic discoverability

Repository organization exists to support knowledge—not define it.

---

# 3. Information Architecture Philosophy

The Research Catalogue is an editorial information architecture rather than merely a document repository.

Its organizational principles shall remain valid regardless of storage technology, repository platform, or publication medium.

Physical storage may evolve.

Logical organization shall remain stable.

Editorial relationships shall remain persistent.

This separation preserves institutional continuity independent of technology.

---

# 4. Organizational Dimensions

Every research asset exists simultaneously within three complementary organizational dimensions.

## Physical Organization

Defines where assets are stored.

Examples include:

* repositories
* directories
* cloud storage
* archives
* document libraries

Physical organization supports storage and retrieval.

---

## Logical Organization

Defines what an asset is.

Examples include:

* Source
* Research Session
* Extraction Record
* Knowledge Article
* Framework Candidate
* Governance Document
* Editorial Review
* Publication Package

Logical organization governs lifecycle and editorial responsibility.

---

## Semantic Organization

Defines what knowledge concerns.

Examples include:

* subject areas
* keywords
* topical classifications
* editorial relationships
* cross-references

Semantic organization supports discovery independent of physical storage.

---

# 5. Research Asset Types

The Research Catalogue recognizes the following canonical asset classes.

## Source Assets

Original research material.

Examples include:

* books
* journals
* academic papers
* manuals
* standards
* websites
* interviews
* historical documents

---

## Research Sessions

Working investigations conducted against one or more sources.

---

## Extraction Records

Structured reusable observations derived from research.

---

## Knowledge Articles

Editorially synthesized reference material intended for long-term reuse.

Knowledge Articles represent durable institutional knowledge rather than raw research.

---

## Framework Candidates

Research identified as potential additions or modifications to the Unified Composition Guide.

---

## Governance Documents

Policies, standards, protocols, and operational guidance governing the Research Catalogue.

---

## Publication Packages

The editorial assets necessary for canonical publication.

---

## Indices

Supporting organizational assets that improve navigation and discovery.

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

The package model represents the preferred editorial progression from research to published knowledge.

---

# 7. Repository Architecture

Repository implementations should reflect logical organization rather than storage convenience.

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

Individual repository implementations may differ provided that logical relationships remain consistent.

Repository technology shall not dictate information architecture.

---

# 8. Asset Identification Standard

Every canonical research asset shall possess a persistent identifier.

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

Identifiers are permanent and should never be reassigned.

---

# 9. Metadata Standard

Every canonical asset shall maintain standardized metadata sufficient to support governance, discovery, and editorial traceability.

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
* Related Assets
* Repository Location

Metadata should remain independent of filenames and repository structure.

---

# 10. Knowledge Relationships

Research assets rarely exist in isolation.

Where meaningful relationships exist between assets, they should be documented to improve discoverability, editorial traceability, and framework understanding.

Relationships supplement repository organization by recording how knowledge contributes to, depends upon, or extends other knowledge.

Knowledge relationships support:

* editorial navigation
* framework maintenance
* impact assessment
* knowledge reuse
* future extensibility

The Research Catalogue recognizes the following core relationship types:

* Derived From
* Supports
* Extends
* References
* Related To
* Parent
* Child
* Supersedes

These relationship types are intentionally limited to those required for current editorial operations.

Additional relationship categories may be introduced through future governance when operational requirements justify their inclusion.

---

# 11. Subject Library

The Subject Library provides the primary semantic organization of the Research Catalogue.

Unlike a traditional index, Subject Library entries contain editorially synthesized knowledge rather than merely pointing to documents.

Knowledge Articles may contribute to multiple subject areas simultaneously.

The Subject Library therefore complements physical repository organization by organizing knowledge according to editorial subject matter rather than storage location.

Subject organization supports:

* discovery
* editorial continuity
* knowledge reuse
* institutional maintenance

---

# 12. Publication Architecture

Canonical publication consists of more than storing a document.

Publication should include:

* canonical asset
* standardized metadata
* relationship updates
* subject library updates
* cross-references
* changelog updates
* version registration
* repository indexing

Publication completes the integration of research into institutional knowledge.

---

# 13. Repository Evolution

Storage technologies will evolve.

Repository platforms may change.

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
* technology-dependent organization
* orphaned assets
* undocumented supersession

Architectural consistency is an editorial responsibility.

---

# 15. Architectural Continuity

This standard intentionally distinguishes between:

* physical organization
* logical organization
* editorial relationships

Together these complementary organizational layers provide sufficient structure to support the current objectives of the Research Catalogue while remaining extensible enough to accommodate future growth without requiring fundamental architectural revision.

The governance established herein defines principles rather than implementation.

---

# 16. Relationship to Previous Governance

RCG-001 defines:

> **Why the Research Catalogue exists.**

RCG-002 defines:

> **How research becomes reusable framework knowledge.**

RCG-003 defines:

> **How research assets are organized, identified, and related within a durable institutional information architecture.**

Together these three documents establish the constitutional foundation of the Research Catalogue.

---

# Foundational Statement

> Knowledge acquires enduring value only when it can be located, understood, verified, related, and reused. The purpose of this standard is to ensure that every research asset contributes to a coherent institutional architecture in which organization serves understanding, relationships preserve context, and structure enables future discovery while remaining focused on the continued development and publication of the Unified Composition Guide.

---

## Document Metadata

**Document ID:** RCG-003

**Title:** Research Asset & Information Architecture Standard

**Version:** 1.0

**Status:** Canonical

**Authority:** Core Operational Standard

**Owner:** Unified Composition Guide Research Catalogue

**Parent Documents:**

* RCG-001 — UCG Research Catalogue Charter
* RCG-002 — Research Extraction & Framework Codification Protocol

**Child Documents (Planned):**

* RCG-004 — Research Editorial Standards
* RCG-005 — Research Publication & Version Control Standard

**Supersedes:** None

**Superseded By:** —

**Approved:** __________________

**Review Cycle:** As Required

**Keywords:**

research architecture, information architecture, research assets, governance, metadata, subject library, publication, organization

---

**End of RCG-003 — Research Asset & Information Architecture Standard v1.0**
