---
title: "Local currency support gift cards now available in the GraphQL Admin API"
url: "https://shopify.dev/changelog/gift-card-local-currency-support"
date: "2026-06-05"
author: ""
feed_url: "https://shopify.dev/changelog"
---
Starting in API version 2026-07, the GraphQL Admin API now supports local currency gift cards, allowing developers to create gift card products issued in a specific currency and control whether buyers can redeem those gift cards across currencies. Apps that directly create gift cards must migrate from the deprecated initialValue field to the new initialAmount field.
