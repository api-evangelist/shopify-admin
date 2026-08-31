---
title: "GitHub commits now name the last theme editor"
url: "https://shopify.dev/changelog/github-commits-now-name-the-last-theme-editor"
date: "2026-08-26"
feed_url: "https://shopify.dev/changelog/feed/"
---
When you edit a theme in the Shopify admin, the commit Shopify pushes to your connected branch now includes the editor's name in the body: Update from Shopify for theme Dawn Committed from shop: Snowdevil Theme last edited by: Bob Bobsen The name is plain text in the commit body. The commit author is still the shopify bot, so git blame and the commit avatar don't change. Edits saved within about 10 seconds of each other are batched into one commit, and the body names whoever saved last.
