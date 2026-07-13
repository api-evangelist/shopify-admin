---
title: "Buy Shipping Labels with the GraphQL Admin API"
url: "https://shopify.dev/changelog/label-purchase-mutation"
date: "2026-06-17"
feed_url: "https://shopify.dev/changelog/feed/"
---
New shippingLabelPurchase mutation in the GraphQL Admin API The GraphQL Admin API now includes the shippingLabelPurchase mutation, which lets apps purchase Shopify Shipping labels for eligible fulfillment orders. Apps can provide the fulfillment order, shipping date and time, package details, total weight, customer notification preference, and optional preferred carrier/service selection. If a preferred rate isn't provided, Shopify selects the cheapest available rate.
