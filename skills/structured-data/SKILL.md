---
name: structured-data
description: Implement truthful JSON-LD structured data for CanliHisse pages and keep schema synchronized with visible content.
---
# Structured Data

Use JSON-LD only when the schema genuinely applies and is supported by visible content.

Potential schemas include Organization, WebSite, BreadcrumbList, Article, NewsArticle, Dataset, and eligible FAQPage.

Rules:
- Match visible content exactly.
- Use real names, dates, authors, images, prices, and relationships.
- Never fabricate ratings, reviews, aggregate scores, authors, prices, FAQ answers, or publication dates.
- Keep canonical URLs consistent.
- Remove or update schema when page content changes.

Validate JSON-LD syntax, required properties, URL consistency, entity identity, and representative templates before scaling programmatically.
