---
title: "`discountedUnitPrice` on `DraftOrderLineItem` Customer Account API deprecation"
url: "https://shopify.dev/changelog/discountedunitprice-on-draftorderlineitem-customer-account-api-deprecation"
date: "2026-07-01"
feed_url: "https://shopify.dev/changelog/feed/"
---
The discountedUnitPrice field on the DraftOrderLineItem object in the Customer Account API is now deprecated. Use approximateDiscountedUnitPrice instead. This new field calculates the discounted total divided by the quantity, resulting in an approximate per-unit price reduction.
