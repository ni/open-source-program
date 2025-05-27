# MILESTONE-2025-10.4 — Contributor Feed Publishing Activation

> 🧾 This milestone authorizes the publication of contributor metadata in public dashboards, contributor lists, and program-visible feeds — provided all metadata is opt-in, validated, and milestone-traceable.

---

## ✅ Authorized Publishing Targets

| Location | Format | Source File |
|----------|--------|-------------|
| Docs Sites | Markdown / YAML | `recertification-feed.yml` |
| Dashboards | JSON | `sharepoint-export.csv` |
| Contributor Cards | GitHub READMEs | `metadata-sync-spec.md`, `contributors/*-view.md` |
| Internal Tools | Spreadsheet / API | `sharepoint-export.csv` |

---

## 🔐 Governance Constraints

- ❌ No contributor may be surfaced unless:
  - They opted in
  - Their entry appears in a feed governed by a committed milestone
  - They passed CLA/DCO validation
- ✅ All published views must reference the governing milestone ID

---

Program Version: `v2025.05-governance-hardened`  
Milestone: `v2025.10.4`  
Status: Active until revised under `v2025.11+`
