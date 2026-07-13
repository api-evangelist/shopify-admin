---
title: "Flow action extensions now support relative paths for endpoint URLs"
url: "https://shopify.dev/changelog/flow-action-extensions-now-support-relative-paths-for-endpoint-urls"
date: "2026-06-18"
feed_url: "https://shopify.dev/changelog/feed/"
---
You can now use relative paths for endpoint URLs in your Flow action extension configuration . The runtime_url , validation_url , config_page_url , and config_page_preview_url properties accept either an absolute HTTPS URL, such as https://example.com/api/flow/actions/place-bid , or a relative path that starts with a single / , such as /api/flow/actions/place-bid . When you use a relative path, Shopify CLI resolves it against your development tunnel URL while shopify app dev is running, and against your app’s application_url after you deploy.
