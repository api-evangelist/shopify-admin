---
title: "Standard storefront events and actions now support cart attributes"
url: "https://shopify.dev/changelog/events-and-actions-cart-attributes-support"
date: "2026-08-06"
feed_url: "https://shopify.dev/changelog/feed/"
---
The updateCart standard action now updates cart attributes, and a new shopify:cart:attributes-update event fires whenever an attributes update is initiated. Before this, changing an attribute meant calling the Storefront API yourself, and nothing told your app when one changed. The action now handles attributes like any other cart update, and the event fires whether your app, the theme, or another app made the change.
