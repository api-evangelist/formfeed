# Formfeed

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Formfeed offers a PDF and image generation API that lets developers render templates written in Jinja2, Liquid, or Handlebars into PDFs, PNGs, and other formats. It can also convert Word and PowerPoint files. The service runs in Frankfurt with EU‑only data residency and provides a free tier of 100 units per month. SDKs are available for TypeScript and Python, a CLI exists, and there is MCP integration for AI agents. Features include batch rendering, webhook notifications, versioned templates, and a visual editor for designing documents.

**Areas:** PDF · Image Generation · Templates · Developer Tools · Software-as-a-Service

## Formfeed on APIs.io

Everything profiled for Formfeed is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/formfeed/](https://apis.io/providers/formfeed/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [Formfeed Account API](https://apis.io/apis/formfeed/formfeed-account-api/) — Workspace, plan and usage.
- [Formfeed Brand API](https://apis.io/apis/formfeed/formfeed-brand-api/) — The organisation's brand kit: colours, fonts, logos and legal footer every template sees as `brand`.
- [Formfeed Compat API](https://apis.io/apis/formfeed/formfeed-compat-api/) — Migration shim for apitemplate.io clients.
- [Formfeed Files API](https://apis.io/apis/formfeed/formfeed-files-api/) — Workspace assets such as images and fonts.
- [Formfeed Partials API](https://apis.io/apis/formfeed/formfeed-partials-api/) — Shared partials of the organisation, included by name from every template of the same engine.
- [Formfeed PDF tools API](https://apis.io/apis/formfeed/formfeed-pdf-tools-api/) — Merge, protect, watermark and inspect PDFs.
- [Formfeed Renders API](https://apis.io/apis/formfeed/formfeed-renders-api/) — Render PDFs and images from templates, HTML or URLs.
- [Formfeed Templates API](https://apis.io/apis/formfeed/formfeed-templates-api/) — Manage templates and versions (templates as code).
- [Formfeed Webhooks API](https://apis.io/apis/formfeed/formfeed-webhooks-api/) — Event delivery to your endpoints.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Formfeed Webhooks](https://apis.io/asyncapis/formfeed/formfeed-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [io.github.formfeed-dev/formfeed](https://apis.io/servers/formfeed/io-github-formfeed-dev-formfeed/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Formfeed Agentic Access](https://apis.io/agentic-access/formfeed/formfeed-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [Brand](https://apis.io/schemas/formfeed/formfeed-brand/)
- [Render](https://apis.io/schemas/formfeed/formfeed-render/)
- [RenderRequest](https://apis.io/schemas/formfeed/formfeed-render-request/)
- [StorageConnection](https://apis.io/schemas/formfeed/formfeed-storage-connection/)
- [StorageConnectionPut](https://apis.io/schemas/formfeed/formfeed-storage-connection-put/)
- [TemplateVersionCreate](https://apis.io/schemas/formfeed/formfeed-template-version-create/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Formfeed Context](https://apis.io/jsonld/formfeed/formfeed-context/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Formfeed Openapi Overlay](https://apis.io/overlays/formfeed/formfeed-openapi-overlay/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Formfeed API Rules](https://apis.io/rules/formfeed/formfeed-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Formfeed Authentication](https://apis.io/security/formfeed/formfeed-authentication/)
- [Formfeed Domain Security](https://apis.io/security/formfeed/formfeed-domain-security/)
- [Formfeed Trust Center](https://apis.io/security/formfeed/formfeed-trust-center/)
- [Formfeed Vulnerability Disclosure](https://apis.io/security/formfeed/formfeed-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Formfeed Plans Pricing](https://apis.io/plans/formfeed/formfeed-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Formfeed Rate Limits](https://apis.io/rate-limits/formfeed/formfeed-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://formfeed.dev/)
- [Documentation](https://docs.formfeed.dev/api/overview)
- [Getting started](https://docs.formfeed.dev/getting-started/quickstart)
- [API reference](https://docs.formfeed.dev/api/reference/formfeed)
- [Pricing](https://formfeed.dev/pricing)
- [Sign up](https://formfeed.dev/pricing)
- [Support](https://formfeed.dev/support)
- [Changelog](https://formfeed.dev/changelog)
- [Blog](https://formfeed.dev/blog)
- [Security](https://formfeed.dev/security)
- [Compliance](https://formfeed.dev/security)
- [Terms of service](https://formfeed.dev/legal/terms)
- [Privacy policy](https://formfeed.dev/legal/privacy)
- [GitHub](https://github.com/formfeed-dev)
- [Status](https://status.formfeed.dev)

## API Evangelist rating

**Kin Score 76.8** — exemplar · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 71.1 |
| Contract governance | 22.0 |
| Operational transparency | 86.8 |
| Developer ergonomics | 63.7 |
| Access clarity | 92.1 |

**Agent readiness 51.8** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | verified |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 43.1** — AI & Biometrics

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/formfeed/](https://apis.io/providers/formfeed/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Formfeed: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/formfeed/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
