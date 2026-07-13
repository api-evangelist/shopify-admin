---
title: "`BusinessEntity` now exposes `legalEntityId` in the GraphQL Admin API"
url: "https://shopify.dev/changelog/businessentity-now-exposes-legalentityid-in-the-admin-api"
date: "2026-07-01"
feed_url: "https://shopify.dev/changelog/feed/"
---
As of API version 2026-07 , the BusinessEntity type in the GraphQL Admin API includes a new legalEntityId field. This field returns the stable Central Legal Entity ID from Shopify's Organizations Platform, giving Partners a consistent identifier for the same legal entity across multiple shops, markets, and sales channels. What's new The BusinessEntity type now includes: legalEntityId ( BigInt , nullable): The stable organization-level legal entity identifier.
