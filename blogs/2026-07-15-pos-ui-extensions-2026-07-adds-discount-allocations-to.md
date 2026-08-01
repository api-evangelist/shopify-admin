---
title: "POS UI Extensions 2026-07 adds discount allocations to bundle components"
url: "https://shopify.dev/changelog/pos-ui-extensions-2026-07-adds-discount-allocations-to-bundle-components"
date: "2026-07-15"
feed_url: "https://shopify.dev/changelog/feed/"
---
Starting with POS UI Extensions API version 2026-07, product bundle components in cart line item data include discount allocation details. Apps can access component-level discount allocations from bundle components on a cart line item, for example: shopify.cartLineItem.components?.[0]?.discountAllocations The same LineItem shape is also used in Cart API cart state, so apps that read line items from shopify.cart.current.value.lineItems can access component discount allocations on bundle components there as well. Previously, POS UI Extensions exposed discount allocations on the parent line item 
