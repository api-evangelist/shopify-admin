---
title: "OrderDisplayFulfillmentStatus now returns FULFILLMENT_NOT_REQUIRED for orders with no items to fulfill"
url: "https://shopify.dev/changelog/orderdisplayfulfillmentstatus-now-returns-fulfillmentnotrequired"
date: "2026-07-03"
feed_url: "https://shopify.dev/changelog/feed/"
---
As of API version 2026-10, the OrderDisplayFulfillmentStatus enum can return a new value: FULFILLMENT_NOT_REQUIRED . It is returned for orders that are not fulfilled but have no items remaining to fulfill — for example, an order that was fully cancelled or fully refunded before any items were fulfilled. Previously, these orders returned UNFULFILLED .
