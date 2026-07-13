---
title: "New purchaseType and recurringCycleLimit fields in the discounts API for discount UI extensions"
url: "https://shopify.dev/changelog/new-purchasetype-and-recurringcyclelimit-fields-available-in-the-discount-ui-extension-api"
date: "2026-06-17"
feed_url: "https://shopify.dev/changelog/feed/"
---
You can now configure purchaseType and recurringCycleLimit for app discounts directly from discount UI extensions using the discounts plugin. Previously, these fields were only accessible through the GraphQL Admin API. App developers building discount UI extensions had no way to let merchants control whether a discount applies to one-time purchases, subscriptions, or both, or how many subscription billing cycles a discount should apply to.
