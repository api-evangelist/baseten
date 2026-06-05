# Baseten (baseten)

Baseten is a production inference platform for deploying and serving custom and pre-trained ML models. Offers a Model APIs catalog with OpenAI-compatible endpoints (DeepSeek, Qwen, GLM, Nemotron), dedicated deployments via Truss, autoscaling GPU compute, async/queue inference, training, chains (multi-model workflows), and management APIs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/baseten/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/baseten/refs/heads/main/apis.yml)

## Tags

- AI
- ML
- Inference
- Deployment
- MLOps
- OpenAI Compatible
- Anthropic Compatible
- Truss

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-19

## APIs

### Baseten LLM Inference API

OpenAI-compatible chat completions for Baseten's Model APIs catalog (DeepSeek V4, Qwen, GLM, Nemotron, etc.). Per-million-token pricing.

- **Human URL:** [https://docs.baseten.co/reference/inference-api/llm-openapi-spec](https://docs.baseten.co/reference/inference-api/llm-openapi-spec)
- **Base URL:** `https://inference.baseten.co/v1`

#### Tags

- AI
- LLM
- Chat Completions
- OpenAI Compatible

#### Properties

- [Documentation](https://docs.baseten.co/)
- [OpenAPI](openapi/baseten-llm-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/baseten-llm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/baseten-llm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Pricing](https://www.baseten.co/pricing/)

### Baseten Anthropic-Compatible Messages API

Anthropic Messages-compatible inference for compatible Model APIs models.

- **Human URL:** [https://docs.baseten.co/reference/inference-api/messages-openapi-spec](https://docs.baseten.co/reference/inference-api/messages-openapi-spec)
- **Base URL:** `https://inference.baseten.co`

#### Tags

- AI
- LLM
- Anthropic Compatible
- Messages

#### Properties

- [Documentation](https://docs.baseten.co/)
- [OpenAPI](openapi/baseten-messages-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/baseten-messages.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/baseten-messages.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Baseten Management & Async API

Deployment management, async/queued inference, chain calls (multi-model workflows), training, dedicated-deployment lifecycle, async result polling, and webhook delivery.

- **Human URL:** [https://docs.baseten.co/api-reference](https://docs.baseten.co/api-reference)
- **Base URL:** `https://api.baseten.co`

#### Tags

- Management
- Async
- Webhooks
- Deployment
- Training

#### Properties

- [Documentation](https://docs.baseten.co/api-reference)
- [Truss C L I](https://docs.baseten.co/)
- [Postman Collection](collections/baseten-llm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/baseten-llm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/baseten-messages.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/baseten-messages.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/basetenlabs)
- [LinkedIn](https://www.linkedin.com/company/baseten)
- [Website](https://www.baseten.co/)
- [Documentation](https://docs.baseten.co/)
- [Pricing](https://www.baseten.co/pricing/)
- [Plans](plans/baseten-plans-pricing.yml)
- [Rate Limits](rate-limits/baseten-rate-limits.yml)
- [Fin Ops](finops/baseten-finops.yml)
- [L L Ms Txt](https://docs.baseten.co/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
