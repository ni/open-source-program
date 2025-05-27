# MILESTONE-2025-06.6 — Recognition Nomination Bot Trigger Model

> 🧠 This milestone defines safe, traceable triggers for nominating contributors to badge eligibility under the NI Open Source Program.

---

## 🔁 Allowed Nomination Channels

- GitHub Discussions with tags such as `badge-nomination`
- Issue templates titled "Badge Nomination Request"
- Comments containing `#nominate-badge` on eligible PRs or test issues

---

## 🔒 Constraints

- ❌ No scoring or CEU logic may run
- ❌ No GitHub Actions may apply labels or generate exports
- ✅ All nominations must be manually reviewed and milestone-logged

---

## 🧠 GPTs Allowed to Process

| GPT Thread | Role |
|------------|------|
| Recognition GPT | May surface nominations to dashboards |
| System GPT | May log milestones and nominations |

---

## 🧾 Notes

This milestone prepares the nomination path for:
- 🧪 Test Coordinator
- ⭐ Top Contributor
- 🧠 SteerCo Nominee

All badges must still be approved by a human. No automation has been authorized under program version `v2025.05-governance-hardened`.
