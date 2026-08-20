---
name: content-integrity
description: Enforce verified, consistent, non-fabricated content and financial data across every CanliHisse page, API response, chart, article, image, and structured-data field.
---
# Content Integrity

## Mission
Never let the application fill missing facts with invented values. Accuracy has priority over completeness and SEO.

## Mandatory Validation
For every financial datum validate:
- entity/ticker identity
- exchange and currency
- numeric type and unit
- timestamp and timezone
- source/provenance
- freshness/status
- plausible range against trusted context

## Forbidden Fabrication
Never invent prices, volume, financial results, ratios, news, quotes, dates, authors, reviews, ratings, traffic, users, historical values, sources, or credentials.

## API Failure
If a provider fails, times out, returns malformed data, or returns the wrong entity:
1. reject invalid data
2. log/flag the failure
3. show unavailable or last verified value with explicit labeling
4. never substitute zero, random data, another ticker, or stale data as current

## AI Content
AI may draft, classify, translate, or summarize. It must not be the source of financial facts. Verify factual claims against trusted application data before publication.

## Cross-Page Consistency
The same company/ticker must not have conflicting names, prices, sectors, identifiers, currencies, or URLs. Fix the source of truth rather than patching individual pages.

## Structured Data and Images
JSON-LD, charts, OG metadata, captions, and image text must match visible and verified data.

## QA Gate
Before publishing generated stock/company/news pages, validate entity identity, data status, dates, sources, calculations, schema, and duplicate/thin-content risk. If a required fact cannot be verified, expose an honest unavailable state.
