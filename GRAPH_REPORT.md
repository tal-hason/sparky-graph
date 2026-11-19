# Graph Report - sparky-backup  (2026-11-19)

## Corpus Check
- 106 files · ~233,759 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 12 file(s) not represented in the graph (top: (none) 5, .service 5, .example 1)

## Summary
- 1391 nodes · 2743 edges · 84 communities (63 shown, 21 thin omitted)
- Extraction: 89% EXTRACTED · 11% INFERRED · 0% AMBIGUOUS · INFERRED: 308 edges (avg confidence: 0.86)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `7831a194`
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
- isTestPayload
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
- redactSecretsInError
- heartbeat-store.js
- ref_child_process
- host-adapters.test.js
- n8n-sparky/test-n8n-patches.js
- lifecycle.test.js
- config.test.js
- phase2c-ops.test.js
- ref_path
- family-relay.js
- test_agent_evaluation.py
- index.js
- server
- patch-n8n-memory-orphans.sh
- sentinel-commute-helpers.js
- reactionCommandService
- publish-graph.sh
- config.js
- TestEvaluationHarnessWorkflow
- TaskDaemon
- ref_fs
- ref_node_path
- TestEvaluationSafetyGuard
- vertex-search-bridge/package.json
- ref_node_test
- TestGoldenDatasetPresence
- Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`)
- scripts
- probe-db-parity.js
- run-agent-eval.sh
- createDb
- sync-services-to-repo.sh
- n8n-stack/scripts/deploy-bridge.sh
- eval-history.md
- TestWorkflowTelemetry
- Requirements Anchor: `[Sparky-AI]` Event-Driven Email Handoff to Gemini App
- n8n-sparky/patch-gemini4-langchain.sh
- n8n-sparky/patch-n8n-memory-orphans.sh
- TestDynamicModelRoutingCallers
- scripts/patch-retry-backoff.sh
- n8n-sparky/patch-retry-backoff.sh
- Requirements Anchor: Sparky-AI Dynamic Main Agent Model & Effort Routing
- TestEopSkillAndBackupScriptContract
- sentinel-commute-helpers.test.js
- vertex-fallback.test.js
- test_workspace_mutations.js
- callVertexWithCascade
- TestReactionCommandDeckWorkflows

## God Nodes (most connected - your core abstractions)
1. `server` - 125 edges
2. `redactSecretsInError()` - 23 edges
3. `queryPostgresJson()` - 23 edges
4. `buildSessionPreamble()` - 23 edges
5. `TaskDaemon` - 21 edges
6. `createModelRouter()` - 20 edges
7. `callBridge()` - 18 edges
8. `createReactionActivityController()` - 17 edges
9. `handleWhatsappTtsRoute()` - 16 edges
10. `createKgStore()` - 15 edges

## Surprising Connections (you probably didn't know these)
- `1. User Intent & Selected Architecture` --references--> `buildSessionPreamble()`  [INFERRED]
  docs/brainstorms/sparky-dynamic-model-routing-requirements.md → services/vertex-search-bridge/server.js
- `A2. Full-Ecosystem Scope (Locked Across All 8 Branches)` --references--> `buildAgyTaskPayload()`  [INFERRED]
  docs/brainstorms/sparky-gemini4-neon-roster-requirements.md → services/vertex-search-bridge/agy-mission-client.js
- `2. Verified Architectural Invariants & Test Alignment` --references--> `compactSessionChatHistory()`  [INFERRED]
  docs/brainstorms/sparky-dynamic-model-routing-requirements.md → services/vertex-search-bridge/config.js
- `A2. Full-Ecosystem Scope (Locked Across All 8 Branches)` --references--> `completeTurn()`  [INFERRED]
  docs/brainstorms/sparky-gemini4-neon-roster-requirements.md → services/vertex-search-bridge/reaction-activity.js
- `🛠️ Microservice Bridge (Port 5055)` --references--> `replayHeldQuietHoursMessages()`  [INFERRED]
  README.md → services/vertex-search-bridge/server.js

## Import Cycles
- None detected.

## Communities (84 total, 21 thin omitted)

### Community 0 - "server.js"
Cohesion: 0.03
Nodes (58): {
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
}, config (+50 more)

### Community 1 - "reaction-commands.test.js"
Cohesion: 0.08
Nodes (13): AgyDriver, assert, BridgeCommandDriver, { EventEmitter }, fs, loadCorrectionLearner(), loadReactionCommands(), os (+5 more)

### Community 2 - "ref_fs"
Cohesion: 0.21
Nodes (13): bridgeRequest(), fs, getBridgeToken(), { bridgeRequest }, fs, isSafeHeartbeatPath(), path, readStdin() (+5 more)

### Community 3 - "model-router.js"
Cohesion: 0.06
Nodes (62): 1. Locked Architecture & 4-Model Periodic Roster (Bootstrap + `/grill-me` Convergence), 2. Live Empirical Probe Ground Truth (`spark-509400` & `agy` CLI, 2026-11-19), 3. Bounded Complex Probes Gating Rollout, 4. Post-Pre-Flight Run #1 `/grill-me` Convergence (Branches 1–5 Locked), A1. Strict Monotonic 6-Tier Periodic Matrix (`COGNITIVE_TIERS` in `/root/vertex-search-bridge/model-router.js`), A2. Full-Ecosystem Scope (Locked Across All 8 Branches), A3. Generalized Heavy-Model Circuit Breaker & Guardrails, Requirements Anchor: Sparky-AI Gemini 4 Neon 4-Model Periodic Roster (+54 more)

### Community 4 - "test_workspace_mutations.js"
Cohesion: 0.07
Nodes (35): assert, assertBalancedSentinelXml(), assertHostileEscaped(), callBridge(), checkActiveDecision(), checkCommute(), checkDue(), checkReminders() (+27 more)

### Community 5 - "server"
Cohesion: 0.11
Nodes (30): normalizeReactionEmoji(), atomicWriteJson(), cleanNullableStr(), encodeMarkdownUrl(), fetchBufferFromUrl(), handleAgyMissionRoute(), handleReactionExecuteRoute(), handleWhatsappTtsRoute() (+22 more)

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

### Community 14 - "isTestPayload"
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

### Community 27 - "reactionCommandService"
Cohesion: 0.16
Nodes (18): readStreamUtf8(), callGoogleRoutesApi(), callOsrmFallback(), callVertexApiWithRetry(), callVertexFastJson(), sendOnce(), computeCommute(), fetchMetaMedia() (+10 more)

### Community 29 - "memory-hygiene.js"
Cohesion: 0.13
Nodes (29): DEF-05: Semantic Memory Contradiction Detection & Temporal Decay, computeRecencyBoost(), createMemoryHygieneStore(), findCandidateNeighbors(), ingestMemoryWithHygiene(), reconcileExistingMemories(), EPISODIC_TYPES, extractSearchTokens() (+21 more)

### Community 30 - "ref_node_fs"
Cohesion: 0.25
Nodes (5): assert, DB_PATH, fs, path, test

### Community 33 - "restore.sh"
Cohesion: 0.47
Nodes (5): HOME, PATH, restore.sh script, sync_published_versions_sql(), verify_and_extract_secrets()

### Community 35 - "nudge-telemetry.js"
Cohesion: 0.17
Nodes (20): classifyDecisionChoice(), computeSenderAdjustment(), createNudgeTelemetryStore(), getEffectivenessReport(), getSenderFeedback(), extractSenderKey(), formatTriageFeedbackXml(), inferDecisionSource() (+12 more)

### Community 36 - "redactSecretsInError"
Cohesion: 0.09
Nodes (37): ALLOWED_AGY_MODEL_SET, ALLOWED_AGY_MODELS, ALLOWED_WORKSPACES, buildAgyTaskPayload(), buildFencedMissionPrompt(), dispatchAgyMissionToDrive(), fetchAgyAccessToken(), fs (+29 more)

### Community 37 - "heartbeat-store.js"
Cohesion: 0.06
Nodes (40): extractInteractiveOptions(), INTERACTIVE_SENTINEL_SOURCES, NON_DECISION_SOURCES, SOURCE_ALIAS_GROUPS, createHeartbeatStore(), flushSentinel(), listHeartbeats(), recordHeartbeat() (+32 more)

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

### Community 44 - "ref_path"
Cohesion: 0.25
Nodes (9): { execFileSync }, fs, main(), migrateJsCode(), migrateNodes(), migrateUrlParam(), path, runPsql() (+1 more)

### Community 45 - "family-relay.js"
Cohesion: 0.07
Nodes (53): classifyFamilyInboundText(), createFamilyRelayService(), configureFamilyMember(), handleFamilyInbound(), loadCtx(), loadFamilyLoops(), processFamilyInbound(), recordChatHistory() (+45 more)

### Community 46 - "test_agent_evaluation.py"
Cohesion: 0.14
Nodes (4): _eval_n8n_expr(), TestAntigravitySkillAndRulesRegistration, TestDeterministicCLIGraphQuery, TestGraphifyCLIBinary

### Community 47 - "index.js"
Cohesion: 0.19
Nodes (12): processJsonRpcMessage(), { ALLOWED_AGY_MODELS, validateOptionalAgyModel }, { bridgeRequest }, dispatchAgyMissionToDrive(), fs, handleToolCall(), readHeartbeatMeta(), readline (+4 more)

### Community 48 - "server"
Cohesion: 0.11
Nodes (32): getDecisionSourceAliases(), advanceInTransitLoopOnKeepTracking(), buildSessionPreamble(), checkAndDispatchDueReminders(), createDecision(), effectiveDue(), getSentinelEvent(), getSystemAudit() (+24 more)

### Community 50 - "sentinel-commute-helpers.js"
Cohesion: 0.27
Nodes (12): evaluateCommuteWindow(), filterAndSortEvents(), formatCommuteBriefingLine(), formatIsoTimeIl(), formatOriginLabel(), hasVideo(), isPhysical(), isVirtualLink() (+4 more)

### Community 51 - "reactionCommandService"
Cohesion: 0.26
Nodes (17): checkAndDispatchWindowKeepalive(), familyRelay, getWindowState(), invalidateWindowStateCache(), logActivityEvent(), postMetaMediaOnce(), queryPostgresWithStdin(), recipientMatchSql() (+9 more)

### Community 52 - "publish-graph.sh"
Cohesion: 0.50
Nodes (3): HOME, PATH, publish-graph.sh script

### Community 53 - "config.js"
Cohesion: 0.14
Nodes (8): compactSessionChatHistory(), compactToolObservationContent(), createMetaTokenReader(), crypto, defaultConfig, fs, normalizeHistoryRow(), path

### Community 55 - "TaskDaemon"
Cohesion: 0.06
Nodes (7): extract_stream_json_result(), read_heartbeat_meta(), resolve_task_model(), resolve_timeouts(), sd_notify(), TaskDaemon, TestDaemon

### Community 56 - "ref_fs"
Cohesion: 0.22
Nodes (6): assert, FIXTURE_PATH, fs, { generateDeterministicLoopId }, path, test

### Community 57 - "ref_node_path"
Cohesion: 0.25
Nodes (5): assert, EGRESS_PATH, fs, path, test

### Community 59 - "vertex-search-bridge/package.json"
Cohesion: 0.18
Nodes (10): pg, dependencies, pg, description, engines, node, main, name (+2 more)

### Community 60 - "ref_node_test"
Cohesion: 0.22
Nodes (6): assert, { createHandoffStore, formatHandoffsXml }, { describe, it }, assert, { createLoopStore }, test

### Community 62 - "Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`)"
Cohesion: 0.33
Nodes (5): Emergency Sub-Minute Rollback to Host `systemd` (`vertex-search.service`), Overview, Returning from Host `systemd` to Container (`vertex-bridge`), Runbook: Containerized Vertex Search Bridge & Sub-Minute Systemd Rollback (`DEF-10`), Standard Deployment & Digest Rollback (`deploy-bridge.sh`)

