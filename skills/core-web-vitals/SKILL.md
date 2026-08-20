---
name: core-web-vitals
description: Diagnose and improve CanliHisse real-user performance, Core Web Vitals, mobile UX, rendering cost, images, ads, charts, and API latency without removing useful content.
---
# Core Web Vitals

## Targets
Optimize LCP, INP, and CLS using field evidence when available. Treat performance as a user-experience requirement, not only a score.

## LCP
Inspect server response time, critical rendering path, hero/image priority, font loading, SSR/HTML availability, and render-blocking assets. Do not lazy-load the primary LCP resource.

## INP
Find expensive event handlers, unnecessary React work, large client bundles, chart recalculation, filters, and synchronous tasks. Prefer smaller work, memoization where justified, deferred work, and server-side computation when appropriate.

## CLS
Reserve dimensions for images, charts, ads, banners, fonts, and dynamic widgets. Never insert content above existing content unexpectedly.

## Network and Assets
Use compression, caching, code splitting, responsive images, modern formats, and minimal client JavaScript. Avoid loading large libraries for simple interactions.

## Financial UI
Stock charts and live data must remain functional. Optimize polling, subscriptions, rendering, and data transformations rather than removing essential market information.

## Validation
Measure before/after on representative mobile and desktop pages. Check real-user signals when available, then verify no SEO, accessibility, layout, or financial-data regressions were introduced.
