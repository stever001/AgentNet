# AgentNet

**AgentNet is an open standard and reference architecture for publishing, resolving, and consuming authoritative machine-readable data for AI systems.**

It introduces a machine-first web layer built on JSON-LD, enabling AI agents to retrieve *grounded, provenance-aware, policy-constrained information* directly from publishers—without scraping, hallucination, or opaque intermediaries.

---

## Why AgentNet Exists

Modern AI systems rely heavily on probabilistic inference over untrusted or ambiguous data. This creates systemic problems:

- Hallucinations and unverifiable claims
- Loss of source authority and provenance
- No enforceable usage terms or attribution
- Inefficient retrieval (token waste, over-contextualization)
- No economic or governance layer for machine access

**AgentNet addresses this by defining a federated, standards-based system where:**

- Publishers declare authoritative facts in machine-readable form
- AI agents retrieve only what is explicitly published and permitted
- Provenance, versioning, and usage constraints are first-class
- Retrieval is deterministic, efficient, and auditable

---

## Core Concepts (High Level)

AgentNet is composed of four foundational elements:

1. **Nodes**  
   Publishers (organizations, creators, datasets, systems) that expose authoritative data.

2. **Capsules**  
   JSON-LD documents that encapsulate facts, metadata, provenance, and usage constraints.

3. **Resolvers**  
   Federated services that locate, validate, and return the appropriate capsule(s) for a given request.

4. **Registrars**  
   Services that manage identity, registration, and trust anchors for nodes and resolvers.

Together, these form a **machine-centric information layer** optimized for AI retrieval and reasoning.

---

## What This Repository Is

This repository is the **public front door** for AgentNet.

It contains:
- The authoritative AgentNet Standards (ANS)
- Conceptual and architectural documentation
- Reference materials and examples
- Governance and roadmap artifacts

This repo is intentionally **communicative and stable**.  
Active implementation code lives in related repositories.

---

## Repository Structure

```text
AgentNet/
├─ README.md                ← You are here
├─ standards/               ← AgentNet Standards (ANS)
│  └─ ANS-Core-v2.0.docx
├─ docs/                    ← Conceptual & architectural documentation
├─ examples/                ← Example capsules, requests, and responses
├─ press/                   ← One-pagers, fact sheets, media assets
├─ GOVERNANCE.md            ← Governance model (bootstrap)
├─ ROADMAP.md               ← Public roadmap
├─ LICENSE
├─ SECURITY.md
├─ CONTRIBUTING.md
└─ CODE_OF_CONDUCT.md

This structure is designed to support multiple audiences simultaneously:

- Standards readers should begin in /standards
- Architects and integrators should explore /docs
- Developers and evaluators should inspect /examples
- Press and partners may reference /press
- Contributors and stewards should review governance and policy documents at the root

The layout is intentionally conservative and explicit to ensure long-term clarity, stability, and ease of navigation.
```

## The AgentNet Standards (ANS)

The **AgentNet Standards (ANS)** define the normative rules of the AgentNet ecosystem.

- Architecture and terminology
- Capsule structure and requirements
- Resolver behavior and selection logic
- Provenance, trust, and governance principles
- Compliance and interoperability expectations

📄 **Start here:**  
`/standards/ANS-Core-v2.0.docx`

ANS Core v2.0 is **final and effective as of 2026-01-01**, superseding all prior drafts.

---

## Getting Started (5-Minute Orientation)

If you are new to AgentNet:

1. Read **ANS Core v2.0** (overview sections first)
2. Review `/docs/overview.md`
3. Inspect example capsules in `/examples/capsules`
4. Explore the reference resolver repository (linked below)

You do *not* need to run infrastructure to understand the system.

---

## Reference Implementations

AgentNet is a standard, not a single product.  
However, reference implementations exist to demonstrate compliance and feasibility.

Related repositories:
- **Reference Resolver:** implements capsule resolution, trust validation, and policy selection
- **Capsule Generator (experimental):** demonstrates automated capsule creation
- **Validator:** checks capsule conformance against ANS

Links are provided in `/docs/implementations.md`.

---

## Status & Maturity

- **Standards:** Stable (ANS Core v2.0)
- **Architecture:** Proven and tested
- **Reference Resolver:** Functional and compliant
- **Ecosystem:** Early, intentionally open

AgentNet is designed for **incremental adoption**—publishers and consumers can start small and expand.

---

## Governance

AgentNet is governed as an **open, federated standard**.

- No single resolver, registrar, or operator is required
- Governance roles are defined but initially unfilled
- Emergency changes require post-hoc disclosure
- Long-term stewardship is designed to be multi-stakeholder

See `GOVERNANCE.md` for details.

---

## Who Should Pay Attention

AgentNet is relevant to:

- AI platform builders and model providers
- Data publishers and content owners
- Enterprises concerned with AI grounding and provenance
- Infrastructure and tooling companies
- Regulators, standards bodies, and policy groups
- Investors evaluating foundational AI infrastructure

---

## Contributing

Contributions are welcome—but standards quality matters.

Please read:
- `CONTRIBUTING.md`
- `CODE_OF_CONDUCT.md`

Standards changes follow a structured review process.

---

## Security

If you discover a vulnerability or integrity issue related to AgentNet reference implementations, please follow the process in `SECURITY.md`.

---

## License

Unless otherwise noted, this repository is licensed under the terms in `LICENSE`.

---

## Final Note

AgentNet is intentionally conservative, explicit, and boring where it matters.

That discipline is what enables **trust, interoperability, and long-term adoption** in a machine-centric web.

If you are building AI systems that need to *know where their facts come from*—you are in the right place.
