---
title: "Delivery options in Shopify Functions input now expose their metafields"
url: "https://shopify.dev/changelog/delivery-options-in-shopify-functions-input-now-expose-their-metafields"
date: "2026-09-15"
feed_url: "https://shopify.dev/changelog/feed/"
---
Shopify Functions can now read metafields attached to delivery options in the cart. On API version 2026-10 , you can call metafield(namespace:, key:) on any option in cart.deliveryGroups.deliveryOptions . This affects apps that build Delivery Customization Functions and any other function whose input includes delivery options.
