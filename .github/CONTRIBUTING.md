# Contributing to AgentNet

Thanks for helping improve AgentNet. This repository centralizes organization-wide community health files for the `agentnet-ai` GitHub organization.

## Before You Contribute

- Search existing issues and pull requests before opening a new one.
- Keep changes focused and scoped to one problem or improvement.
- Be respectful and collaborative in all discussions.

## Filing Issues

When opening an issue:

- Use the appropriate issue template when available.
- Provide a clear title and concise problem statement.
- Include reproduction steps, expected behavior, and actual behavior for bugs.
- Add relevant environment details, logs, or screenshots when helpful.

## Proposing Specification Changes

Specification changes should be proposed in:

- [`agentnet-ai/agentnet`](https://github.com/agentnet-ai/agentnet)

Include rationale, compatibility impact, and any migration notes for proposed spec changes.

## Proposing Code Changes

Code changes should be proposed in the relevant implementation repository, such as:

- `ant-capsulizer`
- `ant-registrar`
- `ant-resolver`
- `ant-orchestrator`

## Branch Naming

Use descriptive branch names with a clear prefix:

- `feat/<short-description>`
- `fix/<short-description>`
- `docs/<short-description>`
- `chore/<short-description>`

Examples:

- `feat/add-resolver-cache-docs`
- `fix/registrar-validation-edge-case`

## Commit Style

Conventional commits are encouraged but optional.

Examples:

- `feat: add resolver request validation`
- `fix: handle missing registrar metadata`
- `docs: clarify ANS Core v2.0 terminology`

## Pull Request Expectations

Every PR should include:

- A clear description of the problem and the proposed solution.
- Linked issues or discussion context, when applicable.
- Tests for code changes, if tests exist in that repository.
- Screenshots or recordings for UI changes.

Keep PRs small enough for efficient review whenever possible.
