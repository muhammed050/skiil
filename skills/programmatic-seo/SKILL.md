---
name: programmatic-seo
description: Design and operate scalable CanliHisse stock, company, sector, comparison, and category pages with real entity-specific value, strong crawl architecture, and safeguards against thin or duplicate content.
---
# Programmatic SEO

## Mission
Scale useful pages, not URLs. Every generated page must solve a real search need and contain verifiable entity-specific information.

## Before Creating a Template
Define:
- search intent
- entity type
- canonical URL pattern
- required data
- unique value
- internal-link role
- sitemap behavior
- indexability rules
- empty/error state
- update/freshness strategy

## Entity Validation
Require valid:
- company name
- ticker
- exchange
- stable identifier
- sector where applicable
- source relationship

Never create a page from an unverified ticker or mismatched API record.

## Stock Page Quality Gate
A stock page should provide meaningful information beyond a ticker and one price. Depending on available data, include verified price status, change, volume, historical information, financial metrics, company context, sector, related news, related entities, and useful explanations.

If critical data is unavailable, show an honest unavailable state. Do not fill missing fields with invented values.

## Duplicate Control
Audit:
- uppercase/lowercase variants
- aliases
- trailing slash variants
- query parameters
- filters
- pagination
- tracking parameters
- duplicate entity routes

Choose canonicalization, redirects, noindex, or route constraints based on actual user intent. Do not blanket-noindex useful pages.

## Scale Safely
Test representative URLs before generating thousands. Check template output, metadata, schema, links, images, HTTP status, canonical, content uniqueness, and data correctness.

Stop generation if the template produces empty, repetitive, invalid, or mismatched pages.

## Thin Content Prevention
Never mass-create pages containing only a ticker, price, generic paragraph, or repeated boilerplate. Do not publish pages merely because a keyword exists.

## Freshness
Volatile market data needs accurate update status. Editorial content needs genuine review before an updated date changes.

## Done
Validate a sample from every page family, plus edge cases and missing-data states. Confirm sitemap and internal discovery behavior and preserve application business logic.
