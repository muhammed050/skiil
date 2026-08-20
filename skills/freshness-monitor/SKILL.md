---
name: freshness-monitor
description: Detect stale market data and editorial content on CanliHisse, enforce truthful freshness signals, and prevent fake updates.
---
# Freshness Monitor

## Data Freshness
Track when available: retrieved_at, updated_at, last_verified_at, source, and status. Use explicit states: live, delayed, historical, updating, unavailable.

## Market Data
Prioritize volatile prices, volume, exchange status, feeds, and timestamps. A page-render timestamp is not a data-retrieval timestamp unless it represents the retrieval event.

If a provider fails, preserve a clearly labeled last verified value or show unavailable. Never make stale data appear live.

## Editorial Freshness
Only change an article's update date after a genuine review or material update. Preserve historical facts and publication dates. Never refresh dates solely for SEO.

## Monitoring
Detect stale records, broken feeds, expired links, outdated company facts, and articles requiring factual review. Prefer fixing upstream data/revalidation processes.

## QA
Test timezone handling, caching, revalidation, API failures, and visible timestamps. Confirm every freshness label matches actual data state.
