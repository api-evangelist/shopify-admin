# Shopify Admin API

**URL:** [https://raw.githubusercontent.com/api-evangelist/shopify-admin/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/shopify-admin/refs/heads/main/apis.yml)

The Shopify Admin API provides programmatic access to manage Shopify store administration. It enables app developers and merchants to manage products, customers, orders, inventory, shipping, fulfillment, collections, webhooks, and store settings. The Admin API is available in both REST and GraphQL formats. Shopify is transitioning from REST to GraphQL as the primary API, with GraphQL recommended for all new development.

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs

### Shopify Admin REST API

The Shopify Admin REST API lets you build apps and integrations that extend and enhance the Shopify admin. Provides access to products, customers, orders, inventory, fulfillment, shipping, and store configuration via a RESTful interface.

**Human URL:** [https://shopify.dev/docs/api/admin-rest](https://shopify.dev/docs/api/admin-rest)
**Base URL:** `https://{store_name}.myshopify.com/admin/api/2024-10`

#### Tags

Commerce, Ecommerce, Admin, REST, Products, Orders, Customers

#### Properties

- [Documentation](https://shopify.dev/docs/api/admin-rest)
- [Reference](https://shopify.dev/docs/api/admin-rest/latest)
- [Authentication](https://shopify.dev/docs/apps/auth/get-access-tokens)
- [Rate Limits](https://shopify.dev/docs/api/usage/rate-limits)
- [Versioning](https://shopify.dev/docs/api/usage/versioning)
- [OpenAPI](openapi/shopify-admin-rest-openapi.yml)
- [Spectral Rules](rules/shopify-admin-rules.yml)
- [Capabilities](capabilities/store-management.yaml)

---

### Shopify Admin GraphQL API

The recommended API for building Shopify apps. GraphQL provides efficient data fetching with precise field selection, real-time subscriptions, and access to advanced platform features not available in REST.

**Human URL:** [https://shopify.dev/docs/api/admin-graphql](https://shopify.dev/docs/api/admin-graphql)
**Base URL:** `https://{store_name}.myshopify.com/admin/api/2024-10/graphql.json`

#### Tags

Commerce, Ecommerce, Admin, GraphQL, Products, Orders, Customers

#### Properties

- [Documentation](https://shopify.dev/docs/api/admin-graphql)
- [Reference](https://shopify.dev/docs/api/admin-graphql/latest)
- [GraphiQL Explorer](https://shopify.dev/docs/api/usage/api-exploration/admin-graphiql-explorer)

---

### Shopify Webhooks

Shopify webhooks allow apps to subscribe to specific events that occur in a store. When an event occurs, Shopify sends an HTTP POST request with a JSON payload to the configured endpoint.

**Human URL:** [https://shopify.dev/docs/api/webhooks](https://shopify.dev/docs/api/webhooks)

#### Tags

Commerce, Ecommerce, Webhooks, Events

---

## Common Properties

- [Developer Documentation](https://shopify.dev/docs/api)
- [Authentication Guide](https://shopify.dev/docs/apps/auth/get-access-tokens)
- [Rate Limits](https://shopify.dev/docs/api/usage/rate-limits)
- [API Versioning](https://shopify.dev/docs/api/usage/versioning)
- [Changelog](https://shopify.dev/changelog)
- [Developer Blog](https://shopify.dev/blog)
- [GitHub](https://github.com/Shopify)

## Artifacts

### OpenAPI Specifications

| File | Description |
|------|-------------|
| [shopify-admin-rest-openapi.yml](openapi/shopify-admin-rest-openapi.yml) | Shopify Admin REST API 2024-10 — products, customers, orders, inventory, locations, webhooks, and shop settings |

### JSON Schemas

| File | Description |
|------|-------------|
| [shopify-admin-product-schema.json](json-schema/shopify-admin-product-schema.json) | JSON Schema for the Shopify Product resource |
| [shopify-admin-order-schema.json](json-schema/shopify-admin-order-schema.json) | JSON Schema for the Shopify Order resource |
| [shopify-admin-customer-schema.json](json-schema/shopify-admin-customer-schema.json) | JSON Schema for the Shopify Customer resource |

### JSON Structures

| File | Description |
|------|-------------|
| [shopify-admin-product-structure.json](json-structure/shopify-admin-product-structure.json) | Field-by-field structural documentation for the Product resource |

### JSON-LD Context

| File | Description |
|------|-------------|
| [shopify-admin-context.jsonld](json-ld/shopify-admin-context.jsonld) | JSON-LD context mapping Shopify Admin vocabulary to schema.org |

### Examples

| File | Description |
|------|-------------|
| [shopify-admin-list-products-example.json](examples/shopify-admin-list-products-example.json) | Example: List products response |
| [shopify-admin-create-order-example.json](examples/shopify-admin-create-order-example.json) | Example: Create order request/response |

### Rules

| File | Description |
|------|-------------|
| [shopify-admin-rules.yml](rules/shopify-admin-rules.yml) | Spectral ruleset enforcing Shopify Admin REST API conventions |

### Capabilities

| File | Description |
|------|-------------|
| [capabilities/store-management.yaml](capabilities/store-management.yaml) | Unified store management workflow — products, orders, customers, inventory, locations, webhooks, and shop settings |
| [capabilities/shared/shopify-admin-rest.yaml](capabilities/shared/shopify-admin-rest.yaml) | Shared per-API Naftiko consumed definition for the Shopify Admin REST API |

### Vocabulary

| File | Description |
|------|-------------|
| [shopify-admin-vocabulary.yml](vocabulary/shopify-admin-vocabulary.yml) | Domain vocabulary for Shopify store administration, commerce, and ecommerce concepts |

## Maintainers

**Email:** kin@apievangelist.com
