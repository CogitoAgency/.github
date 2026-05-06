<p align="center">
  <img src="Assets/banner.svg" alt="Cogito Agency — The OS for AI-native businesses" width="100%">
</p>

<div align="center">

[cogito.cv](https://cogito.cv) &nbsp;·&nbsp; [Breathe](https://cogito.cv/breathe) &nbsp;·&nbsp; [Careers](https://cogito.cv/careers) &nbsp;·&nbsp; [foundry@cogito.cv](mailto:foundry@cogito.cv)

</div>

---

We build the operating system for small businesses. Hair salons. Restaurants. Auto shops. Tax preparers. Tutoring centers.

These businesses are the heartbeat of every neighborhood, operating in every language — yet the tech industry has historically overlooked them. If the people building tools have never sat in that waiting room, or translated for their parents at a government office — how would they know what to build?

We are changing that. And we didn't build a product to do it. **We built the factory that builds the product.**

---

## The Loop

Traditional SaaS freezes when a bug hits — someone writes a ticket, a developer fixes it, a PM prioritizes it. That's a treadmill, not a moat.

Our platform reads its own error logs, writes its own patches, and votes on its own improvements — continuously, autonomously, at no marginal cost.

```
SMB Customer Usage
    → Prometheus signal (tool errors · latency · recipe failures)
    → SignalGoalInjector → GoalEngine (priority queue)
    → DarkFactory (LLM proposes patch → PatchSandbox validates)
    → 5 dry-run passes → Parliament (LLM council, ≥4/6 votes required)
    → Auto-merge to main → Weekly release → Smarter platform
```

Every Sunday at 00:00 UTC the platform ships a version of itself that is measurably better than seven days ago — without a human touching a keyboard.

---

## 🛠 What we ship

### 🌐 Free & Open Source

- **[Breathe Lite](https://github.com/CogitoAgency/breathe-lite)** — Free, open-source MCP server for AI-native developers. Persistent memory, hierarchical task management, autonomous workflows.
- **[GhostUI](https://github.com/CogitoAgency/GhostUI)** — UI toolkit for LLM-assisted Swift and iOS development.
- **[Machine Setup](https://github.com/CogitoAgency/machine-setup)** — One script. Fresh Mac to fully loaded AI dev machine. Claude Code, Gemini, Ollama, Node, Python, Go.

### 🍎 macOS Applications

- **[Breathe](https://cogito.cv/breathe)** — Free macOS menu bar app and AI daemon. Connects every AI tool you use, runs the MCP server, manages the kernel seamlessly.
- **[BreathFlow](https://cogito.cv/breathflow)** — System-wide voice dictation for macOS developers (free with Breathe). WhisperKit on-device, 98ms latency, zero cloud dependencies. Hold `⇧⌘` anywhere — release to paste.

### 🏢 Platform & Commercial

- **Cogito** — Autonomous agent platform. Intent → swarm → shipped. Self-evolving via the DarkFactory loop.
- **SMB** (`$249/mo`) — Full business OS. Booking, CRM, payments, social, voice receptionist, finance — all AI-native and integrated.
- **Enterprise** — Self-hosted. RBAC, compliance, SCIM, SSO (OIDC). Your data, your servers.

---

## 🏗 The Stack

```text
Enterprise   (org learning, dark factory, parliament governance)
     ↓
Kernel       (intent → swarm, goals, daemon)          :3001
     ↓
Engine       (handlers, recipes, MCP tools)           :4567
```

*27 handler domains · 287 YAML recipes · 98 governance rules · 428 MCP tools*

---

## 🤝 We're Hiring

Every person we hire is a **Gentle UX Designer** and a power AI user. That is not just a role — it's the baseline.

We prefer immigrant families. If you grew up switching between languages at the dinner table, you already understand the nuance of the problems we are solving.

→ **[cogito.cv/careers](https://cogito.cv/careers)**
