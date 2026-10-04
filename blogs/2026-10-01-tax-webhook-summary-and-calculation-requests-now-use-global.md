---
title: "Tax webhook summary and calculation requests now use Global IDs"
url: "https://shopify.dev/changelog/tax-webhook-summary-and-calculation-requests-now-use-global-ids"
date: "2026-10-01"
feed_url: "https://shopify.dev/changelog/feed/"
---
Starting with API version 2027-01, third-party tax apps will receive Global IDs (GIDs) in tax calculation requests and tax summary webhook payloads for all entity references of the summary section. This aligns with how Partners interact with other Shopify APIs. These apps can now use the same identifiers across all Shopify endpoints without managing different ID formats for tax-specific integrations.
