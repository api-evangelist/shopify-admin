---
title: "Detect when a POS extension screen finishes navigating"
url: "https://shopify.dev/changelog/detect-when-a-pos-extension-screen-finishes-navigating"
date: "2026-10-12"
feed_url: "https://shopify.dev/changelog/feed/"
---
What changed The POS Navigation API adds the navigatesuccess event. It fires after the destination screen finishes its native transition, and its callback receives a standard Event. currententrychange can fire before the screen finishes appearing, and the navigate() promise doesn’t wait for the transition.
