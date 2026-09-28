---
name: formfeed-create-render-and-fetch-result
description: Create a render and retrieve its result.
api: openapi/api_formfeed.json
operations:
- createRender
- getRenderResult
generated: '2026-09-28'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/api_formfeed.json ; every operationId checked against the contract
---

# formfeed-create-render-and-fetch-result

Create a render and retrieve its result.

## Steps

1. 1. Call `createRender` with the required request body and include the `Idempotency-Key` header (writes).
2. 2. Call `getRenderResult` with the render `id` returned from `createRender`.

## Rules

- Include a bearer token in the `Authorization` header for all requests (bearerAuth).
- Send the `Idempotency-Key` header on the `createRender` request to ensure idempotency.
- If the rate limit of 5 requests per second is exceeded, the API returns HTTP 429.
