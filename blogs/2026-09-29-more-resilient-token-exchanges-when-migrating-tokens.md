---
title: "More resilient token exchanges when migrating tokens without a user session"
url: "https://shopify.dev/changelog/more-resilient-token-exchanges-when-migrating-tokens-without-a-user-session"
date: "2026-09-29"
feed_url: "https://shopify.dev/changelog/feed/"
---
More resilient token exchanges when migrating to expiring offline access tokens When you migrate an app from non-expiring offline tokens to expiring offline access tokens without a user session, you can now recover a lost migration response by retrying the exchange with the original non-expiring token for up to seven days. This reduces how often you need a merchant to reopen the app to restore access, but you don’t need to change existing flows to keep them working. What changed When you migrate an existing non-expiring offline token to an expiring offline access token without a user session, 
