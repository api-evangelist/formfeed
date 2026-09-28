---
name: formfeed-create-and-publish-template
description: Create a new template, add a draft version, and publish it.
api: openapi/api_formfeed.json
operations:
- createTemplate
- createTemplateVersion
- publishTemplateVersion
generated: '2026-09-28'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/api_formfeed.json ; every operationId checked against the contract
---

# formfeed-create-and-publish-template

Create a new template, add a draft version, and publish it.

## Steps

1. 1. `createTemplate` – requires the request body with template metadata.
2. 2. `createTemplateVersion` – requires the template ID in the path and a request body with the version files.
3. 3. `publishTemplateVersion` – requires the template ID and version number in the path.

## Rules

- Auth: Include a Bearer token in the Authorization header (bearerAuth).
- Idempotency: Send an `Idempotency-Key` header on write operations (createTemplate, createTemplateVersion, publishTemplateVersion).
- Pagination: Use `cursor` and `limit` query parameters where applicable.
- Rate limiting: Exceeding 5 requests per second returns HTTP 429.
