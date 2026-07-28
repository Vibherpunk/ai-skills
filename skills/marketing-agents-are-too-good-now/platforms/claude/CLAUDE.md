# Agentic Marketing Teams — Self-Hosted

Build AI marketing agents on open-source infrastructure.

## Stack
- Data pipeline: Airbyte → ClickHouse
- Creative gen: ComfyUI (SDXL/FLUX) + Wav2Lip + Coqui TTS
- Research: SearXNG + Ollama
- Hosting: Coolify or Docker VPS

## Weekly Workflow
1. Research pain points via SearXNG/Reddit + Ollama LLM
2. Generate 5 static images + 1 avatar video per pain point via ComfyUI
3. Publish to FB Ads API (write-only, rate-limited, start PAUSED)
4. 48h learning → kill bottom 30% → promote top 3
5. Inject competitor creative via FB Ads Library + YouTube transcripts

## Budget
- $50/day cap, $15 max CPA, 10 max ads/batch
- Human review gate before ads go live

Source: https://youtu.be/U2hogriGmEw
