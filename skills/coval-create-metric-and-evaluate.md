---
name: Create a Coval metric and evaluate
description: Define an evaluation metric (deterministic, statistical, ML, or LLM-judge), test it, threshold it, and apply it in a run.
api: openapi/coval-metrics-openapi.yml
operations: [createMetric, testMetric, createMetricThreshold, listMetricTemplateVariables, launchRun]
---

# Create a Coval metric and evaluate

Metrics score simulated and production conversations. Types: deterministic (regex/pattern), statistical (timing/acoustic), ML model-based (sentiment/voice consistency), LLM-judge, and trace-derived.

## Auth
`X-API-Key` header; base URL `https://api.coval.dev/v1`.

## Steps
1. **(Optional) Inspect variables** — `listMetricTemplateVariables` (GET) to see the dynamic attributes available in metric prompts.
2. **Create the metric** — `createMetric` (POST `/metrics`) with the metric type and definition/prompt.
3. **Dry-run it** — `testMetric` (POST) against sample input to confirm it scores as intended before you depend on it.
4. **Set a threshold** — `createMetricThreshold` (POST) to define pass/fail bounds for the metric.
5. **Apply** — reference the metric when you `launchRun`; scores appear on each simulation.

## Conventions
- Metrics are versioned (`listMetricVersions` / `revertMetricVersion`); changes are tracked.
- Same Google-RPC error envelope and `page_size`/`page_token` pagination as the rest of the API.
