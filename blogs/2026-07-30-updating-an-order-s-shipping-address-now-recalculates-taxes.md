---
title: "Updating an order's shipping address now recalculates taxes"
url: "https://shopify.dev/changelog/updating-an-orders-shipping-address-returns-accurate-financial-data"
date: "2026-07-30"
feed_url: "https://shopify.dev/changelog/feed/"
---
As of August 31, 2026, changing the shipping address on an unfulfilled order through the orderUpdate GraphQL mutation recalculates the order's taxes against the new destination. Previously, orderUpdate saved the new address but left the original tax lines unchanged, so the order's totals no longer matched the destination it was shipping to. Why it matters The order's financial data is now corrected as part of the update, now totals stay accurate to the shipping destination.
