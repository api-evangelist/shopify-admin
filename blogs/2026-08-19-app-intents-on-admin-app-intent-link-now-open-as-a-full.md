---
title: "App intents on `admin.app.intent.link` now open as a full-page navigation"
url: "https://shopify.dev/changelog/app-intents-on-admin-app-intent-link-now-open-as-a-full-page-navigation"
date: "2026-08-19"
feed_url: "https://shopify.dev/changelog/feed/"
---
When Sidekick invokes an app intent declared on the admin.app.intent.link extension target, the Shopify admin now navigates the merchant to your extension's url as a full page, matching how Shopify's own admin intents behave. Previously, the same intent always opened in an overlay on top of the page the merchant was already on. This is live for all shops, isn't gated by API version, and doesn't require any changes to your extension's configuration, intent schema, or tools.
