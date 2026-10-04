---
title: "Manage packed product dimensions with the Admin GraphQL API"
url: "https://shopify.dev/changelog/manage-packed-product-dimensions-with-the-admin-graphql-api"
date: "2026-09-29"
feed_url: "https://shopify.dev/changelog/feed/"
---
Starting with the 2027-01 Admin GraphQL API version, apps can read and write packed product dimensions using InventoryItemMeasurement.packedDimensions and InventoryItemMeasurementInput.packedDimensions in the Admin GraphQL API. Shopify uses these measurements for automatic package selection on eligible multi-item orders. What changed The packedDimensions field returns the packed length, width, height, and unit for an inventory item.
