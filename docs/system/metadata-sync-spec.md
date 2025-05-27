# 🔄 Contributor Metadata Sync Specification

> This file documents how contributor metadata from the NI Open Source Program may be safely used in downstream dashboards, documentation, and internal systems.

---

## 🧾 Fields Available for Sync

| Field | Description |
|-------|-------------|
| `handle` | GitHub handle (e.g. `@crossruls`) |
| `opt_in` | Contributor confirmed consent |
| `validated` | CLA or DCO status confirmed |
| `pr_url` | GitHub PR that was merged |
| `repo` | The NI-owned repository where contribution occurred |
| `point_value` | Manually assigned based on milestone logic |
| `badge_considered` | Badge surfaced during nomination phase |
| `milestone` | Milestone that governs the contribution |

---

## 📘 Allowed Use Cases

- Internal dashboards (Education Services, Legal, Training)
- Docs sites (e.g. `CONTRIBUTORS.md`, contributor cards)
- Contributor self-check tools (future GPTs)
- Certification readiness reports

---

## 🔐 Governance Rules

- ❌ No automation or scoring may derive from this file
- ✅ All uses must be traceable to:
  - A public milestone
  - An opt-in signal
  - A validated export file

---

Program Version: `v2025.05-governance-hardened`  
Milestone: `v2025.10.3`  
Maintainer: System GPT (retired after `v2025.08.5`)
