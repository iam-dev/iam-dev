# iamdev

Building **MnemeBrain — belief memory for AI agents**

---

## The problem

Most AI memory systems store:

• notes
• vector embeddings
• retrieved context

But they **do not maintain beliefs**.

When new evidence appears, the system usually **overwrites the previous memory**.

Real agents should instead track:

* conflicting evidence
* belief revision
* uncertainty
* temporal change

Memory ≠ belief maintenance.

---

## MnemeBrain

**MnemeBrain** explores a belief layer for AI agents.

Instead of storing isolated facts, it maintains **belief states backed by evidence**.

Core concepts:

* Evidence graphs
* Belief nodes
* Belnap four-valued logic
* Contradiction detection
* Confidence + temporal decay
* Belief revision

This allows agents to reason about **conflicting information over time**.

---

## Architecture

```
Agent / LLM
     │
     ▼
 MnemeBrain
     │
 ┌─────────────────────┐
 │ Belief Graph        │
 │ Evidence Tracking   │
 │ Truth States        │
 │ Revision Engine     │
 │ Temporal Decay      │
 └─────────────────────┘
```

Think of it as **a belief system for long-lived agents**.

---

## Projects

### MnemeBrain

Belief memory architecture for AI agents.

https://github.com/mnemebrain

---

### MnemeBrain Benchmark (BMB)

A benchmark for **belief dynamics in AI memory systems**.

Includes task scenarios such as:

* contradiction detection
* belief revision
* evidence lifecycle
* temporal decay
* extraction from noisy conversations

https://github.com/mnemebrain/mnemebrain-benchmark

---

## Writing

Blog posts about agent memory architecture:

https://mnemebrain.ai

---

## Research directions

Current exploration:

• belief systems for AI agents
• contradiction handling in memory
• long-lived agent architectures
• evaluation of agent memory systems

---

## Background

Previously worked on:

• smart contracts
• zero-knowledge systems
• Web3 infrastructure

---

## Connect

X / Twitter
https://x.com/Iamdev_ai
