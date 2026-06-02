---
title: "Storefront Catalog MCP now implements UCP"
url: "https://shopify.dev/changelog/storefront-catalog-mcp-now-implements-ucp"
date: "2026-05-30"
feed_url: "https://shopify.dev/changelog/feed/"
---
What’s changing The following UCP catalog tools in Storefront Catalog are now available: - `search_catalog`: Search a store's product catalog with filters, pagination, and buyer context - `lookup_catalog`: Batch lookup products or variants by identifier with inputs correlation - `get_product`: Retrieve full product details with interactive variant selection, availability signals, and more Tool calls can be placed against the https://{storedomain}/api/ucp/mcp endpoint. What you should do The previous search and lookup tools are deprecated in favor of the above tool names and endpoint, as well a
