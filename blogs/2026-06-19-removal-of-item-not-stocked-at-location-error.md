---
title: "Removal of ITEM_NOT_STOCKED_AT_LOCATION error"
url: "https://shopify.dev/changelog/removal-of-itemnotstockedatlocation-error"
date: "2026-06-19"
feed_url: "https://shopify.dev/changelog/feed/"
---
The ITEM_NOT_STOCKED_AT_LOCATION error will be removed from InventoryAdjustQuantities , InventoryMoveQuantities , InventorySetOnHandQuantities , and InventorySetQuantitiesUserErrorCode as of API version 2026-10. Following the changes described here , inventory quantities can now be adjusted at any location. As a result, the condition that previously triggered ITEM_NOT_STOCKED_AT_LOCATION can no longer occur, and this error is no longer emitted.
