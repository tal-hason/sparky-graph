# Graph Report - sparky-backup  (2026-11-20)

## Corpus Check
- 112 files · ~254,151 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 12 file(s) not represented in the graph (top: (none) 5, .service 5, .example 1)

## Summary
- 1611 nodes · 3124 edges · 92 communities (69 shown, 23 thin omitted)
- Extraction: 89% EXTRACTED · 11% INFERRED · 0% AMBIGUOUS · INFERRED: 356 edges (avg confidence: 0.86)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `34e806ae`
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
- host-adapters.js
- correction-learner.js
- Sentinel Actor Model & Conversational Handshake Architecture
- The Four Cynefin Domains in Sparky
- family-concierge-store.js
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
- redactSecretsInError
- heartbeat-store.test.js
- ref_child_process
- host-adapters.test.js
- n8n-sparky/test-n8n-patches.js
- lifecycle.test.js
- config.test.js
- phase2c-ops.test.js
- sentinel-commute-helpers.js
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
- isTestPayload
- probe-db-parity.js
- run-agent-eval.sh
- Sparky-Plex: Autonomous Executive Assistant & Infrastructure
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
- sentinel-commute-helpers.test.js
- family-routes.js
- vertex-fallback.test.js
- test_workspace_mutations.js
- callVertexWithCascade
- TestEopSkillAndBackupScriptContract
- TestReactionCommandDeckWorkflows
- createFamilyConciergeStore
- projectTalSchedule
- TestFamilyConciergeWorkflows
- sqlStr
- TestGoldenDatasetPresence

## God Nodes (most connected - your core abstractions)
1. `server` - 117 edges
2. `redactSecretsInError()` - 47 edges
3. `queryPostgresJson()` - 24 edges
4. `normalizeIsraeliPhone()` - 21 edges
5. `buildSessionPreamble()` - 21 edges
6. `TaskDaemon` - 21 edges
7. `sqlStr()` - 20 edges
8. `createModelRouter()` - 19 edges
9. `createFamilyConciergeStore()` - 18 edges
10. `createReactionActivityController()` - 18 edges

## Surprising Connections (you probably didn't know these)
- `1. User Intent & Selected Architecture` --references--> `buildSessionPreamble()`  [INFERRED]
  docs/brainstorms/sparky-dynamic-model-routing-requirements.md → services/vertex-search-bridge/server.js
- `A2. Full-Ecosystem Scope (Locked Across All 8 Branches)` --references--> `completeTurn()`  [INFERRED]
  docs/brainstorms/sparky-gemini4-neon-roster-requirements.md → services/vertex-search-bridge/reaction-activity.js
- `🛠️ Microservice Bridge (Port 5055)` --references--> `replayHeldQuietHoursMessages()`  [INFERRED]
  README.md → services/vertex-search-bridge/server.js
- `🛠️ Microservice Bridge (Port 5055)` --references--> `validateUrlForBrowser()`  [INFERRED]
  README.md → services/vertex-search-bridge/host-adapters.js
- `🛠️ Microservice Bridge (Port 5055)` --references--> `reset()`  [INFERRED]
  README.md → services/vertex-search-bridge/model-router.js

## Import Cycles
- None detected.

## Communities (92 total, 23 thin omitted)

### Community 0 - "server.js"
Cohesion: 0.02
Nodes (60): {
  ALLOWED_WORKSPACES,
  ALLOWED_AGY_MODELS,
  validateOptionalAgyModel,
  buildAgyTaskPayload,
  dispatchAgyMissionToDrive,
}, BRIDGE_API_TOKEN, BRIDGE_STARTED_AT, circuitBreakers, {
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
}, config (+52 more)

### Community 1 - "reaction-commands.test.js"
Cohesion: 0.08
Nodes (13): AgyDriver, assert, BridgeCommandDriver, { EventEmitter }, fs, loadCorrectionLearner(), loadReactionCommands(), os (+5 more)

### Community 2 - "ref_fs"
Cohesion: 0.18
Nodes (13): bridgeRequest(), fs, getBridgeToken(), { bridgeRequest }, fs, isSafeHeartbeatPath(), path, readStdin() (+5 more)

