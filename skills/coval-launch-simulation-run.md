---
name: Launch a Coval simulation run
description: Connect an agent, define a test set, and launch a simulated-conversation evaluation run, then read the results.
api: openapi/coval-runs-openapi.yml
operations: [createAgent, createTestSet, createTestCase, launchRun, getRun, listSimulations]
---

# Launch a Coval simulation run

Coval simulates realistic voice/chat conversations against an agent under test and scores them.

## Auth
Send `X-API-Key: <org key>` on every request. Base URL `https://api.coval.dev/v1`.

## Steps
1. **Connect the agent** — `createAgent` (POST `/agents`) with the connection type (inbound/outbound voice, chat, OpenAI Realtime, Gemini Live, Pipecat, LiveKit, …) and endpoint config. Save the returned `agent_id`.
2. **Define scenarios** — `createTestSet` (POST `/test-sets`), then `createTestCase` (POST `/test-cases`) for each scenario. A test case carries the scenario/transcript/script input and expected behavior.
3. **Launch** — `launchRun` (POST `/runs/launch-run`) referencing the `agent_id`, a `persona_id`, and the `test_set_id`. Save the returned `run_id`.
4. **Track** — poll `getRun` (GET `/runs/{run_id}`) until complete, or subscribe to the `job_complete` webhook instead of polling.
5. **Read results** — `listSimulations` (GET `/simulations?run_id=...`) for per-conversation outcomes and metric scores.

## Conventions
- List endpoints paginate with `page_size` + `page_token`/`cursor`; follow `next_cursor`.
- Errors return `{ error: { code, message, details } }` (codes: INVALID_ARGUMENT, UNAUTHENTICATED, PERMISSION_DENIED, NOT_FOUND, ALREADY_EXISTS, INTERNAL). See `errors/coval-problem-types.yml`.
- There is no Idempotency-Key; re-launching creates a new run.
