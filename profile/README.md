<p align="center">
  <img src="Assets/banner.svg" alt="Cogito Agency - local AI tools for agent builders" width="100%">
</p>

<p align="center">
  <a href="https://cogito.cv"><b>cogito.cv</b></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://cogito.cv/breathe">Breathe</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://cogito.cv/breathflow">BreathFlow</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://cogito.cv/keepr">Keepr</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="mailto:foundry@cogito.cv">foundry@cogito.cv</a>
</p>

<h1 align="center">Cogito</h1>

<p align="center">
  <b>We build software that rewrites itself.</b>
</p>

<p align="center">
  The codebase is a genome. Evolution cycles observe fitness, generate mutations,
  select survivors, and ship improvements autonomously, continuously.
</p>

<p align="center">
  Software rots. We fight entropy at the source.
</p>

<p align="center">
  <code>Evolve</code>
  <code>Kernel</code>
  <code>Engine</code>
  <code>MCP handlers</code>
  <code>YAML recipes</code>
  <code>governance</code>
</p>

<p align="center">
  <img src="Assets/active-products.svg" alt="Cogito active products: Breathe, BreathFlow, Keepr, Evolve, and Engine" width="100%">
</p>

---

## Products

Three macOS apps. All local. No accounts.

| Product | What it does |
|---|---|
| [**Breathe**](https://cogito.cv/breathe) | Local memory for Claude Code. Auto-captures every session via lifecycle hooks. Surfaces patterns. Restores context across projects. |
| [**BreathFlow**](https://cogito.cv/breathflow) | System-wide voice-to-text. Hold a hotkey, speak, release. Text pasted into any app. On-device WhisperKit, no cloud. |
| [**Keepr**](https://cogito.cv/keepr) | Relationship memory. Scans iMessage and Contacts locally, finds the people you went quiet with, opens the thread when it is time. |

---

## Platform

The products run on an agentic harness called Evolve, a self-improving loop that scans a codebase once, builds a specialized agent team, and improves it through observed outcomes.

| Layer | Role |
|---|---|
| **Kernel** | Capability decomposition, agent routing, arbitration. |
| **Engine** | 40+ MCP tool handlers, 400+ YAML recipes, governance rules. |
| **Breathe** | Local MCP daemon and memory graph at `localhost:4567`. |

The platform learns what each product needs, then builds the intelligence to build it.

---

## Stack

```mermaid
flowchart TD
    A["Product surfaces<br/>macOS · SwiftUI · TypeScript"] --> B["Breathe<br/>trajectory memory · evidence chain"]
    B --> C["Evolve<br/>active inference loop"]
    C --> D["Kernel<br/>capability decomposition · arbitration"]
    D --> E["Engine<br/>MCP handlers · YAML recipes · governance"]
    E --> F["Mutations<br/>candidate patches · playbooks"]
    F --> G["Fitness signals<br/>tests · traces · outcomes"]
    G --> H{"Selection"}
    H -->|"survivor"| A
    H -->|"reject"| F
```

Think of the codebase like a little garden that can read its own weather.

The apps are the leaves you can touch. Breathe remembers the trajectory of what happened. Evolve builds a generative model of the work, then tries small mutations. Kernel decides which agents should help. Engine gives them tools, recipes, and governance. Tests and traces become fitness signals. Good changes survive. Bad changes go back into the playbook.

That is the research shape: active inference, explicit reasoning, rule induction, curriculum, evidence chains, and selection pressure, applied to software.

---

## Contact

<p>
  <a href="https://cogito.cv"><b>cogito.cv</b></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="mailto:foundry@cogito.cv"><b>foundry@cogito.cv</b></a>
</p>
