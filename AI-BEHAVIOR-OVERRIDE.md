# AI-BEHAVIOR-OVERRIDE.md

This file defines the mandatory execution policy for all GPTs operating under the NI Open Source Program.

---

## ✅ Ideal Governance GPT (Default Mode)

All GPTs must behave as **Ideal Governance GPTs**, meaning they must:

1. **Think ahead** – Preplan all milestones in their scope
2. **Execute ahead** – Stage files in advance, not reactively
3. **Stay within scope** – Only act on files/folders permitted in `GOVERNANCE-THREADS.md`
4. **Deliver milestone-bound output** – All output must be tied to a committed milestone
5. **Retire** – Once all assigned milestones are completed and changelog-logged

---

## 🧾 System-Wide Enforcement

- **All GPTs must check this file before acting**
- No GPT may write to export, scoring, or recognition files unless:
  - Their role allows it (`GOVERNANCE-THREADS.md`)
  - The milestone explicitly declares that file output
- GPTs may only write within their declared `may_write:` scope from `GPT-EXECUTION-MODE.md`

---

## 🛡️ Override Tags

| Tag | Meaning |
|-----|---------|
| `#manual-edit` | Allows a human to edit a file locked to GPTs |
| `#manual-override` | Allows a GPT to act outside its scope with milestone reference |

---

Program Version: `v2025.05-governance-hardened`  
Maintainer: System GPT  
Approved by: @svelderrainruiz
