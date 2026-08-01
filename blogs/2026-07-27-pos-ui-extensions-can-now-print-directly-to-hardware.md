---
title: "POS UI extensions can now print directly to hardware receipt printers"
url: "https://shopify.dev/changelog/pos-ui-extensions-can-now-print-directly-to-hardware-receipt-printers"
date: "2026-07-27"
feed_url: "https://shopify.dev/changelog/feed/"
---
POS UI Extensions 2026-07 introduces the Printing API ( shopify.printing ), which enables extensions to discover hardware printers with getPrinters() and send documents directly to a connected receipt printer with print() . The Printing API supersedes shopify.print , which is now deprecated. No immediate action is required; plan to migrate when you adopt 2026-07 .
