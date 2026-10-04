---
title: "New fiscalDeviceIdentifier field on PointOfSaleDevice"
url: "https://shopify.dev/changelog/new-fiscaldeviceidentifier-field-on-pointofsaledevice"
date: "2026-10-01"
feed_url: "https://shopify.dev/changelog/feed/"
---
As of the 2026-10 GraphQL Admin API version, the PointOfSaleDevice object includes a new fiscalDeviceIdentifier field. This field returns the Shopify-assigned fiscal register identifier (manufacturing number) for a POS device. You only need to adopt it if your app supports in-person fiscal compliance workflows.
