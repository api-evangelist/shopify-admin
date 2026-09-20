---
title: "The `automaticDiscounts` query is removed in API version 2027-01"
url: "https://shopify.dev/changelog/automaticdiscounts-query-is-removed-in-api-version-2027-01"
date: "2026-09-18"
feed_url: "https://shopify.dev/changelog/feed/"
---
The deprecated automaticDiscounts query is removed from the GraphQL Admin API in version 2027-01 . If your app reads a shop’s automatic discounts through automaticDiscounts , you need to move to the discountNodes query with a method:automatic filter before you upgrade to 2027-01 . Apps on 2026-10 and earlier keep working unchanged while those versions are supported.
