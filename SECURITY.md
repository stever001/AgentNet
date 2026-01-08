# Security Policy

## Purpose

This document describes how **security issues** related to the AgentNet project should be reported, evaluated, and addressed.

AgentNet is a **standards-driven, federated architecture**. Security considerations primarily relate to:
- correctness of normative specifications
- integrity of reference materials
- trust, provenance, and misuse risks
- vulnerabilities in reference implementations (where applicable)

This policy applies to all official AgentNet repositories and materials.

---

## Scope

### In Scope

The following are considered **in scope** for security reporting:

- Vulnerabilities in reference implementations published by AgentNet
- Flaws in resolver logic that could undermine trust, integrity, or provenance
- Errors in standards text that could enable misuse, ambiguity, or exploitation
- Security-relevant issues in examples or documentation that could reasonably mislead implementers
- Supply-chain or dependency issues in maintained reference code

---

### Out of Scope

The following are **out of scope** for this policy:

- Vulnerabilities in third-party implementations not maintained by AgentNet
- Operational security of independently operated Nodes, Resolvers, or Registrars
- Commercial disputes or contractual issues
- Social engineering attacks unrelated to AgentNet materials
- Misuse of AgentNet by non-compliant actors

AgentNet does not operate production infrastructure and does not monitor external deployments.

---

## Reporting a Security Issue

### How to Report

If you believe you have discovered a security issue:

1. **Do not open a public issue.**
2. Report the issue privately to the maintainers using the security contact listed in this repository.
3. Include:
   - A clear description of the issue
   - Affected files, components, or ANS sections
   - Reproduction steps or proof-of-concept (if applicable)
   - Potential impact and severity assessment

Reports should be factual, concise, and technically precise.

---

### Confidentiality

Security reports are handled confidentially.

- Reporters are expected to act in good faith
- Maintainers will not disclose details prematurely
- Coordinated disclosure will be used where appropriate

---

## Evaluation & Response

Security issues are evaluated based on:

- Impact on interoperability, trust, or provenance
- Likelihood of misuse or exploitation
- Scope of affected materials
- Availability of mitigations or clarifications

Possible responses include:

- Documentation clarification or correction
- Non-normative guidance updates
- Errata or standards revision
- Reference implementation fixes
- Security advisories or disclosures

Not all reports will result in changes; some may be classified as non-issues or usage guidance.

---

## Disclosure Policy

AgentNet follows **responsible disclosure** principles.

- Security fixes or clarifications will be documented publicly once resolved
- Emergency changes may be issued with post-hoc disclosure
- Standards-related security corrections will follow governance procedures

Credit may be given to reporters unless anonymity is requested.

---

## Security and the Standards Process

Security considerations are integral to the AgentNet Standards (ANS).

Security-related findings may:
- Influence interpretation of normative language
- Result in clarifications or errata
- Trigger formal RFC processes for standards changes

Security does not override governance or standards discipline.

---

## No Bug Bounty Program

AgentNet does not currently operate a bug bounty program.

Security research is welcome, but participation is voluntary and uncompensated.

---

## Final Note

Security in AgentNet is not about hardening a single system—it is about preserving **trust, correctness, and interoperability** across a federated ecosystem.

Responsible reporting helps ensure that AgentNet remains reliable infrastructure for machine-to-machine communication.
