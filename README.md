# Giphy (giphy)

GIPHY is the world's largest library of GIFs, stickers, animated emoji, and Clips
(GIFs with sound), with a developer API used by messaging apps, social platforms,
productivity tools, advertising, and creator products. GIPHY is owned by Meta.
Authentication is via API key (Beta or Production tier).

**APIs.yml:** [apis.yml](apis.yml)

## Type
- **x-type:** company
- **x-tier:** 1 (enriched full pipeline 2026-05-30)
- **source:** [public-apis/public-apis](https://github.com/public-apis/public-apis) — category: Photography

## API

### GIPHY API
The single GIPHY REST surface, spanning search, trending, translate, random,
lookup, categories, autocomplete, related/trending terms, channels, animated
emoji, animated text, Clips, analytics pingbacks, and uploads.

- Base URL: `https://api.giphy.com` (uploads use `https://upload.giphy.com`)
- [Documentation](https://developers.giphy.com/docs/api) — [API Reference](https://developers.giphy.com/docs/api/endpoint)

#### Specifications & Artifacts
- **OpenAPI:** [openapi/giphy-openapi.yml](openapi/giphy-openapi.yml) — 22 paths, 23 operations.
- **JSON Schemas (9):**
  GIF, Clip, User, Channel, Category, Images/Renditions, Analytics Pingbacks, Meta, Pagination — see [json-schema/](json-schema/).
- **JSON Structure (4):**
  GIF, Clip, Images, Channel field-purpose docs in [json-structure/](json-structure/).
- **Examples (14):** Request/response pairs in [examples/](examples/) covering every key operation
  (search, trending, translate, random, get-by-id, categories, autocomplete, related, trending
  searches, stickers, emoji, clips, upload, analytics action).

#### Naftiko Capabilities (11)
One self-contained capability per OpenAPI tag in [capabilities/](capabilities/):
- `giphy-gifs.yaml` — GIFs surface (5 ops)
- `giphy-stickers.yaml` — Stickers surface (4 ops)
- `giphy-emoji.yaml` — Emoji surface (2 ops)
- `giphy-clips.yaml` — Clips surface (2 ops)
- `giphy-animate.yaml` — Animate text (1 op)
- `giphy-channels.yaml` — Channels (1 op)
- `giphy-categories.yaml` — Categories (1 op)
- `giphy-search-discovery.yaml` — Tag autocomplete + related/trending terms (3 ops)
- `giphy-analytics.yaml` — Search-action pingbacks (1 op)
- `giphy-upload.yaml` — GIF/video upload (1 op)
- `giphy-utilities.yaml` — Random user ID generator (1 op)

Each capability ships with both a REST adapter and an MCP adapter, fully inline.

#### SDKs (Official, github.com/Giphy)
- [iOS SDK](https://github.com/Giphy/giphy-ios-sdk)
- [Android SDK](https://github.com/Giphy/giphy-android-sdk)
- [React Native SDK](https://github.com/Giphy/giphy-react-native-sdk)
- [Flutter SDK](https://github.com/Giphy/giphy-flutter-sdk)
- [Web SDK (giphy-js)](https://github.com/Giphy/giphy-js) — `@giphy/js-fetch-api`, `@giphy/react-components`

#### SDKs (Legacy / Community)
- [Python Client](https://github.com/Giphy/giphy-python-client) (last update 2023)
- [Ruby Client](https://github.com/Giphy/giphy-ruby-client)
- [PHP Client](https://github.com/Giphy/giphy-php-client)

## Cross-cutting

- **Spectral rules:** [rules/giphy-rules.yml](rules/giphy-rules.yml) — enforces canonical tag list, versioned paths, api_key requirement, Title Case summaries, response envelope.
- **Vocabulary:** [vocabulary/giphy-vocabulary.yml](vocabulary/giphy-vocabulary.yml) — operational + capability dimensions.
- **JSON-LD context:** [json-ld/giphy-context.jsonld](json-ld/giphy-context.jsonld) — maps GIPHY fields onto schema.org (`ImageObject`, `VideoObject`, `Brand`, `Person`).
- **Plans / pricing:** [plans/giphy-plans-pricing.yml](plans/giphy-plans-pricing.yml) — Beta (free), Production (custom), Clips Access (gated).
- **Rate limits:** [rate-limits/giphy-rate-limits.yml](rate-limits/giphy-rate-limits.yml) — Beta 100/hour, 50 results/request, 100 MB upload cap, Clips gated.
- **FinOps profile:** [finops/giphy-finops.yml](finops/giphy-finops.yml) — FOCUS-aligned cost tracking guidance against an opaque billing surface.

## MCP servers & Claude skills

GIPHY does not publish a first-party MCP server. Several community implementations
exist on GitHub (e.g. `magarcia/mcp-server-giphy`, `Szatek/giphy-mcp-server`,
`pipeworx-io/mcp-giphy`, `npow/giphy-mcp-server`, `ag2-mcp-servers/giphy-api`). The
Naftiko capabilities in this repo are first-party MCP adapter equivalents and can be
deployed standalone.

## Tags
Photography, Media, GIFs, Stickers, Emoji, Video, Messaging, Social, Meta

## Notes
- Enriched 2026-05-30 via the API Evangelist full pipeline (run-pipeline → 18 steps, CRDs skipped).
- Pricing is undisclosed for the Production tier; Beta tier is free with hard rate limits.

## Timestamps
- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## Maintainers
- **Kin Lane** — kin@apievangelist.com
