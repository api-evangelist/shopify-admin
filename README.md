# Shopify Admin API (shopify-admin)

The Shopify Admin API provides programmatic access to manage Shopify store administration. It enables app developers and merchants to manage products, customers, orders, inventory, shipping, fulfillment, collections, webhooks, and store settings. The Admin API is available in both REST and GraphQL formats. Shopify is transitioning from REST to GraphQL as the primary API, with GraphQL recommended for all new development.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/shopify-admin/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/shopify-admin/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Commerce
- Ecommerce
- Admin
- Products
- Orders
- Customers

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-30

## APIs

### Shopify Admin REST API

The Shopify Admin REST API lets you build apps and integrations that extend and enhance the Shopify admin. It provides access to products, customers, orders, inventory, fulfillment, shipping, and store configuration. All requests require a valid Shopify access token generated through OAuth. Note: Shopify is deprecating the REST Admin API in favor of GraphQL; new development should use the GraphQL Admin API.

- **Human URL:** [https://shopify.dev/docs/api/admin-rest](https://shopify.dev/docs/api/admin-rest)
- **Base URL:** `https://{store_name}.myshopify.com/admin/api/2024-10`

#### Tags

- Commerce
- Ecommerce
- Admin
- REST
- Products
- Orders
- Customers

#### Properties

- [Documentation](https://shopify.dev/docs/api/admin-rest)
- [Reference](https://shopify.dev/docs/api/admin-rest/latest)
- [Authentication](https://shopify.dev/docs/apps/auth/get-access-tokens)
- [Rate Limits](https://shopify.dev/docs/api/usage/rate-limits)
- [Versioning](https://shopify.dev/docs/api/usage/versioning)
- [OpenAPI](openapi/shopify-admin-rest-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shopify-admin-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shopify-admin-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/shopify-admin-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/shopify-admin-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/shopify-admin-customer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/shopify-admin-product-structure.json)
- [J S O N L D Context](json-ld/shopify-admin-context.jsonld)
- [Spectral Rules](rules/shopify-admin-rules.yml)
- [Capabilities](capabilities/store-management.yaml)
- [Vocabulary](vocabulary/shopify-admin-vocabulary.yml)

### Shopify Admin GraphQL API

The Shopify Admin GraphQL API is the recommended API for building Shopify apps and integrations. It provides access to all Shopify admin resources including products, customers, orders, inventory, fulfillment, and analytics. GraphQL enables efficient data fetching with precise field selection, real-time subscriptions, and access to advanced platform features not available in REST.

- **Human URL:** [https://shopify.dev/docs/api/admin-graphql](https://shopify.dev/docs/api/admin-graphql)
- **Base URL:** `https://{store_name}.myshopify.com/admin/api/2024-10/graphql.json`

#### Tags

- Commerce
- Ecommerce
- Admin
- GraphQL
- Products
- Orders
- Customers

#### Properties

- [Documentation](https://shopify.dev/docs/api/admin-graphql)
- [Reference](https://shopify.dev/docs/api/admin-graphql/latest)
- [Getting Started](https://shopify.dev/docs/api/usage/graphql)
- [Explorer](https://shopify.dev/docs/api/usage/api-exploration/admin-graphiql-explorer)
- [Authentication](https://shopify.dev/docs/apps/auth/get-access-tokens)
- [Rate Limits](https://shopify.dev/docs/api/usage/rate-limits)
- [Postman Collection](collections/shopify-admin-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shopify-admin-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Shopify Webhooks

Shopify webhooks allow apps to subscribe to specific events that occur in a store. When an event occurs, Shopify sends an HTTP POST request with a JSON payload to the configured endpoint. Webhooks can be configured for events across all major Shopify resources including orders, products, customers, inventory, fulfillment, and app-specific events.

- **Human URL:** [https://shopify.dev/docs/api/webhooks](https://shopify.dev/docs/api/webhooks)

#### Tags

- Commerce
- Ecommerce
- Webhooks
- Events

#### Properties

- [Documentation](https://shopify.dev/docs/api/webhooks)
- [Reference](https://shopify.dev/docs/api/webhooks/2024-10)
- [AsyncAPI](asyncapi/shopify-admin-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/shopify-admin-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shopify-admin-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/shopify)
- [Website](https://shopify.dev/)
- [Documentation](https://shopify.dev/docs/api)
- [Authentication](https://shopify.dev/docs/apps/auth/get-access-tokens)
- [Rate Limits](https://shopify.dev/docs/api/usage/rate-limits)
- [Versioning](https://shopify.dev/docs/api/usage/versioning)
- [Changelog](https://shopify.dev/changelog)
- [Blog](https://shopify.dev/blog)
- [Git Hub](https://github.com/Shopify)
- [JSON Schema](json-schema/shopify-admin-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/shopify-admin-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/shopify-admin-customer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/shopify-admin-product-structure.json)
- [J S O N L D Context](json-ld/shopify-admin-context.jsonld)
- [Examples](examples/shopify-admin-list-products-example.json)
- [Examples](examples/shopify-admin-create-order-example.json)
- [Vocabulary](vocabulary/shopify-admin-vocabulary.yml)
- [Spectral Rules](rules/shopify-admin-rules.yml)
- [Capabilities](capabilities/store-management.yaml)
- [Integrations](https://shopify.dev/docs/apps/build)
- [L L Ms Txt](https://shopify.dev/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
