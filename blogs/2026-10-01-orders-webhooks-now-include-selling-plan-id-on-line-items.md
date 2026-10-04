---
title: "Orders webhooks now include selling_plan_id on line items"
url: "https://shopify.dev/changelog/orders-webhooks-now-include-selling_plan_id-on-line-items"
date: "2026-10-01"
feed_url: "https://shopify.dev/changelog/feed/"
---
Line items in Orders webhook payloads now include a selling_plan_id field. This field identifies the selling plan applied to a subscription line item, which helps you avoid extra API calls to look up that information. The change applies to API version 2026-10 and later, and you don’t need to take any action to keep your app working.
