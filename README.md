# Baseten (baseten)

Baseten is a production inference platform for deploying and serving custom and pre-trained ML models. Offers a Model APIs catalog with OpenAI- and Anthropic-compatible endpoints (DeepSeek, Qwen, GLM, Nemotron), dedicated deployments via Truss, autoscaling GPU compute, async/queue inference, training, chains (multi-model workflows), and management APIs.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/baseten/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=baseten-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## Tags
- AI, ML, Inference, Deployment, MLOps, OpenAI Compatible, Anthropic Compatible, Truss

## APIs
- **Baseten LLM Inference API** — OpenAI-compatible chat completions for Model APIs catalog. Base URL `https://inference.baseten.co/v1`. [Docs](https://docs.baseten.co/) · [OpenAPI](openapi/baseten-llm-openapi.json)
- **Baseten Anthropic-Compatible Messages API** — Anthropic Messages-compatible inference. [OpenAPI](openapi/baseten-messages-openapi.json)
- **Baseten Management & Async API** — Deployment management, async inference, chains, training. Base URL `https://api.baseten.co`.

### Plans
- **Basic** $0/mo PAYG: dedicated deployments, model APIs, training, fast cold starts, SOC 2 + HIPAA, email/in-app chat support.
- **Pro** (volume discounts): everything in Basic + priority GPU, dedicated compute, higher rate limits, hands-on support.
- **Enterprise** (custom): self-hosted options, custom SLAs, data residency, advanced RBAC.

### Sample Pricing
- Model APIs (per-token): DeepSeek V4 $1.74/M input · $3.48/M output. NVIDIA Nemotron 3 Super $0.30/M input · $0.75/M output.
- Compute (per-minute): T4 $0.01052, up to B200 $0.16633. CPU from $0.00058. No charge for idle time.

## Plans, Rate Limits, FinOps
- [Plans](plans/baseten-plans-pricing.yml)
- [RateLimits](rate-limits/baseten-rate-limits.yml) — Async control rate-limited to 20 req/s; tier-dependent inference limits.
- [FinOps](finops/baseten-finops.yml)

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://www.baseten.co/)
- [Documentation](https://docs.baseten.co/)
- [Pricing](https://www.baseten.co/pricing/)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
