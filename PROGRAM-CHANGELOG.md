# 📘 PROGRAM-CHANGELOG.md

This file tracks all milestone groupings and execution transitions under the NI Open Source Program.

---

## [v2025.99] – Governance System Live

**Date:** 2025-05-27  
**Type:** Program Launch Milestone  
**Actor:** Foundational Architect GPT (executed via Git interface)

---

### 🔧 What Changed

- Declared the NI Open Source Program governance system *live and active*
- Formalized a **single source of truth** model for all milestone execution, contributor roles, and program file inheritance
- Published initial governance manifest: `REPOS-UNDER-GOVERNANCE.md`
- Designated the following repositories as in-scope for milestone-bound automation and contributor recognition:
  - `ni/open-source-program`
  - `ni/labview-open-source-program`
  - `ni/labview-icon-editor`
  - `ni/actor-framework`

---

### 📘 Next Actions

- Begin file inheritance drop in `labview-icon-editor` and `actor-framework`
- Begin milestone-bound contributor scoring, CLA role tracking, and nomination logic under `v2025.14+`
- Prepare `v2026.00` as the first post-launch governance evolution release


---

## 📅 2025-05-27 — v2025.13 Contributor Dashboard Tier Complete

This milestone tier publishes contributor dashboards under governance milestone control.

---

### ✅ Milestones

- `v2025.13.0` → `.13.4`

---

### 📂 Files Rendered

- `contributor-dashboard.yml`
- `CONTRIBUTORS.md`
- `dashboard-index.yml`
- `.github/ISSUE_TEMPLATE/contributor-feedback.yml`

---

### 🔐 Metadata Controls

- Contributors must be opt-in and validated
- All dashboards are milestone-bound
- Feedback and opt-out supported via issue templates

Tier: ✅ Closed  
Program Version: `v2025.05-governance-hardened`

---

## 📅 2025-05-27 — v2025.11 Contributor Licensing Enforcement Tier

This milestone series introduced the CLA + DCO validation system for contributor metadata under the NI Open Source Program.

---

### ✅ Milestones

- `v2025.11.0` — Validation tier launched
- `v2025.11.1` — Contributor verification protocol enforced
- `v2025.11.2` — CLA feed approved for downstream consumption

---

### 📂 Files

- `cla-status.yml`
- `CLA-STATUS-VERIFICATION.md`
- All milestone logs in `docs/governance/`

---

### 🔐 Trust Model

- All contributors in export feeds must be verified
- CLA GPT is registered for read-only access
- GPTs may not modify CLA status without milestone execution

Status: ✅ Tier sealed under `v2025.05-governance-hardened`

---

## 📅 2025-05-26 — v2025.10 Contributor Visibility Tier Complete

This milestone tier introduced contributor-facing metadata, dispute resolution, sync guidelines, and publishing logic.

---

### ✅ Milestones

- `v2025.10.0` → `v2025.10.4`

---

### 📂 Outputs

- `recertification-feed.yml`, `sharepoint-export.csv`, `contributors/*.md`
- `metadata-sync-spec.md`
- `contributor-dispute.md` issue template

---

### 🔐 Trust Rules

- All data opt-in only
- All logic milestone-bound
- No scoring automation permitted

Milestone Status: ✅ Closed  
Version: `v2025.05-governance-hardened`

---

## 📅 2025-05-26 — v2025.07 Recognition Layer Activated

This milestone series introduces the read-only Recognition GPT thread, which passively interprets contributor signals and surfaces candidates for badge nomination.

---

### 🧠 Milestones Completed

- `v2025.07.0` – GPT thread registered for recognition logic
- `v2025.07.1` – Nomination feed published (`nomination-feed.yml`)

---

### 📂 Outputs

- `docs/system/nomination-feed.yml`
- `GOVERNANCE-THREADS.md` updated with Recognition GPT role
- Milestone logs for execution trace

---

### 🔒 Enforcement

- No badge is assigned unless milestone-authorized
- All signal reads must be opt-in and public
- Automation remains frozen under `AUTOMATION-MODE.md`

---


## 📅 2025-05-26 — v2025.06 Execution Tier Completed

This milestone series marks the activation of live contributor metadata observation, onboarding enforcement, and public recognition signal feeds.

---

### ✅ Completed Milestones

- `v2025.06.3` – Onboard `ni/labview-icon-editor`
- `v2025.06.4` – Onboard `ni/actor-framework`
- `v2025.06.5` – Recognition signal observation begins
- `v2025.06.6` – Badge nomination triggers defined (manual only)
- `v2025.06.7` – `recognition-feed.yml` published
- `v2025.06.8` – Contributor opt-in template standardized
- `v2025.06.9` – Repo compliance audit complete

---

### 📂 Outputs

- `recognition-feed.yml` (public opt-in metadata view)
- `REPO-ROLE-MAP.md` and `GOVERNANCE-THREADS.md`
- Contributor license and automation freeze declarations

---

### 🚦 Enforcement

- No scoring or CEUs permitted
- CLA/DCO model assumed per repo
- All recognition must remain opt-in and milestone-bound

---

Version: `v2025.05-governance-hardened`  
Milestone Series: `v2025.06`  
Next: `v2025.07` — Recognition GPT Layer Design
