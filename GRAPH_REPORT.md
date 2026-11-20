# Graph Report - sparky-backup  (2026-11-20)

## Corpus Check
- 112 files · ~257,835 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 12 file(s) not represented in the graph (top: (none) 5, .service 5, .example 1)

## Summary
- 1530 nodes · 3157 edges · 95 communities (73 shown, 22 thin omitted)
- Extraction: 89% EXTRACTED · 11% INFERRED · 0% AMBIGUOUS · INFERRED: 358 edges (avg confidence: 0.86)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `c1eca26f`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- server.js
- reaction-commands.test.js
- ref_fs
- model-router.js
- server-endpoints.test.js
- sentinel-commute-helpers.js
- Requirements Anchor: Sparky-AI Nightly Dreaming Knowledge Graph (`sparky-nightly-knowledge-graph`)
- Semantic Vector Memory & Cortex Sleep Consolidation Architecture
- createReactionActivityController
- test_graphify_integration.py
- host-adapters.js
- correction-learner.js
- Sentinel Actor Model & Conversational Handshake Architecture
- The Four Cynefin Domains in Sparky
- normalizeIsraeliPhone
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
- Sparky-Plex: Autonomous Executive Assistant & Infrastructure
- ref_child_process
- host-adapters.test.js
- n8n-sparky/test-n8n-patches.js
- lifecycle.test.js
- config.test.js
- phase2c-ops.test.js
- daemon.py
- family-relay.js
- reactionCommandService
- index.js
- buildSessionPreamble
- patch-n8n-memory-orphans.sh
- TestWorkflowTelemetry
- queryPostgresJson
- publish-graph.sh
- config.js
- TestEvaluationHarnessWorkflow
- TaskDaemon
- makeWorld
- family-concierge-store.js
- TestEvaluationSafetyGuard
- vertex-search-bridge/package.json
- ref_node_test
- test_agent_evaluation.py
- Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`)
- createFamilyOutboxStore
- probe-db-parity.js
- run-agent-eval.sh
- ref_fs
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
- agy-mission-client.js
- loop-store.integration.test.js
- sentinel-commute-helpers.test.js
- vertex-fallback.test.js
- createDb
- test_workspace_mutations.js
- callVertexWithCascade
- redactSecretsInError
- TestReactionCommandDeckWorkflows
- createFamilyConciergeStore
- family-morning.js
- TestFamilyConciergeWorkflows
- sqlStr
- scripts
- TestDaemon

## God Nodes (most connected - your core abstractions)
1. `server` - 124 edges
2. `redactSecretsInError()` - 47 edges
3. `sqlStr()` - 29 edges
4. `queryPostgresJson()` - 24 edges
5. `buildSessionPreamble()` - 23 edges
6. `TaskDaemon` - 21 edges
7. `normalizeIsraeliPhone()` - 21 edges
8. `createModelRouter()` - 20 edges
9. `createFamilyConciergeStore()` - 18 edges
10. `sqlJsonb()` - 18 edges

## Surprising Connections (you probably didn't know these)
- `🏛️ System Architecture` --references--> `resolveFamilyGrammar()`  [INFERRED]
  README.md → services/vertex-search-bridge/family-schedule.js
- `1. User Intent & Selected Architecture` --references--> `buildSessionPreamble()`  [INFERRED]
  docs/brainstorms/sparky-dynamic-model-routing-requirements.md → services/vertex-search-bridge/server.js
- `A2. Full-Ecosystem Scope (Locked Across All 8 Branches)` --references--> `buildAgyTaskPayload()`  [INFERRED]
  docs/brainstorms/sparky-gemini4-neon-roster-requirements.md → services/vertex-search-bridge/agy-mission-client.js
- `2. Verified Architectural Invariants & Test Alignment` --references--> `compactSessionChatHistory()`  [INFERRED]
  docs/brainstorms/sparky-dynamic-model-routing-requirements.md → services/vertex-search-bridge/config.js
- `🛠️ Microservice Bridge (Port 5055)` --references--> `formatFamilyOutboxBatch()`  [INFERRED]
  README.md → services/vertex-search-bridge/family-morning.js

## Import Cycles
- None detected.

## Communities (95 total, 22 thin omitted)

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

### Community 4 - "server-endpoints.test.js"
Cohesion: 0.07
Nodes (35): assert, assertBalancedSentinelXml(), assertHostileEscaped(), callBridge(), checkActiveDecision(), checkCommute(), checkDue(), checkReminders() (+27 more)

### Community 5 - "sentinel-commute-helpers.js"
Cohesion: 0.27
Nodes (11): evaluateCommuteWindow(), filterAndSortEvents(), formatCommuteBriefingLine(), formatOriginLabel(), hasVideo(), isPhysical(), isVirtualLink(), nextPriorPhysical() (+3 more)

### Community 6 - "Requirements Anchor: Sparky-AI Nightly Dreaming Knowledge Graph (`sparky-nightly-knowledge-graph`)"
Cohesion: 0.50
Nodes (3): 1. User Intent & Selected Architecture (1 + 3 Hybrid), 2. Core Invariants & Boundaries, Requirements Anchor: Sparky-AI Nightly Dreaming Knowledge Graph (`sparky-nightly-knowledge-graph`)

### Community 7 - "Semantic Vector Memory & Cortex Sleep Consolidation Architecture"
Cohesion: 0.11
Nodes (18): 1. Architectural Blueprint & Cognitive Model, 2. Infrastructure & Storage (`pgvector`), 3. Multilingual Embedding Pipeline, 4. Bridge Microservice Endpoints ([`server.js`](file:///root/vertex-search-bridge/server.js)), 5. Main Agent Integration (`search_memory` FunctionCall), 6. Nightly Cortex Sleep Consolidation (`POST /cortex/sleep-cycle`), 7.1 PostgreSQL Relational + Vector Graph Schema, 7.2 Nightly Single-Pass Extraction & Backfill (+10 more)

### Community 8 - "createReactionActivityController"
Cohesion: 0.16
Nodes (23): cloneConfig(), createReactionActivityController(), completeTurn(), dispatchEmojiNow(), evictIfFull(), getConfig(), getOrCreateState(), getStatus() (+15 more)

### Community 9 - "test_graphify_integration.py"
Cohesion: 0.14
Nodes (5): _extract_source_files(), TestCodebaseInclusionInGraph, TestIncrementalUpdateIdempotency, TestPersonalMemoryGraphIsolation, TestStrictExclusionBoundary

### Community 10 - "host-adapters.js"
Cohesion: 0.07
Nodes (33): 1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4), 2. Quality Gates, Observability & Disaster Recovery (Epic E3), 3. Platform Architecture & Refactoring (Epic E5), DEF-01: Global Attention Budget & Quiet Hours Hold Queue (`23:00–07:00`), DEF-02: Nudge-Effectiveness Telemetry & Sentinel Self-Tuning, DEF-03: Sunday Weekly Review & Overdue Loop Escalation Ladder, DEF-06: Auto-Incident Knowledge Base (`knowledge-base.json`) Draft Capture, DEF-07: Golden Evaluation Dataset Expansion (`3/45` → Core Tools) & Change Gate (+25 more)

### Community 11 - "correction-learner.js"
Cohesion: 0.07
Nodes (46): RFC-2822, DEF-04: Real-Time In-Turn Correction Learning (`"No, I meant..."`), containsSecretOrPassword(), createCorrectionLearner(), extractAndSaveCorrection(), detectCorrectionSignal(), findDuplicateFieldNote(), redactAllSecrets() (+38 more)

### Community 12 - "Sentinel Actor Model & Conversational Handshake Architecture"
Cohesion: 0.20
Nodes (9): 1. Executive Summary, 2. Dual-Channel XML Sensory Pipeline, 3. Active Conversational Handshake & Latency Masking, 4. Active Workflow Catalog (11 Total), 5. Central Egress Hub (`/whatsapp/dispatch`), Sentinel Actor Model & Conversational Handshake Architecture, The Problem, The Solution (+1 more)

### Community 13 - "The Four Cynefin Domains in Sparky"
Cohesion: 0.22
Nodes (8): 1. Clear / Simple Domain (Known Knowns), 2. Complicated Domain (Known Unknowns), 3. Complex Domain (Unknown Unknowns), 4. Chaotic Domain (Unknowables / Crises), 5. Aporia / Confusion, Architectural Overview, Cynefin + OODA Loop Cognitive Framework, The Four Cynefin Domains in Sparky

### Community 14 - "normalizeIsraeliPhone"
Cohesion: 0.17
Nodes (19): normalizeIsraeliPhone(), resolveAuthorizedUserByPhone(), checkAndDispatchWindowKeepalive(), familyRoutes, handleAgyMissionRoute(), handleReactionExecuteRoute(), handleWhatsappTtsRoute(), isAuthorizedRecipient() (+11 more)

### Community 15 - "reaction-commands.js"
Cohesion: 0.07
Nodes (56): buildCanonicalLoopKey(), classifyLoopsByDue(), classifyShipmentLifecycle(), computeDefaultShipmentFollowUp(), crypto, effectiveDue(), encodeCanonicalLoopId(), extractLoopEntityKey() (+48 more)

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

### Community 27 - "family-relay.test.js"
Cohesion: 0.06
Nodes (41): extractInteractiveOptions(), FAMILY_NON_DECISION_SOURCES, INTERACTIVE_SENTINEL_SOURCES, NON_DECISION_SOURCES, SOURCE_ALIAS_GROUPS, createHeartbeatStore(), flushSentinel(), listHeartbeats() (+33 more)

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
Cohesion: 0.15
Nodes (20): computeSignature(), createIncidentStore(), draftLessonsFromCandidates(), recordCandidate(), crypto, normalizeErrorKey(), redactAndNormalizeError(), sqlStr() (+12 more)

### Community 37 - "Sparky-Plex: Autonomous Executive Assistant & Infrastructure"
Cohesion: 0.25
Nodes (7): Automated Backup, 🔄 Automated Backup & Disaster Recovery, Full Disaster Recovery, 📁 Repository Structure, 🔒 Security & Privacy Notice, Sparky-Plex: Autonomous Executive Assistant & Infrastructure, 🏛️ System Architecture

### Community 38 - "ref_child_process"
Cohesion: 0.33
Nodes (5): { execFile }, formatPgCell(), formatPgResultAsPsql(), RAW_STRING_OIDS, registerRawStringTypeParsers()

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

### Community 44 - "daemon.py"
Cohesion: 0.11
Nodes (3): extract_stream_json_result(), resolve_task_model(), resolve_timeouts()

### Community 45 - "family-relay.js"
Cohesion: 0.20
Nodes (19): classifyFamilyInboundText(), createFamilyRelayService(), configureFamilyMember(), handleFamilyInbound(), loadCtx(), loadFamilyLoops(), processFamilyInbound(), recordChatHistory() (+11 more)

### Community 46 - "reactionCommandService"
Cohesion: 0.20
Nodes (15): readStreamUtf8(), callGoogleRoutesApi(), callOsrmFallback(), callVertexApiWithRetry(), computeCommute(), fetchMetaMedia(), getAccessToken(), getMetaToken (+7 more)

### Community 47 - "index.js"
Cohesion: 0.19
Nodes (12): processJsonRpcMessage(), { ALLOWED_AGY_MODELS, validateOptionalAgyModel }, { bridgeRequest }, dispatchAgyMissionToDrive(), fs, handleToolCall(), readHeartbeatMeta(), readline (+4 more)

### Community 48 - "buildSessionPreamble"
Cohesion: 0.08
Nodes (50): 🛠️ Microservice Bridge (Port 5055), getDecisionSourceAliases(), normalizeReactionEmoji(), advanceInTransitLoopOnKeepTracking(), buildSessionPreamble(), checkAndDispatchDueReminders(), cleanNullableStr(), createDecision() (+42 more)

### Community 51 - "queryPostgresJson"
Cohesion: 0.28
Nodes (18): familyConciergeStore, familyRelay, getWindowState(), invalidateWindowStateCache(), logActivityEvent(), postMetaMediaOnce(), queryPostgresStrict(), queryPostgresWithStdin() (+10 more)

### Community 52 - "publish-graph.sh"
Cohesion: 0.50
Nodes (3): HOME, PATH, publish-graph.sh script

### Community 53 - "config.js"
Cohesion: 0.14
Nodes (8): compactSessionChatHistory(), compactToolObservationContent(), createMetaTokenReader(), crypto, defaultConfig, fs, normalizeHistoryRow(), path

### Community 55 - "TaskDaemon"
Cohesion: 0.16
Nodes (3): read_heartbeat_meta(), sd_notify(), TaskDaemon

### Community 56 - "makeWorld"
Cohesion: 0.60
Nodes (6): makeWorld(), parseItemsArray(), parseJsonbParam(), queryPostgresJson(), queryPostgresWithStdin(), test

### Community 57 - "family-concierge-store.js"
Cohesion: 0.08
Nodes (19): applyDispatchAckButtonPolicy(), BRIEFING_ACK_SOURCES, computeFamilyKeepaliveDecision(), computeKeepaliveDecision(), FEMALE_REL_SET, getLocalHourMinuteIl(), IL_DATE_FMT, IL_HOUR_MINUTE_FMT (+11 more)

### Community 59 - "vertex-search-bridge/package.json"
Cohesion: 0.18
Nodes (10): pg, dependencies, pg, description, engines, node, main, name (+2 more)

### Community 60 - "ref_node_test"
Cohesion: 0.22
Nodes (6): assert, { createHandoffStore, formatHandoffsXml }, { describe, it }, assert, { createLoopStore }, test

### Community 61 - "test_agent_evaluation.py"
Cohesion: 0.09
Nodes (6): _eval_n8n_expr(), TestGoldenDatasetPresence, TestSessionIsolation, TestDeterministicCLIGraphQuery, TestEopSkillAndBackupScriptContract, TestGraphifyCLIBinary

### Community 62 - "Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`)"
Cohesion: 0.33
Nodes (5): Emergency Sub-Minute Rollback to Host `systemd` (`vertex-search.service`), Overview, Returning from Host `systemd` to Container (`vertex-bridge`), Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`), Standard Deployment & Digest Rollback (`deploy-bridge.sh`)

### Community 63 - "createFamilyOutboxStore"
Cohesion: 0.58
Nodes (9): createFamilyOutboxStore(), ackBatch(), claimDueBatches(), deferBatch(), ensureSchema(), inspectBatchState(), mergeFlushingIntoQueued(), runStrictJsonSql() (+1 more)

### Community 64 - "probe-db-parity.js"
Cohesion: 0.29
Nodes (6): resolveConfig(), assert, config, { createDb }, main(), QUERIES

### Community 65 - "run-agent-eval.sh"
Cohesion: 0.50
Nodes (3): HOME, PATH, run-agent-eval.sh script

### Community 66 - "ref_fs"
Cohesion: 0.22
Nodes (6): assert, FIXTURE_PATH, fs, { generateDeterministicLoopId }, path, test

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

### Community 80 - "agy-mission-client.js"
Cohesion: 0.18
Nodes (15): ALLOWED_AGY_MODEL_SET, ALLOWED_AGY_MODELS, ALLOWED_WORKSPACES, buildAgyTaskPayload(), buildFencedMissionPrompt(), dispatchAgyMissionToDrive(), fetchAgyAccessToken(), fs (+7 more)

### Community 81 - "loop-store.integration.test.js"
Cohesion: 0.32
Nodes (7): assert, { createLoopStore }, { execFile }, queryPostgresJson(), queryPostgresWithStdin(), store, test

### Community 82 - "sentinel-commute-helpers.test.js"
Cohesion: 0.25
Nodes (6): assert, commuteDsl, fs, path, SUT_PATH, test

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

### Community 84 - "createDb"
Cohesion: 0.53
Nodes (5): createDb(), getOrInitPgPool(), queryPostgresJson(), queryPostgresScript(), queryPostgresWithStdin()

### Community 85 - "test_workspace_mutations.js"
Cohesion: 0.11
Nodes (18): APPEND_WF_PATH, cleanupRegistry, CREATE_DOC_WF_PATH, CREATE_SHEET_WF_PATH, CREATE_SLIDES_WF_PATH, { execSync, execFileSync }, EXPECTED_HEADERS, formatOutput() (+10 more)

### Community 86 - "callVertexWithCascade"
Cohesion: 0.20
Nodes (14): analyzeImageBuffer(), callGeminiJson(), callVertexWithCascade(), generateEmbedding(), insertSemanticMemory(), kgStore, memoryHygieneStore, notifyVertexCascadeExhaustion() (+6 more)

### Community 87 - "redactSecretsInError"
Cohesion: 0.33
Nodes (11): loadQueuedBatch(), createFamilyRoutesHandler(), handleFamilyRoute(), handleJsonRoute(), requireToken(), sendFamilyError(), writeStoreResult(), { escXml } (+3 more)

### Community 89 - "createFamilyConciergeStore"
Cohesion: 0.31
Nodes (17): createFamilyConciergeStore(), completeRelayFromAgent(), flushMessagesForTal(), getCachedSchedule(), loadOpenRelayLoops(), manageMessageForTal(), manageMessageForTalUnlocked(), recordChatHistory() (+9 more)

### Community 90 - "family-morning.js"
Cohesion: 0.13
Nodes (20): {
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
}, { formatIsoTimeIl }, { redactSecretsInError }, { sqlStr, sqlJsonb, sqlJsonbArray, sqlTimestamptz }, { ADMIN_PHONE, normalizeIsraeliPhone, sanitizeFamilyText } (+12 more)

### Community 92 - "sqlStr"
Cohesion: 0.16
Nodes (24): updateLoopMetadata(), upsertQueuedBatch(), { parseIsoMs }, { redactSecretsInError }, { sqlStr, sqlJsonb, sqlJsonbArray, sqlTimestamptz }, { stripCalendarEventForFamily, projectTalSchedule }, updateLoopMetadata(), {
  ACTIONABLE_STATUS_RE,
  generateDeterministicLoopId,
  stripBidi,
} (+16 more)

### Community 93 - "scripts"
Cohesion: 0.50
Nodes (4): scripts, start, test, test:ci

## Knowledge Gaps
- **20 isolated node(s):** `PATH`, `PATH`, `HOME`, `REGISTRY_AUTH_FILE`, `PATH` (+15 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 641 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **22 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `redactSecretsInError()` connect `redactSecretsInError` to `server.js`, `incident-store.js`, `normalizeIsraeliPhone`, `agy-mission-client.js`, `buildSessionPreamble`, `vertex-fallback.test.js`, `queryPostgresJson`, `callVertexWithCascade`, `createFamilyConciergeStore`, `family-morning.js`, `sqlStr`, `createFamilyOutboxStore`?**
  _High betweenness centrality (0.028) - this node is a cross-community bridge._
- **What connects `PATH`, `PATH`, `HOME` to the rest of the system?**
  _20 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `server.js` be split into smaller, more focused modules?**
  _Cohesion score 0.030985915492957747 - nodes in this community are weakly interconnected._
- **Why does `DEF-05: Semantic Memory Contradiction Detection & Temporal Decay` connect `memory-hygiene.js` to `host-adapters.js`?**
  _High betweenness centrality (0.023) - this node is a cross-community bridge._
- **Should `reaction-commands.test.js` be split into smaller, more focused modules?**
  _Cohesion score 0.07956989247311828 - nodes in this community are weakly interconnected._
- **Why does `1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4)` connect `host-adapters.js` to `correction-learner.js`, `memory-hygiene.js`?**
  _High betweenness centrality (0.023) - this node is a cross-community bridge._
- **Should `model-router.js` be split into smaller, more focused modules?**
  _Cohesion score 0.07017543859649122 - nodes in this community are weakly interconnected._