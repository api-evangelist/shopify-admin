---
title: "Card deposit endpoint now requires mTLS certificate"
url: "https://shopify.dev/changelog/card-deposit-endpoint-now-requires-mtls-certificate"
date: "2026-07-16"
feed_url: "https://shopify.dev/changelog/feed/"
---
Shopify's card-deposit endpoint now requires a Shopify-issued mTLS client certificate. Apps that store cardholder data with the customerPaymentMethodCreditCardCreate and customerPaymentMethodCreditCardUpdate GraphQL Admin API mutations must first deposit that data at Shopify's /sessions card-deposit endpoint to receive a session identifier. That deposit call must present a Shopify-issued certificate by October 15, 2026 .
