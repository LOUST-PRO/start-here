# LOUST PRO: Start Here

Welcome to the **LOUST PRO** engineering organization. This repository serves as the central handbook for collaboration, technical posture, and architectural discipline across all our projects.

## Collaboration & Pull Requests

Whether you are contributing to our open-source tools (like SnapPipe, TaxonRouter, NetBoozt) or part of our closed-source B2B enterprise pods, we maintain a strict code-quality and workflow standard:

1. **Sandboxed First:** All modifications, AI-agent operations, and build-steps must run locally in a sandboxed stage before proposing upstream Pull Requests. 
2. **Reviewable Audit Trails:** We consider feedback as a two-way loop. If you are opening an issue, bring a reproducer and a minimum-scope patch. We prioritize signal over volume.
3. **Declarative Configuration:** We favor YAML/TOML over complex API ingestions for community configuration (e.g., LZT-Developers). Keep it declarative.

## Development Pipeline & Agentic Workflow

LOUST PRO operates heavily on an **AI-Native Engineering Pipeline**, utilizing autonomous agents (Antigravity IDE, Claude, Gemini) embedded deeply into the development lifecycle via the **Model Context Protocol (MCP)**.

When working with our codebases, agents and operators must adhere to these directives:
- **No Direct Upstream Pushes:** Agents must operate locally and propose PRs or commits for operator review.
- **Context Compaction:** Follow the *Deterministic Sovereign RAG* spec. Do not rely on web-search hallucination; rely on the local deterministic graph and grounded context.
- **Security Scanners:** Tools like `storage-mountguardian` and our internal SAST sidecars are active. Never bypass the security review chain.

## Deterministic Sovereign RAG Spec

Our internal data pipelines, knowledge graphs, and LLM hooks align with our ArXiv preprint specs. For researchers looking to integrate or collaborate, please review the [deterministic-sovereign-rag](https://github.com/LOUST-PRO/deterministic-sovereign-rag) repository.

---

> If you are a developer looking to join our community directory, head over to **[LZT-Developers](https://github.com/LOUST-PRO/LZT-Developers)** and submit your profile!
