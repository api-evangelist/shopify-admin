---
title: "Customer Account API Customer.lastIncompleteCheckout and Checkout types removed in 2026-10"
url: "https://shopify.dev/changelog/customer-account-api-last-incomplete-checkout-and-checkout-types-removed"
date: "2026-07-06"
feed_url: "https://shopify.dev/changelog/feed/"
---
As of Customer Account API version 2026-10, the deprecated Customer.lastIncompleteCheckout field is removed. This also removes the now-unreachable Customer Account API Checkout type subtree, including: Checkout Checkout.appliedGiftCards AppliedGiftCard AvailableShippingRates CheckoutLineItem CheckoutLineItemConnection CheckoutLineItemEdge ShippingRate The Customer.lastIncompleteCheckout field was previously deprecated and returned null . This change removes stale Checkout Classic schema from the Customer Account API.
