---
title: "Cart updates that result in no changes to the cart no longer trigger carts/update webhooks"
url: "https://shopify.dev/changelog/unchanged-carts-no-longer-trigger-carts-update-webhooks"
date: "2026-10-12"
feed_url: "https://shopify.dev/changelog/feed/"
---
Cart operations that leave the cart unchanged, for example, resubmitting the same values a cart already has, no longer trigger a carts/update webhook. Shopify sends a webhook every time a cart's contents or properties change. Previously, every cart operation produced a carts/update webhook.
