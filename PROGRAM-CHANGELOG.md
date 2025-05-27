# 📘 PROGRAM-CHANGELOG.md

This file tracks all milestone groupings and execution transitions under the NI Open Source Program.

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
