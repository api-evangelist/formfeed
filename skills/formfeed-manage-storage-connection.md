---
name: formfeed-manage-storage-connection
description: Create, verify, and manage a storage bucket connection for a workspace.
api: openapi/api_formfeed.json
operations:
- getStorageConnection
- putStorageConnection
- testStorageConnection
generated: '2026-09-28'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/api_formfeed.json ; every operationId checked against the contract
---

# formfeed-manage-storage-connection

Create, verify, and manage a storage bucket connection for a workspace.

## Steps

1. 1. Use `getStorageConnection` to read the current storage connection (requires `Authorization: Bearer <token>` header).
2. 2. Use `putStorageConnection` to connect a bucket (requires `Authorization: Bearer <token>` header and `Idempotency-Key` header).
3. 3. Use `testStorageConnection` to test the newly configured storage connection (requires `Authorization: Bearer <token>` header).

## Rules

- Include a `Authorization: Bearer <token>` header for all calls (bearerAuth).
- Send an `Idempotency-Key` header on write operations (`putStorageConnection`).
- If more than 5 requests are made per second, the API returns HTTP 429 (rate limit).
