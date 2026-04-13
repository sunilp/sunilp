# Sunil Prakash

**Enterprise AI & Platform Architecture Leader** for regulated financial services. Building production AI systems, governance frameworks, and trust infrastructure.

Published research · book · IETF draft · open-source protocols, runtimes, and tooling · enterprise architecture leadership

---

### The Trust Stack for Multi-Agent AI

My research addresses a structural gap: multi-agent AI systems have no standard for identity, delegation, or provenance. I designed a layered trust stack to solve this:

```
 Research          Specifications         Implementations        Guides
 ────────          ──────────────         ───────────────        ──────
 ┌─────────────┐   ┌──────────────┐   ┌──────────────────┐   ┌─────────────┐
 │ Agent        │   │ AIP Spec     │   │ aip (Rust+Python)│   │ Agentic AI  │
 │ Identity     │──▶│ IETF Draft   │──▶│ PyPI packages    │──▶│ for Serious │
 │ (arXiv)      │   │              │   │ Framework addons │   │ Engineers   │
 └─────────────┘   └──────────────┘   └──────────────────┘   └─────────────┘
 ┌─────────────┐                      ┌──────────────────┐
 │ Provenance   │                      │ ldp-protocol     │
 │ Paradox      │─────────────────────▶│ (Rust)           │
 │ + LDP (arXiv)│                      │                  │
 └─────────────┘                      └──────────────────┘
 ┌─────────────┐
 │ DCI:         │
 │ Collective   │   Reasoning layer for multi-agent deliberation
 │ Reasoning    │
 └─────────────┘
```

Each layer solves a different problem: AIP handles *who is this agent and what can it do*, LDP handles *how do agents route and attest provenance*, DCI handles *how do agents reason together*. These ideas flow from protocol research into practical runtimes and developer tooling. The book covers how to build, evaluate, and govern all of it in production.

### Research

| Layer | Paper | Link |
|-------|-------|------|
| **Identity** | AIP: Verifiable Delegation Across MCP and A2A | [arXiv:2603.24775](https://arxiv.org/abs/2603.24775) |
| **Provenance** | The Provenance Paradox in Multi-Agent LLM Routing | [arXiv:2603.18043](https://arxiv.org/abs/2603.18043) |
| **Protocol** | LDP: Identity-Aware Protocol for Multi-Agent Systems | [arXiv:2603.08852](https://arxiv.org/abs/2603.08852) |
| **Reasoning** | DCI: Structured Collective Reasoning with Typed Acts | [arXiv:2603.11781](https://arxiv.org/abs/2603.11781) |

IETF Internet-Draft: [draft-prakash-aip-00](https://datatracker.ietf.org/doc/draft-prakash-aip/)

### Book

**[Agentic AI for Serious Engineers](https://sunilprakash.com/agentic-ai/)** — When to use agents and when not to. Evaluation, hardening, governance, and the production reality most teams discover too late. [Amazon](https://www.amazon.com/dp/B0GVG6848F) (paperback & Kindle) | [Code companion](https://github.com/sunilp/agentic-ai)

### Selected Repositories

| Repository | What it solves |
|---|---|
| [`aip`](https://github.com/sunilp/aip) | Verifiable identity and scoped delegation for AI agents across MCP and A2A (Rust + Python, PyPI) |
| [`ldp-protocol`](https://github.com/sunilp/ldp-protocol) | Identity-aware routing and provenance for multi-agent systems (Rust, crates.io) |
| [`ai-governance-framework`](https://github.com/sunilp/ai-governance-framework) | 50+ governance documents across 8 domains and 8 jurisdictions for regulated AI |
| [`enterprise-rag-bench`](https://github.com/sunilp/enterprise-rag-bench) | RAG patterns benchmarked for enterprise: chunking, retrieval, eval harness, guardrails |
| [`enterprise-genai-platform`](https://github.com/sunilp/enterprise-genai-platform) | Reference architecture for LLM applications in banking |

### Background

19 years in enterprise technology. VP at a global bank leading cross-location AI and platform architecture. Former Chief Scientist at an AI startup. Executive MBA (ISB), M.Tech in Enterprise Analytics (NUS).

[sunilprakash.com](https://sunilprakash.com) | [Google Scholar](https://scholar.google.com/citations?user=RdrGjZQAAAAJ) | [LinkedIn](https://www.linkedin.com/in/sunilprakash)

---

<sub>sunil@sunilprakash.com</sub>
