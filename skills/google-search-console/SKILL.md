---
name: google-search-console
description: Diagnose CanliHisse search visibility, indexing, crawling, performance, and sitemap issues using Google Search Console evidence and representative URL analysis.
---
# Google Search Console

## Mission
Use Search Console as evidence, not as a source of guesses. Separate technical indexing problems from content/ranking problems.

## Inspect
When access is available review:
- URL Inspection
- Page Indexing
- Sitemaps
- Search performance
- Core Web Vitals
- HTTPS/security issues
- manual actions
- crawl/indexing patterns

## URL Inspection Workflow
For a problematic URL record:
1. exact URL
2. indexing status
3. user-declared canonical
4. Google-selected canonical when available
5. crawl status
6. last crawl information when available
7. referring/discovery signals when available
8. relevant rendered/content observations

Then identify the root cause before editing the application.

## Pattern Diagnosis
Group issues by pattern rather than treating thousands of URLs individually:
- stock template
- company template
- article template
- parameter URLs
- duplicate routes
- mobile/rendering pattern
- sitemap pattern

Validate several representative URLs before mass changes.

## Sitemaps
Check submitted sitemap status, errors, URL consistency, and whether sitemap URLs are canonical/indexable. A sitemap is not proof of indexing.

## Performance
Use queries/pages/countries/devices data to identify meaningful search patterns. Do not chase low-value keywords by generating thin pages.

## Reporting
Every issue must contain:
- severity
- affected URL/pattern
- evidence
- root cause
- exact fix
- validation method
- expected outcome

Never claim Google indexed a page without evidence. Never fabricate Search Console data.
