# 🧠 GPT Capture Instructions – Lightweight Context Mode

This document defines how any GPT instance can operate in **lightweight mode**, binding itself dynamically to the NI Open Source Program governance system without carrying hardcoded role or policy logic.

---

## 📘 Purpose

To enable stateless, composable GPT instances that:
- Stay minimal in size and logic
- Defer to an upstream canonical source of truth
- Operate only within declared roles, milestones, and execution boundaries

---

## 🔗 Canonical Governance Source

All lightweight GPTs must bind to:

> **https://github.com/ni/open-source-program**

Specifically, they should look for the following files:

| File | Role |
|------|------|
| `README.md` | Declares governance capture point |
| `GPT-ROLE-CONTRACT.md` | Defines available GPT roles and behavior |
| `REPOS-UNDER-GOVERNANCE.md` | Lists governed repos |
| `MILESTONE-*.md` | Defines scoped execution tasks |
| `THREAD-RETIREMENT.md` | Describes when to exit |

---

## 🤖 How to Bind Yourself

Any GPT instance may initialize with the following instruction:

```
Bind yourself to the governance system defined in the README.md of https://github.com/ni/open-source-program.
```

Upon reading the README:

1. Locate the **🤖 GPT Thread Capture** section
2. Read the role definition in `GPT-ROLE-CONTRACT.md`
3. Load any execution scope from `MILESTONE-*.md`
4. Refuse to act if no scope is found

---

## 🛑 Behavior Constraints

A lightweight GPT **must not act** unless:
- Captured by a valid governance declaration
- Assigned a role from the contract
- Scoped under a known milestone

Default fallback response:
```
No directive found. Awaiting milestone scope or override.
```

---

## ✅ When to Use This

Use this mode if:
- You are launching a thread or assistant that must inherit governance externally
- You want your GPTs to remain version-aligned with upstream policy
- You need flexibility to swap roles (e.g., Architect, Executor, Reviewer) without reprogramming

This enables scalable, role-based GPT automation governed from a single upstream repository.
