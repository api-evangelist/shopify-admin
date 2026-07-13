---
title: "POS UI extensions 2026-07 uses per-unit fixed-amount line item discounts"
url: "https://shopify.dev/changelog/pos-ui-extensions-2026-07-uses-per-unit-fixed-amount-line-item-discounts"
date: "2026-07-08"
feed_url: "https://shopify.dev/changelog/feed/"
---
Starting with POS UI extensions API version 2026-07, FixedAmount line item discounts passed to setLineItemDiscount and bulkSetLineItemDiscounts from the Cart API must represent a per-unit discount. Why it's changing In API version 2026-04 and earlier, apps could pass a total fixed discount for the entire line item, and Shopify POS automatically converted it to a per-unit value. In API version 2026-07, this conversion no longer occurs.
