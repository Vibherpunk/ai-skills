---
description: >-
  Build and deploy AI marketing agents that autonomously research, create, publish,
  and optimize ad campaigns — entirely self-hosted using open-source infrastructure.
name: marketing-agents-are-too-good-now
tags:
- marketing agents
- Facebook ads
- open-source
- self-hosted
- ComfyUI
- Stable Diffusion
- Airbyte
- ClickHouse
- Coolify
---

# Agentic Marketing Teams — Self-Hosted Edition

Build AI marketing agents with all open-source infrastructure.

## Stack
- **Data:** Airbyte → ClickHouse (replace Fivetran/Snowflake)
- **Images:** ComfyUI + SDXL/FLUX (replace Kai AI/Nano Banana)
- **Video/Avatar:** Wav2Lip + Coqui TTS (replace HeyGen/Seedance)
- **Research:** SearXNG + Ollama (replace Perplexity)
- **Hosting:** Coolify / Docker VPS (replace Railway/Heroku)

## Weekly Cycle
1. **Mon:** Research pain points (SearXNG + Ollama LLM)
2. **Tue-Wed:** Generate creative (ComfyUI bulk gen + Wav2Lip videos)
3. **Thu-Sun:** Publish to FB Ads → 48h learning window → auto-optimize

## Safety
- Start ads PAUSED for human review
- Daily cap: $50 | Max CPA: $15 | Max ads/batch: 10
- FB API: write-only, 0.5s rate limit

## Quick Deploy
```bash
docker compose up -d  # Airbyte, ClickHouse, ComfyUI, SearXNG, Ollama
comfy model download --url <SDXL_URL> --relative-path models/checkpoints
python3 agent.py
```

Source: https://youtu.be/U2hogriGmEw
