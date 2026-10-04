---
title: "Added parseWarnings to ShopifyqlQueryResponse"
url: "https://shopify.dev/changelog/added-parsewarnings-to-shopifyqlqueryresponse"
date: "2026-10-01"
feed_url: "https://shopify.dev/changelog/feed/"
---
Starting in API version 2026-10, the shopifyqlQuery query in the GraphQL Admin API returns a new parseWarnings field on ShopifyqlQueryResponse . This field surfaces non-fatal issues, such as the use of fields scheduled for deprecation, so you can detect and address them proactively. What changed shopifyqlQuery now returns a parseWarnings field alongside your results.
