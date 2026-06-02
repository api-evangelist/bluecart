# BlueCart (bluecart)

BlueCart is an end-to-end eCommerce and procurement platform for the hospitality and food and beverage industries, connecting restaurants and buyers with wholesale distributors and suppliers. It streamlines wholesale ordering, order management, inventory, and payments for both sides of the supply chain. BlueCart exposes a public REST API that lets distributors and partners programmatically manage products, orders, customers, catalogs, and users, returning JSON responses and integrating BlueCart data with external accounting, eCommerce, and logistics systems used across foodservice operations.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/bluecart/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Restaurant, Procurement, Wholesale, Ordering, Food Distribution, Hospitality, eCommerce

## Timestamps

- **Created:** 2026-06-02
- **Modified:** 2026-06-02

## APIs

### BlueCart API

The BlueCart API is defined using REST with predictable, resource-oriented URLs and returns JSON-encoded responses with standard HTTP status codes. It is authenticated using AWS Signature Version 4 against the AWS execute-api service in the us-east-1 region, requiring an Access Key ID, Secret Access Key, and API Key generated from the BlueCart app under Settings, API Access Credentials. The API operates on one object per request and does not support bulk updates, uses next-token pagination returning 25 items per page on collection endpoints, and ships with a Postman collection to help developers make their first request. It exposes resources for orders, products, catalogs, clients, and users.

**Human URL:** [https://docs.bluecart.com/](https://docs.bluecart.com/)

#### Tags:

 - Orders, Products, Catalogs, Clients, Users, Procurement

#### Properties

- [Documentation](https://docs.bluecart.com/)
- [Authentication](https://docs.bluecart.com/authentication)
- [GettingStarted](https://docs.bluecart.com/running-your-first-request)
- [Pagination](https://docs.bluecart.com/pagination)
- [OpenAPI](openapi/bluecart-openapi.yml)
- [NaftikoCapability](capabilities/bluecart-orders.yaml)
- [NaftikoCapability](capabilities/bluecart-products.yaml)
- [NaftikoCapability](capabilities/bluecart-catalogs.yaml)
- [NaftikoCapability](capabilities/bluecart-clients.yaml)
- [NaftikoCapability](capabilities/bluecart-users.yaml)

## Common Properties

- [Website](https://www.bluecart.com/)
- [Documentation](https://docs.bluecart.com/)
- [APIReference](https://docs.bluecart.com/endpoints)
- [Authentication](https://docs.bluecart.com/authentication)
- [Pagination](https://docs.bluecart.com/pagination)
- [Support](https://www.bluecart.com/contact)
- [SignUp](https://www.bluecart.com/)
- [Rules](rules/bluecart-spectral-rules.yml)
- [Vocabulary](vocabulary/bluecart-vocabulary.yaml)
- [JSONLD](json-ld/bluecart-context.jsonld)
- [Plans](plans/bluecart-plans-pricing.yml)
- [RateLimits](rate-limits/bluecart-rate-limits.yml)
- [FinOps](finops/bluecart-finops.yml)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [BlueCart API](openapi/bluecart-openapi.yml) — 11 paths, 22 operations, 20 component schemas (generated from docs.bluecart.com)

### JSON Schema

19 standalone JSON Schema files extracted from the OpenAPI components in [`json-schema/`](json-schema/), including Order, Product, Catalog, Client, and User.

### JSON Structure

19 JSON Structure (json-structure.org) representations in [`json-structure/`](json-structure/), converted from the JSON Schema files.

### JSON-LD

- [BlueCart Context](json-ld/bluecart-context.jsonld) — Linked-data context aligning BlueCart properties with schema.org and XSD datatypes.

### Examples

19 example payloads in [`examples/`](examples/), one per schema.

## Capabilities

Naftiko capabilities, one self-contained file per business surface (OpenAPI tag), each exposing both a REST and an MCP adapter.

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [BlueCart — Orders](capabilities/bluecart-orders.yaml) | BlueCart API | 4 | Distributor Operations, Buyer Procurement |
| [BlueCart — Products](capabilities/bluecart-products.yaml) | BlueCart API | 5 | Catalog Manager |
| [BlueCart — Catalogs](capabilities/bluecart-catalogs.yaml) | BlueCart API | 5 | Catalog Manager, Sales Rep |
| [BlueCart — Clients](capabilities/bluecart-clients.yaml) | BlueCart API | 3 | Sales Rep, Distributor Operations |
| [BlueCart — Users](capabilities/bluecart-users.yaml) | BlueCart API | 5 | Account Administrator |

## Vocabulary

- [BlueCart Vocabulary](vocabulary/bluecart-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 9 actions, 5 workflows, and 5 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [BlueCart Spectral Rules](rules/bluecart-spectral-rules.yml) — 38 rules across metadata, paths, operations, tags, parameters, responses, schemas, security, and HTTP method conventions enforcing BlueCart API conventions.

## Commercial

- [Plans / Pricing](plans/bluecart-plans-pricing.yml) — Subscription tiers (sales-led; third-party-reported figures, unverified).
- [Rate Limits](rate-limits/bluecart-rate-limits.yml) — AWS API Gateway throttling and 25-item next-token pagination (numeric limits not published).
- [FinOps](finops/bluecart-finops.yml) — FOCUS-aligned subscription billing model.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
