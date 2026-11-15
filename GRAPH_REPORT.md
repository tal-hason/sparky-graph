# Graph Report - sparky-backup  (2026-11-15)

## Corpus Check
- 100 files · ~193,147 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 12 file(s) not represented in the graph (top: (none) 5, .service 5, .example 1)

## Summary
- 1237 nodes · 2356 edges · 86 communities (60 shown, 26 thin omitted)
- Extraction: 89% EXTRACTED · 11% INFERRED · 0% AMBIGUOUS · INFERRED: 266 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `345b6060`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- server.js
- reaction-commands.test.js
- ref_fs
- model-router.js
- test_workspace_mutations.js
- TaskDaemon
- Requirements Anchor: Sparky-AI Nightly Dreaming Knowledge Graph (`sparky-nightly-knowledge-graph`)
- Semantic Vector Memory & Cortex Sleep Consolidation Architecture
- createReactionActivityController
- test_graphify_integration.py
- 1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4)
- correction-learner.js
- Sentinel Actor Model & Conversational Handshake Architecture
- The Four Cynefin Domains in Sparky
- Sparky-Plex: Autonomous Executive Assistant & Infrastructure
- family-relay.test.js
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
- readStreamUtf8
- update.sh
- memory-hygiene.js
- db-adapter.test.js
- patch-gemini4-langchain.sh
- install-apps.sh
- restore.sh
- test_agent_telemetry.sh
- nudge-telemetry.js
- reaction-commands.js
- heartbeat-store.js
- quiet-hours.test.js
- host-adapters.test.js
- n8n-sparky/test-n8n-patches.js
- lifecycle.test.js
- config.test.js
- phase2c-ops.test.js
- ref_path
- family-relay.js
- TestEvaluationSafetyGuard
- index.js
- server
- patch-n8n-memory-orphans.sh
- buildSessionPreamble
- reactionCommandService
- publish-graph.sh
- config.js
- decision-helpers.js
- TestDeterministicCLIGraphQuery
- callVertexApiWithRetry
- ref_child_process
- server-endpoints.test.js
- vertex-search-bridge/package.json
- ref_node_test
- test_agent_evaluation.py
- Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`)
- run
- probe-db-parity.js
- run-agent-eval.sh
- run
- sync-services-to-repo.sh
- n8n-stack/scripts/deploy-bridge.sh
- eval-history.md
- TestEvaluationHarnessWorkflow
- atomicWriteJson
- Requirements Anchor: `[Sparky-AI]` Event-Driven Email Handoff to Gemini App
- n8n-sparky/patch-gemini4-langchain.sh
- n8n-sparky/patch-n8n-memory-orphans.sh
- TestWorkflowTelemetry
- scripts/patch-retry-backoff.sh
- n8n-sparky/patch-retry-backoff.sh
- Requirements Anchor: Sparky-AI Dynamic Main Agent Model & Effort Routing
- TestEopSkillAndBackupScriptContract
- TestDynamicModelRoutingCallers
- TestReactionCommandDeckWorkflows
- loop-store.integration.test.js
- scripts
- TestGoldenDatasetPresence
- TestAntigravitySkillAndRulesRegistration

## God Nodes (most connected - your core abstractions)
1. `server` - 98 edges
2. `TaskDaemon` - 21 edges
3. `queryPostgresJson()` - 21 edges
4. `buildSessionPreamble()` - 20 edges
5. `redactSecretsInError()` - 19 edges
6. `createReactionActivityController()` - 16 edges
7. `handleWhatsappTtsRoute()` - 16 edges
8. `createKgStore()` - 15 edges
9. `normalizeIsraeliPhone()` - 14 edges
10. `sqlStr()` - 14 edges

## Surprising Connections (you probably didn't know these)
- `1. User Intent & Selected Architecture` --references--> `buildSessionPreamble()`  [INFERRED]
  docs/brainstorms/sparky-dynamic-model-routing-requirements.md → services/vertex-search-bridge/server.js
- `2. Verified Architectural Invariants & Test Alignment` --references--> `compactSessionChatHistory()`  [INFERRED]
  docs/brainstorms/sparky-dynamic-model-routing-requirements.md → services/vertex-search-bridge/config.js
- `DEF-04: Real-Time In-Turn Correction Learning (`"No, I meant..."`)` --references--> `detectCorrectionSignal()`  [INFERRED]
  docs/DEFERRED_AUTONOMOUS_LIFECYCLE_BACKLOG.md → services/vertex-search-bridge/correction-learner.js
- `DEF-04: Real-Time In-Turn Correction Learning (`"No, I meant..."`)` --references--> `extractAndSaveCorrection()`  [INFERRED]
  docs/DEFERRED_AUTONOMOUS_LIFECYCLE_BACKLOG.md → services/vertex-search-bridge/correction-learner.js
- `DEF-10: Bridge Monolith Decomposition (`server.js`), Native PG Pool & `BRIDGE_URL` Env` --references--> `checkNfs()`  [INFERRED]
  docs/DEFERRED_AUTONOMOUS_LIFECYCLE_BACKLOG.md → services/vertex-search-bridge/host-adapters.js

## Import Cycles
- None detected.

## Communities (86 total, 26 thin omitted)

### Community 0 - "server.js"
Cohesion: 0.04
Nodes (51): {
  ALLOWED_WORKSPACES,
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
}, config (+43 more)

### Community 1 - "reaction-commands.test.js"
Cohesion: 0.08
Nodes (13): AgyDriver, assert, BridgeCommandDriver, { EventEmitter }, fs, loadCorrectionLearner(), loadReactionCommands(), os (+5 more)

### Community 2 - "ref_fs"
Cohesion: 0.21
Nodes (13): bridgeRequest(), fs, getBridgeToken(), { bridgeRequest }, fs, isSafeHeartbeatPath(), path, readStdin() (+5 more)

### Community 3 - "model-router.js"
Cohesion: 0.12
Nodes (32): parseBareChoice(), buildStage2ClassifierPrompt(), CALLER_DEFAULT_ROUTES, { classifyDecisionChoice }, classifyStage1FastPath(), classifyStage2Semantic(), COGNITIVE_TIERS, createCarbonCircuitBreaker() (+24 more)

### Community 4 - "test_workspace_mutations.js"
Cohesion: 0.11
Nodes (18): APPEND_WF_PATH, cleanupRegistry, CREATE_DOC_WF_PATH, CREATE_SHEET_WF_PATH, CREATE_SLIDES_WF_PATH, { execSync, execFileSync }, EXPECTED_HEADERS, formatOutput() (+10 more)

### Community 5 - "TaskDaemon"
Cohesion: 0.07
Nodes (6): extract_stream_json_result(), read_heartbeat_meta(), resolve_timeouts(), sd_notify(), TaskDaemon, TestDaemon

### Community 6 - "Requirements Anchor: Sparky-AI Nightly Dreaming Knowledge Graph (`sparky-nightly-knowledge-graph`)"
Cohesion: 0.50
Nodes (3): 1. User Intent & Selected Architecture (1 + 3 Hybrid), 2. Core Invariants & Boundaries, Requirements Anchor: Sparky-AI Nightly Dreaming Knowledge Graph (`sparky-nightly-knowledge-graph`)

### Community 7 - "Semantic Vector Memory & Cortex Sleep Consolidation Architecture"
Cohesion: 0.11
Nodes (18): 1. Architectural Blueprint & Cognitive Model, 2. Infrastructure & Storage (`pgvector`), 3. Multilingual Embedding Pipeline, 4. Bridge Microservice Endpoints ([`server.js`](file:///root/vertex-search-bridge/server.js)), 5. Main Agent Integration (`search_memory` FunctionCall), 6. Nightly Cortex Sleep Consolidation (`POST /cortex/sleep-cycle`), 7.1 PostgreSQL Relational + Vector Graph Schema, 7.2 Nightly Single-Pass Extraction & Backfill (+10 more)

### Community 8 - "createReactionActivityController"
Cohesion: 0.18
Nodes (21): cloneConfig(), createReactionActivityController(), completeTurn(), dispatchEmojiNow(), getConfig(), getOrCreateState(), getStatus(), handleStageEvent() (+13 more)

### Community 9 - "test_graphify_integration.py"
Cohesion: 0.14
Nodes (5): _extract_source_files(), TestCodebaseInclusionInGraph, TestIncrementalUpdateIdempotency, TestPersonalMemoryGraphIsolation, TestStrictExclusionBoundary

### Community 10 - "1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4)"
Cohesion: 0.07
Nodes (33): 1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4), 2. Quality Gates, Observability & Disaster Recovery (Epic E3), 3. Platform Architecture & Refactoring (Epic E5), DEF-01: Global Attention Budget & Quiet Hours Hold Queue (`23:00–07:00`), DEF-02: Nudge-Effectiveness Telemetry & Sentinel Self-Tuning, DEF-03: Sunday Weekly Review & Overdue Loop Escalation Ladder, DEF-06: Auto-Incident Knowledge Base (`knowledge-base.json`) Draft Capture, DEF-07: Golden Evaluation Dataset Expansion (`3/45` → Core Tools) & Change Gate (+25 more)

### Community 11 - "correction-learner.js"
Cohesion: 0.06
Nodes (49): RFC-2822, DEF-04: Real-Time In-Turn Correction Learning (`"No, I meant..."`), containsSecretOrPassword(), createCorrectionLearner(), extractAndSaveCorrection(), detectCorrectionSignal(), findDuplicateFieldNote(), redactAllSecrets() (+41 more)

### Community 12 - "Sentinel Actor Model & Conversational Handshake Architecture"
Cohesion: 0.20
Nodes (9): 1. Executive Summary, 2. Dual-Channel XML Sensory Pipeline, 3. Active Conversational Handshake & Latency Masking, 4. Active Workflow Catalog (11 Total), 5. Central Egress Hub (`/whatsapp/dispatch`), Sentinel Actor Model & Conversational Handshake Architecture, The Problem, The Solution (+1 more)

### Community 13 - "The Four Cynefin Domains in Sparky"
Cohesion: 0.22
Nodes (8): 1. Clear / Simple Domain (Known Knowns), 2. Complicated Domain (Known Unknowns), 3. Complex Domain (Unknown Unknowns), 4. Chaotic Domain (Unknowables / Crises), 5. Aporia / Confusion, Architectural Overview, Cynefin + OODA Loop Cognitive Framework, The Four Cynefin Domains in Sparky

### Community 14 - "Sparky-Plex: Autonomous Executive Assistant & Infrastructure"
Cohesion: 0.22
Nodes (8): Automated Backup, 🔄 Automated Backup & Disaster Recovery, Full Disaster Recovery, 🛠️ Microservice Bridge (Port 5055), 📁 Repository Structure, 🔒 Security & Privacy Notice, Sparky-Plex: Autonomous Executive Assistant & Infrastructure, 🏛️ System Architecture

### Community 15 - "family-relay.test.js"
Cohesion: 0.14
Nodes (17): assert, BACKUP_FILE, { buildCanonicalLoopKey, generateDeterministicLoopId }, clone(), createFakeWorld(), mergeJsonbLiteral(), queryPostgresJson(), queryPostgresWithStdin() (+9 more)

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
Cohesion: 0.14
Nodes (10): assert, { createMcpHttpServer }, crypto, fs, RFC-7591, os, path, { spawn, execFileSync, execFile } (+2 more)

### Community 26 - "scripts/test-n8n-patches.js"
Cohesion: 0.10
Nodes (18): { cleanupOrphanedMessages }, { ensureParams, failedAttemptHandler }, entries, failedHandlerPath, fs, geminiCjsPath, geminiMessages, geminiMessagesPath (+10 more)

### Community 27 - "readStreamUtf8"
Cohesion: 0.22
Nodes (13): readStreamUtf8(), callGoogleRoutesApi(), callOsrmFallback(), callVertexFastJson(), sendOnce(), computeCommute(), fetchMetaMedia(), getAccessToken() (+5 more)

### Community 29 - "memory-hygiene.js"
Cohesion: 0.13
Nodes (29): DEF-05: Semantic Memory Contradiction Detection & Temporal Decay, computeRecencyBoost(), createMemoryHygieneStore(), findCandidateNeighbors(), ingestMemoryWithHygiene(), reconcileExistingMemories(), EPISODIC_TYPES, extractSearchTokens() (+21 more)

### Community 30 - "db-adapter.test.js"
Cohesion: 0.13
Nodes (10): assert, DB_PATH, fs, path, test, assert, EGRESS_PATH, fs (+2 more)

### Community 33 - "restore.sh"
Cohesion: 0.47
Nodes (5): HOME, PATH, restore.sh script, sync_published_versions_sql(), verify_and_extract_secrets()

### Community 35 - "nudge-telemetry.js"
Cohesion: 0.16
Nodes (21): classifyDecisionChoice(), computeSenderAdjustment(), createNudgeTelemetryStore(), getEffectivenessReport(), getSenderFeedback(), extractSenderKey(), formatTriageFeedbackXml(), inferDecisionSource() (+13 more)

### Community 36 - "reaction-commands.js"
Cohesion: 0.06
Nodes (62): ALLOWED_WORKSPACES, buildAgyTaskPayload(), buildFencedMissionPrompt(), dispatchAgyMissionToDrive(), fetchAgyAccessToken(), fs, loadAgyDaemonConfig(), { redactSecretsInError } (+54 more)

### Community 37 - "heartbeat-store.js"
Cohesion: 0.17
Nodes (15): createHeartbeatStore(), flushSentinel(), listHeartbeats(), recordHeartbeat(), evaluateStaleness(), lookupEntry(), SENTINEL_REGISTRY, sqlStr() (+7 more)

### Community 38 - "quiet-hours.test.js"
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

### Community 39 - "host-adapters.test.js"
Cohesion: 0.17
Nodes (7): assert, fs, HOST_ADAPTERS_PATH, http, net, path, test

### Community 40 - "n8n-sparky/test-n8n-patches.js"
Cohesion: 0.11
Nodes (18): { cleanupOrphanedMessages }, { ensureParams, failedAttemptHandler }, entries, failedHandlerPath, fs, geminiCjsPath, geminiMessages, geminiMessagesPath (+10 more)

### Community 41 - "lifecycle.test.js"
Cohesion: 0.15
Nodes (9): assert, CONFIG_PATH, { execFileSync }, fs, os, path, SERVER_PATH, test (+1 more)

### Community 42 - "config.test.js"
Cohesion: 0.22
Nodes (6): assert, CONFIG_PATH, fs, os, path, test

### Community 43 - "phase2c-ops.test.js"
Cohesion: 0.25
Nodes (7): assert, { execFileSync }, fs, path, PATHS, readOrSkip(), test

### Community 44 - "ref_path"
Cohesion: 0.13
Nodes (15): { execFileSync }, fs, main(), migrateJsCode(), migrateNodes(), migrateUrlParam(), path, runPsql() (+7 more)

### Community 45 - "family-relay.js"
Cohesion: 0.06
Nodes (70): classifyFamilyInboundText(), createFamilyRelayService(), configureFamilyMember(), handleFamilyInbound(), loadCtx(), loadFamilyLoops(), processFamilyInbound(), recordChatHistory() (+62 more)

### Community 47 - "index.js"
Cohesion: 0.23
Nodes (10): processJsonRpcMessage(), { bridgeRequest }, dispatchAgyMissionToDrive(), fs, handleToolCall(), readHeartbeatMeta(), readline, sendJsonRpc() (+2 more)

### Community 48 - "server"
Cohesion: 0.16
Nodes (22): normalizeReactionEmoji(), checkAndDispatchDueReminders(), effectiveDue(), fetchBufferFromUrl(), handleAgyMissionRoute(), handleReactionExecuteRoute(), handleWhatsappTtsRoute(), isDateOnlyAutoShipmentLoop() (+14 more)

### Community 50 - "buildSessionPreamble"
Cohesion: 0.17
Nodes (21): buildSessionPreamble(), getJerusalemOffsetString(), getSentinelEvent(), getSystemAudit(), isFamilyConciergeLoop(), isTestLoop(), loadActivityStream(), loadAgyAttention() (+13 more)

### Community 51 - "reactionCommandService"
Cohesion: 0.27
Nodes (15): checkAndDispatchWindowKeepalive(), familyRelay, getWindowState(), invalidateWindowStateCache(), logActivityEvent(), postMetaMediaOnce(), queryPostgresWithStdin(), recipientMatchSql() (+7 more)

### Community 52 - "publish-graph.sh"
Cohesion: 0.50
Nodes (3): HOME, PATH, publish-graph.sh script

### Community 53 - "config.js"
Cohesion: 0.14
Nodes (8): compactSessionChatHistory(), compactToolObservationContent(), createMetaTokenReader(), crypto, defaultConfig, fs, normalizeHistoryRow(), path

### Community 54 - "decision-helpers.js"
Cohesion: 0.22
Nodes (7): extractInteractiveOptions(), getDecisionSourceAliases(), INTERACTIVE_SENTINEL_SOURCES, NON_DECISION_SOURCES, SOURCE_ALIAS_GROUPS, createDecision(), loadDecisions()

### Community 56 - "callVertexApiWithRetry"
Cohesion: 0.18
Nodes (13): analyzeImageBuffer(), callGeminiJson(), callVertexApiWithRetry(), generateEmbedding(), getCircuitBreaker(), insertSemanticMemory(), kgStore, memoryHygieneStore (+5 more)

### Community 57 - "ref_child_process"
Cohesion: 0.23
Nodes (10): createDb(), getOrInitPgPool(), queryPostgresJson(), queryPostgresScript(), queryPostgresWithStdin(), { execFile }, formatPgCell(), formatPgResultAsPsql() (+2 more)

### Community 58 - "server-endpoints.test.js"
Cohesion: 0.12
Nodes (9): REACTION_COMMAND_MAP, assert, cleanupReactionDeckTestRows(), { execFile }, execPsqlStrict(), FAMILY_CONTEXT_FILES, fs, test (+1 more)

### Community 59 - "vertex-search-bridge/package.json"
Cohesion: 0.18
Nodes (10): pg, dependencies, pg, description, engines, node, main, name (+2 more)

### Community 60 - "ref_node_test"
Cohesion: 0.20
Nodes (6): assert, { createHandoffStore, formatHandoffsXml }, { describe, it }, assert, { createLoopStore }, test

### Community 62 - "Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`)"
Cohesion: 0.33
Nodes (5): Emergency Sub-Minute Rollback to Host `systemd` (`vertex-search.service`), Overview, Returning from Host `systemd` to Container (`vertex-bridge`), Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`), Standard Deployment & Digest Rollback (`deploy-bridge.sh`)

### Community 64 - "probe-db-parity.js"
Cohesion: 0.29
Nodes (6): resolveConfig(), assert, config, { createDb }, main(), QUERIES

### Community 65 - "run-agent-eval.sh"
Cohesion: 0.50
Nodes (3): HOME, PATH, run-agent-eval.sh script

### Community 71 - "atomicWriteJson"
Cohesion: 0.33
Nodes (6): atomicWriteJson(), loadBriefedMeetings(), markBriefedMeeting(), resolveDecision(), saveDecisions(), saveFieldNotes()

### Community 78 - "Requirements Anchor: Sparky-AI Dynamic Main Agent Model & Effort Routing"
Cohesion: 0.50
Nodes (3): 1. User Intent & Selected Architecture, 2. Verified Architectural Invariants & Test Alignment, Requirements Anchor: Sparky-AI Dynamic Main Agent Model & Effort Routing

### Community 82 - "loop-store.integration.test.js"
Cohesion: 0.32
Nodes (7): assert, { createLoopStore }, { execFile }, queryPostgresJson(), queryPostgresWithStdin(), store, test

### Community 83 - "scripts"
Cohesion: 0.50
Nodes (4): scripts, start, test, test:ci

## Knowledge Gaps
- **20 isolated node(s):** `PATH`, `PATH`, `HOME`, `REGISTRY_AUTH_FILE`, `PATH` (+15 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 559 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **26 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `createReactionActivityController()` connect `createReactionActivityController` to `server.js`?**
  _High betweenness centrality (0.031) - this node is a cross-community bridge._
- **What connects `PATH`, `PATH`, `HOME` to the rest of the system?**
  _20 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `server.js` be split into smaller, more focused modules?**
  _Cohesion score 0.037037037037037035 - nodes in this community are weakly interconnected._
- **Why does `createDb()` connect `ref_child_process` to `probe-db-parity.js`, `server.js`?**
  _High betweenness centrality (0.030) - this node is a cross-community bridge._
- **Should `reaction-commands.test.js` be split into smaller, more focused modules?**
  _Cohesion score 0.07956989247311828 - nodes in this community are weakly interconnected._
- **Why does `createHandoffStore()` connect `correction-learner.js` to `server.js`?**
  _High betweenness centrality (0.019) - this node is a cross-community bridge._
- **Should `model-router.js` be split into smaller, more focused modules?**
  _Cohesion score 0.12477718360071301 - nodes in this community are weakly interconnected._