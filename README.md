# Traceable (traceable)

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

Traceable is an API security and observability platform that provides API discovery, threat detection, and protection across the full application lifecycle. It uses context-aware AI to detect and block API-based attacks while providing deep visibility into API behavior and risk. Traceable exposes public GraphQL APIs for configuration, analytics, and operational data access, as well as an MCP server with 12 tools for AI-assisted security workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/traceable/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/traceable/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- API Discovery
- API Protection
- API Security
- API Testing
- Observability
- Security
- Threat Detection

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-19

## APIs

### Traceable Platform GraphQL API

The Traceable Platform GraphQL API provides programmatic access to API security configuration and operational data. Supports queries for API discovery analytics, vulnerability data, threat activity, entity scoping, and API test suite management. Authentication uses a platform API token passed in the Authorization header.

- **Human URL:** [https://docs.traceable.ai/docs/public-apis](https://docs.traceable.ai/docs/public-apis)
- **Base URL:** `https://api.traceable.ai`

#### Tags

- API Discovery
- API Security
- GraphQL
- Threat Detection
- Vulnerability Management

#### Properties

- [Documentation](https://docs.traceable.ai/docs/public-apis)
- [OpenAPI](openapi/traceable-platform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/traceable-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/traceable-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/traceable-api-entity-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/traceable-api-entity-structure.json)
- [JSON-LD](json-ld/traceable-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/traceable-rules.yml)
- [Vocabulary](vocabulary/traceable-vocabulary.yml)
- [Graph Q L](https://api.traceable.ai/graphql)
- [A P I Spec Download](https://docs.traceable.ai/docs/download-api-spec)

### Traceable API Security Platform

Traceable provides an intelligent API security platform offering API discovery, threat detection and protection, and API security testing. It uses distributed tracing and context-aware AI to understand API behavior, detect threats, and protect APIs across the full application lifecycle. The platform supports REST, SOAP, gRPC, GraphQL, and WebSocket APIs.

- **Human URL:** [https://www.traceable.ai](https://www.traceable.ai)

#### Tags

- API Discovery
- API Security
- API Testing
- Observability
- Threat Detection

#### Properties

- [Documentation](https://docs.traceable.ai)
- [A P I Discovery](https://www.traceable.ai/product/api-discovery)
- [Threat Detection](https://www.traceable.ai/product/threat-detection)
- [A P I Security Testing](https://www.traceable.ai/product/api-security-testing)
- [M C P Server](https://docs.traceable.ai/docs/traceable-mcp-server)
- [Postman Collection](collections/traceable-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/traceable-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Traceable Active Security Testing

Traceable Active Security Testing (AST) provides automated API security testing with GraphQL-based configuration for scan creation, suite management, and CI/CD pipeline integration. Supports GitHub Actions, GitLab CI, and Jenkins integrations.

- **Human URL:** [https://docs.traceable.ai/docs/en/ast-getting-started](https://docs.traceable.ai/docs/en/ast-getting-started)

#### Tags

- API Security Testing
- CI/CD
- DAST
- Security Automation

#### Properties

- [Documentation](https://docs.traceable.ai/docs/en/ast-getting-started)
- [Git Hub Action](https://github.com/Traceableai/ast-action)
- [Jenkins Plugin](https://github.com/Traceableai/traceable-xast-jenkins-plugin)
- [Graph Q L Scan A P I](https://docs.traceable.ai/docs/scans-using-graphql-api)
- [Graph Q L Suite A P I](https://docs.traceable.ai/docs/suites-using-graphql-api)
- [Postman Collection](collections/traceable-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/traceable-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.traceable.ai)
- [Documentation](https://docs.traceable.ai)
- [Blog](https://www.traceable.ai/blog)
- [About](https://www.traceable.ai/company)
- [Contact](https://www.traceable.ai/contact)
- [Demo](https://www.traceable.ai/request-demo)
- [Partners](https://www.traceable.ai/partners)
- [Resources](https://www.traceable.ai/resources)
- [LinkedIn](https://www.linkedin.com/company/traboraceable/)
- [Twitter](https://twitter.com/ATraceableAI)
- [Git Hub](https://github.com/Traceableai)
- [M C P Server](https://docs.traceable.ai/docs/traceable-mcp-server)
- [Integrations](https://www.traceable.ai/partners)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
