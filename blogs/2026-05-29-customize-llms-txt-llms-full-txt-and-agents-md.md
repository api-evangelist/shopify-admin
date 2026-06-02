---
title: "Customize /llms.txt, /llms-full.txt and /agents.md"
url: "https://shopify.dev/changelog/customize-llmstxt-llms-fulltxt-and-agentsmd"
date: "2026-05-29"
feed_url: "https://shopify.dev/changelog/feed/"
---
Your store includes a default agents.md file accessible at /agents.md . The paths /llms.txt and /llms-full.txt also point to this content by default. Add any of the following templates under Online Store > Themes > Edit code to serve different content per path: templates/agents.md.liquid — controls /agents.md (and the default for the other two paths) templates/llms.txt.liquid — controls /llms.txt only templates/llms-full.txt.liquid — controls /llms-full.txt only If no template is present for a given path, it falls back to your agents.md template, then to the Shopify-generated default.
