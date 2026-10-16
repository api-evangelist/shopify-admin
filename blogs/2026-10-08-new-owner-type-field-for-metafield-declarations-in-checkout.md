---
title: "New `owner_type` field for metafield declarations in Checkout and Customer Account UI extensions, required in 2027-01"
url: "https://shopify.dev/changelog/metafield-owner-types-required-for-checkout-and-customer-account-ui-extensions"
date: "2026-10-08"
feed_url: "https://shopify.dev/changelog/feed/"
---
Starting with API version 2026-10 , Checkout and Customer Account UI extensions can specify an owner_type for each metafield declaration in shopify.extension.toml . Starting with API version 2027-01 , owner_type is required for every metafield declaration, and deployments without it will be blocked. What changed Metafield declarations in [[extensions.metafields]] and [[extensions.targeting.metafields]] accept a new owner_type property.
