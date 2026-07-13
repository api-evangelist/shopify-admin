---
title: "Define and set metafields on inventory transfers in the GraphQL Admin API"
url: "https://shopify.dev/changelog/define-and-set-metafields-on-inventory-transfers-in-the-admin-graphql-api"
date: "2026-06-17"
feed_url: "https://shopify.dev/changelog/feed/"
---
As of GraphQL Admin API version 2026-07 , you can define metafields for inventory transfers and set metafields directly when creating or editing transfers. Use MetafieldOwnerType.TRANSFER with metafield definition mutations to create transfer-specific metafield definitions. You can also pass metafields in the metafields input on the following mutations: inventoryTransferCreate inventoryTransferCreateAsReadyToShip inventoryTransferEdit Duplicating a transfer will also duplicates its metafields on inventoryTransferDuplicate .
