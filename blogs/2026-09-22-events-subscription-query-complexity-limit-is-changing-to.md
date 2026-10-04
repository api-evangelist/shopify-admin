---
title: "Events subscription query complexity limit is changing to 100 points"
url: "https://shopify.dev/changelog/events-subscription-query-complexity-limit-is-changing-to-100-points"
date: "2026-09-22"
feed_url: "https://shopify.dev/changelog/feed/"
---
We’re reducing the query complexity limit for Events subscriptions from 250 to 100 points. This change does not affect Classic Webhooks. Shopify assigns each Events query a complexity score based on the fields it selects, the types of data those fields return, and the number of items requested in connections using first or last, following the GraphQL query cost calculation .
