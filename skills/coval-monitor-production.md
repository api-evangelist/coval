---
name: Monitor production conversations in Coval
description: Submit real production conversations, monitor them against metrics, and read per-conversation scores.
api: openapi/coval-conversations-openapi.yml
operations: [submitConversation, listConversations, getConversation, listConversationMetrics, createMonitor]
---

# Monitor production conversations in Coval

Coval's Observe surface evaluates real production calls, not just simulations.

## Auth
`X-API-Key` header; base URL `https://api.coval.dev/v1`.

## Steps
1. **Ingest** — `submitConversation` (POST `/conversations`) with the transcript/audio and metadata. For audio, `createAudioUpload` first, then attach (attach is once-per-conversation).
2. **(Optional) Traces** — send OpenTelemetry spans via `ingestTraces` for trace-derived metrics.
3. **Set up monitoring** — `createMonitor` (POST `/monitors`) to run metrics automatically on incoming conversations.
4. **Read scores** — `listConversations` (GET) then `listConversationMetrics` (GET `/conversations/{id}/metrics`) or `getConversation` for the full record.
5. **React** — subscribe a `job_complete` webhook (`createWebhook`) to be notified when evaluation finishes.

## Conventions
- Correlate ingestion with `X-Conversation-Id` / `X-Simulation-Id` headers where supported.
- Pagination `page_size`/`page_token`/`cursor`; Google-RPC error envelope. See `conventions/coval-conventions.yml`.
