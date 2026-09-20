---
title: "Dynamic complexity cost for `metafieldsSet` mutation"
url: "https://shopify.dev/changelog/dynamic-complexity-cost-for-metafieldsset-mutation"
date: "2026-09-15"
feed_url: "https://shopify.dev/changelog/feed/"
---
The metafieldsSet mutation now uses dynamic complexity costing. Instead of a flat cost for every call, a request's cost reflects how many distinct resources metafields were changed. Most apps need no changes, as updating a single resource remains cheap.
