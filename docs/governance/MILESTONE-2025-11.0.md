# MILESTONE-2025-11.0 — Contributor CLA Validation Tier Launch

> 🔐 This milestone launches a dedicated execution tier to validate contributor licensing under the NI Open Source Program.  
> All contributors listed in export feeds must meet this tier's requirements.

---

## 🧾 Validation Rules

| Condition | Accepted |
|-----------|----------|
| CLA signed via GitHub bot | ✅ Yes |
| Valid Developer Certificate of Origin (DCO) | ✅ Yes |
| Manual validation via `CLA-VERIFICATION.md` | ✅ Yes |
| Unknown handle or no matching PR | ❌ No |

---

## 📘 Scope of Execution

This tier allows:
- New GPTs scoped to validate CLA/DCO status
- Generation of `cla-status.yml` (GitHub identity → CLA/DCO status)
- Tooling to confirm contributor status from PR metadata or commit signature

---

## 🧠 GPT Thread Note

A `CLA GPT` may be introduced under this tier using `GOVERNANCE-THREADS.md`.  
It may only read:
- GitHub PR metadata
- Commit signature status
- CLA verification logs

---

Milestone: `v2025.11.0`  
Program: NI Open Source Program  
Version: `v2025.05-governance-hardened`
