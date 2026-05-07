<p align="center">
  <img src="Assets/banner.svg" alt="Cogito — The self-evolving business OS" width="100%">
</p>

<div align="center">

[cogito.cv](https://cogito.cv) &nbsp;·&nbsp; [Breathe](https://cogito.cv/breathe) &nbsp;·&nbsp; [Careers](https://cogito.cv/careers) &nbsp;·&nbsp; [foundry@cogito.cv](mailto:foundry@cogito.cv)

</div>

---

> *四两拨千斤 — four ounces moves a thousand pounds.*
> Defeat force not by matching it, but by redirecting it.

Most software companies scale by adding engineers. We built a system that doesn't need to.

Cogito is an AI engineering system that designs, ships, and continuously improves software products — autonomously. It observes real usage, identifies what needs to change, reasons about how to change it, validates the change in isolation, and deploys nightly. A small founding team. A platform that compounds every 24 hours.

The first product we are proving this system on is **Cogito SMB**: a full operating system for small businesses — the hair salons, restaurants, auto shops, and tutoring centers that are the backbone of every neighborhood and the most underserved market in enterprise software. SMB is a use case. The system is the company.

---

## The Engineering System

The core is a closed feedback loop that treats the product as a living artifact — observable, improvable, and self-correcting.

```
Real usage signal (failures · drop-offs · latency · outcomes)
           ↓
     Goal engine — what matters, ranked by customer impact
           ↓
     Proposal — LLM drafts a scoped, typed improvement
           ↓
     Validation — sandboxed execution, regression suite
           ↓
     Governance — multi-model council, supermajority required
           ↓
     Deployment → measurement → signal feeds back in
```

Nothing ships without passing validation. Nothing stays shipped without being measured. The loop is not a cron job — it is the primary development process.

This is the hard problem we are working on: not building a chatbot, not wrapping an API. Building a system that can reason about its own behavior, propose correct improvements under uncertainty, and govern its own output quality well enough that humans can trust the result.

---

## The Use Case: SMB

33 million small businesses in the US spend an estimated **$500B/year** on admin labor and software combined. Most are still running on group texts, paper ledgers, and Square. The tools that exist were built for companies with IT departments. These businesses do not have IT departments.

**Cogito SMB** gives a small business owner a complete operating system: AI receptionist, online booking, client CRM, payments, SMS and email automation, social media, invoicing, and a business website — all integrated, all AI-native, one monthly price, no setup required.

It works in English, Spanish, and Chinese because the owners we are building for grew up navigating more than one language.

Every interaction — a booking confirmed, a call handled, a follow-up sent — is a training signal that flows back into the engineering system. The product gets more accurate every week, not because engineers manually tune it, but because the loop runs.

---

## Architecture

| Layer | What it does |
|---|---|
| **Intelligence** | Observes the full stack. Proposes, validates, and governs its own improvements. |
| **Kernel** | Persistent AI reasoning core — intent understanding, goal management, agent coordination. |
| **Engine** | Execution layer — the domain tools and automated workflows that run daily operations. |
| **Products** | What customers touch — built and continuously evolved by the layers above. |

The intelligence layer sits above everything and treats the entire system as something it can read, reason about, and rewrite. It is not a feature bolt-on. It is the architecture.

---

## Why Now

Large language models crossed a threshold in 2024: they can now reason about code, propose changes, and evaluate their own output with enough reliability to close a feedback loop without constant human supervision. We are building the engineering system that operationalizes this — not as a research project, but as a commercial product running on real customers.

The window is open. It will not stay open long.

---

## For Engineers

If you have ever felt the frustration of building something that stops improving the moment you stop touching it — this is the opposite of that.

The engineering problems here are real: how do you validate that an autonomously proposed change is safe? How do you build a governance layer that doesn't block good changes while blocking bad ones? How do you measure intelligence in a system that rewrites itself? How do you build trust between an autonomous system and the humans who depend on it?

These are not toy problems. We are solving them in production, on a live product, with real customers.

Small team. High ownership. Grounded in research — Hinton, Vaswani, Silver, Chollet — not buzzwords.

---

## For Investors

- **Market**: 33M US small businesses, $500B/year addressable spend, no credible AI-native competitor
- **Defensibility**: Every week of customer usage makes the model more accurate for that vertical. A later entrant starts at zero signal.
- **Leverage**: The same engineering system that builds SMB can be directed at any domain. SMB is the beachhead.
- **Team**: Immigrant founders who grew up inside the problem. Not building for a market they read about.

---

## We're Hiring

We hire **Gentle UX Designers** — a standard, not a role. Everyone here, regardless of function, has personally navigated the gap between technology and the communities we serve. If you grew up translating for your parents, you already understand the problem better than most people with the right résumé.

We value craft, directness, and the willingness to build things that have never existed before.

→ **[cogito.cv/careers](https://cogito.cv/careers)**