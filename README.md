# GamerPower (gamerpower)

GamerPower is a free, no-authentication REST API that aggregates live game giveaways across PC, console, mobile, VR, and DRM-free platforms — tracking free games, beta keys, DLC drops, and in-game loot offers from Steam, Epic Games Store, GOG, Ubisoft Connect, EA Origin, itch.io, Battle.net, PlayStation, Xbox, Switch, Android, iOS, and VR storefronts. Multi-value platform/type filtering, date/value/popularity sorting, and aggregate USD worth estimation are exposed.

**URL:** [Visit APIs.json URL](https://www.gamerpower.com/api-read)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

- Games And Comics, Giveaways, Free Games, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### GamerPower API
Free REST API aggregating live game giveaways, beta keys, DLC drops, and in-game loot offers across 18 gaming platforms. JSON responses, no authentication, multi-value filtering, and aggregate USD worth estimation.

**Human URL:** [https://www.gamerpower.com/api-read](https://www.gamerpower.com/api-read)

#### Tags:

- Games And Comics, Giveaways, Free Games

#### Properties

- [Documentation](https://www.gamerpower.com/api-read)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/openapi/gamerpower.yml)
- [Rules](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/rules/gamerpower-rules.yml)
- [JSONSchema (Giveaway)](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/json-schema/gamerpower-giveaway-schema.json)
- [JSONSchema (GiveawayList)](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/json-schema/gamerpower-giveaway-list-schema.json)
- [JSONSchema (WorthEstimation)](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/json-schema/gamerpower-worth-estimation-schema.json)
- [JSONSchema (StatusEnvelope)](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/json-schema/gamerpower-status-envelope-schema.json)
- [JSONStructure (Giveaway)](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/json-structure/gamerpower-giveaway-structure.json)
- [JSONStructure (WorthEstimation)](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/json-structure/gamerpower-worth-estimation-structure.json)
- [JSONStructure (StatusEnvelope)](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/json-structure/gamerpower-status-envelope-structure.json)
- [JSONLD](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/json-ld/gamerpower.jsonld)
- [JSONLDContext](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/json-ld/gamerpower-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/vocabulary/gamerpower.yml)
- [Plans](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/plans/gamerpower-plans-pricing.yml)
- [RateLimits](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/rate-limits/gamerpower-rate-limits.yml)
- [FinOps](https://raw.githubusercontent.com/api-evangelist/gamerpower/refs/heads/main/finops/gamerpower-finops.yml)
- [Authentication](https://www.gamerpower.com/api-read)
- [NaftikoCapability (Giveaways)](capabilities/gamerpower-giveaways.yaml)
- [NaftikoCapability (Filter)](capabilities/gamerpower-filter.yaml)
- [NaftikoCapability (Worth)](capabilities/gamerpower-worth.yaml)

## Common Properties

- [Website](https://www.gamerpower.com)
- [Documentation](https://www.gamerpower.com/api-read)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- [Marketplace — RapidAPI Listing](https://rapidapi.com/digiwalls/api/gamerpower)
- [CodeExamples — Game_Grabber](https://github.com/LuckyLuke00/Game_Grabber)
- [CodeExamples — api-gamerpower](https://github.com/suvayan-m/api-gamerpower)
- [CodeExamples — gamehub (Flutter)](https://github.com/AnggaPutraa/gamehub)

## Features

| Name | Description |
|------|-------------|
| No Authentication | Fully open API; no key, token, or login required to consume any endpoint. |
| 18 Gaming Platforms | Coverage of PC, Steam, Epic Games Store, GOG, Ubisoft, Origin, Battle.net, itch.io, PS4, PS5, Xbox One, Xbox Series X\|S, Xbox 360, Switch, Android, iOS, VR, and DRM-Free. |
| Multi-Value Filtering | The /filter endpoint accepts dot-separated platform and type lists for combined queries like "Epic Games OR Steam" and "Game OR Loot". |
| Sort By Date / Value / Popularity | Built-in sort-by query parameter on /giveaways and /filter. |
| Worth Aggregation | The /worth endpoint returns a live count and total USD value of the active giveaway pool — useful for marketing and trend dashboards. |
| Free For Personal And Commercial Use | Attribution to GamerPower.com is the only requirement. |

## Use Cases

| Name | Description |
|------|-------------|
| Discord / Telegram Free-Game Bots | Push notifications when new giveaways match a watched platform or type. |
| Free-Game RSS / Newsletter Pipelines | Schedule daily fetches of live giveaways and email subscribers digestible summaries. |
| Gaming Companion Apps | Embed live free-game listings inside mobile or web gaming companions. |
| Marketing And Trend Dashboards | Track aggregate USD worth of live free-game promotions over time. |
| API Workshops And Tutorials | Use as a zero-friction, no-auth example API when teaching REST consumption, MCP, or API mocking. |

## Integrations

| Name | Description |
|------|-------------|
| RapidAPI | Third-party marketplace listing exposes the same surface with managed keys, CORS, and tiered limits. |
| Naftiko | REST + MCP capability adapters published for Giveaways, Filter, and Worth surfaces. |
| Microcks | OpenAPI ships with x-microcks-operation extensions and named default examples for direct mock import. |
| Spectral | A repo-local Spectral ruleset enforces GamerPower path, summary, parameter, schema, and method conventions. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [GamerPower API](openapi/gamerpower.yml)

### JSON Schema

- [Giveaway](json-schema/gamerpower-giveaway-schema.json)
- [GiveawayList](json-schema/gamerpower-giveaway-list-schema.json)
- [WorthEstimation](json-schema/gamerpower-worth-estimation-schema.json)
- [StatusEnvelope](json-schema/gamerpower-status-envelope-schema.json)

### JSON Structure

- [Giveaway](json-structure/gamerpower-giveaway-structure.json)
- [WorthEstimation](json-structure/gamerpower-worth-estimation-structure.json)
- [StatusEnvelope](json-structure/gamerpower-status-envelope-structure.json)

### JSON-LD

- [GamerPower API](json-ld/gamerpower.jsonld)
- [GamerPower Context](json-ld/gamerpower-context.jsonld)

### Examples

- [Single Giveaway](examples/gamerpower-giveaway-example.json)
- [Giveaway List](examples/gamerpower-giveaway-list-example.json)
- [Worth Estimation](examples/gamerpower-worth-estimation-example.json)
- [Status Envelope](examples/gamerpower-status-envelope-example.json)
- [List Giveaways](examples/list-giveaways.json)
- [Filter Giveaways](examples/filter-giveaways.json)
- [Get Worth](examples/get-worth.json)

### Plans, Rate Limits, FinOps

- [Plans & Pricing](plans/gamerpower-plans-pricing.yml)
- [Rate Limits](rate-limits/gamerpower-rate-limits.yml)
- [FinOps](finops/gamerpower-finops.yml)

## Capabilities

Naftiko capabilities organized per business surface.

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [GamerPower — Giveaways](capabilities/gamerpower-giveaways.yaml) | gamerpower | 2 | Gaming Content Developer, Giveaway Bot Operator |
| [GamerPower — Filter](capabilities/gamerpower-filter.yaml) | gamerpower | 1 | Gaming Content Developer, Giveaway Bot Operator |
| [GamerPower — Worth](capabilities/gamerpower-worth.yaml) | gamerpower | 1 | Marketing Analyst, Giveaway Bot Operator |

## Vocabulary

- [GamerPower Vocabulary](vocabulary/gamerpower.yml) — Unified taxonomy mapping 3 resources, 4 actions, 3 workflows, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [GamerPower Spectral Ruleset](rules/gamerpower-rules.yml) — 31 rules across info, servers, paths, operations, tags, parameters, responses, schemas, security, and Microcks categories enforcing GamerPower API conventions

## Notes

- This entry was initially bulk-registered as part of a public-apis catalog sweep on 2026-05-28 and fully enriched on 2026-05-30 via the run-pipeline skill.
- The GitHub user `GamerPower` exists but currently has 0 public repos; no official SDK, MCP server, or Claude Code skill is published by the provider.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
