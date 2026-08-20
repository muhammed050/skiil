---
name: freshness-monitor
description: Detect and manage stale CanliHisse market data and editorial content without fake timestamps or meaningless updates.
---
# Freshness Monitor

Track appropriate fields such as retrieved_at, updated_at, last_verified_at, source, and data status.

For market data distinguish live, delayed, historical, updating, and unavailable. Never generate a timestamp from page-render time unless it represents the actual data retrieval event.

For editorial content, only change an updated date after genuine review or material update. Preserve historical context and facts.

Prioritize stale volatile data, broken feeds, outdated company information, expired links, and articles requiring factual updates.

When data is unavailable, show unavailable or the last verified value with clear labeling. Never refresh a timestamp to make stale content appear fresh.
