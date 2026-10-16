---
title: "New APIs for buyer-requested order edits"
url: "https://shopify.dev/changelog/new-apis-for-buyer-requested-order-edits"
date: "2026-10-01"
feed_url: "https://shopify.dev/changelog/feed/"
---
You can now manage buyer-requested order edits through the GraphQL Admin API, Customer Account API, and three new webhook topics in API version 2026-10 . Buyers can request the removal of unfulfilled line items from an order, and merchants (or apps acting on their behalf) can review, resolve, or decline those requests. What changed Buyers can now request edits to the unfulfilled line items on an order, and those requests are exposed as a first-class resource, RequestedOrderEdit , across Shopify's APIs.