### Community 3 - "model-router.js"
Cohesion: 0.07
Nodes (54): 1. Locked Architecture & 4-Model Periodic Roster (Bootstrap + `/grill-me` Convergence), 2. Live Empirical Probe Ground Truth (`spark-509400` & `agy` CLI, 2026-11-19), 3. Bounded Complex Probes Gating Rollout, 4. Post-Pre-Flight Run #1 `/grill-me` Convergence (Branches 1–5 Locked), A1. Strict Monotonic 6-Tier Periodic Matrix (`COGNITIVE_TIERS` in `/root/vertex-search-bridge/model-router.js`), A2. Full-Ecosystem Scope (Locked Across All 8 Branches), A3. Generalized Heavy-Model Circuit Breaker & Guardrails, Requirements Anchor: Sparky-AI Gemini 4 Neon 4-Model Periodic Roster (+46 more)

### Community 4 - "server-endpoints.test.js"
Cohesion: 0.06
Nodes (35): assert, assertBalancedSentinelXml(), assertHostileEscaped(), callBridge(), checkActiveDecision(), checkCommute(), checkDue(), checkReminders() (+27 more)

### Community 5 - "server"
Cohesion: 0.09
Nodes (36): normalizeReactionEmoji(), atomicWriteJson(), cleanNullableStr(), encodeMarkdownUrl(), fetchBufferFromUrl(), generateEmbedding(), handleAgyMissionRoute(), handleReactionExecuteRoute() (+28 more)

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

### Community 14 - "family-concierge-store.js"
Cohesion: 0.08
Nodes (11): {
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
}, { formatIsoTimeIl }, { redactSecretsInError }, { sqlStr, sqlJsonb, sqlJsonbArray, sqlTimestamptz }, { ADMIN_PHONE, normalizeIsraeliPhone, sanitizeFamilyText } (+3 more)

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
Cohesion: 0.11
Nodes (17): assert, BACKUP_FILE, { buildCanonicalLoopKey, generateDeterministicLoopId }, clone(), createFakeWorld(), mergeJsonbLiteral(), queryPostgresJson(), queryPostgresWithStdin() (+9 more)

### Community 29 - "memory-hygiene.js"
Cohesion: 0.12
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

### Community 36 - "redactSecretsInError"
Cohesion: 0.08
Nodes (43): ALLOWED_AGY_MODEL_SET, ALLOWED_AGY_MODELS, ALLOWED_WORKSPACES, buildAgyTaskPayload(), buildFencedMissionPrompt(), dispatchAgyMissionToDrive(), fetchAgyAccessToken(), fs (+35 more)

### Community 37 - "heartbeat-store.test.js"
Cohesion: 0.09
Nodes (24): extractInteractiveOptions(), FAMILY_NON_DECISION_SOURCES, INTERACTIVE_SENTINEL_SOURCES, NON_DECISION_SOURCES, SOURCE_ALIAS_GROUPS, createHeartbeatStore(), flushSentinel(), listHeartbeats() (+16 more)

### Community 38 - "ref_child_process"
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

### Community 44 - "sentinel-commute-helpers.js"
Cohesion: 0.27
Nodes (12): evaluateCommuteWindow(), filterAndSortEvents(), formatCommuteBriefingLine(), formatIsoTimeIl(), formatOriginLabel(), hasVideo(), isPhysical(), isVirtualLink() (+4 more)

### Community 45 - "family-relay.js"
Cohesion: 0.18
Nodes (22): classifyFamilyInboundText(), createFamilyRelayService(), configureFamilyMember(), handleFamilyInbound(), loadCtx(), loadFamilyLoops(), processFamilyInbound(), recordChatHistory() (+14 more)

### Community 46 - "reactionCommandService"
Cohesion: 0.16
Nodes (18): readStreamUtf8(), callGoogleRoutesApi(), callOsrmFallback(), callVertexApiWithRetry(), callVertexFastJson(), runModelAttempt(), sendOnce(), computeCommute() (+10 more)

### Community 47 - "index.js"
Cohesion: 0.19
Nodes (12): processJsonRpcMessage(), { ALLOWED_AGY_MODELS, validateOptionalAgyModel }, { bridgeRequest }, dispatchAgyMissionToDrive(), fs, handleToolCall(), readHeartbeatMeta(), readline (+4 more)

