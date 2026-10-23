---
title: "Identify the published version running in a POS extension"
url: "https://shopify.dev/changelog/identify-the-published-version-running-in-a-pos-extension"
date: "2026-10-12"
feed_url: "https://shopify.dev/changelog/feed/"
---
What changed shopify.extension.version returns the version of the extension that is running. It’s the same name shown on the Versions page in the Dev Dashboard and chosen when running shopify app deploy. The value is an opaque name, not a version number, so compare it for equality rather than sorting it.
