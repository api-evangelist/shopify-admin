---
title: "Carrier services will no longer be automatically added to the default shipping profile"
url: "https://shopify.dev/changelog/carrier-services-will-no-longer-be-automatically-added-to-the-default-shipping-profile"
date: "2026-06-26"
feed_url: "https://shopify.dev/changelog/feed/"
---
Starting with GraphQL Admin API version 2026-10, creating a carrier service no longer automatically adds it to the shop’s General shipping profile. This breaking change affects carrier services created using: GraphQL Admin API: carrierServiceCreate REST Admin API: POST /admin/api/{version}/carrier_services.json Previously, active API carrier services created through these APIs were automatically added to eligible shipping zones in the shop’s General shipping profile. In API version 2026-10 and later, creating a carrier service only registers the carrier service.
