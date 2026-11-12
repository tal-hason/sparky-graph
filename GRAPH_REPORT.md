# Graph Report - sparky-backup  (2026-11-12)

## Corpus Check
- 94 files · ~162,104 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 12 file(s) not represented in the graph (top: (none) 5, .service 5, .example 1)

## Summary
- 1164 nodes · 2024 edges · 75 communities (52 shown, 23 thin omitted)
- Extraction: 89% EXTRACTED · 11% INFERRED · 0% AMBIGUOUS · INFERRED: 230 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `46e19acd`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- server.js
- family-relay.test.js
- ref_fs
- model-router.js
- test_workspace_mutations.js
- daemon.py
- Requirements Anchor: Sparky-AI Nightly Dreaming Knowledge Graph (`sparky-nightly-knowledge-graph`)
- Semantic Vector Memory & Cortex Sleep Consolidation Architecture
- createReactionActivityController
- test_graphify_integration.py
- 1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4)
- loop-store.integration.test.js
- Sentinel Actor Model & Conversational Handshake Architecture
- The Four Cynefin Domains in Sparky
- Sparky-Plex: Autonomous Executive Assistant & Infrastructure
- test_graphify_integration.py
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
- correction-learner.js
- probe-incident-signatures.js
- heartbeat-store.js
- quiet-hours.test.js
- host-adapters.test.js
- TestGoldenDatasetPresence
- lifecycle.test.js
- config.test.js
- phase2c-ops.test.js
- ref_path
- migrate-loop-keys.js
- TestAntigravitySkillAndRulesRegistration
- index.js
- server
- patch-n8n-memory-orphans.sh
- TestGraphifyCLIBinary
- checkAndDispatchWindowKeepalive
- publish-graph.sh
- config.js
- ref_node_assert
- callVertexApiWithRetry
- atomicWriteJson
- server-endpoints.test.js
- vertex-search-bridge/package.json
- ref_node_test
- TestEvaluationHarnessWorkflow
- Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`)
- run-agent-eval.sh
- TestEvaluationSafetyGuard
- sync-services-to-repo.sh
- n8n-stack/scripts/deploy-bridge.sh
- eval-history.md
- TestEopSkillAndBackupScriptContract
- Requirements Anchor: `[Sparky-AI]` Event-Driven Email Handoff to Gemini App
- n8n-sparky/patch-gemini4-langchain.sh
- n8n-sparky/patch-n8n-memory-orphans.sh
- TestWorkflowTelemetry
- scripts/patch-retry-backoff.sh
- n8n-sparky/patch-retry-backoff.sh
- TestDynamicModelRoutingCallers

## God Nodes (most connected - your core abstractions)
1. `server` - 81 edges
2. `TaskDaemon` - 21 edges
3. `queryPostgresJson()` - 20 edges
4. `buildSessionPreamble()` - 17 edges
5. `createReactionActivityController()` - 15 edges
6. `createKgStore()` - 14 edges
7. `upsertKgEntity()` - 13 edges
8. `createModelRouter()` - 13 edges
9. `queryPostgresWithStdin()` - 12 edges
10. `stripBidi()` - 12 edges

## Surprising Connections (you probably didn't know these)
- `1. User Intent & Selected Architecture` --references--> `buildSessionPreamble()`  [INFERRED]
  docs/brainstorms/sparky-dynamic-model-routing-requirements.md → services/vertex-search-bridge/server.js
- `DEF-10: Bridge Monolith Decomposition (`server.js`), Native PG Pool & `BRIDGE_URL` Env` --references--> `checkNfs()`  [INFERRED]
  docs/DEFERRED_AUTONOMOUS_LIFECYCLE_BACKLOG.md → services/vertex-search-bridge/host-adapters.js
- `DEF-10: Bridge Monolith Decomposition (`server.js`), Native PG Pool & `BRIDGE_URL` Env` --references--> `runDatabaseMaintenance()`  [INFERRED]
  docs/DEFERRED_AUTONOMOUS_LIFECYCLE_BACKLOG.md → services/vertex-search-bridge/host-adapters.js
- `DEF-05: Semantic Memory Contradiction Detection & Temporal Decay` --references--> `ingestMemoryWithHygiene()`  [INFERRED]
  docs/DEFERRED_AUTONOMOUS_LIFECYCLE_BACKLOG.md → services/vertex-search-bridge/memory-hygiene.js
- `DEF-05: Semantic Memory Contradiction Detection & Temporal Decay` --references--> `hasFactMutationTokens()`  [INFERRED]
  docs/DEFERRED_AUTONOMOUS_LIFECYCLE_BACKLOG.md → services/vertex-search-bridge/memory-hygiene.js

## Import Cycles
- None detected.

## Communities (75 total, 23 thin omitted)

### Community 0 - "server.js"
Cohesion: 0.02
Nodes (46): BRIDGE_API_TOKEN, BRIDGE_STARTED_AT, circuitBreakers, {
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
}, config, {
  containsSecretOrPassword,
  redactAllSecrets,
  stripChatWrapper,
  detectCorrectionSignal,
  findDuplicateFieldNote,
  createCorrectionLearner,
} (+38 more)

### Community 1 - "family-relay.test.js"
Cohesion: 0.10
Nodes (21): extractInteractiveOptions(), INTERACTIVE_SENTINEL_SOURCES, NON_DECISION_SOURCES, SOURCE_ALIAS_GROUPS, assert, BACKUP_FILE, { buildCanonicalLoopKey, generateDeterministicLoopId }, clone() (+13 more)

### Community 2 - "ref_fs"
Cohesion: 0.20
Nodes (13): bridgeRequest(), fs, getBridgeToken(), { bridgeRequest }, fs, isSafeHeartbeatPath(), path, readStdin() (+5 more)

### Community 3 - "model-router.js"
Cohesion: 0.12
Nodes (32): parseBareChoice(), buildStage2ClassifierPrompt(), CALLER_DEFAULT_ROUTES, { classifyDecisionChoice }, classifyStage1FastPath(), classifyStage2Semantic(), COGNITIVE_TIERS, createCarbonCircuitBreaker() (+24 more)

### Community 4 - "test_workspace_mutations.js"
Cohesion: 0.11
Nodes (18): APPEND_WF_PATH, cleanupRegistry, CREATE_DOC_WF_PATH, CREATE_SHEET_WF_PATH, CREATE_SLIDES_WF_PATH, { execSync, execFileSync }, EXPECTED_HEADERS, formatOutput() (+10 more)

### Community 5 - "daemon.py"
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
Cohesion: 0.08
Nodes (28): 2. Quality Gates, Observability & Disaster Recovery (Epic E3), 3. Platform Architecture & Refactoring (Epic E5), DEF-06: Auto-Incident Knowledge Base (`knowledge-base.json`) Draft Capture, DEF-07: Golden Evaluation Dataset Expansion (`3/45` → Core Tools) & Change Gate, DEF-08: Daily Sentinel Heartbeat SLO Monitor, DEF-09: Turnkey Bare-Metal DR Playbook & Encrypted Credential Bootstrap (`restore.sh`), DEF-10: Bridge Monolith Decomposition (`server.js`), Native PG Pool & `BRIDGE_URL` Env, DEF-11: Meta WhatsApp Delivery & Read Receipt Tracking (+20 more)

### Community 11 - "loop-store.integration.test.js"
Cohesion: 0.32
Nodes (7): assert, { createLoopStore }, { execFile }, queryPostgresJson(), queryPostgresWithStdin(), store, test

### Community 12 - "Sentinel Actor Model & Conversational Handshake Architecture"
Cohesion: 0.20
Nodes (9): 1. Executive Summary, 2. Dual-Channel XML Sensory Pipeline, 3. Active Conversational Handshake & Latency Masking, 4. Active Workflow Catalog (11 Total), 5. Central Egress Hub (`/whatsapp/dispatch`), Sentinel Actor Model & Conversational Handshake Architecture, The Problem, The Solution (+1 more)

### Community 13 - "The Four Cynefin Domains in Sparky"
Cohesion: 0.22
Nodes (8): 1. Clear / Simple Domain (Known Knowns), 2. Complicated Domain (Known Unknowns), 3. Complex Domain (Unknown Unknowns), 4. Chaotic Domain (Unknowables / Crises), 5. Aporia / Confusion, Architectural Overview, Cynefin + OODA Loop Cognitive Framework, The Four Cynefin Domains in Sparky

### Community 14 - "Sparky-Plex: Autonomous Executive Assistant & Infrastructure"
Cohesion: 0.22
Nodes (8): Automated Backup, 🔄 Automated Backup & Disaster Recovery, Full Disaster Recovery, 🛠️ Microservice Bridge (Port 5055), 📁 Repository Structure, 🔒 Security & Privacy Notice, Sparky-Plex: Autonomous Executive Assistant & Infrastructure, 🏛️ System Architecture

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
Cohesion: 0.04
Nodes (40): assert, { cleanupOrphanedMessages }, { ensureParams }, entries, failedHandlerPath, fs, geminiCjsPath, geminiMessages (+32 more)

### Community 27 - "readStreamUtf8"
Cohesion: 0.18
Nodes (16): readStreamUtf8(), callGoogleRoutesApi(), callOsrmFallback(), callVertexFastJson(), sendOnce(), computeCommute(), fetchMetaMedia(), getAccessToken() (+8 more)

### Community 29 - "memory-hygiene.js"
Cohesion: 0.13
Nodes (29): DEF-05: Semantic Memory Contradiction Detection & Temporal Decay, computeRecencyBoost(), createMemoryHygieneStore(), findCandidateNeighbors(), ingestMemoryWithHygiene(), reconcileExistingMemories(), EPISODIC_TYPES, extractSearchTokens() (+21 more)

### Community 30 - "db-adapter.test.js"
Cohesion: 0.13
Nodes (10): assert, DB_PATH, fs, path, test, assert, EGRESS_PATH, fs (+2 more)

### Community 33 - "restore.sh"
Cohesion: 0.47
Nodes (5): HOME, PATH, restore.sh script, sync_published_versions_sql(), verify_and_extract_secrets()

### Community 35 - "correction-learner.js"
Cohesion: 0.09
Nodes (37): 1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4), DEF-01: Global Attention Budget & Quiet Hours Hold Queue (`23:00–07:00`), DEF-02: Nudge-Effectiveness Telemetry & Sentinel Self-Tuning, DEF-03: Sunday Weekly Review & Overdue Loop Escalation Ladder, DEF-04: Real-Time In-Turn Correction Learning (`"No, I meant..."`), DEF-12: `agy-daemon` Failed Mission Re-Surfacing & Retry Digest, containsSecretOrPassword(), createCorrectionLearner() (+29 more)

### Community 36 - "probe-incident-signatures.js"
Cohesion: 0.08
Nodes (38): pg, resolveConfig(), createDb(), getOrInitPgPool(), queryPostgresJson(), queryPostgresScript(), queryPostgresWithStdin(), { execFile } (+30 more)

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

### Community 41 - "lifecycle.test.js"
Cohesion: 0.17
Nodes (9): assert, CONFIG_PATH, { execFileSync }, fs, os, path, SERVER_PATH, test (+1 more)

### Community 42 - "config.test.js"
Cohesion: 0.22
Nodes (6): assert, CONFIG_PATH, fs, os, path, test

### Community 43 - "phase2c-ops.test.js"
Cohesion: 0.25
Nodes (7): assert, { execFileSync }, fs, path, PATHS, readOrSkip(), test

### Community 44 - "ref_path"
Cohesion: 0.25
Nodes (9): { execFileSync }, fs, main(), migrateJsCode(), migrateNodes(), migrateUrlParam(), path, runPsql() (+1 more)

### Community 45 - "migrate-loop-keys.js"
Cohesion: 0.06
Nodes (65): classifyFamilyInboundText(), createFamilyRelayService(), configureFamilyMember(), handleFamilyInbound(), loadCtx(), loadFamilyLoops(), processFamilyInbound(), recordChatHistory() (+57 more)

### Community 47 - "index.js"
Cohesion: 0.23
Nodes (10): processJsonRpcMessage(), { bridgeRequest }, dispatchAgyMissionToDrive(), fs, handleToolCall(), readHeartbeatMeta(), readline, sendJsonRpc() (+2 more)

### Community 48 - "server"
Cohesion: 0.14
Nodes (32): getDecisionSourceAliases(), buildSessionPreamble(), checkAndDispatchDueReminders(), createDecision(), effectiveDue(), fetchBufferFromUrl(), getJerusalemOffsetString(), getSentinelEvent() (+24 more)

### Community 51 - "checkAndDispatchWindowKeepalive"
Cohesion: 0.47
Nodes (9): checkAndDispatchWindowKeepalive(), familyRelay, getWindowState(), invalidateWindowStateCache(), recipientMatchSql(), replayHeldWindowMessages(), safeWindowRecipient(), sendWhatsAppDirect() (+1 more)

### Community 52 - "publish-graph.sh"
Cohesion: 0.50
Nodes (3): HOME, PATH, publish-graph.sh script

### Community 53 - "config.js"
Cohesion: 0.11
Nodes (11): 1. User Intent & Selected Architecture, 2. Verified Architectural Invariants & Test Alignment, Requirements Anchor: Sparky-AI Dynamic Main Agent Model & Effort Routing, compactSessionChatHistory(), compactToolObservationContent(), createMetaTokenReader(), crypto, defaultConfig (+3 more)

### Community 54 - "ref_node_assert"
Cohesion: 0.09
Nodes (34): RFC-2822, findDuplicateFieldNote(), classifyDecisionChoice(), computeSenderAdjustment(), createNudgeTelemetryStore(), getEffectivenessReport(), getSenderFeedback(), extractSenderKey() (+26 more)

### Community 55 - "callVertexApiWithRetry"
Cohesion: 0.18
Nodes (13): analyzeImageBuffer(), callGeminiJson(), callVertexApiWithRetry(), generateEmbedding(), getCircuitBreaker(), insertSemanticMemory(), kgStore, memoryHygieneStore (+5 more)

### Community 56 - "atomicWriteJson"
Cohesion: 0.22
Nodes (10): atomicWriteJson(), loadBriefedMeetings(), loopStore, markBriefedMeeting(), queryPostgresWithStdin(), saveContext(), saveDecisions(), saveFieldNotes() (+2 more)

### Community 58 - "server-endpoints.test.js"
Cohesion: 0.18
Nodes (6): assert, { execFile }, FAMILY_CONTEXT_FILES, fs, test, TOKEN

### Community 59 - "vertex-search-bridge/package.json"
Cohesion: 0.14
Nodes (13): dependencies, pg, description, engines, node, main, name, private (+5 more)

### Community 60 - "ref_node_test"
Cohesion: 0.20
Nodes (6): assert, { createHandoffStore, formatHandoffsXml }, { describe, it }, assert, { createHandoffStore, formatHandoffsXml }, { describe, it }

### Community 62 - "Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`)"
Cohesion: 0.33
Nodes (5): Emergency Sub-Minute Rollback to Host `systemd` (`vertex-search.service`), Overview, Returning from Host `systemd` to Container (`vertex-bridge`), Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`), Standard Deployment & Digest Rollback (`deploy-bridge.sh`)

### Community 65 - "run-agent-eval.sh"
Cohesion: 0.50
Nodes (3): HOME, PATH, run-agent-eval.sh script

## Knowledge Gaps
- **20 isolated node(s):** `RFC-8414`, `RFC-9728`, `RFC-7591`, `PATH`, `HOME` (+15 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 568 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **23 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `server` connect `server` to `server.js`, `family-relay.test.js`, `correction-learner.js`, `model-router.js`, `quiet-hours.test.js`, `migrate-loop-keys.js`, `checkAndDispatchWindowKeepalive`, `ref_node_assert`, `callVertexApiWithRetry`, `atomicWriteJson`, `readStreamUtf8`, `memory-hygiene.js`?**
  _High betweenness centrality (0.027) - this node is a cross-community bridge._
- **What connects `RFC-8414`, `RFC-9728`, `RFC-7591` to the rest of the system?**
  _20 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `server.js` be split into smaller, more focused modules?**
  _Cohesion score 0.019801980198019802 - nodes in this community are weakly interconnected._
- **Why does `1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4)` connect `correction-learner.js` to `1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4)`, `memory-hygiene.js`?**
  _High betweenness centrality (0.017) - this node is a cross-community bridge._
- **Should `family-relay.test.js` be split into smaller, more focused modules?**
  _Cohesion score 0.09971509971509972 - nodes in this community are weakly interconnected._
- **Why does `DEF-05: Semantic Memory Contradiction Detection & Temporal Decay` connect `memory-hygiene.js` to `correction-learner.js`?**
  _High betweenness centrality (0.012) - this node is a cross-community bridge._
- **Should `model-router.js` be split into smaller, more focused modules?**
  _Cohesion score 0.12299465240641712 - nodes in this community are weakly interconnected._