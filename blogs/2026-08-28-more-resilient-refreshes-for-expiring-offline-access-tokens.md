---
title: "More resilient refreshes for expiring offline access tokens"
url: "https://shopify.dev/changelog/more-resilient-refreshes-for-expiring-offline-access-tokens"
date: "2026-08-28"
feed_url: "https://shopify.dev/changelog/feed/"
---
Expiring offline access token refreshes now retain the previously used refresh token until an app begins using its replacement. This rollout helps apps recover when a refresh response is lost or isn’t persisted. No migration is required, but apps should continue to store every refreshed token pair atomically.
