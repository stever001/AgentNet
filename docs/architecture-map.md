# AgentNet Architecture Map

## Canonical flow

AgentNet reference implementations follow this execution path:

1. **Capsulizer** ingests source material and produces capsule-ready records.
2. **Registrar** issues node identity and manages canonical owner/lifecycle state.
3. **Resolver** serves deterministic lookup and retrieval over registered data.
4. **Orchestrator** composes resolver-backed outputs into end-user interaction flows.

## Repository mapping

- Capsulizer: https://github.com/agentnet-ai/ant-capsulizer
- Registrar: https://github.com/agentnet-ai/ant-registrar
- Resolver: https://github.com/agentnet-ai/ant-resolver
- Orchestrator: https://github.com/agentnet-ai/ant-orchestrator
- Standards root: https://github.com/agentnet-ai/AgentNet

## Technical notes

- ANS Core v2.0 defines normative behavior; implementations are reference baselines.
- Service boundaries are explicit to support independent deployment and verification.
- Local development commonly runs all four services for end-to-end validation.
