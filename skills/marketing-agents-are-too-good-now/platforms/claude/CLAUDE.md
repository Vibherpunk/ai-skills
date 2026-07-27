# Marketing Agents Are Too Good Now

Build AI marketing agents that research pain points, generate creatives, publish to Facebook Ads, and optimize in a continuous loop — powered by a unified data warehouse.

## Architecture
- **Data Pipeline:** Airbyte → ClickHouse (unify FB Ads, GA, Stripe, CRM)
- **Agent Hosting:** Railway/Heroku/cloud
- **FB API:** Write-only (publish, turn off, promote)

## Workflow
1. Research pain points (Reddit, Perplexity) → Rank by frequency
2. Generate creative (Kai AI, Nano Banana, HeyGen, Seedance)
3. Publish to FB Ads via Marketing API
4. 2-3 day learning window → Auto-optimize
5. Feedback loop: analyze what works, generate more like it

## Entropy Prevention
- Facebook Ads Library for competitor creative
- YouTube/podcast transcripts for fresh insights

## Quick Start
1. Set up data pipeline
2. Connect data sources
3. Deploy agent code to cloud
4. Connect FB Marketing API
5. Start with 2 ad sets/day, 5 ads/ad set

Source: https://youtu.be/U2hogriGmEw — Cody Schneider × Greg Isenberg
