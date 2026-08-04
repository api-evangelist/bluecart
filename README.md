# BlueCart (bluecart)

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
