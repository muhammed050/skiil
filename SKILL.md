---
name: canlihisse-seo-intelligence
description: Use when auditing, improving, debugging, or implementing SEO, Google indexing, Google Images, stock pages, financial content, technical SEO, structured data, sitemaps, robots.txt, canonical URLs, metadata, internal linking, JavaScript rendering, Core Web Vitals, Search Console visibility, image SEO, news SEO, entity SEO, freshness, AdSense safety, or programmatic SEO for CanliHisse.
---

# CanliHisse SEO Intelligence

Use this skill as the unified SEO and content-quality playbook for CanliHisse (canlihisse.com). Preserve financial-data accuracy and existing application business logic.

## 1. AdSense Policy Guard
- Keep pages useful even without ads.
- Never encourage ad clicks or create deceptive ad-like buttons.
- Keep ads visually distinct from navigation, charts, stock controls, downloads, and content.
- Avoid excessive ad density and accidental-click risk, especially on mobile.
- Never fabricate reviews, ratings, statistics, authors, sources, or financial claims.
- Never promise guaranteed profits or risk-free investing.

## 2. Technical SEO Quality
- Keep important public pages crawlable and indexable.
- Use unique titles, descriptions, canonical URLs, Open Graph metadata, and appropriate language metadata.
- Avoid duplicate URLs, accidental noindex, broken links, and blocked essential resources.
- Keep important pages in the XML sitemap.
- Optimize server response, images, JavaScript, caching, layout stability, and mobile UX.

## 3. Helpful Content Editor
- Write original, useful, people-first Turkish content.
- Answer real search intent directly.
- Avoid keyword stuffing, filler, spun text, and near-duplicate programmatic pages.
- Separate facts, historical data, analysis, commentary, and opinion.
- Financial content must never present speculation as certainty.

## 4. Trust and Transparency
- Maintain accurate Hakkımızda, İletişim, Gizlilik Politikası, Kullanım Koşulları, and advertising/sponsorship disclosures where applicable.
- Clearly communicate market-data source, freshness, delay status, and last verified time when relevant.
- Never invent licenses, partnerships, experts, authors, offices, reviews, or credentials.
- Clearly label sponsored and affiliate content.

## 5. Content Integrity
- Never invent stock prices, volume, financial results, news, sources, dates, authors, statistics, reviews, or historical data.
- If an API fails, show an honest unavailable or last-verified state instead of fake data.
- Validate ticker/company/exchange relationships and timestamps.
- Structured data must match visible content.

## 6. Google Indexing
For every important public page, verify this chain:
1. URL returns the correct HTTP status, normally 200.
2. Page is publicly accessible.
3. Page is not accidentally blocked by robots.txt.
4. Page is not accidentally noindex.
5. Canonical points to the preferred URL.
6. Page is included in the appropriate sitemap.
7. Page has meaningful internal links.
8. JavaScript rendering does not hide essential content from crawlers.
9. Thin, duplicate, empty, or invalid pages are not mass-published.
10. Use Google Search Console inspection/reporting to diagnose discovered-but-not-indexed and crawled-but-not-indexed cases.

Never claim that a page is indexed merely because it is in the sitemap. Indexing is decided by Google.

## 7. Image Indexing
Optimize images so search engines can discover and understand them.
- Use real, crawlable image URLs.
- Do not block important image paths with robots.txt or restrictive headers.
- Use descriptive filenames where practical.
- Provide useful alt text that describes the image naturally.
- Give images width and height to reduce layout shifts.
- Use responsive images and srcset where appropriate.
- Prefer efficient formats such as WebP or AVIF when compatible.
- Ensure important images are present in rendered HTML or otherwise discoverable.
- Use an image sitemap for large or image-heavy sections when useful.
- Do not create keyword-stuffed alt text.
- Do not invent image content or misleading filenames.
- Make sure CDN/image transformations do not prevent Googlebot from fetching images.

## 8. Programmatic SEO
- Generate pages only when each page has meaningful entity-specific value.
- Validate every ticker, company, sector, and identifier before generating a page.
- Avoid thousands of thin pages that differ only by a name or symbol.
- Include real data, explanations, relevant links, useful tables/charts, and freshness information.
- Do not publish empty pages when required data is unavailable.

## 9. Internal Linking
- Build useful contextual links between related stocks, companies, sectors, news, and educational guides.
- Link important pages from navigational/category pages.
- Avoid orphan pages where important content has no internal path.
- Use descriptive anchor text naturally.
- Do not create artificial link networks or irrelevant link blocks.

## 10. Structured Data
Use JSON-LD only when the page genuinely qualifies.
Possible schemas include Organization, WebSite, BreadcrumbList, Article, NewsArticle, FAQPage, and Dataset where appropriate.
- Schema must match visible content.
- Never fabricate ratings, reviews, authors, dates, prices, or FAQ answers.
- Remove unsupported schema instead of forcing it.

