---
name: formfeed-manage-webhooks
description: Create a webhook endpoint, test it, and list existing webhook endpoints.
api: openapi/api_formfeed.json
operations:
- createWebhook
- testWebhook
- listWebhooks
generated: '2026-09-28'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/api_formfeed.json ; every operationId checked against the contract
---

# formfeed-manage-webhooks

Create a webhook endpoint, test it, and list existing webhook endpoints.

## Steps

1. 1. Call `createWebhook` with required body fields for the webhook endpoint.
2. 2. Call `testWebhook` with the webhook `id` returned from creation to send a test event.
3. 3. Call `listWebhooks` to retrieve the current webhook endpoints.

## Rules

- Include a `Authorization: Bearer <token>` header (bearerAuth).
- Send an `Idempotency-Key` header on the `createWebhook` write request.
- Use cursor‑based pagination (`cursor`, `limit`) when calling `listWebhooks`.
