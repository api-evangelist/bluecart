# BlueCart (bluecart)

BlueCart is an end-to-end eCommerce and procurement platform for the hospitality and food and beverage industries, connecting restaurants and buyers with wholesale distributors and suppliers. It streamlines wholesale ordering, order management, inventory, and payments for both sides of the supply chain. BlueCart exposes a public REST API that lets distributors and partners programmatically manage products, orders, customers, catalogs, and users, returning JSON responses and integrating BlueCart data with external accounting, eCommerce, and logistics systems used across foodservice operations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/bluecart/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/bluecart/refs/heads/main/apis.yml)

## Scope

- **Type:** Company

## Tags

- Restaurant
- Procurement
- Wholesale
- Ordering
- Food Distribution
- Hospitality
- eCommerce

## Timestamps

- **Created:** 2026-06-02
- **Modified:** 2026-06-02

## APIs

### BlueCart API

The BlueCart API is defined using REST with predictable, resource-oriented URLs and returns JSON-encoded responses with standard HTTP status codes. It is authenticated using AWS Signature Version 4 against the AWS execute-api service in the us-east-1 region, requiring an Access Key ID, Secret Access Key, and API Key generated from the BlueCart app under Settings, API Access Credentials. The API operates on one object per request and does not support bulk updates, uses next-token pagination returning 25 items per page on collection endpoints, and ships with a Postman collection to help developers make their first request. It exposes resources for orders, products, catalogs, clients, and users.

- **Human URL:** [https://docs.bluecart.com/](https://docs.bluecart.com/)

#### Tags

- Orders
- Products
- Catalogs
- Clients
- Users
- Procurement

#### Properties

- [Documentation](https://docs.bluecart.com/)
- [Authentication](https://docs.bluecart.com/authentication)
- [Getting Started](https://docs.bluecart.com/running-your-first-request)
- [Pagination](https://docs.bluecart.com/pagination)
- [OpenAPI](openapi/bluecart-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bluecart.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bluecart.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.bluecart.com/)
- [Documentation](https://docs.bluecart.com/)
- [API Reference](https://docs.bluecart.com/endpoints)
- [Authentication](https://docs.bluecart.com/authentication)
- [Pagination](https://docs.bluecart.com/pagination)
- [Support](https://www.bluecart.com/contact)
- [Sign Up](https://www.bluecart.com/)
- [Rules](rules/bluecart-spectral-rules.yml)
- [Vocabulary](vocabulary/bluecart-vocabulary.yaml)
- [JSON-LD](json-ld/bluecart-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Plans](plans/bluecart-plans-pricing.yml)
- [Rate Limits](rate-limits/bluecart-rate-limits.yml)
- [Fin Ops](finops/bluecart-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
