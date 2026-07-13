---
title: "Draft order deposit fields are now available in the GraphQL Admin API and Customer Account API"
url: "https://shopify.dev/changelog/draft-order-deposit-fields-now-available-in-the-admin-and-customer-account-graphql-apis"
date: "2026-07-01"
feed_url: "https://shopify.dev/changelog/feed/"
---
As of the 2026-07 API version, draft order deposit fields are available in the GraphQL Admin API and Customer Account API. Apps can now set a deposit when creating or updating a draft order with DraftOrderInput.deposit in the GraphQL Admin API. This supports draft order flows where part of the payment is due at checkout and the remaining balance is due later, such as due-on-fulfillment payment terms.
