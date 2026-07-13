---
title: "New `lineItem` field on the `GiftCard` object"
url: "https://shopify.dev/changelog/new-lineitem-field-on-the-giftcard-graphql-object"
date: "2026-07-01"
feed_url: "https://shopify.dev/changelog/feed/"
---
The GraphQL Admin API's GiftCard object now includes a lineItem field, representing the LineItem from the order that initiated the gift card's creation. The field returns null for gift cards that were issued manually instead of through an order.
