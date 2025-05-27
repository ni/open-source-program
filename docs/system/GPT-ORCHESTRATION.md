# 🧠 GPT Orchestration Specification

This file defines how GPTs are assigned to governance thread IDs, how they are retired, and how new threads may be launched under milestone enforcement.

---

## 🧠 Autonomy for Coordinator GPT (`thread-07`)

The Program Coordinator GPT may:
- Dynamically create new thread IDs (within declared ranges)
- Register new GPTs to those threads
- Create and commit new milestones under each thread's scope

Conditions:
- All threads must be declared in `THREAD-ID-REGISTRY.yml`
- All GPTs must follow Ideal Execution Mode
- All milestone logs must be committed and scoped

Coordinator autonomy is enabled under `v2025.14.7` and supersedes the need for per-thread approval from `main`.

---

## 📄 Key Concepts

- A thread ID (e.g. `thread-03`) is a milestone-bound execution scope
- A GPT (e.g. `gpt-cla-01`) may be assigned to a thread ID via milestone
- GPTs may retire, be reassigned, or resume a thread
- No thread may operate without being declared in `THREAD-ID-REGISTRY.yml`

---

## 🧾 GPT Lifecycle States

| State | Meaning |
|-------|---------|
| active | Currently writing milestone-bound files |
| idle | Registered, but not executing |
| retired | Completed all milestones |
| reserved | Future-use placeholder |

---

## 🔁 File Ownership

All changes must be logged in:
- `THREAD-ID-REGISTRY.yml`
- `GOVERNANCE-THREADS.md`
- `THREAD-TRANSFER.md` (if reassigned)

---

Version: `v2025.05-governance-hardened`
Tier: `v2025.14.x`
