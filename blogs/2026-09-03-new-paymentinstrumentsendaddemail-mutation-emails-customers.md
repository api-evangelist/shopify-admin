---
title: "New paymentInstrumentSendAddEmail mutation emails customers a link to add a payment method for a subscription, order, or draft order"
url: "https://shopify.dev/changelog/new-paymentinstrumentsendaddemail-mutation"
date: "2026-09-03"
feed_url: "https://shopify.dev/changelog/feed/"
---
You can now use the paymentInstrumentSendAddEmail mutation in the GraphQL Admin API to email a customer a link for adding a payment method to a specific resource (for example, a subscription contract). This lets you collect payment details directly from the customer rather than needing them up front, and the link scopes the customer to that specific resource, so they don't need to sign in to their account. The mutation is available as of API version 2026-10.
