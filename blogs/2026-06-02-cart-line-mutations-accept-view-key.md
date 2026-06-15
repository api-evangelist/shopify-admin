---
title: "Identify cart lines by view_key in cartLinesUpdate and cartLinesRemove"
url: "https://shopify.dev/changelog/cart-line-mutations-accept-view-key"
date: "2026-06-02"
author: ""
feed_url: "https://shopify.dev/changelog"
---
The Storefront GraphQL API now allows identifying cart lines using view_key as an alternative to id in the cartLinesUpdate and cartLinesRemove mutations. This provides an additional identifier option while maintaining backward compatibility with existing integrations that use the original id or lineIds parameters.
