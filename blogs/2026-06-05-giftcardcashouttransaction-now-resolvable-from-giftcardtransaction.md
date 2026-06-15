---
title: "GiftCardCashOutTransaction is now resolvable from GiftCardTransaction"
url: "https://shopify.dev/changelog/giftcardcashouttransaction-now-resolvable-from-giftcardtransaction"
date: "2026-06-05"
author: ""
feed_url: "https://shopify.dev/changelog"
---
Starting with GraphQL Admin API version 2026-07, a new GiftCardCashOutTransaction type has been introduced to specifically represent gift card balance payouts through point-of-sale systems. Previously, these transactions were classified as GiftCardDebitTransaction in earlier API versions, but developers should now use the __typename field to differentiate cash-out transactions from other transaction types.
