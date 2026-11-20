# Graph Report - sparky-backup  (2026-11-20)

## Corpus Check
- 112 files · ~253,569 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 12 file(s) not represented in the graph (top: (none) 5, .service 5, .example 1)

## Summary
- 1523 nodes · 3136 edges · 96 communities (73 shown, 23 thin omitted)
- Extraction: 89% EXTRACTED · 11% INFERRED · 0% AMBIGUOUS · INFERRED: 354 edges (avg confidence: 0.86)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `38251b8e`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- server.js
- reaction-commands.test.js
- ref_fs
- model-router.js
- test_workspace_mutations.js
- server
- Requirements Anchor: Sparky-AI Nightly Dreaming Knowledge Graph (`sparky-nightly-knowledge-graph`)
- Semantic Vector Memory & Cortex Sleep Consolidation Architecture
- createReactionActivityController
- test_graphify_integration.py
- 1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4)
- correction-learner.js
- Sentinel Actor Model & Conversational Handshake Architecture
- The Four Cynefin Domains in Sparky
- ref_fs
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
- reactionCommandService
- update.sh
- memory-hygiene.js
- ref_node_fs
- patch-gemini4-langchain.sh
- install-apps.sh
- restore.sh
- test_agent_telemetry.sh
- nudge-telemetry.js
- incident-store.js
- heartbeat-store.js
- db.js
- host-adapters.test.js
- n8n-sparky/test-n8n-patches.js
- lifecycle.test.js
- config.test.js
- phase2c-ops.test.js
- family-relay.test.js
- family-relay.js
- TestGoldenDatasetPresence
- index.js
- buildSessionPreamble
- patch-n8n-memory-orphans.sh
- TestWorkflowTelemetry
- reactionCommandService
- publish-graph.sh
- config.js
- TestEvaluationHarnessWorkflow
- TaskDaemon
- family-concierge-store.test.js
- family-concierge-store.js
- TestEvaluationSafetyGuard
- vertex-search-bridge/package.json
- ref_node_test
- test_agent_evaluation.py
- Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`)
- loop-keys.js
- probe-db-parity.js
- run-agent-eval.sh
- TestEopSkillAndBackupScriptContract
- sync-services-to-repo.sh
- n8n-stack/scripts/deploy-bridge.sh
- eval-history.md
- isTestPayload
- ref_path
- Requirements Anchor: `[Sparky-AI]` Event-Driven Email Handoff to Gemini App
- n8n-sparky/patch-gemini4-langchain.sh
- n8n-sparky/patch-n8n-memory-orphans.sh
- TestDynamicModelRoutingCallers
- scripts/patch-retry-backoff.sh
- n8n-sparky/patch-retry-backoff.sh
- Requirements Anchor: Sparky-AI Dynamic Main Agent Model & Effort Routing
- TestAntigravitySkillAndRulesRegistration
- loop-store.integration.test.js
- createLoopStore
- redactSecretsInError
- vertex-fallback.test.js
- handoff-store.js
- test_workspace_mutations.js
- callVertexWithCascade
- triage-helpers.js
- TestReactionCommandDeckWorkflows
- createFamilyConciergeStore
- loop-store.js
- TestFamilyConciergeWorkflows
- sqlStr
- migrate-loop-keys.js
- probe-incident-signatures.js
- incident-store.test.js

## God Nodes (most connected - your core abstractions)
1. `server` - 124 edges
2. `redactSecretsInError()` - 47 edges
3. `sqlStr()` - 29 edges
4. `queryPostgresJson()` - 24 edges
5. `buildSessionPreamble()` - 23 edges
6. `TaskDaemon` - 21 edges
7. `createModelRouter()` - 20 edges
8. `normalizeIsraeliPhone()` - 19 edges
9. `createFamilyConciergeStore()` - 18 edges
10. `sqlJsonb()` - 18 edges

## Surprising Connections (you probably didn't know these)
- `1. User Intent & Selected Architecture` --references--> `buildSessionPreamble()`  [INFERRED]
  docs/brainstorms/sparky-dynamic-model-routing-requirements.md → services/vertex-search-bridge/server.js
- `A2. Full-Ecosystem Scope (Locked Across All 8 Branches)` --references--> `buildAgyTaskPayload()`  [INFERRED]
  docs/brainstorms/sparky-gemini4-neon-roster-requirements.md → services/vertex-search-bridge/agy-mission-client.js
- `2. Verified Architectural Invariants & Test Alignment` --references--> `compactSessionChatHistory()`  [INFERRED]
  docs/brainstorms/sparky-dynamic-model-routing-requirements.md → services/vertex-search-bridge/config.js
- `🛠️ Microservice Bridge (Port 5055)` --references--> `formatFamilyOutboxBatch()`  [INFERRED]
  README.md → services/vertex-search-bridge/family-morning.js
- `🛠️ Microservice Bridge (Port 5055)` --references--> `reset()`  [INFERRED]
  README.md → services/vertex-search-bridge/model-router.js

## Import Cycles
- None detected.

## Communities (96 total, 23 thin omitted)

### Community 0 - "server.js"
Cohesion: 0.03
Nodes (68): {
  ALLOWED_WORKSPACES,
  ALLOWED_AGY_MODELS,
  validateOptionalAgyModel,
  buildAgyTaskPayload,
  dispatchAgyMissionToDrive,
}, atomicWriteJson(), BRIDGE_API_TOKEN, BRIDGE_STARTED_AT, circuitBreakers, {
  classifyDecisionChoice,
  inferDecisionSource,
  extractSenderKey,
  computeSenderAdjustment,
  formatTriageFeedbackXml,
  createNudgeTelemetryStore,
}, {
  COGNITIVE_TIERS,
  CALLER_DEFAULT_ROUTES,
  HEAVY_MODELS,
  ALLOWED_ROUTER_MODELS,
  classifyStage1FastPath,
  createModelRouter,
}, {
  computeRecencyBoost,
  rankMemoriesWithDecay,
  hasFactMutationTokens,
  mergeContextNotes,
  projectContextNotes,
  searchContextNotesLexical,
  createMemoryHygieneStore,
} (+60 more)

### Community 1 - "reaction-commands.test.js"
Cohesion: 0.08
Nodes (13): AgyDriver, assert, BridgeCommandDriver, { EventEmitter }, fs, loadCorrectionLearner(), loadReactionCommands(), os (+5 more)

### Community 2 - "ref_fs"
Cohesion: 0.21
Nodes (13): bridgeRequest(), fs, getBridgeToken(), { bridgeRequest }, fs, isSafeHeartbeatPath(), path, readStdin() (+5 more)

### Community 3 - "model-router.js"
Cohesion: 0.07
Nodes (54): 1. Locked Architecture & 4-Model Periodic Roster (Bootstrap + `/grill-me` Convergence), 2. Live Empirical Probe Ground Truth (`spark-509400` & `agy` CLI, 2026-11-19), 3. Bounded Complex Probes Gating Rollout, 4. Post-Pre-Flight Run #1 `/grill-me` Convergence (Branches 1–5 Locked), A1. Strict Monotonic 6-Tier Periodic Matrix (`COGNITIVE_TIERS` in `/root/vertex-search-bridge/model-router.js`), A2. Full-Ecosystem Scope (Locked Across All 8 Branches), A3. Generalized Heavy-Model Circuit Breaker & Guardrails, Requirements Anchor: Sparky-AI Gemini 4 Neon 4-Model Periodic Roster (+46 more)

### Community 4 - "test_workspace_mutations.js"
Cohesion: 0.07
Nodes (35): assert, assertBalancedSentinelXml(), assertHostileEscaped(), callBridge(), checkActiveDecision(), checkCommute(), checkDue(), checkReminders() (+27 more)

### Community 5 - "server"
Cohesion: 0.12
Nodes (26): evaluateCommuteWindow(), filterAndSortEvents(), formatCommuteBriefingLine(), formatOriginLabel(), hasVideo(), isPhysical(), isVirtualLink(), nextPriorPhysical() (+18 more)

### Community 6 - "Requirements Anchor: Sparky-AI Nightly Dreaming Knowledge Graph (`sparky-nightly-knowledge-graph`)"
Cohesion: 0.50
Nodes (3): 1. User Intent & Selected Architecture (1 + 3 Hybrid), 2. Core Invariants & Boundaries, Requirements Anchor: Sparky-AI Nightly Dreaming Knowledge Graph (`sparky-nightly-knowledge-graph`)

### Community 7 - "Semantic Vector Memory & Cortex Sleep Consolidation Architecture"
Cohesion: 0.11
Nodes (18): 1. Architectural Blueprint & Cognitive Model, 2. Infrastructure & Storage (`pgvector`), 3. Multilingual Embedding Pipeline, 4. Bridge Microservice Endpoints ([`server.js`](file:///root/vertex-search-bridge/server.js)), 5. Main Agent Integration (`search_memory` FunctionCall), 6. Nightly Cortex Sleep Consolidation (`POST /cortex/sleep-cycle`), 7.1 PostgreSQL Relational + Vector Graph Schema, 7.2 Nightly Single-Pass Extraction & Backfill (+10 more)

### Community 8 - "createReactionActivityController"
Cohesion: 0.18
Nodes (22): cloneConfig(), createReactionActivityController(), completeTurn(), dispatchEmojiNow(), evictIfFull(), getConfig(), getOrCreateState(), getStatus() (+14 more)

### Community 9 - "test_graphify_integration.py"
Cohesion: 0.14
Nodes (5): _extract_source_files(), TestCodebaseInclusionInGraph, TestIncrementalUpdateIdempotency, TestPersonalMemoryGraphIsolation, TestStrictExclusionBoundary

### Community 10 - "1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4)"
Cohesion: 0.05
Nodes (41): 1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4), 2. Quality Gates, Observability & Disaster Recovery (Epic E3), 3. Platform Architecture & Refactoring (Epic E5), DEF-01: Global Attention Budget & Quiet Hours Hold Queue (`23:00–07:00`), DEF-02: Nudge-Effectiveness Telemetry & Sentinel Self-Tuning, DEF-03: Sunday Weekly Review & Overdue Loop Escalation Ladder, DEF-06: Auto-Incident Knowledge Base (`knowledge-base.json`) Draft Capture, DEF-07: Golden Evaluation Dataset Expansion (`3/45` → Core Tools) & Change Gate (+33 more)

### Community 11 - "correction-learner.js"
Cohesion: 0.20
Nodes (17): DEF-04: Real-Time In-Turn Correction Learning (`"No, I meant..."`), containsSecretOrPassword(), createCorrectionLearner(), extractAndSaveCorrection(), detectCorrectionSignal(), redactAllSecrets(), SECRET_PATTERNS, stripChatWrapper() (+9 more)

### Community 12 - "Sentinel Actor Model & Conversational Handshake Architecture"
Cohesion: 0.20
Nodes (9): 1. Executive Summary, 2. Dual-Channel XML Sensory Pipeline, 3. Active Conversational Handshake & Latency Masking, 4. Active Workflow Catalog (11 Total), 5. Central Egress Hub (`/whatsapp/dispatch`), Sentinel Actor Model & Conversational Handshake Architecture, The Problem, The Solution (+1 more)

### Community 13 - "The Four Cynefin Domains in Sparky"
Cohesion: 0.22
Nodes (8): 1. Clear / Simple Domain (Known Knowns), 2. Complicated Domain (Known Unknowns), 3. Complex Domain (Unknown Unknowns), 4. Chaotic Domain (Unknowables / Crises), 5. Aporia / Confusion, Architectural Overview, Cynefin + OODA Loop Cognitive Framework, The Four Cynefin Domains in Sparky

### Community 14 - "ref_fs"
Cohesion: 0.22
Nodes (6): assert, FIXTURE_PATH, fs, { generateDeterministicLoopId }, path, test

### Community 15 - "reaction-commands.js"
Cohesion: 0.07
Nodes (51): ALLOWED_AGY_MODEL_SET, ALLOWED_AGY_MODELS, ALLOWED_WORKSPACES, buildAgyTaskPayload(), buildFencedMissionPrompt(), dispatchAgyMissionToDrive(), fetchAgyAccessToken(), fs (+43 more)

### Community 16 - "kg-store.js"
Cohesion: 0.10
Nodes (48): atomicWriteFile(), bareTableName(), buildAsciiVaultSlug(), buildCanonicalEntityId(), buildDeterministicEdgeId(), canonicalDescriptorToString(), createKgStore(), ensureKgTables() (+40 more)

### Community 17 - "sparky-mcp/package.json"
Cohesion: 0.25
Nodes (7): description, main, name, private, scripts, test, version

### Community 18 - "http-server.js"
Cohesion: 0.11
Nodes (23): RFC-8414, RFC-9728, ALLOWED_REDIRECT_HOSTS, { bridgeRequest }, createMcpHttpServer(), crypto, DEFAULT_PUBLIC_ORIGIN, escHtml() (+15 more)

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
Cohesion: 0.47
Nodes (5): encrypt_file(), HOME, PATH, run_encrypted_secrets_stage(), backup.sh script

### Community 24 - "render-local-kg-html.sh"
Cohesion: 0.50
Nodes (3): HOME, PATH, render-local-kg-html.sh script

### Community 25 - "mcp.test.js"
Cohesion: 0.15
Nodes (10): assert, { createMcpHttpServer, processJsonRpcMessage }, crypto, fs, RFC-7591, mcpIndex, os, path (+2 more)

### Community 26 - "scripts/test-n8n-patches.js"
Cohesion: 0.08
Nodes (27): assert, { cleanupOrphanedMessages }, { ensureParams, failedAttemptHandler }, entries, failedHandlerPath, fs, geminiCjsPath, geminiMessages (+19 more)

### Community 27 - "reactionCommandService"
Cohesion: 0.19
Nodes (17): readStreamUtf8(), callGoogleRoutesApi(), callOsrmFallback(), callVertexApiWithRetry(), computeCommute(), fetchMetaMedia(), getAccessToken(), getMetaToken (+9 more)

### Community 29 - "memory-hygiene.js"
Cohesion: 0.13
Nodes (29): DEF-05: Semantic Memory Contradiction Detection & Temporal Decay, computeRecencyBoost(), createMemoryHygieneStore(), findCandidateNeighbors(), ingestMemoryWithHygiene(), reconcileExistingMemories(), EPISODIC_TYPES, extractSearchTokens() (+21 more)

### Community 30 - "ref_node_fs"
Cohesion: 0.13
Nodes (10): assert, DB_PATH, fs, path, test, assert, EGRESS_PATH, fs (+2 more)

### Community 33 - "restore.sh"
Cohesion: 0.47
Nodes (5): HOME, PATH, restore.sh script, sync_published_versions_sql(), verify_and_extract_secrets()

### Community 35 - "nudge-telemetry.js"
Cohesion: 0.16
Nodes (21): classifyDecisionChoice(), computeSenderAdjustment(), createNudgeTelemetryStore(), getEffectivenessReport(), getSenderFeedback(), extractSenderKey(), formatTriageFeedbackXml(), inferDecisionSource() (+13 more)

### Community 36 - "incident-store.js"
Cohesion: 0.36
Nodes (8): computeSignature(), createIncidentStore(), draftLessonsFromCandidates(), recordCandidate(), crypto, normalizeErrorKey(), redactAndNormalizeError(), sqlStr()

### Community 37 - "heartbeat-store.js"
Cohesion: 0.09
Nodes (24): extractInteractiveOptions(), FAMILY_NON_DECISION_SOURCES, INTERACTIVE_SENTINEL_SOURCES, NON_DECISION_SOURCES, SOURCE_ALIAS_GROUPS, createHeartbeatStore(), flushSentinel(), listHeartbeats() (+16 more)

### Community 38 - "db.js"
Cohesion: 0.21
Nodes (11): pg, createDb(), getOrInitPgPool(), queryPostgresJson(), queryPostgresScript(), queryPostgresWithStdin(), { execFile }, formatPgCell() (+3 more)

### Community 39 - "host-adapters.test.js"
Cohesion: 0.17
Nodes (7): assert, fs, HOST_ADAPTERS_PATH, http, net, path, test

### Community 40 - "n8n-sparky/test-n8n-patches.js"
Cohesion: 0.08
Nodes (27): assert, { cleanupOrphanedMessages }, { ensureParams, failedAttemptHandler }, entries, failedHandlerPath, fs, geminiCjsPath, geminiMessages (+19 more)

### Community 41 - "lifecycle.test.js"
Cohesion: 0.17
Nodes (9): assert, CONFIG_PATH, { execFileSync }, fs, os, path, SERVER_PATH, test (+1 more)

### Community 42 - "config.test.js"
Cohesion: 0.22
Nodes (6): assert, CONFIG_PATH, fs, os, path, test

### Community 43 - "phase2c-ops.test.js"
Cohesion: 0.25
Nodes (7): assert, { execFileSync }, fs, path, PATHS, readOrSkip(), test

### Community 44 - "family-relay.test.js"
Cohesion: 0.14
Nodes (17): assert, BACKUP_FILE, { buildCanonicalLoopKey, generateDeterministicLoopId }, clone(), createFakeWorld(), mergeJsonbLiteral(), queryPostgresJson(), queryPostgresWithStdin() (+9 more)

### Community 45 - "family-relay.js"
Cohesion: 0.19
Nodes (23): classifyFamilyInboundText(), createFamilyRelayService(), configureFamilyMember(), handleFamilyInbound(), loadCtx(), loadFamilyLoops(), processFamilyInbound(), recordChatHistory() (+15 more)

### Community 47 - "index.js"
Cohesion: 0.19
Nodes (12): processJsonRpcMessage(), { ALLOWED_AGY_MODELS, validateOptionalAgyModel }, { bridgeRequest }, dispatchAgyMissionToDrive(), fs, handleToolCall(), readHeartbeatMeta(), readline (+4 more)

### Community 48 - "buildSessionPreamble"
Cohesion: 0.10
Nodes (33): getDecisionSourceAliases(), classifyLoopsByDue(), buildSessionPreamble(), checkAndDispatchWindowKeepalive(), createDecision(), familyRoutes, getSentinelEvent(), getSystemAudit() (+25 more)

### Community 51 - "reactionCommandService"
Cohesion: 0.28
Nodes (18): familyConciergeStore, familyRelay, getWindowState(), invalidateWindowStateCache(), logActivityEvent(), postMetaMediaOnce(), queryPostgresStrict(), queryPostgresWithStdin() (+10 more)

### Community 52 - "publish-graph.sh"
Cohesion: 0.50
Nodes (3): HOME, PATH, publish-graph.sh script

### Community 53 - "config.js"
Cohesion: 0.14
Nodes (8): compactSessionChatHistory(), compactToolObservationContent(), createMetaTokenReader(), crypto, defaultConfig, fs, normalizeHistoryRow(), path

### Community 55 - "TaskDaemon"
Cohesion: 0.06
Nodes (7): extract_stream_json_result(), read_heartbeat_meta(), resolve_task_model(), resolve_timeouts(), sd_notify(), TaskDaemon, TestDaemon

### Community 56 - "family-concierge-store.test.js"
Cohesion: 0.11
Nodes (13): { ADMIN_PHONE, sanitizeFamilyText }, assert, { getLocalHourMinuteIl }, makeWorld(), parseItemsArray(), parseJsonbParam(), queryPostgresJson(), queryPostgresWithStdin() (+5 more)

### Community 57 - "family-concierge-store.js"
Cohesion: 0.12
Nodes (27): {
  ADMIN_PHONE,
  normalizeIsraeliPhone,
  resolveAuthorizedUserByPhone,
  sanitizeFamilyText,
}, { createFamilyMorningService }, { createFamilyOutboxStore }, {
  escXml,
  formatIlDate,
  stripCalendarEventForFamily,
  projectTalSchedule,
  buildFamilyContextXml,
  computeKeepaliveDecision,
  computeFamilyKeepaliveDecision,
  applyDispatchAckButtonPolicy,
}, { formatIsoTimeIl }, { redactSecretsInError }, { sqlStr, sqlJsonb, sqlJsonbArray, sqlTimestamptz }, evaluateDueBatch() (+19 more)

### Community 59 - "vertex-search-bridge/package.json"
Cohesion: 0.14
Nodes (13): dependencies, pg, description, engines, node, main, name, private (+5 more)

### Community 60 - "ref_node_test"
Cohesion: 0.12
Nodes (12): assert, { createHandoffStore, formatHandoffsXml }, { describe, it }, assert, { createLoopStore }, test, assert, commuteDsl (+4 more)

### Community 61 - "test_agent_evaluation.py"
Cohesion: 0.15
Nodes (4): _eval_n8n_expr(), TestSessionIsolation, TestDeterministicCLIGraphQuery, TestGraphifyCLIBinary

### Community 62 - "Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`)"
Cohesion: 0.33
Nodes (5): Emergency Sub-Minute Rollback to Host `systemd` (`vertex-search.service`), Overview, Returning from Host `systemd` to Container (`vertex-bridge`), Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`), Standard Deployment & Digest Rollback (`deploy-bridge.sh`)

### Community 63 - "loop-keys.js"
Cohesion: 0.18
Nodes (19): buildCanonicalLoopKey(), crypto, effectiveDue(), encodeCanonicalLoopId(), extractLoopEntityKey(), extractShipmentIdentifiers(), formatDueBucket(), formatIsraelDate() (+11 more)

### Community 64 - "probe-db-parity.js"
Cohesion: 0.29
Nodes (6): resolveConfig(), assert, config, { createDb }, main(), QUERIES

### Community 65 - "run-agent-eval.sh"
Cohesion: 0.50
Nodes (3): HOME, PATH, run-agent-eval.sh script

### Community 70 - "isTestPayload"
Cohesion: 0.16
Nodes (17): BYPASS_SOURCES, computeQuietHoursVerdict(), getLocalHour(), hourFormatter, isQuietWindow(), assert, {
  QUIET_START_HOUR,
  QUIET_END_HOUR,
  TZ,
  BYPASS_SOURCES,
  getLocalHour,
  isQuietWindow,
  computeQuietHoursVerdict,
}, test (+9 more)

### Community 71 - "ref_path"
Cohesion: 0.25
Nodes (9): { execFileSync }, fs, main(), migrateJsCode(), migrateNodes(), migrateUrlParam(), path, runPsql() (+1 more)

### Community 78 - "Requirements Anchor: Sparky-AI Dynamic Main Agent Model & Effort Routing"
Cohesion: 0.50
Nodes (3): 1. User Intent & Selected Architecture, 2. Verified Architectural Invariants & Test Alignment, Requirements Anchor: Sparky-AI Dynamic Main Agent Model & Effort Routing

### Community 80 - "loop-store.integration.test.js"
Cohesion: 0.32
Nodes (7): assert, { createLoopStore }, { execFile }, queryPostgresJson(), queryPostgresWithStdin(), store, test

### Community 81 - "createLoopStore"
Cohesion: 0.18
Nodes (20): classifyShipmentLifecycle(), createLoopStore(), completeOpenLoopById(), extractValidCrossEntityTokens(), getLoopById(), markLoopNotified(), rescheduleOpenLoopById(), resolveOpenRowSchedule() (+12 more)

### Community 82 - "redactSecretsInError"
Cohesion: 0.23
Nodes (16): createFamilyMorningService(), composeMorningGreeting(), formatFamilyOutboxBatch(), getMorningGreetingTargets(), loadCtx(), createFamilyRoutesHandler(), handleFamilyRoute(), handleJsonRoute() (+8 more)

### Community 83 - "vertex-fallback.test.js"
Cohesion: 0.12
Nodes (30): callVertexFastJson(), runModelAttempt(), sendOnce(), createCircuitBreaker(), getCircuitBreaker(), modelRouter, {
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
}, assert (+22 more)

### Community 84 - "handoff-store.js"
Cohesion: 0.21
Nodes (15): { containsSecretOrPassword }, createHandoffStore(), claimHandoffs(), completeHandoff(), createHandoff(), ensureSchema(), getLatestHandoff(), listHandoffs() (+7 more)

### Community 85 - "test_workspace_mutations.js"
Cohesion: 0.11
Nodes (18): APPEND_WF_PATH, cleanupRegistry, CREATE_DOC_WF_PATH, CREATE_SHEET_WF_PATH, CREATE_SLIDES_WF_PATH, { execSync, execFileSync }, EXPECTED_HEADERS, formatOutput() (+10 more)

### Community 86 - "callVertexWithCascade"
Cohesion: 0.20
Nodes (14): analyzeImageBuffer(), callGeminiJson(), callVertexWithCascade(), generateEmbedding(), insertSemanticMemory(), kgStore, memoryHygieneStore, notifyVertexCascadeExhaustion() (+6 more)

### Community 87 - "triage-helpers.js"
Cohesion: 0.18
Nodes (13): RFC-2822, findDuplicateFieldNote(), assert, test, triageHelpers, DTF_HUMAN, DTF_ISRAEL_DATE, isSparkyHandoffEcho() (+5 more)

### Community 89 - "createFamilyConciergeStore"
Cohesion: 0.35
Nodes (15): createFamilyConciergeStore(), completeRelayFromAgent(), flushMessagesForTal(), getCachedSchedule(), loadOpenRelayLoops(), manageMessageForTal(), manageMessageForTalUnlocked(), recordChatHistory() (+7 more)

### Community 90 - "loop-store.js"
Cohesion: 0.17
Nodes (8): { ADMIN_PHONE, normalizeIsraeliPhone, sanitizeFamilyText }, { redactSecretsInError }, { sqlStr }, { TZ, escXml, formatIlDate }, {
  ACTIONABLE_STATUS_RE,
  generateDeterministicLoopId,
  stripBidi,
}, sanitizeSqlValue(), sqlJsonbArray(), stripNullCharsReplacer()

### Community 92 - "sqlStr"
Cohesion: 0.45
Nodes (12): createFamilyOutboxStore(), ackBatch(), claimDueBatches(), deferBatch(), ensureSchema(), inspectBatchState(), loadQueuedBatch(), mergeFlushingIntoQueued() (+4 more)

### Community 93 - "migrate-loop-keys.js"
Cohesion: 0.31
Nodes (7): { execFile }, HISTORICAL_CLOSE_IDS, { INVOICE_RE, generateDeterministicLoopId }, loadAllRows(), queryPostgresWithStdin(), runMigration(), { sqlStr, sqlJsonb }

### Community 94 - "probe-incident-signatures.js"
Cohesion: 0.43
Nodes (6): classifyRootCause(), { execFileSync }, main(), parseAlertText(), {
  redactSecretsInError,
  normalizeErrorKey,
  computeSignature,
}, runSqlJson()

### Community 95 - "incident-store.test.js"
Cohesion: 0.38
Nodes (6): assert, { execFile }, queryPostgresJson(), {
  redactSecretsInError,
  normalizeErrorKey,
  computeSignature,
  createIncidentStore,
}, runPsql(), test

## Knowledge Gaps
- **20 isolated node(s):** `PATH`, `PATH`, `HOME`, `REGISTRY_AUTH_FILE`, `PATH` (+15 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 637 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **23 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `createHostAdapters()` connect `1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4)` to `server.js`?**
  _High betweenness centrality (0.027) - this node is a cross-community bridge._
- **What connects `PATH`, `PATH`, `HOME` to the rest of the system?**
  _20 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `server.js` be split into smaller, more focused modules?**
  _Cohesion score 0.030985915492957747 - nodes in this community are weakly interconnected._
- **Why does `redactSecretsInError()` connect `redactSecretsInError` to `server.js`, `incident-store.js`, `server`, `reaction-commands.js`, `buildSessionPreamble`, `vertex-fallback.test.js`, `reactionCommandService`, `callVertexWithCascade`, `incident-store.test.js`, `createFamilyConciergeStore`, `loop-store.js`, `reactionCommandService`, `sqlStr`, `probe-incident-signatures.js`, `family-concierge-store.js`?**
  _High betweenness centrality (0.023) - this node is a cross-community bridge._
- **Should `reaction-commands.test.js` be split into smaller, more focused modules?**
  _Cohesion score 0.07956989247311828 - nodes in this community are weakly interconnected._
- **Why does `createModelRouter()` connect `model-router.js` to `server.js`?**
  _High betweenness centrality (0.019) - this node is a cross-community bridge._
- **Should `model-router.js` be split into smaller, more focused modules?**
  _Cohesion score 0.07017543859649122 - nodes in this community are weakly interconnected._