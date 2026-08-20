---
name: google-indexing
description: Diagnose and improve Google indexing for CanliHisse using evidence from crawlability, indexability, rendering, canonical signals, sitemaps, internal links, URL patterns, and Search Console.
---
# Google Indexing

## Mission
Get valuable public CanliHisse URLs discoverable, crawlable, renderable, canonicalized, and eligible for indexing. Never equate crawlability, sitemap inclusion, or a successful HTTP response with actual indexing.

## Diagnostic Chain
For every important URL check in order:
1. URL resolves to the intended page.
2. HTTP status is correct.
3. Response is accessible to Googlebot.
4. robots.txt does not block required crawling.
5. noindex or equivalent response/header directives are not accidental.
6. Canonical is present and points to the intended equivalent URL.
7. Rendered HTML contains meaningful primary content.
8. Important content is available without impossible client-side interactions.
9. URL is discoverable through sitemap and/or normal internal links.
10. Page is not thin, empty, duplicate, invalid, or misleading.

## URL Classes
Test representative examples of:
- homepage
- stock pages
- company pages
- sector pages
- market/category pages
- news/article pages
- paginated pages
- filtered/search pages
- parameter URLs
- 404/410 pages
- redirects
- private/dashboard routes

## Common States
Investigate separately:
- blocked by robots
- excluded by noindex
- duplicate/canonicalized
- discovered but not indexed
- crawled but not indexed
- soft 404
- redirect
- server error
- rendering failure

Do not apply the same fix to every state.

## Programmatic Pages
Before scaling, validate a representative sample for entity accuracy, unique value, content completeness, canonical behavior, internal links, and sitemap inclusion. Do not mass-publish empty or near-duplicate stock URLs.

## Search Console
When connected, use URL Inspection, Page Indexing, Sitemaps, and performance data. Record exact evidence before changing code. Separate indexing problems from ranking/content problems.

## Validation
After changes verify generated HTML, status codes, robots behavior, canonical tags, sitemap entries, internal discovery, rendered content, and representative URLs. Recheck both a successful case and a previously failing case.

## Hard Rules
Never claim a page is indexed without evidence. Never create fake content to force indexing. Never mass-delete or mass-redirect pages without URL-pattern analysis. Preserve financial application logic.
