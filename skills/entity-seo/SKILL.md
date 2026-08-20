---
name: entity-seo
description: Build and maintain authoritative, consistent search entities for CanliHisse companies, stocks, sectors, exchanges, markets, people, and related content.
---
# Entity SEO

## Entity Model
Treat each company/security as a canonical entity with stable identity, not merely a keyword.

Validate and normalize:
- legal/display company name
- ticker
- exchange
- stable identifier when available
- sector/industry
- canonical URL
- aliases
- source relationship

## Identity Safety
Never merge similarly named companies or tickers. Never attach news, prices, logos, or financial metrics to the wrong entity. Resolve duplicate entity URLs through canonicalization or redirects only when they represent the same entity.

## Site Graph
Build useful relationships:
Company ↔ Stock ↔ Exchange ↔ Sector ↔ Related Stocks ↔ News ↔ Educational Content.
Use relationships for contextual internal links and relevant structured data, never artificial link networks.

## Structured Data
Entity fields in JSON-LD must match visible page content and verified application data. Do not invent identifiers, logos, ratings, reviews, or organizational relationships.

## Templates
Every entity template must remain useful when data is missing. Show honest unavailable states rather than generic filler.

## QA
Test representative entities with similar names, multiple exchanges, missing data, aliases, old URLs, and news relationships. Verify no cross-entity contamination before mass generation.
