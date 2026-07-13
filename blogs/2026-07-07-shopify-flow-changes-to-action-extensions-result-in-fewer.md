---
title: "Shopify Flow: Changes to Action extensions result in fewer breaking changes"
url: "https://shopify.dev/changelog/shopify-flow-changes-to-action-extensions-result-in-fewer-breaking-changes"
date: "2026-07-07"
feed_url: "https://shopify.dev/changelog/feed/"
---
Your server-side code now has more control over how breaking changes to an action’s configuration fields are handled. Instead of failing validation when there’s a field mismatch, workflows that use older versions of an action will continue to execute, and Shopify will still send the request to the configured endpoint URL. Your server can then decide how to handle schema differences: for example, it can set default values for new required fields, ignore fields that were removed, or reject the request.
