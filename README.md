# Ditto

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

Ditto is a peer-to-peer data sync platform for mobile and edge devices that enables real-time synchronization without requiring a central server, using Bluetooth, WiFi Direct, and LAN transports. The platform ships an embeddable SDK for iOS, Android, Flutter, React Native, JavaScript, .NET/C#, C++, Rust, Go, Java, and Kotlin, and backs it with an optional cloud tier (the "Big Peer") that bridges device meshes to the internet. Developers query and mutate data through DQL (Ditto Query Language) on-device, or via a cloud HTTP API (v5) against per-app endpoints. Ditto targets mission-critical mobile and edge workloads — retail, manufacturing, aviation, healthcare — where connectivity is intermittent or absent.

**Areas:** Developer Tools · Database · Synchronization · Peer-to-Peer · Edge Computing · Offline-First · Mobile

## Ditto on APIs.io

Everything profiled for Ditto is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ditto-live/](https://apis.io/providers/ditto-live/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Ditto SDK](https://apis.io/apis/ditto-live/sdk/) — Multi-platform embeddable SDK for peer-to-peer and cloud-synced data storage. Supports Swift, Kotlin, Flutter, React Native, JavaScript, .NET/C#, C++, Rust,…
- [Ditto API Keys API](https://apis.io/apis/ditto-live/ditto-live-api-keys-api/) — Big Peer HTTP API keys
- [Ditto Apps API](https://apis.io/apis/ditto-live/ditto-live-apps-api/) — The Apps API from Ditto — 6 operation(s) for apps.
- [Ditto BigPeerReplication API](https://apis.io/apis/ditto-live/ditto-live-bigpeerreplication-api/) — The BigPeerReplication API from Ditto — 2 operation(s) for bigpeerreplication.
- [Ditto Data Bridge API](https://apis.io/apis/ditto-live/ditto-live-data-bridge-api/) — Apps' data bridges (CDC)
- [Ditto Store API](https://apis.io/apis/ditto-live/ditto-live-store-api/) — The Store API from Ditto — 5 operation(s) for store.
- [Ditto Sync API](https://apis.io/apis/ditto-live/ditto-live-sync-api/) — The Sync API from Ditto — 1 operation(s) for sync.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [ditto-live](https://apis.io/servers/ditto-live/ditto-live/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Ditto Live Agentic Access](https://apis.io/agentic-access/ditto-live/ditto-live-agentic-access/)

#### JSON Schema (11)

The data models the API reads and writes.

- [ApiKey](https://apis.io/schemas/ditto-live/ditto-live-apikey/)
- [App](https://apis.io/schemas/ditto-live/ditto-live-app/)
- [BigPeerReplication](https://apis.io/schemas/ditto-live/ditto-live-bigpeer-replication/)
- [DataBridge](https://apis.io/schemas/ditto-live/ditto-live-databridge/)
- [Document](https://apis.io/schemas/ditto-live/ditto-live-document/)
- [FindRequest](https://apis.io/schemas/ditto-live/ditto-live-findrequest/)
- [FindResponse](https://apis.io/schemas/ditto-live/ditto-live-findresponse/)
- [QueryRequest](https://apis.io/schemas/ditto-live/ditto-live-queryrequest/)
- [QueryResponse](https://apis.io/schemas/ditto-live/ditto-live-queryresponse/)
- [WriteRequest](https://apis.io/schemas/ditto-live/ditto-live-writerequest/)
- [WriteResponse](https://apis.io/schemas/ditto-live/ditto-live-writeresponse/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Ditto Live Context](https://apis.io/jsonld/ditto-live/ditto-live-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Ditto Platform Vocabulary](https://apis.io/vocabularies/ditto-live/ditto-live-vocabulary/)

#### Examples (6)

Example requests and responses.

- [Ditto Live Store Execute Request Example](https://apis.io/examples/ditto-live/ditto-live-store-execute-request-example/)
- [Ditto Live Store Execute Response Example](https://apis.io/examples/ditto-live/ditto-live-store-execute-response-example/)
- [Ditto Live Store Find Request Example](https://apis.io/examples/ditto-live/ditto-live-store-find-request-example/)
- [Ditto Live Store Find Response Example](https://apis.io/examples/ditto-live/ditto-live-store-find-response-example/)
- [Ditto Live Store Write Request Example](https://apis.io/examples/ditto-live/ditto-live-store-write-request-example/)
- [Ditto Live Store Write Response Example](https://apis.io/examples/ditto-live/ditto-live-store-write-response-example/)

#### Collections (6)

Postman and Open Collection request collections.

- [Ditto HTTP RPC API Keys API](https://apis.io/collections/ditto-live/open-ditto-live-api-keys-api/)
- [Ditto HTTP RPC API Keys Apps API](https://apis.io/collections/ditto-live/open-ditto-live-apps-api/)
- [Ditto HTTP RPC API Keys BigPeerReplication API](https://apis.io/collections/ditto-live/open-ditto-live-bigpeerreplication-api/)
- [Ditto HTTP RPC API Keys Data Bridge API](https://apis.io/collections/ditto-live/open-ditto-live-data-bridge-api/)
- [Ditto HTTP RPC API Keys Store API](https://apis.io/collections/ditto-live/open-ditto-live-store-api/)
- [Ditto HTTP RPC API Keys Sync API](https://apis.io/collections/ditto-live/open-ditto-live-sync-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Ditto — jsonschema rules](https://apis.io/rules/ditto-live/ditto-live-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Ditto Live Authentication](https://apis.io/security/ditto-live/ditto-live-authentication/)
- [Ditto Live Domain Security](https://apis.io/security/ditto-live/ditto-live-domain-security/)
- [Ditto Live Trust Center](https://apis.io/security/ditto-live/ditto-live-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Ditto Live Plans Pricing](https://apis.io/plans/ditto-live/ditto-live-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Ditto Live Rate Limits](https://apis.io/rate-limits/ditto-live/ditto-live-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Ditto Live Finops](https://apis.io/finops/ditto-live/ditto-live-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ditto.com)
- [Documentation](https://docs.ditto.live)
- [Pricing](https://www.ditto.com/pricing/cloud-sync)
- [Changelog](https://docs.ditto.live/changelog)
- [Blog](https://www.ditto.com/blog)
- [GitHub](https://github.com/getditto)

## API Evangelist rating

**Kin Score 36.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 60.0 |
| Contract quality | 51.7 |
| Contract governance | 9.8 |
| Operational transparency | 26.3 |
| Developer ergonomics | 33.3 |
| Access clarity | 26.3 |

**Agent readiness 30.8** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | platform (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 21.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ditto-live/](https://apis.io/providers/ditto-live/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Ditto: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ditto-live/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
