# Awesome MCP

![Awesome](https://raw.githubusercontent.com/abordage/schemas/main/badges/awesome.svg)
[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-mcp?label=last%20update)](README.md)
![Repositories](https://img.shields.io/badge/repositories-2,524-06b6d4)
![Total Stars](https://img.shields.io/badge/total%20stars-2,628,264-gold)
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

- [oraios/serena](https://github.com/oraios/serena) — Semantic code retrieval and editing toolkit ☆`31,071`
- [zilliztech/claude-context](https://github.com/zilliztech/claude-context) — Code search for Claude Code agents ☆`12,668`
- [Q00/ouroboros](https://github.com/Q00/ouroboros) — Agent OS: the agent gets smarter on its own. We just hold the line: Interview-gated, staged evaluation, budgeted evolution loop. MCP server, 14 runtimes: Claude Code, Codex CLI, ☆`6,315`
- [CodeGraphContext/CodeGraphContext](https://github.com/CodeGraphContext/CodeGraphContext) — Code graph indexing for AI context ☆`4,374`
- [ezyang/codemcp](https://github.com/ezyang/codemcp) — Coding assistant MCP for Claude Desktop ☆`1,604`
- [ref-tools/ref-tools-mcp](https://github.com/ref-tools/ref-tools-mcp) — Reference tools for coding agents ☆`1,184`
- [mybolide/coding-tools-mcp](https://github.com/mybolide/coding-tools-mcp) — Desktop MCP workspace for file edits, command execution and session history ☆`436`
- [SDGLBL/mcp-claude-code](https://github.com/SDGLBL/mcp-claude-code) — MCP implementation of Claude Code capabilities and more ☆`305`
- [cafeTechne/antigravity-link-extension](https://github.com/cafeTechne/antigravity-link-extension) — Mobile companion for Google's Antigravity IDE. Mirror AI sessions on your phone, send messages, stop generation, automate via 9 MCP tools or OpenAPI. ☆`222`
- [freema/openclaw-mcp](https://github.com/freema/openclaw-mcp) — MCP server for OpenClaw - secure bridge between Claude.ai and your self-hosted OpenClaw assistant with OAuth2 authentication ☆`188`
- [stippi/code-assistant](https://github.com/stippi/code-assistant) — LLM-powered autonomous coding assistant ☆`186`
- [aresyn/codex-control-plane-mcp](https://github.com/aresyn/codex-control-plane-mcp) — Durable MCP control plane for long-running Codex Desktop tasks ☆`124`
- [archcore-ai/archcore](https://github.com/archcore-ai/archcore) — Git-native context engineering and spec-driven development for AI coding agents ☆`74`
- [lamemind/mcp-server-multiverse](https://github.com/lamemind/mcp-server-multiverse) — MCP server for multiverse context management ☆`82`
- [sshahzaiib/agy-bridge](https://github.com/sshahzaiib/agy-bridge) — MCP bridge that lets Claude Code delegate heavy tasks to the Antigravity CLI (agy) - purpose-built tools, model routing with fallback, session continuity, and output truncation ☆`60`
- [contextstream/mcp-server](https://github.com/contextstream/mcp-server) — Shared project context for AI coding agents across MCP clients ☆`45`
- [wende/cicada](https://github.com/wende/cicada) — AI Coders search blindly. Be their guide. ☆`41`
- [mybolide/mcp-probe-kit](https://github.com/mybolide/mcp-probe-kit) — Spec-driven development workflow MCP with resumable plans and a converge gate ☆`41`
- [gabrielmaialva33/winx-code-agent](https://github.com/gabrielmaialva33/winx-code-agent) — MCP-powered code agent for development ☆`38`
- [religa/multi_mcp](https://github.com/religa/multi_mcp) — Multi-Model chat, code review and analysis MCP Server for Claude Code ☆`36`
- [josephsenior/Grinta-Coding-Agent](https://github.com/josephsenior/Grinta-Coding-Agent) — Local-first resilient terminal coding agent with MCP ☆`32`
- [Touchpoint-Labs/Touchpoint](https://github.com/Touchpoint-Labs/Touchpoint) — Give your AI agent eyes and hands on any desktop - cross-platform accessibility API with MCP server ☆`47`
- [bshea-1/Routed](https://github.com/bshea-1/Routed) — Universal local router for Agent Skills across AI coding environments ☆`28`
- [REX-codebase/fable-mode](https://github.com/REX-codebase/fable-mode) — Open-source MCP control plane for AI coding agents: mechanical time-locks, evidence-gated proof receipts, red-team remediation, and persistent engineering memory. ☆`26`
- [x51xxx/codex-mcp-tool](https://github.com/x51xxx/codex-mcp-tool) — Claude/Cursor to Codex CLI bridge with multi-turn sessions ☆`24`
- [alpadalar/netops-mcp](https://github.com/alpadalar/netops-mcp) — MCP server with 30 network diagnostic tools: ping, traceroute, mtr, nmap, DNS, TLS, HTTP and system monitoring. ☆`16`
- [abnegate/magents](https://github.com/abnegate/magents) — Shared session bus for Claude Code, Codex, and Cursor ☆`16`
- [Sim-xia/skill-cortex-server](https://github.com/Sim-xia/skill-cortex-server) — A third-party MCP server that enable all IDEs to access Claude Code Skills capabilities ☆`24`
- [eirikb/any-cli-mcp-server](https://github.com/eirikb/any-cli-mcp-server) — Convert any (whatever) CLI to proper MCP server with tools mapped based on CLI help ☆`24`
- [VertexStudio/developer](https://github.com/VertexStudio/developer) — File editing, shell execution, screen capture ☆`20`
- [HendryAvila/Hoofy](https://github.com/HendryAvila/Hoofy) — Hoofy - AI development companion MCP server. Persistent memory, spec-driven development, adaptive change pipeline, Clarity Gate. 32 tools, single Go binary, zero deps. ☆`16`
### Human-in-the-Loop

- [ttommyth/interactive-mcp](https://github.com/ttommyth/interactive-mcp) — Interactive MCP server for human-in-the-loop AI ☆`351`
- [RapidataAI/human-use](https://github.com/RapidataAI/human-use) — Enable AI to ask anyone anything ☆`73`
- [gotohuman/gotohuman-mcp-server](https://github.com/gotohuman/gotohuman-mcp-server) — Human approvals for AI agentic workflows ☆`52`
- [nazar256/user-prompt-mcp](https://github.com/nazar256/user-prompt-mcp) — User input requests for Cursor ☆`21`
### Multi-Agent

- [rinadelph/Agent-MCP](https://github.com/rinadelph/Agent-MCP) — Multi-agent AI collaboration framework ☆`1,304`
- [Get-Concord-AI/concord-mcp](https://github.com/Get-Concord-AI/concord-mcp) — Local-first shared work-state for coding agents with presence, file claims, messaging, handoffs and review packets ☆`906`
- [roboticforce/sugar](https://github.com/roboticforce/sugar) — Local persistent memory, cross-session context, and optional tasks ☆`100`
### Reasoning & Prompts

- [ooples/token-optimizer-mcp](https://github.com/ooples/token-optimizer-mcp) — Token optimization with caching and compression ☆`567`
- [PV-Bhat/vibe-check-mcp-server](https://github.com/PV-Bhat/vibe-check-mcp-server) — Mentor-like feedback tool preventing AI over-engineering ☆`504`
- [Rai220/think-mcp](https://github.com/Rai220/think-mcp) — MCP Server for reasoning ☆`107`
- [hyperb1iss/lucidity-mcp](https://github.com/hyperb1iss/lucidity-mcp) — MCP server for enhanced AI clarity and reasoning ☆`90`
- [YuChenSSR/multi-ai-advisor-mcp](https://github.com/YuChenSSR/multi-ai-advisor-mcp) — council of models for decision ☆`89`
- [nikkoxgonzales/crash-mcp](https://github.com/nikkoxgonzales/crash-mcp) — Structured reasoning with step validation ☆`72`
- [VoDaiLocz/kilo-kit-mcp](https://github.com/VoDaiLocz/kilo-kit-mcp) — An MCP server for safer coding agents: skill routing, C4 workflow gates, memory checks, and verification before completion. ☆`27`
- [gwbischof/free-will-mcp](https://github.com/gwbischof/free-will-mcp) — Experimental AI self-prompting MCP server ☆`38`
- [aquarius-wing/actor-critic-thinking-mcp](https://github.com/aquarius-wing/actor-critic-thinking-mcp) — Dual-perspective thinking analysis server ☆`32`
- [ejentum/ejentum-mcp](https://github.com/ejentum/ejentum-mcp) — Agent loop with reasoning, code, memory, and anti-deception ☆`16`
- [vasayxtx/mcp-prompt-engine](https://github.com/vasayxtx/mcp-prompt-engine) — MCP Prompt Engine ☆`18`
- [abhinav-mangla/inner-monologue-mcp](https://github.com/abhinav-mangla/inner-monologue-mcp) — Inner Monologue MCP Server ☆`17`
- [abhinav-mangla/think-tool-mcp](https://github.com/abhinav-mangla/think-tool-mcp) — MCP Think Tool Server ☆`16`
## AI Memory & RAG

### Memory

- [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) — Hindsight: Agent Memory That Learns ☆`58,564`
- [basicmachines-co/basic-memory](https://github.com/basicmachines-co/basic-memory) — AI conversations that remember context ☆`4,468`
- [vshulcz/deja-vu](https://github.com/vshulcz/deja-vu) — Claude Code memory, Codex memory, Cursor memory, OpenCode memory, Gemini CLI memory, Windsurf memory & Cline memory across 44 agents. AI coding memory, Claude Code history, ☆`1,400`
- [shaneholloman/mcp-knowledge-graph](https://github.com/shaneholloman/mcp-knowledge-graph) — MCP server enabling persistent memory for Claude through a local knowledge graph - fork focused on local development ☆`887`
- [riponcm/projectmem](https://github.com/riponcm/projectmem) — Open-source coding agents memory. Records issues, attempts, fixes and decisions, then warns your agent before it repeats an approach that already failed. Native MCP server for ☆`877`
- [agentic-box/memora](https://github.com/agentic-box/memora) — Persistent shared memories in SQLite ☆`746`
- [Ikalus1988/MisakaNet](https://github.com/Ikalus1988/MisakaNet) — Re-debugging Solved Failures? No Way. 500+ Evidence-graded fix lessons, One MCP Call-->https://misakanet.org ☆`553`
- [MaxFreedomPollard/Compartment](https://github.com/MaxFreedomPollard/Compartment) — Offline AEAD-encrypted vector memory without network ☆`580`
- [syncable-dev/memtrace-public](https://github.com/syncable-dev/memtrace-public) — Structural memory for AI coding agents. Bi-temporal graph, MCP-native, zero LLM calls. Cursor · Claude Code · Codex · DeepSeek Harness · Hermes · VS Code · Windsurf. ☆`511`
- [Beever-AI/beever-atlas](https://github.com/Beever-AI/beever-atlas) — LLM Wiki memory for team chat (Slack, Discord, Teams) ☆`451`
- [gannonh/memento-mcp](https://github.com/gannonh/memento-mcp) — Memento MCP: A Knowledge Graph Memory System for LLMs ☆`426`
- [mcpware/cross-code-organizer](https://github.com/mcpware/cross-code-organizer) — Cross-Code Organizer (formerly Claude Code Organizer): cross-harness config dashboard for Claude Code, Codex CLI, MCP servers, skills, memories, agents, sessions, security ☆`386`
- [Goldentrii/AgentRecall-X](https://github.com/Goldentrii/AgentRecall-X) — Correction-first persistent memory for AI agents. MCP server + SDK + CLI. Compounds across sessions. ☆`373`
- [CheMiguel23/MemoryMesh](https://github.com/CheMiguel23/MemoryMesh) — MCP server for knowledge graph memory ☆`354`
- [qualixar/superlocalmemory](https://github.com/qualixar/superlocalmemory) — Open-source governed, local-first memory control plane for AI agents and teams. arXiv:2608.08253 ☆`271`
- [roomi-fields/notebooklm-mcp](https://github.com/roomi-fields/notebooklm-mcp) — Google Gemini Notebook (formerly NotebookLM) over MCP + a local HTTP REST API. Citation-backed Q&A, full Studio generation, chat history, multi-account rotation. For Claude Code, ☆`219`
- [alibaizhanov/mengram](https://github.com/alibaizhanov/mengram) — Human-like memory for AI agents - semantic, episodic & procedural. Experience-driven procedures that learn from failures. Free API, Python & JS SDKs, LangChain, CrewAI & OpenClaw ☆`206`
- [sandbaseai/cli](https://github.com/sandbaseai/cli) — Open-source AI CLI and local MCP server connecting 25 clients-Claude Code, Cursor, Codex, ChatGPT, Hermes, and OpenClaw-to 2,000+ models/APIs, with OAuth and rollback. ☆`185`
- [Patdolitse/piia-engram](https://github.com/Patdolitse/piia-engram) — Local-first AI memory you can see, edit, and override - portable across Claude Code, Codex, Cursor, Windsurf, and other MCP coding tools. ☆`165`
- [dnotitia/akb](https://github.com/dnotitia/akb) — AKB - Agent Knowledgebase. Organizational memory for AI agents: vault-scoped docs / tables / files unified by URI graph, served over MCP. ☆`165`
- [pi22by7/In-Memoria](https://github.com/pi22by7/In-Memoria) — Persistent Intelligence Infrastructure for AI Agents ☆`175`
- [jean-technologies/jean-memory](https://github.com/jean-technologies/jean-memory) — AI memory with mem0 and graphiti ☆`171`
- [redleaves/context-keeper](https://github.com/redleaves/context-keeper) — Intelligent memory and context for AI agents ☆`156`
- [Bevel-Software/Hexis](https://github.com/Bevel-Software/Hexis) — Centrally manage AI-agent skills, tools, context, permissions, and identity across your entire org. Self-hosted, Git-backed and MCP-native. ☆`122`
- [DrDroidLab/open-index](https://github.com/DrDroidLab/open-index) — Structured context graphs with hybrid search and writes ☆`113`
- [HiAi-gg/docsmint](https://github.com/HiAi-gg/docsmint) — Open-source knowledge base for people and AI agents. Rich-text editing, hybrid search, GraphRAG, and MCP. Self-host with Docker or use DocsMint Cloud. ☆`110`
- [unibaseio/membase](https://github.com/unibaseio/membase) — Decentralized memory layer for AI agents ☆`100`
- [2b3pro/roam-research-mcp](https://github.com/2b3pro/roam-research-mcp) — MCP Server and CLI tool for Roam Research Graph Integration ☆`100`
- [IvenKooLab/loci](https://github.com/IvenKooLab/loci) — Shared memory for AI coding tools: hybrid search, cited Q&A, harness memory discovery and a built-in Web console. Local index, MCP + HTTP. ☆`101`
- [dweigend/joplin-mcp-server](https://github.com/dweigend/joplin-mcp-server) — A Model Context Protocol (MCP) Server for https://joplinapp.org/ that enables note access through the https://modelcontextprotocol.io. Perfect for integration with AI assistants ☆`96`
- [pinkpixel-dev/mem0-mcp](https://github.com/pinkpixel-dev/mem0-mcp) — A memory system using mem0 for AI applications. Enables long-term memory for AI agents as a drop-in MCP server. ☆`96`
- [zcag/tela](https://github.com/zcag/tela) — Open-source, self-hostable markdown team wiki with a built-in MCP server - so AI agents read, write, and search your docs as first-class teammates. Live multiplayer, semantic + ☆`91`
- [dodopayments/context-mcp](https://github.com/dodopayments/context-mcp) — Self-hosted MCP server for your documentation ☆`87`
- [spences10/mcp-memory-libsql](https://github.com/spences10/mcp-memory-libsql) — High-performance persistent memory system for Model Context Protocol (MCP) powered by libSQL. Features vector search, semantic knowledge storage, and efficient relationship ☆`87`
- [James-Chahwan/repo-graph](https://github.com/James-Chahwan/repo-graph) — Structural graph memory for AI coding assistants - MCP server for codebase navigation ☆`87`
- [kunwar-shah/claudex](https://github.com/kunwar-shah/claudex) — MCP server with persistent memory + FTS5 search for Claude Code conversation history. Index your ~/.claude/projects/, expose 10 MCP tools, browse via web UI. MIT-licensed. ☆`97`
- [cdeust/Cortex](https://github.com/cdeust/Cortex) — Cross-platform persistent memory MCP for Codex, Gemini CLI, Claude Code, and other local MCP hosts. 36 cited neuroscience mechanisms, local-first SQLite/PostgreSQL, hybrid ☆`76`
- [vbcherepanov/total-agent-memory](https://github.com/vbcherepanov/total-agent-memory) — Persistent local memory for AI coding agents - Claude Code, Codex CLI, Cursor, any MCP client. Temporal knowledge graph, procedural memory, AST codebase ingest, cross-project ☆`74`
- [ukkit/memcord](https://github.com/ukkit/memcord) — MCP server for memory and context management ☆`74`
- [writerslogic/scrivener-mcp](https://github.com/writerslogic/scrivener-mcp) — The definitive MCP server for Scrivener - connect your novels, screenplays, and manuscripts to Claude, ChatGPT, and any AI assistant. 53 tools: document management, writing ☆`70`
- [Abhigyan-Shekhar/Waggle-mcp](https://github.com/Abhigyan-Shekhar/Waggle-mcp) — MCP server for external memory layer for AI agents + more . Download from pypi , and get started ☆`44`
- [SecurityRonin/docx-mcp](https://github.com/SecurityRonin/docx-mcp) — MCP server for reading and editing Word (.docx) documents with track changes, comments, footnotes, and structural validation ☆`67`
- [knowall-ai/mcp-reverie](https://github.com/knowall-ai/mcp-reverie) — Memory management using Neo4j graphs ☆`67`
- [decisionnode/DecisionNode](https://github.com/decisionnode/DecisionNode) — CLI + Local MCP - A shared structured memory store across Claude Code, Cursor, Windsurf, Antigravity, and every MCP client. Semantically queryable. ☆`82`
- [max-ramas/rms-memory-mcp](https://github.com/max-ramas/rms-memory-mcp) — Persistent, local, cross-IDE memory for AI agents - markdown source of truth, LanceDB-powered semantic search, zero cloud dependency ☆`64`
- [ZengLiangYi/ChatCrystal](https://github.com/ZengLiangYi/ChatCrystal) — Local-first AI PKM for coding conversations: import Claude Code/Cursor/Codex, distill notes, semantic search, tag graph, MCP memory. ☆`61`
- [JinyangWang27/people-context](https://github.com/JinyangWang27/people-context) — Local-first memory for AI agents about the people in your life. MCP server + CLI on SQLite. Never phones home. ☆`59`
- [CamdenClark/anki-mcp-server](https://github.com/CamdenClark/anki-mcp-server) — A model context protocol server that connects to Anki through AnkiConnect ☆`80`
- [roampal-ai/roampal-core](https://github.com/roampal-ai/roampal-core) — Outcome-based persistent memory MCP server for Claude Code and OpenCode. Good advice promoted, bad advice demoted. pip install roampal. ☆`54`
- [pallaprolus/mendeley-mcp](https://github.com/pallaprolus/mendeley-mcp) — MCP server for Mendeley reference manager - search, retrieve, and manage your academic library from Claude and other MCP clients ☆`47`
- [jasperket/clanki](https://github.com/jasperket/clanki) — An MCP server for connecting LLMs with Anki Flashcards. ☆`45`
- [DollhouseMCP/mcp-server](https://github.com/DollhouseMCP/mcp-server) — A Free, Open Source MCP server for dynamic custom persona management with public a GitHub collection of personas, skills, templates, and other elements for AI models. ☆`46`
- [BetaBots-LLC/callimachus](https://github.com/BetaBots-LLC/callimachus) — One local, searchable index of your AI coding-agent history Claude Code, Codex, Cursor, Gemini & more. Keyword + semantic search, MCP server, CLI & VS Code extension. ☆`46`
- [dailydaniel/logseq-mcp](https://github.com/dailydaniel/logseq-mcp) — simple logseq mcp server ☆`43`
- [peless/claude-thread-continuity](https://github.com/peless/claude-thread-continuity) — Save and restore project context ☆`65`
- [IzumiSy/mcp-duckdb-memory-server](https://github.com/IzumiSy/mcp-duckdb-memory-server) — MCP Memory Server with DuckDB backend ☆`59`
- [linxule/lotus-wisdom-mcp](https://github.com/linxule/lotus-wisdom-mcp) — Contemplative reasoning MCP server - Lotus Sutra wisdom framework with interactive ext-apps journey visualization. ☆`37`
- [crewAIInc/enterprise-mcp-server](https://github.com/crewAIInc/enterprise-mcp-server) — MCP Server for kicking off and getting status of your crew deployments ☆`60`
- [hungryrobot1/MCP-PIF](https://github.com/hungryrobot1/MCP-PIF) — Personal intelligence framework in Haskell ☆`57`
- [majiayu000/remem](https://github.com/majiayu000/remem) — Local-first persistent memory for Claude Code & Codex CLI - Rust CLI, hooks, MCP server, SQLite/SQLCipher, auditable recall for long-running coding work. ☆`34`
- [knaisoma/data-olympus](https://github.com/knaisoma/data-olympus) — Governance-grade, OKF-compatible knowledge-base format with a single-writer MCP server and CLI. Pre-release. ☆`31`
- [Yuchen20/Memory-Plus](https://github.com/Yuchen20/Memory-Plus) — Enhanced persistent memory management ☆`56`
- [nicholasglazer/gnosis-mcp](https://github.com/nicholasglazer/gnosis-mcp) — Zero-config MCP server for searchable documentation (SQLite default, PostgreSQL optional) ☆`30`
- [novyxlabs/novyx-mcp](https://github.com/novyxlabs/novyx-mcp) — MCP tools for Novyx governed actions, shared memory, audit, rollback, and evidence workflows. ☆`29`
- [T1nker-1220/memories-with-lessons-mcp-server](https://github.com/T1nker-1220/memories-with-lessons-mcp-server) — I enhance the existing memory mcp server from the official mcp github, so big thanks and credits for creating this ☆`52`
- [mnemoverse/mcp-memory-server](https://github.com/mnemoverse/mcp-memory-server) — Hosted memory that re-ranks recall by reported outcomes ☆`28`
- [jagoff/memo](https://github.com/jagoff/memo) — Your coding agent starts every session with amnesia - memo fixes that, 100% on your machine. Persistent memory for Claude Code, Codex, Cursor & any MCP client: Markdown source of ☆`26`
- [Siddhant-K-code/mcp-apple-notes](https://github.com/Siddhant-K-code/mcp-apple-notes) — MCP server for apple notes ☆`25`
- [Siddhant-K-code/memory-journal-mcp-server](https://github.com/Siddhant-K-code/memory-journal-mcp-server) — MCP server designed to help you search and analyze your photo library (iCloud - Apple photos) ☆`25`
- [masondelan/selvedge](https://github.com/masondelan/selvedge) — Persistent decision memory for AI agents: rationale, rejected approaches, and entity history. Connect any compatible agent through local MCP or the CLI. ☆`26`
- [JamesANZ/memory-mcp](https://github.com/JamesANZ/memory-mcp) — Shared memory store and retrieval for multiple LLMs ☆`23`
- [SaravananJaichandar/world-model-mcp](https://github.com/SaravananJaichandar/world-model-mcp) — world-model-mcp is a signed audit memory server for AI coding agents, delivered as an MCP tool. Every event Ed25519-signed and Merkle-chained; offline-verifiable against pinned ☆`24`
- [olgasafonova/mediawiki-mcp-server](https://github.com/olgasafonova/mediawiki-mcp-server) — MCP server for MediaWiki wikis - search, read, and edit wiki content from AI assistants ☆`23`
- [jamjet-labs/jamjet](https://github.com/jamjet-labs/jamjet) — The open-source safety layer for AI agents - block unsafe tool calls, require approval, enforce budgets, audit, replay. ☆`23`
- [terrizoaguimor/celiums-memory](https://github.com/terrizoaguimor/celiums-memory) — Open-source cognitive engine for AI agents - persistent memory, a first-person journal, a four-layer ethics engine, and a per-user biological clock, over MCP. Apache-2.0. ☆`23`
- [get-engram/engram](https://github.com/get-engram/engram) — Persistent, searchable long-term memory for AI agents. MCP-native. Works with ChatGPT, Claude, Cursor, and any MCP client. ☆`22`
- [Destrayon/Connapse](https://github.com/Destrayon/Connapse) — Self-hosted knowledge base and memory for AI agents. MCP server and REST API with hybrid search, reranking and per-user permissions over your files, S3, Azure Blob, GitHub, ☆`22`
- [VonderVuflya/Yggdrasil](https://github.com/VonderVuflya/Yggdrasil) — Durable, local-first memory for AI coding agents over MCP - zero-dependency, curated & semantically de-duped, you own the data (SQLite + Markdown). Works with Claude Code, Codex ☆`22`
- [paladini/mcp-me](https://github.com/paladini/mcp-me) — Your AI assistants don't know who you are. mcp-me fixes that: a local MCP server that gives any AI a full picture of who you are ☆`21`
- [Mnemosyne-OS/Mnemosyne-Neural-OS](https://github.com/Mnemosyne-OS/Mnemosyne-Neural-OS) — A control room for AI memory. Your files and conversations become searchable memory any model you connect can draw on, and you decide what enters, what moves and what leaves. ☆`21`
- [hjqcan/GoodMemory](https://github.com/hjqcan/GoodMemory) — Local-first, auditable memory layer for AI apps and coding agents - Codex, Claude Code, MCP, HTTP, TypeScript, and Python. ☆`20`
- [grooverLab/fable](https://github.com/grooverLab/fable) — High-fidelity transcript memory for Claude Code - index every session, recall byte-identical, search, prune, compose. Local-first, stdlib-only, MCP. ☆`19`
- [JinNing6/Noosphere](https://github.com/JinNing6/Noosphere) — The live network for high-quality Agent Skills - discover the latest verified versions, publish your own, and communicate agent-to-agent via MCP. ☆`18`
- [ihorponom/agentpack](https://github.com/ihorponom/agentpack) — Local task-state ledger for AI coding agents. Preserve decisions, source conclusions, evidence, and checkpoints across Codex, Claude Code, Cursor, and other MCP clients. ☆`18`
- [epicsagas/alcove](https://github.com/epicsagas/alcove) — Alcove is an MCP server that gives AI coding agents on-demand access to your private project docs - BM25 + vector hybrid search for precision retrieval, tree-sitter code indexing ☆`17`
- [AtlasCloudAI/mcp-server](https://github.com/AtlasCloudAI/mcp-server) — MCP server for Atlas Cloud - AI API aggregation platform for image/video generation and LLM ☆`17`
- [graphpilot-oss/graphpilot](https://github.com/graphpilot-oss/graphpilot) — Structural memory for coding agents - index your repo once, query symbols, callers, and call-edges over MCP. ☆`17`
- [skydeckai/mcp-server-rememberizer](https://github.com/skydeckai/mcp-server-rememberizer) — An MCP Server to enable global access to Rememberizer ☆`36`
- [michielinksee/linksee-memory](https://github.com/michielinksee/linksee-memory) — Local-first agent memory MCP - cross-agent brain with token-saving file diff cache. By Synapse Arrows. ☆`16`
- [remembra-ai/remembra](https://github.com/remembra-ai/remembra) — Remembra Relay: one agent stops, the next one already knows. Session handoffs built from git facts, for the next coding agent in any MCP tool, on any machine. MCP server + CLI. ☆`16`
- [ryanjoachim/mcp-rtfm](https://github.com/ryanjoachim/mcp-rtfm) — Ever been told to RTFM only to find there is no FM to R? MCP-RTFM helps you CREATE the Fing Manual that people keep telling everyone to read! Transform your non-existent or ☆`35`
- [stagsz/Unconventional-thinking](https://github.com/stagsz/Unconventional-thinking) — An MCP server for unconventional and boundary-breaking problem-solving through an advanced note-taking system. ☆`30`
- [9Ninety/MCPNotes](https://github.com/9Ninety/MCPNotes) — A simple note-taking MCP server for recording and managing notes with AI models. ☆`37`
- [Sivan22/mcp-sefaria-server](https://github.com/Sivan22/mcp-sefaria-server) — Fetch and read Jewish texts through the API of Sefaria.org ☆`35`
- [TheStack-ai/jarvis-orb](https://github.com/TheStack-ai/jarvis-orb) — See AI thinking in real time - 3D orb that visualizes Claude Code reasoning. Free, open-source MCP server ☆`24`
- [SecretiveShell/MCP-llms-txt](https://github.com/SecretiveShell/MCP-llms-txt) — MCP server for SecretiveShell/Awesome-llms-txt. Add documentation directly into your conversation via MCP resources. ☆`26`
- [dengls24/annota](https://github.com/dengls24/annota) — Annota - AI-Powered Paper Annotation MCP Server. Reads PDFs, highlights findings, explains formulas, writes structured notes. ☆`20`
- [besslframework-stack/project-tessera](https://github.com/besslframework-stack/project-tessera) — Tessera - Memory layer for every AI. 58 MCP tools, 54 REST endpoints, local-first, AES-256 encrypted. ☆`18`
- [RyoJerryYu/mcp-server-memos-py](https://github.com/RyoJerryYu/mcp-server-memos-py) — A Python package enabling LLM models to interact with the Memos server via the MCP interface for searching, creating, retrieving, and managing memos. ☆`21`
- [hubertciebiada/context-crystallizer](https://github.com/hubertciebiada/context-crystallizer) — Large repos into AI-consumable knowledge for agents ☆`17`
- [ssmirnovpro/extended-memory-mcp](https://github.com/ssmirnovpro/extended-memory-mcp) — Cross-session persistent memory for Claude Desktop ☆`18`
### RAG

- [apecloud/ApeRAG](https://github.com/apecloud/ApeRAG) — Production GraphRAG with multi-modal ☆`1,319`
- [heymrun/heym](https://github.com/heymrun/heym) — Build agentic systems. Run them with confidence. Orchestrate agents, automate business processes, inspect every execution, and keep humans in control. Deploy Heym on your own ☆`1,176`
- [Minima-AI-Inc/minima](https://github.com/Minima-AI-Inc/minima) — On-premises conversational RAG with configurable containers ☆`1,056`
- [GreatScottyMac/context-portal](https://github.com/GreatScottyMac/context-portal) — Memory bank MCP with knowledge graph ☆`767`
- [shinpr/mcp-local-rag](https://github.com/shinpr/mcp-local-rag) — MCP server for local RAG operations ☆`429`
- [graphlit/graphlit-mcp-server](https://github.com/graphlit/graphlit-mcp-server) — Model Context Protocol (MCP) Server for Graphlit Platform ☆`378`
- [lyonzin/knowledge-rag](https://github.com/lyonzin/knowledge-rag) — Local RAG MCP server for Claude Code - hybrid search (semantic + BM25), cross-encoder reranking, 13 MCP tools, 20 format parsers. Zero external servers, zero API keys. ☆`301`
- [hannesrudolph/mcp-ragdocs](https://github.com/hannesrudolph/mcp-ragdocs) — MCP server for RAG document retrieval ☆`263`
- [jztan/pdf-mcp](https://github.com/jztan/pdf-mcp) — MCP server that lets Claude Code and other AI agents read and search large PDFs, one file or a whole folder: agentic RAG with hybrid semantic + keyword search, selective page ☆`165`
- [newideas99/Deepseek-Thinking-Claude-3.5-Sonnet-CLINE-MCP](https://github.com/newideas99/Deepseek-Thinking-Claude-3.5-Sonnet-CLINE-MCP) — MCP server implementing RAT (Retrieval Augmented Thinking) - combines DeepSeek's reasoning with GPT-4/Claude/Mistral responses, maintaining conversation context between ☆`115`
- [arthurpanhku/DocSentinel](https://github.com/arthurpanhku/DocSentinel) — MCP server for AI agent for cybersecurity: automate assessment of documents, questionnaires & reports. Multi-format parsing, RAG knowledge base,Risks, compliance gaps, ☆`90`
- [needle-ai/needle-mcp](https://github.com/needle-ai/needle-mcp) — Needle MCP Server for easy RAG.Long-term memory for LLMs. ☆`104`
- [ragieai/ragie-mcp-server](https://github.com/ragieai/ragie-mcp-server) — Ragie Model Context Protocol Server ☆`90`
- [pinecone-io/assistant-mcp](https://github.com/pinecone-io/assistant-mcp) — Pinecone Assistant MCP server ☆`46`
- [tomohiro-owada/devrag](https://github.com/tomohiro-owada/devrag) — Markdown vector search MCP server for Claude Code. Natural language search for markdown files using multilingual-e5-small embeddings. ☆`64`
- [2015xli/clangd-graph-rag](https://github.com/2015xli/clangd-graph-rag) — Source code graph RAG (GraphRAG) for C/C++ development based on clang/clangd ☆`63`
- [jurasofish/mcpunk](https://github.com/jurasofish/mcpunk) — MCP tools for Roaming RAG ☆`56`
- [Thanatos9404/llmslim](https://github.com/Thanatos9404/llmslim) — Long-term memory for AI agents with no LLM call: an MCP server and Claude Code plugin, plus local-first context compression for LLM apps. ☆`24`
- [nonatofabio/local_faiss_mcp](https://github.com/nonatofabio/local_faiss_mcp) — Local FAISS MCP - semantic search for Claude/Copilot ☆`36`
- [pipeshub-ai/mcp-server](https://github.com/pipeshub-ai/mcp-server) — This repository contains the packages that make up Pipeshub's local MCP server ☆`17`
- [vectara/vectara-mcp](https://github.com/vectara/vectara-mcp) — Open source MCP server for Vectara ☆`30`
- [agentset-ai/mcp-server](https://github.com/agentset-ai/mcp-server) — Agentset MCP Server - Build RAG with Agentic superpowers ☆`30`
- [renl/mcp-rag-local](https://github.com/renl/mcp-rag-local) — Local RAG with Ollama embeddings and ChromaDB ☆`18`
## AI Platforms

- [rocketride-org/rocketride-server](https://github.com/rocketride-org/rocketride-server) — High-performance AI pipeline engine with a C++ core and 50+ Python-extensible nodes. Build, debug, and scale LLM workflows with 13+ model providers, 8+ vector databases, and ☆`19,899`
- [Kiln-AI/Kiln](https://github.com/Kiln-AI/Kiln) — Build AI systems with Evals, RAG, Agents, fine-tuning ☆`5,254`
- [paiml/paiml-mcp-agent-toolkit](https://github.com/paiml/paiml-mcp-agent-toolkit) — Pragmatic AI Labs toolkit for deterministic agents ☆`169`
- [TheRaLabs/legion-mcp](https://github.com/TheRaLabs/legion-mcp) — MCP server for Legion AI platform ☆`95`
- [PromptExecution/just-mcp](https://github.com/PromptExecution/just-mcp) — mcp server for just ☆`62`
- [atlanhq/agent-toolkit](https://github.com/atlanhq/agent-toolkit) — Atlan AI Agent Toolkit ☆`42`
- [Mitek99/deepview-mcp](https://github.com/Mitek99/deepview-mcp) — MCP server for DeepView AI analysis ☆`65`
- [StitchAI/stitch-ai-mcp](https://github.com/StitchAI/stitch-ai-mcp) — Decentralized Knowledge Hub for AI ☆`39`
- [PV-Bhat/gemsuite-mcp](https://github.com/PV-Bhat/gemsuite-mcp) — MCP server for GemSuite tools ☆`32`
- [DumplingAI/mcp-server-dumplingai](https://github.com/DumplingAI/mcp-server-dumplingai) — MCP (Model Context Protocol) server for Dumpling AI ☆`30`
- [sequa-ai/sequa-mcp](https://github.com/sequa-ai/sequa-mcp) — MCP server for Sequa AI platform ☆`22`
## Aggregators & Gateways

### Aggregators

- [mindsdb/mindshub](https://github.com/mindsdb/mindshub) — Query Engine for AI Analytics - self-reasoning agents on live data ☆`39,833`
- [Klavis-AI/klavis](https://github.com/Klavis-AI/klavis) — Klavis AI: MCP integration platforms that let AI agents use tools reliably at any scale ☆`5,828`
- [metatool-ai/metamcp](https://github.com/metatool-ai/metamcp) — MCP Aggregator, Orchestrator, Middleware, Gateway in one docker ☆`2,749`
- [mcpjungle/MCPJungle](https://github.com/mcpjungle/MCPJungle) — One place to manage & connect to all your MCP servers ☆`1,551`
- [1mcp-app/agent](https://github.com/1mcp-app/agent) — Unified MCP server aggregator ☆`526`
- [K-Dense-AI/claude-skills-mcp](https://github.com/K-Dense-AI/claude-skills-mcp) — Claude Agent Skills vector search ☆`411`
- [BlockRunAI/blockrun-mcp](https://github.com/BlockRunAI/blockrun-mcp) — Live data for AI agents - search, research, markets, crypto, X/Twitter. Pay-per-call via x402 micropayments. ☆`389`
- [boltmcp/boltmcp](https://github.com/boltmcp/boltmcp) — Enterprise-grade MCP orchestration platform to create, deploy, and manage custom MCP servers on-premises. Unlicensed. ☆`371`
- [sitbon/magg](https://github.com/sitbon/magg) — Magg: The MCP Aggregator ☆`143`
- [wanaku-ai/wanaku](https://github.com/wanaku-ai/wanaku) — Wanaku Governed Action Proxy for AI Agents ☆`135`
- [badkk/awesome-crypto-mcp-servers](https://github.com/badkk/awesome-crypto-mcp-servers) — A collection of crypto MCP servers. ☆`147`
- [yylo-dev/roundtable](https://github.com/yylo-dev/roundtable) — Zero-config MCP unifying multiple AI coding assistants ☆`128`
- [portel-dev/ncp](https://github.com/portel-dev/ncp) — Natural Context Provider with smart MCP tool loading ☆`101`
- [nguyenvanduocit/all-in-one-model-context-protocol](https://github.com/nguyenvanduocit/all-in-one-model-context-protocol) — GitLab, Jira, Confluence, YouTube ☆`107`
- [VeriTeknik/pluggedin-mcp](https://github.com/VeriTeknik/pluggedin-mcp) — Plugged.in MCP Server manages all your other MCPs in one MCP. ☆`52`
- [bh-rat/context-awesome](https://github.com/bh-rat/context-awesome) — awesome-lists now available as CLI & MCP server for your agent. ☆`61`
- [profullstack/mcp-server](https://github.com/profullstack/mcp-server) — A generic, modular server for implementing the Model Context Protocol (MCP). ☆`45`
- [waystation-ai/mcp](https://github.com/waystation-ai/mcp) — No-code secure MCP integration hub ☆`66`
- [hamidra/yamcp](https://github.com/hamidra/yamcp) — Local MCP workspace organization ☆`67`
- [gotoolkits/mcp-difyworkflow-server](https://github.com/gotoolkits/mcp-difyworkflow-server) — MCP server for Dify workflow invocation ☆`62`
- [Wolido/OpenAaaS](https://github.com/Wolido/OpenAaaS) — OpenAaaS: science agent network - bring AI to your data, not your data to AI. AaaS, Agent as a Service, MCP protocol, local execution, Docker sandbox, zero-config Rust nodes. ☆`31`
- [arikusi/deepseek-mcp-server](https://github.com/arikusi/deepseek-mcp-server) — MCP server for DeepSeek (deepseek-flash V4.1, deepseek-v4-pro, 1M context): chat, thinking mode, function calling, JSON schema output, FIM, peak/off-peak cost tracking. ☆`26`
- [glenngillen/mcpmcp-server](https://github.com/glenngillen/mcpmcp-server) — MCP server aggregator and router ☆`43`
- [tadas-github/a2asearch-mcp](https://github.com/tadas-github/a2asearch-mcp) — MCP server for searching AI agents, MCP servers, CLI tools and agent skills via A2ASearch ☆`21`
- [membranehq/mcp-server](https://github.com/membranehq/mcp-server) — MCP Server for Membrane ☆`36`
- [nazar256/combine-mcp](https://github.com/nazar256/combine-mcp) — MCP aggregator combining multiple servers into one interface ☆`35`
- [wojtyniak/mcp-mcp](https://github.com/wojtyniak/mcp-mcp) — Meta-MCP for tool discovery and provisioning ☆`23`
- [agree-able/room-mcp](https://github.com/agree-able/room-mcp) — Coordinate agents using rooms ☆`23`
- [isaac-levine/forage](https://github.com/isaac-levine/forage) — Self-improving tool discovery for AI agents. Agents find, install, and learn to use new MCP tools automatically. ☆`19`
### Gateways & Proxies

- [apache/apisix](https://github.com/apache/apisix) — The Cloud-Native API Gateway and AI Gateway ☆`17,292`
- [maximhq/bifrost](https://github.com/maximhq/bifrost) — Open-source, high-performance AI gateway that works as your LLM gateway, MCP gateway and agent gateway. One OpenAI-compatible API for 10,000+ models, with failover, load ☆`9,331`
- [IBM/mcp-context-forge](https://github.com/IBM/mcp-context-forge) — An AI Gateway, registry, and proxy that sits in front of any MCP, A2A, or REST/gRPC APIs, exposing a unified endpoint with centralized discovery, guardrails and management. ☆`4,751`
- [sparfenyuk/mcp-proxy](https://github.com/sparfenyuk/mcp-proxy) — A bridge between Streamable HTTP and stdio MCP transports ☆`2,815`
- [stacklok/toolhive](https://github.com/stacklok/toolhive) — Runtime and gateway for deploying MCP servers in containers ☆`2,324`
- [AmoyLab/Unla](https://github.com/AmoyLab/Unla) — MCP Gateway - A lightweight gateway service that instantly transforms existing MCP Servers and APIs into MCP servers with zero code changes. Features Docker deployment and ☆`2,252`
- [docker/mcp-gateway](https://github.com/docker/mcp-gateway) — docker mcp CLI plugin / MCP Gateway ☆`1,623`
- [obot-platform/obot](https://github.com/obot-platform/obot) — Complete AI Governance Platform from Obot AI ☆`1,161`
- [HelpCode-ai/anythingmcp](https://github.com/HelpCode-ai/anythingmcp) — Self-hosted gateway from REST, SOAP, GraphQL, and SQL ☆`757`
- [tbxark/mcp-proxy](https://github.com/tbxark/mcp-proxy) — Aggregate multiple MCP servers via HTTP ☆`742`
- [TheLunarCompany/lunar](https://github.com/TheLunarCompany/lunar) — lunar.dev: Agent native MCP Gateway for governance and security ☆`507`
- [decocms/studio](https://github.com/decocms/studio) — Open-source control plane for your AI agents. Connect tools, hire agents, track every token and dollar ☆`415`
- [activeing123/mcptoon](https://github.com/activeing123/mcptoon) — One zero-dependency MCP gateway CLI for every server and agent skill. Token optimization, tool discovery and context compression: 71,929 -> 581 tokens (-99.2%, measured), schemas ☆`420`
- [Nexus-Router/nexus](https://github.com/Nexus-Router/nexus) — Govern & Secure your AI ☆`438`
- [smart-mcp-proxy/mcpproxy-go](https://github.com/smart-mcp-proxy/mcpproxy-go) — Supercharge AI Agents, Safely ☆`407`
- [lasso-security/mcp-gateway](https://github.com/lasso-security/mcp-gateway) — A plugin-based gateway that orchestrates other MCPs and allows developers to build upon it enterprise-grade agents. ☆`397`
- [punkpeye/mcp-proxy](https://github.com/punkpeye/mcp-proxy) — A TypeScript streamable HTTP and SSE proxy for MCP servers that use stdio transport. ☆`293`
- [agoda-com/api-agent](https://github.com/agoda-com/api-agent) — Universal MCP server for GraphQL/REST APIs ☆`298`
- [btsouth/toolport](https://github.com/btsouth/toolport) — Local-first MCP gateway. Set up MCP servers once and use them in every AI client, with secrets in the OS keychain, tool integrity checks and quarantine, and on-demand tool search ☆`233`
- [api7/aisix](https://github.com/api7/aisix) — Open-source AI gateway for LLMs & AI agents, built in Rust. One OpenAI-compatible API for OpenAI, Anthropic, Gemini, Bedrock & more - routing, guardrails, caching, rate limits, ☆`212`
- [ssut/Remote-MCP](https://github.com/ssut/Remote-MCP) — Type-safe solution for remote MCP communication ☆`207`
- [agiletec-inc/airis-mcp-gateway](https://github.com/agiletec-inc/airis-mcp-gateway) —  ☆`173`
- [sxhxliang/mcp-access-point](https://github.com/sxhxliang/mcp-access-point) — Convert any web server to MCP instantly ☆`185`
- [toolprint/hypertool-mcp](https://github.com/toolprint/hypertool-mcp) — Expose tools based on Agent Persona ☆`155`
- [lightconetech/mcp-gateway](https://github.com/lightconetech/mcp-gateway) — A gateway demo for MCP SSE Server ☆`153`
- [VeriTeknik/pluggedin-mcp-proxy](https://github.com/VeriTeknik/pluggedin-mcp-proxy) — Unified MCP proxy managing multiple MCPs ☆`138`
- [acehoss/mcp-gateway](https://github.com/acehoss/mcp-gateway) — A flexible gateway server that bridges Model Context Protocol (MCP) STDIO servers to MCP HTTP+SSE and REST API, enabling multi-instance MCP servers to be exposed over HTTP. ☆`130`
- [kfirtoledo/multi-mcp](https://github.com/kfirtoledo/multi-mcp) — A flexible and dynamic Multi-MCP Proxy Server that acts as a single MCP server while connecting to and routing between multiple backend MCP servers over STDIO or SSE.... ☆`111`
- [MikkoParkkola/mcp-gateway](https://github.com/MikkoParkkola/mcp-gateway) — Unlimited MCP servers, tools and APIs. One fixed context cost. Plug every tool you own into Claude, Cursor, Codex or any MCP client: your agent sees a handful, finds the rest on ☆`85`
- [boilingdata/mcp-server-and-gw](https://github.com/boilingdata/mcp-server-and-gw) — An MCP stdio to HTTP SSE transport gateway with example server and MCP client ☆`91`
- [hasmcp/hasmcp-ce](https://github.com/hasmcp/hasmcp-ce) — HasMCP Community Edition ☆`63`
- [Rendeverance/toolfunnel](https://github.com/Rendeverance/toolfunnel) — A zero-dependency MCP and Local tool gateway: host your own tools in any language, forward and curate tools from other MCP servers, expose them leanly to cut agent token cost, ☆`38`
- [phildougherty/mcp-compose](https://github.com/phildougherty/mcp-compose) — Compose, manage, and run MCP servers as Docker containers. With a Unified API gateway built in. ☆`58`
- [Cognipeer/console](https://github.com/Cognipeer/console) — Open-source, self-hosted AI gateway and control plane: OpenAI-compatible LLM routing, RAG, an MCP hub, guardrails and agent tracing for multi-tenant teams. ☆`27`
- [Consiliency/pmcp](https://github.com/Consiliency/pmcp) — MCP Gateway - A meta-server for minimal Claude Code tool bloat with progressive disclosure ☆`23`
- [oidebrett/mcpauth](https://github.com/oidebrett/mcpauth) — MCP Gateway for external Authentication and Authorization ☆`32`
- [cgrtml/reasongate](https://github.com/cgrtml/reasongate) — Explainable security gate for LLM apps - blocks prompt injection with an auditable reason for every decision. ☆`17`
- [adiom-data/grpcmcp](https://github.com/adiom-data/grpcmcp) — MCP Server for gRPC ☆`29`
- [universal-mcp/universal-mcp](https://github.com/universal-mcp/universal-mcp) — Middleware for API applications ☆`26`
- [pyroprompts/mcp-stdio-to-streamable-http-adapter](https://github.com/pyroprompts/mcp-stdio-to-streamable-http-adapter) — STDIO to Streamable HTTP proxy ☆`26`
- [webrix-ai/secure-mcp-gateway](https://github.com/webrix-ai/secure-mcp-gateway) — Secure OAuth gateway for MCP authentication ☆`22`
- [nick1udwig/ws-mcp](https://github.com/nick1udwig/ws-mcp) — MCP server with WebSocket transport ☆`21`
### Platforms & Registries

- [modelcontextprotocol/registry](https://github.com/modelcontextprotocol/registry) — A community driven registry service for Model Context Protocol (MCP) servers. ☆`7,435`
- [archestra-ai/archestra](https://github.com/archestra-ai/archestra) — Enterprise AI guardrails, registry, gateway, and orchestrator ☆`4,426`
- [microsoft/mcp](https://github.com/microsoft/mcp) — Catalog of official Microsoft MCP (Model Context Protocol) server implementations for AI-powered data access and tool integration ☆`3,832`
- [metorial/metorial](https://github.com/metorial/metorial) — Connect any AI model to 1200+ integrations (MCP, CLI, API) ☆`3,372`
- [chatmcp/mcpso](https://github.com/chatmcp/mcpso) — directory for Awesome MCP Servers ☆`2,115`
- [julien040/anyquery](https://github.com/julien040/anyquery) — SQL queries for GitHub, Notion, +40 more ☆`1,789`
- [jaw9c/awesome-remote-mcp-servers](https://github.com/jaw9c/awesome-remote-mcp-servers) — Remote MCP Servers ☆`1,176`
- [docker/mcp-registry](https://github.com/docker/mcp-registry) — Official Docker MCP registry ☆`580`
- [pathintegral-institute/mcpm.sh](https://github.com/pathintegral-institute/mcpm.sh) — CLI MCP package manager & registry for all platforms and all clients. Search & configure MCP servers. Advanced Router & Profile features. ☆`1,021`
- [boltmcp/boltmcp](https://github.com/boltmcp/boltmcp) — Open standard and registry for converting web APIs into MCP servers ☆`371`
- [apappascs/mcp-servers-hub](https://github.com/apappascs/mcp-servers-hub) — Discover the most comprehensive and up-to-date collection of MCP servers in the market. This repository serves as a centralized hub, offering an extensive catalog of open-source ☆`330`
- [liuyoshio/mcp-compass](https://github.com/liuyoshio/mcp-compass) — MCP discovery and recommendation ☆`248`
- [juspay/neurolink](https://github.com/juspay/neurolink) — Universal AI platform with MCP and multi-provider support ☆`157`
- [integromat/make-mcp-server](https://github.com/integromat/make-mcp-server) — Make MCP Server ☆`174`
- [Jeamee/MCPHub-Desktop](https://github.com/Jeamee/MCPHub-Desktop) — Desktop APP for Discover and Install MCP Servers ☆`148`
- [rust-mcp-stack/mcp-discovery](https://github.com/rust-mcp-stack/mcp-discovery) — CLI for discovering MCP server capabilities ☆`87`
- [matthewdcage/cursor-mcp-installer](https://github.com/matthewdcage/cursor-mcp-installer) — Install MCPs in Cursor from git URL ☆`75`
- [useparagon/paragon-mcp](https://github.com/useparagon/paragon-mcp) — Access 130+ SaaS integrations via ActionKit ☆`48`
- [aiagenta2z/onekey-gateway](https://github.com/aiagenta2z/onekey-gateway) — OneKey Agent Gateway access to Commercial APIs, Skills, MCPs Build once and Ship 10× faster. For devs & builders, A unified API registry to serve and distribute across all agent ☆`52`
- [VeyraX/veyrax-mcp](https://github.com/VeyraX/veyrax-mcp) — VeyraX unified tool access via single MCP ☆`48`
- [robhunter/agentdeals](https://github.com/robhunter/agentdeals) — Catalogue of developer infrastructure free tiers, startup credits and pricing, with side-by-side vendor comparisons for hosting, databases and AI APIs. Website, JSON API and MCP ☆`24`
- [Data-Everything/mcp-server-templates](https://github.com/Data-Everything/mcp-server-templates) — Docker, Kubernetes, CLI, and HTTP MCP templates ☆`22`
- [bytesagain/ai-skills](https://github.com/bytesagain/ai-skills) — AI Agent Skills for Claude Code, Manus, OpenClaw & more ☆`16`
## Browser Automation

### AI Automation

- [Skyvern-AI/skyvern](https://github.com/Skyvern-AI/skyvern) — Automate browser based workflows with AI ☆`23,336`
- [nottelabs/notte](https://github.com/nottelabs/notte) — Framework to build web agents ☆`2,054`
- [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) — AI browser agent, ships as an MCP server and a web UI ☆`892`
- [kontext-security/browser-use-mcp-server](https://github.com/kontext-security/browser-use-mcp-server) — Browse the web, directly from Cursor etc. ☆`849`
- [imprvhub/mcp-browser-agent](https://github.com/imprvhub/mcp-browser-agent) — MCP server for autonomous browser automation with Claude ☆`43`
- [desplega-ai/qa-use](https://github.com/desplega-ai/qa-use) — Agent-first E2E testing CLI ☆`29`
### Browser Tools

- [BrowserMCP/mcp](https://github.com/BrowserMCP/mcp) — Browser control for AI applications ☆`7,285`
- [LvcidPsyche/auto-browser](https://github.com/LvcidPsyche/auto-browser) — Give your AI agent a real browser - with a human in the loop. Open-source MCP-native browser agent. ☆`921`
- [kontext-security/browser-use-mcp-server](https://github.com/kontext-security/browser-use-mcp-server) — Browse the web, directly from Cursor etc. ☆`849`
- [nirholas/XActions](https://github.com/nirholas/XActions) — The Complete X/Twitter Automation Toolkit - Scrapers, MCP server for AI agents (Claude/GPT), CLI, browser scripts. No API fees. Open source. Unfollow people who don't follow ☆`643`
- [merajmehrabi/puppeteer-mcp-server](https://github.com/merajmehrabi/puppeteer-mcp-server) — This MCP server provides browser automation capabilities through Puppeteer, allowing interaction with both new browser instances and existing Chrome windows. ☆`489`
- [fullselfbrowsing/FSB](https://github.com/fullselfbrowsing/FSB) — DOM-first AI browser automation for Chrome and MCP clients. ☆`204`
- [swimmwatch/cloakbrowser-mcp](https://github.com/swimmwatch/cloakbrowser-mcp) — Runs upstream Playwright MCP with CloakBrowser Chromium, preserving its browser tools and adding bridge diagnostics. ☆`176`
- [hanzili/comet-mcp](https://github.com/hanzili/comet-mcp) — MCP Server connecting to Perplexity Comet browser ☆`181`
- [onllm-dev/onUI](https://github.com/onllm-dev/onUI) — Annotation-first UI pair programming in the browser ☆`108`
- [Agent360dk/browser-mcp](https://github.com/Agent360dk/browser-mcp) — The browser tool that can stop and ask you. A 2FA code, a CAPTCHA, a choice only you can make: it asks on your screen, then carries on in the same signed-in Chrome. 40 tools, MCP ☆`61`
- [ofershap/real-browser-mcp](https://github.com/ofershap/real-browser-mcp) — MCP server + Chrome extension that gives AI agents control of your real browser with existing sessions and logins ☆`58`
- [ndthanhdev/mcp-browser-kit](https://github.com/ndthanhdev/mcp-browser-kit) — AI assistants interact with local browser ☆`55`
- [webdriverio/mcp](https://github.com/webdriverio/mcp) — A Model Context Protocol (MCP) server that enables AI assistants to interact with web browsers and mobile applications using WebDriverIO. Automate Chrome browsers, iOS apps, and ☆`44`
- [2captcha/2captcha-mcp](https://github.com/2captcha/2captcha-mcp) — 2Captcha MCP server for AI agents with web search, web scraping, browser automation, captcha solving, and scalable web data collection. ☆`39`
- [ymw0407/auth-fetch-mcp](https://github.com/ymw0407/auth-fetch-mcp) — MCP server that lets AI assistants fetch content from authenticated web pages. ☆`36`
- [BeatAPI/BeatBrowser](https://github.com/BeatAPI/BeatBrowser) — Your Chrome, now an agent browser. No browser switch. No login migration. Codex, Claude Code & more. Free & open source. ☆`36`
- [samson-art/transcriptor-mcp](https://github.com/samson-art/transcriptor-mcp) — One MCP server that gives Claude, ChatGPT, Cursor and any other AI app transcripts, chapters, metadata and frames from YouTube and 10 more video platforms. ☆`24`
- [SanggonBoy/PyreCrawl](https://github.com/SanggonBoy/PyreCrawl) — Web browsing superpowers for AI agents - one MCP server to scrape, crawl, extract, map, search, batch, research & monitor the web. Self-hosted, no API keys. Free Firecrawl ☆`23`
- [BB-fat/browser-use-rs](https://github.com/BB-fat/browser-use-rs) — Rust-based browser automation MCP server ☆`41`
- [nnemirovsky/iwdp-mcp](https://github.com/nnemirovsky/iwdp-mcp) — MCP server + CLI for iOS Safari debugging via ios-webkit-debug-proxy - full WebKit Inspector Protocol support ☆`21`
- [ilien-dev/svipall](https://github.com/ilien-dev/svipall) — Local-first MCP server and CLI in Rust: any page as LLM-ready Markdown, whole-site crawls, keyless search, and local captcha solving. No cloud, no API keys. ☆`20`
- [drisplabs/browser-mcp](https://github.com/drisplabs/browser-mcp) — Token-efficient browser automation MCP for AI agents, with semantic page snapshots and stable element IDs. ☆`19`
- [LeonTing1010/tap](https://github.com/LeonTing1010/tap) — Capture a logged-in browser task once - replay it forever at zero LLM tokens. Local-first browser-automation MCP for Claude Code, Cursor & any MCP host; credentials never leave ☆`18`
- [protostatis/unbrowser](https://github.com/protostatis/unbrowser) — Agent-native browser and MCP server for lightweight, Chrome-free web discovery, with explicit escalation to Unchained for browser-only flows. ☆`17`
### Cloud Services

- [hyperbrowserai/mcp](https://github.com/hyperbrowserai/mcp) — A MCP server implementation for hyperbrowser ☆`793`
- [browserstack/mcp-server](https://github.com/browserstack/mcp-server) — BrowserStack's Official MCP Server ☆`154`
- [kernel/kernel-mcp-server](https://github.com/kernel/kernel-mcp-server) — Secure cloud-browser automation on Kernel ☆`39`
- [browserless/browserless-mcp](https://github.com/browserless/browserless-mcp) — Official MCP server for the Browserless.io ☆`18`
### DevTools

- [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) — Chrome DevTools for coding agents ☆`54,747`
- [mozilla/firefox-devtools-mcp](https://github.com/mozilla/firefox-devtools-mcp) — MCP server for Firefox DevTools integration ☆`545`
- [eyalzh/browser-control-mcp](https://github.com/eyalzh/browser-control-mcp) — Browser control via extension for AI agents ☆`340`
- [achiya-automation/safari-mcp](https://github.com/achiya-automation/safari-mcp) — Native Safari browser automation for AI agents. 98 tools via AppleScript - zero overhead, keeps logins, runs silently in background. Drop-in alternative to Chrome DevTools MCP ☆`233`
### Playwright

- [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) — Playwright MCP server ☆`39,148`
- [executeautomation/mcp-playwright](https://github.com/executeautomation/mcp-playwright) — MCP server for Playwright browser testing ☆`5,674`
- [vostride/agent-qa](https://github.com/vostride/agent-qa) — Open-source self-improving QA agent for software teams. A test harness with memory. Write tests in natural language for web and mobile. agent-qa learns from every run, adapts to ☆`924`
- [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) — Playwright MCP server undetected by anti-bots and captchas: AI agent browses the web on anti-detect stealth Firefox, Python, undetected browser automation, scraping, computer use. ☆`892`
- [VikashLoomba/MCP-Server-Playwright](https://github.com/VikashLoomba/MCP-Server-Playwright) — MCP server for browser automation using Playwright ☆`297`
- [blackwhite084/playwright-plus-python-mcp](https://github.com/blackwhite084/playwright-plus-python-mcp) — Enhanced Playwright browser automation ☆`188`
- [wukan1986/mcp_query_table](https://github.com/wukan1986/mcp_query_table) — query table from some websites, support MCP ☆`60`
- [acunningham-ship-it/veilbrowser](https://github.com/acunningham-ship-it/veilbrowser) — Stealth browser for AI agents - real Chrome over raw CDP, no Playwright/Puppeteer. TypeScript + MCP-native. Passes sannysoft 57/57, bypasses Cloudflare. ☆`47`
- [kimtth/mcp-aoai-web-browsing](https://github.com/kimtth/mcp-aoai-web-browsing) — Azure OpenAI with Playwright browser control ☆`35`
- [mcpware/pagecast](https://github.com/mcpware/pagecast) — Record any browser page as GIF or video via MCP - powered by Playwright + ffmpeg ☆`52`
- [twolven/mcp-server-puppeteer-py](https://github.com/twolven/mcp-server-puppeteer-py) — MCP server providing browser automation via Playwright (Python), enabling LLMs to interact with web pages, take screenshots, and execute JavaScript in a real browser. ☆`19`
- [AishwaryShrivastav/vibe-testing](https://github.com/AishwaryShrivastav/vibe-testing) — Code-aware browser testing for AI coding agents. 14 MCP tools, CLI workflows, regression memory, and human-readable QA reports. ☆`18`
- [sh6drack/zen-mcp](https://github.com/sh6drack/zen-mcp) — The first MCP server for Zen Browser. 20 tools. No Selenium, no Playwright, just WebSocket. ☆`27`
- [random-robbie/mcp-web-browser](https://github.com/random-robbie/mcp-web-browser) — An advanced web browsing server for the Model Context Protocol (MCP) powered by Playwright, enabling headless browser interactions through a flexible, secure API. ☆`27`
## CLI Tools

- [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) — Terminal control, file search, diff editing ☆`10,208`
- [f/mcptools](https://github.com/f/mcptools) — A command-line interface for interacting with MCP (Model Context Protocol) servers using both stdio and HTTP transport. ☆`1,629`
- [classfang/ssh-mcp-server](https://github.com/classfang/ssh-mcp-server) — SSH MCP server included in official repo ☆`1,010`
- [20000419/fauxnix](https://github.com/20000419/fauxnix) — Run Linux-style commands on Windows via deterministic bash→PowerShell translation. No VM, no WSL. MCP server + CLI built for AI agents (Claude Code, Codex, OpenCode...). ☆`898`
- [tufantunc/ssh-mcp](https://github.com/tufantunc/ssh-mcp) — SSH control for Linux servers ☆`856`
- [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp) — iTerm command execution for REPL/CLI ☆`571`
- [bvisible/mcp-ssh-manager](https://github.com/bvisible/mcp-ssh-manager) — MCP server for SSH: let Claude Code, Codex and any MCP client run commands, transfer files and manage servers over SSH, with human approval, an encrypted vault and a live audit ☆`532`
- [baryhuang/mcp-remote-macos-use](https://github.com/baryhuang/mcp-remote-macos-use) — AI agent for full Mac control ☆`490`
- [peakmojo/applescript-mcp](https://github.com/peakmojo/applescript-mcp) — Execute AppleScript for Mac control ☆`466`
- [wong2/mcp-cli](https://github.com/wong2/mcp-cli) — A CLI inspector for the Model Context Protocol ☆`447`
- [AmrDab/clawdcursor](https://github.com/AmrDab/clawdcursor) — Local MCP server that gives any AI agent safe desktop control on Windows, macOS and Linux. Reads the screen as text and structure (accessibility + OCR) and acts by element name, ☆`406`
- [domdomegg/computer-use-mcp](https://github.com/domdomegg/computer-use-mcp) — Full computer control for AI models ☆`393`
- [claude-did-this/MCPControl](https://github.com/claude-did-this/MCPControl) — MCP server for Windows OS automation ☆`334`
- [nickgnd/tmux-mcp](https://github.com/nickgnd/tmux-mcp) — A MCP server for our beloved terminal multiplexer tmux. ☆`306`
- [g0t4/mcp-server-commands](https://github.com/g0t4/mcp-server-commands) — MCP server to run commands (runProcess tool) ☆`237`
- [tumf/mcp-shell-server](https://github.com/tumf/mcp-shell-server) — Shell execution with whitelisted commands ☆`201`
- [dvcrn/mcp-server-siri-shortcuts](https://github.com/dvcrn/mcp-server-siri-shortcuts) — MCP for calling Siri Shorcuts from LLMs ☆`195`
- [AB498/computer-control-mcp](https://github.com/AB498/computer-control-mcp) — Mouse, keyboard, OCR via PyAutoGUI ☆`173`
- [lacs-project/sysknife](https://github.com/lacs-project/sysknife) — Security-hardened MCP server for Linux sysadmin: 189 typed actions instead of shell strings, Ed25519 hash-chain audit log, approval receipts, automatic rollback ☆`169`
- [MladenSU/cli-mcp-server](https://github.com/MladenSU/cli-mcp-server) — CLI with secure execution and custom policies ☆`179`
- [AppachiTech/suvadu](https://github.com/AppachiTech/suvadu) — Shell history replacement with AI agent tracking and MCP server. Built in Rust, 100% local. ☆`127`
- [sonirico/mcp-shell](https://github.com/sonirico/mcp-shell) — Secure, auditable shell commands for AI ☆`110`
- [automateyournetwork/pyATS_MCP](https://github.com/automateyournetwork/pyATS_MCP) — An MCP Server for pyATS (experimental) ☆`90`
- [nylas/cli](https://github.com/nylas/cli) — Nylas CLI is a unified command-line tool for Nylas API authentication, email management (GPG signing/encryption), calendar, contacts, webhooks, timezone utilities, and OTP ☆`81`
- [inercia/MCPShell](https://github.com/inercia/MCPShell) — Use shell scripts as MCP tools ☆`72`
- [danmartuszewski/hop](https://github.com/danmartuszewski/hop) — Fast, elegant SSH connection manager with a TUI dashboard and MCP server ☆`64`
- [NakaokaRei/swift-mcp-gui](https://github.com/NakaokaRei/swift-mcp-gui) — Keyboard and mouse control on macOS ☆`61`
- [ooples/mcp-console-automation](https://github.com/ooples/mcp-console-automation) — MCP for AI-driven console automation and monitoring ☆`54`
- [nihalxkumar/arch-mcp](https://github.com/nihalxkumar/arch-mcp) — Arch Linux MCP (Model Context Protocol) Server ☆`61`
- [InsForge/insforge-mcp](https://github.com/InsForge/insforge-mcp) — MCP server for InsForge - full-stack builders for coding agents ☆`38`
- [YawLabs/tailscale-mcp](https://github.com/YawLabs/tailscale-mcp) — Tailscale MCP server for managing your tailnet from AI assistants ☆`35`
- [JonathanRReed/Apple-MCPs](https://github.com/JonathanRReed/Apple-MCPs) — Model Context Protocol (MCP) servers that give AI agents local access to macOS apps: Mail, Calendar, Reminders, Messages, Contacts, Notes, Shortcuts, Files, System, and Maps. ☆`34`
- [zb-ss/servonaut](https://github.com/zb-ss/servonaut) — Manage AWS, Hetzner, OVH, and custom servers from one TUI - with a built-in AI assistant and MCP server ☆`31`
- [munimtechnologies/munim-computer-use](https://github.com/munimtechnologies/munim-computer-use) — Open-source Computer Use MCP server for any coding agent - macOS, Windows, Linux. Accessibility-first, background input, agent pointer, zoom, your signed-in Chrome. ☆`27`
- [Harusame64/desktop-touch-mcp](https://github.com/Harusame64/desktop-touch-mcp) — Windows computer-use MCP server: drive any desktop app via semantic discover-then-act targeting (entities + leases, not pixel coordinates), with per-action perception guards, a ☆`25`
- [maxim-saplin/mcp_safe_local_python_executor](https://github.com/maxim-saplin/mcp_safe_local_python_executor) — Safe Python executor from smolagents ☆`48`
- [faze79/WPFVisualTreeMcp](https://github.com/faze79/WPFVisualTreeMcp) — MCP server and CLI for WPF: inspect visual trees and bindings, capture scrollable content, drive mouse/touch input, and record workflows as runnable xUnit tests. ☆`21`
- [raychao-oao/pty-mcp](https://github.com/raychao-oao/pty-mcp) — MCP server for interactive terminal sessions - local shells, SSH, serial ports, and persistent remote sessions ☆`20`
- [fixed-width/glass](https://github.com/fixed-width/glass) — MCP server: build → see → interact → debug loop over native GUI apps ☆`20`
- [OthmaneBlial/term_mcp_deepseek](https://github.com/OthmaneBlial/term_mcp_deepseek) — Approve terminal commands after risk and access checks ☆`18`
- [Beer-Bears/scaffold](https://github.com/Beer-Bears/scaffold) — Structural RAG system for large codebases ☆`19`
- [ostapondo/Plonk](https://github.com/ostapondo/Plonk) — A native, local macOS toolbox for screenshots, OCR, measuring, keep-awake, pointer tools, shortcuts, windows, workspaces, voice and MCP. ☆`17`
- [ferodrigop/forge](https://github.com/ferodrigop/forge) — Terminal MCP server for AI coding agents - spawn, manage, and monitor PTY sessions via the Model Context Protocol ☆`28`
- [blakerouse/ssh-mcp](https://github.com/blakerouse/ssh-mcp) — Local SSH host groups and remote command execution ☆`19`
- [PhialsBasement/CMD-MCP-Server](https://github.com/PhialsBasement/CMD-MCP-Server) — CMD command execution for Claude agents ☆`25`
- [aybelatchane/mcp-server-terminal](https://github.com/aybelatchane/mcp-server-terminal) — TUI and CLI automation via Terminal State Tree ☆`21`
- [amol21p/mcp-interactive-terminal](https://github.com/amol21p/mcp-interactive-terminal) — MCP server that gives AI agents (Claude Code, Cursor, Windsurf) real interactive terminal sessions - REPLs, SSH, databases, Docker, and any interactive CLI with clean output and ☆`20`
- [erniebrodeur/mcp-grep](https://github.com/erniebrodeur/mcp-grep) — simple mcp server to wrap the local instance of grep. ☆`25`
- [JoshuaRileyDev/mac-apps-launcher](https://github.com/JoshuaRileyDev/mac-apps-launcher) — Launch and manage macOS applications ☆`19`
## CRM & ERP

- [ivnvxd/mcp-server-odoo](https://github.com/ivnvxd/mcp-server-odoo) — MCP server for Odoo ERP integration ☆`411`
- [saurabhsharma2u/search-console-mcp](https://github.com/saurabhsharma2u/search-console-mcp) — Search & analytics data as infrastructure - MCP server for Google Search Console, Bing Webmaster Tools, Google Adsense and GA4, designed for AI agents and automation. ☆`320`
- [explorium-ai/vibeprospecting-mcp](https://github.com/explorium-ai/vibeprospecting-mcp) — Power your chat with B2B data to create lead lists, research companies, personalize your outreach, and more. ☆`294`
- [GeLi2001/shopify-mcp](https://github.com/GeLi2001/shopify-mcp) — Shopify API for Claude and Cursor ☆`239`
- [tsmztech/mcp-server-salesforce](https://github.com/tsmztech/mcp-server-salesforce) — Salesforce MCP Server ☆`165`
- [smn2gnt/MCP-Salesforce](https://github.com/smn2gnt/MCP-Salesforce) — MCP Salesforce connector ☆`179`
- [baryhuang/mcp-hubspot](https://github.com/baryhuang/mcp-hubspot) — HubSpot CRM integration for AI assistants ☆`129`
- [augmnt/augments-mcp-server](https://github.com/augmnt/augments-mcp-server) — MCP server for Augments AI platform ☆`127`
- [tomaspavlin/rohlik-mcp](https://github.com/tomaspavlin/rohlik-mcp) — Shop groceries on Rohlik Group platforms ☆`121`
- [mafzaal/d365fo-client](https://github.com/mafzaal/d365fo-client) — Client for Microsoft Dynamics 365 F&O ☆`41`
- [AiondaDotCom/mcp-salesforce](https://github.com/AiondaDotCom/mcp-salesforce) — Salesforce OAuth and CRUD for any object ☆`17`
- [dsvantien/netsuite-mcp-server](https://github.com/dsvantien/netsuite-mcp-server) — NetSuite ERP records, queries, and operations ☆`22`
- [hmk/attio-mcp-server](https://github.com/hmk/attio-mcp-server) — Attio CRM records and notes management ☆`16`
## Cloud & Infrastructure

### AWS

- [awslabs/mcp](https://github.com/awslabs/mcp) — AWS MCP servers for AI assistants ☆`9,874`
- [towardsthecloud/cloudburn](https://github.com/towardsthecloud/cloudburn) — Open-source policy engine that blocks bad AWS spending patterns before they ship and remediates what's already burning. ☆`1,800`
- [aarora79/aws-cost-explorer-mcp-server](https://github.com/aarora79/aws-cost-explorer-mcp-server) — MCP server for understanding AWS spend ☆`127`
- [rishikavikondala/mcp-server-aws](https://github.com/rishikavikondala/mcp-server-aws) — MCP server for AWS resource operations ☆`127`
- [aws-samples/sample-mcp-server-s3](https://github.com/aws-samples/sample-mcp-server-s3) — Retrieve PDFs and data from AWS S3 ☆`79`
- [groovyBugify/aws-security-mcp](https://github.com/groovyBugify/aws-security-mcp) — A Model Context Protocol server that connects AI assistants like Claude to AWS security services, allowing them to autonomously query, inspect, and analyze AWS infrastructure for ☆`84`
- [localstack/localstack-mcp-server](https://github.com/localstack/localstack-mcp-server) — LocalStack AWS emulation ☆`29`
- [Sidd27/infrawise](https://github.com/Sidd27/infrawise) — MCP server for AWS infrastructure analysis - DynamoDB, Lambda, SQS, SNS, S3, API Gateway, PostgreSQL, MySQL, MongoDB, Kafka & IaC drift. Works with Claude Code, Cursor, and ☆`22`
- [getnable/finopsmcp](https://github.com/getnable/finopsmcp) — The headless FinOps intelligence layer: API-first, agent-first cost control for cloud + AI. Connect your cloud stack in Claude, Cursor, or the terminal, and gate what agents do ☆`20`
- [baryhuang/mcp-server-aws-resources-python](https://github.com/baryhuang/mcp-server-aws-resources-python) — Run boto3 code to manage AWS resources ☆`24`
### Cloud Platforms

- [google/mcp](https://github.com/google/mcp) — Google MCP ☆`4,686`
- [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) — Cloudflare services management ☆`4,442`
- [microsoft/azure-devops-mcp](https://github.com/microsoft/azure-devops-mcp) — Azure DevOps integration for AI agents ☆`2,079`
- [TencentCloudBase/CloudBase-AI-Toolkit](https://github.com/TencentCloudBase/CloudBase-AI-Toolkit) — Connect CloudBase to AI agents ☆`1,156`
- [GoogleCloudPlatform/cloud-run-mcp](https://github.com/GoogleCloudPlatform/cloud-run-mcp) — MCP server to deploy apps to Cloud Run ☆`636`
- [aliyun/alibabacloud-devops-mcp-server](https://github.com/aliyun/alibabacloud-devops-mcp-server) — MCP server for Alibaba Yunxiao DevOps platform ☆`180`
- [babelcloud/gbox](https://github.com/babelcloud/gbox) — AI control for Android, browser, desktop ☆`183`
- [aliyun/alibaba-cloud-ops-mcp-server](https://github.com/aliyun/alibaba-cloud-ops-mcp-server) — AlibabaCloud CloudOps MCP Server ☆`137`
- [dkruyt/mcp-hetzner](https://github.com/dkruyt/mcp-hetzner) — Hetzner Cloud management ☆`152`
- [heroku/heroku-mcp-server](https://github.com/heroku/heroku-mcp-server) — Heroku Platform MCP Server using the Heroku CLI ☆`82`
- [vantage-sh/vantage-mcp-server](https://github.com/vantage-sh/vantage-mcp-server) — Fetch costs and usage from Vantage ☆`86`
- [AliKarami/MikroMCP](https://github.com/AliKarami/MikroMCP) — Production-grade MCP server for MikroTik RouterOS routers and SwOS switches, with secure AI-native network automation. ☆`84`
- [rosenvladimirov/odoo-claude-mcp](https://github.com/rosenvladimirov/odoo-claude-mcp) — Self-hosted MCP server connecting Claude to Odoo 15→19 - 197+ tools, multi-tenant, Bulgaria l10n ☆`51`
- [call518/MCP-OpenStack-Ops](https://github.com/call518/MCP-OpenStack-Ops) — MCP server providing OpenStack project management ☆`49`
- [backblaze-labs/b2-mcp](https://github.com/backblaze-labs/b2-mcp) — MCP server for Backblaze B2 Cloud Storage: a focused, safe 40-tool surface (17 native B2 SDK, 19 S3 data-plane, 4 analytics) for any MCP-compatible AI client, currently ☆`47`
- [aliyun/alibabacloud-dataworks-mcp-server](https://github.com/aliyun/alibabacloud-dataworks-mcp-server) — Alibaba Cloud DataWorks API integration ☆`56`
- [aantti/mcp-netbird](https://github.com/aantti/mcp-netbird) — Netbird network management ☆`64`
- [kestra-io/mcp-server-python](https://github.com/kestra-io/mcp-server-python) — Python MCP for Kestra AI Agents ☆`35`
- [oborseth/Porkbun-MCP](https://github.com/oborseth/Porkbun-MCP) — Official Porkbun MCP server - exposes the Porkbun v3 API as native tools for Claude Desktop, Cursor, and other AI agents. Idempotency-safe writes, full domain lifecycle. ☆`34`
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

- [agentgateway/agentgateway](https://github.com/agentgateway/agentgateway) — Next Generation Agentic Proxy for AI Agents and MCP servers ☆`5,938`
- [skyhook-io/radar](https://github.com/skyhook-io/radar) — The missing open-source Kubernetes UI with a built-in MCP server for AI agents. See what's broken, why, and what changed. Issues, Topology, event timeline, Helm, GitOps, live ☆`4,032`
- [containers/kubernetes-mcp-server](https://github.com/containers/kubernetes-mcp-server) — Kubernetes and OpenShift management ☆`2,219`
- [Flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) — MCP Server for kubernetes management commands ☆`1,610`
- [rohitg00/kubectl-mcp-server](https://github.com/rohitg00/kubectl-mcp-server) — Kubernetes cluster chat with Claude/Cursor ☆`967`
- [microsoft/mcp-gateway](https://github.com/microsoft/mcp-gateway) — MCP Gateway is a reverse proxy and management layer for MCP servers, enabling scalable, session-aware stateful routing and lifecycle management of MCP servers in Kubernetes ☆`907`
- [weibaohui/k8m](https://github.com/weibaohui/k8m) — Mini Kubernetes AI Dashboard ☆`892`
- [argoproj-labs/mcp-for-argocd](https://github.com/argoproj-labs/mcp-for-argocd) — An implementation of Model Context Protocol (MCP) server for Argo CD. ☆`603`
- [strowk/mcp-k8s-go](https://github.com/strowk/mcp-k8s-go) — Go-based Kubernetes connection ☆`381`
- [vfarcic/dot-ai](https://github.com/vfarcic/dot-ai) — Deploy apps to any Kubernetes cluster ☆`339`
- [portainer/portainer-mcp](https://github.com/portainer/portainer-mcp) — Portainer container management ☆`241`
- [reza-gholizade/k8s-mcp-server](https://github.com/reza-gholizade/k8s-mcp-server) — Kubernetes cluster management ☆`188`
- [kubestellar/console](https://github.com/kubestellar/console) — Multi-cluster Kubernetes dashboard with natural-language MCP ☆`152`
- [silenceper/mcp-k8s](https://github.com/silenceper/mcp-k8s) — Kubernetes cluster interaction ☆`153`
- [weibaohui/kom](https://github.com/weibaohui/kom) — Kubernetes SDK wrapping kubectl ☆`151`
- [andrewmoshu/diagram-mcp-server](https://github.com/andrewmoshu/diagram-mcp-server) — An MCP server that seamlessly creates infrastructure diagrams for AWS, Azure, GCP, Kubernetes and more ☆`148`
- [OptimNow/cloud-finops-skills](https://github.com/OptimNow/cloud-finops-skills) — Cloud FinOps Skill & MCP by OptimNow. FinOps Foundation aligned knowledge for AI agents: cloud cost (AWS/Azure/GCP/OCI), AI inference economics, Kubernetes, data platforms, ☆`66`
- [StacklokLabs/mkp](https://github.com/StacklokLabs/mkp) — MKP Kubernetes MCP server ☆`59`
- [dhyansraj/mcp-mesh](https://github.com/dhyansraj/mcp-mesh) — Enterprise-grade distributed AI agent framework | Develop → Deploy → Observe | K8s-native | Dynamic DI | Auto-failover | Multi-LLM | Python + Java + TypeScript | MCP + A2A + REST ☆`42`
- [vitorbari/mcp-operator](https://github.com/vitorbari/mcp-operator) — Production Kubernetes operator for deploying and validating MCP servers ☆`29`
- [zekker6/mcp-helm](https://github.com/zekker6/mcp-helm) — MCP server for Helm package manager ☆`28`
- [wenhuwang/mcp-k8s-eye](https://github.com/wenhuwang/mcp-k8s-eye) — Kubernetes diagnosis and management ☆`29`
- [cyclops-ui/mcp-cyclops](https://github.com/cyclops-ui/mcp-cyclops) — Cyclops Kubernetes management ☆`30`
- [basebandit/kai](https://github.com/basebandit/kai) — An MCP Server for Kubernetes ☆`20`
- [kubesphere/ks-mcp-server](https://github.com/kubesphere/ks-mcp-server) — KubeSphere APIs for workspaces, clusters, users, and roles ☆`17`
### Virtualization & IaC

- [patrickchugh/terravision](https://github.com/patrickchugh/terravision) — Cloud architecture diagrams in both directions: AI prompt or JSON to diagram, diagram to Terraform via MCP server, and Terraform to diagram via CLI or CI/CD. Using Official AWS, ☆`1,670`
- [hashicorp/terraform-mcp-server](https://github.com/hashicorp/terraform-mcp-server) — Terraform ecosystem integration for AI ☆`1,556`
- [agentic-community/mcp-gateway-registry](https://github.com/agentic-community/mcp-gateway-registry) — Enterprise-ready MCP Gateway & Registry that centralizes AI development tools with secure OAuth authentication, dynamic tool discovery, and unified access for both autonomous AI ☆`1,036`
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

- [mattt/iMCP](https://github.com/mattt/iMCP) — Access Messages, Contacts, Reminders on Mac ☆`1,945`
- [carterlasalle/mac_messages_mcp](https://github.com/carterlasalle/mac_messages_mcp) — MCP server for secure iMessage database access on macOS ☆`344`
- [hannesrudolph/imessage-query-fastmcp-mcp-server](https://github.com/hannesrudolph/imessage-query-fastmcp-mcp-server) — Safe iMessage database queries ☆`81`
- [wyattjoh/imessage-mcp](https://github.com/wyattjoh/imessage-mcp) — iMessage data reading from macOS ☆`29`
- [ictinnovations/ictbroadcast-mcp](https://github.com/ictinnovations/ictbroadcast-mcp) — MCP server for ICTBroadcast - monitor outbound voice/SMS/fax campaigns and start/stop them. By ICT Innovations. ☆`16`
- [marissamarym/imessage-mcp-server](https://github.com/marissamarym/imessage-mcp-server) — An MCP server that uses AppleScript to send iMessages and manage contacts. ☆`29`
### Email

- [elie222/inbox-zero](https://github.com/elie222/inbox-zero) — AI email assistant for inbox zero ☆`12,906`
- [Atomic-Mail/atomic-mail-agentic](https://github.com/Atomic-Mail/atomic-mail-agentic) — Let your agents read, send, and react to email autonomously, without human involvement ☆`268`
- [wyattjoh/jmap-mcp](https://github.com/wyattjoh/jmap-mcp) — A Model Context Protocol (MCP) server that provides tools for interacting with JMAP (JSON Meta Application Protocol) email servers. Built with Deno and using the jmap-jam client ☆`179`
- [codefuturist/email-mcp](https://github.com/codefuturist/email-mcp) — Email MCP server with full IMAP + SMTP support - read, search, send, manage, and organize email from any AI assistant via the Model Context Protocol ☆`145`
- [MadLlama25/fastmail-mcp](https://github.com/MadLlama25/fastmail-mcp) — Access to Fastmail API for AI assistants ☆`131`
- [tecnologicachile/mail-mcp](https://github.com/tecnologicachile/mail-mcp) — Secure IMAP/SMTP/EWS/Graph API MCP server in Rust - Microsoft 365, Hotmail, Gmail, Zoho, OAuth2, multi-account ☆`114`
- [ZilongXue/claude-post](https://github.com/ZilongXue/claude-post) — Email management via natural language ☆`114`
- [MrGo2/icloud-mcp](https://github.com/MrGo2/icloud-mcp) — MCP server for Apple services - Mail, Calendar, Contacts, Reminders, Notes, Messages, Safari - via AppleScript (local) or iCloud IMAP/CalDAV/CardDAV (cloud) ☆`76`
- [agentmail-to/agentmail-mcp](https://github.com/agentmail-to/agentmail-mcp) — Email for AI agents: create inboxes on the fly to send, receive and act on email. ☆`70`
- [mailtrap/mailtrap-mcp](https://github.com/mailtrap/mailtrap-mcp) — Official Mailtrap MCP server — over 125 tools to send email from Claude, Cursor, VS Code & other AI assistants. Send transactional and bulk email, test in Email Sandbox, manage templates, contacts, domains and webhooks, and inspect delivery logs and stats. ☆`66`
- [mailgun/mailgun-mcp-server](https://github.com/mailgun/mailgun-mcp-server) — Mailgun API integration ☆`63`
- [qubrics/qubrics-sdk](https://github.com/qubrics/qubrics-sdk) — Official monorepo of SDKs, CLI, and MCP servers for Sendmux email APIs across TypeScript, Python, Go, PHP, Rust, and Ruby. ☆`62`
- [Shy2593666979/mcp-server-email](https://github.com/Shy2593666979/mcp-server-email) — Email with attachments for Gmail, Outlook, QQ ☆`81`
- [openagentemail/openagentemail](https://github.com/openagentemail/openagentemail) — Open communication and task handoffs for AI agents - self-hosted email, task threads, approvals, and webhooks over MCP and REST. Apache-2.0. ☆`55`
- [desek/outlook-local-mcp](https://github.com/desek/outlook-local-mcp) — Local MCP server for Microsoft Outlook - calendars, events, and email via Microsoft Graph API ☆`45`
- [littlebearapps/outlook-assistant](https://github.com/littlebearapps/outlook-assistant) — MCP server for Outlook email, calendar, and contacts - let your AI assistant manage your inbox directly from the conversation. ☆`39`
- [marlinjai/email-mcp](https://github.com/marlinjai/email-mcp) — Unified MCP server for email access across Gmail, Outlook, iCloud, and IMAP ☆`26`
- [wildsurfer/your-mail-mcp](https://github.com/wildsurfer/your-mail-mcp) — Self-hosted, read-only MCP server that serves IMAP mail from a local notmuch index over authenticated HTTP ☆`20`
- [adecubed/gigamail](https://github.com/adecubed/gigamail) — Mail for AI agents ( and humans). MCP server giving Claude (or any agent) safe, permission-controlled access to email (Microsoft Graph + IMAP), calendar and your knowledge files. ☆`17`
- [egyptianego17/email-mcp-server](https://github.com/egyptianego17/email-mcp-server) — Send emails with attachments via SMTP ☆`28`
- [Zacccck/Claude-MCP-Read-Email-Attachments](https://github.com/Zacccck/Claude-MCP-Read-Email-Attachments) — Local MCP server for Claude Desktop to read Outlook emails/bodies/attachments and send local files as attachments. ☆`19`
### Messengers

- [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) — WhatsApp MCP server ☆`6,801`
- [chigwell/telegram-mcp](https://github.com/chigwell/telegram-mcp) — MCP server for Telegram messaging ☆`1,981`
- [line/line-bot-mcp-server](https://github.com/line/line-bot-mcp-server) — LINE Messaging API for AI agents ☆`797`
- [chaindead/telegram-mcp](https://github.com/chaindead/telegram-mcp) — Telegram dialogs, messages, drafts, statuses ☆`350`
- [reminia/zendesk-mcp-server](https://github.com/reminia/zendesk-mcp-server) — A Model Context Protocol server for Zendesk ☆`125`
- [cometchat/docs-mcp](https://github.com/cometchat/docs-mcp) — CometChat docs search + implementation bundles: add chat, voice, video & moderation to your app through your AI coding agent. ☆`137`
- [googlarz/proton-mail-bridge-client](https://github.com/googlarz/proton-mail-bridge-client) — Local-first Proton Mail MCP server and CLI via Proton Bridge. Search, draft, send and organize mail from Claude Desktop, Claude Code or any MCP client. 96 tools, read-only and ☆`85`
- [imdinu/apple-mail-mcp](https://github.com/imdinu/apple-mail-mcp) — Apple Mail MCP server with full-coverage FTS5 body search. Reliable on large mailboxes where AppleScript-based servers timeout. ☆`74`
- [ztxtxwd/open-feishu-mcp-server](https://github.com/ztxtxwd/open-feishu-mcp-server) — Feishu/Lark OAuth and document management ☆`87`
- [mcp-telegram/mcp-telegram](https://github.com/mcp-telegram/mcp-telegram) — Telegram MCP server: connect your personal Telegram account to Claude, ChatGPT, Cursor and any MCP client. 182 tools over MTProto. Self-host with npx or Docker, or use the hosted ☆`65`
- [areweai/tsgram-mcp](https://github.com/areweai/tsgram-mcp) — Telegram for local Claude Code debug ☆`88`
- [leshchenko1979/fast-mcp-telegram](https://github.com/leshchenko1979/fast-mcp-telegram) — Telegram MCP gateway for AI agents: 8 tools, multi-tenant HTTP/stdio, MTProto ☆`50`
- [kushneryk/join.cloud](https://github.com/kushneryk/join.cloud) — Join.cloud lets AI agents work together in real-time rooms. Agents join a room, exchange messages, commit files to shared storage, and optionally review each other's work - all ☆`66`
- [PhilflowIO/dav-mcp](https://github.com/PhilflowIO/dav-mcp) — Transform AI agents into orchestrating assistants managing calendars, contacts, and tasks ☆`42`
- [mjknowles/matrix-mcp-server](https://github.com/mjknowles/matrix-mcp-server) — Matrix server integration and chat ☆`57`
- [pubnub/pubnub-mcp-server](https://github.com/pubnub/pubnub-mcp-server) — PubNub Model Context Protocol Server ☆`33`
- [parasxos/apple-mail-mcp](https://github.com/parasxos/apple-mail-mcp) — MCP server for Apple Mail: sub-ms search over 300k+ messages via Mail's own SQLite index, verified sends, Exchange body backfill, triage plan/review/apply. 849 tests, MIT. ☆`34`
- [yjcho9317/nworks](https://github.com/yjcho9317/nworks) — Full-featured MCP server and CLI for LINE WORKS (NAVER WORKS) - 26 tools covering messages, calendar, drive, mail, tasks, and boards. Automate with AI agents or scripts. ☆`28`
- [belaytzev/Telebrief](https://github.com/belaytzev/Telebrief) — Personal digests from Telegram channels and chats: summarizes threads, extracts key points, and delivers a clean daily/weekly brief with links and context. ☆`25`
- [qpd-v/mcp-communicator-telegram](https://github.com/qpd-v/mcp-communicator-telegram) — An MCP server that enables communication with users through Telegram. This server provides a tool to ask questions to users and receive their responses via a Telegram bot. ☆`47`
- [ictinnovations/ictfax-mcp](https://github.com/ictinnovations/ictfax-mcp) — MCP server for ICTFax - list and track faxes, upload documents and send faxes over ICTCore REST. By ICT Innovations. ☆`17`
- [skeptrunedev/call4me](https://github.com/skeptrunedev/call4me) — Your coding agent makes phone calls for you: an MCP tool on Telnyx + OpenAI GPT-Live ☆`16`
- [gotoolkits/mcp-wecombot-server](https://github.com/gotoolkits/mcp-wecombot-server) — An MCP server application that sends various types of messages to the WeCom group robot. ☆`36`
- [DLHellMe/telegram-mcp-server](https://github.com/DLHellMe/telegram-mcp-server) — Scrape and analyze Telegram content ☆`31`
### Notifications

- [777genius/agent-notifications](https://github.com/777genius/agent-notifications) — Local MCP server for desktop attention and progress notifications. ☆`825`
- [gitmotion/ntfy-me-mcp](https://github.com/gitmotion/ntfy-me-mcp) — MCP server for ntfy push notifications ☆`75`
- [AshikNesin/pushover-mcp](https://github.com/AshikNesin/pushover-mcp) — A MCP implementation for sending notifications via Pushover ☆`43`
- [infobip/mcp](https://github.com/infobip/mcp) — Infobip Remote MCP Servers Documentation ☆`36`
- [Cactusinhand/mcp_server_notify](https://github.com/Cactusinhand/mcp_server_notify) — Send system notification when Agent task is done. ☆`54`
- [teddyzxcv/ntfy-mcp](https://github.com/teddyzxcv/ntfy-mcp) — MCP server for ntfy push notifications ☆`44`
- [aahl/mcp-notify](https://github.com/aahl/mcp-notify) — Notify to Weixin, Telegram, Bark, Lark, DingTalk ☆`29`
### Team Chat

- [korotovsky/slack-mcp-server](https://github.com/korotovsky/slack-mcp-server) — MCP server for Slack workspace integration ☆`1,882`
- [chatmcp/mcp-server-chatsum](https://github.com/chatmcp/mcp-server-chatsum) — Query and Summarize your chat messages. ☆`1,027`
- [SaseQ/discord-mcp](https://github.com/SaseQ/discord-mcp) — MCP server for Discord integration ☆`588`
- [joinly-ai/joinly](https://github.com/joinly-ai/joinly) — Make your meetings accessible to AI Agents ☆`569`
- [v-3/discordmcp](https://github.com/v-3/discordmcp) — Discord MCP Server for Claude Integration ☆`243`
- [discourse/discourse-mcp](https://github.com/discourse/discourse-mcp) — MCP client for Discourse sites ☆`79`
- [colibird-ai/local-mcp-releases](https://github.com/colibird-ai/local-mcp-releases) — Connect Claude, ChatGPT, Cursor and other AI assistants to your Mac and Windows apps: Mail, Messages, Teams, Slack, WhatsApp, Outlook, OneDrive, Google Drive and Office. The ☆`78`
- [zencoderai/slack-mcp-server](https://github.com/zencoderai/slack-mcp-server) — Slack workspace interaction and messaging ☆`75`
- [jtalk22/slack-mcp-server](https://github.com/jtalk22/slack-mcp-server) — Put your agent inside your Slack. Zero bots, zero admin queues, no Business+ upgrade - 20+ tools for stealth search, thread parsing and mention tracking. ☆`32`
- [PaSympa/discord-mcp](https://github.com/PaSympa/discord-mcp) — MCP server to control Discord - messages, channels, roles, permissions, members, and moderation ☆`31`
- [jagan-shanmugam/mattermost-mcp-host](https://github.com/jagan-shanmugam/mattermost-mcp-host) — Mattermost integration with LangGraph agent ☆`34`
### Voice & Telephony

- [voygr-tech/placecall](https://github.com/voygr-tech/placecall) — Hosted MCP server that phones US businesses for an agent and returns the outcome, transcript and recording ☆`110`
- [radres/call-me](https://github.com/radres/call-me) — Hosted MCP server that rings the user's iPhone so an agent can ask aloud and get the spoken answer; needs the paid /call-me iPhone app ☆`32`
- [ictinnovations/pbx-mcp](https://github.com/ictinnovations/pbx-mcp) — MCP server for Asterisk and FreeSWITCH. Lets AI assistants inspect channels, SIP registrations, trunk status and dialplan on a live PBX. ☆`19`
- [ictinnovations/ictpbx-mcp](https://github.com/ictinnovations/ictpbx-mcp) — Read-only MCP server for ICTPBX - extensions, DIDs, SIP trunks, tenants and PBX statistics over ICTCore REST. By ICT Innovations. ☆`16`
- [mohitbadwal/ringback](https://github.com/mohitbadwal/ringback) — Let your AI agent call your phone and talk to you - MCP servers for live, interruptible voice calls + tiered alerts, using free self-hosted pieces (pjsua2 + whisper.cpp + ☆`28`
- [gerkensm/callcenter.js-mcp](https://github.com/gerkensm/callcenter.js-mcp) — Callcenter.JS AI Voice Agent VOIP Connector, MCP + CLI ☆`25`
## Data & Analytics

### AI/ML Platforms

- [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) — Daily radar for new AI terms: names of new models, products and repos, caught on X, Hugging Face, GitHub and sitemaps before keyword tools list them. ☆`2,099`
- [MigoXLab/dingo](https://github.com/MigoXLab/dingo) — AI data, model, app quality evaluation ☆`764`
- [evalstate/mcp-hfspace](https://github.com/evalstate/mcp-hfspace) — HuggingFace Spaces integration ☆`389`
- [huggingface/hf-mcp-server](https://github.com/huggingface/hf-mcp-server) — Hugging Face MCP Server ☆`312`
- [YanxingLiu/dify-mcp-server](https://github.com/YanxingLiu/dify-mcp-server) — Model Context Protocol (MCP) Server for dify workflows ☆`279`
- [sato942/game-asset-mcp](https://github.com/sato942/game-asset-mcp) — An MCP server for creating 2D/3D game assets from text using Hugging Face AI models. ☆`166`
- [0xshellming/mcp-summarizer](https://github.com/0xshellming/mcp-summarizer) — MCP Server for AI Summarization ☆`167`
- [optuna/optuna-mcp](https://github.com/optuna/optuna-mcp) — Optuna hyperparameter optimization ☆`90`
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

- [reading-plus-ai/mcp-server-data-exploration](https://github.com/reading-plus-ai/mcp-server-data-exploration) — Interactive CSV data exploration ☆`543`
- [kdqed/zaturn](https://github.com/kdqed/zaturn) — Data Analysis With Vibes ☆`76`
- [brightlikethelight/networkx-mcp-server](https://github.com/brightlikethelight/networkx-mcp-server) — NetworkX graph algorithms for AI conversations ☆`22`
- [santoshray02/csv-editor](https://github.com/santoshray02/csv-editor) — AI-powered CSV data manipulation and analysis ☆`25`
### Data Platforms

- [dbt-labs/dbt-mcp](https://github.com/dbt-labs/dbt-mcp) — A MCP (Model Context Protocol) server for interacting with dbt. ☆`616`
- [kubeflow/mcp-apache-spark-history-server](https://github.com/kubeflow/mcp-apache-spark-history-server) — Apache Spark History Server bridge ☆`206`
- [microsoft/fabric-rti-mcp](https://github.com/microsoft/fabric-rti-mcp) — Fabric Real-Time Intelligence server ☆`133`
- [acryldata/mcp-server-datahub](https://github.com/acryldata/mcp-server-datahub) — Official MCP server for DataHub ☆`85`
- [keboola/mcp-server](https://github.com/keboola/mcp-server) — Model Context Protocol (MCP) Server for the Keboola Platform ☆`85`
- [bintocher/mcp-superset](https://github.com/bintocher/mcp-superset) — MCP server for managing Apache Superset - 128+ tools for dashboards, charts, datasets, SQL Lab, access control ☆`61`
- [thoughtspot/mcp-server](https://github.com/thoughtspot/mcp-server) — The ThoughtSpot MCP Server ☆`34`
- [aywengo/kafka-schema-reg-mcp](https://github.com/aywengo/kafka-schema-reg-mcp) — Kafka Schema Registry management ☆`32`
- [bruno-portfolio/agrobr-mcp](https://github.com/bruno-portfolio/agrobr-mcp) — MCP server for Brazilian agricultural data via agrobr - prices, crops, trade, climate, deforestation and fires from CEPEA, CONAB, IBGE, B3, INPE and more ☆`30`
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

- [datalayer/jupyter-mcp-server](https://github.com/datalayer/jupyter-mcp-server) — Model Context Protocol (MCP) Server for Jupyter. ☆`1,319`
- [jjsantos01/jupyter-notebook-mcp](https://github.com/jjsantos01/jupyter-notebook-mcp) — A Model Context Protocol (MCP) for Jupyter Notebook ☆`128`
- [phisanti/MCPR](https://github.com/phisanti/MCPR) — AI agents in interactive R sessions ☆`27`
### Visualization

- [antvis/mcp-server-chart](https://github.com/antvis/mcp-server-chart) — 25+ visual charts using @antvis for data analysis ☆`4,412`
- [hustcc/mcp-echarts](https://github.com/hustcc/mcp-echarts) — ECharts visual charts with AI ☆`268`
- [isaacwasserman/mcp-vegalite-server](https://github.com/isaacwasserman/mcp-vegalite-server) — MCP server for Vega-Lite data visualization ☆`100`
- [easecloudio/mcp-metabase-server](https://github.com/easecloudio/mcp-metabase-server) — A comprehensive MCP server for Metabase with 70+ tools. ☆`83`
- [palewire/datawrapper-mcp](https://github.com/palewire/datawrapper-mcp) — Create Datawrapper charts with AI ☆`61`
- [KyuRish/mcp-dashboards](https://github.com/KyuRish/mcp-dashboards) — Turn your data into interactive dashboards inside any AI client - MCP Apps powered ☆`52`
## Databases

### Analytics & Warehouses

- [ClickHouse/mcp-clickhouse](https://github.com/ClickHouse/mcp-clickhouse) — Connect ClickHouse to your AI assistants. ☆`901`
- [motherduckdb/mcp-server-motherduck](https://github.com/motherduckdb/mcp-server-motherduck) — Local MCP server for DuckDB and MotherDuck ☆`539`
- [Snowflake-Labs/mcp](https://github.com/Snowflake-Labs/mcp) — Snowflake Cortex AI and SQL orchestration ☆`303`
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

- [redis/mcp-redis](https://github.com/redis/mcp-redis) — MCP server for Redis database operations ☆`641`
- [aliyun/alibabacloud-tablestore-mcp-server](https://github.com/aliyun/alibabacloud-tablestore-mcp-server) — MCP server for Alibaba Tablestore NoSQL ☆`157`
- [upstash/mcp-server](https://github.com/upstash/mcp-server) — Upstash Model Context Server ☆`61`
- [prajwalnayak7/mcp-server-redis](https://github.com/prajwalnayak7/mcp-server-redis) — MCP server to interact with Redis Server, AWS Memory DB, etc for caching or other use-cases where in-memory and key-value based storage is appropriate ☆`25`
### Cloud Platforms

- [instantdb/instant](https://github.com/instantdb/instant) — Modern Firebase with real-time database ☆`10,563`
- [supabase/mcp](https://github.com/supabase/mcp) — Connect Supabase to your AI assistants ☆`2,991`
- [alexander-zuev/supabase-mcp-server](https://github.com/alexander-zuev/supabase-mcp-server) — MCP server for Supabase database and auth ☆`835`
- [neondatabase/mcp-server-neon](https://github.com/neondatabase/mcp-server-neon) — Neon Management API and databases ☆`660`
- [planetscale/cli](https://github.com/planetscale/cli) — The CLI for PlanetScale Database ☆`671`
- [gannonh/firebase-mcp](https://github.com/gannonh/firebase-mcp) — Model Context Protocol (MCP) server for Firebase. ☆`247`
- [coleam00/supabase-mcp](https://github.com/coleam00/supabase-mcp) — Supabase MCP server created in Python. ☆`194`
- [Aiven-Open/mcp-aiven](https://github.com/Aiven-Open/mcp-aiven) — Model Context Protocol server for Aiven ☆`28`
- [JoshuaRileyDev/supabase-mcp-server](https://github.com/JoshuaRileyDev/supabase-mcp-server) — MCP server for Supabase database operations ☆`52`
- [niledatabase/nile-mcp-server](https://github.com/niledatabase/nile-mcp-server) — Nile Database tenants, users, auth for LLMs ☆`19`
### Graph Databases

- [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j) — Neo4j Labs Model Context Protocol servers ☆`989`
- [neo4j-contrib/gds-agent](https://github.com/neo4j-contrib/gds-agent) — Neo4j Graph Data Science tools ☆`99`
- [FalkorDB/FalkorDB-MCPServer](https://github.com/FalkorDB/FalkorDB-MCPServer) — Connect LLMs to FalkorDB ☆`42`
- [da-okazaki/mcp-neo4j-server](https://github.com/da-okazaki/mcp-neo4j-server) — mcp-neo4j-server ☆`60`
- [ravenwits/mcp-server-arangodb](https://github.com/ravenwits/mcp-server-arangodb) — ArangoDB database interaction ☆`46`
### Multi-Database Tools

- [googleapis/mcp-toolbox](https://github.com/googleapis/mcp-toolbox) — Open source database MCP toolbox ☆`16,797`
- [bytebase/dbhub](https://github.com/bytebase/dbhub) — Token-efficient multi-database MCP ☆`3,780`
- [damms005/devdb-vscode](https://github.com/damms005/devdb-vscode) — Zero-config VS Code database extension ☆`1,454`
- [centralmind/gateway](https://github.com/centralmind/gateway) — Universal database MCP for LLMs ☆`549`
- [FreePeak/db-mcp-server](https://github.com/FreePeak/db-mcp-server) — MCP server for database operations ☆`479`
- [runekaagaard/mcp-alchemy](https://github.com/runekaagaard/mcp-alchemy) — MCP server for SQLAlchemy database operations ☆`422`
- [executeautomation/mcp-database-server](https://github.com/executeautomation/mcp-database-server) — Connect to SQLite, SQL Server, PostgreSQL ☆`389`
- [XGenerationLab/xiyan_mcp_server](https://github.com/XGenerationLab/xiyan_mcp_server) — Natural language database queries ☆`238`
- [memgraph/ai-toolkit](https://github.com/memgraph/ai-toolkit) — Open-source tools for AI on Memgraph: persistent agent memory, knowledge graphs, GraphRAG, and integrations for LangChain, LightRAG, and MCP. ☆`118`
- [FROWNINGdev/orm-lens](https://github.com/FROWNINGdev/orm-lens) — ER diagrams, N+1 detection, schema drift & migration-risk linting for Django and SQLAlchemy (Alembic) - VS Code, CLI and MCP server. Static analysis: no database, no app boot. ☆`98`
- [appwrite/mcp](https://github.com/appwrite/mcp) — Appwrite's MCP server. Operating your backend has never been easier. ☆`72`
- [yimindev/dati](https://github.com/yimindev/dati) — Turn your database into secure, semantically rich MCP tools for agents. ☆`74`
- [AzureCosmosDB/azure-cosmos-mcp-server-samples](https://github.com/AzureCosmosDB/azure-cosmos-mcp-server-samples) — This repository contains a collection of sample implementations of the MCP across multiple programming languages, all backed by Azure Cosmos DB. These examples demonstrate how to ☆`64`
- [s2-streamstore/s2-sdk-typescript](https://github.com/s2-streamstore/s2-sdk-typescript) — TypeScript SDK for S2, the durable streams API ☆`37`
- [cyanheads/filesystem-mcp-server](https://github.com/cyanheads/filesystem-mcp-server) — A Model Context Protocol (MCP) server for platform-agnostic file capabilities, including advanced search/replace and directory tree traversal ☆`54`
- [schemacrawler/SchemaCrawler-AI-MCP-Server-Usage](https://github.com/schemacrawler/SchemaCrawler-AI-MCP-Server-Usage) — How to use SchemaCrawler AI MCP Server ☆`30`
- [ExpeditedProjects/hutchdb](https://github.com/ExpeditedProjects/hutchdb) — A database for AI agents. No schema, SQL, or structure required. Claude Code, Codex, Cursor, Hermes, Claw, Grokbot, and other MCP clients store, query, and share the same ☆`24`
- [spences10/mcp-turso-cloud](https://github.com/spences10/mcp-turso-cloud) — A Model Context Protocol (MCP) server that provides integration with Turso databases for LLMs. This server implements a two-level authentication system to handle both ☆`18`
- [codeurali/mcp-dataverse](https://github.com/codeurali/mcp-dataverse) — MCP server for Microsoft Dataverse Web API for devs ! ☆`18`
- [FocusSearch/focus_mcp_sql](https://github.com/FocusSearch/focus_mcp_sql) — A NL2SQL plugin based on FocusSearch keyword parsing, offering greater accuracy, higher speed, and more reliability! ☆`38`
- [fireproof-storage/mcp-database-server](https://github.com/fireproof-storage/mcp-database-server) — Store and load JSON documents from LLM tool use ☆`31`
- [theronic/datomic-mcp](https://github.com/theronic/datomic-mcp) — Datomic MCP Server so your AI model can query your database (uses Modex MCP library) ☆`25`
- [datastrato/mcp-server-gravitino](https://github.com/datastrato/mcp-server-gravitino) — MCP server for Apache Gravitino ☆`23`
- [keonchennl/mcp-server-graphdb](https://github.com/keonchennl/mcp-server-graphdb) — A Model Context Protocol server that provides read only access to graphs in a certain repository in Ontotext GraphDB. This server enables LLMs to execute SPARQL queries. ☆`17`
- [OpenLinkSoftware/mcp-jdbc-server](https://github.com/OpenLinkSoftware/mcp-jdbc-server) — Java JDBC access for SQL databases ☆`17`
### NoSQL & Document

- [mongodb-js/mongodb-mcp-server](https://github.com/mongodb-js/mongodb-mcp-server) — Connect to MongoDB and Atlas clusters ☆`1,156`
- [kiliczsh/mcp-mongo-server](https://github.com/kiliczsh/mcp-mongo-server) — A Model Context Protocol Server for MongoDB ☆`284`
- [furey/mongodb-lens](https://github.com/furey/mongodb-lens) — MongoDB Lens: Full Featured MCP Server for MongoDB Databases ☆`207`
- [QuantGeekDev/mongo-mcp](https://github.com/QuantGeekDev/mongo-mcp) — A mongo db server for the model context protocol (MCP) ☆`176`
- [datastax/astra-db-mcp](https://github.com/datastax/astra-db-mcp) — An MCP server for Astra DB workloads ☆`43`
- [couchbase/mcp-server-couchbase](https://github.com/couchbase/mcp-server-couchbase) — Couchbase database cluster integration ☆`34`
- [Knuckles-Team/vector-mcp](https://github.com/Knuckles-Team/vector-mcp) — Vector MCP Server for AI Agents - Supports ChromaDB, Couchbase, MongoDB, Qdrant, and PGVector ☆`16`
### SQL Databases

- [crystaldba/postgres-mcp](https://github.com/crystaldba/postgres-mcp) — Postgres with read/write access and performance ☆`3,452`
- [benborla/mcp-server-mysql](https://github.com/benborla/mcp-server-mysql) — MCP server for MySQL database operations ☆`2,201`
- [designcomputer/mysql_mcp_server](https://github.com/designcomputer/mysql_mcp_server) — Secure MySQL database interaction ☆`1,407`
- [subnetmarco/pgmcp](https://github.com/subnetmarco/pgmcp) — An MCP server to query any Postgres database in natural language. ☆`542`
- [agent-next/polymarket-paper-trader](https://github.com/agent-next/polymarket-paper-trader) — Paper trading simulator for Polymarket ☆`495`
- [oracle/mcp](https://github.com/oracle/mcp) — Repository containing MCP (Model Context Protocol) servers that provides a suite of tools for managing and interacting with Oracle products. ☆`473`
- [RichardHan/mssql_mcp_server](https://github.com/RichardHan/mssql_mcp_server) — A Model Context Protocol (MCP) server for Microsoft SQL Server that enables secure database interactions through a controlled interface. Allows AI assistants to safely list ☆`401`
- [apache/doris-mcp-server](https://github.com/apache/doris-mcp-server) — Apache Doris MCP Server ☆`357`
- [MariaDB/mcp](https://github.com/MariaDB/mcp) — MariaDB MCP (Model Context Protocol) server implementation ☆`217`
- [wenb1n-dev/mysql_mcp_server_pro](https://github.com/wenb1n-dev/mysql_mcp_server_pro) — Enhanced MySQL with anomaly analysis ☆`249`
- [StarRocks/mcp-server-starrocks](https://github.com/StarRocks/mcp-server-starrocks) — StarRocks MCP (Model Context Protocol) Server ☆`196`
- [HenkDz/postgresql-mcp-server](https://github.com/HenkDz/postgresql-mcp-server) — A Powerful PostgreSQL MCP server with 14 consolidated database management tools for AI assistants. ☆`204`
- [ashishsinha1602/schemagate](https://github.com/ashishsinha1602/schemagate) — Text-to-SQL access control: schema selection that gives the LLM only the tables the caller is allowed to read. Row-level-security-aware table pruning for LangChain, MCP and any ☆`173`
- [call518/MCP-PostgreSQL-Ops](https://github.com/call518/MCP-PostgreSQL-Ops) — PostgreSQL operations and monitoring ☆`164`
- [f4ww4z/mcp-mysql-server](https://github.com/f4ww4z/mcp-mysql-server) — A Model Context Protocol server for MySQL database operations ☆`171`
- [tuannvm/mcp-trino](https://github.com/tuannvm/mcp-trino) — High-performance Trino MCP in Go ☆`122`
- [jparkerweb/mcp-sqlite](https://github.com/jparkerweb/mcp-sqlite) — Comprehensive SQLite interaction ☆`130`
- [oceanbase/awesome-oceanbase-mcp](https://github.com/oceanbase/awesome-oceanbase-mcp) — MCP Server for OceanBase database and its tools ☆`110`
- [hannesrudolph/sqlite-explorer-fastmcp-mcp-server](https://github.com/hannesrudolph/sqlite-explorer-fastmcp-mcp-server) — Read-only SQLite database access ☆`108`
- [wenb1n-dev/SmartDB_MCP](https://github.com/wenb1n-dev/SmartDB_MCP) — Universal database MCP for MySQL, PostgreSQL, Oracle and more ☆`78`
- [Teradata/teradata-mcp-server](https://github.com/Teradata/teradata-mcp-server) — Teradata database integration ☆`58`
- [donghao1393/mcp-dbutils](https://github.com/donghao1393/mcp-dbutils) — Multi-database connector for SQLite, MySQL, PostgreSQL ☆`89`
- [JexinSam/mssql_mcp_server](https://github.com/JexinSam/mssql_mcp_server) — A Model Context Protocol (MCP) server facilitating secure interactions with MSSQL databases. ☆`60`
- [shkyyy18/mi_fitness_data_bridge](https://github.com/shkyyy18/mi_fitness_data_bridge) — Unofficial Mi Fitness data export to local SQLite, CSV and JSON, with a local stdio MCP server. 小米运动健康数据导出；实验性，兼容性依设备与地区而异。 ☆`62`
- [aliyun/alibabacloud-rds-openapi-mcp-server](https://github.com/aliyun/alibabacloud-rds-openapi-mcp-server) — MCP server for RDS Services via OPENAPI. ☆`54`
- [Zhwt/go-mcp-mysql](https://github.com/Zhwt/go-mcp-mysql) — Go-based MCP server for MySQL ☆`66`
- [drhalto/agentmako](https://github.com/drhalto/agentmako) — Local-first MCP server that gives coding agents structured context packets, code/schema facts, and diagnostics - backed by a local SQLite store. ☆`54`
- [haymon-ai/dbmcp](https://github.com/haymon-ai/dbmcp) — Database MCP server for MySQL, MariaDB, PostgreSQL, and SQLite - with builtin PII redaction and write-prevention ☆`33`
- [ydb-platform/ydb-mcp](https://github.com/ydb-platform/ydb-mcp) — MCP server for YDB distributed database ☆`29`
- [antonorlov/mcp-postgres-server](https://github.com/antonorlov/mcp-postgres-server) — MCP server for PostgreSQL. Works with VS Code, Cursor, Claude Code, Codex, and Windsurf. ☆`24`
- [slotix/dbconvert-streams-public](https://github.com/slotix/dbconvert-streams-public) — DBConvert Streams: Database IDE, Federated SQL, Real-time CDC & AI assistants via MCP - explore, query, and replicate data across databases and files ☆`24`
- [B0yko/pgwarden](https://github.com/B0yko/pgwarden) — Governed Postgres access for AI assistants: an MCP gateway with OAuth 2.1 and OIDC login, one Postgres role per person, database-enforced read-only queries, PII masking, ☆`23`
- [Xexr/mcp-libsql](https://github.com/Xexr/mcp-libsql) — MCP server for libSQL database ☆`21`
- [singlestore-labs/mcp-server-singlestore](https://github.com/singlestore-labs/mcp-server-singlestore) — SingleStore database management API ☆`33`
- [dolthub/dolt-mcp](https://github.com/dolthub/dolt-mcp) — The MCP server for Dolt ☆`19`
- [pingcap/pytidb](https://github.com/pingcap/pytidb) — TiDB AI SDK for apps and agents ☆`34`
- [isdaniel/pgtuner_mcp](https://github.com/isdaniel/pgtuner_mcp) — provides AI-powered PostgreSQL performance tuning capabilities. ☆`30`
- [tyrchen/postgres-mcp](https://github.com/tyrchen/postgres-mcp) — postgres mcp implementation ☆`33`
- [rahgadda/oracledb_mcp_server](https://github.com/rahgadda/oracledb_mcp_server) — MCP server to connect to Oracle Database ☆`35`
- [ahmedmustahid/postgres-mcp-server](https://github.com/ahmedmustahid/postgres-mcp-server) — MCP server for PostgreSQL ☆`31`
- [panasenco/mcp-sqlite](https://github.com/panasenco/mcp-sqlite) — SQLite with Datasette metadata support ☆`28`
- [NetanelBollag/simple-psql-mcp](https://github.com/NetanelBollag/simple-psql-mcp) — A beginner-friendly MCP server template featuring a PostgreSQL connector with clean, easy-to-understand code. Perfect for developers new to Model Context Protocol who want to ☆`32`
- [ian-cowley/MCPSqlServer](https://github.com/ian-cowley/MCPSqlServer) — SQL Server MCP Server - A standalone MCP server providing SQL Server integration capabilities ☆`19`
- [amornpan/py-mcp-mssql](https://github.com/amornpan/py-mcp-mssql) — py-mcp-mssql ☆`27`
- [vignesh-codes/ai-agents-mcp-pg](https://github.com/vignesh-codes/ai-agents-mcp-pg) — This repo is an extension of PostgreSQL MCP Server providing functionalities to create tables, insert entries, update entries, delete entries, and drop tables. ☆`27`
- [syahiidkamil/mcp-postgres-full-access](https://github.com/syahiidkamil/mcp-postgres-full-access) — Full access postgres mcp server ☆`25`
- [hdcola/mcp-server-oracle](https://github.com/hdcola/mcp-server-oracle) — Model Context Protocol server to access oracle database ☆`25`
- [dave-wind/mysql-mcp-server](https://github.com/dave-wind/mysql-mcp-server) — mcp model-context-protocol mysql cursor n8n ☆`16`
- [aliyun/alibabacloud-adbpg-mcp-server](https://github.com/aliyun/alibabacloud-adbpg-mcp-server) — AnalyticDB PostgreSQL metadata and SQL operations ☆`16`
- [shibayu36/mysql-schema-explorer-mcp](https://github.com/shibayu36/mysql-schema-explorer-mcp) — Facilitates efficient access to MySQL database schema information using the Model Context Protocol, ideal for large-scale databases. ☆`22`
- [OpenLinkSoftware/mcp-sqlalchemy-server](https://github.com/OpenLinkSoftware/mcp-sqlalchemy-server) — ODBC server with FastAPI and SQLAlchemy ☆`25`
- [c4pt0r/mcp-server-tidb](https://github.com/c4pt0r/mcp-server-tidb) — mcp server for tidb ☆`24`
- [cuongtl1992/mcp-dbs](https://github.com/cuongtl1992/mcp-dbs) — The MCP Server support your LLMs integrate with SQL Database (SQLite, SQL Server, Postgres SQL) ☆`21`
- [abel9851/mcp-server-mariadb](https://github.com/abel9851/mcp-server-mariadb) — An mcp server that provides read-only access to MariaDB. ☆`20`
- [Dataring-engineering/mcp-server-trino](https://github.com/Dataring-engineering/mcp-server-trino) — MCP Server for Trino ☆`18`
### Search Engines

- [elastic/mcp-server-elasticsearch](https://github.com/elastic/mcp-server-elasticsearch) — Elasticsearch queries and index management ☆`729`
- [cr7258/elasticsearch-mcp-server](https://github.com/cr7258/elasticsearch-mcp-server) — Elasticsearch and OpenSearch interaction ☆`314`
- [meilisearch/meilisearch-mcp](https://github.com/meilisearch/meilisearch-mcp) — Meilisearch interaction via LLM interfaces ☆`198`
- [opensearch-project/opensearch-mcp-server-py](https://github.com/opensearch-project/opensearch-mcp-server-py) — OpenSearch cluster interaction for AI ☆`158`
- [vectorize-io/vectorize-mcp-server](https://github.com/vectorize-io/vectorize-mcp-server) — Official Vectorize MCP Server ☆`115`
- [suhail-ak-2/mcp-typesense-server](https://github.com/suhail-ak-2/mcp-typesense-server) — Typesense search for AI assistants ☆`19`
### Spreadsheets & No-Code

- [baserow/baserow](https://github.com/baserow/baserow) — No-code database, apps, agents with AI ☆`6,270`
- [xing5/mcp-google-sheets](https://github.com/xing5/mcp-google-sheets) — Google Drive and Sheets integration ☆`1,016`
- [negokaz/excel-mcp-server](https://github.com/negokaz/excel-mcp-server) — A Model Context Protocol (MCP) server that reads and writes MS Excel data ☆`1,046`
- [busabase/busabase](https://github.com/busabase/busabase) — Open-source database & workspace for AI agents - structured data, durable knowledge, reusable skills, runnable apps, and human review on the writes that matter. Local-first and ☆`692`
- [domdomegg/airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server) — Airtable bases integration for AI systems ☆`456`
- [freema/mcp-gsheets](https://github.com/freema/mcp-gsheets) — Google Sheets read, write, manipulate ☆`104`
- [rashidazarang/airtable-mcp](https://github.com/rashidazarang/airtable-mcp) — Airtable integration for AI applications ☆`87`
- [PSU3D0/agent-spreadsheet](https://github.com/PSU3D0/agent-spreadsheet) — MCP server for spreadsheet analysis and editing. Slim, token-efficient tool surface designed for LLM agents. ☆`63`
- [edwinbernadus/nocodb-mcp-server](https://github.com/edwinbernadus/nocodb-mcp-server) — nocodb mcp server ☆`76`
- [felores/airtable-mcp](https://github.com/felores/airtable-mcp) — Manage Airtable bases and records ☆`75`
- [logisky/logisheets-mcp](https://github.com/logisky/logisheets-mcp) — give your AI agent a spreadsheet it can actually think in: deterministic Excel-compatible math + structured memory (blocks), real .xlsx out. Open source, self-hostable. ☆`41`
- [proompteng/bilig](https://github.com/proompteng/bilig) — Headless spreadsheet formulas, edits, and JSON persistence ☆`35`
- [kazz187/mcp-google-spreadsheet](https://github.com/kazz187/mcp-google-spreadsheet) — MCP Server for Google Spreadsheet ☆`51`
- [VOYAGER-Inc/excel-vision-mcp](https://github.com/VOYAGER-Inc/excel-vision-mcp) — MCP server that lets AI agents SEE embedded images inside Excel files - full text + image extraction for .xlsx/.xlsm ☆`20`
### Streaming & Messaging

- [confluentinc/mcp-confluent](https://github.com/confluentinc/mcp-confluent) — MCP server for Confluent Kafka platform ☆`168`
- [kanapuli/mcp-kafka](https://github.com/kanapuli/mcp-kafka) — A Model Context Protocol Server to perform Kafka client operations ☆`82`
- [amazon-mq/mcp-server-rabbitmq](https://github.com/amazon-mq/mcp-server-rabbitmq) — MCP server for RabbitMQ ☆`43`
- [tuannvm/kafka-mcp-server](https://github.com/tuannvm/kafka-mcp-server) — Apache Kafka server in Go ☆`57`
- [kenliao94/mcp-server-rabbitmq](https://github.com/kenliao94/mcp-server-rabbitmq) — MCP server for interacting with RabbitMQ ☆`38`
### Time-Series & Metrics

- [GreptimeTeam/greptimedb](https://github.com/GreptimeTeam/greptimedb) — Unified observability DB for metrics, logs, traces ☆`6,783`
- [pab1it0/prometheus-mcp-server](https://github.com/pab1it0/prometheus-mcp-server) — MCP server for Prometheus metrics ☆`522`
- [VictoriaMetrics/mcp-victorialogs](https://github.com/VictoriaMetrics/mcp-victorialogs) — VictoriaLogs log management integration ☆`107`
- [idoru/influxdb-mcp-server](https://github.com/idoru/influxdb-mcp-server) — An MCP Server for querying InfluxDB ☆`47`
- [apache/iotdb-mcp-server](https://github.com/apache/iotdb-mcp-server) — Apache IoTDB MCP Server ☆`39`
- [influxdata/influxdb3_mcp_server](https://github.com/influxdata/influxdb3_mcp_server) — MCP Server for InfluxDB 3 ☆`38`
- [GreptimeTeam/greptimedb-mcp-server](https://github.com/GreptimeTeam/greptimedb-mcp-server) — A Model Context Protocol (MCP) server for GreptimeDB ☆`29`
### Vector Databases

- [qdrant/mcp-server-qdrant](https://github.com/qdrant/mcp-server-qdrant) — Official Qdrant vector database MCP ☆`1,562`
- [chroma-core/chroma-mcp](https://github.com/chroma-core/chroma-mcp) — Chroma vector database capabilities ☆`601`
- [zilliztech/mcp-server-milvus](https://github.com/zilliztech/mcp-server-milvus) — Model Context Protocol Servers for Milvus ☆`246`
- [weaviate/mcp-server-weaviate](https://github.com/weaviate/mcp-server-weaviate) — MCP (Model Context Protocol) server for Weaviate ☆`162`
- [pinecone-io/pinecone-mcp](https://github.com/pinecone-io/pinecone-mcp) — Connect Pinecone to AI assistants ☆`72`
- [mhalder/qdrant-mcp-server](https://github.com/mhalder/qdrant-mcp-server) — MCP server for semantic search using local Qdrant vector database and OpenAI embeddings ☆`36`
- [privetin/chroma](https://github.com/privetin/chroma) — MCP server for Chroma ☆`41`
- [delorenj/mcp-qdrant-memory](https://github.com/delorenj/mcp-qdrant-memory) — MCP server providing a knowledge graph implementation with semantic search capabilities powered by Qdrant vector database ☆`24`
- [p-funk/fegis](https://github.com/p-funk/fegis) — Define AI tools in YAML with natural language schemas. All tool usage is automatically stored in Qdrant vector database, enabling semantic search, filtering, and memory retrieval ☆`24`
## Developer Tools

### API Tools

- [tadata-org/fastapi_mcp](https://github.com/tadata-org/fastapi_mcp) — Expose FastAPI endpoints as MCP tools ☆`12,026`
- [WordPress/mcp-adapter](https://github.com/WordPress/mcp-adapter) — Bridge Abilities API to MCP ☆`1,902`
- [zcaceres/fetch-mcp](https://github.com/zcaceres/fetch-mcp) — A flexible HTTP fetching Model Context Protocol server. ☆`836`
- [automation-ai-labs/mcp-link](https://github.com/automation-ai-labs/mcp-link) — Convert Any OpenAPI V3 API to MCP Server ☆`624`
- [blurrah/mcp-graphql](https://github.com/blurrah/mcp-graphql) — Model Context Protocol server for GraphQL ☆`407`
- [postmanlabs/postman-mcp-server](https://github.com/postmanlabs/postman-mcp-server) — Postman collections, OpenAPI specs, and environments ☆`325`
- [apollographql/apollo-mcp-server](https://github.com/apollographql/apollo-mcp-server) — Apollo MCP Server ☆`318`
- [MFYDev/ghost-mcp](https://github.com/MFYDev/ghost-mcp) — Interact with Ghost CMS via LLM ☆`243`
- [hostinger/api-mcp-server](https://github.com/hostinger/api-mcp-server) — MCP server for Hostinger API integration ☆`168`
- [getmockd/mockd](https://github.com/getmockd/mockd) — High-performance, multi-protocol mock server. HTTP, WebSocket, gRPC, MQTT, SSE, GraphQL, SOAP in one binary. ☆`155`
- [webflow/mcp-server](https://github.com/webflow/mcp-server) — Model Context Protocol (MCP) server for the Webflow Data API. ☆`140`
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

- [czlonkowski/n8n-mcp](https://github.com/czlonkowski/n8n-mcp) — Build n8n workflows with AI assistants ☆`23,208`
- [leonardsellem/n8n-mcp-server](https://github.com/leonardsellem/n8n-mcp-server) — Tools for interacting with n8n API ☆`1,630`
- [googleapis/gcloud-mcp](https://github.com/googleapis/gcloud-mcp) — gcloud MCP server ☆`943`
- [utensils/mcp-nixos](https://github.com/utensils/mcp-nixos) — MCP-NixOS - Model Context Protocol Server for NixOS resources ☆`874`
- [ckreiling/mcp-server-docker](https://github.com/ckreiling/mcp-server-docker) — MCP server for Docker ☆`752`
- [vercel-labs/mcp-handler](https://github.com/vercel-labs/mcp-handler) — Easily spin up an MCP Server on Next.js, Nuxt, Svelte, and more ☆`694`
- [QuantGeekDev/docker-mcp](https://github.com/QuantGeekDev/docker-mcp) — A docker MCP Server (modelcontextprotocol) ☆`504`
- [TencentEdgeOne/edgeone-makers-mcp](https://github.com/TencentEdgeOne/edgeone-makers-mcp) — Deploy HTML to EdgeOne Pages with public URL ☆`440`
- [jamsocket/forevervm](https://github.com/jamsocket/forevervm) — Stateful AI code sandboxes ☆`230`
- [docker/hub-mcp](https://github.com/docker/hub-mcp) — Docker Hub MCP Server ☆`171`
- [MatanYemini/bitbucket-mcp](https://github.com/MatanYemini/bitbucket-mcp) — Bitbucket MCP - A Model Context Protocol (MCP) server for integrating with Bitbucket Cloud and Server APIs ☆`167`
- [DefangLabs/defang](https://github.com/DefangLabs/defang) — MCP server for Defang cloud deployment ☆`167`
- [yangkyeongmo/mcp-server-apache-airflow](https://github.com/yangkyeongmo/mcp-server-apache-airflow) — MCP server for Apache Airflow workflows ☆`182`
- [nacos-group/nacos-mcp-router](https://github.com/nacos-group/nacos-mcp-router) — MCP server discovery, install, and proxy ☆`183`
- [harness/mcp-server](https://github.com/harness/mcp-server) — Harness’ official MCP Server ☆`111`
- [OctopusDeploy/mcp-server](https://github.com/OctopusDeploy/mcp-server) — Octopus Deploy Official MCP Server ☆`103`
- [buildkite/buildkite-mcp-server](https://github.com/buildkite/buildkite-mcp-server) — Official MCP Server for Buildkite. ☆`56`
- [Vortiago/mcp-azure-devops](https://github.com/Vortiago/mcp-azure-devops) — AI assistants with Azure DevOps ☆`79`
- [call518/MCP-Airflow-API](https://github.com/call518/MCP-Airflow-API) — Apache Airflow API integration ☆`54`
- [bitrise-io/bitrise-mcp](https://github.com/bitrise-io/bitrise-mcp) — Bitrise CI/CD app and build management ☆`43`
- [Daghis/teamcity-mcp](https://github.com/Daghis/teamcity-mcp) — Model Context Protocol (MCP) server for JetBrains TeamCity: control builds, tests, agents and configs from AI coding assistants. ☆`31`
- [ruudmens/Koppla](https://github.com/ruudmens/Koppla) — A Model-Context-Protocol (MCP) Server for Active Directory ☆`58`
- [launchdarkly/mcp-server](https://github.com/launchdarkly/mcp-server) — LaunchDarkly's locally hostable Model Context Protocol (MCP) Server ☆`27`
- [IvanAmador/vercel-ai-docs-mcp](https://github.com/IvanAmador/vercel-ai-docs-mcp) — Vercel AI SDK documentation search ☆`50`
- [leonardosepulvedat/mcp-n8n](https://github.com/leonardosepulvedat/mcp-n8n) — n8n API plus 100 workflow templates with matching ☆`21`
- [raye-deng/open-code-review](https://github.com/raye-deng/open-code-review) — AI code quality gate for AI-generated code. Detects hallucinated packages, phantom dependencies, stale APIs, and more. MCP Server + CLI + CI/CD Action. ☆`40`
- [gofireflyio/firefly-mcp](https://github.com/gofireflyio/firefly-mcp) — Firefly MCP ☆`16`
- [configcat/mcp-server](https://github.com/configcat/mcp-server) — Official ConfigCat Model Context Protocol (MCP) Server ☆`17`
- [ruibaby/1Panel-mcp](https://github.com/ruibaby/1Panel-mcp) — A MCP server for automated website deployment to 1Panel (Experimental) ☆`36`
- [prassanna-ravishankar/clearml-mcp](https://github.com/prassanna-ravishankar/clearml-mcp) — lightweight MCP server for ClearML ☆`17`
- [endorhq/cli](https://github.com/endorhq/cli) — Sandboxed environments for favorite services via MCP ☆`26`
- [serkanh/cloudwatch-logs-mcp](https://github.com/serkanh/cloudwatch-logs-mcp) — A Python-based MCP server providing direct access to AWS CloudWatch logs, with tools for listing log groups and retrieving filtered log entries, built on FastMCP and boto3.... ☆`27`
- [conductor-oss/conductor-mcp](https://github.com/conductor-oss/conductor-mcp) — Model Context Protocol server for Orkes Conductor ☆`16`
- [shinzo-labs/heimdall](https://github.com/shinzo-labs/heimdall) — Control the tools your MCP-enabled agents can access with minimal overhead. ☆`21`
- [axliupore/mcp-code-runner](https://github.com/axliupore/mcp-code-runner) — MCP server for executing code in Docker containers ☆`18`
### Code Analysis

- [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) — Local code intelligence for developers and AI agents. Connect code, docs and infrastructure in a persistent graph, with CBM Lens, MCP tools, agent integrations and change-aware ☆`48,109`
- [kucherenko/jscpd](https://github.com/kucherenko/jscpd) — Copy/paste detector for source code. 220+ languages, Rust engine, SARIF/HTML/badge reporters, GitHub Action, MCP server for AI agents. ☆`6,499`
- [cocoindex-io/cocoindex-code](https://github.com/cocoindex-io/cocoindex-code) — A super light-weight embedded code search engine CLI (AST based) that just works - improves speed and efficiency for coding agent Star if you like it! ☆`2,963`
- [Mibayy/token-savior](https://github.com/Mibayy/token-savior) — MCP server that gets Claude to 97.9% (188/192) on a real coding benchmark at -80% active tokens and -83% wall time, vs 78.3% plain. Structural code navigation + persistent memory ☆`1,204`
- [bgauryy/octocode](https://github.com/bgauryy/octocode) — MCP server for semantic code search and context generation ☆`956`
- [bgauryy/octocode](https://github.com/bgauryy/octocode) — Code research platform for AI agents; find, understand, and prove context across your code and all of GitHub, in a fraction of the tokens. One toolset, MCP or CLI ☆`956`
- [SonarSource/sonarqube-mcp-server](https://github.com/SonarSource/sonarqube-mcp-server) — Official SonarQube quality and security for agents ☆`678`
- [Muvon/octocode](https://github.com/Muvon/octocode) — Structural code intelligence for AI agents - semantic search, knowledge graphs, and a built-in MCP server in one Rust binary. Give Claude, Cursor, and any MCP client a deep ☆`520`
- [admica/FileScopeMCP](https://github.com/admica/FileScopeMCP) — Codebase dependency diagrams ☆`302`
- [ozgurcd/gograph](https://github.com/ozgurcd/gograph) — Local-only Go static analysis engine with a built-in MCP server. Gives AI coding agents deterministic structural awareness: call graphs, impact analysis, symbol search, and more. ☆`231`
- [nikolai-vysotskyi/trace-mcp](https://github.com/nikolai-vysotskyi/trace-mcp) — Framework-aware code intelligence MCP server - 91 framework integrations, 81 languages, 72.7% fewer input tokens to review a pull request, comprehension at parity ☆`202`
- [janreges/ai-distiller](https://github.com/janreges/ai-distiller) — Fast tool for extracting essential public information from code ☆`172`
- [ajitpratap0/GoSQLX](https://github.com/ajitpratap0/GoSQLX) — Pure-Go SQL parser, formatter, linter and security scanner for 8 dialects. Zero-copy, race-free, with an LSP and MCP server. ☆`124`
- [SimplyLiz/ckb](https://github.com/SimplyLiz/ckb) — Code intelligence for AI assistants - MCP server, CLI, and HTTP API with symbol navigation, impact analysis, and architecture mapping ☆`112`
- [st3v3nmw/sourcerer-mcp](https://github.com/st3v3nmw/sourcerer-mcp) — Semantic code search reducing token waste ☆`121`
- [micl2e2/code-to-tree](https://github.com/micl2e2/code-to-tree) — Source code to AST tree conversion ☆`89`
- [codacy/codacy-mcp-server](https://github.com/codacy/codacy-mcp-server) — Codacy's MCP Server implementation ☆`58`
- [lineai-intelligence/lineai-mcp-server](https://github.com/lineai-intelligence/lineai-mcp-server) — Codelogic software dependency analysis ☆`37`
- [Disentinel/grafema](https://github.com/Disentinel/grafema) — Semantic code graphs for call chains, data flow, and search ☆`35`
- [kandrwmrtn/cplusplus_mcp](https://github.com/kandrwmrtn/cplusplus_mcp) — MCP server for C++ codebase analysis using libclang ☆`34`
- [azer/react-analyzer-mcp](https://github.com/azer/react-analyzer-mcp) — React code analysis and docs generation ☆`58`
- [Luqueee/kivgraph](https://github.com/Luqueee/kivgraph) — A local MCP server for cross-repository semantic code intelligence in TypeScript and Go, backed by a persistent LadybugDB graph. ☆`23`
- [vezlo/src-to-kb](https://github.com/vezlo/src-to-kb) — Convert source code to LLM ready knowledge base ☆`40`
- [isiahw1/mcp-server-bing-webmaster](https://github.com/isiahw1/mcp-server-bing-webmaster) — Bing Webmaster Tools for SEO and analytics ☆`31`
- [cqfn/aibolit-mcp-server](https://github.com/cqfn/aibolit-mcp-server) — Aibolit Java static analyzer for AI agents ☆`27`
- [j4c0bs/mcp-server-sql-analyzer](https://github.com/j4c0bs/mcp-server-sql-analyzer) — MCP server for SQL static analysis. ☆`32`
- [danielbowne/claude-context](https://github.com/danielbowne/claude-context) — Claude Context with LanceDB local vector database - AI-powered semantic code search for MCP ☆`17`
### Debuggers

- [jasonjmcghee/claude-debugs-for-you](https://github.com/jasonjmcghee/claude-debugs-for-you) — Interactive debugging via MCP and VS Code ☆`514`
- [Continuum-AI-Corp/OrcaReplay](https://github.com/Continuum-AI-Corp/OrcaReplay) — Record, replay and fork coding-agent runs ☆`315`
- [cameroncooke/reloaderoo](https://github.com/cameroncooke/reloaderoo) — Powerful MCP debugging proxy and CLI inspection tool. ☆`127`
- [stass/lldb-mcp](https://github.com/stass/lldb-mcp) — LLDB MCP server ☆`114`
- [pansila/mcp_server_gdb](https://github.com/pansila/mcp_server_gdb) — MCP Server to expose the GDB debugging capabilities ☆`68`
- [Jubstaaa/hono-telescope](https://github.com/Jubstaaa/hono-telescope) — Laravel Telescope-style debugging for Hono - plus an MCP server so your AI agent can read the app's live requests, exceptions and queries ☆`27`
- [knewstimek/agent-tool](https://github.com/knewstimek/agent-tool) — MCP tool server for AI coding agents -- encoding-aware file tools, binary analysis, DAP debugger, SSH/SFTP, process memory, and more ☆`24`
- [imatza-rh/mcp-zuul](https://github.com/imatza-rh/mcp-zuul) — MCP server for Zuul CI - debug build failures, search logs, manage pipelines, and monitor jobs from Claude, Cursor, or any MCP client ☆`21`
### Design & UI

- [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) — Figma layout info for AI coding agents ☆`16,150`
- [grab/cursor-talk-to-figma-mcp](https://github.com/grab/cursor-talk-to-figma-mcp) — Cursor and Figma communication ☆`7,076`
- [21st-dev/magic-mcp](https://github.com/21st-dev/magic-mcp) — Frontend development with AI like Magic ☆`6,366`
- [Jpisnice/shadcn-ui-mcp-server](https://github.com/Jpisnice/shadcn-ui-mcp-server) — MCP server for shadcn/ui component library ☆`3,083`
- [modelcontextprotocol/ext-apps](https://github.com/modelcontextprotocol/ext-apps) — Official repo for spec & SDK of MCP Apps protocol - standard for UIs embedded AI chatbots, served by MCP servers ☆`3,046`
- [awdr74100/figwright](https://github.com/awdr74100/figwright) — Free, two-way Figma MCP server. Turn designs into framework-aware code, and push code back to the canvas. Works with Claude Code, Cursor, Codex, and any MCP client. ☆`1,298`
- [gethopp/figma-mcp-bridge](https://github.com/gethopp/figma-mcp-bridge) — Figma Plugin & MCP server to bypass API limits ☆`876`
- [hustcc/mcp-mermaid](https://github.com/hustcc/mcp-mermaid) — Generate mermaid diagram and chart with AI MCP dynamically. ☆`647`
- [marvkr/better-design](https://github.com/marvkr/better-design) — Open-source design MCP server and shadcn/ui registry. AI design systems for MCP clients, with themes, design tokens, UI principles and WCAG rules. ☆`554`
- [public-ui/kolibri](https://github.com/public-ui/kolibri) — The accessible HTML-Standard ☆`289`
- [mastergo-design/mastergo-magic-mcp](https://github.com/mastergo-design/mastergo-magic-mcp) — Connect MasterGo to AI assistants ☆`286`
- [YuChenSSR/mindmap-mcp-server](https://github.com/YuChenSSR/mindmap-mcp-server) — mindmap, mcp server, artifact ☆`240`
- [MatthewDailey/figma-mcp](https://github.com/MatthewDailey/figma-mcp) — ModelContextProtocol for Figma's REST API ☆`214`
- [TimHolden/figma-mcp-server](https://github.com/TimHolden/figma-mcp-server) — Model Context Protocol server implementation for Figma API ☆`149`
- [freema/mcp-design-system-extractor](https://github.com/freema/mcp-design-system-extractor) — MCP server for extracting design system components ☆`72`
- [thirdstrandstudio/mcp-figma](https://github.com/thirdstrandstudio/mcp-figma) — Figma MCP Server with full API functionality ☆`77`
- [starwind-ui/starwind-ui-mcp](https://github.com/starwind-ui/starwind-ui-mcp) — Starwind UI for Cursor and Windsurf ☆`35`
- [themesberg/flowbite-mcp](https://github.com/themesberg/flowbite-mcp) — Figma to code with Flowbite ☆`42`
- [NonicaTeam/AI-Connector-for-Revit](https://github.com/NonicaTeam/AI-Connector-for-Revit) — Issue tracker for the NonicaTab Revit AI Connector ☆`19`
- [themeselection/flyonui-mcp](https://github.com/themeselection/flyonui-mcp) — MCP server for flyonUI ☆`32`
- [smartzan63/lucid-mcp-server](https://github.com/smartzan63/lucid-mcp-server) — Search, export, and create Lucid charts and diagrams ☆`19`
- [heilgar/shadcn-ui-mcp-server](https://github.com/heilgar/shadcn-ui-mcp-server) — MCP server for shadcn/ui component library ☆`27`
- [kapilduraphe/webflow-mcp-server](https://github.com/kapilduraphe/webflow-mcp-server) — Webflow MCP server ☆`21`
### Diagrams

- [DayuanJiang/next-ai-draw-io](https://github.com/DayuanJiang/next-ai-draw-io) — Draw and edit draw.io diagrams by chatting with an AI. Web app, desktop app, and an MCP server for Claude Code, Cursor, Codex and VS Code. ☆`36,682`
- [jinzcdev/markmap-mcp-server](https://github.com/jinzcdev/markmap-mcp-server) — Markdown to interactive mind maps ☆`290`
- [veelenga/claude-mermaid](https://github.com/veelenga/claude-mermaid) — MCP Server to previewing mermaid diagrams with live reload ☆`221`
- [apeyroux/mcp-xmind](https://github.com/apeyroux/mcp-xmind) — Analyze and query XMind mind maps ☆`95`
- [paulhkang94/markview](https://github.com/paulhkang94/markview) — Native macOS markdown preview + MCP server for Claude Code. Swift/SwiftUI, GFM, Mermaid, syntax highlighting. No Electron. ☆`38`
- [Narasimhaponnada/mermaid-mcp](https://github.com/Narasimhaponnada/mermaid-mcp) — MCP server for Mermaid diagram generation ☆`53`
### Documentation

- [upstash/context7](https://github.com/upstash/context7) — Up-to-date code docs for LLMs ☆`64,156`
- [microsoft/mcp-for-beginners](https://github.com/microsoft/mcp-for-beginners) — This open-source curriculum introduces the fundamentals of Model Context Protocol (MCP) through real-world, cross-language examples in .NET, Java, TypeScript, JavaScript, Rust ☆`17,602`
- [modelcontextprotocol/modelcontextprotocol](https://github.com/modelcontextprotocol/modelcontextprotocol) — Specification and documentation for the Model Context Protocol ☆`9,613`
- [lingodotdev/lingo.dev](https://github.com/lingodotdev/lingo.dev) — MCP server for Lingo localization platform ☆`5,402`
- [liaokongVFX/MCP-Chinese-Getting-Started-Guide](https://github.com/liaokongVFX/MCP-Chinese-Getting-Started-Guide) — Model Context Protocol(MCP) 编程极速入门 ☆`3,580`
- [MicrosoftDocs/mcp](https://github.com/MicrosoftDocs/mcp) — Microsoft Learn MCP for LLMs ☆`1,971`
- [arabold/docs-mcp-server](https://github.com/arabold/docs-mcp-server) — Grounded Docs MCP Server: Open-Source Alternative to Context7, Nia, and Ref.Tools ☆`1,856`
- [kimsungwhee/apple-docs-mcp](https://github.com/kimsungwhee/apple-docs-mcp) — Apple Developer Documentation search ☆`1,382`
- [modelcontextprotocol/quickstart-resources](https://github.com/modelcontextprotocol/quickstart-resources) — A repository of servers and clients from the Model Context Protocol tutorials ☆`1,231`
- [andrea9293/mcp-documentation-server](https://github.com/andrea9293/mcp-documentation-server) — Document management with Gemini ☆`344`
- [context-hub/generator](https://github.com/context-hub/generator) — CTX: a tool that solves the context management gap when working with LLMs like ChatGPT or Claude. It helps developers organize and automatically collect information from their ☆`341`
- [szeider/consult7](https://github.com/szeider/consult7) — MCP server to consult a language model with large context size ☆`295`
- [Govcraft/rust-docs-mcp-server](https://github.com/Govcraft/rust-docs-mcp-server) — Rust documentation lookup ☆`300`
- [Kapeli/dash-mcp-server](https://github.com/Kapeli/dash-mcp-server) — MCP server for Dash, the macOS API documentation browser ☆`190`
- [khromov/svelte-llm-mcp](https://github.com/khromov/svelte-llm-mcp) — Svelte developer documentation as an MCP and in llms.txt format ☆`159`
- [spences10/mcp-svelte-docs](https://github.com/spences10/mcp-svelte-docs) — MCP server that lets you search and access Svelte documentation with built-in caching ☆`123`
- [mrjoshuak/godoc-mcp](https://github.com/mrjoshuak/godoc-mcp) — Structured Go docs to avoid dumping source into context ☆`126`
- [KallistoX/mcp-unifi-applications](https://github.com/KallistoX/mcp-unifi-applications) — UniFi MCP server that makes the official UniFi API documentation (Network, Protect, Site Manager, InnerSpace) queryable by AI agents - endpoint search, schema drill-down, code ☆`40`
- [tosin2013/mcp-adr-analysis-server](https://github.com/tosin2013/mcp-adr-analysis-server) — AI-powered ADR and architecture analysis ☆`35`
- [mishafyi/Apple-Docs-2.0-MCP](https://github.com/mishafyi/Apple-Docs-2.0-MCP) — Apple developer documentation, HIG and WWDC sessions with code, plus an offline index of 336,629 pages ☆`26`
- [0xKoda/mcp-rust-docs](https://github.com/0xKoda/mcp-rust-docs) — An MCP to retrieve rust crate documentation for LLM's ☆`47`
- [yWorks/mcp-typescribe](https://github.com/yWorks/mcp-typescribe) — TypeScript library support for LLMs ☆`46`
- [V0v1kkk/DotNetMetadataMcpServer](https://github.com/V0v1kkk/DotNetMetadataMcpServer) — .NET type metadata for AI coding agents ☆`32`
- [yikakia/godoc-mcp-server](https://github.com/yikakia/godoc-mcp-server) — Go package docs from pkg.go.dev ☆`38`
- [oborchers/mcp-server-docy](https://github.com/oborchers/mcp-server-docy) — Documentation access capabilities ☆`18`
- [Quantum3-Labs/ARBuilder](https://github.com/Quantum3-Labs/ARBuilder) — AI-powered code generator for Arbitrum Stylus, SDK bridging, dApps & Orbit chains - 19 MCP tools with RAG ☆`24`
- [inkeep/mcp-server-python](https://github.com/inkeep/mcp-server-python) — Inkeep MCP Server ☆`25`
- [idachev/mcp-javadc](https://github.com/idachev/mcp-javadc) — MCP server for decompiling Java .class files to source ☆`20`
- [Excoriate/mcp-terragrunt-docs](https://github.com/Excoriate/mcp-terragrunt-docs) — Terragrunt documentation context ☆`20`
- [jonathanfischer97/juliadoc-mcp](https://github.com/jonathanfischer97/juliadoc-mcp) — MCP server for efficiently retrieving Julia docstrings and source code ☆`18`
- [augmentedivan/fabric-mcp-server](https://github.com/augmentedivan/fabric-mcp-server) — Fabric patterns with AI agents ☆`18`
### IDE & Editors

- [PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp) — The fast, Pythonic way to build MCP servers and clients. ☆`28,294`
- [getsentry/MobileBuildMCP](https://github.com/getsentry/MobileBuildMCP) — MCP server for Xcode build operations ☆`6,536`
- [supercorp-ai/supergateway](https://github.com/supercorp-ai/supergateway) — Run MCP stdio servers over HTTP streamable, SSE and SSE over stdio. AI gateway. ☆`2,948`
- [samanhappy/mcphub](https://github.com/samanhappy/mcphub) — Self-hosted MCP gateway and control plane for connecting, controlling, and operating MCP servers. ☆`2,631`
- [isaacphi/mcp-language-server](https://github.com/isaacphi/mcp-language-server) — MCP server implementing Language Server Protocol ☆`1,613`
- [JetBrains/mcp-jetbrains](https://github.com/JetBrains/mcp-jetbrains) — MCP server for JetBrains IDE integration ☆`962`
- [maquina-app/rails-mcp-server](https://github.com/maquina-app/rails-mcp-server) — A Ruby gem implementation of a Model Context Protocol (MCP) server for Rails projects. This server allows LLMs (Large Language Models) to interact with Rails projects through the ☆`574`
- [hanlulong/stata-mcp](https://github.com/hanlulong/stata-mcp) — Stata MCP Extension for VS Code, Cursor, and Antigravity IDE ☆`520`
- [ravitemer/mcp-hub](https://github.com/ravitemer/mcp-hub) — A centralized manager for Model Context Protocol (MCP) servers with dynamic server management and monitoring ☆`526`
- [VikashLoomba/copilot-mcp](https://github.com/VikashLoomba/copilot-mcp) — A VSCode extension that lets you find and install Agent Skills and MCP Apps to use with GitHub Copilot, Claude Code, and Codex CLI. ☆`507`
- [juehang/vscode-mcp-server](https://github.com/juehang/vscode-mcp-server) — VS Code editing features for LLM coding ☆`392`
- [hechtcarmel/jetbrains-index-mcp-plugin](https://github.com/hechtcarmel/jetbrains-index-mcp-plugin) — JetBrains plugin for MCP index integration ☆`375`
- [r-huijts/xcode-mcp-server](https://github.com/r-huijts/xcode-mcp-server) — Xcode project management ☆`387`
- [bigcodegen/mcp-neovim-server](https://github.com/bigcodegen/mcp-neovim-server) — Control Neovim via MCP ☆`324`
- [A11yance/aria-query](https://github.com/A11yance/aria-query) — Programmatic access to the ARIA specification ☆`307`
- [omnirexflora-labs/omnicoreagent](https://github.com/omnirexflora-labs/omnicoreagent) — An agent runtime for Python. Give your agent real work. Keep control: every action checked before it runs, every run survives a crash without silently redoing anything, every ☆`253`
- [biegehydra/BifrostMCP](https://github.com/biegehydra/BifrostMCP) — VS Code semantic tools via MCP ☆`225`
- [tumf/mcp-text-editor](https://github.com/tumf/mcp-text-editor) — Line-oriented text editing for LLM tools ☆`202`
- [adamwattis/mcp-proxy-server](https://github.com/adamwattis/mcp-proxy-server) — An MCP proxy server that aggregates and serves multiple MCP resource servers through a single interface ☆`202`
- [cyanheads/mcp-ts-core](https://github.com/cyanheads/mcp-ts-core) — Agent-native TypeScript framework for building MCP servers. ☆`153`
- [aspect-build/rules_ts](https://github.com/aspect-build/rules_ts) — Bazel rules for the tsc compiler from http://typescriptlang.org ☆`139`
- [leehack/mcp_dart](https://github.com/leehack/mcp_dart) — Dart implementation of MCP SDK ☆`117`
- [hechtcarmel/jetbrains-debugger-mcp-plugin](https://github.com/hechtcarmel/jetbrains-debugger-mcp-plugin) — JetBrains debugger control via MCP ☆`117`
- [lucasmontano/mcp-montano-server](https://github.com/lucasmontano/mcp-montano-server) — Simple MCP Server Implementation ☆`133`
- [Tritlo/lsp-mcp](https://github.com/Tritlo/lsp-mcp) — An MCP server that lets you interact with LSP servers ☆`128`
- [hloiseau/mcp-gopls](https://github.com/hloiseau/mcp-gopls) — Go LSP server via gopls ☆`105`
- [dkmaker/mcp-rest-api](https://github.com/dkmaker/mcp-rest-api) — A TypeScript-based MCP server that enables testing of REST APIs through Cline. This tool allows you to test and interact with any REST API endpoints directly from your ☆`103`
- [bourhaouta/vscode-tailwindshades](https://github.com/bourhaouta/vscode-tailwindshades) — Tailwind CSS palettes (50-950) from any color, for Tailwind v4, v3, v2 and v1. A VS Code extension, a CLI, and an MCP server for AI agents. ☆`78`
- [hanweg/mcp-pdf-tools](https://github.com/hanweg/mcp-pdf-tools) — MCP server for working with PDF files ☆`76`
- [linw1995/nvim-mcp](https://github.com/linw1995/nvim-mcp) — MCP server for Neovim integration ☆`74`
- [vertile-ai/next-mcp-server](https://github.com/vertile-ai/next-mcp-server) — Help LLMs to understand your Next apps better ☆`99`
- [paulburgess1357/nvim-mcp](https://github.com/paulburgess1357/nvim-mcp) — MCP server that connects AI agents to your running Neovim instance via msgpack-RPC - no plugins required. ☆`67`
- [marimo-team/codemirror-mcp](https://github.com/marimo-team/codemirror-mcp) — CodeMirror MCP extension ☆`79`
- [ShenghaiWang/xcodebuild](https://github.com/ShenghaiWang/xcodebuild) — Xcode iOS build with error feedback ☆`85`
- [AllAboutAI-YT/mcp-servers](https://github.com/AllAboutAI-YT/mcp-servers) — All About AI MCP Servers ☆`81`
- [xpn/mythic_mcp](https://github.com/xpn/mythic_mcp) — A simple POC to expose Mythic as a MCP server ☆`81`
- [aashari/boilerplate-mcp-server](https://github.com/aashari/boilerplate-mcp-server) — TypeScript Model Context Protocol (MCP) server boilerplate providing IP lookup tools/resources. Includes CLI support and extensible structure for connecting AI systems (LLMs) to ☆`73`
- [lucianoayres/mcp-server-node](https://github.com/lucianoayres/mcp-server-node) — MCP Server implemented in JavaScript using Node.js that demonstrates how to build an MCP server with a custom prompt and custom tools, including one that loads an environment ☆`76`
- [laurynas-biveinis/elisp-dev-mcp](https://github.com/laurynas-biveinis/elisp-dev-mcp) — Emacs Elisp development tools for LLMs ☆`49`
- [WatermelonBros/reado](https://github.com/WatermelonBros/reado) — Inverted code review: a read-first IDE where you comment on the lines that matter and your coding agent (Claude Code, Codex, Cursor, Copilot) resolves them. Free and open source. ☆`31`
- [anggasct/mcp-insomnia](https://github.com/anggasct/mcp-insomnia) — MCP-Insomnia is an MCP server for creating and managing Insomnia-compatible API collections, requests, and environments. ☆`27`
- [phughesmcr/deno-mcp-template](https://github.com/phughesmcr/deno-mcp-template) — A template repo for writing and publishing local, remote, DXT, and binary MCP servers using Deno. ☆`33`
- [borisdan/mcp-audit-extension](https://github.com/borisdan/mcp-audit-extension) — Audit and log all GitHub Copilot MCP tool calls in VSCode with ease. ☆`27`
- [riza-io/mcp-go](https://github.com/riza-io/mcp-go) — Build Model Context Protocol (MCP) servers in Go ☆`36`
- [tanevanwifferen/mcp-inception](https://github.com/tanevanwifferen/mcp-inception) — Call another MCP client from your MCP client. Offload context windows, delegate tasks, split between models ☆`28`
- [baronfel/mcp-binlog-tool](https://github.com/baronfel/mcp-binlog-tool) — A Model Context Protocol server binary that exposes information inside an MSBuild Binary Log to LLMs to aid build analysis. ☆`22`
- [Jacck/mcp-ortools](https://github.com/Jacck/mcp-ortools) — Model Context Protocol (MCP) server implementation using Google OR-Tools for constraint solving ☆`22`
- [AB498/code-context-provider-mcp](https://github.com/AB498/code-context-provider-mcp) — Code context and analysis for AI ☆`20`
- [kaichen/mcp-local-router](https://github.com/kaichen/mcp-local-router) — An MCP (Model Context Protocol) local router that serves as an aggregation proxy for MCP servers. ☆`18`
### MCP SDKs

- [PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp) — Python framework for building MCP servers and clients ☆`28,294`
- [modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk) — The official Python SDK for Model Context Protocol servers and clients ☆`24,758`
- [modelcontextprotocol/typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk) — The official TypeScript SDK for Model Context Protocol servers and clients ☆`13,706`
- [mark3labs/mcp-go](https://github.com/mark3labs/mcp-go) — Go implementation of MCP ☆`9,217`
- [modelcontextprotocol/go-sdk](https://github.com/modelcontextprotocol/go-sdk) — The official Go SDK for Model Context Protocol servers and clients. Maintained in collaboration with Google. ☆`5,308`
- [modelcontextprotocol/csharp-sdk](https://github.com/modelcontextprotocol/csharp-sdk) — The official C# SDK for Model Context Protocol servers and clients. Maintained in collaboration with Microsoft. ☆`4,614`
- [modelcontextprotocol/rust-sdk](https://github.com/modelcontextprotocol/rust-sdk) — The official Rust SDK for the Model Context Protocol ☆`4,088`
- [modelcontextprotocol/java-sdk](https://github.com/modelcontextprotocol/java-sdk) — The official Java SDK for Model Context Protocol servers and clients. Maintained in collaboration with Spring AI ☆`3,762`
- [modelcontextprotocol/php-sdk](https://github.com/modelcontextprotocol/php-sdk) — The official PHP SDK for Model Context Protocol servers and clients. Maintained in collaboration with The PHP Foundation. ☆`1,654`
- [modelcontextprotocol/swift-sdk](https://github.com/modelcontextprotocol/swift-sdk) — The official Swift SDK for Model Context Protocol servers and clients. Maintained in collaboration with Apple ☆`1,563`
- [modelcontextprotocol/kotlin-sdk](https://github.com/modelcontextprotocol/kotlin-sdk) — The official Kotlin SDK for Model Context Protocol servers and clients. Maintained in collaboration with JetBrains ☆`1,485`
- [metoro-io/mcp-golang](https://github.com/metoro-io/mcp-golang) — Write Model Context Protocol servers in few lines of go code. Docs at https://mcpgolang.com . Created by https://metoro.io ☆`1,229`
- [modelcontextprotocol/ruby-sdk](https://github.com/modelcontextprotocol/ruby-sdk) — The official Ruby SDK for the Model Context Protocol servers and clients. ☆`943`
- [QuantGeekDev/mcp-framework](https://github.com/QuantGeekDev/mcp-framework) — TypeScript framework with auto-discovery ☆`930`
- [bhauman/clojure-mcp](https://github.com/bhauman/clojure-mcp) — Clojure MCP ☆`784`
- [baidubce/app-builder](https://github.com/baidubce/app-builder) — appbuilder-sdk, 千帆AppBuilder-SDK帮助开发者灵活、快速的搭建AI原生应用 ☆`587`
- [php-mcp/laravel](https://github.com/php-mcp/laravel) — Laravel SDK for building MCP servers ☆`476`
- [ghost-in-the-droid/android-agent](https://github.com/ghost-in-the-droid/android-agent) — Open-source framework to drive a real phone with AI agents: Android over ADB, iPhone over WebDriverAgent, 62 MCP tools, Python skills, a Vue dashboard, and swappable local or ☆`413`
- [opgginc/laravel-mcp-server](https://github.com/opgginc/laravel-mcp-server) — Laravel package for MCP servers ☆`330`
- [zcaceres/easy-mcp](https://github.com/zcaceres/easy-mcp) — Absurdly easy Model Context Protocol Servers in Typescript ☆`197`
- [agentfront/frontmcp](https://github.com/agentfront/frontmcp) — The TypeScript framework for MCP servers Build MCP tools that share services, validate inputs and apply the access rules you configure. Bring authentication, testing, agents and ☆`148`
- [dev-mirzabicer/ticktick-sdk](https://github.com/dev-mirzabicer/ticktick-sdk) — A comprehensive async Python library for TickTick with MCP support. ☆`147`
- [agentcathq/agentcat-typescript-sdk](https://github.com/agentcathq/agentcat-typescript-sdk) — AgentCat is an analytics platform for MCP server owners . ☆`127`
- [Epistates/turbomcp](https://github.com/Epistates/turbomcp) — High-performance MCP framework ☆`99`
- [bulutarkan/mac-mcp](https://github.com/bulutarkan/mac-mcp) — Let your AI apps use your Mac: a local server and menu bar app that lets Claude, ChatGPT, Codex and other MCP apps work in your Mac's apps, files, terminal and browser, with ☆`96`
- [agentcathq/agentcat-python-sdk](https://github.com/agentcathq/agentcat-python-sdk) — AgentCat is an analytics platform for MCP server owners . ☆`53`
- [edwin-finance/edwin](https://github.com/edwin-finance/edwin) — Empowering AI agents to dominate DeFAI ☆`66`
- [justjoehere/mcp_gradio_client](https://github.com/justjoehere/mcp_gradio_client) — This is a proof of concept repo on how to create a gradio UI using the Model Context Protocol Client Python SDK. ☆`68`
- [tachyonmcp/tachyon](https://github.com/tachyonmcp/tachyon) — Java/Kotlin MCP runtime with HTTP, Netty, and sessions ☆`38`
- [reflagcom/javascript](https://github.com/reflagcom/javascript) — JS/TS SDKs for Reflag ☆`25`
- [oatpp/oatpp-mcp](https://github.com/oatpp/oatpp-mcp) — C++ MCP implementation for Oat++ framework ☆`50`
- [IvanMurzak/MCP-Plugin-dotnet](https://github.com/IvanMurzak/MCP-Plugin-dotnet) — .NET MCP bridge: expose app methods/data as MCP tools, prompts, and resources via an in-app plugin + lightweight server (SignalR; stdio/http). ☆`21`
- [LastSearch-HQ/lastsearch](https://github.com/LastSearch-HQ/lastsearch) — Reliable research infrastructure for AI agents. Evidence-backed web search with citations, confidence scores, and Clarity anti-hallucination. MCP server, REST API, Python SDK. ☆`20`
- [Alation/alation-ai-agent-sdk](https://github.com/Alation/alation-ai-agent-sdk) — Python library for integrating the Alation API into agentic workflows ☆`18`
- [micl2e2/mcpc](https://github.com/micl2e2/mcpc) — Cross-platform C SDK for Model Context Protocol (MCP), in modern C23. ☆`34`
- [Super-I-Tech/mcp_plexus](https://github.com/Super-I-Tech/mcp_plexus) — Multi-tenant MCP framework built on FastMCP ☆`30`
- [vrknetha/aisdk-mcp-bridge](https://github.com/vrknetha/aisdk-mcp-bridge) — Bridge package enabling seamless integration between Model Context Protocol (MCP) servers and AI SDK tools. Supports multiple server types, real-time communication, and TypeScript. ☆`23`
- [stephencme/create-mcp-ts](https://github.com/stephencme/create-mcp-ts) — TypeScript MCP server template ☆`21`
- [MushroomFleet/DeepLucid3D-MCP](https://github.com/MushroomFleet/DeepLucid3D-MCP) — MCP server for unified cognitive processing - deep reasoning framework for Cline, Claude & AI code assistants ☆`16`
- [mcpagents-ai/mcpagentai](https://github.com/mcpagents-ai/mcpagentai) — Python SDK designed to simplify interactions with MCP (Model Context Protocol) servers. It provides an easy-to-use interface for connecting to MCP servers, reading resources, and ☆`21`
- [waldzellai/mcp-agent-ts](https://github.com/waldzellai/mcp-agent-ts) — TypeScript port of the original MCP Agent framework by lastmile-ai ☆`18`
### Mobile Development

- [mobile-next/mobile-mcp](https://github.com/mobile-next/mobile-mcp) — Mobile automation for iOS, Android, emulators ☆`10,277`
- [callstack/agent-device](https://github.com/callstack/agent-device) — Open source device layer for AI coding agents: a CLI, MCP server, and typed Node.js API to control mobile, web, TV, and desktop apps on devices and simulators, locally or in the ☆`5,265`
- [joshuayoes/ios-simulator-mcp](https://github.com/joshuayoes/ios-simulator-mcp) — MCP server for interacting with the iOS simulator ☆`2,206`
- [minhalvp/android-mcp-server](https://github.com/minhalvp/android-mcp-server) — Android device control via adb ☆`811`
- [hyperb1iss/droidmind](https://github.com/hyperb1iss/droidmind) — Control your Android devices with AI using Model Context Protocol ☆`448`
- [Arenukvern/mcp_flutter](https://github.com/Arenukvern/mcp_flutter) — MCP Toolkit for Flutter AI Agent Driven Development (MCP/CLI + custom client side tools) - via closed feedback loop (visual & semantic snapshot) and high client side ☆`395`
- [InditexTech/mcp-server-simulator-ios-idb](https://github.com/InditexTech/mcp-server-simulator-ios-idb) — MCP server for iOS simulator via IDB ☆`342`
- [mhmzdev/figma-flutter-mcp](https://github.com/mhmzdev/figma-flutter-mcp) — Figma design tokens for Flutter code agents ☆`241`
- [zelentsov-dev/asc-mcp](https://github.com/zelentsov-dev/asc-mcp) — MCP server for App Store Connect API - 502 tools for apps, builds, TestFlight, subscriptions, Xcode Cloud, and more from Claude, Cursor, VS Code, or any MCP client ☆`83`
- [ateymoori/oh-my-android](https://github.com/ateymoori/oh-my-android) — macOS app with MCP server to drive the Android Emulator and phones ☆`77`
- [ethbak/icon-composer-mcp](https://github.com/ethbak/icon-composer-mcp) — Apple Icon Composer CLI & MCP server: create and manipulate .icon bundles and images with Liquid Glass rendering ☆`66`
- [zillow/auto-mobile](https://github.com/zillow/auto-mobile) — Mobile automation tools with MCP ☆`80`
- [martingeidobler/android-mcp-server](https://github.com/martingeidobler/android-mcp-server) — MCP server for controlling Android emulators via ADB - screenshots, UI interaction, logcat, and bug documentation for Claude Code ☆`69`
- [mikusnuz/app-publish-mcp](https://github.com/mikusnuz/app-publish-mcp) — Unified MCP server for App Store Connect & Google Play Console - 91 tools for listings, screenshots, releases, reviews & submissions ☆`40`
- [Nagarjuna2997/ios-agent-skill](https://github.com/Nagarjuna2997/ios-agent-skill) — Swift source, Apple guides and MCP tools for AI coding agents. Review iOS code, scaffold apps, and build/run/preview with Xcode Simulator. ☆`40`
- [JoshuaRileyDev/simulator-mcp-server](https://github.com/JoshuaRileyDev/simulator-mcp-server) — MCP server for iOS Simulator control ☆`53`
- [Tommertom/awesome-ionic-mcp](https://github.com/Tommertom/awesome-ionic-mcp) — Ionic and Capacitor mobile app development ☆`45`
- [kao273183/mk-qa-master](https://github.com/kao273183/mk-qa-master) — AI 測試大師 - MCP server driving pytest / Jest / Cypress / Go / Maestro. Analyze, generate, run, advise. Web + Mobile (iOS/Android/BlueStacks). ☆`37`
- [FidelisMM/shipstores](https://github.com/FidelisMM/shipstores) — Ship iOS and Android apps from your AI agent. MCP server for App Store Connect, Google Play Console and Expo EAS. ☆`19`
- [thecombatwombat/replicant-mcp](https://github.com/thecombatwombat/replicant-mcp) — Android MCP server - production-grade, token-optimized, accessibility-first ☆`18`
- [iksnerd/adb-mcp](https://github.com/iksnerd/adb-mcp) — MCP server for Android - drive emulators and real devices over adb from Claude Code, Cursor, or VS Code. 73 tools: screenshots, UI hierarchy, tap/swipe/type, logcat, device ☆`17`
- [XixianLiang/HarmonyOS-mcp-server](https://github.com/XixianLiang/HarmonyOS-mcp-server) — MCP server for manipulating HarmonyOS next devices. ☆`35`
- [Neverlow512/agent-droid-bridge](https://github.com/Neverlow512/agent-droid-bridge) — Agent Droid Bridge gives AI agents programmatic control over Android devices and emulators via ADB, exposed as an MCP server. ☆`23`
- [ambar/simctl-mcp](https://github.com/ambar/simctl-mcp) — MCP server for iOS Simulator control ☆`20`
### OpenAPI

- [open-webui/mcpo](https://github.com/open-webui/mcpo) — A simple, secure MCP-to-OpenAPI proxy server ☆`4,417`
- [koreainvestment/open-trading-api](https://github.com/koreainvestment/open-trading-api) — Korea Investment & Securities Open API Github ☆`1,655`
- [cuga-project/cuga-agent](https://github.com/cuga-project/cuga-agent) — CUGA is an open-source generalist agent harness for the enterprise, supporting complex task execution on web and APIs, OpenAPI/MCP integrations, composable architecture, ☆`1,070`
- [janwilmake/openapi-mcp-server](https://github.com/janwilmake/openapi-mcp-server) — Complex OpenAPI exploration with plain language ☆`905`
- [mattt/emcee](https://github.com/mattt/emcee) — MCP generator for OpenAPIs ☆`334`
- [ivo-toby/mcp-openapi-server](https://github.com/ivo-toby/mcp-openapi-server) — MCP Server (Model Context Protocol) for turning OpenAPI specifications into a MCP Resource ☆`302`
- [higress-group/openapi-to-mcpserver](https://github.com/higress-group/openapi-to-mcpserver) — A tool&lib that can automatically convert OpenAPI documents into Higress remote MCP server configurations. ☆`292`
- [ckanthony/openapi-mcp](https://github.com/ckanthony/openapi-mcp) — Dockerized OpenAPI to MCP conversion ☆`199`
- [twilio-labs/mcp](https://github.com/twilio-labs/mcp) — OpenAPI to MCP tools and Twilio APIs ☆`114`
- [zaizaizhao/mcp-swagger-server](https://github.com/zaizaizhao/mcp-swagger-server) — OpenAPI/Swagger to MCP conversion ☆`77`
- [kadykov/mcp-openapi-schema-explorer](https://github.com/kadykov/mcp-openapi-schema-explorer) — Token-efficient OpenAPI/Swagger exploration ☆`76`
- [ReAPI-com/mcp-openapi](https://github.com/ReAPI-com/mcp-openapi) — OpenAPI specification MCP server. ☆`90`
- [baryhuang/mcp-server-any-openapi](https://github.com/baryhuang/mcp-server-any-openapi) — Call APIs via semantic search ☆`82`
- [gunpal5/QuickMCP](https://github.com/gunpal5/QuickMCP) — Effortlessly Build Model Context Protocol Servers with OpenAPI or Swagger or Google Discovery Specifications ☆`70`
- [hannesj/mcp-openapi-schema](https://github.com/hannesj/mcp-openapi-schema) — OpenAPI Schema Model Context Protocol Server ☆`50`
- [delimit-ai/delimit-mcp-server](https://github.com/delimit-ai/delimit-mcp-server) — Building your AI organization: shared records and handoffs, plus a merge gate for AI-written code with signed, replayable attestation. Works with Claude Code, Codex, Cursor, and ☆`23`
- [MonadWorks/agentify](https://github.com/MonadWorks/agentify) — Agent Interface Compiler - One command. Every agent speaks your product. Transform OpenAPI specs into MCP Servers, Skills, CLAUDE.md, AGENTS.md, and more. ☆`42`
- [SonAIengine/graph-tool-call](https://github.com/SonAIengine/graph-tool-call) — Graph-based tool retrieval for LLM agents - 248 tools → 82% accuracy, 79% fewer tokens. Zero dependencies. OpenAPI / MCP / LangChain. ☆`18`
- [criteo/openapi-to-mcp](https://github.com/criteo/openapi-to-mcp) — An MCP server for your API ☆`35`
### Package Managers

- [rafsilva85/credit-optimizer-v5](https://github.com/rafsilva85/credit-optimizer-v5) — Save 47% on Manus AI credits automatically. Zero downsides. Pays for itself in ~27 prompts. Free MCP Server (PyPI) + $12 Manus Skill bundle with Fast Navigation (115x speed boost). ☆`53`
- [arvindand/maven-tools-mcp](https://github.com/arvindand/maven-tools-mcp) — Maven Central dependency intelligence for JVM build tools ☆`35`
- [Artmann/package-registry-mcp](https://github.com/Artmann/package-registry-mcp) — NPM, Cargo, PyPi, NuGet package search ☆`39`
- [VikrantSingh01/adaptive-cards-mcp](https://github.com/VikrantSingh01/adaptive-cards-mcp) — AI-powered Adaptive Card MCP server - 9 tools for generating, validating, optimizing cards for Teams, Outlook, Copilot, ChatGPT. npm: adaptive-cards-mcp ☆`33`
- [Bigsy/maven-mcp-server](https://github.com/Bigsy/maven-mcp-server) — Maven build and dependency tools ☆`34`
- [jeannier/homebrew-mcp](https://github.com/jeannier/homebrew-mcp) — Homebrew package management ☆`30`
- [btwiuse/npm-search-mcp-server](https://github.com/btwiuse/npm-search-mcp-server) — MCP server for searching npm packages ☆`16`
- [subelsky/bundler_mcp](https://github.com/subelsky/bundler_mcp) — MCP server for Ruby Bundler integration ☆`21`
### Robotics & Automation

- [trycua/cua](https://github.com/trycua/cua) — MCP server for CUA platform ☆`31,692`
- [robotmcp/ros-mcp-server](https://github.com/robotmcp/ros-mcp-server) — ROS robot control with Claude and GPT ☆`1,512`
- [omni-mcp/isaac-sim-mcp](https://github.com/omni-mcp/isaac-sim-mcp) — Isaac Simulation MCP Extension and Server ☆`199`
- [wise-vision/ros2_mcp](https://github.com/wise-vision/ros2_mcp) — ROS 2 robotics AI bridge ☆`98`
- [abrinsmead/mindpilot-mcp](https://github.com/abrinsmead/mindpilot-mcp) — Visualize code and architect new systems ☆`90`
- [lpigeon/unitree-go2-mcp-server](https://github.com/lpigeon/unitree-go2-mcp-server) — MCP server for Unitree Go2 robot control ☆`88`
- [Yutarop/ros-mcp](https://github.com/Yutarop/ros-mcp) — MCP server for ROS to control robots via topics, services, and actions. ☆`36`
### Task Management

- [cjo4m06/mcp-shrimp-task-manager](https://github.com/cjo4m06/mcp-shrimp-task-manager) — Task manager with chain-of-thought and reflection ☆`2,149`
- [amxv/mcp-manager](https://github.com/amxv/mcp-manager) — Web UI to manage MCP servers in Claude ☆`296`
### Testing & QA

- [modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector) — Deterministic testing tools for MCP servers ☆`11,229`
- [MCPJam/inspector](https://github.com/MCPJam/inspector) — Testing and evaluation platform to chat, inspect, and debug MCP servers, MCP apps, and ChatGPT apps. ☆`2,298`
- [QAInsights/jmeter-mcp-server](https://github.com/QAInsights/jmeter-mcp-server) — JMeter AI workflow integration ☆`74`
- [debugg-ai/debugg-ai-mcp](https://github.com/debugg-ai/debugg-ai-mcp) — AI-managed end-to-end testing ☆`68`
- [SmartBear/smartbear-mcp](https://github.com/SmartBear/smartbear-mcp) — SmartBear's official MCP Server ☆`44`
- [hungthai1401/bruno-mcp](https://github.com/hungthai1401/bruno-mcp) — MCP Server for running Bruno Collections ☆`44`
- [mrexodia/user-feedback-mcp](https://github.com/mrexodia/user-feedback-mcp) — Human-in-the-loop workflow for Cursor ☆`54`
- [reportportal/reportportal-mcp-server](https://github.com/reportportal/reportportal-mcp-server) — MCP server for ReportPortal ☆`24`
- [currents-dev/currents-mcp](https://github.com/currents-dev/currents-mcp) — Currents MCP Server ☆`21`
- [QAInsights/k6-mcp-server](https://github.com/QAInsights/k6-mcp-server) — k6 MCP server ☆`26`
### Utilities

- [anaisbetts/mcp-installer](https://github.com/anaisbetts/mcp-installer) — An MCP server that installs other MCP servers for you ☆`1,535`
- [johnhuang316/code-index-mcp](https://github.com/johnhuang316/code-index-mcp) — A Model Context Protocol (MCP) server that helps large language models index, search, and analyze code repositories with minimal setup ☆`1,007`
- [jina-ai/MCP](https://github.com/jina-ai/MCP) — Official Jina AI Remote MCP Server ☆`902`
- [tidewave-ai/tidewave_phoenix](https://github.com/tidewave-ai/tidewave_phoenix) — MCP server with runtime-level tools for Phoenix development ☆`858`
- [zinja-coder/jadx-mcp-server](https://github.com/zinja-coder/jadx-mcp-server) — MCP server for JADX-AI Plugin ☆`832`
- [vercel/next-devtools-mcp](https://github.com/vercel/next-devtools-mcp) — Next.js Development for Coding Agent ☆`835`
- [slowmist/MCP-Security-Checklist](https://github.com/slowmist/MCP-Security-Checklist) — A comprehensive security checklist for MCP-based AI tools. Built by SlowMist to safeguard LLM plugin ecosystems. ☆`831`
- [Kentucky-ai/opentakeoff](https://github.com/Kentucky-ai/opentakeoff) — Open-source (AGPL-3.0) PDF takeoff for construction & flooring - the first engine an AI agent drives natively over MCP, not bolted on. Rooms measured on the wall faces, symbol ☆`752`
- [tedeh/jayson](https://github.com/tedeh/jayson) — Jayson is a simple but featureful JSON-RPC 2.0/1.0 client and server for node.js ☆`727`
- [daobataotie/CAD-MCP](https://github.com/daobataotie/CAD-MCP) — CAD MCP Server ☆`668`
- [puran-water/autocad-mcp](https://github.com/puran-water/autocad-mcp) — MCP server for AutoCAD LT v3.1: freehand AutoLISP execution, 8 consolidated tools, File IPC + ezdxf backends, focus-free dispatch, undo/redo, P&ID symbols, and robust IPC with ☆`627`
- [cloudflare/workers-mcp](https://github.com/cloudflare/workers-mcp) — Talk to a Cloudflare Worker from Claude Desktop! ☆`647`
- [Wasdubya/x64dbgMCP](https://github.com/Wasdubya/x64dbgMCP) — Model Context Protocol for x64dbg & x32dbg ☆`609`
- [spences10/mcp-sequentialthinking-tools](https://github.com/spences10/mcp-sequentialthinking-tools) — An adaptation of the MCP Sequential Thinking Server to guide tool usage. This server provides recommendations for which MCP tools would be most effective at each stage. ☆`587`
- [google/mcp-security](https://github.com/google/mcp-security) — Chronicle & Mandiant integration for threat detection and incident response. ☆`537`
- [makafeli/n8n-workflow-builder](https://github.com/makafeli/n8n-workflow-builder) — AI assistant integration for n8n workflow automation through Model Context Protocol (MCP). Connect Claude Desktop, ChatGPT, and other AI assistants to n8n for natural language ☆`550`
- [Miasyster/QuantGPT](https://github.com/Miasyster/QuantGPT) — Agent-driven alpha factory - LLM autonomously designs, backtests, and submits factors to WorldQuant BRAIN ☆`506`
- [tidewave-ai/tidewave_rails](https://github.com/tidewave-ai/tidewave_rails) — MCP server with runtime-level tools for Rails development ☆`475`
- [delorenj/mcp-server-trello](https://github.com/delorenj/mcp-server-trello) — A Model Context Protocol (MCP) server that provides tools for interacting with Trello boards. ☆`447`
- [cyanheads/atlas-mcp-server](https://github.com/cyanheads/atlas-mcp-server) — A Model Context Protocol (MCP) server for ATLAS, a Neo4j-powered task management system for LLM Agents - implementing a three-tier architecture (Projects, Tasks, Knowledge) to ☆`478`
- [dnakov/frida-mcp](https://github.com/dnakov/frida-mcp) — MCP stdio server for frida ☆`463`
- [dcSpark/shinkai-local-ai-agents](https://github.com/dcSpark/shinkai-local-ai-agents) — Shinkai is a two click install App that allows you to create Local AI agents in 5 minutes or less using a simple UI. Supports: MCPs, Remote and Local AI, Crypto and Payments. ☆`435`
- [TencentEdgeOne/edgeone-makers-mcp](https://github.com/TencentEdgeOne/edgeone-makers-mcp) — An MCP service designed for deploying HTML content to EdgeOne Makers and obtaining an accessible public URL. ☆`440`
- [adhikasp/mcp-reddit](https://github.com/adhikasp/mcp-reddit) — A Model Context Protocol (MCP) server that provides tools for fetching and analyzing Reddit content. ☆`437`
- [cisco-open/network-sketcher](https://github.com/cisco-open/network-sketcher) — Network Sketcher is an AI-ready network design tool with Local MCP, Online, and Offline editions for creating network designs and exporting PowerPoint diagrams and Excel-based ☆`417`
- [EnesCinr/twitter-mcp](https://github.com/EnesCinr/twitter-mcp) — A Model Context Protocol server allows to interact with Twitter, enabling posting tweets and searching Twitter. ☆`407`
- [ai-dashboad/flutter-skill](https://github.com/ai-dashboad/flutter-skill) — AI-powered E2E testing for 10 platforms. 253 MCP tools. Zero config. Works with Claude, Cursor, Windsurf, Copilot. Test Flutter, React Native, iOS, Android, Web, Electron, Tauri, ☆`400`
- [joshrutkowski/applescript-mcp](https://github.com/joshrutkowski/applescript-mcp) — A macOS AppleScript MCP server ☆`395`
- [mcp2everything/mcp2mqtt](https://github.com/mcp2everything/mcp2mqtt) — 本项目通过将 MCP 协议转换为 MQTT 协议，我们能够利用强大的大型语言模型（LLMs），就能轻松操控您的智能家居、机器人或其他硬件设备。 ☆`371`
- [microsoft/mcsmcp](https://github.com/microsoft/mcsmcp) — Lab for creating an MCP Server and using it in Microsoft Copilot Studio. ☆`340`
- [kleneway/awesome-cursor-mpc-server](https://github.com/kleneway/awesome-cursor-mpc-server) — Example of an MCP server with custom tools that can be called directly from cursor ☆`338`
- [proxy-intell/facebook-ads-library-mcp](https://github.com/proxy-intell/facebook-ads-library-mcp) — MCP Server for Facebook ADs Library - Get instant answers from FB's ad library ☆`321`
- [jkf87/hwp-mcp](https://github.com/jkf87/hwp-mcp) — mcp for handling hwp ☆`271`
- [zh19980811/Easy-MCP-AutoCad](https://github.com/zh19980811/Easy-MCP-AutoCad) — 这个项目是一个基于Model Context Protocol (MCP)的AutoCAD集成服务器，它允许通过自然语言与AutoCAD进行交互。通过这个服务器，用户可以使用Claude等大型语言模型来创建、修改和分析AutoCAD图纸，同时还可以存储和查询CAD元素的相关数据。目前制作参考学习，仅实现端到端之间的通信，具体工具函数尚未晚上 ☆`270`
- [DMontgomery40/mcp-3D-printer-server](https://github.com/DMontgomery40/mcp-3D-printer-server) — Connects MCP to major 3D printer APIs (Orca, FULU's Orca/Bambu, OctoPrint, Klipper, Duet, Repetier, Prusa, Creality). Control prints, monitor status, and perform advanced STL ☆`258`
- [MCP-Defender/MCP-Defender](https://github.com/MCP-Defender/MCP-Defender) — Desktop app that automatically scans and blocks malicious MCP traffic in AI apps like Cursor, Claude, VS Code and Windsurf. ☆`255`
- [salacoste/mcp-n8n-workflow-builder](https://github.com/salacoste/mcp-n8n-workflow-builder) — AI-powered n8n workflow automation through natural language. MCP server enabling Claude AI & Cursor IDE to create, manage, and monitor workflows via Model Context Protocol. ☆`237`
- [aliargun/mcp-server-gemini](https://github.com/aliargun/mcp-server-gemini) — MCP server implementation for Google's Gemini API ☆`259`
- [tolkonepiu/best-of-mcp-servers](https://github.com/tolkonepiu/best-of-mcp-servers) — A ranked list of MCP servers. Updated weekly. ☆`161`
- [peng-shawn/mermaid-mcp-server](https://github.com/peng-shawn/mermaid-mcp-server) — A Model Context Protocol (MCP) server that converts Mermaid diagrams to PNG images ☆`234`
- [aipotheosis-labs/aci-mcp](https://github.com/aipotheosis-labs/aci-mcp) — MCP server(s) for Aipolabs ACI.dev ☆`254`
- [Azure-Samples/mcp-agent-langchainjs](https://github.com/Azure-Samples/mcp-agent-langchainjs) — Serverless AI agent using LangChain.js and Model Context Protocol (MCP) integration to order burgers from a burger restaurant ☆`204`
- [code-rabi/interactive-brokers-mcp](https://github.com/code-rabi/interactive-brokers-mcp) — Interactive Brokers MCP Server ☆`228`
- [ConstantineB6/comfy-pilot](https://github.com/ConstantineB6/comfy-pilot) — MCP server + embedded terminal that lets Claude Code see and edit your ComfyUI workflows ☆`232`
- [jhacksman/OpenSCAD-MCP-Server](https://github.com/jhacksman/OpenSCAD-MCP-Server) — Devin's attempt at creating an OpenSCAD MCP Server that takes a user prompt and generates a preview image and 3d file. ☆`214`
- [quarkiverse/quarkus-mcp-server](https://github.com/quarkiverse/quarkus-mcp-server) — This extension enables developers to implement the MCP server features easily. ☆`202`
- [microsoft/mcp-dotnet-samples](https://github.com/microsoft/mcp-dotnet-samples) — A comprehensive set of samples of creating and using MCP servers and clients with .NET ☆`201`
- [bonninr/freecad_mcp](https://github.com/bonninr/freecad_mcp) — FreecadMCP connects Freecad to Claude AI and other MCP-ready tools like Cursor through the Model Context Protocol (MCP), allowing Claude to directly interact with and control ☆`227`
- [minipuft/claude-prompts-mcp](https://github.com/minipuft/claude-prompts-mcp) — MCP server for reusable prompt templates, multi-step workflow chains, and quality gates. Compose agentic workflows with an operator syntax; export as native skills to Claude ☆`192`
- [invariantlabs-ai/mcp-injection-experiments](https://github.com/invariantlabs-ai/mcp-injection-experiments) — Code snippets to reproduce MCP tool poisoning attacks. ☆`210`
- [mattt/Companion](https://github.com/mattt/Companion) — Your neighborhood friendly MCP utility for macOS, iOS, and visionOS ☆`189`
- [rectalogic/langchain-mcp](https://github.com/rectalogic/langchain-mcp) — Model Context Protocol tool support for LangChain ☆`205`
- [eniayomi/gcp-mcp](https://github.com/eniayomi/gcp-mcp) — A Model Context Protocol (MCP) server that enables AI assistants like Claude to interact with your Google Cloud Platform environment. This allows for natural language querying ☆`200`
- [blackwell-systems/agent-lsp](https://github.com/blackwell-systems/agent-lsp) — MCP server that orchestrates language servers into agent-native workflows. 65 tools, 30 CI-verified languages. ☆`170`
- [openfate-ai/openfate-mcp](https://github.com/openfate-ai/openfate-mcp) — OpenFate Bazi MCP server with deterministic Four Pillars calculation, True Solar Time, branch interactions, and reverse Bazi lookup. ☆`162`
- [sammcj/mcp-devtools](https://github.com/sammcj/mcp-devtools) — A modular MCP server that provides commonly used developer tools for AI coding agents ☆`162`
- [githejie/mcp-server-calculator](https://github.com/githejie/mcp-server-calculator) — A Model Context Protocol server for calculating. ☆`161`
- [BV-Venky/excalidraw-architect-mcp](https://github.com/BV-Venky/excalidraw-architect-mcp) — Turn your architecture into a living, queryable knowledge graph - and render it as beautiful auto-laid-out Excalidraw diagrams. An MCP server for Cursor, Claude Code & Windsurf. ☆`163`
- [Azure-Samples/remote-mcp-functions-dotnet](https://github.com/Azure-Samples/remote-mcp-functions-dotnet) — This is a quickstart template to easily build and deploy a custom remote MCP server to the cloud using Azure functions. You can clone/restore/run on your local machine with ☆`134`
- [pzfreo/build123d-mcp](https://github.com/pzfreo/build123d-mcp) — MCP server for build123d to improve AI cognition when creating 3D CAD models ☆`140`
- [Flux159/mcp-chat](https://github.com/Flux159/mcp-chat) — Open Source Generic MCP Client for testing & evaluating mcp servers and agents ☆`139`
- [stefanoamorelli/fred-mcp-server](https://github.com/stefanoamorelli/fred-mcp-server) — Open-source FRED MCP Server (Federal Reserve Economic Data) ☆`130`
- [Nyrok/flompt](https://github.com/Nyrok/flompt) — flow + prompt = flompt - Visual AI Prompt Builder. Decompose, edit as flowchart, recompile into optimized machine-readable prompts ☆`155`
- [readwiseio/readwise-mcp](https://github.com/readwiseio/readwise-mcp) — Readwise MCP ☆`152`
- [golioth/tinymcp](https://github.com/golioth/tinymcp) — Let LLMs control embedded devices via the Model Context Protocol. ☆`157`
- [aviveldan/datagov-mcp](https://github.com/aviveldan/datagov-mcp) — MCP server for Israel Government Data ☆`146`
- [dhakalnirajan/blender-open-mcp](https://github.com/dhakalnirajan/blender-open-mcp) — MCP for Blender Using Open Weights Models ☆`122`
- [JordyZomer/codeql-mcp](https://github.com/JordyZomer/codeql-mcp) — This project runs a Model Context Protocol (MCP) server that wraps the CodeQL query server. It enables tools like or AI agents to interact with ☆`148`
- [baryhuang/mcp-hubspot](https://github.com/baryhuang/mcp-hubspot) — A Model Context Protocol (MCP) server that enables AI assistants to interact with HubSpot CRM data, providing built-in vector storage and caching mechanisms help overcome HubSpot ☆`129`
- [rcontesti/IB_MCP](https://github.com/rcontesti/IB_MCP) — This project provides an Interactive Brokers (IB) API interface using the Model Context Protocol (MCP). ☆`141`
- [makalin/SecureMCP](https://github.com/makalin/SecureMCP) — SecureMCP is a security auditing tool designed to detect vulnerabilities and misconfigurations in applications using the [Model Context Protocol ☆`140`
- [jangtrinh/design-os-3d-blender](https://github.com/jangtrinh/design-os-3d-blender) — AI agent operating system for Blender 5.2: bpy knowledge base, AGENTOK execution contract, 3D-print production gate, worked keyboard and desktop-robot builds. ☆`109`
- [borgius/jobspy-mcp-server](https://github.com/borgius/jobspy-mcp-server) — MCP server to search for jobs across multiple job listing platforms ☆`123`
- [mertkayacs/reevesagents](https://github.com/mertkayacs/reevesagents) — Run Claude Code, Codex, Kimi, OpenCode, Hermes and one of the 26 other coding agents using MCP , CLI or TUI , WebUI. ☆`109`
- [mclenhard/mcp-evals](https://github.com/mclenhard/mcp-evals) — A Node.js package and GitHub Action for evaluating MCP (Model Context Protocol) tool implementations using LLM-based scoring. This helps ensure your MCP server's tools are ☆`134`
- [yylo-dev/roundtable](https://github.com/yylo-dev/roundtable) — Zero-configuration MCP server that unifies multiple AI coding assistants (Codex, Claude Code, Cursor, Gemini) through intelligent auto-discovery and standardized interface ☆`128`
- [LeulAria/Aria-Icons](https://github.com/LeulAria/Aria-Icons) — MCP server for 1M+ SVG icons ☆`104`
- [jlsookiki/secondhand-mcp](https://github.com/jlsookiki/secondhand-mcp) — MCP server for searching secondhand marketplaces - Facebook Marketplace, eBay, and Depop. Works with Claude Desktop, Claude Code, and other MCP clients. ☆`99`
- [portel-dev/photon](https://github.com/portel-dev/photon) — Define intent once. Photon turns a single TypeScript file into CLI tools, MCP servers, and web interfaces. ☆`100`
- [TonyWang-hub/mcp-cn-commerce](https://github.com/TonyWang-hub/mcp-cn-commerce) — 中国电商 MCP 连接器：8 个平台、155 个已注册工具。开源标准版，含能力矩阵与实际工程验收记录；真实商家联调状态逐项公开。Chinese commerce MCP connectors with documented capabilities and validation status. ☆`96`
- [mikeyny/ai-image-gen-mcp](https://github.com/mikeyny/ai-image-gen-mcp) — An MCP-compliant server that generates images from text prompts using Replicate's model, demonstrating extensibility and protocol adherence in the MCP server ecosystem. ☆`121`
- [theronic/modex](https://github.com/theronic/modex) — Modex is a Clojure MCP Library to augment your AI models with Tools, Resources & Prompts using Clojure (Model Context Protocol). Implements MCP Server & Client. ☆`121`
- [garagon/aguara](https://github.com/garagon/aguara) — The open source security engine for AI agent and supply-chain trust. ☆`94`
- [f/mcp-startup-boilerplate](https://github.com/f/mcp-startup-boilerplate) — A Rails template for creating Paid MCP servers compatible with Claude Integrations. It uses Rails 8.0.2, Devise, Doorkeeper, FastMCP and Stripe. Has a built-in UI. ☆`112`
- [MaxEllis/orcaslicer-mcp](https://github.com/MaxEllis/orcaslicer-mcp) — OrcaSlicer MCP - drive OrcaSlicer from Claude or any MCP client: load models, tune settings, slice, analyze ☆`90`
- [pfldy2850/py-mcp-naver](https://github.com/pfldy2850/py-mcp-naver) — python MCP NAVER ☆`115`
- [embedded-society/altium-designer-mcp](https://github.com/embedded-society/altium-designer-mcp) — MCP server for AI-assisted management of Altium Designer component libraries ☆`89`
- [TocharianOU/mcp-server-kibana](https://github.com/TocharianOU/mcp-server-kibana) — MCP server for Kibana, Access search and manage Kibana in MCP Client. ☆`86`
- [JoxoAI/joxo](https://github.com/JoxoAI/joxo) — Team workspace for AI coding agents: your Claude Code, Codex, Cursor, Gemini CLI and OpenCode agents share one project, task board and handoffs. Desktop, iPhone and MCP server. ☆`89`
- [LLMQuant/data-mcp](https://github.com/LLMQuant/data-mcp) — The knowledge harness for AI‑native finance - MCP server for LLMQuant Data. ☆`87`
- [NapthaAI/http-oauth-mcp-server](https://github.com/NapthaAI/http-oauth-mcp-server) — Remote MCP server (SEE + Streamable HTTP) implementing the MCP spec's authorization extension. Use directly from your agents, or from Cursor / Claude with mcp-remote ☆`110`
- [TermiX-official/bsc-mcp](https://github.com/TermiX-official/bsc-mcp) — A plug-and-play MCP tool server to send BNB, transfer BEP-20 tokens, deploy tokens, and interact with smart contracts on the Binance Smart Chain (BSC) - built for Claude... ☆`105`
- [oculairmedia/Letta-MCP-server](https://github.com/oculairmedia/Letta-MCP-server) — MCP server to manage letta server and comunicate with agents ☆`80`
- [TermiX-official/binance-mcp](https://github.com/TermiX-official/binance-mcp) — binance-mcp ☆`97`
- [escapeboy/agent-fleet-o](https://github.com/escapeboy/agent-fleet-o) — Open-source AI agent orchestration platform - self-hosted mission control for autonomous multi-agent systems. Visual DAG workflows, 670+ MCP tools, human-in-the-loop approvals. ☆`77`
- [ronantakizawa/a11ymcp](https://github.com/ronantakizawa/a11ymcp) — MCP Server for Web Accessibility Testing (10k+ Downloads, #20 on ProductHunt) ☆`94`
- [smadi0x86/MDB-MCP](https://github.com/smadi0x86/MDB-MCP) — Multi Debugger MCP server that enables LLMs to interact with GDB and LLDB for binary debugging and analysis. ☆`74`
- [MarcelRoozekrans/roslyn-codelens-mcp](https://github.com/MarcelRoozekrans/roslyn-codelens-mcp) — Roslyn-based MCP server giving AI agents deep semantic understanding of .NET/C# codebases - 67 tools for navigation, call graphs, diagnostics & code fixes, safe refactoring, ☆`70`
- [stefanoamorelli/nasdaq-data-link-mcp](https://github.com/stefanoamorelli/nasdaq-data-link-mcp) — A Nasdaq Data Link MCP (Model Context Protocol) Server ☆`68`
- [shitianfang/jev-use](https://github.com/shitianfang/jev-use) — Claude Code / Codex / pi plugin that hands agent steps needing no text output to Jev (TypeSafe's judgment model) - measured p50 ~230 ms and ~$0.02 per 1,000 judgments, with typed ☆`67`
- [ruvnet/federated-mcp](https://github.com/ruvnet/federated-mcp) — This implementation follows the official MCP specification, including proper message framing, transport layer implementation, and complete protocol lifecycle management. It ☆`65`
- [contentful/contentful-mcp-server](https://github.com/contentful/contentful-mcp-server) — MCP (Model Context Protocol) server for the Contentful Management API ☆`62`
- [lethain/library-mcp](https://github.com/lethain/library-mcp) — MCP server for operating on Markdown knowledge bases ☆`91`
- [jsdelivr/globalping-mcp-server](https://github.com/jsdelivr/globalping-mcp-server) — Remote network commands for LLMs ☆`65`
- [Mearman/mcp-wayback-machine](https://github.com/Mearman/mcp-wayback-machine) — MCP server and CLI tool for interacting with the Internet Archive's Wayback Machine ☆`64`
- [ilyautov/marketplaces-mcp-ru](https://github.com/ilyautov/marketplaces-mcp-ru) — MCP-сервер для кабинетов Wildberries, Ozon, Яндекс Маркета и Авито: продажи, заказы, остатки, цены, финансы, отзывы через API напрямую, без браузера. 1022 метода schema-driven, ☆`60`
- [PSPDFKit/nutrient-document-engine-mcp-server](https://github.com/PSPDFKit/nutrient-document-engine-mcp-server) — A Model Context Protocol (MCP) server implementation exposes document processing capabilities through natural language, supporting both direct human interaction and AI agent tool ☆`62`
- [DeDeveloper23/codebase-mcp](https://github.com/DeDeveloper23/codebase-mcp) — Model Context Protocol implementation for retrieving codebases using RepoMix ☆`85`
- [kranz-org/kranz](https://github.com/kranz-org/kranz) — Keyboard-first local service orchestrator with a focused terminal UI ☆`62`
- [Pantani/tdmcp](https://github.com/Pantani/tdmcp) — TouchDesigner MCP server, describe a visual to Claude, Cursor or Codex and it builds a real, playable node network (audio-reactive, generative, particle, 3D, feedback) with live ☆`58`
- [linux-china/mcp-rs-template](https://github.com/linux-china/mcp-rs-template) — Model Context Protocol (MCP) CLI server template for Rust ☆`82`
- [brentmid/evernote-mcp-server](https://github.com/brentmid/evernote-mcp-server) — Evernote MCP server - allows LLMs that support MCP (like Claude Desktop) to query your notes in Evernote ☆`56`
- [xianyu-sheng/Xenon](https://github.com/xianyu-sheng/Xenon) — Verifiable AI coding agent harness / 可验证的 AI 编码代理：evidence hash-chain · hollow-answer gate · manual verification checklist · 6 engines + MCP · multi-model · Windows/CJK · listed ☆`56`
- [MorDavid/ExternalAttacker-MCP](https://github.com/MorDavid/ExternalAttacker-MCP) — A modular external attack surface mapping tool integrating tools for automated reconnaissance and bug bounty workflows. ☆`78`
- [gabrielekarra/mcp-anything](https://github.com/gabrielekarra/mcp-anything) — One command to turn any codebase into an MCP server ☆`55`
- [LadislavSopko/mcp-ai-server-visual-studio](https://github.com/LadislavSopko/mcp-ai-server-visual-studio) — MCP AI Server - Roslyn-powered MCP server for Visual Studio. 20 tools for AI assistants. ☆`55`
- [raw-labs/mxcp](https://github.com/raw-labs/mxcp) — Model eXecution + Context Protocol: Enterprise-Grade Data-to-AI Infrastructure ☆`68`
- [priyankark/a11y-mcp](https://github.com/priyankark/a11y-mcp) — An MCP (Model Context Protocol) server for performing accessibility audits on webpages using axe-core. Use the results in an agentic loop with your favorite AI assistants ☆`53`
- [HaseebKhalid1507/SynapsCLI](https://github.com/HaseebKhalid1507/SynapsCLI) — A terminal-native AI agent runtime built in Rust. Interactive chat, parallel agent orchestration, and autonomous supervision. ☆`53`
- [ThingsPanel/thingspanel-mcp](https://github.com/ThingsPanel/thingspanel-mcp) — This MCP server integrates ThingsPanel IoT platform with AI models like Claude, GPT, and others that support the Model Context Protocol. ☆`48`
- [MarcusJellinghaus/mcp-workspace](https://github.com/MarcusJellinghaus/mcp-workspace) — MCP Workspace Server: A secure Model Context Protocol server providing file, git, and GitHub tools for AI assistants within a sandboxed project directory. ☆`49`
- [maton-ai/agent-toolkit](https://github.com/maton-ai/agent-toolkit) — MCP server to connect and manage SaaS tools like HubSpot and Salesforce. ☆`50`
- [attalla1/photopea-mcp-server](https://github.com/attalla1/photopea-mcp-server) — MCP server for AI-driven image editing with Photopea ☆`49`
- [RyanCardin15/AzureDevOps-MCP](https://github.com/RyanCardin15/AzureDevOps-MCP) — Model Context Protocol (MCP) server offering a convenient API for interacting with Azure DevOps services, enabling management of work items, repositories, boards, and sprints. ☆`60`
- [adenot/mcp-google-search](https://github.com/adenot/mcp-google-search) — MCP server that provides Google Search results via the Google Custom Search API. ☆`71`
- [CSCSoftware/AiDex](https://github.com/CSCSoftware/AiDex) — MCP Server for persistent code indexing. Gives AI assistants (Claude, Gemini, Copilot, Cursor) instant access to your codebase. 50x less context than grep. ☆`48`
- [rootlyhq/rootly-mcp-server](https://github.com/rootlyhq/rootly-mcp-server) — Rootly MCP server ☆`45`
- [NON906/omniparser-autogui-mcp](https://github.com/NON906/omniparser-autogui-mcp) — Automatic operation of on-screen GUI. ☆`72`
- [pzalutski-pixel/javalens-mcp](https://github.com/pzalutski-pixel/javalens-mcp) — MCP server providing semantic Java code analysis for AI agents. Built on Eclipse JDT with tools for navigation, refactoring, search, and metrics. ☆`46`
- [CheckPointSW/mcp-servers](https://github.com/CheckPointSW/mcp-servers) — AI-accessible Check Point firewall and threat management. ☆`44`
- [dejuknow/md-redline](https://github.com/dejuknow/md-redline) — Inline review comments for markdown specs. Built-in MCP server hands feedback directly to your AI agent. ☆`46`
- [datadog-labs/mcp-server](https://github.com/datadog-labs/mcp-server) — Official Datadog MCP Server ☆`47`
- [heltonteixeira/openrouterai](https://github.com/heltonteixeira/openrouterai) — MCP server for OpenRouter.ai integration ☆`64`
- [anzy-renlab-ai/pronounce](https://github.com/anzy-renlab-ai/pronounce) — Hear how developers actually pronounce kubectl, nginx, GIF & 1,900+ tech terms. Sourced dictionary + CLI + VS Code + GitHub Action + MCP + Agent Skill. ☆`47`
- [Cifero74/mcp-apple-music](https://github.com/Cifero74/mcp-apple-music) — Full Apple Music integration for Claude via MCP - search catalog, manage library & playlists ☆`45`
- [cnitlrt/headless-ida-mcp-server](https://github.com/cnitlrt/headless-ida-mcp-server) — headless-ida-mcp-server ☆`45`
- [MikeRecognex/mcp-codebase-index](https://github.com/MikeRecognex/mcp-codebase-index) — 17 MCP query tools for codebase navigation - functions, classes, imports, dependency graphs, change impact. Zero dependencies. 87% token reduction. ☆`63`
- [withastro/docs-mcp](https://github.com/withastro/docs-mcp) — Astro Docs MCP Server ☆`68`
- [hetaoBackend/mcp-github-trending](https://github.com/hetaoBackend/mcp-github-trending) — MCP server for getting github trending repos & developers ☆`62`
- [Text2Go/ai-humanizer-mcp-server](https://github.com/Text2Go/ai-humanizer-mcp-server) — A powerful Model Context Protocol (MCP) server that helps refine AI-generated content to sound more natural and human-like. Built with advanced AI detection and text enhancement ☆`64`
- [flamexnreal/davinci-resolve-ai-bridge-mcp](https://github.com/flamexnreal/davinci-resolve-ai-bridge-mcp) — DaVinci Resolve (Free Version and Studio) MCP server for Claude, Cursor, Codex, and Antigravity. Full timeline editing, cuts, camera zoom, and color grading. ☆`42`
- [Mtehabsim/ScreenPilot](https://github.com/Mtehabsim/ScreenPilot) — AI device control like a human ☆`55`
- [pylegifrance/mcp-server-legifrance](https://github.com/pylegifrance/mcp-server-legifrance) — Legifrance MCP Server ☆`65`
- [Decodo/mcp-server](https://github.com/Decodo/mcp-server) — The Decodo MCP server which enables MCP clients to interface with services. ☆`39`
- [pzalutski-pixel/sharplens-mcp](https://github.com/pzalutski-pixel/sharplens-mcp) — Roslyn-powered MCP server for AI-driven C# semantic analysis, refactoring, and code generation ☆`40`
- [daobataotie/mssql-mcp](https://github.com/daobataotie/mssql-mcp) — mssql mcp server ☆`39`
- [decriptor/DilettoLabs.AvaloniaUI.MCP](https://github.com/decriptor/DilettoLabs.AvaloniaUI.MCP) — MCP server for AvaloniaUI ☆`39`
- [demcp/demcp-defillama-mcp](https://github.com/demcp/demcp-defillama-mcp) — DeFiLlama MCP is a powerful and flexible tool that provides a microservice-based API wrapper around the DeFi Llama ecosystem. ☆`63`
- [verygoodplugins/mcp-toggl](https://github.com/verygoodplugins/mcp-toggl) — MCP server for Toggl Track integration with intelligent caching and reporting tools ☆`36`
- [circuit-synth/kicad-sch-api](https://github.com/circuit-synth/kicad-sch-api) — API for manipulating sexpr in KiCAD schematic editor ☆`57`
- [alxspiker/mcp-server-ftp](https://github.com/alxspiker/mcp-server-ftp) — Model Context Protocol server for FTP access ☆`36`
- [xiaotonng/lc2mcp](https://github.com/xiaotonng/lc2mcp) — Convert LangChain tools to FastMCP tools ☆`56`
- [bharathvaj-ganesan/whois-mcp](https://github.com/bharathvaj-ganesan/whois-mcp) — MCP Server for whois lookups. ☆`60`
- [kirich1409/maven-mcp](https://github.com/kirich1409/maven-mcp) — Maven dependency intelligence MCP server and Claude Code / Grok Build plugin ☆`37`
- [swgee/BurpMCP](https://github.com/swgee/BurpMCP) — Burp Suite Extension with MCP Server to enhance manual application security testing ☆`57`
- [telmon95/VulneraMCP](https://github.com/telmon95/VulneraMCP) — An AI-Powered Bug Bounty Hunting Platform - Comprehensive MCP server for security testing, vulnerability research, and bug bounty hunting ☆`50`
- [zazencodes/random-number-mcp](https://github.com/zazencodes/random-number-mcp) — MCP server for random number generation ☆`50`
- [dynatrace-oss/dynatrace-managed-mcp](https://github.com/dynatrace-oss/dynatrace-managed-mcp) — An MCP server for self-hosted Dynatrace Managed platform ☆`33`
- [metavert-io/lightcms](https://github.com/metavert-io/lightcms) — Self-hosted CMS that works human or headless: full admin UI plus REST and MCP APIs, built-in semantic search and site chat, and content forking, versioning, diff/merge review, ☆`34`
- [daipendency/daipendency-mcp](https://github.com/daipendency/daipendency-mcp) — Model Context Protocol server for Daipendency ☆`58`
- [muppet-dev/kit](https://github.com/muppet-dev/kit) — Debugging and Testing tool for MCP servers ☆`58`
- [feiyun0112/spec-coding-mcp](https://github.com/feiyun0112/spec-coding-mcp) — Transform feature ideas into production-ready code through systematic Spec-Driven Development 通过系统化的规格驱动开发，将功能想法转化为可投入生产的代码 ☆`50`
- [Azure-Samples/mcp-auth-servers](https://github.com/Azure-Samples/mcp-auth-servers) — Reference MCP servers that demo how authentication works with the current Model Context Protocol spec. ☆`50`
- [XenoXilus/outlook-mcp](https://github.com/XenoXilus/outlook-mcp) — MCP server for Microsoft Office 365 Outlook - email, calendar & SharePoint integration for Claude, ChatGPT, and AI assistants via Microsoft Graph API ☆`30`
- [zhaoyouj/mcp-slicer](https://github.com/zhaoyouj/mcp-slicer) — A Model Context Protocol server for 3D Slicer integration ☆`45`
- [zxzinn/opencti-mcp](https://github.com/zxzinn/opencti-mcp) — MCP server for querying OpenCTI threat intelligence, indicators, reports, malware, and threat actors. ☆`42`
- [librejustice/librejustice](https://github.com/librejustice/librejustice) — Moteur de recherche libre sur le droit français et européen - jurisprudence et textes (loi à n'importe quelle date), en web, API et MCP. Free search engine for French case law ☆`30`
- [newtype-01/prompthouse-mcp](https://github.com/newtype-01/prompthouse-mcp) — Personal prompt library manager ☆`53`
- [henilcalagiya/mcp-apple-notes](https://github.com/henilcalagiya/mcp-apple-notes) — An local mcp server for interacting with Apple Notes via LLM. ☆`53`
- [portone-io/mcp-server](https://github.com/portone-io/mcp-server) — PortOne MCP Server for Developers ☆`29`
- [taiste/harvest-mcp-server](https://github.com/taiste/harvest-mcp-server) — MCP Server for Harvest ☆`38`
- [HarshJ23/deepseek-claude-MCP-server](https://github.com/HarshJ23/deepseek-claude-MCP-server) — a MCP server which integrates reasoning capabilities of DeepSeek R1 model into claude desktop app. ☆`50`
- [StefH/McpDotNet.Extensions.SemanticKernel](https://github.com/StefH/McpDotNet.Extensions.SemanticKernel) — Microsoft SemanticKernel integration for the Model Context Protocol (MCP). Enables seamless use of MCP tools as AI functions. ☆`40`
- [Whq02/MercuryCLI](https://github.com/Whq02/MercuryCLI) — Mercury CLI: multiple AI coding sessions in one terminal. Mix and match provider and locally hosted models, spawn cross-company agents & workflows, and use built-in debugging, ☆`27`
- [mcp-agents-ai/mcp-agents-hub](https://github.com/mcp-agents-ai/mcp-agents-hub) — The open-source ecosystem for building, discovering, and deploying Model Context Protocol servers and clients. ☆`44`
- [mcp2everything/mcp2serial](https://github.com/mcp2everything/mcp2serial) — A open-source library enabling AI models to control hardware devices via serial communication using the MCP protocol. Initial support for Raspberry Pi Pico. ☆`50`
- [FelixFoster/mcp-enhance-prompt](https://github.com/FelixFoster/mcp-enhance-prompt) — AI-powered prompt enhancement and generation ☆`24`
- [wretcher207/reaper-daemon](https://github.com/wretcher207/reaper-daemon) — Free, open source REAPER MCP server that lets an AI agent (Claude or any MCP client) drive REAPER: read every plugin and parameter, set FX values, write automation, and measure a ☆`25`
- [shieldyguy/stm32-mcp](https://github.com/shieldyguy/stm32-mcp) — build, flash, debug stm32 projects ☆`25`
- [fireostendere/mcp_diptrace](https://github.com/fireostendere/mcp_diptrace) — MCP server and live XML bridge for DipTrace ☆`25`
- [fastn-ai/fastn-mcp](https://github.com/fastn-ai/fastn-mcp) — Governed, audited access to customer systems of record ☆`23`
- [Ming-jiayou/mcp_demo](https://github.com/Ming-jiayou/mcp_demo) — A simple example of building an MCP client using C#. ☆`47`
- [panbanda/omen](https://github.com/panbanda/omen) — SAST intelligence for AI agents. Complexity, hotspots, blast radius, and tech debt analysis over MCP. ☆`21`
- [abhiphile/fermat-mcp](https://github.com/abhiphile/fermat-mcp) — SymPy, NumPy, and Matplotlib in one math engine ☆`22`
- [maple-kit/maple](https://github.com/maple-kit/maple) — Open-source visual UX review comments on deployed previews, with a CI merge gate and an agent loop ☆`22`
- [keplertech/naja-scope](https://github.com/keplertech/naja-scope) — MCP server for AI agents to explore SystemVerilog, Verilog and VHDL (beta) designs: trace connectivity, walk hierarchy, jump to source - without pasting RTL into context. Built ☆`22`
- [ourongxing/newsnow-mcp-server](https://github.com/ourongxing/newsnow-mcp-server) — Official MCP Server for newnow, 40+ sources available. ☆`34`
- [addozhang/spring-rest-to-mcp](https://github.com/addozhang/spring-rest-to-mcp) — Convert Spring REST API to MCP Server with OpenRewrite ☆`39`
- [nsxdavid/clickup-mcp-server](https://github.com/nsxdavid/clickup-mcp-server) — A Node.js-based MCP server for ClickUp, enabling workspace, task, document, and checklist management directly from conversation interfaces. ☆`43`
- [hjbaard/SolidWorks-MCP](https://github.com/hjbaard/SolidWorks-MCP) — MCP server that lets AI agents build, measure and verify parametric parts and assemblies in a running SolidWorks (Windows, COM). ☆`20`
- [huanglizhuo/OctoCounts](https://github.com/huanglizhuo/OctoCounts) — Count lines of code (SLOC) in any public GitHub repo without cloning: web app, browser extension, CLI, GitHub Action and MCP server, powered by tokei. The SLOC panel GitHub forgot. ☆`20`
- [ZedMoster/revit-mcp](https://github.com/ZedMoster/revit-mcp) — revit-mcp ☆`38`
- [SecretiveShell/MCP-timeserver](https://github.com/SecretiveShell/MCP-timeserver) — Datetime info for agentic systems ☆`42`
- [patchloom/patchloom](https://github.com/patchloom/patchloom) — Structured file edits for AI agents (JSON/YAML/TOML, markdown, AST, dry-run, MCP). Not a generic filesystem MCP. ☆`20`
- [jonemo/openpyxl-mcp-server](https://github.com/jonemo/openpyxl-mcp-server) — A thin wrapper around the OpenPyXl Python library that exposes some of its features as Model Context Protocol (MCP) server. This allows Claude and other MCP clients to fetch data ☆`19`
- [axonixtools/PocketMCP](https://github.com/axonixtools/PocketMCP) — Turn your Android phone into an MCP (Model Context Protocol) server. AI agents and desktop scripts can call your phone for live data and actions over LAN. ☆`19`
- [Azure-Samples/remote-mcp-webapp-dotnet](https://github.com/Azure-Samples/remote-mcp-webapp-dotnet) — This project contains a .NET web app implementation of a Model Context Protocol (MCP) server. The application is designed to be deployed to Azure App Service. ☆`40`
- [jmtanguy/droit-francais-mcp](https://github.com/jmtanguy/droit-francais-mcp) — Serveur MCP pour des recherches directement sur Légifrance et Judilibre. ☆`36`
- [tokenizin-agency/mcp-npx-fetch](https://github.com/tokenizin-agency/mcp-npx-fetch) — A powerful MCP server for fetching and transforming web content into various formats (HTML, JSON, Markdown, Plain Text) with ease. ☆`42`
- [angrysky56/ast-mcp-server](https://github.com/angrysky56/ast-mcp-server) — By transforming source code into a queryable Semantic Graph and a structured AST, this tool bridges the gap between "reading text" and "understanding structure." For an AI ☆`37`
- [Cyreslab-AI/crunchbase-mcp-server](https://github.com/Cyreslab-AI/crunchbase-mcp-server) — MCP server for the Crunchbase API - company, funding, and investor intelligence for AI assistants. ☆`17`
- [stefanoamorelli/companies-house-mcp](https://github.com/stefanoamorelli/companies-house-mcp) — MCP server for UK Companies House API - Search companies, retrieve detailed information, filing history, officers, and charges data through the Model Context Protocol ☆`31`
- [Buga-luga/cursor-mcp](https://github.com/Buga-luga/cursor-mcp) — An AI-powered IDE that integrates Claude agents with MCP capabilities, providing session-based memory, function calling, and agent chaining directly within the coding editor... ☆`39`
- [arikusi/nakkas](https://github.com/arikusi/nakkas) — MCP server that turns AI into an SVG artist ☆`31`
- [bingal/FastDomainCheck-MCP-Server](https://github.com/bingal/FastDomainCheck-MCP-Server) — A Model Context Protocol for checking domain name registration status in bulk. ☆`40`
- [qualixar/slm-mesh](https://github.com/qualixar/slm-mesh) — Peer-to-peer communication for AI coding agents. 8 MCP tools, full CLI, Python client. Part of the Qualixar research initiative by Varun Pratap Bhardwaj. ☆`16`
- [shadowfax92/apple-reminders-mcp](https://github.com/shadowfax92/apple-reminders-mcp) — An MCP server for AI assistants to manage Apple Reminders on macOS, with a TypeScript API to create, complete, and delete reminders. ☆`39`
- [andybrandt/mcp-simple-timeserver](https://github.com/andybrandt/mcp-simple-timeserver) — Current time check for Claude via MCP ☆`33`
- [Braffolk/mcp-summarization-functions](https://github.com/Braffolk/mcp-summarization-functions) — Provides summarised output from various actions that could otherwise eat up tokens and cause crashes for AI agents ☆`37`
- [mytechnotalent/MalwareBazaar_MCP](https://github.com/mytechnotalent/MalwareBazaar_MCP) — An AI-driven MCP server that autonomously interfaces with Malware Bazaar, delivering real-time threat intel and sample metadata for authorized cybersecurity research workflows. ☆`32`
- [54yyyu/code-mcp](https://github.com/54yyyu/code-mcp) — Code-MCP: Connect Claude AI to your development environment through the Model Context Protocol (MCP), enabling terminal commands and file operations through the AI interface. ☆`38`
- [CartographAI/atlas-docs-mcp](https://github.com/CartographAI/atlas-docs-mcp) — Provide LLMs hosted, clean markdown documentation of libraries and frameworks ☆`36`
- [rsdouglas/janee](https://github.com/rsdouglas/janee) — Secrets management for AI agents via MCP • @janeesecure ☆`30`
- [stefanoamorelli/hyprmcp](https://github.com/stefanoamorelli/hyprmcp) — Community MCP server for hyprctl ☆`35`
- [stefanskiasan/azure-devops-mcp-server](https://github.com/stefanskiasan/azure-devops-mcp-server) — MCP Server for Cline to Access Azure devops ☆`33`
- [mlobo2012/Claude_Desktop_API_USE_VIA_MCP](https://github.com/mlobo2012/Claude_Desktop_API_USE_VIA_MCP) — MCP server implementation for using Claude API with Claude Desktop, providing advanced API integration and conversation management. ☆`34`
- [isaacwasserman/mcp-langchain-ts-client](https://github.com/isaacwasserman/mcp-langchain-ts-client) — LangChain.js client for Model Context Protocol. ☆`35`
- [oakenai/mcp-edit-file-lines](https://github.com/oakenai/mcp-edit-file-lines) — MCP Server to make line-based edits to a file. ☆`34`
- [cyanheads/mentor-mcp-server](https://github.com/cyanheads/mentor-mcp-server) — A Model Context Protocol server providing LLM Agents a second opinion via AI-powered Deepseek-Reasoning R1 mentorship capabilities, including code review, design critique, ☆`32`
- [NikiforovAll/mcp-template-dotnet](https://github.com/NikiforovAll/mcp-template-dotnet) — This repository contains a template for creating a Model Context Protocol (MCP) applications in .NET. ☆`25`
- [abhishekbhakat/airflow-mcp-server](https://github.com/abhishekbhakat/airflow-mcp-server) — MCP Server for Apache Airflow ☆`33`
- [superfly/flymcp](https://github.com/superfly/flymcp) — MCP server for Fly.io CLI integration with Claude Desktop ☆`34`
- [ap425q/CutterMCP](https://github.com/ap425q/CutterMCP) — MCP Server for Cutter ☆`34`
- [amgadabdelhafez/dbx-mcp-server](https://github.com/amgadabdelhafez/dbx-mcp-server) — MCP Server for Dropbox ☆`30`
- [CharlieDigital/runjs](https://github.com/CharlieDigital/runjs) — The only MCP server you need: let your LLM generate and safely execute JavaScript -- including fetch API calls, JSONPath ETL, built-in resiliencey, and secrets management ☆`32`
- [nguyenvanduocit/dev-kit](https://github.com/nguyenvanduocit/dev-kit) — [Model Context Protocol] Dev Kit - anything a developer need for him day to day works ☆`33`
- [willibrandon/NetContextServer](https://github.com/willibrandon/NetContextServer) — A .NET implementation of the Model Context Protocol enabling AI assistants to explore and understand .NET codebases. ☆`32`
- [ofek/pycli-mcp](https://github.com/ofek/pycli-mcp) — MCP server for any Python command line application ☆`22`
- [ZeparHyfar/mcp-datetime](https://github.com/ZeparHyfar/mcp-datetime) — A MCP server for datetime formatting and file name generation. ☆`31`
- [tooluse-labs/perfetto-mcp-rs](https://github.com/tooluse-labs/perfetto-mcp-rs) — Perfetto trace analysis via MCP - PerfettoSQL queries plus dedicated Chrome tools for scroll jank, page loads, and main-thread hotspots ☆`22`
- [PCDCK/ozon-mcp](https://github.com/PCDCK/ozon-mcp) — MCP-сервер для Ozon Seller API и Performance API - подключите любого AI-агента к кабинету продавца ☆`25`
- [TheoBrigitte/mcp-time](https://github.com/TheoBrigitte/mcp-time) — Dates and times with natural language and timezones ☆`25`
- [jenstangen1/pptx-xlsx-mcp](https://github.com/jenstangen1/pptx-xlsx-mcp) — Antrophics Model context protocol to edit powerpoint files ☆`30`
- [Nazruden/clickup-mcp-server](https://github.com/Nazruden/clickup-mcp-server) — A Model Context Protocol server implementation for ClickUp integration, enabling AI assistants to interact with ClickUp workspaces. ☆`23`
- [janwilmake/install-this-mcp](https://github.com/janwilmake/install-this-mcp) — Reduce installation-friction for your MCP servers ☆`25`
- [MAG-Cie/mcp-microsoft-todo](https://github.com/MAG-Cie/mcp-microsoft-todo) — MCP server for Microsoft To Do via Microsoft Graph API. Manage task lists, create, update, complete and delete tasks from Claude Code, Claude Desktop, or any MCP-compatible ☆`19`
- [izzzzzi/codewiki-mcp](https://github.com/izzzzzi/codewiki-mcp) — MCP server for codewiki.google - search, fetch docs, and ask questions about any open-source repo ☆`19`
- [ADEOSec/mcp-shodan](https://github.com/ADEOSec/mcp-shodan) — The Shodan MCP Server by ADEO Cybersecurity Services provides cybersecurity professionals with streamlined access to Shodan's powerful reconnaissance capabilities through an ☆`26`
- [bmorphism/anti-bullshit-mcp-server](https://github.com/bmorphism/anti-bullshit-mcp-server) — MCP server for analyzing claims, validating sources, and detecting manipulation using multiple epistemological frameworks ☆`23`
- [stakpak/mcp](https://github.com/stakpak/mcp) — Lightweight MCP server to give you access to the Stakpak API. ☆`18`
- [ameeralns/DeepResearchMCP](https://github.com/ameeralns/DeepResearchMCP) — Deep Research MCP is an intelligent research assistant built on the Model Context Protocol (MCP) that performs comprehensive, multi-step research on any topic. ☆`27`
- [TexasFortress-AI/rs_filesystem](https://github.com/TexasFortress-AI/rs_filesystem) — MCP Filesystem tools written in Rust ☆`22`
- [syedazharmbnr1/ClaudeMCPServer](https://github.com/syedazharmbnr1/ClaudeMCPServer) — MCP Server implementation for Claude ☆`27`
- [openSVM/dexscreener-mcp-server](https://github.com/openSVM/dexscreener-mcp-server) — An MCP server implementation for accessing the DexScreener API, providing real-time access to DEX pair data, token information, and market statistics across multiple blockchains. ☆`24`
- [mcpware/ui-annotator-mcp](https://github.com/mcpware/ui-annotator-mcp) — MCP server that annotates any web page with hover labels - zero extensions, works in any browser ☆`21`
- [7gugu/zip-mcp](https://github.com/7gugu/zip-mcp) — An MCP tool that provides AI with the ability to compress and decompress local files. ☆`16`
- [davidvc/code-knowledge-mcptool](https://github.com/davidvc/code-knowledge-mcptool) — MCP tool that lets Cline inquire about a code base ☆`24`
- [hanweg/mcp-tool-builder](https://github.com/hanweg/mcp-tool-builder) — MCP server that creates its own tools as needed ☆`25`
- [philipp-eisen/modal-mcp-toolbox](https://github.com/philipp-eisen/modal-mcp-toolbox) — A collection of tools for your LLMs that run on Modal ☆`25`
- [austenstone/myinstants-mcp](https://github.com/austenstone/myinstants-mcp) — MCP server that lets your ai agent press sound buttons. it's not that deep. ☆`20`
- [SJTU-Geek/sjtu-mcp-server](https://github.com/SJTU-Geek/sjtu-mcp-server) — 本项目基于MCP协议构建校园服务Agent，通过标准化接口将大模型与校园信息系统（如课表查询、图书馆预约、成绩分析等）深度对接，用户仅需自然语言指令即可完成复杂操作 ☆`20`
- [abhishekjairath/sonic-pi-mcp](https://github.com/abhishekjairath/sonic-pi-mcp) — Model Context Protocol (MCP) server for controlling Sonic Pi through AI assistants ☆`19`
- [lobehub/mcp-hello-world](https://github.com/lobehub/mcp-hello-world) — A simple Hello World MCP server for CI/CD test ☆`22`
- [ajtazer/ZAP-MCP](https://github.com/ajtazer/ZAP-MCP) — VIBE CODING lol ☆`23`
- [mrwadams/otx-mcp](https://github.com/mrwadams/otx-mcp) — Interface to OTX feeds and threat intel. ☆`22`
- [CartographAI/mcp-server-codegraph](https://github.com/CartographAI/mcp-server-codegraph) — MCP server for graph representation of a codebase ☆`22`
- [ykhli/mcp-light-control](https://github.com/ykhli/mcp-light-control) — MCP server to control Philips Hue lights, including sending Morse code through them ☆`22`
- [yy1588133/code-merge-mcp](https://github.com/yy1588133/code-merge-mcp) — Facilitates code file extraction, merging, and analysis for large language models using the Model Context Protocol. ☆`21`
- [amornpan/py-mcp-line](https://github.com/amornpan/py-mcp-line) — python mcp LINE ☆`20`
- [acashmoney/bio-mcp](https://github.com/acashmoney/bio-mcp) — BioMCP: Enabling agent-based biomedical R&D ☆`20`
- [cmpxchg16/mcp-ethical-hacking](https://github.com/cmpxchg16/mcp-ethical-hacking) — MCP Ethical Hacking Security sample for educational ☆`20`
- [asmith26/jupytercad-mcp](https://github.com/asmith26/jupytercad-mcp) — An MCP server for JupyterCAD that allows you to control it using LLMs/natural language. ☆`20`
- [ODAncona/code2prompt-mcp](https://github.com/ODAncona/code2prompt-mcp) — Transforms complex codebases into structured summaries optimized for language models through an MCP server, facilitating better code understanding and analysis workflows.... ☆`19`
- [rohans2/mcp-google-sheets](https://github.com/rohans2/mcp-google-sheets) — MCP server written in TypeScript to access and modify data in your Google Sheets. ☆`18`
- [ricauts/CyberMCP](https://github.com/ricauts/CyberMCP) — CyberMCP is a Model Context Protocol (MCP) server designed for testing backend APIs for security vulnerabilities. It provides a set of specialized tools and resources that can be ☆`16`
- [ggerve/coding-standards-mcp](https://github.com/ggerve/coding-standards-mcp) — MCP Server for Coding Standards - providing standardized coding guidelines and best practices ☆`17`
- [torshepherd/compiler-explorer-mcp](https://github.com/torshepherd/compiler-explorer-mcp) — A Model Context Protocol server that connects LLMs to the Compiler Explorer API, enabling compilation and exploration of code across different compilers and languages. This is... ☆`16`
### Version Control

- [github/github-mcp-server](https://github.com/github/github-mcp-server) — GitHub's official MCP Server ☆`34,205`
- [idosal/git-mcp](https://github.com/idosal/git-mcp) — Free remote MCP for any GitHub project ☆`8,505`
- [repowise-dev/repowise](https://github.com/repowise-dev/repowise) — Codebase intelligence for AI and humans: code health scores, auto-generated docs, git analytics, dead code detection, and architectural decisions via MCP. ☆`8,133`
- [gitkraken/gk-cli](https://github.com/gitkraken/gk-cli) — GitKraken CLI Releases and Documentation ☆`461`
- [Tiberriver256/mcp-server-azure-devops](https://github.com/Tiberriver256/mcp-server-azure-devops) — An MCP server for Azure DevOps ☆`399`
- [adhikasp/mcp-git-ingest](https://github.com/adhikasp/mcp-git-ingest) — GitHub repository content reading ☆`315`
- [cyanheads/git-mcp-server](https://github.com/cyanheads/git-mcp-server) — Clone, commit, diff, branch, merge, rebase, cherry-pick, stash, tag, and manage worktrees in local git repos via MCP. STDIO or Streamable HTTP. ☆`245`
- [puravparab/Gitingest-MCP](https://github.com/puravparab/Gitingest-MCP) — mcp server for gitingest ☆`138`
- [kopfrechner/gitlab-mr-mcp](https://github.com/kopfrechner/gitlab-mr-mcp) — MCP server for GitLab merge requests and issues ☆`94`
- [PhpCodeArcheology/PhpCodeArcheology](https://github.com/PhpCodeArcheology/PhpCodeArcheology) — PHP static analysis for architecture & maintainability - 60+ metrics, complexity analysis, dependency graphs, git churn hotspots, and AI-ready MCP server. Alternative to ☆`92`
- [sverklo/sverklo](https://github.com/sverklo/sverklo) — Repo memory for coding agents. Local-first MCP for Claude Code, Cursor, Windsurf, and Codex CLI: symbol graph, blast radius, diff-aware review, and git-pinned decisions. MIT; no ☆`82`
- [oschina/mcp-gitee](https://github.com/oschina/mcp-gitee) — MCP server for Gitee repositories ☆`66`
- [srclight/srclight](https://github.com/srclight/srclight) — Deep code indexing MCP server for AI agents. 25 tools: hybrid FTS5 + embedding search, call graphs, git blame/hotspots, build system analysis. Multi-repo workspaces, ☆`59`
- [KongFangXun/sofagent](https://github.com/KongFangXun/sofagent) — sofagent is an open-source FDE Harness for AI coding agents - on entry, write your business judgment into files (workflows, ontology, AI nodes); after departure, audit every ☆`55`
- [raohwork/forgejo-mcp](https://github.com/raohwork/forgejo-mcp) — A MCP server that enables you to manage Gitea/Forgejo repositories through AI assistants ☆`70`
- [jmrplens/gitlab-mcp-server](https://github.com/jmrplens/gitlab-mcp-server) — Open source GitLab MCP server for AI assistants: 2-tool dynamic find/execute over 850+ GitLab actions (1,000+ Enterprise), stdio/HTTP/OAuth, safe/read-only modes. ☆`46`
- [Ryan0204/github-repo-mcp](https://github.com/Ryan0204/github-repo-mcp) — GitHub repository reading ☆`33`
- [cq27-dev/rag-rat](https://github.com/cq27-dev/rag-rat) — Local repo-intelligence index + MCP server: semantic search, symbol/graph navigation, impact-surface preflight, git + GitHub papertrail, and a source-anchored memory graph. ☆`25`
- [sgroy10/speclock](https://github.com/sgroy10/speclock) — Action guardrails for AI coding agents - native Claude Code enforcement, MCP integrations, and Git/CI checks. ☆`25`
- [MykytaStel/repopilot](https://github.com/MykytaStel/repopilot) — Local, deterministic review of Git changes: weakened tests and CI gates, security boundaries, blast radius. CLI, GitHub Action, MCP server, and coding-agent plugins. ☆`24`
- [xxczaki/local-history-mcp](https://github.com/xxczaki/local-history-mcp) — MCP server for accessing VS Code/Cursor's Local History ☆`16`
- [geropl/git-mcp-go](https://github.com/geropl/git-mcp-go) — Git MCP based on mcp-go ☆`38`
- [ddukbg/github-enterprise-mcp](https://github.com/ddukbg/github-enterprise-mcp) — github-enterprise-mcp ☆`29`
- [kurdin/github-repos-manager-mcp](https://github.com/kurdin/github-repos-manager-mcp) — GitHub Repos Manager MCP Server for MCP clients ☆`22`
## Embedded & IoT

- [stack-chan/stack-chan](https://github.com/stack-chan/stack-chan) — A JavaScript-driven M5Stack-embedded super-kawaii robot. ☆`1,845`
- [tevonsb/homeassistant-mcp](https://github.com/tevonsb/homeassistant-mcp) — A MCP server for Home Assistant ☆`575`
- [lamaalrajih/kicad-mcp](https://github.com/lamaalrajih/kicad-mcp) — KiCad integration for Mac, Windows, Linux ☆`532`
- [Extelligence-ai/bagel](https://github.com/Extelligence-ai/bagel) — Chat with robotics, drone, IoT data ☆`400`
- [voska/hass-mcp](https://github.com/voska/hass-mcp) — Home Assistant control and queries from LLMs ☆`351`
- [recursechat/mcp-server-apple-shortcuts](https://github.com/recursechat/mcp-server-apple-shortcuts) — Apple Shortcuts automation on macOS ☆`353`
- [wiresage/mikrotik-mcp](https://github.com/wiresage/mikrotik-mcp) — MCP server for Mikrotik ☆`315`
- [hao-cyber/phone-mcp](https://github.com/hao-cyber/phone-mcp) — Control Android phone via ADB ☆`249`
- [FradSer/mcp-server-apple-events](https://github.com/FradSer/mcp-server-apple-events) — Native integration with Apple Reminders and Calendar ☆`233`
- [codeofaxel/Kiln](https://github.com/codeofaxel/Kiln) — From idea to object, and every version in between. Kiln is the open-source MCP server for 3D printing: AI agents (ChatGPT, Claude, Codex, Cursor, Gemini, Grok, Hermes Agent, or ☆`240`
- [coffeenmusic/altium-mcp](https://github.com/coffeenmusic/altium-mcp) — Altium Model Context Protocol server and Altium API script ☆`211`
- [Adancurusul/embedded-debugger-mcp](https://github.com/Adancurusul/embedded-debugger-mcp) — MCP server + CLI + Codex/Claude skill for embedded debugging via probe-rs or OpenOCD - ARM Cortex-M, RISC-V, and Xtensa (ESP32), with AI crash diagnosis ☆`212`
- [horw/esp-mcp](https://github.com/horw/esp-mcp) — ESP32 commands and getting started ☆`156`
- [LGDiMaggio/predictive-maintenance-mcp](https://github.com/LGDiMaggio/predictive-maintenance-mcp) — Predictive maintenance and fault diagnosis ☆`107`
- [johannesPettersson80/codesys-mcp-toolkit](https://github.com/johannesPettersson80/codesys-mcp-toolkit) — CODESYS industrial automation platform ☆`128`
- [Adancurusul/serial-mcp-server](https://github.com/Adancurusul/serial-mcp-server) — Rust MCP server and CLI for serial/UART devices, with JSON macro automation and agent skills for repeatable timed workflows. ☆`96`
- [thingsboard/thingsboard-mcp](https://github.com/thingsboard/thingsboard-mcp) — MCP server for ThingsBoard IoT platform interaction ☆`99`
- [handsomejustin/mijia-control](https://github.com/handsomejustin/mijia-control) — MijiaPilot - 小米-米家生态 × MCP × CLI x AI Agent × HomeKit 全桥接家庭智能家居平台。 ☆`80`
- [yoelbassin/gr-mcp](https://github.com/yoelbassin/gr-mcp) — MCP server for GNU Radio ☆`57`
- [Hybirdss/smartest-tv](https://github.com/Hybirdss/smartest-tv) — Control any smart TV with natural language. Play Netflix by name from your terminal. PyPI: stv · MCP server · LG/Samsung/Roku/Android ☆`56`
- [vishalmysore/choturobo](https://github.com/vishalmysore/choturobo) — Arduino robotics with AI integration ☆`79`
- [aqara/aqara-mcp-server](https://github.com/aqara/aqara-mcp-server) — Aqara's official MCP Server ☆`49`
- [jango-blockchained/advanced-homeassistant-mcp](https://github.com/jango-blockchained/advanced-homeassistant-mcp) — MCP server that gives AI assistants control over your Home Assistant. Including 50+ tools over 3 transports. Batteries included ☆`58`
- [chrisgleissner/c64bridge](https://github.com/chrisgleissner/c64bridge) — Commodore 64 Ultimate, Ultimate II, and VICE control ☆`41`
- [alexpfau/zigbee2mqtt-mcp](https://github.com/alexpfau/zigbee2mqtt-mcp) — MCP server for administering a Zigbee2MQTT estate: health reporting, mesh diagnostics, OTA updates, pairing, binding and device options over the MQTT bridge API. ☆`36`
- [NickoScope/nickol-knx-mcp](https://github.com/NickoScope/nickol-knx-mcp) — Design-time KNX/ETS assistant as an MCP server: validate (naming·DPT·status·Secure·Matter), repair (propose fixes), decompose devices (exact vendor models from ETS app-programs), ☆`30`
- [hekmon8/Homeassistant-server-mcp](https://github.com/hekmon8/Homeassistant-server-mcp) — A Model Context Protocol (MCP) server for interacting with Home Assistant. This server provides tools to control and monitor your Home Assistant devices through MCP-enabled ☆`48`
- [kambriso/fritzbox-mcp-server](https://github.com/kambriso/fritzbox-mcp-server) — FRITZ!Box MCP Server for LLM/ KI Integration - Home Automation from your favourite KI agent ☆`26`
- [yiwenlu66/PiloTY](https://github.com/yiwenlu66/PiloTY) — AI pilot for PTY operations - control terminals via MCP ☆`45`
- [nokia-steward/mcp-redfish](https://github.com/nokia-steward/mcp-redfish) — Query DMTF Redfish servers, systems, and network interfaces ☆`21`
- [ProductOfAmerica/mcp-server-kicad](https://github.com/ProductOfAmerica/mcp-server-kicad) — Maintenance mode: security and KiCad compatibility fixes only (see README for why). KiCad MCP server: 100+ Model Context Protocol tools that let an AI assistant do schematic ☆`16`
- [OctoEverywhere/mcp](https://github.com/OctoEverywhere/mcp) — 3D printing live status and control ☆`38`
- [ByteAsk/ByteAsk-Embedded-MCP](https://github.com/ByteAsk/ByteAsk-Embedded-MCP) — The open-source MCP server behind ByteAsk Embedded Docs: a source-grounded, page-cited evidence-retrieval server for coding agents (Claude Code, Codex, Cursor) that write ☆`26`
- [thinq-connect/thinqconnect-mcp](https://github.com/thinq-connect/thinqconnect-mcp) — ThinQ Connect MCP Server ☆`33`
- [kukapay/opcua-mcp](https://github.com/kukapay/opcua-mcp) — An MCP server that connects to OPC UA-enabled industrial systems. ☆`31`
- [github-hewei/mcp-android-adb-server](https://github.com/github-hewei/mcp-android-adb-server) — 通过AI大模型操作安卓设备 ☆`27`
- [kukapay/modbus-mcp](https://github.com/kukapay/modbus-mcp) — Industrial Modbus data for AI ☆`26`
- [Hypijump31/bluetooth-mcp-server](https://github.com/Hypijump31/bluetooth-mcp-server) — bluetooth-mcp-server for Claude AI ☆`25`
- [wolfcoming/adb_mcp_server](https://github.com/wolfcoming/adb_mcp_server) — Android ADB MCP 服务器 - 通过Claude或其他MCP客户端远程控制Android设备 ☆`25`
- [hpohlmann/home-assistant-mcp](https://github.com/hpohlmann/home-assistant-mcp) — A Model Context Protocol (MCP) integration that enables AI assistants to search for and control Home Assistant devices through natural language commands in Cursor. ☆`24`
- [MiddlePoint-Solutions/mcp-on-android-tv](https://github.com/MiddlePoint-Solutions/mcp-on-android-tv) — MCP server on Android TV with ADB ☆`23`
- [gNucleus/text-to-cad-mcp](https://github.com/gNucleus/text-to-cad-mcp) — gNucleus Text To CAD MCP server ☆`19`
## File Systems & Storage

- [chrisryugj/kordoc](https://github.com/chrisryugj/kordoc) — 한국 문서를 읽고·고치고·새로 쓰는 AI 문서 도구 - HWP·HWPX·PDF·오피스·스캔(OCR)을 Markdown으로, 신구대조·서식 보존 편집·Markdown→HWPX 작성·HWP→HWPX 변환·양식 채우기·공문서 검수까지. 라이브러리·CLI·MCP | Read, diff, edit, write and ☆`2,914`
- [SylphxAI/anymd](https://github.com/SylphxAI/anymd) — Any file → clean Markdown for AI agents: PDF, Word, PowerPoint, Excel, EPUB, HTML and web pages, images (OCR), audio and video (metadata, subtitles, transcripts). A fast Rust MCP ☆`1,061`
- [mark3labs/mcp-filesystem-server](https://github.com/mark3labs/mcp-filesystem-server) — Go filesystem operations via MCP ☆`695`
- [cyberchitta/llm-context.py](https://github.com/cyberchitta/llm-context.py) — Python library for LLM context management ☆`308`
- [8b-is/smart-tree](https://github.com/8b-is/smart-tree) — Context-aware AI-crafted replacement for tree command ☆`272`
- [isaacphi/mcp-gdrive](https://github.com/isaacphi/mcp-gdrive) — Google Drive file reading ☆`282`
- [rust-mcp-stack/rust-mcp-filesystem](https://github.com/rust-mcp-stack/rust-mcp-filesystem) — Fast async filesystem operations ☆`184`
- [efforthye/fast-filesystem-mcp](https://github.com/efforthye/fast-filesystem-mcp) — High-performance MCP server for file operations ☆`65`
- [UseJunior/safe-docx](https://github.com/UseJunior/safe-docx) — Safe DOCX suite: docx-primitives, docx-comparison, safe-docx MCP server ☆`47`
- [vespo92/TrueNasCoreMCP](https://github.com/vespo92/TrueNasCoreMCP) — A working TrueNAS Core MCP Server ☆`34`
- [j0hanz/filesystem-mcp](https://github.com/j0hanz/filesystem-mcp) — Filesystem MCP server for AI assistants. Search, read, edit, and manage local files in directories you choose. ☆`30`
- [dimitar-grigorov/mcp-file-tools](https://github.com/dimitar-grigorov/mcp-file-tools) — MCP server for file operations on non-UTF-8 text: detects the encoding from the bytes, hands the model UTF-8, and writes back in the original encoding with BOM and CRLF/LF ☆`29`
- [exoticknight/mcp-file-merger](https://github.com/exoticknight/mcp-file-merger) — MCP server for merging multiple files into one ☆`28`
- [Tencent/cos-mcp](https://github.com/Tencent/cos-mcp) — Tencent Cloud COS storage integration ☆`40`
- [NetApp/mcp](https://github.com/NetApp/mcp) — Model Context Protocol servers for NetApp services ☆`19`
- [willianpinho/large-file-mcp](https://github.com/willianpinho/large-file-mcp) — Chunk, search, navigate, and stream large files ☆`18`
- [Xuanwo/mcp-server-opendal](https://github.com/Xuanwo/mcp-server-opendal) — Model Context Protocol Server for Apache OpenDAL ☆`35`
## Finance

### Accounting & Budgeting

- [intuit/quickbooks-online-mcp-server](https://github.com/intuit/quickbooks-online-mcp-server) — The QuickBooks MCP Server lets AI assistants access QuickBooks data via a standard interface. It uses the Model Context Protocol to expose QBO features as callable tools, ☆`442`
- [openaccountants/openaccountants](https://github.com/openaccountants/openaccountants) — Open tax skills for AI: 2,250 skills across 266 jurisdictions, every figure cited to the law. Works in ChatGPT, Claude, Cursor and any MCP client. ☆`476`
- [XeroAPI/xero-mcp-server](https://github.com/XeroAPI/xero-mcp-server) — Xero accounting API integration ☆`389`
- [akutishevsky/lunchmoney-mcp](https://github.com/akutishevsky/lunchmoney-mcp) — MCP server for Lunch Money budgeting app ☆`112`
- [ignaciohermosillacornejo/copilot-money-mcp](https://github.com/ignaciohermosillacornejo/copilot-money-mcp) — MCP server for Copilot Money App - AI powered personal finance queries using local data ☆`88`
- [iiAtlas/hledger-mcp](https://github.com/iiAtlas/hledger-mcp) — A local MCP server for interacting with the HLedger cli ☆`65`
- [openMF/mcp-mifosx](https://github.com/openMF/mcp-mifosx) — Model Context Protocol - MCP for Mifos X ☆`28`
- [finlynq/finlynq](https://github.com/finlynq/finlynq) — Open-source (AGPL v3) personal finance app with a first-party MCP server. Track your money here, analyze it anywhere - query your finances from Claude, Cursor, or any MCP client. ☆`28`
- [minhyeoky/mcp-server-ledger](https://github.com/minhyeoky/mcp-server-ledger) — MCP server for Ledger CLI double-entry accounting ☆`51`
- [john-zhang-dev/xero-mcp](https://github.com/john-zhang-dev/xero-mcp) — Interact with Xero accounting ☆`22`
- [henfrydls/actual-budget-mcp](https://github.com/henfrydls/actual-budget-mcp) — MCP server for Actual Budget. Query and manage your personal finances through Claude ☆`20`
### Crypto & Blockchain

- [atilaahmettaner/tradingview-mcp](https://github.com/atilaahmettaner/tradingview-mcp) — MCP server for market analysis in AI assistants: screeners, multi-timeframe technical analysis, backtests and sentiment for crypto, stocks, forex and futures. 39 tools. Self-host ☆`5,203`
- [mcpdotdirect/evm-mcp-server](https://github.com/mcpdotdirect/evm-mcp-server) — EVM network interaction for LLMs ☆`379`
- [aaronjmars/web3-research-mcp](https://github.com/aaronjmars/web3-research-mcp) — Local MCP server for deep crypto token research across CoinGecko, DeFiLlama and web search. Free, no API key. ☆`171`
- [yolfinance/yolfi-agent](https://github.com/yolfinance/yolfi-agent) — Yolfi Agent Kit SDK, CLI, and MCP server for AI coding agents. ☆`177`
- [armorwallet/armor-crypto-mcp](https://github.com/armorwallet/armor-crypto-mcp) — Blockchain swaps and strategic planning ☆`178`
- [sendaifun/solana-mcp](https://github.com/sendaifun/solana-mcp) — A Model Context Protocol server for interacting with the Solana blockchain, powered by the Solana Agent Kit (https://github.com/sendaifun/solana-agent-kit) ☆`166`
- [Scottcjn/rustchain-mcp](https://github.com/Scottcjn/rustchain-mcp) — MCP server for AI agents in the RustChain ecosystem: RTC credit wallets and signed transfers, bounty discovery, BoTTube video publishing, and Beacon agent-to-agent messaging. ☆`119`
- [coinpaprika/dexpaprika-mcp](https://github.com/coinpaprika/dexpaprika-mcp) — MCP server for DEX trading data and crypto token analytics ☆`119`
- [kukapay/crypto-indicators-mcp](https://github.com/kukapay/crypto-indicators-mcp) — Cryptocurrency technical analysis indicators ☆`131`
- [alchemyplatform/alchemy-mcp-server](https://github.com/alchemyplatform/alchemy-mcp-server) — Alchemy blockchain API for AI agents ☆`88`
- [twelvedata/mcp](https://github.com/twelvedata/mcp) — MCP server for real-time financial market data access ☆`86`
- [lazy-dinosaur/ccxt-mcp](https://github.com/lazy-dinosaur/ccxt-mcp) — CCXT MCP Server bridges the gap between AI models and cryptocurrency trading by providing a standardized interface through the Model Context Protocol. Created to empower ☆`95`
- [amygdala-labs/web3-mcp](https://github.com/amygdala-labs/web3-mcp) — 1 MCP to rule all them chains ☆`93`
- [QuantGeekDev/coincap-mcp](https://github.com/QuantGeekDev/coincap-mcp) — A coincap mcp server to access crypto data from coincap API ☆`92`
- [getAlby/mcp](https://github.com/getAlby/mcp) — Bitcoin Lightning wallet via Nostr ☆`66`
- [norman-finance/norman-mcp-server](https://github.com/norman-finance/norman-mcp-server) — AI-powered bookkeeping and tax automation via MCP ☆`65`
- [bnb-chain/bnbchain-mcp](https://github.com/bnb-chain/bnbchain-mcp) — BNB Chain, BSC, opBNB, Greenfield ☆`61`
- [Bankless/onchain-mcp](https://github.com/Bankless/onchain-mcp) — Bringing the bankless onchain API to MCP ☆`78`
- [Nayshins/mcp-server-ccxt](https://github.com/Nayshins/mcp-server-ccxt) — Cryptocurrency Market Data MCP Server ☆`82`
- [kukapay/cryptopanic-mcp-server](https://github.com/kukapay/cryptopanic-mcp-server) — Provide latest cryptocurrency news to AI agents. ☆`74`
- [AbdelStark/bitcoin-mcp](https://github.com/AbdelStark/bitcoin-mcp) — Bitcoin & Lightning Network MCP Server. ☆`77`
- [heurist-network/heurist-mesh-mcp-server](https://github.com/heurist-network/heurist-mesh-mcp-server) — Blockchain and web3 via Heurist Mesh ☆`67`
- [GoPlausible/algorand-mcp](https://github.com/GoPlausible/algorand-mcp) — Algorand Local Model Context Protocol (Server & Client) ☆`44`
- [truss44/mcp-crypto-price](https://github.com/truss44/mcp-crypto-price) — A Model Context Protocol (MCP) server that provides real-time cryptocurrency analysis via CoinCap's API. Enables Claude and other MCP clients to fetch crypto prices, analyze ☆`40`
- [kukapay/whale-tracker-mcp](https://github.com/kukapay/whale-tracker-mcp) — A mcp server for tracking cryptocurrency whale transactions. ☆`58`
- [shinzo-labs/coinmarketcap-mcp](https://github.com/shinzo-labs/coinmarketcap-mcp) — MCP Implementation for CoinMarketCap ☆`51`
- [debridge-finance/debridge-mcp](https://github.com/debridge-finance/debridge-mcp) — MCP server that gives AI agents the ability to execute cross-chain cryptocurrency swaps and transfers via the deBridge protocol ☆`31`
- [kukapay/crypto-feargreed-mcp](https://github.com/kukapay/crypto-feargreed-mcp) — Crypto Fear & Greed Index data ☆`52`
- [vanto/beanquery-mcp](https://github.com/vanto/beanquery-mcp) — Beancount MCP Server is an experimental implementation that utilizes the Model Context Protocol (MCP) to enable AI assistants to query and analyze Beancount ledger files using ☆`52`
- [wowinter13/solscan-mcp](https://github.com/wowinter13/solscan-mcp) — Solana transaction queries ☆`49`
- [atxp-dev/atxp](https://github.com/atxp-dev/atxp) — Give your AI agent a wallet, email, phone number, and instant access to paid MCP tools - web search, image/video/music gen, X search, SMS, voice calls, code execution, and more. ☆`45`
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
- [dioptx/web3-docs](https://github.com/dioptx/web3-docs) — MCP server for Web3 protocol documentation - EIPs, ERCs, BIPs, SIMDs, Cosmos ADRs, Polkadot RFCs, contract registry ☆`36`
- [kukapay/kukapay-mcp-servers](https://github.com/kukapay/kukapay-mcp-servers) — Suite of MCP servers from Kukapay ☆`32`
- [longmans/coin_api_mcp](https://github.com/longmans/coin_api_mcp) — CoinMarketCap cryptocurrency data ☆`36`
- [crazyrabbitLTC/mcp-etherscan-server](https://github.com/crazyrabbitLTC/mcp-etherscan-server) — An MCP (Model Context Protocol) server that provides Ethereum blockchain data tools via Etherscan's API. Features include checking ETH balances, viewing transaction history, ☆`30`
- [nearai/near-mcp](https://github.com/nearai/near-mcp) — An MCP server for the NEAR blockchain ☆`31`
- [kukapay/hyperliquid-info-mcp](https://github.com/kukapay/hyperliquid-info-mcp) — MCP server for Hyperliquid DEX data ☆`30`
- [tedlikeskix/alpaca-mcp-server](https://github.com/tedlikeskix/alpaca-mcp-server) — Model Context Protocol (MCP) server for Alpaca trading API ☆`28`
- [kukapay/jupiter-mcp](https://github.com/kukapay/jupiter-mcp) — Jupiter DEX token swaps on Solana ☆`29`
- [devonmojito/ton-blockchain-mcp](https://github.com/devonmojito/ton-blockchain-mcp) — TON blockchain interaction ☆`27`
- [pwh-pwh/coin-mcp-server](https://github.com/pwh-pwh/coin-mcp-server) — Cryptocurrency info via Bitget API ☆`26`
- [aldrin-labs/solana-mcp-server](https://github.com/aldrin-labs/solana-mcp-server) — solana mcp sever to enable solana rpc methods ☆`25`
- [Codex-Data/codex-mcp](https://github.com/Codex-Data/codex-mcp) — A Model Context Protocol server for the Codex API ☆`25`
- [kukapay/token-minter-mcp](https://github.com/kukapay/token-minter-mcp) — ERC-20 token minting for AI agents ☆`22`
- [ahnlabio/bicscan-mcp](https://github.com/ahnlabio/bicscan-mcp) — BICScan MCP Server ☆`16`
- [kukapay/rug-check-mcp](https://github.com/kukapay/rug-check-mcp) — An MCP server that detects potential risks in Solana meme tokens. ☆`21`
- [magnetai/mcp-free-usdc-transfer](https://github.com/magnetai/mcp-free-usdc-transfer) — Free USDC transfer via Coinbase CDP ☆`21`
- [saintdoresh/Crypto-Trader-MCP-ClaudeDesktop](https://github.com/saintdoresh/Crypto-Trader-MCP-ClaudeDesktop) — An MCP (Model Context Protocol) tool that provides cryptocurrency market data using the CoinGecko API, specifically designed for Claude Desktop. ☆`21`
- [janswist/mcp-dexscreener](https://github.com/janswist/mcp-dexscreener) — Dexscreener on-chain price checking ☆`19`
- [xiaok/etherscan-mcp](https://github.com/xiaok/etherscan-mcp) — Model Context Protocol (MCP) Server for Etherscan ☆`18`
- [kukapay/crypto-rss-mcp](https://github.com/kukapay/crypto-rss-mcp) — Real-time cryptocurrency news from multiple RSS feeds ☆`17`
- [syronlabs/stellar-mcp](https://github.com/syronlabs/stellar-mcp) — A Stellar MCP to interact with Horizon API and Soroban ☆`18`
- [kukapay/defi-yields-mcp](https://github.com/kukapay/defi-yields-mcp) — DeFi yield opportunities powered by DefiLlama ☆`16`
- [kukapay/crypto-orderbook-mcp](https://github.com/kukapay/crypto-orderbook-mcp) — Order-book depth and imbalance on major crypto exchanges ☆`16`
### Payments & Banking

- [stripe/ai](https://github.com/stripe/ai) — One-stop shop for building AI-powered products and businesses with Stripe. ☆`2,035`
- [razorpay/razorpay-mcp-server](https://github.com/razorpay/razorpay-mcp-server) — Razorpay's Official MCP Server ☆`231`
- [paypal/agent-toolkit](https://github.com/paypal/agent-toolkit) — PayPal Agent ☆`198`
- [square/square-mcp-server](https://github.com/square/square-mcp-server) — A Model Context Protocol (MCP) server for square ☆`109`
- [ninetails-io/gnucash-mcp](https://github.com/ninetails-io/gnucash-mcp) — MCP server enabling AI assistants to read and write GnuCash accounting data ☆`85`
- [nuanu-ai/agent-payment-node](https://github.com/nuanu-ai/agent-payment-node) — Local stdio MCP payment runtime for AI agents on macOS Apple Silicon, with x402 support and foreground owner approval. ☆`78`
- [PaddleHQ/paddle-mcp-server](https://github.com/PaddleHQ/paddle-mcp-server) — Interact with Paddle API ☆`49`
- [icyberdeveloper/tbank-mcp](https://github.com/icyberdeveloper/tbank-mcp) — Unofficial MCP server for T-Bank (Т-Банк, ex-Tinkoff) mobile banking: accounts, cards, transfers, bill pay, grocery ordering, tickets & travel - for Claude Code and any MCP client. ☆`40`
- [CorpusIQ/corpusiq-docs](https://github.com/CorpusIQ/corpusiq-docs) — Hermes Agent Production Knowledge Repository - 406+ repos, AI Agent Marketplace, MCP servers, autonomous AI agent patterns. Production-tested from 1,200+ hours of ops. Updated ☆`29`
- [qonto/qonto-mcp-server](https://github.com/qonto/qonto-mcp-server) — Qonto MCP Server ☆`42`
- [atharvagupta2003/mcp-stripe](https://github.com/atharvagupta2003/mcp-stripe) — Stripe payments, customers, and refunds ☆`44`
- [ant-intl/global-antom-mcp](https://github.com/ant-intl/global-antom-mcp) —  ☆`32`
- [Fewsats/fewsats-mcp](https://github.com/Fewsats/fewsats-mcp) — Fewsats MCP server ☆`21`
### Stock Data & Analytics

- [financial-datasets/mcp-server](https://github.com/financial-datasets/mcp-server) — Financial Datasets stock market API ☆`2,317`
- [relaticle/relaticle](https://github.com/relaticle/relaticle) — Open-source CRM your AI agents can read and update: companies, people, opportunities, tasks and notes. REST API, self-hosted or cloud. ☆`1,807`
- [rootSunc/CNEquity](https://github.com/rootSunc/CNEquity) — 开源中国股市（A股）本地数据湖：沪深股票行情、A股股票数据与金融数据，面向量化研究、量化交易与回测，含财务数据、期货数据、资金流向、公告、指数行业与宏观。55 个日更数据集，复权与历史成分内置，行级溯源、PIT，MCP 原生。免注册、免 Token，自托管。Open-source China stock market data lake for ☆`948`
- [massive-com/mcp_massive](https://github.com/massive-com/mcp_massive) — An MCP server for Massive.com Financial Market Data ☆`400`
- [stefanoamorelli/sec-edgar-mcp](https://github.com/stefanoamorelli/sec-edgar-mcp) — A SEC EDGAR MCP (Model Context Protocol) Server ☆`384`
- [s-stefanov/actual-mcp](https://github.com/s-stefanov/actual-mcp) — Model Context Protocol for Actual Budget API ☆`280`
- [daniel3303/Equibles](https://github.com/daniel3303/Equibles) — SEC filings, fundamentals, transcripts, 13F and insider data ☆`240`
- [narumiruna/yfinance-mcp](https://github.com/narumiruna/yfinance-mcp) — MCP server for Yahoo Finance stock data and news ☆`207`
- [traceloop/opentelemetry-mcp-server](https://github.com/traceloop/opentelemetry-mcp-server) — Unified MCP server for querying OpenTelemetry traces across multiple backends (Jaeger, Tempo, Traceloop, etc.), enabling AI agents to analyze distributed traces for automated ☆`204`
- [jjlabsio/korea-stock-mcp](https://github.com/jjlabsio/korea-stock-mcp) — MCP Server for Korean stock analysis ☆`184`
- [calebl/ynab-mcp-server](https://github.com/calebl/ynab-mcp-server) — Model Context Protocol for YNAB (you need a budget) ☆`162`
- [Tapetide-hq/nse-bse-indian-stock-market-data-mcp](https://github.com/Tapetide-hq/nse-bse-indian-stock-market-data-mcp) — NSE and BSE (India) stock data, screeners, FII/DII flows, option chains and filings ☆`147`
- [OctagonAI/octagon-mcp-server](https://github.com/OctagonAI/octagon-mcp-server) — Public filings, earnings, financial analysis ☆`148`
- [berlinbra/polymarket-mcp](https://github.com/berlinbra/polymarket-mcp) — MCP Server for PolyMarket API ☆`144`
- [HuggingAGI/mcp-baostock-server](https://github.com/HuggingAGI/mcp-baostock-server) — MCP server for BaoStock Chinese stock market data ☆`119`
- [unusual-whales/unusual-whales-official-mcp](https://github.com/unusual-whales/unusual-whales-official-mcp) —  ☆`93`
- [berlinbra/alpha-vantage-mcp](https://github.com/berlinbra/alpha-vantage-mcp) — MCP Server for Alpha Advantage API ☆`104`
- [calvernaz/alphavantage](https://github.com/calvernaz/alphavantage) — A MCP server for the stock market data API, Alphavantage API. ☆`74`
- [twolven/mcp-stockscreen](https://github.com/twolven/mcp-stockscreen) — Stock screening provider for Claude Desktop using MCP ☆`49`
- [infaton/MCP35](https://github.com/infaton/MCP35) — INFATON MCP Server - 94 tools for 1C:Enterprise ERP via Model Context Protocol (JSON-RPC 2.0). Open source, MIT. infaton.ru · chatmcp.ru ☆`47`
- [twolven/mcp-optionsflow](https://github.com/twolven/mcp-optionsflow) — An MCP server providing advanced options analysis through Yahoo Finance, supporting Greeks calculations, strategy evaluation (CCS/PCS/CSP/CC), and risk metrics. Built for MCP ☆`41`
- [Adity-star/mcp-yfinance-server](https://github.com/Adity-star/mcp-yfinance-server) — Real-time stock data with yfinance ☆`54`
- [JamesANZ/prediction-market-mcp](https://github.com/JamesANZ/prediction-market-mcp) — Polymarket, PredictIt, Kalshi data ☆`38`
- [dustinliang666-blip/lava-mcp](https://github.com/dustinliang666-blip/lava-mcp) — China A-share news-flow heat for AI agents — trending concepts, sectors, and related tickers (read-only) ☆`40`
- [AgentX-ai/yahoo-finance-server](https://github.com/AgentX-ai/yahoo-finance-server) — Yahoo Finance stock data and news ☆`53`
- [ComplyEaze/bridge](https://github.com/ComplyEaze/bridge) — ComplyEaze Bridge is an open-source (Apache-2.0) TallyPrime MCP server for Claude Desktop, for CA firms and accountants. Reads the books on your own computer; prepares vouchers ☆`35`
- [9crusher/mcp-server-kalshi](https://github.com/9crusher/mcp-server-kalshi) — A MCP server to interact with Kalshi prediction markets ☆`32`
- [zlinzzzz/finData-mcp-server](https://github.com/zlinzzzz/finData-mcp-server) — Financial data from Tushare, Wind, DataYes ☆`57`
- [vanderheijden86/moneybird-mcp-server](https://github.com/vanderheijden86/moneybird-mcp-server) — Moneybird MCP Server - AI-powered bookkeeping ☆`29`
- [twolven/mcp-stockflow](https://github.com/twolven/mcp-stockflow) — Stock market data provider for Claude Desktop using MCP ☆`27`
- [trayders/trayd-mcp](https://github.com/trayders/trayd-mcp) — Trade Robinhood via Claude Code - MCP Server ☆`41`
- [tonnode/mcp](https://github.com/tonnode/mcp) — TON MCP server for Claude, ChatGPT, Cursor, Codex and any MCP client - liteserver queries over native ADNL: balances, account state, transaction history, get-methods. Private & ☆`27`
- [Mrbaeksang/korea-stock-analyzer-mcp](https://github.com/Mrbaeksang/korea-stock-analyzer-mcp) — Korean stocks from DART filings and KRX quotes ☆`25`
- [danishashko/yahoo-finance-mcp](https://github.com/danishashko/yahoo-finance-mcp) — Beginner-friendly Yahoo Finance MCP server for Claude. Get real-time stock data, charts, financials, analyst ratings, and compare multiple companies. ☆`24`
- [grahammccain/chart-library-mcp](https://github.com/grahammccain/chart-library-mcp) — MCP server for Chart Library - visual chart pattern search engine. Find similar historical stock charts and see what happened next. ☆`23`
- [cliwant/mcp-sam-gov](https://github.com/cliwant/mcp-sam-gov) — Keyless-first MCP server - 150 tools for US federal + state/local (SLED) government contracting, spending, regulation & partner vetting. SAM.gov, USAspending, Grants.gov, OFAC, ☆`16`
- [OctagonAI/octagon-vc-agents](https://github.com/OctagonAI/octagon-vc-agents) — AI-driven venture capitalist agents ☆`32`
- [27dream/mcp-eastmoney](https://github.com/27dream/mcp-eastmoney) — 东方财富MCP服务器 | A股实时行情+主力资金+板块数据+K线 | Claude Code/Cursor通用 ☆`18`
- [QuantGeekDev/fiscal-data-mcp](https://github.com/QuantGeekDev/fiscal-data-mcp) — mcp server connected to us treasury data, built with mcp-framework ☆`20`
### Trading & Exchanges

- [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) — "Vibe-Trading: Your Personal Trading Agent" ☆`37,639`
- [chengzuopeng/stock-sdk](https://github.com/chengzuopeng/stock-sdk) — 为前端设计的无需 Python、无需后端服务、零依赖的获取股票数据 JavaScript SDK。 ☆`1,999`
- [mnemox-ai/tradememory-protocol](https://github.com/mnemox-ai/tradememory-protocol) — Decision audit trail + persistent memory for AI trading agents. Outcome-weighted recall, tamper-evident SHA-256 chain with RFC 3161 anchoring, 20 MCP tools. ☆`1,440`
- [whchien/ai-trader](https://github.com/whchien/ai-trader) — Backtrader-powered backtesting framework for algorithmic trading, featuring 20+ strategies, multi-market support, CLI tools, and an integrated MCP server for professional traders. ☆`1,132`
- [alpacahq/alpaca-mcp-server](https://github.com/alpacahq/alpaca-mcp-server) — Trade stocks, ETFs, crypto, options ☆`1,057`
- [ariadng/metatrader-mcp-server](https://github.com/ariadng/metatrader-mcp-server) — MetaTrader trading platform for AI LLMs ☆`843`
- [dragon1086/prism-insight](https://github.com/dragon1086/prism-insight) — AI-based stock analysis and trading system ☆`795`
- [krakenfx/kraken-cli](https://github.com/krakenfx/kraken-cli) — Trade crypto, tokenized stocks, forex and futures on Kraken from your terminal or your AI agent. Built-in MCP server for Claude, Codex and Cursor, JSON output, and paper trading ☆`797`
- [YoungCan-Wang/WyckoffTradingAgent](https://github.com/YoungCan-Wang/WyckoffTradingAgent) — Open-source Wyckoff trading agent and AI stock screener for volume-price analysis, A-share screening, CLI workflows, and MCP tools.灵感来自秋生trader @Hoyooyoo ☆`768`
- [caiovicentino/polymarket-mcp-server](https://github.com/caiovicentino/polymarket-mcp-server) — AI-Powered MCP Server for Polymarket - Enable Claude to trade prediction markets with 45 tools, real-time monitoring, and enterprise-grade safety features ☆`737`
- [wshobson/maverick-mcp](https://github.com/wshobson/maverick-mcp) — Stock market MCP server for Yahoo Finance data, technical analysis, portfolio tracking, and Python backtesting. Runs locally with no API key for core tools. ☆`718`
- [saidsurucu/borsa-mcp](https://github.com/saidsurucu/borsa-mcp) — MCP Server for Turkish & American Stock Exchange and Fund Data ☆`660`
- [okx/agent-trade-kit](https://github.com/okx/agent-trade-kit) — OKX trading MCP server - connect AI agents to spot, swap, futures, options & grid bots via the Model Context Protocol. ☆`501`
- [longbridge/openapi](https://github.com/longbridge/openapi) — Longbridge OpenAPI SDK Base. ☆`465`
- [elsejj/mcp-cn-a-stock](https://github.com/elsejj/mcp-cn-a-stock) — 这是一个为大模型提供 A 股数据的的 MCP(Model Content Protocol) 服务。 ☆`462`
- [koreal6803/finlab-ai](https://github.com/koreal6803/finlab-ai) — Official FinLab skill: backtest Taiwan and U.S. stocks with Claude Code or Codex on real market data. ☆`424`
- [staskh/trading_skills](https://github.com/staskh/trading_skills) — Claude powered advisor system for option traders ☆`403`
- [Alex2Yang97/yahoo-finance-mcp](https://github.com/Alex2Yang97/yahoo-finance-mcp) — This is a Model Context Protocol (MCP) server that provides comprehensive financial data from Yahoo Finance. It allows you to retrieve detailed information about stocks, ☆`366`
- [aahl/mcp-aktools](https://github.com/aahl/mcp-aktools) — 提供股票、加密货币的数据查询和分析功能MCP服务器 ☆`391`
- [ferdousbhai/investor-agent](https://github.com/ferdousbhai/investor-agent) — Investor agent building via MCP ☆`348`
- [QuantMLResearch/AI-Kline](https://github.com/QuantMLResearch/AI-Kline) — Python-based stock analysis tool that combines traditional technical analysis with AI prediction capabilities. Providing comprehensive stock analysis and forecasting using K-line ☆`345`
- [guangxiangdebizi/TradingAgents-MCPmode](https://github.com/guangxiangdebizi/TradingAgents-MCPmode) — TradingAgents-MCPmode 是一个创新的多智能体交易分析系统，集成了 Model Context Protocol (MCP) 工具，实现了智能化的股票分析和交易决策流程。系统通过多个专业化智能体的协作，提供全面的市场分析、投资建议和风险管理。 ☆`339`
- [Qoyyuum/mcp-metatrader5-server](https://github.com/Qoyyuum/mcp-metatrader5-server) — A Model Context Protocol (MCP) server for interacting with the MetaTrader 5 trading platform. This server provides AI assistants with tools and resources to access market data, ☆`239`
- [zwldarren/akshare-one-mcp](https://github.com/zwldarren/akshare-one-mcp) — MCP server that provides access to Chinese stock market data using akshare-one ☆`240`
- [wbsu2003/stock-scanner-mcp](https://github.com/wbsu2003/stock-scanner-mcp) — 这是一个基于 FastAPI-MCP 的股票分析服务，旨在通过 MCP 工具函数接口提供股票相关的综合数据和分析能力，包括价格、评分、技术报告和 AI 分析。 ☆`244`
- [dfkai/xtquantai](https://github.com/dfkai/xtquantai) — 迅投 QMT 量化 AI 技能集（Agent Skills）：研报因子回测脚本生成等，适用于 Claude Code / Cursor / Codex / Kimi 等 70+ AI 编程工具 ☆`170`
- [imbenrabi/Financial-Modeling-Prep-MCP-Server](https://github.com/imbenrabi/Financial-Modeling-Prep-MCP-Server) — A Model Context Protocol (MCP) implementation for Financial Modeling Prep, enabling AI assistants to access and analyze financial data, stock information, company fundamentals, ☆`149`
- [kukapay/freqtrade-mcp](https://github.com/kukapay/freqtrade-mcp) — Freqtrade crypto trading bot ☆`149`
- [doggybee/mcp-server-ccxt](https://github.com/doggybee/mcp-server-ccxt) — Cryptocurrency exchange integration via CCXT ☆`145`
- [taylorwilsdon/quantconnect-mcp](https://github.com/taylorwilsdon/quantconnect-mcp) — QuantConnect trading orchestration ☆`125`
- [ferdousbhai/tasty-agent](https://github.com/ferdousbhai/tasty-agent) — Let Claude manage your tastytrade portfolio. ☆`89`
- [QuantConnect/mcp-server](https://github.com/QuantConnect/mcp-server) — QuantConnect algo trading interaction ☆`80`
- [dragon1086/kospi-kosdaq-stock-server](https://github.com/dragon1086/kospi-kosdaq-stock-server) — An MCP server that provides KOSPI/KOSDAQ stock data using FastMCP ☆`74`
- [trade-it-inc/trade-it-mcp](https://github.com/trade-it-inc/trade-it-mcp) — Trade It stocks and crypto trading ☆`62`
- [netanelavr/trading-mcp](https://github.com/netanelavr/trading-mcp) — The MCP server that will help you trade smarter (or at least try) ☆`75`
- [hypurrquant/perp-cli](https://github.com/hypurrquant/perp-cli) — Multi-DEX perpetual futures CLI + MCP server for traders and AI agents - trade on Hyperliquid (incl. HIP-3), Pacifica, Lighter, Aster, Ondo, Arcus, QFEX and more; funding-rate ☆`40`
- [coinpaprika/coinpaprika-mcp](https://github.com/coinpaprika/coinpaprika-mcp) — MCP server for CoinPaprika cryptocurrency market data API - prices, tickers, exchanges, OHLCV, and more ☆`31`
- [ozgureyilmaz/polymarket-mcp](https://github.com/ozgureyilmaz/polymarket-mcp) — Polymarket prediction markets data ☆`48`
- [mektigboy/server-hyperliquid](https://github.com/mektigboy/server-hyperliquid) — Hyperliquid DEX trading integration ☆`44`
- [demwick/polymarket-agent-mcp](https://github.com/demwick/polymarket-agent-mcp) — The most comprehensive MCP server for Polymarket - 48 tools spanning direct trading, market discovery, smart money tracking, copy trading, backtesting, risk management, and ☆`18`
- [ethancod1ng/binance-mcp-server](https://github.com/ethancod1ng/binance-mcp-server) — Binance exchange API integration ☆`34`
- [saintdoresh/YFinance-Trader-MCP-ClaudeDesktop](https://github.com/saintdoresh/YFinance-Trader-MCP-ClaudeDesktop) — An MCP (Model Context Protocol) tool that provides stock market data and trading capabilities using the yfinance library, specifically adapted for Claude Desktop. ☆`37`
- [laukikk/alpaca-mcp](https://github.com/laukikk/alpaca-mcp) — Alpaca stock and crypto trading ☆`35`
- [ferdousbhai/wsb-analyst-mcp](https://github.com/ferdousbhai/wsb-analyst-mcp) — MCP server for analyzing WallStreetBets ☆`31`
- [paperinvest/mcp-server](https://github.com/paperinvest/mcp-server) — Paper trading platform integration ☆`24`
- [solangii/upbit-mcp-server](https://github.com/solangii/upbit-mcp-server) — MCP(Model Context Protocol) server for Upbit ☆`17`
## Frameworks & SDKs

- [mastra-ai/mastra](https://github.com/mastra-ai/mastra) — TypeScript AI agent framework with RAG ☆`29,318`
- [mcp-use/mcp-use](https://github.com/mcp-use/mcp-use) — The fullstack MCP framework to develop MCP Apps for ChatGPT / Claude & MCP Servers for AI Agents. ☆`10,845`
- [lastmile-ai/mcp-agent](https://github.com/lastmile-ai/mcp-agent) — Build agents with MCP and workflow patterns ☆`8,575`
- [xmcp](https://github.com/basementstudio/xmcp) — TypeScript framework for building MCP servers. Website: https://xmcp.dev. ☆`1,346`
- [afrise/MCPSharp](https://github.com/afrise/MCPSharp) — MCPSharp is a .NET library that helps you build Model Context Protocol (MCP) servers and clients - the standardized API protocol used by AI assistants and models. ☆`377`
- [vinkius-labs/mcpfusion](https://github.com/vinkius-labs/mcpfusion) — MCP Fusion - The TypeScript framework for secure MCP servers. ☆`255`
- [posit-dev/mcptools](https://github.com/posit-dev/mcptools) — Model Context Protocol For R ☆`203`
- [quarkiverse/quarkus-mcp-servers](https://github.com/quarkiverse/quarkus-mcp-servers) — Model Context Protocol Servers in Quarkus ☆`196`
- [wong2/litemcp](https://github.com/wong2/litemcp) — A TypeScript framework for building MCP servers elegantly ☆`186`
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

- [Coding-Solo/godot-mcp](https://github.com/Coding-Solo/godot-mcp) — MCP server for Godot game engine ☆`6,498`
- [IvanMurzak/Unity-MCP](https://github.com/IvanMurzak/Unity-MCP) — AI-powered bridge connecting LLMs to Unity Editor ☆`4,578`
- [CoderGamester/mcp-unity](https://github.com/CoderGamester/mcp-unity) — MCP server for Unity game engine integration ☆`2,013`
- [youichi-uda/godot-mcp-pro](https://github.com/youichi-uda/godot-mcp-pro) — 162 MCP tools for AI-powered Godot 4 development. Scene, animation, 3D, physics, particles, audio, shader, input simulation, runtime analysis, navigation, testing & more. $15 ☆`641`
- [ee0pdt/Godot-MCP](https://github.com/ee0pdt/Godot-MCP) — An MCP for Godot that lets you create and edit games in the Godot game engine with tools like Claude ☆`621`
- [kvick-games/UnrealMCP](https://github.com/kvick-games/UnrealMCP) — MCP to allow AI agents to control Unreal ☆`615`
- [IvanMurzak/Godot-MCP](https://github.com/IvanMurzak/Godot-MCP) — Godot 4.x editor and runtime for AI agents ☆`322`
- [playcanvas/editor-mcp-server](https://github.com/playcanvas/editor-mcp-server) — MCP Server for AI automation of the PlayCanvas Editor ☆`150`
- [ayeletstudioindia/unreal-analyzer-mcp](https://github.com/ayeletstudioindia/unreal-analyzer-mcp) — MCP server for Unreal Engine 5 ☆`161`
- [quazaai/UnityMCPIntegration](https://github.com/quazaai/UnityMCPIntegration) — Enable AI Agents to Control Unity ☆`156`
- [Erodenn/godot-mcp-runtime](https://github.com/Erodenn/godot-mcp-runtime) — A lightweight, zero-footprint TypeScript MCP server that lets AI assistants drive the Godot 4.x game engine. ☆`96`
- [tonypan2/minesweeper-mcp-server](https://github.com/tonypan2/minesweeper-mcp-server) — An MCP server for playing Minesweeper ☆`106`
- [pab1it0/chess-mcp](https://github.com/pab1it0/chess-mcp) — MCP server for Chess.com player data, games and statistics ☆`93`
- [codemaestroai/advanced-unity-mcp](https://github.com/codemaestroai/advanced-unity-mcp) — Advanced Unity game engine integration ☆`95`
- [hope1026/weppy-roblox-mcp](https://github.com/hope1026/weppy-roblox-mcp) — Roblox Studio MCP server & plugin for Claude Code, Cursor, Codex, and Gemini. AI-powered scripts, terrain, assets, lighting, and bidirectional project sync. ☆`74`
- [kkjdaniel/bgg-mcp](https://github.com/kkjdaniel/bgg-mcp) — MCP server for BoardGameGeek data ☆`59`
- [IvanMurzak/Unreal-MCP](https://github.com/IvanMurzak/Unreal-MCP) — Unreal Engine 5.7 editor and runtime for AI agents ☆`57`
- [sawa-zen/vrchat-mcp](https://github.com/sawa-zen/vrchat-mcp) — VRChat API interaction ☆`71`
- [beckettlab/beckett-godot-mcp](https://github.com/beckettlab/beckett-godot-mcp) — Zero-sidecar MCP server inside the Godot editor. AI agents (Claude Code, Cursor) inspect, author, run and SEE your game. GDScript + C#, validate-before-write, no Node.js. Godot ☆`49`
- [Dokujaa/Godot-MCP](https://github.com/Dokujaa/Godot-MCP) — An MCP for Godot that leverages Claude ☆`54`
- [jalpp/chessagine-mcp](https://github.com/jalpp/chessagine-mcp) — Advanced chess analysis capabilities ☆`34`
- [dearlordylord/5e-quint](https://github.com/dearlordylord/5e-quint) — Quint definition of Dungeons and Dragons 5e core rules ☆`32`
- [kitao/pyxel-mcp](https://github.com/kitao/pyxel-mcp) — MCP server for AI-assisted retro game development with Pyxel ☆`32`
- [german-krasnikov/unity-biome-mcp](https://github.com/german-krasnikov/unity-biome-mcp) — MCP server for Unity Editor - 160 tools for scene, assets, animation, VFX, playtest & more ☆`31`
- [procload/dnd-mcp](https://github.com/procload/dnd-mcp) — MCP Server implementation of the DnD 5e API using resources, tools, and prompts. ☆`53`
- [DiegoLopez0208/RpgMakerMVUltimate-MCP](https://github.com/DiegoLopez0208/RpgMakerMVUltimate-MCP) — RPG Maker MV Copilot MCP - Debug events, edit maps, and playtest RPG Maker MV projects with AI. ☆`30`
- [runeape-sats/unreal-mcp](https://github.com/runeape-sats/unreal-mcp) — pure python Unreal Engine MCP server ☆`47`
- [buildepicshit/Wick](https://github.com/buildepicshit/Wick) — Roslyn-enriched C# exception telemetry for Godot Engine, exposed over MCP ☆`22`
- [karayaman/lichess-mcp](https://github.com/karayaman/lichess-mcp) — A Model Context Protocol (MCP) server that enables Claude Desktop to interact with Lichess chess platform through natural language. Play games, analyze positions, manage your ☆`20`
- [IvanMurzak/GameDev-MCP-Server](https://github.com/IvanMurzak/GameDev-MCP-Server) — Open-source, engine-agnostic MCP server shared by Unity-MCP, Godot-MCP, and Unreal-MCP ☆`18`
- [cryppadotta/scryfall-mcp](https://github.com/cryppadotta/scryfall-mcp) — A mcp server for interacting with the Scryfall Magic The Gathering API ☆`36`
- [jifrozen0110/mcp-riot](https://github.com/jifrozen0110/mcp-riot) — League of Legends MCP Server ☆`27`
- [jiayao/mcp-chess](https://github.com/jiayao/mcp-chess) — MCP server for playing chess against AI ☆`24`
- [tahooki/unreal-blender-mcp](https://github.com/tahooki/unreal-blender-mcp) — unreal-blender-mcp ☆`21`
- [sonirico/mcp-stockfish](https://github.com/sonirico/mcp-stockfish) — MCP server connecting AI systems to Stockfish chess engine ☆`16`
## Healthcare & Bioinformatics

- [genomoncology/biomcp](https://github.com/genomoncology/biomcp) — BioMCP: Biomedical Model Context Protocol ☆`672`
- [the-momentum/apple-health-mcp-server](https://github.com/the-momentum/apple-health-mcp-server) — Apple Health data queries with DuckDB ☆`285`
- [wso2/fhir-mcp-server](https://github.com/wso2/fhir-mcp-server) — FHIR healthcare API integration ☆`137`
- [JamesANZ/medical-mcp](https://github.com/JamesANZ/medical-mcp) — MCP server for medical data processing ☆`120`
- [ChristianHinge/dicom-mcp](https://github.com/ChristianHinge/dicom-mcp) — DICOM server (PACS) interaction ☆`106`
- [grll/pubmedmcp](https://github.com/grll/pubmedmcp) — A MCP server for PubMed data ☆`122`
- [davidmosiah/google-health-mcp](https://github.com/davidmosiah/google-health-mcp) — Local-first MCP server for Google Health API v4 (Fitbit + Pixel Watch) - Claude/Cursor/Hermes ☆`79`
- [the-momentum/fhir-mcp-server](https://github.com/the-momentum/fhir-mcp-server) — FHIR MCP Server for handling medical data standard. ☆`102`
- [soma-intelligence/open-health-sync](https://github.com/soma-intelligence/open-health-sync) — Open source health data aggregator and self-hosted Terra alternative. One API for wearable data from Apple Health, Health Connect, Oura, WHOOP, Withings, Fitbit, Dexcom and more: ☆`60`
- [srijanshukla18/xray](https://github.com/srijanshukla18/xray) — MCP server for X-ray analysis ☆`52`
- [cafferychen777/ChatSpatial](https://github.com/cafferychen777/ChatSpatial) — Spatial transcriptomics via natural language (Python/R) ☆`45`
- [akutishevsky/withings-mcp](https://github.com/akutishevsky/withings-mcp) — MCP server for Withings health data integration ☆`45`
- [kidzik/other-public-mcps](https://github.com/kidzik/other-public-mcps) — A suite of MCP servers enabling AI assistants to access and interact with various biomedical databases and resources for research purposes. Key for life sciences and biomedical... ☆`58`
- [OHNLP/omop_mcp](https://github.com/OHNLP/omop_mcp) — MCP server for OMOP medical data standard ☆`41`
- [OkGoDoIt/beemcp](https://github.com/OkGoDoIt/beemcp) — BeeMCP: an unofficial Model Context Protocol (MCP) server that connects your Bee wearable lifelogger to AI via the Model Context Protocol ☆`51`
- [ammawla/encode-toolkit](https://github.com/ammawla/encode-toolkit) — MCP server and Claude Code plugin for the ENCODE Project: search, download and analyze ChIP-seq, ATAC-seq, RNA-seq, WGBS, Hi-C and CUT&RUN data with 20 tools, 47 skills and 7 ☆`22`
- [wavelovey/pubmed_search](https://github.com/wavelovey/pubmed_search) — MCP PubMed Search Server ☆`46`
- [Jezue/fitatu_library](https://github.com/Jezue/fitatu_library) — Unofficial Python API client for Fitatu - built for AI agents and automation ☆`21`
- [longevity-genie/biothings-mcp](https://github.com/longevity-genie/biothings-mcp) — MCP (Model Context Protocol) server for biothings ☆`37`
- [SidneyBissoli/medical-terminologies-mcp](https://github.com/SidneyBissoli/medical-terminologies-mcp) — Unified MCP server for six medical terminologies (ICD-11, LOINC, RxNorm, MeSH, ATC, CID-10) with authoritative WHO ICD-10→ICD-11 mapping and provenance on every response. Hosted ☆`16`
- [tomekkorbak/oura-mcp-server](https://github.com/tomekkorbak/oura-mcp-server) — MCP server for Oura API integration ☆`39`
- [longevity-genie/gget-mcp](https://github.com/longevity-genie/gget-mcp) — Bioinformatic gget functions ☆`33`
- [Sivan22/mcp-otzaria-server](https://github.com/Sivan22/mcp-otzaria-server) — makes the jewish library accessible to LLMs through the MCP protocol ☆`23`
- [longevity-genie/opengenes-mcp](https://github.com/longevity-genie/opengenes-mcp) — MCP for the open-genes ☆`21`
- [deak-ai/openehr-mcp-server](https://github.com/deak-ai/openehr-mcp-server) — Facilitates seamless integration with openEHR REST APIs, enabling the creation and management of electronic health records and compositions. Supports AI-driven EHR operations. ☆`18`
## LLM Bridges

- [CherryHQ/cherry-studio](https://github.com/CherryHQ/cherry-studio) — Your AI workspace for models, agents, and productivity. ☆`53,256`
- [perplexityai/modelcontextprotocol](https://github.com/perplexityai/modelcontextprotocol) — Official Perplexity API MCP server ☆`2,607`
- [ggozad/oterm](https://github.com/ggozad/oterm) — the terminal client for LLMs ☆`2,446`
- [jamubc/gemini-mcp-tool](https://github.com/jamubc/gemini-mcp-tool) — MCP server for Gemini CLI with large file analysis ☆`2,294`
- [OpenAgentPlatform/Dive](https://github.com/OpenAgentPlatform/Dive) — Dive is an open-source MCP Host Desktop Application that seamlessly integrates with any LLMs supporting function calling capabilities. ☆`1,823`
- [patruff/ollama-mcp-bridge](https://github.com/patruff/ollama-mcp-bridge) — Bridge between Ollama and MCP servers, enabling local LLMs to use Model Context Protocol tools ☆`984`
- [DMontgomery40/deepseek-mcp-server](https://github.com/DMontgomery40/deepseek-mcp-server) — MCP server for DeepSeek language models ☆`362`
- [nesquikm/mcp-rubber-duck](https://github.com/nesquikm/mcp-rubber-duck) — MCP bridge to query multiple OpenAI-compatible LLMs ☆`180`
- [pyroprompts/any-chat-completions-mcp](https://github.com/pyroprompts/any-chat-completions-mcp) — MCP Server for using any LLM as a Tool ☆`166`
- [eLyiN/gemini-bridge](https://github.com/eLyiN/gemini-bridge) — Bridge AI agents to Google Gemini via CLI ☆`99`
- [elvismdev/mem0-mcp-selfhosted](https://github.com/elvismdev/mem0-mcp-selfhosted) — Self-hosted mem0 MCP server for Claude Code. Run a complete memory server against self-hosted Qdrant + Neo4j + Ollama while using Claude as the main LLM. ☆`112`
- [choplin/mcp-gemini-cli](https://github.com/choplin/mcp-gemini-cli) — MCP server for Gemini CLI integration ☆`100`
- [spranab/brainstorm-mcp](https://github.com/spranab/brainstorm-mcp) — A single model's confident answer can still be wrong, so brainstorm-mcp runs multi-round debates between GPT, Gemini, DeepSeek, Claude, and local Ollama models and returns a ☆`72`
- [pierrebrunelle/mcp-server-openai](https://github.com/pierrebrunelle/mcp-server-openai) — Query OpenAI models from Claude via MCP ☆`84`
- [merterbak/Grok-MCP](https://github.com/merterbak/Grok-MCP) — MCP server for xAI Grok API with tool calling and vision ☆`54`
- [mzxrai/mcp-openai](https://github.com/mzxrai/mcp-openai) — Chat with OpenAI models from Claude Desktop ☆`77`
- [ruixingshi/deepseek-thinker-mcp](https://github.com/ruixingshi/deepseek-thinker-mcp) — DeepSeek reasoning for MCP-enabled clients ☆`69`
- [kamelirzouni/MCP-server-Deepseek_R1](https://github.com/kamelirzouni/MCP-server-Deepseek_R1) — Connect Claude Desktop with DeepSeek ☆`68`
- [vixl-ai/vixl](https://github.com/vixl-ai/vixl) — Local-first desktop coding agent with BYOK, MCP, and OpenAI-compatible / Ollama hosts ☆`22`
- [JamesANZ/cross-llm-mcp](https://github.com/JamesANZ/cross-llm-mcp) — ChatGPT, Claude, Gemini, Mistral, Kimi, and DeepSeek APIs ☆`17`
- [HyperbolicLabs/hyperbolic-mcp](https://github.com/HyperbolicLabs/hyperbolic-mcp) — MCP Server for Claude ☆`17`
- [andybrandt/mcp-simple-openai-assistant](https://github.com/andybrandt/mcp-simple-openai-assistant) — Use OpenAI GPTs assistants from Claude ☆`39`
- [emgeee/mcp-ollama](https://github.com/emgeee/mcp-ollama) — Query model running with Ollama from within Claude Desktop or other MCP clients ☆`34`
- [billster45/mcp-chatgpt-responses](https://github.com/billster45/mcp-chatgpt-responses) — MCP server for OpenAI ChatGPT API with Responses API ☆`25`
- [kamelirzouni/MCP-server-Qwen_Max](https://github.com/kamelirzouni/MCP-server-Qwen_Max) — MCP server for Qwen Max model ☆`24`
## Location & Maps

### GIS

- [jjsantos01/qgis_mcp](https://github.com/jjsantos01/qgis_mcp) — QGIS Desktop control for language models ☆`1,146`
- [mahdin75/gis-mcp](https://github.com/mahdin75/gis-mcp) — MCP server connecting LLMs to GIS capabilities ☆`202`
- [mahdin75/geoserver-mcp](https://github.com/mahdin75/geoserver-mcp) — GeoServer geospatial integration ☆`96`
- [JordanGunn/gdal-mcp](https://github.com/JordanGunn/gdal-mcp) — Geospatial analysis with epistemic reasoning ☆`84`
- [BnJam/stac-mcp](https://github.com/BnJam/stac-mcp) — An MCP Server for STAC requests ☆`20`
- [webcoderz/MCP-Geo](https://github.com/webcoderz/MCP-Geo) — Geocoding MCP server with GeoPY! ☆`34`
### IP Geolocation

- [briandconnelly/mcp-server-ipinfo](https://github.com/briandconnelly/mcp-server-ipinfo) — IP Geolocation Server for MCP using ipinfo.io ☆`45`
- [ip2location/mcp-ip2location-io](https://github.com/ip2location/mcp-ip2location-io) — IP Geolocation MCP server using IP2Location.io API ☆`16`
- [iplocate/mcp-server-iplocate](https://github.com/iplocate/mcp-server-iplocate) — IP geolocation, proxy detection via IPLocate.io API ☆`20`
### Maps & Navigation

- [cablate/mcp-google-map](https://github.com/cablate/mcp-google-map) — 18 Google Maps tools and 3 Agent Skills for place search, routes, travel planning, and local SEO-via MCP or standalone CLI. ☆`488`
- [baidu-maps/mcp](https://github.com/baidu-maps/mcp) — Baidu Map MCP Server ☆`447`
- [mapbox/mcp-server](https://github.com/mapbox/mcp-server) — Mapbox Model Context Protocol (MCP) server ☆`365`
- [jagan-shanmugam/open-streetmap-mcp](https://github.com/jagan-shanmugam/open-streetmap-mcp) — MCP server for OpenStreetMap data ☆`231`
- [gaopengbin/cesium-mcp](https://github.com/gaopengbin/cesium-mcp) — Protocol-agnostic CesiumJS AI control runtime for MCP, WebMCP, function calling, and browser agents. ☆`149`
- [tomtom-international/tomtom-maps-mcp](https://github.com/tomtom-international/tomtom-maps-mcp) — TomTom location, search, routing ☆`59`
- [Knight60/ArcGIS-Pro-MCP](https://github.com/Knight60/ArcGIS-Pro-MCP) — ArcGIS Pro add-in that speaks the Model Context Protocol, so an AI assistant can drive your open project in plain language - 112 tools, every geoprocessing tool, and arbitrary ☆`58`
- [muend/arcgis-mcp-bridge](https://github.com/muend/arcgis-mcp-bridge) — Secure, local-first MCP server exposing ArcGIS Pro's ArcPy engine over stdio JSON-RPC. ☆`24`
- [stadiamaps/stadiamaps-mcp-server-ts](https://github.com/stadiamaps/stadiamaps-mcp-server-ts) — Stadia Maps API integration in TypeScript ☆`25`
- [kukapay/nearby-search-mcp](https://github.com/kukapay/nearby-search-mcp) — Nearby place search with IP-based location ☆`22`
### Weather

- [isdaniel/mcp_weather_server](https://github.com/isdaniel/mcp_weather_server) — Weather info via Open-Meteo API ☆`61`
- [caiyunapp/mcp-caiyun-weather](https://github.com/caiyunapp/mcp-caiyun-weather) — A Model Context Protocol (MCP) server for Caiyun (ColorfulClouds) Weather. ☆`48`
- [vikramgorla/mcp-swiss](https://github.com/vikramgorla/mcp-swiss) — Swiss open data MCP server - transport, weather, geodata, companies, etc,. Zero API keys. ☆`25`
- [adhikasp/mcp-weather](https://github.com/adhikasp/mcp-weather) — MCP server that provides hourly weather forecasts using the AccuWeather API ☆`38`
- [TimLukaHorstmann/mcp-weather](https://github.com/TimLukaHorstmann/mcp-weather) — AccuWeather hourly and daily forecasts ☆`34`
- [sjanaX01/weather-mcp-server](https://github.com/sjanaX01/weather-mcp-server) — A simple minimal weather mcp server :) ☆`24`
- [mschneider82/mcp-openweather](https://github.com/mschneider82/mcp-openweather) — mcp server for openweather free api ☆`22`
## MCP Clients

- [lobehub/lobehub](https://github.com/lobehub/lobehub) — LobeHub is your Chief Agent Operator, organizing your agents into 7×24 operations by hiring, scheduling, and reporting on your entire AI team. ☆`83,869`
- [aaif-goose/goose](https://github.com/aaif-goose/goose) — an open source, extensible AI agent that goes beyond code suggestions - install, execute, edit, and test with any LLM ☆`56,224`
- [LibreChat-AI/LibreChat](https://github.com/LibreChat-AI/LibreChat) — Enhanced ChatGPT Clone: Features Agents, MCP, Skills, DeepSeek, Anthropic, AWS, OpenAI, Responses API, Azure, Groq, o1, GPT-5, Mistral, OpenRouter, Vertex AI, Gemini, Artifacts, ☆`46,739`
- [Upsonic/Upsonic](https://github.com/Upsonic/Upsonic) — Build autonomous AI agents in Python. ☆`7,969`
- [genkit-ai/genkit](https://github.com/genkit-ai/genkit) — AI app framework for JavaScript and Go ☆`6,565`
- [ThinkInAIXYZ/deepchat](https://github.com/ThinkInAIXYZ/deepchat) — DeepChat - A smart assistant that connects powerful AI to your personal world ☆`6,383`
- [nanbingxyz/5ire](https://github.com/nanbingxyz/5ire) — 5ire is a cross-platform desktop AI assistant, MCP client. It compatible with major service providers, supports local knowledge base and tools via model context protocol servers . ☆`5,373`
- [srbhptl39/MCP-SuperAssistant](https://github.com/srbhptl39/MCP-SuperAssistant) — Brings MCP to ChatGPT, DeepSeek, Perplexity, Grok, Gemini, Google AI Studio, OpenRouter, DeepSeek, T3 Chat and more... ☆`2,627`
- [daodao97/chatmcp](https://github.com/daodao97/chatmcp) — ChatMCP is an AI chat client implementing the Model Context Protocol (MCP). ☆`2,223`
- [NitroRCr/AIaW](https://github.com/NitroRCr/AIaW) — AI as Workspace - An elegant AI chat client. Full-featured, lightweight. Support multiple workspaces, plugin system, cross-platform, local first + real-time cloud sync, ☆`1,841`
- [ravitemer/mcphub.nvim](https://github.com/ravitemer/mcphub.nvim) — MCP client for Neovim with intuitive server management ☆`1,790`
- [CopilotKit/open-mcp-client](https://github.com/CopilotKit/open-mcp-client) — A self-hosted, open-source client for the Model Context Protocol (MCP), enabling users to chat with any MCP server within their own app. It serves as a bridge for integrating... ☆`1,651`
- [ASCIT31/Dark-Moon](https://github.com/ASCIT31/Dark-Moon) — Autonomous pentest host for 80+ security tools ☆`1,200`
- [SecretiveShell/MCP-Bridge](https://github.com/SecretiveShell/MCP-Bridge) — OpenAI-compatible endpoint calling MCP tools ☆`922`
- [aeonfun/aeon](https://github.com/aeonfun/aeon) — GitHub Actions agents with OAuth to remote MCP servers ☆`787`
- [xark-argo/argo](https://github.com/xark-argo/argo) — ARGO is an open-source AI Agent platform that brings Local Manus to your desktop. With one-click model downloads, seamless closed LLM integration, and offline-first RAG knowledge ☆`832`
- [BigSweetPotatoStudio/HyperChat](https://github.com/BigSweetPotatoStudio/HyperChat) — HyperChat is a Chat client that strives for openness, utilizing APIs from various LLMs to achieve the best Chat experience, as well as implementing productivity tools through the ☆`708`
- [swarmclawai/swarmclaw](https://github.com/swarmclawai/swarmclaw) — Open-source self-hosted AI agent runtime and multi-agent framework for autonomous agent swarms. Agent memory, MCP tools, schedules, delegation, and 23+ LLM providers (Claude, ☆`704`
- [mario-andreschak/FLUJO](https://github.com/mario-andreschak/FLUJO) — Local visual agent builder with MCP and multi-model chat ☆`673`
- [truffle-ai/dexto](https://github.com/truffle-ai/dexto) — Agent harness and tookit for building AI agents and agentic applications. CLI and SDKs included ☆`660`
- [adhikasp/mcp-client-cli](https://github.com/adhikasp/mcp-client-cli) — A simple CLI to run LLM prompt and implement MCP client. ☆`675`
- [QuixiAI/dolphin-mcp](https://github.com/QuixiAI/dolphin-mcp) — Dolphin-MCP is an open-source multi-server bridging client for MCP. It allows you to connect any MCP-compatible server any LLM (local or remote), enabling flexible tool... ☆`533`
- [Muvon/octomind](https://github.com/Muvon/octomind) — Open-source AI coding agent and agent runtime: one binary, any model, MCP-native. Runs in terminal, CI, or as a daemon. ☆`478`
- [Lucassssss/eechat](https://github.com/Lucassssss/eechat) — Local AI chat application ☆`351`
- [supercorp-ai/superinterface](https://github.com/supercorp-ai/superinterface) — Superinterface is an AI assistants library for building AI capabilities into your app or website. You use React components and hooks to build AI-first assistants-based interfaces ☆`346`
- [3choff/mcp-chatbot](https://github.com/3choff/mcp-chatbot) — CLI chatbot with MCP integration demo ☆`251`
- [EvalsOne/MCP-connect](https://github.com/EvalsOne/MCP-connect) — Cloud AI access to local Stdio MCP servers ☆`240`
- [autohandai/code-cli](https://github.com/autohandai/code-cli) — Open-source terminal coding agent. Use 15+ model providers, local models or your own key. Plan mode before edits. Imports your Codex, Cursor, Claude Code setup. ☆`216`
- [AI-QL/chat-mcp](https://github.com/AI-QL/chat-mcp) — Desktop chat app with MCP support ☆`239`
- [benord-labs/frink](https://github.com/benord-labs/frink) — Desktop-first app for parallel agents and triggered multi-step workflows ☆`183`
- [johannesbrandenburger/typst-mcp](https://github.com/johannesbrandenburger/typst-mcp) — MCP server for Typst markup-based typesetting system ☆`186`
- [3dify-project/dify-mcp-client](https://github.com/3dify-project/dify-mcp-client) — MCP Client as an Agent Strategy Plugin. Support GUI operation via UI-TARS-SDK. ☆`172`
- [aofp/yume](https://github.com/aofp/yume) — Native desktop UI for Claude Code with orchestration, streaming, background agents, and multi-provider support. Built with Tauri + React. ☆`151`
- [off-grid-ai/OGAD](https://github.com/off-grid-ai/OGAD) — On-device MCP client for Mac with a local LLM ☆`142`
- [sooperset/mcp-client-slackbot](https://github.com/sooperset/mcp-client-slackbot) — Simple Slackbot MCP Client ☆`163`
- [yincongcyincong/mcp-client-go](https://github.com/yincongcyincong/mcp-client-go) — mcp client for Go (Golang). Integrate multiple Model Context Protocol (MCP) servers ☆`150`
- [SylphAI-Inc/adal-cli](https://github.com/SylphAI-Inc/adal-cli) — The automation-first agent harness. Every coding agent can build - AdaL does GTM directly from your codebase. ☆`111`
- [tanaikech/ToolsForMCPServer](https://github.com/tanaikech/ToolsForMCPServer) — MCP server built with Google Apps Script for Gemini CLI ☆`108`
- [ckanthony/gin-mcp](https://github.com/ckanthony/gin-mcp) — Enable MCP features for any Gin API with a line of code ☆`85`
- [nick1udwig/kibitz](https://github.com/nick1udwig/kibitz) — The coding agent for professionals ☆`111`
- [taskade/taskade](https://github.com/taskade/taskade) — Public docs, comparisons, and clone-ready kits for the AI-native workspace. Not the product source - issues welcome. ☆`73`
- [xzq-xu/jvm-mcp-server](https://github.com/xzq-xu/jvm-mcp-server) — JVM-based MCP server implementation ☆`91`
- [apify/tester-mcp-client](https://github.com/apify/tester-mcp-client) — Model Context Protocol (MCP) Client for Apify's Actors ☆`80`
- [Xingsandesu/CarrotAI](https://github.com/Xingsandesu/CarrotAI) — CarrotAI is a cutting-edge AI agent application that delivers real-time streaming chat via Server-Sent Events (SSE) with built-in Model Control Protocol (MCP) integration. It ☆`86`
- [n00bvn/CanvasMCPClient](https://github.com/n00bvn/CanvasMCPClient) — Canvas MCP Client is an open-source, self-hostable dashboard application built around an infinite, zoomable, and pannable canvas. It provides a unified interface for interacting ☆`78`
- [seekrays/seekchat](https://github.com/seekrays/seekchat) — A Sleek and Powerful AI Desktop Assistant that supports MCP integration ☆`65`
- [zacharypodbela/django-rest-framework-mcp](https://github.com/zacharypodbela/django-rest-framework-mcp) — MCP server for Django REST Framework ☆`54`
- [php-mcp/client](https://github.com/php-mcp/client) — Core PHP implementation for the Model Context Protocol (MCP) Client ☆`58`
- [jdbcx/jdbcx](https://github.com/jdbcx/jdbcx) — JDBCX: Extended JDBC driver for dynamic multi-language queries with optional bridge server for federated datasource connectivity. ☆`33`
- [rakesh-eltropy/mcp-client](https://github.com/rakesh-eltropy/mcp-client) — REST API and CLI client for MCP with LangChain ☆`49`
- [LeulAria/volt](https://github.com/LeulAria/volt) — AI code editor on VS Code core with MCP client support and ACP coding agents ☆`20`
- [gcc3/simple-ai-chat](https://github.com/gcc3/simple-ai-chat) — AI chat application based on large language models (LLMs), supports web and command-line interfaces. ☆`16`
- [vincent-pli/mcp-cli-host](https://github.com/vincent-pli/mcp-cli-host) — A command-line interface (CLI) host platform that facilitates interactions between Large Language Models and external tools via the Model Context Protocol (MCP). ☆`21`
- [shane-kercheval/mcp-client-agent](https://github.com/shane-kercheval/mcp-client-agent) — CLI that uses DSPy to interact with MCP servers. ☆`24`
- [johnrobinsn/askit](https://github.com/johnrobinsn/askit) — LLM Function Calling Library and CLI with Support for MCP Servers ☆`21`
## Marketing & Analytics

- [nowork-studio/notfair-plugin](https://github.com/nowork-studio/notfair-plugin) — Open-source SEO, GEO, and marketing skills for AI agents. ☆`4,111`
- [nowork-studio/notfair-plugin](https://github.com/nowork-studio/notfair-plugin) — Google Ads diagnosis, recommendations, and edits ☆`4,111`
- [nowork-studio/notfair-plugin](https://github.com/nowork-studio/notfair-plugin) — SEO, GEO, ads, Search Console, and Analytics skills ☆`4,106`
- [pipeboard-co/meta-ads-mcp](https://github.com/pipeboard-co/meta-ads-mcp) — Hosted Facebook and Instagram Ads for AI agents ☆`1,349`
- [getopenpost/openpost](https://github.com/getopenpost/openpost) — Create, adapt, schedule, and track social posts. Open-source, hosted or self-hosted. ☆`865`
- [gomarble-ai/facebook-ads-mcp-server](https://github.com/gomarble-ai/facebook-ads-mcp-server) — Facebook and Instagram Ads management ☆`368`
- [proxy-intell/facebook-ads-library-mcp](https://github.com/proxy-intell/facebook-ads-library-mcp) — Facebook Ads Library search and access ☆`321`
- [open-strategy-partners/osp_marketing_tools](https://github.com/open-strategy-partners/osp_marketing_tools) — MCP server for marketing automation tools ☆`274`
- [stape-io/google-tag-manager-mcp-server](https://github.com/stape-io/google-tag-manager-mcp-server) — MCP server for Google Tag Manager ☆`243`
- [surendranb/google-analytics-mcp](https://github.com/surendranb/google-analytics-mcp) — Google Analytics 4 data access ☆`244`
- [cnych/seo-mcp](https://github.com/cnych/seo-mcp) — SEO tool based on Ahrefs data ☆`260`
- [gomarble-ai/google-ads-mcp-server](https://github.com/gomarble-ai/google-ads-mcp-server) — Google Ads performance data analysis ☆`146`
- [microsoft/clarity-mcp-server](https://github.com/microsoft/clarity-mcp-server) — Microsoft Clarity integration ☆`137`
- [amekala/ads-mcp](https://github.com/amekala/ads-mcp) — Google, Meta, LinkedIn, and TikTok campaign management ☆`106`
- [mikusnuz/meta-ads-mcp](https://github.com/mikusnuz/meta-ads-mcp) — MCP server for Meta Marketing API v25.0 - 135 tools for Facebook & Instagram ad campaign management ☆`93`
- [bzsasson/screaming-frog-mcp](https://github.com/bzsasson/screaming-frog-mcp) — Headless MCP server for Screaming Frog SEO Spider - run crawls, export and analyze crawl data via the CLI. Small locked-down tool surface for scheduled audits, CI, and unattended ☆`94`
- [AdsMCP/tiktok-ads-mcp-server](https://github.com/AdsMCP/tiktok-ads-mcp-server) — TikTok Ads Marketing API integration via MCP ☆`54`
- [builtwith/builtwith-mcp](https://github.com/builtwith/builtwith-mcp) — BuiltWith MCP Server ☆`43`
- [AKzar1el/mcp-geo](https://github.com/AKzar1el/mcp-geo) — Track brand citations across seven AI search surfaces. Free OSS/self-host; optional EUR 99 client-ready audit. ☆`40`
- [gvaibhav/TAM-MCP-Server](https://github.com/gvaibhav/TAM-MCP-Server) — Market sizing and TAM/SAM analysis ☆`36`
- [MarketplaceAdPros/amazon-ads-mcp-server](https://github.com/MarketplaceAdPros/amazon-ads-mcp-server) — MCP Server to interact with Amazon Ads ☆`29`
- [brandu-mos/konquest-meta-ads-mcp](https://github.com/brandu-mos/konquest-meta-ads-mcp) — 57-tool supervised Meta Ads MCP server for Claude Code. Open-core: full CRUD, multi-asset ads, targeting, diagnostics, safety gates. Premium adds 41 tools: optimization engine, ☆`44`
- [alexey-pelykh/lhremote](https://github.com/alexey-pelykh/lhremote) — CLI and MCP server for LinkedHelper automation - let AI assistants control LinkedIn outreach ☆`20`
- [Synter-Media-AI/mcp-server](https://github.com/Synter-Media-AI/mcp-server) — Open-source MCP server for AI agents: read across 43 ad platforms, with verified write and create across 16 core platforms (Google, Meta, LinkedIn, Microsoft, Reddit, TikTok, X, ☆`21`
- [stape-io/stape-mcp-server](https://github.com/stape-io/stape-mcp-server) — Stape API for Claude, Cursor, and other AI clients ☆`18`
- [Kiran1689/storyblok-mcp-server](https://github.com/Kiran1689/storyblok-mcp-server) — MCP server for Storyblok CMS management ☆`41`
- [damientilman/mailchimp-mcp-server](https://github.com/damientilman/mailchimp-mcp-server) — The most complete Mailchimp Marketing API MCP server: 227 tools across campaigns, audiences, reports, segments, automations and full e-commerce, with multi-account support and ☆`25`
- [rafaelstz/adobe-commerce-dev-mcp](https://github.com/rafaelstz/adobe-commerce-dev-mcp) — Adobe Commerce Dev MCP Server ☆`27`
- [MatiousCorp/google-ad-manager-mcp](https://github.com/MatiousCorp/google-ad-manager-mcp) — MCP server for Google Ad Manager. Manage ad campaigns, orders, line items, and creatives through AI assistants like Claude, ChatGPT, Gemini, Cursor, and VS Code. Automate your ad ☆`20`
- [jonathan-politzki/smartlead-mcp-server](https://github.com/jonathan-politzki/smartlead-mcp-server) — Smartlead MCP deployment ☆`18`
## Media Processing

### 3D & Animation

- [samuelgursky/davinci-resolve-mcp](https://github.com/samuelgursky/davinci-resolve-mcp) — MCP server integration for DaVinci Resolve Studio ☆`3,916`
- [ATH-MaaS/Pixelle-MCP](https://github.com/ATH-MaaS/Pixelle-MCP) — Multimodal AIGC with ComfyUI + MCP ☆`1,131`
- [diivi/aseprite-mcp](https://github.com/diivi/aseprite-mcp) — MCP server for interacting with the Aseprite API ☆`879`
- [abhiemj/manim-mcp-server](https://github.com/abhiemj/manim-mcp-server) — Manim animation code execution ☆`656`
- [8beeeaaat/touchdesigner-mcp](https://github.com/8beeeaaat/touchdesigner-mcp) — MCP server for TouchDesigner ☆`612`
- [mhyrr/sketchup-mcp](https://github.com/mhyrr/sketchup-mcp) — Sketchup Model Context Protocol ☆`531`
- [dylanroscover/Embody](https://github.com/dylanroscover/Embody) — TouchDesigner MCP server with 70 tools and diffable network export ☆`211`
- [PatrickPalmer/MayaMCP](https://github.com/PatrickPalmer/MayaMCP) — Autodesk Maya 3D integration ☆`120`
- [pranav-deshmukh/blender-mcp](https://github.com/pranav-deshmukh/blender-mcp) — Blender 3D modeling integration ☆`98`
- [FishWoWater/trellis_blender](https://github.com/FishWoWater/trellis_blender) — Blender plugin for TRELLIS and TRELLIS.2 (3D AIGC Model, Text-to-3D, Image-to-3D) ☆`77`
- [BearNetwork-BRNKC/SketchUp-MCP](https://github.com/BearNetwork-BRNKC/SketchUp-MCP) — SketchUp-MCP For AI ☆`28`
- [wilsonchenghy/ShaderToy-MCP](https://github.com/wilsonchenghy/ShaderToy-MCP) — Create and explore GLSL shaders on ShaderToy ☆`50`
- [junmer/mcp-server-lottiefiles](https://github.com/junmer/mcp-server-lottiefiles) — Search and retrieve Lottie animations from LottieFiles ☆`19`
### Audio & Music

- [ahujasid/ableton-mcp](https://github.com/ahujasid/ableton-mcp) — Control Ableton Live with any LLM: create tracks, arrange clips & compose music via MCP ☆`3,296`
- [varunneal/spotify-mcp](https://github.com/varunneal/spotify-mcp) — MCP to connect your LLM with Spotify. ☆`614`
- [marcelmarais/spotify-mcp-server](https://github.com/marcelmarais/spotify-mcp-server) — Lightweight MCP server for Spotify ☆`496`
- [Simon-Kansara/ableton-live-mcp-server](https://github.com/Simon-Kansara/ableton-live-mcp-server) — Ableton Live OSC control ☆`397`
- [adamjmurray/producer-pal](https://github.com/adamjmurray/producer-pal) — AI music production assistant for Ableton Live ☆`359`
- [tiianhk/MaxMSP-MCP-Server](https://github.com/tiianhk/MaxMSP-MCP-Server) — MCP (Model Context Protocol) Server for Max (Max/MSP/Jitter) ☆`285`
- [dschuler36/reaper-mcp-server](https://github.com/dschuler36/reaper-mcp-server) — An MCP Server for interacting with Reaper projects. ☆`135`
- [rosasynthesiz/flstudio-mcp](https://github.com/rosasynthesiz/flstudio-mcp) — AI-powered FL Studio control via the Model Context Protocol. Beyond piano-roll notes - full in-DAW mixing (Mix Doctor, gain staging, EQ/comp/reverb, reference matching), routing, ☆`127`
- [xDarkzx/Reaper-MCP](https://github.com/xDarkzx/Reaper-MCP) — AI-powered music production and post-production in REAPER via MCP - 181 tools for composition, mixing, mastering, batch editing, audio QC, and ReaScript automation. ☆`112`
- [TwelveTake-Studios/reaper-mcp](https://github.com/TwelveTake-Studios/reaper-mcp) — REAPER DAW mixing, mastering, MIDI, and production ☆`102`
- [SkyworkAI/Mureka-mcp](https://github.com/SkyworkAI/Mureka-mcp) — AI lyrics, song, and music generation ☆`123`
- [AceDataCloud/SunoMCP](https://github.com/AceDataCloud/SunoMCP) — MCP server for Suno AI music generation, lyrics, and cover workflows via Ace Data Cloud. ☆`72`
- [imprvhub/mcp-claude-spotify](https://github.com/imprvhub/mcp-claude-spotify) — Spotify interaction for Claude Desktop ☆`53`
- [vsaez/mcp-spotify-player](https://github.com/vsaez/mcp-spotify-player) — MCP server to manage Spotify from MCP clients ☆`22`
### Image Generation

- [jau123/MeiGen-AI-Design-MCP](https://github.com/jau123/MeiGen-AI-Design-MCP) — Discover inspiration and create images and videos with the latest AI models. Works with ChatGPT, Claude, Cursor, and other MCP clients. ☆`1,797`
- [glifxyz/glif-mcp-server](https://github.com/glifxyz/glif-mcp-server) — Glif's hosted MCP server, plugin and skills for creating images, video and audio. Works with Claude, ChatGPT, Codex, Cursor and more. ☆`218`
- [shinpr/mcp-image](https://github.com/shinpr/mcp-image) — AI image generation with Gemini 3 ☆`187`
- [awkoy/replicate-flux-mcp](https://github.com/awkoy/replicate-flux-mcp) — MCP server for Replicate Flux image and SVG generation ☆`106`
- [GenWaveLLC/svgmaker-mcp](https://github.com/GenWaveLLC/svgmaker-mcp) — MCP server for SVG generation ☆`88`
- [apinetwork/piapi-mcp-server](https://github.com/apinetwork/piapi-mcp-server) — PiAPI media: Midjourney, Flux, Kling ☆`75`
- [Flyworks-AI/flyworks-mcp](https://github.com/Flyworks-AI/flyworks-mcp) — Fast and free zeroshot lipsync MCP server ☆`94`
- [hamflx/imagen3-mcp](https://github.com/hamflx/imagen3-mcp) — MCP server for Google Imagen 3 image generation ☆`78`
- [WaveSpeedAI/mcp-server](https://github.com/WaveSpeedAI/mcp-server) — Image and video generation with WaveSpeed AI ☆`36`
- [MohamedAbdallah-14/prompt-to-asset](https://github.com/MohamedAbdallah-14/prompt-to-asset) — Images from 30+ models through one API ☆`24`
- [InhiblabCore/mcp-image-compression](https://github.com/InhiblabCore/mcp-image-compression) — High-performance image compression service ☆`34`
- [zxkane/mcp-server-amazon-bedrock](https://github.com/zxkane/mcp-server-amazon-bedrock) — Amazon Bedrock Nova Canvas image generation ☆`25`
### Image Processing

- [openclaw/Peekaboo](https://github.com/openclaw/Peekaboo) — macOS screenshot and window capture MCP server ☆`5,426`
- [BeatAPI/BeatDesign](https://github.com/BeatAPI/BeatDesign) — Local-first AI canvas and timeline. Any MCP agent. Open-source alternative to Higgsfield. ☆`327`
- [sunriseapps/imagesorcery-mcp](https://github.com/sunriseapps/imagesorcery-mcp) — Image processing operations ☆`335`
- [royshil/obs-mcp](https://github.com/royshil/obs-mcp) — An MCP server for OBS ☆`158`
- [IDEA-Research/DINO-X-MCP](https://github.com/IDEA-Research/DINO-X-MCP) — MCP server for DINO-X vision model ☆`111`
- [drolosoft/immich-photo-manager](https://github.com/drolosoft/immich-photo-manager) — MCP server and Claude Code plugin for self-hosted Immich: CLIP and OCR search, geographic albums, duplicates, people and faces, metadata repair, PDF photobooks. 94 tools, tested ☆`62`
- [upnorthmedia/ScreenshotMCP](https://github.com/upnorthmedia/ScreenshotMCP) — Website screenshot capture and optimization ☆`62`
- [groundlight/mcp-vision](https://github.com/groundlight/mcp-vision) — Computer vision models as MCP servers ☆`63`
- [screenshotone/mcp](https://github.com/screenshotone/mcp) — A CLI version of an MCP server for the ScreenshotOne API ☆`38`
- [spencerhhubert/illustrator-mcp-server](https://github.com/spencerhhubert/illustrator-mcp-server) — mcp server to run scripts on adobe illustrator ☆`57`
- [a-y-ibrahim/after-effects-mcp](https://github.com/a-y-ibrahim/after-effects-mcp) — MCP server for controlling Adobe After Effects from AI clients (Claude, etc.) - ExtendScript execution, background rendering, deep project/layer inspection, and first-class ☆`29`
- [nota/gyazo-mcp-server](https://github.com/nota/gyazo-mcp-server) — Official Model Context Protocol server for Gyazo ☆`28`
- [saury1120/pdf-mcp](https://github.com/saury1120/pdf-mcp) — 一个强大的 PDF 处理 MCP（Model Context Protocol）服务，提供全面的 PDF 文档分析功能 ☆`51`
- [MoussaabBadla/code-screenshot-mcp](https://github.com/MoussaabBadla/code-screenshot-mcp) — Generate code screenshots ☆`44`
- [stass/exif-mcp](https://github.com/stass/exif-mcp) — MCP server to extract image metadata (EXIF, XMP, etc) ☆`40`
- [editmamei/editmamei](https://github.com/editmamei/editmamei) — Editmamei: Photoshop MCP server for natural-language AI photo editing. ☆`16`
- [torrentclaw/torrentclaw-mcp](https://github.com/torrentclaw/torrentclaw-mcp) — The official MCP by TorrentClaw.com ☆`16`
- [magarcia/mcp-server-giphy](https://github.com/magarcia/mcp-server-giphy) — Giphy GIF integration ☆`36`
- [kazuph/mcp-screenshot](https://github.com/kazuph/mcp-screenshot) — Repository for MCP screenshot functionality ☆`23`
- [flowy11/imagician](https://github.com/flowy11/imagician) — A MCP server for image edition ☆`19`
- [bmorphism/say-mcp-server](https://github.com/bmorphism/say-mcp-server) — MCP server for macOS text-to-speech functionality ☆`20`
### Media Services

- [garylab/pexels-mcp-server](https://github.com/garylab/pexels-mcp-server) — A Pexels MCP Server for Images and Videos searching ☆`27`
### Video

- [ronak-create/FableCut](https://github.com/ronak-create/FableCut) — Zero-dependency browser video editor that AI agents can drive - JSON timeline, MCP + REST, live-reloading UI ☆`778`
- [eat-pray-ai/yutu](https://github.com/eat-pray-ai/yutu) — CLI, MCP server, and AI agent to automate YouTube workflows ☆`712`
- [ZubeidHendricks/youtube-mcp-server](https://github.com/ZubeidHendricks/youtube-mcp-server) — YouTube API and video management ☆`593`
- [kimtaeyoon83/mcp-server-youtube-transcript](https://github.com/kimtaeyoon83/mcp-server-youtube-transcript) — YouTube video transcript downloader ☆`603`
- [anaisbetts/mcp-youtube](https://github.com/anaisbetts/mcp-youtube) — A Model-Context Protocol Server for YouTube ☆`552`
- [ffroliva/gflow-cli](https://github.com/ffroliva/gflow-cli) — Drive Google Flow from the command line: Veo video and Imagen images, scripted, batched and pipeline-ready. Ships an MCP server so coding agents can drive it too, giving you and ☆`358`
- [WeftCut/WeftCut](https://github.com/WeftCut/WeftCut) — Free, open-source AI video editor for macOS, Windows and Linux - drive the whole timeline from any MCP client. ☆`310`
- [guaardvark/guaardvark](https://github.com/guaardvark/guaardvark) — Self-hosted AI studio on your own GPU: chat with your files (RAG), screen and browser agents, coding swarms, LoRA training, an MCP server for Claude Code and Cursor, and local ☆`299`
- [burningion/video-editing-mcp](https://github.com/burningion/video-editing-mcp) — MCP Interface for Video Jungle ☆`295`
- [KyaniteLabs/kinocut](https://github.com/KyaniteLabs/kinocut) — Guardrailed video editing MCP server for AI agents. FFmpeg, Hyperframes, repurposing tools, Python client, and CLI. Local, fast, free. ☆`244`
- [Cassette-Editor/oh-my-cassette](https://github.com/Cassette-Editor/oh-my-cassette) — 你的随身 AI 剪辑搭档 | Pocket AI co-editor for video montage - AI video editing plugin & MCP server for Claude Code, Codex, Hermes & OpenCode ☆`217`
- [muxinc/mux-ts](https://github.com/muxinc/mux-ts) — Mux Video and Data API wrapper ☆`182`
- [video-creator/ffmpeg-mcp](https://github.com/video-creator/ffmpeg-mcp) — Using ffmpeg command line to achieve an mcp server, can be very convenient, through the dialogue to achieve the local video search, tailoring, stitching, playback,clip, overlay, ☆`153`
- [DareDev256/fcp-mcp-server](https://github.com/DareDev256/fcp-mcp-server) — MCP server for Final Cut Pro XML. Lets Claude read, edit and generate real timelines: cut detection, markers, roles, transcript-based editing. Published on PyPI as fcp-mcp-server. ☆`136`
- [guimatheus92/mcp-video-analyzer](https://github.com/guimatheus92/mcp-video-analyzer) — MCP server that turns any video - YouTube, Instagram, TikTok, Loom, X, Vimeo, direct URLs, local files - into transcripts, key frames, OCR text, and metadata for AI agents. ☆`111`
- [stabgan/openrouter-mcp-multimodal](https://github.com/stabgan/openrouter-mcp-multimodal) — MCP server for OpenRouter - chat with 300+ LLMs (Claude, Gemini, GPT), analyze images / audio / video, generate images / speech / music / video (Veo 3.1, Seedance, Kling, Wan) ☆`102`
- [arcmira/mcp](https://github.com/arcmira/mcp) — YouTube and podcast transcript search with timestamped sources; proprietary hosted MCP, Arcmira account required. [API docs](https://arcmira.com/docs). ☆`78`
- [Laksh-star/mcp-server-tmdb](https://github.com/Laksh-star/mcp-server-tmdb) — MCP Server with TMDB ☆`74`
- [tan-yong-sheng/ai-vision-mcp](https://github.com/tan-yong-sheng/ai-vision-mcp) — Image and video analysis capabilities ☆`80`
- [runapi-ai/mcp](https://github.com/runapi-ai/mcp) — RunAPI MCP server for model discovery, pricing lookup, media task creation, and balance checks. ☆`56`
- [luminarylane/fal-mcp-server](https://github.com/luminarylane/fal-mcp-server) — Fal.ai image, video, music generation ☆`61`
- [nabid-pf/youtube-video-summarizer-mcp](https://github.com/nabid-pf/youtube-video-summarizer-mcp) — YouTube video captions and summarization ☆`62`
- [video-db/agent-toolkit](https://github.com/video-db/agent-toolkit) — MCP toolkit for video database operations ☆`50`
- [marcindulak/stt-mcp-server-linux](https://github.com/marcindulak/stt-mcp-server-linux) — Local speech-to-text for Tmux on Linux ☆`24`
- [tubeagentkit/youtube-mcp](https://github.com/tubeagentkit/youtube-mcp) — Remote YouTube transcript, video/channel search, and playlist extraction, free tier ☆`24`
- [Aditya2755/video-edit-mcp](https://github.com/Aditya2755/video-edit-mcp) — Video and audio editing: trim, merge, effects, overlays, format conversion, audio processing and YouTube downloads, chaining steps without intermediate files. ☆`30`
- [maoxiaoke/mcp-media-processor](https://github.com/maoxiaoke/mcp-media-processor) — A Node.js server implementing Model Context Protocol (MCP) for media processing operations, providing powerful video and image manipulation capabilities. ☆`29`
- [omergocmen/json2video-mcp-server](https://github.com/omergocmen/json2video-mcp-server) — json2video API integration ☆`26`
- [sinjab/mcp_youtube_extract](https://github.com/sinjab/mcp_youtube_extract) — YouTube clip information extraction ☆`19`
- [TSavo/creatify-mcp](https://github.com/TSavo/creatify-mcp) — MCP server for AI video generation ☆`23`
- [13rac1/videocapture-mcp](https://github.com/13rac1/videocapture-mcp) — MCP server to capture images from webcam or video source ☆`20`
- [ananddtyagi/gif-creator-mcp](https://github.com/ananddtyagi/gif-creator-mcp) — MCP that allows you to take your video and turn it into a gif. ☆`18`
## Monitoring & Observability

- [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana) — MCP server for Grafana ☆`3,636`
- [getsentry/toolkit](https://github.com/getsentry/toolkit) — Agentic tooling for Sentry ☆`953`
- [0xKoda/WireMCP](https://github.com/0xKoda/WireMCP) — An MCP for WireShark (tshark). Empower LLM's with realtime network traffic analysis capability ☆`604`
- [Higangssh/homebutler](https://github.com/Higangssh/homebutler) — Tells you what changed on your server - only what's worth telling. Single Go binary, no database, nothing running on the machines it watches. MCP server built in. ☆`314`
- [mpeirone/zabbix-mcp-server](https://github.com/mpeirone/zabbix-mcp-server) — MCP server for Zabbix monitoring with 40+ tools ☆`260`
- [initMAX/zabbix-mcp-server](https://github.com/initMAX/zabbix-mcp-server) — MCP server for the complete Zabbix API - 237 tools, multi-server, OAuth 2.1 + bearer auth, PDF reports, systemd ready. Works with ChatGPT, Claude, VS Code, Codex, JetBrains and ☆`247`
- [VictoriaMetrics/mcp-victoriametrics](https://github.com/VictoriaMetrics/mcp-victoriametrics) — VictoriaMetrics monitoring integration ☆`242`
- [comet-ml/opik-mcp](https://github.com/comet-ml/opik-mcp) — MCP server for Opik LLM evaluation platform ☆`225`
- [aliyun/alibabacloud-observability-mcp-server](https://github.com/aliyun/alibabacloud-observability-mcp-server) — Facilitates seamless integration with Alibaba Cloud's observability products, offering tools for efficient log and application monitoring. ☆`171`
- [langfuse/mcp-server-langfuse](https://github.com/langfuse/mcp-server-langfuse) — MCP server for Langfuse LLM observability ☆`176`
- [pydantic/logfire-mcp](https://github.com/pydantic/logfire-mcp) — The Logfire MCP Server is here! ☆`162`
- [prometheus/prometheus-mcp](https://github.com/prometheus/prometheus-mcp) — MCP server for LLMs to interact with Prometheus ☆`134`
- [Necmttn/ax](https://github.com/Necmttn/ax) — Local observability for agent sessions, tools, and costs ☆`122`
- [avivsinai/langfuse-mcp](https://github.com/avivsinai/langfuse-mcp) — A Model Context Protocol (MCP) server for Langfuse, enabling AI agents to query Langfuse trace data for enhanced debugging and observability ☆`112`
- [ruslanlap/pagespeed-insights-mcp](https://github.com/ruslanlap/pagespeed-insights-mcp) — MCP server for Google PageSpeed Insights & Chrome UX Report APIs. Analyze, compare, and optimize web performance directly through Claude, Cursor, or any MCP-compatible AI client. ☆`78`
- [seekrays/mcp-monitor](https://github.com/seekrays/mcp-monitor) — MCP server monitoring tool ☆`91`
- [last9/last9-mcp-server](https://github.com/last9/last9-mcp-server) — Last9 MCP Server ☆`63`
- [andreisirbu91-lab/MCPSpend](https://github.com/andreisirbu91-lab/MCPSpend) — Real-time cost observability for Model Context Protocol (MCP) tool calls. Wraps any MCP server, attributes spend per tool/project/customer. Free tier 25K calls/mo. EU-hosted ☆`62`
- [8bitgentleman/activitywatch-mcp-server](https://github.com/8bitgentleman/activitywatch-mcp-server) — Model Context Protocol server for ActivityWatch time tracking data ☆`74`
- [mcpcap/mcpcap](https://github.com/mcpcap/mcpcap) — Network analysis for the AI age ☆`54`
- [GeLi2001/datadog-mcp-server](https://github.com/GeLi2001/datadog-mcp-server) — MCP server interacts with the official Datadog API ☆`70`
- [rootlyhq/rootly-mcp-server](https://github.com/rootlyhq/rootly-mcp-server) — Rootly MCP server ☆`45`
- [mhajder/librenms-mcp](https://github.com/mhajder/librenms-mcp) — MCP server for LibreNMS (network monitoring): devices, ports, inventory, locations and groups, alerts and alert rules, eventlog/syslog, graphs, billing, BGP/OSPF/VRF, ARP/FDB lookups, sensors, services and Oxidized configs. Read-only mode, tag-based tool filtering and rate limiting. ☆`42`
- [metoro-io/metoro-mcp-server](https://github.com/metoro-io/metoro-mcp-server) — Metoro MCP Server ☆`51`
- [RedHatInsights/insights-mcp](https://github.com/RedHatInsights/insights-mcp) — Red Hat Insights AI connection ☆`25`
- [MindscapeHQ/mcp-server-raygun](https://github.com/MindscapeHQ/mcp-server-raygun) — Raygun error investigation for AI ☆`31`
- [phuryn/staygreen](https://github.com/phuryn/staygreen) — Free uptime and incident monitoring for apps built with coding agents. Plus, public issues for staygreen.io ☆`30`
- [fclairamb/solidping](https://github.com/fclairamb/solidping) — Self-hostable uptime monitor with a built-in MCP server for checks, incidents and status pages ☆`29`
- [inspektor-gadget/ig-mcp-server](https://github.com/inspektor-gadget/ig-mcp-server) — Container and Kubernetes debugging with AI ☆`28`
- [mottibec/otelcol-mcp](https://github.com/mottibec/otelcol-mcp) — The OTEL MCP Server ☆`52`
- [ntk148v/alertmanager-mcp-server](https://github.com/ntk148v/alertmanager-mcp-server) — MCP server for Prometheus Alertmanager integration ☆`25`
- [agentkitai/agentlens](https://github.com/agentkitai/agentlens) — Open-source observability and audit trail platform for AI agents. MCP-native, tamper-evident event logging, real-time dashboard. ☆`25`
- [gologinapp/gologin-mcp](https://github.com/gologinapp/gologin-mcp) — Manage GoLogin browser profiles, proxies, and fingerprints ☆`24`
- [GeiserX/genieacs-mcp](https://github.com/GeiserX/genieacs-mcp) — MCP Server for GenieACS written in Go ☆`19`
- [VictoriaMetrics/mcp-victoriatraces](https://github.com/VictoriaMetrics/mcp-victoriatraces) — The implementation of Model Context Protocol (MCP) server for VictoriaTraces ☆`18`
- [emicklei/mcp-log-proxy](https://github.com/emicklei/mcp-log-proxy) — a web logging proxy for MCP client-server communication ☆`32`
- [tumf/grafana-loki-mcp](https://github.com/tumf/grafana-loki-mcp) — Grafana Loki MCP Repository ☆`29`
- [CaesarYangs/prometheus_mcp_server](https://github.com/CaesarYangs/prometheus_mcp_server) — A Model Context Protocol (MCP) server enabling LLMs to query, analyze, and interact with Prometheus databases through predefined routes. ☆`33`
- [tgeselle/bugsnag-mcp](https://github.com/tgeselle/bugsnag-mcp) — MCP server for Bugsnag error monitoring ☆`25`
- [Pratyay/mac-monitor-mcp](https://github.com/Pratyay/mac-monitor-mcp) — MCP server for macOS system monitoring ☆`23`
- [alilxxey/openobserve-community-mcp](https://github.com/alilxxey/openobserve-community-mcp) — MCP server for OpenObserve Community Edition via REST API. Read-only tools for searching logs, traces, stream schemas, and dashboards without requiring the Enterprise license. ☆`16`
- [iLert/mcp-ilert](https://github.com/iLert/mcp-ilert) — MCP server for ilert ☆`17`
## Productivity

### Atlassian

- [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) — MCP server for Atlassian tools (Confluence, Jira) ☆`6,080`
- [atlassian/atlassian-mcp-server](https://github.com/atlassian/atlassian-mcp-server) — Official remote MCP server for Atlassian. Securely connect Jira, Confluence, Jira Service Management, Bitbucket, and Compass to Claude, ChatGPT, Cursor, VS Code, and other AI ☆`1,146`
- [aashari/mcp-server-atlassian-bitbucket](https://github.com/aashari/mcp-server-atlassian-bitbucket) — Atlassian Bitbucket repositories and PRs ☆`164`
- [nguyenvanduocit/jira-mcp](https://github.com/nguyenvanduocit/jira-mcp) — Jira issues and sprints via Go MCP ☆`96`
- [aashari/mcp-server-atlassian-jira](https://github.com/aashari/mcp-server-atlassian-jira) — Atlassian Jira projects, issues and sprints ☆`78`
- [aashari/mcp-server-atlassian-confluence](https://github.com/aashari/mcp-server-atlassian-confluence) — Atlassian Confluence spaces and pages ☆`62`
- [spranab/saga-mcp](https://github.com/spranab/saga-mcp) — Your agent loses the plan between sessions, so saga-mcp gives it a SQLite-backed tracker for projects, epics, tasks, subtasks, dependencies, and notes: 41 MCP tools, an activity ☆`42`
- [phuc-nt/mcp-atlassian-server](https://github.com/phuc-nt/mcp-atlassian-server) — Jira and Confluence integration ☆`52`
- [athapong/aio-mcp](https://github.com/athapong/aio-mcp) — All-in-one MCP server with AI search, RAG, and multi-service integrations (GitLab/Jira/Confluence/YouTube) for AI-enhanced development workflows. Folk from ☆`36`
- [rahulthedevil/Jira-Context-MCP](https://github.com/rahulthedevil/Jira-Context-MCP) — Jira tickets info for AI coding agents ☆`26`
- [KS-GEN-AI/jira-mcp-server](https://github.com/KS-GEN-AI/jira-mcp-server) — A test of jira mcp server ☆`26`
### Collaboration

- [CrossPaste/crosspaste-desktop](https://github.com/CrossPaste/crosspaste-desktop) — Cross-device clipboard sync for macOS, Windows & Linux - end-to-end encrypted, LAN-only, no cloud. OCR, CLI and MCP server built in. ☆`2,689`
- [erpipe-org/mcp-odoo](https://github.com/erpipe-org/mcp-odoo) — Odoo MCP for AI agents - gated writes, multi-instance. Hosted product: https://erpipe.com ☆`428`
- [Orkas-AI/Orkas-VideoStudio](https://github.com/Orkas-AI/Orkas-VideoStudio) — Turn your coding agent into a video studio: describe a video in plain language, and your agent writes the timeline and produces the file. ☆`343`
- [workopia/workopia-mcp](https://github.com/workopia/workopia-mcp) — Workopia MCP Server - free job search, resume builder & career advice for Claude, ChatGPT, Cursor. ☆`312`
- [BrightbeamAI/chap](https://github.com/BrightbeamAI/chap) — CHAP, the Collaborative Human Agent Protocol, is a MCP/A2A-compatible runtime for auditable human-agent work: approvals, overrides, handoffs, escalation and verifiable evidence ☆`122`
- [evalstate/mcp-miro](https://github.com/evalstate/mcp-miro) — MCP server for Miro whiteboard manipulation and sticky creation ☆`113`
- [hiromitsusasaki/raindrop-io-mcp-server](https://github.com/hiromitsusasaki/raindrop-io-mcp-server) — Raindrop.io bookmark management ☆`74`
- [k-jarzyna/mcp-miro](https://github.com/k-jarzyna/mcp-miro) — Miro integration for Model Context Protocol ☆`65`
- [dearlordylord/huly-mcp](https://github.com/dearlordylord/huly-mcp) — Huly MCP and CLI: Feature-complete MCP server and CLI for Huly platform. Intabia partially compatible. ☆`63`
- [kintone/mcp-server](https://github.com/kintone/mcp-server) — kintone official MCP server ☆`59`
- [orellazri/coda-mcp](https://github.com/orellazri/coda-mcp) — MCP Server for Coda ☆`62`
- [tale-project/tale](https://github.com/tale-project/tale) — Built-in HTTP MCP for organizational knowledge and automation authoring, tests, deployments, and runs. ☆`41`
- [6figr-com/jobgpt-mcp-server](https://github.com/6figr-com/jobgpt-mcp-server) — MCP server for JobGPT - search jobs, auto-apply, generate resumes, and track applications from Claude, Cursor, Windsurf, and any MCP client ☆`26`
- [lexmount/artifact-site](https://github.com/lexmount/artifact-site) — A self-hosted home for your team's AI-generated pages and documents. Publish HTML, build folders, ZIPs and PDFs as sandboxed, versioned links. CLI + remote MCP for AI agents. ☆`26`
- [OurThinkTank/founders-os](https://github.com/OurThinkTank/founders-os) — Founders OS - CRM, tasks, finances, feeds, and memory for founders, as an MCP server. ☆`22`
- [winfunc/asterisk-mcp-server](https://github.com/winfunc/asterisk-mcp-server) — Asterisk Model Context Protocol (MCP) server. ☆`34`
- [srikanth-paladugula/mcp-dynamics365-server](https://github.com/srikanth-paladugula/mcp-dynamics365-server) — MCP Server for Microsoft Dynamics 365 ☆`22`
### Documents

- [zcaceres/markdownify-mcp](https://github.com/zcaceres/markdownify-mcp) — Convert almost anything to Markdown ☆`2,999`
- [vivekVells/mcp-pandoc](https://github.com/vivekVells/mcp-pandoc) — MCP server for document format conversion using pandoc. ☆`585`
- [onebirdrocks/ebook-mcp](https://github.com/onebirdrocks/ebook-mcp) — MCP server for ebook processing ☆`396`
- [baruchiro/paperless-mcp](https://github.com/baruchiro/paperless-mcp) — MCP server for Paperless-NGX document management ☆`150`
- [vgnshiyer/apple-books-mcp](https://github.com/vgnshiyer/apple-books-mcp) — Apple Books MCP Server ☆`64`
- [Unstructured-IO/UNS-MCP](https://github.com/Unstructured-IO/UNS-MCP) — MCP server for Unstructured document processing ☆`43`
- [esignaturescom/mcp-server-esignatures](https://github.com/esignaturescom/mcp-server-esignatures) — eSignatures.com document signing ☆`40`
- [thechandanbhagat/cv-forge](https://github.com/thechandanbhagat/cv-forge) — ATS-friendly CVs, cover letters, and job-tailored emails ☆`30`
- [danielkennedy1/pdf-tools-mcp](https://github.com/danielkennedy1/pdf-tools-mcp) — MCP server for PDF manipulation (merge, extract, snippets) ☆`32`
- [gpetraroli/mcp_pdf_reader](https://github.com/gpetraroli/mcp_pdf_reader) — An MCP server to extraxt/search text from pdf ☆`32`
- [intsig-textin/textin-mcp](https://github.com/intsig-textin/textin-mcp) — OCR and document-to-Markdown conversion ☆`29`
- [Sohaib-2/pdf-mcp-server](https://github.com/Sohaib-2/pdf-mcp-server) — Comprehensive PDF manipulation toolkit. Merge, split, encrypt, optimize PDFs through natural language commands via MCP protocol. ☆`16`
### Google Workspace

- [taylorwilsdon/google_workspace_mcp](https://github.com/taylorwilsdon/google_workspace_mcp) — MCP server for Google Workspace integration ☆`3,473`
- [MarkusPfundstein/mcp-gsuite](https://github.com/MarkusPfundstein/mcp-gsuite) — MCP Server to interact with Google Gsuite prodcuts ☆`491`
- [felores/gdrive-mcp-server](https://github.com/felores/gdrive-mcp-server) — Efficient implementation of the Google Drive MCP server ☆`72`
- [v-3/google-calendar](https://github.com/v-3/google-calendar) — Google Calendar events and scheduling ☆`72`
- [baryhuang/mcp-headless-gmail](https://github.com/baryhuang/mcp-headless-gmail) — Gmail without local credentials ☆`55`
- [giuseppe-coco/Google-Workspace-MCP-Server](https://github.com/giuseppe-coco/Google-Workspace-MCP-Server) — Gmail, Calendar, and Drive integration ☆`30`
- [vakharwalad23/google-mcp](https://github.com/vakharwalad23/google-mcp) — Gmail, Calendar, and other Google workspace tools ☆`21`
### Helpdesk & Support

- [echelon-ai-labs/servicenow-mcp](https://github.com/echelon-ai-labs/servicenow-mcp) — MCP Server for ServiceNow ☆`304`
- [effytech/freshdesk_mcp](https://github.com/effytech/freshdesk_mcp) — Freshdesk support ticket integration ☆`71`
- [modesty/fluent-mcp](https://github.com/modesty/fluent-mcp) — MCP server and AI skill suite for Fluent (ServiceNow SDK) ☆`31`
- [quickchatai/quickchat-ai-mcp](https://github.com/quickchatai/quickchat-ai-mcp) — The Quickchat AI MCP server ☆`24`
### Learning & Flashcards

- [ankimcp/anki-mcp-server](https://github.com/ankimcp/anki-mcp-server) — MCP server for Anki spaced repetition flashcards ☆`544`
- [scorzeth/anki-mcp-server](https://github.com/scorzeth/anki-mcp-server) — An MCP server for Anki ☆`185`
- [jinzcdev/leetcode-mcp-server](https://github.com/jinzcdev/leetcode-mcp-server) — MCP server for LeetCode problems and solutions ☆`155`
- [nietus/anki-mcp](https://github.com/nietus/anki-mcp) — MCP server for Anki: get quizzed, track retention, find leeches and manage your flashcards from Claude and other MCP clients (via AnkiConnect) ☆`44`
- [rember/rember-mcp](https://github.com/rember/rember-mcp) — A Model Context Protocol (MCP) server for Rember. ☆`63`
- [spacholski1225/anki-connect-mcp](https://github.com/spacholski1225/anki-connect-mcp) — MCP implementation for Anki Web ☆`27`
- [doggybee/mcp-server-leetcode](https://github.com/doggybee/mcp-server-leetcode) — MCP server for LeetCode coding challenges ☆`44`
### Microsoft 365

- [haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server) — Excel file manipulation ☆`4,273`
- [Softeria/ms-365-mcp-server](https://github.com/Softeria/ms-365-mcp-server) — Microsoft 365 and Office via Graph API ☆`1,110`
- [sbroenne/mcp-server-excel](https://github.com/sbroenne/mcp-server-excel) — Excel MCP Server - 23 tools for AI-powered automation ☆`844`
- [InditexTech/mcp-teams-server](https://github.com/InditexTech/mcp-teams-server) — MCP server for Microsoft Teams integration ☆`466`
- [merill/lokka](https://github.com/merill/lokka) — MCP for Microsoft 365 and Graph ☆`310`
- [pnp/cli-microsoft365-mcp-server](https://github.com/pnp/cli-microsoft365-mcp-server) — Manage Microsoft 365 using MCP server ☆`135`
- [ilia-sokolov/OfficeAgent.NET](https://github.com/ilia-sokolov/OfficeAgent.NET) — Structured Word, PowerPoint, and Excel automation for .NET and coding agents, with validated plans, MCP, tracked changes, and SharePoint ☆`27`
- [Norcim133/OutlookMCPServer](https://github.com/Norcim133/OutlookMCPServer) — MCP Server for msgraph - mail, calendar, files ☆`16`
### Note-taking & Docs

- [RafalWilinski/mcp-apple-notes](https://github.com/RafalWilinski/mcp-apple-notes) — RAG over Apple Notes for Claude ☆`417`
- [vasylenko/bear-notes-mcp](https://github.com/vasylenko/bear-notes-mcp) — MCP Server for Bear note taking app available as Claude Desktop extension or standalone server for any other AI tool ☆`207`
- [lostintangent/gistpad-mcp](https://github.com/lostintangent/gistpad-mcp) — Personal knowledge and daily notes management ☆`207`
- [Vortiago/mcp-outline](https://github.com/Vortiago/mcp-outline) — AI assistants with Outline docs ☆`158`
- [entanglr/zettelkasten-mcp](https://github.com/entanglr/zettelkasten-mcp) — MCP server implementing Zettelkasten knowledge management ☆`168`
- [gornskew/cyborg-whisperer](https://github.com/gornskew/cyborg-whisperer) — Manage Lisply lisp-speaking backends ☆`54`
- [2slides/mcp-2slides](https://github.com/2slides/mcp-2slides) — MCP Server for 2slides - AI agent for PPT generation ☆`34`
- [ONLYOFFICE/docspace-mcp](https://github.com/ONLYOFFICE/docspace-mcp) — DocSpace MCP Server ☆`31`
- [koruworks/mono](https://github.com/koruworks/mono) — Local MCP server for Koru, a local-first notes, docs and files app ☆`31`
- [pinto-notes/pinto-notes](https://github.com/pinto-notes/pinto-notes) — Notes for iPhone and Mac that ChatGPT, Claude, Claude Code and Codex can read and edit. Feels like Apple Notes, imports it too. Open source, encrypted. ☆`30`
- [Piotr1215/mcp-obsidian](https://github.com/Piotr1215/mcp-obsidian) — simple mcp server for interacting with local obsidian notes ☆`24`
- [akseyh/bear-mcp-server](https://github.com/akseyh/bear-mcp-server) — MCP Server integration for Bear note app ☆`45`
- [joshylchen/zettelkasten](https://github.com/joshylchen/zettelkasten) — Zettelkasten notes with search, links, CLI, API, and web ☆`40`
- [danield137/mcp-workflowy](https://github.com/danield137/mcp-workflowy) — An MCP server for workflowy ☆`29`
- [Harry-027/JotDown](https://github.com/Harry-027/JotDown) — An MCP Server in Rust for creating Notion pages & mdBooks with LLMs ☆`23`
- [louis030195/easy-obsidian-mcp](https://github.com/louis030195/easy-obsidian-mcp) — wire your brain to AGI through the best obsidian MCP ☆`17`
### Notion

- [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server) — Official Notion MCP Server ☆`4,694`
- [suekou/mcp-notion-server](https://github.com/suekou/mcp-notion-server) — MCP server for Notion API with Markdown conversion ☆`925`
- [danhilse/notion_mcp](https://github.com/danhilse/notion_mcp) — Notion integration with advanced formatting ☆`209`
- [awkoy/notion-mcp-server](https://github.com/awkoy/notion-mcp-server) — Notion MCP server with token auth: connect Claude Code, Claude Desktop, Cursor, VS Code and Codex to Notion pages, databases, comments and files. 3 tools, 94% less context than ☆`179`
- [v-3/notion-server](https://github.com/v-3/notion-server) — MCP server for searching, reading, updating, and creating Notion pages via Claude-compatible agents. ☆`118`
- [evergreen-it-dev/folio](https://github.com/evergreen-it-dev/folio) — The AI-assisted, open-source alternative to Notion and Confluence: a team wiki that lives in Git, with real-time editing, data tables, whiteboards, offline mode, and first-class ☆`81`
- [Grey-Iris/easy-notion-mcp](https://github.com/Grey-Iris/easy-notion-mcp) — Markdown-first Notion MCP server. ~6-7x fewer response tokens vs official Notion MCP. 43 tools. ☆`55`
- [Badhansen/notion-mcp](https://github.com/Badhansen/notion-mcp) — Notion workspace management ☆`31`
- [pbohannon/notion-api-mcp](https://github.com/pbohannon/notion-api-mcp) — A Python-based MCP for use in exposing Notion functionality to LLMs (Claude) ☆`28`
- [Ejb503/systemprompt-mcp-notion](https://github.com/Ejb503/systemprompt-mcp-notion) — This an Model Context Protocol (MCP) server that integrates Notion into your AI workflows. This server enables seamless access to Notion through MCP, allowing AI agents to ☆`26`
- [orbit-logistics/notion-mcp-server](https://github.com/orbit-logistics/notion-mcp-server) — MCP server for Notion integration ☆`21`
### Obsidian

- [MarkusPfundstein/mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) — Obsidian integration via REST API plugin ☆`4,516`
- [bitbonsai/mcpvault](https://github.com/bitbonsai/mcpvault) — Lightweight Obsidian vault access ☆`1,713`
- [StevenStavrakis/obsidian-mcp](https://github.com/StevenStavrakis/obsidian-mcp) — A simple MCP server for Obsidian ☆`748`
- [cyanheads/obsidian-mcp-server](https://github.com/cyanheads/obsidian-mcp-server) — Read, write, search, and surgically edit Obsidian vault notes, tags, and frontmatter via MCP. STDIO or Streamable HTTP. ☆`701`
- [WenyuChiou/research-hub](https://github.com/WenyuChiou/research-hub) — AI-operable research workspace for Zotero, Obsidian, and NotebookLM. Use any two, or all three, through CLI, MCP, REST, and dashboard. ☆`68`
- [shaqmughal/seekstone](https://github.com/shaqmughal/seekstone) — The Obsidian MCP server that needs no plugin, no running Obsidian app - and doesn't blow your context window. Filesystem-direct: single-digit-ms keyword search, ~26 ms local ☆`35`
- [oomkapwn/enquire-mcp](https://github.com/oomkapwn/enquire-mcp) — The #1 Obsidian MCP for AI memory - freshness-aware, cited, local-first and read-only by default. Dataview, Bases, PDFs, every agent. ☆`34`
- [aliasunder/vault-cortex](https://github.com/aliasunder/vault-cortex) — Standalone MCP server for Obsidian vaults - hybrid search, structured memory, task management, files, OAuth 2.1. Run locally, self-host, or one-click deploy for remote access. ☆`34`
- [rps321321/obsidian-mcp-pro](https://github.com/rps321321/obsidian-mcp-pro) — The most feature-complete MCP server for Obsidian vaults - 23 tools + 3 resources for search, read, write, tags, link analysis, graph traversal, and canvas. Also ships as an ☆`33`
- [Semiotronika/NOUZ-MCP](https://github.com/Semiotronika/NOUZ-MCP) — Локальный семантический граф и MCP-сервер для Markdown и Obsidian ☆`24`
- [rwnalds/engram](https://github.com/rwnalds/engram) — Self-hosted MCP server + dashboard giving Claude Code, Cursor & Hermes agents shared long-term memory over a git-backed markdown vault. Agent-native, Obsidian-compatible second ☆`20`
- [maxkuminov/obsidian-mcp](https://github.com/maxkuminov/obsidian-mcp) — Self-hosted MCP server for Obsidian: semantic + full-text search, wikilink graph, note CRUD, OAuth, and a self-describing vault guide. ☆`18`
- [smith-and-web/obsidian-mcp-server](https://github.com/smith-and-web/obsidian-mcp-server) — MCP server for Obsidian vault management - enables Claude and other AI assistants to read, write, search, and organize your notes ☆`19`
- [renezander030/agentic-task-system](https://github.com/renezander030/agentic-task-system) — CLI + MCP for agent context: a task layer over TickTick, Notion, GitHub, Obsidian & more (RRF retrieval, provenance, reviewed writes, undo) plus a knowledge-graph layer - ats kg: ☆`17`
- [aka-kika/kika-obsidian-mcp](https://github.com/aka-kika/kika-obsidian-mcp) — Local-first MCP server for Obsidian vaults - no plugins, no API keys, with schema-validated Bases (.base) support. ☆`17`
- [junnnnnw00/obsidian-everywhere](https://github.com/junnnnnw00/obsidian-everywhere) — Graph + local semantic context for Obsidian, with guarded remote MCP access and edits from Codex, ChatGPT, Claude, and any MCP client. ☆`16`
- [anpigon/mcp-server-obsidian-omnisearch](https://github.com/anpigon/mcp-server-obsidian-omnisearch) — An MCP server that enables searches within Obsidian vaults using the Omnisearch plugin API. Returns absolute paths to matching notes for seamless integration. ☆`30`
### Project Management

- [mondaycom/mcp](https://github.com/mondaycom/mcp) — AI agents with secure data access ☆`436`
- [makeplane/plane-mcp-server](https://github.com/makeplane/plane-mcp-server) — Plane's Official Model Context Protocol Server ☆`356`
- [jerhadf/linear-mcp-server](https://github.com/jerhadf/linear-mcp-server) — MCP server for Linear issue tracking ☆`346`
- [taskade/mcp](https://github.com/taskade/mcp) — MCP server for Taskade project management ☆`171`
- [tacticlaunch/mcp-linear](https://github.com/tacticlaunch/mcp-linear) — MCP server for Linear project management ☆`149`
- [roychri/mcp-server-asana](https://github.com/roychri/mcp-server-asana) — MCP server for Asana task and project management ☆`149`
- [its-dart/dart-mcp-server](https://github.com/its-dart/dart-mcp-server) — Dart AI Model Context Protocol (MCP) server ☆`128`
- [aikts/yandex-tracker-mcp](https://github.com/aikts/yandex-tracker-mcp) — Yandex Tracker MCP Server with OAuth2 support ☆`122`
- [feuerdev/keep-mcp](https://github.com/feuerdev/keep-mcp) — MCP server for Google Keep ☆`111`
- [georgeantonopoulos/Basecamp-MCP-Server](https://github.com/georgeantonopoulos/Basecamp-MCP-Server) — Basecamp 3+ project management ☆`101`
- [tonyzorin/youtrack-mcp](https://github.com/tonyzorin/youtrack-mcp) — YouTrack server, ARM64 and AMD64 ☆`99`
- [taazkareem/clickup-mcp-server](https://github.com/taazkareem/clickup-mcp-server) — ClickUp MCP Server - project management with AI ☆`53`
- [m0xai/trello-mcp-server](https://github.com/m0xai/trello-mcp-server) — A simple yet powerful MCP server for Trello. ☆`54`
- [dkships/pm-copilot](https://github.com/dkships/pm-copilot) — MCP server that triangulates customer support tickets and feature requests to help PMs decide what to build next ☆`30`
- [Teamwork/mcp](https://github.com/Teamwork/mcp) — Teamwork.com MCP server ☆`28`
- [EduBase/MCP](https://github.com/EduBase/MCP) — MCP server for EduBase e-learning platform ☆`28`
- [kelvin6365/plane-mcp-server](https://github.com/kelvin6365/plane-mcp-server) — MCP server for Plane.so project management ☆`40`
- [kocakli/Trello-Desktop-MCP](https://github.com/kocakli/Trello-Desktop-MCP) — Trello integration for Claude Desktop via MCP ☆`38`
- [TylerIlunga/procore-mcp-server](https://github.com/TylerIlunga/procore-mcp-server) — MCP server exposing the full Procore REST API for Claude Desktop and Claude Code ☆`18`
- [devemberx/mcp-server-polarion](https://github.com/devemberx/mcp-server-polarion) — MCP server for Polarion ALM - read and write documents, work items, test runs, traceability links, and comments from any MCP-compatible AI assistant ☆`17`
- [bivex/kanboard-mcp](https://github.com/bivex/kanboard-mcp) — MCP server for Kanboard project management integration ☆`28`
- [Prat011/mcp-server-monday](https://github.com/Prat011/mcp-server-monday) — MCP Server to interact with Monday.com boards and items ☆`34`
- [khaoss85/mcp-orchestro](https://github.com/khaoss85/mcp-orchestro) — Task breakdown, dependencies, and progress for AI teams ☆`16`
### Tasks & Calendar

- [screenpipe/screenpipe](https://github.com/screenpipe/screenpipe) — Searchable screen text and audio history via MCP; source-available under the Screenpipe Commercial License ☆`22,226`
- [nspady/google-calendar-mcp](https://github.com/nspady/google-calendar-mcp) — MCP integration for Google Calendar to manage events. ☆`1,209`
- [Doist/todoist-mcp](https://github.com/Doist/todoist-mcp) — Todoist tools for AI agents ☆`561`
- [abhiz123/todoist-mcp-server](https://github.com/abhiz123/todoist-mcp-server) — Todoist natural language task management ☆`392`
- [Omar-V2/mcp-ical](https://github.com/Omar-V2/mcp-ical) — Interact with MacOS Calendar ☆`333`
- [zcaceres/gtasks-mcp](https://github.com/zcaceres/gtasks-mcp) — A Google Tasks Model Context Protocol Server for Claude ☆`175`
- [dominik1001/caldav-mcp](https://github.com/dominik1001/caldav-mcp) — CalDAV calendar sync ☆`108`
- [alexarevalo9/ticktick-mcp-server](https://github.com/alexarevalo9/ticktick-mcp-server) — TickTick task management ☆`73`
- [takumi0706/google-calendar-mcp](https://github.com/takumi0706/google-calendar-mcp) — Google Calendar for Claude Desktop ☆`59`
- [arpitbatra123/mcp-googletasks](https://github.com/arpitbatra123/mcp-googletasks) — MCP server for Google Tasks management ☆`51`
- [stanislavlysenko0912/todoist-mcp-server](https://github.com/stanislavlysenko0912/todoist-mcp-server) — Todoist Rest API and Sync API ☆`63`
- [flesler/mcp-tasks](https://github.com/flesler/mcp-tasks) — Efficient task management with views ☆`47`
- [jen6/ticktick-mcp](https://github.com/jen6/ticktick-mcp) — TickTick task management with filtering ☆`67`
- [2nd1st/open-mcp-apps](https://github.com/2nd1st/open-mcp-apps) — Persistent, interactive MCP Apps for any MCP host: the AI builds an app once, you both reuse it - data outlives the conversation. Ships an engine, a 22-app App Store, and a ☆`36`
- [awwaiid/mcp-server-taskwarrior](https://github.com/awwaiid/mcp-server-taskwarrior) — MCP Server for TaskWarrior! ☆`51`
- [urbanogardun/things3-mcp](https://github.com/urbanogardun/things3-mcp) — MCP server for Things3 integration on macOS ☆`25`
- [jbrinkman/valkey-ai-tasks](https://github.com/jbrinkman/valkey-ai-tasks) — MCP server for task management with Valkey persistence ☆`25`
- [hichana/goalstory-mcp](https://github.com/hichana/goalstory-mcp) — Goal tracking with AI-powered storytelling ☆`18`
- [Danielpeter-99/calcom-mcp](https://github.com/Danielpeter-99/calcom-mcp) — Cal.com event types, bookings, and schedule data ☆`19`
### Wiki & Collaboration

- [anyproto/anytype-mcp](https://github.com/anyproto/anytype-mcp) — AI with Anytype encrypted local data ☆`536`
- [ProfessionalWiki/MediaWiki-MCP-Server](https://github.com/ProfessionalWiki/MediaWiki-MCP-Server) — Connect AI with any MediaWiki ☆`146`
- [yuna0x0/hackmd-mcp](https://github.com/yuna0x0/hackmd-mcp) — HackMD note-taking integration ☆`67`
- [HenryHaoson/Yuque-MCP-Server](https://github.com/HenryHaoson/Yuque-MCP-Server) — Yuque mcp server ☆`69`
- [jtauschl/openproject-ce-mcp](https://github.com/jtauschl/openproject-ce-mcp) — MCP server for OpenProject Community Edition: projects, work packages, time tracking, meetings, wiki and more as preview-first tools for AI agents such as Claude Code, Codex and ☆`39`
- [growilabs/growi-mcp-server](https://github.com/growilabs/growi-mcp-server) — GROWI wiki search and retrieval for AI answers ☆`20`
### Education

- [RohanMuppa/brightspace-mcp-server](https://github.com/RohanMuppa/brightspace-mcp-server) — MCP server for Brightspace (D2L). Check grades, due dates, assignments, announcements, rosters, syllabus & course content via Claude, ChatGPT, Cursor, Windsurf, or any MCP ☆`62`
- [AnonymousOnyx22/brightspace-d2l-mcp](https://github.com/AnonymousOnyx22/brightspace-d2l-mcp) — Brightspace D2L MCP server for Claude, ChatGPT, Cursor and Copilot. Knows what you already handed in, so it only tells you what is actually left. Due dates, grades and course ☆`29`
- [ictinnovations/ictexam-mcp](https://github.com/ictinnovations/ictexam-mcp) — MCP server for ICTExam - read exams, gradebooks and item analysis; parse papers with AI and publish exams. By ICT Innovations. ☆`17`
## Research & Science

- [mnemox-ai/idea-reality-mcp](https://github.com/mnemox-ai/idea-reality-mcp) — Pre-build reality check for AI coding agents. Scans GitHub, HN, npm, PyPI, Product Hunt. MCP server. 290+ stars. ☆`828`
- [oOo0oOo/lean-lsp-mcp](https://github.com/oOo0oOo/lean-lsp-mcp) — Lean Theorem Prover MCP ☆`545`
- [rrrrrredy/research-toolkit](https://github.com/rrrrrredy/research-toolkit) — Research methods, workflow tools, and independent review for AI agents, packaged as a Skill, plugin, and local MCP server. ☆`313`
- [yusong652/itasca-mcp](https://github.com/yusong652/itasca-mcp) — MCP server connecting AI agents to ITASCA engines (PFC, FLAC, 3DEC, MPoint, MassFlow) - run geotechnical & geomechanics simulations through natural conversation ☆`226`
- [szeider/mcp-solver](https://github.com/szeider/mcp-solver) — Constraint optimization and solving ☆`186`
- [pminervini/deep-research-mcp](https://github.com/pminervini/deep-research-mcp) — MCP server for OpenAI and Gemini Deep Research, Tavily Research, and self-hosted DR-Tulu and openJiuwen DeepSearch (Gnosis). ☆`116`
- [ProgramComputer/NASA-MCP-server](https://github.com/ProgramComputer/NASA-MCP-server) — A Model Context Protocol (MCP) server for NASA APIs, providing a standardized interface for AI models to interact with NASA's vast array of data sources. ☆`94`
- [Pantheon-Security/notebooklm-mcp-secure](https://github.com/Pantheon-Security/notebooklm-mcp-secure) — Secure NotebookLM MCP with 14 security layers ☆`88`
- [NellyW8/MCP4EDA](https://github.com/NellyW8/MCP4EDA) — RTL-to-GDSII automation with LLM ☆`112`
- [patsnap/patent-literature-search-mcp](https://github.com/patsnap/patent-literature-search-mcp) — Search global patents across WIPO, EPO, USPTO, CNIPA, JPO, KIPO and other authorities, together with scientific literature from PubMed, arXiv, Nature, Science and other major ☆`85`
- [SecretiveShell/MCP-wolfram-alpha](https://github.com/SecretiveShell/MCP-wolfram-alpha) — Wolfram Alpha computational intelligence ☆`76`
- [smaniches/semantic-scholar-mcp](https://github.com/smaniches/semantic-scholar-mcp) — Semantic Scholar MCP server: 14 typed tools for paper search, citation graphs, author profiles, recommendations, PyPI/Docker. ☆`24`
- [Scormave/gramps-web-mcp](https://github.com/Scormave/gramps-web-mcp) — MCP server for Gramps Web. Gives AI agents structured, tool-based access to family trees through the Model Context Protocol. Built with .NET 10. ☆`22`
- [kimimgo/viznoir](https://github.com/kimimgo/viznoir) — VTK is all you need. AI-Ready VTK visualization for science and engineering. ☆`19`
- [nguyenvanduocit/research-kit](https://github.com/nguyenvanduocit/research-kit) — Toolkit to help you get started with Spec-Driven Research ☆`20`
- [neuromechanist/matlab-mcp-tools](https://github.com/neuromechanist/matlab-mcp-tools) — MATLAB pipelines by section and figure inspection ☆`19`
- [Orthogonalpub/modelica_simulation_mcp_server](https://github.com/Orthogonalpub/modelica_simulation_mcp_server) — Public MCP server to run modelica simulation ☆`22`
- [RLabs-Inc/ios-forensics-mcp](https://github.com/RLabs-Inc/ios-forensics-mcp) — iOS Forensics MCP Server for analyzing iPhone/iPad file systems ☆`20`
- [anuj0456/arxiv-mcp-server](https://github.com/anuj0456/arxiv-mcp-server) — MCP server for arXiv.org - Search, analyze, and export academic papers with AI assistants. Features advanced paper discovery, citation analysis, trend tracking, and multi-format ☆`19`
## Sandboxing & Execution

- [superradcompany/microsandbox](https://github.com/superradcompany/microsandbox) — easy, fast, programmable and local-first microVM runtime and library ☆`8,939`
- [dagger/container-use](https://github.com/dagger/container-use) — MCP server for container orchestration ☆`4,082`
- [grafbase/grafbase](https://github.com/grafbase/grafbase) — [Acquired by The Guild] The Grafbase GraphQL Federation Gateway ☆`1,226`
- [microsoft/wassette](https://github.com/microsoft/wassette) — Wassette: A security-oriented runtime that runs WebAssembly Components via MCP ☆`974`
- [sandbaseai/sandbase-harness](https://github.com/sandbaseai/sandbase-harness) — Sandboxed local agent runtime with approvals and audit ☆`641`
- [docker/labs-ai-tools-for-devs](https://github.com/docker/labs-ai-tools-for-devs) — Your trusted home for discovering MCP tools - seamlessly integrated into Docker ☆`398`
- [Automata-Labs-team/code-sandbox-mcp](https://github.com/Automata-Labs-team/code-sandbox-mcp) — Secure code sandbox in Docker ☆`327`
- [formulahendry/mcp-server-code-runner](https://github.com/formulahendry/mcp-server-code-runner) — Code Runner MCP Server ☆`242`
- [bazinga012/mcp_code_executor](https://github.com/bazinga012/mcp_code_executor) — Execute Python in Conda environment ☆`211`
- [alfonsograziano/node-code-sandbox-mcp](https://github.com/alfonsograziano/node-code-sandbox-mcp) — MCP server for Node.js code sandbox execution ☆`158`
- [hopx-ai/mcp](https://github.com/hopx-ai/mcp) — Execute code in isolated cloud containers ☆`128`
- [ccq1/awsome_kali_MCPServers](https://github.com/ccq1/awsome_kali_MCPServers) — awsome kali MCPServers is a set of MCP servers tailored for Kali Linux ☆`110`
- [r33drichards/mcp-js](https://github.com/r33drichards/mcp-js) — MCP server exposing V8 JavaScript runtime for AI agents ☆`64`
- [gradion-ai/ipybox](https://github.com/gradion-ai/ipybox) — Python code execution sandbox with MCP tool calling ☆`76`
- [UsamaK98/python-notebook-mcp](https://github.com/UsamaK98/python-notebook-mcp) — Lightweight Python Notebook MCP - Enable AI assistants to create, edit, and view Jupyter notebooks via Model Context Protocol ☆`45`
- [Alec2435/python_mcp](https://github.com/Alec2435/python_mcp) — MCP Server to run python code locally ☆`54`
- [yepcode/mcp-server-js](https://github.com/yepcode/mcp-server-js) — JavaScript MCP server framework by YepCode ☆`47`
- [hdresearch/mcp-python](https://github.com/hdresearch/mcp-python) — A python repl for MCP ☆`43`
- [Tsuchijo/matlab-mcp](https://github.com/Tsuchijo/matlab-mcp) — Model Context Protocol server to let LLMs write and execute matlab scripts ☆`40`
- [SebastianGilPinzon/colab-mcp](https://github.com/SebastianGilPinzon/colab-mcp) — Fixed & enhanced fork of Google's Colab MCP - tools visible at startup, GPU control, Windows support, no more 'Disconnected' ☆`24`
- [ihrpr/mcp-server-jupyter](https://github.com/ihrpr/mcp-server-jupyter) — MCP server for Jupyter Notebooks and JupyterLab ☆`34`
- [hileamlakB/Python-Runtime-Interpreter-MCP-Server](https://github.com/hileamlakB/Python-Runtime-Interpreter-MCP-Server) — Safe Python runtime interpreter ☆`30`
- [turlockmike/apple-notifier-mcp](https://github.com/turlockmike/apple-notifier-mcp) — A simple MCP server for sending notifications on mac devices, directly serving as an MCP server example. ☆`26`
- [gwbischof/outsource-mcp](https://github.com/gwbischof/outsource-mcp) — Give your AI assistant its own AI assistants. ☆`30`
- [54rt1n/container-mcp](https://github.com/54rt1n/container-mcp) — A podman ubuntu 24.04 container that serves a MCP server; with file, code execution, bash shell, knowledgebase, and more. ☆`22`
## Search & Extraction

### Academic Research

- [blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server) — arXiv paper search and analysis ☆`3,253`
- [iosifache/annas-mcp](https://github.com/iosifache/annas-mcp) — MCP server and CLI tool for searching and downloading documents from Anna's Archive ☆`1,108`
- [JackKuo666/Google-Scholar-MCP-Server](https://github.com/JackKuo666/Google-Scholar-MCP-Server) — Search Google Scholar papers ☆`430`
- [reading-plus-ai/mcp-server-deep-research](https://github.com/reading-plus-ai/mcp-server-deep-research) — Comprehensive research with reports ☆`215`
- [adityak74/mcp-scholarly](https://github.com/adityak74/mcp-scholarly) — A MCP server to search for accurate academic articles. ☆`185`
- [andybrandt/mcp-simple-arxiv](https://github.com/andybrandt/mcp-simple-arxiv) — arXiv paper search and reading ☆`202`
- [kujenga/zotero-mcp](https://github.com/kujenga/zotero-mcp) — Lightweight Model Context Protocol (MCP) server for the Zotero API, in Python ☆`162`
- [andybrandt/mcp-simple-pubmed](https://github.com/andybrandt/mcp-simple-pubmed) — PubMed medical research search ☆`171`
- [takashiishida/arxiv-latex-mcp](https://github.com/takashiishida/arxiv-latex-mcp) — MCP server for arXiv LaTeX paper retrieval ☆`149`
- [kaliaboi/mcp-zotero](https://github.com/kaliaboi/mcp-zotero) — Zotero collections for Claude Desktop ☆`163`
- [JackKuo666/PubMed-MCP-Server](https://github.com/JackKuo666/PubMed-MCP-Server) — Search and analyze PubMed articles ☆`132`
- [afrise/academic-search-mcp-server](https://github.com/afrise/academic-search-mcp-server) — Academic Paper Search MCP Server for Claude Desktop integration. Allows Claude to access data from Semantic Scholar and Crossref. ☆`119`
- [OctagonAI/octagon-deep-research-mcp](https://github.com/OctagonAI/octagon-deep-research-mcp) — AI-powered comprehensive research and analysis ☆`94`
- [HzaCode/OneCite](https://github.com/HzaCode/OneCite) — Parse and format academic references ☆`68`
- [akalaric/mcp-wolframalpha](https://github.com/akalaric/mcp-wolframalpha) — Wolfram Alpha integration for Python ☆`86`
- [oscardvs/zoteus](https://github.com/oscardvs/zoteus) — Zotero MCP server: search, citations, add by DOI, safe writes, semantic search and PDF page images for Claude, ChatGPT and any MCP client. TypeScript, local-first. ☆`64`
- [szeider/mcp-dblp](https://github.com/szeider/mcp-dblp) — Access DBLP computer science bibliography ☆`47`
- [drAbreu/alex-mcp](https://github.com/drAbreu/alex-mcp) — MCP server for OpenAlex ☆`57`
- [wd041216-bit/zero-api-key-web-search](https://github.com/wd041216-bit/zero-api-key-web-search) — Jev-powered search infrastructure for AI agents: zero API keys, MCP-ready, LLM-context aware, with local neural evidence verification. ☆`20`
- [prashalruchiranga/arxiv-mcp-server](https://github.com/prashalruchiranga/arxiv-mcp-server) — arXiv API via natural language ☆`41`
- [JackKuo666/bioRxiv-MCP-Server](https://github.com/JackKuo666/bioRxiv-MCP-Server) — Access bioRxiv papers ☆`27`
- [hbg/mcp-paperswithcode](https://github.com/hbg/mcp-paperswithcode) — MCP interface for PapersWithCode API ☆`26`
- [mochow13/google-scholar-mcp](https://github.com/mochow13/google-scholar-mcp) — MCP server for Google Scholar written in TypeScript ☆`26`
- [gemy411/multi-agents-research](https://github.com/gemy411/multi-agents-research) — Kotlin multi-agent research server on Ktor ☆`16`
### Data APIs

- [cantian-ai/bazi-mcp](https://github.com/cantian-ai/bazi-mcp) — Bazi Chinese astrology information ☆`436`
- [Rudra-ravi/wikipedia-mcp](https://github.com/Rudra-ravi/wikipedia-mcp) — Retrieve Wikipedia information ☆`305`
- [ahonn/mcp-server-gsc](https://github.com/ahonn/mcp-server-gsc) — Google Search Console data access ☆`282`
- [hellokaton/unsplash-mcp-server](https://github.com/hellokaton/unsplash-mcp-server) — A MCP server for Unsplash image search. ☆`239`
- [deadletterq/mcp-opennutrition](https://github.com/deadletterq/mcp-opennutrition) — MCP server for nutrition data and analysis ☆`208`
- [cameronrye/openzim-mcp](https://github.com/cameronrye/openzim-mcp) — MCP server for OpenZIM archive access ☆`149`
- [damionrashford/RivalSearchMCP](https://github.com/damionrashford/RivalSearchMCP) — MCP server for competitive search analysis ☆`134`
- [cswkim/discogs-mcp-server](https://github.com/cswkim/discogs-mcp-server) — MCP Server for Discogs ☆`133`
- [OpenDataMCP/OpenDataMCP](https://github.com/OpenDataMCP/OpenDataMCP) — Connect any Open Data to any LLM with Model Context Protocol. ☆`156`
- [8enSmith/mcp-open-library](https://github.com/8enSmith/mcp-open-library) — MCP server for Open Library book and author search ☆`100`
- [riemannzeta/patent_mcp_server](https://github.com/riemannzeta/patent_mcp_server) — MCP Server for USPTO data ☆`85`
- [zoomeye-ai/mcp_zoomeye](https://github.com/zoomeye-ai/mcp_zoomeye) — MCP server for ZoomEye network asset information ☆`83`
- [yuna0x0/anilist-mcp](https://github.com/yuna0x0/anilist-mcp) — AniList MCP server for accessing anime and manga data ☆`91`
- [Linked-API/linkedapi-mcp](https://github.com/Linked-API/linkedapi-mcp) — LinkedIn account control and data retrieval ☆`70`
- [anysiteio/anysite-mcp-server](https://github.com/anysiteio/anysite-mcp-server) — LinkedIn data access ☆`65`
- [imprvhub/mcp-domain-availability](https://github.com/imprvhub/mcp-domain-availability) — MCP server to check domain availability ☆`61`
- [djalal/quran-mcp-server](https://github.com/djalal/quran-mcp-server) — Quran.com verses, translations, tafsir ☆`73`
- [r-huijts/rijksmuseum-mcp](https://github.com/r-huijts/rijksmuseum-mcp) — Rijksmuseum artwork exploration ☆`72`
- [DappierAI/dappier-mcp](https://github.com/DappierAI/dappier-mcp) — MCP server for Dappier AI integration ☆`44`
- [0xDAEF0F/job-searchoor](https://github.com/0xDAEF0F/job-searchoor) — A simple MCP server that delivers you jobs based on your needs ☆`65`
- [JamesANZ/us-legal-mcp](https://github.com/JamesANZ/us-legal-mcp) — An MCP server that provides comprehensive US legislation. ☆`38`
- [yamanoku/baseline-mcp-server](https://github.com/yamanoku/baseline-mcp-server) — Web API Baseline status information ☆`37`
- [amurshak/congressMCP](https://github.com/amurshak/congressMCP) — US Congress data for AI agents ☆`36`
- [zzaebok/mcp-wikidata](https://github.com/zzaebok/mcp-wikidata) — Wikidata API implementation ☆`49`
- [joelio/stocky](https://github.com/joelio/stocky) — An MCP server for searching and downloading stock photography. ☆`28`
- [jhomen368/overseerr-mcp](https://github.com/jhomen368/overseerr-mcp) — Overseerr/Seerr media search, requests, and library ☆`25`
- [adawalli/nexus](https://github.com/adawalli/nexus) — MCP Server to make searching openrouter easy ☆`22`
- [Himalayas-App/himalayas-mcp](https://github.com/Himalayas-App/himalayas-mcp) — Remote job search, listings, candidates, and salaries ☆`21`
- [mikechao/metmuseum-mcp](https://github.com/mikechao/metmuseum-mcp) — Met Museum art collection discovery ☆`35`
- [cameronrye/activitypub-mcp](https://github.com/cameronrye/activitypub-mcp) — Fediverse browsing and interaction via ActivityPub ☆`17`
- [parallel-web/task-mcp](https://github.com/parallel-web/task-mcp) — Hosted deep research and dataset enrichment via Parallel ☆`16`
- [cameronrye/gopher-mcp](https://github.com/cameronrye/gopher-mcp) — A modern, cross-platform Model Context Protocol (MCP) server that enables AI assistants to browse and interact with both Gopher protocol and Gemini protocol resources safely and efficiently. ☆`16`
- [kehvinbehvin/json-mcp-filter](https://github.com/kehvinbehvin/json-mcp-filter) — JSON MCP server to filter only relevant data for your LLM ☆`26`
- [angheljf/nyt](https://github.com/angheljf/nyt) — MCP server for New York Times article search ☆`18`
- [siva010928/multi-chat-mcp-server](https://github.com/siva010928/multi-chat-mcp-server) — MCP server for multi-chat capabilities ☆`27`
- [delorenj/mcp-server-ticketmaster](https://github.com/delorenj/mcp-server-ticketmaster) — Ticketmaster Discovery API ☆`24`
- [r-huijts/opentk-mcp](https://github.com/r-huijts/opentk-mcp) — MCP server for Dutch parliamentary data via OpenTK ☆`23`
- [AshwinSundar/congress_gov_mcp](https://github.com/AshwinSundar/congress_gov_mcp) — Query US Congress.gov API ☆`19`
- [Trevato/bible-mcp](https://github.com/Trevato/bible-mcp) — add biblical context to your generative AI applications ☆`16`
### News & Content

- [6551Team/opennews-mcp](https://github.com/6551Team/opennews-mcp) — News Aggregation · AI Ratings · Trading Signals · Real-time Updates ☆`2,435`
- [guangxiangdebizi/FinanceMCP](https://github.com/guangxiangdebizi/FinanceMCP) — 这是一个金融领域相关的mcp,本项目通过集成 Tushare API 和 Binance API 为语言模型（如Claude）提供全面的实时金融数据访问能力，支持股票、基金、债券、宏观经济指标、稳定币、虚拟货币等多维度金融数据分析。其中也包含了金融数据查询、财经新闻查询、国家统计局数据查询等 ☆`867`
- [lfnovo/content-core](https://github.com/lfnovo/content-core) — Extract what matters from any media source ☆`182`
- [wopal-cn/mcp-hotnews-server](https://github.com/wopal-cn/mcp-hotnews-server) — A Model Context Protocol server that provides real-time hot trending topics from major Chinese social platforms and news sites. ☆`202`
- [superagents-lab/search1api-mcp](https://github.com/superagents-lab/search1api-mcp) — Official Search1API MCP server for web search, news, crawling, sitemaps, and trends-hosted with OAuth 2.1 or local via npm. ☆`172`
- [lennney/agent-search-mcp](https://github.com/lennney/agent-search-mcp) — Free-first Chinese and English web search MCP using zero-key sources and inspectable evidence. ☆`113`
- [erithwik/mcp-hn](https://github.com/erithwik/mcp-hn) — MCP Server for Hackernews ☆`76`
- [trendsmcp-ai/Trends-MCP](https://github.com/trendsmcp-ai/Trends-MCP) — MCP server for live trend data. Query Google Search, YouTube, TikTok, Reddit, Amazon, Wikipedia, News sentiment, Web Traffic, App Downloads, Steam, npm and more. Works with ☆`46`
- [imprvhub/mcp-rss-aggregator](https://github.com/imprvhub/mcp-rss-aggregator) — RSS feed aggregation for Claude Desktop ☆`27`
- [VectorInstitute/mcp-goodnews](https://github.com/VectorInstitute/mcp-goodnews) — A simple MCP application that delivers curated positive and uplifting news stories. ☆`48`
- [aloth/cred-1](https://github.com/aloth/cred-1) — CRED-1: Open, reproducible domain credibility dataset for automated pre-bunking of online misinformation. TypeScript library, CLI & MCP server. Check any news source's ☆`18`
- [pskill9/hn-server](https://github.com/pskill9/hn-server) — Hacker news MCP server ☆`40`
- [pranciskus/newsmcp](https://github.com/pranciskus/newsmcp) — MCP server for real-time world news - free, no API key required ☆`35`
- [format37/youtube_mcp](https://github.com/format37/youtube_mcp) — youtube transcriber mcp server ☆`32`
- [the0807/GeekNews-MCP-Server](https://github.com/the0807/GeekNews-MCP-Server) — GeekNews MCP Server ☆`18`
### Web Search Engines

- [assafelovic/gpt-researcher](https://github.com/assafelovic/gpt-researcher) — An autonomous agent that conducts deep research on any data using any LLM providers ☆`30,480`
- [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) — Exa MCP for web search and web crawling! ☆`5,209`
- [tavily-ai/tavily-mcp](https://github.com/tavily-ai/tavily-mcp) — Real-time search, extract, map and crawl ☆`2,476`
- [Aas-ee/open-webSearch](https://github.com/Aas-ee/open-webSearch) — MCP server for open web search ☆`1,895`
- [nickclyde/duckduckgo-mcp-server](https://github.com/nickclyde/duckduckgo-mcp-server) — MCP server for DuckDuckGo search ☆`1,567`
- [brave/brave-search-mcp-server](https://github.com/brave/brave-search-mcp-server) — Brave Search with AI summarization ☆`1,557`
- [ihor-sokoliuk/mcp-searxng](https://github.com/ihor-sokoliuk/mcp-searxng) — Private SearXNG web search for AI assistants ☆`1,345`
- [mrkrsl/web-search-mcp](https://github.com/mrkrsl/web-search-mcp) — Local web search for Claude Desktop ☆`1,194`
- [kagisearch/kagimcp](https://github.com/kagisearch/kagimcp) — Official Kagi search MCP server ☆`558`
- [pskill9/web-search](https://github.com/pskill9/web-search) — Web search using free google search (NO API KEYS REQUIRED) ☆`473`
- [angiejones/mcp-selenium](https://github.com/angiejones/mcp-selenium) — An MCP implementation for Selenium WebDriver ☆`430`
- [spences10/mcp-omnisearch](https://github.com/spences10/mcp-omnisearch) — A Model Context Protocol (MCP) server providing unified access to multiple search engines (Tavily, Brave, Kagi, Exa), AI tools (Kagi FastGPT, Exa, Linkup), and content extraction ☆`358`
- [jae-jae/g-search-mcp](https://github.com/jae-jae/g-search-mcp) — Parallel Google search with summaries ☆`272`
- [serpapi/serpapi-mcp](https://github.com/serpapi/serpapi-mcp) — SerpApi MCP Server for Google and other search engine results ☆`183`
- [DasDigitaleMomentum/searxNcrawl](https://github.com/DasDigitaleMomentum/searxNcrawl) — Open-source MCP server that gives AI agents web search (SearXNG) and clean Markdown crawling of pages, whole sites and logged-in areas. Self-hosted, no API key. ☆`184`
- [superagents-lab/search1api-mcp](https://github.com/superagents-lab/search1api-mcp) — MCP server for web search and crawl via Search1API ☆`172`
- [nkapila6/mcpsurfr](https://github.com/nkapila6/mcpsurfr) — RAG-like web search via MCP ☆`151`
- [ChanMeng666/server-google-news](https://github.com/ChanMeng666/server-google-news) — MCP server for Google News integration ☆`130`
- [SecretiveShell/MCP-searxng](https://github.com/SecretiveShell/MCP-searxng) — SearXNG search for agentic systems ☆`131`
- [mikechao/brave-search-mcp](https://github.com/mikechao/brave-search-mcp) — MCP server for Brave Search with filtering options ☆`130`
- [ScrapeGraphAI/scrapegraph-mcp](https://github.com/ScrapeGraphAI/scrapegraph-mcp) — ScapeGraph MCP Server ☆`120`
- [isnow890/naver-search-mcp](https://github.com/isnow890/naver-search-mcp) — MCP server for Naver search integration ☆`87`
- [zoharbabin/web-researcher-mcp](https://github.com/zoharbabin/web-researcher-mcp) — Search the web and primary sources, read full pages, and check every citation. MCP server for Claude, Cursor, Codex and more. Runs on your machine. ☆`77`
- [tanigami/mcp-server-perplexity](https://github.com/tanigami/mcp-server-perplexity) — Perplexity API chat with citations ☆`95`
- [ConechoAI/openai-websearch-mcp](https://github.com/ConechoAI/openai-websearch-mcp) — openai websearch tool as mcp server ☆`94`
- [JovaniPink/mcp-browser-use](https://github.com/JovaniPink/mcp-browser-use) — FastAPI MCP server that exposes browser-use automation through a testable Model Context Protocol boundary. ☆`62`
- [zhsama/duckduckgo-mcp-server](https://github.com/zhsama/duckduckgo-mcp-server) — MCP server for DuckDuckGo web search ☆`87`
- [goesByhc/cn-scraper-mcp](https://github.com/goesByhc/cn-scraper-mcp) — Let AI agents search the Chinese internet via MCP - Taobao, JD, Xiaohongshu, Zhihu, Weibo, Bilibili, ZSXQ, Douban, Dianping, and more. ☆`76`
- [steel-dev/steel-mcp-server](https://github.com/steel-dev/steel-mcp-server) — Cloud Chrome for MCP clients. Read pages that block plain fetches, fill forms, take screenshots, and hand the browser to a human when a login needs one. ☆`58`
- [thedaviddias/mcp-llms-txt-explorer](https://github.com/thedaviddias/mcp-llms-txt-explorer) — MCP to explore websites with llms.txt files ☆`78`
- [leehanchung/bing-search-mcp](https://github.com/leehanchung/bing-search-mcp) — MCP Server for Bing Search API ☆`81`
- [XZXZZX-Ai/bilibili-mcp](https://github.com/XZXZZX-Ai/bilibili-mcp) — Bilibili MCP工具 A Bilibili MCP server ☆`48`
- [laurentvv/crawl4ai-mcp-llm](https://github.com/laurentvv/crawl4ai-mcp-llm) — Web crawling tool that integrates with AI assistants via the MCP ☆`45`
- [pwilkin/mcp-searxng-public](https://github.com/pwilkin/mcp-searxng-public) — Query public SearXNG instances ☆`57`
- [ubie-oss/mcp-vertexai-search](https://github.com/ubie-oss/mcp-vertexai-search) — A MCP server for Vertex AI Search ☆`38`
- [OvertliDS/mcp-searxng-enhanced](https://github.com/OvertliDS/mcp-searxng-enhanced) — SearXNG web search with category awareness ☆`55`
- [dazeb/markdown-downloader](https://github.com/dazeb/markdown-downloader) — A MCP Server that will download any webpage as markdown in an instant. Download docs straight to your IDE for AI context. Powered by Jina.ai ☆`56`
- [dorukardahan/domain-search-mcp](https://github.com/dorukardahan/domain-search-mcp) — Zero-config domain availability MCP server for Claude & ChatGPT. Live pricing via Porkbun, premium/auction detection via GoDaddy, AI suggestions, RDAP/WHOIS fallback. Stdio + HTTP. ☆`28`
- [Tomatio13/mcp-server-tavily](https://github.com/Tomatio13/mcp-server-tavily) — MCP Server for Tavily API integration ☆`50`
- [youdotcom-oss/mcp](https://github.com/youdotcom-oss/mcp) — STDIO bridge for the hosted You.com MCP server at https://api.you.com/mcp. ☆`25`
- [n24q02m/wet](https://github.com/n24q02m/wet) — Open-source MCP server for AI agents: web search, content extraction, and library docs -- 5-strategy scraping, runs without API keys. ☆`23`
- [apache/solr-mcp](https://github.com/apache/solr-mcp) — Solr MCP Server ☆`21`
- [czottmann/kagi-ken-mcp](https://github.com/czottmann/kagi-ken-mcp) — Unofficial MCP server for working with Kagi without API access (you'll need to be a customer). Searches and summarizes. Uses Kagi session token for easy authentication. Works ☆`42`
- [Role1776/mcp-retrieval](https://github.com/Role1776/mcp-retrieval) — Fast, idiomatic Go MCP server for web search, image search, and page scraping to Markdown. Runs locally, no API keys, free. ☆`23`
- [garylab/serper-mcp-server](https://github.com/garylab/serper-mcp-server) — A Serper MCP Server ☆`39`
- [HasData/hasdata-mcp](https://github.com/HasData/hasdata-mcp) — HasData MCP server for web scraping and search. Google Search, Maps, Amazon, Zillow, Airbnb, YouTube and 20 more sites as structured JSON, hosted over streamable HTTP. ☆`21`
- [ac3xx/mcp-servers-kagi](https://github.com/ac3xx/mcp-servers-kagi) — A Model Context Protocol server implementation for Kagi's API ☆`44`
- [robertheadley/chrome-debug-mcp](https://github.com/robertheadley/chrome-debug-mcp) — An MCP server to allow you to debug webpages using LLMs ☆`45`
- [mnhlt/WebSearch-MCP](https://github.com/mnhlt/WebSearch-MCP) — MCP server for web search integration ☆`42`
- [MikkoParkkola/nab](https://github.com/MikkoParkkola/nab) — Token-lean web microfetch for LLM agents: any URL → clean markdown via CLI, MCP server, and Claude Code plugin. Real browser-cookie auth, passkeys, anti-bot reach, on-by-default ☆`19`
- [cevatkerim/unsplash-mcp](https://github.com/cevatkerim/unsplash-mcp) — An MCP server for Unsplash photo search with proper attribution built-in. Key differentiator: Returns ready-to-use attributiontext and attributionhtml for each photo, making it ☆`36`
- [KyuRish/mcp-server-for-fiverr-unofficial](https://github.com/KyuRish/mcp-server-for-fiverr-unofficial) — Unofficial, independent MCP server for searching public Fiverr gig listings. Not affiliated with or endorsed by Fiverr. ☆`16`
- [andyliszewski/webcrawl-mcp](https://github.com/andyliszewski/webcrawl-mcp) — Local-first web scraping, DuckDuckGo search, site mapping and crawling, using trafilatura with an optional Firecrawl fallback for JS-rendered pages. ☆`16`
- [orliesaurus/pulsemcp-server](https://github.com/orliesaurus/pulsemcp-server) — An MCP server that helps you find MCP servers that are listed on PulseMCP.com ☆`30`
- [codingthefuturewithai/rag-retriever](https://github.com/codingthefuturewithai/rag-retriever) — A Python application that loads and processes both web pages and local documents, indexing their content using embeddings, and enabling semantic search queries. ☆`28`
- [oso95/domain-suite-mcp](https://github.com/oso95/domain-suite-mcp) — MCP with skills for your agent to do domain and DNS management across Porkbun, Namecheap, GoDaddy and Cloudflare. ☆`23`
- [chatmcp/mcp-server-collector](https://github.com/chatmcp/mcp-server-collector) — A MCP Server used to collect MCP Servers over the internet. ☆`20`
## Security

### Identity & Access

- [auth0/auth0-mcp-server](https://github.com/auth0/auth0-mcp-server) — Auth0 tenant management via natural language ☆`122`
- [hashicorp/vault-mcp-server](https://github.com/hashicorp/vault-mcp-server) — Read secrets and manage HashiCorp Vault policies via MCP. ☆`66`
- [sshaaf/keycloak-mcp-server](https://github.com/sshaaf/keycloak-mcp-server) — MCP server for Keycloak identity and access management ☆`48`
- [ChristophEnglisch/keycloak-model-context-protocol](https://github.com/ChristophEnglisch/keycloak-model-context-protocol) — Keycloak user and realm management ☆`46`
- [firstorderai/authenticator_mcp](https://github.com/firstorderai/authenticator_mcp) — Authenticator App for AI agents ☆`48`
- [atomicchonk/roadrecon_mcp_server](https://github.com/atomicchonk/roadrecon_mcp_server) — Azure AD ROADrecon analysis for Claude ☆`53`
- [hieuttmmo/entraid-mcp-server](https://github.com/hieuttmmo/entraid-mcp-server) — EntraID via Microsoft Graph API ☆`41`
- [descope-sample-apps/descope-mcp-server-stdio](https://github.com/descope-sample-apps/descope-mcp-server-stdio) — Descope user management and audits ☆`38`
- [kapilduraphe/okta-mcp-server](https://github.com/kapilduraphe/okta-mcp-server) — Okta MCP Server ☆`22`
### MCP Security

- [snyk/agent-scan](https://github.com/snyk/agent-scan) — Security scanner for AI agents, MCP servers and agent skills. ☆`3,203`
- [harishsg993010/damn-vulnerable-MCP-server](https://github.com/harishsg993010/damn-vulnerable-MCP-server) — Damn Vulnerable MCP Server ☆`1,364`
- [hashgraph-online/hol-guard](https://github.com/hashgraph-online/hol-guard) — Open-source antivirus and firewall for AI agents: block risky tools, secret access, prompt injection, malicious packages, MCP servers, plugins, and skills at runtime. ☆`1,069`
- [riseandignite/mcp-shield](https://github.com/riseandignite/mcp-shield) — Security scanner for MCP servers ☆`555`
- [bx33661/Wireshark-MCP](https://github.com/bx33661/Wireshark-MCP) — Wireshark-MCP，Give your AI assistant a packet analyzer. Drop a .pcap file, ask questions in plain English - get answers backed by real tshark data. ☆`368`
- [trailofbits/mcp-context-protector](https://github.com/trailofbits/mcp-context-protector) — MCP security wrapper ☆`228`
- [eqtylab/mcp-guardian](https://github.com/eqtylab/mcp-guardian) — Manage / Proxy / Secure your MCP Servers ☆`204`
- [stevenyu113228/BloodHound-MCP](https://github.com/stevenyu113228/BloodHound-MCP) — Enables security professionals to analyze Active Directory and Azure AD environments through natural language queries by connecting to BloodHound's Neo4j database. Provides a... ☆`164`
- [KryptosAI/mcp-observatory](https://github.com/KryptosAI/mcp-observatory) — Free, MIT-licensed MCP security testing from ClearFrame. Scan, audit, compare, and review locally; continue in the ClearFrame CLI or Mac app. ☆`135`
- [kapilduraphe/mcp-watch](https://github.com/kapilduraphe/mcp-watch) — Security scanner for MCP servers ☆`139`
- [mobilehackinglab/jadx-mcp-plugin](https://github.com/mobilehackinglab/jadx-mcp-plugin) — Facilitates decompiler access for Claude by bridging Jadx API over HTTP using MCP, enabling live interaction with decompiled code. ☆`105`
- [dtkmn/mcp-zap-server](https://github.com/dtkmn/mcp-zap-server) — Give AI agents a safe, self-hosted ZAP operator for guided web security scans, findings, reports, and production guardrails. ☆`68`
- [82ch/MCP-Dandan](https://github.com/82ch/MCP-Dandan) — MCP security with real-time proxying ☆`67`
- [snyk/studio-mcp](https://github.com/snyk/studio-mcp) — Embeds Snyk's security engines into agentic workflows to secure AI-generated code in real time and work through vulnerability backlogs faster. ☆`58`
- [postralai/masquerade](https://github.com/postralai/masquerade) — The Privacy Firewall for LLMs ☆`79`
- [pomerium/mcp-app-demo](https://github.com/pomerium/mcp-app-demo) — Demo application showcasing how to build and secure MCP servers and clients with Pomerium using contextual access policies. ☆`51`
- [Synvoya/codeinspectus](https://github.com/Synvoya/codeinspectus) — Local-first MCP security scanner for AI-generated apps. Scan → fix → rescan from Claude Code, Cursor, Codex, and other agents. ☆`50`
- [doublegate/CyberChef-MCP](https://github.com/doublegate/CyberChef-MCP) — Model Context Protocol server for CyberChef - exposes GCHQ's "Cyber Swiss Army Knife" as AI-agent tools: 504 operations across encryption, encoding, compression and forensics, on ☆`32`
- [icoretech/warden-mcp](https://github.com/icoretech/warden-mcp) — Vaultwarden / Bitwarden MCP server for credential-aware AI agents ☆`26`
- [CakeRepository/1Password-MCP](https://github.com/CakeRepository/1Password-MCP) — 1Password MCP server used for storing passwords create separate vault please ☆`22`
- [Acacian/aegis](https://github.com/Acacian/aegis) — LLM guardrails & prompt injection detection for Python. Auto-instruments LangChain, CrewAI, OpenAI, LiteLLM + 8 more frameworks. PII masking, toxicity detection, policy CI/CD. ☆`18`
- [echelongraph/echelongraph-mcp](https://github.com/echelongraph/echelongraph-mcp) — MCP server for CVE intelligence: 16 read-only tools for CVE records, CISA KEV, EPSS history, exploits, fix guidance as sources state it, version, SBOM and lockfile checks, vendor ☆`17`
- [Top-Celestial-Company-Ltd/DROS-VajraClaw-Hacker](https://github.com/Top-Celestial-Company-Ltd/DROS-VajraClaw-Hacker) — DROS™ VajraClaw (Hacker Edition): Free Multi-Agent Runtime Security & Docker Governance Gateway with W3C DID & <1μs Enforcement ☆`16`
- [kontext-security/attestable-mcp-server](https://github.com/kontext-security/attestable-mcp-server) — Hardware attestation for MCP server integrity ☆`22`
- [operantlabs/operant-mcp](https://github.com/operantlabs/operant-mcp) — Turn your AI agent into a hacker by plugging in this MCP ☆`27`
- [MorDavid/Hashcat-MCP](https://github.com/MorDavid/Hashcat-MCP) — MCP wrapper for Hashcat - automate hash cracking with natural language ☆`27`
- [AIM-Intelligence/AIM-MCP](https://github.com/AIM-Intelligence/AIM-MCP) — AIM MCP Server :: Guard and Protect your MCPs & AI Chatting ☆`23`
- [cromwellian/hippycampus](https://github.com/cromwellian/hippycampus) — REST endpoint to MCP conversion ☆`20`
### Network & Firewall

- [pipelab-org/pipelock](https://github.com/pipelab-org/pipelock) — Open-source AI agent firewall for MCP security and agent egress. Scans mediated HTTP, MCP, A2A, and WebSocket traffic for exfiltration, SSRF, and prompt injection, and emits ☆`984`
- [vespo92/OPNSenseMCP](https://github.com/vespo92/OPNSenseMCP) — MCP Server for OPNSense to act as IaC proxy ☆`95`
- [AynOps/AynOps](https://github.com/AynOps/AynOps) — An Open Sourced Model Context Protocol (MCP) Local server that gives AI Clients real-time cybersecurity reconnaissance capabilities ☆`29`
- [girste/CHIHUAUDIT](https://github.com/girste/CHIHUAUDIT) — Linux security audit tool ☆`54`
- [intruder-io/intruder-mcp](https://github.com/intruder-io/intruder-mcp) — An MCP server to let AI agents control Intruder ☆`26`
### Pentesting & OSINT

- [koala73/worldmonitor](https://github.com/koala73/worldmonitor) — Real-time global intelligence dashboard. AI-powered news aggregation, geopolitical monitoring, and infrastructure tracking in a unified situational awareness interface ☆`90,153`
- [Tencent/AI-Infra-Guard](https://github.com/Tencent/AI-Infra-Guard) — A full-stack AI Red Teaming platform securing AI ecosystems via Agent Scan, Skills Scan, MCP scan, AI Infra scan and LLM jailbreak evaluation. ☆`7,377`
- [OpenOSINT/OpenOSINT](https://github.com/OpenOSINT/OpenOSINT) — Open-source engine for passive OSINT checks: 21 tools as CLI, MCP server and web UI. Hosted Monitor & Diligence at app.openosint.tech. ☆`1,850`
- [prompt-security/clawsec](https://github.com/prompt-security/clawsec) — A complete security skill suite for OpenClaw, Hermes, PicoClaw and NanoClaw agents (and variants). Protect your SOUL.md (etc') with drift detection, live security ☆`1,130`
- [marc-shade/world-intel-mcp](https://github.com/marc-shade/world-intel-mcp) — 160-tool MCP server for real-time global intelligence from free public APIs: markets, liquidity, prediction markets, SEC filings, conflict, military, aircraft-cohort early ☆`1,063`
- [w0h1v/mcp-maigret](https://github.com/w0h1v/mcp-maigret) — Maigret OSINT user account collection ☆`269`
- [JeanExtreme002/PyMemoryEditor](https://github.com/JeanExtreme002/PyMemoryEditor) — A pure-Python library, app and MCP that lets you inspect, modify and search the memory of any running process in a few lines of Python :snake: . ☆`225`
- [frishtik/osint-tools-mcp-server](https://github.com/frishtik/osint-tools-mcp-server) — MCP server exposing multiple OSINT tools for AI assistants like Claude ☆`247`
- [OSINT-Experts-Society/Consensus-OSINT](https://github.com/OSINT-Experts-Society/Consensus-OSINT) — Username, email & phone OSINT - 9,700+ lookup checks from 19 projects, with profile enrichment, bulk searches, evidence graphs and expert-reviewed updates. ☆`203`
- [w0h1v/mcp-shodan](https://github.com/w0h1v/mcp-shodan) — MCP server for Shodan - device search, IP recon, CVE intel ☆`186`
- [timescale/rsigma](https://github.com/timescale/rsigma) — A complete Sigma detection engineering toolkit: parser, linter, evaluator, correlation engine, conversion framework, streaming daemon, MCP and LSP servers :crab: ☆`183`
- [w0h1v/mcp-virustotal](https://github.com/w0h1v/mcp-virustotal) — VirusTotal API queries ☆`155`
- [XposedOrNot/XposedOrNot-API](https://github.com/XposedOrNot/XposedOrNot-API) — Open-source API to check if an email has been exposed in a data breach and monitor breaches across your verified domains. Real-time alerts and breach analytics protect your ☆`103`
- [26zl/cybersec-toolkit](https://github.com/26zl/cybersec-toolkit) — One command installs 670+ security tools on Debian/Ubuntu/Kali, Fedora, Arch, openSUSE and Termux. Its authorization-gated MCP server runs them in a disposable Kata Containers VM ☆`87`
- [roadwy/cve-search_mcp](https://github.com/roadwy/cve-search_mcp) — CVE database security queries ☆`109`
- [mobb-dev/bugsy](https://github.com/mobb-dev/bugsy) — Automatic security vulnerability remediation for your code. ☆`68`
- [MediaPublishing/mcp-manager](https://github.com/MediaPublishing/mcp-manager) — A web-based GUI tool for managing Model Context Protocol (MCP) servers in Claude and Cursor ☆`83`
- [Cyreslab-AI/shodan-mcp-server](https://github.com/Cyreslab-AI/shodan-mcp-server) — MCP server for Shodan - host/network recon, CVE and exploit lookup, InternetDB, and persistent alerts (34 tools). ☆`53`
- [w0h1v/mcp-dnstwist](https://github.com/w0h1v/mcp-dnstwist) — DNS fuzzing for phishing detection ☆`51`
- [pollinations/chucknorris](https://github.com/pollinations/chucknorris) — C̷h̷u̷c̷k̷N̷o̷r̷r̷i̷s̷ MCP server: Helping LLMs break limits. Provides enhancement prompts inspired by elder-plinius' L1B3RT4S ☆`69`
- [frangelbarrera/osint-agent-skills](https://github.com/frangelbarrera/osint-agent-skills) — OSINT knowledge base + MCP server for autonomous AI agents - Claude Code, Cursor, Kimi K3, recon & threat intel playbooks. ☆`45`
- [StacklokLabs/osv-mcp](https://github.com/StacklokLabs/osv-mcp) — An MCP server for OSV ☆`44`
- [GitGuardian/ggmcp](https://github.com/GitGuardian/ggmcp) — Scan and remediate hardcoded secrets ☆`41`
- [koda-ai-studio/agent-bom](https://github.com/koda-ai-studio/agent-bom) — AI supply-chain BOM: every agent, MCP server and AI package, and what each one can reach. Open-source scanner and self-hosted control plane for code, containers, cloud and AI. ☆`36`
- [UPinar/contrastapi](https://github.com/UPinar/contrastapi) — MCP server with 55 security intelligence tools - CVE/KEV, MITRE ATLAS+D3FEND, Sigma detection rules, email security posture (SPF/DMARC), domain & web intel, threat intel. ☆`36`
- [vetcoders/mcp-server-semgrep](https://github.com/vetcoders/mcp-server-semgrep) — MCP Server Semgrep is a compliant server that integrates the powerful Semgrep static analysis tool with AI assistants ☆`28`
- [addcontent/nuclei-mcp](https://github.com/addcontent/nuclei-mcp) — An implementation of a Model Context Protocol (MCP) for the Nuclei scanner. This tool enables context-aware vulnerability scanning by intelligently providing models and context ☆`50`
- [sophymarine/openregistry](https://github.com/sophymarine/openregistry) — OpenRegistry - the world's first MCP and API for live company profile, directors, shareholders, financials and filings directly from official government registries worldwide. 90+ ☆`23`
- [mastyf-ai/mastyf.ai](https://github.com/mastyf-ai/mastyf.ai) — Open-source AI security platform providing perimeter defense for LLMs and AI agents through swarm analysis, policy enforcement, adversarial testing, and real-time threat detection. ☆`21`
- [SOsintOps/claudii-exploratores](https://github.com/SOsintOps/claudii-exploratores) — OSINT suite for Claude - 909 curated OSINT tools from Exploratores as an Agent Skill + offline MCP server: indicator classifier, URL builder with VPN/geo-lock warnings, IBAN ☆`21`
- [kontext-security/attestable-mcp-server](https://github.com/kontext-security/attestable-mcp-server) — Verify that any MCP server is running the intended and untampered code via hardware attestation. ☆`22`
- [nickpending/mcp-recon](https://github.com/nickpending/mcp-recon) — Tellix conversational recon interface ☆`31`
- [agentward-ai/agentward](https://github.com/agentward-ai/agentward) — Open-source permission control plane for AI agents. Scan, enforce, and audit every tool call. ☆`19`
- [ajipurn/fida](https://github.com/ajipurn/fida) — a local-first secret leak prevention layer for AI coding agents ☆`19`
- [aak204/MCP-Scorecard](https://github.com/aak204/MCP-Scorecard) — Deterministic CI scanner and surface-risk scoring for MCP (Model Context Protocol) servers. ☆`21`
- [elliotllliu/agent-shield](https://github.com/elliotllliu/agent-shield) — Multi-engine security scanner for AI agents, MCP servers & plugins - 13 engines, one report. ☆`16`
- [gnlds/mcp-cve-intelligence-server-lite](https://github.com/gnlds/mcp-cve-intelligence-server-lite) — CVE intelligence from NVD, MITRE, GitHub ☆`19`
- [Hexix23/shodan-mcp](https://github.com/Hexix23/shodan-mcp) —  ☆`16`
### Reverse Engineering

- [morluto/rea](https://github.com/morluto/rea) — Local CLI and MCP server for agent-assisted reverse engineering. ☆`427,780`
- [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) — IDA Pro reverse engineering with AI ☆`13,345`
- [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) — MCP Server for Ghidra ☆`11,751`
- [zinja-coder/jadx-ai-mcp](https://github.com/zinja-coder/jadx-ai-mcp) — Plugin for JADX to integrate MCP server ☆`2,977`
- [svnscha/mcp-windbg](https://github.com/svnscha/mcp-windbg) — Model Context Protocol for WinDbg. ☆`1,653`
- [LING71671/open-reverselab](https://github.com/LING71671/open-reverselab) — Ghidra, Frida, x64dbg, Rizin, and YARA in one lab ☆`1,335`
- [cyberkaida/reverse-engineering-assistant](https://github.com/cyberkaida/reverse-engineering-assistant) — MCP server for reverse engineering tasks in Ghidra ☆`935`
- [symgraph/GhidrAssistMCP](https://github.com/symgraph/GhidrAssistMCP) — An native MCP server extension for Ghidra ☆`804`
- [zinja-coder/apktool-mcp-server](https://github.com/zinja-coder/apktool-mcp-server) — APK Tool for Android reverse engineering ☆`707`
- [fosdickio/binary_ninja_mcp](https://github.com/fosdickio/binary_ninja_mcp) — Binary Ninja plugin for LLM integration ☆`455`
- [radareorg/radare2-mcp](https://github.com/radareorg/radare2-mcp) — MCP stdio server for radare2 ☆`348`
- [taida957789/ida-mcp-server-plugin](https://github.com/taida957789/ida-mcp-server-plugin) — IDA Pro Plugin for serving MCP SSE server for cursor / claude ☆`191`
- [13bm/GhidraMCP](https://github.com/13bm/GhidraMCP) — Active Socket based MCP Server for Ghidra ☆`150`
- [NadavLor/windbg-ext-mcp](https://github.com/NadavLor/windbg-ext-mcp) — WinDbg-ext-MCP bridges your favorite LLM client (like Cursor, Claude, or VS Code) with WinDbg, enabling real-time, AI assisted kernel debugging. Write prompts in your AI coding ☆`118`
- [fdrechsler/mcp-server-idapro](https://github.com/fdrechsler/mcp-server-idapro) — A Model Context Protocol (MCP) server that enables AI assistants to interact with IDA Pro for reverse engineering and binary analysis tasks. ☆`103`
- [Invoke-RE/binja-lattice-mcp](https://github.com/Invoke-RE/binja-lattice-mcp) — Plugin interface for remote communications with Binary Ninja database and MCP server for interfacing with LLMs. ☆`67`
- [MCPPhalanx/binaryninja-mcp](https://github.com/MCPPhalanx/binaryninja-mcp) — Another™ MCP Server for Binary Ninja with superpower ☆`52`
- [pullkitsan/mobsf-mcp-server](https://github.com/pullkitsan/mobsf-mcp-server) — MobSF APK and IPA security scanning ☆`24`
### SIEM & SecOps

- [beelzebub-labs/beelzebub](https://github.com/beelzebub-labs/beelzebub) — Low-code honeypot with AI virtualization ☆`2,230`
- [MorDavid/BloodHound-MCP-AI](https://github.com/MorDavid/BloodHound-MCP-AI) — BloodHound integration with AI through MCP ☆`383`
- [CrowdStrike/falcon-mcp](https://github.com/CrowdStrike/falcon-mcp) — CrowdStrike Falcon security analysis ☆`277`
- [gbrigandi/mcp-server-wazuh](https://github.com/gbrigandi/mcp-server-wazuh) — MCP Server for Wazuh SIEM ☆`241`
- [securityfortech/secops-mcp](https://github.com/securityfortech/secops-mcp) — All-in-one security testing toolbox via MCP ☆`219`
- [cycodehq/cycode-cli](https://github.com/cycodehq/cycode-cli) — SAST, SCA, Secrets, IaC security scanning ☆`99`
- [Farenhytee/database-sentinel](https://github.com/Farenhytee/database-sentinel) — Open-source security audits for Supabase: a read-only MCP server, a CLI agent and a Claude Skill. Finds RLS misconfigurations, exposed keys and risky functions, and returns a ☆`51`
- [panther-labs/mcp-panther](https://github.com/panther-labs/mcp-panther) — Detections, alerts, and log queries ☆`47`
- [qianniuspace/mcp-security-audit](https://github.com/qianniuspace/mcp-security-audit) — MCP server for security auditing ☆`58`
- [zxzinn/opencti-mcp](https://github.com/zxzinn/opencti-mcp) — OpenCTI threat intelligence platform ☆`42`
- [Gaffx/volatility-mcp](https://github.com/Gaffx/volatility-mcp) — This repo hosts an MCP server for volatility3.x ☆`53`
- [fr0gger/MCP_Security](https://github.com/fr0gger/MCP_Security) — This is a repository to experiment with MCP for security ☆`52`
- [slouchd/cyberchef-api-mcp-server](https://github.com/slouchd/cyberchef-api-mcp-server) — CyberChef API MCP Server ☆`44`
- [Contrast-Security-OSS/mcp-contrast](https://github.com/Contrast-Security-OSS/mcp-contrast) — MCP Server for Contrast Security ☆`23`
- [mcp-hangar/mcp-hangar](https://github.com/mcp-hangar/mcp-hangar) — MCP policy enforcement plane - deterministic policy on every Model Context Protocol call: identity, RFC 8707 audience binding, tool schema digest pinning, full audit trail. ☆`17`
- [jyjune/mcp_vms](https://github.com/jyjune/mcp_vms) — MCP server for controlling and accessing a video surveillance system ☆`17`
- [gbrigandi/mcp-server-cortex](https://github.com/gbrigandi/mcp-server-cortex) — MCP Server for Cortex ☆`17`
- [gbrigandi/mcp-server-thehive](https://github.com/gbrigandi/mcp-server-thehive) — MCP Server for TheHive ☆`16`
## Social Media

- [iFurySt/RedNote-MCP](https://github.com/iFurySt/RedNote-MCP) — MCP server for accessing RedNote(XiaoHongShu, xhs). ☆`1,129`
- [karanb192/reddit-mcp-buddy](https://github.com/karanb192/reddit-mcp-buddy) — Clean Reddit data: posts, search, users ☆`877`
- [dialog-tools/reddit-research-mcp](https://github.com/dialog-tools/reddit-research-mcp) — Reddit research with structured insights ☆`261`
- [Xquik-dev/x-twitter-scraper](https://github.com/Xquik-dev/x-twitter-scraper) — X/Twitter search, profiles, posting, and media download ☆`227`
- [HagaiHen/facebook-mcp-server](https://github.com/HagaiHen/facebook-mcp-server) — Facebook posts, comments, insights automation ☆`234`
- [taisly/agent](https://github.com/taisly/agent) — Taisly Agent Kit: MCP server, CLI, SDK, and agent docs for publishing videos to TikTok, Reels, Shorts, X, and Facebook. ☆`222`
- [adhikasp/mcp-twikit](https://github.com/adhikasp/mcp-twikit) — Twitter interaction via MCP ☆`237`
- [Seym0n/tiktok-mcp](https://github.com/Seym0n/tiktok-mcp) — Model Context Protocol (MCP) with TikTok integration ☆`208`
- [34892002/bilibili-mcp-js](https://github.com/34892002/bilibili-mcp-js) — Bilibili video search MCP service ☆`197`
- [ihuzaifashoukat/x-use](https://github.com/ihuzaifashoukat/x-use) — MCP server for X (Twitter). Research profiles, read inboxes, and review posts, replies and outreach with AI clients. Python, multi-account, no X API key required. ☆`180`
- [sparfenyuk/mcp-telegram](https://github.com/sparfenyuk/mcp-telegram) — MCP server to work with Telegram through MTProto ☆`190`
- [trypeggy/instagram_dm_mcp](https://github.com/trypeggy/instagram_dm_mcp) — Instagram Direct messages MCP ☆`188`
- [hanweg/mcp-discord](https://github.com/hanweg/mcp-discord) — MCP server for discord bot ☆`166`
- [anwerj/youtube-uploader-mcp](https://github.com/anwerj/youtube-uploader-mcp) — Upload, update, and schedule YouTube videos ☆`64`
- [conorbronsdon/substack-mcp](https://github.com/conorbronsdon/substack-mcp) — MCP server for Substack: rich drafts, Notes, analytics, and consented subscriber management across publications. Long-form posts stay draft-only; Notes publish immediately. Used ☆`45`
- [vidhupv/x-mcp](https://github.com/vidhupv/x-mcp) — An MCP server to create, manage and publish X/Twitter posts directly through Claude chat. ☆`61`
- [mikusnuz/meta-mcp](https://github.com/mikusnuz/meta-mcp) — MCP server for Instagram Graph API, Threads API & Meta platform - 57 tools with Graph API v25.0 ☆`31`
- [jaipandya/producthunt-mcp-server](https://github.com/jaipandya/producthunt-mcp-server) — MCP server for Product Hunt data access ☆`56`
- [macrocosm-os/macrocosmos-mcp](https://github.com/macrocosm-os/macrocosmos-mcp) — The MCP for macrocosmos subnets. ☆`29`
- [AstaBlackClove/posthive](https://github.com/AstaBlackClove/posthive) — Agentic social media scheduler to post on multi platforms with built-in MCP ☆`25`
- [bulatko/vk-mcp-server](https://github.com/bulatko/vk-mcp-server) — Model Context Protocol (MCP) server for VK (VKontakte) social network API ☆`16`
- [AbdelStark/nostr-mcp](https://github.com/AbdelStark/nostr-mcp) — Nostr posting and interaction ☆`39`
- [lumizone/postsider](https://github.com/lumizone/postsider) — Open-source social media scheduling for 30+ platforms, with a public API, SDK and MCP server. ☆`16`
- [ertiqah/linkedin-mcp-runner](https://github.com/ertiqah/linkedin-mcp-runner) — LinkedIn content analysis and posting ☆`31`
- [laulauland/bluesky-context-server](https://github.com/laulauland/bluesky-context-server) — Bluesky MCP server ☆`35`
- [jonathan-politzki/mcp-writer-substack](https://github.com/jonathan-politzki/mcp-writer-substack) — Bridge Substack writings to Claude ☆`34`
- [mbelinky/x-mcp-server](https://github.com/mbelinky/x-mcp-server) — MCP server to post on x.com with OAuth v1 and v2 ☆`24`
- [gwbischof/bluesky-social-mcp](https://github.com/gwbischof/bluesky-social-mcp) — A Bluesky MCP ☆`16`
## Sports

- [r-huijts/strava-mcp](https://github.com/r-huijts/strava-mcp) — Strava fitness data integration ☆`502`
- [JamsusMaximus/trainingpeaks-mcp](https://github.com/JamsusMaximus/trainingpeaks-mcp) — TrainingPeaks MCP server for Claude Desktop, Code and Cowork. No API approval needed - works with any account. Query workouts, CTL/ATL/TSB fitness data, power PRs via natural ☆`194`
- [livetennisapi/livetennisapi-mcp](https://github.com/livetennisapi/livetennisapi-mcp) — MCP server for the Live Tennis API. Gives LLM agents in Claude, Cursor and other MCP clients real-time tennis scores, odds and model win-probability. ☆`148`
- [krmisystems/fantasy-football-manager](https://github.com/krmisystems/fantasy-football-manager) — ESPN draft and lineup tools for Codex and other MCP clients, with browser sign-in, approval modes, per-team limits, and server monitoring. ☆`88`
- [rishijatia/fantasy-pl-mcp](https://github.com/rishijatia/fantasy-pl-mcp) — Fantasy Premier League MCP Server ☆`80`
- [guillochon/mlb-api-mcp](https://github.com/guillochon/mlb-api-mcp) — MCP server for MLB baseball statistics ☆`59`
- [lacausecrypto/mcp-sports-hub](https://github.com/lacausecrypto/mcp-sports-hub) — Unified MCP server - 41 sports API providers, 396 tools in one process: scores, stats, odds, esports, F1/MotoGP/NASCAR, EuroLeague, chess, AFL, boxing & more across 70+ sports. ☆`40`
- [googlarz/suunto-mcp](https://github.com/googlarz/suunto-mcp) — MCP server that connects your Suunto watch data to Claude and other AI assistants ☆`39`
- [jordanlyall/wc26-mcp](https://github.com/jordanlyall/wc26-mcp) — AI companion for FIFA World Cup 2026 - 18 tools covering matches, teams, venues, city guides, fan zones, visa info, head-to-head records, and more. Works with Claude, ChatGPT, ☆`34`
- [DanielTomaro13/sportsdata-mcp](https://github.com/DanielTomaro13/sportsdata-mcp) — Free, open-source sports-data MCP server - 841 tools across 64 providers: cross-book betting odds, official league stats, racing, fantasy, cricket, F1 and more. 44 providers need ☆`32`
- [RobSpectre/mvf1](https://github.com/RobSpectre/mvf1) — Python package and CLI for MultiViewer For F1 ☆`20`
- [PeanutSplash/chelaile-mcp](https://github.com/PeanutSplash/chelaile-mcp) — MCP server for 车来了 realtime bus data ☆`35`
- [drivly/auto-dev-skill](https://github.com/drivly/auto-dev-skill) — Automotive Data for AI Agents ☆`19`
- [yeonupark/mcp-soccer-data](https://github.com/yeonupark/mcp-soccer-data) — Real-time football data ☆`39`
- [mikechao/balldontlie-mcp](https://github.com/mikechao/balldontlie-mcp) — MCP server for NBA, NFL, MLB sports data ☆`26`
- [smamidipaka6/flights-mcp-server](https://github.com/smamidipaka6/flights-mcp-server) — MCP Server for Google Flights !! ☆`30`
- [lenwood/cfbd-mcp-server](https://github.com/lenwood/cfbd-mcp-server) — An MCP server enabling CFBD API queries within Claude Desktop. ☆`27`
- [amith-vp/indian-railway-mcp](https://github.com/amith-vp/indian-railway-mcp) — MCP server for Indian Railway data. Search trains, check seat availability, get live statuses, delay info, station/train codes, and more - all via a simple Claude Desktop ☆`28`
- [kw510/strava-mcp](https://github.com/kw510/strava-mcp) — MCP server with Strava OAuth on Cloudflare Workers ☆`26`
- [tomekkorbak/strava-mcp-server](https://github.com/tomekkorbak/strava-mcp-server) — MCP server for Strava API integration ☆`25`
- [salamentic/google-flights-mcp](https://github.com/salamentic/google-flights-mcp) — Facilitates travel agent-level flight planning using the fast-flights API, offering seamless integration with Claude Desktop. ☆`22`
- [willvelida/mcp-afl-server](https://github.com/willvelida/mcp-afl-server) — Australian Football League data from Squiggle ☆`18`
- [r-huijts/firstcycling-mcp](https://github.com/r-huijts/firstcycling-mcp) — MCP server for professional cycling data from FirstCycling ☆`18`
## Text-to-Speech

- [mbailey/voicemode](https://github.com/mbailey/voicemode) — Natural voice conversations with Claude Code ☆`1,436`
- [mberg/kokoro-tts-mcp](https://github.com/mberg/kokoro-tts-mcp) — Kokoro Text to Speech (TTS) MCP Server ☆`83`
- [cartesia-ai/cartesia-mcp](https://github.com/cartesia-ai/cartesia-mcp) — The official Cartesia MCP Server ☆`17`
- [ybouhjira/claude-code-tts](https://github.com/ybouhjira/claude-code-tts) — Text-to-Speech MCP plugin for Claude Code - hear audio feedback while coding (OpenAI TTS) ☆`21`
## Translation

- [caol64/wenyan-mcp](https://github.com/caol64/wenyan-mcp) — Markdown formatting and translation to Chinese ☆`1,354`
- [aymericzip/intlayer](https://github.com/aymericzip/intlayer) — MCP server for Intlayer internationalization ☆`863`
- [DeepL/deepl-mcp-server](https://github.com/DeepL/deepl-mcp-server) — Translation with DeepL API ☆`120`
- [translated/lara-mcp](https://github.com/translated/lara-mcp) — Lara Translate API with language detection ☆`100`
- [mmntm/weblate-mcp](https://github.com/mmntm/weblate-mcp) — Manage Weblate projects, components, and translations ☆`24`
## Travel & Transport

- [Joooook/12306-mcp](https://github.com/Joooook/12306-mcp) — This is a 12306 ticket search server based on the Model Context Protocol (MCP). ☆`2,422`
- [LetsFG/LetsFG](https://github.com/LetsFG/LetsFG) — Agent-native flight & hotel search and booking - MCP server, CLI, and Python/JS SDKs. Every airline in the world, major booking sites and OTAs, with per-flight reliability history. ☆`2,229`
- [openbnb-org/mcp-server-airbnb](https://github.com/openbnb-org/mcp-server-airbnb) — Search Airbnb using your AI Agent ☆`556`
- [shaikhspeare/wanderlog-mcp](https://github.com/shaikhspeare/wanderlog-mcp) — MCP server for Wanderlog - build and edit trip itineraries through conversation ☆`169`
- [cobanov/teslamate-mcp](https://github.com/cobanov/teslamate-mcp) — MCP server for TeslaMate vehicle data and analytics ☆`142`
- [r-huijts/ns-mcp-server](https://github.com/r-huijts/ns-mcp-server) — MCP server for Dutch Railways (NS) travel information ☆`64`
- [pab1it0/tripadvisor-mcp](https://github.com/pab1it0/tripadvisor-mcp) — MCP server for Tripadvisor location data and reviews ☆`64`
- [donghyun-chae/mcp-amadeus](https://github.com/donghyun-chae/mcp-amadeus) — Amadeus MCP(Model Context Protocol) Server ☆`60`
- [variflight/variflight-mcp](https://github.com/variflight/variflight-mcp) — Variflight services implementation ☆`33`
- [Pradumnasaraf/aviationstack-mcp](https://github.com/Pradumnasaraf/aviationstack-mcp) — MCP for AviationStack API - real-time flight data ☆`28`
- [sunsetcoder/flightradar24-mcp-server](https://github.com/sunsetcoder/flightradar24-mcp-server) — Model Context Protocol server for Flight Tracking ☆`47`
- [KyrieTangSheng/mcp-server-nationalparks](https://github.com/KyrieTangSheng/mcp-server-nationalparks) — US National Parks info via NPS API ☆`41`
- [mfukushim/map-traveler-mcp](https://github.com/mfukushim/map-traveler-mcp) — Virtual traveler library for MCP ☆`24`
- [JordanDalton/DoorDash-MCP-Server](https://github.com/JordanDalton/DoorDash-MCP-Server) — MCP server for DoorDash delivery service integration ☆`25`
- [campertunity/mcp-server](https://github.com/campertunity/mcp-server) — Search campgrounds, check availability, and book campsites ☆`17`
## Web Scraping

- [ScrapeGraphAI/Scrapegraph-ai](https://github.com/ScrapeGraphAI/Scrapegraph-ai) — Python scraper based on AI ☆`32,473`
- [apify/apify-mcp-server](https://github.com/apify/apify-mcp-server) — MCP server for Apify web scraping and data extraction ☆`14,622`
- [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server) — Web scraping and search for LLM clients ☆`7,761`
- [KnockOutEZ/wigolo](https://github.com/KnockOutEZ/wigolo) — The go-to web for your AI coding agent - local-first search, fetch, crawl & research over MCP. No API keys, no cloud, $0/query. Public beta. ☆`5,527`
- [brightdata/brightdata-mcp](https://github.com/brightdata/brightdata-mcp) — All-in-one public web access solution ☆`2,709`
- [0xMassi/webclaw](https://github.com/0xMassi/webclaw) — Fast, local-first web content extraction for LLMs. Scrape, crawl, extract structured data - all from Rust. CLI, REST API, and MCP server. ☆`2,428`
- [fastcrw/crw](https://github.com/fastcrw/crw) — Fast, lightweight Firecrawl/Tavily alternative in Rust. Web scraper, crawler & search API with MCP server for AI agents. Drop-in Firecrawl-compatible API (/scrape, /crawl, ☆`1,226`
- [jae-jae/fetcher-mcp](https://github.com/jae-jae/fetcher-mcp) — Playwright web page content fetching ☆`1,088`
- [etsd-tech/mcp-pointer](https://github.com/etsd-tech/mcp-pointer) — DOM element pointing for agents ☆`599`
- [eliasbiondo/linkedin-mcp-server](https://github.com/eliasbiondo/linkedin-mcp-server) — A Model Context Protocol (MCP) server for LinkedIn - search people, companies, and jobs, scrape profiles, and get structured data via any MCP-compatible AI client. ☆`212`
- [tinyfish-io/agentql-mcp](https://github.com/tinyfish-io/agentql-mcp) — AgentQL data extraction integration ☆`182`
- [scrapeless-ai/scrapeless-mcp-server](https://github.com/scrapeless-ai/scrapeless-mcp-server) — Scrapeless Mcp Server ☆`170`
- [just-every/mcp-read-website-fast](https://github.com/just-every/mcp-read-website-fast) — Fast webpage to markdown conversion ☆`163`
- [pskill9/website-downloader](https://github.com/pskill9/website-downloader) — MCP server to download entire websites ☆`157`
- [cyberchitta/scrapling-fetch-mcp](https://github.com/cyberchitta/scrapling-fetch-mcp) — Access bot-protected websites ☆`127`
- [just-every/mcp-screenshot-website-fast](https://github.com/just-every/mcp-screenshot-website-fast) — Fast webpage screenshots for LLMs ☆`111`
- [oxylabs/oxylabs-mcp](https://github.com/oxylabs/oxylabs-mcp) — Official Oxylabs MCP integration ☆`104`
- [supadata-ai/mcp](https://github.com/supadata-ai/mcp) — Video and web scraping for Claude ☆`63`
- [pragmar/mcp-server-webcrawl](https://github.com/pragmar/mcp-server-webcrawl) — Web crawler data and archives connection ☆`46`
- [webscraping-ai/webscraping-ai-mcp-server](https://github.com/webscraping-ai/webscraping-ai-mcp-server) — MCP server for AI-powered web scraping ☆`45`
- [crawlbase/crawlbase-mcp](https://github.com/crawlbase/crawlbase-mcp) — MCP server connecting AI agents with real-time web data ☆`60`
- [Decodo/mcp-server](https://github.com/Decodo/mcp-server) — Decodo web scraping for MCP clients ☆`39`
- [puremd/puremd-mcp](https://github.com/puremd/puremd-mcp) — Unblock, scrape, and search tools for MCP clients ☆`60`
- [ananddtyagi/webpage-screenshot-mcp](https://github.com/ananddtyagi/webpage-screenshot-mcp) — MCP server for webpage screenshot capture ☆`55`
- [djannot/puppeteer-vision-mcp](https://github.com/djannot/puppeteer-vision-mcp) — Web scraping with AI-driven interaction handling ☆`48`
- [olostep/olostep-mcp-server](https://github.com/olostep/olostep-mcp-server) — Live web scrape, crawl, batch extract, and search ☆`25`
- [wong2/mcp-jina-reader](https://github.com/wong2/mcp-jina-reader) — Jina Reader MCP Server ☆`47`
- [DevEnterpriseSoftware/scrapi-mcp](https://github.com/DevEnterpriseSoftware/scrapi-mcp) — MCP server for using ScrAPI to scrape web pages. ☆`18`
- [levz0r/html-to-markdown-mcp](https://github.com/levz0r/html-to-markdown-mcp) — HTML to Markdown converter using Turndown ☆`26`
- [rohanrav/screeny](https://github.com/rohanrav/screeny) — Screeny is a privacy-focused macOS MCP server enabling AI agents to capture screenshots of user-approved windows ☆`18`
## E-Commerce

- [Azure-Samples/eShopLite](https://github.com/Azure-Samples/eShopLite) — eShopLite is a set of reference .NET applications implementing an eCommerce site with features like Semantic Search, MCP, Reasoning models and more. ☆`169`
- [nicktcode/swissgroceries-mcp](https://github.com/nicktcode/swissgroceries-mcp) — MCP server for Swiss grocery stores: Migros, Coop, Aldi, Denner, Lidl ☆`41`
- [Dudude-bit/yandex-lavka-mcp](https://github.com/Dudude-bit/yandex-lavka-mcp) — Unofficial MCP server for ordering Yandex Lavka groceries from an AI assistant (search, cart, checkout with confirmation) ☆`25`
- [arthurpanhku/DragonMCP](https://github.com/arthurpanhku/DragonMCP) — DragonMCP is a Model Context Protocol (MCP) server designed for AI Agents to interact with local life services in Greater China (Mainland China, HKSAR) and Asia. DragonMCP 是一个专为 ☆`22`
- [nexscope-ai/nexscope-ecommerce-api](https://github.com/nexscope-ai/nexscope-ecommerce-api) — Ecommerce data and creative AI APIs for marketplace research, product imagery, and video generation, with documentation and code examples. ☆`18`
- [uju777/coupang-mcp](https://github.com/uju777/coupang-mcp) — Claude/Cursor에서 쿠팡 검색. 최저가 비교, 로켓배송 표시, 중고상품도 검색됨. API 키 불필요. ☆`18`
## Legal

- [chrisryugj/korean-law-mcp](https://github.com/chrisryugj/korean-law-mcp) — 법령·판례를 AI가 찾고 인용까지 검증하는 MCP 서버 - 법제처 API 42개를 도구 10개로: 법령·조문·별표, 판례·헌재·해석례 23개 도메인, 조례 정비 레이더, 신구조문대비표 | MCP server for Korean law - statutes, precedents, ordinances, comparison ☆`2,836`
- [ilhamfp/pasal](https://github.com/ilhamfp/pasal) — Pasal.id - The first open, AI-native Indonesian legal platform. MCP server + REST API + web app giving AI grounded access Indonesian laws. ☆`285`
- [lawchat-oss/mcp-taiwan-legal-db](https://github.com/lawchat-oss/mcp-taiwan-legal-db) — 台灣司法院判決 + 全國法規資料庫 MCP server · Query Taiwan legal data from any MCP AI agent ☆`226`
- [dealfluence/adeu](https://github.com/dealfluence/adeu) — docx ↔ LLM translator. Projects .docx office files to Markdown for editing. Projects edits back to OOXML as tracked changes (redlines). Python and Node.js implementations. ☆`170`
- [AI-WorkDeck/aiworkdeck](https://github.com/AI-WorkDeck/aiworkdeck) — Open-source AI workspace shaped by everyday legal practice and colleagues' feedback, developed with team support. Documents, reviewable AI edits, linked sources, and project ☆`169`
- [ayunis-core/ayunis-legal-mcp](https://github.com/ayunis-core/ayunis-legal-mcp) — An MCP server for German legal codes ☆`91`
- [sboghossian/master-claude-for-legal](https://github.com/sboghossian/master-claude-for-legal) — Master skill pack for legal teams using Claude. References, starter skills, templates, and the source webinar dataset. Built from Anthropic's Claude for Legal Teams webinar + ☆`77`
- [Mahender22/legal-mcp](https://github.com/Mahender22/legal-mcp) — The first comprehensive US legal MCP server -- case law, citations, practice management, and court filings for AI assistants ☆`68`
- [veronica-builds/emilie](https://github.com/veronica-builds/emilie) — Swiss sovereign legal AI. Fork of Mike, extended with MCP client and local model support (Apertus). Named after Emilie Kempin-Spyri. ☆`32`
- [agentic-ops/legal-mcp](https://github.com/agentic-ops/legal-mcp) — A comprehensive MCP Server for legal workflows - seeking legal professionals for case study collaboration ☆`40`
- [numikel/law-scrapper-mcp](https://github.com/numikel/law-scrapper-mcp) — A comprehensive Model Context Protocol (MCP) server for accessing and analyzing Polish legal acts from the Sejm API, enabling AI-powered legal research and document analysis. ☆`23`
- [Honeyfield-Org/ris-mcp-ts](https://github.com/Honeyfield-Org/ris-mcp-ts) — MCP Server for the Austrian Legal Information System (RIS) - Access Austrian federal laws, state laws, court decisions and more ☆`20`
- [matematicsolutions/patron](https://github.com/matematicsolutions/patron) — Local-first AI workspace for law firms: case files stay on your machine, local or chosen cloud model, hash-chained audit trail with its own verifier. 9 editions. AGPL-3.0. ☆`16`
- [protomated/legal-context-ce](https://github.com/protomated/legal-context-ce) — LegalContext is an open-source Model Context Protocol (MCP) server that creates a secure, standardized bridge between law firms' document management systems (specifically Clio) ☆`29`
- [yoda-digital/mcp-cerebra-legal-server](https://github.com/yoda-digital/mcp-cerebra-legal-server) — Cerebra Legal is an enterprise-grade server for legal reasoning and analysis, offering domain-specific tools for structured legal thinking, follow-up questioning, and result... ☆`33`
## Speech-to-Text

- [korovin-aa97/talkthrough-mcp](https://github.com/korovin-aa97/talkthrough-mcp) — Recordings in. Agent-ready evidence out. Local-first MCP for transcripts, keyframes, OCR, speakers, and wall-clock evidence. ☆`33`


---

## 🏆 Top 100 by Stars

> The most starred projects in this list, sorted by GitHub stars.

1. [morluto/rea](https://github.com/morluto/rea) — Local CLI and MCP server for agent-assisted reverse engineering. ☆`427,780`
1. [koala73/worldmonitor](https://github.com/koala73/worldmonitor) — Real-time global intelligence dashboard. AI-powered news aggregation, geopolitical monitoring, and infrastructure tracking in a unified situational awareness interface ☆`90,153`
1. [lobehub/lobehub](https://github.com/lobehub/lobehub) — LobeHub is your Chief Agent Operator, organizing your agents into 7×24 operations by hiring, scheduling, and reporting on your entire AI team. ☆`83,869`
1. [upstash/context7](https://github.com/upstash/context7) — Up-to-date code docs for LLMs ☆`64,156`
1. [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) — Hindsight: Agent Memory That Learns ☆`58,564`
1. [aaif-goose/goose](https://github.com/aaif-goose/goose) — an open source, extensible AI agent that goes beyond code suggestions - install, execute, edit, and test with any LLM ☆`56,224`
1. [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) — Chrome DevTools for coding agents ☆`54,747`
1. [CherryHQ/cherry-studio](https://github.com/CherryHQ/cherry-studio) — Your AI workspace for models, agents, and productivity. ☆`53,256`
1. [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) — Local code intelligence for developers and AI agents. Connect code, docs and infrastructure in a persistent graph, with CBM Lens, MCP tools, agent integrations and change-aware ☆`48,109`
1. [LibreChat-AI/LibreChat](https://github.com/LibreChat-AI/LibreChat) — Enhanced ChatGPT Clone: Features Agents, MCP, Skills, DeepSeek, Anthropic, AWS, OpenAI, Responses API, Azure, Groq, o1, GPT-5, Mistral, OpenRouter, Vertex AI, Gemini, Artifacts, ☆`46,739`
1. [mindsdb/mindshub](https://github.com/mindsdb/mindshub) — Query Engine for AI Analytics - self-reasoning agents on live data ☆`39,833`
1. [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) — Playwright MCP server ☆`39,148`
1. [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) — "Vibe-Trading: Your Personal Trading Agent" ☆`37,639`
1. [DayuanJiang/next-ai-draw-io](https://github.com/DayuanJiang/next-ai-draw-io) — Draw and edit draw.io diagrams by chatting with an AI. Web app, desktop app, and an MCP server for Claude Code, Cursor, Codex and VS Code. ☆`36,682`
1. [github/github-mcp-server](https://github.com/github/github-mcp-server) — GitHub's official MCP Server ☆`34,205`
1. [ScrapeGraphAI/Scrapegraph-ai](https://github.com/ScrapeGraphAI/Scrapegraph-ai) — Python scraper based on AI ☆`32,473`
1. [trycua/cua](https://github.com/trycua/cua) — MCP server for CUA platform ☆`31,692`
1. [oraios/serena](https://github.com/oraios/serena) — Semantic code retrieval and editing toolkit ☆`31,071`
1. [assafelovic/gpt-researcher](https://github.com/assafelovic/gpt-researcher) — An autonomous agent that conducts deep research on any data using any LLM providers ☆`30,480`
1. [mastra-ai/mastra](https://github.com/mastra-ai/mastra) — TypeScript AI agent framework with RAG ☆`29,318`
1. [PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp) — Python framework for building MCP servers and clients ☆`28,294`
1. [PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp) — The fast, Pythonic way to build MCP servers and clients. ☆`28,294`
1. [modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk) — The official Python SDK for Model Context Protocol servers and clients ☆`24,758`
1. [Skyvern-AI/skyvern](https://github.com/Skyvern-AI/skyvern) — Automate browser based workflows with AI ☆`23,336`
1. [czlonkowski/n8n-mcp](https://github.com/czlonkowski/n8n-mcp) — Build n8n workflows with AI assistants ☆`23,208`
1. [screenpipe/screenpipe](https://github.com/screenpipe/screenpipe) — Searchable screen text and audio history via MCP; source-available under the Screenpipe Commercial License ☆`22,226`
1. [rocketride-org/rocketride-server](https://github.com/rocketride-org/rocketride-server) — High-performance AI pipeline engine with a C++ core and 50+ Python-extensible nodes. Build, debug, and scale LLM workflows with 13+ model providers, 8+ vector databases, and ☆`19,899`
1. [microsoft/mcp-for-beginners](https://github.com/microsoft/mcp-for-beginners) — This open-source curriculum introduces the fundamentals of Model Context Protocol (MCP) through real-world, cross-language examples in .NET, Java, TypeScript, JavaScript, Rust ☆`17,602`
1. [apache/apisix](https://github.com/apache/apisix) — The Cloud-Native API Gateway and AI Gateway ☆`17,292`
1. [googleapis/mcp-toolbox](https://github.com/googleapis/mcp-toolbox) — Open source database MCP toolbox ☆`16,797`
1. [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) — Figma layout info for AI coding agents ☆`16,150`
1. [apify/apify-mcp-server](https://github.com/apify/apify-mcp-server) — MCP server for Apify web scraping and data extraction ☆`14,622`
1. [modelcontextprotocol/typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk) — The official TypeScript SDK for Model Context Protocol servers and clients ☆`13,706`
1. [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) — IDA Pro reverse engineering with AI ☆`13,345`
1. [elie222/inbox-zero](https://github.com/elie222/inbox-zero) — AI email assistant for inbox zero ☆`12,906`
1. [zilliztech/claude-context](https://github.com/zilliztech/claude-context) — Code search for Claude Code agents ☆`12,668`
1. [tadata-org/fastapi_mcp](https://github.com/tadata-org/fastapi_mcp) — Expose FastAPI endpoints as MCP tools ☆`12,026`
1. [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) — MCP Server for Ghidra ☆`11,751`
1. [modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector) — Deterministic testing tools for MCP servers ☆`11,229`
1. [mcp-use/mcp-use](https://github.com/mcp-use/mcp-use) — The fullstack MCP framework to develop MCP Apps for ChatGPT / Claude & MCP Servers for AI Agents. ☆`10,845`
1. [instantdb/instant](https://github.com/instantdb/instant) — Modern Firebase with real-time database ☆`10,563`
1. [mobile-next/mobile-mcp](https://github.com/mobile-next/mobile-mcp) — Mobile automation for iOS, Android, emulators ☆`10,277`
1. [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) — Terminal control, file search, diff editing ☆`10,208`
1. [awslabs/mcp](https://github.com/awslabs/mcp) — AWS MCP servers for AI assistants ☆`9,874`
1. [modelcontextprotocol/modelcontextprotocol](https://github.com/modelcontextprotocol/modelcontextprotocol) — Specification and documentation for the Model Context Protocol ☆`9,613`
1. [maximhq/bifrost](https://github.com/maximhq/bifrost) — Open-source, high-performance AI gateway that works as your LLM gateway, MCP gateway and agent gateway. One OpenAI-compatible API for 10,000+ models, with failover, load ☆`9,331`
1. [mark3labs/mcp-go](https://github.com/mark3labs/mcp-go) — Go implementation of MCP ☆`9,217`
1. [superradcompany/microsandbox](https://github.com/superradcompany/microsandbox) — easy, fast, programmable and local-first microVM runtime and library ☆`8,939`
1. [lastmile-ai/mcp-agent](https://github.com/lastmile-ai/mcp-agent) — Build agents with MCP and workflow patterns ☆`8,575`
1. [idosal/git-mcp](https://github.com/idosal/git-mcp) — Free remote MCP for any GitHub project ☆`8,505`
1. [repowise-dev/repowise](https://github.com/repowise-dev/repowise) — Codebase intelligence for AI and humans: code health scores, auto-generated docs, git analytics, dead code detection, and architectural decisions via MCP. ☆`8,133`
1. [Upsonic/Upsonic](https://github.com/Upsonic/Upsonic) — Build autonomous AI agents in Python. ☆`7,969`
1. [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server) — Web scraping and search for LLM clients ☆`7,761`
1. [modelcontextprotocol/registry](https://github.com/modelcontextprotocol/registry) — A community driven registry service for Model Context Protocol (MCP) servers. ☆`7,435`
1. [Tencent/AI-Infra-Guard](https://github.com/Tencent/AI-Infra-Guard) — A full-stack AI Red Teaming platform securing AI ecosystems via Agent Scan, Skills Scan, MCP scan, AI Infra scan and LLM jailbreak evaluation. ☆`7,377`
1. [BrowserMCP/mcp](https://github.com/BrowserMCP/mcp) — Browser control for AI applications ☆`7,285`
1. [grab/cursor-talk-to-figma-mcp](https://github.com/grab/cursor-talk-to-figma-mcp) — Cursor and Figma communication ☆`7,076`
1. [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) — WhatsApp MCP server ☆`6,801`
1. [GreptimeTeam/greptimedb](https://github.com/GreptimeTeam/greptimedb) — Unified observability DB for metrics, logs, traces ☆`6,783`
1. [genkit-ai/genkit](https://github.com/genkit-ai/genkit) — AI app framework for JavaScript and Go ☆`6,565`
1. [getsentry/MobileBuildMCP](https://github.com/getsentry/MobileBuildMCP) — MCP server for Xcode build operations ☆`6,536`
1. [kucherenko/jscpd](https://github.com/kucherenko/jscpd) — Copy/paste detector for source code. 220+ languages, Rust engine, SARIF/HTML/badge reporters, GitHub Action, MCP server for AI agents. ☆`6,499`
1. [Coding-Solo/godot-mcp](https://github.com/Coding-Solo/godot-mcp) — MCP server for Godot game engine ☆`6,498`
1. [ThinkInAIXYZ/deepchat](https://github.com/ThinkInAIXYZ/deepchat) — DeepChat - A smart assistant that connects powerful AI to your personal world ☆`6,383`
1. [21st-dev/magic-mcp](https://github.com/21st-dev/magic-mcp) — Frontend development with AI like Magic ☆`6,366`
1. [Q00/ouroboros](https://github.com/Q00/ouroboros) — Agent OS: the agent gets smarter on its own. We just hold the line: Interview-gated, staged evaluation, budgeted evolution loop. MCP server, 14 runtimes: Claude Code, Codex CLI, ☆`6,315`
1. [baserow/baserow](https://github.com/baserow/baserow) — No-code database, apps, agents with AI ☆`6,270`
1. [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) — MCP server for Atlassian tools (Confluence, Jira) ☆`6,080`
1. [agentgateway/agentgateway](https://github.com/agentgateway/agentgateway) — Next Generation Agentic Proxy for AI Agents and MCP servers ☆`5,938`
1. [Klavis-AI/klavis](https://github.com/Klavis-AI/klavis) — Klavis AI: MCP integration platforms that let AI agents use tools reliably at any scale ☆`5,828`
1. [executeautomation/mcp-playwright](https://github.com/executeautomation/mcp-playwright) — MCP server for Playwright browser testing ☆`5,674`
1. [KnockOutEZ/wigolo](https://github.com/KnockOutEZ/wigolo) — The go-to web for your AI coding agent - local-first search, fetch, crawl & research over MCP. No API keys, no cloud, $0/query. Public beta. ☆`5,527`
1. [openclaw/Peekaboo](https://github.com/openclaw/Peekaboo) — macOS screenshot and window capture MCP server ☆`5,426`
1. [lingodotdev/lingo.dev](https://github.com/lingodotdev/lingo.dev) — MCP server for Lingo localization platform ☆`5,402`
1. [nanbingxyz/5ire](https://github.com/nanbingxyz/5ire) — 5ire is a cross-platform desktop AI assistant, MCP client. It compatible with major service providers, supports local knowledge base and tools via model context protocol servers . ☆`5,373`
1. [modelcontextprotocol/go-sdk](https://github.com/modelcontextprotocol/go-sdk) — The official Go SDK for Model Context Protocol servers and clients. Maintained in collaboration with Google. ☆`5,308`
1. [callstack/agent-device](https://github.com/callstack/agent-device) — Open source device layer for AI coding agents: a CLI, MCP server, and typed Node.js API to control mobile, web, TV, and desktop apps on devices and simulators, locally or in the ☆`5,265`
1. [Kiln-AI/Kiln](https://github.com/Kiln-AI/Kiln) — Build AI systems with Evals, RAG, Agents, fine-tuning ☆`5,254`
1. [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) — Exa MCP for web search and web crawling! ☆`5,209`
1. [atilaahmettaner/tradingview-mcp](https://github.com/atilaahmettaner/tradingview-mcp) — MCP server for market analysis in AI assistants: screeners, multi-timeframe technical analysis, backtests and sentiment for crypto, stocks, forex and futures. 39 tools. Self-host ☆`5,203`
1. [IBM/mcp-context-forge](https://github.com/IBM/mcp-context-forge) — An AI Gateway, registry, and proxy that sits in front of any MCP, A2A, or REST/gRPC APIs, exposing a unified endpoint with centralized discovery, guardrails and management. ☆`4,751`
1. [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server) — Official Notion MCP Server ☆`4,694`
1. [google/mcp](https://github.com/google/mcp) — Google MCP ☆`4,686`
1. [modelcontextprotocol/csharp-sdk](https://github.com/modelcontextprotocol/csharp-sdk) — The official C# SDK for Model Context Protocol servers and clients. Maintained in collaboration with Microsoft. ☆`4,614`
1. [IvanMurzak/Unity-MCP](https://github.com/IvanMurzak/Unity-MCP) — AI-powered bridge connecting LLMs to Unity Editor ☆`4,578`
1. [MarkusPfundstein/mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) — Obsidian integration via REST API plugin ☆`4,516`
1. [basicmachines-co/basic-memory](https://github.com/basicmachines-co/basic-memory) — AI conversations that remember context ☆`4,468`
1. [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) — Cloudflare services management ☆`4,442`
1. [archestra-ai/archestra](https://github.com/archestra-ai/archestra) — Enterprise AI guardrails, registry, gateway, and orchestrator ☆`4,426`
1. [open-webui/mcpo](https://github.com/open-webui/mcpo) — A simple, secure MCP-to-OpenAPI proxy server ☆`4,417`
1. [antvis/mcp-server-chart](https://github.com/antvis/mcp-server-chart) — 25+ visual charts using @antvis for data analysis ☆`4,412`
1. [CodeGraphContext/CodeGraphContext](https://github.com/CodeGraphContext/CodeGraphContext) — Code graph indexing for AI context ☆`4,374`
1. [haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server) — Excel file manipulation ☆`4,273`
1. [nowork-studio/notfair-plugin](https://github.com/nowork-studio/notfair-plugin) — Open-source SEO, GEO, and marketing skills for AI agents. ☆`4,111`
1. [nowork-studio/notfair-plugin](https://github.com/nowork-studio/notfair-plugin) — Google Ads diagnosis, recommendations, and edits ☆`4,111`
1. [nowork-studio/notfair-plugin](https://github.com/nowork-studio/notfair-plugin) — SEO, GEO, ads, Search Console, and Analytics skills ☆`4,106`
1. [modelcontextprotocol/rust-sdk](https://github.com/modelcontextprotocol/rust-sdk) — The official Rust SDK for the Model Context Protocol ☆`4,088`
1. [dagger/container-use](https://github.com/dagger/container-use) — MCP server for container orchestration ☆`4,082`
1. [skyhook-io/radar](https://github.com/skyhook-io/radar) — The missing open-source Kubernetes UI with a built-in MCP server for AI agents. See what's broken, why, and what changed. Issues, Topology, event timeline, Helm, GitOps, live ☆`4,032`
1. [samuelgursky/davinci-resolve-mcp](https://github.com/samuelgursky/davinci-resolve-mcp) — MCP server integration for DaVinci Resolve Studio ☆`3,916`

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
