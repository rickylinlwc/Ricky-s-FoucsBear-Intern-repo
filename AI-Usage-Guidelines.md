### 1) When should I use AI vs rely on my own skills?
**Good times to use AI**
- Drafting: documentation, summaries, checklists, PR descriptions
- Learning support: explaining concepts, proposing investigation steps, generating query skeletons
- Refactoring text: grammar/clarity improvements for reports (after removing sensitive info)

**When I should rely on my own skills**
- Any decision that affects security posture, privacy, or production systems
- Declaring severity/impact of an incident
- Approving changes without reviewing and testing
- Anything involving sensitive/confidential data that cannot be safely redacted

---

### 2) How can I avoid over-reliance while still benefiting?
- Use AI as a **second pass** (after I attempt my own solution first)
- Require myself to explain "why this is correct" in 2-3 sentences
- Keep a short "lessons learned" note after each task (what I learned without AI)
- Always test/verify: no copy-paste into production without review

---

### 3) Steps I will take to ensure data privacy when using AI tools
- Redact and minimise: use the smallest, safest amount of info possible
- Never paste secrets/PII/internal incident content into AI prompts
- Use company-approved tools only (if policy requires)
- Prefer summaries over raw logs/screenshots
- Store outputs in appropriate locations (repo docs/private docs), not public channels

---

## 🛠️ Task

### 1) One task I improved using an AI tool
Task: Draft a clear weekly progress update for my internship (what I did, what's next, blockers).
AI tool used: ChatGPT
What I asked the AI to do (prompt summary): Turn my messy bullet notes into a short, professional update with Done / Next / Blocked, and suggest a clearer order.

### 2) Did the AI output require editing or fact-checking?
Yes

What I changed after reviewing:
- Rewrote a few sentences to match my real work (removed features/tasks I didn't actually complete).
- Simplified the wording and added exact dates + repo file names so it was accurate and easy to verify.


### 3) One best practice I will follow at Focus Bear
**Best practice:** I will never enter secrets, user-identifying info, or internal incident details into AI tools.  
If I need help, I will redact and summarise first, and I will validate outputs against primary sources before using them.
