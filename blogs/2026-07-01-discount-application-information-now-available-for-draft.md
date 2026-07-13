---
title: "Discount application information now available for draft orders on the Customer Account API"
url: "https://shopify.dev/changelog/discount-application-information-now-available-for-draft-orders-on-the-customer-account-api"
date: "2026-07-01"
feed_url: "https://shopify.dev/changelog/feed/"
---
As of GraphQL Customer Account API version 2026-07, draft orders now expose discount applications. You can use the new discountApplications field on DraftOrder to query discounts applied to a draft order, and the new discountAllocations field on DraftOrderLineItem to query how discounts are allocated across line items. For example: query DraftOrderDiscounts($id: ID!) { draftOrder(id: $id) { discountApplications(first: 10) { nodes { __typename ...
