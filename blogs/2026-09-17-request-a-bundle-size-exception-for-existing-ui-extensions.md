---
title: "Request a bundle size exception for existing UI extensions"
url: "https://shopify.dev/changelog/request-a-bundle-size-exception-for-existing-ui-extensions"
date: "2026-09-17"
feed_url: "https://shopify.dev/changelog/feed/"
---
UI extensions using API version 2025-10 or later are limited to a 64 KB compressed JavaScript bundle per extension. Full page customer account extensions may use up to 128 KB. If your extension remains over the limit after optimization, run shopify app build and submit the minified bundle and its esbuild metafile through the bundle size exception form .
