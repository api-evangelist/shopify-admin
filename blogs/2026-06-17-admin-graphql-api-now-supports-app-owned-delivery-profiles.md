---
title: "Admin GraphQL API now supports app-owned delivery profiles that cover all shippable items"
url: "https://shopify.dev/changelog/admin-graphql-api-now-supports-app-owned-delivery-profiles-that-cover-all-shippable-items"
date: "2026-06-17"
feed_url: "https://shopify.dev/changelog/feed/"
---
As of GraphQL Admin API version 2026-07, app-owned shipping delivery profiles support a new boolean coversAllItems field. Use coversAllItems on app-owned shipping delivery profiles to indicate that a profile applies to every shippable product variant in the store, without explicitly assigning each product or variant to that profile. The field is available on the DeliveryProfile type: query { deliveryProfiles(first: 10) { nodes { id name coversAllItems } } } You can also set coversAllItems through DeliveryProfileInput when creating or updating an app-owned shipping delivery profile: mutation { 
