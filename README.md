# Awesome MCP

![Awesome](https://raw.githubusercontent.com/abordage/schemas/main/badges/awesome.svg)
[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-mcp?label=last%20update)](README.md)
![Repositories](https://img.shields.io/badge/repositories-2,513-06b6d4)
![Total Stars](https://img.shields.io/badge/total%20stars-2,619,214-gold)
[![License](https://img.shields.io/github/license/abordage/awesome-mcp)](LICENSE)

**Automated. Curated. Ranked.**

[Model Context Protocol (MCP)](https://modelcontextprotocol.io/) servers, clients, and frameworks — the open standard for connecting AI assistants to external data sources and tools. This awesome list is automatically maintained with daily GitHub API updates. Projects are re-ranked daily based on current activity metrics.

**Daily process:** Merge community PRs → Scan repos → Filter stale projects → Recalculate scores → Rebuild list

- [AI Agents](#ai-agents)
  - [Code Assistants](#code-assistants)
  - [Human-in-the-Loop](#human-in-the-loop)
  - [Multi-Agent](#multi-agent)
  - [Reasoning & Prompts](#reasoning--prompts)
- [AI Memory & RAG](#ai-memory--rag)
  - [Memory](#memory)
  - [RAG](#rag)
- [AI Platforms](#ai-platforms)
- [Aggregators & Gateways](#aggregators--gateways)
  - [Aggregators](#aggregators)
  - [Gateways & Proxies](#gateways--proxies)
  - [Platforms & Registries](#platforms--registries)
- [Browser Automation](#browser-automation)
  - [AI Automation](#ai-automation)
  - [Browser Tools](#browser-tools)
  - [Cloud Services](#cloud-services)
  - [DevTools](#devtools)
  - [Playwright](#playwright)
- [CLI Tools](#cli-tools)
- [CRM & ERP](#crm--erp)
- [Cloud & Infrastructure](#cloud--infrastructure)
  - [AWS](#aws)
  - [Cloud Platforms](#cloud-platforms)
  - [Kubernetes](#kubernetes)
  - [Virtualization & IaC](#virtualization--iac)
- [Communication & Messaging](#communication--messaging)
  - [Apple Messages](#apple-messages)
  - [Email](#email)
  - [Messengers](#messengers)
  - [Notifications](#notifications)
  - [Team Chat](#team-chat)
  - [Voice & Telephony](#voice--telephony)
- [Data & Analytics](#data--analytics)
  - [AI/ML Platforms](#aiml-platforms)
  - [Data APIs](#data-apis)
  - [Data Exploration](#data-exploration)
  - [Data Platforms](#data-platforms)
  - [Jupyter & Notebooks](#jupyter--notebooks)
  - [Visualization](#visualization)
- [Databases](#databases)
  - [Analytics & Warehouses](#analytics--warehouses)
  - [Cache & Key-Value](#cache--key-value)
  - [Cloud Platforms](#cloud-platforms)
  - [Graph Databases](#graph-databases)
  - [Multi-Database Tools](#multi-database-tools)
  - [NoSQL & Document](#nosql--document)
  - [SQL Databases](#sql-databases)
  - [Search Engines](#search-engines)
  - [Spreadsheets & No-Code](#spreadsheets--no-code)
  - [Streaming & Messaging](#streaming--messaging)
  - [Time-Series & Metrics](#time-series--metrics)
  - [Vector Databases](#vector-databases)
- [Developer Tools](#developer-tools)
  - [API Tools](#api-tools)
  - [CI/CD & DevOps](#cicd--devops)
  - [Code Analysis](#code-analysis)
  - [Debuggers](#debuggers)
  - [Design & UI](#design--ui)
  - [Diagrams](#diagrams)
  - [Documentation](#documentation)
  - [IDE & Editors](#ide--editors)
  - [MCP SDKs](#mcp-sdks)
  - [Mobile Development](#mobile-development)
  - [OpenAPI](#openapi)
  - [Package Managers](#package-managers)
  - [Robotics & Automation](#robotics--automation)
  - [Task Management](#task-management)
  - [Testing & QA](#testing--qa)
  - [Utilities](#utilities)
  - [Version Control](#version-control)
- [Embedded & IoT](#embedded--iot)
- [File Systems & Storage](#file-systems--storage)
- [Finance](#finance)
  - [Accounting & Budgeting](#accounting--budgeting)
  - [Crypto & Blockchain](#crypto--blockchain)
  - [Payments & Banking](#payments--banking)
  - [Stock Data & Analytics](#stock-data--analytics)
  - [Trading & Exchanges](#trading--exchanges)
- [Frameworks & SDKs](#frameworks--sdks)
- [Gaming](#gaming)
- [Healthcare & Bioinformatics](#healthcare--bioinformatics)
- [LLM Bridges](#llm-bridges)
- [Location & Maps](#location--maps)
  - [GIS](#gis)
  - [IP Geolocation](#ip-geolocation)
  - [Maps & Navigation](#maps--navigation)
  - [Weather](#weather)
- [MCP Clients](#mcp-clients)
- [Marketing & Analytics](#marketing--analytics)
- [Media Processing](#media-processing)
  - [3D & Animation](#3d--animation)
  - [Audio & Music](#audio--music)
  - [Image Generation](#image-generation)
  - [Image Processing](#image-processing)
  - [Media Services](#media-services)
  - [Video](#video)
- [Monitoring & Observability](#monitoring--observability)
- [Productivity](#productivity)
  - [Atlassian](#atlassian)
  - [Collaboration](#collaboration)
  - [Documents](#documents)
  - [Google Workspace](#google-workspace)
  - [Helpdesk & Support](#helpdesk--support)
  - [Learning & Flashcards](#learning--flashcards)
  - [Microsoft 365](#microsoft-365)
  - [Note-taking & Docs](#note-taking--docs)
  - [Notion](#notion)
  - [Obsidian](#obsidian)
  - [Project Management](#project-management)
  - [Tasks & Calendar](#tasks--calendar)
  - [Wiki & Collaboration](#wiki--collaboration)
  - [Education](#education)
- [Research & Science](#research--science)
- [Sandboxing & Execution](#sandboxing--execution)
- [Search & Extraction](#search--extraction)
  - [Academic Research](#academic-research)
  - [Data APIs](#data-apis)
  - [News & Content](#news--content)
  - [Web Search Engines](#web-search-engines)
- [Security](#security)
  - [Identity & Access](#identity--access)
  - [MCP Security](#mcp-security)
  - [Network & Firewall](#network--firewall)
  - [Pentesting & OSINT](#pentesting--osint)
  - [Reverse Engineering](#reverse-engineering)
  - [SIEM & SecOps](#siem--secops)
- [Social Media](#social-media)
- [Sports](#sports)
- [Text-to-Speech](#text-to-speech)
- [Translation](#translation)
- [Travel & Transport](#travel--transport)
- [Web Scraping](#web-scraping)
- [E-Commerce](#e-commerce)
- [Legal](#legal)
- [Speech-to-Text](#speech-to-text)


## AI Agents

### Code Assistants

- [oraios/serena](https://github.com/oraios/serena) — Semantic code retrieval and editing toolkit ☆`31,278`
- [zilliztech/claude-context](https://github.com/zilliztech/claude-context) — Code search for Claude Code agents ☆`12,686`
- [Q00/ouroboros](https://github.com/Q00/ouroboros) — Agent that proposes changes, then evaluates them under a budget ☆`6,345`
- [CodeGraphContext/CodeGraphContext](https://github.com/CodeGraphContext/CodeGraphContext) — Code graph indexing for AI context ☆`4,408`
- [ezyang/codemcp](https://github.com/ezyang/codemcp) — Coding assistant MCP for Claude Desktop ☆`1,603`
- [ref-tools/ref-tools-mcp](https://github.com/ref-tools/ref-tools-mcp) — Reference tools for coding agents ☆`1,186`
- [mybolide/coding-tools-mcp](https://github.com/mybolide/coding-tools-mcp) — Desktop workspace for edits, commands and history ☆`438`
- [SDGLBL/mcp-claude-code](https://github.com/SDGLBL/mcp-claude-code) — MCP implementation of Claude Code capabilities and more ☆`306`
- [cafeTechne/antigravity-link-extension](https://github.com/cafeTechne/antigravity-link-extension) — Phone companion for the Antigravity IDE ☆`222`
- [stippi/code-assistant](https://github.com/stippi/code-assistant) — LLM-powered autonomous coding assistant ☆`188`
- [freema/openclaw-mcp](https://github.com/freema/openclaw-mcp) — OAuth bridge from Claude.ai to a self-hosted OpenClaw assistant ☆`188`
- [aresyn/codex-control-plane-mcp](https://github.com/aresyn/codex-control-plane-mcp) — Keep long-running Codex Desktop tasks alive ☆`121`
- [archcore-ai/archcore](https://github.com/archcore-ai/archcore) — Git-native specs and context for coding agents ☆`75`
- [lamemind/mcp-server-multiverse](https://github.com/lamemind/mcp-server-multiverse) — MCP server for multiverse context management ☆`82`
- [sshahzaiib/agy-bridge](https://github.com/sshahzaiib/agy-bridge) — Hand heavy tasks from Claude Code to the Antigravity CLI ☆`62`
- [contextstream/mcp-server](https://github.com/contextstream/mcp-server) — Shared project context for AI coding agents across MCP clients ☆`46`
- [wende/cicada](https://github.com/wende/cicada) — AI Coders search blindly. Be their guide. ☆`42`
- [mybolide/mcp-probe-kit](https://github.com/mybolide/mcp-probe-kit) — Spec-driven plans that can resume and must converge ☆`41`
- [gabrielmaialva33/winx-code-agent](https://github.com/gabrielmaialva33/winx-code-agent) — MCP-powered code agent for development ☆`39`
- [religa/multi_mcp](https://github.com/religa/multi_mcp) — Multi-Model chat, code review and analysis MCP Server for Claude Code ☆`36`
- [Touchpoint-Labs/Touchpoint](https://github.com/Touchpoint-Labs/Touchpoint) — Cross-platform desktop control from the accessibility API ☆`48`
- [josephsenior/Grinta-Coding-Agent](https://github.com/josephsenior/Grinta-Coding-Agent) — Local-first resilient terminal coding agent with MCP ☆`32`
- [bshea-1/Routed](https://github.com/bshea-1/Routed) — Universal local router for Agent Skills across AI coding environments ☆`28`
- [REX-codebase/fable-mode](https://github.com/REX-codebase/fable-mode) — Time locks, proof receipts and memory for coding agents ☆`26`
- [x51xxx/codex-mcp-tool](https://github.com/x51xxx/codex-mcp-tool) — Claude/Cursor to Codex CLI bridge with multi-turn sessions ☆`24`
- [alpadalar/netops-mcp](https://github.com/alpadalar/netops-mcp) — Ping, traceroute, nmap, DNS, TLS and HTTP checks ☆`16`
- [abnegate/magents](https://github.com/abnegate/magents) — Shared session bus for Claude Code, Codex, and Cursor ☆`16`
- [Sim-xia/skill-cortex-server](https://github.com/Sim-xia/skill-cortex-server) — Claude Code skills from IDEs that are not Claude Code ☆`24`
- [eirikb/any-cli-mcp-server](https://github.com/eirikb/any-cli-mcp-server) — Turn any CLI into MCP tools from its help text ☆`25`
- [VertexStudio/developer](https://github.com/VertexStudio/developer) — File editing, shell execution, screen capture ☆`20`
- [HendryAvila/Hoofy](https://github.com/HendryAvila/Hoofy) — Companion with memory, specs and a change pipeline, one Go binary ☆`16`
### Human-in-the-Loop

- [ttommyth/interactive-mcp](https://github.com/ttommyth/interactive-mcp) — Interactive MCP server for human-in-the-loop AI ☆`351`
- [RapidataAI/human-use](https://github.com/RapidataAI/human-use) — Enable AI to ask anyone anything ☆`73`
- [gotohuman/gotohuman-mcp-server](https://github.com/gotohuman/gotohuman-mcp-server) — Human approvals for AI agentic workflows ☆`52`
- [nazar256/user-prompt-mcp](https://github.com/nazar256/user-prompt-mcp) — User input requests for Cursor ☆`21`
### Multi-Agent

- [rinadelph/Agent-MCP](https://github.com/rinadelph/Agent-MCP) — Multi-agent AI collaboration framework ☆`1,306`
- [Get-Concord-AI/concord-mcp](https://github.com/Get-Concord-AI/concord-mcp) — Shared presence, file claims and handoffs for coding agents ☆`1,058`
- [roboticforce/sugar](https://github.com/roboticforce/sugar) — Local persistent memory, cross-session context, and optional tasks ☆`100`
### Reasoning & Prompts

- [ooples/token-optimizer-mcp](https://github.com/ooples/token-optimizer-mcp) — Token optimization with caching and compression ☆`577`
- [PV-Bhat/vibe-check-mcp-server](https://github.com/PV-Bhat/vibe-check-mcp-server) — Mentor-like feedback tool preventing AI over-engineering ☆`505`
- [Rai220/think-mcp](https://github.com/Rai220/think-mcp) — MCP Server for reasoning ☆`107`
- [hyperb1iss/lucidity-mcp](https://github.com/hyperb1iss/lucidity-mcp) — MCP server for enhanced AI clarity and reasoning ☆`90`
- [YuChenSSR/multi-ai-advisor-mcp](https://github.com/YuChenSSR/multi-ai-advisor-mcp) — council of models for decision ☆`89`
- [nikkoxgonzales/crash-mcp](https://github.com/nikkoxgonzales/crash-mcp) — Structured reasoning with step validation ☆`72`
- [VoDaiLocz/kilo-kit-mcp](https://github.com/VoDaiLocz/kilo-kit-mcp) — Skill routing and a check before the agent finishes ☆`27`
- [gwbischof/free-will-mcp](https://github.com/gwbischof/free-will-mcp) — Experimental AI self-prompting MCP server ☆`39`
- [aquarius-wing/actor-critic-thinking-mcp](https://github.com/aquarius-wing/actor-critic-thinking-mcp) — Dual-perspective thinking analysis server ☆`32`
- [ejentum/ejentum-mcp](https://github.com/ejentum/ejentum-mcp) — Agent loop with reasoning, code, memory, and anti-deception ☆`16`
- [vasayxtx/mcp-prompt-engine](https://github.com/vasayxtx/mcp-prompt-engine) — MCP Prompt Engine ☆`18`
- [abhinav-mangla/inner-monologue-mcp](https://github.com/abhinav-mangla/inner-monologue-mcp) — Inner Monologue MCP Server ☆`17`
- [abhinav-mangla/think-tool-mcp](https://github.com/abhinav-mangla/think-tool-mcp) — MCP Think Tool Server ☆`16`
## AI Memory & RAG

### Memory

- [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) — Hindsight: Agent Memory That Learns ☆`60,347`
- [basicmachines-co/basic-memory](https://github.com/basicmachines-co/basic-memory) — AI conversations that remember context ☆`4,550`
- [vshulcz/deja-vu](https://github.com/vshulcz/deja-vu) — Shared memory of coding-agent history across many clients ☆`1,476`
- [shaneholloman/mcp-knowledge-graph](https://github.com/shaneholloman/mcp-knowledge-graph) — Local knowledge graph as memory for Claude ☆`888`
- [riponcm/projectmem](https://github.com/riponcm/projectmem) — Record failed attempts and warn before the agent repeats one ☆`879`
- [agentic-box/memora](https://github.com/agentic-box/memora) — Persistent shared memories in SQLite ☆`748`
- [Ikalus1988/MisakaNet](https://github.com/Ikalus1988/MisakaNet) — Graded fixes for failures an agent has already solved ☆`558`
- [MaxFreedomPollard/Compartment](https://github.com/MaxFreedomPollard/Compartment) — Offline AEAD-encrypted vector memory without network ☆`569`
- [syncable-dev/memtrace-public](https://github.com/syncable-dev/memtrace-public) — Structural memory graph, with no model call ☆`515`
- [Beever-AI/beever-atlas](https://github.com/Beever-AI/beever-atlas) — LLM Wiki memory for team chat (Slack, Discord, Teams) ☆`453`
- [gannonh/memento-mcp](https://github.com/gannonh/memento-mcp) — Memento MCP: A Knowledge Graph Memory System for LLMs ☆`426`
- [mcpware/cross-code-organizer](https://github.com/mcpware/cross-code-organizer) — Dashboard for Claude Code, Codex, skills and sessions ☆`391`
- [Goldentrii/AgentRecall-X](https://github.com/Goldentrii/AgentRecall-X) — Memory that keeps corrections across sessions ☆`375`
- [CheMiguel23/MemoryMesh](https://github.com/CheMiguel23/MemoryMesh) — MCP server for knowledge graph memory ☆`355`
- [qualixar/superlocalmemory](https://github.com/qualixar/superlocalmemory) — Local memory control plane for agents and teams ☆`274`
- [roomi-fields/notebooklm-mcp](https://github.com/roomi-fields/notebooklm-mcp) — NotebookLM questions, citations and Studio generation ☆`237`
- [alibaizhanov/mengram](https://github.com/alibaizhanov/mengram) — Semantic, episodic and procedural memory ☆`207`
- [sandbaseai/cli](https://github.com/sandbaseai/cli) — CLI and local server for many clients and model APIs, with rollback ☆`186`
- [dnotitia/akb](https://github.com/dnotitia/akb) — Org memory of docs, tables and files, addressed by URI ☆`166`
- [Patdolitse/piia-engram](https://github.com/Patdolitse/piia-engram) — Local memory you can read, edit and override ☆`165`
- [pi22by7/In-Memoria](https://github.com/pi22by7/In-Memoria) — Persistent Intelligence Infrastructure for AI Agents ☆`175`
- [jean-technologies/jean-memory](https://github.com/jean-technologies/jean-memory) — AI memory with mem0 and graphiti ☆`171`
- [unibaseio/membase](https://github.com/unibaseio/membase) — Decentralized memory layer for AI agents ☆`139`
- [redleaves/context-keeper](https://github.com/redleaves/context-keeper) — Intelligent memory and context for AI agents ☆`156`
- [Bevel-Software/Hexis](https://github.com/Bevel-Software/Hexis) — Org-wide skills, tools, permissions and identity for agents ☆`125`
- [2b3pro/roam-research-mcp](https://github.com/2b3pro/roam-research-mcp) — MCP Server and CLI tool for Roam Research Graph Integration ☆`100`
- [IvenKooLab/loci](https://github.com/IvenKooLab/loci) — Shared memory with hybrid search and cited answers ☆`101`
- [DrDroidLab/open-index](https://github.com/DrDroidLab/open-index) — Structured context graphs with hybrid search and writes ☆`114`
- [dweigend/joplin-mcp-server](https://github.com/dweigend/joplin-mcp-server) — Search and edit notes in Joplin ☆`96`
- [pinkpixel-dev/mem0-mcp](https://github.com/pinkpixel-dev/mem0-mcp) — Long-term memory for agents, as a drop-in mem0 server ☆`96`
- [zcag/tela](https://github.com/zcag/tela) — Self-hosted markdown wiki agents can read, edit and search ☆`92`
- [dodopayments/context-mcp](https://github.com/dodopayments/context-mcp) — Self-hosted MCP server for your documentation ☆`87`
- [spences10/mcp-memory-libsql](https://github.com/spences10/mcp-memory-libsql) — Persistent memory with vector search on libSQL ☆`87`
- [kunwar-shah/claudex](https://github.com/kunwar-shah/claudex) — Search Claude Code session history, with a small web UI ☆`97`
- [cdeust/Cortex](https://github.com/cdeust/Cortex) — Local long-term memory for coding agents ☆`76`
- [vbcherepanov/total-agent-memory](https://github.com/vbcherepanov/total-agent-memory) — Local temporal graph and procedural memory ☆`75`
- [writerslogic/scrivener-mcp](https://github.com/writerslogic/scrivener-mcp) — Novels and screenplays in Scrivener ☆`72`
- [HiAi-gg/docsmint](https://github.com/HiAi-gg/docsmint) — Knowledge base with rich text, hybrid search and GraphRAG ☆`74`
- [Abhigyan-Shekhar/Waggle-mcp](https://github.com/Abhigyan-Shekhar/Waggle-mcp) — External memory layer for agents, installable from PyPI ☆`45`
- [knowall-ai/mcp-reverie](https://github.com/knowall-ai/mcp-reverie) — Memory management using Neo4j graphs ☆`67`
- [max-ramas/rms-memory-mcp](https://github.com/max-ramas/rms-memory-mcp) — Local cross-editor memory, with semantic search in LanceDB ☆`66`
- [decisionnode/DecisionNode](https://github.com/decisionnode/DecisionNode) — Shared structured memory any MCP client can query ☆`82`
- [ZengLiangYi/ChatCrystal](https://github.com/ZengLiangYi/ChatCrystal) — Import coding chats, distill notes and search them ☆`61`
- [ukkit/memcord](https://github.com/ukkit/memcord) — MCP server for memory and context management ☆`74`
- [JinyangWang27/people-context](https://github.com/JinyangWang27/people-context) — Local notes about the people in your life, for agents ☆`60`
- [CamdenClark/anki-mcp-server](https://github.com/CamdenClark/anki-mcp-server) — Read and review Anki decks through AnkiConnect ☆`81`
- [SecurityRonin/docx-mcp](https://github.com/SecurityRonin/docx-mcp) — Word documents with track changes, comments and footnotes ☆`67`
- [roampal-ai/roampal-core](https://github.com/roampal-ai/roampal-core) — Memory that promotes advice that worked and demotes what failed ☆`54`
- [pallaprolus/mendeley-mcp](https://github.com/pallaprolus/mendeley-mcp) — Search and manage a Mendeley library ☆`47`
- [James-Chahwan/repo-graph](https://github.com/James-Chahwan/repo-graph) — Graph of a codebase for navigation ☆`50`
- [jasperket/clanki](https://github.com/jasperket/clanki) — An MCP server for connecting LLMs with Anki Flashcards. ☆`45`
- [dailydaniel/logseq-mcp](https://github.com/dailydaniel/logseq-mcp) — simple logseq mcp server ☆`46`
- [DollhouseMCP/mcp-server](https://github.com/DollhouseMCP/mcp-server) — Swap personas, skills and templates from a public collection ☆`45`
- [BetaBots-LLC/callimachus](https://github.com/BetaBots-LLC/callimachus) — Searchable local index of coding-agent session history ☆`47`
- [peless/claude-thread-continuity](https://github.com/peless/claude-thread-continuity) — Save and restore project context ☆`65`
- [IzumiSy/mcp-duckdb-memory-server](https://github.com/IzumiSy/mcp-duckdb-memory-server) — MCP Memory Server with DuckDB backend ☆`58`
- [linxule/lotus-wisdom-mcp](https://github.com/linxule/lotus-wisdom-mcp) — Contemplative reasoning based on the Lotus Sutra ☆`37`
- [crewAIInc/enterprise-mcp-server](https://github.com/crewAIInc/enterprise-mcp-server) — Start a CrewAI deployment and check its status ☆`60`
- [hungryrobot1/MCP-PIF](https://github.com/hungryrobot1/MCP-PIF) — Personal intelligence framework in Haskell ☆`57`
- [majiayu000/remem](https://github.com/majiayu000/remem) — Local memory for long coding sessions, with an audit trail ☆`33`
- [nicholasglazer/gnosis-mcp](https://github.com/nicholasglazer/gnosis-mcp) — Searchable docs, in SQLite by default or PostgreSQL ☆`31`
- [Yuchen20/Memory-Plus](https://github.com/Yuchen20/Memory-Plus) — Enhanced persistent memory management ☆`56`
- [knaisoma/data-olympus](https://github.com/knaisoma/data-olympus) — Knowledge-base format with a single-writer server and CLI ☆`30`
- [novyxlabs/novyx-mcp](https://github.com/novyxlabs/novyx-mcp) — Governed actions, shared memory, audit and rollback ☆`29`
- [T1nker-1220/memories-with-lessons-mcp-server](https://github.com/T1nker-1220/memories-with-lessons-mcp-server) — Memory server extended with lessons ☆`52`
- [mnemoverse/mcp-memory-server](https://github.com/mnemoverse/mcp-memory-server) — Hosted memory that re-ranks recall by reported outcomes ☆`28`
- [jagoff/memo](https://github.com/jagoff/memo) — Local markdown memory so a coding agent keeps what it learned ☆`26`
- [Siddhant-K-code/mcp-apple-notes](https://github.com/Siddhant-K-code/mcp-apple-notes) — MCP server for apple notes ☆`25`
- [Siddhant-K-code/memory-journal-mcp-server](https://github.com/Siddhant-K-code/memory-journal-mcp-server) — Search and analyze an iCloud photo library ☆`25`
- [masondelan/selvedge](https://github.com/masondelan/selvedge) — Why a decision was made, what was rejected, and the history ☆`26`
- [JamesANZ/memory-mcp](https://github.com/JamesANZ/memory-mcp) — Shared memory store and retrieval for multiple LLMs ☆`23`
- [jamjet-labs/jamjet](https://github.com/jamjet-labs/jamjet) — Block unsafe tool calls, require approval and keep an audit log ☆`23`
- [olgasafonova/mediawiki-mcp-server](https://github.com/olgasafonova/mediawiki-mcp-server) — Search, read and edit a MediaWiki wiki ☆`23`
- [SaravananJaichandar/world-model-mcp](https://github.com/SaravananJaichandar/world-model-mcp) — Signed hash-chained audit of coding-agent actions ☆`24`
- [get-engram/engram](https://github.com/get-engram/engram) — Searchable long-term memory for agents ☆`22`
- [terrizoaguimor/celiums-memory](https://github.com/terrizoaguimor/celiums-memory) — Memory, a journal and an ethics layer for agents ☆`23`
- [Destrayon/Connapse](https://github.com/Destrayon/Connapse) — Self-hosted knowledge base with hybrid search and permissions ☆`22`
- [Mnemosyne-OS/Mnemosyne-Neural-OS](https://github.com/Mnemosyne-OS/Mnemosyne-Neural-OS) — Choose what enters and leaves searchable memory ☆`22`
- [VonderVuflya/Yggdrasil](https://github.com/VonderVuflya/Yggdrasil) — Local memory in SQLite and markdown, de-duplicated ☆`22`
- [hjqcan/GoodMemory](https://github.com/hjqcan/GoodMemory) — Local memory for apps and coding agents, with an audit trail ☆`20`
- [JinNing6/Noosphere](https://github.com/JinNing6/Noosphere) — Discover and publish agent skills, and let agents message each other ☆`18`
- [ihorponom/agentpack](https://github.com/ihorponom/agentpack) — Ledger of decisions, evidence and checkpoints ☆`18`
- [AtlasCloudAI/mcp-server](https://github.com/AtlasCloudAI/mcp-server) — Image, video and LLM APIs through Atlas Cloud ☆`17`
- [graphpilot-oss/graphpilot](https://github.com/graphpilot-oss/graphpilot) — Index a repo once, then ask about symbols and call edges ☆`17`
- [skydeckai/mcp-server-rememberizer](https://github.com/skydeckai/mcp-server-rememberizer) — An MCP Server to enable global access to Rememberizer ☆`36`
- [michielinksee/linksee-memory](https://github.com/michielinksee/linksee-memory) — Local cross-agent memory, with a cache of file diffs ☆`16`
- [remembra-ai/remembra](https://github.com/remembra-ai/remembra) — Hand the next coding agent a summary built from git facts ☆`16`
- [epicsagas/alcove](https://github.com/epicsagas/alcove) — Hybrid search over private project docs for coding agents ☆`16`
- [stagsz/Unconventional-thinking](https://github.com/stagsz/Unconventional-thinking) — Unconventional solutions kept out of the main context ☆`30`
- [ryanjoachim/mcp-rtfm](https://github.com/ryanjoachim/mcp-rtfm) — Generate the manual a project is missing ☆`34`
- [9Ninety/MCPNotes](https://github.com/9Ninety/MCPNotes) — Simple notes an assistant can record and look up ☆`37`
- [Sivan22/mcp-sefaria-server](https://github.com/Sivan22/mcp-sefaria-server) — Fetch and read Jewish texts through the API of Sefaria.org ☆`35`
- [paladini/mcp-me](https://github.com/paladini/mcp-me) — Local profile so an assistant knows who you are ☆`21`
- [grooverLab/fable](https://github.com/grooverLab/fable) — Local transcript of Claude Code sessions you can search exactly ☆`19`
- [TheStack-ai/jarvis-orb](https://github.com/TheStack-ai/jarvis-orb) — 3D orb that shows Claude Code reasoning as it happens ☆`24`
- [SecretiveShell/MCP-llms-txt](https://github.com/SecretiveShell/MCP-llms-txt) — Pull llms.txt documentation into the conversation ☆`26`
- [dengls24/annota](https://github.com/dengls24/annota) — Read a PDF, highlight findings and write structured notes ☆`20`
- [besslframework-stack/project-tessera](https://github.com/besslframework-stack/project-tessera) — Local memory of what a conversation learned ☆`18`
- [RyoJerryYu/mcp-server-memos-py](https://github.com/RyoJerryYu/mcp-server-memos-py) — Search and manage notes on a Memos server ☆`21`
- [ssmirnovpro/extended-memory-mcp](https://github.com/ssmirnovpro/extended-memory-mcp) — Cross-session persistent memory for Claude Desktop ☆`18`
- [hubertciebiada/context-crystallizer](https://github.com/hubertciebiada/context-crystallizer) — Large repos into AI-consumable knowledge for agents ☆`17`
### RAG

- [heymrun/heym](https://github.com/heymrun/heym) — Run agent workflows, inspect each step and keep a person in control ☆`1,543`
- [apecloud/ApeRAG](https://github.com/apecloud/ApeRAG) — Production GraphRAG with multi-modal ☆`1,319`
- [Minima-AI-Inc/minima](https://github.com/Minima-AI-Inc/minima) — On-premises conversational RAG with configurable containers ☆`1,056`
- [GreatScottyMac/context-portal](https://github.com/GreatScottyMac/context-portal) — Memory bank MCP with knowledge graph ☆`768`
- [shinpr/mcp-local-rag](https://github.com/shinpr/mcp-local-rag) — MCP server for local RAG operations ☆`429`
- [graphlit/graphlit-mcp-server](https://github.com/graphlit/graphlit-mcp-server) — Model Context Protocol (MCP) Server for Graphlit Platform ☆`379`
- [lyonzin/knowledge-rag](https://github.com/lyonzin/knowledge-rag) — Local RAG with hybrid search and reranking, no API key ☆`305`
- [hannesrudolph/mcp-ragdocs](https://github.com/hannesrudolph/mcp-ragdocs) — MCP server for RAG document retrieval ☆`263`
- [jztan/pdf-mcp](https://github.com/jztan/pdf-mcp) — Search large PDFs by meaning and by keyword, a file or a folder ☆`170`
- [needle-ai/needle-mcp](https://github.com/needle-ai/needle-mcp) — Find perfect leads and run outreach campaigns on Linkedin, email, Instagram and more. ☆`104`
- [newideas99/Deepseek-Thinking-Claude-3.5-Sonnet-CLINE-MCP](https://github.com/newideas99/Deepseek-Thinking-Claude-3.5-Sonnet-CLINE-MCP) — Reason, then a second model ☆`115`
- [arthurpanhku/DocSentinel](https://github.com/arthurpanhku/DocSentinel) — Review security documents and questionnaires for gaps ☆`90`
- [ragieai/ragie-mcp-server](https://github.com/ragieai/ragie-mcp-server) — Ragie Model Context Protocol Server ☆`90`
- [tomohiro-owada/devrag](https://github.com/tomohiro-owada/devrag) — Semantic search over markdown files ☆`64`
- [pinecone-io/assistant-mcp](https://github.com/pinecone-io/assistant-mcp) — Pinecone Assistant MCP server ☆`45`
- [2015xli/clangd-graph-rag](https://github.com/2015xli/clangd-graph-rag) — Graph RAG over C and C++ source, built on clangd ☆`63`
- [jurasofish/mcpunk](https://github.com/jurasofish/mcpunk) — MCP tools for Roaming RAG ☆`56`
- [Thanatos9404/llmslim](https://github.com/Thanatos9404/llmslim) — Long-term memory and compression without another model ☆`25`
- [nonatofabio/local_faiss_mcp](https://github.com/nonatofabio/local_faiss_mcp) — Local FAISS MCP - semantic search for Claude/Copilot ☆`36`
- [pipeshub-ai/mcp-server](https://github.com/pipeshub-ai/mcp-server) — Ask across Jira, Slack, GitHub and Drive with your own rights ☆`17`
- [vectara/vectara-mcp](https://github.com/vectara/vectara-mcp) — Open source MCP server for Vectara ☆`30`
- [agentset-ai/mcp-server](https://github.com/agentset-ai/mcp-server) — Agentset MCP Server - Build RAG with Agentic superpowers ☆`30`
- [renl/mcp-rag-local](https://github.com/renl/mcp-rag-local) — Local RAG with Ollama embeddings and ChromaDB ☆`18`
## AI Platforms

- [rocketride-org/rocketride-server](https://github.com/rocketride-org/rocketride-server) — Pipeline engine for LLM workflows, with a C++ core ☆`20,061`
- [Kiln-AI/Kiln](https://github.com/Kiln-AI/Kiln) — Build AI systems with Evals, RAG, Agents, fine-tuning ☆`5,268`
- [paiml/paiml-mcp-agent-toolkit](https://github.com/paiml/paiml-mcp-agent-toolkit) — Pragmatic AI Labs toolkit for deterministic agents ☆`171`
- [TheRaLabs/legion-mcp](https://github.com/TheRaLabs/legion-mcp) — MCP server for Legion AI platform ☆`95`
- [atlanhq/agent-toolkit](https://github.com/atlanhq/agent-toolkit) — Atlan AI Agent Toolkit ☆`42`
- [PromptExecution/just-mcp](https://github.com/PromptExecution/just-mcp) — mcp server for just ☆`60`
- [Mitek99/deepview-mcp](https://github.com/Mitek99/deepview-mcp) — MCP server for DeepView AI analysis ☆`65`
- [StitchAI/stitch-ai-mcp](https://github.com/StitchAI/stitch-ai-mcp) — Decentralized Knowledge Hub for AI ☆`39`
- [PV-Bhat/gemsuite-mcp](https://github.com/PV-Bhat/gemsuite-mcp) — MCP server for GemSuite tools ☆`32`
- [DumplingAI/mcp-server-dumplingai](https://github.com/DumplingAI/mcp-server-dumplingai) — MCP (Model Context Protocol) server for Dumpling AI ☆`30`
- [sequa-ai/sequa-mcp](https://github.com/sequa-ai/sequa-mcp) — MCP server for Sequa AI platform ☆`22`
## Aggregators & Gateways

### Aggregators

- [mindsdb/mindshub](https://github.com/mindsdb/mindshub) — Query Engine for AI Analytics - self-reasoning agents on live data ☆`39,854`
- [metatool-ai/metamcp](https://github.com/metatool-ai/metamcp) — MCP Aggregator, Orchestrator, Middleware, Gateway in one docker ☆`2,762`
- [mcpjungle/MCPJungle](https://github.com/mcpjungle/MCPJungle) — One place to manage & connect to all your MCP servers ☆`1,619`
- [1mcp-app/agent](https://github.com/1mcp-app/agent) — Unified MCP server aggregator ☆`530`
- [K-Dense-AI/claude-skills-mcp](https://github.com/K-Dense-AI/claude-skills-mcp) — Claude Agent Skills vector search ☆`411`
- [BlockRunAI/blockrun-mcp](https://github.com/BlockRunAI/blockrun-mcp) — Search, markets and crypto, paid per call with x402 ☆`390`
- [boltmcp/boltmcp](https://github.com/boltmcp/boltmcp) — Create and run custom MCP servers on your own machines ☆`372`
- [sitbon/magg](https://github.com/sitbon/magg) — Magg: The MCP Aggregator ☆`143`
- [wanaku-ai/wanaku](https://github.com/wanaku-ai/wanaku) — Wanaku Governed Action Proxy for AI Agents ☆`135`
- [badkk/awesome-crypto-mcp-servers](https://github.com/badkk/awesome-crypto-mcp-servers) — A collection of crypto MCP servers. ☆`147`
- [portel-dev/ncp](https://github.com/portel-dev/ncp) — Natural Context Provider with smart MCP tool loading ☆`101`
- [nguyenvanduocit/all-in-one-model-context-protocol](https://github.com/nguyenvanduocit/all-in-one-model-context-protocol) — GitLab, Jira, Confluence, YouTube ☆`107`
- [VeriTeknik/pluggedin-mcp](https://github.com/VeriTeknik/pluggedin-mcp) — Plugged.in MCP Server manages all your other MCPs in one MCP. ☆`52`
- [bh-rat/context-awesome](https://github.com/bh-rat/context-awesome) — awesome-lists now available as CLI & MCP server for your agent. ☆`61`
- [profullstack/mcp-server](https://github.com/profullstack/mcp-server) — Modular skeleton for implementing an MCP server ☆`45`
- [waystation-ai/mcp](https://github.com/waystation-ai/mcp) — No-code secure MCP integration hub ☆`66`
- [hamidra/yamcp](https://github.com/hamidra/yamcp) — Local MCP workspace organization ☆`67`
- [gotoolkits/mcp-difyworkflow-server](https://github.com/gotoolkits/mcp-difyworkflow-server) — MCP server for Dify workflow invocation ☆`62`
- [Wolido/OpenAaaS](https://github.com/Wolido/OpenAaaS) — Agents that run next to the data, in a local Docker sandbox ☆`32`
- [arikusi/deepseek-mcp-server](https://github.com/arikusi/deepseek-mcp-server) — Chat, reasoning and tool calls on DeepSeek models ☆`26`
- [glenngillen/mcpmcp-server](https://github.com/glenngillen/mcpmcp-server) — MCP server aggregator and router ☆`45`
- [tadas-github/a2asearch-mcp](https://github.com/tadas-github/a2asearch-mcp) — Search for agents, MCP servers, CLIs and skills ☆`21`
- [membranehq/mcp-server](https://github.com/membranehq/mcp-server) — MCP Server for Membrane ☆`36`
- [nazar256/combine-mcp](https://github.com/nazar256/combine-mcp) — MCP aggregator combining multiple servers into one interface ☆`35`
- [Markgatcha/universal-mcp-toolkit](https://github.com/Markgatcha/universal-mcp-toolkit) — The canonical open-source monorepo for production-ready MCP servers. ☆`16`
- [wojtyniak/mcp-mcp](https://github.com/wojtyniak/mcp-mcp) — Meta-MCP for tool discovery and provisioning ☆`23`
- [agree-able/room-mcp](https://github.com/agree-able/room-mcp) — Coordinate agents using rooms ☆`23`
- [isaac-levine/forage](https://github.com/isaac-levine/forage) — Agents find, install and learn new MCP tools on their own ☆`19`
### Gateways & Proxies

- [apache/apisix](https://github.com/apache/apisix) — The Cloud-Native API Gateway and AI Gateway ☆`17,311`
- [maximhq/bifrost](https://github.com/maximhq/bifrost) — Open-source gateway for models, MCP and agents, with failover ☆`9,488`
- [IBM/mcp-context-forge](https://github.com/IBM/mcp-context-forge) — Gateway and registry in front of MCP, A2A and REST APIs ☆`4,784`
- [sparfenyuk/mcp-proxy](https://github.com/sparfenyuk/mcp-proxy) — A bridge between Streamable HTTP and stdio MCP transports ☆`2,822`
- [stacklok/toolhive](https://github.com/stacklok/toolhive) — Runtime and gateway for deploying MCP servers in containers ☆`2,334`
- [AmoyLab/Unla](https://github.com/AmoyLab/Unla) — Turn existing APIs and MCP servers into MCP endpoints ☆`2,252`
- [docker/mcp-gateway](https://github.com/docker/mcp-gateway) — docker mcp CLI plugin / MCP Gateway ☆`1,628`
- [obot-platform/obot](https://github.com/obot-platform/obot) — Complete AI Governance Platform from Obot AI ☆`1,177`
- [HelpCode-ai/anythingmcp](https://github.com/HelpCode-ai/anythingmcp) — Self-hosted gateway from REST, SOAP, GraphQL, and SQL ☆`768`
- [tbxark/mcp-proxy](https://github.com/tbxark/mcp-proxy) — Aggregate multiple MCP servers via HTTP ☆`744`
- [TheLunarCompany/lunar](https://github.com/TheLunarCompany/lunar) — lunar.dev: Agent native MCP Gateway for governance and security ☆`509`
- [activeing123/mcptoon](https://github.com/activeing123/mcptoon) — CLI that compresses MCP tool schemas and discovers servers ☆`428`
- [decocms/studio](https://github.com/decocms/studio) — Control plane to connect tools, run agents and track spend ☆`416`
- [smart-mcp-proxy/mcpproxy-go](https://github.com/smart-mcp-proxy/mcpproxy-go) — Supercharge AI Agents, Safely ☆`413`
- [Nexus-Router/nexus](https://github.com/Nexus-Router/nexus) — Govern & Secure your AI ☆`438`
- [lasso-security/mcp-gateway](https://github.com/lasso-security/mcp-gateway) — Plugin gateway that orchestrates other MCP servers ☆`402`
- [punkpeye/mcp-proxy](https://github.com/punkpeye/mcp-proxy) — HTTP and SSE proxy for MCP servers that speak stdio ☆`293`
- [agoda-com/api-agent](https://github.com/agoda-com/api-agent) — Universal MCP server for GraphQL/REST APIs ☆`299`
- [btsouth/toolport](https://github.com/btsouth/toolport) — One local gateway for MCP servers, with secrets in the keychain ☆`238`
- [api7/aisix](https://github.com/api7/aisix) — Rust AI gateway with routing, guardrails, cache and limits ☆`217`
- [ssut/Remote-MCP](https://github.com/ssut/Remote-MCP) — Type-safe solution for remote MCP communication ☆`207`
- [agiletec-inc/airis-mcp-gateway](https://github.com/agiletec-inc/airis-mcp-gateway) — MCP gateway for routing agent tool calls ☆`173`
- [sxhxliang/mcp-access-point](https://github.com/sxhxliang/mcp-access-point) — Convert any web server to MCP instantly ☆`185`
- [toolprint/hypertool-mcp](https://github.com/toolprint/hypertool-mcp) — Expose tools based on Agent Persona ☆`155`
- [lightconetech/mcp-gateway](https://github.com/lightconetech/mcp-gateway) — A gateway demo for MCP SSE Server ☆`153`
- [VeriTeknik/pluggedin-mcp-proxy](https://github.com/VeriTeknik/pluggedin-mcp-proxy) — Unified MCP proxy managing multiple MCPs ☆`139`
- [acehoss/mcp-gateway](https://github.com/acehoss/mcp-gateway) — Expose STDIO MCP servers over HTTP and a REST API ☆`130`
- [kfirtoledo/multi-mcp](https://github.com/kfirtoledo/multi-mcp) — One server that routes to several backend MCP servers ☆`111`
- [MikkoParkkola/mcp-gateway](https://github.com/MikkoParkkola/mcp-gateway) — Many MCP servers behind one small, fixed context cost ☆`84`
- [boilingdata/mcp-server-and-gw](https://github.com/boilingdata/mcp-server-and-gw) — STDIO-to-HTTP gateway, with an example server and client ☆`91`
- [hasmcp/hasmcp-ce](https://github.com/hasmcp/hasmcp-ce) — HasMCP Community Edition ☆`63`
- [Rendeverance/toolfunnel](https://github.com/Rendeverance/toolfunnel) — Host your own tools and forward others, with a smaller context ☆`38`
- [phildougherty/mcp-compose](https://github.com/phildougherty/mcp-compose) — Run MCP servers as Docker containers, with one gateway ☆`58`
- [Cognipeer/console](https://github.com/Cognipeer/console) — Self-hosted gateway for model routing, RAG, guardrails and traces ☆`27`
- [Consiliency/pmcp](https://github.com/Consiliency/pmcp) — Gateway that reveals MCP tools gradually, to save context ☆`23`
- [oidebrett/mcpauth](https://github.com/oidebrett/mcpauth) — MCP Gateway for external Authentication and Authorization ☆`32`
- [cgrtml/reasongate](https://github.com/cgrtml/reasongate) — Block prompt injection and record why each request was blocked ☆`17`
- [adiom-data/grpcmcp](https://github.com/adiom-data/grpcmcp) — MCP Server for gRPC ☆`29`
- [universal-mcp/universal-mcp](https://github.com/universal-mcp/universal-mcp) — Middleware for API applications ☆`26`
- [pyroprompts/mcp-stdio-to-streamable-http-adapter](https://github.com/pyroprompts/mcp-stdio-to-streamable-http-adapter) — STDIO to Streamable HTTP proxy ☆`26`
- [webrix-ai/secure-mcp-gateway](https://github.com/webrix-ai/secure-mcp-gateway) — Secure OAuth gateway for MCP authentication ☆`22`
- [nick1udwig/ws-mcp](https://github.com/nick1udwig/ws-mcp) — MCP server with WebSocket transport ☆`21`
### Platforms & Registries

- [modelcontextprotocol/registry](https://github.com/modelcontextprotocol/registry) — Community registry of MCP servers ☆`7,455`
- [archestra-ai/archestra](https://github.com/archestra-ai/archestra) — Enterprise AI guardrails, registry, gateway, and orchestrator ☆`4,437`
- [microsoft/mcp](https://github.com/microsoft/mcp) — Catalog of official Microsoft MCP servers ☆`3,843`
- [metorial/metorial](https://github.com/metorial/metorial) — Connect any AI model to 1200+ integrations (MCP, CLI, API) ☆`3,377`
- [chatmcp/mcpso](https://github.com/chatmcp/mcpso) — directory for Awesome MCP Servers ☆`2,116`
- [julien040/anyquery](https://github.com/julien040/anyquery) — SQL queries for GitHub, Notion, +40 more ☆`1,791`
- [jaw9c/awesome-remote-mcp-servers](https://github.com/jaw9c/awesome-remote-mcp-servers) — Remote MCP Servers ☆`1,183`
- [docker/mcp-registry](https://github.com/docker/mcp-registry) — Official Docker MCP registry ☆`583`
- [pathintegral-institute/mcpm.sh](https://github.com/pathintegral-institute/mcpm.sh) — CLI to search, install and configure MCP servers ☆`1,021`
- [apappascs/mcp-servers-hub](https://github.com/apappascs/mcp-servers-hub) — Catalog of open-source MCP servers ☆`330`
- [liuyoshio/mcp-compass](https://github.com/liuyoshio/mcp-compass) — MCP discovery and recommendation ☆`250`
- [juspay/neurolink](https://github.com/juspay/neurolink) — Universal AI platform with MCP and multi-provider support ☆`169`
- [integromat/make-mcp-server](https://github.com/integromat/make-mcp-server) — Make MCP Server ☆`174`
- [Jeamee/MCPHub-Desktop](https://github.com/Jeamee/MCPHub-Desktop) — Desktop APP for Discover and Install MCP Servers ☆`148`
- [rust-mcp-stack/mcp-discovery](https://github.com/rust-mcp-stack/mcp-discovery) — CLI for discovering MCP server capabilities ☆`87`
- [matthewdcage/cursor-mcp-installer](https://github.com/matthewdcage/cursor-mcp-installer) — Install MCPs in Cursor from git URL ☆`75`
- [useparagon/paragon-mcp](https://github.com/useparagon/paragon-mcp) — Access 130+ SaaS integrations via ActionKit ☆`48`
- [aiagenta2z/onekey-gateway](https://github.com/aiagenta2z/onekey-gateway) — One registry for commercial APIs, skills and MCP servers ☆`52`
- [robhunter/agentdeals](https://github.com/robhunter/agentdeals) — Free tiers and prices for developer infrastructure ☆`24`
- [VeyraX/veyrax-mcp](https://github.com/VeyraX/veyrax-mcp) — VeyraX unified tool access via single MCP ☆`48`
- [Data-Everything/mcp-server-templates](https://github.com/Data-Everything/mcp-server-templates) — Docker, Kubernetes, CLI, and HTTP MCP templates ☆`22`
- [bytesagain/ai-skills](https://github.com/bytesagain/ai-skills) — AI Agent Skills for Claude Code, Manus, OpenClaw & more ☆`16`
## Browser Automation

### AI Automation

- [Skyvern-AI/skyvern](https://github.com/Skyvern-AI/skyvern) — Automate browser based workflows with AI ☆`23,376`
- [nottelabs/notte](https://github.com/nottelabs/notte) — Framework to build web agents ☆`2,058`
- [kontext-security/browser-use-mcp-server](https://github.com/kontext-security/browser-use-mcp-server) — Browse the web, directly from Cursor etc. ☆`849`
- [imprvhub/mcp-browser-agent](https://github.com/imprvhub/mcp-browser-agent) — MCP server for autonomous browser automation with Claude ☆`43`
- [desplega-ai/qa-use](https://github.com/desplega-ai/qa-use) — Agent-first E2E testing CLI ☆`29`
### Browser Tools

- [BrowserMCP/mcp](https://github.com/BrowserMCP/mcp) — Browser control for AI applications ☆`7,332`
- [LvcidPsyche/auto-browser](https://github.com/LvcidPsyche/auto-browser) — Browser agent that can hand control back to a person ☆`925`
- [nirholas/XActions](https://github.com/nirholas/XActions) — Scrape and automate X without paying for the API ☆`650`
- [merajmehrabi/puppeteer-mcp-server](https://github.com/merajmehrabi/puppeteer-mcp-server) — Automate a new browser or an existing Chrome window ☆`489`
- [fullselfbrowsing/FSB](https://github.com/fullselfbrowsing/FSB) — DOM-first AI browser automation for Chrome and MCP clients. ☆`205`
- [swimmwatch/cloakbrowser-mcp](https://github.com/swimmwatch/cloakbrowser-mcp) — Playwright MCP on CloakBrowser Chromium ☆`178`
- [hanzili/comet-mcp](https://github.com/hanzili/comet-mcp) — MCP Server connecting to Perplexity Comet browser ☆`181`
- [onllm-dev/onUI](https://github.com/onllm-dev/onUI) — Annotation-first UI pair programming in the browser ☆`108`
- [Agent360dk/browser-mcp](https://github.com/Agent360dk/browser-mcp) — Browser automation that can pause, ask you, then continue ☆`62`
- [ofershap/real-browser-mcp](https://github.com/ofershap/real-browser-mcp) — Control your real Chrome, with the logins already in it ☆`59`
- [ndthanhdev/mcp-browser-kit](https://github.com/ndthanhdev/mcp-browser-kit) — AI assistants interact with local browser ☆`55`
- [webdriverio/mcp](https://github.com/webdriverio/mcp) — Browsers and mobile apps through WebdriverIO ☆`44`
- [2captcha/2captcha-mcp](https://github.com/2captcha/2captcha-mcp) — Captcha solving, scraping and browser automation for agents ☆`40`
- [BeatAPI/BeatBrowser](https://github.com/BeatAPI/BeatBrowser) — Let an agent drive the Chrome you are already signed into ☆`39`
- [ymw0407/auth-fetch-mcp](https://github.com/ymw0407/auth-fetch-mcp) — Fetch a page that requires the user to be signed in ☆`36`
- [samson-art/transcriptor-mcp](https://github.com/samson-art/transcriptor-mcp) — Transcripts, chapters and frames from online video ☆`24`
- [SanggonBoy/PyreCrawl](https://github.com/SanggonBoy/PyreCrawl) — Self-hosted scrape, crawl, search and monitor, with no API key ☆`23`
- [BB-fat/browser-use-rs](https://github.com/BB-fat/browser-use-rs) — Rust-based browser automation MCP server ☆`41`
- [nnemirovsky/iwdp-mcp](https://github.com/nnemirovsky/iwdp-mcp) — Debug iOS Safari through ios-webkit-debug-proxy ☆`21`
- [ilien-dev/svipall](https://github.com/ilien-dev/svipall) — Local markdown extraction, site crawls and keyless search ☆`20`
- [drisplabs/browser-mcp](https://github.com/drisplabs/browser-mcp) — Browser automation that uses semantic snapshots, not raw HTML ☆`19`
- [LeonTing1010/tap](https://github.com/LeonTing1010/tap) — Record a logged-in browser task once and replay it without a model ☆`18`
- [autokeren/ghostfox](https://github.com/autokeren/ghostfox) — Ghostfox - the browser that can SEE: Gecko-native agent browser. 71 MCP tools, unhookable a11y/compositor vision, captcha solvers, pagedownload, Android dial-out, visual QA for ☆`17`
- [protostatis/unbrowser](https://github.com/protostatis/unbrowser) — Lightweight browser for agents, with a path to a full browser ☆`17`
### Cloud Services

- [hyperbrowserai/mcp](https://github.com/hyperbrowserai/mcp) — A MCP server implementation for hyperbrowser ☆`793`
- [browserstack/mcp-server](https://github.com/browserstack/mcp-server) — BrowserStack's Official MCP Server ☆`154`
- [kernel/kernel-mcp-server](https://github.com/kernel/kernel-mcp-server) — Secure cloud-browser automation on Kernel ☆`39`
- [browserless/browserless-mcp](https://github.com/browserless/browserless-mcp) — Official MCP server for the Browserless.io ☆`18`
### DevTools

- [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) — Chrome DevTools for coding agents ☆`55,085`
- [mozilla/firefox-devtools-mcp](https://github.com/mozilla/firefox-devtools-mcp) — MCP server for Firefox DevTools integration ☆`561`
- [eyalzh/browser-control-mcp](https://github.com/eyalzh/browser-control-mcp) — Browser control via extension for AI agents ☆`346`
- [achiya-automation/safari-mcp](https://github.com/achiya-automation/safari-mcp) — Automate Safari through AppleScript while keeping logins ☆`240`
### Playwright

- [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) — Playwright MCP server ☆`39,472`
- [executeautomation/mcp-playwright](https://github.com/executeautomation/mcp-playwright) — MCP server for Playwright browser testing ☆`5,682`
- [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) — Stealth Firefox browsing that avoids anti-bot checks ☆`878`
- [vostride/agent-qa](https://github.com/vostride/agent-qa) — Natural-language web and mobile tests that adapt ☆`850`
- [VikashLoomba/MCP-Server-Playwright](https://github.com/VikashLoomba/MCP-Server-Playwright) — MCP server for browser automation using Playwright ☆`297`
- [blackwhite084/playwright-plus-python-mcp](https://github.com/blackwhite084/playwright-plus-python-mcp) — Enhanced Playwright browser automation ☆`188`
- [acunningham-ship-it/veilbrowser](https://github.com/acunningham-ship-it/veilbrowser) — Stealth Chrome for agents over CDP, without Playwright ☆`49`
- [wukan1986/mcp_query_table](https://github.com/wukan1986/mcp_query_table) — query table from some websites, support MCP ☆`60`
- [kimtth/mcp-aoai-web-browsing](https://github.com/kimtth/mcp-aoai-web-browsing) — Azure OpenAI with Playwright browser control ☆`35`
- [mcpware/pagecast](https://github.com/mcpware/pagecast) — Record a browser page as a GIF or video ☆`54`
- [random-robbie/mcp-web-browser](https://github.com/random-robbie/mcp-web-browser) — Headless browsing with Playwright ☆`27`
- [twolven/mcp-server-puppeteer-py](https://github.com/twolven/mcp-server-puppeteer-py) — Browser automation with Playwright in Python ☆`19`
- [AishwaryShrivastav/vibe-testing](https://github.com/AishwaryShrivastav/vibe-testing) — Code-aware browser tests with regression memory ☆`18`
- [sh6drack/zen-mcp](https://github.com/sh6drack/zen-mcp) — Control Zen Browser over a WebSocket, without Selenium ☆`28`
## CLI Tools

- [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) — Terminal control, file search, diff editing ☆`10,283`
- [f/mcptools](https://github.com/f/mcptools) — CLI for calling MCP servers over stdio or HTTP ☆`1,629`
- [classfang/ssh-mcp-server](https://github.com/classfang/ssh-mcp-server) — SSH MCP server included in official repo ☆`1,032`
- [20000419/fauxnix](https://github.com/20000419/fauxnix) — Run Linux-style commands on Windows by translating bash to PowerShell ☆`900`
- [tufantunc/ssh-mcp](https://github.com/tufantunc/ssh-mcp) — SSH control for Linux servers ☆`870`
- [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp) — iTerm command execution for REPL/CLI ☆`571`
- [bvisible/mcp-ssh-manager](https://github.com/bvisible/mcp-ssh-manager) — SSH commands and file copy, with approval ☆`537`
- [baryhuang/mcp-remote-macos-use](https://github.com/baryhuang/mcp-remote-macos-use) — AI agent for full Mac control ☆`491`
- [peakmojo/applescript-mcp](https://github.com/peakmojo/applescript-mcp) — Execute AppleScript for Mac control ☆`467`
- [wong2/mcp-cli](https://github.com/wong2/mcp-cli) — A CLI inspector for the Model Context Protocol ☆`448`
- [AmrDab/clawdcursor](https://github.com/AmrDab/clawdcursor) — Desktop control from screen text and accessibility names ☆`407`
- [domdomegg/computer-use-mcp](https://github.com/domdomegg/computer-use-mcp) — Full computer control for AI models ☆`398`
- [claude-did-this/MCPControl](https://github.com/claude-did-this/MCPControl) — MCP server for Windows OS automation ☆`334`
- [nickgnd/tmux-mcp](https://github.com/nickgnd/tmux-mcp) — A MCP server for our beloved terminal multiplexer tmux. ☆`306`
- [g0t4/mcp-server-commands](https://github.com/g0t4/mcp-server-commands) — MCP server to run commands (runProcess tool) ☆`237`
- [lacs-project/sysknife](https://github.com/lacs-project/sysknife) — Typed Linux admin actions with an audit log and rollback ☆`213`
- [tumf/mcp-shell-server](https://github.com/tumf/mcp-shell-server) — Shell execution with whitelisted commands ☆`201`
- [dvcrn/mcp-server-siri-shortcuts](https://github.com/dvcrn/mcp-server-siri-shortcuts) — MCP for calling Siri Shorcuts from LLMs ☆`195`
- [AB498/computer-control-mcp](https://github.com/AB498/computer-control-mcp) — Mouse, keyboard, OCR via PyAutoGUI ☆`174`
- [MladenSU/cli-mcp-server](https://github.com/MladenSU/cli-mcp-server) — CLI with secure execution and custom policies ☆`179`
- [AppachiTech/suvadu](https://github.com/AppachiTech/suvadu) — Local shell history that also records what agents ran ☆`127`
- [sonirico/mcp-shell](https://github.com/sonirico/mcp-shell) — Secure, auditable shell commands for AI ☆`112`
- [automateyournetwork/pyATS_MCP](https://github.com/automateyournetwork/pyATS_MCP) — An MCP Server for pyATS (experimental) ☆`90`
- [nylas/cli](https://github.com/nylas/cli) — Nylas email, calendar and contacts from the command line ☆`81`
- [danmartuszewski/hop](https://github.com/danmartuszewski/hop) — SSH connection manager with a terminal UI and an MCP server ☆`64`
- [NakaokaRei/swift-mcp-gui](https://github.com/NakaokaRei/swift-mcp-gui) — Keyboard and mouse control on macOS ☆`61`
- [inercia/MCPShell](https://github.com/inercia/MCPShell) — Use shell scripts as MCP tools ☆`72`
- [ooples/mcp-console-automation](https://github.com/ooples/mcp-console-automation) — MCP for AI-driven console automation and monitoring ☆`54`
- [nihalxkumar/arch-mcp](https://github.com/nihalxkumar/arch-mcp) — Arch Linux MCP (Model Context Protocol) Server ☆`61`
- [InsForge/insforge-mcp](https://github.com/InsForge/insforge-mcp) — MCP server for InsForge - full-stack builders for coding agents ☆`38`
- [munimtechnologies/munim-computer-use](https://github.com/munimtechnologies/munim-computer-use) — Desktop control from accessibility APIs ☆`35`
- [YawLabs/tailscale-mcp](https://github.com/YawLabs/tailscale-mcp) — Tailscale MCP server for managing your tailnet from AI assistants ☆`35`
- [JonathanRReed/Apple-MCPs](https://github.com/JonathanRReed/Apple-MCPs) — Mail, Calendar, Reminders, Messages and other Mac apps ☆`34`
- [zb-ss/servonaut](https://github.com/zb-ss/servonaut) — One terminal UI for AWS, Hetzner, OVH and your own servers ☆`32`
- [Harusame64/desktop-touch-mcp](https://github.com/Harusame64/desktop-touch-mcp) — Drive Windows apps by name, not by pixels ☆`25`
- [maxim-saplin/mcp_safe_local_python_executor](https://github.com/maxim-saplin/mcp_safe_local_python_executor) — Safe Python executor from smolagents ☆`48`
- [faze79/WPFVisualTreeMcp](https://github.com/faze79/WPFVisualTreeMcp) — Inspect a WPF visual tree and record the steps as tests ☆`21`
- [raychao-oao/pty-mcp](https://github.com/raychao-oao/pty-mcp) — Interactive shells, SSH and serial ports ☆`20`
- [fixed-width/glass](https://github.com/fixed-width/glass) — Build, see and debug native GUI apps in a loop ☆`20`
- [OthmaneBlial/term_mcp_deepseek](https://github.com/OthmaneBlial/term_mcp_deepseek) — Approve terminal commands after risk and access checks ☆`18`
- [Beer-Bears/scaffold](https://github.com/Beer-Bears/scaffold) — Structural RAG system for large codebases ☆`19`
- [ostapondo/Plonk](https://github.com/ostapondo/Plonk) — Mac toolbox for screenshots, OCR, windows and shortcuts ☆`17`
- [ferodrigop/forge](https://github.com/ferodrigop/forge) — Spawn and watch terminal sessions for coding agents ☆`28`
- [PhialsBasement/CMD-MCP-Server](https://github.com/PhialsBasement/CMD-MCP-Server) — CMD command execution for Claude agents ☆`25`
- [aybelatchane/mcp-server-terminal](https://github.com/aybelatchane/mcp-server-terminal) — TUI and CLI automation via Terminal State Tree ☆`21`
- [blakerouse/ssh-mcp](https://github.com/blakerouse/ssh-mcp) — Local SSH host groups and remote command execution ☆`21`
- [amol21p/mcp-interactive-terminal](https://github.com/amol21p/mcp-interactive-terminal) — Interactive terminals: REPLs, SSH and Docker ☆`20`
- [erniebrodeur/mcp-grep](https://github.com/erniebrodeur/mcp-grep) — simple mcp server to wrap the local instance of grep. ☆`25`
- [JoshuaRileyDev/mac-apps-launcher](https://github.com/JoshuaRileyDev/mac-apps-launcher) — Launch and manage macOS applications ☆`19`
## CRM & ERP

- [ivnvxd/mcp-server-odoo](https://github.com/ivnvxd/mcp-server-odoo) — MCP server for Odoo ERP integration ☆`415`
- [saurabhsharma2u/search-console-mcp](https://github.com/saurabhsharma2u/search-console-mcp) — Search Console, Bing Webmaster, AdSense and GA4 ☆`321`
- [explorium-ai/vibeprospecting-mcp](https://github.com/explorium-ai/vibeprospecting-mcp) — B2B lead lists and company research ☆`293`
- [GeLi2001/shopify-mcp](https://github.com/GeLi2001/shopify-mcp) — Shopify API for Claude and Cursor ☆`239`
- [tsmztech/mcp-server-salesforce](https://github.com/tsmztech/mcp-server-salesforce) — Salesforce MCP Server ☆`164`
- [smn2gnt/MCP-Salesforce](https://github.com/smn2gnt/MCP-Salesforce) — MCP Salesforce connector ☆`179`
- [augmnt/augments-mcp-server](https://github.com/augmnt/augments-mcp-server) — MCP server for Augments AI platform ☆`127`
- [tomaspavlin/rohlik-mcp](https://github.com/tomaspavlin/rohlik-mcp) — Shop groceries on Rohlik Group platforms ☆`121`
- [mafzaal/d365fo-client](https://github.com/mafzaal/d365fo-client) — Client for Microsoft Dynamics 365 F&O ☆`41`
- [AiondaDotCom/mcp-salesforce](https://github.com/AiondaDotCom/mcp-salesforce) — Salesforce OAuth and CRUD for any object ☆`17`
- [dsvantien/netsuite-mcp-server](https://github.com/dsvantien/netsuite-mcp-server) — NetSuite ERP records, queries, and operations ☆`22`
- [hmk/attio-mcp-server](https://github.com/hmk/attio-mcp-server) — Attio CRM records and notes management ☆`16`
## Cloud & Infrastructure

### AWS

- [awslabs/mcp](https://github.com/awslabs/mcp) — AWS MCP servers for AI assistants ☆`9,904`
- [towardsthecloud/cloudburn](https://github.com/towardsthecloud/cloudburn) — Block wasteful AWS spend before it ships ☆`1,801`
- [aarora79/aws-cost-explorer-mcp-server](https://github.com/aarora79/aws-cost-explorer-mcp-server) — MCP server for understanding AWS spend ☆`127`
- [rishikavikondala/mcp-server-aws](https://github.com/rishikavikondala/mcp-server-aws) — MCP server for AWS resource operations ☆`127`
- [aws-samples/sample-mcp-server-s3](https://github.com/aws-samples/sample-mcp-server-s3) — Retrieve PDFs and data from AWS S3 ☆`79`
- [groovyBugify/aws-security-mcp](https://github.com/groovyBugify/aws-security-mcp) — Inspect AWS security services and the resources they see ☆`84`
- [localstack/localstack-mcp-server](https://github.com/localstack/localstack-mcp-server) — LocalStack AWS emulation ☆`29`
- [Sidd27/infrawise](https://github.com/Sidd27/infrawise) — AWS resources and drift across databases, queues and functions ☆`22`
- [getnable/finopsmcp](https://github.com/getnable/finopsmcp) — Cloud and AI cost checks an agent can query before it spends ☆`20`
- [baryhuang/mcp-server-aws-resources-python](https://github.com/baryhuang/mcp-server-aws-resources-python) — Run boto3 code to manage AWS resources ☆`24`
### Cloud Platforms

- [google/mcp](https://github.com/google/mcp) — Google MCP ☆`4,696`
- [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) — Cloudflare services management ☆`4,457`
- [microsoft/azure-devops-mcp](https://github.com/microsoft/azure-devops-mcp) — Azure DevOps integration for AI agents ☆`2,085`
- [TencentCloudBase/CloudBase-AI-Toolkit](https://github.com/TencentCloudBase/CloudBase-AI-Toolkit) — Connect CloudBase to AI agents ☆`1,163`
- [GoogleCloudPlatform/cloud-run-mcp](https://github.com/GoogleCloudPlatform/cloud-run-mcp) — MCP server to deploy apps to Cloud Run ☆`639`
- [aliyun/alibabacloud-devops-mcp-server](https://github.com/aliyun/alibabacloud-devops-mcp-server) — MCP server for Alibaba Yunxiao DevOps platform ☆`184`
- [babelcloud/gbox](https://github.com/babelcloud/gbox) — AI control for Android, browser, desktop ☆`183`
- [aliyun/alibaba-cloud-ops-mcp-server](https://github.com/aliyun/alibaba-cloud-ops-mcp-server) — AlibabaCloud CloudOps MCP Server ☆`137`
- [dkruyt/mcp-hetzner](https://github.com/dkruyt/mcp-hetzner) — Hetzner Cloud management ☆`153`
- [AliKarami/MikroMCP](https://github.com/AliKarami/MikroMCP) — Automate MikroTik RouterOS routers and SwOS switches ☆`87`
- [heroku/heroku-mcp-server](https://github.com/heroku/heroku-mcp-server) — Heroku Platform MCP Server using the Heroku CLI ☆`82`
- [vantage-sh/vantage-mcp-server](https://github.com/vantage-sh/vantage-mcp-server) — Fetch costs and usage from Vantage ☆`86`
- [call518/MCP-OpenStack-Ops](https://github.com/call518/MCP-OpenStack-Ops) — MCP server providing OpenStack project management ☆`49`
- [backblaze-labs/b2-mcp](https://github.com/backblaze-labs/b2-mcp) — Manage Backblaze B2 buckets and objects ☆`47`
- [aliyun/alibabacloud-dataworks-mcp-server](https://github.com/aliyun/alibabacloud-dataworks-mcp-server) — Alibaba Cloud DataWorks API integration ☆`57`
- [aantti/mcp-netbird](https://github.com/aantti/mcp-netbird) — Netbird network management ☆`64`
- [kestra-io/mcp-server-python](https://github.com/kestra-io/mcp-server-python) — Python MCP for Kestra AI Agents ☆`35`
- [oborseth/Porkbun-MCP](https://github.com/oborseth/Porkbun-MCP) — Domains, DNS and the rest of the Porkbun v3 API ☆`36`
- [aliyun/alibabacloud-hologres-mcp-server](https://github.com/aliyun/alibabacloud-hologres-mcp-server) — MCP server for Alibaba Hologres data warehouse ☆`37`
- [redis/mcp-redis-cloud](https://github.com/redis/mcp-redis-cloud) — MCP server for Redis Cloud database operations ☆`43`
- [qiniu/qiniu-mcp-server](https://github.com/qiniu/qiniu-mcp-server) — Qiniu Cloud storage, CDN, and media processing ☆`39`
- [liveblocks/liveblocks-mcp-server](https://github.com/liveblocks/liveblocks-mcp-server) — MCP server for Liveblocks. ☆`19`
- [hardik-id/azure-resource-graph-mcp-server](https://github.com/hardik-id/azure-resource-graph-mcp-server) — Azure Resource Graph query interface ☆`18`
- [pythonanywhere/pythonanywhere-mcp-server](https://github.com/pythonanywhere/pythonanywhere-mcp-server) — Manage PythonAnywhere files, apps, and tasks ☆`17`
- [Azure-Samples/mcp](https://github.com/Azure-Samples/mcp) — Samples and resources for Azure MCP ☆`42`
- [api7/apisix-mcp](https://github.com/api7/apisix-mcp) — APISIX gateway for LLM integration ☆`38`
- [alexbakers/mcp-ipfs](https://github.com/alexbakers/mcp-ipfs) — MCP IPFS Server ☆`22`
- [higress-group/higress-ops-mcp-server](https://github.com/higress-group/higress-ops-mcp-server) — Higress API gateway configuration management ☆`23`
- [pibblokto/cert-manager-mcp-server](https://github.com/pibblokto/cert-manager-mcp-server) — MCP Server for cert-manager ☆`23`
- [espressif/esp-rainmaker-mcp](https://github.com/espressif/esp-rainmaker-mcp) — ESP RainMaker MCP server ☆`18`
- [kocierik/consul-mcp-server](https://github.com/kocierik/consul-mcp-server) — A consul MCP Server (modelcontextprotocol) ☆`18`
### Kubernetes

- [agentgateway/agentgateway](https://github.com/agentgateway/agentgateway) — Proxy in front of AI agents and MCP servers ☆`6,081`
- [skyhook-io/radar](https://github.com/skyhook-io/radar) — Kubernetes UI with issues, topology and a built-in MCP server ☆`4,086`
- [containers/kubernetes-mcp-server](https://github.com/containers/kubernetes-mcp-server) — Kubernetes and OpenShift management ☆`2,237`
- [Flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) — MCP Server for kubernetes management commands ☆`1,611`
- [rohitg00/kubectl-mcp-server](https://github.com/rohitg00/kubectl-mcp-server) — Kubernetes cluster chat with Claude/Cursor ☆`972`
- [microsoft/mcp-gateway](https://github.com/microsoft/mcp-gateway) — Proxy and lifecycle manager for MCP on Kubernetes ☆`913`
- [weibaohui/k8m](https://github.com/weibaohui/k8m) — Mini Kubernetes AI Dashboard ☆`893`
- [argoproj-labs/mcp-for-argocd](https://github.com/argoproj-labs/mcp-for-argocd) — Manage Argo CD applications ☆`604`
- [strowk/mcp-k8s-go](https://github.com/strowk/mcp-k8s-go) — Go-based Kubernetes connection ☆`382`
- [vfarcic/dot-ai](https://github.com/vfarcic/dot-ai) — Deploy apps to any Kubernetes cluster ☆`340`
- [portainer/portainer-mcp](https://github.com/portainer/portainer-mcp) — Portainer container management ☆`242`
- [reza-gholizade/k8s-mcp-server](https://github.com/reza-gholizade/k8s-mcp-server) — Kubernetes cluster management ☆`189`
- [kubestellar/console](https://github.com/kubestellar/console) — Multi-cluster Kubernetes dashboard with natural-language MCP ☆`151`
- [silenceper/mcp-k8s](https://github.com/silenceper/mcp-k8s) — Kubernetes cluster interaction ☆`152`
- [weibaohui/kom](https://github.com/weibaohui/kom) — Kubernetes SDK wrapping kubectl ☆`150`
- [andrewmoshu/diagram-mcp-server](https://github.com/andrewmoshu/diagram-mcp-server) — Diagrams for AWS, Azure, GCP and Kubernetes ☆`148`
- [OptimNow/cloud-finops-skills](https://github.com/OptimNow/cloud-finops-skills) — Cloud and AI cost knowledge for agents ☆`66`
- [StacklokLabs/mkp](https://github.com/StacklokLabs/mkp) — MKP Kubernetes MCP server ☆`59`
- [dhyansraj/mcp-mesh](https://github.com/dhyansraj/mcp-mesh) — Framework for many specialized agents, deployable on Kubernetes ☆`42`
- [vitorbari/mcp-operator](https://github.com/vitorbari/mcp-operator) — Kubernetes operator that deploys and checks MCP servers ☆`29`
- [zekker6/mcp-helm](https://github.com/zekker6/mcp-helm) — MCP server for Helm package manager ☆`28`
- [wenhuwang/mcp-k8s-eye](https://github.com/wenhuwang/mcp-k8s-eye) — Kubernetes diagnosis and management ☆`29`
- [cyclops-ui/mcp-cyclops](https://github.com/cyclops-ui/mcp-cyclops) — Cyclops Kubernetes management ☆`30`
- [basebandit/kai](https://github.com/basebandit/kai) — An MCP Server for Kubernetes ☆`20`
- [kubesphere/ks-mcp-server](https://github.com/kubesphere/ks-mcp-server) — KubeSphere APIs for workspaces, clusters, users, and roles ☆`17`
- [razvanmacovei/k8s-multicluster-mcp](https://github.com/razvanmacovei/k8s-multicluster-mcp) — An MCP (Model Context Protocol) server application for Kubernetes operations, providing a standardized API to interact with multiple Kubernetes clusters simultaneously using multiple kubeconfig files. ☆`16`
### Virtualization & IaC

- [patrickchugh/terravision](https://github.com/patrickchugh/terravision) — Diagrams to and from Terraform ☆`1,679`
- [hashicorp/terraform-mcp-server](https://github.com/hashicorp/terraform-mcp-server) — Terraform ecosystem integration for AI ☆`1,558`
- [agentic-community/mcp-gateway-registry](https://github.com/agentic-community/mcp-gateway-registry) — MCP gateway and registry with OAuth ☆`1,043`
- [nwiizo/tfmcp](https://github.com/nwiizo/tfmcp) — Terraform AI-assisted infrastructure ☆`371`
- [1Panel-dev/mcp-1panel](https://github.com/1Panel-dev/mcp-1panel) — MCP server for 1Panel management ☆`171`
- [kocierik/mcp-nomad](https://github.com/kocierik/mcp-nomad) — A nomad MCP Server (modelcontextprotocol) ☆`59`
- [bright8192/esxi-mcp-server](https://github.com/bright8192/esxi-mcp-server) — MCP server for VMware ESXi management ☆`64`
- [jokemanfire/mcp-containerd](https://github.com/jokemanfire/mcp-containerd) — Use mcp to manage containerd(developing) ☆`53`
- [felhen-ai/mcp-proxmox](https://github.com/felhen-ai/mcp-proxmox) — MCP server for managing Proxmox VE clusters through AI assistants ☆`18`
- [bsahane/mcp-ansible](https://github.com/bsahane/mcp-ansible) — MCP Ansible Server ☆`30`
- [openstack-kr/python-openstackmcp-server](https://github.com/openstack-kr/python-openstackmcp-server) — openstack mcp server ☆`19`
- [severity1/terraform-cloud-mcp](https://github.com/severity1/terraform-cloud-mcp) — Terraform Cloud API integration ☆`23`
## Communication & Messaging

### Apple Messages

- [mattt/iMCP](https://github.com/mattt/iMCP) — Access Messages, Contacts, Reminders on Mac ☆`1,962`
- [carterlasalle/mac_messages_mcp](https://github.com/carterlasalle/mac_messages_mcp) — MCP server for secure iMessage database access on macOS ☆`344`
- [hannesrudolph/imessage-query-fastmcp-mcp-server](https://github.com/hannesrudolph/imessage-query-fastmcp-mcp-server) — Safe iMessage database queries ☆`81`
- [wyattjoh/imessage-mcp](https://github.com/wyattjoh/imessage-mcp) — iMessage data reading from macOS ☆`29`
- [ictinnovations/ictbroadcast-mcp](https://github.com/ictinnovations/ictbroadcast-mcp) — Start, stop and watch ICTBroadcast campaigns ☆`16`
- [marissamarym/imessage-mcp-server](https://github.com/marissamarym/imessage-mcp-server) — Send iMessages and manage contacts through AppleScript ☆`29`
### Email

- [elie222/inbox-zero](https://github.com/elie222/inbox-zero) — AI email assistant for inbox zero ☆`12,977`
- [Atomic-Mail/atomic-mail-agentic](https://github.com/Atomic-Mail/atomic-mail-agentic) — Agents read, send and react to email on their own ☆`256`
- [wyattjoh/jmap-mcp](https://github.com/wyattjoh/jmap-mcp) — Mail on a JMAP server ☆`179`
- [codefuturist/email-mcp](https://github.com/codefuturist/email-mcp) — Read, search, send and file mail over IMAP and SMTP ☆`153`
- [MadLlama25/fastmail-mcp](https://github.com/MadLlama25/fastmail-mcp) — Access to Fastmail API for AI assistants ☆`131`
- [tecnologicachile/mail-mcp](https://github.com/tecnologicachile/mail-mcp) — IMAP, SMTP and Microsoft 365 mail for several accounts ☆`116`
- [ZilongXue/claude-post](https://github.com/ZilongXue/claude-post) — Email management via natural language ☆`114`
- [MrGo2/icloud-mcp](https://github.com/MrGo2/icloud-mcp) — Mail, calendar, contacts and notes through AppleScript or iCloud ☆`79`
- [agentmail-to/agentmail-mcp](https://github.com/agentmail-to/agentmail-mcp) — Create inboxes so agents can send and receive email ☆`72`
- [mailtrap/mailtrap-mcp](https://github.com/mailtrap/mailtrap-mcp) — Send and test email through Mailtrap, including sandboxes ☆`66`
- [mailgun/mailgun-mcp-server](https://github.com/mailgun/mailgun-mcp-server) — Mailgun API integration ☆`64`
- [Shy2593666979/mcp-server-email](https://github.com/Shy2593666979/mcp-server-email) — Email with attachments for Gmail, Outlook, QQ ☆`81`
- [openagentemail/openagentemail](https://github.com/openagentemail/openagentemail) — Self-hosted mail and approvals between agents ☆`55`
- [qubrics/qubrics-sdk](https://github.com/qubrics/qubrics-sdk) — SDKs, a CLI and MCP servers for Sendmux email ☆`56`
- [desek/outlook-local-mcp](https://github.com/desek/outlook-local-mcp) — Outlook mail and calendar through Microsoft Graph ☆`45`
- [littlebearapps/outlook-assistant](https://github.com/littlebearapps/outlook-assistant) — Outlook mail, calendar and contacts ☆`40`
- [marlinjai/email-mcp](https://github.com/marlinjai/email-mcp) — One server for Gmail, Outlook, iCloud and IMAP ☆`26`
- [wildsurfer/your-mail-mcp](https://github.com/wildsurfer/your-mail-mcp) — Read-only IMAP mail from a local notmuch index ☆`20`
- [adecubed/gigamail](https://github.com/adecubed/gigamail) — Permissioned email, calendar and files for agents ☆`18`
- [egyptianego17/email-mcp-server](https://github.com/egyptianego17/email-mcp-server) — Send emails with attachments via SMTP ☆`28`
- [Zacccck/Claude-MCP-Read-Email-Attachments](https://github.com/Zacccck/Claude-MCP-Read-Email-Attachments) — Read Outlook mail and send local files ☆`19`
### Messengers

- [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) — WhatsApp MCP server ☆`6,856`
- [chigwell/telegram-mcp](https://github.com/chigwell/telegram-mcp) — MCP server for Telegram messaging ☆`2,020`
- [line/line-bot-mcp-server](https://github.com/line/line-bot-mcp-server) — LINE Messaging API for AI agents ☆`801`
- [chaindead/telegram-mcp](https://github.com/chaindead/telegram-mcp) — Telegram dialogs, messages, drafts, statuses ☆`350`
- [reminia/zendesk-mcp-server](https://github.com/reminia/zendesk-mcp-server) — A Model Context Protocol server for Zendesk ☆`126`
- [cometchat/docs-mcp](https://github.com/cometchat/docs-mcp) — CometChat docs and bundles for adding chat, voice and video ☆`140`
- [googlarz/proton-mail-bridge-client](https://github.com/googlarz/proton-mail-bridge-client) — Search, draft and send Proton Mail ☆`87`
- [imdinu/apple-mail-mcp](https://github.com/imdinu/apple-mail-mcp) — Full-text search of Apple Mail, including large mailboxes ☆`73`
- [mcp-telegram/mcp-telegram](https://github.com/mcp-telegram/mcp-telegram) — Personal Telegram account over MTProto, self-hosted or hosted ☆`69`
- [ztxtxwd/open-feishu-mcp-server](https://github.com/ztxtxwd/open-feishu-mcp-server) — Feishu/Lark OAuth and document management ☆`87`
- [areweai/tsgram-mcp](https://github.com/areweai/tsgram-mcp) — Telegram for local Claude Code debug ☆`88`
- [leshchenko1979/fast-mcp-telegram](https://github.com/leshchenko1979/fast-mcp-telegram) — Telegram gateway for agents, over HTTP or stdio ☆`50`
- [kushneryk/join.cloud](https://github.com/kushneryk/join.cloud) — Rooms where agents exchange messages and share files ☆`66`
- [PhilflowIO/dav-mcp](https://github.com/PhilflowIO/dav-mcp) — Calendars, contacts and tasks over CalDAV and CardDAV ☆`43`
- [mjknowles/matrix-mcp-server](https://github.com/mjknowles/matrix-mcp-server) — Matrix server integration and chat ☆`57`
- [parasxos/apple-mail-mcp](https://github.com/parasxos/apple-mail-mcp) — Fast search of Apple Mail, including verified sends ☆`36`
- [pubnub/pubnub-mcp-server](https://github.com/pubnub/pubnub-mcp-server) — PubNub Model Context Protocol Server ☆`33`
- [yjcho9317/nworks](https://github.com/yjcho9317/nworks) — LINE WORKS messages, calendar, drive, mail and tasks ☆`28`
- [belaytzev/Telebrief](https://github.com/belaytzev/Telebrief) — Daily or weekly digests of Telegram chats and channels ☆`26`
- [qpd-v/mcp-communicator-telegram](https://github.com/qpd-v/mcp-communicator-telegram) — Ask the user a question through a Telegram bot and wait ☆`47`
- [ictinnovations/ictfax-mcp](https://github.com/ictinnovations/ictfax-mcp) — List, upload and send faxes through ICTFax ☆`18`
- [skeptrunedev/call4me](https://github.com/skeptrunedev/call4me) — Place phone calls through Telnyx and a live voice model ☆`17`
- [gotoolkits/mcp-wecombot-server](https://github.com/gotoolkits/mcp-wecombot-server) — Post messages to a WeCom group robot ☆`36`
- [DLHellMe/telegram-mcp-server](https://github.com/DLHellMe/telegram-mcp-server) — Scrape and analyze Telegram content ☆`31`
### Notifications

- [777genius/agent-notifications](https://github.com/777genius/agent-notifications) — Desktop alerts when an agent needs you ☆`829`
- [gitmotion/ntfy-me-mcp](https://github.com/gitmotion/ntfy-me-mcp) — MCP server for ntfy push notifications ☆`76`
- [AshikNesin/pushover-mcp](https://github.com/AshikNesin/pushover-mcp) — A MCP implementation for sending notifications via Pushover ☆`43`
- [infobip/mcp](https://github.com/infobip/mcp) — Infobip Remote MCP Servers Documentation ☆`36`
- [Cactusinhand/mcp_server_notify](https://github.com/Cactusinhand/mcp_server_notify) — Send system notification when Agent task is done. ☆`54`
- [teddyzxcv/ntfy-mcp](https://github.com/teddyzxcv/ntfy-mcp) — MCP server for ntfy push notifications ☆`44`
- [aahl/mcp-notify](https://github.com/aahl/mcp-notify) — Notify to Weixin, Telegram, Bark, Lark, DingTalk ☆`29`
### Team Chat

- [korotovsky/slack-mcp-server](https://github.com/korotovsky/slack-mcp-server) — MCP server for Slack workspace integration ☆`1,892`
- [chatmcp/mcp-server-chatsum](https://github.com/chatmcp/mcp-server-chatsum) — Query and Summarize your chat messages. ☆`1,027`
- [SaseQ/discord-mcp](https://github.com/SaseQ/discord-mcp) — MCP server for Discord integration ☆`602`
- [joinly-ai/joinly](https://github.com/joinly-ai/joinly) — Make your meetings accessible to AI Agents ☆`571`
- [v-3/discordmcp](https://github.com/v-3/discordmcp) — Discord MCP Server for Claude Integration ☆`245`
- [discourse/discourse-mcp](https://github.com/discourse/discourse-mcp) — MCP client for Discourse sites ☆`79`
- [colibird-ai/local-mcp-releases](https://github.com/colibird-ai/local-mcp-releases) — Reach Mail, chat, files and Office on your Mac or PC ☆`80`
- [zencoderai/slack-mcp-server](https://github.com/zencoderai/slack-mcp-server) — Slack workspace interaction and messaging ☆`75`
- [jtalk22/slack-mcp-server](https://github.com/jtalk22/slack-mcp-server) — Search Slack and read threads without adding a bot ☆`33`
- [PaSympa/discord-mcp](https://github.com/PaSympa/discord-mcp) — Messages, roles and moderation on Discord ☆`33`
- [jagan-shanmugam/mattermost-mcp-host](https://github.com/jagan-shanmugam/mattermost-mcp-host) — Mattermost integration with LangGraph agent ☆`34`
### Voice & Telephony

- [voygr-tech/placecall](https://github.com/voygr-tech/placecall) — Phone a US business and return the transcript and recording ☆`115`
- [radres/call-me](https://github.com/radres/call-me) — Ring the user's iPhone so the agent can ask out loud ☆`41`
- [ictinnovations/pbx-mcp](https://github.com/ictinnovations/pbx-mcp) — Channels and dialplan on Asterisk or FreeSWITCH ☆`20`
- [ictinnovations/ictpbx-mcp](https://github.com/ictinnovations/ictpbx-mcp) — Read extensions, trunks and tenants on ICTPBX ☆`16`
- [mohitbadwal/ringback](https://github.com/mohitbadwal/ringback) — Agent places a live phone call and can be interrupted ☆`31`
- [gerkensm/callcenter.js-mcp](https://github.com/gerkensm/callcenter.js-mcp) — Callcenter.JS AI Voice Agent VOIP Connector, MCP + CLI ☆`25`
## Data & Analytics

### AI/ML Platforms

- [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) — New model and product names before keyword tools ☆`2,148`
- [MigoXLab/dingo](https://github.com/MigoXLab/dingo) — AI data, model, app quality evaluation ☆`767`
- [evalstate/mcp-hfspace](https://github.com/evalstate/mcp-hfspace) — HuggingFace Spaces integration ☆`388`
- [huggingface/hf-mcp-server](https://github.com/huggingface/hf-mcp-server) — Hugging Face MCP Server ☆`314`
- [YanxingLiu/dify-mcp-server](https://github.com/YanxingLiu/dify-mcp-server) — Model Context Protocol (MCP) Server for dify workflows ☆`279`
- [sato942/game-asset-mcp](https://github.com/sato942/game-asset-mcp) — 2D and 3D game assets from text, using Hugging Face models ☆`166`
- [0xshellming/mcp-summarizer](https://github.com/0xshellming/mcp-summarizer) — MCP Server for AI Summarization ☆`167`
- [optuna/optuna-mcp](https://github.com/optuna/optuna-mcp) — Optuna hyperparameter optimization ☆`91`
- [ChronulusAI/chronulus-mcp](https://github.com/ChronulusAI/chronulus-mcp) — Chronulus AI forecasting and prediction agents ☆`111`
- [zenml-io/mcp-zenml](https://github.com/zenml-io/mcp-zenml) — ZenML MLOps platform connection ☆`49`
- [arrismo/kaggle-mcp](https://github.com/arrismo/kaggle-mcp) — MCP server for Kaggle ☆`39`
- [HumanSignal/label-studio-mcp-server](https://github.com/HumanSignal/label-studio-mcp-server) — MCP server for Label Studio data labeling ☆`37`
- [privetin/dataset-viewer](https://github.com/privetin/dataset-viewer) — MCP server for Hugging Face dataset viewer ☆`31`
### Data APIs

- [anshumax/world_bank_mcp_server](https://github.com/anshumax/world_bank_mcp_server) — World Bank open data API ☆`50`
- [YangLiangwei/PersonalizationMCP](https://github.com/YangLiangwei/PersonalizationMCP) — Personal data hub for AI from Steam, YouTube, Bilibili ☆`63`
- [Jellyfish-AI/jellyfish-mcp](https://github.com/Jellyfish-AI/jellyfish-mcp) — Jellyfish MCP server ☆`20`
- [explorium-ai/mcp-explorium](https://github.com/explorium-ai/mcp-explorium) — Explorium B2B Data - MCP Server ☆`22`
### Data Exploration

- [reading-plus-ai/mcp-server-data-exploration](https://github.com/reading-plus-ai/mcp-server-data-exploration) — Interactive CSV data exploration ☆`544`
- [kdqed/zaturn](https://github.com/kdqed/zaturn) — Data Analysis With Vibes ☆`76`
- [brightlikethelight/networkx-mcp-server](https://github.com/brightlikethelight/networkx-mcp-server) — NetworkX graph algorithms for AI conversations ☆`22`
- [santoshray02/csv-editor](https://github.com/santoshray02/csv-editor) — AI-powered CSV data manipulation and analysis ☆`25`
### Data Platforms

- [dbt-labs/dbt-mcp](https://github.com/dbt-labs/dbt-mcp) — A MCP (Model Context Protocol) server for interacting with dbt. ☆`620`
- [kubeflow/mcp-apache-spark-history-server](https://github.com/kubeflow/mcp-apache-spark-history-server) — Apache Spark History Server bridge ☆`206`
- [microsoft/fabric-rti-mcp](https://github.com/microsoft/fabric-rti-mcp) — Fabric Real-Time Intelligence server ☆`133`
- [acryldata/mcp-server-datahub](https://github.com/acryldata/mcp-server-datahub) — Official MCP server for DataHub ☆`85`
- [keboola/mcp-server](https://github.com/keboola/mcp-server) — Model Context Protocol (MCP) Server for the Keboola Platform ☆`85`
- [bintocher/mcp-superset](https://github.com/bintocher/mcp-superset) — Dashboards, charts, datasets and SQL Lab in Apache Superset ☆`64`
- [thoughtspot/mcp-server](https://github.com/thoughtspot/mcp-server) — The ThoughtSpot MCP Server ☆`35`
- [aywengo/kafka-schema-reg-mcp](https://github.com/aywengo/kafka-schema-reg-mcp) — Kafka Schema Registry management ☆`32`
- [bruno-portfolio/agrobr-mcp](https://github.com/bruno-portfolio/agrobr-mcp) — Brazilian crop prices, trade, climate and fire data ☆`30`
- [JordiNeil/mcp-databricks-server](https://github.com/JordiNeil/mcp-databricks-server) — MCP Server for Databricks ☆`50`
- [growthbook/growthbook-mcp](https://github.com/growthbook/growthbook-mcp) — GrowthBook flags and experiments ☆`24`
- [RafaelCartenet/mcp-databricks-server](https://github.com/RafaelCartenet/mcp-databricks-server) — AI agents interact with Databricks ☆`43`
- [IBM/data-intelligence-mcp-server](https://github.com/IBM/data-intelligence-mcp-server) — Watsonx Data Intelligence gateway across microservices ☆`20`
- [syucream/lightdash-mcp-server](https://github.com/syucream/lightdash-mcp-server) — Access to Lightdash analytics ☆`27`
- [yangkyeongmo/mcp-server-openmetadata](https://github.com/yangkyeongmo/mcp-server-openmetadata) — OpenMetadata integration for data catalog ☆`24`
- [mattijsdp/dbt-docs-mcp](https://github.com/mattijsdp/dbt-docs-mcp) — dbt documentation interaction ☆`23`
- [datumnova/ms-fabric-mcp](https://github.com/datumnova/ms-fabric-mcp) — Microsoft Fabric workspaces, lakehouses, and PySpark notebooks ☆`17`
- [yashshingvi/databricks-genie-MCP](https://github.com/yashshingvi/databricks-genie-MCP) — Ask Databricks Genie questions and run SQL queries ☆`17`
### Jupyter & Notebooks

- [datalayer/jupyter-mcp-server](https://github.com/datalayer/jupyter-mcp-server) — Model Context Protocol (MCP) Server for Jupyter. ☆`1,323`
- [jjsantos01/jupyter-notebook-mcp](https://github.com/jjsantos01/jupyter-notebook-mcp) — A Model Context Protocol (MCP) for Jupyter Notebook ☆`128`
- [phisanti/MCPR](https://github.com/phisanti/MCPR) — AI agents in interactive R sessions ☆`26`
### Visualization

- [antvis/mcp-server-chart](https://github.com/antvis/mcp-server-chart) — 25+ visual charts using @antvis for data analysis ☆`4,416`
- [hustcc/mcp-echarts](https://github.com/hustcc/mcp-echarts) — ECharts visual charts with AI ☆`268`
- [easecloudio/mcp-metabase-server](https://github.com/easecloudio/mcp-metabase-server) — A comprehensive MCP server for Metabase with 70+ tools. ☆`83`
- [isaacwasserman/mcp-vegalite-server](https://github.com/isaacwasserman/mcp-vegalite-server) — MCP server for Vega-Lite data visualization ☆`100`
- [palewire/datawrapper-mcp](https://github.com/palewire/datawrapper-mcp) — Create Datawrapper charts with AI ☆`63`
- [KyuRish/mcp-dashboards](https://github.com/KyuRish/mcp-dashboards) — Turn data into an interactive dashboard inside the chat ☆`53`
## Databases

### Analytics & Warehouses

- [ClickHouse/mcp-clickhouse](https://github.com/ClickHouse/mcp-clickhouse) — Connect ClickHouse to your AI assistants. ☆`903`
- [motherduckdb/mcp-server-motherduck](https://github.com/motherduckdb/mcp-server-motherduck) — Local MCP server for DuckDB and MotherDuck ☆`540`
- [Snowflake-Labs/mcp](https://github.com/Snowflake-Labs/mcp) — Snowflake Cortex AI and SQL orchestration ☆`302`
- [isaacwasserman/mcp-snowflake-server](https://github.com/isaacwasserman/mcp-snowflake-server) — MCP server for Snowflake database queries ☆`184`
- [ktanaka101/mcp-server-duckdb](https://github.com/ktanaka101/mcp-server-duckdb) — DuckDB database interaction ☆`179`
- [ergut/mcp-bigquery-server](https://github.com/ergut/mcp-bigquery-server) — MCP server for Google BigQuery integration ☆`148`
- [LucasHild/mcp-server-bigquery](https://github.com/LucasHild/mcp-server-bigquery) — Google BigQuery database access ☆`131`
- [lishenxydlgzs/aws-athena-mcp](https://github.com/lishenxydlgzs/aws-athena-mcp) — MCP server to run AWS Athena queries ☆`41`
- [pab1it0/adx-mcp-server](https://github.com/pab1it0/adx-mcp-server) — MCP server for Azure Data Explorer ☆`59`
- [aliyun/alibabacloud-adb-mysql-mcp-server](https://github.com/aliyun/alibabacloud-adb-mysql-mcp-server) — AnalyticDB for MySQL MCP Server ☆`32`
- [startreedata/mcp-pinot](https://github.com/startreedata/mcp-pinot) — MCP Server for Apache Pinot ☆`17`
- [iunera/druid-mcp-server](https://github.com/iunera/druid-mcp-server) — Apache Druid cluster tools, resources, and analysis ☆`18`
### Cache & Key-Value

- [redis/mcp-redis](https://github.com/redis/mcp-redis) — MCP server for Redis database operations ☆`642`
- [aliyun/alibabacloud-tablestore-mcp-server](https://github.com/aliyun/alibabacloud-tablestore-mcp-server) — MCP server for Alibaba Tablestore NoSQL ☆`157`
- [upstash/mcp-server](https://github.com/upstash/mcp-server) — Upstash Model Context Server ☆`61`
- [prajwalnayak7/mcp-server-redis](https://github.com/prajwalnayak7/mcp-server-redis) — Get and set keys in Redis or MemoryDB ☆`25`
### Cloud Platforms

- [instantdb/instant](https://github.com/instantdb/instant) — Modern Firebase with real-time database ☆`10,561`
- [supabase/mcp](https://github.com/supabase/mcp) — Connect Supabase to your AI assistants ☆`3,004`
- [alexander-zuev/supabase-mcp-server](https://github.com/alexander-zuev/supabase-mcp-server) — MCP server for Supabase database and auth ☆`836`
- [neondatabase/mcp-server-neon](https://github.com/neondatabase/mcp-server-neon) — Neon Management API and databases ☆`663`
- [planetscale/cli](https://github.com/planetscale/cli) — The CLI for PlanetScale Database ☆`672`
- [gannonh/firebase-mcp](https://github.com/gannonh/firebase-mcp) — Model Context Protocol (MCP) server for Firebase. ☆`247`
- [coleam00/supabase-mcp](https://github.com/coleam00/supabase-mcp) — Supabase MCP server created in Python. ☆`194`
- [Aiven-Open/mcp-aiven](https://github.com/Aiven-Open/mcp-aiven) — Model Context Protocol server for Aiven ☆`28`
- [JoshuaRileyDev/supabase-mcp-server](https://github.com/JoshuaRileyDev/supabase-mcp-server) — MCP server for Supabase database operations ☆`52`
- [niledatabase/nile-mcp-server](https://github.com/niledatabase/nile-mcp-server) — Nile Database tenants, users, auth for LLMs ☆`19`
### Graph Databases

- [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j) — Neo4j Labs Model Context Protocol servers ☆`989`
- [neo4j-contrib/gds-agent](https://github.com/neo4j-contrib/gds-agent) — Neo4j Graph Data Science tools ☆`99`
- [FalkorDB/FalkorDB-MCPServer](https://github.com/FalkorDB/FalkorDB-MCPServer) — Connect LLMs to FalkorDB ☆`42`
- [da-okazaki/mcp-neo4j-server](https://github.com/da-okazaki/mcp-neo4j-server) — mcp-neo4j-server ☆`59`
- [ravenwits/mcp-server-arangodb](https://github.com/ravenwits/mcp-server-arangodb) — ArangoDB database interaction ☆`46`
### Multi-Database Tools

- [googleapis/mcp-toolbox](https://github.com/googleapis/mcp-toolbox) — Open source database MCP toolbox ☆`16,836`
- [bytebase/dbhub](https://github.com/bytebase/dbhub) — Token-efficient multi-database MCP ☆`3,825`
- [damms005/devdb-vscode](https://github.com/damms005/devdb-vscode) — Zero-config VS Code database extension ☆`1,456`
- [centralmind/gateway](https://github.com/centralmind/gateway) — Universal database MCP for LLMs ☆`550`
- [FreePeak/db-mcp-server](https://github.com/FreePeak/db-mcp-server) — MCP server for database operations ☆`480`
- [runekaagaard/mcp-alchemy](https://github.com/runekaagaard/mcp-alchemy) — MCP server for SQLAlchemy database operations ☆`422`
- [executeautomation/mcp-database-server](https://github.com/executeautomation/mcp-database-server) — Connect to SQLite, SQL Server, PostgreSQL ☆`391`
- [XGenerationLab/xiyan_mcp_server](https://github.com/XGenerationLab/xiyan_mcp_server) — Natural language database queries ☆`239`
- [memgraph/ai-toolkit](https://github.com/memgraph/ai-toolkit) — Agent memory and GraphRAG on Memgraph ☆`119`
- [FROWNINGdev/orm-lens](https://github.com/FROWNINGdev/orm-lens) — ER diagrams, N+1 and migration risk for Django and SQLAlchemy ☆`99`
- [appwrite/mcp](https://github.com/appwrite/mcp) — Appwrite's MCP server. Operating your backend has never been easier. ☆`72`
- [yimindev/dati](https://github.com/yimindev/dati) — Turn your database into secure, semantically rich MCP tools for agents. ☆`74`
- [AzureCosmosDB/azure-cosmos-mcp-server-samples](https://github.com/AzureCosmosDB/azure-cosmos-mcp-server-samples) — Sample MCP servers on Azure Cosmos DB ☆`64`
- [s2-streamstore/s2-sdk-typescript](https://github.com/s2-streamstore/s2-sdk-typescript) — TypeScript SDK for S2, the durable streams API ☆`37`
- [cyanheads/filesystem-mcp-server](https://github.com/cyanheads/filesystem-mcp-server) — Search, read and edit files, including directory trees ☆`54`
- [schemacrawler/SchemaCrawler-AI-MCP-Server-Usage](https://github.com/schemacrawler/SchemaCrawler-AI-MCP-Server-Usage) — How to use SchemaCrawler AI MCP Server ☆`30`
- [ExpeditedProjects/hutchdb](https://github.com/ExpeditedProjects/hutchdb) — Schema-free store agents can write to and query together ☆`26`
- [spences10/mcp-turso-cloud](https://github.com/spences10/mcp-turso-cloud) — Turso databases, with separate platform and database auth ☆`18`
- [codeurali/mcp-dataverse](https://github.com/codeurali/mcp-dataverse) — MCP server for Microsoft Dataverse Web API for devs ! ☆`18`
- [FocusSearch/focus_mcp_sql](https://github.com/FocusSearch/focus_mcp_sql) — Natural language to SQL, parsed from keywords ☆`38`
- [fireproof-storage/mcp-database-server](https://github.com/fireproof-storage/mcp-database-server) — Store and load JSON documents from LLM tool use ☆`31`
- [theronic/datomic-mcp](https://github.com/theronic/datomic-mcp) — Query a Datomic database ☆`25`
- [datastrato/mcp-server-gravitino](https://github.com/datastrato/mcp-server-gravitino) — MCP server for Apache Gravitino ☆`23`
- [keonchennl/mcp-server-graphdb](https://github.com/keonchennl/mcp-server-graphdb) — Read-only SPARQL against an Ontotext GraphDB repository ☆`17`
- [OpenLinkSoftware/mcp-jdbc-server](https://github.com/OpenLinkSoftware/mcp-jdbc-server) — Java JDBC access for SQL databases ☆`17`
### NoSQL & Document

- [mongodb-js/mongodb-mcp-server](https://github.com/mongodb-js/mongodb-mcp-server) — Connect to MongoDB and Atlas clusters ☆`1,160`
- [kiliczsh/mcp-mongo-server](https://github.com/kiliczsh/mcp-mongo-server) — A Model Context Protocol Server for MongoDB ☆`284`
- [furey/mongodb-lens](https://github.com/furey/mongodb-lens) — MongoDB Lens: Full Featured MCP Server for MongoDB Databases ☆`207`
- [QuantGeekDev/mongo-mcp](https://github.com/QuantGeekDev/mongo-mcp) — A mongo db server for the model context protocol (MCP) ☆`176`
- [datastax/astra-db-mcp](https://github.com/datastax/astra-db-mcp) — An MCP server for Astra DB workloads ☆`43`
- [couchbase/mcp-server-couchbase](https://github.com/couchbase/mcp-server-couchbase) — Couchbase database cluster integration ☆`34`
- [Knuckles-Team/vector-mcp](https://github.com/Knuckles-Team/vector-mcp) — Vector search on Chroma, Qdrant, MongoDB or pgvector ☆`16`
### SQL Databases

- [crystaldba/postgres-mcp](https://github.com/crystaldba/postgres-mcp) — Postgres with read/write access and performance ☆`3,467`
- [benborla/mcp-server-mysql](https://github.com/benborla/mcp-server-mysql) — MCP server for MySQL database operations ☆`2,213`
- [designcomputer/mysql_mcp_server](https://github.com/designcomputer/mysql_mcp_server) — Secure MySQL database interaction ☆`1,414`
- [subnetmarco/pgmcp](https://github.com/subnetmarco/pgmcp) — An MCP server to query any Postgres database in natural language. ☆`542`
- [agent-next/polymarket-paper-trader](https://github.com/agent-next/polymarket-paper-trader) — Paper trading simulator for Polymarket ☆`503`
- [oracle/mcp](https://github.com/oracle/mcp) — Tools for managing Oracle products ☆`477`
- [RichardHan/mssql_mcp_server](https://github.com/RichardHan/mssql_mcp_server) — Query SQL Server through a limited interface ☆`404`
- [apache/doris-mcp-server](https://github.com/apache/doris-mcp-server) — Apache Doris MCP Server ☆`357`
- [MariaDB/mcp](https://github.com/MariaDB/mcp) — MariaDB MCP (Model Context Protocol) server implementation ☆`217`
- [wenb1n-dev/mysql_mcp_server_pro](https://github.com/wenb1n-dev/mysql_mcp_server_pro) — Enhanced MySQL with anomaly analysis ☆`249`
- [StarRocks/mcp-server-starrocks](https://github.com/StarRocks/mcp-server-starrocks) — StarRocks MCP (Model Context Protocol) Server ☆`196`
- [HenkDz/postgresql-mcp-server](https://github.com/HenkDz/postgresql-mcp-server) — PostgreSQL admin tools folded into a smaller set ☆`204`
- [call518/MCP-PostgreSQL-Ops](https://github.com/call518/MCP-PostgreSQL-Ops) — PostgreSQL operations and monitoring ☆`164`
- [f4ww4z/mcp-mysql-server](https://github.com/f4ww4z/mcp-mysql-server) — A Model Context Protocol server for MySQL database operations ☆`171`
- [ashishsinha1602/schemagate](https://github.com/ashishsinha1602/schemagate) — Text-to-SQL that only shows tables the caller may read ☆`135`
- [tuannvm/mcp-trino](https://github.com/tuannvm/mcp-trino) — High-performance Trino MCP in Go ☆`122`
- [oceanbase/awesome-oceanbase-mcp](https://github.com/oceanbase/awesome-oceanbase-mcp) — MCP Server for OceanBase database and its tools ☆`110`
- [jparkerweb/mcp-sqlite](https://github.com/jparkerweb/mcp-sqlite) — Comprehensive SQLite interaction ☆`130`
- [hannesrudolph/sqlite-explorer-fastmcp-mcp-server](https://github.com/hannesrudolph/sqlite-explorer-fastmcp-mcp-server) — Read-only SQLite database access ☆`108`
- [wenb1n-dev/SmartDB_MCP](https://github.com/wenb1n-dev/SmartDB_MCP) — Universal database MCP for MySQL, PostgreSQL, Oracle and more ☆`78`
- [shkyyy18/mi_fitness_data_bridge](https://github.com/shkyyy18/mi_fitness_data_bridge) — Unofficial Mi Fitness export to SQLite, CSV and JSON ☆`70`
- [Teradata/teradata-mcp-server](https://github.com/Teradata/teradata-mcp-server) — Teradata database integration ☆`58`
- [donghao1393/mcp-dbutils](https://github.com/donghao1393/mcp-dbutils) — Multi-database connector for SQLite, MySQL, PostgreSQL ☆`89`
- [JexinSam/mssql_mcp_server](https://github.com/JexinSam/mssql_mcp_server) — Controlled access to Microsoft SQL Server ☆`60`
- [aliyun/alibabacloud-rds-openapi-mcp-server](https://github.com/aliyun/alibabacloud-rds-openapi-mcp-server) — MCP server for RDS Services via OPENAPI. ☆`54`
- [Zhwt/go-mcp-mysql](https://github.com/Zhwt/go-mcp-mysql) — Go-based MCP server for MySQL ☆`66`
- [drhalto/agentmako](https://github.com/drhalto/agentmako) — Local context packets, code facts and diagnostics for agents ☆`54`
- [haymon-ai/dbmcp](https://github.com/haymon-ai/dbmcp) — MySQL, MariaDB, PostgreSQL and SQLite, with PII redaction ☆`33`
- [ydb-platform/ydb-mcp](https://github.com/ydb-platform/ydb-mcp) — MCP server for YDB distributed database ☆`29`
- [antonorlov/mcp-postgres-server](https://github.com/antonorlov/mcp-postgres-server) — Query and manage PostgreSQL ☆`25`
- [slotix/dbconvert-streams-public](https://github.com/slotix/dbconvert-streams-public) — Query and replicate data across databases, with CDC ☆`24`
- [B0yko/pgwarden](https://github.com/B0yko/pgwarden) — Per-person read-only Postgres access, with PII masking ☆`23`
- [Xexr/mcp-libsql](https://github.com/Xexr/mcp-libsql) — MCP server for libSQL database ☆`21`
- [singlestore-labs/mcp-server-singlestore](https://github.com/singlestore-labs/mcp-server-singlestore) — SingleStore database management API ☆`33`
- [dolthub/dolt-mcp](https://github.com/dolthub/dolt-mcp) — The MCP server for Dolt ☆`19`
- [pingcap/pytidb](https://github.com/pingcap/pytidb) — TiDB AI SDK for apps and agents ☆`34`
- [isdaniel/pgtuner_mcp](https://github.com/isdaniel/pgtuner_mcp) — provides AI-powered PostgreSQL performance tuning capabilities. ☆`31`
- [tyrchen/postgres-mcp](https://github.com/tyrchen/postgres-mcp) — postgres mcp implementation ☆`33`
- [rahgadda/oracledb_mcp_server](https://github.com/rahgadda/oracledb_mcp_server) — MCP server to connect to Oracle Database ☆`35`
- [ahmedmustahid/postgres-mcp-server](https://github.com/ahmedmustahid/postgres-mcp-server) — MCP server for PostgreSQL ☆`31`
- [panasenco/mcp-sqlite](https://github.com/panasenco/mcp-sqlite) — SQLite with Datasette metadata support ☆`28`
- [NetanelBollag/simple-psql-mcp](https://github.com/NetanelBollag/simple-psql-mcp) — Beginner MCP server template for PostgreSQL ☆`32`
- [ian-cowley/MCPSqlServer](https://github.com/ian-cowley/MCPSqlServer) — Query Microsoft SQL Server ☆`19`
- [amornpan/py-mcp-mssql](https://github.com/amornpan/py-mcp-mssql) — py-mcp-mssql ☆`27`
- [vignesh-codes/ai-agents-mcp-pg](https://github.com/vignesh-codes/ai-agents-mcp-pg) — Create and edit rows in PostgreSQL ☆`27`
- [syahiidkamil/mcp-postgres-full-access](https://github.com/syahiidkamil/mcp-postgres-full-access) — Full access postgres mcp server ☆`25`
- [hdcola/mcp-server-oracle](https://github.com/hdcola/mcp-server-oracle) — Model Context Protocol server to access oracle database ☆`25`
- [dave-wind/mysql-mcp-server](https://github.com/dave-wind/mysql-mcp-server) — mcp model-context-protocol mysql cursor n8n ☆`16`
- [aliyun/alibabacloud-adbpg-mcp-server](https://github.com/aliyun/alibabacloud-adbpg-mcp-server) — AnalyticDB PostgreSQL metadata and SQL operations ☆`16`
- [shibayu36/mysql-schema-explorer-mcp](https://github.com/shibayu36/mysql-schema-explorer-mcp) — MySQL schema for large databases, without the rows ☆`22`
- [OpenLinkSoftware/mcp-sqlalchemy-server](https://github.com/OpenLinkSoftware/mcp-sqlalchemy-server) — ODBC server with FastAPI and SQLAlchemy ☆`25`
- [c4pt0r/mcp-server-tidb](https://github.com/c4pt0r/mcp-server-tidb) — mcp server for tidb ☆`24`
- [cuongtl1992/mcp-dbs](https://github.com/cuongtl1992/mcp-dbs) — Query SQLite, SQL Server and PostgreSQL ☆`21`
- [abel9851/mcp-server-mariadb](https://github.com/abel9851/mcp-server-mariadb) — An mcp server that provides read-only access to MariaDB. ☆`20`
- [Dataring-engineering/mcp-server-trino](https://github.com/Dataring-engineering/mcp-server-trino) — MCP Server for Trino ☆`18`
### Search Engines

- [elastic/mcp-server-elasticsearch](https://github.com/elastic/mcp-server-elasticsearch) — Elasticsearch queries and index management ☆`729`
- [cr7258/elasticsearch-mcp-server](https://github.com/cr7258/elasticsearch-mcp-server) — Elasticsearch and OpenSearch interaction ☆`317`
- [meilisearch/meilisearch-mcp](https://github.com/meilisearch/meilisearch-mcp) — Meilisearch interaction via LLM interfaces ☆`198`
- [opensearch-project/opensearch-mcp-server-py](https://github.com/opensearch-project/opensearch-mcp-server-py) — OpenSearch cluster interaction for AI ☆`158`
- [vectorize-io/vectorize-mcp-server](https://github.com/vectorize-io/vectorize-mcp-server) — Official Vectorize MCP Server ☆`116`
- [suhail-ak-2/mcp-typesense-server](https://github.com/suhail-ak-2/mcp-typesense-server) — Typesense search for AI assistants ☆`19`
### Spreadsheets & No-Code

- [baserow/baserow](https://github.com/baserow/baserow) — No-code database, apps, agents with AI ☆`6,316`
- [xing5/mcp-google-sheets](https://github.com/xing5/mcp-google-sheets) — Google Drive and Sheets integration ☆`1,019`
- [negokaz/excel-mcp-server](https://github.com/negokaz/excel-mcp-server) — Read and write Excel workbooks ☆`1,048`
- [busabase/busabase](https://github.com/busabase/busabase) — Local database and workspace where agents store data and skills ☆`765`
- [domdomegg/airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server) — Airtable bases integration for AI systems ☆`456`
- [freema/mcp-gsheets](https://github.com/freema/mcp-gsheets) — Google Sheets read, write, manipulate ☆`105`
- [rashidazarang/airtable-mcp](https://github.com/rashidazarang/airtable-mcp) — Airtable integration for AI applications ☆`87`
- [PSU3D0/agent-spreadsheet](https://github.com/PSU3D0/agent-spreadsheet) — Analyze and edit spreadsheets with a small tool set ☆`63`
- [edwinbernadus/nocodb-mcp-server](https://github.com/edwinbernadus/nocodb-mcp-server) — nocodb mcp server ☆`76`
- [felores/airtable-mcp](https://github.com/felores/airtable-mcp) — Manage Airtable bases and records ☆`75`
- [logisky/logisheets-mcp](https://github.com/logisky/logisheets-mcp) — Spreadsheet an agent can calculate in, then export as xlsx ☆`41`
- [proompteng/bilig](https://github.com/proompteng/bilig) — Headless spreadsheet formulas, edits, and JSON persistence ☆`35`
- [kazz187/mcp-google-spreadsheet](https://github.com/kazz187/mcp-google-spreadsheet) — MCP Server for Google Spreadsheet ☆`51`
- [VOYAGER-Inc/excel-vision-mcp](https://github.com/VOYAGER-Inc/excel-vision-mcp) — Read images embedded in an Excel file ☆`20`
### Streaming & Messaging

- [confluentinc/mcp-confluent](https://github.com/confluentinc/mcp-confluent) — MCP server for Confluent Kafka platform ☆`170`
- [kanapuli/mcp-kafka](https://github.com/kanapuli/mcp-kafka) — A Model Context Protocol Server to perform Kafka client operations ☆`82`
- [amazon-mq/mcp-server-rabbitmq](https://github.com/amazon-mq/mcp-server-rabbitmq) — MCP server for RabbitMQ ☆`43`
- [tuannvm/kafka-mcp-server](https://github.com/tuannvm/kafka-mcp-server) — Apache Kafka server in Go ☆`57`
- [kenliao94/mcp-server-rabbitmq](https://github.com/kenliao94/mcp-server-rabbitmq) — MCP server for interacting with RabbitMQ ☆`38`
### Time-Series & Metrics

- [GreptimeTeam/greptimedb](https://github.com/GreptimeTeam/greptimedb) — Unified observability DB for metrics, logs, traces ☆`6,802`
- [pab1it0/prometheus-mcp-server](https://github.com/pab1it0/prometheus-mcp-server) — MCP server for Prometheus metrics ☆`524`
- [VictoriaMetrics/mcp-victorialogs](https://github.com/VictoriaMetrics/mcp-victorialogs) — VictoriaLogs log management integration ☆`110`
- [idoru/influxdb-mcp-server](https://github.com/idoru/influxdb-mcp-server) — An MCP Server for querying InfluxDB ☆`49`
- [apache/iotdb-mcp-server](https://github.com/apache/iotdb-mcp-server) — Apache IoTDB MCP Server ☆`40`
- [influxdata/influxdb3_mcp_server](https://github.com/influxdata/influxdb3_mcp_server) — MCP Server for InfluxDB 3 ☆`38`
- [GreptimeTeam/greptimedb-mcp-server](https://github.com/GreptimeTeam/greptimedb-mcp-server) — A Model Context Protocol (MCP) server for GreptimeDB ☆`29`
### Vector Databases

- [qdrant/mcp-server-qdrant](https://github.com/qdrant/mcp-server-qdrant) — Official Qdrant vector database MCP ☆`1,567`
- [chroma-core/chroma-mcp](https://github.com/chroma-core/chroma-mcp) — Chroma vector database capabilities ☆`602`
- [zilliztech/mcp-server-milvus](https://github.com/zilliztech/mcp-server-milvus) — Model Context Protocol Servers for Milvus ☆`245`
- [weaviate/mcp-server-weaviate](https://github.com/weaviate/mcp-server-weaviate) — MCP (Model Context Protocol) server for Weaviate ☆`162`
- [pinecone-io/pinecone-mcp](https://github.com/pinecone-io/pinecone-mcp) — Connect Pinecone to AI assistants ☆`72`
- [mhalder/qdrant-mcp-server](https://github.com/mhalder/qdrant-mcp-server) — Semantic search in a local Qdrant database ☆`36`
- [privetin/chroma](https://github.com/privetin/chroma) — MCP server for Chroma ☆`41`
- [delorenj/mcp-qdrant-memory](https://github.com/delorenj/mcp-qdrant-memory) — Knowledge graph with semantic search in Qdrant ☆`24`
- [p-funk/fegis](https://github.com/p-funk/fegis) — Define tools in YAML and store each call in Qdrant ☆`24`
## Developer Tools

### API Tools

- [tadata-org/fastapi_mcp](https://github.com/tadata-org/fastapi_mcp) — Expose FastAPI endpoints as MCP tools ☆`12,028`
- [WordPress/mcp-adapter](https://github.com/WordPress/mcp-adapter) — Bridge Abilities API to MCP ☆`1,914`
- [zcaceres/fetch-mcp](https://github.com/zcaceres/fetch-mcp) — A flexible HTTP fetching Model Context Protocol server. ☆`837`
- [automation-ai-labs/mcp-link](https://github.com/automation-ai-labs/mcp-link) — Convert Any OpenAPI V3 API to MCP Server ☆`624`
- [blurrah/mcp-graphql](https://github.com/blurrah/mcp-graphql) — Model Context Protocol server for GraphQL ☆`407`
- [postmanlabs/postman-mcp-server](https://github.com/postmanlabs/postman-mcp-server) — Postman collections, OpenAPI specs, and environments ☆`328`
- [apollographql/apollo-mcp-server](https://github.com/apollographql/apollo-mcp-server) — Apollo MCP Server ☆`318`
- [MFYDev/ghost-mcp](https://github.com/MFYDev/ghost-mcp) — Interact with Ghost CMS via LLM ☆`244`
- [hostinger/api-mcp-server](https://github.com/hostinger/api-mcp-server) — MCP server for Hostinger API integration ☆`171`
- [getmockd/mockd](https://github.com/getmockd/mockd) — One binary that mocks HTTP, gRPC, MQTT, GraphQL and more ☆`155`
- [webflow/mcp-server](https://github.com/webflow/mcp-server) — Model Context Protocol (MCP) server for the Webflow Data API. ☆`141`
- [delano/postman-mcp-server](https://github.com/delano/postman-mcp-server) — An MCP server that provides access to Postman. ☆`157`
- [shannonlal/mcp-postman](https://github.com/shannonlal/mcp-postman) — MCP Server for running Postman Collections with Newman ☆`84`
- [ivo-toby/contentful-mcp](https://github.com/ivo-toby/contentful-mcp) — Contentful CMS Management API ☆`62`
- [Arize-ai/text-to-graphql-mcp](https://github.com/Arize-ai/text-to-graphql-mcp) — MCP server for text-to-GraphQL conversion ☆`26`
- [Omedia/mcp-server-drupal](https://github.com/Omedia/mcp-server-drupal) — Drupal MCP module companion ☆`51`
- [shanejonas/openrpc-mcp-server](https://github.com/shanejonas/openrpc-mcp-server) — JSON-RPC via OpenRPC ☆`43`
- [xxxbrian/mcp-rquest](https://github.com/xxxbrian/mcp-rquest) — Browser-like HTTP with TLS fingerprinting ☆`47`
- [hannesj/mcp-graphql-schema](https://github.com/hannesj/mcp-graphql-schema) — GraphQL Schema Model Context Protocol Server ☆`46`
- [Jktfe/serveMyAPI](https://github.com/Jktfe/serveMyAPI) — MCP server for custom API serving ☆`25`
- [hijaz/postmancer](https://github.com/hijaz/postmancer) — REST client replacing Postman/Insomnia ☆`29`
- [fotoetienne/gqai](https://github.com/fotoetienne/gqai) — Turn any GraphQL endpoint into a set of MCP tools ☆`23`
- [drestrepom/mcp_graphql](https://github.com/drestrepom/mcp_graphql) — Interact with GraphQL APIs via MCP tools ☆`19`
### CI/CD & DevOps

- [czlonkowski/n8n-mcp](https://github.com/czlonkowski/n8n-mcp) — Build n8n workflows with AI assistants ☆`23,235`
- [leonardsellem/n8n-mcp-server](https://github.com/leonardsellem/n8n-mcp-server) — Tools for interacting with n8n API ☆`1,630`
- [googleapis/gcloud-mcp](https://github.com/googleapis/gcloud-mcp) — gcloud MCP server ☆`948`
- [utensils/mcp-nixos](https://github.com/utensils/mcp-nixos) — MCP-NixOS - Model Context Protocol Server for NixOS resources ☆`883`
- [ckreiling/mcp-server-docker](https://github.com/ckreiling/mcp-server-docker) — MCP server for Docker ☆`753`
- [vercel-labs/mcp-handler](https://github.com/vercel-labs/mcp-handler) — MCP server helper for Next.js, Nuxt and Svelte ☆`697`
- [QuantGeekDev/docker-mcp](https://github.com/QuantGeekDev/docker-mcp) — A docker MCP Server (modelcontextprotocol) ☆`504`
- [jamsocket/forevervm](https://github.com/jamsocket/forevervm) — Stateful AI code sandboxes ☆`230`
- [docker/hub-mcp](https://github.com/docker/hub-mcp) — Docker Hub MCP Server ☆`171`
- [DefangLabs/defang](https://github.com/DefangLabs/defang) — MCP server for Defang cloud deployment ☆`167`
- [yangkyeongmo/mcp-server-apache-airflow](https://github.com/yangkyeongmo/mcp-server-apache-airflow) — MCP server for Apache Airflow workflows ☆`182`
- [MatanYemini/bitbucket-mcp](https://github.com/MatanYemini/bitbucket-mcp) — Bitbucket Cloud and Server repositories and pull requests ☆`168`
- [nacos-group/nacos-mcp-router](https://github.com/nacos-group/nacos-mcp-router) — MCP server discovery, install, and proxy ☆`183`
- [harness/mcp-server](https://github.com/harness/mcp-server) — Harness’ official MCP Server ☆`113`
- [OctopusDeploy/mcp-server](https://github.com/OctopusDeploy/mcp-server) — Octopus Deploy Official MCP Server ☆`103`
- [buildkite/buildkite-mcp-server](https://github.com/buildkite/buildkite-mcp-server) — Official MCP Server for Buildkite. ☆`56`
- [Vortiago/mcp-azure-devops](https://github.com/Vortiago/mcp-azure-devops) — AI assistants with Azure DevOps ☆`79`
- [call518/MCP-Airflow-API](https://github.com/call518/MCP-Airflow-API) — Apache Airflow API integration ☆`54`
- [bitrise-io/bitrise-mcp](https://github.com/bitrise-io/bitrise-mcp) — Bitrise CI/CD app and build management ☆`43`
- [Daghis/teamcity-mcp](https://github.com/Daghis/teamcity-mcp) — Builds, tests, agents and configs in JetBrains TeamCity ☆`32`
- [ruudmens/Koppla](https://github.com/ruudmens/Koppla) — A Model-Context-Protocol (MCP) Server for Active Directory ☆`58`
- [launchdarkly/mcp-server](https://github.com/launchdarkly/mcp-server) — Local server for LaunchDarkly feature flags ☆`27`
- [IvanAmador/vercel-ai-docs-mcp](https://github.com/IvanAmador/vercel-ai-docs-mcp) — Vercel AI SDK documentation search ☆`50`
- [leonardosepulvedat/mcp-n8n](https://github.com/leonardosepulvedat/mcp-n8n) — n8n API plus 100 workflow templates with matching ☆`22`
- [raye-deng/open-code-review](https://github.com/raye-deng/open-code-review) — Flag hallucinated packages and stale APIs ☆`40`
- [gofireflyio/firefly-mcp](https://github.com/gofireflyio/firefly-mcp) — Firefly MCP ☆`16`
- [configcat/mcp-server](https://github.com/configcat/mcp-server) — Official ConfigCat Model Context Protocol (MCP) Server ☆`17`
- [ruibaby/1Panel-mcp](https://github.com/ruibaby/1Panel-mcp) — Deploy a site onto 1Panel ☆`36`
- [prassanna-ravishankar/clearml-mcp](https://github.com/prassanna-ravishankar/clearml-mcp) — lightweight MCP server for ClearML ☆`17`
- [endorhq/cli](https://github.com/endorhq/cli) — Sandboxed environments for favorite services via MCP ☆`26`
- [serkanh/cloudwatch-logs-mcp](https://github.com/serkanh/cloudwatch-logs-mcp) — List CloudWatch log groups and read filtered events ☆`27`
- [conductor-oss/conductor-mcp](https://github.com/conductor-oss/conductor-mcp) — Model Context Protocol server for Orkes Conductor ☆`16`
- [shinzo-labs/heimdall](https://github.com/shinzo-labs/heimdall) — Limit which MCP tools an agent is allowed to call ☆`21`
- [axliupore/mcp-code-runner](https://github.com/axliupore/mcp-code-runner) — MCP server for executing code in Docker containers ☆`18`
### Code Analysis

- [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) — Persistent graph of code, docs and infrastructure ☆`48,430`
- [kucherenko/jscpd](https://github.com/kucherenko/jscpd) — Find copy-pasted code across more than 200 languages ☆`6,526`
- [cocoindex-io/cocoindex-code](https://github.com/cocoindex-io/cocoindex-code) — Lightweight AST search over a codebase ☆`2,974`
- [Mibayy/token-savior](https://github.com/Mibayy/token-savior) — Structural code navigation and memory that cut active tokens ☆`1,214`
- [bgauryy/octocode](https://github.com/bgauryy/octocode) — Find and cite code in your repos and on GitHub, in fewer tokens ☆`959`
- [SonarSource/sonarqube-mcp-server](https://github.com/SonarSource/sonarqube-mcp-server) — Official SonarQube quality and security for agents ☆`685`
- [Muvon/octocode](https://github.com/Muvon/octocode) — Semantic search and a knowledge graph of code, in one Rust binary ☆`523`
- [admica/FileScopeMCP](https://github.com/admica/FileScopeMCP) — Codebase dependency diagrams ☆`303`
- [ozgurcd/gograph](https://github.com/ozgurcd/gograph) — Call graphs, impact and symbol search for Go, locally ☆`231`
- [nikolai-vysotskyi/trace-mcp](https://github.com/nikolai-vysotskyi/trace-mcp) — Framework-aware code intelligence across many languages ☆`203`
- [janreges/ai-distiller](https://github.com/janreges/ai-distiller) — Fast tool for extracting essential public information from code ☆`172`
- [ajitpratap0/GoSQLX](https://github.com/ajitpratap0/GoSQLX) — Pure-Go SQL parser, formatter, linter and scanner, plus LSP ☆`124`
- [SimplyLiz/ckb](https://github.com/SimplyLiz/ckb) — Symbol navigation, impact and architecture for a codebase ☆`112`
- [st3v3nmw/sourcerer-mcp](https://github.com/st3v3nmw/sourcerer-mcp) — Semantic code search reducing token waste ☆`121`
- [micl2e2/code-to-tree](https://github.com/micl2e2/code-to-tree) — Source code to AST tree conversion ☆`89`
- [codacy/codacy-mcp-server](https://github.com/codacy/codacy-mcp-server) — Codacy's MCP Server implementation ☆`58`
- [lineai-intelligence/lineai-mcp-server](https://github.com/lineai-intelligence/lineai-mcp-server) — Codelogic software dependency analysis ☆`37`
- [Disentinel/grafema](https://github.com/Disentinel/grafema) — Semantic code graphs for call chains, data flow, and search ☆`35`
- [kandrwmrtn/cplusplus_mcp](https://github.com/kandrwmrtn/cplusplus_mcp) — MCP server for C++ codebase analysis using libclang ☆`34`
- [azer/react-analyzer-mcp](https://github.com/azer/react-analyzer-mcp) — React code analysis and docs generation ☆`58`
- [Luqueee/kivgraph](https://github.com/Luqueee/kivgraph) — Semantic code graph across TypeScript and Go repositories ☆`23`
- [vezlo/src-to-kb](https://github.com/vezlo/src-to-kb) — Convert source code to LLM ready knowledge base ☆`40`
- [isiahw1/mcp-server-bing-webmaster](https://github.com/isiahw1/mcp-server-bing-webmaster) — Bing Webmaster Tools for SEO and analytics ☆`31`
- [cqfn/aibolit-mcp-server](https://github.com/cqfn/aibolit-mcp-server) — Aibolit Java static analyzer for AI agents ☆`27`
- [j4c0bs/mcp-server-sql-analyzer](https://github.com/j4c0bs/mcp-server-sql-analyzer) — MCP server for SQL static analysis. ☆`32`
- [danielbowne/claude-context](https://github.com/danielbowne/claude-context) — Semantic code search with a local LanceDB index ☆`17`
### Debuggers

- [Continuum-AI-Corp/OrcaReplay](https://github.com/Continuum-AI-Corp/OrcaReplay) — Record, replay and fork coding-agent runs ☆`504`
- [jasonjmcghee/claude-debugs-for-you](https://github.com/jasonjmcghee/claude-debugs-for-you) — Interactive debugging via MCP and VS Code ☆`515`
- [cameroncooke/reloaderoo](https://github.com/cameroncooke/reloaderoo) — Powerful MCP debugging proxy and CLI inspection tool. ☆`127`
- [stass/lldb-mcp](https://github.com/stass/lldb-mcp) — LLDB MCP server ☆`114`
- [pansila/mcp_server_gdb](https://github.com/pansila/mcp_server_gdb) — MCP Server to expose the GDB debugging capabilities ☆`68`
- [knewstimek/agent-tool](https://github.com/knewstimek/agent-tool) — Encoding-aware files, binary analysis, a debugger and SSH ☆`26`
- [Jubstaaa/hono-telescope](https://github.com/Jubstaaa/hono-telescope) — Live requests, exceptions and queries from a Hono app ☆`27`
- [imatza-rh/mcp-zuul](https://github.com/imatza-rh/mcp-zuul) — Debug Zuul CI failures, logs and pipelines ☆`21`
### Design & UI

- [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) — Figma layout info for AI coding agents ☆`16,189`
- [grab/cursor-talk-to-figma-mcp](https://github.com/grab/cursor-talk-to-figma-mcp) — Cursor and Figma communication ☆`7,101`
- [21st-dev/magic-mcp](https://github.com/21st-dev/magic-mcp) — Frontend development with AI like Magic ☆`6,455`
- [Jpisnice/shadcn-ui-mcp-server](https://github.com/Jpisnice/shadcn-ui-mcp-server) — MCP server for shadcn/ui component library ☆`3,095`
- [modelcontextprotocol/ext-apps](https://github.com/modelcontextprotocol/ext-apps) — Spec and SDK for MCP apps embedded in a chat ☆`3,068`
- [awdr74100/figwright](https://github.com/awdr74100/figwright) — Two-way Figma: design to code, and code back to the canvas ☆`1,353`
- [gethopp/figma-mcp-bridge](https://github.com/gethopp/figma-mcp-bridge) — Figma Plugin & MCP server to bypass API limits ☆`906`
- [hustcc/mcp-mermaid](https://github.com/hustcc/mcp-mermaid) — Generate mermaid diagram and chart with AI MCP dynamically. ☆`649`
- [marvkr/better-design](https://github.com/marvkr/better-design) — Design system and shadcn/ui registry for MCP clients ☆`567`
- [public-ui/kolibri](https://github.com/public-ui/kolibri) — The accessible HTML-Standard ☆`290`
- [mastergo-design/mastergo-magic-mcp](https://github.com/mastergo-design/mastergo-magic-mcp) — Connect MasterGo to AI assistants ☆`288`
- [YuChenSSR/mindmap-mcp-server](https://github.com/YuChenSSR/mindmap-mcp-server) — mindmap, mcp server, artifact ☆`240`
- [MatthewDailey/figma-mcp](https://github.com/MatthewDailey/figma-mcp) — ModelContextProtocol for Figma's REST API ☆`214`
- [TimHolden/figma-mcp-server](https://github.com/TimHolden/figma-mcp-server) — Model Context Protocol server implementation for Figma API ☆`149`
- [freema/mcp-design-system-extractor](https://github.com/freema/mcp-design-system-extractor) — MCP server for extracting design system components ☆`73`
- [thirdstrandstudio/mcp-figma](https://github.com/thirdstrandstudio/mcp-figma) — Figma MCP Server with full API functionality ☆`77`
- [starwind-ui/starwind-ui-mcp](https://github.com/starwind-ui/starwind-ui-mcp) — Starwind UI for Cursor and Windsurf ☆`35`
- [themesberg/flowbite-mcp](https://github.com/themesberg/flowbite-mcp) — Figma to code with Flowbite ☆`42`
- [kapilduraphe/webflow-mcp-server](https://github.com/kapilduraphe/webflow-mcp-server) — Webflow MCP server ☆`21`
- [NonicaTeam/AI-Connector-for-Revit](https://github.com/NonicaTeam/AI-Connector-for-Revit) — Issue tracker for the NonicaTab Revit AI Connector ☆`19`
- [themeselection/flyonui-mcp](https://github.com/themeselection/flyonui-mcp) — MCP server for flyonUI ☆`33`
- [smartzan63/lucid-mcp-server](https://github.com/smartzan63/lucid-mcp-server) — Search, export, and create Lucid charts and diagrams ☆`19`
- [heilgar/shadcn-ui-mcp-server](https://github.com/heilgar/shadcn-ui-mcp-server) — MCP server for shadcn/ui component library ☆`27`
### Diagrams

- [DayuanJiang/next-ai-draw-io](https://github.com/DayuanJiang/next-ai-draw-io) — Draw and edit draw.io diagrams by chatting ☆`36,845`
- [jinzcdev/markmap-mcp-server](https://github.com/jinzcdev/markmap-mcp-server) — Markdown to interactive mind maps ☆`289`
- [veelenga/claude-mermaid](https://github.com/veelenga/claude-mermaid) — MCP Server to previewing mermaid diagrams with live reload ☆`221`
- [apeyroux/mcp-xmind](https://github.com/apeyroux/mcp-xmind) — Analyze and query XMind mind maps ☆`95`
- [paulhkang94/markview](https://github.com/paulhkang94/markview) — Native Mac markdown preview, with Mermaid ☆`38`
- [Narasimhaponnada/mermaid-mcp](https://github.com/Narasimhaponnada/mermaid-mcp) — MCP server for Mermaid diagram generation ☆`53`
### Documentation

- [upstash/context7](https://github.com/upstash/context7) — Up-to-date code docs for LLMs ☆`64,550`
- [microsoft/mcp-for-beginners](https://github.com/microsoft/mcp-for-beginners) — Cross-language curriculum for learning MCP ☆`17,634`
- [modelcontextprotocol/modelcontextprotocol](https://github.com/modelcontextprotocol/modelcontextprotocol) — Specification and documentation for MCP ☆`9,655`
- [lingodotdev/lingo.dev](https://github.com/lingodotdev/lingo.dev) — MCP server for Lingo localization platform ☆`5,402`
- [liaokongVFX/MCP-Chinese-Getting-Started-Guide](https://github.com/liaokongVFX/MCP-Chinese-Getting-Started-Guide) — Chinese getting-started guide ☆`3,583`
- [MicrosoftDocs/mcp](https://github.com/MicrosoftDocs/mcp) — Microsoft Learn MCP for LLMs ☆`1,981`
- [arabold/docs-mcp-server](https://github.com/arabold/docs-mcp-server) — Serve library documentation so model answers stay grounded ☆`1,866`
- [modelcontextprotocol/quickstart-resources](https://github.com/modelcontextprotocol/quickstart-resources) — Servers and clients from the MCP tutorials ☆`1,238`
- [kimsungwhee/apple-docs-mcp](https://github.com/kimsungwhee/apple-docs-mcp) — Apple Developer Documentation search ☆`1,384`
- [andrea9293/mcp-documentation-server](https://github.com/andrea9293/mcp-documentation-server) — Document management with Gemini ☆`346`
- [context-hub/generator](https://github.com/context-hub/generator) — Collect project context so a model sees the right files ☆`342`
- [szeider/consult7](https://github.com/szeider/consult7) — MCP server to consult a language model with large context size ☆`296`
- [Govcraft/rust-docs-mcp-server](https://github.com/Govcraft/rust-docs-mcp-server) — Rust documentation lookup ☆`301`
- [Kapeli/dash-mcp-server](https://github.com/Kapeli/dash-mcp-server) — MCP server for Dash, the macOS API documentation browser ☆`190`
- [khromov/svelte-llm-mcp](https://github.com/khromov/svelte-llm-mcp) — Svelte developer documentation as an MCP and in llms.txt format ☆`159`
- [spences10/mcp-svelte-docs](https://github.com/spences10/mcp-svelte-docs) — Search the Svelte documentation ☆`124`
- [mrjoshuak/godoc-mcp](https://github.com/mrjoshuak/godoc-mcp) — Structured Go docs to avoid dumping source into context ☆`126`
- [KallistoX/mcp-unifi-applications](https://github.com/KallistoX/mcp-unifi-applications) — Search the official UniFi API docs and schemas ☆`40`
- [tosin2013/mcp-adr-analysis-server](https://github.com/tosin2013/mcp-adr-analysis-server) — AI-powered ADR and architecture analysis ☆`35`
- [mishafyi/Apple-Docs-2.0-MCP](https://github.com/mishafyi/Apple-Docs-2.0-MCP) — Apple docs, Human Interface Guidelines and WWDC sessions ☆`26`
- [0xKoda/mcp-rust-docs](https://github.com/0xKoda/mcp-rust-docs) — An MCP to retrieve rust crate documentation for LLM's ☆`47`
- [yWorks/mcp-typescribe](https://github.com/yWorks/mcp-typescribe) — TypeScript library support for LLMs ☆`46`
- [V0v1kkk/DotNetMetadataMcpServer](https://github.com/V0v1kkk/DotNetMetadataMcpServer) — .NET type metadata for AI coding agents ☆`32`
- [yikakia/godoc-mcp-server](https://github.com/yikakia/godoc-mcp-server) — Go package docs from pkg.go.dev ☆`38`
- [oborchers/mcp-server-docy](https://github.com/oborchers/mcp-server-docy) — Documentation access capabilities ☆`18`
- [Quantum3-Labs/ARBuilder](https://github.com/Quantum3-Labs/ARBuilder) — Generate Arbitrum Stylus contracts and Orbit chain code ☆`24`
- [inkeep/mcp-server-python](https://github.com/inkeep/mcp-server-python) — Inkeep MCP Server ☆`25`
- [idachev/mcp-javadc](https://github.com/idachev/mcp-javadc) — MCP server for decompiling Java .class files to source ☆`20`
- [Excoriate/mcp-terragrunt-docs](https://github.com/Excoriate/mcp-terragrunt-docs) — Terragrunt documentation context ☆`20`
- [jonathanfischer97/juliadoc-mcp](https://github.com/jonathanfischer97/juliadoc-mcp) — Fetch Julia docstrings and source ☆`18`
- [augmentedivan/fabric-mcp-server](https://github.com/augmentedivan/fabric-mcp-server) — Fabric patterns with AI agents ☆`18`
### IDE & Editors

- [PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp) — The fast, Pythonic way to build MCP servers and clients. ☆`28,377`
- [getsentry/MobileBuildMCP](https://github.com/getsentry/MobileBuildMCP) — MCP server for Xcode build operations ☆`6,562`
- [supercorp-ai/supergateway](https://github.com/supercorp-ai/supergateway) — Run a stdio MCP server over HTTP or SSE ☆`2,953`
- [samanhappy/mcphub](https://github.com/samanhappy/mcphub) — Self-hosted gateway to connect and operate MCP servers ☆`2,655`
- [isaacphi/mcp-language-server](https://github.com/isaacphi/mcp-language-server) — MCP server implementing Language Server Protocol ☆`1,617`
- [JetBrains/mcp-jetbrains](https://github.com/JetBrains/mcp-jetbrains) — MCP server for JetBrains IDE integration ☆`963`
- [maquina-app/rails-mcp-server](https://github.com/maquina-app/rails-mcp-server) — Let a model inspect and work inside a Rails project ☆`573`
- [hanlulong/stata-mcp](https://github.com/hanlulong/stata-mcp) — Stata MCP Extension for VS Code, Cursor, and Antigravity IDE ☆`522`
- [ravitemer/mcp-hub](https://github.com/ravitemer/mcp-hub) — Start, stop and monitor a set of MCP servers ☆`525`
- [VikashLoomba/copilot-mcp](https://github.com/VikashLoomba/copilot-mcp) — Find and install agent skills and MCP apps for Copilot ☆`508`
- [hechtcarmel/jetbrains-index-mcp-plugin](https://github.com/hechtcarmel/jetbrains-index-mcp-plugin) — JetBrains plugin for MCP index integration ☆`379`
- [juehang/vscode-mcp-server](https://github.com/juehang/vscode-mcp-server) — VS Code editing features for LLM coding ☆`392`
- [r-huijts/xcode-mcp-server](https://github.com/r-huijts/xcode-mcp-server) — Xcode project management ☆`386`
- [bigcodegen/mcp-neovim-server](https://github.com/bigcodegen/mcp-neovim-server) — Control Neovim via MCP ☆`325`
- [A11yance/aria-query](https://github.com/A11yance/aria-query) — Programmatic access to the ARIA specification ☆`307`
- [omnirexflora-labs/omnicoreagent](https://github.com/omnirexflora-labs/omnicoreagent) — Agent runtime that checks actions and survives crashes ☆`253`
- [biegehydra/BifrostMCP](https://github.com/biegehydra/BifrostMCP) — VS Code semantic tools via MCP ☆`225`
- [tumf/mcp-text-editor](https://github.com/tumf/mcp-text-editor) — Line-oriented text editing for LLM tools ☆`202`
- [adamwattis/mcp-proxy-server](https://github.com/adamwattis/mcp-proxy-server) — One proxy in front of several MCP resource servers ☆`202`
- [cyanheads/mcp-ts-core](https://github.com/cyanheads/mcp-ts-core) — Agent-native TypeScript framework for building MCP servers. ☆`153`
- [aspect-build/rules_ts](https://github.com/aspect-build/rules_ts) — Bazel rules for the tsc compiler from http://typescriptlang.org ☆`139`
- [hechtcarmel/jetbrains-debugger-mcp-plugin](https://github.com/hechtcarmel/jetbrains-debugger-mcp-plugin) — JetBrains debugger control via MCP ☆`118`
- [leehack/mcp_dart](https://github.com/leehack/mcp_dart) — Dart implementation of MCP SDK ☆`116`
- [lucasmontano/mcp-montano-server](https://github.com/lucasmontano/mcp-montano-server) — Simple MCP Server Implementation ☆`133`
- [Tritlo/lsp-mcp](https://github.com/Tritlo/lsp-mcp) — An MCP server that lets you interact with LSP servers ☆`128`
- [hloiseau/mcp-gopls](https://github.com/hloiseau/mcp-gopls) — Go LSP server via gopls ☆`104`
- [dkmaker/mcp-rest-api](https://github.com/dkmaker/mcp-rest-api) — Call any REST endpoint and inspect the response ☆`103`
- [bourhaouta/vscode-tailwindshades](https://github.com/bourhaouta/vscode-tailwindshades) — Tailwind palettes from any color ☆`79`
- [linw1995/nvim-mcp](https://github.com/linw1995/nvim-mcp) — MCP server for Neovim integration ☆`76`
- [hanweg/mcp-pdf-tools](https://github.com/hanweg/mcp-pdf-tools) — MCP server for working with PDF files ☆`76`
- [vertile-ai/next-mcp-server](https://github.com/vertile-ai/next-mcp-server) — Help LLMs to understand your Next apps better ☆`99`
- [paulburgess1357/nvim-mcp](https://github.com/paulburgess1357/nvim-mcp) — Drive a running Neovim instance, with no plugin ☆`67`
- [marimo-team/codemirror-mcp](https://github.com/marimo-team/codemirror-mcp) — CodeMirror MCP extension ☆`79`
- [ShenghaiWang/xcodebuild](https://github.com/ShenghaiWang/xcodebuild) — Xcode iOS build with error feedback ☆`85`
- [AllAboutAI-YT/mcp-servers](https://github.com/AllAboutAI-YT/mcp-servers) — All About AI MCP Servers ☆`81`
- [xpn/mythic_mcp](https://github.com/xpn/mythic_mcp) — A simple POC to expose Mythic as a MCP server ☆`81`
- [aashari/boilerplate-mcp-server](https://github.com/aashari/boilerplate-mcp-server) — TypeScript MCP boilerplate with an IP lookup ☆`73`
- [lucianoayres/mcp-server-node](https://github.com/lucianoayres/mcp-server-node) — Example Node.js MCP server with a prompt and custom tools ☆`76`
- [laurynas-biveinis/elisp-dev-mcp](https://github.com/laurynas-biveinis/elisp-dev-mcp) — Emacs Elisp development tools for LLMs ☆`49`
- [phughesmcr/deno-mcp-template](https://github.com/phughesmcr/deno-mcp-template) — Template for a local, remote or binary MCP server in Deno ☆`34`
- [WatermelonBros/reado](https://github.com/WatermelonBros/reado) — Comment on lines and let the agent resolve them ☆`31`
- [anggasct/mcp-insomnia](https://github.com/anggasct/mcp-insomnia) — Create Insomnia collections, requests and environments ☆`27`
- [borisdan/mcp-audit-extension](https://github.com/borisdan/mcp-audit-extension) — Log every GitHub Copilot MCP tool call in VS Code ☆`27`
- [riza-io/mcp-go](https://github.com/riza-io/mcp-go) — Build Model Context Protocol (MCP) servers in Go ☆`36`
- [tanevanwifferen/mcp-inception](https://github.com/tanevanwifferen/mcp-inception) — Call one MCP client from another to split the context ☆`28`
- [baronfel/mcp-binlog-tool](https://github.com/baronfel/mcp-binlog-tool) — Inspect MSBuild binary logs to explain a build ☆`22`
- [Jacck/mcp-ortools](https://github.com/Jacck/mcp-ortools) — Constraint solving with Google OR-Tools ☆`22`
- [AB498/code-context-provider-mcp](https://github.com/AB498/code-context-provider-mcp) — Code context and analysis for AI ☆`20`
- [kaichen/mcp-local-router](https://github.com/kaichen/mcp-local-router) — Local proxy that aggregates several MCP servers ☆`18`
### MCP SDKs

- [modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk) — Official Python SDK for MCP servers and clients ☆`24,818`
- [modelcontextprotocol/typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk) — Official TypeScript SDK for MCP ☆`13,740`
- [mark3labs/mcp-go](https://github.com/mark3labs/mcp-go) — Go implementation of MCP ☆`9,233`
- [modelcontextprotocol/go-sdk](https://github.com/modelcontextprotocol/go-sdk) — Official Go SDK for MCP servers and clients ☆`5,328`
- [modelcontextprotocol/csharp-sdk](https://github.com/modelcontextprotocol/csharp-sdk) — Official C# SDK for MCP servers and clients ☆`4,625`
- [modelcontextprotocol/rust-sdk](https://github.com/modelcontextprotocol/rust-sdk) — The official Rust SDK for the Model Context Protocol ☆`4,104`
- [modelcontextprotocol/java-sdk](https://github.com/modelcontextprotocol/java-sdk) — Official Java SDK for MCP servers and clients ☆`3,765`
- [modelcontextprotocol/php-sdk](https://github.com/modelcontextprotocol/php-sdk) — Official PHP SDK for MCP servers and clients ☆`1,666`
- [modelcontextprotocol/swift-sdk](https://github.com/modelcontextprotocol/swift-sdk) — Official Swift SDK for MCP servers and clients ☆`1,572`
- [modelcontextprotocol/kotlin-sdk](https://github.com/modelcontextprotocol/kotlin-sdk) — Official Kotlin SDK for MCP servers and clients ☆`1,487`
- [metoro-io/mcp-golang](https://github.com/metoro-io/mcp-golang) — Write an MCP server in a few lines of Go ☆`1,230`
- [modelcontextprotocol/ruby-sdk](https://github.com/modelcontextprotocol/ruby-sdk) — Official Ruby SDK for MCP servers and clients ☆`949`
- [QuantGeekDev/mcp-framework](https://github.com/QuantGeekDev/mcp-framework) — TypeScript framework with auto-discovery ☆`931`
- [bhauman/clojure-mcp](https://github.com/bhauman/clojure-mcp) — Clojure MCP ☆`786`
- [baidubce/app-builder](https://github.com/baidubce/app-builder) — SDK for building AI applications on Baidu AppBuilder ☆`587`
- [php-mcp/laravel](https://github.com/php-mcp/laravel) — Laravel SDK for building MCP servers ☆`477`
- [ghost-in-the-droid/android-agent](https://github.com/ghost-in-the-droid/android-agent) — Drive a real Android phone or iPhone from an agent ☆`416`
- [opgginc/laravel-mcp-server](https://github.com/opgginc/laravel-mcp-server) — Laravel package for MCP servers ☆`331`
- [zcaceres/easy-mcp](https://github.com/zcaceres/easy-mcp) — Absurdly easy Model Context Protocol Servers in Typescript ☆`197`
- [agentfront/frontmcp](https://github.com/agentfront/frontmcp) — TypeScript framework for MCP tools, services and access rules ☆`148`
- [dev-mirzabicer/ticktick-sdk](https://github.com/dev-mirzabicer/ticktick-sdk) — Async Python client for TickTick, with MCP tools ☆`148`
- [agentcathq/agentcat-typescript-sdk](https://github.com/agentcathq/agentcat-typescript-sdk) — TypeScript SDK for analytics on your MCP server ☆`127`
- [Epistates/turbomcp](https://github.com/Epistates/turbomcp) — High-performance MCP framework ☆`99`
- [bulutarkan/mac-mcp](https://github.com/bulutarkan/mac-mcp) — Let an assistant use Mac apps, files, the terminal and the browser ☆`97`
- [agentcathq/agentcat-python-sdk](https://github.com/agentcathq/agentcat-python-sdk) — Python SDK for analytics on your MCP server ☆`53`
- [edwin-finance/edwin](https://github.com/edwin-finance/edwin) — Empowering AI agents to dominate DeFAI ☆`66`
- [justjoehere/mcp_gradio_client](https://github.com/justjoehere/mcp_gradio_client) — Example of a Gradio UI built on the MCP Python client ☆`68`
- [tachyonmcp/tachyon](https://github.com/tachyonmcp/tachyon) — Java/Kotlin MCP runtime with HTTP, Netty, and sessions ☆`38`
- [reflagcom/javascript](https://github.com/reflagcom/javascript) — JS/TS SDKs for Reflag ☆`26`
- [oatpp/oatpp-mcp](https://github.com/oatpp/oatpp-mcp) — C++ MCP implementation for Oat++ framework ☆`50`
- [IvanMurzak/MCP-Plugin-dotnet](https://github.com/IvanMurzak/MCP-Plugin-dotnet) — Expose a .NET app's methods as MCP tools ☆`21`
- [LastSearch-HQ/lastsearch](https://github.com/LastSearch-HQ/lastsearch) — Web search that returns citations and a confidence score ☆`20`
- [Alation/alation-ai-agent-sdk](https://github.com/Alation/alation-ai-agent-sdk) — Call the Alation API from agent workflows ☆`18`
- [micl2e2/mcpc](https://github.com/micl2e2/mcpc) — Cross-platform C SDK for Model Context Protocol (MCP), in modern C23. ☆`35`
- [Super-I-Tech/mcp_plexus](https://github.com/Super-I-Tech/mcp_plexus) — Multi-tenant MCP framework built on FastMCP ☆`31`
- [vrknetha/aisdk-mcp-bridge](https://github.com/vrknetha/aisdk-mcp-bridge) — Use MCP servers as tools in the Vercel AI SDK ☆`23`
- [stephencme/create-mcp-ts](https://github.com/stephencme/create-mcp-ts) — TypeScript MCP server template ☆`21`
- [MushroomFleet/DeepLucid3D-MCP](https://github.com/MushroomFleet/DeepLucid3D-MCP) — Structured thinking tools for hard problems ☆`16`
- [mcpagents-ai/mcpagentai](https://github.com/mcpagents-ai/mcpagentai) — Python SDK for connecting to MCP servers and calling tools ☆`21`
- [waldzellai/mcp-agent-ts](https://github.com/waldzellai/mcp-agent-ts) — TypeScript port of the MCP Agent framework ☆`18`
### Mobile Development

- [mobile-next/mobile-mcp](https://github.com/mobile-next/mobile-mcp) — Mobile automation for iOS, Android, emulators ☆`10,480`
- [callstack/agent-device](https://github.com/callstack/agent-device) — Control phones, browsers, TVs and desktop apps on devices ☆`5,319`
- [joshuayoes/ios-simulator-mcp](https://github.com/joshuayoes/ios-simulator-mcp) — MCP server for interacting with the iOS simulator ☆`2,216`
- [minhalvp/android-mcp-server](https://github.com/minhalvp/android-mcp-server) — Android device control via adb ☆`811`
- [hyperb1iss/droidmind](https://github.com/hyperb1iss/droidmind) — Control your Android devices with AI using Model Context Protocol ☆`453`
- [Arenukvern/mcp_flutter](https://github.com/Arenukvern/mcp_flutter) — Flutter toolkit with visual and semantic snapshots for agents ☆`398`
- [InditexTech/mcp-server-simulator-ios-idb](https://github.com/InditexTech/mcp-server-simulator-ios-idb) — MCP server for iOS simulator via IDB ☆`346`
- [mhmzdev/figma-flutter-mcp](https://github.com/mhmzdev/figma-flutter-mcp) — Figma design tokens for Flutter code agents ☆`242`
- [ateymoori/oh-my-android](https://github.com/ateymoori/oh-my-android) — Drive the Android emulator and phones from macOS ☆`141`
- [zelentsov-dev/asc-mcp](https://github.com/zelentsov-dev/asc-mcp) — Apps, builds, TestFlight and subscriptions in App Store Connect ☆`84`
- [ethbak/icon-composer-mcp](https://github.com/ethbak/icon-composer-mcp) — Build and edit Apple .icon bundles, including Liquid Glass ☆`69`
- [zillow/auto-mobile](https://github.com/zillow/auto-mobile) — Mobile automation tools with MCP ☆`80`
- [martingeidobler/android-mcp-server](https://github.com/martingeidobler/android-mcp-server) — Screenshots, taps and logcat on an Android emulator ☆`69`
- [mikusnuz/app-publish-mcp](https://github.com/mikusnuz/app-publish-mcp) — Listings and releases on the App Store and Google Play ☆`40`
- [Nagarjuna2997/ios-agent-skill](https://github.com/Nagarjuna2997/ios-agent-skill) — Review Swift and run the app in the Simulator ☆`41`
- [JoshuaRileyDev/simulator-mcp-server](https://github.com/JoshuaRileyDev/simulator-mcp-server) — MCP server for iOS Simulator control ☆`53`
- [Tommertom/awesome-ionic-mcp](https://github.com/Tommertom/awesome-ionic-mcp) — Ionic and Capacitor mobile app development ☆`45`
- [kao273183/mk-qa-master](https://github.com/kao273183/mk-qa-master) — MCP server that drives pytest, Jest, Cypress, Go and Maestro ☆`37`
- [FidelisMM/shipstores](https://github.com/FidelisMM/shipstores) — Ship iOS and Android builds to the stores and Expo ☆`21`
- [thecombatwombat/replicant-mcp](https://github.com/thecombatwombat/replicant-mcp) — Android control aimed at accessibility and fewer tokens ☆`19`
- [iksnerd/adb-mcp](https://github.com/iksnerd/adb-mcp) — Screenshots, taps and logcat on Android over adb ☆`18`
- [XixianLiang/HarmonyOS-mcp-server](https://github.com/XixianLiang/HarmonyOS-mcp-server) — MCP server for manipulating HarmonyOS next devices. ☆`35`
- [Neverlow512/agent-droid-bridge](https://github.com/Neverlow512/agent-droid-bridge) — Control Android devices and emulators over adb ☆`23`
- [ambar/simctl-mcp](https://github.com/ambar/simctl-mcp) — MCP server for iOS Simulator control ☆`20`
### OpenAPI

- [open-webui/mcpo](https://github.com/open-webui/mcpo) — A simple, secure MCP-to-OpenAPI proxy server ☆`4,422`
- [koreainvestment/open-trading-api](https://github.com/koreainvestment/open-trading-api) — Korea Investment & Securities Open API Github ☆`1,662`
- [cuga-project/cuga-agent](https://github.com/cuga-project/cuga-agent) — Enterprise agent harness for tasks on the web and on APIs ☆`1,141`
- [janwilmake/openapi-mcp-server](https://github.com/janwilmake/openapi-mcp-server) — Complex OpenAPI exploration with plain language ☆`905`
- [mattt/emcee](https://github.com/mattt/emcee) — MCP generator for OpenAPIs ☆`334`
- [ivo-toby/mcp-openapi-server](https://github.com/ivo-toby/mcp-openapi-server) — Turn an OpenAPI spec into MCP resources ☆`301`
- [higress-group/openapi-to-mcpserver](https://github.com/higress-group/openapi-to-mcpserver) — OpenAPI document to a Higress MCP server config ☆`292`
- [ckanthony/openapi-mcp](https://github.com/ckanthony/openapi-mcp) — Dockerized OpenAPI to MCP conversion ☆`199`
- [twilio-labs/mcp](https://github.com/twilio-labs/mcp) — OpenAPI to MCP tools and Twilio APIs ☆`114`
- [kadykov/mcp-openapi-schema-explorer](https://github.com/kadykov/mcp-openapi-schema-explorer) — Token-efficient OpenAPI/Swagger exploration ☆`76`
- [ReAPI-com/mcp-openapi](https://github.com/ReAPI-com/mcp-openapi) — OpenAPI specification MCP server. ☆`90`
- [zaizaizhao/mcp-swagger-server](https://github.com/zaizaizhao/mcp-swagger-server) — OpenAPI/Swagger to MCP conversion ☆`77`
- [baryhuang/mcp-server-any-openapi](https://github.com/baryhuang/mcp-server-any-openapi) — Call APIs via semantic search ☆`82`
- [gunpal5/QuickMCP](https://github.com/gunpal5/QuickMCP) — Generate an MCP server from an OpenAPI or Discovery spec ☆`70`
- [hannesj/mcp-openapi-schema](https://github.com/hannesj/mcp-openapi-schema) — OpenAPI Schema Model Context Protocol Server ☆`50`
- [delimit-ai/delimit-mcp-server](https://github.com/delimit-ai/delimit-mcp-server) — Shared records and a signed gate on AI-written code ☆`23`
- [MonadWorks/agentify](https://github.com/MonadWorks/agentify) — Turn an OpenAPI spec into MCP servers, skills and agent docs ☆`42`
- [SonAIengine/graph-tool-call](https://github.com/SonAIengine/graph-tool-call) — Choose tools from a graph instead of loading them all ☆`18`
- [criteo/openapi-to-mcp](https://github.com/criteo/openapi-to-mcp) — An MCP server for your API ☆`35`
### Package Managers

- [rafsilva85/credit-optimizer-v5](https://github.com/rafsilva85/credit-optimizer-v5) — Cut Manus AI credit use, with a free MCP server ☆`53`
- [arvindand/maven-tools-mcp](https://github.com/arvindand/maven-tools-mcp) — Maven Central dependency intelligence for JVM build tools ☆`35`
- [Artmann/package-registry-mcp](https://github.com/Artmann/package-registry-mcp) — NPM, Cargo, PyPi, NuGet package search ☆`39`
- [VikrantSingh01/adaptive-cards-mcp](https://github.com/VikrantSingh01/adaptive-cards-mcp) — Generate and validate Adaptive Cards ☆`33`
- [Bigsy/maven-mcp-server](https://github.com/Bigsy/maven-mcp-server) — Maven build and dependency tools ☆`34`
- [jeannier/homebrew-mcp](https://github.com/jeannier/homebrew-mcp) — Homebrew package management ☆`30`
- [btwiuse/npm-search-mcp-server](https://github.com/btwiuse/npm-search-mcp-server) — MCP server for searching npm packages ☆`16`
- [subelsky/bundler_mcp](https://github.com/subelsky/bundler_mcp) — MCP server for Ruby Bundler integration ☆`21`
### Robotics & Automation

- [trycua/cua](https://github.com/trycua/cua) — MCP server for CUA platform ☆`32,156`
- [robotmcp/ros-mcp-server](https://github.com/robotmcp/ros-mcp-server) — ROS robot control with Claude and GPT ☆`1,519`
- [omni-mcp/isaac-sim-mcp](https://github.com/omni-mcp/isaac-sim-mcp) — Isaac Simulation MCP Extension and Server ☆`201`
- [wise-vision/ros2_mcp](https://github.com/wise-vision/ros2_mcp) — ROS 2 robotics AI bridge ☆`99`
- [abrinsmead/mindpilot-mcp](https://github.com/abrinsmead/mindpilot-mcp) — Visualize code and architect new systems ☆`90`
- [lpigeon/unitree-go2-mcp-server](https://github.com/lpigeon/unitree-go2-mcp-server) — MCP server for Unitree Go2 robot control ☆`88`
- [Yutarop/ros-mcp](https://github.com/Yutarop/ros-mcp) — MCP server for ROS to control robots via topics, services, and actions. ☆`36`
### Task Management

- [cjo4m06/mcp-shrimp-task-manager](https://github.com/cjo4m06/mcp-shrimp-task-manager) — Task manager with chain-of-thought and reflection ☆`2,150`
- [amxv/mcp-manager](https://github.com/amxv/mcp-manager) — Web UI to manage MCP servers in Claude ☆`296`
### Testing & QA

- [modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector) — Deterministic testing tools for MCP servers ☆`11,266`
- [MCPJam/inspector](https://github.com/MCPJam/inspector) — Chat with, inspect and debug MCP servers and apps ☆`2,307`
- [QAInsights/jmeter-mcp-server](https://github.com/QAInsights/jmeter-mcp-server) — JMeter AI workflow integration ☆`74`
- [debugg-ai/debugg-ai-mcp](https://github.com/debugg-ai/debugg-ai-mcp) — AI-managed end-to-end testing ☆`69`
- [SmartBear/smartbear-mcp](https://github.com/SmartBear/smartbear-mcp) — SmartBear's official MCP Server ☆`44`
- [hungthai1401/bruno-mcp](https://github.com/hungthai1401/bruno-mcp) — MCP Server for running Bruno Collections ☆`44`
- [mrexodia/user-feedback-mcp](https://github.com/mrexodia/user-feedback-mcp) — Human-in-the-loop workflow for Cursor ☆`54`
- [reportportal/reportportal-mcp-server](https://github.com/reportportal/reportportal-mcp-server) — MCP server for ReportPortal ☆`24`
- [currents-dev/currents-mcp](https://github.com/currents-dev/currents-mcp) — Currents MCP Server ☆`21`
- [QAInsights/k6-mcp-server](https://github.com/QAInsights/k6-mcp-server) — k6 MCP server ☆`26`
### Utilities

- [anaisbetts/mcp-installer](https://github.com/anaisbetts/mcp-installer) — An MCP server that installs other MCP servers for you ☆`1,537`
- [johnhuang316/code-index-mcp](https://github.com/johnhuang316/code-index-mcp) — Index a repo so a model can search it cheaply ☆`1,005`
- [jina-ai/MCP](https://github.com/jina-ai/MCP) — Official Jina AI Remote MCP Server ☆`906`
- [tidewave-ai/tidewave_phoenix](https://github.com/tidewave-ai/tidewave_phoenix) — Runtime tools for developing a Phoenix app ☆`859`
- [zinja-coder/jadx-mcp-server](https://github.com/zinja-coder/jadx-mcp-server) — MCP server for JADX-AI Plugin ☆`841`
- [vercel/next-devtools-mcp](https://github.com/vercel/next-devtools-mcp) — Next.js Development for Coding Agent ☆`835`
- [slowmist/MCP-Security-Checklist](https://github.com/slowmist/MCP-Security-Checklist) — Security checklist for tools built on MCP ☆`832`
- [Kentucky-ai/opentakeoff](https://github.com/Kentucky-ai/opentakeoff) — Measure rooms on a construction PDF for a quantity takeoff ☆`784`
- [tedeh/jayson](https://github.com/tedeh/jayson) — JSON-RPC 2.0 client and server for Node.js ☆`727`
- [daobataotie/CAD-MCP](https://github.com/daobataotie/CAD-MCP) — CAD MCP Server ☆`683`
- [puran-water/autocad-mcp](https://github.com/puran-water/autocad-mcp) — Draw in AutoCAD LT through AutoLISP, with undo ☆`643`
- [cloudflare/workers-mcp](https://github.com/cloudflare/workers-mcp) — Talk to a Cloudflare Worker from Claude Desktop! ☆`647`
- [Wasdubya/x64dbgMCP](https://github.com/Wasdubya/x64dbgMCP) — Model Context Protocol for x64dbg & x32dbg ☆`608`
- [spences10/mcp-sequentialthinking-tools](https://github.com/spences10/mcp-sequentialthinking-tools) — Suggest which MCP tool to use at each step ☆`588`
- [google/mcp-security](https://github.com/google/mcp-security) — Chronicle and Mandiant tools for detection and response ☆`538`
- [makafeli/n8n-workflow-builder](https://github.com/makafeli/n8n-workflow-builder) — Create and run n8n workflows in natural language ☆`549`
- [Miasyster/QuantGPT](https://github.com/Miasyster/QuantGPT) — Design, backtest and submit factors to WorldQuant BRAIN ☆`508`
- [tidewave-ai/tidewave_rails](https://github.com/tidewave-ai/tidewave_rails) — MCP server with runtime-level tools for Rails development ☆`475`
- [delorenj/mcp-server-trello](https://github.com/delorenj/mcp-server-trello) — Boards, lists and cards in Trello ☆`447`
- [cyanheads/atlas-mcp-server](https://github.com/cyanheads/atlas-mcp-server) — Projects, tasks and notes for agents, stored in Neo4j ☆`480`
- [dnakov/frida-mcp](https://github.com/dnakov/frida-mcp) — MCP stdio server for frida ☆`465`
- [dcSpark/shinkai-local-ai-agents](https://github.com/dcSpark/shinkai-local-ai-agents) — Desktop app for local agents, models and payments ☆`435`
- [TencentEdgeOne/edgeone-makers-mcp](https://github.com/TencentEdgeOne/edgeone-makers-mcp) — Publish HTML to EdgeOne Makers and get a public URL ☆`440`
- [cisco-open/network-sketcher](https://github.com/cisco-open/network-sketcher) — Design a network and export PowerPoint and Excel ☆`418`
- [adhikasp/mcp-reddit](https://github.com/adhikasp/mcp-reddit) — Fetch and analyze Reddit posts and comments ☆`437`
- [EnesCinr/twitter-mcp](https://github.com/EnesCinr/twitter-mcp) — Post and search on Twitter ☆`408`
- [ai-dashboad/flutter-skill](https://github.com/ai-dashboad/flutter-skill) — End-to-end tests for Flutter, native, web and desktop apps ☆`403`
- [joshrutkowski/applescript-mcp](https://github.com/joshrutkowski/applescript-mcp) — A macOS AppleScript MCP server ☆`396`
- [mcp2everything/mcp2mqtt](https://github.com/mcp2everything/mcp2mqtt) — Bridge from MCP to MQTT for smart home devices and hardware ☆`372`
- [microsoft/mcsmcp](https://github.com/microsoft/mcsmcp) — Lab for an MCP server used from Microsoft Copilot Studio ☆`340`
- [proxy-intell/facebook-ads-library-mcp](https://github.com/proxy-intell/facebook-ads-library-mcp) — Search the Facebook ads library ☆`326`
- [kleneway/awesome-cursor-mpc-server](https://github.com/kleneway/awesome-cursor-mpc-server) — Example MCP server with tools for Cursor ☆`338`
- [jkf87/hwp-mcp](https://github.com/jkf87/hwp-mcp) — mcp for handling hwp ☆`270`
- [zh19980811/Easy-MCP-AutoCad](https://github.com/zh19980811/Easy-MCP-AutoCad) — MCP server for creating and editing AutoCAD drawings ☆`272`
- [DMontgomery40/mcp-3D-printer-server](https://github.com/DMontgomery40/mcp-3D-printer-server) — Start and watch prints on common printer APIs ☆`262`
- [salacoste/mcp-n8n-workflow-builder](https://github.com/salacoste/mcp-n8n-workflow-builder) — Create and monitor n8n workflows from chat ☆`239`
- [MCP-Defender/MCP-Defender](https://github.com/MCP-Defender/MCP-Defender) — Desktop app that scans and blocks malicious MCP traffic ☆`255`
- [tolkonepiu/best-of-mcp-servers](https://github.com/tolkonepiu/best-of-mcp-servers) — A ranked list of MCP servers. Updated weekly. ☆`165`
- [aliargun/mcp-server-gemini](https://github.com/aliargun/mcp-server-gemini) — MCP server implementation for Google's Gemini API ☆`260`
- [peng-shawn/mermaid-mcp-server](https://github.com/peng-shawn/mermaid-mcp-server) — Render a Mermaid diagram to PNG ☆`234`
- [aipotheosis-labs/aci-mcp](https://github.com/aipotheosis-labs/aci-mcp) — MCP server(s) for Aipolabs ACI.dev ☆`254`
- [Azure-Samples/mcp-agent-langchainjs](https://github.com/Azure-Samples/mcp-agent-langchainjs) — Sample agent that orders burgers ☆`205`
- [code-rabi/interactive-brokers-mcp](https://github.com/code-rabi/interactive-brokers-mcp) — Interactive Brokers MCP Server ☆`228`
- [jhacksman/OpenSCAD-MCP-Server](https://github.com/jhacksman/OpenSCAD-MCP-Server) — Turn a prompt into an OpenSCAD preview and a 3D file ☆`215`
- [ConstantineB6/comfy-pilot](https://github.com/ConstantineB6/comfy-pilot) — See and edit ComfyUI graphs from Claude Code ☆`232`
- [quarkiverse/quarkus-mcp-server](https://github.com/quarkiverse/quarkus-mcp-server) — Quarkus extension for implementing an MCP server ☆`202`
- [microsoft/mcp-dotnet-samples](https://github.com/microsoft/mcp-dotnet-samples) — Samples of MCP servers and clients in .NET ☆`201`
- [bonninr/freecad_mcp](https://github.com/bonninr/freecad_mcp) — Drive FreeCAD: model, inspect and export from an assistant ☆`229`
- [minipuft/claude-prompts-mcp](https://github.com/minipuft/claude-prompts-mcp) — Reusable prompts, workflow chains and quality gates ☆`192`
- [invariantlabs-ai/mcp-injection-experiments](https://github.com/invariantlabs-ai/mcp-injection-experiments) — Snippets that reproduce MCP tool poisoning ☆`211`
- [mattt/Companion](https://github.com/mattt/Companion) — Your neighborhood friendly MCP utility for macOS, iOS, and visionOS ☆`189`
- [rectalogic/langchain-mcp](https://github.com/rectalogic/langchain-mcp) — Model Context Protocol tool support for LangChain ☆`205`
- [eniayomi/gcp-mcp](https://github.com/eniayomi/gcp-mcp) — Query a Google Cloud project in natural language ☆`199`
- [blackwell-systems/agent-lsp](https://github.com/blackwell-systems/agent-lsp) — Language servers packaged as tools for coding agents ☆`174`
- [sammcj/mcp-devtools](https://github.com/sammcj/mcp-devtools) — Common developer tools collected for coding agents ☆`164`
- [openfate-ai/openfate-mcp](https://github.com/openfate-ai/openfate-mcp) — Four Pillars calculation, true solar time and reverse lookup ☆`162`
- [BV-Venky/excalidraw-architect-mcp](https://github.com/BV-Venky/excalidraw-architect-mcp) — Architecture graph drawn as an Excalidraw diagram ☆`163`
- [githejie/mcp-server-calculator](https://github.com/githejie/mcp-server-calculator) — A Model Context Protocol server for calculating. ☆`160`
- [pzfreo/build123d-mcp](https://github.com/pzfreo/build123d-mcp) — Build 3D models with build123d ☆`146`
- [Azure-Samples/remote-mcp-functions-dotnet](https://github.com/Azure-Samples/remote-mcp-functions-dotnet) — Azure Functions template for a remote MCP ☆`134`
- [Flux159/mcp-chat](https://github.com/Flux159/mcp-chat) — Generic client for trying MCP servers and agents ☆`139`
- [stefanoamorelli/fred-mcp-server](https://github.com/stefanoamorelli/fred-mcp-server) — Economic series from FRED ☆`131`
- [Nyrok/flompt](https://github.com/Nyrok/flompt) — Edit a prompt as a flowchart, then compile it back ☆`155`
- [golioth/tinymcp](https://github.com/golioth/tinymcp) — Let LLMs control embedded devices via the Model Context Protocol. ☆`158`
- [readwiseio/readwise-mcp](https://github.com/readwiseio/readwise-mcp) — Readwise MCP ☆`152`
- [aviveldan/datagov-mcp](https://github.com/aviveldan/datagov-mcp) — MCP server for Israel Government Data ☆`146`
- [dhakalnirajan/blender-open-mcp](https://github.com/dhakalnirajan/blender-open-mcp) — MCP for Blender Using Open Weights Models ☆`123`
- [JordyZomer/codeql-mcp](https://github.com/JordyZomer/codeql-mcp) — Run CodeQL queries from an agent ☆`148`
- [baryhuang/mcp-hubspot](https://github.com/baryhuang/mcp-hubspot) — Read and update HubSpot CRM records ☆`129`
- [rcontesti/IB_MCP](https://github.com/rcontesti/IB_MCP) — Market data and orders through the Interactive Brokers API ☆`141`
- [makalin/SecureMCP](https://github.com/makalin/SecureMCP) — Audit MCP apps for vulnerabilities and bad configuration ☆`140`
- [jangtrinh/design-os-3d-blender](https://github.com/jangtrinh/design-os-3d-blender) — Blender workflow with a gate for 3D-print files ☆`113`
- [borgius/jobspy-mcp-server](https://github.com/borgius/jobspy-mcp-server) — Search jobs across several listing sites ☆`128`
- [mclenhard/mcp-evals](https://github.com/mclenhard/mcp-evals) — Score MCP tools with a model, including a GitHub Action ☆`134`
- [mertkayacs/reevesagents](https://github.com/mertkayacs/reevesagents) — Run many coding agents from MCP, a CLI or a web UI ☆`107`
- [yylo-dev/roundtable](https://github.com/yylo-dev/roundtable) — One interface that discovers Codex, Claude Code, Cursor and Gemini ☆`129`
- [LeulAria/Aria-Icons](https://github.com/LeulAria/Aria-Icons) — MCP server for 1M+ SVG icons ☆`106`
- [jlsookiki/secondhand-mcp](https://github.com/jlsookiki/secondhand-mcp) — Search Facebook Marketplace, eBay and Depop ☆`101`
- [MaxEllis/orcaslicer-mcp](https://github.com/MaxEllis/orcaslicer-mcp) — Load a model in OrcaSlicer, tune settings and slice it ☆`97`
- [portel-dev/photon](https://github.com/portel-dev/photon) — One TypeScript file becomes a CLI, an MCP server and a web UI ☆`100`
- [TonyWang-hub/mcp-cn-commerce](https://github.com/TonyWang-hub/mcp-cn-commerce) — MCP connectors for Chinese commerce platforms ☆`97`
- [mikeyny/ai-image-gen-mcp](https://github.com/mikeyny/ai-image-gen-mcp) — Generate images from text through Replicate ☆`121`
- [theronic/modex](https://github.com/theronic/modex) — Clojure library for MCP tools, resources and prompts ☆`121`
- [garagon/aguara](https://github.com/garagon/aguara) — The open source security engine for AI agent and supply-chain trust. ☆`94`
- [f/mcp-startup-boilerplate](https://github.com/f/mcp-startup-boilerplate) — Rails template for a paid MCP server, with Stripe and OAuth ☆`112`
- [embedded-society/altium-designer-mcp](https://github.com/embedded-society/altium-designer-mcp) — Manage Altium Designer component libraries ☆`91`
- [pfldy2850/py-mcp-naver](https://github.com/pfldy2850/py-mcp-naver) — python MCP NAVER ☆`115`
- [TocharianOU/mcp-server-kibana](https://github.com/TocharianOU/mcp-server-kibana) — Search and manage Kibana ☆`86`
- [LLMQuant/data-mcp](https://github.com/LLMQuant/data-mcp) — Finance datasets from LLMQuant Data ☆`88`
- [TermiX-official/bsc-mcp](https://github.com/TermiX-official/bsc-mcp) — Send BNB, move BEP-20 tokens and call contracts on BSC ☆`105`
- [NapthaAI/http-oauth-mcp-server](https://github.com/NapthaAI/http-oauth-mcp-server) — Remote MCP server with the OAuth extension ☆`110`
- [oculairmedia/Letta-MCP-server](https://github.com/oculairmedia/Letta-MCP-server) — Manage a Letta server and talk to its agents ☆`80`
- [escapeboy/agent-fleet-o](https://github.com/escapeboy/agent-fleet-o) — Self-hosted mission control for multi-agent workflows ☆`79`
- [TermiX-official/binance-mcp](https://github.com/TermiX-official/binance-mcp) — binance-mcp ☆`97`
- [ronantakizawa/a11ymcp](https://github.com/ronantakizawa/a11ymcp) — Test a page for web accessibility issues ☆`95`
- [smadi0x86/MDB-MCP](https://github.com/smadi0x86/MDB-MCP) — Debug a binary with GDB or LLDB ☆`74`
- [MarcelRoozekrans/roslyn-codelens-mcp](https://github.com/MarcelRoozekrans/roslyn-codelens-mcp) — Navigate, diagnose and refactor .NET code ☆`72`
- [shitianfang/jev-use](https://github.com/shitianfang/jev-use) — Hand steps that need no prose to a small judgment model ☆`69`
- [stefanoamorelli/nasdaq-data-link-mcp](https://github.com/stefanoamorelli/nasdaq-data-link-mcp) — Datasets from Nasdaq Data Link ☆`68`
- [contentful/contentful-mcp-server](https://github.com/contentful/contentful-mcp-server) — Manage Contentful entries through the Management API ☆`62`
- [ruvnet/federated-mcp](https://github.com/ruvnet/federated-mcp) — Read public RuFlo federation channels, labeled as untrusted ☆`65`
- [jsdelivr/globalping-mcp-server](https://github.com/jsdelivr/globalping-mcp-server) — Remote network commands for LLMs ☆`66`
- [lethain/library-mcp](https://github.com/lethain/library-mcp) — MCP server for operating on Markdown knowledge bases ☆`91`
- [Mearman/mcp-wayback-machine](https://github.com/Mearman/mcp-wayback-machine) — Look up pages in the Internet Archive Wayback Machine ☆`65`
- [ilyautov/marketplaces-mcp-ru](https://github.com/ilyautov/marketplaces-mcp-ru) — Wildberries, Ozon, Yandex Market and Avito seller data ☆`61`
- [Pantani/tdmcp](https://github.com/Pantani/tdmcp) — Build a playable TouchDesigner network from a description ☆`62`
- [PSPDFKit/nutrient-document-engine-mcp-server](https://github.com/PSPDFKit/nutrient-document-engine-mcp-server) — Process documents in natural language ☆`62`
- [DeDeveloper23/codebase-mcp](https://github.com/DeDeveloper23/codebase-mcp) — Pack a repository with RepoMix so a model can read it ☆`85`
- [kranz-org/kranz](https://github.com/kranz-org/kranz) — Keyboard-first local service orchestrator with a focused terminal UI ☆`62`
- [linux-china/mcp-rs-template](https://github.com/linux-china/mcp-rs-template) — Model Context Protocol (MCP) CLI server template for Rust ☆`82`
- [HaseebKhalid1507/SynapsCLI](https://github.com/HaseebKhalid1507/SynapsCLI) — Rust terminal agent with parallel workers and supervision ☆`57`
- [brentmid/evernote-mcp-server](https://github.com/brentmid/evernote-mcp-server) — Search and read notes in Evernote ☆`56`
- [xianyu-sheng/Xenon](https://github.com/xianyu-sheng/Xenon) — Verifiable AI coding agent harness with an evidence hash-chain ☆`56`
- [JoxoAI/joxo](https://github.com/JoxoAI/joxo) — Shared project and task board for coding agents, on desktop and iPhone ☆`57`
- [LadislavSopko/mcp-ai-server-visual-studio](https://github.com/LadislavSopko/mcp-ai-server-visual-studio) — Roslyn tools inside Visual Studio ☆`56`
- [gabrielekarra/mcp-anything](https://github.com/gabrielekarra/mcp-anything) — One command to turn any codebase into an MCP server ☆`56`
- [MorDavid/ExternalAttacker-MCP](https://github.com/MorDavid/ExternalAttacker-MCP) — Map an external attack surface for recon and bug bounty ☆`78`
- [raw-labs/mxcp](https://github.com/raw-labs/mxcp) — Enterprise path from data sources to tools a model can call ☆`68`
- [priyankark/a11y-mcp](https://github.com/priyankark/a11y-mcp) — Accessibility audits of a page with axe-core ☆`53`
- [attalla1/photopea-mcp-server](https://github.com/attalla1/photopea-mcp-server) — MCP server for AI-driven image editing with Photopea ☆`51`
- [ThingsPanel/thingspanel-mcp](https://github.com/ThingsPanel/thingspanel-mcp) — Devices and data on the ThingsPanel IoT platform ☆`48`
- [maton-ai/agent-toolkit](https://github.com/maton-ai/agent-toolkit) — Connect SaaS tools such as HubSpot and Salesforce ☆`50`
- [MarcusJellinghaus/mcp-workspace](https://github.com/MarcusJellinghaus/mcp-workspace) — Files, git and GitHub inside a project sandbox ☆`49`
- [RyanCardin15/AzureDevOps-MCP](https://github.com/RyanCardin15/AzureDevOps-MCP) — Work items, repos and boards in Azure DevOps ☆`60`
- [CSCSoftware/AiDex](https://github.com/CSCSoftware/AiDex) — Persistent index so an assistant can jump around a codebase ☆`48`
- [adenot/mcp-google-search](https://github.com/adenot/mcp-google-search) — Google results through the Custom Search API ☆`71`
- [CheckPointSW/mcp-servers](https://github.com/CheckPointSW/mcp-servers) — AI-accessible Check Point firewall and threat management. ☆`46`
- [dejuknow/md-redline](https://github.com/dejuknow/md-redline) — Inline review comments on markdown specs, handed to the agent ☆`48`
- [NON906/omniparser-autogui-mcp](https://github.com/NON906/omniparser-autogui-mcp) — Automatic operation of on-screen GUI. ☆`72`
- [rootlyhq/rootly-mcp-server](https://github.com/rootlyhq/rootly-mcp-server) — Rootly MCP server ☆`45`
- [pzalutski-pixel/javalens-mcp](https://github.com/pzalutski-pixel/javalens-mcp) — Navigate, search and refactor Java through Eclipse JDT ☆`47`
- [flamexnreal/davinci-resolve-ai-bridge-mcp](https://github.com/flamexnreal/davinci-resolve-ai-bridge-mcp) — Cut and grade a DaVinci Resolve timeline ☆`48`
- [anzy-renlab-ai/pronounce](https://github.com/anzy-renlab-ai/pronounce) — Hear how developers pronounce kubectl, nginx and other terms ☆`48`
- [Cifero74/mcp-apple-music](https://github.com/Cifero74/mcp-apple-music) — Search Apple Music and manage the library and playlists ☆`46`
- [datadog-labs/mcp-server](https://github.com/datadog-labs/mcp-server) — Official Datadog MCP Server ☆`47`
- [cnitlrt/headless-ida-mcp-server](https://github.com/cnitlrt/headless-ida-mcp-server) — headless-ida-mcp-server ☆`45`
- [MikeRecognex/mcp-codebase-index](https://github.com/MikeRecognex/mcp-codebase-index) — Functions, imports and change impact ☆`63`
- [withastro/docs-mcp](https://github.com/withastro/docs-mcp) — Astro Docs MCP Server ☆`68`
- [hetaoBackend/mcp-github-trending](https://github.com/hetaoBackend/mcp-github-trending) — GitHub trending repositories and developers ☆`62`
- [pzalutski-pixel/sharplens-mcp](https://github.com/pzalutski-pixel/sharplens-mcp) — Semantic analysis and refactoring of C# through Roslyn ☆`42`
- [Decodo/mcp-server](https://github.com/Decodo/mcp-server) — Scrape sites, search and shops into structured results ☆`40`
- [Text2Go/ai-humanizer-mcp-server](https://github.com/Text2Go/ai-humanizer-mcp-server) — Rewrite AI-sounding text so it reads more naturally ☆`64`
- [heltonteixeira/openrouterai](https://github.com/heltonteixeira/openrouterai) — MCP server for OpenRouter.ai integration ☆`64`
- [Mtehabsim/ScreenPilot](https://github.com/Mtehabsim/ScreenPilot) — AI device control like a human ☆`55`
- [pylegifrance/mcp-server-legifrance](https://github.com/pylegifrance/mcp-server-legifrance) — Legifrance MCP Server ☆`65`
- [daobataotie/mssql-mcp](https://github.com/daobataotie/mssql-mcp) — mssql mcp server ☆`39`
- [verygoodplugins/mcp-toggl](https://github.com/verygoodplugins/mcp-toggl) — Time entries and reports in Toggl Track ☆`36`
- [decriptor/DilettoLabs.AvaloniaUI.MCP](https://github.com/decriptor/DilettoLabs.AvaloniaUI.MCP) — MCP server for AvaloniaUI ☆`39`
- [demcp/demcp-defillama-mcp](https://github.com/demcp/demcp-defillama-mcp) — DeFi protocol data from DefiLlama ☆`63`
- [circuit-synth/kicad-sch-api](https://github.com/circuit-synth/kicad-sch-api) — API for manipulating sexpr in KiCAD schematic editor ☆`57`
- [alxspiker/mcp-server-ftp](https://github.com/alxspiker/mcp-server-ftp) — Model Context Protocol server for FTP access ☆`37`
- [bharathvaj-ganesan/whois-mcp](https://github.com/bharathvaj-ganesan/whois-mcp) — MCP Server for whois lookups. ☆`60`
- [xiaotonng/lc2mcp](https://github.com/xiaotonng/lc2mcp) — Convert LangChain tools to FastMCP tools ☆`55`
- [telmon95/VulneraMCP](https://github.com/telmon95/VulneraMCP) — Security testing and vulnerability research for bug bounty ☆`51`
- [kirich1409/maven-mcp](https://github.com/kirich1409/maven-mcp) — Look up Maven dependencies and how they are used ☆`37`
- [swgee/BurpMCP](https://github.com/swgee/BurpMCP) — Burp Suite extension that exposes the proxy to an assistant ☆`57`
- [dynatrace-oss/dynatrace-managed-mcp](https://github.com/dynatrace-oss/dynatrace-managed-mcp) — Query a self-hosted Dynatrace Managed instance ☆`34`
- [zazencodes/random-number-mcp](https://github.com/zazencodes/random-number-mcp) — MCP server for random number generation ☆`50`
- [metavert-io/lightcms](https://github.com/metavert-io/lightcms) — Self-hosted CMS with an admin UI, REST, MCP and semantic search ☆`34`
- [daipendency/daipendency-mcp](https://github.com/daipendency/daipendency-mcp) — Model Context Protocol server for Daipendency ☆`58`
- [librejustice/librejustice](https://github.com/librejustice/librejustice) — Search French and European case law and statutes ☆`34`
- [muppet-dev/kit](https://github.com/muppet-dev/kit) — Debugging and Testing tool for MCP servers ☆`58`
- [ZeparHyfar/mcp-datetime](https://github.com/ZeparHyfar/mcp-datetime) — A MCP server for datetime formatting and file name generation. ☆`31`
- [feiyun0112/spec-coding-mcp](https://github.com/feiyun0112/spec-coding-mcp) — Spec-driven workflow that turns feature ideas ☆`50`
- [zhaoyouj/mcp-slicer](https://github.com/zhaoyouj/mcp-slicer) — A Model Context Protocol server for 3D Slicer integration ☆`46`
- [Azure-Samples/mcp-auth-servers](https://github.com/Azure-Samples/mcp-auth-servers) — Reference servers showing how MCP authentication works ☆`50`
- [XenoXilus/outlook-mcp](https://github.com/XenoXilus/outlook-mcp) — Outlook mail, calendar and SharePoint through Microsoft Graph ☆`30`
- [wretcher207/reaper-daemon](https://github.com/wretcher207/reaper-daemon) — Drive REAPER: plugins, automation and measurements ☆`31`
- [Whq02/MercuryCLI](https://github.com/Whq02/MercuryCLI) — Several coding sessions in one terminal, mixing providers ☆`30`
- [zxzinn/opencti-mcp](https://github.com/zxzinn/opencti-mcp) — Indicators, reports and threat actors in OpenCTI ☆`42`
- [newtype-01/prompthouse-mcp](https://github.com/newtype-01/prompthouse-mcp) — Personal prompt library manager ☆`53`
- [henilcalagiya/mcp-apple-notes](https://github.com/henilcalagiya/mcp-apple-notes) — Read and write Apple Notes on this Mac ☆`53`
- [portone-io/mcp-server](https://github.com/portone-io/mcp-server) — PortOne MCP Server for Developers ☆`29`
- [HarshJ23/deepseek-claude-MCP-server](https://github.com/HarshJ23/deepseek-claude-MCP-server) — DeepSeek R1 reasoning inside Claude Desktop ☆`50`
- [StefH/McpDotNet.Extensions.SemanticKernel](https://github.com/StefH/McpDotNet.Extensions.SemanticKernel) — Use MCP tools as Semantic Kernel functions ☆`40`
- [taiste/harvest-mcp-server](https://github.com/taiste/harvest-mcp-server) — MCP Server for Harvest ☆`37`
- [mcp-agents-ai/mcp-agents-hub](https://github.com/mcp-agents-ai/mcp-agents-hub) — Find, build and deploy MCP servers and clients ☆`44`
- [mcp2everything/mcp2serial](https://github.com/mcp2everything/mcp2serial) — Control hardware such as a Raspberry Pi Pico over serial ☆`50`
- [hjbaard/SolidWorks-MCP](https://github.com/hjbaard/SolidWorks-MCP) — Build and measure parts in a running SolidWorks session ☆`26`
- [shieldyguy/stm32-mcp](https://github.com/shieldyguy/stm32-mcp) — build, flash, debug stm32 projects ☆`26`
- [FelixFoster/mcp-enhance-prompt](https://github.com/FelixFoster/mcp-enhance-prompt) — AI-powered prompt enhancement and generation ☆`24`
- [fireostendere/mcp_diptrace](https://github.com/fireostendere/mcp_diptrace) — MCP server and live XML bridge for DipTrace ☆`26`
- [fastn-ai/fastn-mcp](https://github.com/fastn-ai/fastn-mcp) — Governed, audited access to customer systems of record ☆`23`
- [panbanda/omen](https://github.com/panbanda/omen) — Complexity, hotspots and blast radius for a codebase ☆`22`
- [bmorphism/anti-bullshit-mcp-server](https://github.com/bmorphism/anti-bullshit-mcp-server) — Check claims, sources and signs of manipulation ☆`23`
- [Ming-jiayou/mcp_demo](https://github.com/Ming-jiayou/mcp_demo) — A simple example of building an MCP client using C#. ☆`47`
- [abhiphile/fermat-mcp](https://github.com/abhiphile/fermat-mcp) — SymPy, NumPy, and Matplotlib in one math engine ☆`22`
- [huanglizhuo/OctoCounts](https://github.com/huanglizhuo/OctoCounts) — Count lines of code in a public GitHub repo without cloning it ☆`22`
- [maple-kit/maple](https://github.com/maple-kit/maple) — Visual review comments on a preview, with a CI merge gate ☆`22`
- [keplertech/naja-scope](https://github.com/keplertech/naja-scope) — Trace connectivity and hierarchy in SystemVerilog and VHDL ☆`22`
- [ourongxing/newsnow-mcp-server](https://github.com/ourongxing/newsnow-mcp-server) — Official MCP Server for newnow, 40+ sources available. ☆`34`
- [addozhang/spring-rest-to-mcp](https://github.com/addozhang/spring-rest-to-mcp) — Convert Spring REST API to MCP Server with OpenRewrite ☆`39`
- [axonixtools/PocketMCP](https://github.com/axonixtools/PocketMCP) — Expose an Android phone as an MCP server on the local network ☆`20`
- [nsxdavid/clickup-mcp-server](https://github.com/nsxdavid/clickup-mcp-server) — ClickUp tasks, docs and checklists from the conversation ☆`43`
- [ZedMoster/revit-mcp](https://github.com/ZedMoster/revit-mcp) — revit-mcp ☆`38`
- [patchloom/patchloom](https://github.com/patchloom/patchloom) — Structured edits for JSON, YAML, markdown and code, with a dry run ☆`20`
- [SecretiveShell/MCP-timeserver](https://github.com/SecretiveShell/MCP-timeserver) — Datetime info for agentic systems ☆`42`
- [jonemo/openpyxl-mcp-server](https://github.com/jonemo/openpyxl-mcp-server) — Read and write Excel workbooks through openpyxl ☆`19`
- [jmtanguy/droit-francais-mcp](https://github.com/jmtanguy/droit-francais-mcp) — French statutes and case law from Legifrance ☆`37`
- [Azure-Samples/remote-mcp-webapp-dotnet](https://github.com/Azure-Samples/remote-mcp-webapp-dotnet) — .NET MCP server for Azure App Service ☆`40`
- [tokenizin-agency/mcp-npx-fetch](https://github.com/tokenizin-agency/mcp-npx-fetch) — Fetch a page as HTML, JSON, markdown or plain text ☆`42`
- [angrysky56/ast-mcp-server](https://github.com/angrysky56/ast-mcp-server) — Query a semantic graph and AST of a codebase ☆`37`
- [Cyreslab-AI/crunchbase-mcp-server](https://github.com/Cyreslab-AI/crunchbase-mcp-server) — Companies, funding and investors from Crunchbase ☆`17`
- [stefanoamorelli/companies-house-mcp](https://github.com/stefanoamorelli/companies-house-mcp) — UK companies, officers and filings ☆`31`
- [Buga-luga/cursor-mcp](https://github.com/Buga-luga/cursor-mcp) — Bridge Claude to desktop apps through Cursor ☆`39`
- [arikusi/nakkas](https://github.com/arikusi/nakkas) — MCP server that turns AI into an SVG artist ☆`31`
- [bingal/FastDomainCheck-MCP-Server](https://github.com/bingal/FastDomainCheck-MCP-Server) — Check whether many domain names are registered ☆`40`
- [qualixar/slm-mesh](https://github.com/qualixar/slm-mesh) — Peer-to-peer messaging between coding agents ☆`16`
- [shadowfax92/apple-reminders-mcp](https://github.com/shadowfax92/apple-reminders-mcp) — Create, complete and delete Apple Reminders ☆`39`
- [skulitom/Nestbolt](https://github.com/skulitom/Nestbolt) — Free, open-source 2D nesting for fixed sheets: laser, CNC, plasma, waterjet and fabric. SVG/DXF in and out, part-in-part, several sheets. Runs in your browser (nothing uploaded), ☆`16`
- [andybrandt/mcp-simple-timeserver](https://github.com/andybrandt/mcp-simple-timeserver) — Current time check for Claude via MCP ☆`33`
- [Braffolk/mcp-summarization-functions](https://github.com/Braffolk/mcp-summarization-functions) — Shorten tool output so agents spend fewer tokens ☆`37`
- [mytechnotalent/MalwareBazaar_MCP](https://github.com/mytechnotalent/MalwareBazaar_MCP) — Threat intel and sample metadata from MalwareBazaar ☆`32`
- [54yyyu/code-mcp](https://github.com/54yyyu/code-mcp) — Connect Claude to a local terminal and files through MCP ☆`38`
- [CartographAI/atlas-docs-mcp](https://github.com/CartographAI/atlas-docs-mcp) — Clean markdown docs for libraries and frameworks ☆`36`
- [rsdouglas/janee](https://github.com/rsdouglas/janee) — Secrets management for AI agents via MCP • @janeesecure ☆`30`
- [stefanoamorelli/hyprmcp](https://github.com/stefanoamorelli/hyprmcp) — Community MCP server for hyprctl ☆`35`
- [stefanskiasan/azure-devops-mcp-server](https://github.com/stefanskiasan/azure-devops-mcp-server) — MCP Server for Cline to Access Azure devops ☆`33`
- [isaacwasserman/mcp-langchain-ts-client](https://github.com/isaacwasserman/mcp-langchain-ts-client) — LangChain.js client for Model Context Protocol. ☆`35`
- [mlobo2012/Claude_Desktop_API_USE_VIA_MCP](https://github.com/mlobo2012/Claude_Desktop_API_USE_VIA_MCP) — Call the Claude API from Claude Desktop ☆`34`
- [oakenai/mcp-edit-file-lines](https://github.com/oakenai/mcp-edit-file-lines) — MCP Server to make line-based edits to a file. ☆`34`
- [cyanheads/mentor-mcp-server](https://github.com/cyanheads/mentor-mcp-server) — Second-opinion review from a DeepSeek reasoning model ☆`32`
- [NikiforovAll/mcp-template-dotnet](https://github.com/NikiforovAll/mcp-template-dotnet) — Template for an MCP application in .NET ☆`25`
- [abhishekbhakat/airflow-mcp-server](https://github.com/abhishekbhakat/airflow-mcp-server) — MCP Server for Apache Airflow ☆`33`
- [superfly/flymcp](https://github.com/superfly/flymcp) — MCP server for Fly.io CLI integration with Claude Desktop ☆`34`
- [ap425q/CutterMCP](https://github.com/ap425q/CutterMCP) — MCP Server for Cutter ☆`34`
- [amgadabdelhafez/dbx-mcp-server](https://github.com/amgadabdelhafez/dbx-mcp-server) — MCP Server for Dropbox ☆`30`
- [CharlieDigital/runjs](https://github.com/CharlieDigital/runjs) — Let a model write JavaScript and run it, including HTTP calls ☆`32`
- [nguyenvanduocit/dev-kit](https://github.com/nguyenvanduocit/dev-kit) — Everyday developer tools behind one MCP server ☆`33`
- [willibrandon/NetContextServer](https://github.com/willibrandon/NetContextServer) — Explore a .NET codebase ☆`32`
- [tooluse-labs/perfetto-mcp-rs](https://github.com/tooluse-labs/perfetto-mcp-rs) — Perfetto traces, including Chrome jank ☆`22`
- [ofek/pycli-mcp](https://github.com/ofek/pycli-mcp) — MCP server for any Python command line application ☆`22`
- [PCDCK/ozon-mcp](https://github.com/PCDCK/ozon-mcp) — Seller and ads APIs for an Ozon shop ☆`25`
- [TheoBrigitte/mcp-time](https://github.com/TheoBrigitte/mcp-time) — Dates and times with natural language and timezones ☆`25`
- [Nazruden/clickup-mcp-server](https://github.com/Nazruden/clickup-mcp-server) — Tasks and workspaces in ClickUp ☆`23`
- [jenstangen1/pptx-xlsx-mcp](https://github.com/jenstangen1/pptx-xlsx-mcp) — Antrophics Model context protocol to edit powerpoint files ☆`30`
- [janwilmake/install-this-mcp](https://github.com/janwilmake/install-this-mcp) — Reduce installation-friction for your MCP servers ☆`25`
- [izzzzzi/codewiki-mcp](https://github.com/izzzzzi/codewiki-mcp) — Search and ask questions against codewiki.google ☆`19`
- [ADEOSec/mcp-shodan](https://github.com/ADEOSec/mcp-shodan) — Query Shodan for host and search reconnaissance ☆`26`
- [stakpak/mcp](https://github.com/stakpak/mcp) — Lightweight MCP server to give you access to the Stakpak API. ☆`18`
- [ameeralns/DeepResearchMCP](https://github.com/ameeralns/DeepResearchMCP) — Multi-step research assistant over MCP ☆`27`
- [TexasFortress-AI/rs_filesystem](https://github.com/TexasFortress-AI/rs_filesystem) — MCP Filesystem tools written in Rust ☆`22`
- [syedazharmbnr1/ClaudeMCPServer](https://github.com/syedazharmbnr1/ClaudeMCPServer) — MCP Server implementation for Claude ☆`27`
- [stefanoamorelli/codemagic-mcp](https://github.com/stefanoamorelli/codemagic-mcp) — Codemagic CI/CD MCP Server ☆`16`
- [mcpware/ui-annotator-mcp](https://github.com/mcpware/ui-annotator-mcp) — Hover labels on any web page, with no browser extension ☆`21`
- [openSVM/dexscreener-mcp-server](https://github.com/openSVM/dexscreener-mcp-server) — DEX pairs, tokens and markets from DexScreener ☆`24`
- [7gugu/zip-mcp](https://github.com/7gugu/zip-mcp) — Compress and decompress local files ☆`16`
- [davidvc/code-knowledge-mcptool](https://github.com/davidvc/code-knowledge-mcptool) — MCP tool that lets Cline inquire about a code base ☆`24`
- [hanweg/mcp-tool-builder](https://github.com/hanweg/mcp-tool-builder) — MCP server that creates its own tools as needed ☆`25`
- [austenstone/myinstants-mcp](https://github.com/austenstone/myinstants-mcp) — Play sound buttons from MyInstants ☆`20`
- [philipp-eisen/modal-mcp-toolbox](https://github.com/philipp-eisen/modal-mcp-toolbox) — A collection of tools for your LLMs that run on Modal ☆`25`
- [SJTU-Geek/sjtu-mcp-server](https://github.com/SJTU-Geek/sjtu-mcp-server) — Campus services MCP for schedules, library bookings ☆`20`
- [MAG-Cie/mcp-microsoft-todo](https://github.com/MAG-Cie/mcp-microsoft-todo) — Lists and tasks in Microsoft To Do ☆`20`
- [abhishekjairath/sonic-pi-mcp](https://github.com/abhishekjairath/sonic-pi-mcp) — Control Sonic Pi from an assistant ☆`19`
- [lobehub/mcp-hello-world](https://github.com/lobehub/mcp-hello-world) — A simple Hello World MCP server for CI/CD test ☆`22`
- [ajtazer/ZAP-MCP](https://github.com/ajtazer/ZAP-MCP) — VIBE CODING lol ☆`23`
- [CartographAI/mcp-server-codegraph](https://github.com/CartographAI/mcp-server-codegraph) — MCP server for graph representation of a codebase ☆`22`
- [mrwadams/otx-mcp](https://github.com/mrwadams/otx-mcp) — Interface to OTX feeds and threat intel. ☆`22`
- [ykhli/mcp-light-control](https://github.com/ykhli/mcp-light-control) — Philips Hue lights, including Morse code ☆`22`
- [yy1588133/code-merge-mcp](https://github.com/yy1588133/code-merge-mcp) — Extract, merge and analyze code files for a model ☆`21`
- [amornpan/py-mcp-line](https://github.com/amornpan/py-mcp-line) — python mcp LINE ☆`20`
- [acashmoney/bio-mcp](https://github.com/acashmoney/bio-mcp) — BioMCP: Enabling agent-based biomedical R&D ☆`20`
- [cmpxchg16/mcp-ethical-hacking](https://github.com/cmpxchg16/mcp-ethical-hacking) — MCP Ethical Hacking Security sample for educational ☆`20`
- [asmith26/jupytercad-mcp](https://github.com/asmith26/jupytercad-mcp) — Control JupyterCAD in natural language ☆`20`
- [ODAncona/code2prompt-mcp](https://github.com/ODAncona/code2prompt-mcp) — Turn a codebase into a structured summary for a model ☆`19`
- [rohans2/mcp-google-sheets](https://github.com/rohans2/mcp-google-sheets) — Read and edit Google Sheets ☆`18`
- [ricauts/CyberMCP](https://github.com/ricauts/CyberMCP) — Security tests against backend APIs ☆`16`
- [ggerve/coding-standards-mcp](https://github.com/ggerve/coding-standards-mcp) — Coding guidelines and practices a model can look up ☆`17`
- [torshepherd/compiler-explorer-mcp](https://github.com/torshepherd/compiler-explorer-mcp) — Compile on Compiler Explorer and compare assembly ☆`16`
### Version Control

- [github/github-mcp-server](https://github.com/github/github-mcp-server) — GitHub's official MCP Server ☆`34,378`
- [idosal/git-mcp](https://github.com/idosal/git-mcp) — Free remote MCP for any GitHub project ☆`8,512`
- [repowise-dev/repowise](https://github.com/repowise-dev/repowise) — Code health, generated docs, dead code and git analytics ☆`8,101`
- [gitkraken/gk-cli](https://github.com/gitkraken/gk-cli) — GitKraken CLI Releases and Documentation ☆`465`
- [Tiberriver256/mcp-server-azure-devops](https://github.com/Tiberriver256/mcp-server-azure-devops) — An MCP server for Azure DevOps ☆`399`
- [adhikasp/mcp-git-ingest](https://github.com/adhikasp/mcp-git-ingest) — GitHub repository content reading ☆`315`
- [cyanheads/git-mcp-server](https://github.com/cyanheads/git-mcp-server) — Clone, commit, branch, merge and stash in local git repos ☆`245`
- [puravparab/Gitingest-MCP](https://github.com/puravparab/Gitingest-MCP) — mcp server for gitingest ☆`138`
- [kopfrechner/gitlab-mr-mcp](https://github.com/kopfrechner/gitlab-mr-mcp) — MCP server for GitLab merge requests and issues ☆`94`
- [PhpCodeArcheology/PhpCodeArcheology](https://github.com/PhpCodeArcheology/PhpCodeArcheology) — PHP metrics, dependency graphs and git hotspots ☆`92`
- [sverklo/sverklo](https://github.com/sverklo/sverklo) — Symbol graph, blast radius and review notes for a repository ☆`82`
- [oschina/mcp-gitee](https://github.com/oschina/mcp-gitee) — MCP server for Gitee repositories ☆`65`
- [srclight/srclight](https://github.com/srclight/srclight) — Hybrid code search, call graphs and git hotspots ☆`59`
- [KongFangXun/sofagent](https://github.com/KongFangXun/sofagent) — Write business rules into files, then audit what the agent did ☆`55`
- [jmrplens/gitlab-mcp-server](https://github.com/jmrplens/gitlab-mcp-server) — Find and run GitLab actions, with a read-only mode ☆`47`
- [raohwork/forgejo-mcp](https://github.com/raohwork/forgejo-mcp) — Manage Gitea and Forgejo repositories ☆`70`
- [Ryan0204/github-repo-mcp](https://github.com/Ryan0204/github-repo-mcp) — GitHub repository reading ☆`33`
- [cq27-dev/rag-rat](https://github.com/cq27-dev/rag-rat) — Semantic search, symbols and impact across a local repo ☆`27`
- [sgroy10/speclock](https://github.com/sgroy10/speclock) — Guardrails on coding-agent actions, in Claude Code, MCP and CI ☆`26`
- [MykytaStel/repopilot](https://github.com/MykytaStel/repopilot) — Review a git diff for weakened tests, security and blast radius ☆`24`
- [xxczaki/local-history-mcp](https://github.com/xxczaki/local-history-mcp) — MCP server for accessing VS Code/Cursor's Local History ☆`16`
- [geropl/git-mcp-go](https://github.com/geropl/git-mcp-go) — Git MCP based on mcp-go ☆`37`
- [ddukbg/github-enterprise-mcp](https://github.com/ddukbg/github-enterprise-mcp) — github-enterprise-mcp ☆`29`
- [kurdin/github-repos-manager-mcp](https://github.com/kurdin/github-repos-manager-mcp) — GitHub Repos Manager MCP Server for MCP clients ☆`22`
## Embedded & IoT

- [stack-chan/stack-chan](https://github.com/stack-chan/stack-chan) — A JavaScript-driven M5Stack-embedded super-kawaii robot. ☆`1,863`
- [tevonsb/homeassistant-mcp](https://github.com/tevonsb/homeassistant-mcp) — A MCP server for Home Assistant ☆`574`
- [lamaalrajih/kicad-mcp](https://github.com/lamaalrajih/kicad-mcp) — KiCad integration for Mac, Windows, Linux ☆`534`
- [Extelligence-ai/bagel](https://github.com/Extelligence-ai/bagel) — Chat with robotics, drone, IoT data ☆`405`
- [voska/hass-mcp](https://github.com/voska/hass-mcp) — Home Assistant control and queries from LLMs ☆`352`
- [wiresage/mikrotik-mcp](https://github.com/wiresage/mikrotik-mcp) — MCP server for Mikrotik ☆`332`
- [recursechat/mcp-server-apple-shortcuts](https://github.com/recursechat/mcp-server-apple-shortcuts) — Apple Shortcuts automation on macOS ☆`355`
- [hao-cyber/phone-mcp](https://github.com/hao-cyber/phone-mcp) — Control Android phone via ADB ☆`250`
- [codeofaxel/Kiln](https://github.com/codeofaxel/Kiln) — 3D-printing workflow an agent can drive ☆`243`
- [FradSer/mcp-server-apple-events](https://github.com/FradSer/mcp-server-apple-events) — Native integration with Apple Reminders and Calendar ☆`233`
- [coffeenmusic/altium-mcp](https://github.com/coffeenmusic/altium-mcp) — Altium Model Context Protocol server and Altium API script ☆`219`
- [Adancurusul/embedded-debugger-mcp](https://github.com/Adancurusul/embedded-debugger-mcp) — Debug ARM, RISC-V and ESP32 via probe-rs or OpenOCD ☆`217`
- [horw/esp-mcp](https://github.com/horw/esp-mcp) — ESP32 commands and getting started ☆`158`
- [johannesPettersson80/codesys-mcp-toolkit](https://github.com/johannesPettersson80/codesys-mcp-toolkit) — CODESYS industrial automation platform ☆`131`
- [LGDiMaggio/predictive-maintenance-mcp](https://github.com/LGDiMaggio/predictive-maintenance-mcp) — Predictive maintenance and fault diagnosis ☆`114`
- [Adancurusul/serial-mcp-server](https://github.com/Adancurusul/serial-mcp-server) — Talk to serial and UART devices with timed JSON macros ☆`97`
- [thingsboard/thingsboard-mcp](https://github.com/thingsboard/thingsboard-mcp) — MCP server for ThingsBoard IoT platform interaction ☆`99`
- [handsomejustin/mijia-control](https://github.com/handsomejustin/mijia-control) — Bridge between Xiaomi Mijia devices, MCP and HomeKit ☆`80`
- [Hybirdss/smartest-tv](https://github.com/Hybirdss/smartest-tv) — Control LG, Samsung, Roku and Android TVs ☆`59`
- [yoelbassin/gr-mcp](https://github.com/yoelbassin/gr-mcp) — MCP server for GNU Radio ☆`57`
- [vishalmysore/choturobo](https://github.com/vishalmysore/choturobo) — Arduino robotics with AI integration ☆`79`
- [aqara/aqara-mcp-server](https://github.com/aqara/aqara-mcp-server) — Aqara's official MCP Server ☆`50`
- [jango-blockchained/advanced-homeassistant-mcp](https://github.com/jango-blockchained/advanced-homeassistant-mcp) — Control Home Assistant devices ☆`58`
- [chrisgleissner/c64bridge](https://github.com/chrisgleissner/c64bridge) — Commodore 64 Ultimate, Ultimate II, and VICE control ☆`41`
- [alexpfau/zigbee2mqtt-mcp](https://github.com/alexpfau/zigbee2mqtt-mcp) — Health, OTA, pairing and bindings for a Zigbee2MQTT network ☆`36`
- [NickoScope/nickol-knx-mcp](https://github.com/NickoScope/nickol-knx-mcp) — Validate and repair a KNX project in ETS ☆`30`
- [hekmon8/Homeassistant-server-mcp](https://github.com/hekmon8/Homeassistant-server-mcp) — Control and monitor Home Assistant devices ☆`48`
- [kambriso/fritzbox-mcp-server](https://github.com/kambriso/fritzbox-mcp-server) — Control a FRITZ!Box from an assistant ☆`26`
- [yiwenlu66/PiloTY](https://github.com/yiwenlu66/PiloTY) — AI pilot for PTY operations - control terminals via MCP ☆`45`
- [nokia-steward/mcp-redfish](https://github.com/nokia-steward/mcp-redfish) — Query DMTF Redfish servers, systems, and network interfaces ☆`20`
- [ProductOfAmerica/mcp-server-kicad](https://github.com/ProductOfAmerica/mcp-server-kicad) — KiCad schematic and board tools, now maintenance-only ☆`16`
- [OctoEverywhere/mcp](https://github.com/OctoEverywhere/mcp) — 3D printing live status and control ☆`38`
- [ByteAsk/ByteAsk-Embedded-MCP](https://github.com/ByteAsk/ByteAsk-Embedded-MCP) — Cited answers from embedded-systems documentation ☆`26`
- [thinq-connect/thinqconnect-mcp](https://github.com/thinq-connect/thinqconnect-mcp) — ThinQ Connect MCP Server ☆`34`
- [kukapay/opcua-mcp](https://github.com/kukapay/opcua-mcp) — An MCP server that connects to OPC UA-enabled industrial systems. ☆`31`
- [github-hewei/mcp-android-adb-server](https://github.com/github-hewei/mcp-android-adb-server) — Control Android devices over ADB through an MCP ☆`27`
- [kukapay/modbus-mcp](https://github.com/kukapay/modbus-mcp) — Industrial Modbus data for AI ☆`26`
- [Hypijump31/bluetooth-mcp-server](https://github.com/Hypijump31/bluetooth-mcp-server) — bluetooth-mcp-server for Claude AI ☆`25`
- [wolfcoming/adb_mcp_server](https://github.com/wolfcoming/adb_mcp_server) — Remote Android control via ADB for MCP clients ☆`25`
- [hpohlmann/home-assistant-mcp](https://github.com/hpohlmann/home-assistant-mcp) — Find and control Home Assistant devices from Cursor ☆`24`
- [MiddlePoint-Solutions/mcp-on-android-tv](https://github.com/MiddlePoint-Solutions/mcp-on-android-tv) — MCP server on Android TV with ADB ☆`23`
- [gNucleus/text-to-cad-mcp](https://github.com/gNucleus/text-to-cad-mcp) — gNucleus Text To CAD MCP server ☆`19`
## File Systems & Storage

- [chrisryugj/kordoc](https://github.com/chrisryugj/kordoc) — Read and edit Korean HWP, HWPX, PDF and Office documents via MCP ☆`2,955`
- [SylphxAI/anymd](https://github.com/SylphxAI/anymd) — PDF, Office, EPUB, images and audio turned into markdown ☆`1,068`
- [mark3labs/mcp-filesystem-server](https://github.com/mark3labs/mcp-filesystem-server) — Go filesystem operations via MCP ☆`698`
- [cyberchitta/llm-context.py](https://github.com/cyberchitta/llm-context.py) — Python library for LLM context management ☆`308`
- [8b-is/smart-tree](https://github.com/8b-is/smart-tree) — Context-aware AI-crafted replacement for tree command ☆`273`
- [isaacphi/mcp-gdrive](https://github.com/isaacphi/mcp-gdrive) — Google Drive file reading ☆`283`
- [rust-mcp-stack/rust-mcp-filesystem](https://github.com/rust-mcp-stack/rust-mcp-filesystem) — Fast async filesystem operations ☆`185`
- [efforthye/fast-filesystem-mcp](https://github.com/efforthye/fast-filesystem-mcp) — High-performance MCP server for file operations ☆`65`
- [UseJunior/safe-docx](https://github.com/UseJunior/safe-docx) — Compare Word documents and edit them through a safer tool set ☆`47`
- [vespo92/TrueNasCoreMCP](https://github.com/vespo92/TrueNasCoreMCP) — A working TrueNAS Core MCP Server ☆`34`
- [j0hanz/filesystem-mcp](https://github.com/j0hanz/filesystem-mcp) — Search, read and edit files in directories you choose ☆`32`
- [dimitar-grigorov/mcp-file-tools](https://github.com/dimitar-grigorov/mcp-file-tools) — Read and write text files that are not UTF-8 ☆`30`
- [Tencent/cos-mcp](https://github.com/Tencent/cos-mcp) — Tencent Cloud COS storage integration ☆`40`
- [NetApp/mcp](https://github.com/NetApp/mcp) — Model Context Protocol servers for NetApp services ☆`19`
- [willianpinho/large-file-mcp](https://github.com/willianpinho/large-file-mcp) — Chunk, search, navigate, and stream large files ☆`18`
- [exoticknight/mcp-file-merger](https://github.com/exoticknight/mcp-file-merger) — MCP server for merging multiple files into one ☆`28`
- [Xuanwo/mcp-server-opendal](https://github.com/Xuanwo/mcp-server-opendal) — Model Context Protocol Server for Apache OpenDAL ☆`35`
## Finance

### Accounting & Budgeting

- [intuit/quickbooks-online-mcp-server](https://github.com/intuit/quickbooks-online-mcp-server) — Read and update QuickBooks Online ☆`447`
- [openaccountants/openaccountants](https://github.com/openaccountants/openaccountants) — Tax figures for many countries, cited to the statute ☆`480`
- [XeroAPI/xero-mcp-server](https://github.com/XeroAPI/xero-mcp-server) — Xero accounting API integration ☆`391`
- [akutishevsky/lunchmoney-mcp](https://github.com/akutishevsky/lunchmoney-mcp) — MCP server for Lunch Money budgeting app ☆`114`
- [ignaciohermosillacornejo/copilot-money-mcp](https://github.com/ignaciohermosillacornejo/copilot-money-mcp) — Questions over local Copilot Money data ☆`88`
- [iiAtlas/hledger-mcp](https://github.com/iiAtlas/hledger-mcp) — A local MCP server for interacting with the HLedger cli ☆`65`
- [openMF/mcp-mifosx](https://github.com/openMF/mcp-mifosx) — Model Context Protocol - MCP for Mifos X ☆`28`
- [finlynq/finlynq](https://github.com/finlynq/finlynq) — Personal finance app whose data an assistant can query ☆`30`
- [minhyeoky/mcp-server-ledger](https://github.com/minhyeoky/mcp-server-ledger) — MCP server for Ledger CLI double-entry accounting ☆`51`
- [john-zhang-dev/xero-mcp](https://github.com/john-zhang-dev/xero-mcp) — Interact with Xero accounting ☆`22`
- [henfrydls/actual-budget-mcp](https://github.com/henfrydls/actual-budget-mcp) — Query and update a budget in Actual Budget ☆`20`
### Crypto & Blockchain

- [atilaahmettaner/tradingview-mcp](https://github.com/atilaahmettaner/tradingview-mcp) — Screeners and backtests for crypto, stocks and forex ☆`5,257`
- [mcpdotdirect/evm-mcp-server](https://github.com/mcpdotdirect/evm-mcp-server) — EVM network interaction for LLMs ☆`379`
- [aaronjmars/web3-research-mcp](https://github.com/aaronjmars/web3-research-mcp) — Local crypto token research via CoinGecko and DeFiLlama ☆`171`
- [yolfinance/yolfi-agent](https://github.com/yolfinance/yolfi-agent) — Yolfi Agent Kit SDK, CLI, and MCP server for AI coding agents. ☆`173`
- [armorwallet/armor-crypto-mcp](https://github.com/armorwallet/armor-crypto-mcp) — Blockchain swaps and strategic planning ☆`178`
- [sendaifun/solana-mcp](https://github.com/sendaifun/solana-mcp) — Solana actions through the Solana Agent Kit ☆`166`
- [Scottcjn/rustchain-mcp](https://github.com/Scottcjn/rustchain-mcp) — Wallets, bounties and agent messages in the RustChain network ☆`122`
- [coinpaprika/dexpaprika-mcp](https://github.com/coinpaprika/dexpaprika-mcp) — MCP server for DEX trading data and crypto token analytics ☆`118`
- [kukapay/crypto-indicators-mcp](https://github.com/kukapay/crypto-indicators-mcp) — Cryptocurrency technical analysis indicators ☆`131`
- [alchemyplatform/alchemy-mcp-server](https://github.com/alchemyplatform/alchemy-mcp-server) — Alchemy blockchain API for AI agents ☆`88`
- [twelvedata/mcp](https://github.com/twelvedata/mcp) — MCP server for real-time financial market data access ☆`86`
- [lazy-dinosaur/ccxt-mcp](https://github.com/lazy-dinosaur/ccxt-mcp) — Crypto exchange trading through the CCXT library ☆`95`
- [amygdala-labs/web3-mcp](https://github.com/amygdala-labs/web3-mcp) — 1 MCP to rule all them chains ☆`93`
- [QuantGeekDev/coincap-mcp](https://github.com/QuantGeekDev/coincap-mcp) — A coincap mcp server to access crypto data from coincap API ☆`92`
- [getAlby/mcp](https://github.com/getAlby/mcp) — Bitcoin Lightning wallet via Nostr ☆`66`
- [norman-finance/norman-mcp-server](https://github.com/norman-finance/norman-mcp-server) — AI-powered bookkeeping and tax automation via MCP ☆`65`
- [bnb-chain/bnbchain-mcp](https://github.com/bnb-chain/bnbchain-mcp) — BNB Chain, BSC, opBNB, Greenfield ☆`61`
- [Nayshins/mcp-server-ccxt](https://github.com/Nayshins/mcp-server-ccxt) — Cryptocurrency Market Data MCP Server ☆`83`
- [Bankless/onchain-mcp](https://github.com/Bankless/onchain-mcp) — Bringing the bankless onchain API to MCP ☆`78`
- [kukapay/cryptopanic-mcp-server](https://github.com/kukapay/cryptopanic-mcp-server) — Provide latest cryptocurrency news to AI agents. ☆`74`
- [AbdelStark/bitcoin-mcp](https://github.com/AbdelStark/bitcoin-mcp) — Bitcoin & Lightning Network MCP Server. ☆`77`
- [heurist-network/heurist-mesh-mcp-server](https://github.com/heurist-network/heurist-mesh-mcp-server) — Blockchain and web3 via Heurist Mesh ☆`67`
- [GoPlausible/algorand-mcp](https://github.com/GoPlausible/algorand-mcp) — Algorand Local Model Context Protocol (Server & Client) ☆`44`
- [truss44/mcp-crypto-price](https://github.com/truss44/mcp-crypto-price) — Crypto prices and analysis from CoinCap ☆`40`
- [kukapay/whale-tracker-mcp](https://github.com/kukapay/whale-tracker-mcp) — A mcp server for tracking cryptocurrency whale transactions. ☆`58`
- [shinzo-labs/coinmarketcap-mcp](https://github.com/shinzo-labs/coinmarketcap-mcp) — MCP Implementation for CoinMarketCap ☆`51`
- [debridge-finance/debridge-mcp](https://github.com/debridge-finance/debridge-mcp) — Cross-chain swaps and transfers through deBridge ☆`31`
- [kukapay/crypto-feargreed-mcp](https://github.com/kukapay/crypto-feargreed-mcp) — Crypto Fear & Greed Index data ☆`52`
- [vanto/beanquery-mcp](https://github.com/vanto/beanquery-mcp) — Query a Beancount ledger ☆`52`
- [atxp-dev/atxp](https://github.com/atxp-dev/atxp) — Wallet, email, phone and paid tools for search, media and SMS ☆`46`
- [wowinter13/solscan-mcp](https://github.com/wowinter13/solscan-mcp) — Solana transaction queries ☆`49`
- [anjor/coinmarket-mcp-server](https://github.com/anjor/coinmarket-mcp-server) — MCP server for CoinMarketCap cryptocurrency data ☆`49`
- [kukapay/crypto-sentiment-mcp](https://github.com/kukapay/crypto-sentiment-mcp) — Cryptocurrency sentiment analysis ☆`47`
- [t2000-afi/t2000](https://github.com/t2000-afi/t2000) — Agent marketplace ☆`24`
- [noditlabs/nodit-mcp-server](https://github.com/noditlabs/nodit-mcp-server) — Blockchain data via Nodit Web3 API ☆`23`
- [opldotdev/bsv-mcp](https://github.com/opldotdev/bsv-mcp) — An MCP Server for Bitcoin SV ☆`22`
- [hive-intel/hive-sdk](https://github.com/hive-intel/hive-sdk) — Crypto intel for markets, DeFi, wallets, NFTs, and Solana ☆`20`
- [CoinStatsHQ/coinstats-mcp](https://github.com/CoinStatsHQ/coinstats-mcp) — Crypto prices, portfolios, and wallets via CoinStats ☆`17`
- [kukapay/dune-analytics-mcp](https://github.com/kukapay/dune-analytics-mcp) — A mcp server that bridges Dune Analytics data to AI agents. ☆`41`
- [kukapay/uniswap-trader-mcp](https://github.com/kukapay/uniswap-trader-mcp) — Uniswap token swaps for AI agents ☆`40`
- [klever-io/mcp-klever-vm](https://github.com/klever-io/mcp-klever-vm) — MCP server for Klever blockchain smart contract development ☆`31`
- [dioptx/web3-docs](https://github.com/dioptx/web3-docs) — EIPs, BIPs and other Web3 protocol documents ☆`36`
- [kukapay/kukapay-mcp-servers](https://github.com/kukapay/kukapay-mcp-servers) — Suite of MCP servers from Kukapay ☆`32`
- [longmans/coin_api_mcp](https://github.com/longmans/coin_api_mcp) — CoinMarketCap cryptocurrency data ☆`36`
- [nearai/near-mcp](https://github.com/nearai/near-mcp) — An MCP server for the NEAR blockchain ☆`32`
- [crazyrabbitLTC/mcp-etherscan-server](https://github.com/crazyrabbitLTC/mcp-etherscan-server) — ETH balances and transactions from Etherscan ☆`30`
- [kukapay/hyperliquid-info-mcp](https://github.com/kukapay/hyperliquid-info-mcp) — MCP server for Hyperliquid DEX data ☆`30`
- [tedlikeskix/alpaca-mcp-server](https://github.com/tedlikeskix/alpaca-mcp-server) — Trading through the Alpaca API ☆`28`
- [kukapay/jupiter-mcp](https://github.com/kukapay/jupiter-mcp) — Jupiter DEX token swaps on Solana ☆`29`
- [devonmojito/ton-blockchain-mcp](https://github.com/devonmojito/ton-blockchain-mcp) — TON blockchain interaction ☆`27`
- [pwh-pwh/coin-mcp-server](https://github.com/pwh-pwh/coin-mcp-server) — Cryptocurrency info via Bitget API ☆`26`
- [aldrin-labs/solana-mcp-server](https://github.com/aldrin-labs/solana-mcp-server) — solana mcp sever to enable solana rpc methods ☆`25`
- [Codex-Data/codex-mcp](https://github.com/Codex-Data/codex-mcp) — A Model Context Protocol server for the Codex API ☆`25`
- [kukapay/rug-check-mcp](https://github.com/kukapay/rug-check-mcp) — An MCP server that detects potential risks in Solana meme tokens. ☆`23`
- [kukapay/token-minter-mcp](https://github.com/kukapay/token-minter-mcp) — ERC-20 token minting for AI agents ☆`22`
- [ahnlabio/bicscan-mcp](https://github.com/ahnlabio/bicscan-mcp) — BICScan MCP Server ☆`16`
- [magnetai/mcp-free-usdc-transfer](https://github.com/magnetai/mcp-free-usdc-transfer) — Free USDC transfer via Coinbase CDP ☆`21`
- [saintdoresh/Crypto-Trader-MCP-ClaudeDesktop](https://github.com/saintdoresh/Crypto-Trader-MCP-ClaudeDesktop) — Crypto prices from CoinGecko ☆`21`
- [janswist/mcp-dexscreener](https://github.com/janswist/mcp-dexscreener) — Dexscreener on-chain price checking ☆`19`
- [xiaok/etherscan-mcp](https://github.com/xiaok/etherscan-mcp) — Model Context Protocol (MCP) Server for Etherscan ☆`18`
- [kukapay/crypto-rss-mcp](https://github.com/kukapay/crypto-rss-mcp) — Real-time cryptocurrency news from multiple RSS feeds ☆`17`
- [syronlabs/stellar-mcp](https://github.com/syronlabs/stellar-mcp) — A Stellar MCP to interact with Horizon API and Soroban ☆`18`
- [kukapay/defi-yields-mcp](https://github.com/kukapay/defi-yields-mcp) — DeFi yield opportunities powered by DefiLlama ☆`16`
- [kukapay/crypto-orderbook-mcp](https://github.com/kukapay/crypto-orderbook-mcp) — Order-book depth and imbalance on major crypto exchanges ☆`16`
### Payments & Banking

- [stripe/ai](https://github.com/stripe/ai) — One-stop shop for building AI-powered products and businesses with Stripe. ☆`2,054`
- [razorpay/razorpay-mcp-server](https://github.com/razorpay/razorpay-mcp-server) — Razorpay's Official MCP Server ☆`232`
- [paypal/agent-toolkit](https://github.com/paypal/agent-toolkit) — PayPal Agent ☆`199`
- [square/square-mcp-server](https://github.com/square/square-mcp-server) — A Model Context Protocol (MCP) server for square ☆`109`
- [ninetails-io/gnucash-mcp](https://github.com/ninetails-io/gnucash-mcp) — Read and write a GnuCash book ☆`87`
- [nuanu-ai/agent-payment-node](https://github.com/nuanu-ai/agent-payment-node) — Local agent payments on Apple silicon, with approval ☆`75`
- [icyberdeveloper/tbank-mcp](https://github.com/icyberdeveloper/tbank-mcp) — T-Bank accounts, cards, transfers and bill pay ☆`56`
- [PaddleHQ/paddle-mcp-server](https://github.com/PaddleHQ/paddle-mcp-server) — Interact with Paddle API ☆`50`
- [CorpusIQ/corpusiq-docs](https://github.com/CorpusIQ/corpusiq-docs) — Ask questions over live business data from the tools you use ☆`28`
- [qonto/qonto-mcp-server](https://github.com/qonto/qonto-mcp-server) — Qonto MCP Server ☆`42`
- [atharvagupta2003/mcp-stripe](https://github.com/atharvagupta2003/mcp-stripe) — Stripe payments, customers, and refunds ☆`44`
- [ant-intl/global-antom-mcp](https://github.com/ant-intl/global-antom-mcp) — MCP server for Antom global payments ☆`32`
- [Fewsats/fewsats-mcp](https://github.com/Fewsats/fewsats-mcp) — Fewsats MCP server ☆`21`
### Stock Data & Analytics

- [financial-datasets/mcp-server](https://github.com/financial-datasets/mcp-server) — Financial Datasets stock market API ☆`2,324`
- [relaticle/relaticle](https://github.com/relaticle/relaticle) — CRM for companies, people and deals that an agent can update ☆`1,828`
- [rootSunc/CNEquity](https://github.com/rootSunc/CNEquity) — Local data lake for China A-share research, with an MCP server ☆`987`
- [massive-com/mcp_massive](https://github.com/massive-com/mcp_massive) — An MCP server for Massive.com Financial Market Data ☆`401`
- [stefanoamorelli/sec-edgar-mcp](https://github.com/stefanoamorelli/sec-edgar-mcp) — A SEC EDGAR MCP (Model Context Protocol) Server ☆`387`
- [s-stefanov/actual-mcp](https://github.com/s-stefanov/actual-mcp) — Model Context Protocol for Actual Budget API ☆`283`
- [daniel3303/Equibles](https://github.com/daniel3303/Equibles) — SEC filings, fundamentals, transcripts, 13F and insider data ☆`244`
- [narumiruna/yfinance-mcp](https://github.com/narumiruna/yfinance-mcp) — MCP server for Yahoo Finance stock data and news ☆`209`
- [traceloop/opentelemetry-mcp-server](https://github.com/traceloop/opentelemetry-mcp-server) — Query traces in Jaeger, Tempo and other backends ☆`205`
- [jjlabsio/korea-stock-mcp](https://github.com/jjlabsio/korea-stock-mcp) — MCP Server for Korean stock analysis ☆`184`
- [calebl/ynab-mcp-server](https://github.com/calebl/ynab-mcp-server) — Model Context Protocol for YNAB (you need a budget) ☆`167`
- [Tapetide-hq/nse-bse-indian-stock-market-data-mcp](https://github.com/Tapetide-hq/nse-bse-indian-stock-market-data-mcp) — NSE and BSE prices, flows and filings ☆`150`
- [OctagonAI/octagon-mcp-server](https://github.com/OctagonAI/octagon-mcp-server) — Public filings, earnings, financial analysis ☆`149`
- [berlinbra/polymarket-mcp](https://github.com/berlinbra/polymarket-mcp) — MCP Server for PolyMarket API ☆`144`
- [HuggingAGI/mcp-baostock-server](https://github.com/HuggingAGI/mcp-baostock-server) — MCP server for BaoStock Chinese stock market data ☆`119`
- [dustinliang666-blip/lava-mcp](https://github.com/dustinliang666-blip/lava-mcp) — Trending China A-share concepts, sectors and tickers ☆`100`
- [unusual-whales/unusual-whales-official-mcp](https://github.com/unusual-whales/unusual-whales-official-mcp) — Official MCP server for Unusual Whales ☆`94`
- [berlinbra/alpha-vantage-mcp](https://github.com/berlinbra/alpha-vantage-mcp) — MCP Server for Alpha Advantage API ☆`104`
- [calvernaz/alphavantage](https://github.com/calvernaz/alphavantage) — A MCP server for the stock market data API, Alphavantage API. ☆`74`
- [twolven/mcp-stockscreen](https://github.com/twolven/mcp-stockscreen) — Stock screening provider for Claude Desktop using MCP ☆`49`
- [infaton/MCP35](https://github.com/infaton/MCP35) — Tools for 1C:Enterprise ERP ☆`48`
- [twolven/mcp-optionsflow](https://github.com/twolven/mcp-optionsflow) — Options greeks and strategies from Yahoo Finance ☆`41`
- [Adity-star/mcp-yfinance-server](https://github.com/Adity-star/mcp-yfinance-server) — Real-time stock data with yfinance ☆`54`
- [JamesANZ/prediction-market-mcp](https://github.com/JamesANZ/prediction-market-mcp) — Polymarket, PredictIt, Kalshi data ☆`38`
- [AgentX-ai/yahoo-finance-server](https://github.com/AgentX-ai/yahoo-finance-server) — Yahoo Finance stock data and news ☆`54`
- [ComplyEaze/bridge](https://github.com/ComplyEaze/bridge) — Read a local TallyPrime company and prepare vouchers ☆`35`
- [9crusher/mcp-server-kalshi](https://github.com/9crusher/mcp-server-kalshi) — A MCP server to interact with Kalshi prediction markets ☆`32`
- [zlinzzzz/finData-mcp-server](https://github.com/zlinzzzz/finData-mcp-server) — Financial data from Tushare, Wind, DataYes ☆`57`
- [vanderheijden86/moneybird-mcp-server](https://github.com/vanderheijden86/moneybird-mcp-server) — Moneybird MCP Server - AI-powered bookkeeping ☆`29`
- [twolven/mcp-stockflow](https://github.com/twolven/mcp-stockflow) — Stock market data provider for Claude Desktop using MCP ☆`27`
- [trayders/trayd-mcp](https://github.com/trayders/trayd-mcp) — Trade Robinhood via Claude Code - MCP Server ☆`41`
- [Mrbaeksang/korea-stock-analyzer-mcp](https://github.com/Mrbaeksang/korea-stock-analyzer-mcp) — Korean stocks from DART filings and KRX quotes ☆`26`
- [danishashko/yahoo-finance-mcp](https://github.com/danishashko/yahoo-finance-mcp) — Quotes, charts and financials from Yahoo Finance ☆`24`
- [grahammccain/chart-library-mcp](https://github.com/grahammccain/chart-library-mcp) — Find past stock charts that resemble this one ☆`23`
- [tonnode/mcp](https://github.com/tonnode/mcp) — TON balances, account state and transactions over ADNL ☆`20`
- [cliwant/mcp-sam-gov](https://github.com/cliwant/mcp-sam-gov) — US federal and state contracting, spending and sanctions data ☆`17`
- [OctagonAI/octagon-vc-agents](https://github.com/OctagonAI/octagon-vc-agents) — AI-driven venture capitalist agents ☆`33`
- [27dream/mcp-eastmoney](https://github.com/27dream/mcp-eastmoney) — East Money MCP for A-share quotes, fund flow, sectors and candles ☆`19`
- [QuantGeekDev/fiscal-data-mcp](https://github.com/QuantGeekDev/fiscal-data-mcp) — US Treasury fiscal data ☆`20`
### Trading & Exchanges

- [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) — "Vibe-Trading: Your Personal Trading Agent" ☆`37,980`
- [chengzuopeng/stock-sdk](https://github.com/chengzuopeng/stock-sdk) — Zero-dependency JavaScript SDK for fetching stock data ☆`1,999`
- [mnemox-ai/tradememory-protocol](https://github.com/mnemox-ai/tradememory-protocol) — Memory and audit trail for trading agents ☆`1,443`
- [alpacahq/alpaca-mcp-server](https://github.com/alpacahq/alpaca-mcp-server) — Trade stocks, ETFs, crypto, options ☆`1,075`
- [whchien/ai-trader](https://github.com/whchien/ai-trader) — Backtests with many strategies, plus an MCP server ☆`1,134`
- [ariadng/metatrader-mcp-server](https://github.com/ariadng/metatrader-mcp-server) — MetaTrader trading platform for AI LLMs ☆`847`
- [dragon1086/prism-insight](https://github.com/dragon1086/prism-insight) — AI-based stock analysis and trading system ☆`804`
- [krakenfx/kraken-cli](https://github.com/krakenfx/kraken-cli) — Trade on Kraken, including a paper account ☆`807`
- [YoungCan-Wang/WyckoffTradingAgent](https://github.com/YoungCan-Wang/WyckoffTradingAgent) — Wyckoff trading agent and stock screener with MCP ☆`771`
- [caiovicentino/polymarket-mcp-server](https://github.com/caiovicentino/polymarket-mcp-server) — Read and trade Polymarket prediction markets ☆`745`
- [wshobson/maverick-mcp](https://github.com/wshobson/maverick-mcp) — Yahoo Finance data, technicals and local Python backtests ☆`722`
- [saidsurucu/borsa-mcp](https://github.com/saidsurucu/borsa-mcp) — MCP Server for Turkish & American Stock Exchange and Fund Data ☆`660`
- [okx/agent-trade-kit](https://github.com/okx/agent-trade-kit) — Spot, swap, futures and grid bots on OKX ☆`505`
- [longbridge/openapi](https://github.com/longbridge/openapi) — Longbridge OpenAPI SDK Base. ☆`468`
- [elsejj/mcp-cn-a-stock](https://github.com/elsejj/mcp-cn-a-stock) — MCP server for China A-share market data ☆`461`
- [koreal6803/finlab-ai](https://github.com/koreal6803/finlab-ai) — Backtest Taiwan and US stocks on real market data ☆`426`
- [staskh/trading_skills](https://github.com/staskh/trading_skills) — Claude powered advisor system for option traders ☆`406`
- [Alex2Yang97/yahoo-finance-mcp](https://github.com/Alex2Yang97/yahoo-finance-mcp) — Quotes, fundamentals and history from Yahoo Finance ☆`368`
- [aahl/mcp-aktools](https://github.com/aahl/mcp-aktools) — MCP server for stock and crypto data queries ☆`392`
- [ferdousbhai/investor-agent](https://github.com/ferdousbhai/investor-agent) — Investor agent building via MCP ☆`349`
- [QuantMLResearch/AI-Kline](https://github.com/QuantMLResearch/AI-Kline) — Technical analysis and a forecast from stock candlesticks ☆`344`
- [guangxiangdebizi/TradingAgents-MCPmode](https://github.com/guangxiangdebizi/TradingAgents-MCPmode) — Multi-agent stock analysis and trading ☆`340`
- [Qoyyuum/mcp-metatrader5-server](https://github.com/Qoyyuum/mcp-metatrader5-server) — Market data and trading actions in MetaTrader 5 ☆`243`
- [zwldarren/akshare-one-mcp](https://github.com/zwldarren/akshare-one-mcp) — Chinese stock data through akshare-one ☆`246`
- [wbsu2003/stock-scanner-mcp](https://github.com/wbsu2003/stock-scanner-mcp) — Stock prices, scores and technical reports over MCP ☆`244`
- [dfkai/xtquantai](https://github.com/dfkai/xtquantai) — Quant research skills for QMT backtests in coding agents ☆`170`
- [imbenrabi/Financial-Modeling-Prep-MCP-Server](https://github.com/imbenrabi/Financial-Modeling-Prep-MCP-Server) — Market data from Financial Modeling Prep ☆`149`
- [kukapay/freqtrade-mcp](https://github.com/kukapay/freqtrade-mcp) — Freqtrade crypto trading bot ☆`149`
- [taylorwilsdon/quantconnect-mcp](https://github.com/taylorwilsdon/quantconnect-mcp) — QuantConnect trading orchestration ☆`125`
- [doggybee/mcp-server-ccxt](https://github.com/doggybee/mcp-server-ccxt) — Cryptocurrency exchange integration via CCXT ☆`145`
- [ferdousbhai/tasty-agent](https://github.com/ferdousbhai/tasty-agent) — Let Claude manage your tastytrade portfolio. ☆`89`
- [QuantConnect/mcp-server](https://github.com/QuantConnect/mcp-server) — QuantConnect algo trading interaction ☆`80`
- [dragon1086/kospi-kosdaq-stock-server](https://github.com/dragon1086/kospi-kosdaq-stock-server) — KOSPI and KOSDAQ stock data ☆`75`
- [trade-it-inc/trade-it-mcp](https://github.com/trade-it-inc/trade-it-mcp) — Trade It stocks and crypto trading ☆`62`
- [netanelavr/trading-mcp](https://github.com/netanelavr/trading-mcp) — Stock screening, fundamentals, insider trades and news sentiment ☆`75`
- [hypurrquant/perp-cli](https://github.com/hypurrquant/perp-cli) — Perpetual futures on several DEXes ☆`41`
- [ethancod1ng/binance-mcp-server](https://github.com/ethancod1ng/binance-mcp-server) — Binance exchange API integration ☆`34`
- [ferdousbhai/wsb-analyst-mcp](https://github.com/ferdousbhai/wsb-analyst-mcp) — MCP server for analyzing WallStreetBets ☆`32`
- [ozgureyilmaz/polymarket-mcp](https://github.com/ozgureyilmaz/polymarket-mcp) — Polymarket prediction markets data ☆`48`
- [coinpaprika/coinpaprika-mcp](https://github.com/coinpaprika/coinpaprika-mcp) — Prices, tickers and exchanges from CoinPaprika ☆`30`
- [mektigboy/server-hyperliquid](https://github.com/mektigboy/server-hyperliquid) — Hyperliquid DEX trading integration ☆`44`
- [demwick/polymarket-agent-mcp](https://github.com/demwick/polymarket-agent-mcp) — Discover, trade and backtest Polymarket markets ☆`19`
- [saintdoresh/YFinance-Trader-MCP-ClaudeDesktop](https://github.com/saintdoresh/YFinance-Trader-MCP-ClaudeDesktop) — Stock data and trades through yfinance ☆`37`
- [laukikk/alpaca-mcp](https://github.com/laukikk/alpaca-mcp) — Alpaca stock and crypto trading ☆`35`
- [paperinvest/mcp-server](https://github.com/paperinvest/mcp-server) — Paper trading platform integration ☆`24`
- [solangii/upbit-mcp-server](https://github.com/solangii/upbit-mcp-server) — MCP(Model Context Protocol) server for Upbit ☆`17`
## Frameworks & SDKs

- [mastra-ai/mastra](https://github.com/mastra-ai/mastra) — TypeScript AI agent framework with RAG ☆`29,459`
- [mcp-use/mcp-use](https://github.com/mcp-use/mcp-use) — Framework for MCP apps and servers ☆`10,863`
- [lastmile-ai/mcp-agent](https://github.com/lastmile-ai/mcp-agent) — Build agents with MCP and workflow patterns ☆`8,580`
- [xmcp](https://github.com/basementstudio/xmcp) — TypeScript framework for building MCP servers. Website: https://xmcp.dev. ☆`1,351`
- [afrise/MCPSharp](https://github.com/afrise/MCPSharp) — .NET library for building MCP servers and clients ☆`377`
- [vinkius-labs/mcpfusion](https://github.com/vinkius-labs/mcpfusion) — MCP Fusion - The TypeScript framework for secure MCP servers. ☆`255`
- [posit-dev/mcptools](https://github.com/posit-dev/mcptools) — Model Context Protocol For R ☆`206`
- [quarkiverse/quarkus-mcp-server-examples](https://github.com/quarkiverse/quarkus-mcp-server-examples) — Model Context Protocol Servers in Quarkus ☆`197`
- [wong2/litemcp](https://github.com/wong2/litemcp) — A TypeScript framework for building MCP servers elegantly ☆`185`
- [agentrpc/agentrpc](https://github.com/agentrpc/agentrpc) — Universal RPC layer for AI agents ☆`135`
- [vishalmysore/a2ajava](https://github.com/vishalmysore/a2ajava) — Google A2A protocol for Spring Boot ☆`109`
- [strowk/foxy-contexts](https://github.com/strowk/foxy-contexts) — Library for MCP context servers ☆`114`
- [tesla0225/mcp-create](https://github.com/tesla0225/mcp-create) — Dynamic MCP server creation and management ☆`98`
- [abap-ai/mcp](https://github.com/abap-ai/mcp) — ABAP MCP - Model Context Protocol - Server SDK ☆`87`
- [mcpdotdirect/template-mcp-server](https://github.com/mcpdotdirect/template-mcp-server) — Template to quickly set up your own MCP server ☆`76`
- [domdomegg/programmatic-mcp-prototype](https://github.com/domdomegg/programmatic-mcp-prototype) — Programmatic MCP tool composition ☆`44`
- [particlefuture/1mcpserver](https://github.com/particlefuture/1mcpserver) — Auto-discover and configure MCP servers ☆`51`
- [mojolicious/mojo-mcp](https://github.com/mojolicious/mojo-mcp) — Perl SDK for Model Context Protocol servers and clients ☆`23`
- [mcpx-dev/mcp-badges](https://github.com/mcpx-dev/mcp-badges) — Get your projects MCP (Model Context Protocol) badges ☆`30`
## Gaming

- [Coding-Solo/godot-mcp](https://github.com/Coding-Solo/godot-mcp) — MCP server for Godot game engine ☆`6,599`
- [IvanMurzak/Unity-MCP](https://github.com/IvanMurzak/Unity-MCP) — AI-powered bridge connecting LLMs to Unity Editor ☆`4,615`
- [CoderGamester/mcp-unity](https://github.com/CoderGamester/mcp-unity) — MCP server for Unity game engine integration ☆`2,017`
- [youichi-uda/godot-mcp-pro](https://github.com/youichi-uda/godot-mcp-pro) — Godot 4 scenes, animation, physics and shaders ☆`640`
- [ee0pdt/Godot-MCP](https://github.com/ee0pdt/Godot-MCP) — Create and edit games in the Godot editor ☆`621`
- [kvick-games/UnrealMCP](https://github.com/kvick-games/UnrealMCP) — MCP to allow AI agents to control Unreal ☆`615`
- [IvanMurzak/Godot-MCP](https://github.com/IvanMurzak/Godot-MCP) — Godot 4.x editor and runtime for AI agents ☆`336`
- [playcanvas/editor-mcp-server](https://github.com/playcanvas/editor-mcp-server) — MCP Server for AI automation of the PlayCanvas Editor ☆`151`
- [ayeletstudioindia/unreal-analyzer-mcp](https://github.com/ayeletstudioindia/unreal-analyzer-mcp) — MCP server for Unreal Engine 5 ☆`161`
- [quazaai/UnityMCPIntegration](https://github.com/quazaai/UnityMCPIntegration) — Enable AI Agents to Control Unity ☆`155`
- [Erodenn/godot-mcp-runtime](https://github.com/Erodenn/godot-mcp-runtime) — Drive a running Godot 4 editor with no extra plugin weight ☆`97`
- [pab1it0/chess-mcp](https://github.com/pab1it0/chess-mcp) — MCP server for Chess.com player data, games and statistics ☆`94`
- [tonypan2/minesweeper-mcp-server](https://github.com/tonypan2/minesweeper-mcp-server) — An MCP server for playing Minesweeper ☆`106`
- [codemaestroai/advanced-unity-mcp](https://github.com/codemaestroai/advanced-unity-mcp) — Advanced Unity game engine integration ☆`95`
- [hope1026/weppy-roblox-mcp](https://github.com/hope1026/weppy-roblox-mcp) — Scripts, terrain and lighting in Roblox Studio ☆`75`
- [kkjdaniel/bgg-mcp](https://github.com/kkjdaniel/bgg-mcp) — MCP server for BoardGameGeek data ☆`60`
- [IvanMurzak/Unreal-MCP](https://github.com/IvanMurzak/Unreal-MCP) — Unreal Engine 5.7 editor and runtime for AI agents ☆`58`
- [sawa-zen/vrchat-mcp](https://github.com/sawa-zen/vrchat-mcp) — VRChat API interaction ☆`71`
- [beckettlab/beckett-godot-mcp](https://github.com/beckettlab/beckett-godot-mcp) — Inspect, edit and run Godot from inside the editor ☆`50`
- [Dokujaa/Godot-MCP](https://github.com/Dokujaa/Godot-MCP) — An MCP for Godot that leverages Claude ☆`54`
- [jalpp/chessagine-mcp](https://github.com/jalpp/chessagine-mcp) — Advanced chess analysis capabilities ☆`34`
- [dearlordylord/5e-quint](https://github.com/dearlordylord/5e-quint) — Quint definition of Dungeons and Dragons 5e core rules ☆`32`
- [kitao/pyxel-mcp](https://github.com/kitao/pyxel-mcp) — MCP server for AI-assisted retro game development with Pyxel ☆`32`
- [german-krasnikov/unity-biome-mcp](https://github.com/german-krasnikov/unity-biome-mcp) — Unity scenes, assets, animation and playtests ☆`31`
- [procload/dnd-mcp](https://github.com/procload/dnd-mcp) — Dungeons and Dragons 5e rules, spells and monsters ☆`53`
- [DiegoLopez0208/RpgMakerMVUltimate-MCP](https://github.com/DiegoLopez0208/RpgMakerMVUltimate-MCP) — Debug events, edit maps and playtest RPG Maker MV ☆`30`
- [runeape-sats/unreal-mcp](https://github.com/runeape-sats/unreal-mcp) — pure python Unreal Engine MCP server ☆`47`
- [buildepicshit/Wick](https://github.com/buildepicshit/Wick) — C# exception telemetry from Godot, enriched by Roslyn ☆`22`
- [karayaman/lichess-mcp](https://github.com/karayaman/lichess-mcp) — Play and analyze games on Lichess ☆`20`
- [IvanMurzak/GameDev-MCP-Server](https://github.com/IvanMurzak/GameDev-MCP-Server) — Shared server behind the Unity, Godot and Unreal plugins ☆`19`
- [3aKHP/prts-mcp](https://github.com/3aKHP/prts-mcp) — MCP Server for Arknights PRTS Wiki and local game data ☆`16`
- [cryppadotta/scryfall-mcp](https://github.com/cryppadotta/scryfall-mcp) — Look up Magic: The Gathering cards on Scryfall ☆`36`
- [jifrozen0110/mcp-riot](https://github.com/jifrozen0110/mcp-riot) — League of Legends MCP Server ☆`27`
- [jiayao/mcp-chess](https://github.com/jiayao/mcp-chess) — MCP server for playing chess against AI ☆`24`
- [tahooki/unreal-blender-mcp](https://github.com/tahooki/unreal-blender-mcp) — unreal-blender-mcp ☆`21`
- [sonirico/mcp-stockfish](https://github.com/sonirico/mcp-stockfish) — MCP server connecting AI systems to Stockfish chess engine ☆`16`
## Healthcare & Bioinformatics

- [genomoncology/biomcp](https://github.com/genomoncology/biomcp) — BioMCP: Biomedical Model Context Protocol ☆`674`
- [the-momentum/apple-health-mcp-server](https://github.com/the-momentum/apple-health-mcp-server) — Apple Health data queries with DuckDB ☆`286`
- [wso2/fhir-mcp-server](https://github.com/wso2/fhir-mcp-server) — FHIR healthcare API integration ☆`137`
- [JamesANZ/medical-mcp](https://github.com/JamesANZ/medical-mcp) — MCP server for medical data processing ☆`121`
- [ChristianHinge/dicom-mcp](https://github.com/ChristianHinge/dicom-mcp) — DICOM server (PACS) interaction ☆`108`
- [grll/pubmedmcp](https://github.com/grll/pubmedmcp) — A MCP server for PubMed data ☆`122`
- [davidmosiah/google-health-mcp](https://github.com/davidmosiah/google-health-mcp) — Google Health, Fitbit and Pixel Watch data ☆`81`
- [the-momentum/fhir-mcp-server](https://github.com/the-momentum/fhir-mcp-server) — FHIR MCP Server for handling medical data standard. ☆`102`
- [soma-intelligence/open-health-sync](https://github.com/soma-intelligence/open-health-sync) — One API for Apple Health, Oura, WHOOP and Fitbit ☆`65`
- [srijanshukla18/xray](https://github.com/srijanshukla18/xray) — MCP server for X-ray analysis ☆`52`
- [cafferychen777/ChatSpatial](https://github.com/cafferychen777/ChatSpatial) — Spatial transcriptomics via natural language (Python/R) ☆`45`
- [akutishevsky/withings-mcp](https://github.com/akutishevsky/withings-mcp) — MCP server for Withings health data integration ☆`45`
- [kidzik/other-public-mcps](https://github.com/kidzik/other-public-mcps) — Biomedical databases for literature and life-science research ☆`58`
- [OkGoDoIt/beemcp](https://github.com/OkGoDoIt/beemcp) — Unofficial bridge from a Bee wearable lifelog to an assistant ☆`51`
- [OHNLP/omop_mcp](https://github.com/OHNLP/omop_mcp) — MCP server for OMOP medical data standard ☆`43`
- [Jezue/fitatu_library](https://github.com/Jezue/fitatu_library) — Unofficial Python client for the Fitatu food API ☆`23`
- [wavelovey/pubmed_search](https://github.com/wavelovey/pubmed_search) — MCP PubMed Search Server ☆`46`
- [ammawla/encode-toolkit](https://github.com/ammawla/encode-toolkit) — Search and analyze ENCODE ChIP-seq, ATAC-seq and RNA-seq data ☆`20`
- [SidneyBissoli/medical-terminologies-mcp](https://github.com/SidneyBissoli/medical-terminologies-mcp) — ICD-11, LOINC, RxNorm, MeSH and related codes ☆`16`
- [tomekkorbak/oura-mcp-server](https://github.com/tomekkorbak/oura-mcp-server) — MCP server for Oura API integration ☆`39`
- [longevity-genie/biothings-mcp](https://github.com/longevity-genie/biothings-mcp) — MCP (Model Context Protocol) server for biothings ☆`37`
- [longevity-genie/gget-mcp](https://github.com/longevity-genie/gget-mcp) — Bioinformatic gget functions ☆`33`
- [Sivan22/mcp-otzaria-server](https://github.com/Sivan22/mcp-otzaria-server) — Jewish library texts for a model ☆`23`
- [longevity-genie/opengenes-mcp](https://github.com/longevity-genie/opengenes-mcp) — MCP for the open-genes ☆`21`
- [deak-ai/openehr-mcp-server](https://github.com/deak-ai/openehr-mcp-server) — Create and read openEHR health records ☆`18`
## LLM Bridges

- [CherryHQ/cherry-studio](https://github.com/CherryHQ/cherry-studio) — Your AI workspace for models, agents, and productivity. ☆`53,389`
- [perplexityai/modelcontextprotocol](https://github.com/perplexityai/modelcontextprotocol) — Official Perplexity API MCP server ☆`2,620`
- [ggozad/oterm](https://github.com/ggozad/oterm) — the terminal client for LLMs ☆`2,447`
- [jamubc/gemini-mcp-tool](https://github.com/jamubc/gemini-mcp-tool) — MCP server for Gemini CLI with large file analysis ☆`2,297`
- [OpenAgentPlatform/Dive](https://github.com/OpenAgentPlatform/Dive) — Desktop host for any model that can call tools ☆`1,824`
- [patruff/ollama-mcp-bridge](https://github.com/patruff/ollama-mcp-bridge) — Let a local Ollama model call MCP tools ☆`984`
- [DMontgomery40/deepseek-mcp-server](https://github.com/DMontgomery40/deepseek-mcp-server) — MCP server for DeepSeek language models ☆`364`
- [nesquikm/mcp-rubber-duck](https://github.com/nesquikm/mcp-rubber-duck) — MCP bridge to query multiple OpenAI-compatible LLMs ☆`180`
- [pyroprompts/any-chat-completions-mcp](https://github.com/pyroprompts/any-chat-completions-mcp) — MCP Server for using any LLM as a Tool ☆`166`
- [eLyiN/gemini-bridge](https://github.com/eLyiN/gemini-bridge) — Bridge AI agents to Google Gemini via CLI ☆`99`
- [elvismdev/mem0-mcp-selfhosted](https://github.com/elvismdev/mem0-mcp-selfhosted) — Self-hosted mem0 memory using Qdrant, Neo4j and Ollama ☆`112`
- [choplin/mcp-gemini-cli](https://github.com/choplin/mcp-gemini-cli) — MCP server for Gemini CLI integration ☆`101`
- [spranab/brainstorm-mcp](https://github.com/spranab/brainstorm-mcp) — Multi-model debate, then one answer ☆`73`
- [pierrebrunelle/mcp-server-openai](https://github.com/pierrebrunelle/mcp-server-openai) — Query OpenAI models from Claude via MCP ☆`84`
- [merterbak/Grok-MCP](https://github.com/merterbak/Grok-MCP) — MCP server for xAI Grok API with tool calling and vision ☆`55`
- [mzxrai/mcp-openai](https://github.com/mzxrai/mcp-openai) — Chat with OpenAI models from Claude Desktop ☆`77`
- [ruixingshi/deepseek-thinker-mcp](https://github.com/ruixingshi/deepseek-thinker-mcp) — DeepSeek reasoning for MCP-enabled clients ☆`69`
- [kamelirzouni/MCP-server-Deepseek_R1](https://github.com/kamelirzouni/MCP-server-Deepseek_R1) — Connect Claude Desktop with DeepSeek ☆`68`
- [vixl-ai/vixl](https://github.com/vixl-ai/vixl) — Local desktop coding agent, bring your own key ☆`22`
- [JamesANZ/cross-llm-mcp](https://github.com/JamesANZ/cross-llm-mcp) — ChatGPT, Claude, Gemini, Mistral, Kimi, and DeepSeek APIs ☆`17`
- [HyperbolicLabs/hyperbolic-mcp](https://github.com/HyperbolicLabs/hyperbolic-mcp) — MCP Server for Claude ☆`17`
- [andybrandt/mcp-simple-openai-assistant](https://github.com/andybrandt/mcp-simple-openai-assistant) — Use OpenAI GPTs assistants from Claude ☆`39`
- [emgeee/mcp-ollama](https://github.com/emgeee/mcp-ollama) — Ask a model that is running in Ollama ☆`34`
- [billster45/mcp-chatgpt-responses](https://github.com/billster45/mcp-chatgpt-responses) — MCP server for OpenAI ChatGPT API with Responses API ☆`25`
- [kamelirzouni/MCP-server-Qwen_Max](https://github.com/kamelirzouni/MCP-server-Qwen_Max) — MCP server for Qwen Max model ☆`24`
## Location & Maps

### GIS

- [jjsantos01/qgis_mcp](https://github.com/jjsantos01/qgis_mcp) — QGIS Desktop control for language models ☆`1,150`
- [mahdin75/gis-mcp](https://github.com/mahdin75/gis-mcp) — MCP server connecting LLMs to GIS capabilities ☆`205`
- [mahdin75/geoserver-mcp](https://github.com/mahdin75/geoserver-mcp) — GeoServer geospatial integration ☆`97`
- [JordanGunn/gdal-mcp](https://github.com/JordanGunn/gdal-mcp) — Geospatial analysis with epistemic reasoning ☆`85`
- [BnJam/stac-mcp](https://github.com/BnJam/stac-mcp) — An MCP Server for STAC requests ☆`20`
- [webcoderz/MCP-Geo](https://github.com/webcoderz/MCP-Geo) — Geocoding MCP server with GeoPY! ☆`34`
### IP Geolocation

- [ip2location/mcp-ip2location-io](https://github.com/ip2location/mcp-ip2location-io) — IP Geolocation MCP server using IP2Location.io API ☆`16`
- [iplocate/mcp-server-iplocate](https://github.com/iplocate/mcp-server-iplocate) — IP geolocation, proxy detection via IPLocate.io API ☆`20`
### Maps & Navigation

- [cablate/mcp-google-map](https://github.com/cablate/mcp-google-map) — Places, routes and local SEO from Google Maps ☆`491`
- [baidu-maps/mcp](https://github.com/baidu-maps/mcp) — Baidu Map MCP Server ☆`447`
- [mapbox/mcp-server](https://github.com/mapbox/mcp-server) — Mapbox Model Context Protocol (MCP) server ☆`368`
- [jagan-shanmugam/open-streetmap-mcp](https://github.com/jagan-shanmugam/open-streetmap-mcp) — MCP server for OpenStreetMap data ☆`233`
- [gaopengbin/cesium-mcp](https://github.com/gaopengbin/cesium-mcp) — Drive a CesiumJS scene from an agent or the browser ☆`151`
- [Knight60/ArcGIS-Pro-MCP](https://github.com/Knight60/ArcGIS-Pro-MCP) — Drive an open ArcGIS Pro project, including geoprocessing ☆`66`
- [tomtom-international/tomtom-maps-mcp](https://github.com/tomtom-international/tomtom-maps-mcp) — TomTom location, search, routing ☆`59`
- [muend/arcgis-mcp-bridge](https://github.com/muend/arcgis-mcp-bridge) — Local access to ArcGIS Pro through ArcPy ☆`25`
- [stadiamaps/stadiamaps-mcp-server-ts](https://github.com/stadiamaps/stadiamaps-mcp-server-ts) — Stadia Maps API integration in TypeScript ☆`25`
- [kukapay/nearby-search-mcp](https://github.com/kukapay/nearby-search-mcp) — Nearby place search with IP-based location ☆`22`
### Weather

- [isdaniel/mcp_weather_server](https://github.com/isdaniel/mcp_weather_server) — Weather info via Open-Meteo API ☆`61`
- [caiyunapp/mcp-caiyun-weather](https://github.com/caiyunapp/mcp-caiyun-weather) — Forecasts from Caiyun Weather ☆`48`
- [vikramgorla/mcp-swiss](https://github.com/vikramgorla/mcp-swiss) — Swiss open data: transport, weather, maps and companies ☆`26`
- [adhikasp/mcp-weather](https://github.com/adhikasp/mcp-weather) — Hourly forecasts from AccuWeather ☆`38`
- [TimLukaHorstmann/mcp-weather](https://github.com/TimLukaHorstmann/mcp-weather) — AccuWeather hourly and daily forecasts ☆`34`
- [sjanaX01/weather-mcp-server](https://github.com/sjanaX01/weather-mcp-server) — A simple minimal weather mcp server :) ☆`24`
- [mschneider82/mcp-openweather](https://github.com/mschneider82/mcp-openweather) — mcp server for openweather free api ☆`22`
## MCP Clients

- [lobehub/lobehub](https://github.com/lobehub/lobehub) — Hire, schedule and report on a team of agents ☆`84,651`
- [aaif-goose/goose](https://github.com/aaif-goose/goose) — Agent that installs, edits, runs and tests code with any LLM ☆`56,419`
- [LibreChat-AI/LibreChat](https://github.com/LibreChat-AI/LibreChat) — Chat app with agents, MCP and many model providers ☆`46,918`
- [Upsonic/Upsonic](https://github.com/Upsonic/Upsonic) — Build autonomous AI agents in Python. ☆`7,969`
- [genkit-ai/genkit](https://github.com/genkit-ai/genkit) — AI app framework for JavaScript and Go ☆`6,580`
- [ThinkInAIXYZ/deepchat](https://github.com/ThinkInAIXYZ/deepchat) — Desktop assistant that connects models to personal tools ☆`6,387`
- [nanbingxyz/5ire](https://github.com/nanbingxyz/5ire) — Desktop assistant and MCP client, with a local knowledge base ☆`5,370`
- [srbhptl39/MCP-SuperAssistant](https://github.com/srbhptl39/MCP-SuperAssistant) — MCP tools inside ChatGPT, Gemini and Grok ☆`2,629`
- [daodao97/chatmcp](https://github.com/daodao97/chatmcp) — Chat client that speaks MCP ☆`2,224`
- [NitroRCr/AIaW](https://github.com/NitroRCr/AIaW) — Local-first chat client with workspaces, plugins and cloud sync ☆`1,843`
- [ravitemer/mcphub.nvim](https://github.com/ravitemer/mcphub.nvim) — MCP client for Neovim with intuitive server management ☆`1,791`
- [CopilotKit/open-mcp-client](https://github.com/CopilotKit/open-mcp-client) — Self-hosted chat client for any MCP server ☆`1,652`
- [ASCIT31/Dark-Moon](https://github.com/ASCIT31/Dark-Moon) — Autonomous pentest host for 80+ security tools ☆`1,212`
- [SecretiveShell/MCP-Bridge](https://github.com/SecretiveShell/MCP-Bridge) — OpenAI-compatible endpoint calling MCP tools ☆`922`
- [aeonfun/aeon](https://github.com/aeonfun/aeon) — GitHub Actions agents with OAuth to remote MCP servers ☆`792`
- [xark-argo/argo](https://github.com/xark-argo/argo) — Desktop agent platform with local models and offline RAG ☆`837`
- [BigSweetPotatoStudio/HyperChat](https://github.com/BigSweetPotatoStudio/HyperChat) — Chat client for many LLMs, with tools over MCP ☆`708`
- [swarmclawai/swarmclaw](https://github.com/swarmclawai/swarmclaw) — Self-hosted runtime for swarms of agents, with schedules ☆`706`
- [mario-andreschak/FLUJO](https://github.com/mario-andreschak/FLUJO) — Local visual agent builder with MCP and multi-model chat ☆`675`
- [truffle-ai/dexto](https://github.com/truffle-ai/dexto) — Harness, CLI and SDKs for building agents ☆`659`
- [adhikasp/mcp-client-cli](https://github.com/adhikasp/mcp-client-cli) — A simple CLI to run LLM prompt and implement MCP client. ☆`676`
- [Muvon/octomind](https://github.com/Muvon/octomind) — Coding agent and runtime in one binary, for any model ☆`642`
- [QuixiAI/dolphin-mcp](https://github.com/QuixiAI/dolphin-mcp) — Connect several MCP servers to any local or remote model ☆`534`
- [supercorp-ai/superinterface](https://github.com/supercorp-ai/superinterface) — React components for assistants inside your own app ☆`346`
- [Lucassssss/eechat](https://github.com/Lucassssss/eechat) — Local AI chat application ☆`353`
- [3choff/mcp-chatbot](https://github.com/3choff/mcp-chatbot) — CLI chatbot with MCP integration demo ☆`251`
- [EvalsOne/MCP-connect](https://github.com/EvalsOne/MCP-connect) — Cloud AI access to local Stdio MCP servers ☆`240`
- [autohandai/code-cli](https://github.com/autohandai/code-cli) — Terminal coding agent with many providers and a plan mode ☆`217`
- [AI-QL/chat-mcp](https://github.com/AI-QL/chat-mcp) — Desktop chat app with MCP support ☆`240`
- [benord-labs/frink](https://github.com/benord-labs/frink) — Desktop app for parallel agents and multi-step workflows ☆`175`
- [johannesbrandenburger/typst-mcp](https://github.com/johannesbrandenburger/typst-mcp) — MCP server for Typst markup-based typesetting system ☆`187`
- [aofp/yume](https://github.com/aofp/yume) — Desktop app for Claude Code, with background agents ☆`154`
- [3dify-project/dify-mcp-client](https://github.com/3dify-project/dify-mcp-client) — Dify plugin that acts as an MCP client ☆`172`
- [off-grid-ai/OGAD](https://github.com/off-grid-ai/OGAD) — On-device MCP client for Mac with a local LLM ☆`146`
- [sooperset/mcp-client-slackbot](https://github.com/sooperset/mcp-client-slackbot) — Simple Slackbot MCP Client ☆`163`
- [yincongcyincong/mcp-client-go](https://github.com/yincongcyincong/mcp-client-go) — Go client that can attach several MCP servers ☆`150`
- [SylphAI-Inc/adal-cli](https://github.com/SylphAI-Inc/adal-cli) — Agent harness aimed at go-to-market work from the codebase ☆`111`
- [tanaikech/ToolsForMCPServer](https://github.com/tanaikech/ToolsForMCPServer) — MCP server built with Google Apps Script for Gemini CLI ☆`108`
- [nick1udwig/kibitz](https://github.com/nick1udwig/kibitz) — The coding agent for professionals ☆`111`
- [xzq-xu/jvm-mcp-server](https://github.com/xzq-xu/jvm-mcp-server) — JVM-based MCP server implementation ☆`91`
- [ckanthony/gin-mcp](https://github.com/ckanthony/gin-mcp) — Enable MCP features for any Gin API with a line of code ☆`85`
- [taskade/taskade](https://github.com/taskade/taskade) — Public docs and starter kits for the Taskade workspace ☆`71`
- [apify/tester-mcp-client](https://github.com/apify/tester-mcp-client) — Model Context Protocol (MCP) Client for Apify's Actors ☆`80`
- [Xingsandesu/CarrotAI](https://github.com/Xingsandesu/CarrotAI) — Streaming chat client with MCP tools ☆`86`
- [n00bvn/CanvasMCPClient](https://github.com/n00bvn/CanvasMCPClient) — Zoomable canvas dashboard for talking to MCP servers ☆`78`
- [seekrays/seekchat](https://github.com/seekrays/seekchat) — Desktop assistant that can connect MCP servers ☆`65`
- [zacharypodbela/django-rest-framework-mcp](https://github.com/zacharypodbela/django-rest-framework-mcp) — MCP server for Django REST Framework ☆`55`
- [php-mcp/client](https://github.com/php-mcp/client) — Core PHP implementation for the Model Context Protocol (MCP) Client ☆`58`
- [jdbcx/jdbcx](https://github.com/jdbcx/jdbcx) — JDBC driver for queries across languages, with an optional bridge ☆`33`
- [LeulAria/volt](https://github.com/LeulAria/volt) — AI editor on the VS Code core, with an MCP client ☆`27`
- [rakesh-eltropy/mcp-client](https://github.com/rakesh-eltropy/mcp-client) — REST API and CLI client for MCP with LangChain ☆`49`
- [gcc3/simple-ai-chat](https://github.com/gcc3/simple-ai-chat) — Chat app for LLMs, on the web and in the terminal ☆`16`
- [vincent-pli/mcp-cli-host](https://github.com/vincent-pli/mcp-cli-host) — CLI host that connects a model to external MCP tools ☆`21`
- [shane-kercheval/mcp-client-agent](https://github.com/shane-kercheval/mcp-client-agent) — CLI that uses DSPy to interact with MCP servers. ☆`24`
- [johnrobinsn/askit](https://github.com/johnrobinsn/askit) — LLM Function Calling Library and CLI with Support for MCP Servers ☆`21`
## Marketing & Analytics

- [nowork-studio/notfair-plugin](https://github.com/nowork-studio/notfair-plugin) — SEO and marketing skills for agents ☆`4,138`
- [pipeboard-co/meta-ads-mcp](https://github.com/pipeboard-co/meta-ads-mcp) — Hosted Facebook and Instagram Ads for AI agents ☆`1,362`
- [getopenpost/openpost](https://github.com/getopenpost/openpost) — Create, adapt, schedule and track social posts ☆`899`
- [gomarble-ai/facebook-ads-mcp-server](https://github.com/gomarble-ai/facebook-ads-mcp-server) — Facebook and Instagram Ads management ☆`370`
- [stape-io/google-tag-manager-mcp-server](https://github.com/stape-io/google-tag-manager-mcp-server) — MCP server for Google Tag Manager ☆`246`
- [open-strategy-partners/osp_marketing_tools](https://github.com/open-strategy-partners/osp_marketing_tools) — MCP server for marketing automation tools ☆`274`
- [surendranb/google-analytics-mcp](https://github.com/surendranb/google-analytics-mcp) — Google Analytics 4 data access ☆`244`
- [cnych/seo-mcp](https://github.com/cnych/seo-mcp) — SEO tool based on Ahrefs data ☆`260`
- [gomarble-ai/google-ads-mcp-server](https://github.com/gomarble-ai/google-ads-mcp-server) — Google Ads performance data analysis ☆`147`
- [microsoft/clarity-mcp-server](https://github.com/microsoft/clarity-mcp-server) — Microsoft Clarity integration ☆`139`
- [amekala/ads-mcp](https://github.com/amekala/ads-mcp) — Google, Meta, LinkedIn, and TikTok campaign management ☆`105`
- [mikusnuz/meta-ads-mcp](https://github.com/mikusnuz/meta-ads-mcp) — Facebook and Instagram ad campaigns through the Marketing API ☆`94`
- [bzsasson/screaming-frog-mcp](https://github.com/bzsasson/screaming-frog-mcp) — Run Screaming Frog crawls and read the exports ☆`95`
- [AdsMCP/tiktok-ads-mcp-server](https://github.com/AdsMCP/tiktok-ads-mcp-server) — TikTok Ads Marketing API integration via MCP ☆`54`
- [builtwith/builtwith-mcp](https://github.com/builtwith/builtwith-mcp) — BuiltWith MCP Server ☆`43`
- [AKzar1el/mcp-geo](https://github.com/AKzar1el/mcp-geo) — Track how AI search engines cite a brand ☆`40`
- [gvaibhav/TAM-MCP-Server](https://github.com/gvaibhav/TAM-MCP-Server) — Market sizing and TAM/SAM analysis ☆`36`
- [MarketplaceAdPros/amazon-ads-mcp-server](https://github.com/MarketplaceAdPros/amazon-ads-mcp-server) — MCP Server to interact with Amazon Ads ☆`29`
- [damientilman/mailchimp-mcp-server](https://github.com/damientilman/mailchimp-mcp-server) — Campaigns, audiences and reports in Mailchimp ☆`25`
- [brandu-mos/konquest-meta-ads-mcp](https://github.com/brandu-mos/konquest-meta-ads-mcp) — Create and review Meta ads, with a safety check ☆`44`
- [alexey-pelykh/lhremote](https://github.com/alexey-pelykh/lhremote) — Drive LinkedHelper LinkedIn outreach from an assistant ☆`21`
- [Synter-Media-AI/mcp-server](https://github.com/Synter-Media-AI/mcp-server) — Read many ad platforms, and write to a smaller verified set ☆`21`
- [stape-io/stape-mcp-server](https://github.com/stape-io/stape-mcp-server) — Stape API for Claude, Cursor, and other AI clients ☆`18`
- [Kiran1689/storyblok-mcp-server](https://github.com/Kiran1689/storyblok-mcp-server) — MCP server for Storyblok CMS management ☆`41`
- [rafaelstz/adobe-commerce-dev-mcp](https://github.com/rafaelstz/adobe-commerce-dev-mcp) — Adobe Commerce Dev MCP Server ☆`27`
- [MatiousCorp/google-ad-manager-mcp](https://github.com/MatiousCorp/google-ad-manager-mcp) — Campaigns, orders and creatives in Google Ad Manager ☆`20`
- [jonathan-politzki/smartlead-mcp-server](https://github.com/jonathan-politzki/smartlead-mcp-server) — Smartlead MCP deployment ☆`18`
## Media Processing

### 3D & Animation

- [samuelgursky/davinci-resolve-mcp](https://github.com/samuelgursky/davinci-resolve-mcp) — MCP server integration for DaVinci Resolve Studio ☆`4,044`
- [ATH-MaaS/Pixelle-MCP](https://github.com/ATH-MaaS/Pixelle-MCP) — Multimodal AIGC with ComfyUI + MCP ☆`1,131`
- [diivi/aseprite-mcp](https://github.com/diivi/aseprite-mcp) — MCP server for interacting with the Aseprite API ☆`965`
- [abhiemj/manim-mcp-server](https://github.com/abhiemj/manim-mcp-server) — Manim animation code execution ☆`658`
- [8beeeaaat/touchdesigner-mcp](https://github.com/8beeeaaat/touchdesigner-mcp) — MCP server for TouchDesigner ☆`625`
- [mhyrr/sketchup-mcp](https://github.com/mhyrr/sketchup-mcp) — Sketchup Model Context Protocol ☆`540`
- [dylanroscover/Embody](https://github.com/dylanroscover/Embody) — Inspect and edit a TouchDesigner network ☆`217`
- [PatrickPalmer/MayaMCP](https://github.com/PatrickPalmer/MayaMCP) — Autodesk Maya 3D integration ☆`120`
- [pranav-deshmukh/blender-mcp](https://github.com/pranav-deshmukh/blender-mcp) — Blender 3D modeling integration ☆`98`
- [FishWoWater/trellis_blender](https://github.com/FishWoWater/trellis_blender) — Blender plugin for TRELLIS text-to-3D and image-to-3D ☆`78`
- [wilsonchenghy/ShaderToy-MCP](https://github.com/wilsonchenghy/ShaderToy-MCP) — Create and explore GLSL shaders on ShaderToy ☆`51`
- [BearNetwork-BRNKC/SketchUp-MCP](https://github.com/BearNetwork-BRNKC/SketchUp-MCP) — SketchUp-MCP For AI ☆`28`
- [junmer/mcp-server-lottiefiles](https://github.com/junmer/mcp-server-lottiefiles) — Search and retrieve Lottie animations from LottieFiles ☆`19`
### Audio & Music

- [ahujasid/ableton-mcp](https://github.com/ahujasid/ableton-mcp) — Create tracks, arrange clips and compose in Ableton Live ☆`3,330`
- [varunneal/spotify-mcp](https://github.com/varunneal/spotify-mcp) — MCP to connect your LLM with Spotify. ☆`614`
- [marcelmarais/spotify-mcp-server](https://github.com/marcelmarais/spotify-mcp-server) — Lightweight MCP server for Spotify ☆`504`
- [Simon-Kansara/ableton-live-mcp-server](https://github.com/Simon-Kansara/ableton-live-mcp-server) — Ableton Live OSC control ☆`398`
- [adamjmurray/producer-pal](https://github.com/adamjmurray/producer-pal) — AI music production assistant for Ableton Live ☆`371`
- [tiianhk/MaxMSP-MCP-Server](https://github.com/tiianhk/MaxMSP-MCP-Server) — MCP (Model Context Protocol) Server for Max (Max/MSP/Jitter) ☆`286`
- [rosasynthesiz/flstudio-mcp](https://github.com/rosasynthesiz/flstudio-mcp) — Mixing and arrangement inside FL Studio ☆`136`
- [dschuler36/reaper-mcp-server](https://github.com/dschuler36/reaper-mcp-server) — An MCP Server for interacting with Reaper projects. ☆`135`
- [xDarkzx/Reaper-MCP](https://github.com/xDarkzx/Reaper-MCP) — Composition, mixing and batch edits in REAPER ☆`117`
- [TwelveTake-Studios/reaper-mcp](https://github.com/TwelveTake-Studios/reaper-mcp) — REAPER DAW mixing, mastering, MIDI, and production ☆`104`
- [SkyworkAI/Mureka-mcp](https://github.com/SkyworkAI/Mureka-mcp) — AI lyrics, song, and music generation ☆`123`
- [AceDataCloud/SunoMCP](https://github.com/AceDataCloud/SunoMCP) — Generate Suno music, lyrics and covers through Ace Data Cloud ☆`73`
- [imprvhub/mcp-claude-spotify](https://github.com/imprvhub/mcp-claude-spotify) — Spotify interaction for Claude Desktop ☆`53`
- [vsaez/mcp-spotify-player](https://github.com/vsaez/mcp-spotify-player) — MCP server to manage Spotify from MCP clients ☆`22`
### Image Generation

- [jau123/MeiGen-AI-Design-MCP](https://github.com/jau123/MeiGen-AI-Design-MCP) — Generate images and video from current AI models ☆`1,802`
- [glifxyz/glif-mcp-server](https://github.com/glifxyz/glif-mcp-server) — Hosted tools for generating images, video and audio ☆`218`
- [shinpr/mcp-image](https://github.com/shinpr/mcp-image) — AI image generation with Gemini 3 ☆`190`
- [awkoy/replicate-flux-mcp](https://github.com/awkoy/replicate-flux-mcp) — MCP server for Replicate Flux image and SVG generation ☆`106`
- [GenWaveLLC/svgmaker-mcp](https://github.com/GenWaveLLC/svgmaker-mcp) — MCP server for SVG generation ☆`88`
- [apinetwork/piapi-mcp-server](https://github.com/apinetwork/piapi-mcp-server) — PiAPI media: Midjourney, Flux, Kling ☆`76`
- [Flyworks-AI/flyworks-mcp](https://github.com/Flyworks-AI/flyworks-mcp) — Fast and free zeroshot lipsync MCP server ☆`94`
- [hamflx/imagen3-mcp](https://github.com/hamflx/imagen3-mcp) — MCP server for Google Imagen 3 image generation ☆`78`
- [WaveSpeedAI/mcp-server](https://github.com/WaveSpeedAI/mcp-server) — Image and video generation with WaveSpeed AI ☆`36`
- [MohamedAbdallah-14/prompt-to-asset](https://github.com/MohamedAbdallah-14/prompt-to-asset) — Images from 30+ models through one API ☆`24`
- [InhiblabCore/mcp-image-compression](https://github.com/InhiblabCore/mcp-image-compression) — High-performance image compression service ☆`34`
- [zxkane/mcp-server-amazon-bedrock](https://github.com/zxkane/mcp-server-amazon-bedrock) — Amazon Bedrock Nova Canvas image generation ☆`25`
### Image Processing

- [openclaw/Peekaboo](https://github.com/openclaw/Peekaboo) — macOS screenshot and window capture MCP server ☆`5,470`
- [BeatAPI/BeatDesign](https://github.com/BeatAPI/BeatDesign) — Local canvas and timeline any MCP agent can draw on ☆`341`
- [sunriseapps/imagesorcery-mcp](https://github.com/sunriseapps/imagesorcery-mcp) — Image processing operations ☆`338`
- [royshil/obs-mcp](https://github.com/royshil/obs-mcp) — An MCP server for OBS ☆`161`
- [IDEA-Research/DINO-X-MCP](https://github.com/IDEA-Research/DINO-X-MCP) — MCP server for DINO-X vision model ☆`113`
- [drolosoft/immich-photo-manager](https://github.com/drolosoft/immich-photo-manager) — Search and organize a self-hosted Immich photo library ☆`62`
- [upnorthmedia/ScreenshotMCP](https://github.com/upnorthmedia/ScreenshotMCP) — Website screenshot capture and optimization ☆`62`
- [groundlight/mcp-vision](https://github.com/groundlight/mcp-vision) — Computer vision models as MCP servers ☆`64`
- [screenshotone/mcp](https://github.com/screenshotone/mcp) — A CLI version of an MCP server for the ScreenshotOne API ☆`38`
- [spencerhhubert/illustrator-mcp-server](https://github.com/spencerhhubert/illustrator-mcp-server) — mcp server to run scripts on adobe illustrator ☆`57`
- [a-y-ibrahim/after-effects-mcp](https://github.com/a-y-ibrahim/after-effects-mcp) — Run scripts, render and inspect After Effects projects ☆`29`
- [saury1120/pdf-mcp](https://github.com/saury1120/pdf-mcp) — MCP server for analyzing PDF documents ☆`51`
- [stass/exif-mcp](https://github.com/stass/exif-mcp) — MCP server to extract image metadata (EXIF, XMP, etc) ☆`40`
- [MoussaabBadla/code-screenshot-mcp](https://github.com/MoussaabBadla/code-screenshot-mcp) — Generate code screenshots ☆`44`
- [editmamei/editmamei](https://github.com/editmamei/editmamei) — Edit photos in Photoshop with natural-language instructions ☆`18`
- [torrentclaw/torrentclaw-mcp](https://github.com/torrentclaw/torrentclaw-mcp) — The official MCP by TorrentClaw.com ☆`17`
- [magarcia/mcp-server-giphy](https://github.com/magarcia/mcp-server-giphy) — Giphy GIF integration ☆`36`
- [kazuph/mcp-screenshot](https://github.com/kazuph/mcp-screenshot) — Repository for MCP screenshot functionality ☆`23`
- [flowy11/imagician](https://github.com/flowy11/imagician) — A MCP server for image edition ☆`19`
- [bmorphism/say-mcp-server](https://github.com/bmorphism/say-mcp-server) — MCP server for macOS text-to-speech functionality ☆`20`
### Media Services

- [garylab/pexels-mcp-server](https://github.com/garylab/pexels-mcp-server) — A Pexels MCP Server for Images and Videos searching ☆`29`
### Video

- [ronak-create/FableCut](https://github.com/ronak-create/FableCut) — Browser video editor an agent can drive from a JSON timeline ☆`787`
- [eat-pray-ai/yutu](https://github.com/eat-pray-ai/yutu) — CLI, MCP server, and AI agent to automate YouTube workflows ☆`722`
- [ZubeidHendricks/youtube-mcp-server](https://github.com/ZubeidHendricks/youtube-mcp-server) — YouTube API and video management ☆`597`
- [kimtaeyoon83/mcp-server-youtube-transcript](https://github.com/kimtaeyoon83/mcp-server-youtube-transcript) — YouTube video transcript downloader ☆`603`
- [anaisbetts/mcp-youtube](https://github.com/anaisbetts/mcp-youtube) — A Model-Context Protocol Server for YouTube ☆`552`
- [ffroliva/gflow-cli](https://github.com/ffroliva/gflow-cli) — Generate Veo video and Imagen images from Google Flow ☆`377`
- [WeftCut/WeftCut](https://github.com/WeftCut/WeftCut) — Video editor whose timeline any MCP client can drive ☆`326`
- [guaardvark/guaardvark](https://github.com/guaardvark/guaardvark) — Self-hosted RAG, browser agents and LoRA training ☆`312`
- [burningion/video-editing-mcp](https://github.com/burningion/video-editing-mcp) — MCP Interface for Video Jungle ☆`296`
- [KyaniteLabs/kinocut](https://github.com/KyaniteLabs/kinocut) — Guardrailed video editing with FFmpeg and Hyperframes ☆`262`
- [Cassette-Editor/oh-my-cassette](https://github.com/Cassette-Editor/oh-my-cassette) — Pocket AI co-editor and MCP server for video montage ☆`217`
- [muxinc/mux-ts](https://github.com/muxinc/mux-ts) — Mux Video and Data API wrapper ☆`182`
- [DareDev256/fcp-mcp-server](https://github.com/DareDev256/fcp-mcp-server) — Read and edit Final Cut Pro timelines from XML ☆`144`
- [video-creator/ffmpeg-mcp](https://github.com/video-creator/ffmpeg-mcp) — Search, cut, join and overlay local video with ffmpeg ☆`153`
- [guimatheus92/mcp-video-analyzer](https://github.com/guimatheus92/mcp-video-analyzer) — Transcripts, frames and OCR from a video ☆`120`
- [stabgan/openrouter-mcp-multimodal](https://github.com/stabgan/openrouter-mcp-multimodal) — Chat and media generation on OpenRouter ☆`102`
- [Laksh-star/mcp-server-tmdb](https://github.com/Laksh-star/mcp-server-tmdb) — MCP Server with TMDB ☆`77`
- [tan-yong-sheng/ai-vision-mcp](https://github.com/tan-yong-sheng/ai-vision-mcp) — Image and video analysis capabilities ☆`80`
- [runapi-ai/mcp](https://github.com/runapi-ai/mcp) — Model list, prices, media tasks and balance on RunAPI ☆`56`
- [luminarylane/fal-mcp-server](https://github.com/luminarylane/fal-mcp-server) — Fal.ai image, video, music generation ☆`61`
- [nabid-pf/youtube-video-summarizer-mcp](https://github.com/nabid-pf/youtube-video-summarizer-mcp) — YouTube video captions and summarization ☆`62`
- [arcmira/mcp](https://github.com/arcmira/mcp) — YouTube transcript search and monitoring for your AI: exact quotes, full transcripts and speakers. ☆`34`
- [video-db/agent-toolkit](https://github.com/video-db/agent-toolkit) — MCP toolkit for video database operations ☆`49`
- [marcindulak/stt-mcp-server-linux](https://github.com/marcindulak/stt-mcp-server-linux) — Local speech-to-text for Tmux on Linux ☆`24`
- [Aditya2755/video-edit-mcp](https://github.com/Aditya2755/video-edit-mcp) — Trim, merge and convert video and audio, including YouTube ☆`30`
- [maoxiaoke/mcp-media-processor](https://github.com/maoxiaoke/mcp-media-processor) — Process video and images from Node.js ☆`29`
- [omergocmen/json2video-mcp-server](https://github.com/omergocmen/json2video-mcp-server) — json2video API integration ☆`27`
- [sinjab/mcp_youtube_extract](https://github.com/sinjab/mcp_youtube_extract) — YouTube clip information extraction ☆`19`
- [TSavo/creatify-mcp](https://github.com/TSavo/creatify-mcp) — MCP server for AI video generation ☆`23`
- [13rac1/videocapture-mcp](https://github.com/13rac1/videocapture-mcp) — MCP server to capture images from webcam or video source ☆`20`
- [ananddtyagi/gif-creator-mcp](https://github.com/ananddtyagi/gif-creator-mcp) — Turn a video into a GIF ☆`18`
## Monitoring & Observability

- [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana) — MCP server for Grafana ☆`3,658`
- [getsentry/toolkit](https://github.com/getsentry/toolkit) — Agentic tooling for Sentry ☆`961`
- [0xKoda/WireMCP](https://github.com/0xKoda/WireMCP) — MCP server for Wireshark and tshark live packet analysis ☆`603`
- [Higangssh/homebutler](https://github.com/Higangssh/homebutler) — Tell you what changed on a server, without an agent on the host ☆`321`
- [mpeirone/zabbix-mcp-server](https://github.com/mpeirone/zabbix-mcp-server) — MCP server for Zabbix monitoring with 40+ tools ☆`263`
- [initMAX/zabbix-mcp-server](https://github.com/initMAX/zabbix-mcp-server) — The Zabbix API, including alerts and PDF reports ☆`247`
- [VictoriaMetrics/mcp-victoriametrics](https://github.com/VictoriaMetrics/mcp-victoriametrics) — VictoriaMetrics monitoring integration ☆`243`
- [comet-ml/opik-mcp](https://github.com/comet-ml/opik-mcp) — MCP server for Opik LLM evaluation platform ☆`226`
- [aliyun/alibabacloud-observability-mcp-server](https://github.com/aliyun/alibabacloud-observability-mcp-server) — Alibaba Cloud logs and app monitoring ☆`171`
- [langfuse/mcp-server-langfuse](https://github.com/langfuse/mcp-server-langfuse) — MCP server for Langfuse LLM observability ☆`176`
- [pydantic/logfire-mcp](https://github.com/pydantic/logfire-mcp) — The Logfire MCP Server is here! ☆`162`
- [prometheus/prometheus-mcp](https://github.com/prometheus/prometheus-mcp) — MCP server for LLMs to interact with Prometheus ☆`138`
- [Necmttn/ax](https://github.com/Necmttn/ax) — Local observability for agent sessions, tools, and costs ☆`123`
- [avivsinai/langfuse-mcp](https://github.com/avivsinai/langfuse-mcp) — Query Langfuse traces for debugging ☆`112`
- [ruslanlap/pagespeed-insights-mcp](https://github.com/ruslanlap/pagespeed-insights-mcp) — PageSpeed Insights and Chrome UX Report scores ☆`80`
- [seekrays/mcp-monitor](https://github.com/seekrays/mcp-monitor) — MCP server monitoring tool ☆`91`
- [last9/last9-mcp-server](https://github.com/last9/last9-mcp-server) — Last9 MCP Server ☆`63`
- [8bitgentleman/activitywatch-mcp-server](https://github.com/8bitgentleman/activitywatch-mcp-server) — Read ActivityWatch time-tracking data ☆`74`
- [mcpcap/mcpcap](https://github.com/mcpcap/mcpcap) — Network analysis for the AI age ☆`54`
- [andreisirbu91-lab/MCPSpend](https://github.com/andreisirbu91-lab/MCPSpend) — Attribute MCP tool-call cost by tool, project and customer ☆`55`
- [GeLi2001/datadog-mcp-server](https://github.com/GeLi2001/datadog-mcp-server) — MCP server interacts with the official Datadog API ☆`70`
- [mhajder/librenms-mcp](https://github.com/mhajder/librenms-mcp) — Devices, alerts and graphs in LibreNMS ☆`42`
- [metoro-io/metoro-mcp-server](https://github.com/metoro-io/metoro-mcp-server) — Metoro MCP Server ☆`51`
- [RedHatInsights/insights-mcp](https://github.com/RedHatInsights/insights-mcp) — Red Hat Insights AI connection ☆`25`
- [fclairamb/solidping](https://github.com/fclairamb/solidping) — Self-hosted uptime checks, incidents and status pages ☆`33`
- [MindscapeHQ/mcp-server-raygun](https://github.com/MindscapeHQ/mcp-server-raygun) — Raygun error investigation for AI ☆`31`
- [phuryn/staygreen](https://github.com/phuryn/staygreen) — Uptime and incident monitoring for apps built with agents ☆`32`
- [inspektor-gadget/ig-mcp-server](https://github.com/inspektor-gadget/ig-mcp-server) — Container and Kubernetes debugging with AI ☆`28`
- [mottibec/otelcol-mcp](https://github.com/mottibec/otelcol-mcp) — The OTEL MCP Server ☆`52`
- [ntk148v/alertmanager-mcp-server](https://github.com/ntk148v/alertmanager-mcp-server) — MCP server for Prometheus Alertmanager integration ☆`25`
- [agentkitai/agentlens](https://github.com/agentkitai/agentlens) — Tamper-evident audit log and dashboard for agent events ☆`25`
- [gologinapp/gologin-mcp](https://github.com/gologinapp/gologin-mcp) — Manage GoLogin browser profiles, proxies, and fingerprints ☆`24`
- [VictoriaMetrics/mcp-victoriatraces](https://github.com/VictoriaMetrics/mcp-victoriatraces) — Query traces stored in VictoriaTraces ☆`19`
- [GeiserX/genieacs-mcp](https://github.com/GeiserX/genieacs-mcp) — MCP Server for GenieACS written in Go ☆`19`
- [emicklei/mcp-log-proxy](https://github.com/emicklei/mcp-log-proxy) — a web logging proxy for MCP client-server communication ☆`32`
- [tumf/grafana-loki-mcp](https://github.com/tumf/grafana-loki-mcp) — Grafana Loki MCP Repository ☆`29`
- [CaesarYangs/prometheus_mcp_server](https://github.com/CaesarYangs/prometheus_mcp_server) — Query and inspect Prometheus ☆`33`
- [tgeselle/bugsnag-mcp](https://github.com/tgeselle/bugsnag-mcp) — MCP server for Bugsnag error monitoring ☆`25`
- [Pratyay/mac-monitor-mcp](https://github.com/Pratyay/mac-monitor-mcp) — MCP server for macOS system monitoring ☆`23`
- [inventer-dev/mcp-internet-speed-test](https://github.com/inventer-dev/mcp-internet-speed-test) — The MCP Internet Speed Test is a specialized Model Context Protocol (MCP) server that enables AI models and agents to perform internet speed measurements. ☆`16`
- [alilxxey/openobserve-community-mcp](https://github.com/alilxxey/openobserve-community-mcp) — Read-only logs, traces and dashboards in OpenObserve ☆`16`
- [iLert/mcp-ilert](https://github.com/iLert/mcp-ilert) — MCP server for ilert ☆`17`
## Productivity

### Atlassian

- [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) — MCP server for Atlassian tools (Confluence, Jira) ☆`6,112`
- [atlassian/atlassian-mcp-server](https://github.com/atlassian/atlassian-mcp-server) — Official server for Jira, Confluence and Bitbucket ☆`1,151`
- [aashari/mcp-server-atlassian-bitbucket](https://github.com/aashari/mcp-server-atlassian-bitbucket) — Atlassian Bitbucket repositories and PRs ☆`163`
- [nguyenvanduocit/jira-mcp](https://github.com/nguyenvanduocit/jira-mcp) — Jira issues and sprints via Go MCP ☆`96`
- [aashari/mcp-server-atlassian-jira](https://github.com/aashari/mcp-server-atlassian-jira) — Atlassian Jira projects, issues and sprints ☆`78`
- [aashari/mcp-server-atlassian-confluence](https://github.com/aashari/mcp-server-atlassian-confluence) — Atlassian Confluence spaces and pages ☆`62`
- [spranab/saga-mcp](https://github.com/spranab/saga-mcp) — SQLite tracker for projects, epics, tasks and dependencies ☆`42`
- [phuc-nt/mcp-atlassian-server](https://github.com/phuc-nt/mcp-atlassian-server) — Jira and Confluence integration ☆`52`
- [athapong/aio-mcp](https://github.com/athapong/aio-mcp) — Search, RAG, GitLab, Jira, Confluence and YouTube in one server ☆`36`
- [rahulthedevil/Jira-Context-MCP](https://github.com/rahulthedevil/Jira-Context-MCP) — Jira tickets info for AI coding agents ☆`26`
- [KS-GEN-AI/jira-mcp-server](https://github.com/KS-GEN-AI/jira-mcp-server) — A test of jira mcp server ☆`26`
### Collaboration

- [CrossPaste/crosspaste-desktop](https://github.com/CrossPaste/crosspaste-desktop) — Encrypted clipboard sync for Mac, Windows and Linux ☆`2,693`
- [erpipe-org/mcp-odoo](https://github.com/erpipe-org/mcp-odoo) — Odoo access for agents, with writes that must be approved ☆`428`
- [Orkas-AI/Orkas-VideoStudio](https://github.com/Orkas-AI/Orkas-VideoStudio) — Describe a video; the agent writes and renders it ☆`346`
- [workopia/workopia-mcp](https://github.com/workopia/workopia-mcp) — Job search, a resume builder and career advice ☆`312`
- [BrightbeamAI/chap](https://github.com/BrightbeamAI/chap) — Approvals, handoffs and evidence for work shared with agents ☆`122`
- [evalstate/mcp-miro](https://github.com/evalstate/mcp-miro) — MCP server for Miro whiteboard manipulation and sticky creation ☆`113`
- [hiromitsusasaki/raindrop-io-mcp-server](https://github.com/hiromitsusasaki/raindrop-io-mcp-server) — Raindrop.io bookmark management ☆`74`
- [k-jarzyna/mcp-miro](https://github.com/k-jarzyna/mcp-miro) — Miro integration for Model Context Protocol ☆`65`
- [dearlordylord/huly-mcp](https://github.com/dearlordylord/huly-mcp) — Work items and documents on the Huly platform ☆`64`
- [kintone/mcp-server](https://github.com/kintone/mcp-server) — kintone official MCP server ☆`59`
- [orellazri/coda-mcp](https://github.com/orellazri/coda-mcp) — MCP Server for Coda ☆`62`
- [tale-project/tale](https://github.com/tale-project/tale) — Org knowledge plus authoring of automations, tests and deploys ☆`43`
- [6figr-com/jobgpt-mcp-server](https://github.com/6figr-com/jobgpt-mcp-server) — Search jobs, tailor resumes and track applications ☆`26`
- [lexmount/artifact-site](https://github.com/lexmount/artifact-site) — Host AI-generated pages and documents as versioned links ☆`27`
- [OurThinkTank/founders-os](https://github.com/OurThinkTank/founders-os) — CRM, tasks, finances and memory for founders ☆`21`
- [winfunc/asterisk-mcp-server](https://github.com/winfunc/asterisk-mcp-server) — Asterisk Model Context Protocol (MCP) server. ☆`34`
- [srikanth-paladugula/mcp-dynamics365-server](https://github.com/srikanth-paladugula/mcp-dynamics365-server) — MCP Server for Microsoft Dynamics 365 ☆`22`
### Documents

- [zcaceres/markdownify-mcp](https://github.com/zcaceres/markdownify-mcp) — Convert almost anything to Markdown ☆`3,004`
- [vivekVells/mcp-pandoc](https://github.com/vivekVells/mcp-pandoc) — MCP server for document format conversion using pandoc. ☆`587`
- [onebirdrocks/ebook-mcp](https://github.com/onebirdrocks/ebook-mcp) — MCP server for ebook processing ☆`397`
- [baruchiro/paperless-mcp](https://github.com/baruchiro/paperless-mcp) — MCP server for Paperless-NGX document management ☆`151`
- [vgnshiyer/apple-books-mcp](https://github.com/vgnshiyer/apple-books-mcp) — Apple Books MCP Server ☆`64`
- [Unstructured-IO/UNS-MCP](https://github.com/Unstructured-IO/UNS-MCP) — MCP server for Unstructured document processing ☆`43`
- [esignaturescom/mcp-server-esignatures](https://github.com/esignaturescom/mcp-server-esignatures) — eSignatures.com document signing ☆`40`
- [thechandanbhagat/cv-forge](https://github.com/thechandanbhagat/cv-forge) — ATS-friendly CVs, cover letters, and job-tailored emails ☆`30`
- [danielkennedy1/pdf-tools-mcp](https://github.com/danielkennedy1/pdf-tools-mcp) — MCP server for PDF manipulation (merge, extract, snippets) ☆`32`
- [gpetraroli/mcp_pdf_reader](https://github.com/gpetraroli/mcp_pdf_reader) — An MCP server to extraxt/search text from pdf ☆`32`
- [intsig-textin/textin-mcp](https://github.com/intsig-textin/textin-mcp) — OCR and document-to-Markdown conversion ☆`29`
- [Sohaib-2/pdf-mcp-server](https://github.com/Sohaib-2/pdf-mcp-server) — Merge, split, encrypt and optimize PDFs ☆`16`
### Google Workspace

- [taylorwilsdon/google_workspace_mcp](https://github.com/taylorwilsdon/google_workspace_mcp) — MCP server for Google Workspace integration ☆`3,501`
- [MarkusPfundstein/mcp-gsuite](https://github.com/MarkusPfundstein/mcp-gsuite) — MCP Server to interact with Google Gsuite prodcuts ☆`491`
- [felores/gdrive-mcp-server](https://github.com/felores/gdrive-mcp-server) — Efficient implementation of the Google Drive MCP server ☆`72`
- [v-3/google-calendar](https://github.com/v-3/google-calendar) — Google Calendar events and scheduling ☆`72`
- [baryhuang/mcp-headless-gmail](https://github.com/baryhuang/mcp-headless-gmail) — Gmail without local credentials ☆`55`
- [giuseppe-coco/Google-Workspace-MCP-Server](https://github.com/giuseppe-coco/Google-Workspace-MCP-Server) — Gmail, Calendar, and Drive integration ☆`30`
- [vakharwalad23/google-mcp](https://github.com/vakharwalad23/google-mcp) — Gmail, Calendar, and other Google workspace tools ☆`21`
### Helpdesk & Support

- [echelon-ai-labs/servicenow-mcp](https://github.com/echelon-ai-labs/servicenow-mcp) — MCP Server for ServiceNow ☆`304`
- [effytech/freshdesk_mcp](https://github.com/effytech/freshdesk_mcp) — Freshdesk support ticket integration ☆`71`
- [modesty/fluent-mcp](https://github.com/modesty/fluent-mcp) — MCP server and AI skill suite for Fluent (ServiceNow SDK) ☆`32`
- [quickchatai/quickchat-ai-mcp](https://github.com/quickchatai/quickchat-ai-mcp) — The Quickchat AI MCP server ☆`24`
### Learning & Flashcards

- [ankimcp/anki-mcp-server](https://github.com/ankimcp/anki-mcp-server) — MCP server for Anki spaced repetition flashcards ☆`551`
- [scorzeth/anki-mcp-server](https://github.com/scorzeth/anki-mcp-server) — An MCP server for Anki ☆`185`
- [jinzcdev/leetcode-mcp-server](https://github.com/jinzcdev/leetcode-mcp-server) — MCP server for LeetCode problems and solutions ☆`158`
- [nietus/anki-mcp](https://github.com/nietus/anki-mcp) — Quiz, retention and leeches in Anki, through AnkiConnect ☆`44`
- [rember/rember-mcp](https://github.com/rember/rember-mcp) — A Model Context Protocol (MCP) server for Rember. ☆`63`
- [spacholski1225/anki-connect-mcp](https://github.com/spacholski1225/anki-connect-mcp) — MCP implementation for Anki Web ☆`27`
- [doggybee/mcp-server-leetcode](https://github.com/doggybee/mcp-server-leetcode) — MCP server for LeetCode coding challenges ☆`44`
### Microsoft 365

- [haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server) — Excel file manipulation ☆`4,290`
- [Softeria/ms-365-mcp-server](https://github.com/Softeria/ms-365-mcp-server) — Microsoft 365 and Office via Graph API ☆`1,126`
- [sbroenne/mcp-server-excel](https://github.com/sbroenne/mcp-server-excel) — Excel MCP Server - 23 tools for AI-powered automation ☆`883`
- [InditexTech/mcp-teams-server](https://github.com/InditexTech/mcp-teams-server) — MCP server for Microsoft Teams integration ☆`470`
- [merill/lokka](https://github.com/merill/lokka) — MCP for Microsoft 365 and Graph ☆`310`
- [pnp/cli-microsoft365-mcp-server](https://github.com/pnp/cli-microsoft365-mcp-server) — Manage Microsoft 365 using MCP server ☆`135`
- [ilia-sokolov/OfficeAgent.NET](https://github.com/ilia-sokolov/OfficeAgent.NET) — Word, PowerPoint and Excel automation for .NET ☆`28`
- [Norcim133/OutlookMCPServer](https://github.com/Norcim133/OutlookMCPServer) — MCP Server for msgraph - mail, calendar, files ☆`16`
### Note-taking & Docs

- [RafalWilinski/mcp-apple-notes](https://github.com/RafalWilinski/mcp-apple-notes) — RAG over Apple Notes for Claude ☆`419`
- [vasylenko/bear-notes-mcp](https://github.com/vasylenko/bear-notes-mcp) — Notes in the Bear app ☆`207`
- [lostintangent/gistpad-mcp](https://github.com/lostintangent/gistpad-mcp) — Personal knowledge and daily notes management ☆`207`
- [Vortiago/mcp-outline](https://github.com/Vortiago/mcp-outline) — AI assistants with Outline docs ☆`159`
- [entanglr/zettelkasten-mcp](https://github.com/entanglr/zettelkasten-mcp) — MCP server implementing Zettelkasten knowledge management ☆`168`
- [gornskew/cyborg-whisperer](https://github.com/gornskew/cyborg-whisperer) — Manage Lisply lisp-speaking backends ☆`54`
- [2slides/mcp-2slides](https://github.com/2slides/mcp-2slides) — MCP Server for 2slides - AI agent for PPT generation ☆`34`
- [koruworks/mono](https://github.com/koruworks/mono) — Local MCP server for Koru, a local-first notes, docs and files app ☆`35`
- [ONLYOFFICE/docspace-mcp](https://github.com/ONLYOFFICE/docspace-mcp) — DocSpace MCP Server ☆`31`
- [pinto-notes/pinto-notes](https://github.com/pinto-notes/pinto-notes) — Encrypted notes on iPhone and Mac that an assistant can edit ☆`32`
- [Piotr1215/mcp-obsidian](https://github.com/Piotr1215/mcp-obsidian) — simple mcp server for interacting with local obsidian notes ☆`24`
- [akseyh/bear-mcp-server](https://github.com/akseyh/bear-mcp-server) — MCP Server integration for Bear note app ☆`45`
- [joshylchen/zettelkasten](https://github.com/joshylchen/zettelkasten) — Zettelkasten notes with search, links, CLI, API, and web ☆`40`
- [danield137/mcp-workflowy](https://github.com/danield137/mcp-workflowy) — An MCP server for workflowy ☆`29`
- [Harry-027/JotDown](https://github.com/Harry-027/JotDown) — An MCP Server in Rust for creating Notion pages & mdBooks with LLMs ☆`23`
- [louis030195/easy-obsidian-mcp](https://github.com/louis030195/easy-obsidian-mcp) — wire your brain to AGI through the best obsidian MCP ☆`17`
### Notion

- [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server) — Official Notion MCP Server ☆`4,704`
- [suekou/mcp-notion-server](https://github.com/suekou/mcp-notion-server) — MCP server for Notion API with Markdown conversion ☆`925`
- [danhilse/notion_mcp](https://github.com/danhilse/notion_mcp) — Notion integration with advanced formatting ☆`209`
- [awkoy/notion-mcp-server](https://github.com/awkoy/notion-mcp-server) — Notion pages, databases, comments and files ☆`180`
- [v-3/notion-server](https://github.com/v-3/notion-server) — Search, read and create Notion pages ☆`118`
- [evergreen-it-dev/folio](https://github.com/evergreen-it-dev/folio) — Git-backed team wiki with tables, whiteboards and live editing ☆`82`
- [Grey-Iris/easy-notion-mcp](https://github.com/Grey-Iris/easy-notion-mcp) — Notion access that returns markdown and uses fewer tokens ☆`55`
- [Badhansen/notion-mcp](https://github.com/Badhansen/notion-mcp) — Notion workspace management ☆`31`
- [pbohannon/notion-api-mcp](https://github.com/pbohannon/notion-api-mcp) — Expose Notion to a model from Python ☆`28`
- [Ejb503/systemprompt-mcp-notion](https://github.com/Ejb503/systemprompt-mcp-notion) — Read and update Notion from an agent workflow ☆`26`
- [orbit-logistics/notion-mcp-server](https://github.com/orbit-logistics/notion-mcp-server) — MCP server for Notion integration ☆`21`
### Obsidian

- [MarkusPfundstein/mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) — Obsidian integration via REST API plugin ☆`4,530`
- [bitbonsai/mcpvault](https://github.com/bitbonsai/mcpvault) — Lightweight Obsidian vault access ☆`1,722`
- [StevenStavrakis/obsidian-mcp](https://github.com/StevenStavrakis/obsidian-mcp) — A simple MCP server for Obsidian ☆`750`
- [cyanheads/obsidian-mcp-server](https://github.com/cyanheads/obsidian-mcp-server) — Read, search and edit Obsidian notes ☆`702`
- [WenyuChiou/research-hub](https://github.com/WenyuChiou/research-hub) — Research workspace over Zotero, Obsidian and NotebookLM ☆`67`
- [aliasunder/vault-cortex](https://github.com/aliasunder/vault-cortex) — Obsidian server with hybrid search, tasks and OAuth ☆`36`
- [oomkapwn/enquire-mcp](https://github.com/oomkapwn/enquire-mcp) — Read-only Obsidian search that cites notes and watches freshness ☆`34`
- [shaqmughal/seekstone](https://github.com/shaqmughal/seekstone) — Search Obsidian from disk, with no plugin running ☆`35`
- [rps321321/obsidian-mcp-pro](https://github.com/rps321321/obsidian-mcp-pro) — Search, tags, links and canvas in an Obsidian vault ☆`34`
- [Semiotronika/NOUZ-MCP](https://github.com/Semiotronika/NOUZ-MCP) — Local semantic graph of Markdown and Obsidian notes ☆`24`
- [rwnalds/engram](https://github.com/rwnalds/engram) — Shared memory in a git-backed markdown vault ☆`21`
- [maxkuminov/obsidian-mcp](https://github.com/maxkuminov/obsidian-mcp) — Self-hosted Obsidian search, graph and note editing, with OAuth ☆`18`
- [smith-and-web/obsidian-mcp-server](https://github.com/smith-and-web/obsidian-mcp-server) — Read, write, search and organize an Obsidian vault ☆`19`
- [aka-kika/kika-obsidian-mcp](https://github.com/aka-kika/kika-obsidian-mcp) — Local Obsidian access, including Bases, with no plugin ☆`18`
- [renezander030/agentic-task-system](https://github.com/renezander030/agentic-task-system) — Tasks over TickTick, Notion, GitHub and Obsidian ☆`17`
- [junnnnnw00/obsidian-everywhere](https://github.com/junnnnnw00/obsidian-everywhere) — Obsidian graph and search, with guarded remote edits ☆`16`
- [anpigon/mcp-server-obsidian-omnisearch](https://github.com/anpigon/mcp-server-obsidian-omnisearch) — Search Obsidian through the Omnisearch plugin ☆`30`
### Project Management

- [mondaycom/mcp](https://github.com/mondaycom/mcp) — AI agents with secure data access ☆`437`
- [makeplane/plane-mcp-server](https://github.com/makeplane/plane-mcp-server) — Plane's Official Model Context Protocol Server ☆`358`
- [jerhadf/linear-mcp-server](https://github.com/jerhadf/linear-mcp-server) — MCP server for Linear issue tracking ☆`346`
- [taskade/mcp](https://github.com/taskade/mcp) — MCP server for Taskade project management ☆`169`
- [tacticlaunch/mcp-linear](https://github.com/tacticlaunch/mcp-linear) — MCP server for Linear project management ☆`150`
- [roychri/mcp-server-asana](https://github.com/roychri/mcp-server-asana) — MCP server for Asana task and project management ☆`149`
- [its-dart/dart-mcp-server](https://github.com/its-dart/dart-mcp-server) — Dart AI Model Context Protocol (MCP) server ☆`128`
- [aikts/yandex-tracker-mcp](https://github.com/aikts/yandex-tracker-mcp) — Yandex Tracker MCP Server with OAuth2 support ☆`123`
- [feuerdev/keep-mcp](https://github.com/feuerdev/keep-mcp) — MCP server for Google Keep ☆`113`
- [georgeantonopoulos/Basecamp-MCP-Server](https://github.com/georgeantonopoulos/Basecamp-MCP-Server) — Basecamp 3+ project management ☆`101`
- [tonyzorin/youtrack-mcp](https://github.com/tonyzorin/youtrack-mcp) — YouTrack server, ARM64 and AMD64 ☆`99`
- [taazkareem/clickup-mcp-server](https://github.com/taazkareem/clickup-mcp-server) — ClickUp MCP Server - project management with AI ☆`53`
- [m0xai/trello-mcp-server](https://github.com/m0xai/trello-mcp-server) — A simple yet powerful MCP server for Trello. ☆`54`
- [dkships/pm-copilot](https://github.com/dkships/pm-copilot) — Cluster support tickets and requests to see what to build ☆`30`
- [Teamwork/mcp](https://github.com/Teamwork/mcp) — Teamwork.com MCP server ☆`28`
- [EduBase/MCP](https://github.com/EduBase/MCP) — MCP server for EduBase e-learning platform ☆`28`
- [kelvin6365/plane-mcp-server](https://github.com/kelvin6365/plane-mcp-server) — MCP server for Plane.so project management ☆`40`
- [kocakli/Trello-Desktop-MCP](https://github.com/kocakli/Trello-Desktop-MCP) — Trello integration for Claude Desktop via MCP ☆`38`
- [TylerIlunga/procore-mcp-server](https://github.com/TylerIlunga/procore-mcp-server) — The Procore REST API ☆`18`
- [devemberx/mcp-server-polarion](https://github.com/devemberx/mcp-server-polarion) — Documents, work items and test runs in Polarion ALM ☆`17`
- [bivex/kanboard-mcp](https://github.com/bivex/kanboard-mcp) — MCP server for Kanboard project management integration ☆`29`
- [Prat011/mcp-server-monday](https://github.com/Prat011/mcp-server-monday) — MCP Server to interact with Monday.com boards and items ☆`34`
- [khaoss85/mcp-orchestro](https://github.com/khaoss85/mcp-orchestro) — Task breakdown, dependencies, and progress for AI teams ☆`16`
### Tasks & Calendar

- [screenpipe/screenpipe](https://github.com/screenpipe/screenpipe) — Search text and audio captured from the screen ☆`22,343`
- [nspady/google-calendar-mcp](https://github.com/nspady/google-calendar-mcp) — MCP integration for Google Calendar to manage events. ☆`1,215`
- [Doist/todoist-mcp](https://github.com/Doist/todoist-mcp) — Todoist tools for AI agents ☆`563`
- [abhiz123/todoist-mcp-server](https://github.com/abhiz123/todoist-mcp-server) — Todoist natural language task management ☆`392`
- [Omar-V2/mcp-ical](https://github.com/Omar-V2/mcp-ical) — Interact with MacOS Calendar ☆`333`
- [zcaceres/gtasks-mcp](https://github.com/zcaceres/gtasks-mcp) — A Google Tasks Model Context Protocol Server for Claude ☆`176`
- [dominik1001/caldav-mcp](https://github.com/dominik1001/caldav-mcp) — CalDAV calendar sync ☆`111`
- [alexarevalo9/ticktick-mcp-server](https://github.com/alexarevalo9/ticktick-mcp-server) — TickTick task management ☆`73`
- [takumi0706/google-calendar-mcp](https://github.com/takumi0706/google-calendar-mcp) — Google Calendar for Claude Desktop ☆`59`
- [arpitbatra123/mcp-googletasks](https://github.com/arpitbatra123/mcp-googletasks) — MCP server for Google Tasks management ☆`51`
- [stanislavlysenko0912/todoist-mcp-server](https://github.com/stanislavlysenko0912/todoist-mcp-server) — Todoist Rest API and Sync API ☆`63`
- [jen6/ticktick-mcp](https://github.com/jen6/ticktick-mcp) — TickTick task management with filtering ☆`67`
- [2nd1st/open-mcp-apps](https://github.com/2nd1st/open-mcp-apps) — Interactive MCP apps whose data outlives the conversation ☆`36`
- [flesler/mcp-tasks](https://github.com/flesler/mcp-tasks) — Efficient task management with views ☆`47`
- [awwaiid/mcp-server-taskwarrior](https://github.com/awwaiid/mcp-server-taskwarrior) — MCP Server for TaskWarrior! ☆`51`
- [urbanogardun/things3-mcp](https://github.com/urbanogardun/things3-mcp) — MCP server for Things3 integration on macOS ☆`25`
- [jbrinkman/valkey-ai-tasks](https://github.com/jbrinkman/valkey-ai-tasks) — MCP server for task management with Valkey persistence ☆`25`
- [hichana/goalstory-mcp](https://github.com/hichana/goalstory-mcp) — Goal tracking with AI-powered storytelling ☆`18`
- [Danielpeter-99/calcom-mcp](https://github.com/Danielpeter-99/calcom-mcp) — Cal.com event types, bookings, and schedule data ☆`19`
### Wiki & Collaboration

- [anyproto/anytype-mcp](https://github.com/anyproto/anytype-mcp) — AI with Anytype encrypted local data ☆`539`
- [ProfessionalWiki/MediaWiki-MCP-Server](https://github.com/ProfessionalWiki/MediaWiki-MCP-Server) — Connect AI with any MediaWiki ☆`147`
- [yuna0x0/hackmd-mcp](https://github.com/yuna0x0/hackmd-mcp) — HackMD note-taking integration ☆`67`
- [HenryHaoson/Yuque-MCP-Server](https://github.com/HenryHaoson/Yuque-MCP-Server) — Yuque mcp server ☆`69`
- [jtauschl/openproject-ce-mcp](https://github.com/jtauschl/openproject-ce-mcp) — Projects, work packages and time entries in OpenProject ☆`40`
- [growilabs/growi-mcp-server](https://github.com/growilabs/growi-mcp-server) — GROWI wiki search and retrieval for AI answers ☆`20`
### Education

- [RohanMuppa/brightspace-mcp-server](https://github.com/RohanMuppa/brightspace-mcp-server) — Grades, due dates and course content in Brightspace ☆`64`
- [ictinnovations/ictexam-mcp](https://github.com/ictinnovations/ictexam-mcp) — Read exams and gradebooks, and publish exams in ICTExam ☆`17`
## Research & Science

- [mnemox-ai/idea-reality-mcp](https://github.com/mnemox-ai/idea-reality-mcp) — Check GitHub, HN, npm and PyPI before building ☆`831`
- [oOo0oOo/lean-lsp-mcp](https://github.com/oOo0oOo/lean-lsp-mcp) — Lean Theorem Prover MCP ☆`549`
- [rrrrrredy/research-toolkit](https://github.com/rrrrrredy/research-toolkit) — Research methods and an independent review step for agents ☆`314`
- [yusong652/itasca-mcp](https://github.com/yusong652/itasca-mcp) — Geotechnical simulations in PFC, FLAC and other ITASCA engines ☆`228`
- [szeider/mcp-solver](https://github.com/szeider/mcp-solver) — Constraint optimization and solving ☆`187`
- [pminervini/deep-research-mcp](https://github.com/pminervini/deep-research-mcp) — Deep research via OpenAI, Gemini, Tavily or self-hosted ☆`116`
- [ProgramComputer/NASA-MCP-server](https://github.com/ProgramComputer/NASA-MCP-server) — NASA imagery, astronomy and other public NASA APIs ☆`94`
- [Pantheon-Security/notebooklm-mcp-secure](https://github.com/Pantheon-Security/notebooklm-mcp-secure) — Secure NotebookLM MCP with 14 security layers ☆`88`
- [NellyW8/MCP4EDA](https://github.com/NellyW8/MCP4EDA) — RTL-to-GDSII automation with LLM ☆`112`
- [patsnap/patent-literature-search-mcp](https://github.com/patsnap/patent-literature-search-mcp) — Patents from major offices, plus PubMed and arXiv ☆`85`
- [SecretiveShell/MCP-wolfram-alpha](https://github.com/SecretiveShell/MCP-wolfram-alpha) — Wolfram Alpha computational intelligence ☆`76`
- [smaniches/semantic-scholar-mcp](https://github.com/smaniches/semantic-scholar-mcp) — Papers, citations and authors on Semantic Scholar ☆`25`
- [Scormave/gramps-web-mcp](https://github.com/Scormave/gramps-web-mcp) — Family trees in Gramps Web ☆`23`
- [kimimgo/viznoir](https://github.com/kimimgo/viznoir) — VTK visualization aimed at science and engineering agents ☆`20`
- [nguyenvanduocit/research-kit](https://github.com/nguyenvanduocit/research-kit) — Toolkit to help you get started with Spec-Driven Research ☆`20`
- [neuromechanist/matlab-mcp-tools](https://github.com/neuromechanist/matlab-mcp-tools) — MATLAB pipelines by section and figure inspection ☆`19`
- [Orthogonalpub/modelica_simulation_mcp_server](https://github.com/Orthogonalpub/modelica_simulation_mcp_server) — Run a Modelica simulation ☆`22`
- [RLabs-Inc/ios-forensics-mcp](https://github.com/RLabs-Inc/ios-forensics-mcp) — Analyze an iPhone or iPad filesystem ☆`20`
- [anuj0456/arxiv-mcp-server](https://github.com/anuj0456/arxiv-mcp-server) — Search, analyze and export arXiv papers ☆`19`
## Sandboxing & Execution

- [superradcompany/microsandbox](https://github.com/superradcompany/microsandbox) — Local microVM runtime and library ☆`9,015`
- [dagger/container-use](https://github.com/dagger/container-use) — MCP server for container orchestration ☆`4,088`
- [grafbase/grafbase](https://github.com/grafbase/grafbase) — [Acquired by The Guild] The Grafbase GraphQL Federation Gateway ☆`1,226`
- [microsoft/wassette](https://github.com/microsoft/wassette) — Run WebAssembly components through MCP, with a security focus ☆`975`
- [sandbaseai/sandbase-harness](https://github.com/sandbaseai/sandbase-harness) — Sandboxed local agent runtime with approvals and audit ☆`643`
- [docker/labs-ai-tools-for-devs](https://github.com/docker/labs-ai-tools-for-devs) — Find MCP tools and run them from Docker ☆`398`
- [Automata-Labs-team/code-sandbox-mcp](https://github.com/Automata-Labs-team/code-sandbox-mcp) — Secure code sandbox in Docker ☆`327`
- [formulahendry/mcp-server-code-runner](https://github.com/formulahendry/mcp-server-code-runner) — Code Runner MCP Server ☆`242`
- [bazinga012/mcp_code_executor](https://github.com/bazinga012/mcp_code_executor) — Execute Python in Conda environment ☆`211`
- [alfonsograziano/node-code-sandbox-mcp](https://github.com/alfonsograziano/node-code-sandbox-mcp) — MCP server for Node.js code sandbox execution ☆`156`
- [hopx-ai/mcp](https://github.com/hopx-ai/mcp) — Execute code in isolated cloud containers ☆`128`
- [ccq1/awsome_kali_MCPServers](https://github.com/ccq1/awsome_kali_MCPServers) — A set of MCP servers aimed at Kali Linux ☆`110`
- [r33drichards/mcp-js](https://github.com/r33drichards/mcp-js) — MCP server exposing V8 JavaScript runtime for AI agents ☆`64`
- [gradion-ai/ipybox](https://github.com/gradion-ai/ipybox) — Python code execution sandbox with MCP tool calling ☆`76`
- [UsamaK98/python-notebook-mcp](https://github.com/UsamaK98/python-notebook-mcp) — Create and edit Jupyter notebooks ☆`45`
- [Alec2435/python_mcp](https://github.com/Alec2435/python_mcp) — MCP Server to run python code locally ☆`54`
- [yepcode/mcp-server-js](https://github.com/yepcode/mcp-server-js) — JavaScript MCP server framework by YepCode ☆`47`
- [hdresearch/mcp-python](https://github.com/hdresearch/mcp-python) — A python repl for MCP ☆`43`
- [Tsuchijo/matlab-mcp](https://github.com/Tsuchijo/matlab-mcp) — Write and run MATLAB scripts ☆`40`
- [SebastianGilPinzon/colab-mcp](https://github.com/SebastianGilPinzon/colab-mcp) — Colab notebooks with GPU control, including on Windows ☆`24`
- [ihrpr/mcp-server-jupyter](https://github.com/ihrpr/mcp-server-jupyter) — MCP server for Jupyter Notebooks and JupyterLab ☆`34`
- [hileamlakB/Python-Runtime-Interpreter-MCP-Server](https://github.com/hileamlakB/Python-Runtime-Interpreter-MCP-Server) — Safe Python runtime interpreter ☆`30`
- [turlockmike/apple-notifier-mcp](https://github.com/turlockmike/apple-notifier-mcp) — Notifications on a Mac, also a small MCP server example ☆`26`
- [gwbischof/outsource-mcp](https://github.com/gwbischof/outsource-mcp) — Give your AI assistant its own AI assistants. ☆`30`
- [54rt1n/container-mcp](https://github.com/54rt1n/container-mcp) — Containerized MCP server for files, shell and code execution ☆`22`
## Search & Extraction

### Academic Research

- [blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server) — arXiv paper search and analysis ☆`3,271`
- [iosifache/annas-mcp](https://github.com/iosifache/annas-mcp) — Search and download documents from Anna's Archive ☆`1,115`
- [JackKuo666/Google-Scholar-MCP-Server](https://github.com/JackKuo666/Google-Scholar-MCP-Server) — Search Google Scholar papers ☆`432`
- [reading-plus-ai/mcp-server-deep-research](https://github.com/reading-plus-ai/mcp-server-deep-research) — Comprehensive research with reports ☆`215`
- [adityak74/mcp-scholarly](https://github.com/adityak74/mcp-scholarly) — A MCP server to search for accurate academic articles. ☆`185`
- [andybrandt/mcp-simple-arxiv](https://github.com/andybrandt/mcp-simple-arxiv) — arXiv paper search and reading ☆`202`
- [andybrandt/mcp-simple-pubmed](https://github.com/andybrandt/mcp-simple-pubmed) — PubMed medical research search ☆`171`
- [takashiishida/arxiv-latex-mcp](https://github.com/takashiishida/arxiv-latex-mcp) — MCP server for arXiv LaTeX paper retrieval ☆`150`
- [kujenga/zotero-mcp](https://github.com/kujenga/zotero-mcp) — Search a Zotero library through the API ☆`162`
- [kaliaboi/mcp-zotero](https://github.com/kaliaboi/mcp-zotero) — Zotero collections for Claude Desktop ☆`163`
- [JackKuo666/PubMed-MCP-Server](https://github.com/JackKuo666/PubMed-MCP-Server) — Search and analyze PubMed articles ☆`132`
- [afrise/academic-search-mcp-server](https://github.com/afrise/academic-search-mcp-server) — Search papers on Semantic Scholar and Crossref ☆`119`
- [OctagonAI/octagon-deep-research-mcp](https://github.com/OctagonAI/octagon-deep-research-mcp) — AI-powered comprehensive research and analysis ☆`94`
- [akalaric/mcp-wolframalpha](https://github.com/akalaric/mcp-wolframalpha) — Wolfram Alpha integration for Python ☆`87`
- [oscardvs/zoteus](https://github.com/oscardvs/zoteus) — Search Zotero, add by DOI and pull PDF page images ☆`65`
- [HzaCode/OneCite](https://github.com/HzaCode/OneCite) — Parse and format academic references ☆`68`
- [szeider/mcp-dblp](https://github.com/szeider/mcp-dblp) — Access DBLP computer science bibliography ☆`47`
- [drAbreu/alex-mcp](https://github.com/drAbreu/alex-mcp) — MCP server for OpenAlex ☆`57`
- [wd041216-bit/zero-api-key-web-search](https://github.com/wd041216-bit/zero-api-key-web-search) — Web search for agents, with no API key ☆`20`
- [prashalruchiranga/arxiv-mcp-server](https://github.com/prashalruchiranga/arxiv-mcp-server) — arXiv API via natural language ☆`41`
- [JackKuo666/bioRxiv-MCP-Server](https://github.com/JackKuo666/bioRxiv-MCP-Server) — Access bioRxiv papers ☆`27`
- [hbg/mcp-paperswithcode](https://github.com/hbg/mcp-paperswithcode) — MCP interface for PapersWithCode API ☆`26`
- [mochow13/google-scholar-mcp](https://github.com/mochow13/google-scholar-mcp) — MCP server for Google Scholar written in TypeScript ☆`26`
- [gemy411/multi-agents-research](https://github.com/gemy411/multi-agents-research) — Kotlin multi-agent research server on Ktor ☆`16`
### Data APIs

- [cantian-ai/bazi-mcp](https://github.com/cantian-ai/bazi-mcp) — Bazi Chinese astrology information ☆`436`
- [Rudra-ravi/wikipedia-mcp](https://github.com/Rudra-ravi/wikipedia-mcp) — Retrieve Wikipedia information ☆`306`
- [ahonn/mcp-server-gsc](https://github.com/ahonn/mcp-server-gsc) — Google Search Console data access ☆`284`
- [hellokaton/unsplash-mcp-server](https://github.com/hellokaton/unsplash-mcp-server) — A MCP server for Unsplash image search. ☆`239`
- [deadletterq/mcp-opennutrition](https://github.com/deadletterq/mcp-opennutrition) — MCP server for nutrition data and analysis ☆`209`
- [cameronrye/openzim-mcp](https://github.com/cameronrye/openzim-mcp) — MCP server for OpenZIM archive access ☆`151`
- [damionrashford/RivalSearchMCP](https://github.com/damionrashford/RivalSearchMCP) — MCP server for competitive search analysis ☆`138`
- [cswkim/discogs-mcp-server](https://github.com/cswkim/discogs-mcp-server) — MCP Server for Discogs ☆`134`
- [OpenDataMCP/OpenDataMCP](https://github.com/OpenDataMCP/OpenDataMCP) — Connect any Open Data to any LLM with Model Context Protocol. ☆`156`
- [8enSmith/mcp-open-library](https://github.com/8enSmith/mcp-open-library) — MCP server for Open Library book and author search ☆`102`
- [riemannzeta/patent_mcp_server](https://github.com/riemannzeta/patent_mcp_server) — MCP Server for USPTO data ☆`85`
- [zoomeye-ai/mcp_zoomeye](https://github.com/zoomeye-ai/mcp_zoomeye) — MCP server for ZoomEye network asset information ☆`83`
- [yuna0x0/anilist-mcp](https://github.com/yuna0x0/anilist-mcp) — AniList MCP server for accessing anime and manga data ☆`91`
- [Linked-API/linkedapi-mcp](https://github.com/Linked-API/linkedapi-mcp) — LinkedIn account control and data retrieval ☆`70`
- [imprvhub/mcp-domain-availability](https://github.com/imprvhub/mcp-domain-availability) — MCP server to check domain availability ☆`61`
- [anysiteio/anysite-mcp-server](https://github.com/anysiteio/anysite-mcp-server) — LinkedIn data access ☆`65`
- [djalal/quran-mcp-server](https://github.com/djalal/quran-mcp-server) — Quran.com verses, translations, tafsir ☆`73`
- [r-huijts/rijksmuseum-mcp](https://github.com/r-huijts/rijksmuseum-mcp) — Rijksmuseum artwork exploration ☆`72`
- [DappierAI/dappier-mcp](https://github.com/DappierAI/dappier-mcp) — MCP server for Dappier AI integration ☆`44`
- [0xDAEF0F/job-searchoor](https://github.com/0xDAEF0F/job-searchoor) — A simple MCP server that delivers you jobs based on your needs ☆`65`
- [JamesANZ/us-legal-mcp](https://github.com/JamesANZ/us-legal-mcp) — An MCP server that provides comprehensive US legislation. ☆`38`
- [yamanoku/baseline-mcp-server](https://github.com/yamanoku/baseline-mcp-server) — Web API Baseline status information ☆`37`
- [amurshak/congressMCP](https://github.com/amurshak/congressMCP) — US Congress data for AI agents ☆`36`
- [zzaebok/mcp-wikidata](https://github.com/zzaebok/mcp-wikidata) — Wikidata API implementation ☆`49`
- [joelio/stocky](https://github.com/joelio/stocky) — An MCP server for searching and downloading stock photography. ☆`28`
- [jhomen368/overseerr-mcp](https://github.com/jhomen368/overseerr-mcp) — Overseerr/Seerr media search, requests, and library ☆`26`
- [adawalli/nexus](https://github.com/adawalli/nexus) — MCP Server to make searching openrouter easy ☆`21`
- [Himalayas-App/himalayas-mcp](https://github.com/Himalayas-App/himalayas-mcp) — Remote job search, listings, candidates, and salaries ☆`21`
- [mikechao/metmuseum-mcp](https://github.com/mikechao/metmuseum-mcp) — Met Museum art collection discovery ☆`36`
- [cameronrye/activitypub-mcp](https://github.com/cameronrye/activitypub-mcp) — Fediverse browsing and interaction via ActivityPub ☆`17`
- [parallel-web/task-mcp](https://github.com/parallel-web/task-mcp) — Hosted deep research and dataset enrichment via Parallel ☆`16`
- [cameronrye/gopher-mcp](https://github.com/cameronrye/gopher-mcp) — Browse Gopher and Gemini sites ☆`16`
- [kehvinbehvin/json-mcp-filter](https://github.com/kehvinbehvin/json-mcp-filter) — JSON MCP server to filter only relevant data for your LLM ☆`26`
- [angheljf/nyt](https://github.com/angheljf/nyt) — MCP server for New York Times article search ☆`18`
- [siva010928/multi-chat-mcp-server](https://github.com/siva010928/multi-chat-mcp-server) — MCP server for multi-chat capabilities ☆`27`
- [delorenj/mcp-server-ticketmaster](https://github.com/delorenj/mcp-server-ticketmaster) — Ticketmaster Discovery API ☆`24`
- [r-huijts/opentk-mcp](https://github.com/r-huijts/opentk-mcp) — MCP server for Dutch parliamentary data via OpenTK ☆`23`
- [AshwinSundar/congress_gov_mcp](https://github.com/AshwinSundar/congress_gov_mcp) — Query US Congress.gov API ☆`19`
- [Trevato/bible-mcp](https://github.com/Trevato/bible-mcp) — add biblical context to your generative AI applications ☆`16`
### News & Content

- [6551Team/opennews-mcp](https://github.com/6551Team/opennews-mcp) — Live news, ratings and trading signals from many sources ☆`2,436`
- [guangxiangdebizi/FinanceMCP](https://github.com/guangxiangdebizi/FinanceMCP) — Financial data MCP for stocks, funds, bonds, macro ☆`871`
- [lfnovo/content-core](https://github.com/lfnovo/content-core) — Extract what matters from any media source ☆`184`
- [superagents-lab/search1api-mcp](https://github.com/superagents-lab/search1api-mcp) — Web search, news, crawls and trends from Search1API ☆`174`
- [wopal-cn/mcp-hotnews-server](https://github.com/wopal-cn/mcp-hotnews-server) — Trending topics on major Chinese platforms ☆`202`
- [lennney/agent-search-mcp](https://github.com/lennney/agent-search-mcp) — Chinese and English web search that needs no API key ☆`113`
- [erithwik/mcp-hn](https://github.com/erithwik/mcp-hn) — MCP Server for Hackernews ☆`76`
- [trendsmcp-ai/Trends-MCP](https://github.com/trendsmcp-ai/Trends-MCP) — Live trends from Google, YouTube, TikTok, Reddit and Amazon ☆`48`
- [imprvhub/mcp-rss-aggregator](https://github.com/imprvhub/mcp-rss-aggregator) — RSS feed aggregation for Claude Desktop ☆`27`
- [VectorInstitute/mcp-goodnews](https://github.com/VectorInstitute/mcp-goodnews) — A feed of positive news stories ☆`48`
- [aloth/cred-1](https://github.com/aloth/cred-1) — Check a news source against a domain-credibility dataset ☆`18`
- [pskill9/hn-server](https://github.com/pskill9/hn-server) — Hacker news MCP server ☆`40`
- [pranciskus/newsmcp](https://github.com/pranciskus/newsmcp) — MCP server for real-time world news - free, no API key required ☆`31`
- [format37/youtube_mcp](https://github.com/format37/youtube_mcp) — youtube transcriber mcp server ☆`32`
- [the0807/GeekNews-MCP-Server](https://github.com/the0807/GeekNews-MCP-Server) — GeekNews MCP Server ☆`18`
### Web Search Engines

- [assafelovic/gpt-researcher](https://github.com/assafelovic/gpt-researcher) — Autonomous research agent that can use any LLM provider ☆`30,610`
- [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) — Exa MCP for web search and web crawling! ☆`5,225`
- [tavily-ai/tavily-mcp](https://github.com/tavily-ai/tavily-mcp) — Real-time search, extract, map and crawl ☆`2,486`
- [Aas-ee/open-webSearch](https://github.com/Aas-ee/open-webSearch) — MCP server for open web search ☆`1,901`
- [nickclyde/duckduckgo-mcp-server](https://github.com/nickclyde/duckduckgo-mcp-server) — MCP server for DuckDuckGo search ☆`1,576`
- [brave/brave-search-mcp-server](https://github.com/brave/brave-search-mcp-server) — Brave Search with AI summarization ☆`1,567`
- [ihor-sokoliuk/mcp-searxng](https://github.com/ihor-sokoliuk/mcp-searxng) — Private SearXNG web search for AI assistants ☆`1,358`
- [mrkrsl/web-search-mcp](https://github.com/mrkrsl/web-search-mcp) — Local web search for Claude Desktop ☆`1,202`
- [kagisearch/kagimcp](https://github.com/kagisearch/kagimcp) — Official Kagi search MCP server ☆`563`
- [pskill9/web-search](https://github.com/pskill9/web-search) — Web search using free google search (NO API KEYS REQUIRED) ☆`473`
- [angiejones/mcp-selenium](https://github.com/angiejones/mcp-selenium) — An MCP implementation for Selenium WebDriver ☆`429`
- [spences10/mcp-omnisearch](https://github.com/spences10/mcp-omnisearch) — Search via Tavily, Brave, Kagi and Exa ☆`358`
- [jae-jae/g-search-mcp](https://github.com/jae-jae/g-search-mcp) — Parallel Google search with summaries ☆`272`
- [serpapi/serpapi-mcp](https://github.com/serpapi/serpapi-mcp) — SerpApi MCP Server for Google and other search engine results ☆`184`
- [DasDigitaleMomentum/searxNcrawl](https://github.com/DasDigitaleMomentum/searxNcrawl) — Self-hosted search and crawls of logged-in pages ☆`188`
- [nkapila6/mcpsurfr](https://github.com/nkapila6/mcpsurfr) — RAG-like web search via MCP ☆`151`
- [ChanMeng666/server-google-news](https://github.com/ChanMeng666/server-google-news) — MCP server for Google News integration ☆`131`
- [SecretiveShell/MCP-searxng](https://github.com/SecretiveShell/MCP-searxng) — SearXNG search for agentic systems ☆`132`
- [mikechao/brave-search-mcp](https://github.com/mikechao/brave-search-mcp) — MCP server for Brave Search with filtering options ☆`131`
- [ScrapeGraphAI/scrapegraph-mcp](https://github.com/ScrapeGraphAI/scrapegraph-mcp) — ScapeGraph MCP Server ☆`121`
- [isnow890/naver-search-mcp](https://github.com/isnow890/naver-search-mcp) — MCP server for Naver search integration ☆`87`
- [zoharbabin/web-researcher-mcp](https://github.com/zoharbabin/web-researcher-mcp) — Search, read full pages and check each citation ☆`77`
- [tanigami/mcp-server-perplexity](https://github.com/tanigami/mcp-server-perplexity) — Perplexity API chat with citations ☆`95`
- [ConechoAI/openai-websearch-mcp](https://github.com/ConechoAI/openai-websearch-mcp) — openai websearch tool as mcp server ☆`94`
- [JovaniPink/mcp-browser-use](https://github.com/JovaniPink/mcp-browser-use) — Browser-use automation exposed over MCP ☆`64`
- [zhsama/duckduckgo-mcp-server](https://github.com/zhsama/duckduckgo-mcp-server) — MCP server for DuckDuckGo web search ☆`88`
- [goesByhc/cn-scraper-mcp](https://github.com/goesByhc/cn-scraper-mcp) — Search Taobao, Xiaohongshu, Weibo, Bilibili and more ☆`78`
- [steel-dev/steel-mcp-server](https://github.com/steel-dev/steel-mcp-server) — Cloud Chrome for blocked pages, with a human login ☆`58`
- [thedaviddias/mcp-llms-txt-explorer](https://github.com/thedaviddias/mcp-llms-txt-explorer) — MCP to explore websites with llms.txt files ☆`78`
- [leehanchung/bing-search-mcp](https://github.com/leehanchung/bing-search-mcp) — MCP Server for Bing Search API ☆`81`
- [XZXZZX-Ai/bilibili-mcp](https://github.com/XZXZZX-Ai/bilibili-mcp) — MCP server for Bilibili ☆`49`
- [laurentvv/crawl4ai-mcp-llm](https://github.com/laurentvv/crawl4ai-mcp-llm) — Crawl pages and hand the text to an assistant ☆`45`
- [pwilkin/mcp-searxng-public](https://github.com/pwilkin/mcp-searxng-public) — Query public SearXNG instances ☆`57`
- [ubie-oss/mcp-vertexai-search](https://github.com/ubie-oss/mcp-vertexai-search) — A MCP server for Vertex AI Search ☆`38`
- [OvertliDS/mcp-searxng-enhanced](https://github.com/OvertliDS/mcp-searxng-enhanced) — SearXNG web search with category awareness ☆`55`
- [dazeb/markdown-downloader](https://github.com/dazeb/markdown-downloader) — Save a web page as markdown for the editor ☆`56`
- [dorukardahan/domain-search-mcp](https://github.com/dorukardahan/domain-search-mcp) — Check whether a domain is free, with live pricing ☆`28`
- [youdotcom-oss/mcp](https://github.com/youdotcom-oss/mcp) — Local stdio bridge to the hosted You.com MCP server ☆`27`
- [Tomatio13/mcp-server-tavily](https://github.com/Tomatio13/mcp-server-tavily) — MCP Server for Tavily API integration ☆`50`
- [n24q02m/wet](https://github.com/n24q02m/wet) — Web search, page extraction and library docs, with no API key ☆`24`
- [apache/solr-mcp](https://github.com/apache/solr-mcp) — Solr MCP Server ☆`21`
- [Role1776/mcp-retrieval](https://github.com/Role1776/mcp-retrieval) — Local web search, image search and page-to-markdown, no API key ☆`23`
- [czottmann/kagi-ken-mcp](https://github.com/czottmann/kagi-ken-mcp) — Search and summarize Kagi with a session token, no API key ☆`42`
- [ac3xx/mcp-servers-kagi](https://github.com/ac3xx/mcp-servers-kagi) — A Model Context Protocol server implementation for Kagi's API ☆`44`
- [robertheadley/chrome-debug-mcp](https://github.com/robertheadley/chrome-debug-mcp) — An MCP server to allow you to debug webpages using LLMs ☆`45`
- [cevatkerim/unsplash-mcp](https://github.com/cevatkerim/unsplash-mcp) — Search Unsplash photos and get ready-to-use attribution ☆`38`
- [mnhlt/WebSearch-MCP](https://github.com/mnhlt/WebSearch-MCP) — MCP server for web search integration ☆`42`
- [MikkoParkkola/nab](https://github.com/MikkoParkkola/nab) — Fetch a URL as clean markdown, using real browser cookies ☆`18`
- [garylab/serper-mcp-server](https://github.com/garylab/serper-mcp-server) — A Serper MCP Server ☆`39`
- [HasData/hasdata-mcp](https://github.com/HasData/hasdata-mcp) — Structured scrapes of Google, Amazon, Zillow, YouTube and more ☆`17`
- [KyuRish/mcp-server-for-fiverr-unofficial](https://github.com/KyuRish/mcp-server-for-fiverr-unofficial) — Search public Fiverr gig listings ☆`16`
- [andyliszewski/webcrawl-mcp](https://github.com/andyliszewski/webcrawl-mcp) — Local scrape, search and crawl, with a Firecrawl fallback ☆`16`
- [orliesaurus/pulsemcp-server](https://github.com/orliesaurus/pulsemcp-server) — Find MCP servers listed on PulseMCP ☆`30`
- [oso95/domain-suite-mcp](https://github.com/oso95/domain-suite-mcp) — Domains and DNS on Porkbun, Namecheap, GoDaddy and Cloudflare ☆`24`
- [codingthefuturewithai/rag-retriever](https://github.com/codingthefuturewithai/rag-retriever) — Index pages and files, then search by meaning ☆`27`
- [chatmcp/mcp-server-collector](https://github.com/chatmcp/mcp-server-collector) — Find MCP servers published on the internet ☆`20`
## Security

### Identity & Access

- [auth0/auth0-mcp-server](https://github.com/auth0/auth0-mcp-server) — Auth0 tenant management via natural language ☆`122`
- [hashicorp/vault-mcp-server](https://github.com/hashicorp/vault-mcp-server) — Read secrets and manage HashiCorp Vault policies via MCP. ☆`66`
- [sshaaf/keycloak-mcp-server](https://github.com/sshaaf/keycloak-mcp-server) — MCP server for Keycloak identity and access management ☆`49`
- [ChristophEnglisch/keycloak-model-context-protocol](https://github.com/ChristophEnglisch/keycloak-model-context-protocol) — Keycloak user and realm management ☆`46`
- [firstorderai/authenticator_mcp](https://github.com/firstorderai/authenticator_mcp) — Authenticator App for AI agents ☆`48`
- [atomicchonk/roadrecon_mcp_server](https://github.com/atomicchonk/roadrecon_mcp_server) — Azure AD ROADrecon analysis for Claude ☆`53`
- [kapilduraphe/okta-mcp-server](https://github.com/kapilduraphe/okta-mcp-server) — Okta MCP Server ☆`22`
- [hieuttmmo/entraid-mcp-server](https://github.com/hieuttmmo/entraid-mcp-server) — EntraID via Microsoft Graph API ☆`41`
- [descope-sample-apps/descope-mcp-server-stdio](https://github.com/descope-sample-apps/descope-mcp-server-stdio) — Descope user management and audits ☆`38`
### MCP Security

- [snyk/agent-scan](https://github.com/snyk/agent-scan) — Security scanner for AI agents, MCP servers and agent skills. ☆`3,230`
- [harishsg993010/damn-vulnerable-MCP-server](https://github.com/harishsg993010/damn-vulnerable-MCP-server) — Damn Vulnerable MCP Server ☆`1,365`
- [hashgraph-online/hol-guard](https://github.com/hashgraph-online/hol-guard) — Block risky tools, secrets and prompt injection ☆`1,081`
- [riseandignite/mcp-shield](https://github.com/riseandignite/mcp-shield) — Security scanner for MCP servers ☆`555`
- [bx33661/Wireshark-MCP](https://github.com/bx33661/Wireshark-MCP) — Ask questions about a pcap and get answers from tshark ☆`379`
- [eqtylab/mcp-guardian](https://github.com/eqtylab/mcp-guardian) — Manage / Proxy / Secure your MCP Servers ☆`205`
- [kapilduraphe/mcp-watch](https://github.com/kapilduraphe/mcp-watch) — Security scanner for MCP servers ☆`139`
- [stevenyu113228/BloodHound-MCP](https://github.com/stevenyu113228/BloodHound-MCP) — Active Directory questions against BloodHound ☆`164`
- [KryptosAI/mcp-observatory](https://github.com/KryptosAI/mcp-observatory) — Local security tests for MCP servers ☆`120`
- [mobilehackinglab/jadx-mcp-plugin](https://github.com/mobilehackinglab/jadx-mcp-plugin) — Live access to code decompiled in jadx ☆`105`
- [dtkmn/mcp-zap-server](https://github.com/dtkmn/mcp-zap-server) — Guided OWASP ZAP scans, findings and reports ☆`69`
- [82ch/MCP-Dandan](https://github.com/82ch/MCP-Dandan) — MCP security with real-time proxying ☆`68`
- [snyk/studio-mcp](https://github.com/snyk/studio-mcp) — Snyk checks on AI-written code and existing vulnerabilities ☆`59`
- [postralai/masquerade](https://github.com/postralai/masquerade) — The Privacy Firewall for LLMs ☆`80`
- [Synvoya/codeinspectus](https://github.com/Synvoya/codeinspectus) — Security scan of an AI-generated app, then a rescan after fixes ☆`51`
- [pomerium/mcp-app-demo](https://github.com/pomerium/mcp-app-demo) — Demo of securing MCP servers and clients with Pomerium ☆`51`
- [doublegate/CyberChef-MCP](https://github.com/doublegate/CyberChef-MCP) — CyberChef encode, hash and forensics operations as tools ☆`34`
- [icoretech/warden-mcp](https://github.com/icoretech/warden-mcp) — Vaultwarden / Bitwarden MCP server for credential-aware AI agents ☆`26`
- [CakeRepository/1Password-MCP](https://github.com/CakeRepository/1Password-MCP) — 1Password vaults without secrets in the chat ☆`22`
- [echelongraph/echelongraph-mcp](https://github.com/echelongraph/echelongraph-mcp) — CVE records, KEV, EPSS and exploit notes ☆`20`
- [Acacian/aegis](https://github.com/Acacian/aegis) — Python guardrails for prompt injection, PII and toxicity ☆`18`
- [Top-Celestial-Company-Ltd/DROS-VajraClaw-Hacker](https://github.com/Top-Celestial-Company-Ltd/DROS-VajraClaw-Hacker) — Security gateway for agents and Docker ☆`16`
- [operantlabs/operant-mcp](https://github.com/operantlabs/operant-mcp) — Turn your AI agent into a hacker by plugging in this MCP ☆`27`
- [MorDavid/Hashcat-MCP](https://github.com/MorDavid/Hashcat-MCP) — Run Hashcat cracking jobs in natural language ☆`27`
- [AIM-Intelligence/AIM-MCP](https://github.com/AIM-Intelligence/AIM-MCP) — AIM MCP Server :: Guard and Protect your MCPs & AI Chatting ☆`23`
- [cromwellian/hippycampus](https://github.com/cromwellian/hippycampus) — REST endpoint to MCP conversion ☆`20`
### Network & Firewall

- [pipelab-org/pipelock](https://github.com/pipelab-org/pipelock) — Firewall for agent traffic: HTTP, MCP and WebSocket ☆`988`
- [vespo92/OPNSenseMCP](https://github.com/vespo92/OPNSenseMCP) — MCP Server for OPNSense to act as IaC proxy ☆`97`
- [AynOps/AynOps](https://github.com/AynOps/AynOps) — Live reconnaissance and attack-surface mapping for agents ☆`29`
- [girste/CHIHUAUDIT](https://github.com/girste/CHIHUAUDIT) — Linux security audit tool ☆`54`
- [intruder-io/intruder-mcp](https://github.com/intruder-io/intruder-mcp) — An MCP server to let AI agents control Intruder ☆`26`
### Pentesting & OSINT

- [koala73/worldmonitor](https://github.com/koala73/worldmonitor) — News, geopolitics and infrastructure on one dashboard ☆`90,429`
- [Tencent/AI-Infra-Guard](https://github.com/Tencent/AI-Infra-Guard) — Red-team scans of agents, MCP servers and jailbreaks ☆`7,450`
- [OpenOSINT/OpenOSINT](https://github.com/OpenOSINT/OpenOSINT) — Passive OSINT checks as a CLI, an MCP server and a web UI ☆`1,915`
- [prompt-security/clawsec](https://github.com/prompt-security/clawsec) — Security and drift checks for OpenClaw-family agents ☆`1,135`
- [marc-shade/world-intel-mcp](https://github.com/marc-shade/world-intel-mcp) — Markets, filings, conflict and aviation from public APIs ☆`1,067`
- [w0h1v/mcp-maigret](https://github.com/w0h1v/mcp-maigret) — Maigret OSINT user account collection ☆`272`
- [OSINT-Experts-Society/Consensus-OSINT](https://github.com/OSINT-Experts-Society/Consensus-OSINT) — Username, email and phone lookups with evidence ☆`249`
- [JeanExtreme002/PyMemoryEditor](https://github.com/JeanExtreme002/PyMemoryEditor) — Inspect and edit another process's memory ☆`225`
- [frishtik/osint-tools-mcp-server](https://github.com/frishtik/osint-tools-mcp-server) — Several OSINT tools behind one server ☆`249`
- [w0h1v/mcp-shodan](https://github.com/w0h1v/mcp-shodan) — MCP server for Shodan - device search, IP recon, CVE intel ☆`189`
- [timescale/rsigma](https://github.com/timescale/rsigma) — Parse, lint and evaluate Sigma detection rules ☆`187`
- [w0h1v/mcp-virustotal](https://github.com/w0h1v/mcp-virustotal) — VirusTotal API queries ☆`155`
- [XposedOrNot/XposedOrNot-API](https://github.com/XposedOrNot/XposedOrNot-API) — Check whether an email showed up in a breach ☆`102`
- [26zl/cybersec-toolkit](https://github.com/26zl/cybersec-toolkit) — Install security tools and run them in a disposable VM via MCP ☆`96`
- [roadwy/cve-search_mcp](https://github.com/roadwy/cve-search_mcp) — CVE database security queries ☆`109`
- [mobb-dev/bugsy](https://github.com/mobb-dev/bugsy) — Automatic security vulnerability remediation for your code. ☆`67`
- [MediaPublishing/mcp-manager](https://github.com/MediaPublishing/mcp-manager) — Web UI for MCP servers used by Claude and Cursor ☆`83`
- [Cyreslab-AI/shodan-mcp-server](https://github.com/Cyreslab-AI/shodan-mcp-server) — Shodan host lookup, CVEs and alerts ☆`53`
- [w0h1v/mcp-dnstwist](https://github.com/w0h1v/mcp-dnstwist) — DNS fuzzing for phishing detection ☆`51`
- [frangelbarrera/osint-agent-skills](https://github.com/frangelbarrera/osint-agent-skills) — OSINT playbooks and tools for recon and threat intel ☆`46`
- [pollinations/chucknorris](https://github.com/pollinations/chucknorris) — Prompts that try to push a weaker model past its limits ☆`69`
- [StacklokLabs/osv-mcp](https://github.com/StacklokLabs/osv-mcp) — An MCP server for OSV ☆`44`
- [GitGuardian/ggmcp](https://github.com/GitGuardian/ggmcp) — Scan and remediate hardcoded secrets ☆`41`
- [koda-ai-studio/agent-bom](https://github.com/koda-ai-studio/agent-bom) — Inventory of agents, MCP servers and what they can reach ☆`36`
- [UPinar/contrastapi](https://github.com/UPinar/contrastapi) — CVEs, MITRE, Sigma rules, email posture and domain intel ☆`37`
- [vetcoders/mcp-server-semgrep](https://github.com/vetcoders/mcp-server-semgrep) — Run Semgrep static analysis ☆`28`
- [addcontent/nuclei-mcp](https://github.com/addcontent/nuclei-mcp) — Run Nuclei scans with the context the model needs ☆`50`
- [SOsintOps/claudii-exploratores](https://github.com/SOsintOps/claudii-exploratores) — OSINT tools with an indicator classifier ☆`25`
- [sophymarine/openregistry](https://github.com/sophymarine/openregistry) — Company profiles and filings from official registries ☆`23`
- [mastyf-ai/mastyf.ai](https://github.com/mastyf-ai/mastyf.ai) — Perimeter checks, policy and adversarial tests for agents ☆`21`
- [Rul1an/assay](https://github.com/Rul1an/assay) — Open evidence profile for MCP tool actions. Enforce configured tool-call policies and record decisions and observations in offline-verifiable bundles. Optional Linux kernel ☆`16`
- [kontext-security/attestable-mcp-server](https://github.com/kontext-security/attestable-mcp-server) — Attest that the MCP server code is untampered ☆`22`
- [nickpending/mcp-recon](https://github.com/nickpending/mcp-recon) — Tellix conversational recon interface ☆`31`
- [agentward-ai/agentward](https://github.com/agentward-ai/agentward) — Scan, enforce and audit every agent tool call ☆`19`
- [ajipurn/fida](https://github.com/ajipurn/fida) — a local-first secret leak prevention layer for AI coding agents ☆`19`
- [aak204/MCP-Scorecard](https://github.com/aak204/MCP-Scorecard) — CI scanner that scores the attack surface of MCP servers ☆`21`
- [elliotllliu/agent-shield](https://github.com/elliotllliu/agent-shield) — Scan agents, MCP servers and plugins and produce one report ☆`16`
- [gnlds/mcp-cve-intelligence-server-lite](https://github.com/gnlds/mcp-cve-intelligence-server-lite) — CVE intelligence from NVD, MITRE, GitHub ☆`19`
- [Hexix23/shodan-mcp](https://github.com/Hexix23/shodan-mcp) — MCP server for Shodan search and host data ☆`16`
### Reverse Engineering

- [morluto/rea](https://github.com/morluto/rea) — Local CLI and MCP server for agent-assisted reverse engineering. ☆`450,649`
- [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) — IDA Pro reverse engineering with AI ☆`13,436`
- [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) — MCP Server for Ghidra ☆`11,884`
- [zinja-coder/jadx-ai-mcp](https://github.com/zinja-coder/jadx-ai-mcp) — Plugin for JADX to integrate MCP server ☆`3,007`
- [svnscha/mcp-windbg](https://github.com/svnscha/mcp-windbg) — Model Context Protocol for WinDbg. ☆`1,666`
- [LING71671/open-reverselab](https://github.com/LING71671/open-reverselab) — Ghidra, Frida, x64dbg, Rizin, and YARA in one lab ☆`1,360`
- [cyberkaida/reverse-engineering-assistant](https://github.com/cyberkaida/reverse-engineering-assistant) — Reverse-engineering help inside Ghidra ☆`954`
- [symgraph/GhidrAssistMCP](https://github.com/symgraph/GhidrAssistMCP) — An native MCP server extension for Ghidra ☆`808`
- [zinja-coder/apktool-mcp-server](https://github.com/zinja-coder/apktool-mcp-server) — APK Tool for Android reverse engineering ☆`709`
- [fosdickio/binary_ninja_mcp](https://github.com/fosdickio/binary_ninja_mcp) — Binary Ninja plugin for LLM integration ☆`457`
- [radareorg/radare2-mcp](https://github.com/radareorg/radare2-mcp) — MCP stdio server for radare2 ☆`360`
- [taida957789/ida-mcp-server-plugin](https://github.com/taida957789/ida-mcp-server-plugin) — IDA Pro plugin that serves an MCP endpoint ☆`190`
- [13bm/GhidraMCP](https://github.com/13bm/GhidraMCP) — Active Socket based MCP Server for Ghidra ☆`150`
- [NadavLor/windbg-ext-mcp](https://github.com/NadavLor/windbg-ext-mcp) — Kernel debugging in WinDbg, driven from the editor ☆`118`
- [fdrechsler/mcp-server-idapro](https://github.com/fdrechsler/mcp-server-idapro) — Reverse-engineer a binary inside IDA Pro ☆`103`
- [Invoke-RE/binja-lattice-mcp](https://github.com/Invoke-RE/binja-lattice-mcp) — Talk to a Binary Ninja database from a model ☆`67`
- [MCPPhalanx/binaryninja-mcp](https://github.com/MCPPhalanx/binaryninja-mcp) — Another™ MCP Server for Binary Ninja with superpower ☆`52`
- [pullkitsan/mobsf-mcp-server](https://github.com/pullkitsan/mobsf-mcp-server) — MobSF APK and IPA security scanning ☆`24`
### SIEM & SecOps

- [beelzebub-labs/beelzebub](https://github.com/beelzebub-labs/beelzebub) — Low-code honeypot with AI virtualization ☆`2,234`
- [MorDavid/BloodHound-MCP-AI](https://github.com/MorDavid/BloodHound-MCP-AI) — BloodHound integration with AI through MCP ☆`383`
- [CrowdStrike/falcon-mcp](https://github.com/CrowdStrike/falcon-mcp) — CrowdStrike Falcon security analysis ☆`279`
- [gbrigandi/mcp-server-wazuh](https://github.com/gbrigandi/mcp-server-wazuh) — MCP Server for Wazuh SIEM ☆`240`
- [securityfortech/secops-mcp](https://github.com/securityfortech/secops-mcp) — All-in-one security testing toolbox via MCP ☆`219`
- [cycodehq/cycode-cli](https://github.com/cycodehq/cycode-cli) — SAST, SCA, Secrets, IaC security scanning ☆`99`
- [panther-labs/mcp-panther](https://github.com/panther-labs/mcp-panther) — Detections, alerts, and log queries ☆`49`
- [Farenhytee/database-sentinel](https://github.com/Farenhytee/database-sentinel) — Read-only audit of a Supabase project for risky settings ☆`51`
- [qianniuspace/mcp-security-audit](https://github.com/qianniuspace/mcp-security-audit) — MCP server for security auditing ☆`58`
- [Gaffx/volatility-mcp](https://github.com/Gaffx/volatility-mcp) — This repo hosts an MCP server for volatility3.x ☆`53`
- [fr0gger/MCP_Security](https://github.com/fr0gger/MCP_Security) — This is a repository to experiment with MCP for security ☆`52`
- [slouchd/cyberchef-api-mcp-server](https://github.com/slouchd/cyberchef-api-mcp-server) — CyberChef API MCP Server ☆`44`
- [Contrast-Security-OSS/mcp-contrast](https://github.com/Contrast-Security-OSS/mcp-contrast) — MCP Server for Contrast Security ☆`23`
- [mcp-hangar/mcp-hangar](https://github.com/mcp-hangar/mcp-hangar) — Policy check on every MCP call, with identity and an audit trail ☆`17`
- [jyjune/mcp_vms](https://github.com/jyjune/mcp_vms) — MCP server for controlling and accessing a video surveillance system ☆`17`
- [gbrigandi/mcp-server-cortex](https://github.com/gbrigandi/mcp-server-cortex) — MCP Server for Cortex ☆`17`
- [gbrigandi/mcp-server-thehive](https://github.com/gbrigandi/mcp-server-thehive) — MCP Server for TheHive ☆`16`
## Social Media

- [iFurySt/RedNote-MCP](https://github.com/iFurySt/RedNote-MCP) — MCP server for accessing RedNote(XiaoHongShu, xhs). ☆`1,132`
- [karanb192/reddit-mcp-buddy](https://github.com/karanb192/reddit-mcp-buddy) — Clean Reddit data: posts, search, users ☆`891`
- [dialog-tools/reddit-research-mcp](https://github.com/dialog-tools/reddit-research-mcp) — Reddit research with structured insights ☆`265`
- [Xquik-dev/x-twitter-scraper](https://github.com/Xquik-dev/x-twitter-scraper) — X/Twitter search, profiles, posting, and media download ☆`227`
- [HagaiHen/facebook-mcp-server](https://github.com/HagaiHen/facebook-mcp-server) — Facebook posts, comments, insights automation ☆`235`
- [taisly/agent](https://github.com/taisly/agent) — Publish video to TikTok, Reels, Shorts, X and Facebook ☆`221`
- [adhikasp/mcp-twikit](https://github.com/adhikasp/mcp-twikit) — Twitter interaction via MCP ☆`237`
- [Seym0n/tiktok-mcp](https://github.com/Seym0n/tiktok-mcp) — Model Context Protocol (MCP) with TikTok integration ☆`208`
- [34892002/bilibili-mcp-js](https://github.com/34892002/bilibili-mcp-js) — Bilibili video search MCP service ☆`198`
- [ihuzaifashoukat/x-use](https://github.com/ihuzaifashoukat/x-use) — Read X profiles, inboxes and posts without an X API key ☆`182`
- [trypeggy/instagram_dm_mcp](https://github.com/trypeggy/instagram_dm_mcp) — Instagram Direct messages MCP ☆`189`
- [sparfenyuk/mcp-telegram](https://github.com/sparfenyuk/mcp-telegram) — MCP server to work with Telegram through MTProto ☆`190`
- [hanweg/mcp-discord](https://github.com/hanweg/mcp-discord) — MCP server for discord bot ☆`168`
- [anwerj/youtube-uploader-mcp](https://github.com/anwerj/youtube-uploader-mcp) — Upload, update, and schedule YouTube videos ☆`67`
- [conorbronsdon/substack-mcp](https://github.com/conorbronsdon/substack-mcp) — Draft Substack posts, Notes and consented subscriber tasks ☆`46`
- [vidhupv/x-mcp](https://github.com/vidhupv/x-mcp) — Create and publish posts on X ☆`61`
- [mikusnuz/meta-mcp](https://github.com/mikusnuz/meta-mcp) — Instagram, Threads and other Meta platform APIs ☆`32`
- [jaipandya/producthunt-mcp-server](https://github.com/jaipandya/producthunt-mcp-server) — MCP server for Product Hunt data access ☆`56`
- [macrocosm-os/macrocosmos-mcp](https://github.com/macrocosm-os/macrocosmos-mcp) — The MCP for macrocosmos subnets. ☆`29`
- [AstaBlackClove/posthive](https://github.com/AstaBlackClove/posthive) — Schedule posts across social networks ☆`26`
- [bulatko/vk-mcp-server](https://github.com/bulatko/vk-mcp-server) — Read and post on VK through its API ☆`17`
- [lumizone/postsider](https://github.com/lumizone/postsider) — Schedule posts on 30-plus networks, with an API and SDK ☆`17`
- [Upload-Post/upload-post-mcp](https://github.com/Upload-Post/upload-post-mcp) — Model Context Protocol (MCP) server for Upload-Post - publish, schedule, analyze and manage social media from any MCP-compatible AI agent. ☆`16`
- [AbdelStark/nostr-mcp](https://github.com/AbdelStark/nostr-mcp) — Nostr posting and interaction ☆`39`
- [ertiqah/linkedin-mcp-runner](https://github.com/ertiqah/linkedin-mcp-runner) — LinkedIn content analysis and posting ☆`31`
- [laulauland/bluesky-context-server](https://github.com/laulauland/bluesky-context-server) — Bluesky MCP server ☆`35`
- [jonathan-politzki/mcp-writer-substack](https://github.com/jonathan-politzki/mcp-writer-substack) — Bridge Substack writings to Claude ☆`34`
- [mbelinky/x-mcp-server](https://github.com/mbelinky/x-mcp-server) — MCP server to post on x.com with OAuth v1 and v2 ☆`24`
- [gwbischof/bluesky-social-mcp](https://github.com/gwbischof/bluesky-social-mcp) — A Bluesky MCP ☆`16`
- [wangshunnn/bilibili-mcp-server](https://github.com/wangshunnn/bilibili-mcp-server) — MCP server for the bilibili API ☆`16`
## Sports

- [r-huijts/strava-mcp](https://github.com/r-huijts/strava-mcp) — Strava fitness data integration ☆`505`
- [JamsusMaximus/trainingpeaks-mcp](https://github.com/JamsusMaximus/trainingpeaks-mcp) — Workouts and fitness metrics from TrainingPeaks ☆`196`
- [livetennisapi/livetennisapi-mcp](https://github.com/livetennisapi/livetennisapi-mcp) — Live tennis scores, odds and model win probabilities ☆`134`
- [krmisystems/fantasy-football-manager](https://github.com/krmisystems/fantasy-football-manager) — ESPN fantasy drafts and lineups, with limits ☆`85`
- [rishijatia/fantasy-pl-mcp](https://github.com/rishijatia/fantasy-pl-mcp) — Fantasy Premier League MCP Server ☆`80`
- [guillochon/mlb-api-mcp](https://github.com/guillochon/mlb-api-mcp) — MCP server for MLB baseball statistics ☆`59`
- [lacausecrypto/mcp-sports-hub](https://github.com/lacausecrypto/mcp-sports-hub) — Scores, stats and odds from many sports APIs ☆`41`
- [googlarz/suunto-mcp](https://github.com/googlarz/suunto-mcp) — Read training data from a Suunto watch ☆`39`
- [jordanlyall/wc26-mcp](https://github.com/jordanlyall/wc26-mcp) — Matches, venues and city guides for the 2026 FIFA World Cup ☆`34`
- [DanielTomaro13/sportsdata-mcp](https://github.com/DanielTomaro13/sportsdata-mcp) — Scores, odds and stats from many sports-data providers ☆`33`
- [PeanutSplash/chelaile-mcp](https://github.com/PeanutSplash/chelaile-mcp) — MCP server for Chelaile realtime bus data ☆`38`
- [RobSpectre/mvf1](https://github.com/RobSpectre/mvf1) — Python package and CLI for MultiViewer For F1 ☆`20`
- [drivly/auto-dev-skill](https://github.com/drivly/auto-dev-skill) — Automotive Data for AI Agents ☆`19`
- [street1983nk/infranode](https://github.com/street1983nk/infranode) — InfraNode - free, key-less open-data REST API + MCP server for 84 German cities ☆`17`
- [yeonupark/mcp-soccer-data](https://github.com/yeonupark/mcp-soccer-data) — Real-time football data ☆`39`
- [mikechao/balldontlie-mcp](https://github.com/mikechao/balldontlie-mcp) — MCP server for NBA, NFL, MLB sports data ☆`26`
- [smamidipaka6/flights-mcp-server](https://github.com/smamidipaka6/flights-mcp-server) — MCP Server for Google Flights !! ☆`30`
- [lenwood/cfbd-mcp-server](https://github.com/lenwood/cfbd-mcp-server) — An MCP server enabling CFBD API queries within Claude Desktop. ☆`27`
- [amith-vp/indian-railway-mcp](https://github.com/amith-vp/indian-railway-mcp) — Trains, seats, live status and delays on Indian Railways ☆`28`
- [kw510/strava-mcp](https://github.com/kw510/strava-mcp) — MCP server with Strava OAuth on Cloudflare Workers ☆`26`
- [tomekkorbak/strava-mcp-server](https://github.com/tomekkorbak/strava-mcp-server) — MCP server for Strava API integration ☆`25`
- [salamentic/google-flights-mcp](https://github.com/salamentic/google-flights-mcp) — Plan flights with the fast-flights API ☆`22`
- [willvelida/mcp-afl-server](https://github.com/willvelida/mcp-afl-server) — Australian Football League data from Squiggle ☆`18`
- [r-huijts/firstcycling-mcp](https://github.com/r-huijts/firstcycling-mcp) — MCP server for professional cycling data from FirstCycling ☆`18`
## Text-to-Speech

- [mbailey/voicemode](https://github.com/mbailey/voicemode) — Natural voice conversations with Claude Code ☆`1,449`
- [mberg/kokoro-tts-mcp](https://github.com/mberg/kokoro-tts-mcp) — Kokoro Text to Speech (TTS) MCP Server ☆`83`
- [cartesia-ai/cartesia-mcp](https://github.com/cartesia-ai/cartesia-mcp) — The official Cartesia MCP Server ☆`17`
- [ybouhjira/claude-code-tts](https://github.com/ybouhjira/claude-code-tts) — Spoken feedback while Claude Code works ☆`21`
- [da-okazaki/mcp-fish-audio-server](https://github.com/da-okazaki/mcp-fish-audio-server) —  ☆`16`
## Translation

- [caol64/wenyan-mcp](https://github.com/caol64/wenyan-mcp) — Markdown formatting and translation to Chinese ☆`1,357`
- [aymericzip/intlayer](https://github.com/aymericzip/intlayer) — MCP server for Intlayer internationalization ☆`865`
- [DeepL/deepl-mcp-server](https://github.com/DeepL/deepl-mcp-server) — Translation with DeepL API ☆`120`
- [translated/lara-mcp](https://github.com/translated/lara-mcp) — Lara Translate API with language detection ☆`100`
- [mmntm/weblate-mcp](https://github.com/mmntm/weblate-mcp) — Manage Weblate projects, components, and translations ☆`24`
## Travel & Transport

- [Joooook/12306-mcp](https://github.com/Joooook/12306-mcp) — Search train tickets on 12306 ☆`2,430`
- [LetsFG/LetsFG](https://github.com/LetsFG/LetsFG) — Flight and hotel search and booking, with a reliability history ☆`2,255`
- [openbnb-org/mcp-server-airbnb](https://github.com/openbnb-org/mcp-server-airbnb) — Search Airbnb using your AI Agent ☆`559`
- [shaikhspeare/wanderlog-mcp](https://github.com/shaikhspeare/wanderlog-mcp) — Build and edit a Wanderlog trip itinerary ☆`179`
- [cobanov/teslamate-mcp](https://github.com/cobanov/teslamate-mcp) — MCP server for TeslaMate vehicle data and analytics ☆`142`
- [r-huijts/ns-mcp-server](https://github.com/r-huijts/ns-mcp-server) — MCP server for Dutch Railways (NS) travel information ☆`64`
- [pab1it0/tripadvisor-mcp](https://github.com/pab1it0/tripadvisor-mcp) — MCP server for Tripadvisor location data and reviews ☆`64`
- [donghyun-chae/mcp-amadeus](https://github.com/donghyun-chae/mcp-amadeus) — Amadeus MCP(Model Context Protocol) Server ☆`60`
- [variflight/variflight-mcp](https://github.com/variflight/variflight-mcp) — Variflight services implementation ☆`34`
- [Pradumnasaraf/aviationstack-mcp](https://github.com/Pradumnasaraf/aviationstack-mcp) — MCP for AviationStack API - real-time flight data ☆`28`
- [sunsetcoder/flightradar24-mcp-server](https://github.com/sunsetcoder/flightradar24-mcp-server) — Model Context Protocol server for Flight Tracking ☆`47`
- [KyrieTangSheng/mcp-server-nationalparks](https://github.com/KyrieTangSheng/mcp-server-nationalparks) — US National Parks info via NPS API ☆`41`
- [mfukushim/map-traveler-mcp](https://github.com/mfukushim/map-traveler-mcp) — Virtual traveler library for MCP ☆`24`
- [JordanDalton/DoorDash-MCP-Server](https://github.com/JordanDalton/DoorDash-MCP-Server) — MCP server for DoorDash delivery service integration ☆`25`
- [campertunity/mcp-server](https://github.com/campertunity/mcp-server) — Search campgrounds, check availability, and book campsites ☆`17`
## Web Scraping

- [ScrapeGraphAI/Scrapegraph-ai](https://github.com/ScrapeGraphAI/Scrapegraph-ai) — Python scraper based on AI ☆`32,709`
- [apify/apify-mcp-server](https://github.com/apify/apify-mcp-server) — MCP server for Apify web scraping and data extraction ☆`15,666`
- [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server) — Web scraping and search for LLM clients ☆`7,797`
- [KnockOutEZ/wigolo](https://github.com/KnockOutEZ/wigolo) — Local web search, fetch and crawl, with no API key ☆`5,536`
- [brightdata/brightdata-mcp](https://github.com/brightdata/brightdata-mcp) — All-in-one public web access solution ☆`2,720`
- [0xMassi/webclaw](https://github.com/0xMassi/webclaw) — Local web scraper and crawler with a CLI, REST API and MCP server ☆`2,436`
- [fastcrw/crw](https://github.com/fastcrw/crw) — Rust scraper, crawler and search API, with a Firecrawl-like API ☆`1,240`
- [jae-jae/fetcher-mcp](https://github.com/jae-jae/fetcher-mcp) — Playwright web page content fetching ☆`1,088`
- [etsd-tech/mcp-pointer](https://github.com/etsd-tech/mcp-pointer) — DOM element pointing for agents ☆`600`
- [eliasbiondo/linkedin-mcp-server](https://github.com/eliasbiondo/linkedin-mcp-server) — Search LinkedIn people, companies and jobs ☆`217`
- [tinyfish-io/agentql-mcp](https://github.com/tinyfish-io/agentql-mcp) — AgentQL data extraction integration ☆`183`
- [scrapeless-ai/scrapeless-mcp-server](https://github.com/scrapeless-ai/scrapeless-mcp-server) — Scrapeless Mcp Server ☆`170`
- [just-every/mcp-read-website-fast](https://github.com/just-every/mcp-read-website-fast) — Fast webpage to markdown conversion ☆`163`
- [pskill9/website-downloader](https://github.com/pskill9/website-downloader) — MCP server to download entire websites ☆`157`
- [cyberchitta/scrapling-fetch-mcp](https://github.com/cyberchitta/scrapling-fetch-mcp) — Access bot-protected websites ☆`128`
- [just-every/mcp-screenshot-website-fast](https://github.com/just-every/mcp-screenshot-website-fast) — Fast webpage screenshots for LLMs ☆`111`
- [oxylabs/oxylabs-mcp](https://github.com/oxylabs/oxylabs-mcp) — Official Oxylabs MCP integration ☆`105`
- [supadata-ai/mcp](https://github.com/supadata-ai/mcp) — Video and web scraping for Claude ☆`63`
- [pragmar/mcp-server-webcrawl](https://github.com/pragmar/mcp-server-webcrawl) — Web crawler data and archives connection ☆`46`
- [webscraping-ai/webscraping-ai-mcp-server](https://github.com/webscraping-ai/webscraping-ai-mcp-server) — MCP server for AI-powered web scraping ☆`45`
- [crawlbase/crawlbase-mcp](https://github.com/crawlbase/crawlbase-mcp) — MCP server connecting AI agents with real-time web data ☆`60`
- [puremd/puremd-mcp](https://github.com/puremd/puremd-mcp) — Unblock, scrape, and search tools for MCP clients ☆`60`
- [ananddtyagi/webpage-screenshot-mcp](https://github.com/ananddtyagi/webpage-screenshot-mcp) — MCP server for webpage screenshot capture ☆`55`
- [djannot/puppeteer-vision-mcp](https://github.com/djannot/puppeteer-vision-mcp) — Web scraping with AI-driven interaction handling ☆`48`
- [olostep/olostep-mcp-server](https://github.com/olostep/olostep-mcp-server) — Live web scrape, crawl, batch extract, and search ☆`25`
- [wong2/mcp-jina-reader](https://github.com/wong2/mcp-jina-reader) — Jina Reader MCP Server ☆`47`
- [DevEnterpriseSoftware/scrapi-mcp](https://github.com/DevEnterpriseSoftware/scrapi-mcp) — MCP server for using ScrAPI to scrape web pages. ☆`18`
- [levz0r/html-to-markdown-mcp](https://github.com/levz0r/html-to-markdown-mcp) — HTML to Markdown converter using Turndown ☆`26`
- [rohanrav/screeny](https://github.com/rohanrav/screeny) — Screenshots of Mac windows the user has approved ☆`18`
## E-Commerce

- [Azure-Samples/eShopLite](https://github.com/Azure-Samples/eShopLite) — .NET reference store with semantic search and reasoning ☆`169`
- [nicktcode/swissgroceries-mcp](https://github.com/nicktcode/swissgroceries-mcp) — Prices at Migros, Coop, Aldi, Denner and Lidl ☆`43`
- [Dudude-bit/yandex-lavka-mcp](https://github.com/Dudude-bit/yandex-lavka-mcp) — Order Yandex Lavka groceries, after you confirm ☆`25`
- [nexscope-ai/nexscope-ecommerce-api](https://github.com/nexscope-ai/nexscope-ecommerce-api) — Marketplace research, product images and video ☆`18`
- [arthurpanhku/DragonMCP](https://github.com/arthurpanhku/DragonMCP) — MCP server for local life services in Greater China and Asia ☆`22`
- [uju777/coupang-mcp](https://github.com/uju777/coupang-mcp) — Search Coupang products, compare prices and see rocket delivery ☆`18`
## Legal

- [chrisryugj/korean-law-mcp](https://github.com/chrisryugj/korean-law-mcp) — MCP server for Korean statutes, precedents and ordinances ☆`2,854`
- [ilhamfp/pasal](https://github.com/ilhamfp/pasal) — Grounded lookup of Indonesian laws ☆`286`
- [lawchat-oss/mcp-taiwan-legal-db](https://github.com/lawchat-oss/mcp-taiwan-legal-db) — Query Taiwan court decisions and statutes from any ☆`231`
- [AI-WorkDeck/aiworkdeck](https://github.com/AI-WorkDeck/aiworkdeck) — Legal workspace for documents, reviewable edits and sources ☆`174`
- [dealfluence/adeu](https://github.com/dealfluence/adeu) — Edit a Word file as markdown and write back tracked changes ☆`170`
- [ayunis-core/ayunis-legal-mcp](https://github.com/ayunis-core/ayunis-legal-mcp) — An MCP server for German legal codes ☆`91`
- [sboghossian/master-claude-for-legal](https://github.com/sboghossian/master-claude-for-legal) — Starter skills from Anthropic's legal webinar ☆`77`
- [Mahender22/legal-mcp](https://github.com/Mahender22/legal-mcp) — US case law, citations and court filings ☆`69`
- [veronica-builds/emilie](https://github.com/veronica-builds/emilie) — Swiss legal assistant with a local model and an MCP client ☆`32`
- [agentic-ops/legal-mcp](https://github.com/agentic-ops/legal-mcp) — Precedent, statute and contract tools for legal workflows ☆`40`
- [numikel/law-scrapper-mcp](https://github.com/numikel/law-scrapper-mcp) — Polish statutes from the Sejm API ☆`23`
- [Honeyfield-Org/ris-mcp-ts](https://github.com/Honeyfield-Org/ris-mcp-ts) — Austrian statutes and court decisions ☆`20`
- [matematicsolutions/patron](https://github.com/matematicsolutions/patron) — Local workspace for law firms, with a hash-chained audit log ☆`16`
- [protomated/legal-context-ce](https://github.com/protomated/legal-context-ce) — Bridge to a firm's documents, starting with Clio ☆`29`
- [yoda-digital/mcp-cerebra-legal-server](https://github.com/yoda-digital/mcp-cerebra-legal-server) — Legal reasoning with follow-up questions ☆`33`
## Speech-to-Text

- [korovin-aa97/talkthrough-mcp](https://github.com/korovin-aa97/talkthrough-mcp) — Transcripts, keyframes, OCR and speakers from a recording ☆`34`


---

## 🏆 Top 100 by Stars

> The most starred projects in this list, sorted by GitHub stars.

1. [morluto/rea](https://github.com/morluto/rea) — Local CLI and MCP server for agent-assisted reverse engineering. ☆`450,649`
1. [koala73/worldmonitor](https://github.com/koala73/worldmonitor) — News, geopolitics and infrastructure on one dashboard ☆`90,429`
1. [lobehub/lobehub](https://github.com/lobehub/lobehub) — Hire, schedule and report on a team of agents ☆`84,651`
1. [upstash/context7](https://github.com/upstash/context7) — Up-to-date code docs for LLMs ☆`64,550`
1. [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) — Hindsight: Agent Memory That Learns ☆`60,347`
1. [aaif-goose/goose](https://github.com/aaif-goose/goose) — Agent that installs, edits, runs and tests code with any LLM ☆`56,419`
1. [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) — Chrome DevTools for coding agents ☆`55,085`
1. [CherryHQ/cherry-studio](https://github.com/CherryHQ/cherry-studio) — Your AI workspace for models, agents, and productivity. ☆`53,389`
1. [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) — Persistent graph of code, docs and infrastructure ☆`48,430`
1. [LibreChat-AI/LibreChat](https://github.com/LibreChat-AI/LibreChat) — Chat app with agents, MCP and many model providers ☆`46,918`
1. [mindsdb/mindshub](https://github.com/mindsdb/mindshub) — Query Engine for AI Analytics - self-reasoning agents on live data ☆`39,854`
1. [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) — Playwright MCP server ☆`39,472`
1. [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) — "Vibe-Trading: Your Personal Trading Agent" ☆`37,980`
1. [DayuanJiang/next-ai-draw-io](https://github.com/DayuanJiang/next-ai-draw-io) — Draw and edit draw.io diagrams by chatting ☆`36,845`
1. [github/github-mcp-server](https://github.com/github/github-mcp-server) — GitHub's official MCP Server ☆`34,378`
1. [ScrapeGraphAI/Scrapegraph-ai](https://github.com/ScrapeGraphAI/Scrapegraph-ai) — Python scraper based on AI ☆`32,709`
1. [trycua/cua](https://github.com/trycua/cua) — MCP server for CUA platform ☆`32,156`
1. [oraios/serena](https://github.com/oraios/serena) — Semantic code retrieval and editing toolkit ☆`31,278`
1. [assafelovic/gpt-researcher](https://github.com/assafelovic/gpt-researcher) — Autonomous research agent that can use any LLM provider ☆`30,610`
1. [mastra-ai/mastra](https://github.com/mastra-ai/mastra) — TypeScript AI agent framework with RAG ☆`29,459`
1. [PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp) — The fast, Pythonic way to build MCP servers and clients. ☆`28,377`
1. [modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk) — Official Python SDK for MCP servers and clients ☆`24,818`
1. [Skyvern-AI/skyvern](https://github.com/Skyvern-AI/skyvern) — Automate browser based workflows with AI ☆`23,376`
1. [czlonkowski/n8n-mcp](https://github.com/czlonkowski/n8n-mcp) — Build n8n workflows with AI assistants ☆`23,235`
1. [screenpipe/screenpipe](https://github.com/screenpipe/screenpipe) — Search text and audio captured from the screen ☆`22,343`
1. [rocketride-org/rocketride-server](https://github.com/rocketride-org/rocketride-server) — Pipeline engine for LLM workflows, with a C++ core ☆`20,061`
1. [microsoft/mcp-for-beginners](https://github.com/microsoft/mcp-for-beginners) — Cross-language curriculum for learning MCP ☆`17,634`
1. [apache/apisix](https://github.com/apache/apisix) — The Cloud-Native API Gateway and AI Gateway ☆`17,311`
1. [googleapis/mcp-toolbox](https://github.com/googleapis/mcp-toolbox) — Open source database MCP toolbox ☆`16,836`
1. [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) — Figma layout info for AI coding agents ☆`16,189`
1. [apify/apify-mcp-server](https://github.com/apify/apify-mcp-server) — MCP server for Apify web scraping and data extraction ☆`15,666`
1. [modelcontextprotocol/typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk) — Official TypeScript SDK for MCP ☆`13,740`
1. [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) — IDA Pro reverse engineering with AI ☆`13,436`
1. [elie222/inbox-zero](https://github.com/elie222/inbox-zero) — AI email assistant for inbox zero ☆`12,977`
1. [zilliztech/claude-context](https://github.com/zilliztech/claude-context) — Code search for Claude Code agents ☆`12,686`
1. [tadata-org/fastapi_mcp](https://github.com/tadata-org/fastapi_mcp) — Expose FastAPI endpoints as MCP tools ☆`12,028`
1. [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) — MCP Server for Ghidra ☆`11,884`
1. [modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector) — Deterministic testing tools for MCP servers ☆`11,266`
1. [mcp-use/mcp-use](https://github.com/mcp-use/mcp-use) — Framework for MCP apps and servers ☆`10,863`
1. [instantdb/instant](https://github.com/instantdb/instant) — Modern Firebase with real-time database ☆`10,561`
1. [mobile-next/mobile-mcp](https://github.com/mobile-next/mobile-mcp) — Mobile automation for iOS, Android, emulators ☆`10,480`
1. [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) — Terminal control, file search, diff editing ☆`10,283`
1. [awslabs/mcp](https://github.com/awslabs/mcp) — AWS MCP servers for AI assistants ☆`9,904`
1. [modelcontextprotocol/modelcontextprotocol](https://github.com/modelcontextprotocol/modelcontextprotocol) — Specification and documentation for MCP ☆`9,655`
1. [maximhq/bifrost](https://github.com/maximhq/bifrost) — Open-source gateway for models, MCP and agents, with failover ☆`9,488`
1. [mark3labs/mcp-go](https://github.com/mark3labs/mcp-go) — Go implementation of MCP ☆`9,233`
1. [superradcompany/microsandbox](https://github.com/superradcompany/microsandbox) — Local microVM runtime and library ☆`9,015`
1. [lastmile-ai/mcp-agent](https://github.com/lastmile-ai/mcp-agent) — Build agents with MCP and workflow patterns ☆`8,580`
1. [idosal/git-mcp](https://github.com/idosal/git-mcp) — Free remote MCP for any GitHub project ☆`8,512`
1. [repowise-dev/repowise](https://github.com/repowise-dev/repowise) — Code health, generated docs, dead code and git analytics ☆`8,101`
1. [Upsonic/Upsonic](https://github.com/Upsonic/Upsonic) — Build autonomous AI agents in Python. ☆`7,969`
1. [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server) — Web scraping and search for LLM clients ☆`7,797`
1. [modelcontextprotocol/registry](https://github.com/modelcontextprotocol/registry) — Community registry of MCP servers ☆`7,455`
1. [Tencent/AI-Infra-Guard](https://github.com/Tencent/AI-Infra-Guard) — Red-team scans of agents, MCP servers and jailbreaks ☆`7,450`
1. [BrowserMCP/mcp](https://github.com/BrowserMCP/mcp) — Browser control for AI applications ☆`7,332`
1. [grab/cursor-talk-to-figma-mcp](https://github.com/grab/cursor-talk-to-figma-mcp) — Cursor and Figma communication ☆`7,101`
1. [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) — WhatsApp MCP server ☆`6,856`
1. [GreptimeTeam/greptimedb](https://github.com/GreptimeTeam/greptimedb) — Unified observability DB for metrics, logs, traces ☆`6,802`
1. [Coding-Solo/godot-mcp](https://github.com/Coding-Solo/godot-mcp) — MCP server for Godot game engine ☆`6,599`
1. [genkit-ai/genkit](https://github.com/genkit-ai/genkit) — AI app framework for JavaScript and Go ☆`6,580`
1. [getsentry/MobileBuildMCP](https://github.com/getsentry/MobileBuildMCP) — MCP server for Xcode build operations ☆`6,562`
1. [kucherenko/jscpd](https://github.com/kucherenko/jscpd) — Find copy-pasted code across more than 200 languages ☆`6,526`
1. [21st-dev/magic-mcp](https://github.com/21st-dev/magic-mcp) — Frontend development with AI like Magic ☆`6,455`
1. [ThinkInAIXYZ/deepchat](https://github.com/ThinkInAIXYZ/deepchat) — Desktop assistant that connects models to personal tools ☆`6,387`
1. [Q00/ouroboros](https://github.com/Q00/ouroboros) — Agent that proposes changes, then evaluates them under a budget ☆`6,345`
1. [baserow/baserow](https://github.com/baserow/baserow) — No-code database, apps, agents with AI ☆`6,316`
1. [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) — MCP server for Atlassian tools (Confluence, Jira) ☆`6,112`
1. [agentgateway/agentgateway](https://github.com/agentgateway/agentgateway) — Proxy in front of AI agents and MCP servers ☆`6,081`
1. [executeautomation/mcp-playwright](https://github.com/executeautomation/mcp-playwright) — MCP server for Playwright browser testing ☆`5,682`
1. [KnockOutEZ/wigolo](https://github.com/KnockOutEZ/wigolo) — Local web search, fetch and crawl, with no API key ☆`5,536`
1. [openclaw/Peekaboo](https://github.com/openclaw/Peekaboo) — macOS screenshot and window capture MCP server ☆`5,470`
1. [lingodotdev/lingo.dev](https://github.com/lingodotdev/lingo.dev) — MCP server for Lingo localization platform ☆`5,402`
1. [nanbingxyz/5ire](https://github.com/nanbingxyz/5ire) — Desktop assistant and MCP client, with a local knowledge base ☆`5,370`
1. [modelcontextprotocol/go-sdk](https://github.com/modelcontextprotocol/go-sdk) — Official Go SDK for MCP servers and clients ☆`5,328`
1. [callstack/agent-device](https://github.com/callstack/agent-device) — Control phones, browsers, TVs and desktop apps on devices ☆`5,319`
1. [Kiln-AI/Kiln](https://github.com/Kiln-AI/Kiln) — Build AI systems with Evals, RAG, Agents, fine-tuning ☆`5,268`
1. [atilaahmettaner/tradingview-mcp](https://github.com/atilaahmettaner/tradingview-mcp) — Screeners and backtests for crypto, stocks and forex ☆`5,257`
1. [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) — Exa MCP for web search and web crawling! ☆`5,225`
1. [IBM/mcp-context-forge](https://github.com/IBM/mcp-context-forge) — Gateway and registry in front of MCP, A2A and REST APIs ☆`4,784`
1. [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server) — Official Notion MCP Server ☆`4,704`
1. [google/mcp](https://github.com/google/mcp) — Google MCP ☆`4,696`
1. [modelcontextprotocol/csharp-sdk](https://github.com/modelcontextprotocol/csharp-sdk) — Official C# SDK for MCP servers and clients ☆`4,625`
1. [IvanMurzak/Unity-MCP](https://github.com/IvanMurzak/Unity-MCP) — AI-powered bridge connecting LLMs to Unity Editor ☆`4,615`
1. [basicmachines-co/basic-memory](https://github.com/basicmachines-co/basic-memory) — AI conversations that remember context ☆`4,550`
1. [MarkusPfundstein/mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) — Obsidian integration via REST API plugin ☆`4,530`
1. [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) — Cloudflare services management ☆`4,457`
1. [archestra-ai/archestra](https://github.com/archestra-ai/archestra) — Enterprise AI guardrails, registry, gateway, and orchestrator ☆`4,437`
1. [open-webui/mcpo](https://github.com/open-webui/mcpo) — A simple, secure MCP-to-OpenAPI proxy server ☆`4,422`
1. [antvis/mcp-server-chart](https://github.com/antvis/mcp-server-chart) — 25+ visual charts using @antvis for data analysis ☆`4,416`
1. [CodeGraphContext/CodeGraphContext](https://github.com/CodeGraphContext/CodeGraphContext) — Code graph indexing for AI context ☆`4,408`
1. [haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server) — Excel file manipulation ☆`4,290`
1. [nowork-studio/notfair-plugin](https://github.com/nowork-studio/notfair-plugin) — SEO and marketing skills for agents ☆`4,138`
1. [modelcontextprotocol/rust-sdk](https://github.com/modelcontextprotocol/rust-sdk) — The official Rust SDK for the Model Context Protocol ☆`4,104`
1. [dagger/container-use](https://github.com/dagger/container-use) — MCP server for container orchestration ☆`4,088`
1. [skyhook-io/radar](https://github.com/skyhook-io/radar) — Kubernetes UI with issues, topology and a built-in MCP server ☆`4,086`
1. [samuelgursky/davinci-resolve-mcp](https://github.com/samuelgursky/davinci-resolve-mcp) — MCP server integration for DaVinci Resolve Studio ☆`4,044`
1. [microsoft/mcp](https://github.com/microsoft/mcp) — Catalog of official Microsoft MCP servers ☆`3,843`
1. [bytebase/dbhub](https://github.com/bytebase/dbhub) — Token-efficient multi-database MCP ☆`3,825`
1. [modelcontextprotocol/java-sdk](https://github.com/modelcontextprotocol/java-sdk) — Official Java SDK for MCP servers and clients ☆`3,765`
1. [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana) — MCP server for Grafana ☆`3,658`

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Feedback

Found something wrong? Open an issue or submit a pull request — contributions are welcome!

## Credits

- [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers)
- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)
- [appcypher/awesome-mcp-servers](https://github.com/appcypher/awesome-mcp-servers)
- [wong2/awesome-mcp-servers](https://github.com/wong2/awesome-mcp-servers)
- [All Contributors](https://github.com/abordage/awesome-mcp/graphs/contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
