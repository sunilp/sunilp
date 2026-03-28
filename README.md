# Sunil Prakash

**Enterprise AI & Platform Architecture Leader**
Production AI systems, governance, and trust infrastructure for regulated financial services. VP at Deutsche Bank.

---

### Research

Trust infrastructure for multi-agent AI systems: identity, delegation, provenance, and collective reasoning.

**AIP: Agent Identity Protocol for Verifiable Delegation Across MCP and A2A** — [arXiv:2603.24775](https://arxiv.org/abs/2603.24775)
<br>A scan of ~2,000 MCP servers found all lacked authentication. AIP introduces Invocation-Bound Capability Tokens in compact (JWT) and chained (Biscuit) formats. 0.049ms verification (Rust), 100% rejection across 600 adversarial attacks, 0.086% overhead in real LLM agent chains. [`aip`](https://github.com/sunilp/aip)

**The Provenance Paradox in Multi-Agent LLM Routing** — [arXiv:2603.18043](https://arxiv.org/abs/2603.18043)
<br>Self-claimed quality routing performs worse than random when delegates inflate scores. Introduces delegation contracts, claimed-vs-attested identity, and typed failure semantics. Attested routing: d=9.51, p<0.001. [`ldp-research`](https://github.com/sunilp/ldp-research)

**LDP: An Identity-Aware Protocol for Multi-Agent LLM Systems** — [arXiv:2603.08852](https://arxiv.org/abs/2603.08852v1)
<br>Rich delegate identity cards, progressive payload modes, governed sessions, and trust domains for multi-agent delegation. 12x latency gains, 37% token reduction. [`ldp-protocol`](https://github.com/sunilp/ldp-protocol) · [`ldp-research`](https://github.com/sunilp/ldp-research)

**DCI: Structured Collective Reasoning with Typed Epistemic Acts** — [arXiv:2603.11781](https://arxiv.org/abs/2603.11781)
<br>Deliberative structure for multi-agent LLM reasoning: 4 archetypes, 14 typed epistemic acts, convergent flow algorithm. +0.95 over debate on non-routine tasks, 9.56 on hidden-profile (best in study). Honest result: 62x token cost, fails on routine decisions.

### Books

**[Agentic AI for Serious Engineers](https://sunilprakash.com/agentic-ai/)** — Open engineering guide to building reliable, evaluable, and production-grade AI agent systems. Covers agent architectures, tool use, multi-agent coordination, evaluation frameworks, human-in-the-loop design, and production deployment. Also available on [Amazon KDP](https://www.amazon.com/dp/B0F3YSM36M).

### Selected Repositories

| Repository | What It Does |
|---|---|
| [`aip`](https://github.com/sunilp/aip) | Agent Identity Protocol — verifiable, delegable identity for AI agents across MCP and A2A (Rust + Python) |
| [`ldp-protocol`](https://github.com/sunilp/ldp-protocol) | LLM Delegate Protocol — identity-aware communication for multi-agent systems (Rust reference implementation) |
| [`enterprise-rag-bench`](https://github.com/sunilp/enterprise-rag-bench) | RAG patterns benchmarked for enterprise: 5 chunking strategies, 5 retrieval patterns, evaluation harness, guardrails, observability |
| [`enterprise-genai-platform`](https://github.com/sunilp/enterprise-genai-platform) | Reference architecture for LLM applications in banking: chain routing, prompt registry, guardrails, eval pipelines, drift monitoring |
| [`applied-nlp-research`](https://github.com/sunilp/applied-nlp-research) | Production NLP from pre-LLM to post-LLM: capsule networks, BiLSTM-CRF, transformer NER, event-driven stream processing |
| [`ai-governance-framework`](https://github.com/sunilp/ai-governance-framework) | AI governance for regulated industries: risk assessment, model lifecycle, compliance mapping, responsible AI standards |
| [`reference-data-platform-gcp`](https://github.com/sunilp/reference-data-platform-gcp) | GCP data platform reference architecture: BigQuery, Dataflow, Composer, dbt, Data Vault 2.0 |

### Background

- **Deutsche Bank** — VP, Cloud & Platform Architecture (2021–present)
- **Halialabs** — Chief Scientist, AI & Platform Architecture (2018–2021)
- **Cognizant** — Technology Specialist / Software Architect (2012–2017)
- **Syntel** — Software Engineer / Project Lead (2007–2012)

**Education:** PGPMAX (Executive MBA), ISB · M.Tech Business Analytics, NUS · Google Cloud Professional Cloud Architect

### Writing

[sunilprakash.com](https://sunilprakash.com) — Technical writing on enterprise AI, RAG patterns, data architecture, and AI governance.

---

<sub>sunil@sunilprakash.com · [LinkedIn](https://www.linkedin.com/in/sunilprakash)</sub>
