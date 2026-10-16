---
title: "Per-customer request limit for the Customer Account API"
url: "https://shopify.dev/changelog/per-customer-request-limit-for-the-customer-account-api"
date: "2026-10-07"
feed_url: "https://shopify.dev/changelog/feed/"
---
The Customer Account API now enforces a per-customer rate limit of 3000 requests per minute per store, shared across all apps. This affects all apps that call the Customer Account API, but you typically don't need to make changes because normal buyer traffic stays well under this limit. What changed The Customer Account API now limits each customer on a store to 3000 requests per minute.
