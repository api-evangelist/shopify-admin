---
title: "Purchase-type filtering now enforced for app discounts"
url: "https://shopify.dev/changelog/purchase-type-filtering-now-enforced-for-app-discounts"
date: "2026-06-17"
feed_url: "https://shopify.dev/changelog/feed/"
---
The appliesOnSubscription and appliesOnOneTimePurchase fields on app discounts are now enforced at checkout. Previously, these fields existed on DiscountCodeAppInput and DiscountAutomaticAppInput but had no effect. All app discounts applied to every line item regardless of purchase type.