### Community 63 - "scripts"
Cohesion: 0.50
Nodes (4): scripts, start, test, test:ci

### Community 64 - "probe-db-parity.js"
Cohesion: 0.29
Nodes (6): resolveConfig(), assert, config, { createDb }, main(), QUERIES

### Community 65 - "run-agent-eval.sh"
Cohesion: 0.50
Nodes (3): HOME, PATH, run-agent-eval.sh script

### Community 66 - "createDb"
Cohesion: 0.53
Nodes (5): createDb(), getOrInitPgPool(), queryPostgresJson(), queryPostgresScript(), queryPostgresWithStdin()

### Community 78 - "Requirements Anchor: Sparky-AI Dynamic Main Agent Model & Effort Routing"
Cohesion: 0.50
Nodes (3): 1. User Intent & Selected Architecture, 2. Verified Architectural Invariants & Test Alignment, Requirements Anchor: Sparky-AI Dynamic Main Agent Model & Effort Routing

### Community 82 - "sentinel-commute-helpers.test.js"
Cohesion: 0.25
Nodes (6): assert, commuteDsl, fs, path, SUT_PATH, test

### Community 83 - "vertex-fallback.test.js"
Cohesion: 0.17
Nodes (19): createCircuitBreaker(), getCircuitBreaker(), assert, {
  DEFAULT_SENSORY_FALLBACK_CHAIN,
  DEFAULT_CARBON_FALLBACK_CHAIN,
  DEFAULT_NEON_FALLBACK_CHAIN,
  DEFAULT_SEARCH_FALLBACK_CHAIN,
  extractVertexLocationAndModel,
  buildVertexGenerateContentPath,
  resolveFallbackChain,
  adaptVertexPayloadForModel,
  isFallbackEligibleVertexError,
  callVertexWithModelFallback,
  extractVertexCandidateText,
}, fs, path, test, adaptVertexPayloadForModel() (+11 more)

