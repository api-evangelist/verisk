# Verisk (verisk)
Verisk (formerly ISO) is a leading data analytics and technology company serving the insurance, energy, and financial services industries. Verisk provides risk scoring, actuarial data, property analytics, catastrophe modeling, claims benchmarking, and underwriting intelligence through RESTful APIs that power insurance pricing, reserving, and exposure management workflows.

**URL:** [https://gateway.verisk.com/docs/MainPage.ashx](https://gateway.verisk.com/docs/MainPage.ashx)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Insurance, Analytics, Risk Management, Property Data, Catastrophe Modeling, Underwriting, Claims

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-03

## APIs

### Verisk Insurance Analytics API
Verisk Insurance Analytics API provides property risk assessments, ISO fire protection classifications, catastrophe peril scores, insurance risk scoring, and claims benchmarking data for P&C insurance carriers. Delivers loss cost data, risk classification, and underwriting data services for insurance pricing, reserving, and exposure management.

**Human URL:** [https://gateway.verisk.com/docs/MainPage.ashx](https://gateway.verisk.com/docs/MainPage.ashx)

#### Tags:

 - Insurance, Analytics, Risk Management, Property Data, Catastrophe Modeling, Underwriting, Claims

#### Properties

- [Documentation](https://gateway.verisk.com/docs/MainPage.ashx)
- [GettingStarted](https://gateway.verisk.com/docs/Getting-Started.ashx)
- [Authentication](https://gateway.verisk.com/docs/Authentication.ashx)
- [OpenAPI](openapi/verisk-insurance-analytics-openapi.yml)

### Verisk UnderWriting API
Verisk UnderWriting API provides personal and commercial lines insurance underwriting data including homeowner data, motor vehicle reports, A-PLUS auto and property reports, LightSpeed prefill, geocoding, ISO fire protection class, and coverage verification for P&C insurance carriers.

**Human URL:** [https://gateway.verisk.com/docs/MainPage.ashx](https://gateway.verisk.com/docs/MainPage.ashx)

#### Tags:

 - Underwriting, Insurance, Personal Lines, Commercial Lines, Motor Vehicle, Property Data

#### Properties

- [Documentation](https://gateway.verisk.com/docs/MainPage.ashx)
- [GettingStarted](https://gateway.verisk.com/docs/Getting-Started.ashx)
- [Authentication](https://gateway.verisk.com/docs/Authentication.ashx)

## Common Properties

- [Website](https://www.verisk.com)
- [Portal](https://gateway-documentation.verisk.com/)
- [APIReference](https://apicatalog.verisk.com/)
- [Documentation](https://gateway.verisk.com/docs/MainPage.ashx)
- [GettingStarted](https://gateway.verisk.com/docs/Getting-Started.ashx)
- [Authentication](https://gateway.verisk.com/docs/Authentication.ashx)
- [TermsOfService](https://www.verisk.com/terms-of-use/)
- [PrivacyPolicy](https://www.verisk.com/privacy-policy/)
- [Contact](https://www.verisk.com/contact/)

## Features

| Name | Description |
|------|-------------|
| Property Risk Assessment | Comprehensive property risk scoring including construction, fire protection class, and hazard exposure for fire, wind, hail, flood, and earthquake perils. |
| ISO Fire Protection Classification | ISO Public Protection Classification (PPC) grading measuring community fire suppression capability on a 1-10 scale. |
| Catastrophe Peril Scoring | Natural hazard exposure scores for hurricane, tornado, hail, wildfire, earthquake, and flood risk used for catastrophe risk management. |
| Insurance Risk Scoring | Risk scores for properties, policies, and portfolios including fire protection class, building code effectiveness grading, flood zone, and earthquake zone scores. |
| Claims Benchmarking | Industry claims benchmarking data for loss frequency, severity, combined ratio, and loss ratio metrics across lines of business and states. |
| Address Geocoding and Lookup | Address-to-property resolution with geocoding to USGS coordinates and ISO property identification for prefill and underwriting workflows. |
| Prefill and Accelerated Underwriting | LightSpeed and homeowner data APIs provide instant underwriting intelligence from a business name and address for small commercial and personal lines. |
| Weather Analytics Integration | Benchmark API provides hail, wind, lightning, and hurricane wind analytics for property and auto claims and underwriting decisions. |

## Use Cases

| Name | Description |
|------|-------------|
| Insurance Pricing and Rating | Use risk scores and property data to accurately price insurance policies for homeowners, auto, and commercial lines of business. |
| Catastrophe Risk Management | Assess portfolio exposure to natural hazard perils and estimate probable maximum loss (PML) for catastrophe reinsurance programs. |
| Claims Adjudication | Integrate weather analytics and property data to streamline field adjustments, reduce inspection costs, and accelerate claim cycle times. |
| Underwriting Automation | Automate underwriting decisions by integrating prefill data, motor vehicle reports, and coverage verification into policy administration systems. |
| Portfolio Risk Monitoring | Monitor geographic concentration and peril exposure across insurance portfolios for risk management and regulatory reporting. |

## Integrations

| Name | Description |
|------|-------------|
| Policy Administration Systems | Integrate risk scores and underwriting data directly into existing policy administration and underwriting workflow systems. |
| Claims Management Systems | Embed weather analytics and property data into claims management platforms for faster adjudication. |
| Catastrophe Modeling Platforms | Feed peril scores and property data into catastrophe modeling platforms like AIR Worldwide and RMS for exposure analysis. |
| Generative AI Underwriting Assistant | API-enabled GenAI commercial underwriting assistant that integrates into existing policy administration systems. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Verisk Insurance Analytics API](openapi/verisk-insurance-analytics-openapi.yml)

### JSON Schema

- [insurance-analytics-property-risk-schema.json](json-schema/insurance-analytics-property-risk-schema.json)
- [insurance-analytics-construction-data-schema.json](json-schema/insurance-analytics-construction-data-schema.json)
- [insurance-analytics-fire-protection-class-schema.json](json-schema/insurance-analytics-fire-protection-class-schema.json)
- [insurance-analytics-address-lookup-request-schema.json](json-schema/insurance-analytics-address-lookup-request-schema.json)
- [insurance-analytics-property-lookup-response-schema.json](json-schema/insurance-analytics-property-lookup-response-schema.json)
- [insurance-analytics-risk-score-request-schema.json](json-schema/insurance-analytics-risk-score-request-schema.json)
- [insurance-analytics-risk-score-response-schema.json](json-schema/insurance-analytics-risk-score-response-schema.json)
- [insurance-analytics-peril-score-request-schema.json](json-schema/insurance-analytics-peril-score-request-schema.json)
- [insurance-analytics-peril-score-response-schema.json](json-schema/insurance-analytics-peril-score-response-schema.json)
- [insurance-analytics-claims-benchmarks-schema.json](json-schema/insurance-analytics-claims-benchmarks-schema.json)
- [insurance-analytics-address-schema.json](json-schema/insurance-analytics-address-schema.json)
- [insurance-analytics-coordinates-schema.json](json-schema/insurance-analytics-coordinates-schema.json)

### JSON Structure

- [insurance-analytics-property-risk-structure.json](json-structure/insurance-analytics-property-risk-structure.json)
- [insurance-analytics-construction-data-structure.json](json-structure/insurance-analytics-construction-data-structure.json)
- [insurance-analytics-fire-protection-class-structure.json](json-structure/insurance-analytics-fire-protection-class-structure.json)
- [insurance-analytics-claims-benchmarks-structure.json](json-structure/insurance-analytics-claims-benchmarks-structure.json)

### JSON-LD

- [verisk-insurance-analytics-context.jsonld](json-ld/verisk-insurance-analytics-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Verisk Insurance Analytics API](capabilities/shared/insurance-analytics.yaml) — 6 operations for property risk, fire protection class, peril scores, and claims benchmarking

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Insurance Underwriting](capabilities/insurance-underwriting.yaml) | Verisk Insurance Analytics | 6 | Insurance Underwriter, Property Actuary, Catastrophe Risk Manager |

## Vocabulary

- [Verisk Vocabulary](vocabulary/verisk-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 6 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Verisk Spectral Rules](rules/verisk-spectral-rules.yml) — 36 rules across 13 categories enforcing Verisk API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
