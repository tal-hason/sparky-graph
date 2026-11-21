# Graph Report - sparky-backup  (2026-11-21)

## Corpus Check
- 169 files · ~330,019 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 13 file(s) not represented in the graph (top: (none) 6, .service 5, .example 1)

## Summary
- 2265 nodes · 4481 edges · 146 communities (118 shown, 28 thin omitted)
- Extraction: 87% EXTRACTED · 13% INFERRED · 0% AMBIGUOUS · INFERRED: 566 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `fa808cd4`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- server.js
- reaction-commands.test.js
- ref_fs
- model-router.js
- server-endpoints.test.js
- server
- Requirements Anchor: Sparky-AI Nightly Dreaming Knowledge Graph (`sparky-nightly-knowledge-graph`)
- Semantic Vector Memory & Cortex Sleep Consolidation Architecture
- createReactionActivityController
- test_graphify_integration.py
- 2. Quality Gates, Observability & Disaster Recovery (Epic E3)
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
- family-relay.test.js
- update.sh
- memory-hygiene.js
- ref_node_fs
- patch-gemini4-langchain.sh
- install-apps.sh
- restore.sh
- test_agent_telemetry.sh
- nudge-telemetry.js
- incident-store.js
- sparky-runtime-dsl.js
- createDb
- ref_node_assert
- n8n-sparky/test-n8n-patches.js
- lifecycle.test.js
- acp-client.js
- workspace-mcp/index.js
- daemon.py
- family-relay.js
- createGoogleRestMockDriver
- index.js
- buildSessionPreamble
- patch-n8n-memory-orphans.sh
- acp-client.test.js
- queryPostgresJson
- publish-graph.sh
- config.js
- TestEvaluationHarnessWorkflow
- loop-keys.js
- run-acp-eval.py
- family-concierge-store.js
- acp-session-pool.js
- vertex-search-bridge/package.json
- phase2-remediation.test.js
- test_agent_evaluation.py
- Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`)
- createPostgresMemoryDriver
- probe-db-parity.js
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
- TestDynamicModelRoutingCallers
- scripts/patch-retry-backoff.sh
- n8n-sparky/patch-retry-backoff.sh
- Requirements Anchor: Sparky-AI Dynamic Main Agent Model & Effort Routing
- acp-gateway.js
- Requirements Anchor: Sparky-AI Native Antigravity (`agy acp`) Runtime & `n8n` Retirement (`sparky-agy-native-runtime`)
- tool-policy.js
- createMockAcpFaultDriver
- vertex-fallback.test.js
- triage-helpers.js
- test_workspace_mutations.js
- callVertexWithCascade
- TestDaemon
- host-adapters.js
- createFamilyConciergeStore
- runtime-tools.js
- TestFamilyConciergeWorkflows
- sqlStr
- acp-gateway-and-pool.test.js
- Sparky-Plex: Autonomous Executive Assistant & Infrastructure
- run
- run
- quiet-hours.test.js
- event-ingest.test.js
- workspace-mcp.test.js
- sparky-agy/package.json
- createStdioAcpRpcClient
- handleWhatsappTtsRoute
- db.js
- normalizeIsraeliPhone
- TestAcpPluginSafetyGuard
- Commitments & Scheduling Discipline
- Executive Onboarding Protocol
- Family Relay Privacy & Delivery Protocol
- computeDefaultShipmentFollowUp
- build-sparky-agy.sh
- seed-acp-tokens.sh
- google-oauth-client.test.js
- TestReactionCommandDeckWorkflows
- makeWorld
- acp-routes.js
- whatsapp-egress.js
- family-mcp.test.js
- createHostAdapters
- family-mcp/index.js
- plugin-manager.js
- migrate-loop-keys.js
- runPsql
- ssrf-perimeter.test.js
- isTestPayload
- stdio-rpc-client.js
- createGoogleOAuthClient
- turn-ctx-client.js
- createGoogleOAuthClient
- workspace-mcp/package.json
- ref_child_process
- handoff-store.js
- event-ingest.js
- createHandoffStore
- loop-keys.fixture.test.js
- tts-adapter.js
- containsSecretOrPassword
- TestEvaluationSafetyGuard
- family-mcp/package.json
- createMetaTokenReader
- 1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4)
- createAnalyzeDocumentHandler
- TtsDriver
- Gemini App Scheduled Email Monitor Prompt (`@Sparky`)
- ref_node_vm
- fetchBufferFromUrl

## God Nodes (most connected - your core abstractions)
1. `server` - 134 edges
2. `redactSecretsInError()` - 52 edges
3. `sqlStr()` - 29 edges
4. `queryPostgresJson()` - 24 edges
5. `buildSessionPreamble()` - 23 edges
6. `TaskDaemon` - 21 edges
7. `normalizeIsraeliPhone()` - 20 edges
8. `createModelRouter()` - 20 edges
9. `createGoogleRestMockDriver()` - 20 edges
10. `createAcpSessionPool()` - 19 edges

## Surprising Connections (you probably didn't know these)
- `6. Bounded Complex Probes Required at Session 2 Bootstrap` --references--> `transcribeAudioBuffer()`  [INFERRED]
  docs/brainstorms/sparky-agy-native-runtime-requirements.md → services/vertex-search-bridge/server.js
- `E. WhatsApp Ingress, Audio, Google Workspace MCP & Sentinels` --references--> `transcribeAudioBuffer()`  [INFERRED]
  docs/brainstorms/sparky-agy-native-runtime-requirements.md → services/vertex-search-bridge/server.js
- `1. User Intent & Selected Architecture` --references--> `buildSessionPreamble()`  [INFERRED]
  docs/brainstorms/sparky-dynamic-model-routing-requirements.md → services/vertex-search-bridge/server.js
- `2. Verified Architectural Invariants & Test Alignment` --references--> `compactSessionChatHistory()`  [INFERRED]
  docs/brainstorms/sparky-dynamic-model-routing-requirements.md → services/vertex-search-bridge/config.js
- `🛠️ Microservice Bridge (Port 5055)` --references--> `formatFamilyOutboxBatch()`  [INFERRED]
  README.md → services/vertex-search-bridge/family-morning.js

## Import Cycles
- None detected.

## Communities (146 total, 28 thin omitted)

### Community 0 - "server.js"
Cohesion: 0.02
Nodes (79): acpRoutes, {
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
} (+71 more)

### Community 1 - "reaction-commands.test.js"
Cohesion: 0.09
Nodes (12): AgyDriver, assert, BridgeCommandDriver, { EventEmitter }, fs, loadCorrectionLearner(), loadReactionCommands(), os (+4 more)

### Community 2 - "ref_fs"
Cohesion: 0.21
Nodes (12): bridgeRequest(), fs, { bridgeRequest }, fs, isSafeHeartbeatPath(), path, readStdin(), runHook() (+4 more)

### Community 3 - "model-router.js"
Cohesion: 0.07
Nodes (53): 1. Locked Architecture & 4-Model Periodic Roster (Bootstrap + `/grill-me` Convergence), 2. Live Empirical Probe Ground Truth (`spark-509400` & `agy` CLI, 2026-11-19), 3. Bounded Complex Probes Gating Rollout, 4. Post-Pre-Flight Run #1 `/grill-me` Convergence (Branches 1–5 Locked), A1. Strict Monotonic 6-Tier Periodic Matrix (`COGNITIVE_TIERS` in `/root/vertex-search-bridge/model-router.js`), A3. Generalized Heavy-Model Circuit Breaker & Guardrails, Requirements Anchor: Sparky-AI Gemini 4 Neon 4-Model Periodic Roster, parseBareChoice() (+45 more)

### Community 4 - "server-endpoints.test.js"
Cohesion: 0.09
Nodes (23): assert, callBridge(), checkActiveDecision(), checkCommute(), checkDue(), checkReminders(), commitTriagedLoop(), dispatchDefault() (+15 more)

### Community 5 - "server"
Cohesion: 0.10
Nodes (35): evaluateCommuteWindow(), filterAndSortEvents(), formatCommuteBriefingLine(), formatIsoTimeIl(), formatOriginLabel(), hasVideo(), isPhysical(), isVirtualLink() (+27 more)

### Community 6 - "Requirements Anchor: Sparky-AI Nightly Dreaming Knowledge Graph (`sparky-nightly-knowledge-graph`)"
Cohesion: 0.50
Nodes (3): 1. User Intent & Selected Architecture (1 + 3 Hybrid), 2. Core Invariants & Boundaries, Requirements Anchor: Sparky-AI Nightly Dreaming Knowledge Graph (`sparky-nightly-knowledge-graph`)

### Community 7 - "Semantic Vector Memory & Cortex Sleep Consolidation Architecture"
Cohesion: 0.11
Nodes (18): 1. Architectural Blueprint & Cognitive Model, 2. Infrastructure & Storage (`pgvector`), 3. Multilingual Embedding Pipeline, 4. Bridge Microservice Endpoints ([`server.js`](file:///root/vertex-search-bridge/server.js)), 5. Main Agent Integration (`search_memory` FunctionCall), 6. Nightly Cortex Sleep Consolidation (`POST /cortex/sleep-cycle`), 7.1 PostgreSQL Relational + Vector Graph Schema, 7.2 Nightly Single-Pass Extraction & Backfill (+10 more)

### Community 8 - "createReactionActivityController"
Cohesion: 0.08
Nodes (40): A2. Full-Ecosystem Scope (Locked Across All 8 Branches), ALLOWED_AGY_MODEL_SET, ALLOWED_AGY_MODELS, ALLOWED_WORKSPACES, buildAgyTaskPayload(), buildFencedMissionPrompt(), dispatchAgyMissionToDrive(), fetchAgyAccessToken() (+32 more)

### Community 9 - "test_graphify_integration.py"
Cohesion: 0.07
Nodes (9): _extract_source_files(), TestAntigravitySkillAndRulesRegistration, TestCodebaseInclusionInGraph, TestDeterministicCLIGraphQuery, TestEopSkillAndBackupScriptContract, TestGraphifyCLIBinary, TestIncrementalUpdateIdempotency, TestPersonalMemoryGraphIsolation (+1 more)

### Community 10 - "2. Quality Gates, Observability & Disaster Recovery (Epic E3)"
Cohesion: 0.17
Nodes (11): 2. Quality Gates, Observability & Disaster Recovery (Epic E3), 3. Platform Architecture & Refactoring (Epic E5), DEF-06: Auto-Incident Knowledge Base (`knowledge-base.json`) Draft Capture, DEF-07: Golden Evaluation Dataset Expansion (`3/45` → Core Tools) & Change Gate, DEF-08: Daily Sentinel Heartbeat SLO Monitor, DEF-09: Turnkey Bare-Metal DR Playbook & Encrypted Credential Bootstrap (`restore.sh`), DEF-11: Meta WhatsApp Delivery & Read Receipt Tracking, Detailed Backlog Items (+3 more)

### Community 11 - "correction-learner.js"
Cohesion: 0.26
Nodes (12): DEF-04: Real-Time In-Turn Correction Learning (`"No, I meant..."`), createCorrectionLearner(), extractAndSaveCorrection(), detectCorrectionSignal(), findDuplicateFieldNote(), redactAllSecrets(), SECRET_PATTERNS, stripChatWrapper() (+4 more)

### Community 12 - "Sentinel Actor Model & Conversational Handshake Architecture"
Cohesion: 0.20
Nodes (9): 1. Executive Summary, 2. Dual-Channel XML Sensory Pipeline, 3. Active Conversational Handshake & Latency Masking, 4. Active Workflow Catalog (11 Total), 5. Central Egress Hub (`/whatsapp/dispatch`), Sentinel Actor Model & Conversational Handshake Architecture, The Problem, The Solution (+1 more)

### Community 13 - "The Four Cynefin Domains in Sparky"
Cohesion: 0.22
Nodes (8): 1. Clear / Simple Domain (Known Knowns), 2. Complicated Domain (Known Unknowns), 3. Complex Domain (Unknown Unknowns), 4. Chaotic Domain (Unknowables / Crises), 5. Aporia / Confusion, Architectural Overview, Cynefin + OODA Loop Cognitive Framework, The Four Cynefin Domains in Sparky

### Community 14 - "createAcpSessionPool"
Cohesion: 0.20
Nodes (17): createAcpSessionPool(), buildMcpServers(), clearWarmState(), currentAuth(), executeTurn(), getRpc(), handleNotification(), handlePermissionRequest() (+9 more)

### Community 15 - "reaction-commands.js"
Cohesion: 0.15
Nodes (24): { buildAgyTaskPayload }, buildReactionLoopTitle(), buildResult(), {
  classifyShipmentLifecycle,
  computeDefaultShipmentFollowUp,
  getJerusalemDateTimeParts,
}, createReactionCommandService(), dispatchByAction(), executeReactionCommand(), pruneCache() (+16 more)

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

### Community 27 - "family-relay.test.js"
Cohesion: 0.05
Nodes (44): decisionIdMatchesButton(), extractInteractiveOptions(), FAMILY_NON_DECISION_SOURCES, INTERACTIVE_SENTINEL_SOURCES, linkOrCreateDecisionWithDeps(), NON_DECISION_SOURCES, parseDecisionButtonId(), SOURCE_ALIAS_GROUPS (+36 more)

### Community 29 - "memory-hygiene.js"
Cohesion: 0.13
Nodes (29): DEF-05: Semantic Memory Contradiction Detection & Temporal Decay, computeRecencyBoost(), createMemoryHygieneStore(), findCandidateNeighbors(), ingestMemoryWithHygiene(), reconcileExistingMemories(), EPISODIC_TYPES, extractSearchTokens() (+21 more)

### Community 30 - "ref_node_fs"
Cohesion: 0.07
Nodes (24): assert, DB_PATH, fs, path, test, assert, { execFileSync }, fs (+16 more)

### Community 33 - "restore.sh"
Cohesion: 0.47
Nodes (5): HOME, PATH, restore.sh script, sync_published_versions_sql(), verify_and_extract_secrets()

### Community 35 - "nudge-telemetry.js"
Cohesion: 0.17
Nodes (20): classifyDecisionChoice(), computeSenderAdjustment(), createNudgeTelemetryStore(), getEffectivenessReport(), getSenderFeedback(), extractSenderKey(), formatTriageFeedbackXml(), inferDecisionSource() (+12 more)

### Community 36 - "incident-store.js"
Cohesion: 0.16
Nodes (22): computeSignature(), createIncidentStore(), draftLessonsFromCandidates(), recordCandidate(), crypto, normalizeErrorKey(), redactAndNormalizeError(), redactSecretsInError() (+14 more)

### Community 37 - "sparky-runtime-dsl.js"
Cohesion: 0.07
Nodes (40): assert, {
  createAcpHookDriver,
  resolveTalPreToolHookPath,
  resolveTalStopHookPath,
  resolveFamilyPreToolHookPath,
  resolveAcpSessionPoolPath,
}, DENIED_BUILTINS, dsl, EXPECTED_FAMILY, EXPECTED_GEMINI_UNTRUSTED, EXPECTED_SENTINEL_AGYDAEMON, EXPECTED_TAL_EVAL (+32 more)

### Community 38 - "createDb"
Cohesion: 0.28
Nodes (12): pg, createDb(), bindPsqlParams(), ensureAcpSchema(), formatPsqlLiteral(), getOrInitPgPool(), parseJsonTextOrFallback(), queryPostgresJson() (+4 more)

### Community 39 - "ref_node_assert"
Cohesion: 0.08
Nodes (20): assert, { createAcpHookDriver }, DECISION_HELPERS_PATH, dsl, EGRESS_PATH, path, test, assert (+12 more)

### Community 40 - "n8n-sparky/test-n8n-patches.js"
Cohesion: 0.11
Nodes (17): { cleanupOrphanedMessages }, { ensureParams, failedAttemptHandler }, failedHandlerPath, fs, geminiCjsPath, geminiMessages, geminiMessagesPath, { getGeminiAPI } (+9 more)

### Community 41 - "lifecycle.test.js"
Cohesion: 0.10
Nodes (15): assert, CONFIG_PATH, fs, os, path, test, assert, CONFIG_PATH (+7 more)

### Community 42 - "acp-client.js"
Cohesion: 0.08
Nodes (35): assertNotSymlinkFile(), crypto, decryptN8nCredential(), evpBytesToKeyMd5(), { execFileSync }, fs, inspectWorkflowVerifyFallback(), main() (+27 more)

### Community 43 - "workspace-mcp/index.js"
Cohesion: 0.06
Nodes (61): RFC-2045, CALENDAR_TOOLS, calendarRequest(), executeCalendarTool(), { googleRestRequest, clampLimit }, normalizeEventDateTime(), DRIVE_TOOLS, executeDriveTool() (+53 more)

### Community 44 - "daemon.py"
Cohesion: 0.09
Nodes (5): extract_stream_json_result(), read_heartbeat_meta(), resolve_task_model(), resolve_timeouts(), sd_notify()

### Community 45 - "family-relay.js"
Cohesion: 0.18
Nodes (24): classifyFamilyInboundText(), createFamilyRelayService(), configureFamilyMember(), handleFamilyInbound(), loadCtx(), loadFamilyLoops(), processFamilyInbound(), recordChatHistory() (+16 more)

### Community 46 - "createGoogleRestMockDriver"
Cohesion: 0.08
Nodes (15): createGoogleRestMockDriver(), close(), dispatchRequest(), fetchFn(), start(), http, makeMockResponse(), toBase64Url() (+7 more)

### Community 47 - "index.js"
Cohesion: 0.13
Nodes (20): processJsonRpcMessage(), { bridgeRequest }, dispatchAgyMissionToDrive(), fs, getToolsForProfile(), handleToolCall(), HOST_TOOL_ALLOWLIST, readHeartbeatMeta() (+12 more)

### Community 48 - "buildSessionPreamble"
Cohesion: 0.11
Nodes (31): getDecisionSourceAliases(), advanceInTransitLoopOnKeepTracking(), buildSessionPreamble(), checkAndDispatchDueReminders(), checkAndDispatchWindowKeepalive(), createDecision(), effectiveDue(), familyRoutes (+23 more)

### Community 50 - "acp-client.test.js"
Cohesion: 0.09
Nodes (19): ACP_CLIENT_PATH, assert, CHAT_MIRROR_PATH, close(), CONFIG_PATH, { createMockAcpFaultDriver }, { createPostgresMemoryDriver }, DB_PATH (+11 more)

### Community 51 - "queryPostgresJson"
Cohesion: 0.22
Nodes (22): acpClient, familyConciergeStore, familyRelay, getWindowState(), invalidateWindowStateCache(), logActivityEvent(), queryPostgresStrict(), queryPostgresWithStdin() (+14 more)

### Community 52 - "publish-graph.sh"
Cohesion: 0.50
Nodes (3): HOME, PATH, publish-graph.sh script

### Community 53 - "config.js"
Cohesion: 0.14
Nodes (10): ALLOWED_FAMILY_POST_ROUTES, compactSessionChatHistory(), compactToolObservationContent(), crypto, defaultConfig, evaluateBridgeAuth(), fs, normalizeHistoryRow() (+2 more)

### Community 55 - "loop-keys.js"
Cohesion: 0.19
Nodes (19): buildCanonicalLoopKey(), classifyLoopsByDue(), classifyShipmentLifecycle(), crypto, effectiveDue(), extractLoopEntityKey(), extractShipmentIdentifiers(), formatDueBucket() (+11 more)

### Community 56 - "run-acp-eval.py"
Cohesion: 0.21
Nodes (9): build_eval_system_context(), compute_runtime_fingerprint(), evaluate_case(), http_post_json(), load_bridge_token(), main(), normalize_tool_name(), parse_judge_score() (+1 more)

### Community 57 - "family-concierge-store.js"
Cohesion: 0.06
Nodes (43): 🏛️ System Architecture, {
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
}, { formatIsoTimeIl }, { redactSecretsInError }, { sqlStr, sqlJsonb, sqlJsonbArray, sqlTimestamptz } (+35 more)

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

### Community 59 - "vertex-search-bridge/package.json"
Cohesion: 0.14
Nodes (13): dependencies, pg, description, engines, node, main, name, private (+5 more)

### Community 60 - "phase2-remediation.test.js"
Cohesion: 0.08
Nodes (20): createDecisionRoutesHandler(), DB_ERR_SENTINEL, assert, { createAcpClient }, { createAcpRoutesHandler }, { createAnalyzeDocumentHandler }, { createDb }, { createDecisionRoutesHandler } (+12 more)

### Community 61 - "test_agent_evaluation.py"
Cohesion: 0.14
Nodes (4): _eval_n8n_expr(), TestGoldenDatasetPresence, TestSessionIsolation, TestWorkflowTelemetry

### Community 62 - "Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`)"
Cohesion: 0.33
Nodes (5): Emergency Sub-Minute Rollback to Host `systemd` (`vertex-search.service`), Overview, Returning from Host `systemd` to Container (`vertex-bridge`), Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`), Standard Deployment & Digest Rollback (`deploy-bridge.sh`)

### Community 63 - "createPostgresMemoryDriver"
Cohesion: 0.11
Nodes (26): assert, CONFIG_PATH, { createPostgresMemoryDriver }, dsl, fs, path, SERVER_PATH, SUT_PATH (+18 more)

### Community 64 - "probe-db-parity.js"
Cohesion: 0.29
Nodes (6): resolveConfig(), assert, config, { createDb }, main(), QUERIES

### Community 65 - "run-agent-eval.sh"
Cohesion: 0.50
Nodes (3): HOME, PATH, run-agent-eval.sh script

### Community 70 - "hook-utils.js"
Cohesion: 0.22
Nodes (4): fs, http, https, path

### Community 71 - "ref_path"
Cohesion: 0.25
Nodes (9): { execFileSync }, fs, main(), migrateJsCode(), migrateNodes(), migrateUrlParam(), path, runPsql() (+1 more)

### Community 78 - "Requirements Anchor: Sparky-AI Dynamic Main Agent Model & Effort Routing"
Cohesion: 0.50
Nodes (3): 1. User Intent & Selected Architecture, 2. Verified Architectural Invariants & Test Alignment, Requirements Anchor: Sparky-AI Dynamic Main Agent Model & Effort Routing

### Community 79 - "acp-gateway.js"
Cohesion: 0.24
Nodes (11): createAcpGatewayServer(), { createAcpSessionPool }, createCachedTokenReader(), crypto, fs, http, readJsonBody(), { redactSecretsInError } (+3 more)

### Community 80 - "Requirements Anchor: Sparky-AI Native Antigravity (`agy acp`) Runtime & `n8n` Retirement (`sparky-agy-native-runtime`)"
Cohesion: 0.11
Nodes (22): 1. Executive Summary & Core Architectural Decision, 2. Empirical Ground Truth Verified on Host (2026-11-20), 3. Target Architecture Topology, 4. Core Component Design & Invariants, 5. Phased Rollout Plan (Strangler Fig), 6. Bounded Complex Probes Required at Session 2 Bootstrap, A. `sparky-agy` Warm Container & ACP Gateway, B. Direct Family Privacy & Bidirectional Stream Bridge (+14 more)

### Community 81 - "tool-policy.js"
Cohesion: 0.23
Nodes (11): collectToolArgObjects(), FAMILY_TOOLS, GEMINI_UNTRUSTED_TOOLS, hasDisallowedGeminiMediaFields(), isToolAllowedForProfile(), parseCanonicalToolName(), parseSingleArgValue(), PROFILE_TOOL_SETS (+3 more)

### Community 82 - "createMockAcpFaultDriver"
Cohesion: 0.14
Nodes (7): createMockAcpFaultDriver(), close(), createFakeAcpRpcTransport(), makeHandler(), start(), http, readBody()

### Community 83 - "vertex-fallback.test.js"
Cohesion: 0.16
Nodes (24): {
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
}, assert, fs, path, test, adaptGenerationContainer(), adaptVertexPayloadForModel(), ALLOWED_VERTEX_GENERATIVE_MODELS (+16 more)

### Community 84 - "triage-helpers.js"
Cohesion: 0.15
Nodes (17): RFC-2822, buildTodayIsraelRange(), assert, test, triageHelpers, computeDefaultTriageTodayIso(), DTF_HUMAN, DTF_ISRAEL_DATE (+9 more)

### Community 85 - "test_workspace_mutations.js"
Cohesion: 0.11
Nodes (18): APPEND_WF_PATH, cleanupRegistry, CREATE_DOC_WF_PATH, CREATE_SHEET_WF_PATH, CREATE_SLIDES_WF_PATH, { execSync, execFileSync }, EXPECTED_HEADERS, formatOutput() (+10 more)

### Community 86 - "callVertexWithCascade"
Cohesion: 0.12
Nodes (26): readStreamUtf8(), analyzeImageBuffer(), callGeminiJson(), callGoogleRoutesApi(), callOsrmFallback(), callVertexApiWithRetry(), callVertexFastJson(), runModelAttempt() (+18 more)

### Community 88 - "host-adapters.js"
Cohesion: 0.13
Nodes (18): BROWSERLESS_REJECT_PATTERNS, DEFAULT_ALLOWED_PUBLIC_PORTS, dns, { execFile, execSync }, fs, http, https, isPrivateOrLocalIp() (+10 more)

### Community 89 - "createFamilyConciergeStore"
Cohesion: 0.38
Nodes (14): createFamilyConciergeStore(), completeRelayFromAgent(), flushMessagesForTal(), getCachedSchedule(), loadOpenRelayLoops(), manageMessageForTal(), manageMessageForTalUnlocked(), recordChatHistory() (+6 more)

### Community 90 - "runtime-tools.js"
Cohesion: 0.15
Nodes (12): RUNTIME_AND_REMOTE_TOOLS, RUNTIME_ONLY_NAMES, ALLOWED_INGEST_SOURCES, assertNoGeminiMediaPlaceholder(), { getTurnContext, postTurnEgress }, { handleManageSparkyPlugin }, handleRuntimeToolCall(), INTERACTIVE_FORWARD_KEYS (+4 more)

### Community 92 - "sqlStr"
Cohesion: 0.14
Nodes (32): createFamilyOutboxStore(), ackBatch(), claimDueBatches(), deferBatch(), ensureSchema(), inspectBatchState(), loadQueuedBatch(), mergeFlushingIntoQueued() (+24 more)

### Community 93 - "acp-gateway-and-pool.test.js"
Cohesion: 0.20
Nodes (9): assert, { createAcpGatewayServer }, { createAcpSessionPool }, { createStdioAcpRpcClient }, fs, os, path, { resolveProfileForTurn, collectToolArgObjects } (+1 more)

### Community 94 - "Sparky-Plex: Autonomous Executive Assistant & Infrastructure"
Cohesion: 0.29
Nodes (6): Automated Backup, 🔄 Automated Backup & Disaster Recovery, Full Disaster Recovery, 📁 Repository Structure, 🔒 Security & Privacy Notice, Sparky-Plex: Autonomous Executive Assistant & Infrastructure

### Community 95 - "run"
Cohesion: 0.17
Nodes (10): assert, entries, makeHttpErrorResponse(), makePlainJsonResponse(), makeSseStreamResponse(), makeWrappedAbortGaxiosError(), run(), bodyGen() (+2 more)

### Community 96 - "run"
Cohesion: 0.17
Nodes (10): assert, entries, makeHttpErrorResponse(), makePlainJsonResponse(), makeSseStreamResponse(), makeWrappedAbortGaxiosError(), run(), bodyGen() (+2 more)

### Community 97 - "quiet-hours.test.js"
Cohesion: 0.23
Nodes (8): BYPASS_SOURCES, computeQuietHoursVerdict(), getLocalHour(), hourFormatter, isQuietWindow(), assert, {
  QUIET_START_HOUR,
  QUIET_END_HOUR,
  TZ,
  BYPASS_SOURCES,
  getLocalHour,
  isQuietWindow,
  computeQuietHoursVerdict,
}, test

### Community 98 - "event-ingest.test.js"
Cohesion: 0.09
Nodes (16): createAcpHookDriver(), close(), execHook(), runPreToolHook(), runStopHook(), ACP_ROUTES_PATH, assert, { createAcpHookDriver, resolveTalPreToolHookPath } (+8 more)

### Community 99 - "workspace-mcp.test.js"
Cohesion: 0.12
Nodes (14): ALL_22_TOOLS, assert, { createGoogleRestMockDriver }, { createMcpStdioDriver }, EXPECTED_CALENDAR_TOOLS, EXPECTED_DRIVE_WORKSPACE_TOOLS, EXPECTED_GMAIL_TOOLS, EXPECTED_MUTATING_TOOLS (+6 more)

### Community 100 - "sparky-agy/package.json"
Cohesion: 0.20
Nodes (9): description, engines, node, name, private, scripts, start, test (+1 more)

### Community 101 - "createStdioAcpRpcClient"
Cohesion: 0.50
Nodes (9): createStdioAcpRpcClient(), cleanup(), close(), ensureInitialized(), ensureStarted(), rawRequest(), request(), safeWriteLine() (+1 more)

### Community 102 - "handleWhatsappTtsRoute"
Cohesion: 0.21
Nodes (13): createAcpRoutesHandler(), handleAcpOrSearchRoute(), requireBridgeToken(), normalizeReactionEmoji(), handleReactionExecuteRoute(), handleWhatsappTtsRoute(), parsePersonaFromNote(), parseStrictJsonBody() (+5 more)

### Community 103 - "db.js"
Cohesion: 0.50
Nodes (4): { execFile }, formatPgCell(), formatPgResultAsPsql(), RAW_STRING_OIDS

### Community 104 - "normalizeIsraeliPhone"
Cohesion: 0.27
Nodes (12): createFamilyRoutesHandler(), handleFamilyRoute(), handleJsonRoute(), requireToken(), sendFamilyError(), writeStoreResult(), { escXml }, { getJerusalemOffsetString } (+4 more)

### Community 106 - "Commitments & Scheduling Discipline"
Cohesion: 0.40
Nodes (4): Commitments & Scheduling Discipline, Dual-Anchor Rule, Hebrew Colloquial Intent, Symmetric Closure (No Zombie Blocks)

### Community 107 - "Executive Onboarding Protocol"
Cohesion: 0.50
Nodes (3): Executive Onboarding Protocol, When Onboarding Is Already Completed (`onboarding="completed"`), When Onboarding Is Pending (`onboarding="pending"` / `"in_progress"`)

### Community 108 - "Family Relay Privacy & Delivery Protocol"
Cohesion: 0.50
Nodes (3): Family Relay Privacy & Delivery Protocol, Inbound Family Updates, Outbound Relay to Gal

### Community 109 - "computeDefaultShipmentFollowUp"
Cohesion: 0.67
Nodes (4): computeDefaultShipmentFollowUp(), getJerusalemDateTimeParts(), computeSnoozeTarget(), resolveJerusalemWallClockMs()

### Community 112 - "google-oauth-client.test.js"
Cohesion: 0.12
Nodes (12): assert, CONFIG_PATH, { createGoogleRestMockDriver }, crypto, DOC_ROUTES_PATH, fs, http, OAUTH_CLIENT_PATH (+4 more)

### Community 114 - "makeWorld"
Cohesion: 0.60
Nodes (6): makeWorld(), parseItemsArray(), parseJsonbParam(), queryPostgresJson(), queryPostgresWithStdin(), test

### Community 115 - "acp-routes.js"
Cohesion: 0.22
Nodes (7): dns, { handleWebReadRoute }, renderPage(), extractReadableDom(), fetchViaJina(), handleWebReadRoute(), isWafOrErrorPage()

### Community 116 - "whatsapp-egress.js"
Cohesion: 0.20
Nodes (13): applyBypassTestGuard(), buildInteractiveOrTextPayload(), buildReplyButtonsPayload(), computeFooterCappedText(), copyForwardedKeys(), enforceTurnEgressRecipient(), FORWARDED_DISPATCH_KEYS, normalizeDirectArgs() (+5 more)

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

### Community 121 - "migrate-loop-keys.js"
Cohesion: 0.25
Nodes (9): encodeCanonicalLoopId(), generateDeterministicLoopId(), { execFile }, HISTORICAL_CLOSE_IDS, { INVOICE_RE, generateDeterministicLoopId }, loadAllRows(), queryPostgresWithStdin(), runMigration() (+1 more)

### Community 122 - "runPsql"
Cohesion: 0.20
Nodes (11): assertBalancedSentinelXml(), assertHostileEscaped(), cleanupReactionDeckTestRows(), cleanupTestSentinelState(), execPsqlStrict(), restoreLivePendingAndCleanTests(), runPsql(), saveAndSupersedeLivePending() (+3 more)

### Community 123 - "ssrf-perimeter.test.js"
Cohesion: 0.18
Nodes (10): ACP_ROUTES_PATH, assert, dsl, fs, HOST_ADAPTERS_PATH, http, os, path (+2 more)

### Community 124 - "isTestPayload"
Cohesion: 0.40
Nodes (11): createWhatsAppEgress(), postGraphJson(), sendWhatsAppDirect(), sendWhatsAppMediaDirect(), sendWhatsAppReaction(), sendWhatsAppReengageTemplate(), sendWhatsAppTemplate(), timeoutSignal() (+3 more)

### Community 125 - "stdio-rpc-client.js"
Cohesion: 0.22
Nodes (6): readline, { redactSecretsInError }, { spawn }, fs, readline, { spawn }

### Community 126 - "createGoogleOAuthClient"
Cohesion: 0.31
Nodes (8): createGoogleOAuthClient(), getAccessToken(), getOAuthMeta(), loadOAuthCredentials(), refreshToken(), defaultOAuthFilePath(), fs, redactOAuthSecrets()

### Community 127 - "turn-ctx-client.js"
Cohesion: 0.38
Nodes (9): getBridgeToken(), { getBridgeToken }, getTurnContext(), http, https, nodeHttpFetch(), postTurnEgress(), resolveTurnCtxEndpoint() (+1 more)

### Community 128 - "createGoogleOAuthClient"
Cohesion: 0.31
Nodes (8): createGoogleOAuthClient(), getAccessToken(), getOAuthMeta(), loadOAuthCredentials(), refreshToken(), defaultOAuthFilePath(), fs, redactOAuthSecrets()

### Community 129 - "workspace-mcp/package.json"
Cohesion: 0.20
Nodes (9): description, engines, node, main, name, private, scripts, test (+1 more)

### Community 130 - "ref_child_process"
Cohesion: 0.28
Nodes (7): assert, { createLoopStore }, { execFile }, queryPostgresJson(), queryPostgresWithStdin(), store, test

### Community 131 - "handoff-store.js"
Cohesion: 0.25
Nodes (7): { containsSecretOrPassword }, crypto, escXml(), formatHandoffsXml(), isTestHandoff(), VALID_DIRECTIONS, VALID_STATUSES

### Community 132 - "event-ingest.js"
Cohesion: 0.31
Nodes (7): ALLOWED_ACTOR_SOURCE_SET, ALLOWED_ACTOR_SOURCES, createEventIngestHandler(), ingestEvent(), DB_ERR_SENTINEL, sanitizeUntrustedField(), stripPromptInjectionMarkers()

### Community 133 - "createHandoffStore"
Cohesion: 0.54
Nodes (8): createHandoffStore(), claimHandoffs(), completeHandoff(), createHandoff(), ensureSchema(), getLatestHandoff(), listHandoffs(), sqlEscape()

### Community 134 - "loop-keys.fixture.test.js"
Cohesion: 0.25
Nodes (6): assert, FIXTURE_PATH, fs, { generateDeterministicLoopId }, path, test

### Community 135 - "tts-adapter.js"
Cohesion: 0.36
Nodes (7): normalizePersonaModeKey(), PERSONA_VOICE_MAP, { redactSecretsInError }, requestGoogleTtsAudio(), resolveTtsVoice(), synthesizeSpeechGoogleTts(), truncateUtf8TextForTts()

### Community 136 - "containsSecretOrPassword"
Cohesion: 0.43
Nodes (6): containsSecretOrPassword(), {
  detectCorrectionSignal,
  containsSecretOrPassword,
  stripChatWrapper,
}, { execFile }, queryPostgresJson(), queryPostgresWithStdin(), runProbe()

### Community 138 - "family-mcp/package.json"
Cohesion: 0.33
Nodes (5): description, main, name, private, version

### Community 139 - "createMetaTokenReader"
Cohesion: 0.60
Nodes (6): createMetaTokenReader(), getMetaAppSecret(), getMetaToken(), getMetaVerifyToken(), parseEnvKey(), refreshIfNeeded()

### Community 140 - "1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4)"
Cohesion: 0.40
Nodes (5): 1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4), DEF-01: Global Attention Budget & Quiet Hours Hold Queue (`23:00–07:00`), DEF-02: Nudge-Effectiveness Telemetry & Sentinel Self-Tuning, DEF-03: Sunday Weekly Review & Overdue Loop Escalation Ladder, DEF-12: `agy-daemon` Failed Mission Re-Surfacing & Retry Digest

### Community 141 - "createAnalyzeDocumentHandler"
Cohesion: 0.60
Nodes (4): createAnalyzeDocumentHandler(), acquireSlot(), handleAnalyzeDocumentRoute(), releaseSlot()

## Knowledge Gaps
- **21 isolated node(s):** `PATH`, `PATH`, `HOME`, `REGISTRY_AUTH_FILE`, `PATH` (+16 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 1006 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **28 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `createDb()` connect `createDb` to `probe-db-parity.js`, `server.js`, `phase2-remediation.test.js`, `db.js`?**
  _High betweenness centrality (0.042) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `redactSecretsInError()` (e.g. with `handleAcpOrSearchRoute()` and `incident-store.js`) actually correct?**
  _`redactSecretsInError()` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `PATH`, `PATH`, `HOME` to the rest of the system?**
  _21 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `server.js` be split into smaller, more focused modules?**
  _Cohesion score 0.02499247214694369 - nodes in this community are weakly interconnected._
- **Why does `pg` connect `createDb` to `vertex-search-bridge/package.json`?**
  _High betweenness centrality (0.022) - this node is a cross-community bridge._
- **Should `reaction-commands.test.js` be split into smaller, more focused modules?**
  _Cohesion score 0.09116809116809117 - nodes in this community are weakly interconnected._
- **Should `model-router.js` be split into smaller, more focused modules?**
  _Cohesion score 0.07142857142857142 - nodes in this community are weakly interconnected._