---
title: "Standard storefront events and actions"
url: "https://shopify.dev/changelog/standard-storefront-events-and-actions"
date: "2026-06-17"
feed_url: "https://shopify.dev/changelog/feed/"
---
Liquid storefronts now have a standard communication layer between themes and the code that runs on them. Themes emit events, while apps and agents call actions. Both work across all themes, and they ship together so you implement only once: Events are DOM events for commerce interactions: shopify:product:view , shopify:cart:lines-update , shopify:search:update , and others.
