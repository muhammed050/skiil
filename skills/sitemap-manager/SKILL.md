---
name: sitemap-manager
description: Maintain accurate XML, image, and sitemap-index files for CanliHisse to support efficient search-engine discovery.
---
# Sitemap Manager

- Include canonical, public, indexable URLs only.
- Exclude noindex pages, redirects, errors, private pages, and duplicate variants.
- Keep sitemap URLs absolute and valid.
- Generate sitemap indexes when URL volume requires multiple files.
- Maintain image sitemap entries for important crawlable images when useful.
- Keep last modification dates truthful; do not update them on every request without a real content change.
- Regenerate or incrementally update sitemaps when content changes.
- Ensure robots.txt references the correct sitemap URL.
- Avoid huge lists of low-value programmatic URLs.
- Validate XML syntax and URL responses.

Sitemaps help discovery but do not force indexing.