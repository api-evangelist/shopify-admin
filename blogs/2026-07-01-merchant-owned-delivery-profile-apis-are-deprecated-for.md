---
title: "Merchant-owned delivery profile APIs are deprecated for market-driven shipping"
url: "https://shopify.dev/changelog/merchant-owned-delivery-profile-apis-are-deprecated-for-market-driven-shipping"
date: "2026-07-01"
feed_url: "https://shopify.dev/changelog/feed/"
---
What's changing We’re moving merchant-owned shipping configuration from legacy delivery profiles to Markets as part of market-driven shipping, a new model where shipping is configured per Market. When a shop uses market-driven shipping, the legacy delivery profile fields and mutations in the Admin GraphQL API no longer represent the shop’s live merchant-owned shipping configuration. Reads may return a stale snapshot of the legacy configuration, and writes may succeed without errors but will not update the merchant’s live shipping settings.
