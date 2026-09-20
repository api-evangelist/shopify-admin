---
title: "family_name is optional for B2B orders in Payments Apps API requests"
url: "https://shopify.dev/changelog/family_name-is-optional-for-b2b-orders-in-payments-apps-api-requests"
date: "2026-09-15"
feed_url: "https://shopify.dev/changelog/feed/"
---
B2B checkout treats the buyer’s surname as optional, so payment session requests for B2B orders can omit family_name in shipping_address and billing_address . This affects payments apps that handle B2B orders through the Payments Apps API and currently require family_name in these addresses. What changed B2B checkout doesn’t require a buyer surname, and the Payments Apps API already accepts payment session requests for B2B orders without family_name in the shipping_address or billing_address .
