---
title: "Storefront API `@inContext` supports `channelId`"
url: "https://shopify.dev/changelog/new-channelid-argument-for-incontext-directive-in-storefront-api-2026-10"
date: "2026-07-15"
feed_url: "https://shopify.dev/changelog/feed/"
---
As of Storefront API version 2026-10 , the @inContext directive accepts an optional channelId argument. Use channelId to apply a specific sales channel’s context to an entire query, including channel-specific product availability and pricing. Example: query Product($handle: String!, $channelId: ID!) @inContext(channelId: $channelId) { product(handle: $handle) { id title availableForSale priceRange { minVariantPrice { amount currencyCode } } } } Why it's changing The existing @inContext directive lets you set buyer context such as country and language .
