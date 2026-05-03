# Shopify Admin API

The Shopify Admin API provides programmatic access to manage Shopify store administration. It enables app developers and merchants to manage products, customers, orders, inventory, shipping, fulfillment, collections, webhooks, and store settings. The Admin API is available in both REST and GraphQL formats. Shopify is transitioning from REST to GraphQL as the primary API, with GraphQL recommended for all new development.

**Human URL:** [https://shopify.dev/docs/api/admin-rest](https://shopify.dev/docs/api/admin-rest)

## APIs

### Shopify Admin REST API
The Shopify Admin REST API provides access to store resources including products, customers, orders, inventory, and store settings via a RESTful interface.

- **Documentation:** https://shopify.dev/docs/api/admin-rest
- **Authentication:** OAuth (X-Shopify-Access-Token header)
- **Base URL:** `https://{store_name}.myshopify.com/admin/api/2024-10`

### Shopify Admin GraphQL API
The recommended API for building Shopify apps. GraphQL provides efficient data fetching, real-time subscriptions, and access to advanced platform features.

- **Documentation:** https://shopify.dev/docs/api/admin-graphql
- **Explorer:** https://shopify.dev/docs/api/usage/api-exploration/admin-graphiql-explorer

### Shopify Webhooks
Event subscriptions for real-time notifications about store events.

- **Documentation:** https://shopify.dev/docs/api/webhooks

## Artifacts

### OpenAPI Specifications
- [shopify-admin-rest-openapi.yml](openapi/shopify-admin-rest-openapi.yml)

### JSON Schemas
- [shopify-admin-product-schema.json](json-schema/shopify-admin-product-schema.json)
- [shopify-admin-order-schema.json](json-schema/shopify-admin-order-schema.json)
- [shopify-admin-customer-schema.json](json-schema/shopify-admin-customer-schema.json)

### JSON Structure
- [shopify-admin-product-structure.json](json-structure/shopify-admin-product-structure.json)

### JSON-LD Context
- [shopify-admin-context.jsonld](json-ld/shopify-admin-context.jsonld)

### Examples
- [shopify-admin-list-products-example.json](examples/shopify-admin-list-products-example.json)
- [shopify-admin-create-order-example.json](examples/shopify-admin-create-order-example.json)

### Rules
- [shopify-admin-rules.yml](rules/shopify-admin-rules.yml)

### Capabilities
- [store-management.yaml](capabilities/store-management.yaml) — Products, orders, customers, inventory, locations, webhooks, shop settings

### Vocabulary
- [shopify-admin-vocabulary.yml](vocabulary/shopify-admin-vocabulary.yml)

## Maintainers

**Kin Lane** - kin@apievangelist.com
