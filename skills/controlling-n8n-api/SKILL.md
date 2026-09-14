---
name: controlling-n8n-api
description: "Controls, deploys, monitors, and orchestrates n8n instances programmatically using the official n8n Public REST API v1, CLI, and webhooks. Use when the user asks to control n8n via API, deploy workflows programmatically, query executions, manage credentials, activate/deactivate workflows, or inspect n8n instance states."
---

# Controlling n8n via Public REST API & CLI

Comprehensive reference and automated tooling to control self-hosted and cloud n8n instances programmatically.

## When to use this skill
- Querying, creating, updating, activating, or deleting workflows via n8n Public REST API.
- Deploying workflow JSON files directly to an n8n instance from CI/CD, scripts, or agents.
- Inspecting live workflow executions, debugging execution failures, and triggering retries.
- Managing n8n credentials, environment variables, tags, and data tables via API.
- Integrating external webhooks and invoking n8n workflow triggers.

## Authentication
Every request to the n8n API requires:
Header: X-N8N-API-KEY: <api-key>
Content-Type: application/json
Base URL: http://localhost:5678/api/v1 (or remote instance URL)
