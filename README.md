# Xweather (xweather)

Xweather, a Vaisala company, provides weather data APIs delivering science-backed, hyper-local weather intelligence for operational applications. The Xweather Weather API exposes current conditions, forecasts, severe weather alerts, lightning data, air quality, observations, wildfire information, tropical cyclone tracks, and maritime weather through a single REST API. Authentication uses a client_id and client_secret passed as query parameters or HTTP headers.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Air Quality, Company, Data, Forecasts, Lightning, Maritime, Observations, Severe Weather, Weather

## Timestamps

- **Created:** 2024-11-08
- **Modified:** 2026-05-03

## APIs

### Xweather Weather API

The Xweather Weather API provides real-time and historical weather data including current conditions, forecasts, severe weather alerts, lightning data, air quality, maritime weather, wildfire data, and tropical cyclone information. Backed by Vaisala, Xweather delivers science-backed hyper-local weather intelligence through a RESTful interface authenticated with client ID and client secret.

**Human URL:** [https://www.xweather.com/docs/weather-api](https://www.xweather.com/docs/weather-api)

**Base URL:** https://data.api.xweather.com

#### Tags

 - Air Quality, Alerts, Data, Forecasts, Lightning, Maritime, Observations, Severe Weather, Weather

#### Properties

- [Documentation](https://www.xweather.com/docs/weather-api)
- [GettingStarted](https://www.xweather.com/docs/weather-api/getting-started/authentication)
- [APIReference](https://www.xweather.com/docs/weather-api/endpoints)
- [OpenAPI](openapi/xweather-weather-api-openapi.yml)

## Common Properties

- [Website](https://xweather.com)
- [Documentation](https://www.xweather.com/docs/weather-api)
- [APIReference](https://www.xweather.com/docs/weather-api/endpoints)
- [Authentication](https://www.xweather.com/docs/weather-api/getting-started/authentication)
- [SignUp](https://www.xweather.com/)
- [Pricing](https://www.xweather.com/weather-api)

## Features

| Name | Description |
|------|-------------|
| Real-Time Conditions | Current surface weather observations for any location worldwide. |
| Hourly and Daily Forecasts | Forecast records out to 15 days with hourly and daily granularity. |
| Severe Weather Alerts | Government-issued alerts, watches, and warnings with severity, urgency, and certainty. |
| Global Lightning Network | Cloud-to-ground and in-cloud lightning strike data from Vaisala's global detection network. |
| Lightning Threat Nowcast | Probabilistic short-term lightning threat used to drive stop-work and all-clear automation. |
| Air Quality | AQI values, primary pollutant, and detailed pollutant breakdowns for monitoring and reporting. |
| Maritime Weather | Marine weather including waves, swell, sea-surface temperature, and sea state. |
| Wildfire Data | Active wildfire incident records and perimeters for situational awareness. |
| Tropical Cyclones | Active tropical cyclone tracks, intensity, and forecast cones. |

## Use Cases

| Name | Description |
|------|-------------|
| Construction Lightning Safety | Automatically pause and resume outdoor construction work using lightning threat nowcasts. |
| Aviation Ground Operations | Drive ramp closures and re-openings around lightning, severe weather, and visibility thresholds. |
| Outdoor Sports and Events | Manage stadium and event evacuations and re-entries based on lightning and severe weather. |
| Energy and Utilities | Plan grid operations, crew dispatch, and storm restoration around forecasts and alerts. |
| Logistics and Routing | Optimize routing and dispatch decisions using maritime, road weather, and severe weather feeds. |
| Insurance and Risk | Use historical and real-time storm and lightning data for claims and underwriting. |
| Environmental Reporting | Aggregate AQI and pollutant feeds for ESG and regulatory reporting. |

## Integrations

| Name | Description |
|------|-------------|
| AerisWeather Mapping | Tile and overlay services for visualizing Xweather data on web and mobile maps. |
| Vaisala Lightning Network | Underlying global lightning detection infrastructure feeding the Xweather lightning APIs. |
| Common Alerting Protocol | Severe-weather alert payloads align with CAP severity, urgency, and certainty fields. |
| METAR | Surface observations are derived from the international METAR observation standard. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Xweather Weather API](openapi/xweather-weather-api-openapi.yml)

### JSON Schema

- [Location](json-schema/xweather-location-schema.json)
- [Conditions Observation](json-schema/xweather-conditions-observation-schema.json)
- [Conditions Response](json-schema/xweather-conditions-response-schema.json)
- [Conditions Record](json-schema/xweather-conditions-record-schema.json)
- [Forecast Period](json-schema/xweather-forecast-period-schema.json)
- [Forecasts Response](json-schema/xweather-forecasts-response-schema.json)
- [Alert](json-schema/xweather-alert-schema.json)
- [Alerts Response](json-schema/xweather-alerts-response-schema.json)
- [Lightning Strike](json-schema/xweather-lightning-strike-schema.json)
- [Lightning Response](json-schema/xweather-lightning-response-schema.json)
- [Lightning Threats Response](json-schema/xweather-lightning-threats-response-schema.json)
- [Air Quality Observation](json-schema/xweather-air-quality-observation-schema.json)
- [Air Quality Response](json-schema/xweather-air-quality-response-schema.json)
- [Observations Response](json-schema/xweather-observations-response-schema.json)
- [Fires Response](json-schema/xweather-fires-response-schema.json)
- [Tropical Cyclones Response](json-schema/xweather-tropical-cyclones-response-schema.json)
- [Maritime Response](json-schema/xweather-maritime-response-schema.json)

### JSON Structure

- [Xweather Weather API Structure](json-structure/xweather-weather-api-structure.json)

### JSON-LD

- [Xweather Context](json-ld/xweather-context.jsonld)

### Examples

- [Get Conditions](examples/xweather-get-conditions-example.json)
- [Get Forecasts](examples/xweather-get-forecasts-example.json)
- [Get Alerts](examples/xweather-get-alerts-example.json)
- [Get Lightning](examples/xweather-get-lightning-example.json)
- [Get Air Quality](examples/xweather-get-air-quality-example.json)
- [List Tropical Cyclones](examples/xweather-list-tropical-cyclones-example.json)
- [Get Maritime Conditions](examples/xweather-get-maritime-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Xweather Weather API](capabilities/shared/xweather-weather-api.yaml) — 11 operations covering conditions, forecasts, alerts, lightning, air quality, observations, fires, tropical, and maritime

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Operational Weather Monitoring](capabilities/operational-weather-monitoring.yaml) | Xweather Weather API | 3 | Operations Manager |
| [Lightning Safety Automation](capabilities/lightning-safety.yaml) | Xweather Weather API | 2 | Safety Officer |

## Vocabulary

- [Xweather Vocabulary](vocabulary/xweather-vocabulary.yml) — Unified taxonomy mapping 9 resources, 10 actions, 5 workflows, and 5 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Xweather Spectral Rules](rules/xweather-rules.yml) — 11 rules across 4 categories enforcing Xweather API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
