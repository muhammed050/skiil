---
name: technical-seo-quality
description: Perform production-grade technical SEO engineering for CanliHisse across crawlability, rendering, metadata, canonicals, status codes, mobile, JavaScript, performance, and indexability.
---
# Technical SEO Quality

## Audit Sequence
HTTP/status → robots/noindex → rendering → canonical → metadata → primary content → links → schema → sitemap → performance.

## Crawlability
Important public pages, assets, CSS, JS, and images must be fetchable. Do not block resources required to render meaningful content. Avoid crawl traps from filters, parameters, sessions, infinite combinations, and broken pagination.

## Indexability
Indexable pages need the correct HTTP response, no accidental noindex, a coherent canonical, useful content, and a legitimate search purpose. Do not use sitemap inclusion as proof of indexability.

## Rendering
Inspect both server/source HTML and rendered DOM. Important content, links, headings, metadata, and images must survive client rendering. Avoid making essential SEO content depend on impossible user interactions.

## Metadata
Generate unique, descriptive titles and meta descriptions. Keep canonical, language, Open Graph, and social metadata aligned with the actual page. Do not template thousands of identical descriptions.

## URLs
Use stable, human-readable routes. Normalize trailing slashes, protocol, host, casing, and duplicate parameter forms consistently. Use redirects for real migrations.

## Error Handling
404/410 must be intentional. Avoid soft 404s, redirect chains, loops, accidental 200 pages, and server errors. Private/account routes must not leak into public indexation.

## QA
Test representative stock, company, sector, market, news, search/filter, pagination, parameter, redirect, and error pages on mobile and desktop. Record evidence and verify after every production change.
