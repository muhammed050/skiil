---
name: robots-canonical
description: Control CanliHisse crawling and canonical URL signals safely across public pages, parameters, assets, APIs, and generated routes.
---
# Robots and Canonical

## Robots.txt
Use robots.txt to control crawling, not as a substitute for noindex. Never accidentally block important HTML, CSS, JS, images, stock pages, news, or assets required for rendering.

Keep syntax valid and verify production output. Sitemap declarations must reference the real canonical sitemap URL.

## Canonical
Every indexable page should resolve to one preferred canonical URL. Keep canonical, sitemap, redirects, internal links, and preferred domain consistent.

Do not canonicalize unrelated pages to the homepage. Do not use canonical to hide genuinely different content.

## Parameters
Identify sort, filter, pagination, tracking, search, and session parameters. Decide deliberately which variants are indexable and which should consolidate or remain non-indexable.

## Migrations
For URL changes, use relevant 301/308 redirects, update internal links and sitemaps, then validate old/new URL behavior. Avoid redirect chains and loops.

## QA
Test representative stock, company, news, category, parameter, 404, and redirect URLs. Inspect response headers, HTML canonical, robots directives, robots.txt, sitemap membership, and rendered accessibility.
