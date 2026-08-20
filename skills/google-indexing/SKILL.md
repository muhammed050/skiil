---
name: google-indexing
description: Diagnose and improve Google indexing for CanliHisse using crawlability, rendering, canonical signals, sitemaps, internal discovery, URL patterns, content quality, and Search Console evidence.
---
# Google Indexing

## Objective
Make valuable public URLs discoverable, crawlable, renderable, canonicalized, and eligible for indexing. Never promise indexing.

## Diagnostic Chain
Check in order:
1. intended URL resolves
2. correct HTTP status
3. Googlebot can fetch it
4. robots allows required crawling
5. no accidental noindex/header restriction
6. canonical is correct
7. rendered HTML has meaningful primary content
8. important links/content are crawlable
9. sitemap/internal discovery exists
10. page is not thin, duplicate, empty, invalid, or misleading

## Diagnose by State
Handle separately: robots blocked, noindex, duplicate/canonicalized, discovered-not-indexed, crawled-not-indexed, soft 404, redirect, server error, rendering failure. Do not apply one fix to all states.

## Programmatic Scale
Before mass publishing stock/company pages, sample entity accuracy, unique value, content completeness, canonical behavior, internal links, schema, and sitemap inclusion. Stop generation when quality gates fail.

## Search Console
Use URL Inspection/Page Indexing/Sitemaps when connected. Record Google-selected vs user-declared canonical when available. Separate indexing from ranking.

## Validation
Verify source and rendered HTML, status, robots, noindex, canonical, sitemap, internal discovery, and representative successful/failing URLs after changes.

## Hard Rules
Never claim “indexed” without evidence. Never create fake content to force indexing. Never mass-delete or redirect without pattern analysis. Preserve financial application logic.
