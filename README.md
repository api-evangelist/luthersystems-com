# Luther Systems

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

Luther Systems is a London- and Campbell, CA-based enterprise software company (Luther Systems Limited and Luther Systems US Incorporated) whose Luther Platform automates end-to-end enterprise processes — "Deep Process Automation" — for customers such as Allianz and DLA Piper's TOKO, running business logic (ELPS "phyla") on the Substrate runtime over Hyperledger Fabric with ConnectorHub integrations, a shiroclient JSON-RPC gateway, LutherAuth identity and Buf-managed Protobuf contracts. Its public, agent-native surface is two products: AgentSearch (agentsearch.luthersystems.com) — a free, no-auth, daily-scored index of ~4,300 AI agents and MCP servers exposed as an OpenAPI 3.1 HTTP API, a hosted Streamable HTTP MCP server (5 tools) plus an npm stdio package, and an A2A 0.3.0 agent card with a live JSON-RPC endpoint — and InsideOut (Riley) — an agentic cloud architect that designs, prices, generates Terraform for, deploys and inspects AWS/GCP infrastructure through a hosted MCP server at app.luthersystems.com (24 tools, session-scoped, no keys for design), an A2A 0.3 card, provider-published Agent Skills, Claude Code / Kiro / Cursor plugins and a Docker image. The enterprise platform ships Go SDKs, the shirotester CLI (with a local MCP server), the mars infrastructure CLI and a public docs repository with dated release notes.

**Areas:** Agents · Agent Discovery · MCP · A2A · Agent-Native · Cloud Infrastructure · Terraform · Infrastructure as Code · Process Automation · Enterprise Automation · Distributed Ledger · Hyperledger Fabric

## Luther Systems on APIs.io

Everything profiled for Luther Systems is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/luthersystems-com/](https://apis.io/providers/luthersystems-com/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [AgentSearch MCP Server](https://apis.io/apis/luthersystems-com/agentsearch-mcp/) — Model Context Protocol surface for AgentSearch in two deployments. Hosted: POST https://agentsearch.luthersystems.com/api/mcp, Streamable HTTP, protocol…
- [AgentSearch A2A Agent](https://apis.io/apis/luthersystems-com/agentsearch-a2a-agent/) — Agent2Agent surface for AgentSearch — an agent card at https://agentsearch.luthersystems.com/.well-known/agent-card.json (protocolVersion 0.3.0, version…
- [InsideOut (Riley) MCP Server](https://apis.io/apis/luthersystems-com/insideout-mcp/) — Hosted Model Context Protocol server for InsideOut, Luther Systems' agentic cloud architect: POST https://app.luthersystems.com/v1/insideout-mcp, Streamable…
- [InsideOut A2A Agent](https://apis.io/apis/luthersystems-com/insideout-a2a-agent/) — Agent2Agent surface for InsideOut — an agent card at https://insideout.luthersystems.com/.well-known/agent-card.json (protocolVersion 0.3, version 1.0.0,…
- [Luther Platform Protobuf Contracts](https://apis.io/apis/luthersystems-com/luther-platform-protobuf/) — Buf-managed Protocol Buffers published at github.com/luthersystems/protos (module buf.build/luthersystems/protos) that define API contracts and shared…
- [Luther Systems Agent API](https://apis.io/apis/luthersystems-com/luthersystems-com-agent-api/) — The Agent API from Luther Systems — 1 operation(s) for agent.
- [Luther Systems Browse API](https://apis.io/apis/luthersystems-com/luthersystems-com-browse-api/) — The Browse API from Luther Systems — 1 operation(s) for browse.
- [Luther Systems Found Agent API](https://apis.io/apis/luthersystems-com/luthersystems-com-found-agent-api/) — The Found Agent API from Luther Systems — 1 operation(s) for found agent.
- [Luther Systems Search API](https://apis.io/apis/luthersystems-com/luthersystems-com-search-api/) — The Search API from Luther Systems — 1 operation(s) for search.
- [Luther Systems Stats API](https://apis.io/apis/luthersystems-com/luthersystems-com-stats-api/) — The Stats API from Luther Systems — 1 operation(s) for stats.
- [Luther Systems .well Known API](https://apis.io/apis/luthersystems-com/luthersystems-com-well-known-api/) — The .well Known API from Luther Systems — 1 operation(s) for .well known.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (2)

Model Context Protocol servers that expose the API to agents.

- [InsideOut hosted MCP endpoint (Streamable HTTP)](https://apis.io/servers/luthersystems-com/insideout-hosted-mcp-endpoint-streamable-http/)
- [luthersystems-com-mcp.yml](https://apis.io/servers/luthersystems-com/luthersystems-com-mcp-yml/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Luthersystems Com Agentsearch Overlay](https://apis.io/overlays/luthersystems-com/luthersystems-com-agentsearch-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Luthersystems Com Authentication](https://apis.io/security/luthersystems-com/luthersystems-com-authentication/)
- [Luthersystems Com Domain Security](https://apis.io/security/luthersystems-com/luthersystems-com-domain-security/)
- [Luthersystems Com Vulnerability Disclosure](https://apis.io/security/luthersystems-com/luthersystems-com-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Luthersystems Com Plans Pricing](https://apis.io/plans/luthersystems-com/luthersystems-com-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Luthersystems Com Rate Limits](https://apis.io/rate-limits/luthersystems-com/luthersystems-com-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://luthersystems.com/)
- [Documentation](https://docs.luthersystems.com/)
- [Getting started](https://github.com/luthersystems/docs/blob/main/common-operation-script/quickstart/README.md)
- [API reference](https://agentsearch.luthersystems.com/api-docs)
- [Pricing](https://agentsearch.luthersystems.com/.well-known/agent-card.json)
- [Support](https://www.luthersystems.com/contact)
- [Changelog](https://github.com/luthersystems/docs/blob/main/release-notes.md)
- [Blog](https://www.luthersystems.com/insights)
- [Security](https://github.com/luthersystems/insideout-agent-skills/blob/main/SECURITY.md)
- [Privacy policy](https://www.luthersystems.com/privacy-policy)
- [GitHub](https://github.com/luthersystems)

## API Evangelist rating

**Kin Score 49.6** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.7 |
| Contract quality | 43.3 |
| Contract governance | 18.2 |
| Operational transparency | 52.6 |
| Developer ergonomics | 69.0 |
| Access clarity | 42.1 |

**Agent readiness 31.7** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | near-conformant (partial credit) |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | na |

**Regulatory alignment 27.2** — Insurance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/luthersystems-com/](https://apis.io/providers/luthersystems-com/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Luther Systems: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/luthersystems-com/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