## 11. Sitemap Manager
Maintain valid XML sitemaps.
- Include canonical, public, indexable URLs.
- Exclude redirects, 404s, noindex pages, duplicates, and private URLs.
- Keep sitemap URLs absolute and HTTPS when HTTPS is canonical.
- Update sitemaps when important content changes.
- Use image sitemap entries where they provide value.
- Split large sitemaps into sitemap indexes when limits require it.
- A sitemap helps discovery but does not guarantee indexing.

## 12. Robots and Canonical
- robots.txt controls crawling; it is not a replacement for noindex.
- Never accidentally disallow important pages or required resources.
- Keep the sitemap declaration correct.
- Canonical URLs must be stable, HTTPS, preferred-domain URLs and self-consistent.
- Do not canonicalize unrelated pages to the homepage.
- Avoid canonical conflicts between HTML, sitemap, redirects, and internal links.

## 13. Core Web Vitals
Prioritize real-user performance:
- LCP: optimize server response, critical assets, hero images, and rendering.
- INP: reduce unnecessary client JavaScript and expensive event handlers.
- CLS: reserve image/ad/chart dimensions and avoid layout shifts.
Also improve mobile responsiveness, font loading, caching, compression, and database/API latency.

## 14. Financial Content Safety
- Do not provide guaranteed price predictions or guaranteed returns.
- Clearly distinguish factual market data from analysis and opinion.
- Show data freshness/delay where relevant.
- Never fabricate missing financial values.
- Use neutral Turkish financial terminology.
- Explain uncertainty when discussing future market behavior.

## 15. Google Search Console
Use Search Console as the primary diagnostic source for Google search visibility.
Check, when access is available:
- URL Inspection
- Page indexing
- Sitemaps
- Core Web Vitals
- HTTPS/security issues
- Manual actions
- Search performance
- Crawl/indexing patterns
Do not infer indexing status from a sitemap alone.
When fixing an issue, identify the exact URL pattern and verify the fix rather than making broad speculative changes.

## 16. Image SEO
For every important image:
- meaningful filename
- accurate alt text
- appropriate dimensions
- responsive delivery
- efficient format
- relevant surrounding text
- stable canonical page context
Do not use decorative images as keyword targets. Do not stuff keywords into alt attributes.

## 17. News SEO
For genuine news content:
- use accurate headline and publication/update dates
- identify the source
- preserve the meaning of the source
- avoid fabricated quotes and events
- distinguish reporting from commentary
- use NewsArticle only when the page genuinely qualifies
- keep timestamps accurate
- avoid fake breaking-news claims

## 18. Entity SEO
Treat companies, stocks, sectors, exchanges, and financial entities consistently.
- Use stable identifiers and canonical URLs.
- Keep ticker, company name, exchange, sector, and data relationships correct.
- Link entity pages consistently.
- Avoid mixing similarly named companies or symbols.
- Where structured data is used, represent only verified entity information.

## 19. Freshness Monitor
For changing market pages and articles:
- track last data retrieval and verification times.
- distinguish live, delayed, historical, and unavailable states.
- update volatile values from verified sources.
- do not change an article's updated date unless it was actually reviewed/updated.
- preserve historical context.
- flag stale or failed upstream data instead of silently presenting it as current.

## 20. SEO Audit
When asked to audit CanliHisse, inspect in this order:
1. Indexability and HTTP status.
2. robots.txt and sitemap.
3. Canonical consistency.
4. Titles and descriptions.
5. Rendering and crawlable content.
6. Internal links and orphan pages.
7. Structured data.
8. Duplicate/thin content.
9. Programmatic page quality.
10. Image discovery and image SEO.
11. Core Web Vitals/mobile UX.
12. Financial-data integrity.
13. Trust, privacy, and advertising transparency.
14. Search Console signals when available.

For every issue report:
- severity: critical / high / medium / low
- affected URL or pattern
- evidence
- root cause
- exact fix
- validation method

## Safe Automation Rules
- Never mass-delete or mass-redirect pages without inspecting URL patterns first.
- Never change production financial-data logic while performing an SEO task unless explicitly required.
- Never invent data to fill empty states.
- Prefer small, reversible changes.
- Verify generated files such as robots.txt, sitemap.xml, and JSON-LD after edits.
- Preserve existing working business logic.

## Definition of Done
An SEO change is complete only when:
- the intended URLs are crawlable/indexable,
- canonical signals are consistent,
- sitemap/robots behavior is correct,
- metadata is useful and unique,
- structured data is valid and truthful,
- important content is rendered for crawlers,
- images are discoverable and optimized,
- internal links support important pages,
- mobile performance remains healthy,
- financial data remains accurate,
- and no misleading AdSense or financial-content behavior was introduced.
