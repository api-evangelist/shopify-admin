---
title: "Metafields now require a definition to be accessed through the Customer Account API"
url: "https://shopify.dev/changelog/metafields-now-require-a-definition-to-be-accessed-through-the-customer-account-api"
date: "2026-06-16"
feed_url: "https://shopify.dev/changelog/feed/"
---
Starting today, metafields stored on the app resource must have a metafield definition and customer accounts permissions to be accessible through the Customer Account API. Going forward, when calling the Customer Accounts API, app metafields without a definition will no longer return a value. If your app has functionality which depends on these fields, update those metafields to use definitions with the Customer Account API permission to avoid disruption.
