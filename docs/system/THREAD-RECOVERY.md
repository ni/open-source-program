# THREAD-RECOVERY.md

This file defines recovery rules for GPT threads under the NI Open Source Program.

---

## 🔁 When Recovery Is Allowed

A thread may be restarted if:
- It was marked as `retired` or `idle`
- Its last milestone was committed
- No other GPT is assigned to the same thread ID

---

## 📘 Recovery Options

| Recovery Type | Description |
|---------------|-------------|
| Resume | GPT instance reclaims its own thread ID |
| Fork | New thread ID is created using previous thread's history |
| Proxy | A different GPT executes remaining milestones on behalf of a retired thread |

---

## 🧾 Governance Requirements

- All recoveries must be milestone-bound
- `THREAD-ID-REGISTRY.yml` must show `resumed_by` or `fork_of`
- `THREAD-TRANSFER.md` must declare the transition
- `GOVERNANCE-THREADS.md` must assign the active GPT

---

## 🔒 Restrictions

- No auto-recovery without milestone
- Retired threads may not be reactivated unless `THREAD-RETIREMENT.md` permits it
- All resumed threads must inherit Ideal Execution Mode

---

Program Version: v2025.05-governance-hardened  
Maintained by: Program Coordinator GPT
