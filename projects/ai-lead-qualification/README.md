# AI Lead Qualification

## Overview

An AI-assisted workflow for evaluating leads and supporting follow-up prioritization.

## Workflow File

- workflow.json - Exported n8n workflow definition.

## Requirements

- An n8n instance compatible with the workflow's nodes.
- Your own credentials for the external services used.
- Any required application IDs, URLs, or resource settings.

## Import and Setup

1. Import workflow.json into your n8n instance.
2. Create or select your own credentials for the connected services.
3. Configure the required IDs, URLs, and other environment-specific values.
4. Inspect the nodes and confirm their settings.
5. Test with sample data before activating the workflow.

## Security

Credential secrets are not intentionally included. Review all node
parameters, resource references, URLs, and example data before use.
Do not use production data when testing an unfamiliar configuration.

## Notes

Requirements and behavior depend on the actual workflow configuration.
Review the nodes after importing and update this documentation as needed.
