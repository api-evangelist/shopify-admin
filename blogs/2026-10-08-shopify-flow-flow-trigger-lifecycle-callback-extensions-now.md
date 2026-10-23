---
title: "Shopify Flow: Flow Trigger Lifecycle Callback extensions now support relative url paths"
url: "https://shopify.dev/changelog/shopify-flow-flow-trigger-lifecycle-callback-extensions-now-support-relative-url-paths"
date: "2026-10-08"
feed_url: "https://shopify.dev/changelog/feed/"
---
What's changed Flow Trigger Lifecycle Callback extensions now support relative URLs in addition to absolute HTTPS URLs. This works similarly to relative URLs with Flow action extensions. Running app dev resolves your relative URL against your development tunnel URL and app deploy resolves against your app's application_url Previously, the URL for Flow trigger lifecycle callback extensions were required to be absolute HTTPS URLs pointing to a web server.
