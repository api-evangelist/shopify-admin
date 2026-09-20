---
title: "Removed session.currentSession.staffMemberId from POS UI Extensions (2026-10)"
url: "https://shopify.dev/changelog/removed-session-currentsession-staffmemberid-from-pos-ui-extensions-2026-10"
date: "2026-09-17"
feed_url: "https://shopify.dev/changelog/feed/"
---
As of API version 2026-10, the static session.currentSession.staffMemberId field has been removed from the POS UI Extensions Session API. It was deprecated in 2026-07 in favour of session.staffMember, a reactive signal that updates when a different staff member pins into POS. Before targeting API version 2026-10, replace reads of session.currentSession.staffMemberId with session.staffMember.value?.id.
