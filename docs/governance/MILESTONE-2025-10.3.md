# MILESTONE-2025-10.3 — Contributor Metadata Sync Proposal

> 🔄 This milestone proposes a method for safely syncing contributor metadata from the NI Open Source Program into downstream systems and GPTs.

---

## ✅ Sync Targets

| System | Allowed Data |
|--------|--------------|
| GitHub Dashboards | Public contributor feeds (`recognition-feed.yml`, `recertification-feed.yml`) |
| Docs Sites / READMEs | GitHub handle, opt-in status, milestone links |
| GPT Dashboards | Public data only, milestone-locked |
| Internal Tools | SharePoint exports, CLA-validated records |

---

## 🔒 Sync Enforcement Rules

- No system may auto-sync unless authorized by milestone (`v2025.11+`)
- All metadata must be:
  - Milestone-bound
  - Contributor opt-in
  - Read-only unless overridden

---

## 🧾 Metadata Includes

- GitHub handle
- Recognition tags (if surfaced)
- Point value (if milestone-approved)
- Opt-in and validation status
- Source repo + PR reference

---

Program Version: `v2025.05-governance-hardened`  
Milestone: `v2025.10.3`  
Execution Layer: Contributor Visibility
