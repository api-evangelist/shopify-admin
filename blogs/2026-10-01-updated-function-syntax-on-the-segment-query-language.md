---
title: "Updated function syntax on the segment query language"
url: "https://shopify.dev/changelog/updated-function-syntax-on-the-segment-query-language"
date: "2026-10-01"
feed_url: "https://shopify.dev/changelog/feed/"
---
As of GraphQL Admin API version 2026-10, functions in the segment query language now use the operators MATCHES / NOT MATCHES instead of = true / = false . For example, the previous query shopify_email.opened() = true would now be represented as shopify_email.opened MATCHES () . The parameters for each function have also been expanded to use their own operators.
