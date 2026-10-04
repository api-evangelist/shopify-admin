---
title: "Removing marketCurrencySettingsUpdate mutation"
url: "https://shopify.dev/changelog/removing-marketcurrencysettingsupdate-mutation"
date: "2026-09-22"
feed_url: "https://shopify.dev/changelog/feed/"
---
As of GraphQL Admin API version 2027-01 , the marketCurrencySettingsUpdate mutation is removed, along with the MarketCurrencySettingsUpdatePayload , MarketCurrencySettingsUserError , and MarketCurrencySettingsUserErrorCode types. The mutation already returns an error for every request, so this removes an endpoint that can no longer be used. What's changed In API version 2027-01 , the Admin GraphQL API removes: marketCurrencySettingsUpdate MarketCurrencySettingsUpdatePayload MarketCurrencySettingsUserError MarketCurrencySettingsUserErrorCode The mutation was deprecated when Markets Home launche
