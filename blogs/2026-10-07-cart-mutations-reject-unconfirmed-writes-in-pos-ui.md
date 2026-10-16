---
title: "Cart mutations reject unconfirmed writes in POS UI extensions 2026-10"
url: "https://shopify.dev/changelog/cart-mutations-reject-unconfirmed-writes-in-pos-ui-extensions-2026-10"
date: "2026-10-07"
feed_url: "https://shopify.dev/changelog/feed/"
---
In POS UI extensions API version 2026-10 , Cart API mutations reject when Shopify POS doesn't confirm that the cart changed. In earlier versions these mutations resolve whether or not POS applied the write. This is a breaking change for apps that adopt 2026-10 , and those apps need to handle a rejected promise on every cart mutation they call.