### Community 85 - "test_workspace_mutations.js"
Cohesion: 0.11
Nodes (18): APPEND_WF_PATH, cleanupRegistry, CREATE_DOC_WF_PATH, CREATE_SHEET_WF_PATH, CREATE_SLIDES_WF_PATH, { execSync, execFileSync }, EXPECTED_HEADERS, formatOutput() (+10 more)

### Community 86 - "callVertexWithCascade"
Cohesion: 0.20
Nodes (14): analyzeImageBuffer(), callGeminiJson(), callVertexWithCascade(), generateEmbedding(), insertSemanticMemory(), kgStore, memoryHygieneStore, notifyVertexCascadeExhaustion() (+6 more)

## Knowledge Gaps
- **20 isolated node(s):** `PATH`, `PATH`, `HOME`, `REGISTRY_AUTH_FILE`, `PATH` (+15 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 590 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **21 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4)` connect `1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4)` to `correction-learner.js`, `memory-hygiene.js`?**
  _High betweenness centrality (0.040) - this node is a cross-community bridge._
- **What connects `PATH`, `PATH`, `HOME` to the rest of the system?**
  _20 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `server.js` be split into smaller, more focused modules?**
  _Cohesion score 0.03389830508474576 - nodes in this community are weakly interconnected._
- **Why does `DEF-05: Semantic Memory Contradiction Detection & Temporal Decay` connect `memory-hygiene.js` to `1. Adaptive Autonomy & Closed-Loop Feedback (Epic E4)`?**
  _High betweenness centrality (0.030) - this node is a cross-community bridge._
- **Should `reaction-commands.test.js` be split into smaller, more focused modules?**
  _Cohesion score 0.07956989247311828 - nodes in this community are weakly interconnected._
- **Should `model-router.js` be split into smaller, more focused modules?**
  _Cohesion score 0.056535504296698326 - nodes in this community are weakly interconnected._
- **Should `test_workspace_mutations.js` be split into smaller, more focused modules?**
  _Cohesion score 0.0673758865248227 - nodes in this community are weakly interconnected._