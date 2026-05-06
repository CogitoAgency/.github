<p align="center">
  <img src="Assets/banner.svg" alt="Cogito Agency — The OS for AI-native businesses" width="100%">
</p>

<div align="center">

[cogito.cv](https://cogito.cv) &nbsp;·&nbsp; [Breathe](https://cogito.cv/breathe) &nbsp;·&nbsp; [Careers](https://cogito.cv/careers) &nbsp;·&nbsp; [foundry@cogito.cv](mailto:foundry@cogito.cv)

</div>

---

## The Problem

There are 33 million small businesses in the United States. Hair salons. Restaurants. Auto shops. Tax preparers. Tutoring centers. The heartbeat of every neighborhood — operating in every language, built by immigrants and families, funded by craft and stubbornness.

They are also the most underserved businesses in technology. The software industry built tools for companies with tech teams. These businesses don't have tech teams. They have one person doing everything — and when they're with a client, the phone rings. When the phone rings, they miss the booking. When they miss the booking, they lose $80. Multiplied across a year, it's thousands of dollars in invisible losses that no product on the market was ever designed to recover.

We are building the operating system that fixes this — not by replacing these owners, but by giving them an AI that works the way they do: in their language, learning their patterns, getting better every week.

---

## What We Built

**Cogito SMB** is a full business OS for small operators: AI receptionist, online booking, client CRM, payments, SMS/email automation, social media scheduling, and a business website — all AI-native, all integrated, one monthly fee, no setup required.

Tell it what your business does. It adapts. A client books → AI sends the confirmation. A repeat client calls → AI knows their name and last appointment. The business owner just shows up and works.

The platform speaks English, Spanish, Chinese, and Portuguese out of the box because the owners we're building for grew up in more than one language.

---

## How It Stays Ahead

Traditional software freezes when a bug hits — someone files a ticket, a developer fixes it eventually, a PM decides whether it's a priority. That cycle takes weeks. At 33 million businesses, that's not a product problem. That's a structural one.

We solved it at the architecture level. Cogito reads its own performance data, proposes its own improvements via LLM, validates them through a sandboxed test harness, and passes them through a governance council of six models before anything touches production. No human required.

```
Live usage signals
  (tool errors · missed bookings · recipe failures · customer outcomes)
         ↓
  GoalEngine: priority queue built from real signal
         ↓
  DarkFactory: LLM proposes patch → sandbox validates (5 dry-run passes)
         ↓
  Parliament: 6-model council, 4/6 votes required to merge
         ↓
  Auto-merge → nightly release → measurably better platform
```

Every night the platform ships a version of itself that is better than the night before. The longer it runs on real businesses, the more precisely it learns what small business owners actually need — and the harder it becomes for a competitor starting from scratch to catch up.

---

## The Stack

```
Enterprise   org-level evolution · parliament governance · compliance · SCIM/SSO
     ↓
Kernel       intent → swarm dispatch · goal engine · daemon          :3001
     ↓
Engine       MCP tool handlers · YAML recipes                        :4567
     ↓
Products     SMB · Breathe · AetherCloud Console
```

28 handler domains · 287 YAML recipes · 98 governance rules · 428+ MCP tools · 5,800+ automated tests

---

## Products

**Breathe** — Free macOS daemon and MCP server. Connects all AI tools, manages the local kernel, stores memory in a searchable graph. Free forever.

**SMB ($249/mo)** — Full business OS. Booking, CRM, payments, voice receptionist, social scheduler, invoicing, website. One price, everything on, no per-seat fees.

**Enterprise** — Self-hosted. RBAC, audit trails, SCIM directory sync, OIDC/SSO (Okta, Google, Azure AD, Auth0). Your data, your infrastructure.

---

## We're Hiring

Every person we hire is a **Gentle UX Designer** — someone who has personally navigated the gap between technology and the communities we serve. If you grew up translating for your parents at a government office, you already understand the problem better than most PMs at a FAANG company.

→ **[cogito.cv/careers](https://cogito.cv/careers)**