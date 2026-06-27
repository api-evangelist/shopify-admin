---
title: "Storefront MCP cart tools are being deprecated in favour of UCP Cart MCP"
url: "https://shopify.dev/changelog/storefront-mcp-cart-tools-are-being-deprecated-in-favour-of-ucp-cart-mcp"
date: "2026-06-24"
feed_url: "https://shopify.dev/changelog/feed/"
---
What's changing The cart tools on the Storefront MCP server are being deprecated in favour of the UCP-conforming Cart MCP tools: get_cart and update_cart on https://{shop}.myshopify.com/api/mcp are deprecated. Cart MCP implements the UCP cart capability ( dev.ucp.shopping.cart , version 2026-04-08 ) and exposes the following tools at the https://{shop-domain}/api/ucp/mcp endpoint: create_cart : Create a new cart with line items and optional buyer context. get_cart : Retrieve the current state of a cart.
