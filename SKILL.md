---
name: canlihisse-seo-intelligence
description: Use when auditing, building, debugging, or optimizing CanliHisse SEO, Google Search indexing, Google Images, stock and company pages, Turkish financial content, programmatic SEO, structured data, sitemaps, robots.txt, canonical URLs, metadata, internal linking, JavaScript rendering, Core Web Vitals, Search Console, image SEO, news SEO, entity SEO, freshness, AdSense safety, and content integrity.
---

# CanliHisse SEO Intelligence — Production Playbook

This skill is the operating standard for CanliHisse (canlihisse.com). It is designed for an AI coding agent that can inspect and modify the application.

## Mission

Improve organic visibility and user value without breaking business logic or financial-data accuracy.

Priority order:
1. Accuracy and user safety
2. Crawlability and indexability
3. Helpful, original content
4. Trust and transparency
5. Performance and accessibility
6. SEO growth
7. Monetization

Never sacrifice truth, usability, or working product behavior for an SEO shortcut.

## Operating Procedure

Before changing code:
1. Identify the affected URL(s) and page type.
2. Inspect existing implementation and data flow.
3. Determine whether the issue is crawl, index, content, rendering, metadata, schema, links, images, performance, or data integrity.
4. Make the smallest safe change.
5. Validate the generated output.
6. Check mobile behavior.
7. Check that financial APIs and business logic still work.
8. Report evidence, changed files, and validation.

Never make broad SEO changes based on assumptions when the actual URL pattern or implementation can be inspected.

# 1. AdSense Policy Guard

- Pages must provide substantial value without ads.
- Never encourage ad clicks.
- Never make ads resemble navigation, stock charts, buy/sell controls, downloads, or functional buttons.
- Avoid excessive ad density and accidental-click risk, especially on mobile.
- Keep sponsored and affiliate content clearly disclosed.
- Never fabricate reviews, ratings, users, traffic, sources, authors, statistics, or financial claims.
- Never promise guaranteed profits, guaranteed returns, or risk-free investing.
- Never create pages whose primary purpose is advertising.
- Preserve clear privacy, contact, ownership, and policy information.

# 2. Technical SEO

Every indexable page should have:
- unique title
- useful meta description
- canonical URL
- correct language
- Open Graph metadata
- appropriate Twitter/X metadata

Check:
- HTTP status
- crawlability
- indexability
- robots.txt
- noindex
- canonical
- redirects
- internal links
- sitemap inclusion
- JavaScript rendering
- duplicate URLs
- mobile rendering

Do not block essential CSS or JavaScript resources.

# 3. Google Indexing

For each important public URL verify this chain:

URL → correct HTTP status → publicly accessible → not blocked → not accidental noindex → canonical correct → sitemap where appropriate → internal links → crawlable rendered content.

Important rules:
- A sitemap does not guarantee indexing.
- Never claim a URL is indexed merely because it is in the sitemap.
- Investigate discovered-but-not-indexed and crawled-but-not-indexed patterns through Search Console when available.
- Fix the cause, not only the symptom.
- Avoid mass-publishing thin, empty, duplicate, or invalid URLs.
- Avoid orphaning important pages.
- Do not use noindex as a substitute for proper canonicalization when duplicates should consolidate.

# 4. Google Images and Image Indexing

Important images must be genuinely discoverable and fetchable.

For important images:
- use crawlable absolute/valid URLs
- use descriptive filenames
- use accurate natural alt text
- provide width and height
- use responsive images and srcset where appropriate
- use WebP/AVIF when compatible
- preserve meaningful surrounding text/captions
- ensure JavaScript does not hide critical images from crawlers
- ensure CDN transformations allow Googlebot access
- check robots.txt and X-Robots-Tag restrictions
- use image sitemap entries for large/image-heavy sections when useful

Do not keyword-stuff alt text.
Do not use misleading filenames or fabricated image descriptions.
Do not assume an image sitemap guarantees ranking in Google Images.

# 5. Image SEO

For each important image evaluate:
- relevance to the page
- original/useful content
- filename
- alt text
- caption when useful
- surrounding text
- dimensions
- compression
- format
- responsive delivery
- lazy loading strategy
- CDN accessibility
- page canonical context

Decorative images should not be forced into SEO targets.

# 6. Helpful Content Editor

Create original, people-first Turkish content.

Every page must satisfy a real user intent.

Separate:
- facts
- historical data
- analysis
- commentary
- opinion
- sponsored content

Avoid:
- keyword stuffing
- filler
- spun content
- automatic synonym replacement
- copied articles
- near-duplicate pages
- content created only to capture search traffic

Financial statements must be cautious and evidence-based.

# 7. Programmatic SEO

Programmatic pages are allowed only when each page has meaningful entity-specific value.

For stock pages validate:
- company
- ticker
- exchange
- identifier
- sector
- source data

Useful stock-page components may include:
- current/last verified price
- change
- volume
- historical data
- financial metrics
- company information
- sector information
- related news
- related stocks
- update status
- explanatory content

Never generate thousands of pages containing only a ticker, price, and generic paragraph.

Do not publish empty entity pages unless there is a legitimate reason and useful content exists.

# 8. Internal Linking

Create a logical information architecture:

Home → Categories → Sectors → Companies → Stocks → News/Analysis/Education

Use contextual links between:
- stock and company
- stock and sector
- stock and related stocks
- stock and relevant news
- article and relevant entities
- educational guide and related concepts

Use descriptive natural anchor text.
Avoid artificial link blocks, irrelevant links, and excessive repetition.

Important pages should have discoverable internal paths.

# 9. Structured Data

Use JSON-LD only when supported by visible content.

