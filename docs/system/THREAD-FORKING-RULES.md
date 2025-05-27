# THREAD-FORKING-RULES.md

This file defines governance rules for creating new GPT threads by forking or resuming existing thread IDs.

---

## ✅ Forking a Thread

A thread may be forked when:
- Its milestone range has closed
- Its scope needs to be extended or divided
- The original GPT has retired

Forked threads must:
- Get a new `thread_id` from `THREAD-ID-GENERATOR.md`
- Be milestone-declared
- Reference the source thread in `THREAD-TRANSFER.md`

---

## 🔄 Resume Rules

A thread may be resumed if:
- It was paused or idle
- It has not been replaced or retired
- A new GPT has authority via milestone

---

## 🔐 Trace Requirements

| Log | Purpose |
|-----|---------|
| `THREAD-ID-REGISTRY.yml` | Register the new thread ID |
| `GOVERNANCE-THREADS.md` | Declare execution scope |
| `THREAD-TRANSFER.md` | Log the fork or reassignment |
| `MILESTONE-*.md` | Bind the fork to a program milestone |

---

Version: v2025.05-governance-hardened
Approved by: Program Coordinator GPT
