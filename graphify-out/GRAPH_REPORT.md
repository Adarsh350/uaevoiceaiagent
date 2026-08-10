# Graph Report - .  (2026-08-10)

## Corpus Check
- 92 files · ~94,915 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 464 nodes · 710 edges · 25 communities (19 shown, 6 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS · INFERRED: 2 edges (avg confidence: 0.5)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Community 0
- Community 1
- Community 2
- Community 3
- Community 4
- Community 5
- Community 6
- Community 7
- Community 8
- Community 9
- Community 10
- Community 11
- Community 12
- Community 13
- Community 14
- Community 15
- Community 16
- Community 17
- Community 18
- Community 19
- Community 20
- Community 21
- Community 22
- Community 24

## God Nodes (most connected - your core abstractions)
1. `optionalEnv()` - 21 edges
2. `compilerOptions` - 16 edges
3. `compilerOptions` - 16 edges
4. `clean()` - 14 edges
5. `fileReport()` - 13 edges
6. `buildTools()` - 10 edges
7. `getSupabase()` - 10 edges
8. `CatalogueCore` - 9 edges
9. `LivingInfo` - 8 edges
10. `TriagePage()` - 8 edges

## Surprising Connections (you probably didn't know these)
- `generateStaticParams()` --calls--> `getAllServices()`  [EXTRACTED]
  app/services/[slug]/page.tsx → lib/services.ts
- `ServicePage()` --calls--> `getService()`  [EXTRACTED]
  app/services/[slug]/page.tsx → lib/services.ts
- `Home()` --calls--> `getAllServices()`  [EXTRACTED]
  app/page.tsx → lib/services.ts
- `Home()` --calls--> `getService()`  [EXTRACTED]
  app/page.tsx → lib/services.ts
- `TriagePage()` --calls--> `getTriageRows()`  [EXTRACTED]
  app/triage/page.tsx → lib/triage.ts

## Import Cycles
- None detected.

## Communities (25 total, 6 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.06
Nodes (69): bodySchema, POST(), runtime, secretMatches(), spellForSpeech(), payloadSchema, POST(), runtime (+61 more)

### Community 1 - "Community 1"
Cohesion: 0.05
Nodes (42): Catalogue, CatalogueCore, indexDataset(), normaliseDataset(), splitList(), DATASET_FIELDS, fetchAll(), fetchPage() (+34 more)

### Community 2 - "Community 2"
Cohesion: 0.11
Nodes (27): Home(), generateStaticParams(), ServicePage(), Orb(), OrbProps, RotatingPrompts(), VoiceConsole(), Fee (+19 more)

### Community 3 - "Community 3"
Cohesion: 0.05
Nodes (38): @eslint/eslintrc, @supabase/supabase-js, dependencies, next, react, react-dom, @supabase/supabase-js, zod (+30 more)

### Community 4 - "Community 4"
Cohesion: 0.05
Nodes (37): @elevenlabs/react, dependencies, @elevenlabs/react, next, qrcode, react, react-dom, devDependencies (+29 more)

### Community 5 - "Community 5"
Cohesion: 0.06
Nodes (30): MCPServer, **/*.mts, .next/dev/types/**/*.ts, SupportLoop, compilerOptions, allowJs, esModuleInterop, incremental (+22 more)

### Community 6 - "Community 6"
Cohesion: 0.07
Nodes (26): compilerOptions, allowJs, esModuleInterop, incremental, isolatedModules, jsx, lib, module (+18 more)

### Community 7 - "Community 7"
Cohesion: 0.17
Nodes (12): atkinson, metadata, mono, DisplayControls(), SIZE_OPTIONS, DisplayPreferencesContext, DisplayPreferencesProvider(), DisplayPreferencesValue (+4 more)

### Community 8 - "Community 8"
Cohesion: 0.12
Nodes (16): dependencies, @modelcontextprotocol/sdk, description, engines, node, name, private, scripts (+8 more)

### Community 9 - "Community 9"
Cohesion: 0.17
Nodes (14): catalogue, indicators, living, BY_NAME, catalogue, CORS, fetch(), handleRpc() (+6 more)

### Community 10 - "Community 10"
Cohesion: 0.24
Nodes (11): AGENT_ID, AgentSettings, API_KEY, buildAgentPatch(), elevenlabsFetch(), loadPrompt(), loadSettings(), main() (+3 more)

### Community 11 - "Community 11"
Cohesion: 0.20
Nodes (7): catalogue, indicators, KEEP, living, OUT, ROOT, snap

### Community 12 - "Community 12"
Cohesion: 0.38
Nodes (5): metadata, TriagePage(), EXAMPLE_ROWS, getTriageRows(), TriageRow

### Community 13 - "Community 13"
Cohesion: 0.33
Nodes (3): call(), LEAKS, rpc()

### Community 14 - "Community 14"
Cohesion: 0.33
Nodes (3): LiveFetcher, scrape(), SOURCES

### Community 15 - "Community 15"
Cohesion: 0.53
Nodes (4): WhatsAppCta(), getWhatsAppLink(), WHATSAPP_NUMBER, WHATSAPP_PROMPT_TEXT

### Community 16 - "Community 16"
Cohesion: 0.40
Nodes (3): metadata, FeedbackForm(), Result

### Community 18 - "Community 18"
Cohesion: 0.40
Nodes (4): compat, __dirname, eslintConfig, __filename

## Knowledge Gaps
- **185 isolated node(s):** `REPO_ROOT`, `API_KEY`, `AGENT_ID`, `AgentSettings`, `name` (+180 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **6 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `CatalogueCore` connect `Community 1` to `Community 9`?**
  _High betweenness centrality (0.005) - this node is a cross-community bridge._
- **What connects `REPO_ROOT`, `API_KEY`, `AGENT_ID` to the rest of the system?**
  _185 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.057203956161454156 - nodes in this community are weakly interconnected._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.051251956181533644 - nodes in this community are weakly interconnected._
- **Should `Community 2` be split into smaller, more focused modules?**
  _Cohesion score 0.1076923076923077 - nodes in this community are weakly interconnected._
- **Should `Community 3` be split into smaller, more focused modules?**
  _Cohesion score 0.05128205128205128 - nodes in this community are weakly interconnected._
- **Should `Community 4` be split into smaller, more focused modules?**
  _Cohesion score 0.05263157894736842 - nodes in this community are weakly interconnected._