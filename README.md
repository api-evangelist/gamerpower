# GamerPower

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

GamerPower is a free, no-authentication REST API that aggregates live game giveaways across PC, console, mobile, VR, and DRM-free platforms — tracking free games, beta keys, DLC drops, and in-game loot offers from Steam, Epic Games Store, GOG, Ubisoft Connect, EA Origin, itch.io, Battle.net, PlayStation, Xbox, Switch, Android, iOS, and VR storefronts. Multi-value platform/type filtering, date/value/popularity sorting, and aggregate USD worth estimation are exposed.

**Areas:** Giveaways · Free Games · Public APIs · Gaming · Video Games

## GamerPower on APIs.io

Everything profiled for GamerPower is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/gamerpower/](https://apis.io/providers/gamerpower/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [GamerPower Filter API](https://apis.io/apis/gamerpower/gamerpower-filter-api/) — Multi-value platform and type filtering using dot-separated values.
- [GamerPower Giveaways API](https://apis.io/apis/gamerpower/gamerpower-giveaways-api/) — List and look up live game giveaways, beta keys, DLC drops, and loot offers.
- [GamerPower Worth API](https://apis.io/apis/gamerpower/gamerpower-worth-api/) — Aggregate live giveaway counts and USD value estimation.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Gamerpower Agentic Access](https://apis.io/agentic-access/gamerpower/gamerpower-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [Giveaway](https://apis.io/schemas/gamerpower/gamerpower-giveaway/)
- [GiveawayList](https://apis.io/schemas/gamerpower/gamerpower-giveaway-list/)
- [StatusEnvelope](https://apis.io/schemas/gamerpower/gamerpower-status-envelope/)
- [WorthEstimation](https://apis.io/schemas/gamerpower/gamerpower-worth-estimation/)

#### JSON Structure (3)

Data models expressed in JSON Structure.

- [Gamerpower Giveaway Structure](https://apis.io/json-structure/gamerpower/gamerpower-giveaway-structure/)
- [Gamerpower Status Envelope Structure](https://apis.io/json-structure/gamerpower/gamerpower-status-envelope-structure/)
- [Gamerpower Worth Estimation Structure](https://apis.io/json-structure/gamerpower/gamerpower-worth-estimation-structure/)

#### JSON-LD (2)

Linked-data contexts for the provider's vocabulary.

- [Gamerpower Context](https://apis.io/jsonld/gamerpower/gamerpower/)
- [Gamerpower Context](https://apis.io/jsonld/gamerpower/gamerpower-context/)

#### Examples (4)

Example requests and responses.

- [Gamerpower Giveaway Example](https://apis.io/examples/gamerpower/gamerpower-giveaway-example/)
- [Gamerpower Status Envelope Example](https://apis.io/examples/gamerpower/gamerpower-status-envelope-example/)
- [Gamerpower Worth Estimation Example](https://apis.io/examples/gamerpower/gamerpower-worth-estimation-example/)
- [Get Worth](https://apis.io/examples/gamerpower/get-worth/)

#### Collections (4)

Postman and Open Collection request collections.

- [GamerPower API](https://apis.io/collections/gamerpower/open-gamerpower/)
- [GamerPower Filter API](https://apis.io/collections/gamerpower/open-gamerpower-filter-api/)
- [GamerPower Filter Giveaways API](https://apis.io/collections/gamerpower/open-gamerpower-giveaways-api/)
- [GamerPower Filter Worth API](https://apis.io/collections/gamerpower/open-gamerpower-worth-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [GamerPower — jsonschema rules](https://apis.io/rules/gamerpower/gamerpower-jsonschema-spectral-rules/)
- [GamerPower API Rules](https://apis.io/rules/gamerpower/gamerpower-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Gamerpower Domain Security](https://apis.io/security/gamerpower/gamerpower-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Gamerpower Plans Pricing](https://apis.io/plans/gamerpower/gamerpower-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Gamerpower Rate Limits](https://apis.io/rate-limits/gamerpower/gamerpower-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Gamerpower Finops](https://apis.io/finops/gamerpower/gamerpower-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.gamerpower.com)
- [Documentation](https://www.gamerpower.com/api-read)

## API Evangelist rating

**Kin Score 24.4** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 27.8 |
| Contract governance | 27.3 |
| Operational transparency | 5.3 |
| Developer ergonomics | 21.4 |
| Access clarity | 5.3 |

**Agent readiness 35.4** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/gamerpower/](https://apis.io/providers/gamerpower/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for GamerPower: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/gamerpower/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
