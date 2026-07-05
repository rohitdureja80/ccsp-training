# Changelog

All notable changes to the CCSP Living Study Guide will be documented in this file.

This project follows a documentation-as-code approach:
- Markdown files are the source of truth.
- Git history tracks all content changes.
- PDF/DOCX exports are generated artifacts.
- Updates are organized around CCSP domains and exam objectives.

---

## [Unreleased]

### Added
- Placeholder for upcoming CCSP content additions.

---

## [2.0.0] - 2026-07-04

### Added
- Migrated CCSP Living Study Guide to Git-based knowledge repository.
- Created documentation-as-code structure.
- Established folder organization:
  - domains
  - quick-reference
  - high-yield
  - resources
  - exports
  - images

### Added Study Guide Framework
- Added support for six ISC2 CCSP domains:
  - Domain 1: Cloud Concepts, Architecture & Design
  - Domain 2: Cloud Data Security
  - Domain 3: Cloud Platform & Infrastructure Security
  - Domain 4: Cloud Application Security
  - Domain 5: Cloud Security Operations
  - Domain 6: Legal, Risk & Compliance

### Added Tracking Methodology
- Introduced High-Yield Concept tracking.
- Added personal weak-area tracking.
- Added exam frequency ratings:
  - ⭐⭐⭐⭐⭐ Very High
  - ⭐⭐⭐⭐ High
  - ⭐⭐⭐ Moderate
  - ⭐⭐ Low
  - ⭐ Reference

### Added Priority Classification
Concepts will be tagged as:

- 🔴 Critical
  - Frequently tested concepts
  - Personal weak areas
  - Must understand before exam

- 🟡 Important
  - Common exam topics
  - Review regularly

- 🟢 Review
  - Known concepts requiring periodic refresh

### Added Standard Topic Template
Each major topic will include:

- Definition
- Architecture explanation
- Real-world cloud examples
  - Azure
  - AWS
  - Google Cloud
- CCSP exam tips
- Common exam traps
- Related concepts
- Further reading references

### Migration Notes
This version replaces the previous single-document approach.

Previous format:

CCSP_Living_Study_Guide_v2.0_2026-07-04.docx

New format:

Markdown + Git repository

Primary benefits:
- Version history
- Smaller incremental updates
- Easier topic maintenance
- Better cross-linking
- Future automated exports