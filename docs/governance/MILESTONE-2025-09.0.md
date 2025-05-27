# MILESTONE-2025-09.0 — Contributor Identity + CLA Verification

> This milestone initiates validation of contributors surfaced in nomination or recertification feeds.  
> All contributors must have confirmed GitHub identity and signed CLA or verified DCO status.

---

## ✅ CLA / DCO Requirement

All contributors listed in:
- `recognition-feed.yml`
- `nomination-feed.yml`
- `recertification-feed.yml`

…must meet one of the following:
- Signed NI Contributor License Agreement (CLA)
- DCO check via commit history
- Verified GitHub identity and public profile

---

## 🔐 Enforcement

- Contributors failing this check will be excluded from `sharepoint-export.csv`
- A new `validated: true/false` field will be added to recertification feeds
- GPTs and Education Services may only use data from verified contributors

---

Program: NI Open Source Program  
Milestone: v2025.09.0  
Version: v2025.05-governance-hardened
