---
title: "Downgrade app access scopes from write to read"
url: "https://shopify.dev/changelog/downgrade-app-access-scopes-from-write-to-read"
date: "2026-10-07"
feed_url: "https://shopify.dev/changelog/feed/"
---
Starting with Admin GraphQL API version 2027-01 , apps that use Shopify-managed installation can call appDowngradeAccessScopes to replace optional write scopes with their matching read scopes. No action is required for existing apps. What changed The mutation affects only the calling app’s installation.
