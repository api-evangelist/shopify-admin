---
title: "`metafieldInteger` collection condition removed in API version 2027-01"
url: "https://shopify.dev/changelog/metafieldinteger-collection-condition-removed-in-api-version-2027-01"
date: "2026-10-01"
feed_url: "https://shopify.dev/changelog/feed/"
---
As of API version 2027-01 , the metafieldInteger collection source condition inputs and types is removed from GraphQL Admin API. If you use metafieldInteger to create or read collection source conditions, you need to migrate to metafieldInt before you upgrade to API version 2027-01 . What changed With metafieldInt , the value field on integer metafield conditions changes type from Int to String , to align with the metafield value field on the Storefront API.
