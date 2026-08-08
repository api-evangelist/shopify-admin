---
title: "The `orderCreate` mutation now supports multiple tracking numbers for each fulfillment"
url: "https://shopify.dev/changelog/order-create-fulfillment-tracking-numbers"
date: "2026-08-03"
feed_url: "https://shopify.dev/changelog/feed/"
---
We’ve added a trackingNumbers field to OrderCreateFulfillmentInput , so you can attach multiple tracking numbers to a fulfillment when importing orders. If you use the orderCreate mutation to import orders that ship in more than one package, you no longer need to update the fulfillment after creation to add additional tracking numbers. Instead, you can include all tracking numbers upfront when you create the order.
