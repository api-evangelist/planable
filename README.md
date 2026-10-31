# Planable

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

Planable is a collaboration-first social media management platform used by agencies, multi-location brands, multi-brand companies and in-house marketing teams to create, plan, collaborate on, approve, schedule, publish and analyze content across Facebook, Instagram, X (Twitter), LinkedIn, TikTok, YouTube, Pinterest, Threads and Google Business Profile. It exposes three programmable surfaces: a REST Public API v1 at https://api.planable.io/api/v1 with 51 operations over workspaces, pages, posts, comments, campaigns, labels, media, members, stories, competitor analytics and social listening; a remote OAuth-protected MCP server at https://mcp.planable.io/mcp for Claude, ChatGPT and Gemini; and twelve MIT-licensed Agent Skills published as a Claude Code plugin. Agent- and API-created content always lands as a draft and passes through Planable's normal approval workflow.

**Areas:** Social Media · Content Collaboration · Approval Workflows · Social Media Management · Content Publishing · Marketing · Social Media Analytics · Social Listening · MCP · AI Agents · Agent Skills

## Planable on APIs.io

Everything profiled for Planable is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/planable/](https://apis.io/providers/planable/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [Planable Campaigns API](https://apis.io/apis/planable/planable-campaigns-api/) — The Campaigns API from Planable — 5 operation(s). Create, read, update and delete campaigns — named groupings of posts inside a workspace.
- [Planable Competitors API](https://apis.io/apis/planable/planable-competitors-api/) — The Competitors API from Planable — 6 operation(s). Track up to five competitor social pages per page and pull comparison tables, follower/engagement trends…
- [Planable Labels API](https://apis.io/apis/planable/planable-labels-api/) — The Labels API from Planable — 2 operation(s). List and create the color-coded labels used to organize posts by topic, format or event within a workspace.
- [Planable Media API](https://apis.io/apis/planable/planable-media-api/) — The Media API from Planable — 3 operation(s). List the workspace media library, upload assets from a public URL (up to 100MB per file) and read an asset’s…
- [Planable Members API](https://apis.io/apis/planable/planable-members-api/) — The Members API from Planable — 1 operation(s). List workspace members with their roles and approval-level assignments.
- [Planable Pages API](https://apis.io/apis/planable/planable-pages-api/) — The Pages API from Planable — 4 operation(s). List the social channels connected to a workspace, pull per-page analytics, and trigger and poll a metrics…
- [Planable Posts API](https://apis.io/apis/planable/planable-posts-api/) — The Posts API from Planable — 18 operation(s). The core content surface — list, create, read, update and delete posts, create synced cross-platform group…
- [Planable Social Listening API](https://apis.io/apis/planable/planable-social-listening-api/) — The Social Listening API from Planable — 7 operation(s). Track brand and topic keywords for a workspace, then read matched mentions, daily metrics,…
- [Planable Stories API](https://apis.io/apis/planable/planable-stories-api/) — The Stories API from Planable — 1 operation(s). Create single-frame or multi-frame Instagram and Facebook stories.
- [Planable System API](https://apis.io/apis/planable/planable-system-api/) — The System API from Planable — 1 operation(s). Health check for the Planable Public API.
- [Planable Workspaces API](https://apis.io/apis/planable/planable-workspaces-api/) — The Workspaces API from Planable — 3 operation(s). List, create and delete the workspaces that scope every other resource in the API.
- [Planable MCP Server](https://apis.io/apis/planable/planable-mcp/) — Planable’s official remote Model Context Protocol server at https://mcp.planable.io/mcp. An OAuth 2.0 protected resource (authorization code + PKCE, dynamic…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Planable MCP](https://apis.io/servers/planable/planable-mcp/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Planable Agentic Access](https://apis.io/agentic-access/planable/planable-agentic-access/)

#### JSON Schema (151)

The data models the API reads and writes.

- [Delete_Campaigns_{Id} Response 401](https://apis.io/schemas/planable/delete_campaigns_{id}-response-401/)
- [Delete_Campaigns_{Id} Response 429](https://apis.io/schemas/planable/delete_campaigns_{id}-response-429/)
- [Delete_Campaigns_{Id} Response 500](https://apis.io/schemas/planable/delete_campaigns_{id}-response-500/)
- [Delete_Posts_{Id} Response 401](https://apis.io/schemas/planable/delete_posts_{id}-response-401/)
- [Delete_Posts_{Id} Response 429](https://apis.io/schemas/planable/delete_posts_{id}-response-429/)
- [Delete_Posts_{Id} Response 500](https://apis.io/schemas/planable/delete_posts_{id}-response-500/)
- [Delete_Workspaces_{Id} Response 401](https://apis.io/schemas/planable/delete_workspaces_{id}-response-401/)
- [Delete_Workspaces_{Id} Response 429](https://apis.io/schemas/planable/delete_workspaces_{id}-response-429/)
- [Delete_Workspaces_{Id} Response 500](https://apis.io/schemas/planable/delete_workspaces_{id}-response-500/)
- [Get_Campaigns Response 200](https://apis.io/schemas/planable/get_campaigns-response-200/)
- [Get_Campaigns Response 401](https://apis.io/schemas/planable/get_campaigns-response-401/)
- [Get_Campaigns Response 403](https://apis.io/schemas/planable/get_campaigns-response-403/)
- [Get_Campaigns Response 429](https://apis.io/schemas/planable/get_campaigns-response-429/)
- [Get_Campaigns Response 500](https://apis.io/schemas/planable/get_campaigns-response-500/)
- [Get_Campaigns_{Id} Response 200](https://apis.io/schemas/planable/get_campaigns_{id}-response-200/)
- [Get_Campaigns_{Id} Response 401](https://apis.io/schemas/planable/get_campaigns_{id}-response-401/)
- [Get_Campaigns_{Id} Response 403](https://apis.io/schemas/planable/get_campaigns_{id}-response-403/)
- [Get_Campaigns_{Id} Response 429](https://apis.io/schemas/planable/get_campaigns_{id}-response-429/)
- [Get_Campaigns_{Id} Response 500](https://apis.io/schemas/planable/get_campaigns_{id}-response-500/)
- [Get_Labels Response 200](https://apis.io/schemas/planable/get_labels-response-200/)
- [Get_Labels Response 401](https://apis.io/schemas/planable/get_labels-response-401/)
- [Get_Labels Response 403](https://apis.io/schemas/planable/get_labels-response-403/)
- [Get_Labels Response 429](https://apis.io/schemas/planable/get_labels-response-429/)
- [Get_Labels Response 500](https://apis.io/schemas/planable/get_labels-response-500/)
- [Get_Media Response 200](https://apis.io/schemas/planable/get_media-response-200/)
- …and 126 more published on APIs.io

#### Collections (8)

Postman and Open Collection request collections.

- [Planable Public Campaigns API](https://apis.io/collections/planable/open-planable-campaigns-api/)
- [Planable Public Campaigns Labels API](https://apis.io/collections/planable/open-planable-labels-api/)
- [Planable Public Campaigns Media API](https://apis.io/collections/planable/open-planable-media-api/)
- [Planable Public Campaigns Pages API](https://apis.io/collections/planable/open-planable-pages-api/)
- [Planable Public Campaigns Posts API](https://apis.io/collections/planable/open-planable-posts-api/)
- [Planable Public Campaigns Stories API](https://apis.io/collections/planable/open-planable-stories-api/)
- [Planable Public Campaigns System API](https://apis.io/collections/planable/open-planable-system-api/)
- [Planable Public Campaigns Workspaces API](https://apis.io/collections/planable/open-planable-workspaces-api/)

#### Overlays (11)

OpenAPI overlays, including conversational phrasing for each operation.

- [Planable Campaigns Api Overlay](https://apis.io/overlays/planable/planable-campaigns-api-overlay/)
- [Planable Competitors Api Overlay](https://apis.io/overlays/planable/planable-competitors-api-overlay/)
- [Planable Labels Api Overlay](https://apis.io/overlays/planable/planable-labels-api-overlay/)
- [Planable Media Api Overlay](https://apis.io/overlays/planable/planable-media-api-overlay/)
- [Planable Members Api Overlay](https://apis.io/overlays/planable/planable-members-api-overlay/)
- [Planable Pages Api Overlay](https://apis.io/overlays/planable/planable-pages-api-overlay/)
- [Planable Posts Api Overlay](https://apis.io/overlays/planable/planable-posts-api-overlay/)
- [Planable Social Listening Api Overlay](https://apis.io/overlays/planable/planable-social-listening-api-overlay/)
- [Planable Stories Api Overlay](https://apis.io/overlays/planable/planable-stories-api-overlay/)
- [Planable System Api Overlay](https://apis.io/overlays/planable/planable-system-api-overlay/)
- [Planable Workspaces Api Overlay](https://apis.io/overlays/planable/planable-workspaces-api-overlay/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Planable — jsonschema rules](https://apis.io/rules/planable/planable-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Planable Authentication](https://apis.io/security/planable/planable-authentication/)
- [Planable Domain Security](https://apis.io/security/planable/planable-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Planable Scopes](https://apis.io/scopes/planable/planable-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Planable Plans Pricing](https://apis.io/plans/planable/planable-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Planable Rate Limits](https://apis.io/rate-limits/planable/planable-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Planable Finops](https://apis.io/finops/planable/planable-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://planable.io/)
- [Documentation](https://help.planable.io/hc/en-us/)
- [Getting started](https://planable.io/guides/planable-public-api/)
- [API reference](https://api.planable.io/api/v1/docs)
- [Pricing](https://planable.io/pricing/)
- [Sign up](https://app.planable.io/signup)
- [Support](https://help.planable.io/hc/en-us/)
- [Blog](https://planable.io/blog/)
- [Terms of service](https://planable.io/terms/)
- [Privacy policy](https://planable.io/privacy/)
- [GitHub](https://github.com/Planable)
- [Status](https://status.planable.io/)

## API Evangelist rating

**Kin Score 59.5** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 51.9 |
| Contract governance | 28.0 |
| Operational transparency | 55.3 |
| Developer ergonomics | 61.9 |
| Access clarity | 69.7 |

**Agent readiness 52.9** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | documented (partial credit) |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 34.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/planable/](https://apis.io/providers/planable/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Planable: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/planable/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
