---
name: seo-audit
description: Perform evidence-based end-to-end SEO audits of CanliHisse and produce prioritized, implementation-ready fixes with validation criteria.
---
# SEO Audit

## Audit Order
1. HTTP/status/indexability
2. robots.txt and crawl directives
3. sitemap architecture
4. canonical consistency
5. titles/descriptions/OG
6. rendered primary content
7. internal links and orphan pages
8. structured data
9. duplicate/thin programmatic content
10. image discovery/indexing/SEO
11. Core Web Vitals/mobile UX
12. financial-data integrity
13. trust/advertising transparency
14. Search Console evidence

## Severity
- Critical: blocks crawling/indexing or creates serious data/deception risk.
- High: affects important page families or large-scale discovery.
- Medium: meaningful but localized SEO/UX issue.
- Low: refinement with limited impact.

## Evidence Requirement
Every finding must include exact URL or pattern, observed behavior, evidence, likely root cause, recommended fix, and validation method. Do not report generic SEO advice as a finding when the implementation can be inspected.

## Page Families
Audit representative examples of homepage, stock, company, sector, market, article/news, search/filter, pagination, parameter, 404, redirect, and private routes.

## Data Integrity Gate
If market data is stale, mismatched, or fabricated, treat it as a high-priority integrity issue. SEO changes must never hide data failures.

## Change Control
Do not mass-delete, mass-redirect, mass-noindex, or mass-publish without sampling the affected pattern first. Prefer reversible, evidence-backed changes.

## Verification
After implementation re-check status, canonical, robots, sitemap, metadata, rendered content, structured data, links, images, mobile layout, and financial functionality. Record what changed and what remains.
