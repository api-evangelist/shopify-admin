---
title: "Updates to Events payloads and subscription configuration"
url: "https://shopify.dev/changelog/updates-to-events-payloads-and-subscription-configuration"
date: "2026-09-16"
feed_url: "https://shopify.dev/changelog/feed/"
---
Starting today, we're updating Events payloads, trigger syntax, and delivery headers. Classic Webhook subscriptions are unaffected. What's changed fields_changed now describes how each path changed The flat array becomes an object containing three arrays: added , updated , and removed .
