---
title: "New SubscriptionContractCalculation API for subscription management"
url: "https://shopify.dev/changelog/new-subscriptioncontractcalculation-api-for-subscription-management"
date: "2026-10-01"
feed_url: "https://shopify.dev/changelog/feed/"
---
A new SubscriptionContractCalculation API is now available to manage subscriptions. This new API runs subscription contract edits through Shopify's checkout engine, enabling new capabilities: Shopify Functions, including cart transforms and delivery customizations are supported during contract calculations Contract edits align with what the subscriber sees during billing Get a preview of the full calculated contract (totals, delivery options, and warnings) before persisting any changes Developers using the SubscriptionDraft API should migrate to SubscriptionContractCalculation API. The Subscri
