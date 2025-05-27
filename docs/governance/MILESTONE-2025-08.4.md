# MILESTONE-2025-08.4 — Education Services Handoff & Read-Only Role Declaration

> 📦 This milestone formally registers Education Services as a system-level consumer of contributor metadata and recertification exports under the NI Open Source Program.

---

## 🧠 Scope of Role

| Capability | Status |
|------------|--------|
| May read `recertification-feed.yml` | ✅ Yes |
| May use `sharepoint-export.csv` | ✅ Yes |
| May update contributor status in SharePoint | ✅ Internal only |
| May edit badge logic or scoring | ❌ No |
| May create training guides from dashboard data | ✅ Yes |
| May activate a GPT in a separate repo | ✅ Future milestone only |

---

## 🧾 Files Delivered

- `recertification-feed.yml`
- `sharepoint-export.csv`
- `README-education.md`

All data is opt-in, milestone-bound, and publicly sourced.

---

## 🔐 Enforcement Notes

- Education Services is a read-only metadata consumer
- Any GPTs or workflows triggered for Education Services must be declared in `GOVERNANCE-THREADS.md` under a new thread ID
- SharePoint exports are not scoring-eligible unless milestone-authorized in `v2025.09+`

---

Acknowledged by: System GPT  
Program Version: `v2025.05-governance-hardened`
