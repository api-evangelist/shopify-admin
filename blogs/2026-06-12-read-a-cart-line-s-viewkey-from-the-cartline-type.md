---
title: "Read a cart line's `viewKey` from the `CartLine` type"
url: "https://shopify.dev/changelog/cart-line-view-key-field"
date: "2026-06-12"
feed_url: "https://shopify.dev/changelog/feed/"
---
The CartLine type now exposes a viewKey field, so you can correlate a returned cart line with the viewKey you sent to cartLinesUpdate and cartLinesRemove . What's new CartLine.viewKey returns the same viewKey your Liquid storefront renders, alongside the existing UUID id . How to use Previously, identifying a line by viewKey was input-only: you could send a viewKey , but the response returned a UUID id with no viewKey to map back.
