# GamerPower (gamerpower)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

GamerPower is a free, no-authentication REST API that aggregates live game giveaways across PC, console, mobile, VR, and DRM-free platforms — tracking free games, beta keys, DLC drops, and in-game loot offers from Steam, Epic Games Store, GOG, Ubisoft Connect, EA Origin, itch.io, Battle.net, PlayStation, Xbox, Switch, Android, iOS, and VR storefronts. Multi-value platform/type filtering, date/value/popularity sorting, and aggregate USD worth estimation are exposed.

**APIs.json:** [https://www.gamerpower.com/api-read](https://www.gamerpower.com/api-read)

## Tags

- Games And Comics
- Giveaways
- Free Games
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### GamerPower API

Free REST API aggregating live game giveaways, beta keys, DLC drops, and in-game loot offers across 18 gaming platforms. JSON responses, no authentication, multi-value filtering, and aggregate USD worth estimation.

- **Human URL:** [https://www.gamerpower.com/api-read](https://www.gamerpower.com/api-read)
- **Base URL:** `https://www.gamerpower.com/api`

#### Tags

- Games And Comics
- Giveaways
- Free Games

#### Properties

- [Documentation](https://www.gamerpower.com/api-read)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/openapi/gamerpower.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Rules](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/rules/gamerpower-rules.yml)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/json-schema/gamerpower-giveaway-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/json-schema/gamerpower-giveaway-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/json-schema/gamerpower-worth-estimation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/json-schema/gamerpower-status-envelope-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/json-structure/gamerpower-giveaway-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/json-structure/gamerpower-worth-estimation-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/json-structure/gamerpower-status-envelope-structure.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/json-ld/gamerpower.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/json-ld/gamerpower-context.jsonld)
- [Example](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/examples/gamerpower-giveaway-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/examples/gamerpower-giveaway-list-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/examples/gamerpower-worth-estimation-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/examples/gamerpower-status-envelope-example.json)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/vocabulary/gamerpower.yml)
- [Plans](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/plans/gamerpower-plans-pricing.yml)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/rate-limits/gamerpower-rate-limits.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/finops/gamerpower-finops.yml)
- [Authentication](https://www.gamerpower.com/api-read)
- [Rate Limits](https://www.gamerpower.com/api-read)
- [Postman Collection](collections/gamerpower.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gamerpower.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.gamerpower.com)
- [Documentation](https://www.gamerpower.com/api-read)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Marketplace](https://rapidapi.com/digiwalls/api/gamerpower)
- [Code Examples](https://github.com/LuckyLuke00/Game_Grabber)
- [Code Examples](https://github.com/suvayan-m/api-gamerpower)
- [Code Examples](https://github.com/AnggaPutraa/gamehub)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
