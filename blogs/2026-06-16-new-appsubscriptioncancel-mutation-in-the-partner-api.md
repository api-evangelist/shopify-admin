---
title: "New appSubscriptionCancel mutation in the Partner API"
url: "https://shopify.dev/changelog/new-appsubscriptioncancel-mutation-in-the-partner-api"
date: "2026-06-16"
feed_url: "https://shopify.dev/changelog/feed/"
---
Starting with API version 2026-07, Partner API clients can use the new appSubscriptionCancel mutation to cancel app subscriptions for public apps they own. The mutation supports: Immediate cancellation Deferred cancellation at the end of the current billing cycle Requesting prorated credits, when applicable Optionally skipping the final usage charge for usage-billed subscriptions This mutation is available to Partner API clients that have the View financials permission in the Partner Dashboard. Learn more in the Partner API 2026-07 documentation .
