---
title: "New translatable boolean field for Metafield GraphQL Object"
url: "https://shopify.dev/changelog/is-translatable-metafield-field"
date: "2026-09-21"
feed_url: "https://shopify.dev/changelog/feed/"
---
API version 2026-10 adds a non-null translatable field to the Metafield object in the GraphQL Admin API. Apps that fetch translatable metafields and migrate to 2026-10 can now see whether a metafield’s value is translatable directly on the metafield itself. If your app doesn’t query for translatable metafields by shop, you don’t need to change anything.
