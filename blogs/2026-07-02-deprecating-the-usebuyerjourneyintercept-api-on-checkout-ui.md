---
title: "Deprecating the useBuyerJourneyIntercept API on checkout UI extensions"
url: "https://shopify.dev/changelog/deprecating-the-usebuyerjourneyintercept-api-on-checkout-ui-extensions"
date: "2026-07-02"
feed_url: "https://shopify.dev/changelog/feed/"
---
Starting in version 2026-07 , the useBuyerJourneyIntercept hook on checkout UI extensions, and the block_progress capability it depends on, are deprecated. Existing extensions will continue to work on current and prior API versions, but this API will be removed in a future version , so you should plan to migrate. The following are deprecated: useBuyerJourneyIntercept (Preact hook) in checkout UI extensions The block_progress capability in the extension’s shopify.extension.toml configuration file If you currently use useBuyerJourneyIntercept to enforce merchant business rules, migrate to a cart
