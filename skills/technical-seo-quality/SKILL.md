---
name: technical-seo-quality
description: Implement and audit production-grade technical SEO for CanliHisse, including crawlability, rendering, metadata, canonicalization, status codes, mobile SEO, and indexability.
---
# Technical SEO Quality

## Audit Order
HTTP status → crawlability → indexability → rendering → canonical → metadata → links → structured data → sitemap → performance.

## Rules
- Important public pages must return the intended HTTP status.
- Do not accidentally block important URLs, CSS, JS, or images.
- Use one stable canonical URL per indexable page.
- Canonicals must use the preferred HTTPS domain and must not point unrelated pages to the homepage.
- Titles and descriptions must be unique and useful.
- Keep language and Open Graph metadata accurate.
- Prevent duplicate URL variants and parameter-driven duplicates where appropriate.
- Ensure important content is available to crawlers after rendering.
- Maintain responsive mobile layouts.

## Validation
Inspect source HTML and rendered output. Check generated routes, status codes, canonical tags, robots directives, metadata, and internal links. Test representative stock, company, category, article, and error pages.

## Done
Provide evidence, affected URL patterns, root cause, exact changes, and validation results.