Potential schemas:
- Organization
- WebSite
- BreadcrumbList
- Article
- NewsArticle
- Dataset
- FAQPage only when genuinely applicable and eligible

Never fabricate:
- reviews
- ratings
- authors
- prices
- dates
- FAQ answers
- aggregate scores

Schema must match visible page content and should be removed when no longer valid.

# 10. Sitemap Manager

Maintain valid XML sitemaps.

Include:
- canonical
- public
- indexable
- valid HTTPS URLs when HTTPS is canonical

Exclude:
- redirects
- 404/410 URLs
- noindex URLs
- duplicates
- private/dashboard URLs
- invalid generated pages

Use sitemap indexes when scale requires splitting files.
Use image sitemap entries where useful.
Update sitemap generation when important content changes.

# 11. Robots and Canonical

robots.txt controls crawling; it is not a noindex mechanism.

Never accidentally disallow:
- important pages
- CSS/JS needed for rendering
- important images

Canonical rules:
- stable
- absolute
- preferred domain
- HTTPS
- self-consistent

Do not canonicalize unrelated pages to the homepage.
Check consistency across:
- HTML canonical
- sitemap
- redirects
- internal links
- structured data where relevant

# 12. Core Web Vitals and Performance

Optimize:
- LCP: server response, critical assets, hero images, rendering
- INP: client JavaScript and expensive event handlers
- CLS: reserved image/ad/chart dimensions and stable layouts

Also evaluate:
- mobile responsiveness
- font loading
- caching
- compression
- code splitting
- image optimization
- API latency
- database queries
- unnecessary hydration/client JavaScript

Do not remove useful content simply to chase synthetic scores.

# 13. Financial Content Safety

CanliHisse is a financial information product.

Never state uncertain future prices as facts.
Never promise returns.
Never describe investments as risk-free.

Clearly distinguish market data from analysis and opinion.
Show live/delayed/historical/unavailable status when relevant.
Use neutral Turkish financial terminology.

Bad:
“THYAO kesin %30 yükselecek.”

Good:
“THYAO son dönemde X% değişti. Gelecekteki fiyat hareketi kesin olarak öngörülemez.”

# 14. Content Integrity

Never invent:
- stock prices
- volume
- financial results
- news
- quotes
- sources
- dates
- authors
- statistics
- reviews
- historical prices
- user counts

When an API fails:
- show unavailable, or
- show a clearly marked last verified value

Never use random values, zero, another stock's value, or stale data disguised as current.

Validate numeric type, currency, exchange, ticker/company relationship, timestamp, and source before publishing.

# 15. Data Freshness

Track when appropriate:
- retrieved_at
- updated_at
- last_verified_at
- data status

Statuses may be:
- live
- delayed
- historical
- updating
- unavailable

Never generate a fake update timestamp.
Never change an article's updated date unless it was actually reviewed/updated.
Preserve historical context.

# 16. News SEO

For genuine news:
- accurate headline
- accurate publication date
- accurate update date when applicable
- source identification
- meaningful article content
- correct author only if real
- appropriate article image
- correct canonical
- NewsArticle only when eligible

Never fabricate quotes, events, sources, or breaking-news claims.
Do not rewrite another publisher's article into a lightly changed copy and call it original reporting.

# 17. Entity SEO

Keep entities consistent across the site.

Example:
THYAO → Türk Hava Yolları → company entity → BIST listing → sector → related news

Validate:
- ticker
- company name
- exchange
- sector
- stable identifier
- canonical URL

Never mix similarly named companies or symbols.

# 18. Google Search Console

When access is available, use Search Console to inspect:
- URL Inspection
- Page indexing
- Sitemaps
- Core Web Vitals
- HTTPS/security issues
- manual actions
- search performance
- crawl/indexing patterns

Do not infer indexing status from sitemap presence.
For each issue identify:
- exact URL or pattern
- evidence
- likely root cause
- fix
- validation

# 19. Trust and Transparency

Maintain accurate:
- Hakkımızda
- İletişim
- Gizlilik Politikası
- Kullanım Koşulları where applicable
- advertising/sponsorship disclosure

Clearly communicate:
- data sources
- data freshness
- delay status
- last verified time
- sponsored/affiliate relationships

Never invent:
- licenses
- partnerships
- experts
- credentials
- offices
- awards
- authors

# 20. SEO Audit

When asked to audit CanliHisse, inspect in this order:
1. HTTP status and indexability
2. robots.txt
3. sitemap
4. canonical consistency
5. metadata
6. rendered/crawlable content
7. internal links/orphans
8. structured data
9. duplicate/thin content
10. programmatic pages
11. image discovery/SEO
12. Core Web Vitals/mobile UX
13. financial-data integrity
14. trust/advertising transparency
15. Search Console signals

Every reported issue must contain:
- severity: critical/high/medium/low
- affected URL or pattern
- evidence
- root cause
- exact fix
- validation method

# Safety and Change Control

- Never mass-delete pages without inspecting the URL pattern.
- Never mass-redirect without validating destination relevance.
- Never change production financial-data logic during an SEO task unless explicitly required.
- Never invent data to fill an empty state.
- Prefer small, reversible changes.
- Validate robots.txt, sitemap XML, canonical tags, JSON-LD, metadata, and generated URLs after changes.
- Preserve existing working business logic.

# Definition of Done

An SEO task is complete only when:
- intended URLs are crawlable/indexable
- canonical signals are consistent
- sitemap and robots behavior are correct
- metadata is useful and unique
- essential content is crawlable/renderable
- structured data is truthful and supported
- images are discoverable and optimized
- internal links support important pages
- mobile performance remains healthy
- financial data remains accurate
- trust and advertising transparency are preserved
- no deceptive SEO or AdSense behavior was introduced