### Community 48 - "buildSessionPreamble"
Cohesion: 0.11
Nodes (31): getDecisionSourceAliases(), advanceInTransitLoopOnKeepTracking(), buildSessionPreamble(), checkAndDispatchDueReminders(), createDecision(), effectiveDue(), getSentinelEvent(), getSystemAudit() (+23 more)

### Community 51 - "queryPostgresJson"
Cohesion: 0.19
Nodes (25): checkAndDispatchWindowKeepalive(), familyConciergeStore, familyRelay, familyRoutes, getWindowState(), invalidateWindowStateCache(), loadCleanDialogueTurns(), loadContext() (+17 more)

### Community 52 - "publish-graph.sh"
Cohesion: 0.50
Nodes (3): HOME, PATH, publish-graph.sh script

### Community 53 - "config.js"
Cohesion: 0.14
Nodes (8): compactSessionChatHistory(), compactToolObservationContent(), createMetaTokenReader(), crypto, defaultConfig, fs, normalizeHistoryRow(), path

### Community 55 - "TaskDaemon"
Cohesion: 0.06
Nodes (7): extract_stream_json_result(), read_heartbeat_meta(), resolve_task_model(), resolve_timeouts(), sd_notify(), TaskDaemon, TestDaemon

### Community 56 - "makeWorld"
Cohesion: 0.60
Nodes (6): makeWorld(), parseItemsArray(), parseJsonbParam(), queryPostgresJson(), queryPostgresWithStdin(), test

### Community 57 - "family-concierge-store.js"
Cohesion: 0.09
Nodes (16): applyDispatchAckButtonPolicy(), BRIEFING_ACK_SOURCES, computeFamilyKeepaliveDecision(), computeKeepaliveDecision(), getLocalHourMinuteIl(), IL_DATE_FMT, IL_HOUR_MINUTE_FMT, isQuietHourRange() (+8 more)

### Community 59 - "vertex-search-bridge/package.json"
Cohesion: 0.14
Nodes (13): dependencies, pg, description, engines, node, main, name, private (+5 more)

### Community 60 - "ref_node_test"
Cohesion: 0.12
Nodes (12): assert, { createHandoffStore, formatHandoffsXml }, { describe, it }, assert, FIXTURE_PATH, fs, { generateDeterministicLoopId }, path (+4 more)

### Community 61 - "test_agent_evaluation.py"
Cohesion: 0.15
Nodes (4): _eval_n8n_expr(), TestSessionIsolation, TestDeterministicCLIGraphQuery, TestGraphifyCLIBinary

