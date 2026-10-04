---
title: "Inventory shipment webhooks include inventory transfer IDs"
url: "https://shopify.dev/changelog/inventory-shipment-webhooks-include-inventory-transfer-ids"
date: "2026-10-01"
feed_url: "https://shopify.dev/changelog/feed/"
---
We are introducing the inventory_transfer_id to several inventory_shipment webhook payloads to make it easier for developers to identify which inventory_transfer records, if any, a given shipment is related to. This will ease integration burdens and remove the need for developers to merge the datasets on their end to manually build the links. What changed Introduces an inventory_transfer_id field to the payloads of the following...
