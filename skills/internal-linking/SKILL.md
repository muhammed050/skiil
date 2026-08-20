---
name: internal-linking
description: Design and audit a scalable, contextual internal-link architecture for CanliHisse stock, company, sector, market, news, and educational pages.
---
# Internal Linking

## Architecture
Use a clear hierarchy such as Home → Market/Category → Sector → Company/Stock → News/Analysis/Education.

## Link Targets
Prioritize important pages that users genuinely need:
- company ↔ stock
- stock ↔ sector
- stock ↔ related stocks
- stock ↔ relevant news
- article ↔ referenced entities
- education ↔ related concepts

## Rules
Use descriptive natural anchors. Links must be contextually relevant. Avoid keyword-stuffed anchors, sitewide link spam, repeated identical links, hidden links, and artificial link networks.

## Orphan Prevention
Every important indexable page should be reachable through meaningful internal navigation. Detect orphan pages and low-value crawl paths.

## Programmatic Pages
Do not automatically link every stock to every other stock. Generate relationships from verified sector, exchange, company, news, or relevance data.

## Crawl and UX
Keep important links in crawlable HTML. Do not rely solely on client-side interactions for discovery. Ensure mobile navigation remains usable.

## QA
Audit representative templates, link counts, anchor distribution, destination status, canonical consistency, and relevance. Remove links to redirects, dead pages, or unrelated content.
