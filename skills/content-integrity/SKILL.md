---
name: content-integrity
description: Prevent fabricated market data, stale values, duplicate content, unsupported structured data, and unreliable financial information on CanliHisse.
---
# Content Integrity

- Never invent prices, volumes, financial results, ratings, news, sources, authors, statistics, reviews, or historical values.
- If data is unavailable, show an explicit unavailable state.
- Never label delayed or historical data as live.
- Keep real retrieved_at, updated_at, and last_verified_at values when applicable.
- On API failure, preserve only clearly marked last-known data or show unavailable; never generate fallback numbers.
- Validate ticker/company/exchange relationships, types, ranges, timestamps, currency, and required fields.
- Reject suspicious responses such as impossible values, future timestamps, or mismatched identifiers.
- Structured data must exactly reflect visible content.
- Avoid duplicate, spun, copied, and thin programmatic pages.
- AI-generated financial claims must be verified before publication.

Critical rule: if a verified value does not exist, show that it is unavailable rather than inventing one.