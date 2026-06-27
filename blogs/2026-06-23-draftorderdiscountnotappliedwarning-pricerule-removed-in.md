---
title: "`DraftOrderDiscountNotAppliedWarning.priceRule` removed in GraphQL Admin API 2026-10"
url: "https://shopify.dev/changelog/remove-pricerule-from-draft-order-discount-warning"
date: "2026-06-23"
feed_url: "https://shopify.dev/changelog/feed/"
---
Starting with GraphQL Admin API version 2026-10 , the deprecated priceRule field on the DraftOrderDiscountNotAppliedWarning object is removed. This is a breaking change for apps that query priceRule on DraftOrderDiscountNotAppliedWarning , which is returned in draft order discount warnings from mutations such as draftOrderCalculate , draftOrderCreate , and draftOrderUpdate . If your app selects priceRule in these responses, you must update those queries before upgrading to 2026-10 .
