# 4x4 Use Cases

Beyond weekly planning, the 4x4 framework surfaces surprising value in other contexts. This document captures those patterns.

---

## 1. Two-Way Onboarding

**Scenario:** A new team member (or contractor, or AI assistant) joins a project.

At the end of 2-3 days (or even a week), hand them a blank [4X4.md](4X4.md) and ask them to fill it out based on what they know so far.
 
**What it reveals:**
- **For the new person** — it forces fast learning. Compressing the project into 4 strategic bets + 4 concrete weekly moves exposes gaps in their understanding immediately. If they can't fill those slots confidently, they know exactly what to ask about next.
- **For existing stakeholders** — it's a 60-second alignment check. Scan the filled-out doc and see whether the author's mental model matches reality: what they think matters, what they think is urgent, what they think success looks like, and what they're choosing to ignore.

**The forcing function:** The 4-item constraint creates productive tension. If someone tries to sneak in 12 priorities, you know they're not actually prioritizing.

**Review it in a short sync. Ask 3 questions:**
1. "What did you exclude and why?"
2. "Which item changes if an urgent bug hits?"
3. "What does 'done' mean for item #1 this week?"

---

## 2. LLM-Assisted Self-Population

**Scenario:** You're working with an AI coding assistant (Copilot, Claude, Cursor, etc.) on a project.

Ask the LLM to fill out a blank 4X4.md based on the codebase, open issues, and recent PRs. Then review what it produced.

**What it reveals:**
- Whether the LLM actually understands the project's priorities or is just summarizing file names.
- Misalignments between what the codebase suggests is important and what your team actually cares about.
- A useful first draft you can edit in 2 minutes instead of writing from scratch.

**Example prompt:**
> "Based on the open GitHub issues, recent commits, and README, fill out a 4X4.md for this project. What are the 4 most important strategic goals and 4 tasks we should tackle this week?"

**Tip:** After 3-4 iterations on a project with an LLM, ask it to fill out the 4X4. The quality of its output is a proxy for how well it has absorbed context.

---

## 3. Stakeholder Check-Ins

**Scenario:** You need to update a non-technical stakeholder (founder, PM, client) without a 30-minute meeting.

Send them your current 4X4.md. It answers their real questions — *what are you working on, what got done, what's blocked, and what did you learn* — in a format they can scan in under a minute.

**Why it works:** Stakeholders don't need Jira boards or sprint burndowns. They need signal. The 4-item constraint strips away noise and gives them exactly that.

---

## 4. Sprint Retrospective Seed

**Scenario:** Your retros feel repetitive or shallow.

Pull the last 4 weeks of "Lessons Learned" sections from your 4X4 history. Patterns will jump out — recurring blockers, repeated process failures, wins that never got reinforced.

**Why it works:** Retro insights captured in the moment (Section 4) are more honest than what people recall in a meeting two weeks later.

---

## 5. Interview / Trial Project Evaluation

**Scenario:** You're evaluating a candidate or contractor through a trial project.

Include a blank 4X4.md in the trial repo. Ask them to fill it out as part of their deliverable.

**What it reveals:**
- Can they identify what matters vs. what's just busywork?
- Do they think in terms of outcomes or just tasks?
- How do they frame tradeoffs and lessons learned?

**Tip:** It's a lightweight signal for strategic thinking that a code review alone won't surface. Look for candidates who ask about context before making recommendations.

---

## When NOT to Use the 4x4

The 4x4 Dashboard is powerful, but it's not a universal solution. Avoid these anti-patterns:

- **Don't replace detailed technical specs** — The 4x4 is for high-level priorities, not implementation details or architecture decisions.
- **Don't force it on teams with strong alignment** — If your team already has clear priorities and excellent communication, adding another artifact may create overhead without value.
- **Don't use it as a performance review tool** — The 4x4 is for team alignment and transparency, not individual evaluation. Using it for performance reviews will kill psychological safety.
- **Don't treat it as a contract** — Priorities shift. The 4x4 should be a living document that adapts to reality, not a rigid commitment that creates guilt when things change.
- **Don't skip the retrospective** — The "Previous Week" and "Lessons Learned" sections are where the real improvement happens. If you're only planning forward, you're missing half the value.

---

## Have a use case to add?

We'd love to hear how you're using the 4x4 Dashboard!

**Share your story:**
- Submit a PR to add your use case to this document
- Open an issue with your scenario and we'll help format it
- Tweet it with **#4x4clarity** and tag us — we'll add the best ones here

Visit [4x4clarity.com](https://4x4clarity.com) to learn more.

---

## License
This work is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) License. To view a copy of this license, visit [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/).

Copyright © 2026 Hypercart DBA Neochrome, Inc. | 4x4Clarity.com
