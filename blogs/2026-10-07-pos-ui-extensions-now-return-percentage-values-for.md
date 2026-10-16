---
title: "POS UI extensions now return percentage values for percentage discounts"
url: "https://shopify.dev/changelog/pos-ui-extensions-now-return-percentage-values-for-percentage-discounts"
date: "2026-10-07"
feed_url: "https://shopify.dev/changelog/feed/"
---
Shopify POS 11.15 corrects the value returned by Discount.amount for Percentage discounts to match the Cart API contract. Extensions that used this value as money need to update their logic. What changed A 25% discount on a $200 line item now returns amount: 25 .
