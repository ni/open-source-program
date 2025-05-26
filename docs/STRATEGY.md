# 🧭 Governance Strategy: Repository and Program Separation

> This document explains the strategic rationale behind separating the **NI Open-Source Governance Framework** from implementation repositories such as `labview-open-source-framework`.

---

## 🎯 Goals

This architecture was designed to:

- Protect contributor trust and badge traceability
- Allow individual repos to evolve, fork, or sunset without disrupting the program
- Enable NI or future owners to reuse the governance system across unrelated codebases
- Make role authority, recognition logic, and scoring visible and auditable outside of any single technical project

---

## 🧱 Structural Overview

| Element | Repo | Purpose |
|--------|------|---------|
| **Governance Program** | [`ni/open-source`](https://github.com/ni/open-source) | Defines contributor roles, scoring models, recognition, override paths |
| **Implementation Repo** | [`labview-open-source-framework`](https://github.com/ni/labview-open-source-framework) | Hosts LabVIEW code governed by that program — enforces templates, participation rules, and trust model |
| **Badge and Scoring Logic** | Stored centrally | Ensures governance continuity across forks or org shifts |
| **License (BSD-0)** | Per-repo | Allows each implementation to define reuse terms without affecting the program itself |

---

## 🔄 Forking and Continuity

This structure enables:

- A fork of `labview-open-source-framework` to still honor the upstream governance rules
- A future NI program to fork `ni/open-source` and define a **new governance milestone**
- Contributors to remain eligible for scoring even if they shift repos or orgs

---

## 🔐 Risk-Proofing Contributor Recognition

All public recognition is:

- **Opt-in and GitHub-visible**
- Anchored in participation + templates (not employer or org status)
- Scored centrally and confirmed by the Program Manager or Core Team

This ensures that contributors are protected from political drift, hidden reprioritization, or internal reframing.

---

## 🧭 Strategic Asset Summary

By separating governance from implementation:

- The **governance system becomes reusable**
- **Scoring and recognition stay intact** across forks
- The program can **scale to new technologies or teams** without rebuilding policy
- **NI leadership or successors must operate transparently** when evolving contributor terms

---

Maintained by: Program Manager & Architect  
Governance Milestone: `v2025.05-governance-hardened`  
License: BSD Zero Clause (repo-level), CLA/DCO-enforced (program-level)
