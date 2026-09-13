---
title: "Customer Address APIs now support countryCode"
url: "https://shopify.dev/changelog/customer-address-apis-now-support-countrycode"
date: "2026-09-08"
feed_url: "https://shopify.dev/changelog/feed/"
---
Starting with Customer Account API version 2026-10, customer address inputs and objects support countryCode . The existing territoryCode field is deprecated but remains fully supported, so current integrations continue working without interruption. Developers should migrate to countryCode when adopting API version 2026-10.
