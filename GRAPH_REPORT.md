# Graph Report - sparky-backup  (2026-10-28)

## Corpus Check
- 80 files · ~119,100 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 11 file(s) not represented in the graph (top: (none) 5, .service 4, .example 1)

## Summary
- 878 nodes · 1525 edges · 70 communities (49 shown, 21 thin omitted)
- Extraction: 89% EXTRACTED · 11% INFERRED · 0% AMBIGUOUS · INFERRED: 161 edges (avg confidence: 0.86)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `6abe2a49`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- server.js
- decision-helpers.js
- ref_fs
- TestWorkflowTelemetry
- test_workspace_mutations.js
- nudge-telemetry.js
- Requirements Anchor: Sparky-AI Nightly Dreaming Knowledge Graph (`sparky-nightly-knowledge-graph`)
- Semantic Vector Memory & Cortex Sleep Consolidation Architecture
- TestGoldenDatasetPresence
- test_graphify_integration.py
- 1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4)
- ref_child_process
- Sentinel Actor Model & Conversational Handshake Architecture
- The Four Cynefin Domains in Sparky
- Sparky-Plex: Autonomous Executive Assistant & Infrastructure
- TestEvaluationHarnessWorkflow
- kg-store.js
- sparky-mcp/package.json
- n8n-sparky/test-n8n-patches.js
- sparky-watchdog.sh
- n8n Stack Configuration & Deployment
- postgres-maintenance.sh
- update-n8n.sh
- backup.sh
- render-local-kg-html.sh
- daemon.py
- test-n8n-patches.js
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
- whatsapp-egress.test.js
- lifecycle.test.js
- config.test.js
- phase2c-ops.test.js
- TestEopSkillAndBackupScriptContract
- migrate-loop-keys.js
- TaskDaemon
- ref_path
- server
- patch-n8n-memory-orphans.sh
- TestDaemon
- TestEvaluationSafetyGuard
- publish-graph.sh
- config.js
- mcp.test.js
- callVertexApiWithRetry
- index.js
- ref_node_assert
- server-endpoints.test.js
- ref_node_test
- TestAntigravitySkillAndRulesRegistration
- TestGraphifyCLIBinary
- Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`)
- queryPostgresWithStdin
- run-agent-eval.sh
- sync-services-to-repo.sh
- n8n-stack/scripts/deploy-bridge.sh
- eval-history.md
- n8n-sparky/patch-gemini4-langchain.sh
- n8n-sparky/patch-n8n-memory-orphans.sh

## God Nodes (most connected - your core abstractions)
1. `server` - 65 edges
2. `TaskDaemon` - 21 edges
3. `queryPostgresJson()` - 17 edges
4. `buildSessionPreamble()` - 16 edges
5. `createKgStore()` - 15 edges
6. `upsertKgEntity()` - 13 edges
7. `stripBidi()` - 12 edges
8. `callVertexApiWithRetry()` - 11 edges
9. `TestDaemon` - 10 edges
10. `resolveTables()` - 10 edges

## Surprising Connections (you probably didn't know these)
- `DEF-04: Real-Time In-Turn Correction Learning (`"No, I meant..."`)` --references--> `detectCorrectionSignal()`  [INFERRED]
  docs/DEFERRED_AUTONOMOUS_LIFECYCLE_BACKLOG.md → services/vertex-search-bridge/correction-learner.js
- `DEF-04: Real-Time In-Turn Correction Learning (`"No, I meant..."`)` --references--> `extractAndSaveCorrection()`  [INFERRED]
  docs/DEFERRED_AUTONOMOUS_LIFECYCLE_BACKLOG.md → services/vertex-search-bridge/correction-learner.js
- `DEF-10: Bridge Monolith Decomposition (`server.js`), Native PG Pool & `BRIDGE_URL` Env` --references--> `checkNfs()`  [INFERRED]
  docs/DEFERRED_AUTONOMOUS_LIFECYCLE_BACKLOG.md → services/vertex-search-bridge/host-adapters.js
- `DEF-10: Bridge Monolith Decomposition (`server.js`), Native PG Pool & `BRIDGE_URL` Env` --references--> `runDatabaseMaintenance()`  [INFERRED]
  docs/DEFERRED_AUTONOMOUS_LIFECYCLE_BACKLOG.md → services/vertex-search-bridge/host-adapters.js
- `DEF-05: Semantic Memory Contradiction Detection & Temporal Decay` --references--> `rankMemoriesWithDecay()`  [INFERRED]
  docs/DEFERRED_AUTONOMOUS_LIFECYCLE_BACKLOG.md → services/vertex-search-bridge/memory-hygiene.js

## Import Cycles
- None detected.

## Communities (70 total, 21 thin omitted)

### Community 0 - "server.js"
Cohesion: 0.05
Nodes (37): BRIDGE_API_TOKEN, BRIDGE_STARTED_AT, circuitBreakers, {
  classifyDecisionChoice,
  inferDecisionSource,
  extractSenderKey,
  computeSenderAdjustment,
  formatTriageFeedbackXml,
  createNudgeTelemetryStore,
}, {
  computeRecencyBoost,
  rankMemoriesWithDecay,
  hasFactMutationTokens,
  mergeContextNotes,
  createMemoryHygieneStore,
}, config, {
  containsSecretOrPassword,
  redactAllSecrets,
  stripChatWrapper,
  detectCorrectionSignal,
  findDuplicateFieldNote,
  createCorrectionLearner,
}, correctionLearner (+29 more)

### Community 1 - "decision-helpers.js"
Cohesion: 0.20
Nodes (8): extractInteractiveOptions(), getDecisionSourceAliases(), INTERACTIVE_SENTINEL_SOURCES, NON_DECISION_SOURCES, parseBareChoice(), SOURCE_ALIAS_GROUPS, createDecision(), loadDecisions()

### Community 2 - "ref_fs"
Cohesion: 0.20
Nodes (13): bridgeRequest(), fs, getBridgeToken(), { bridgeRequest }, fs, isSafeHeartbeatPath(), path, readStdin() (+5 more)

### Community 4 - "test_workspace_mutations.js"
Cohesion: 0.11
Nodes (18): APPEND_WF_PATH, cleanupRegistry, CREATE_DOC_WF_PATH, CREATE_SHEET_WF_PATH, CREATE_SLIDES_WF_PATH, { execSync, execFileSync }, EXPECTED_HEADERS, formatOutput() (+10 more)

### Community 5 - "nudge-telemetry.js"
Cohesion: 0.16
Nodes (20): classifyDecisionChoice(), computeSenderAdjustment(), createNudgeTelemetryStore(), getEffectivenessReport(), getSenderFeedback(), extractSenderKey(), formatTriageFeedbackXml(), inferDecisionSource() (+12 more)

### Community 6 - "Requirements Anchor: Sparky-AI Nightly Dreaming Knowledge Graph (`sparky-nightly-knowledge-graph`)"
Cohesion: 0.50
Nodes (3): 1. User Intent & Selected Architecture (1 + 3 Hybrid), 2. Core Invariants & Boundaries, Requirements Anchor: Sparky-AI Nightly Dreaming Knowledge Graph (`sparky-nightly-knowledge-graph`)

### Community 7 - "Semantic Vector Memory & Cortex Sleep Consolidation Architecture"
Cohesion: 0.11
Nodes (18): 1. Architectural Blueprint & Cognitive Model, 2. Infrastructure & Storage (`pgvector`), 3. Multilingual Embedding Pipeline, 4. Bridge Microservice Endpoints ([`server.js`](file:///root/vertex-search-bridge/server.js)), 5. Main Agent Integration (`search_memory` FunctionCall), 6. Nightly Cortex Sleep Consolidation (`POST /cortex/sleep-cycle`), 7.1 PostgreSQL Relational + Vector Graph Schema, 7.2 Nightly Single-Pass Extraction & Backfill (+10 more)

### Community 9 - "test_graphify_integration.py"
Cohesion: 0.13
Nodes (6): _extract_source_files(), TestCodebaseInclusionInGraph, TestDeterministicCLIGraphQuery, TestIncrementalUpdateIdempotency, TestPersonalMemoryGraphIsolation, TestStrictExclusionBoundary

### Community 10 - "1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4)"
Cohesion: 0.07
Nodes (33): 1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4), 2. Quality Gates, Observability & Disaster Recovery (Epic E3), 3. Platform Architecture & Refactoring (Epic E5), DEF-01: Global Attention Budget & Quiet Hours Hold Queue (`23:00–07:00`), DEF-02: Nudge-Effectiveness Telemetry & Sentinel Self-Tuning, DEF-03: Sunday Weekly Review & Overdue Loop Escalation Ladder, DEF-06: Auto-Incident Knowledge Base (`knowledge-base.json`) Draft Capture, DEF-07: Golden Evaluation Dataset Expansion (`3/45` → Core Tools) & Change Gate (+25 more)

### Community 11 - "ref_child_process"
Cohesion: 0.09
Nodes (24): pg, createDb(), getOrInitPgPool(), queryPostgresJson(), queryPostgresScript(), queryPostgresWithStdin(), { execFile }, formatPgCell() (+16 more)

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

### Community 18 - "n8n-sparky/test-n8n-patches.js"
Cohesion: 0.13
Nodes (15): assert, { cleanupOrphanedMessages }, entries, fs, geminiCjsPath, geminiMessages, geminiMessagesPath, { getGeminiAPI } (+7 more)

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

### Community 26 - "test-n8n-patches.js"
Cohesion: 0.12
Nodes (15): assert, { cleanupOrphanedMessages }, entries, fs, geminiCjsPath, geminiMessages, geminiMessagesPath, { getGeminiAPI } (+7 more)

### Community 27 - "readStreamUtf8"
Cohesion: 0.26
Nodes (12): readStreamUtf8(), callGoogleRoutesApi(), callOsrmFallback(), computeCommute(), fetchMetaMedia(), getAccessToken(), getMetaToken, logActivityEvent() (+4 more)

### Community 29 - "memory-hygiene.js"
Cohesion: 0.18
Nodes (19): DEF-05: Semantic Memory Contradiction Detection & Temporal Decay, computeRecencyBoost(), createMemoryHygieneStore(), findCandidateNeighbors(), ingestMemoryWithHygiene(), reconcileExistingMemories(), EPISODIC_TYPES, hasFactMutationTokens() (+11 more)

### Community 30 - "db-adapter.test.js"
Cohesion: 0.25
Nodes (5): assert, DB_PATH, fs, path, test

### Community 33 - "restore.sh"
Cohesion: 0.47
Nodes (5): HOME, PATH, restore.sh script, sync_published_versions_sql(), verify_and_extract_secrets()

### Community 35 - "correction-learner.js"
Cohesion: 0.12
Nodes (26): DEF-04: Real-Time In-Turn Correction Learning (`"No, I meant..."`), containsSecretOrPassword(), createCorrectionLearner(), extractAndSaveCorrection(), detectCorrectionSignal(), findDuplicateFieldNote(), redactAllSecrets(), SECRET_PATTERNS (+18 more)

### Community 36 - "probe-incident-signatures.js"
Cohesion: 0.17
Nodes (21): computeSignature(), createIncidentStore(), draftLessonsFromCandidates(), recordCandidate(), crypto, normalizeErrorKey(), redactAndNormalizeError(), redactSecretsInError() (+13 more)

### Community 37 - "heartbeat-store.js"
Cohesion: 0.17
Nodes (15): createHeartbeatStore(), flushSentinel(), listHeartbeats(), recordHeartbeat(), evaluateStaleness(), lookupEntry(), SENTINEL_REGISTRY, sqlStr() (+7 more)

### Community 38 - "quiet-hours.test.js"
Cohesion: 0.16
Nodes (13): BYPASS_SOURCES, computeQuietHoursVerdict(), getLocalHour(), hourFormatter, isQuietWindow(), assert, {
  QUIET_START_HOUR,
  QUIET_END_HOUR,
  TZ,
  BYPASS_SOURCES,
  getLocalHour,
  isQuietWindow,
  computeQuietHoursVerdict,
}, test (+5 more)

### Community 39 - "host-adapters.test.js"
Cohesion: 0.17
Nodes (7): assert, fs, HOST_ADAPTERS_PATH, http, net, path, test

### Community 40 - "whatsapp-egress.test.js"
Cohesion: 0.25
Nodes (5): assert, EGRESS_PATH, fs, path, test

### Community 41 - "lifecycle.test.js"
Cohesion: 0.17
Nodes (9): assert, CONFIG_PATH, { execFileSync }, fs, os, path, SERVER_PATH, test (+1 more)

### Community 42 - "config.test.js"
Cohesion: 0.22
Nodes (6): assert, CONFIG_PATH, fs, os, path, test

### Community 43 - "phase2c-ops.test.js"
Cohesion: 0.25
Nodes (7): assert, { execFileSync }, fs, path, PATHS, readOrSkip(), test

### Community 45 - "migrate-loop-keys.js"
Cohesion: 0.06
Nodes (47): buildCanonicalLoopKey(), crypto, effectiveDue(), encodeCanonicalLoopId(), extractLoopEntityKey(), formatDueBucket(), formatIsraelDate(), generateDeterministicLoopId() (+39 more)

### Community 47 - "ref_path"
Cohesion: 0.25
Nodes (9): { execFileSync }, fs, main(), migrateJsCode(), migrateNodes(), migrateUrlParam(), path, runPsql() (+1 more)

### Community 48 - "server"
Cohesion: 0.17
Nodes (26): classifyLoopsByDue(), buildSessionPreamble(), checkAndDispatchDueReminders(), effectiveDue(), fetchBufferFromUrl(), getJerusalemOffsetString(), getSentinelEvent(), getSystemAudit() (+18 more)

### Community 52 - "publish-graph.sh"
Cohesion: 0.50
Nodes (3): HOME, PATH, publish-graph.sh script

### Community 53 - "config.js"
Cohesion: 0.14
Nodes (8): compactSessionChatHistory(), compactToolObservationContent(), createMetaTokenReader(), crypto, defaultConfig, fs, normalizeHistoryRow(), path

### Community 54 - "mcp.test.js"
Cohesion: 0.18
Nodes (7): assert, fs, os, path, { spawn, execFileSync, execFile }, test, { TOOLS, handleToolCall, TAL_RECIPIENT }

### Community 55 - "callVertexApiWithRetry"
Cohesion: 0.18
Nodes (13): analyzeImageBuffer(), callGeminiJson(), callVertexApiWithRetry(), generateEmbedding(), getCircuitBreaker(), insertSemanticMemory(), kgStore, memoryHygieneStore (+5 more)

### Community 56 - "index.js"
Cohesion: 0.27
Nodes (8): { bridgeRequest }, fs, handleToolCall(), readHeartbeatMeta(), readline, sendJsonRpc(), startStdioServer(), TOOLS

### Community 57 - "ref_node_assert"
Cohesion: 0.25
Nodes (6): resolveConfig(), assert, config, { createDb }, main(), QUERIES

### Community 58 - "server-endpoints.test.js"
Cohesion: 0.22
Nodes (5): assert, { execFile }, fs, test, TOKEN

### Community 59 - "ref_node_test"
Cohesion: 0.40
Nodes (3): assert, {
  computeRecencyBoost,
  rankMemoriesWithDecay,
  hasFactMutationTokens,
  mergeContextNotes,
  createMemoryHygieneStore,
}, test

### Community 62 - "Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`)"
Cohesion: 0.33
Nodes (5): Emergency Sub-Minute Rollback to Host `systemd` (`vertex-search.service`), Overview, Returning from Host `systemd` to Container (`vertex-bridge`), Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`), Standard Deployment & Digest Rollback (`deploy-bridge.sh`)

### Community 63 - "queryPostgresWithStdin"
Cohesion: 0.20
Nodes (11): atomicWriteJson(), loadBriefedMeetings(), loopStore, markBriefedMeeting(), queryPostgresWithStdin(), resolveDecision(), saveContext(), saveDecisions() (+3 more)

### Community 65 - "run-agent-eval.sh"
Cohesion: 0.50
Nodes (3): HOME, PATH, run-agent-eval.sh script

## Knowledge Gaps
- **15 isolated node(s):** `PATH`, `PATH`, `HOME`, `REGISTRY_AUTH_FILE`, `PATH` (+10 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 426 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **21 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `createDb()` connect `ref_child_process` to `server.js`, `ref_node_assert`?**
  _High betweenness centrality (0.033) - this node is a cross-community bridge._
- **What connects `PATH`, `PATH`, `HOME` to the rest of the system?**
  _15 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `server.js` be split into smaller, more focused modules?**
  _Cohesion score 0.04878048780487805 - nodes in this community are weakly interconnected._
- **Why does `1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4)` connect `1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4)` to `correction-learner.js`, `memory-hygiene.js`?**
  _High betweenness centrality (0.022) - this node is a cross-community bridge._
- **Should `test_workspace_mutations.js` be split into smaller, more focused modules?**
  _Cohesion score 0.11428571428571428 - nodes in this community are weakly interconnected._
- **Should `Semantic Vector Memory & Cortex Sleep Consolidation Architecture` be split into smaller, more focused modules?**
  _Cohesion score 0.10526315789473684 - nodes in this community are weakly interconnected._
- **Should `test_graphify_integration.py` be split into smaller, more focused modules?**
  _Cohesion score 0.1286549707602339 - nodes in this community are weakly interconnected._