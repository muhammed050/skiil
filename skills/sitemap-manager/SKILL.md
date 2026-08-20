---
name: sitemap-manager
description: Generate and validate production-quality XML, image, and sitemap-index files for CanliHisse without exposing duplicate, private, redirected, or non-indexable URLs.
---
# Sitemap Manager

## Inclusion Gate
Include only canonical, public, indexable, successful URLs that are genuinely useful.

Exclude:
- redirects
- 404/410 URLs
- noindex pages
- duplicates
- private/account pages
- invalid programmatic pages
- parameter noise

## Sitemap Types
Use a sitemap index when scale requires splitting. Maintain separate logical groups for major content types when useful. Add image sitemap data where it materially helps image discovery.

## Accuracy
Sitemap URLs must match the site's preferred HTTPS host and canonical URLs. Do not list URLs merely because they exist in a database.

## Freshness
Regenerate or revalidate after meaningful content/URL changes. Do not manipulate last-modification information to pretend content changed when it did not.

## Validation
Check XML syntax, URL accessibility, response codes, canonical consistency, duplicates, limits, encoding, and production hostname. Confirm robots.txt points to the real sitemap.

## Search Console
Sitemap submission is a discovery signal, not an indexing guarantee. Monitor errors and investigate patterns instead of repeatedly resubmitting unchanged broken files.
