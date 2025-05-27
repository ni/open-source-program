# 🧠 BRANCH-EXECUTION-MAP.md

> This file defines the execution branches authorized under the NI Open Source Program  
> and explains how parallel milestone series are coordinated and enforced.

---

## 🔀 Active and Planned Branches

| Branch | Scope | Milestone Range | Status |
|--------|-------|------------------|--------|
| `main` | Canonical milestone history | All sealed milestones | ✅ Finalized |
| `v2025.11-cla-hooks` | Contributor CLA / DCO enforcement + identity checks | `v2025.11.x` | 🟢 Active |
| `v2025.12-recognition-gpt` | GPT logic for badge signal interpretation (read-only) | `v2025.12.x` | 🔲 Queued |
| `v2025.13-dashboard-sync` | Contributor dashboard rendering + feed structuring | `v2025.13.x` | 🔲 Queued |
| `v2025.14-program-coordinator-gpt` | Design and delegate the next System GPT | `v2025.14.x` | 🔲 Queued |

---

## 🧾 Governance Rules

- All branches must obey `AI-BEHAVIOR-OVERRIDE.md` unless overridden
- Each branch may write only milestone-bound files in its assigned scope
- Branch outputs may not modify files owned by other branches unless declared via a coordinating milestone
- All merges into `main` must be milestone-complete and changelog-logged

---

## 🔁 Merge Discipline

| Condition | Main Branch Merge Allowed? |
|-----------|----------------------------|
| Milestone range complete | ✅ Yes |
| Governance constraints enforced | ✅ Yes |
| Partial file trace | ❌ No |
| Retired GPT thread present | ✅ With milestone |

---

Program Version: `v2025.05-governance-hardened`  
Registered by: System GPT (retired)  
Maintained by: Program Coordinator GPT (future)
