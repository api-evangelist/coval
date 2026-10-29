# Coval

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

Coval is the deployment-readiness platform for voice and chat AI agents. Teams simulate thousands of realistic conversation scenarios before launch, monitor real production calls, and improve reliability with metrics and human review. Coval supports inbound/outbound voice, standard chat, chat over WebSocket, chat A2A (JSON-RPC), voice-to-voice models (OpenAI Realtime, Gemini Live), SMS, Pipecat, and LiveKit agents. Its v1 REST API, TypeScript and Python SDKs, Homebrew CLI, and hosted MCP server let developers connect agents, define personas and test sets, launch simulation runs, ingest production conversations and OpenTelemetry traces, define deterministic/statistical/ML/LLM-judge metrics, and route critical calls to human reviewers. Coval is backed by General Catalyst and is SOC 2 Type II, GDPR, and HIPAA compliant.

**Areas:** Company · AI Agents · Voice AI · Testing · Evaluation · Simulation · Observability · Conversational AI · LLM · Quality Assurance

## Coval on APIs.io

Everything profiled for Coval is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/coval/](https://apis.io/providers/coval/)** — or go straight to one of the APIs or properties below.

### APIs (25)

- [Coval Agents API](https://apis.io/apis/coval/coval-agents-api/) — CRUD operations for AI agent configurations
- [Coval API Keys API](https://apis.io/apis/coval/coval-api-keys-api/) — Manage API keys for your organization
- [Coval Audio API](https://apis.io/apis/coval/coval-audio-api/) — Upload audio for evaluation and access conversation audio files
- [Coval Conversations API](https://apis.io/apis/coval/coval-conversations-api/) — Submit and manage real-world conversation monitoring evaluations
- [Coval Dashboards API](https://apis.io/apis/coval/coval-dashboards-api/) — Dashboard CRUD operations
- [Coval Metric Outputs API](https://apis.io/apis/coval/coval-metric-outputs-api/) — Retrieve metric computation results for simulations
- [Coval Metrics API](https://apis.io/apis/coval/coval-metrics-api/) — CRUD operations for custom evaluation metrics
- [Coval Monitor Events API](https://apis.io/apis/coval/coval-monitor-events-api/) — Monitor evaluation event history
- [Coval Monitors API](https://apis.io/apis/coval/coval-monitors-api/) — CRUD operations for monitor definitions
- [Coval Mutations API](https://apis.io/apis/coval/coval-mutations-api/) — CRUD operations for agent configuration mutations
- [Coval Organization Conversations Config API](https://apis.io/apis/coval/coval-organization-conversations-config-api/) — Organization-level configuration for conversation metrics — the default and conditional metrics run on conversations.
- [Coval Personas API](https://apis.io/apis/coval/coval-personas-api/) — Persona CRUD operations
- [Coval Reports API](https://apis.io/apis/coval/coval-reports-api/) — CRUD operations for saved multi-run reports
- [Coval Review Annotations API](https://apis.io/apis/coval/coval-review-annotations-api/) — Annotation CRUD operations
- [Coval Review Projects API](https://apis.io/apis/coval/coval-review-projects-api/) — Project CRUD operations
- [Coval Run Templates API](https://apis.io/apis/coval/coval-run-templates-api/) — CRUD operations for reusable run configurations
- [Coval Runs API](https://apis.io/apis/coval/coval-runs-api/) — Launch and manage simulation runs
- [Coval Scheduled Runs API](https://apis.io/apis/coval/coval-scheduled-runs-api/) — CRUD operations for scheduled evaluations
- [Coval Simulations API](https://apis.io/apis/coval/coval-simulations-api/) — Launch and manage individual simulation executions
- [Coval Tags API](https://apis.io/apis/coval/coval-tags-api/) — CRUD operations for resource tags
- [Coval Test Cases API](https://apis.io/apis/coval/coval-test-cases-api/) — Operations for managing test cases
- [Coval Test Sets API](https://apis.io/apis/coval/coval-test-sets-api/) — Operations for managing test sets
- [Coval Traces API](https://apis.io/apis/coval/coval-traces-api/) — OTLP trace ingestion for simulations and monitoring conversations.
- [Coval Webhooks API](https://apis.io/apis/coval/coval-webhooks-api/) — CRUD operations for event webhooks
- [Coval Widgets API](https://apis.io/apis/coval/coval-widgets-api/) — Dashboard widget CRUD operations

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Coval Webhooks](https://apis.io/asyncapis/coval/coval-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [coval](https://apis.io/servers/coval/coval/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Coval Agentic Access](https://apis.io/agentic-access/coval/coval-agentic-access/)

#### Collections (48)

Postman and Open Collection request collections.

- [Coval Agents API](https://apis.io/collections/coval/open-coval-agents-api/)
- [Coval Agents API Keys API](https://apis.io/collections/coval/open-coval-api-keys-api/)
- [Coval Agents Audio API](https://apis.io/collections/coval/open-coval-audio-api/)
- [Coval Agents Conversations API](https://apis.io/collections/coval/open-coval-conversations-api/)
- [Coval Agents Dashboards API](https://apis.io/collections/coval/open-coval-dashboards-api/)
- [Coval Agents Metric Outputs API](https://apis.io/collections/coval/open-coval-metric-outputs-api/)
- [Coval Agents Metrics API](https://apis.io/collections/coval/open-coval-metrics-api/)
- [Coval Agents Monitor Events API](https://apis.io/collections/coval/open-coval-monitor-events-api/)
- [Coval Agents Monitors API](https://apis.io/collections/coval/open-coval-monitors-api/)
- [Coval Agents Mutations API](https://apis.io/collections/coval/open-coval-mutations-api/)
- [Coval Agents Organization Conversations Config API](https://apis.io/collections/coval/open-coval-organization-conversations-config-api/)
- [Coval Agents Personas API](https://apis.io/collections/coval/open-coval-personas-api/)
- [Coval Agents Reports API](https://apis.io/collections/coval/open-coval-reports-api/)
- [Coval Agents Run Templates API](https://apis.io/collections/coval/open-coval-run-templates-api/)
- [Coval Agents Runs API](https://apis.io/collections/coval/open-coval-runs-api/)
- [Coval Agents Scheduled Runs API](https://apis.io/collections/coval/open-coval-scheduled-runs-api/)
- [Coval Agents Simulations API](https://apis.io/collections/coval/open-coval-simulations-api/)
- [Coval Agents Tags API](https://apis.io/collections/coval/open-coval-tags-api/)
- [Coval Agents Test Cases API](https://apis.io/collections/coval/open-coval-test-cases-api/)
- [Coval Agents Test Sets API](https://apis.io/collections/coval/open-coval-test-sets-api/)
- [Coval Agents Traces API](https://apis.io/collections/coval/open-coval-traces-api/)
- [Coval Agents Webhooks API](https://apis.io/collections/coval/open-coval-webhooks-api/)
- [Coval Agents Widgets API](https://apis.io/collections/coval/open-coval-widgets-api/)
- [Coval Agents API](https://apis.io/collections/coval/postman-coval-agents-api/)
- [Coval Agents API Keys API](https://apis.io/collections/coval/postman-coval-api-keys-api/)
- …and 23 more published on APIs.io

#### Overlays (20)

OpenAPI overlays, including conversational phrasing for each operation.

- [Coval Agents Overlay](https://apis.io/overlays/coval/coval-agents-overlay/)
- [Coval Api Keys Overlay](https://apis.io/overlays/coval/coval-api-keys-overlay/)
- [Coval Conversations Overlay](https://apis.io/overlays/coval/coval-conversations-overlay/)
- [Coval Dashboards Overlay](https://apis.io/overlays/coval/coval-dashboards-overlay/)
- [Coval Metrics Overlay](https://apis.io/overlays/coval/coval-metrics-overlay/)
- [Coval Monitors Overlay](https://apis.io/overlays/coval/coval-monitors-overlay/)
- [Coval Mutations Overlay](https://apis.io/overlays/coval/coval-mutations-overlay/)
- [Coval Organization Overlay](https://apis.io/overlays/coval/coval-organization-overlay/)
- [Coval Personas Overlay](https://apis.io/overlays/coval/coval-personas-overlay/)
- [Coval Reports Overlay](https://apis.io/overlays/coval/coval-reports-overlay/)
- [Coval Reviews Overlay](https://apis.io/overlays/coval/coval-reviews-overlay/)
- [Coval Run Templates Overlay](https://apis.io/overlays/coval/coval-run-templates-overlay/)
- [Coval Runs Overlay](https://apis.io/overlays/coval/coval-runs-overlay/)
- [Coval Scheduled Runs Overlay](https://apis.io/overlays/coval/coval-scheduled-runs-overlay/)
- [Coval Simulations Overlay](https://apis.io/overlays/coval/coval-simulations-overlay/)
- [Coval Tags Overlay](https://apis.io/overlays/coval/coval-tags-overlay/)
- [Coval Test Cases Overlay](https://apis.io/overlays/coval/coval-test-cases-overlay/)
- [Coval Test Sets Overlay](https://apis.io/overlays/coval/coval-test-sets-overlay/)
- [Coval Traces Overlay](https://apis.io/overlays/coval/coval-traces-overlay/)
- [Coval Webhooks Overlay](https://apis.io/overlays/coval/coval-webhooks-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Coval Authentication](https://apis.io/security/coval/coval-authentication/)
- [Coval Domain Security](https://apis.io/security/coval/coval-domain-security/)
- [Coval Trust Center](https://apis.io/security/coval/coval-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Coval Plans Pricing](https://apis.io/plans/coval/coval-plans-pricing/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://coval.ai)
- [Documentation](https://docs.coval.ai)
- [Getting started](https://docs.coval.ai/cli/overview)
- [API reference](https://docs.coval.ai/api-reference/v1/introduction)
- [Pricing](https://www.coval.ai/pricing)
- [Sign up](https://app.coval.dev/login)
- [Support](https://forms.gle/frTn8eCHkcTfw67p8)
- [Changelog](https://docs.coval.ai/changelog)
- [Blog](https://www.coval.ai/blog)
- [Compliance](https://trust.oneleet.com/coval)
- [Trust centre](https://trust.oneleet.com/coval)
- [Terms of service](https://www.coval.ai/terms-of-service)
- [Privacy policy](https://www.coval.ai/privacy-policy)
- [GitHub](https://github.com/coval-ai)
- [Status](https://status.coval.dev)

## API Evangelist rating

**Kin Score 57.5** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 80.0 |
| Contract quality | 64.0 |
| Contract governance | 4.5 |
| Operational transparency | 42.1 |
| Developer ergonomics | 74.4 |
| Access clarity | 63.2 |

**Agent readiness 60.7** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 22.7** — AI & Biometrics

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/coval/](https://apis.io/providers/coval/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Coval: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/coval/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
