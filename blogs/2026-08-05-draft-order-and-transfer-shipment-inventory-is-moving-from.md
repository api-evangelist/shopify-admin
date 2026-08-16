---
title: "Draft order and transfer/shipment inventory is moving from reserved to committed"
url: "https://shopify.dev/changelog/draft-order-and-transfer-shipment-inventory-is-moving-from-reserved-to-committed"
date: "2026-08-05"
feed_url: "https://shopify.dev/changelog/feed/"
---
We're consolidating how in-progress inventory holds are represented. Inventory that was previously tracked under the reserved quantity state for draft orders, transfers, and shipments is being moved to the committed quantity state. This change aligns these holds with how order inventory is already represented, so that committed reflects all inventory that is spoken for but not yet fulfilled.
