---
name: robots-canonical
description: Control CanliHisse crawl directives and canonicalization to prevent accidental blocking, duplicate indexing, and wrong URL selection.
---
# Robots and Canonical

- Keep important public content crawlable.
- Do not block CSS, JS, images, or essential resources needed for rendering.
- Use robots.txt to manage crawl access, not as a substitute for page-level noindex.
- Keep private/admin/internal areas protected appropriately.
- Every indexable page should have a self-consistent canonical or a deliberate canonical target.
- Canonicals must use HTTPS and the preferred hostname.
- Never canonicalize unrelated pages to the homepage.
- Avoid conflicting canonical tags, sitemap URLs, redirects, and internal links.
- Keep canonical targets indexable and successful.
- Audit parameter and filter URLs for duplicate/crawl-waste behavior.

After changes test robots.txt, canonical tags, redirects, sitemap URLs, and representative page types.