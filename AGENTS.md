# AGENTS.md — agent instructions and operational contract

This file is written for automated coding agents (for example: Copilot coding agents). It exists to provide a concise operational contract and guardrails for agents working in this repository. It is not the canonical source for design or style rules. Those live in the developer documentation linked below.

## Organization-wide guidelines (required)

- Follow the prioritized shared instructions in [hoverkraft-tech/.github/AGENTS.md](https://github.com/hoverkraft-tech/.github/blob/main/AGENTS.md) before working in this repository.

## Quick Start

This project is a catalog of Kubernetes `CustomResourceDefinition` JSON schemas for validating custom resources with tools such as `kubeconform` or `datree`. For comprehensive documentation, see the main [README.md](./README.md).

### Key Sections to Reference

- [Purpose](./README.md#purpose) - Why this catalog exists and use cases
- [Repository layout](./README.md#repository-layout) - How schemas are organized by API group
- [Usage](./README.md#usage) - How to use with `kubeconform` and `datree`
- [Contributing](./README.md#contributing) - Guidelines for contributing schemas

## Agent-Specific Development Patterns

### Critical Workflow Knowledge

```bash
# Essential commands for development
make lint        # Run Super Linter (dockerized)
make lint-fix    # Auto-fix linting issues
```
