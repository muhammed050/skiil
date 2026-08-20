---
name: image-indexing
description: Diagnose and improve Google Images discovery, crawling, rendering, relevance, and index eligibility for CanliHisse images across HTML, CDN, sitemaps, and responsive delivery.
---
# Image Indexing

## Discovery
Important images should have stable fetchable URLs and be discoverable from crawlable HTML or appropriate image sitemap mechanisms. Do not depend on user sessions or opaque client-only interactions.

## Crawl Access
Check robots.txt, X-Robots-Tag, authentication, CDN hotlink rules, signed/expiring URLs, redirects, content type, HTTPS, and response status. Google must be able to fetch the actual image bytes.

## Responsive Images
Use srcset/picture responsibly. Ensure responsive markup does not prevent discovery of useful source URLs. Critical images must not be hidden behind broken lazy-loading behavior.

## Context
Google Images relevance depends on the image and its surrounding page context. Use accurate filenames, natural alt text, captions when useful, and relevant surrounding content. Never keyword-stuff.

## Image Types
Handle company logos, article images, stock charts, market graphics, OG images, and decorative assets differently. Decorative UI icons are not automatic SEO targets.

## Image Sitemap
Use image sitemap support for image-heavy sections when useful. Keep URLs valid and canonical. Never claim sitemap inclusion equals indexing or ranking.

## Quality
Do not fabricate chart values, company logos, image subjects, or descriptions. Do not replace a meaningful image with a generic stock image merely for SEO.

## QA
Test representative images on mobile/desktop, inspect rendered HTML and network responses, verify Content-Type/status, CDN accessibility, stable URLs, dimensions, context, and accidental blocking.
