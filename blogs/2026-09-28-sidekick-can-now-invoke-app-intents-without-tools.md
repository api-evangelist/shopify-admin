---
title: "Sidekick can now invoke app intents without tools"
url: "https://shopify.dev/changelog/sidekick-can-now-invoke-app-intents-without-tools"
date: "2026-09-28"
feed_url: "https://shopify.dev/changelog/feed/"
---
Sidekick now surfaces app extensions that declare only intents , with no tools file. Previously an extension had to declare tools to be eligible for Sidekick, so an admin.app.intent.link or admin.app.intent.render extension that registered only an intent was skipped and Sidekick never suggested the app. This applies to all apps on all stores, with no API version to target and nothing to opt into.
