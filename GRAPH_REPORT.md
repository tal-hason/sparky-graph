# Graph Report - sparky-backup  (2026-11-21)

## Corpus Check
- 198 files · ~376,437 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 14 file(s) not represented in the graph (top: (none) 7, .service 5, .example 1)

## Summary
- 2696 nodes · 5366 edges · 151 communities (132 shown, 19 thin omitted)
- Extraction: 88% EXTRACTED · 12% INFERRED · 0% AMBIGUOUS · INFERRED: 659 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `16565cb2`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- server.js
- reaction-commands.test.js
- ref_fs
- model-router.js
- createSentinelJobs
- server
- Requirements Anchor: Sparky-AI Nightly Dreaming Knowledge Graph (`sparky-nightly-knowledge-graph`)
- Semantic Vector Memory & Cortex Sleep Consolidation Architecture
- createReactionActivityController
- test_graphify_integration.py
- redactSecretsInError
- correction-learner.js
- Sentinel Actor Model & Conversational Handshake Architecture
- The Four Cynefin Domains in Sparky
- createAcpSessionPool
- reaction-commands.js
- kg-store.js
- sparky-mcp/package.json
- http-server.js
- sparky-watchdog.sh
- n8n Stack Configuration & Deployment
- postgres-maintenance.sh
- update-n8n.sh
- backup.sh
- render-local-kg-html.sh
- mcp.test.js
- scripts/test-n8n-patches.js
- event-ingest.js
- update.sh
- memory-hygiene.js
- ref_node_assert
- patch-gemini4-langchain.sh
- install-apps.sh
- restore.sh
- test_agent_telemetry.sh
- extract-n8n-oauth.js
- createCdpSession
- sparky-runtime-dsl.js
- _install_ci_stubs_if_missing
- redactSecretsInError
- n8n-sparky/test-n8n-patches.js
- family-relay.test.js
- acp-client.js
- workspace-mcp/index.js
- test_whisper.py
- family-relay.js
- createGoogleRestMockDriver
- index.js
- queryPostgresJson
- patch-n8n-memory-orphans.sh
- acp-client.test.js
- queryPostgresJson
- publish-graph.sh
- config.js
- workspace-mcp.test.js
- loop-keys.js
- run-acp-eval.py
- Sparky-Plex: Autonomous Executive Assistant & Infrastructure
- acp-session-pool.js
- createDb
- phase2-remediation.test.js
- host-adapters.test.js
- Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`)
- createPostgresMemoryDriver
- whatsapp-ingress-helpers.js
- run-agent-eval.sh
- TaskDaemon
- sync-services-to-repo.sh
- n8n-stack/scripts/deploy-bridge.sh
- eval-history.md
- hook-utils.js
- ref_path
- Requirements Anchor: `[Sparky-AI]` Event-Driven Email Handoff to Gemini App
- n8n-sparky/patch-gemini4-langchain.sh
- n8n-sparky/patch-n8n-memory-orphans.sh
- browser-mcp/package.json
- scripts/patch-retry-backoff.sh
- n8n-sparky/patch-retry-backoff.sh
- app.py
- acp-gateway.js
- Requirements Anchor: Sparky-AI Native Antigravity (`agy acp`) Runtime & `n8n` Retirement (`sparky-agy-native-runtime`)
- tool-policy.js
- ref_child_process
- vertex-fallback.test.js
- phase3-remediation.test.js
- test_workspace_mutations.js
- callVertexWithCascade
- TestDaemon
- host-adapters.js
- createFamilyConciergeStore
- turn-ctx-client.js
- TestSparkyWhisperService
- sqlStr
- acp-gateway-and-pool.test.js
- phase35-parity.test.js
- run
- run
- quiet-hours.test.js
- sparky-runtime-dsl.js
- loop-keys.fixture.test.js
- sparky-agy/package.json
- createStdioAcpRpcClient
- sentinel-scheduler.test.js
- event-ingest.test.js
- Sparky Brain Sync Workflow
- TestAcpPluginSafetyGuard
- Commitments & Scheduling Discipline
- Executive Onboarding Protocol
- Family Relay Privacy & Delivery Protocol
- ref_node_fs
- build-sparky-agy.sh
- seed-acp-tokens.sh
- Sparky Research & Handoff Workflow
- loop-store.js
- processSingleMessage
- acp-routes.js
- whatsapp-egress.js
- family-mcp.test.js
- createHostAdapters
- family-mcp/index.js
- plugin-manager.js
- Sparky Travel, Conference & Trip Prep Workflow
- family-routes.js
- runPsql
- incident-store.test.js
- createSentinelScheduler
- createGoogleOAuthClient
- _StubFastAPI
- createGoogleOAuthClient
- workspace-mcp/package.json
- generateEmbedding
- makeWorld
- Sparky-AI — Gemini Skills (`Customise → Skills`)
- Sparky AGY Mission Dispatch Workflow
- whisper-transcribe.test.js
- handleSentinelError
- fetchBufferFromUrl
- family-mcp/package.json
- whatsapp-ingress.js
- family-concierge-store.js
- ssrf-perimeter.test.js
- Gemini App Scheduled Email Monitor Prompt (`@Sparky`)
- server-endpoints.test.js
- family-concierge-store.test.js
- createAnalyzeDocumentHandler
- sentinel-error-boundary.test.js
- Gemini Scheduled Briefings — Morning & End-of-Day Prompts
- Sparky-AI — Gemini Tasks Prompts Reference (Copy & Paste)
- createMetaTokenReader
- runtime-tools.js
- handleWhatsappTtsRoute

## God Nodes (most connected - your core abstractions)
1. `server` - 131 edges
2. `redactSecretsInError()` - 61 edges
3. `createCdpSession()` - 32 edges
4. `sqlStr()` - 29 edges
5. `queryPostgresJson()` - 25 edges
6. `normalizeIsraeliPhone()` - 24 edges
7. `buildSessionPreamble()` - 24 edges
8. `TaskDaemon` - 21 edges
9. `createDb()` - 21 edges
10. `createGoogleRestMockDriver()` - 21 edges

## Surprising Connections (you probably didn't know these)
- `6. Bounded Complex Probes Required at Session 2 Bootstrap` --references--> `transcribeAudioBuffer()`  [INFERRED]
  docs/brainstorms/sparky-agy-native-runtime-requirements.md → services/vertex-search-bridge/server.js
- `E. WhatsApp Ingress, Audio, Google Workspace MCP & Sentinels` --references--> `transcribeAudioBuffer()`  [INFERRED]
  docs/brainstorms/sparky-agy-native-runtime-requirements.md → services/vertex-search-bridge/server.js
- `1. User Intent & Selected Architecture` --references--> `buildSessionPreamble()`  [INFERRED]
  docs/brainstorms/sparky-dynamic-model-routing-requirements.md → services/vertex-search-bridge/server.js
- `A2. Full-Ecosystem Scope (Locked Across All 8 Branches)` --references--> `buildAgyTaskPayload()`  [INFERRED]
  docs/brainstorms/sparky-gemini4-neon-roster-requirements.md → services/vertex-search-bridge/agy-mission-client.js
- `🛠️ Microservice Bridge (Port 5055)` --references--> `formatFamilyOutboxBatch()`  [INFERRED]
  README.md → services/vertex-search-bridge/family-morning.js

## Import Cycles
- None detected.

## Communities (151 total, 19 thin omitted)

### Community 0 - "server.js"
Cohesion: 0.02
Nodes (88): acpRoutes, {
  ALLOWED_WORKSPACES,
  ALLOWED_AGY_MODELS,
  validateOptionalAgyModel,
  buildAgyTaskPayload,
  dispatchAgyMissionToDrive,
}, backgroundPostTurnPromises, BRIDGE_API_TOKEN, BRIDGE_STARTED_AT, chatMirrorStore, circuitBreakers, {
  classifyDecisionChoice,
  inferDecisionSource,
  extractSenderKey,
  computeSenderAdjustment,
  formatTriageFeedbackXml,
  createNudgeTelemetryStore,
} (+80 more)

### Community 1 - "reaction-commands.test.js"
Cohesion: 0.08
Nodes (13): AgyDriver, assert, BridgeCommandDriver, { EventEmitter }, fs, loadCorrectionLearner(), loadReactionCommands(), os (+5 more)

### Community 2 - "ref_fs"
Cohesion: 0.21
Nodes (12): bridgeRequest(), fs, { bridgeRequest }, fs, isSafeHeartbeatPath(), path, readStdin(), runHook() (+4 more)

### Community 3 - "model-router.js"
Cohesion: 0.07
Nodes (53): 1. Locked Architecture & 4-Model Periodic Roster (Bootstrap + `/grill-me` Convergence), 2. Live Empirical Probe Ground Truth (`spark-509400` & `agy` CLI, 2026-11-19), 3. Bounded Complex Probes Gating Rollout, 4. Post-Pre-Flight Run #1 `/grill-me` Convergence (Branches 1–5 Locked), A1. Strict Monotonic 6-Tier Periodic Matrix (`COGNITIVE_TIERS` in `/root/vertex-search-bridge/model-router.js`), A3. Generalized Heavy-Model Circuit Breaker & Guardrails, Requirements Anchor: Sparky-AI Gemini 4 Neon 4-Model Periodic Roster, parseBareChoice() (+45 more)

### Community 4 - "createSentinelJobs"
Cohesion: 0.22
Nodes (25): buildFallbackContext(), cleanNullable(), cleanPreMeetingTokens(), countPreMeetingTokenOverlap(), createSentinelJobs(), callBridgeJson(), dispatchMessage(), fetchCalendarEventsRange() (+17 more)

### Community 5 - "server"
Cohesion: 0.10
Nodes (33): evaluateCommuteWindow(), filterAndSortEvents(), formatCommuteBriefingLine(), formatIsoTimeIl(), formatOriginLabel(), hasVideo(), isPhysical(), isVirtualLink() (+25 more)

### Community 6 - "Requirements Anchor: Sparky-AI Nightly Dreaming Knowledge Graph (`sparky-nightly-knowledge-graph`)"
Cohesion: 0.50
Nodes (3): 1. User Intent & Selected Architecture (1 + 3 Hybrid), 2. Core Invariants & Boundaries, Requirements Anchor: Sparky-AI Nightly Dreaming Knowledge Graph (`sparky-nightly-knowledge-graph`)

### Community 7 - "Semantic Vector Memory & Cortex Sleep Consolidation Architecture"
Cohesion: 0.11
Nodes (18): 1. Architectural Blueprint & Cognitive Model, 2. Infrastructure & Storage (`pgvector`), 3. Multilingual Embedding Pipeline, 4. Bridge Microservice Endpoints ([`server.js`](file:///root/vertex-search-bridge/server.js)), 5. Main Agent Integration (`search_memory` FunctionCall), 6. Nightly Cortex Sleep Consolidation (`POST /cortex/sleep-cycle`), 7.1 PostgreSQL Relational + Vector Graph Schema, 7.2 Nightly Single-Pass Extraction & Backfill (+10 more)

### Community 8 - "createReactionActivityController"
Cohesion: 0.15
Nodes (24): A2. Full-Ecosystem Scope (Locked Across All 8 Branches), cloneConfig(), createReactionActivityController(), completeTurn(), dispatchEmojiNow(), evictIfFull(), getConfig(), getOrCreateState() (+16 more)

### Community 9 - "test_graphify_integration.py"
Cohesion: 0.05
Nodes (12): TestGoldenDatasetPresence, TestPostRetirementInvariants, TestSessionIsolation, _extract_source_files(), TestAntigravitySkillAndRulesRegistration, TestCodebaseInclusionInGraph, TestDeterministicCLIGraphQuery, TestEopSkillAndBackupScriptContract (+4 more)

### Community 10 - "redactSecretsInError"
Cohesion: 0.22
Nodes (14): computeSignature(), createIncidentStore(), draftLessonsFromCandidates(), recordCandidate(), crypto, normalizeErrorKey(), redactAndNormalizeError(), sqlStr() (+6 more)

### Community 11 - "correction-learner.js"
Cohesion: 0.10
Nodes (33): DEF-04: Real-Time In-Turn Correction Learning (`"No, I meant..."`), containsSecretOrPassword(), createCorrectionLearner(), extractAndSaveCorrection(), detectCorrectionSignal(), findDuplicateFieldNote(), redactAllSecrets(), SECRET_PATTERNS (+25 more)

### Community 12 - "Sentinel Actor Model & Conversational Handshake Architecture"
Cohesion: 0.20
Nodes (9): 1. Executive Summary, 2. Dual-Channel XML Sensory Pipeline, 3. Active Conversational Handshake & Latency Masking, 4. Active Workflow Catalog (11 Total), 5. Central Egress Hub (`/whatsapp/dispatch`), Sentinel Actor Model & Conversational Handshake Architecture, The Problem, The Solution (+1 more)

### Community 13 - "The Four Cynefin Domains in Sparky"
Cohesion: 0.22
Nodes (8): 1. Clear / Simple Domain (Known Knowns), 2. Complicated Domain (Known Unknowns), 3. Complex Domain (Unknown Unknowns), 4. Chaotic Domain (Unknowables / Crises), 5. Aporia / Confusion, Architectural Overview, Cynefin + OODA Loop Cognitive Framework, The Four Cynefin Domains in Sparky

### Community 14 - "createAcpSessionPool"
Cohesion: 0.21
Nodes (16): createAcpSessionPool(), buildMcpServers(), clearWarmState(), currentAuth(), executeTurn(), getRpc(), handleNotification(), maybeRecycleIdle() (+8 more)

### Community 15 - "reaction-commands.js"
Cohesion: 0.13
Nodes (28): computeDefaultShipmentFollowUp(), getJerusalemDateTimeParts(), { buildAgyTaskPayload }, buildReactionLoopTitle(), buildResult(), {
  classifyShipmentLifecycle,
  computeDefaultShipmentFollowUp,
  getJerusalemDateTimeParts,
}, computeSnoozeTarget(), createReactionCommandService() (+20 more)

### Community 16 - "kg-store.js"
Cohesion: 0.10
Nodes (48): atomicWriteFile(), bareTableName(), buildAsciiVaultSlug(), buildCanonicalEntityId(), buildDeterministicEdgeId(), canonicalDescriptorToString(), createKgStore(), ensureKgTables() (+40 more)

### Community 17 - "sparky-mcp/package.json"
Cohesion: 0.25
Nodes (7): description, main, name, private, scripts, test, version

### Community 18 - "http-server.js"
Cohesion: 0.11
Nodes (24): RFC-8414, RFC-9728, ALLOWED_REDIRECT_HOSTS, { bridgeRequest }, createMcpHttpServer(), crypto, DEFAULT_PUBLIC_ORIGIN, escHtml() (+16 more)

### Community 19 - "sparky-watchdog.sh"
Cohesion: 0.50
Nodes (7): can_alert(), flush_incident_buffer(), PATH, record_alert(), record_watchdog_incident(), send_direct_wa_alert(), sparky-watchdog.sh script

### Community 20 - "n8n Stack Configuration & Deployment"
Cohesion: 0.40
Nodes (4): Architecture, 🔒 Crucial Notes on `N8N_ENCRYPTION_KEY`, 🚀 Deployment Instructions, n8n Stack Configuration & Deployment

### Community 22 - "update-n8n.sh"
Cohesion: 0.40
Nodes (4): HOME, PATH, REGISTRY_AUTH_FILE, update-n8n.sh script

### Community 23 - "backup.sh"
Cohesion: 0.43
Nodes (6): cleanup_wf_export(), encrypt_file(), HOME, PATH, run_encrypted_secrets_stage(), backup.sh script

### Community 24 - "render-local-kg-html.sh"
Cohesion: 0.50
Nodes (3): HOME, PATH, render-local-kg-html.sh script

### Community 25 - "mcp.test.js"
Cohesion: 0.13
Nodes (11): assert, { createMcpHttpServer, processJsonRpcMessage }, crypto, fs, http, RFC-7591, mcpIndex, os (+3 more)

### Community 26 - "scripts/test-n8n-patches.js"
Cohesion: 0.11
Nodes (17): { cleanupOrphanedMessages }, { ensureParams, failedAttemptHandler }, failedHandlerPath, fs, geminiCjsPath, geminiMessages, geminiMessagesPath, { getGeminiAPI } (+9 more)

### Community 27 - "event-ingest.js"
Cohesion: 0.06
Nodes (53): RFC-2822, ACTOR_ROUTE_KEY, ALLOWED_ACTOR_SOURCE_SET, ALLOWED_ACTOR_SOURCES, BRIEF_ACTOR_SOURCES, { CALLER_DEFAULT_ROUTES }, { computeSenderAdjustment }, createEventIngestHandler() (+45 more)

### Community 28 - "update.sh"
Cohesion: 0.67
Nodes (5): PATH, recreate_acp_containers(), rollback_acp_containers(), update.sh script, wait_for_acp_health()

### Community 29 - "memory-hygiene.js"
Cohesion: 0.07
Nodes (45): 1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4), 2. Quality Gates, Observability & Disaster Recovery (Epic E3), 3. Platform Architecture & Refactoring (Epic E5), DEF-01: Global Attention Budget & Quiet Hours Hold Queue (`23:00–07:00`), DEF-02: Nudge-Effectiveness Telemetry & Sentinel Self-Tuning, DEF-03: Sunday Weekly Review & Overdue Loop Escalation Ladder, DEF-05: Semantic Memory Contradiction Detection & Temporal Decay, DEF-06: Auto-Incident Knowledge Base (`knowledge-base.json`) Draft Capture (+37 more)

### Community 30 - "ref_node_assert"
Cohesion: 0.05
Nodes (36): assert, { createAcpHookDriver }, DECISION_HELPERS_PATH, dsl, EGRESS_PATH, path, test, assert (+28 more)

### Community 33 - "restore.sh"
Cohesion: 0.40
Nodes (4): HOME, PATH, restore.sh script, verify_and_extract_secrets()

### Community 35 - "extract-n8n-oauth.js"
Cohesion: 0.24
Nodes (13): assertNotSymlinkFile(), crypto, decryptN8nCredential(), evpBytesToKeyMd5(), { execFileSync }, fs, inspectWorkflowVerifyFallback(), main() (+5 more)

### Community 36 - "createCdpSession"
Cohesion: 0.05
Nodes (77): RFC-6455, buildWsUrl(), clampIdleTtl(), CONTENT_AX_ROLES, createCdpSession(), applyViewport(), click(), close() (+69 more)

### Community 37 - "sparky-runtime-dsl.js"
Cohesion: 0.10
Nodes (21): buildMetaWebhookPayload(), crypto, http, listenWebhookTestServer(), sendRawWebhookRequest(), signMetaPayload(), probeWhatsappWebhookSecurity(), resolveEmailReactionClearsGmail() (+13 more)

### Community 38 - "_install_ci_stubs_if_missing"
Cohesion: 0.11
Nodes (9): _FakeFloatArray, _install_ci_stubs_if_missing(), _concatenate(), to_ndarray(), astype(), flatten(), __getitem__(), reshape() (+1 more)

### Community 39 - "redactSecretsInError"
Cohesion: 0.16
Nodes (19): ALLOWED_AGY_MODEL_SET, ALLOWED_AGY_MODELS, ALLOWED_WORKSPACES, buildAgyTaskPayload(), buildFencedMissionPrompt(), dispatchAgyMissionToDrive(), fetchAgyAccessToken(), fs (+11 more)

### Community 40 - "n8n-sparky/test-n8n-patches.js"
Cohesion: 0.11
Nodes (17): { cleanupOrphanedMessages }, { ensureParams, failedAttemptHandler }, failedHandlerPath, fs, geminiCjsPath, geminiMessages, geminiMessagesPath, { getGeminiAPI } (+9 more)

### Community 41 - "family-relay.test.js"
Cohesion: 0.14
Nodes (17): assert, BACKUP_FILE, { buildCanonicalLoopKey, generateDeterministicLoopId }, clone(), createFakeWorld(), mergeJsonbLiteral(), queryPostgresJson(), queryPostgresWithStdin() (+9 more)

### Community 42 - "acp-client.js"
Cohesion: 0.12
Nodes (22): createAcpClient(), fetchRehydrateHistory(), runTurn(), crypto, escapeXmlText(), formatOutreachDeltaXml(), http, https (+14 more)

### Community 43 - "workspace-mcp/index.js"
Cohesion: 0.05
Nodes (69): RFC-2045, CALENDAR_TOOLS, calendarRequest(), executeCalendarTool(), { googleRestRequest, clampLimit }, normalizeEventDateTime(), DRIVE_TOOLS, executeDriveTool() (+61 more)

### Community 44 - "test_whisper.py"
Cohesion: 0.08
Nodes (5): extract_stream_json_result(), resolve_task_model(), resolve_timeouts(), _StubHTTPException, _StubJSONResponse

### Community 45 - "family-relay.js"
Cohesion: 0.19
Nodes (20): classifyFamilyInboundText(), createFamilyRelayService(), configureFamilyMember(), handleFamilyInbound(), loadCtx(), loadFamilyLoops(), processFamilyInbound(), recordChatHistory() (+12 more)

### Community 46 - "createGoogleRestMockDriver"
Cohesion: 0.07
Nodes (20): createGoogleRestMockDriver(), close(), dispatchRequest(), fetchFn(), start(), http, makeMockResponse(), toBase64Url() (+12 more)

### Community 47 - "index.js"
Cohesion: 0.13
Nodes (20): processJsonRpcMessage(), { bridgeRequest }, dispatchAgyMissionToDrive(), fs, getToolsForProfile(), handleToolCall(), HOST_TOOL_ALLOWLIST, readHeartbeatMeta() (+12 more)

### Community 48 - "queryPostgresJson"
Cohesion: 0.11
Nodes (30): buildTodayIsraelRange(), advanceInTransitLoopOnKeepTracking(), buildSessionPreamble(), checkAndDispatchDueReminders(), createDecision(), effectiveDue(), familyRoutes, getSentinelEvent() (+22 more)

### Community 50 - "acp-client.test.js"
Cohesion: 0.06
Nodes (26): ACP_CLIENT_PATH, assert, CHAT_MIRROR_PATH, close(), CONFIG_PATH, { createMockAcpFaultDriver }, { createPostgresMemoryDriver }, DB_PATH (+18 more)

### Community 51 - "queryPostgresJson"
Cohesion: 0.21
Nodes (23): normalizeReactionEmoji(), acpClient, applyWhatsAppDeliveryStatuses(), familyConciergeStore, familyRelay, getWindowState(), invalidateWindowStateCache(), logActivityEvent() (+15 more)

### Community 52 - "publish-graph.sh"
Cohesion: 0.50
Nodes (3): HOME, PATH, publish-graph.sh script

### Community 53 - "config.js"
Cohesion: 0.11
Nodes (13): 1. User Intent & Selected Architecture, 2. Verified Architectural Invariants & Test Alignment, Requirements Anchor: Sparky-AI Dynamic Main Agent Model & Effort Routing, ALLOWED_FAMILY_POST_ROUTES, compactSessionChatHistory(), compactToolObservationContent(), crypto, defaultConfig (+5 more)

### Community 54 - "workspace-mcp.test.js"
Cohesion: 0.11
Nodes (15): ALL_27_TOOLS, assert, { createGoogleRestMockDriver }, { createMcpStdioDriver }, EXPECTED_CALENDAR_TOOLS, EXPECTED_DRIVE_WORKSPACE_TOOLS, EXPECTED_GMAIL_TOOLS, EXPECTED_MUTATING_TOOLS (+7 more)

### Community 55 - "loop-keys.js"
Cohesion: 0.18
Nodes (21): buildCanonicalLoopKey(), classifyLoopsByDue(), classifyShipmentLifecycle(), crypto, effectiveDue(), encodeCanonicalLoopId(), extractLoopEntityKey(), extractShipmentIdentifiers() (+13 more)

### Community 56 - "run-acp-eval.py"
Cohesion: 0.24
Nodes (9): build_eval_system_context(), compute_runtime_fingerprint(), evaluate_case(), http_post_json(), load_bridge_token(), main(), normalize_tool_name(), parse_judge_score() (+1 more)

### Community 57 - "Sparky-Plex: Autonomous Executive Assistant & Infrastructure"
Cohesion: 0.25
Nodes (7): Automated Backup, 🔄 Automated Backup & Disaster Recovery, Full Disaster Recovery, 📁 Repository Structure, 🔒 Security & Privacy Notice, Sparky-Plex: Autonomous Executive Assistant & Infrastructure, 🏛️ System Architecture

### Community 58 - "acp-session-pool.js"
Cohesion: 0.20
Nodes (15): ensureSession(), loadBoundedRehydration(), { createStdioAcpRpcClient }, fs, { isTruthyFlag }, {
  PROFILE_TOOL_SETS,
  parseCanonicalToolName,
  collectToolArgObjects,
  resolveProfileForTurn,
  isToolAllowedForProfile,
}, {
  setBoundedMap,
  buildMcpServers: buildMcpServersHelper,
  loadBoundedRehydration: loadBoundedRehydrationHelper,
  isQuotaError,
  isSessionNotFoundError,
  lookupStoredSession: lookupStoredSessionHelper,
  persistSession: persistSessionHelper,
  recordSessionUpdate,
}, STEP_DOWN_CHAIN (+7 more)

### Community 59 - "createDb"
Cohesion: 0.07
Nodes (35): pg, resolveConfig(), createDb(), bindPsqlParams(), ensureAcpSchema(), formatPsqlLiteral(), getOrInitPgPool(), parseJsonTextOrFallback() (+27 more)

### Community 60 - "phase2-remediation.test.js"
Cohesion: 0.08
Nodes (20): createDecisionRoutesHandler(), DB_ERR_SENTINEL, assert, { createAcpClient }, { createAcpRoutesHandler }, { createAnalyzeDocumentHandler }, { createDb }, { createDecisionRoutesHandler } (+12 more)

### Community 61 - "host-adapters.test.js"
Cohesion: 0.18
Nodes (7): assert, fs, HOST_ADAPTERS_PATH, http, net, path, test

### Community 62 - "Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`)"
Cohesion: 0.33
Nodes (5): Emergency Sub-Minute Rollback to Host `systemd` (`vertex-search.service`), Overview, Returning from Host `systemd` to Container (`vertex-bridge`), Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`), Standard Deployment & Digest Rollback (`deploy-bridge.sh`)

### Community 63 - "createPostgresMemoryDriver"
Cohesion: 0.11
Nodes (26): assert, CONFIG_PATH, { createPostgresMemoryDriver }, dsl, fs, path, SERVER_PATH, SUT_PATH (+18 more)

### Community 64 - "whatsapp-ingress-helpers.js"
Cohesion: 0.14
Nodes (21): decisionIdMatchesButton(), parseDecisionButtonId(), buildAgentTurnInput(), buildPhaseOverrideXml(), COMMAND_REACTIONS, EDITH_P, escXml(), FRIDAY_P (+13 more)

### Community 65 - "run-agent-eval.sh"
Cohesion: 0.50
Nodes (3): HOME, PATH, run-agent-eval.sh script

### Community 66 - "TaskDaemon"
Cohesion: 0.16
Nodes (3): read_heartbeat_meta(), sd_notify(), TaskDaemon

### Community 70 - "hook-utils.js"
Cohesion: 0.14
Nodes (8): fs, http, https, path, redactSecretsInError(), readline, { redactSecretsInError }, { spawn }

### Community 71 - "ref_path"
Cohesion: 0.25
Nodes (9): { execFileSync }, fs, main(), migrateJsCode(), migrateNodes(), migrateUrlParam(), path, runPsql() (+1 more)

### Community 75 - "browser-mcp/package.json"
Cohesion: 0.18
Nodes (10): description, engines, node, main, name, private, scripts, start (+2 more)

### Community 78 - "app.py"
Cohesion: 0.09
Nodes (6): _decode_audio_to_float32(), health(), lifespan(), transcribe(), _transcribe_and_release(), _transcribe_sync()

### Community 79 - "acp-gateway.js"
Cohesion: 0.25
Nodes (10): createAcpGatewayServer(), { createAcpSessionPool }, createCachedTokenReader(), crypto, fs, http, readJsonBody(), { redactSecretsInError } (+2 more)

### Community 80 - "Requirements Anchor: Sparky-AI Native Antigravity (`agy acp`) Runtime & `n8n` Retirement (`sparky-agy-native-runtime`)"
Cohesion: 0.11
Nodes (22): 1. Executive Summary & Core Architectural Decision, 2. Empirical Ground Truth Verified on Host (2026-11-20), 3. Target Architecture Topology, 4. Core Component Design & Invariants, 5. Phased Rollout Plan (Strangler Fig), 6. Bounded Complex Probes Required at Session 2 Bootstrap, A. `sparky-agy` Warm Container & ACP Gateway, B. Direct Family Privacy & Bidirectional Stream Bridge (+14 more)

### Community 81 - "tool-policy.js"
Cohesion: 0.22
Nodes (12): handlePermissionRequest(), collectToolArgObjects(), FAMILY_TOOLS, GEMINI_UNTRUSTED_TOOLS, hasDisallowedGeminiMediaFields(), isToolAllowedForProfile(), parseCanonicalToolName(), parseSingleArgValue() (+4 more)

### Community 82 - "ref_child_process"
Cohesion: 0.28
Nodes (7): assert, { createLoopStore }, { execFile }, queryPostgresJson(), queryPostgresWithStdin(), store, test

### Community 83 - "vertex-fallback.test.js"
Cohesion: 0.17
Nodes (23): {
  ALLOWED_VERTEX_GENERATIVE_MODELS,
  DEFAULT_SENSORY_FALLBACK_CHAIN,
  DEFAULT_CARBON_FALLBACK_CHAIN,
  DEFAULT_NEON_FALLBACK_CHAIN,
  DEFAULT_SEARCH_FALLBACK_CHAIN,
  isAllowedGemini4Model,
  extractVertexLocationAndModel,
  buildVertexGenerateContentPath,
  resolveFallbackChain,
  usesThinkingLevel,
  deprecatesSamplingParams,
  adaptVertexPayloadForModel,
  isFallbackEligibleVertexError,
  callVertexWithModelFallback,
  extractVertexCandidateText,
}, assert, fs, path, test, adaptGenerationContainer(), adaptVertexPayloadForModel(), ALLOWED_VERTEX_GENERATIVE_MODELS (+15 more)

### Community 84 - "phase3-remediation.test.js"
Cohesion: 0.08
Nodes (21): assert, { buildMetaWebhookPayload }, { createAcpRoutesHandler }, { createAnalyzeDocumentHandler }, { createDb }, { createSentinelErrorBoundary }, { createSentinelJobs }, { createSentinelScheduler } (+13 more)

### Community 85 - "test_workspace_mutations.js"
Cohesion: 0.10
Nodes (17): APPEND_WF_PATH, cleanupRegistry, CREATE_DOC_WF_PATH, CREATE_SHEET_WF_PATH, CREATE_SLIDES_WF_PATH, { execSync, execFileSync }, EXPECTED_HEADERS, formatOutput() (+9 more)

### Community 86 - "callVertexWithCascade"
Cohesion: 0.13
Nodes (25): readStreamUtf8(), analyzeImageBuffer(), analyzeImageByMediaId(), callGeminiJson(), callGoogleRoutesApi(), callOsrmFallback(), callVertexApiWithRetry(), callVertexFastJson() (+17 more)

### Community 88 - "host-adapters.js"
Cohesion: 0.11
Nodes (22): BROWSERLESS_REJECT_PATTERNS, renderPage(), DEFAULT_ALLOWED_PUBLIC_PORTS, dns, { execFile, execSync }, extractReadableDom(), fetchViaJina(), fs (+14 more)

### Community 89 - "createFamilyConciergeStore"
Cohesion: 0.38
Nodes (14): createFamilyConciergeStore(), completeRelayFromAgent(), flushMessagesForTal(), getCachedSchedule(), loadOpenRelayLoops(), manageMessageForTal(), manageMessageForTalUnlocked(), recordChatHistory() (+6 more)

### Community 90 - "turn-ctx-client.js"
Cohesion: 0.38
Nodes (9): getBridgeToken(), { getBridgeToken }, getTurnContext(), http, https, nodeHttpFetch(), postTurnEgress(), resolveTurnCtxEndpoint() (+1 more)

### Community 91 - "TestSparkyWhisperService"
Cohesion: 0.10
Nodes (14): _find_route_endpoint(), _invoke_endpoint(), _run_app_startup_and_call(), _StubUploadFile, TestSparkyWhisperService, check_after_startup(), raise_once(), run_probe() (+6 more)

### Community 92 - "sqlStr"
Cohesion: 0.23
Nodes (23): createFamilyOutboxStore(), ackBatch(), claimDueBatches(), deferBatch(), ensureSchema(), inspectBatchState(), loadQueuedBatch(), mergeFlushingIntoQueued() (+15 more)

### Community 93 - "acp-gateway-and-pool.test.js"
Cohesion: 0.18
Nodes (10): assert, { buildMcpServers }, { createAcpGatewayServer }, { createAcpSessionPool }, { createStdioAcpRpcClient }, fs, os, path (+2 more)

### Community 94 - "phase35-parity.test.js"
Cohesion: 0.06
Nodes (40): extractInteractiveOptions(), FAMILY_NON_DECISION_SOURCES, getDecisionSourceAliases(), INTERACTIVE_SENTINEL_SOURCES, linkOrCreateDecisionWithDeps(), NON_DECISION_SOURCES, SOURCE_ALIAS_GROUPS, createHeartbeatStore() (+32 more)

### Community 95 - "run"
Cohesion: 0.17
Nodes (10): assert, entries, makeHttpErrorResponse(), makePlainJsonResponse(), makeSseStreamResponse(), makeWrappedAbortGaxiosError(), run(), bodyGen() (+2 more)

### Community 96 - "run"
Cohesion: 0.17
Nodes (10): assert, entries, makeHttpErrorResponse(), makePlainJsonResponse(), makeSseStreamResponse(), makeWrappedAbortGaxiosError(), run(), bodyGen() (+2 more)

### Community 97 - "quiet-hours.test.js"
Cohesion: 0.21
Nodes (9): BYPASS_SOURCES, computeQuietHoursVerdict(), getLocalHour(), hourFormatter, isQuietWindow(), checkAndDispatchWindowKeepalive(), assert, {
  QUIET_START_HOUR,
  QUIET_END_HOUR,
  TZ,
  BYPASS_SOURCES,
  getLocalHour,
  isQuietWindow,
  computeQuietHoursVerdict,
} (+1 more)

### Community 98 - "sparky-runtime-dsl.js"
Cohesion: 0.07
Nodes (43): assert, {
  createAcpHookDriver,
  resolveTalPreToolHookPath,
  resolveTalStopHookPath,
  resolveFamilyPreToolHookPath,
  resolveAcpSessionPoolPath,
}, DENIED_BUILTINS, dsl, EXPECTED_FAMILY, EXPECTED_GEMINI_UNTRUSTED, EXPECTED_SENTINEL_AGYDAEMON, EXPECTED_TAL_EVAL (+35 more)

### Community 99 - "loop-keys.fixture.test.js"
Cohesion: 0.25
Nodes (6): assert, FIXTURE_PATH, fs, { generateDeterministicLoopId }, path, test

### Community 100 - "sparky-agy/package.json"
Cohesion: 0.20
Nodes (9): description, engines, node, name, private, scripts, start, test (+1 more)

### Community 101 - "createStdioAcpRpcClient"
Cohesion: 0.50
Nodes (9): createStdioAcpRpcClient(), cleanup(), close(), ensureInitialized(), ensureStarted(), rawRequest(), request(), safeWriteLine() (+1 more)

### Community 102 - "sentinel-scheduler.test.js"
Cohesion: 0.15
Nodes (12): assert, { createDb }, createRealDbHarness(), dsl, ERROR_BOUNDARY_PATH, fs, JOBS_PATH, path (+4 more)

### Community 103 - "event-ingest.test.js"
Cohesion: 0.09
Nodes (16): createAcpHookDriver(), close(), execHook(), runPreToolHook(), runStopHook(), ACP_ROUTES_PATH, assert, { createAcpHookDriver, resolveTalPreToolHookPath } (+8 more)

### Community 104 - "Sparky Brain Sync Workflow"
Cohesion: 0.33
Nodes (5): Safety Invariants, Sparky Brain Sync Workflow, Step 1 — Audit Existing State Before Writing, Step 2 — Respect Consent & Confirmation Boundaries, Step 3 — Route Each Artifact to the Exact Right Tool

### Community 106 - "Commitments & Scheduling Discipline"
Cohesion: 0.40
Nodes (4): Commitments & Scheduling Discipline, Dual-Anchor Rule, Hebrew Colloquial Intent, Symmetric Closure (No Zombie Blocks)

### Community 107 - "Executive Onboarding Protocol"
Cohesion: 0.50
Nodes (3): Executive Onboarding Protocol, When Onboarding Is Already Completed (`onboarding="completed"`), When Onboarding Is Pending (`onboarding="pending"` / `"in_progress"`)

### Community 108 - "Family Relay Privacy & Delivery Protocol"
Cohesion: 0.50
Nodes (3): Family Relay Privacy & Delivery Protocol, Inbound Family Updates, Outbound Relay to Gal

### Community 109 - "ref_node_fs"
Cohesion: 0.06
Nodes (26): assert, CONFIG_PATH, fs, os, path, test, fs, readline (+18 more)

### Community 112 - "Sparky Research & Handoff Workflow"
Cohesion: 0.33
Nodes (5): Sparky Research & Handoff Workflow, Step 1 — Ground Context in `@Sparky` First, Step 2 — Execute Focused Research, Step 3 — Deliver Clean Output in Gemini Chat, Step 4 — Sync Conclusion Back to `@Sparky`

### Community 113 - "loop-store.js"
Cohesion: 0.14
Nodes (16): { parseIsoMs }, { redactSecretsInError }, { sqlStr, sqlJsonb, sqlJsonbArray, sqlTimestamptz }, { stripCalendarEventForFamily, projectTalSchedule }, {
  ACTIONABLE_STATUS_RE,
  generateDeterministicLoopId,
  stripBidi,
}, sanitizeSqlValue(), sqlJsonb(), sqlJsonbArray() (+8 more)

### Community 114 - "processSingleMessage"
Cohesion: 0.54
Nodes (8): createWhatsAppIngressHandler(), fetchTodayCalendarForFamily(), handleFamilyTurn(), processSingleMessage(), processWebhookPayload(), recordMetricRow(), sendMetaReadAndTyping(), sendViaDispatch()

### Community 115 - "acp-routes.js"
Cohesion: 0.27
Nodes (8): createAcpRoutesHandler(), handleAcpOrSearchRoute(), requireBridgeToken(), dns, escSentinelXml(), { handleWebReadRoute }, handleWebReadRoute(), sendJsonResponse()

### Community 116 - "whatsapp-egress.js"
Cohesion: 0.16
Nodes (24): applyBypassTestGuard(), buildInteractiveOrTextPayload(), buildReplyButtonsPayload(), computeFooterCappedText(), copyForwardedKeys(), createWhatsAppEgress(), postGraphJson(), sendWhatsAppDirect() (+16 more)

### Community 117 - "family-mcp.test.js"
Cohesion: 0.15
Nodes (10): assert, { createMcpStdioDriver }, EXPECTED_5_TOOLS, FAMILY_MCP_ENTRY, fs, http, os, path (+2 more)

### Community 118 - "createHostAdapters"
Cohesion: 0.26
Nodes (11): DEF-10: Bridge Monolith Decomposition (`server.js`), Native PG Pool & `BRIDGE_URL` Env, 🛠️ Microservice Bridge (Port 5055), assertSafePublicUrlWithDns(), createHostAdapters(), assertSafeBrowserUrl(), assertSafeBrowserUrlAsync(), captureScreenshot(), checkNfs() (+3 more)

### Community 119 - "family-mcp/index.js"
Cohesion: 0.24
Nodes (11): ALLOWED_TOOL_NAMES, callFamilyBridge(), DEFAULT_BRIDGE_URL, fs, getImmutableFamilySender(), handleToolCall(), readFamilyBridgeToken(), readline (+3 more)

### Community 120 - "plugin-manager.js"
Cohesion: 0.33
Nodes (10): assertNotSymlinkIfExists(), assertSafeSkillPaths(), assertValidSlug(), fs, handleManageSparkyPlugin(), path, readFileNoFollow(), resolveSkillsDir() (+2 more)

### Community 121 - "Sparky Travel, Conference & Trip Prep Workflow"
Cohesion: 0.33
Nodes (5): Sparky Travel, Conference & Trip Prep Workflow, Step 1 — Anchor Time & Existing Sparky Context, Step 2 — Gather Reservations & Schedule, Step 3 — Deliver Structured Hebrew Checklist, Step 4 — Optional Sparky Sync (Only When Asked)

### Community 122 - "family-routes.js"
Cohesion: 0.22
Nodes (17): normalizeIsraeliPhone(), resolveAuthorizedUserByPhone(), createFamilyRoutesHandler(), handleFamilyRoute(), handleJsonRoute(), requireToken(), resolveAuthorizedFamilyHeaderSender(), sendFamilyError() (+9 more)

### Community 123 - "runPsql"
Cohesion: 0.20
Nodes (11): assertBalancedSentinelXml(), assertHostileEscaped(), cleanupReactionDeckTestRows(), cleanupTestSentinelState(), execPsqlStrict(), restoreLivePendingAndCleanTests(), runPsql(), saveAndSupersedeLivePending() (+3 more)

### Community 124 - "incident-store.test.js"
Cohesion: 0.38
Nodes (6): assert, { execFile }, queryPostgresJson(), {
  redactSecretsInError,
  normalizeErrorKey,
  computeSignature,
  createIncidentStore,
}, runPsql(), test

### Community 125 - "createSentinelScheduler"
Cohesion: 0.26
Nodes (9): createSentinelScheduler(), markExternalSlotComplete(), persistWatermark(), readWatermark(), start(), tickDueJobs(), getDueSlotKey(), getJerusalemSlotParts() (+1 more)

### Community 126 - "createGoogleOAuthClient"
Cohesion: 0.31
Nodes (8): createGoogleOAuthClient(), getAccessToken(), getOAuthMeta(), loadOAuthCredentials(), refreshToken(), defaultOAuthFilePath(), fs, redactOAuthSecrets()

### Community 127 - "_StubFastAPI"
Cohesion: 0.27
Nodes (4): _StubFastAPI, decorator(), decorator(), _StubRoute

### Community 128 - "createGoogleOAuthClient"
Cohesion: 0.31
Nodes (8): createGoogleOAuthClient(), getAccessToken(), getOAuthMeta(), loadOAuthCredentials(), refreshToken(), defaultOAuthFilePath(), fs, redactOAuthSecrets()

### Community 129 - "workspace-mcp/package.json"
Cohesion: 0.20
Nodes (9): description, engines, node, main, name, private, scripts, test (+1 more)

### Community 130 - "generateEmbedding"
Cohesion: 0.40
Nodes (6): generateEmbedding(), insertSemanticMemory(), memoryHygieneStore, sanitizeContent(), searchSemanticMemories(), searchSemanticMemoriesByVector()

### Community 131 - "makeWorld"
Cohesion: 0.60
Nodes (6): makeWorld(), parseItemsArray(), parseJsonbParam(), queryPostgresJson(), queryPostgresWithStdin(), test

### Community 132 - "Sparky-AI — Gemini Skills (`Customise → Skills`)"
Cohesion: 0.40
Nodes (4): How to Upload into Gemini, Included Skills, Note on Gemini Native Memory vs. Sparky Memory, Sparky-AI — Gemini Skills (`Customise → Skills`)

### Community 133 - "Sparky AGY Mission Dispatch Workflow"
Cohesion: 0.40
Nodes (4): Sparky AGY Mission Dispatch Workflow, Step 1 — Pre-Flight Context Check (Prevent Collisions), Step 2 — Formulate a Tight Systems-Architect Prompt, Step 3 — Dispatch Gate & Execution

### Community 134 - "whisper-transcribe.test.js"
Cohesion: 0.22
Nodes (8): assert, dsl, extractComposeServiceBlock(), fs, path, SERVER_PATH, test, WHISPER_CLIENT_PATH

### Community 135 - "handleSentinelError"
Cohesion: 0.31
Nodes (8): createSentinelErrorBoundary(), evictExpiredCooldowns(), handleSentinelError(), recordIncidentCandidate(), sendDirectMetaFallback(), { redactSecretsInError, normalizeErrorKey, computeSignature }, resolveNowMs(), safeCoerceErrorMessage()

### Community 138 - "family-mcp/package.json"
Cohesion: 0.33
Nodes (5): description, main, name, private, version

### Community 139 - "whatsapp-ingress.js"
Cohesion: 0.18
Nodes (10): buildIsraelTodayBounds(), crypto, getIsraelIsoOffset(), extractDeliveryStatuses(), { isTestPayload }, markEmailAsReadInGmail(), { redactSecretsInError }, { safeTokenEqual } (+2 more)

### Community 140 - "family-concierge-store.js"
Cohesion: 0.12
Nodes (23): {
  ADMIN_PHONE,
  normalizeIsraeliPhone,
  resolveAuthorizedUserByPhone,
  sanitizeFamilyText,
}, { createFamilyMorningService }, { createFamilyOutboxStore }, {
  escXml,
  formatIlDate,
  stripCalendarEventForFamily,
  projectTalSchedule,
  resolveFamilyGrammar,
  buildFamilyContextXml,
  computeKeepaliveDecision,
  computeFamilyKeepaliveDecision,
  applyDispatchAckButtonPolicy,
}, { formatIsoTimeIl }, { redactSecretsInError }, { sqlStr, sqlJsonb, sqlJsonbArray, sqlTimestamptz }, { ADMIN_PHONE, normalizeIsraeliPhone, sanitizeFamilyText } (+15 more)

### Community 142 - "ssrf-perimeter.test.js"
Cohesion: 0.18
Nodes (10): ACP_ROUTES_PATH, assert, dsl, fs, HOST_ADAPTERS_PATH, http, os, path (+2 more)

### Community 145 - "server-endpoints.test.js"
Cohesion: 0.08
Nodes (24): assert, callBridge(), checkActiveDecision(), checkCommute(), checkDue(), checkReminders(), commitTriagedLoop(), dispatchDefault() (+16 more)

### Community 147 - "family-concierge-store.test.js"
Cohesion: 0.08
Nodes (19): applyDispatchAckButtonPolicy(), BRIEFING_ACK_SOURCES, computeFamilyKeepaliveDecision(), computeKeepaliveDecision(), FEMALE_REL_SET, getLocalHourMinuteIl(), IL_DATE_FMT, IL_HOUR_MINUTE_FMT (+11 more)

### Community 148 - "createAnalyzeDocumentHandler"
Cohesion: 0.60
Nodes (4): createAnalyzeDocumentHandler(), acquireSlot(), handleAnalyzeDocumentRoute(), releaseSlot()

### Community 152 - "sentinel-error-boundary.test.js"
Cohesion: 0.25
Nodes (7): assert, BOUNDARY_PATH, { createDb }, createIncidentDbHarness(), fs, path, test

### Community 154 - "Gemini Scheduled Briefings — Morning & End-of-Day Prompts"
Cohesion: 0.40
Nodes (4): Architecture & Failsafe Summary, Gemini Scheduled Briefings — Morning & End-of-Day Prompts, Task 1 — Daily Morning Brief (Schedule: `07:30 Asia/Jerusalem` Daily), Task 2 — Daily End-of-Day Brief (Schedule: `18:30 Asia/Jerusalem` Daily)

### Community 156 - "Sparky-AI — Gemini Tasks Prompts Reference (Copy & Paste)"
Cohesion: 0.18
Nodes (10): Sparky-AI — Gemini Tasks Prompts Reference (Copy & Paste), Task 1 — Real-Time Incoming Email Triage, Task 2 — Daily VIP & Ghosting Follow-Up Radar, Task 3 — Daily Morning Brief (Flight Plan), Task 4 — Daily End-of-Day Brief, Task 5 (Optional) — Morning Non-Urgent Email Digest, Task 6 — Sunday Week-Ahead Lookahead, Task 7 — Monthly Subscription, Invoice & Price-Hike Audit (+2 more)

### Community 157 - "createMetaTokenReader"
Cohesion: 0.31
Nodes (10): createMetaTokenReader(), getMetaAppSecret(), getMetaToken(), getMetaVerifyToken(), parseEnvKey(), refreshIfNeeded(), handleWebhookRequest(), sendJson() (+2 more)

### Community 159 - "runtime-tools.js"
Cohesion: 0.15
Nodes (12): RUNTIME_AND_REMOTE_TOOLS, RUNTIME_ONLY_NAMES, ALLOWED_INGEST_SOURCES, assertNoGeminiMediaPlaceholder(), { getTurnContext, postTurnEgress }, { handleManageSparkyPlugin }, handleRuntimeToolCall(), INTERACTIVE_FORWARD_KEYS (+4 more)

### Community 162 - "handleWhatsappTtsRoute"
Cohesion: 0.16
Nodes (17): handleReactionExecuteRoute(), handleWhatsappTtsRoute(), loadCleanDialogueTurns(), parseStrictJsonBody(), reactionCommandService, sendWhatsAppMediaDirect(), sqlQuote(), sqlQuoteOrNull() (+9 more)

## Knowledge Gaps
- **22 isolated node(s):** `PATH`, `PATH`, `HOME`, `REGISTRY_AUTH_FILE`, `PATH` (+17 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 1230 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **19 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `3. Platform Architecture & Refactoring (Epic E5)` connect `memory-hygiene.js` to `createHostAdapters`?**
  _High betweenness centrality (0.145) - this node is a cross-community bridge._
- **Are the 3 inferred relationships involving `redactSecretsInError()` (e.g. with `handleAcpOrSearchRoute()` and `incident-store.js`) actually correct?**
  _`redactSecretsInError()` has 3 INFERRED edges - model-reasoned connections that need verification._
- **What connects `PATH`, `PATH`, `HOME` to the rest of the system?**
  _22 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `server.js` be split into smaller, more focused modules?**
  _Cohesion score 0.022216913521261348 - nodes in this community are weakly interconnected._
- **Why does `_StubUploadFile` connect `TestSparkyWhisperService` to `test_whisper.py`, `memory-hygiene.js`?**
  _High betweenness centrality (0.144) - this node is a cross-community bridge._
- **Should `reaction-commands.test.js` be split into smaller, more focused modules?**
  _Cohesion score 0.07956989247311828 - nodes in this community are weakly interconnected._
- **Should `model-router.js` be split into smaller, more focused modules?**
  _Cohesion score 0.07142857142857142 - nodes in this community are weakly interconnected._