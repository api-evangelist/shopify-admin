---
title: "SubscriptionContractCalculation API now available in early access"
url: "https://shopify.dev/changelog/subscription-contract-calculation-api-now-available-in-early-access"
date: "2026-07-27"
feed_url: "https://shopify.dev/changelog/feed/"
---
The new SubscriptionContractCalculation object on the GraphQL Admin API is now available in early access on the 2026-10 release candidate API version. It's the successor to the GraphQL Admin API's SubscriptionDraft object for creating, updating, and editing subscription contracts, replacing the multi-step draft workflow with a stateless calculate → poll → commit lifecycle that runs through Shopify's unified checkout engine. Moving contract edits onto the unified checkout engine keeps calculations consistent with checkout, one calculate mutation replaces 12+ draft mutations, and new checkout ca
