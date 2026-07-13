---
title: "Payment mandates now expose an id field"
url: "https://shopify.dev/changelog/payment-mandates-id-field"
date: "2026-06-27"
feed_url: "https://shopify.dev/changelog/feed/"
---
In API version 2026-07 and later, the PaymentMandateResource object includes a new id field. PaymentMandateResource is returned by the mandates connection on CustomerPaymentMethod . Its id is the same as the corresponding CustomerPaymentMethod.id , which lets you determine which payment method to use for a given mandate scope (for example, the SUBSCRIPTIONS scope) when a single payment instrument is associated with multiple mandate types.
