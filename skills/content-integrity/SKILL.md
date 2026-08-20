---
name: content-integrity
description: Prevent fabricated, stale, mismatched, malformed, duplicate, and misleading content or financial data on CanliHisse.
---
# Content Integrity

Never invent prices, volume, financial results, news, quotes, sources, dates, authors, ratings, reviews, statistics, or historical prices.

Validate every market response for ticker/company identity, exchange, currency, numeric types, timestamp, source, and plausible ranges. If required data is missing, return an explicit unavailable state or a clearly marked last verified value.

When an API fails, never use random values, zero, another entity's value, or stale data presented as current.

AI may draft and summarize, but factual financial claims must be verified against reliable data.

Prevent duplicate and thin content. Validate structured data against visible content. Preserve historical facts and do not fake update timestamps.

QA every generated stock/company/news page before publication.
