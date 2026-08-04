# Xweather (xweather)

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

Xweather, a Vaisala company, provides weather data APIs delivering science-backed, hyper-local weather intelligence for operational applications. The Xweather Weather API exposes current conditions, forecasts, severe weather alerts, lightning data, air quality, observations, wildfire information, tropical cyclone tracks, and maritime weather through a single REST API. Authentication uses a client_id and client_secret passed as query parameters or HTTP headers.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Air Quality
- Company
- Data
- Forecasts
- Lightning
- Maritime
- Observations
- Severe Weather
- Weather

## Timestamps

- **Created:** 2024-11-08
- **Modified:** 2026-05-19

## APIs

### Xweather Weather API

The Xweather Weather API provides real-time and historical weather data including current conditions, forecasts, severe weather alerts, lightning data, air quality, maritime weather, wildfire data, and tropical cyclone information. Backed by Vaisala, Xweather delivers science-backed hyper-local weather intelligence through a RESTful interface authenticated with client ID and client secret.

- **Human URL:** [https://www.xweather.com/docs/weather-api](https://www.xweather.com/docs/weather-api)
- **Base URL:** `https://data.api.xweather.com`

#### Tags

- Air Quality
- Alerts
- Data
- Forecasts
- Lightning
- Maritime
- Observations
- Severe Weather
- Weather

#### Properties

- [Documentation](https://www.xweather.com/docs/weather-api)
- [Getting Started](https://www.xweather.com/docs/weather-api/getting-started/authentication)
- [API Reference](https://www.xweather.com/docs/weather-api/endpoints)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/openapi/xweather-weather-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/xweather-weather-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/xweather-weather-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/vaisala-xweather)
- [LinkedIn](https://www.linkedin.com/company/xweather)
- [Website](https://xweather.com)
- [Documentation](https://www.xweather.com/docs/weather-api)
- [API Reference](https://www.xweather.com/docs/weather-api/endpoints)
- [Authentication](https://www.xweather.com/docs/weather-api/getting-started/authentication)
- [Sign Up](https://www.xweather.com/)
- [Pricing](https://www.xweather.com/weather-api)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/openapi/xweather-weather-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-schema/xweather-location-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-schema/xweather-conditions-observation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-schema/xweather-forecast-period-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-schema/xweather-alert-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-schema/xweather-lightning-strike-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-schema/xweather-air-quality-observation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-structure/xweather-weather-api-structure.json)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-ld/xweather-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/vocabulary/xweather-vocabulary.yml)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/rules/xweather-rules.yml)
- [Example](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-get-conditions-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-get-forecasts-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-get-alerts-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-get-lightning-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-get-air-quality-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-list-tropical-cyclones-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-get-maritime-example.json)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
