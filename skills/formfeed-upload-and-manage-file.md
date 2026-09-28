---
name: formfeed-upload-and-manage-file
description: Upload a file to a workspace, retrieve its details, list files, and optionally delete it.
api: openapi/api_formfeed.json
operations:
- uploadFile
- getFile
- listFiles
- deleteFile
generated: '2026-09-28'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/api_formfeed.json ; every operationId checked against the contract
---

# formfeed-upload-and-manage-file

Upload a file to a workspace, retrieve its details, list files, and optionally delete it.

## Steps

1. 1. Use `uploadFile` with the request body containing the file data and the `Idempotency-Key` header for write idempotency.
2. 2. Use `getFile` with the path parameter `id` returned from the upload to read the file's metadata.
3. 3. Use `listFiles` with optional query parameters `cursor` and `limit` to paginate through workspace files.
4. 4. (Optional) Use `deleteFile` with the same `id` and the `Idempotency-Key` header to remove the file.

## Rules

- Include a bearer token in the `Authorization` header (bearerAuth).
- Send the `Idempotency-Key` header on `uploadFile` and `deleteFile` requests.
- Paginate `listFiles` results using `cursor` and `limit` query parameters.
- If the rate limit of 5 requests per second is exceeded, the API returns HTTP 429.
