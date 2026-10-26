# Giphy (giphy)

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

GIPHY is the world's largest library of GIFs, stickers, animated emoji, and Clips (GIFs with sound), with a developer API used by messaging apps, social platforms, productivity tools, ads, and creator products. GIPHY is owned by Meta. Authentication is via API key (Beta or Production tier) and all surfaces share the same envelope (data + meta + pagination) with rich, multi-rendition media payloads.

**APIs.json:** [https://developers.giphy.com/](https://developers.giphy.com/)

## Tags

- Photography
- Media
- GIFs
- Stickers
- Emoji
- Video
- Messaging
- Social
- Meta

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### GIPHY API

The GIPHY REST API. Search, trending, translate, random, lookup, categories, autocomplete, related/trending terms, channels, animated emoji, animated text, Clips, analytics pingbacks, and uploads — all behind a single API key.

- **Human URL:** [https://developers.giphy.com/docs/api](https://developers.giphy.com/docs/api)
- **Base URL:** `https://api.giphy.com`

#### Tags

- GIFs
- Stickers
- Emoji
- Clips
- Channels
- Categories
- Search Discovery
- Analytics
- Upload
- Utilities

#### Properties

- [Documentation](https://developers.giphy.com/docs/api)
- [API Reference](https://developers.giphy.com/docs/api/endpoint)
- [Getting Started](https://developers.giphy.com/docs/api)
- [Authentication](https://developers.giphy.com/docs/api#quick-start-guide)
- [OpenAPI](openapi/giphy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/giphy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/giphy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/giphy-gif-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/giphy-clip-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/giphy-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/giphy-channel-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/giphy-category-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/giphy-images-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/giphy-analytics-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/giphy-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/giphy-pagination-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/giphy-gif-structure.json)
- [JSON Structure](json-structure/giphy-clip-structure.json)
- [JSON Structure](json-structure/giphy-images-structure.json)
- [JSON Structure](json-structure/giphy-channel-structure.json)
- [Example](examples/giphy-search-gifs-example.json)
- [Example](examples/giphy-get-trending-gifs-example.json)
- [Example](examples/giphy-translate-gif-example.json)
- [Example](examples/giphy-get-random-gif-example.json)
- [Example](examples/giphy-get-gif-by-id-example.json)
- [Example](examples/giphy-list-gif-categories-example.json)
- [Example](examples/giphy-autocomplete-search-tags-example.json)
- [Example](examples/giphy-get-related-search-terms-example.json)
- [Example](examples/giphy-get-trending-searches-example.json)
- [Example](examples/giphy-search-stickers-example.json)
- [Example](examples/giphy-list-emoji-example.json)
- [Example](examples/giphy-search-clips-example.json)
- [Example](examples/giphy-upload-gif-example.json)
- [Example](examples/giphy-register-search-action-example.json)
- [SDK](https://github.com/Giphy/giphy-ios-sdk)
- [SDK](https://github.com/Giphy/giphy-android-sdk)
- [SDK](https://github.com/Giphy/giphy-react-native-sdk)
- [SDK](https://github.com/Giphy/giphy-flutter-sdk)
- [SDK](https://github.com/Giphy/giphy-js)
- [SDK](https://github.com/Giphy/giphy-python-client)
- [SDK](https://github.com/Giphy/giphy-ruby-client)
- [SDK](https://github.com/Giphy/giphy-php-client)
- [Rate Limits](rate-limits/giphy-rate-limits.yml)
- [Pricing](plans/giphy-plans-pricing.yml)

## Common Properties

- [Website](https://giphy.com/)
- [Developer Portal](https://developers.giphy.com/)
- [Documentation](https://developers.giphy.com/docs/)
- [Console](https://developers.giphy.com/dashboard/)
- [Sign Up](https://giphy.com/join)
- [Login](https://giphy.com/login)
- [Terms of Service](https://developers.giphy.com/terms/)
- [Privacy Policy](https://support.giphy.com/hc/en-us/articles/360032872931-GIPHY-Privacy-Policy)
- [Branding](https://support.giphy.com/hc/en-us/articles/360020027252-GIPHY-Brand-Guidelines)
- [Support](https://support.giphy.com/hc/en-us)
- [GitHub Organization](https://github.com/Giphy)
- [GitHub Repository](https://github.com/Giphy/GiphyAPI)
- [Blog](https://medium.com/@giphy)
- [X (Twitter)](https://x.com/giphy)
- [Tools](https://github.com/Giphy/giphy-bandwidth-saver)
- [Tools](https://github.com/Giphy/cloudflare-cdn-config-ref-implementation)
- [Tools](https://github.com/Giphy/fastly-compute-ref-implementation)
- [Spectral Rules](rules/giphy-rules.yml)
- [Vocabulary](vocabulary/giphy-vocabulary.yml)
- [JSON-LD](json-ld/giphy-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Plans](plans/giphy-plans-pricing.yml)
- [Rate Limits](rate-limits/giphy-rate-limits.yml)
- [Resources](finops/giphy-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
