---
title: "POS Extensions now supports a background extension target"
url: "https://shopify.dev/changelog/pos-extensions-now-supports-a-background-extension-target"
date: "2026-07-09"
feed_url: "https://shopify.dev/changelog/feed/"
---
The pos.app.ready.data target runs for the entire POS session, letting your extension observe POS events and run background logic without rendering any UI surface. Use it for event observation, data storage, and calling non-visual background APIs. What you need to do Subscribe to Shopify POS events with shopify.addEventListener() : shopify.addEventListener('transactioncomplete', (event) => { console.log('Transaction complete', event); }); Supported events Supported events include: transactioncomplete cashtrackingsessionstart cashtrackingsessioncomplete For comprehensive details and best practi
