---
title: "Manage packed product dimensions with the GraphQL Admin API"
url: "https://shopify.dev/changelog/manage-packed-product-dimensions-with-the-graphql-admin-api"
date: "2026-09-29"
feed_url: "https://shopify.dev/changelog/feed/"
---
Starting with GraphQL Admin API version 2027-01 , apps can read and write packed product dimensions using InventoryItemMeasurement.packedDimensions and InventoryItemMeasurementInput.packedDimensions . Shopify uses these measurements for automatic package selection on eligible multi-item orders. What changed The packedDimensions field returns the packed length, width, height, and unit for an inventory item.
