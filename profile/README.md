<p align="center">
  <img src="Assets/banner.svg" alt="Cogito Agency — The OS for AI-native businesses" width="100%">
</p>

<div align="center">

[cogito.cv](https://cogito.cv) &nbsp;·&nbsp; [Breathe](https://cogito.cv/breathe) &nbsp;·&nbsp; [Careers](https://cogito.cv/careers) &nbsp;·&nbsp; [foundry@cogito.cv](mailto:foundry@cogito.cv)

</div>

---

## The Moat: A Platform That Rewrites Itself

Most SaaS companies ship code. We ship a platform that ships its own code.

Every night, Cogito reads its own performance data, proposes improvements via LLM, validates them through a sandboxed test harness, and passes them through a six-model governance council — with no human in the loop. The platform gets measurably smarter every 24 hours. The longer it runs, the wider the gap from anything a traditional engineering team could match.

```
Live Usage Signals
  (tool errors · latency · recipe failures · customer outcomes)
         ↓
  SignalGoalInjector → GoalEngine (priority queue)
         ↓
  DarkFactory: LLM proposes typed patch → PatchSandbox (5 dry-run passes)
         ↓
  Parliament: 6-model LLM council, ≥4 votes required to merge
         ↓
  Auto-merge → nightly release → measurably better platform
```

**The compounding effect:** Each improvement increases the platform's ability to propose better next improvements. The kernel tracks its own intelligence across 10 dimensions — reasoning, tool selection, metacognition, recovery, memory coherence — and the score goes up every cycle. We call this the **Kernel Intelligence Score (KIS)**.

---

## Why This Is a Moat

| Traditional SaaS | Cogito |
|---|---|
| Engineers write patches in response to bugs | Platform detects, proposes, and merges its own patches |
| Feature velocity limited by headcount | Feature velocity scales with compute |
| Institutional knowledge walks out the door | Every decision is committed, versioned, and searchable |
| Roadmap driven by PM priority queues | Roadmap driven by live customer signal + governance rules |
| Churn is a lagging indicator | Churn risk surfaces as a model signal before the customer leaves |

The business that runs on Cogito gets a compounding return: every week, the AI that runs their operations gets better at their specific business context — booking patterns, client preferences, seasonal load, language. That's not software. That's a trained asset.

---

## The Stack

```
Enterprise   org-level evolution, parliament governance, compliance, SCIM/SSO
     ↓
Kernel       intent → swarm dispatch, goals, daemon          :3001
     ↓
Engine       MCP tool handlers, YAML recipes                 :4567
     ↓
Products     SMB portal · Breathe · AetherCloud Console
```

**Scale today:** 28 handler domains · 287 YAML recipes · 98 governance rules · 428+ MCP tools · 5,800+ automated tests

The same kernel that powers a hair salon in the Mission can power a 200-person nonprofit or a multi-location franchise. The topology changes; the loop does not.

---

## Products

### Breathe — Free Developer Daemon
macOS menu bar app and MCP server. Connects all AI tools, manages the local kernel, stores memory in a searchable SQLite graph. Free forever.

### SMB — $249/mo Business OS
Booking · CRM · Payments · SMS/Email · AI Voice Receptionist · Social Scheduler · Finance · Google Presence. Every feature AI-native. One price, everything on. No per-seat fees.

### Enterprise — Self-Hosted
RBAC · Audit trails · SCIM directory sync · OIDC/SSO (Okta, Google, Azure AD, Auth0) · Per-org evolution isolation · Compliance dashboard (target: 100/100). Your data, your infrastructure.

---

## The Market We're Actually Addressing

The 33 million small businesses in the US spend an estimated **$500B/year** on software and admin labor combined — and most are still running on spreadsheets, group texts, and Square. They don't need another point solution. They need an OS.

We are building that OS for the neighborhoods most software companies have never visited — immigrant-owned, multilingual, cash-and-relationship-driven. That is not a charity thesis. It is an untapped market with high retention, strong word-of-mouth, and zero competitive pressure from incumbents.

---

## We're Hiring

Every person we hire is a **Gentle UX Designer** — someone who has personally navigated the gap between technology and the communities we serve. If you grew up translating for your parents at a government office, you already understand the problem better than most PMs at a FAANG company.

→ **[cogito.cv/careers](https://cogito.cv/careers)**
