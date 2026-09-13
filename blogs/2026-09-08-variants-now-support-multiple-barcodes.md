---
title: "Variants now support multiple barcodes"
url: "https://shopify.dev/changelog/product-variant-barcode-is-being-replaced-by-barcodes"
date: "2026-09-08"
feed_url: "https://shopify.dev/changelog/feed/"
---
Merchants often sell the same variant under more than one identifier: a manufacturer UPC alongside a private-label EAN, a GTIN, a reissued ISBN, or an ASIN for a marketplace listing. Until now a variant held a single barcode value, so the extras ended up in metafields, tags, or outside Shopify entirely. What's new You can now read a variant's full set from the new barcodes connection on ProductVariant, and write it with the barcodes input on the productSet mutation , productVariantsBulkCreate mutation , and productVariantsBulkUpdate mutation .
