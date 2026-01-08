# Contributing to AgentNet

Thank you for your interest in contributing to **AgentNet**.

AgentNet is a **standards-driven, federated architecture** intended for long-term interoperability, neutrality, and trust in machine-readable data systems. Contributions are welcome, but must meet a high bar for clarity, rigor, and alignment with the AgentNet Standards (ANS).

This document describes **how to contribute responsibly and effectively**.

---

## Guiding Principles for Contributions

All contributions MUST adhere to the following principles:

- **Standards-first:** ANS stability and coherence take precedence over novelty.
- **Interoperability:** Contributions MUST consider multi-implementation impact.
- **Neutrality:** No contribution may privilege a specific vendor, platform, or operator.
- **Transparency:** Rationale and tradeoffs MUST be documented.
- **Precision:** Ambiguous or underspecified changes are discouraged.

AgentNet is not optimized for rapid iteration; it is optimized for **durable correctness**.

---

## What You Can Contribute

Contributions MAY include:

- Clarifications or corrections to ANS language
- Proposed extensions or optional capabilities
- Documentation improvements
- Example Capsules, requests, or responses
- Reference materials that aid understanding or adoption
- Governance or process refinements (non-normative)

Contributions SHOULD NOT include:

- Implementation-specific optimizations presented as standards requirements
- Commercial or pricing models
- Platform-specific dependencies
- Operational mandates for Nodes, Resolvers, or Registrars

---

## Contribution Types

### 1. Standards Proposals (ANS Changes)

Changes to the AgentNet Standards (ANS) are the most sensitive contribution type.

Standards proposals MUST:

- Clearly identify affected ANS sections
- Distinguish **normative** vs **non-normative** changes
- Preserve backward compatibility unless explicitly justified
- Include rationale, alternatives considered, and tradeoffs
- Avoid introducing mandatory dependencies

Standards changes follow the governance process defined in `GOVERNANCE.md`.

---

### 2. Documentation Contributions

Documentation improvements are encouraged and lower-friction.

These include:
- Clarifying explanations
- Diagrams or examples
- Terminology alignment
- Editorial corrections

Documentation MUST remain consistent with ANS terminology and definitions.

---

### 3. Examples and Reference Materials

Example Capsules, resolver responses, or workflows are welcome provided that:

- They are clearly marked as **examples**, not requirements
- They conform to ANS Core v2.0
- They avoid implying preferred implementations

Examples MAY illustrate optional or experimental patterns when clearly labeled.

---

## How to Contribute

### Step 1: Review Existing Materials

Before contributing, please review:
- `README.md`
- `standards/ANS-Core-v2.0.docx`
- `GOVERNANCE.md`

Understanding the architecture and governance model is essential.

---

### Step 2: Open an Issue

All substantive contributions SHOULD begin with an issue describing:

- The problem or gap being addressed
- Relevant ANS sections (if applicable)
- Proposed approach
- Potential impact on interoperability

This allows early feedback and avoids misaligned work.

---

### Step 3: Submit a Pull Request

Pull requests SHOULD:

- Be focused and scoped
- Include clear commit messages
- Reference the relevant issue
- Avoid unrelated formatting changes
- Preserve existing terminology unless explicitly revised

Large or controversial changes MAY require staged or split PRs.

---

## Review Process

Contributions are reviewed for:

- Alignment with ANS Core
- Technical correctness
- Clarity and precision
- Backward compatibility
- Ecosystem impact

Approval is not guaranteed. Rejection does not imply lack of merit—only misalignment with current standards objectives.

---

## Normative Language

When proposing standards language, contributors SHOULD use RFC-style terms consistently:

- **MUST / SHALL**
- **SHOULD**
- **MAY**
- **MUST NOT / SHALL NOT**

Avoid informal or ambiguous phrasing in normative sections.

---

## Licensing and Attribution

By submitting a contribution, you agree that:

- Your contribution may be incorporated into the AgentNet Standards
- Your contribution will be distributed under the repository license
- Attribution MAY be preserved in commit history or acknowledgments

Do not submit material you do not have the right to license.

---

## Code of Conduct

All contributors are expected to follow the community standards defined in `CODE_OF_CONDUCT.md`.

Professional, respectful discourse is required at all times.

---

## Final Note

AgentNet exists to enable **trustworthy machine-to-machine interaction at global scale**.

Thoughtful, precise contributions help ensure that the standard remains:
- Useful
- Neutral
- Interoperable
- Enduring

Thank you for contributing responsibly.
