---
name: freshness-monitor
description: Detect stale CanliHisse market data and content, maintain truthful update timestamps, and prevent old information from appearing current.
---
# Freshness Monitor

- Define freshness expectations by data type: live market data, delayed data, news, company facts, and evergreen education.
- Store real retrieval and verification timestamps.
- Mark stale, delayed, historical, and unavailable states explicitly.
- Never change an update date unless the content or data was actually reviewed or updated.
- Detect old prices, broken feeds, failed APIs, stale news labels, and outdated company facts.
- Preserve historical values as historical rather than replacing them with current values.
- Alert or flag pages when important volatile data exceeds its freshness threshold.
- Never hide stale data behind a live-looking UI.

Freshness is a data-quality problem first and an SEO problem second.