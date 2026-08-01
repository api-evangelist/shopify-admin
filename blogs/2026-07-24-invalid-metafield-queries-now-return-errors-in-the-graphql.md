---
title: "Invalid metafield queries now return errors in the GraphQL Admin API"
url: "https://shopify.dev/changelog/invalid-metafield-queries-now-return-errors-in-the-graphql-admin-api"
date: "2026-07-24"
feed_url: "https://shopify.dev/changelog/feed/"
---
Starting in API version 2026-10, the GraphQL Admin API returns an error when a query filters by a metafield that isn't set up for filtering, instead of silently returning incorrect results. This is a breaking change. It affects apps that filter resources by metafield on version 2026-10 or later, and you'll need to update affected queries before you upgrade.
