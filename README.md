# Agent Diff

Agent Diff creates isolated, ephemeral replicas of third-party APIs (Slack, Linear, GitHub). Agents interact with these sandboxes to produce deterministic state-change diffs without side effects, rate limits, or real API calls. Ideal for testing AI agents that interact with external APIs.

## APIs

- **Agent Diff Sandbox API** — Create and manage ephemeral sandbox replicas of third-party APIs and track agent-produced state diffs.

## Documentation

- [Agent Diff Website](https://www.agentdiff.dev/)

## OpenAPI

- [Agent Diff Sandbox OpenAPI](openapi/agent-diff-sandbox-openapi.yml)

## Capabilities

- [API Agent Testing Workflow](capabilities/api-agent-testing.yaml)
- [Shared: Agent Diff Sandbox API](capabilities/shared/agent-diff-sandbox-api.yaml)

## JSON Schema

- [Sandbox Create Request](json-schema/sandbox-sandbox-create-request-schema.json)
- [Sandbox](json-schema/sandbox-sandbox-schema.json)
- [Diff Entry](json-schema/sandbox-diff-entry-schema.json)

## Vocabulary

- [Agent Diff Vocabulary](vocabulary/agent-diff-vocabulary.yaml)

## Tags

API Testing, AI Agents, Sandboxing, API Diffing, Developer Tools

## Maintainers

- Kin Lane (kin@apievangelist.com)
