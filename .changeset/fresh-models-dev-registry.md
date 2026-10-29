---
"@voltagent/core": patch
---

Regenerate the model provider registry from models.dev, adding 156 providers and their model IDs. The six providers models.dev no longer lists (firmware, github-models, iflowcn, kimi-for-coding, llama, v0) stay registered so existing model IDs keep resolving. Seven providers that models.dev moved to packages core has no adapter for (cloudflare-ai-gateway, cloudflare-workers-ai, gitlab, google-vertex-anthropic, openrouter, sap-ai-core, venice) keep their previous configuration. Fixes #1476.
