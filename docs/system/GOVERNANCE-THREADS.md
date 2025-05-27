# 🧠 GOVERNANCE-THREADS.md

This file defines all AI threads and GPTs authorized to execute milestones, validate outputs, or write files in the NI Open Source Program.

---

## 🔁 Active GPT Threads (v2025.05)

| Thread Name | Role | May Write | May Read | Milestones |
|-------------|------|-----------|----------|------------|
| Certification Layer GPT | Contributor profile + certification export | `docs/certification/`, `docs/export/` | `docs/forms/` | v2025.08 → v2025.18 |
| Forms Parser GPT | Field mapping + opt-in ingestion | `FORMS-METADATA-MAP.md`, test forms | `.github/ISSUE_TEMPLATE` | v2025.06.2 |
| System GPT | Milestone logs + onboarding registry | `docs/governance/`, `docs/system/` | All folders | v2025.06.0 → v2025.09.4 (✅ Retired via v2025.08.5) |


---

## 🔒 Enforcement

- No GPT may write outside its declared folders
- All execution must be milestone-bound
- All role changes must be declared via program milestone

| Recognition GPT | Signal observer, nomination interpreter | `docs/system/recognition-feed.yml`, `.github/ISSUE_TEMPLATE/`, GitHub Discussions | None (read-only) | `v2025.07.x` |
