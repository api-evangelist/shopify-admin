---
title: "The `orderCancel` mutation now returns a structured `jobResult`"
url: "https://shopify.dev/changelog/the-ordercancel-mutation-now-returns-a-structured-jobresult"
date: "2026-10-01"
feed_url: "https://shopify.dev/changelog/feed/"
---
As of the 2026-10 GraphQL Admin API version, the orderCancel mutation returns a new jobResult field of type OrderCancelJobResult . Order cancellations run asynchronously. The jobResult field provides a structured, cancellation-specific result, including the cancellation status, any errors, and the affected order.