### Community 62 - "Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`)"
Cohesion: 0.33
Nodes (5): Emergency Sub-Minute Rollback to Host `systemd` (`vertex-search.service`), Overview, Returning from Host `systemd` to Container (`vertex-bridge`), Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`), Standard Deployment & Digest Rollback (`deploy-bridge.sh`)

### Community 63 - "isTestPayload"
Cohesion: 0.47
Nodes (9): createWhatsAppEgress(), sendWhatsAppDirect(), sendWhatsAppReengageTemplate(), sendWhatsAppTemplate(), isTestPayload(), normalizeDirectArgs(), quietHours, sanitizeTemplateParam() (+1 more)

### Community 64 - "probe-db-parity.js"
Cohesion: 0.29
Nodes (6): resolveConfig(), assert, config, { createDb }, main(), QUERIES

### Community 65 - "run-agent-eval.sh"
Cohesion: 0.50
Nodes (3): HOME, PATH, run-agent-eval.sh script

### Community 66 - "Sparky-Plex: Autonomous Executive Assistant & Infrastructure"
Cohesion: 0.25
Nodes (7): Automated Backup, 🔄 Automated Backup & Disaster Recovery, Full Disaster Recovery, 📁 Repository Structure, 🔒 Security & Privacy Notice, Sparky-Plex: Autonomous Executive Assistant & Infrastructure, 🏛️ System Architecture

### Community 70 - "isTestPayload"
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

### Community 71 - "ref_path"
Cohesion: 0.29
Nodes (9): { execFileSync }, fs, main(), migrateJsCode(), migrateNodes(), migrateUrlParam(), path, runPsql() (+1 more)

### Community 78 - "Requirements Anchor: Sparky-AI Dynamic Main Agent Model & Effort Routing"
Cohesion: 0.50
Nodes (3): 1. User Intent & Selected Architecture, 2. Verified Architectural Invariants & Test Alignment, Requirements Anchor: Sparky-AI Dynamic Main Agent Model & Effort Routing

### Community 80 - "sentinel-commute-helpers.test.js"
Cohesion: 0.25
Nodes (6): assert, commuteDsl, fs, path, SUT_PATH, test

### Community 82 - "family-routes.js"
Cohesion: 0.40
Nodes (3): { escXml }, { redactSecretsInError }, { sanitizeFamilyText, normalizeIsraeliPhone }

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

### Community 85 - "test_workspace_mutations.js"
Cohesion: 0.11
Nodes (18): APPEND_WF_PATH, cleanupRegistry, CREATE_DOC_WF_PATH, CREATE_SHEET_WF_PATH, CREATE_SLIDES_WF_PATH, { execSync, execFileSync }, EXPECTED_HEADERS, formatOutput() (+10 more)

### Community 86 - "callVertexWithCascade"
Cohesion: 0.39
Nodes (8): analyzeImageBuffer(), callGeminiJson(), callVertexWithCascade(), kgStore, notifyVertexCascadeExhaustion(), searchWithVertex(), transcribeAudioBuffer(), extractVertexCandidateText()

### Community 89 - "createFamilyConciergeStore"
Cohesion: 0.38
Nodes (14): createFamilyConciergeStore(), completeRelayFromAgent(), flushMessagesForTal(), getCachedSchedule(), loadOpenRelayLoops(), manageMessageForTal(), manageMessageForTalUnlocked(), recordChatHistory() (+6 more)

### Community 90 - "projectTalSchedule"
Cohesion: 0.20
Nodes (13): 🛠️ Microservice Bridge (Port 5055), createFamilyMorningService(), composeMorningGreeting(), formatFamilyOutboxBatch(), getMorningGreetingTargets(), loadCtx(), evaluateDueBatch(), buildFamilyContextXml() (+5 more)

### Community 92 - "sqlStr"
Cohesion: 0.08
Nodes (47): createFamilyOutboxStore(), ackBatch(), claimDueBatches(), deferBatch(), ensureSchema(), inspectBatchState(), loadQueuedBatch(), mergeFlushingIntoQueued() (+39 more)

## Knowledge Gaps
- **20 isolated node(s):** `RFC-8414`, `RFC-9728`, `RFC-7591`, `PATH`, `HOME` (+15 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 718 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **23 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `server` connect `server` to `server.js`, `model-router.js`, `redactSecretsInError`, `nudge-telemetry.js`, `correction-learner.js`, `sentinel-commute-helpers.js`, `family-relay.js`, `reactionCommandService`, `reaction-commands.js`, `buildSessionPreamble`, `queryPostgresJson`, `callVertexWithCascade`, `projectTalSchedule`, `sqlStr`, `memory-hygiene.js`, `isTestPayload`?**
  _High betweenness centrality (0.032) - this node is a cross-community bridge._
- **What connects `RFC-8414`, `RFC-9728`, `RFC-7591` to the rest of the system?**
  _20 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `server.js` be split into smaller, more focused modules?**
  _Cohesion score 0.015748031496062992 - nodes in this community are weakly interconnected._
- **Why does `redactSecretsInError()` connect `redactSecretsInError` to `server.js`, `server`, `family-concierge-store.js`, `reactionCommandService`, `reaction-commands.js`, `family-routes.js`, `queryPostgresJson`, `callVertexWithCascade`, `createFamilyConciergeStore`, `projectTalSchedule`, `sqlStr`?**
  _High betweenness centrality (0.026) - this node is a cross-community bridge._
- **Should `reaction-commands.test.js` be split into smaller, more focused modules?**
  _Cohesion score 0.07956989247311828 - nodes in this community are weakly interconnected._
- **Why does `1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4)` connect `host-adapters.js` to `correction-learner.js`, `memory-hygiene.js`?**
  _High betweenness centrality (0.016) - this node is a cross-community bridge._
- **Should `model-router.js` be split into smaller, more focused modules?**
  _Cohesion score 0.07017543859649122 - nodes in this community are weakly interconnected._