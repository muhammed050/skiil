---
name: image-indexing
description: Diagnose and improve Google Images discovery and crawlability for CanliHisse images, including image URLs, HTML rendering, responsive markup, sitemaps, CDN access, robots directives, and contextual relevance.
---
# Image Indexing

## Mission
Make valuable CanliHisse images discoverable, fetchable, understandable, and useful without misleading metadata or sacrificing page performance.

## Image Discovery Checklist
For important images verify:
- valid stable image URL
- HTTPS and correct host/CDN
- image is reachable by crawlers
- robots.txt does not block it
- X-Robots-Tag or HTTP headers do not accidentally restrict it
- image appears in crawlable HTML or an appropriate discovery mechanism
- JavaScript does not hide the source from crawlers
- responsive `srcset`/`picture` still exposes useful source URLs
- image is associated with the correct canonical page

## Metadata
Use:
- descriptive filenames
- concise natural alt text for informative images
- empty alt for purely decorative images
- captions when they add information
- meaningful surrounding text

Never keyword-stuff alt text, filenames, captions, or image attributes.

## Image Sitemap
Use image sitemap support for image-heavy sections when useful. Keep URLs valid and canonical. An image sitemap improves discovery opportunities; it does not guarantee Google Images indexing or ranking.

## CanliHisse Image Types
Review separately:
- company logos
- stock/company hero images
- article images
- financial charts
- market graphics
- OG/social images
- decorative UI assets

Do not treat every UI icon as an SEO image.

## Rendering and Performance
Do not lazy-load a critical image in a way that prevents discovery. Reserve dimensions to prevent CLS. Prefer modern formats and responsive delivery when compatible. Do not destroy chart readability through excessive compression.

## CDN Audit
Check redirects, hotlink protection, signed/expiring URLs, query transformations, content type, caching, and crawler accessibility. Image URLs must not depend on a user session.

## Validation
Inspect rendered HTML and representative image URLs. Confirm correct `Content-Type`, successful response, stable URL, contextual relevance, and no accidental blocking. Test mobile and desktop.

## Hard Rules
Never fabricate image subjects, chart values, company identities, or descriptions. Never claim an image is indexed merely because it is in a sitemap.
