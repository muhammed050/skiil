---
name: structured-data
description: Implement truthful, valid, page-specific Schema.org JSON-LD for CanliHisse while preventing fabricated entities, reviews, ratings, dates, and unsupported markup.
---
# Structured Data

## Core Rule
Structured data describes visible, truthful page content. It is not a place to add claims that users cannot see or verify.

## Candidate Types
Use only when genuinely applicable:
- Organization
- WebSite
- BreadcrumbList
- Article
- NewsArticle
- Dataset
- FAQPage when content and eligibility requirements are actually met

## Rules
- Match visible name, URL, headline, author, publisher, image, dates, and entity identity.
- Use the canonical URL consistently.
- Never fabricate ratings, reviews, prices, authors, credentials, dates, FAQ answers, or aggregate scores.
- Do not mark hidden or unrelated content.
- Avoid duplicate/conflicting schema graphs.
- Keep JSON valid and use the correct Schema.org vocabulary.

## Financial Pages
A stock price or financial value in schema must come from the same verified source as the visible value and carry appropriate freshness context when the chosen type supports it. Do not invent financial properties simply to increase markup.

## QA
Validate JSON-LD syntax, entity relationships, URLs, dates, images, visible-content parity, and representative templates. Remove obsolete schema when page content changes. Structured data is not an indexing or rich-result guarantee.
