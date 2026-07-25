# Awesome MCP

![Awesome](https://raw.githubusercontent.com/abordage/schemas/main/badges/awesome.svg)
[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-mcp?label=last%20update)](README.md)
![Repositories](https://img.shields.io/badge/repositories-1,313-06b6d4)
![Total Stars](https://img.shields.io/badge/total%20stars-1,065,661-gold)
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


## AI Agents

### Code Assistants

- [oraios/serena](https://github.com/oraios/serena) — Semantic code retrieval and editing toolkit ☆`26,816`
- [zilliztech/claude-context](https://github.com/zilliztech/claude-context) — Code search for Claude Code agents ☆`12,194`
- [CodeGraphContext/CodeGraphContext](https://github.com/CodeGraphContext/CodeGraphContext) — Code graph indexing for AI context ☆`3,980`
- [ezyang/codemcp](https://github.com/ezyang/codemcp) — Coding assistant MCP for Claude Desktop ☆`1,609`
- [ref-tools/ref-tools-mcp](https://github.com/ref-tools/ref-tools-mcp) — Reference tools for coding agents ☆`1,143`
- [SDGLBL/mcp-claude-code](https://github.com/SDGLBL/mcp-claude-code) — MCP implementation of Claude Code capabilities and more ☆`304`
- [stippi/code-assistant](https://github.com/stippi/code-assistant) — LLM-powered autonomous coding assistant ☆`176`
- [lamemind/mcp-server-multiverse](https://github.com/lamemind/mcp-server-multiverse) — MCP server for multiverse context management ☆`81`
- [wende/cicada](https://github.com/wende/cicada) — AI Coders search blindly. Be their guide. ☆`40`
- [gabrielmaialva33/winx-code-agent](https://github.com/gabrielmaialva33/winx-code-agent) — MCP-powered code agent for development ☆`33`
- [x51xxx/codex-mcp-tool](https://github.com/x51xxx/codex-mcp-tool) — Claude/Cursor to Codex CLI bridge with multi-turn sessions ☆`23`
- [VertexStudio/developer](https://github.com/VertexStudio/developer) — File editing, shell execution, screen capture ☆`21`
### Human-in-the-Loop

- [ttommyth/interactive-mcp](https://github.com/ttommyth/interactive-mcp) — Interactive MCP server for human-in-the-loop AI ☆`352`
- [gotohuman/gotohuman-mcp-server](https://github.com/gotohuman/gotohuman-mcp-server) — Human approvals for AI agentic workflows ☆`53`
- [RapidataAI/human-use](https://github.com/RapidataAI/human-use) — Enable AI to ask anyone anything ☆`73`
- [nazar256/user-prompt-mcp](https://github.com/nazar256/user-prompt-mcp) — User input requests for Cursor ☆`21`
### Multi-Agent

- [rinadelph/Agent-MCP](https://github.com/rinadelph/Agent-MCP) — Multi-agent AI collaboration framework ☆`1,270`
- [roboticforce/sugar](https://github.com/roboticforce/sugar) — Persistent memory for AI coding agents. Local-first, cross-session context, global knowledge, and optional autonomous task execution. ☆`92`
### Reasoning & Prompts

- [PV-Bhat/vibe-check-mcp-server](https://github.com/PV-Bhat/vibe-check-mcp-server) — Mentor-like feedback tool preventing AI over-engineering ☆`501`
- [ooples/token-optimizer-mcp](https://github.com/ooples/token-optimizer-mcp) — Token optimization with caching and compression ☆`449`
- [Rai220/think-mcp](https://github.com/Rai220/think-mcp) — MCP Server for reasoning ☆`107`
- [hyperb1iss/lucidity-mcp](https://github.com/hyperb1iss/lucidity-mcp) — MCP server for enhanced AI clarity and reasoning ☆`89`
- [YuChenSSR/multi-ai-advisor-mcp](https://github.com/YuChenSSR/multi-ai-advisor-mcp) — council of models for decision ☆`83`
- [nikkoxgonzales/crash-mcp](https://github.com/nikkoxgonzales/crash-mcp) — Structured reasoning with step validation ☆`71`
- [gwbischof/free-will-mcp](https://github.com/gwbischof/free-will-mcp) — Experimental AI self-prompting MCP server ☆`37`
- [aquarius-wing/actor-critic-thinking-mcp](https://github.com/aquarius-wing/actor-critic-thinking-mcp) — Dual-perspective thinking analysis server ☆`32`
- [vasayxtx/mcp-prompt-engine](https://github.com/vasayxtx/mcp-prompt-engine) — MCP Prompt Engine ☆`18`
- [abhinav-mangla/inner-monologue-mcp](https://github.com/abhinav-mangla/inner-monologue-mcp) — Inner Monologue MCP Server ☆`17`
- [abhinav-mangla/think-tool-mcp](https://github.com/abhinav-mangla/think-tool-mcp) — MCP Think Tool Server ☆`16`
## AI Memory & RAG

### Memory

- [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) — Hindsight: Agent Memory That Learns ☆`18,747`
- [basicmachines-co/basic-memory](https://github.com/basicmachines-co/basic-memory) — AI conversations that remember context ☆`3,508`
- [Beever-AI/beever-atlas](https://github.com/Beever-AI/beever-atlas) — LLM Wiki memory for team chat (Slack, Discord, Teams) ☆`433`
- [agentic-box/memora](https://github.com/agentic-box/memora) — Persistent shared memories in SQLite ☆`432`
- [gannonh/memento-mcp](https://github.com/gannonh/memento-mcp) — Memento MCP: A Knowledge Graph Memory System for LLMs ☆`424`
- [CheMiguel23/MemoryMesh](https://github.com/CheMiguel23/MemoryMesh) — MCP server for knowledge graph memory ☆`349`
- [pi22by7/In-Memoria](https://github.com/pi22by7/In-Memoria) — Persistent Intelligence Infrastructure for AI Agents ☆`170`
- [jean-technologies/jean-memory](https://github.com/jean-technologies/jean-memory) — AI memory with mem0 and graphiti ☆`170`
- [redleaves/context-keeper](https://github.com/redleaves/context-keeper) — Intelligent memory and context for AI agents ☆`153`
- [ukkit/memcord](https://github.com/ukkit/memcord) — MCP server for memory and context management ☆`71`
- [knowall-ai/mcp-neo4j-agent-memory](https://github.com/knowall-ai/mcp-neo4j-agent-memory) — Memory management using Neo4j graphs ☆`70`
- [peless/claude-thread-continuity](https://github.com/peless/claude-thread-continuity) — Save and restore project context ☆`64`
- [hungryrobot1/MCP-PIF](https://github.com/hungryrobot1/MCP-PIF) — Personal intelligence framework in Haskell ☆`57`
- [Yuchen20/Memory-Plus](https://github.com/Yuchen20/Memory-Plus) — Enhanced persistent memory management ☆`56`
- [skydeckai/mcp-server-rememberizer](https://github.com/skydeckai/mcp-server-rememberizer) — An MCP Server to enable global access to Rememberizer ☆`35`
- [JamesANZ/memory-mcp](https://github.com/JamesANZ/memory-mcp) — A simple MCP server that stores and retrieves memories from multiple LLMs. ☆`19`
- [unibaseio/membase-mcp](https://github.com/unibaseio/membase-mcp) — Decentralized memory layer for AI agents ☆`24`
- [ssmirnovpro/extended-memory-mcp](https://github.com/ssmirnovpro/extended-memory-mcp) — Cross-session persistent memory for Claude Desktop ☆`17`
- [hubertciebiada/context-crystallizer](https://github.com/hubertciebiada/context-crystallizer) — Large repos into AI-consumable knowledge for agents ☆`16`
### RAG

- [apecloud/ApeRAG](https://github.com/apecloud/ApeRAG) — Production GraphRAG with multi-modal ☆`1,285`
- [dmayboroda/minima](https://github.com/dmayboroda/minima) — On-premises conversational RAG with configurable containers ☆`1,047`
- [GreatScottyMac/context-portal](https://github.com/GreatScottyMac/context-portal) — Memory bank MCP with knowledge graph ☆`764`
- [graphlit/graphlit-mcp-server](https://github.com/graphlit/graphlit-mcp-server) — Model Context Protocol (MCP) Server for Graphlit Platform ☆`378`
- [shinpr/mcp-local-rag](https://github.com/shinpr/mcp-local-rag) — MCP server for local RAG operations ☆`352`
- [hannesrudolph/mcp-ragdocs](https://github.com/hannesrudolph/mcp-ragdocs) — MCP server for RAG document retrieval ☆`265`
- [needle-ai/needle-mcp](https://github.com/needle-ai/needle-mcp) — Needle MCP Server for easy RAG.Long-term memory for LLMs. ☆`99`
- [ragieai/ragie-mcp-server](https://github.com/ragieai/ragie-mcp-server) — Ragie Model Context Protocol Server ☆`89`
- [run-llama/mcp-server-llamacloud](https://github.com/run-llama/mcp-server-llamacloud) — LlamaCloud managed indexes connection ☆`87`
- [pinecone-io/assistant-mcp](https://github.com/pinecone-io/assistant-mcp) — Pinecone Assistant MCP server ☆`45`
- [vectara/vectara-mcp](https://github.com/vectara/vectara-mcp) — Open source MCP server for Vectara ☆`27`
- [nonatofabio/local_faiss_mcp](https://github.com/nonatofabio/local_faiss_mcp) — Local FAISS MCP - semantic search for Claude/Copilot ☆`33`
- [agentset-ai/mcp-server](https://github.com/agentset-ai/mcp-server) — Agentset MCP Server - Build RAG with Agentic superpowers ☆`30`
- [renl/mcp-rag-local](https://github.com/renl/mcp-rag-local) — Local RAG with Ollama embeddings and ChromaDB ☆`18`
## AI Platforms

- [Kiln-AI/Kiln](https://github.com/Kiln-AI/Kiln) — Build AI systems with Evals, RAG, Agents, fine-tuning ☆`4,971`
- [paiml/paiml-mcp-agent-toolkit](https://github.com/paiml/paiml-mcp-agent-toolkit) — Pragmatic AI Labs toolkit for deterministic agents ☆`159`
- [IBM/wxflows](https://github.com/IBM/wxflows) — watsonx.ai Flows AI app tutorials ☆`117`
- [TheRaLabs/legion-mcp](https://github.com/TheRaLabs/legion-mcp) — MCP server for Legion AI platform ☆`94`
- [PromptExecution/just-mcp](https://github.com/PromptExecution/just-mcp) — mcp server for just ☆`53`
- [ai-1st/deepview-mcp](https://github.com/ai-1st/deepview-mcp) — MCP server for DeepView AI analysis ☆`65`
- [atlanhq/agent-toolkit](https://github.com/atlanhq/agent-toolkit) — Atlan AI Agent Toolkit ☆`32`
- [StitchAI/stitch-ai-mcp](https://github.com/StitchAI/stitch-ai-mcp) — Decentralized Knowledge Hub for AI ☆`40`
- [DumplingAI/mcp-server-dumplingai](https://github.com/DumplingAI/mcp-server-dumplingai) — MCP (Model Context Protocol) server for Dumpling AI ☆`31`
- [PV-Bhat/gemsuite-mcp](https://github.com/PV-Bhat/gemsuite-mcp) — MCP server for GemSuite tools ☆`29`
- [sequa-ai/sequa-mcp](https://github.com/sequa-ai/sequa-mcp) — MCP server for Sequa AI platform ☆`21`
- [patronus-ai/patronus-mcp-server](https://github.com/patronus-ai/patronus-mcp-server) —  ☆`16`
## Aggregators & Gateways

### Aggregators

- [mindsdb/mindshub](https://github.com/mindsdb/mindshub) — Query Engine for AI Analytics - self-reasoning agents on live data ☆`39,482`
- [metatool-ai/metamcp](https://github.com/metatool-ai/metamcp) — MCP Aggregator, Orchestrator, Middleware, Gateway in one docker ☆`2,548`
- [mcpjungle/MCPJungle](https://github.com/mcpjungle/MCPJungle) — One place to manage & connect to all your MCP servers ☆`1,173`
- [1mcp-app/agent](https://github.com/1mcp-app/agent) — Unified MCP server aggregator ☆`476`
- [K-Dense-AI/claude-skills-mcp](https://github.com/K-Dense-AI/claude-skills-mcp) — Claude Agent Skills vector search ☆`393`
- [OldJii/mcp-dock](https://github.com/OldJii/mcp-dock) — Desktop MCP manager for 14 AI clients with 9200+ servers and 3100+ skills ☆`219`
- [sitbon/magg](https://github.com/sitbon/magg) — Magg: The MCP Aggregator ☆`139`
- [wanaku-ai/wanaku](https://github.com/wanaku-ai/wanaku) — Wanaku MCP Router ☆`130`
- [badkk/awesome-crypto-mcp-servers](https://github.com/badkk/awesome-crypto-mcp-servers) — A collection of crypto MCP servers. ☆`141`
- [askbudi/roundtable](https://github.com/askbudi/roundtable) — Zero-config MCP unifying multiple AI coding assistants ☆`121`
- [portel-dev/ncp](https://github.com/portel-dev/ncp) — Natural Context Provider with smart MCP tool loading ☆`97`
- [nguyenvanduocit/all-in-one-model-context-protocol](https://github.com/nguyenvanduocit/all-in-one-model-context-protocol) — GitLab, Jira, Confluence, YouTube ☆`105`
- [bh-rat/context-awesome](https://github.com/bh-rat/context-awesome) — awesome-lists now available as CLI & MCP server for your agent. ☆`57`
- [VeriTeknik/pluggedin-mcp](https://github.com/VeriTeknik/pluggedin-mcp) — Plugged.in MCP Server manages all your other MCPs in one MCP. ☆`51`
- [hamidra/yamcp](https://github.com/hamidra/yamcp) — Local MCP workspace organization ☆`66`
- [waystation-ai/mcp](https://github.com/waystation-ai/mcp) — No-code secure MCP integration hub ☆`58`
- [gotoolkits/mcp-difyworkflow-server](https://github.com/gotoolkits/mcp-difyworkflow-server) — MCP server for Dify workflow invocation ☆`60`
- [membranehq/mcp-server](https://github.com/membranehq/mcp-server) — MCP Server for Membrane ☆`38`
- [wojtyniak/mcp-mcp](https://github.com/wojtyniak/mcp-mcp) — Meta-MCP for tool discovery and provisioning ☆`23`
- [nazar256/combine-mcp](https://github.com/nazar256/combine-mcp) — MCP aggregator combining multiple servers into one interface ☆`34`
- [glenngillen/mcpmcp-server](https://github.com/glenngillen/mcpmcp-server) — MCP server aggregator and router ☆`33`
- [agree-able/room-mcp](https://github.com/agree-able/room-mcp) — Coordinate agents using rooms ☆`23`
### Gateways & Proxies

- [apache/apisix](https://github.com/apache/apisix) — The Cloud-Native API Gateway and AI Gateway ☆`16,907`
- [sparfenyuk/mcp-proxy](https://github.com/sparfenyuk/mcp-proxy) — A bridge between Streamable HTTP and stdio MCP transports ☆`2,683`
- [stacklok/toolhive](https://github.com/stacklok/toolhive) — Runtime and gateway for deploying MCP servers in containers ☆`1,968`
- [tbxark/mcp-proxy](https://github.com/tbxark/mcp-proxy) — Aggregate multiple MCP servers via HTTP ☆`709`
- [smart-mcp-proxy/mcpproxy-go](https://github.com/smart-mcp-proxy/mcpproxy-go) — Supercharge AI Agents, Safely ☆`300`
- [ssut/Remote-MCP](https://github.com/ssut/Remote-MCP) — Type-safe solution for remote MCP communication ☆`208`
- [sxhxliang/mcp-access-point](https://github.com/sxhxliang/mcp-access-point) — Convert any web server to MCP instantly ☆`181`
- [HelpCode-ai/anythingmcp](https://github.com/HelpCode-ai/anythingmcp) — Self-hosted source-available MCP gateway converting REST/SOAP/GraphQL/SQL APIs into MCP tools with 29 pre-built adapters and OAuth2 + RBAC + audit log ☆`164`
- [toolprint/hypertool-mcp](https://github.com/toolprint/hypertool-mcp) — Expose tools based on Agent Persona ☆`155`
- [VeriTeknik/pluggedin-mcp-proxy](https://github.com/VeriTeknik/pluggedin-mcp-proxy) — Unified MCP proxy managing multiple MCPs ☆`132`
- [tigranbs/mcgravity](https://github.com/tigranbs/mcgravity) — Proxy for composing multiple MCP servers into one endpoint ☆`101`
- [universal-mcp/universal-mcp](https://github.com/universal-mcp/universal-mcp) — Middleware for API applications ☆`26`
- [pyroprompts/mcp-stdio-to-streamable-http-adapter](https://github.com/pyroprompts/mcp-stdio-to-streamable-http-adapter) — STDIO to Streamable HTTP proxy ☆`27`
- [nick1udwig/ws-mcp](https://github.com/nick1udwig/ws-mcp) — MCP server with WebSocket transport ☆`21`
- [webrix-ai/secure-mcp-gateway](https://github.com/webrix-ai/secure-mcp-gateway) — Secure OAuth gateway for MCP authentication ☆`20`
### Platforms & Registries

- [archestra-ai/archestra](https://github.com/archestra-ai/archestra) — Enterprise AI Platform with guardrails, MCP registry, gateway & orchestrator ☆`4,021`
- [metorial/metorial](https://github.com/metorial/metorial) — Connect any AI model to 1200+ integrations (MCP, CLI, API) ☆`3,322`
- [chatmcp/mcpso](https://github.com/chatmcp/mcpso) — directory for Awesome MCP Servers ☆`2,030`
- [julien040/anyquery](https://github.com/julien040/anyquery) — SQL queries for GitHub, Notion, +40 more ☆`1,735`
- [jaw9c/awesome-remote-mcp-servers](https://github.com/jaw9c/awesome-remote-mcp-servers) — Remote MCP Servers ☆`1,095`
- [boltmcp/boltmcp](https://github.com/boltmcp/boltmcp) — Open standard and registry for converting web APIs into MCP servers ☆`362`
- [milisp/mcp-linker](https://github.com/milisp/mcp-linker) — Sync MCP configs across clients ☆`320`
- [liuyoshio/mcp-compass](https://github.com/liuyoshio/mcp-compass) — MCP discovery and recommendation ☆`246`
- [integromat/make-mcp-server](https://github.com/integromat/make-mcp-server) — Make MCP Server ☆`164`
- [juspay/neurolink](https://github.com/juspay/neurolink) — Universal AI platform with MCP and multi-provider support ☆`113`
- [Jeamee/MCPHub-Desktop](https://github.com/Jeamee/MCPHub-Desktop) — Desktop APP for Discover and Install MCP Servers ☆`150`
- [rust-mcp-stack/mcp-discovery](https://github.com/rust-mcp-stack/mcp-discovery) — CLI for discovering MCP server capabilities ☆`84`
- [matthewdcage/cursor-mcp-installer](https://github.com/matthewdcage/cursor-mcp-installer) — Install MCPs in Cursor from git URL ☆`76`
- [useparagon/paragon-mcp](https://github.com/useparagon/paragon-mcp) — Access 130+ SaaS integrations via ActionKit ☆`47`
- [VeyraX/veyrax-mcp](https://github.com/VeyraX/veyrax-mcp) — VeyraX unified tool access via single MCP ☆`48`
- [Data-Everything/mcp-server-templates](https://github.com/Data-Everything/mcp-server-templates) — A flexible platform that provides Docker & Kubernetes backends, a lightweight CLI (mcpt), and client utilities for seamless MCP integration. Spin up servers from templates, route requests through a single endpoint with load balancing, and support both deployed (HTTP) and local (stdio) transports — all with sensible defaults and YAML-based configs. ☆`19`
## Browser Automation

### AI Automation

- [Skyvern-AI/skyvern](https://github.com/Skyvern-AI/skyvern) — Automate browser based workflows with AI ☆`22,583`
- [nottelabs/notte](https://github.com/nottelabs/notte) — Framework to build web agents ☆`1,986`
- [imprvhub/mcp-browser-agent](https://github.com/imprvhub/mcp-browser-agent) — MCP server for autonomous browser automation with Claude ☆`41`
- [desplega-ai/qa-use](https://github.com/desplega-ai/qa-use) — Agent-first E2E testing CLI ☆`25`
### Browser Tools

- [BrowserMCP/mcp](https://github.com/BrowserMCP/mcp) — Browser control for AI applications ☆`6,867`
- [kontext-security/browser-use-mcp-server](https://github.com/kontext-security/browser-use-mcp-server) — Browse the web, directly from Cursor etc. ☆`826`
- [onllm-dev/onUI](https://github.com/onllm-dev/onUI) — Browser extension and MCP server for annotation-first UI pair programming with AI agents ☆`85`
- [ndthanhdev/mcp-browser-kit](https://github.com/ndthanhdev/mcp-browser-kit) — AI assistants interact with local browser ☆`54`
- [BB-fat/browser-use-rs](https://github.com/BB-fat/browser-use-rs) — Rust-based browser automation MCP server ☆`41`
### Cloud Services

- [hyperbrowserai/mcp](https://github.com/hyperbrowserai/mcp) — A MCP server implementation for hyperbrowser ☆`772`
- [browserstack/mcp-server](https://github.com/browserstack/mcp-server) — BrowserStack's Official MCP Server ☆`146`
- [kernel/kernel-mcp-server](https://github.com/kernel/kernel-mcp-server) — Secure cloud-browser automation on Kernel ☆`30`
### DevTools

- [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) — Chrome DevTools for coding agents ☆`47,555`
- [mozilla/firefox-devtools-mcp](https://github.com/mozilla/firefox-devtools-mcp) — MCP server for Firefox DevTools integration ☆`316`
- [eyalzh/browser-control-mcp](https://github.com/eyalzh/browser-control-mcp) — Browser control via extension for AI agents ☆`305`
### Playwright

- [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) — Playwright MCP server ☆`35,453`
- [executeautomation/mcp-playwright](https://github.com/executeautomation/mcp-playwright) — MCP server for Playwright browser testing ☆`5,614`
- [VikashLoomba/MCP-Server-Playwright](https://github.com/VikashLoomba/MCP-Server-Playwright) — MCP server for browser automation using Playwright ☆`298`
- [blackwhite084/playwright-plus-python-mcp](https://github.com/blackwhite084/playwright-plus-python-mcp) — Enhanced Playwright browser automation ☆`189`
- [kimtth/mcp-aoai-web-browsing](https://github.com/kimtth/mcp-aoai-web-browsing) — Azure OpenAI with Playwright browser control ☆`34`
## CLI Tools

- [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) — Terminal control, file search, diff editing ☆`8,789`
- [IBM/mcp-cli](https://github.com/IBM/mcp-cli) — Feature-rich CLI for interacting with MCP servers ☆`2,003`
- [classfang/ssh-mcp-server](https://github.com/classfang/ssh-mcp-server) — SSH MCP server included in official repo ☆`685`
- [rusiaaman/wcgw](https://github.com/rusiaaman/wcgw) — Shell and coding agent on mcp clients ☆`669`
- [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp) — iTerm command execution for REPL/CLI ☆`566`
- [tufantunc/ssh-mcp](https://github.com/tufantunc/ssh-mcp) — SSH control for Linux servers ☆`553`
- [baryhuang/mcp-remote-macos-use](https://github.com/baryhuang/mcp-remote-macos-use) — AI agent for full Mac control ☆`487`
- [peakmojo/applescript-mcp](https://github.com/peakmojo/applescript-mcp) — Execute AppleScript for Mac control ☆`462`
- [wong2/mcp-cli](https://github.com/wong2/mcp-cli) — A CLI inspector for the Model Context Protocol ☆`441`
- [domdomegg/computer-use-mcp](https://github.com/domdomegg/computer-use-mcp) — Full computer control for AI models ☆`334`
- [claude-did-this/MCPControl](https://github.com/claude-did-this/MCPControl) — MCP server for Windows OS automation ☆`330`
- [nickgnd/tmux-mcp](https://github.com/nickgnd/tmux-mcp) — A MCP server for our beloved terminal multiplexer tmux. ☆`298`
- [g0t4/mcp-server-commands](https://github.com/g0t4/mcp-server-commands) — MCP server to run commands (runProcess tool) ☆`230`
- [tumf/mcp-shell-server](https://github.com/tumf/mcp-shell-server) — Shell execution with whitelisted commands ☆`183`
- [dvcrn/mcp-server-siri-shortcuts](https://github.com/dvcrn/mcp-server-siri-shortcuts) — MCP for calling Siri Shorcuts from LLMs ☆`190`
- [MladenSU/cli-mcp-server](https://github.com/MladenSU/cli-mcp-server) — CLI with secure execution and custom policies ☆`173`
- [AB498/computer-control-mcp](https://github.com/AB498/computer-control-mcp) — Mouse, keyboard, OCR via PyAutoGUI ☆`154`
- [sonirico/mcp-shell](https://github.com/sonirico/mcp-shell) — Secure, auditable shell commands for AI ☆`94`
- [automateyournetwork/pyATS_MCP](https://github.com/automateyournetwork/pyATS_MCP) — An MCP Server for pyATS (experimental) ☆`77`
- [inercia/MCPShell](https://github.com/inercia/MCPShell) — Use shell scripts as MCP tools ☆`66`
- [NakaokaRei/swift-mcp-gui](https://github.com/NakaokaRei/swift-mcp-gui) — Keyboard and mouse control on macOS ☆`62`
- [ooples/mcp-console-automation](https://github.com/ooples/mcp-console-automation) — MCP for AI-driven console automation and monitoring ☆`43`
- [nihalxkumar/arch-mcp](https://github.com/nihalxkumar/arch-mcp) — Arch Linux MCP (Model Context Protocol) Server ☆`52`
- [InsForge/insforge-mcp](https://github.com/InsForge/insforge-mcp) — MCP server for InsForge - full-stack builders for coding agents ☆`33`
- [maxim-saplin/mcp_safe_local_python_executor](https://github.com/maxim-saplin/mcp_safe_local_python_executor) — Safe Python executor from smolagents ☆`46`
- [blakerouse/ssh-mcp](https://github.com/blakerouse/ssh-mcp) — SSH MCP server that runs locally making it easy to manage hosts and perform commands across a group of hosts ☆`17`
- [PhialsBasement/CMD-MCP-Server](https://github.com/PhialsBasement/CMD-MCP-Server) — CMD command execution for Claude agents ☆`25`
- [erniebrodeur/mcp-grep](https://github.com/erniebrodeur/mcp-grep) — simple mcp server to wrap the local instance of grep. ☆`24`
- [aybelatchane/mcp-server-terminal](https://github.com/aybelatchane/mcp-server-terminal) — Terminal MCP Server - Model Context Protocol server for TUI/CLI automation with structured Terminal State Tree (TST) ☆`18`
- [Beer-Bears/scaffold](https://github.com/Beer-Bears/scaffold) — Structural RAG system for large codebases ☆`18`
- [OthmaneBlial/term_mcp_deepseek](https://github.com/OthmaneBlial/term_mcp_deepseek) — A MCP‑like server using the DeepSeek API for Terminal ☆`16`
- [JoshuaRileyDev/mac-apps-launcher](https://github.com/JoshuaRileyDev/mac-apps-launcher) — Launch and manage macOS applications ☆`19`
## CRM & ERP

- [ivnvxd/mcp-server-odoo](https://github.com/ivnvxd/mcp-server-odoo) — MCP server for Odoo ERP integration ☆`345`
- [GeLi2001/shopify-mcp](https://github.com/GeLi2001/shopify-mcp) — Shopify API for Claude and Cursor ☆`229`
- [smn2gnt/MCP-Salesforce](https://github.com/smn2gnt/MCP-Salesforce) — MCP Salesforce connector ☆`178`
- [tsmztech/mcp-server-salesforce](https://github.com/tsmztech/mcp-server-salesforce) — Salesforce MCP Server ☆`163`
- [baryhuang/mcp-hubspot](https://github.com/baryhuang/mcp-hubspot) — HubSpot CRM integration for AI assistants ☆`128`
- [augmnt/augments-mcp-server](https://github.com/augmnt/augments-mcp-server) — MCP server for Augments AI platform ☆`125`
- [tomaspavlin/rohlik-mcp](https://github.com/tomaspavlin/rohlik-mcp) — Shop groceries on Rohlik Group platforms ☆`117`
- [mafzaal/d365fo-client](https://github.com/mafzaal/d365fo-client) — Client for Microsoft Dynamics 365 F&O ☆`37`
- [AiondaDotCom/mcp-salesforce](https://github.com/AiondaDotCom/mcp-salesforce) — Complete MCP (Model Context Protocol) server for Salesforce integration with Claude Desktop. Provides seamless OAuth authentication, universal CRUD operations on any Salesforce object. ☆`17`
- [dsvantien/netsuite-mcp-server](https://github.com/dsvantien/netsuite-mcp-server) — This project is officially listed on the https://github.com/modelcontextprotocol/servers , which showcases community-built and verified MCP servers. ☆`18`
- [hmk/attio-mcp-server](https://github.com/hmk/attio-mcp-server) — Attio CRM records and notes management ☆`16`
## Cloud & Infrastructure

### AWS

- [awslabs/mcp](https://github.com/awslabs/mcp) — AWS MCP servers for AI assistants ☆`9,491`
- [alexei-led/cloud-mcp-server](https://github.com/alexei-led/cloud-mcp-server) — AWS CLI in containerized environment ☆`185`
- [aarora79/aws-cost-explorer-mcp-server](https://github.com/aarora79/aws-cost-explorer-mcp-server) — MCP server for understanding AWS spend ☆`127`
- [rishikavikondala/mcp-server-aws](https://github.com/rishikavikondala/mcp-server-aws) — MCP server for AWS resource operations ☆`128`
- [aws-samples/sample-mcp-server-s3](https://github.com/aws-samples/sample-mcp-server-s3) — Retrieve PDFs and data from AWS S3 ☆`78`
- [localstack/localstack-mcp-server](https://github.com/localstack/localstack-mcp-server) — LocalStack AWS emulation ☆`25`
- [baryhuang/mcp-server-aws-resources-python](https://github.com/baryhuang/mcp-server-aws-resources-python) — Run boto3 code to manage AWS resources ☆`24`
- [trilogy-group/aws-pricing-mcp](https://github.com/trilogy-group/aws-pricing-mcp) — AWS EC2 pricing search by CPU, RAM, network ☆`21`
### Cloud Platforms

- [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) — Cloudflare services management ☆`3,984`
- [microsoft/azure-devops-mcp](https://github.com/microsoft/azure-devops-mcp) — Azure DevOps integration for AI agents ☆`1,907`
- [TencentCloudBase/CloudBase-AI-Toolkit](https://github.com/TencentCloudBase/CloudBase-AI-Toolkit) — Connect CloudBase to AI agents ☆`1,065`
- [GoogleCloudPlatform/cloud-run-mcp](https://github.com/GoogleCloudPlatform/cloud-run-mcp) — MCP server to deploy apps to Cloud Run ☆`622`
- [babelcloud/gbox](https://github.com/babelcloud/gbox) — AI control for Android, browser, desktop ☆`177`
- [aliyun/alibabacloud-devops-mcp-server](https://github.com/aliyun/alibabacloud-devops-mcp-server) — MCP server for Alibaba Yunxiao DevOps platform ☆`144`
- [aliyun/alibaba-cloud-ops-mcp-server](https://github.com/aliyun/alibaba-cloud-ops-mcp-server) — AlibabaCloud CloudOps MCP Server ☆`124`
- [dkruyt/mcp-hetzner](https://github.com/dkruyt/mcp-hetzner) — Hetzner Cloud management ☆`127`
- [heroku/heroku-mcp-server](https://github.com/heroku/heroku-mcp-server) — Heroku Platform MCP Server using the Heroku CLI ☆`80`
- [vantage-sh/vantage-mcp-server](https://github.com/vantage-sh/vantage-mcp-server) — Fetch costs and usage from Vantage ☆`83`
- [aliyun/alibabacloud-dataworks-mcp-server](https://github.com/aliyun/alibabacloud-dataworks-mcp-server) — Alibaba Cloud DataWorks API integration ☆`47`
- [aliyun/alibabacloud-hologres-mcp-server](https://github.com/aliyun/alibabacloud-hologres-mcp-server) — MCP server for Alibaba Hologres data warehouse ☆`34`
- [call518/MCP-OpenStack-Ops](https://github.com/call518/MCP-OpenStack-Ops) — MCP server providing OpenStack project management ☆`35`
- [kestra-io/mcp-server-python](https://github.com/kestra-io/mcp-server-python) — Python MCP for Kestra AI Agents ☆`29`
- [aantti/mcp-netbird](https://github.com/aantti/mcp-netbird) — Netbird network management ☆`53`
- [qiniu/qiniu-mcp-server](https://github.com/qiniu/qiniu-mcp-server) — Qiniu Cloud storage, CDN, and media processing ☆`38`
- [redis/mcp-redis-cloud](https://github.com/redis/mcp-redis-cloud) — MCP server for Redis Cloud database operations ☆`40`
- [liveblocks/liveblocks-mcp-server](https://github.com/liveblocks/liveblocks-mcp-server) — MCP server for Liveblocks. ☆`17`
- [pythonanywhere/pythonanywhere-mcp-server](https://github.com/pythonanywhere/pythonanywhere-mcp-server) —  ☆`17`
- [Azure-Samples/mcp](https://github.com/Azure-Samples/mcp) — Samples and resources for Azure MCP ☆`41`
- [api7/apisix-mcp](https://github.com/api7/apisix-mcp) — APISIX gateway for LLM integration ☆`38`
- [pibblokto/cert-manager-mcp-server](https://github.com/pibblokto/cert-manager-mcp-server) — MCP Server for cert-manager ☆`24`
- [higress-group/higress-ops-mcp-server](https://github.com/higress-group/higress-ops-mcp-server) — Higress API gateway configuration management ☆`23`
- [alexbakers/mcp-ipfs](https://github.com/alexbakers/mcp-ipfs) — MCP IPFS Server ☆`20`
- [hardik-id/azure-resource-graph-mcp-server](https://github.com/hardik-id/azure-resource-graph-mcp-server) — Azure Resource Graph query interface ☆`18`
- [espressif/esp-rainmaker-mcp](https://github.com/espressif/esp-rainmaker-mcp) — ESP RainMaker MCP server ☆`16`
- [kocierik/consul-mcp-server](https://github.com/kocierik/consul-mcp-server) — A consul MCP Server (modelcontextprotocol) ☆`17`
### Kubernetes

- [containers/kubernetes-mcp-server](https://github.com/containers/kubernetes-mcp-server) — Kubernetes and OpenShift management ☆`1,846`
- [Flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) — MCP Server for kubernetes management commands ☆`1,463`
- [rohitg00/kubectl-mcp-server](https://github.com/rohitg00/kubectl-mcp-server) — Kubernetes cluster chat with Claude/Cursor ☆`932`
- [weibaohui/k8m](https://github.com/weibaohui/k8m) — Mini Kubernetes AI Dashboard ☆`866`
- [strowk/mcp-k8s-go](https://github.com/strowk/mcp-k8s-go) — Go-based Kubernetes connection ☆`384`
- [vfarcic/dot-ai](https://github.com/vfarcic/dot-ai) — Deploy apps to any Kubernetes cluster ☆`333`
- [portainer/portainer-mcp](https://github.com/portainer/portainer-mcp) — Portainer container management ☆`203`
- [alexei-led/k8s-mcp-server](https://github.com/alexei-led/k8s-mcp-server) — Kubernetes cluster management ☆`213`
- [reza-gholizade/k8s-mcp-server](https://github.com/reza-gholizade/k8s-mcp-server) — Kubernetes cluster management ☆`173`
- [silenceper/mcp-k8s](https://github.com/silenceper/mcp-k8s) — Kubernetes cluster interaction ☆`148`
- [kubestellar/console](https://github.com/kubestellar/console) — AI-powered multi-cluster Kubernetes dashboard with MCP server (kc-agent) for natural language operations ☆`122`
- [weibaohui/kom](https://github.com/weibaohui/kom) — Kubernetes SDK wrapping kubectl ☆`150`
- [StacklokLabs/mkp](https://github.com/StacklokLabs/mkp) — MKP Kubernetes MCP server ☆`59`
- [cyclops-ui/mcp-cyclops](https://github.com/cyclops-ui/mcp-cyclops) — Cyclops Kubernetes management ☆`30`
- [wenhuwang/mcp-k8s-eye](https://github.com/wenhuwang/mcp-k8s-eye) — Kubernetes diagnosis and management ☆`28`
### Virtualization & IaC

- [hashicorp/terraform-mcp-server](https://github.com/hashicorp/terraform-mcp-server) — Terraform ecosystem integration for AI ☆`1,482`
- [nwiizo/tfmcp](https://github.com/nwiizo/tfmcp) — Terraform AI-assisted infrastructure ☆`371`
- [1Panel-dev/mcp-1panel](https://github.com/1Panel-dev/mcp-1panel) — MCP server for 1Panel management ☆`158`
- [kocierik/mcp-nomad](https://github.com/kocierik/mcp-nomad) — A nomad MCP Server (modelcontextprotocol) ☆`58`
- [bright8192/esxi-mcp-server](https://github.com/bright8192/esxi-mcp-server) — MCP server for VMware ESXi management ☆`60`
- [jokemanfire/mcp-containerd](https://github.com/jokemanfire/mcp-containerd) — Use mcp to manage containerd(developing) ☆`53`
- [openstack-kr/python-openstackmcp-server](https://github.com/openstack-kr/python-openstackmcp-server) — openstack mcp server ☆`20`
- [severity1/terraform-cloud-mcp](https://github.com/severity1/terraform-cloud-mcp) — Terraform Cloud API integration ☆`23`
## Communication & Messaging

### Apple Messages

- [mattt/iMCP](https://github.com/mattt/iMCP) — Access Messages, Contacts, Reminders on Mac ☆`1,502`
- [carterlasalle/mac_messages_mcp](https://github.com/carterlasalle/mac_messages_mcp) — MCP server for secure iMessage database access on macOS ☆`307`
- [hannesrudolph/imessage-query-fastmcp-mcp-server](https://github.com/hannesrudolph/imessage-query-fastmcp-mcp-server) — Safe iMessage database queries ☆`79`
- [wyattjoh/imessage-mcp](https://github.com/wyattjoh/imessage-mcp) — iMessage data reading from macOS ☆`29`
### Email

- [elie222/inbox-zero](https://github.com/elie222/inbox-zero) — AI email assistant for inbox zero ☆`11,695`
- [MadLlama25/fastmail-mcp](https://github.com/MadLlama25/fastmail-mcp) — Access to Fastmail API for AI assistants ☆`124`
- [ZilongXue/claude-post](https://github.com/ZilongXue/claude-post) — Email management via natural language ☆`113`
- [mailtrap/mailtrap-mcp](https://github.com/mailtrap/mailtrap-mcp) — Official mailtrap.io MCP server ☆`61`
- [mailgun/mailgun-mcp-server](https://github.com/mailgun/mailgun-mcp-server) — Mailgun API integration ☆`56`
- [Shy2593666979/mcp-server-email](https://github.com/Shy2593666979/mcp-server-email) — Email with attachments for Gmail, Outlook, QQ ☆`78`
- [egyptianego17/email-mcp-server](https://github.com/egyptianego17/email-mcp-server) — Send emails with attachments via SMTP ☆`28`
### Messengers

- [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) — WhatsApp MCP server ☆`5,934`
- [chigwell/telegram-mcp](https://github.com/chigwell/telegram-mcp) — MCP server for Telegram messaging ☆`1,329`
- [line/line-bot-mcp-server](https://github.com/line/line-bot-mcp-server) — LINE Messaging API for AI agents ☆`708`
- [chaindead/telegram-mcp](https://github.com/chaindead/telegram-mcp) — Telegram dialogs, messages, drafts, statuses ☆`338`
- [ztxtxwd/open-feishu-mcp-server](https://github.com/ztxtxwd/open-feishu-mcp-server) — Feishu/Lark OAuth and document management ☆`85`
- [areweai/tsgram-mcp](https://github.com/areweai/tsgram-mcp) — Telegram for local Claude Code debug ☆`92`
- [pubnub/pubnub-mcp-server](https://github.com/pubnub/pubnub-mcp-server) — PubNub Model Context Protocol Server ☆`32`
- [mjknowles/matrix-mcp-server](https://github.com/mjknowles/matrix-mcp-server) — Matrix server integration and chat ☆`48`
- [DLHellMe/telegram-mcp-server](https://github.com/DLHellMe/telegram-mcp-server) — Scrape and analyze Telegram content ☆`31`
### Notifications

- [gitmotion/ntfy-me-mcp](https://github.com/gitmotion/ntfy-me-mcp) — MCP server for ntfy push notifications ☆`70`
- [Cactusinhand/mcp_server_notify](https://github.com/Cactusinhand/mcp_server_notify) — Send system notification when Agent task is done. ☆`55`
- [infobip/mcp](https://github.com/infobip/mcp) — Infobip Remote MCP Servers Documentation ☆`32`
- [teddyzxcv/ntfy-mcp](https://github.com/teddyzxcv/ntfy-mcp) — MCP server for ntfy push notifications ☆`43`
- [AshikNesin/pushover-mcp](https://github.com/AshikNesin/pushover-mcp) — A MCP implementation for sending notifications via Pushover ☆`41`
- [aahl/mcp-notify](https://github.com/aahl/mcp-notify) — Notify to Weixin, Telegram, Bark, Lark, DingTalk ☆`28`
### Team Chat

- [korotovsky/slack-mcp-server](https://github.com/korotovsky/slack-mcp-server) — MCP server for Slack workspace integration ☆`1,752`
- [chatmcp/mcp-server-chatsum](https://github.com/chatmcp/mcp-server-chatsum) — Query and Summarize your chat messages. ☆`1,030`
- [joinly-ai/joinly](https://github.com/joinly-ai/joinly) — Make your meetings accessible to AI Agents ☆`533`
- [SaseQ/discord-mcp](https://github.com/SaseQ/discord-mcp) — MCP server for Discord integration ☆`420`
- [v-3/discordmcp](https://github.com/v-3/discordmcp) — Discord MCP Server for Claude Integration ☆`220`
- [discourse/discourse-mcp](https://github.com/discourse/discourse-mcp) — MCP client for Discourse sites ☆`67`
- [zencoderai/slack-mcp-server](https://github.com/zencoderai/slack-mcp-server) — Slack workspace interaction and messaging ☆`75`
- [jagan-shanmugam/mattermost-mcp-host](https://github.com/jagan-shanmugam/mattermost-mcp-host) — Mattermost integration with LangGraph agent ☆`34`
### Voice & Telephony

- [gerkensm/callcenter.js-mcp](https://github.com/gerkensm/callcenter.js-mcp) — Callcenter.JS AI Voice Agent VOIP Connector, MCP + CLI ☆`23`
## Data & Analytics

### AI/ML Platforms

- [MigoXLab/dingo](https://github.com/MigoXLab/dingo) — AI data, model, app quality evaluation ☆`728`
- [evalstate/mcp-hfspace](https://github.com/evalstate/mcp-hfspace) — HuggingFace Spaces integration ☆`388`
- [YanxingLiu/dify-mcp-server](https://github.com/YanxingLiu/dify-mcp-server) — Model Context Protocol (MCP) Server for dify workflows ☆`278`
- [0xshellming/mcp-summarizer](https://github.com/0xshellming/mcp-summarizer) — MCP Server for AI Summarization ☆`163`
- [ChronulusAI/chronulus-mcp](https://github.com/ChronulusAI/chronulus-mcp) — Chronulus AI forecasting and prediction agents ☆`111`
- [optuna/optuna-mcp](https://github.com/optuna/optuna-mcp) — Optuna hyperparameter optimization ☆`81`
- [zenml-io/mcp-zenml](https://github.com/zenml-io/mcp-zenml) — ZenML MLOps platform connection ☆`49`
- [arrismo/kaggle-mcp](https://github.com/arrismo/kaggle-mcp) — MCP server for Kaggle ☆`39`
- [kumo-ai/kumo-rfm-mcp](https://github.com/kumo-ai/kumo-rfm-mcp) — MCP server to query KumoRFM in your agentic flows ☆`33`
- [HumanSignal/label-studio-mcp-server](https://github.com/HumanSignal/label-studio-mcp-server) — MCP server for Label Studio data labeling ☆`34`
- [privetin/dataset-viewer](https://github.com/privetin/dataset-viewer) — MCP server for Hugging Face dataset viewer ☆`31`
### Data APIs

- [YangLiangwei/PersonalizationMCP](https://github.com/YangLiangwei/PersonalizationMCP) — Personal data hub for AI from Steam, YouTube, Bilibili ☆`59`
- [anshumax/world_bank_mcp_server](https://github.com/anshumax/world_bank_mcp_server) — World Bank open data API ☆`49`
- [explorium-ai/mcp-explorium](https://github.com/explorium-ai/mcp-explorium) — Explorium B2B Data - MCP Server ☆`22`
### Data Exploration

- [reading-plus-ai/mcp-server-data-exploration](https://github.com/reading-plus-ai/mcp-server-data-exploration) — Interactive CSV data exploration ☆`545`
- [kdqed/zaturn](https://github.com/kdqed/zaturn) — Data Analysis With Vibes ☆`74`
- [santoshray02/csv-editor](https://github.com/santoshray02/csv-editor) — AI-powered CSV data manipulation and analysis ☆`24`
- [brightlikethelight/networkx-mcp-server](https://github.com/brightlikethelight/networkx-mcp-server) — First NetworkX MCP server for graph analysis in AI conversations | Community & Enterprise editions | Graph algorithms • Network analysis • MCP integration ☆`20`
### Data Platforms

- [dbt-labs/dbt-mcp](https://github.com/dbt-labs/dbt-mcp) — A MCP (Model Context Protocol) server for interacting with dbt. ☆`594`
- [kubeflow/mcp-apache-spark-history-server](https://github.com/kubeflow/mcp-apache-spark-history-server) — Apache Spark History Server bridge ☆`183`
- [microsoft/fabric-rti-mcp](https://github.com/microsoft/fabric-rti-mcp) — Fabric Real-Time Intelligence server ☆`126`
- [acryldata/mcp-server-datahub](https://github.com/acryldata/mcp-server-datahub) — Official MCP server for DataHub ☆`79`
- [keboola/mcp-server](https://github.com/keboola/mcp-server) — Model Context Protocol (MCP) Server for the Keboola Platform ☆`84`
- [thoughtspot/mcp-server](https://github.com/thoughtspot/mcp-server) — The ThoughtSpot MCP Server ☆`33`
- [aywengo/kafka-schema-reg-mcp](https://github.com/aywengo/kafka-schema-reg-mcp) — Kafka Schema Registry management ☆`32`
- [JordiNeil/mcp-databricks-server](https://github.com/JordiNeil/mcp-databricks-server) — MCP Server for Databricks ☆`50`
- [RafaelCartenet/mcp-databricks-server](https://github.com/RafaelCartenet/mcp-databricks-server) — AI agents interact with Databricks ☆`40`
- [growthbook/growthbook-mcp](https://github.com/growthbook/growthbook-mcp) — GrowthBook flags and experiments ☆`24`
- [IBM/data-intelligence-mcp-server](https://github.com/IBM/data-intelligence-mcp-server) — data-intelligence-mcp-server is a centralized Model Context Protocol (MCP) server that provides a unified gateway for exposing and managing MCP tools across microservices in the Watsonx Data Intelligence ecosystem ☆`19`
- [yangkyeongmo/mcp-server-openmetadata](https://github.com/yangkyeongmo/mcp-server-openmetadata) — OpenMetadata integration for data catalog ☆`24`
- [mattijsdp/dbt-docs-mcp](https://github.com/mattijsdp/dbt-docs-mcp) — dbt documentation interaction ☆`23`
- [syucream/lightdash-mcp-server](https://github.com/syucream/lightdash-mcp-server) — Access to Lightdash analytics ☆`26`
- [yashshingvi/databricks-genie-MCP](https://github.com/yashshingvi/databricks-genie-MCP) —  ☆`18`
- [datumnova/ms-fabric-mcp](https://github.com/datumnova/ms-fabric-mcp) —  ☆`16`
### Jupyter & Notebooks

- [datalayer/jupyter-mcp-server](https://github.com/datalayer/jupyter-mcp-server) — Model Context Protocol (MCP) Server for Jupyter. ☆`1,223`
- [jjsantos01/jupyter-notebook-mcp](https://github.com/jjsantos01/jupyter-notebook-mcp) — A Model Context Protocol (MCP) for Jupyter Notebook ☆`130`
- [phisanti/MCPR](https://github.com/phisanti/MCPR) — AI agents in interactive R sessions ☆`26`
### Visualization

- [antvis/mcp-server-chart](https://github.com/antvis/mcp-server-chart) — 25+ visual charts using @antvis for data analysis ☆`4,259`
- [hustcc/mcp-echarts](https://github.com/hustcc/mcp-echarts) — ECharts visual charts with AI ☆`254`
- [isaacwasserman/mcp-vegalite-server](https://github.com/isaacwasserman/mcp-vegalite-server) — MCP server for Vega-Lite data visualization ☆`101`
- [palewire/datawrapper-mcp](https://github.com/palewire/datawrapper-mcp) — Create Datawrapper charts with AI ☆`48`
## Databases

### Analytics & Warehouses

- [ClickHouse/mcp-clickhouse](https://github.com/ClickHouse/mcp-clickhouse) — Connect ClickHouse to your AI assistants. ☆`832`
- [motherduckdb/mcp-server-motherduck](https://github.com/motherduckdb/mcp-server-motherduck) — Local MCP server for DuckDB and MotherDuck ☆`503`
- [Snowflake-Labs/mcp](https://github.com/Snowflake-Labs/mcp) — Snowflake Cortex AI and SQL orchestration ☆`292`
- [isaacwasserman/mcp-snowflake-server](https://github.com/isaacwasserman/mcp-snowflake-server) — MCP server for Snowflake database queries ☆`185`
- [ktanaka101/mcp-server-duckdb](https://github.com/ktanaka101/mcp-server-duckdb) — DuckDB database interaction ☆`177`
- [ergut/mcp-bigquery-server](https://github.com/ergut/mcp-bigquery-server) — MCP server for Google BigQuery integration ☆`145`
- [LucasHild/mcp-server-bigquery](https://github.com/LucasHild/mcp-server-bigquery) — Google BigQuery database access ☆`128`
- [pab1it0/adx-mcp-server](https://github.com/pab1it0/adx-mcp-server) — MCP server for Azure Data Explorer ☆`56`
- [aliyun/alibabacloud-adb-mysql-mcp-server](https://github.com/aliyun/alibabacloud-adb-mysql-mcp-server) — AnalyticDB for MySQL MCP Server ☆`32`
- [lishenxydlgzs/aws-athena-mcp](https://github.com/lishenxydlgzs/aws-athena-mcp) — MCP server to run AWS Athena queries ☆`41`
- [startreedata/mcp-pinot](https://github.com/startreedata/mcp-pinot) — MCP Server for Apache Pinot ☆`16`
- [iunera/druid-mcp-server](https://github.com/iunera/druid-mcp-server) — A comprehensive Model Context Protocol (MCP) server for Apache Druid that provides extensive tools, resources, and AI-assisted prompts for managing and analyzing Druid clusters. Built with Spring Boot and Spring AI, this server enables seamless integration between AI assistants and Apache Druid through standardized MCP protocol. ☆`16`
### Cache & Key-Value

- [redis/mcp-redis](https://github.com/redis/mcp-redis) — MCP server for Redis database operations ☆`553`
- [aliyun/alibabacloud-tablestore-mcp-server](https://github.com/aliyun/alibabacloud-tablestore-mcp-server) — MCP server for Alibaba Tablestore NoSQL ☆`157`
- [upstash/mcp-server](https://github.com/upstash/mcp-server) — Upstash Model Context Server ☆`56`
### Cloud Platforms

- [instantdb/instant](https://github.com/instantdb/instant) — Modern Firebase with real-time database ☆`10,362`
- [supabase/mcp](https://github.com/supabase/mcp) — Connect Supabase to your AI assistants ☆`2,831`
- [alexander-zuev/supabase-mcp-server](https://github.com/alexander-zuev/supabase-mcp-server) — MCP server for Supabase database and auth ☆`830`
- [neondatabase/mcp-server-neon](https://github.com/neondatabase/mcp-server-neon) — Neon Management API and databases ☆`620`
- [gannonh/firebase-mcp](https://github.com/gannonh/firebase-mcp) — Model Context Protocol (MCP) server for Firebase. ☆`247`
- [Aiven-Open/mcp-aiven](https://github.com/Aiven-Open/mcp-aiven) — Model Context Protocol server for Aiven ☆`26`
- [JoshuaRileyDev/supabase-mcp-server](https://github.com/JoshuaRileyDev/supabase-mcp-server) — MCP server for Supabase database operations ☆`51`
- [niledatabase/nile-mcp-server](https://github.com/niledatabase/nile-mcp-server) — Nile Database tenants, users, auth for LLMs ☆`17`
### Graph Databases

- [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j) — Neo4j Labs Model Context Protocol servers ☆`983`
- [neo4j-contrib/gds-agent](https://github.com/neo4j-contrib/gds-agent) — Neo4j Graph Data Science tools ☆`95`
- [ravenwits/mcp-server-arangodb](https://github.com/ravenwits/mcp-server-arangodb) — ArangoDB database interaction ☆`48`
- [da-okazaki/mcp-neo4j-server](https://github.com/da-okazaki/mcp-neo4j-server) — mcp-neo4j-server ☆`59`
- [FalkorDB/FalkorDB-MCPServer](https://github.com/FalkorDB/FalkorDB-MCPServer) — Connect LLMs to FalkorDB ☆`38`
### Multi-Database Tools

- [googleapis/mcp-toolbox](https://github.com/googleapis/mcp-toolbox) — Open source database MCP toolbox ☆`16,008`
- [bytebase/dbhub](https://github.com/bytebase/dbhub) — Token-efficient multi-database MCP ☆`3,228`
- [damms005/devdb-vscode](https://github.com/damms005/devdb-vscode) — Zero-config VS Code database extension ☆`1,426`
- [centralmind/gateway](https://github.com/centralmind/gateway) — Universal database MCP for LLMs ☆`539`
- [FreePeak/db-mcp-server](https://github.com/FreePeak/db-mcp-server) — MCP server for database operations ☆`407`
- [runekaagaard/mcp-alchemy](https://github.com/runekaagaard/mcp-alchemy) — MCP server for SQLAlchemy database operations ☆`412`
- [executeautomation/mcp-database-server](https://github.com/executeautomation/mcp-database-server) — Connect to SQLite, SQL Server, PostgreSQL ☆`377`
- [XGenerationLab/xiyan_mcp_server](https://github.com/XGenerationLab/xiyan_mcp_server) — Natural language database queries ☆`240`
- [s2-streamstore/s2-sdk-typescript](https://github.com/s2-streamstore/s2-sdk-typescript) — TypeScript SDK for S2, the durable streams API ☆`33`
- [schemacrawler/SchemaCrawler-AI-MCP-Server-Usage](https://github.com/schemacrawler/SchemaCrawler-AI-MCP-Server-Usage) — How to use SchemaCrawler AI MCP Server ☆`28`
- [prisma/mcp](https://github.com/prisma/mcp) — Prisma database workflows ☆`46`
- [fireproof-storage/mcp-database-server](https://github.com/fireproof-storage/mcp-database-server) — Store and load JSON documents from LLM tool use ☆`31`
- [datastrato/mcp-server-gravitino](https://github.com/datastrato/mcp-server-gravitino) — MCP server for Apache Gravitino ☆`23`
### NoSQL & Document

- [mongodb-js/mongodb-mcp-server](https://github.com/mongodb-js/mongodb-mcp-server) — Connect to MongoDB and Atlas clusters ☆`1,087`
- [kiliczsh/mcp-mongo-server](https://github.com/kiliczsh/mcp-mongo-server) — A Model Context Protocol Server for MongoDB ☆`282`
- [furey/mongodb-lens](https://github.com/furey/mongodb-lens) — MongoDB Lens: Full Featured MCP Server for MongoDB Databases ☆`204`
- [QuantGeekDev/mongo-mcp](https://github.com/QuantGeekDev/mongo-mcp) — A mongo db server for the model context protocol (MCP) ☆`175`
- [datastax/astra-db-mcp](https://github.com/datastax/astra-db-mcp) — An MCP server for Astra DB workloads ☆`39`
- [couchbase/mcp-server-couchbase](https://github.com/couchbase/mcp-server-couchbase) — Couchbase database cluster integration ☆`34`
### SQL Databases

- [crystaldba/postgres-mcp](https://github.com/crystaldba/postgres-mcp) — Postgres with read/write access and performance ☆`3,108`
- [benborla/mcp-server-mysql](https://github.com/benborla/mcp-server-mysql) — MCP server for MySQL database operations ☆`1,974`
- [designcomputer/mysql_mcp_server](https://github.com/designcomputer/mysql_mcp_server) — Secure MySQL database interaction ☆`1,340`
- [subnetmarco/pgmcp](https://github.com/subnetmarco/pgmcp) — An MCP server to query any Postgres database in natural language. ☆`540`
- [apache/doris-mcp-server](https://github.com/apache/doris-mcp-server) — Apache Doris MCP Server ☆`318`
- [wenb1n-dev/mysql_mcp_server_pro](https://github.com/wenb1n-dev/mysql_mcp_server_pro) — Enhanced MySQL with anomaly analysis ☆`246`
- [StarRocks/mcp-server-starrocks](https://github.com/StarRocks/mcp-server-starrocks) — StarRocks MCP (Model Context Protocol) Server ☆`181`
- [MariaDB/mcp](https://github.com/MariaDB/mcp) — MariaDB MCP (Model Context Protocol) server implementation ☆`184`
- [call518/MCP-PostgreSQL-Ops](https://github.com/call518/MCP-PostgreSQL-Ops) — PostgreSQL operations and monitoring ☆`154`
- [f4ww4z/mcp-mysql-server](https://github.com/f4ww4z/mcp-mysql-server) — A Model Context Protocol server for MySQL database operations ☆`166`
- [tuannvm/mcp-trino](https://github.com/tuannvm/mcp-trino) — High-performance Trino MCP in Go ☆`117`
- [oceanbase/awesome-oceanbase-mcp](https://github.com/oceanbase/awesome-oceanbase-mcp) — MCP Server for OceanBase database and its tools ☆`107`
- [jparkerweb/mcp-sqlite](https://github.com/jparkerweb/mcp-sqlite) — Comprehensive SQLite interaction ☆`119`
- [hannesrudolph/sqlite-explorer-fastmcp-mcp-server](https://github.com/hannesrudolph/sqlite-explorer-fastmcp-mcp-server) — Read-only SQLite database access ☆`107`
- [wenb1n-dev/SmartDB_MCP](https://github.com/wenb1n-dev/SmartDB_MCP) — Universal database MCP for MySQL, PostgreSQL, Oracle and more ☆`87`
- [donghao1393/mcp-dbutils](https://github.com/donghao1393/mcp-dbutils) — Multi-database connector for SQLite, MySQL, PostgreSQL ☆`90`
- [Teradata/teradata-mcp-server](https://github.com/Teradata/teradata-mcp-server) — Teradata database integration ☆`53`
- [aliyun/alibabacloud-rds-openapi-mcp-server](https://github.com/aliyun/alibabacloud-rds-openapi-mcp-server) — MCP server for RDS Services via OPENAPI. ☆`54`
- [Zhwt/go-mcp-mysql](https://github.com/Zhwt/go-mcp-mysql) — Go-based MCP server for MySQL ☆`64`
- [singlestore-labs/mcp-server-singlestore](https://github.com/singlestore-labs/mcp-server-singlestore) — SingleStore database management API ☆`32`
- [ydb-platform/ydb-mcp](https://github.com/ydb-platform/ydb-mcp) — MCP server for YDB distributed database ☆`28`
- [isdaniel/pgtuner_mcp](https://github.com/isdaniel/pgtuner_mcp) — provides AI-powered PostgreSQL performance tuning capabilities. ☆`25`
- [pingcap/pytidb](https://github.com/pingcap/pytidb) — TiDB AI SDK for apps and agents ☆`33`
- [aliyun/alibabacloud-adbpg-mcp-server](https://github.com/aliyun/alibabacloud-adbpg-mcp-server) —  ☆`16`
- [panasenco/mcp-sqlite](https://github.com/panasenco/mcp-sqlite) — SQLite with Datasette metadata support ☆`24`
- [ahmedmustahid/postgres-mcp-server](https://github.com/ahmedmustahid/postgres-mcp-server) — MCP server for PostgreSQL ☆`31`
- [dolthub/dolt-mcp](https://github.com/dolthub/dolt-mcp) — The MCP server for Dolt ☆`20`
- [OpenLinkSoftware/mcp-sqlalchemy-server](https://github.com/OpenLinkSoftware/mcp-sqlalchemy-server) — ODBC server with FastAPI and SQLAlchemy ☆`24`
- [c4pt0r/mcp-server-tidb](https://github.com/c4pt0r/mcp-server-tidb) — mcp server for tidb ☆`24`
- [Xexr/mcp-libsql](https://github.com/Xexr/mcp-libsql) — MCP server for libSQL database ☆`21`
- [abel9851/mcp-server-mariadb](https://github.com/abel9851/mcp-server-mariadb) — An mcp server that provides read-only access to MariaDB. ☆`20`
- [Dataring-engineering/mcp-server-trino](https://github.com/Dataring-engineering/mcp-server-trino) — MCP Server for Trino ☆`18`
### Search Engines

- [elastic/mcp-server-elasticsearch](https://github.com/elastic/mcp-server-elasticsearch) — Elasticsearch queries and index management ☆`698`
- [cr7258/elasticsearch-mcp-server](https://github.com/cr7258/elasticsearch-mcp-server) — Elasticsearch and OpenSearch interaction ☆`299`
- [meilisearch/meilisearch-mcp](https://github.com/meilisearch/meilisearch-mcp) — Meilisearch interaction via LLM interfaces ☆`194`
- [opensearch-project/opensearch-mcp-server-py](https://github.com/opensearch-project/opensearch-mcp-server-py) — OpenSearch cluster interaction for AI ☆`141`
- [vectorize-io/vectorize-mcp-server](https://github.com/vectorize-io/vectorize-mcp-server) — Official Vectorize MCP Server ☆`109`
- [suhail-ak-2/mcp-typesense-server](https://github.com/suhail-ak-2/mcp-typesense-server) — Typesense search for AI assistants ☆`19`
### Spreadsheets & No-Code

- [baserow/baserow](https://github.com/baserow/baserow) — No-code database, apps, agents with AI ☆`5,402`
- [xing5/mcp-google-sheets](https://github.com/xing5/mcp-google-sheets) — Google Drive and Sheets integration ☆`957`
- [domdomegg/airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server) — Airtable bases integration for AI systems ☆`453`
- [freema/mcp-gsheets](https://github.com/freema/mcp-gsheets) — Google Sheets read, write, manipulate ☆`86`
- [rashidazarang/airtable-mcp](https://github.com/rashidazarang/airtable-mcp) — Airtable integration for AI applications ☆`87`
- [edwinbernadus/nocodb-mcp-server](https://github.com/edwinbernadus/nocodb-mcp-server) — nocodb mcp server ☆`74`
- [felores/airtable-mcp](https://github.com/felores/airtable-mcp) — Manage Airtable bases and records ☆`75`
- [proompteng/bilig](https://github.com/proompteng/bilig) — Headless spreadsheet WorkPaper MCP server for formula readback, input edits, and JSON persistence in Node.js agent workflows. ☆`34`
### Streaming & Messaging

- [confluentinc/mcp-confluent](https://github.com/confluentinc/mcp-confluent) — MCP server for Confluent Kafka platform ☆`164`
- [tuannvm/kafka-mcp-server](https://github.com/tuannvm/kafka-mcp-server) — Apache Kafka server in Go ☆`53`
- [kenliao94/mcp-server-rabbitmq](https://github.com/kenliao94/mcp-server-rabbitmq) — MCP server for interacting with RabbitMQ ☆`39`
### Time-Series & Metrics

- [GreptimeTeam/greptimedb](https://github.com/GreptimeTeam/greptimedb) — Unified observability DB for metrics, logs, traces ☆`6,496`
- [pab1it0/prometheus-mcp-server](https://github.com/pab1it0/prometheus-mcp-server) — MCP server for Prometheus metrics ☆`504`
- [VictoriaMetrics/mcp-victorialogs](https://github.com/VictoriaMetrics/mcp-victorialogs) — VictoriaLogs log management integration ☆`93`
- [apache/iotdb-mcp-server](https://github.com/apache/iotdb-mcp-server) — Apache IoTDB MCP Server ☆`38`
- [influxdata/influxdb3_mcp_server](https://github.com/influxdata/influxdb3_mcp_server) — MCP Server for InfluxDB 3 ☆`36`
- [GreptimeTeam/greptimedb-mcp-server](https://github.com/GreptimeTeam/greptimedb-mcp-server) — A Model Context Protocol (MCP) server for GreptimeDB ☆`28`
- [idoru/influxdb-mcp-server](https://github.com/idoru/influxdb-mcp-server) — An MCP Server for querying InfluxDB ☆`43`
### Vector Databases

- [qdrant/mcp-server-qdrant](https://github.com/qdrant/mcp-server-qdrant) — Official Qdrant vector database MCP ☆`1,477`
- [chroma-core/chroma-mcp](https://github.com/chroma-core/chroma-mcp) — Chroma vector database capabilities ☆`574`
- [zilliztech/mcp-server-milvus](https://github.com/zilliztech/mcp-server-milvus) — Model Context Protocol Servers for Milvus ☆`237`
- [weaviate/mcp-server-weaviate](https://github.com/weaviate/mcp-server-weaviate) — MCP (Model Context Protocol) server for Weaviate ☆`162`
- [pinecone-io/pinecone-mcp](https://github.com/pinecone-io/pinecone-mcp) — Connect Pinecone to AI assistants ☆`70`
- [privetin/chroma](https://github.com/privetin/chroma) — MCP server for Chroma ☆`41`
## Developer Tools

### API Tools

- [tadata-org/fastapi_mcp](https://github.com/tadata-org/fastapi_mcp) — Expose FastAPI endpoints as MCP tools ☆`11,950`
- [WordPress/mcp-adapter](https://github.com/WordPress/mcp-adapter) — Bridge Abilities API to MCP ☆`1,475`
- [zcaceres/fetch-mcp](https://github.com/zcaceres/fetch-mcp) — A flexible HTTP fetching Model Context Protocol server. ☆`802`
- [automation-ai-labs/mcp-link](https://github.com/automation-ai-labs/mcp-link) — Convert Any OpenAPI V3 API to MCP Server ☆`620`
- [blurrah/mcp-graphql](https://github.com/blurrah/mcp-graphql) — Model Context Protocol server for GraphQL ☆`403`
- [apollographql/apollo-mcp-server](https://github.com/apollographql/apollo-mcp-server) — Apollo MCP Server ☆`299`
- [postmanlabs/postman-mcp-server](https://github.com/postmanlabs/postman-mcp-server) — Postman MCP Server — connect AI agents (Claude Code, Cursor, VS Code Copilot, Gemini CLI) to your Postman collections, OpenAPI specs, and environments via Model Context Protocol (MCP) ☆`287`
- [MFYDev/ghost-mcp](https://github.com/MFYDev/ghost-mcp) — Interact with Ghost CMS via LLM ☆`216`
- [delano/postman-mcp-server](https://github.com/delano/postman-mcp-server) — An MCP server that provides access to Postman. ☆`157`
- [hostinger/api-mcp-server](https://github.com/hostinger/api-mcp-server) — MCP server for Hostinger API integration ☆`132`
- [webflow/mcp-server](https://github.com/webflow/mcp-server) — Model Context Protocol (MCP) server for the Webflow Data API. ☆`134`
- [shannonlal/mcp-postman](https://github.com/shannonlal/mcp-postman) — MCP Server for running Postman Collections with Newman ☆`84`
- [Kong/mcp-konnect](https://github.com/Kong/mcp-konnect) — Interact with Kong Konnect APIs ☆`43`
- [ivo-toby/contentful-mcp](https://github.com/ivo-toby/contentful-mcp) — Contentful CMS Management API ☆`62`
- [shanejonas/openrpc-mcp-server](https://github.com/shanejonas/openrpc-mcp-server) — JSON-RPC via OpenRPC ☆`43`
- [Omedia/mcp-server-drupal](https://github.com/Omedia/mcp-server-drupal) — Drupal MCP module companion ☆`51`
- [Jktfe/serveMyAPI](https://github.com/Jktfe/serveMyAPI) — MCP server for custom API serving ☆`25`
- [xxxbrian/mcp-rquest](https://github.com/xxxbrian/mcp-rquest) — Browser-like HTTP with TLS fingerprinting ☆`48`
- [hannesj/mcp-graphql-schema](https://github.com/hannesj/mcp-graphql-schema) — GraphQL Schema Model Context Protocol Server ☆`47`
- [Arize-ai/text-to-graphql-mcp](https://github.com/Arize-ai/text-to-graphql-mcp) — MCP server for text-to-GraphQL conversion ☆`24`
- [hijaz/postmancer](https://github.com/hijaz/postmancer) — REST client replacing Postman/Insomnia ☆`28`
- [drestrepom/mcp_graphql](https://github.com/drestrepom/mcp_graphql) — Interact with GraphQL APIs via MCP tools ☆`20`
- [fotoetienne/gqai](https://github.com/fotoetienne/gqai) — Turn any GraphQL endpoint into a set of MCP tools ☆`23`
### CI/CD & DevOps

- [czlonkowski/n8n-mcp](https://github.com/czlonkowski/n8n-mcp) — Build n8n workflows with AI assistants ☆`22,398`
- [leonardsellem/n8n-mcp-server](https://github.com/leonardsellem/n8n-mcp-server) — Tools for interacting with n8n API ☆`1,631`
- [utensils/mcp-nixos](https://github.com/utensils/mcp-nixos) — MCP-NixOS - Model Context Protocol Server for NixOS resources ☆`773`
- [ckreiling/mcp-server-docker](https://github.com/ckreiling/mcp-server-docker) — MCP server for Docker ☆`733`
- [QuantGeekDev/docker-mcp](https://github.com/QuantGeekDev/docker-mcp) — A docker MCP Server (modelcontextprotocol) ☆`497`
- [TencentEdgeOne/edgeone-makers-mcp](https://github.com/TencentEdgeOne/edgeone-makers-mcp) — Deploy HTML to EdgeOne Pages with public URL ☆`431`
- [jamsocket/forevervm](https://github.com/jamsocket/forevervm) — Stateful AI code sandboxes ☆`227`
- [docker/hub-mcp](https://github.com/docker/hub-mcp) — Docker Hub MCP Server ☆`158`
- [DefangLabs/defang](https://github.com/DefangLabs/defang) — MCP server for Defang cloud deployment ☆`164`
- [nacos-group/nacos-mcp-router](https://github.com/nacos-group/nacos-mcp-router) — MCP server discovery, install, and proxy ☆`180`
- [yangkyeongmo/mcp-server-apache-airflow](https://github.com/yangkyeongmo/mcp-server-apache-airflow) — MCP server for Apache Airflow workflows ☆`172`
- [OctopusDeploy/mcp-server](https://github.com/OctopusDeploy/mcp-server) — Octopus Deploy Official MCP Server ☆`98`
- [harness/mcp-server](https://github.com/harness/mcp-server) — This is the official repo for the Harness MCP server ☆`85`
- [CircleCI-Public/mcp-server-circleci](https://github.com/CircleCI-Public/mcp-server-circleci) — MCP server for CircleCI CI/CD pipeline integration ☆`86`
- [Vortiago/mcp-azure-devops](https://github.com/Vortiago/mcp-azure-devops) — AI assistants with Azure DevOps ☆`79`
- [buildkite/buildkite-mcp-server](https://github.com/buildkite/buildkite-mcp-server) — Official MCP Server for Buildkite. ☆`52`
- [call518/MCP-Airflow-API](https://github.com/call518/MCP-Airflow-API) — Apache Airflow API integration ☆`49`
- [bitrise-io/bitrise-mcp](https://github.com/bitrise-io/bitrise-mcp) — Bitrise CI/CD app and build management ☆`40`
- [IvanAmador/vercel-ai-docs-mcp](https://github.com/IvanAmador/vercel-ai-docs-mcp) — Vercel AI SDK documentation search ☆`50`
- [launchdarkly/mcp-server](https://github.com/launchdarkly/mcp-server) — LaunchDarkly's Model Context Protocol (MCP) Server ☆`22`
- [configcat/mcp-server](https://github.com/configcat/mcp-server) — Official ConfigCat Model Context Protocol (MCP) Server ☆`17`
- [endorhq/cli](https://github.com/endorhq/cli) — Sandboxed environments for favorite services via MCP ☆`27`
- [gofireflyio/firefly-mcp](https://github.com/gofireflyio/firefly-mcp) — Firefly MCP ☆`16`
- [conductor-oss/conductor-mcp](https://github.com/conductor-oss/conductor-mcp) — Model Context Protocol server for Orkes Conductor ☆`16`
- [leonardosepulvedat/mcp-n8n](https://github.com/leonardosepulvedat/mcp-n8n) — Complete n8n API integration for Claude Desktop and Cursor - 100 workflow templates with intelligent matching ☆`21`
- [axliupore/mcp-code-runner](https://github.com/axliupore/mcp-code-runner) — MCP server for executing code in Docker containers ☆`18`
### Code Analysis

- [bgauryy/octocode](https://github.com/bgauryy/octocode) — MCP server for semantic code search and context generation ☆`899`
- [SonarSource/sonarqube-mcp-server](https://github.com/SonarSource/sonarqube-mcp-server) — Official SonarQube MCP Server for code quality and security in AI agents ☆`606`
- [admica/FileScopeMCP](https://github.com/admica/FileScopeMCP) — Codebase dependency diagrams ☆`299`
- [janreges/ai-distiller](https://github.com/janreges/ai-distiller) — Fast tool for extracting essential public information from code ☆`163`
- [st3v3nmw/sourcerer-mcp](https://github.com/st3v3nmw/sourcerer-mcp) — Semantic code search reducing token waste ☆`118`
- [micl2e2/code-to-tree](https://github.com/micl2e2/code-to-tree) — Source code to AST tree conversion ☆`88`
- [codacy/codacy-mcp-server](https://github.com/codacy/codacy-mcp-server) — Codacy's MCP Server implementation ☆`61`
- [CodeLogicIncEngineering/codelogic-mcp-server](https://github.com/CodeLogicIncEngineering/codelogic-mcp-server) — Codelogic software dependency analysis ☆`38`
- [Disentinel/grafema](https://github.com/Disentinel/grafema) — Semantic code graph MCP server for AI coding agents — 40+ tools for call-chain tracing, data-flow analysis, and semantic code search ☆`36`
- [azer/react-analyzer-mcp](https://github.com/azer/react-analyzer-mcp) — React code analysis and docs generation ☆`59`
- [vezlo/src-to-kb](https://github.com/vezlo/src-to-kb) — Convert source code to LLM ready knowledge base ☆`38`
- [cqfn/aibolit-mcp-server](https://github.com/cqfn/aibolit-mcp-server) — Aibolit Java static analyzer for AI agents ☆`27`
- [kandrwmrtn/cplusplus_mcp](https://github.com/kandrwmrtn/cplusplus_mcp) — MCP server for C++ codebase analysis using libclang ☆`30`
- [j4c0bs/mcp-server-sql-analyzer](https://github.com/j4c0bs/mcp-server-sql-analyzer) — MCP server for SQL static analysis. ☆`32`
- [PromptExecution/rust-cargo-docs-rag-mcp](https://github.com/PromptExecution/rust-cargo-docs-rag-mcp) — MCP tools for Rust Context Engineering (rustdocs, rust analyzer) ☆`19`
- [isiahw1/mcp-server-bing-webmaster](https://github.com/isiahw1/mcp-server-bing-webmaster) — MCP server providing access to Bing Webmaster Tools API endpoints for SEO management and analytics ☆`17`
### Debuggers

- [jasonjmcghee/claude-debugs-for-you](https://github.com/jasonjmcghee/claude-debugs-for-you) — Interactive debugging via MCP and VS Code ☆`511`
- [cameroncooke/reloaderoo](https://github.com/cameroncooke/reloaderoo) — Powerful MCP debugging proxy and CLI inspection tool. ☆`126`
- [stass/lldb-mcp](https://github.com/stass/lldb-mcp) — LLDB MCP server ☆`111`
- [pansila/mcp_server_gdb](https://github.com/pansila/mcp_server_gdb) — MCP Server to expose the GDB debugging capabilities ☆`68`
### Design & UI

- [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) — Figma layout info for AI coding agents ☆`15,485`
- [grab/cursor-talk-to-figma-mcp](https://github.com/grab/cursor-talk-to-figma-mcp) — Cursor and Figma communication ☆`6,931`
- [21st-dev/magic-mcp](https://github.com/21st-dev/magic-mcp) — Frontend development with AI like Magic ☆`5,498`
- [Jpisnice/shadcn-ui-mcp-server](https://github.com/Jpisnice/shadcn-ui-mcp-server) — MCP server for shadcn/ui component library ☆`2,881`
- [hustcc/mcp-mermaid](https://github.com/hustcc/mcp-mermaid) — Generate mermaid diagram and chart with AI MCP dynamically. ☆`613`
- [mastergo-design/mastergo-magic-mcp](https://github.com/mastergo-design/mastergo-magic-mcp) — Connect MasterGo to AI assistants ☆`274`
- [public-ui/kolibri](https://github.com/public-ui/kolibri) — The accessible HTML-Standard ☆`273`
- [storybookjs/mcp](https://github.com/storybookjs/mcp) — MCP server for Storybook UI component library ☆`264`
- [YuChenSSR/mindmap-mcp-server](https://github.com/YuChenSSR/mindmap-mcp-server) — mindmap, mcp server, artifact ☆`236`
- [freema/mcp-design-system-extractor](https://github.com/freema/mcp-design-system-extractor) — MCP server for extracting design system components ☆`69`
- [starwind-ui/starwind-ui-mcp](https://github.com/starwind-ui/starwind-ui-mcp) — Starwind UI for Cursor and Windsurf ☆`35`
- [smartzan63/lucid-mcp-server](https://github.com/smartzan63/lucid-mcp-server) —  ☆`18`
- [themesberg/flowbite-mcp](https://github.com/themesberg/flowbite-mcp) — Figma to code with Flowbite ☆`38`
- [NonicaTeam/AI-Connector-for-Revit](https://github.com/NonicaTeam/AI-Connector-for-Revit) — This repository is to log suggestions and issues regarding the AI Connector for Revit in NonicaTab. ☆`16`
- [themeselection/flyonui-mcp](https://github.com/themeselection/flyonui-mcp) — MCP server for flyonUI ☆`32`
- [heilgar/shadcn-ui-mcp-server](https://github.com/heilgar/shadcn-ui-mcp-server) — MCP server for shadcn/ui component library ☆`24`
- [kapilduraphe/webflow-mcp-server](https://github.com/kapilduraphe/webflow-mcp-server) — Webflow MCP server ☆`21`
- [2niuhe/mcp_plantuml](https://github.com/2niuhe/mcp_plantuml) — Generate PlantUML Diagrams as PNG/SVG with Embedded Web Viewer ☆`16`
### Diagrams

- [jinzcdev/markmap-mcp-server](https://github.com/jinzcdev/markmap-mcp-server) — Markdown to interactive mind maps ☆`272`
- [veelenga/claude-mermaid](https://github.com/veelenga/claude-mermaid) — MCP Server to previewing mermaid diagrams with live reload ☆`193`
- [apeyroux/mcp-xmind](https://github.com/apeyroux/mcp-xmind) — Analyze and query XMind mind maps ☆`88`
- [Narasimhaponnada/mermaid-mcp](https://github.com/Narasimhaponnada/mermaid-mcp) — MCP server for Mermaid diagram generation ☆`50`
### Documentation

- [upstash/context7](https://github.com/upstash/context7) — Up-to-date code docs for LLMs ☆`59,671`
- [lingodotdev/lingo.dev](https://github.com/lingodotdev/lingo.dev) — MCP server for Lingo localization platform ☆`5,401`
- [MicrosoftDocs/mcp](https://github.com/MicrosoftDocs/mcp) — Microsoft Learn MCP for LLMs ☆`1,795`
- [kimsungwhee/apple-docs-mcp](https://github.com/kimsungwhee/apple-docs-mcp) — Apple Developer Documentation search ☆`1,346`
- [andrea9293/mcp-documentation-server](https://github.com/andrea9293/mcp-documentation-server) — Document management with Gemini ☆`339`
- [szeider/consult7](https://github.com/szeider/consult7) — MCP server to consult a language model with large context size ☆`295`
- [Govcraft/rust-docs-mcp-server](https://github.com/Govcraft/rust-docs-mcp-server) — Rust documentation lookup ☆`288`
- [khromov/svelte-llm-mcp](https://github.com/khromov/svelte-llm-mcp) — Svelte developer documentation as an MCP and in llms.txt format ☆`161`
- [mrjoshuak/godoc-mcp](https://github.com/mrjoshuak/godoc-mcp) — MCP server that reduces LLM context usage when AI coding agents work with Go — structured documentation instead of source-file dumps. ☆`124`
- [tosin2013/mcp-adr-analysis-server](https://github.com/tosin2013/mcp-adr-analysis-server) — AI-powered ADR and architecture analysis ☆`32`
- [V0v1kkk/DotNetMetadataMcpServer](https://github.com/V0v1kkk/DotNetMetadataMcpServer) — .NET type metadata for AI coding agents ☆`29`
- [yWorks/mcp-typescribe](https://github.com/yWorks/mcp-typescribe) — TypeScript library support for LLMs ☆`46`
- [yikakia/godoc-mcp-server](https://github.com/yikakia/godoc-mcp-server) — Go package docs from pkg.go.dev ☆`38`
- [inkeep/mcp-server-python](https://github.com/inkeep/mcp-server-python) — Inkeep MCP Server ☆`24`
- [augmentedivan/fabric-mcp-server](https://github.com/augmentedivan/fabric-mcp-server) — Fabric patterns with AI agents ☆`18`
- [Excoriate/mcp-terragrunt-docs](https://github.com/Excoriate/mcp-terragrunt-docs) — Terragrunt documentation context ☆`21`
- [idachev/mcp-javadc](https://github.com/idachev/mcp-javadc) — MCP server for decompiling Java .class files to source ☆`20`
- [oborchers/mcp-server-docy](https://github.com/oborchers/mcp-server-docy) — Documentation access capabilities ☆`18`
### IDE & Editors

- [getsentry/XcodeBuildMCP](https://github.com/getsentry/XcodeBuildMCP) — MCP server for Xcode build operations ☆`6,133`
- [isaacphi/mcp-language-server](https://github.com/isaacphi/mcp-language-server) — MCP server implementing Language Server Protocol ☆`1,570`
- [JetBrains/mcp-jetbrains](https://github.com/JetBrains/mcp-jetbrains) — MCP server for JetBrains IDE integration ☆`963`
- [juehang/vscode-mcp-server](https://github.com/juehang/vscode-mcp-server) — VS Code editing features for LLM coding ☆`380`
- [r-huijts/xcode-mcp-server](https://github.com/r-huijts/xcode-mcp-server) — Xcode project management ☆`385`
- [bigcodegen/mcp-neovim-server](https://github.com/bigcodegen/mcp-neovim-server) — Control Neovim via MCP ☆`321`
- [hechtcarmel/jetbrains-index-mcp-plugin](https://github.com/hechtcarmel/jetbrains-index-mcp-plugin) — JetBrains plugin for MCP index integration ☆`292`
- [biegehydra/BifrostMCP](https://github.com/biegehydra/BifrostMCP) — VS Code semantic tools via MCP ☆`222`
- [tumf/mcp-text-editor](https://github.com/tumf/mcp-text-editor) — Line-oriented text editing for LLM tools ☆`198`
- [Tritlo/lsp-mcp](https://github.com/Tritlo/lsp-mcp) — An MCP server that lets you interact with LSP servers ☆`123`
- [hloiseau/mcp-gopls](https://github.com/hloiseau/mcp-gopls) — Go LSP server via gopls ☆`96`
- [hechtcarmel/jetbrains-debugger-mcp-plugin](https://github.com/hechtcarmel/jetbrains-debugger-mcp-plugin) — JetBrains debugger control via MCP ☆`91`
- [marimo-team/codemirror-mcp](https://github.com/marimo-team/codemirror-mcp) — CodeMirror MCP extension ☆`78`
- [ShenghaiWang/xcodebuild](https://github.com/ShenghaiWang/xcodebuild) — Xcode iOS build with error feedback ☆`84`
- [linw1995/nvim-mcp](https://github.com/linw1995/nvim-mcp) — MCP server for Neovim integration ☆`63`
- [laurynas-biveinis/elisp-dev-mcp](https://github.com/laurynas-biveinis/elisp-dev-mcp) — Emacs Elisp development tools for LLMs ☆`46`
- [AB498/code-context-provider-mcp](https://github.com/AB498/code-context-provider-mcp) — Code context and analysis for AI ☆`20`
### MCP SDKs

- [PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp) — Python framework for building MCP servers and clients ☆`26,826`
- [mark3labs/mcp-go](https://github.com/mark3labs/mcp-go) — Go implementation of MCP ☆`8,920`
- [QuantGeekDev/mcp-framework](https://github.com/QuantGeekDev/mcp-framework) — TypeScript framework with auto-discovery ☆`930`
- [bhauman/clojure-mcp](https://github.com/bhauman/clojure-mcp) — Clojure MCP ☆`770`
- [php-mcp/laravel](https://github.com/php-mcp/laravel) — Laravel SDK for building MCP servers ☆`477`
- [opgginc/laravel-mcp-server](https://github.com/opgginc/laravel-mcp-server) — Laravel package for MCP servers ☆`330`
- [Epistates/turbomcp](https://github.com/Epistates/turbomcp) — High-performance MCP framework ☆`92`
- [reflagcom/javascript](https://github.com/reflagcom/javascript) — JS/TS SDKs for Reflag ☆`25`
- [oatpp/oatpp-mcp](https://github.com/oatpp/oatpp-mcp) — C++ MCP implementation for Oat++ framework ☆`50`
- [kpavlov/tachyon](https://github.com/kpavlov/tachyon) — Tachyon MCP Runtime for JVM - a Java Model Context Protocol (MCP) server with Streamable HTTP, native Netty transports, tasks, resources, prompts, completions, resumable sessions, and stateless deployment support. ☆`25`
- [Super-I-Tech/mcp_plexus](https://github.com/Super-I-Tech/mcp_plexus) — Multi-tenant MCP framework built on FastMCP ☆`30`
- [stephencme/create-mcp-ts](https://github.com/stephencme/create-mcp-ts) — TypeScript MCP server template ☆`21`
### Mobile Development

- [mobile-next/mobile-mcp](https://github.com/mobile-next/mobile-mcp) — Mobile automation for iOS, Android, emulators ☆`5,608`
- [joshuayoes/ios-simulator-mcp](https://github.com/joshuayoes/ios-simulator-mcp) — MCP server for interacting with the iOS simulator ☆`2,110`
- [minhalvp/android-mcp-server](https://github.com/minhalvp/android-mcp-server) — Android device control via adb ☆`786`
- [hyperb1iss/droidmind](https://github.com/hyperb1iss/droidmind) — Control your Android devices with AI using Model Context Protocol ☆`421`
- [InditexTech/mcp-server-simulator-ios-idb](https://github.com/InditexTech/mcp-server-simulator-ios-idb) — MCP server for iOS simulator via IDB ☆`307`
- [mhmzdev/figma-flutter-mcp](https://github.com/mhmzdev/figma-flutter-mcp) — Figma design tokens for Flutter code agents ☆`242`
- [zillow/auto-mobile](https://github.com/zillow/auto-mobile) — Mobile automation tools with MCP ☆`79`
- [JoshuaRileyDev/simulator-mcp-server](https://github.com/JoshuaRileyDev/simulator-mcp-server) — MCP server for iOS Simulator control ☆`53`
- [Tommertom/awesome-ionic-mcp](https://github.com/Tommertom/awesome-ionic-mcp) — Ionic and Capacitor mobile app development ☆`45`
- [XixianLiang/HarmonyOS-mcp-server](https://github.com/XixianLiang/HarmonyOS-mcp-server) — MCP server for manipulating HarmonyOS next devices. ☆`34`
- [ambar/simctl-mcp](https://github.com/ambar/simctl-mcp) — MCP server for iOS Simulator control ☆`20`
### OpenAPI

- [janwilmake/openapi-mcp-server](https://github.com/janwilmake/openapi-mcp-server) — Complex OpenAPI exploration with plain language ☆`899`
- [ckanthony/openapi-mcp](https://github.com/ckanthony/openapi-mcp) — Dockerized OpenAPI to MCP conversion ☆`189`
- [twilio-labs/mcp](https://github.com/twilio-labs/mcp) — OpenAPI to MCP tools and Twilio APIs ☆`108`
- [kadykov/mcp-openapi-schema-explorer](https://github.com/kadykov/mcp-openapi-schema-explorer) — Token-efficient OpenAPI/Swagger exploration ☆`75`
- [zaizaizhao/mcp-swagger-server](https://github.com/zaizaizhao/mcp-swagger-server) — OpenAPI/Swagger to MCP conversion ☆`72`
- [ReAPI-com/mcp-openapi](https://github.com/ReAPI-com/mcp-openapi) — OpenAPI specification MCP server. ☆`88`
- [baryhuang/mcp-server-any-openapi](https://github.com/baryhuang/mcp-server-any-openapi) — Call APIs via semantic search ☆`82`
- [hannesj/mcp-openapi-schema](https://github.com/hannesj/mcp-openapi-schema) — OpenAPI Schema Model Context Protocol Server ☆`50`
- [criteo/openapi-to-mcp](https://github.com/criteo/openapi-to-mcp) — An MCP server for your API ☆`34`
### Package Managers

- [arvindand/maven-tools-mcp](https://github.com/arvindand/maven-tools-mcp) — Maven Central dependency intelligence for JVM build tools ☆`29`
- [Artmann/package-registry-mcp](https://github.com/Artmann/package-registry-mcp) — NPM, Cargo, PyPi, NuGet package search ☆`39`
- [Bigsy/maven-mcp-server](https://github.com/Bigsy/maven-mcp-server) — Maven build and dependency tools ☆`33`
- [jeannier/homebrew-mcp](https://github.com/jeannier/homebrew-mcp) — Homebrew package management ☆`29`
- [btwiuse/npm-search-mcp-server](https://github.com/btwiuse/npm-search-mcp-server) — MCP server for searching npm packages ☆`16`
- [subelsky/bundler_mcp](https://github.com/subelsky/bundler_mcp) — MCP server for Ruby Bundler integration ☆`19`
### Robotics & Automation

- [trycua/cua](https://github.com/trycua/cua) — MCP server for CUA platform ☆`20,525`
- [robotmcp/ros-mcp-server](https://github.com/robotmcp/ros-mcp-server) — ROS robot control with Claude and GPT ☆`1,357`
- [omni-mcp/isaac-sim-mcp](https://github.com/omni-mcp/isaac-sim-mcp) — Isaac Simulation MCP Extension and Server ☆`180`
- [abrinsmead/mindpilot-mcp](https://github.com/abrinsmead/mindpilot-mcp) — Visualize code and architect new systems ☆`90`
- [lpigeon/unitree-go2-mcp-server](https://github.com/lpigeon/unitree-go2-mcp-server) — MCP server for Unitree Go2 robot control ☆`85`
- [wise-vision/ros2_mcp](https://github.com/wise-vision/ros2_mcp) — ROS 2 robotics AI bridge ☆`83`
- [Yutarop/ros-mcp](https://github.com/Yutarop/ros-mcp) — MCP server for ROS to control robots via topics, services, and actions. ☆`35`
### Task Management

- [cjo4m06/mcp-shrimp-task-manager](https://github.com/cjo4m06/mcp-shrimp-task-manager) — Task manager with chain-of-thought and reflection ☆`2,134`
- [amxv/mcp-manager](https://github.com/amxv/mcp-manager) — Web UI to manage MCP servers in Claude ☆`289`
### Testing & QA

- [debugg-ai/debugg-ai-mcp](https://github.com/debugg-ai/debugg-ai-mcp) — AI-managed end-to-end testing ☆`83`
- [QAInsights/jmeter-mcp-server](https://github.com/QAInsights/jmeter-mcp-server) — JMeter AI workflow integration ☆`69`
- [SmartBear/smartbear-mcp](https://github.com/SmartBear/smartbear-mcp) — SmartBear's official MCP Server ☆`40`
- [mrexodia/user-feedback-mcp](https://github.com/mrexodia/user-feedback-mcp) — Human-in-the-loop workflow for Cursor ☆`53`
- [reportportal/reportportal-mcp-server](https://github.com/reportportal/reportportal-mcp-server) — MCP server for ReportPortal ☆`22`
- [hungthai1401/bruno-mcp](https://github.com/hungthai1401/bruno-mcp) — MCP Server for running Bruno Collections ☆`44`
- [Hypersequent/qasphere-mcp](https://github.com/Hypersequent/qasphere-mcp) — MCP Server for QA Sphere TMS ☆`23`
- [currents-dev/currents-mcp](https://github.com/currents-dev/currents-mcp) — Currents MCP Server ☆`17`
- [QAInsights/k6-mcp-server](https://github.com/QAInsights/k6-mcp-server) — k6 MCP server ☆`25`
### Utilities

- [anaisbetts/mcp-installer](https://github.com/anaisbetts/mcp-installer) — An MCP server that installs other MCP servers for you ☆`1,532`
- [githejie/mcp-server-calculator](https://github.com/githejie/mcp-server-calculator) — A Model Context Protocol server for calculating. ☆`153`
- [jsdelivr/globalping-mcp-server](https://github.com/jsdelivr/globalping-mcp-server) — Remote network commands for LLMs ☆`62`
- [Mtehabsim/ScreenPilot](https://github.com/Mtehabsim/ScreenPilot) — AI device control like a human ☆`54`
- [zazencodes/random-number-mcp](https://github.com/zazencodes/random-number-mcp) — MCP server for random number generation ☆`50`
- [NON906/omniparser-autogui-mcp](https://github.com/NON906/omniparser-autogui-mcp) — Automatic operation of on-screen GUI. ☆`70`
- [bharathvaj-ganesan/whois-mcp](https://github.com/bharathvaj-ganesan/whois-mcp) — MCP Server for whois lookups. ☆`58`
- [newtype-01/prompthouse-mcp](https://github.com/newtype-01/prompthouse-mcp) — Personal prompt library manager ☆`52`
- [fastn-ai/fastn-mcp](https://github.com/fastn-ai/fastn-mcp) — Fastn MCP server — give AI agents governed, audited access to integrations and tools across your customers' systems of record. ☆`23`
- [ofek/pycli-mcp](https://github.com/ofek/pycli-mcp) — MCP server for any Python command line application ☆`23`
- [andybrandt/mcp-simple-timeserver](https://github.com/andybrandt/mcp-simple-timeserver) — Current time check for Claude via MCP ☆`33`
- [SecretiveShell/MCP-timeserver](https://github.com/SecretiveShell/MCP-timeserver) — Datetime info for agentic systems ☆`42`
- [abhiphile/fermat-mcp](https://github.com/abhiphile/fermat-mcp) — Fermat MCP: The Ultimate Math Engine - Unifying SymPy, NumPy & Matplotlib in one powerful server! Perfect for devs & researchers. ☆`18`
- [TheoBrigitte/mcp-time](https://github.com/TheoBrigitte/mcp-time) — MCP (Model Context Protocol) server which provides utilities to work with time and dates, with natural language, multiple formats and timezone convertion capabilities ☆`25`
- [ZeparHyfar/mcp-datetime](https://github.com/ZeparHyfar/mcp-datetime) — A MCP server for datetime formatting and file name generation. ☆`30`
- [FelixFoster/mcp-enhance-prompt](https://github.com/FelixFoster/mcp-enhance-prompt) — AI-powered prompt enhancement and generation ☆`24`
### Version Control

- [github/github-mcp-server](https://github.com/github/github-mcp-server) — GitHub's official MCP Server ☆`31,671`
- [idosal/git-mcp](https://github.com/idosal/git-mcp) — Free remote MCP for any GitHub project ☆`8,280`
- [gitkraken/gk-cli](https://github.com/gitkraken/gk-cli) — GitKraken CLI Releases and Documentation ☆`439`
- [Tiberriver256/mcp-server-azure-devops](https://github.com/Tiberriver256/mcp-server-azure-devops) — An MCP server for Azure DevOps ☆`380`
- [adhikasp/mcp-git-ingest](https://github.com/adhikasp/mcp-git-ingest) — GitHub repository content reading ☆`315`
- [puravparab/Gitingest-MCP](https://github.com/puravparab/Gitingest-MCP) — mcp server for gitingest ☆`138`
- [kopfrechner/gitlab-mr-mcp](https://github.com/kopfrechner/gitlab-mr-mcp) — MCP server for GitLab merge requests and issues ☆`93`
- [oschina/mcp-gitee](https://github.com/oschina/mcp-gitee) — MCP server for Gitee repositories ☆`62`
- [ddukbg/github-enterprise-mcp](https://github.com/ddukbg/github-enterprise-mcp) — github-enterprise-mcp ☆`29`
- [Ryan0204/github-repo-mcp](https://github.com/Ryan0204/github-repo-mcp) — GitHub repository reading ☆`29`
- [kurdin/github-repos-manager-mcp](https://github.com/kurdin/github-repos-manager-mcp) — GitHub Repos Manager MCP Server for MCP clients ☆`21`
## Embedded & IoT

- [stack-chan/stack-chan](https://github.com/stack-chan/stack-chan) — A JavaScript-driven M5Stack-embedded super-kawaii robot. ☆`1,606`
- [tevonsb/homeassistant-mcp](https://github.com/tevonsb/homeassistant-mcp) — A MCP server for Home Assistant ☆`573`
- [lamaalrajih/kicad-mcp](https://github.com/lamaalrajih/kicad-mcp) — KiCad integration for Mac, Windows, Linux ☆`490`
- [Extelligence-ai/bagel](https://github.com/Extelligence-ai/bagel) — Chat with robotics, drone, IoT data ☆`388`
- [recursechat/mcp-server-apple-shortcuts](https://github.com/recursechat/mcp-server-apple-shortcuts) — Apple Shortcuts automation on macOS ☆`338`
- [voska/hass-mcp](https://github.com/voska/hass-mcp) — Control and query Home Assistant from Claude and other LLMs — a Model Context Protocol (MCP) server. ☆`309`
- [jeff-nasseri/mikrotik-mcp](https://github.com/jeff-nasseri/mikrotik-mcp) — MCP server for Mikrotik ☆`236`
- [hao-cyber/phone-mcp](https://github.com/hao-cyber/phone-mcp) — Control Android phone via ADB ☆`240`
- [FradSer/mcp-server-apple-events](https://github.com/FradSer/mcp-server-apple-events) — Native integration with Apple Reminders and Calendar ☆`172`
- [horw/esp-mcp](https://github.com/horw/esp-mcp) — ESP32 commands and getting started ☆`156`
- [johannesPettersson80/codesys-mcp-toolkit](https://github.com/johannesPettersson80/codesys-mcp-toolkit) — CODESYS industrial automation platform ☆`107`
- [thingsboard/thingsboard-mcp](https://github.com/thingsboard/thingsboard-mcp) — MCP server for ThingsBoard IoT platform interaction ☆`98`
- [LGDiMaggio/predictive-maintenance-mcp](https://github.com/LGDiMaggio/predictive-maintenance-mcp) — AI predictive maintenance and fault diagnosis via MCP ☆`55`
- [vishalmysore/choturobo](https://github.com/vishalmysore/choturobo) — Arduino robotics with AI integration ☆`78`
- [yoelbassin/gr-mcp](https://github.com/yoelbassin/gr-mcp) — MCP server for GNU Radio ☆`46`
- [aqara/aqara-mcp-server](https://github.com/aqara/aqara-mcp-server) — Aqara's official MCP Server ☆`38`
- [chrisgleissner/c64bridge](https://github.com/chrisgleissner/c64bridge) — MCP server to control and program the Commodore 64 Ultimate, Ultimate 64, Ultimate II, or VICE. ☆`32`
- [yiwenlu66/PiloTY](https://github.com/yiwenlu66/PiloTY) — AI pilot for PTY operations - control terminals via MCP ☆`42`
- [OctoEverywhere/mcp](https://github.com/OctoEverywhere/mcp) — 3D printing live status and control ☆`35`
- [kukapay/opcua-mcp](https://github.com/kukapay/opcua-mcp) — An MCP server that connects to OPC UA-enabled industrial systems. ☆`29`
- [thinq-connect/thinqconnect-mcp](https://github.com/thinq-connect/thinqconnect-mcp) — ThinQ Connect MCP Server ☆`29`
- [kukapay/modbus-mcp](https://github.com/kukapay/modbus-mcp) — Industrial Modbus data for AI ☆`26`
- [MiddlePoint-Solutions/mcp-on-android-tv](https://github.com/MiddlePoint-Solutions/mcp-on-android-tv) — MCP server on Android TV with ADB ☆`22`
- [Hypijump31/bluetooth-mcp-server](https://github.com/Hypijump31/bluetooth-mcp-server) — bluetooth-mcp-server for Claude AI ☆`22`
- [gNucleus/text-to-cad-mcp](https://github.com/gNucleus/text-to-cad-mcp) — gNucleus Text To CAD MCP server ☆`18`
## File Systems & Storage

- [mark3labs/mcp-filesystem-server](https://github.com/mark3labs/mcp-filesystem-server) — Go filesystem operations via MCP ☆`669`
- [cyberchitta/llm-context.py](https://github.com/cyberchitta/llm-context.py) — Python library for LLM context management ☆`305`
- [isaacphi/mcp-gdrive](https://github.com/isaacphi/mcp-gdrive) — Google Drive file reading ☆`283`
- [8b-is/smart-tree](https://github.com/8b-is/smart-tree) — Context-aware AI-crafted replacement for tree command ☆`263`
- [rust-mcp-stack/rust-mcp-filesystem](https://github.com/rust-mcp-stack/rust-mcp-filesystem) — Fast async filesystem operations ☆`166`
- [efforthye/fast-filesystem-mcp](https://github.com/efforthye/fast-filesystem-mcp) — High-performance MCP server for file operations ☆`59`
- [Tencent/cos-mcp](https://github.com/Tencent/cos-mcp) — Tencent Cloud COS storage integration ☆`38`
- [willianpinho/large-file-mcp](https://github.com/willianpinho/large-file-mcp) — MCP server for intelligent handling of large files — smart chunking, search, navigation, and streaming. ☆`18`
- [vespo92/TrueNasCoreMCP](https://github.com/vespo92/TrueNasCoreMCP) — A working TrueNAS Core MCP Server ☆`28`
- [Xuanwo/mcp-server-opendal](https://github.com/Xuanwo/mcp-server-opendal) — Model Context Protocol Server for Apache OpenDAL ☆`35`
- [exoticknight/mcp-file-merger](https://github.com/exoticknight/mcp-file-merger) — MCP server for merging multiple files into one ☆`27`
## Finance

### Accounting & Budgeting

- [XeroAPI/xero-mcp-server](https://github.com/XeroAPI/xero-mcp-server) — Xero accounting API integration ☆`342`
- [akutishevsky/lunchmoney-mcp](https://github.com/akutishevsky/lunchmoney-mcp) — MCP server for Lunch Money budgeting app ☆`85`
- [iiAtlas/hledger-mcp](https://github.com/iiAtlas/hledger-mcp) — A local MCP server for interacting with the HLedger cli ☆`59`
- [minhyeoky/mcp-server-ledger](https://github.com/minhyeoky/mcp-server-ledger) — MCP server for Ledger CLI double-entry accounting ☆`51`
- [openMF/mcp-mifosx](https://github.com/openMF/mcp-mifosx) — Model Context Protocol - MCP for Mifos X ☆`25`
- [john-zhang-dev/xero-mcp](https://github.com/john-zhang-dev/xero-mcp) — Interact with Xero accounting ☆`21`
### Crypto & Blockchain

- [mcpdotdirect/evm-mcp-server](https://github.com/mcpdotdirect/evm-mcp-server) — EVM network interaction for LLMs ☆`380`
- [aaronjmars/web3-research-mcp](https://github.com/aaronjmars/web3-research-mcp) — Deep Research for crypto - free & fully local ☆`160`
- [armorwallet/armor-crypto-mcp](https://github.com/armorwallet/armor-crypto-mcp) — Blockchain swaps and strategic planning ☆`181`
- [kukapay/crypto-indicators-mcp](https://github.com/kukapay/crypto-indicators-mcp) — Cryptocurrency technical analysis indicators ☆`130`
- [alchemyplatform/alchemy-mcp-server](https://github.com/alchemyplatform/alchemy-mcp-server) — Alchemy blockchain API for AI agents ☆`88`
- [Bankless/onchain-mcp](https://github.com/Bankless/onchain-mcp) — Bringing the bankless onchain API to MCP ☆`80`
- [twelvedata/mcp](https://github.com/twelvedata/mcp) — MCP server for real-time financial market data access ☆`73`
- [QuantGeekDev/coincap-mcp](https://github.com/QuantGeekDev/coincap-mcp) — A coincap mcp server to access crypto data from coincap API ☆`93`
- [getAlby/mcp](https://github.com/getAlby/mcp) — Bitcoin Lightning wallet via Nostr ☆`67`
- [AbdelStark/bitcoin-mcp](https://github.com/AbdelStark/bitcoin-mcp) — Bitcoin & Lightning Network MCP Server. ☆`76`
- [kukapay/cryptopanic-mcp-server](https://github.com/kukapay/cryptopanic-mcp-server) — Provide latest cryptocurrency news to AI agents. ☆`72`
- [norman-finance/norman-mcp-server](https://github.com/norman-finance/norman-mcp-server) — AI-powered bookkeeping and tax automation via MCP ☆`53`
- [heurist-network/heurist-mesh-mcp-server](https://github.com/heurist-network/heurist-mesh-mcp-server) — Blockchain and web3 via Heurist Mesh ☆`66`
- [bnb-chain/bnbchain-mcp](https://github.com/bnb-chain/bnbchain-mcp) — BNB Chain, BSC, opBNB, Greenfield ☆`60`
- [GoPlausible/algorand-mcp](https://github.com/GoPlausible/algorand-mcp) — Algorand Local Model Context Protocol (Server & Client) ☆`44`
- [coinpaprika/dexpaprika-mcp](https://github.com/coinpaprika/dexpaprika-mcp) — MCP server for DEX trading data and crypto token analytics ☆`41`
- [kukapay/whale-tracker-mcp](https://github.com/kukapay/whale-tracker-mcp) — A mcp server for tracking cryptocurrency whale transactions. ☆`59`
- [shinzo-labs/coinmarketcap-mcp](https://github.com/shinzo-labs/coinmarketcap-mcp) — MCP Implementation for CoinMarketCap ☆`52`
- [kukapay/crypto-feargreed-mcp](https://github.com/kukapay/crypto-feargreed-mcp) — Crypto Fear & Greed Index data ☆`53`
- [kukapay/crypto-sentiment-mcp](https://github.com/kukapay/crypto-sentiment-mcp) — Cryptocurrency sentiment analysis ☆`49`
- [anjor/coinmarket-mcp-server](https://github.com/anjor/coinmarket-mcp-server) — MCP server for CoinMarketCap cryptocurrency data ☆`50`
- [wowinter13/solscan-mcp](https://github.com/wowinter13/solscan-mcp) — Solana transaction queries ☆`42`
- [noditlabs/nodit-mcp-server](https://github.com/noditlabs/nodit-mcp-server) — Blockchain data via Nodit Web3 API ☆`23`
- [maestro-org/maestro-mcp-server](https://github.com/maestro-org/maestro-mcp-server) — Maestro MCP Server for Bitcoin ☆`24`
- [thirdweb-dev/ai](https://github.com/thirdweb-dev/ai) — Blockchain data, wallet, and smart contracts ☆`19`
- [hive-intel/hive-sdk](https://github.com/hive-intel/hive-sdk) — Managed crypto intelligence MCP for AI agents across market data, DeFi, wallets, security, DEX flows, NFTs, Solana, infrastructure, and prediction markets. ☆`17`
- [kukapay/dune-analytics-mcp](https://github.com/kukapay/dune-analytics-mcp) — A mcp server that bridges Dune Analytics data to AI agents. ☆`41`
- [CoinStatsHQ/coinstats-mcp](https://github.com/CoinStatsHQ/coinstats-mcp) —  ☆`16`
- [kukapay/uniswap-trader-mcp](https://github.com/kukapay/uniswap-trader-mcp) — Uniswap token swaps for AI agents ☆`38`
- [longmans/coin_api_mcp](https://github.com/longmans/coin_api_mcp) — CoinMarketCap cryptocurrency data ☆`37`
- [kukapay/kukapay-mcp-servers](https://github.com/kukapay/kukapay-mcp-servers) — Suite of MCP servers from Kukapay ☆`30`
- [kukapay/jupiter-mcp](https://github.com/kukapay/jupiter-mcp) — Jupiter DEX token swaps on Solana ☆`29`
- [kukapay/hyperliquid-info-mcp](https://github.com/kukapay/hyperliquid-info-mcp) — MCP server for Hyperliquid DEX data ☆`29`
- [ahnlabio/bicscan-mcp](https://github.com/ahnlabio/bicscan-mcp) — BICScan MCP Server ☆`17`
- [pwh-pwh/coin-mcp-server](https://github.com/pwh-pwh/coin-mcp-server) — Cryptocurrency info via Bitget API ☆`27`
- [devonmojito/ton-blockchain-mcp](https://github.com/devonmojito/ton-blockchain-mcp) — TON blockchain interaction ☆`26`
- [Codex-Data/codex-mcp](https://github.com/Codex-Data/codex-mcp) — A Model Context Protocol server for the Codex API ☆`25`
- [kukapay/token-minter-mcp](https://github.com/kukapay/token-minter-mcp) — ERC-20 token minting for AI agents ☆`21`
- [kukapay/crypto-rss-mcp](https://github.com/kukapay/crypto-rss-mcp) — An MCP server that aggregates real-time cryptocurrency news from multiple RSS feeds. ☆`17`
- [kukapay/crypto-news-mcp](https://github.com/kukapay/crypto-news-mcp) — An MCP server that provides real-time cryptocurrency news sourced from NewsData for AI agents. ☆`16`
- [magnetai/mcp-free-usdc-transfer](https://github.com/magnetai/mcp-free-usdc-transfer) — Free USDC transfer via Coinbase CDP ☆`21`
- [kukapay/rug-check-mcp](https://github.com/kukapay/rug-check-mcp) — An MCP server that detects potential risks in Solana meme tokens. ☆`20`
- [janswist/mcp-dexscreener](https://github.com/janswist/mcp-dexscreener) — Dexscreener on-chain price checking ☆`18`
- [kukapay/crypto-orderbook-mcp](https://github.com/kukapay/crypto-orderbook-mcp) — An MCP server that analyzes order book depth and imbalance across major crypto exchanges. ☆`17`
- [syronlabs/stellar-mcp](https://github.com/syronlabs/stellar-mcp) — A Stellar MCP to interact with Horizon API and Soroban ☆`18`
### Payments & Banking

- [stripe/ai](https://github.com/stripe/ai) — One-stop shop for building AI-powered products and businesses with Stripe. ☆`1,706`
- [razorpay/razorpay-mcp-server](https://github.com/razorpay/razorpay-mcp-server) — Razorpay's Official MCP Server ☆`229`
- [paypal/agent-toolkit](https://github.com/paypal/agent-toolkit) — PayPal Agent ☆`188`
- [square/square-mcp-server](https://github.com/square/square-mcp-server) — A Model Context Protocol (MCP) server for square ☆`102`
- [PaddleHQ/paddle-mcp-server](https://github.com/PaddleHQ/paddle-mcp-server) — Interact with Paddle API ☆`50`
- [qonto/qonto-mcp-server](https://github.com/qonto/qonto-mcp-server) — Qonto MCP Server ☆`37`
- [atharvagupta2003/mcp-stripe](https://github.com/atharvagupta2003/mcp-stripe) — Stripe payments, customers, and refunds ☆`44`
- [Fewsats/fewsats-mcp](https://github.com/Fewsats/fewsats-mcp) — Fewsats MCP server ☆`21`
### Stock Data & Analytics

- [financial-datasets/mcp-server](https://github.com/financial-datasets/mcp-server) — Financial Datasets stock market API ☆`2,244`
- [massive-com/mcp_massive](https://github.com/massive-com/mcp_massive) — An MCP server for Massive.com Financial Market Data ☆`371`
- [stefanoamorelli/sec-edgar-mcp](https://github.com/stefanoamorelli/sec-edgar-mcp) — A SEC EDGAR MCP (Model Context Protocol) Server ☆`335`
- [narumiruna/yfinance-mcp](https://github.com/narumiruna/yfinance-mcp) — MCP server for Yahoo Finance stock data and news ☆`172`
- [jjlabsio/korea-stock-mcp](https://github.com/jjlabsio/korea-stock-mcp) — MCP Server for Korean stock analysis ☆`166`
- [OctagonAI/octagon-mcp-server](https://github.com/OctagonAI/octagon-mcp-server) — Public filings, earnings, financial analysis ☆`144`
- [HuggingAGI/mcp-baostock-server](https://github.com/HuggingAGI/mcp-baostock-server) — MCP server for BaoStock Chinese stock market data ☆`114`
- [berlinbra/alpha-vantage-mcp](https://github.com/berlinbra/alpha-vantage-mcp) — MCP Server for Alpha Advantage API ☆`103`
- [Adity-star/mcp-yfinance-server](https://github.com/Adity-star/mcp-yfinance-server) — Real-time stock data with yfinance ☆`55`
- [AgentX-ai/yahoo-finance-server](https://github.com/AgentX-ai/yahoo-finance-server) — Yahoo Finance stock data and news ☆`50`
- [zlinzzzz/finData-mcp-server](https://github.com/zlinzzzz/finData-mcp-server) — Financial data from Tushare, Wind, DataYes ☆`57`
- [Mrbaeksang/korea-stock-analyzer-mcp](https://github.com/Mrbaeksang/korea-stock-analyzer-mcp) — Remote MCP server for Korean stock analysis — real DART filings, KRX quotes, conservative valuation ranges for Claude, Cursor and any MCP client ☆`23`
- [JamesANZ/prediction-market-mcp](https://github.com/JamesANZ/prediction-market-mcp) — Polymarket, PredictIt, Kalshi data ☆`36`
- [OctagonAI/octagon-vc-agents](https://github.com/OctagonAI/octagon-vc-agents) — AI-driven venture capitalist agents ☆`30`
### Trading & Exchanges

- [alpacahq/alpaca-mcp-server](https://github.com/alpacahq/alpaca-mcp-server) — Trade stocks, ETFs, crypto, options ☆`886`
- [ariadng/metatrader-mcp-server](https://github.com/ariadng/metatrader-mcp-server) — MetaTrader trading platform for AI LLMs ☆`663`
- [ferdousbhai/investor-agent](https://github.com/ferdousbhai/investor-agent) — Investor agent building via MCP ☆`341`
- [doggybee/mcp-server-ccxt](https://github.com/doggybee/mcp-server-ccxt) — Cryptocurrency exchange integration via CCXT ☆`140`
- [kukapay/freqtrade-mcp](https://github.com/kukapay/freqtrade-mcp) — Freqtrade crypto trading bot ☆`124`
- [taylorwilsdon/quantconnect-mcp](https://github.com/taylorwilsdon/quantconnect-mcp) — QuantConnect trading orchestration ☆`116`
- [ferdousbhai/tasty-agent](https://github.com/ferdousbhai/tasty-agent) — Let Claude manage your tastytrade portfolio. ☆`80`
- [QuantConnect/mcp-server](https://github.com/QuantConnect/mcp-server) — QuantConnect algo trading interaction ☆`78`
- [trade-it-inc/trade-it-mcp](https://github.com/trade-it-inc/trade-it-mcp) — Trade It stocks and crypto trading ☆`55`
- [ozgureyilmaz/polymarket-mcp](https://github.com/ozgureyilmaz/polymarket-mcp) — Polymarket prediction markets data ☆`49`
- [mektigboy/server-hyperliquid](https://github.com/mektigboy/server-hyperliquid) — Hyperliquid DEX trading integration ☆`43`
- [ethancod1ng/binance-mcp-server](https://github.com/ethancod1ng/binance-mcp-server) — Binance exchange API integration ☆`33`
- [laukikk/alpaca-mcp](https://github.com/laukikk/alpaca-mcp) — Alpaca stock and crypto trading ☆`36`
- [ferdousbhai/wsb-analyst-mcp](https://github.com/ferdousbhai/wsb-analyst-mcp) — MCP server for analyzing WallStreetBets ☆`29`
- [paperinvest/mcp-server](https://github.com/paperinvest/mcp-server) — Paper trading platform integration ☆`23`
- [solangii/upbit-mcp-server](https://github.com/solangii/upbit-mcp-server) — MCP(Model Context Protocol) server for Upbit ☆`17`
## Frameworks & SDKs

- [mastra-ai/mastra](https://github.com/mastra-ai/mastra) — TypeScript AI agent framework with RAG ☆`26,513`
- [lastmile-ai/mcp-agent](https://github.com/lastmile-ai/mcp-agent) — Build agents with MCP and workflow patterns ☆`8,479`
- [quarkiverse/quarkus-mcp-servers](https://github.com/quarkiverse/quarkus-mcp-servers) — Model Context Protocol Servers in Quarkus ☆`195`
- [posit-dev/mcptools](https://github.com/posit-dev/mcptools) — Model Context Protocol For R ☆`185`
- [agentrpc/agentrpc](https://github.com/agentrpc/agentrpc) — Universal RPC layer for AI agents ☆`133`
- [vishalmysore/a2ajava](https://github.com/vishalmysore/a2ajava) — Google A2A protocol for Spring Boot ☆`107`
- [strowk/foxy-contexts](https://github.com/strowk/foxy-contexts) — Library for MCP context servers ☆`114`
- [abap-ai/mcp](https://github.com/abap-ai/mcp) — ABAP MCP - Model Context Protocol - Server SDK ☆`77`
- [tesla0225/mcp-create](https://github.com/tesla0225/mcp-create) — Dynamic MCP server creation and management ☆`97`
- [mcpdotdirect/template-mcp-server](https://github.com/mcpdotdirect/template-mcp-server) — Template to quickly set up your own MCP server ☆`75`
- [particlefuture/1mcpserver](https://github.com/particlefuture/1mcpserver) — Auto-discover and configure MCP servers ☆`53`
- [domdomegg/programmatic-mcp-prototype](https://github.com/domdomegg/programmatic-mcp-prototype) — Programmatic MCP tool composition ☆`42`
- [mojolicious/mojo-mcp](https://github.com/mojolicious/mojo-mcp) — Perl SDK for Model Context Protocol servers and clients ☆`21`
- [mcpx-dev/mcp-badges](https://github.com/mcpx-dev/mcp-badges) — Get your projects MCP (Model Context Protocol) badges ☆`30`
## Gaming

- [Coding-Solo/godot-mcp](https://github.com/Coding-Solo/godot-mcp) — MCP server for Godot game engine ☆`4,892`
- [IvanMurzak/Unity-MCP](https://github.com/IvanMurzak/Unity-MCP) — AI-powered bridge connecting LLMs to Unity Editor ☆`3,654`
- [CoderGamester/mcp-unity](https://github.com/CoderGamester/mcp-unity) — MCP server for Unity game engine integration ☆`1,843`
- [IvanMurzak/Godot-MCP](https://github.com/IvanMurzak/Godot-MCP) — Open-source MCP server connecting AI agents to the Godot Editor and runtime (Godot 4.x, C#) ☆`187`
- [quazaai/UnityMCPIntegration](https://github.com/quazaai/UnityMCPIntegration) — Enable AI Agents to Control Unity ☆`156`
- [playcanvas/editor-mcp-server](https://github.com/playcanvas/editor-mcp-server) — MCP Server for AI automation of the PlayCanvas Editor ☆`126`
- [pab1it0/chess-mcp](https://github.com/pab1it0/chess-mcp) — MCP server for Chess.com player data, games and statistics ☆`79`
- [codemaestroai/advanced-unity-mcp](https://github.com/codemaestroai/advanced-unity-mcp) — Advanced Unity game engine integration ☆`92`
- [sawa-zen/vrchat-mcp](https://github.com/sawa-zen/vrchat-mcp) — VRChat API interaction ☆`63`
- [kkjdaniel/bgg-mcp](https://github.com/kkjdaniel/bgg-mcp) — MCP server for BoardGameGeek data ☆`52`
- [jalpp/chessagine-mcp](https://github.com/jalpp/chessagine-mcp) — Advanced chess analysis capabilities ☆`25`
- [jifrozen0110/mcp-riot](https://github.com/jifrozen0110/mcp-riot) — League of Legends MCP Server ☆`27`
- [jiayao/mcp-chess](https://github.com/jiayao/mcp-chess) — MCP server for playing chess against AI ☆`23`
## Healthcare & Bioinformatics

- [genomoncology/biomcp](https://github.com/genomoncology/biomcp) — BioMCP: Biomedical Model Context Protocol ☆`556`
- [the-momentum/apple-health-mcp-server](https://github.com/the-momentum/apple-health-mcp-server) — Apple Health data queries with DuckDB ☆`234`
- [wso2/fhir-mcp-server](https://github.com/wso2/fhir-mcp-server) — FHIR healthcare API integration ☆`129`
- [JamesANZ/medical-mcp](https://github.com/JamesANZ/medical-mcp) — MCP server for medical data processing ☆`105`
- [ChristianHinge/dicom-mcp](https://github.com/ChristianHinge/dicom-mcp) — DICOM server (PACS) interaction ☆`99`
- [the-momentum/fhir-mcp-server](https://github.com/the-momentum/fhir-mcp-server) — FHIR MCP Server for handling medical data standard. ☆`97`
- [cafferychen777/ChatSpatial](https://github.com/cafferychen777/ChatSpatial) — Spatial transcriptomics via natural language (Python/R) ☆`41`
- [OHNLP/omop_mcp](https://github.com/OHNLP/omop_mcp) — MCP server for OMOP medical data standard ☆`39`
- [srijanshukla18/xray](https://github.com/srijanshukla18/xray) — MCP server for X-ray analysis ☆`51`
- [akutishevsky/withings-mcp](https://github.com/akutishevsky/withings-mcp) — MCP server for Withings health data integration ☆`29`
- [tomekkorbak/oura-mcp-server](https://github.com/tomekkorbak/oura-mcp-server) — MCP server for Oura API integration ☆`38`
- [longevity-genie/biothings-mcp](https://github.com/longevity-genie/biothings-mcp) — MCP (Model Context Protocol) server for biothings ☆`33`
- [longevity-genie/gget-mcp](https://github.com/longevity-genie/gget-mcp) — Bioinformatic gget functions ☆`30`
- [longevity-genie/opengenes-mcp](https://github.com/longevity-genie/opengenes-mcp) — MCP for the open-genes ☆`20`
## LLM Bridges

- [perplexityai/modelcontextprotocol](https://github.com/perplexityai/modelcontextprotocol) — Official Perplexity API MCP server ☆`2,406`
- [jamubc/gemini-mcp-tool](https://github.com/jamubc/gemini-mcp-tool) — MCP server for Gemini CLI with large file analysis ☆`2,263`
- [DMontgomery40/deepseek-mcp-server](https://github.com/DMontgomery40/deepseek-mcp-server) — MCP server for DeepSeek language models ☆`349`
- [nesquikm/mcp-rubber-duck](https://github.com/nesquikm/mcp-rubber-duck) — MCP bridge to query multiple OpenAI-compatible LLMs ☆`171`
- [pyroprompts/any-chat-completions-mcp](https://github.com/pyroprompts/any-chat-completions-mcp) — MCP Server for using any LLM as a Tool ☆`155`
- [eLyiN/gemini-bridge](https://github.com/eLyiN/gemini-bridge) — Bridge AI agents to Google Gemini via CLI ☆`93`
- [choplin/mcp-gemini-cli](https://github.com/choplin/mcp-gemini-cli) — MCP server for Gemini CLI integration ☆`102`
- [pierrebrunelle/mcp-server-openai](https://github.com/pierrebrunelle/mcp-server-openai) — Query OpenAI models from Claude via MCP ☆`84`
- [mzxrai/mcp-openai](https://github.com/mzxrai/mcp-openai) — Chat with OpenAI models from Claude Desktop ☆`75`
- [merterbak/Grok-MCP](https://github.com/merterbak/Grok-MCP) — MCP server for xAI Grok API with tool calling and vision ☆`47`
- [ruixingshi/deepseek-thinker-mcp](https://github.com/ruixingshi/deepseek-thinker-mcp) — DeepSeek reasoning for MCP-enabled clients ☆`69`
- [kamelirzouni/MCP-server-Deepseek_R1](https://github.com/kamelirzouni/MCP-server-Deepseek_R1) — Connect Claude Desktop with DeepSeek ☆`69`
- [amidabuddha/unichat-mcp-server](https://github.com/amidabuddha/unichat-mcp-server) — Unified chat across multiple LLM providers ☆`40`
- [andybrandt/mcp-simple-openai-assistant](https://github.com/andybrandt/mcp-simple-openai-assistant) — Use OpenAI GPTs assistants from Claude ☆`39`
- [JamesANZ/cross-llm-mcp](https://github.com/JamesANZ/cross-llm-mcp) — A Model Context Protocol (MCP) server that provides access to multiple Large Language Model (LLM) APIs including ChatGPT, Claude, Gemini, Mistral, Kimi K2, and DeepSeek. ☆`16`
- [kamelirzouni/MCP-server-Qwen_Max](https://github.com/kamelirzouni/MCP-server-Qwen_Max) — MCP server for Qwen Max model ☆`24`
- [billster45/mcp-chatgpt-responses](https://github.com/billster45/mcp-chatgpt-responses) — MCP server for OpenAI ChatGPT API with Responses API ☆`18`
- [HyperbolicLabs/hyperbolic-mcp](https://github.com/HyperbolicLabs/hyperbolic-mcp) — MCP Server for Claude ☆`18`
## Location & Maps

### GIS

- [jjsantos01/qgis_mcp](https://github.com/jjsantos01/qgis_mcp) — Model Context Protocol (MCP) that allows LLMs to use QGIS Desktop ☆`1,033`
- [mahdin75/gis-mcp](https://github.com/mahdin75/gis-mcp) — MCP server connecting LLMs to GIS capabilities ☆`171`
- [JordanGunn/gdal-mcp](https://github.com/JordanGunn/gdal-mcp) — Geospatial analysis with epistemic reasoning ☆`72`
- [mahdin75/geoserver-mcp](https://github.com/mahdin75/geoserver-mcp) — GeoServer geospatial integration ☆`85`
- [webcoderz/MCP-Geo](https://github.com/webcoderz/MCP-Geo) — Geocoding MCP server with GeoPY! ☆`33`
### IP Geolocation

- [briandconnelly/mcp-server-ipinfo](https://github.com/briandconnelly/mcp-server-ipinfo) — IP Geolocation Server for MCP using ipinfo.io ☆`44`
- [iplocate/mcp-server-iplocate](https://github.com/iplocate/mcp-server-iplocate) — IP geolocation, proxy detection via IPLocate.io API ☆`19`
### Maps & Navigation

- [baidu-maps/mcp](https://github.com/baidu-maps/mcp) — Baidu Map MCP Server ☆`435`
- [mapbox/mcp-server](https://github.com/mapbox/mcp-server) — Mapbox Model Context Protocol (MCP) server ☆`351`
- [jagan-shanmugam/open-streetmap-mcp](https://github.com/jagan-shanmugam/open-streetmap-mcp) — MCP server for OpenStreetMap data ☆`210`
- [tomtom-international/tomtom-maps-mcp](https://github.com/tomtom-international/tomtom-maps-mcp) — TomTom location, search, routing ☆`51`
- [PinMeTo/pinmeto-location-mcp](https://github.com/PinMeTo/pinmeto-location-mcp) — PinMeTo MCP server that enables users with authorized credentials to unlock their data ☆`16`
- [stadiamaps/stadiamaps-mcp-server-ts](https://github.com/stadiamaps/stadiamaps-mcp-server-ts) — Stadia Maps API integration in TypeScript ☆`23`
- [kukapay/nearby-search-mcp](https://github.com/kukapay/nearby-search-mcp) — Nearby place search with IP-based location ☆`23`
### Weather

- [isdaniel/mcp_weather_server](https://github.com/isdaniel/mcp_weather_server) — Weather info via Open-Meteo API ☆`54`
- [TimLukaHorstmann/mcp-weather](https://github.com/TimLukaHorstmann/mcp-weather) — AccuWeather hourly and daily forecasts ☆`34`
- [sjanaX01/weather-mcp-server](https://github.com/sjanaX01/weather-mcp-server) — A simple minimal weather mcp server :) ☆`24`
- [mschneider82/mcp-openweather](https://github.com/mschneider82/mcp-openweather) — mcp server for openweather free api ☆`18`
## MCP Clients

- [Upsonic/Upsonic](https://github.com/Upsonic/Upsonic) — Build autonomous AI agents in Python. ☆`7,923`
- [genkit-ai/genkit](https://github.com/genkit-ai/genkit) — AI app framework for JavaScript and Go ☆`6,281`
- [ravitemer/mcphub.nvim](https://github.com/ravitemer/mcphub.nvim) — MCP client for Neovim with intuitive server management ☆`1,785`
- [SecretiveShell/MCP-Bridge](https://github.com/SecretiveShell/MCP-Bridge) — OpenAI-compatible endpoint calling MCP tools ☆`928`
- [ASCIT31/Dark-Moon](https://github.com/ASCIT31/Dark-Moon) — Autonomous AI pentest MCP host that drives Claude or a local model to orchestrate 80+ offensive-security tools, with a local Privacy Gateway ☆`775`
- [Lucassssss/eechat](https://github.com/Lucassssss/eechat) — Local AI chat application ☆`344`
- [3choff/mcp-chatbot](https://github.com/3choff/mcp-chatbot) — CLI chatbot with MCP integration demo ☆`250`
- [EvalsOne/MCP-connect](https://github.com/EvalsOne/MCP-connect) — Cloud AI access to local Stdio MCP servers ☆`238`
- [AI-QL/chat-mcp](https://github.com/AI-QL/chat-mcp) — Desktop chat app with MCP support ☆`242`
- [johannesbrandenburger/typst-mcp](https://github.com/johannesbrandenburger/typst-mcp) — MCP server for Typst markup-based typesetting system ☆`171`
- [tanaikech/ToolsForMCPServer](https://github.com/tanaikech/ToolsForMCPServer) — MCP server built with Google Apps Script for Gemini CLI ☆`106`
- [ckanthony/gin-mcp](https://github.com/ckanthony/gin-mcp) — Enable MCP features for any Gin API with a line of code ☆`82`
- [xzq-xu/jvm-mcp-server](https://github.com/xzq-xu/jvm-mcp-server) — JVM-based MCP server implementation ☆`87`
- [off-grid-ai/OGAD](https://github.com/off-grid-ai/OGAD) — On-device MCP client for Mac with a local LLM ☆`45`
- [php-mcp/client](https://github.com/php-mcp/client) — Core PHP implementation for the Model Context Protocol (MCP) Client ☆`57`
- [zacharypodbela/django-rest-framework-mcp](https://github.com/zacharypodbela/django-rest-framework-mcp) — MCP server for Django REST Framework ☆`52`
- [rakesh-eltropy/mcp-client](https://github.com/rakesh-eltropy/mcp-client) — REST API and CLI client for MCP with LangChain ☆`49`
## Marketing & Analytics

- [nowork-studio/NotFair](https://github.com/nowork-studio/NotFair) — Claude Code skills for SEO, GEO, Google Ads MCP, Meta Ads MCP, Google Search Console MCP, and Google Analytics (GA4) MCP ☆`3,260`
- [nowork-studio/NotFair](https://github.com/nowork-studio/NotFair) — NotFair Google Ads MCP — diagnose, recommend, and execute campaign changes ☆`3,260`
- [pipeboard-co/meta-ads-mcp](https://github.com/pipeboard-co/meta-ads-mcp) — Meta Ads (Facebook/Instagram) MCP server for Claude, ChatGPT, Perplexity & Cursor — the Meta node of Pipeboard’s 5-platform family (+ Google, TikTok, Snap, Reddit). Hosted remote MCP, badged Meta Business Partner, free plan — no self-hosting required. ☆`1,107`
- [gomarble-ai/facebook-ads-mcp-server](https://github.com/gomarble-ai/facebook-ads-mcp-server) — Facebook and Instagram Ads management ☆`343`
- [proxy-intell/facebook-ads-library-mcp](https://github.com/proxy-intell/facebook-ads-library-mcp) — Facebook Ads Library search and access ☆`274`
- [open-strategy-partners/osp_marketing_tools](https://github.com/open-strategy-partners/osp_marketing_tools) — MCP server for marketing automation tools ☆`270`
- [surendranb/google-analytics-mcp](https://github.com/surendranb/google-analytics-mcp) — Google Analytics 4 data access ☆`229`
- [cnych/seo-mcp](https://github.com/cnych/seo-mcp) — SEO tool based on Ahrefs data ☆`252`
- [stape-io/google-tag-manager-mcp-server](https://github.com/stape-io/google-tag-manager-mcp-server) — MCP server for Google Tag Manager ☆`187`
- [gomarble-ai/google-ads-mcp-server](https://github.com/gomarble-ai/google-ads-mcp-server) — Google Ads performance data analysis ☆`138`
- [microsoft/clarity-mcp-server](https://github.com/microsoft/clarity-mcp-server) — Microsoft Clarity integration ☆`101`
- [amekala/ads-mcp](https://github.com/amekala/ads-mcp) — MCP server for managing ad campaigns across Google Ads, Meta Ads, LinkedIn Ads, and TikTok Ads. 100+ tools for campaign creation, performance analysis, keyword research, and budget optimization. Works with ChatGPT, Claude, Gemini CLI, Cursor, Codex, and Windsurf. ☆`74`
- [AdsMCP/tiktok-ads-mcp-server](https://github.com/AdsMCP/tiktok-ads-mcp-server) — TikTok Ads Marketing API integration via MCP ☆`45`
- [builtwith/builtwith-mcp](https://github.com/builtwith/builtwith-mcp) — BuiltWith MCP Server ☆`41`
- [rafaelstz/adobe-commerce-dev-mcp](https://github.com/rafaelstz/adobe-commerce-dev-mcp) — Adobe Commerce Dev MCP Server ☆`27`
- [Kiran1689/storyblok-mcp-server](https://github.com/Kiran1689/storyblok-mcp-server) — MCP server for Storyblok CMS management ☆`40`
- [gvaibhav/TAM-MCP-Server](https://github.com/gvaibhav/TAM-MCP-Server) — Market sizing and TAM/SAM analysis ☆`33`
- [MarketplaceAdPros/amazon-ads-mcp-server](https://github.com/MarketplaceAdPros/amazon-ads-mcp-server) — MCP Server to interact with Amazon Ads ☆`28`
- [jonathan-politzki/smartlead-mcp-server](https://github.com/jonathan-politzki/smartlead-mcp-server) — Smartlead MCP deployment ☆`17`
## Media Processing

### 3D & Animation

- [ahujasid/blender-mcp](https://github.com/ahujasid/blender-mcp) — Blender 3D modeling with Claude AI ☆`24,778`
- [samuelgursky/davinci-resolve-mcp](https://github.com/samuelgursky/davinci-resolve-mcp) — MCP server integration for DaVinci Resolve Studio ☆`1,833`
- [ATH-MaaS/Pixelle-MCP](https://github.com/ATH-MaaS/Pixelle-MCP) — Multimodal AIGC with ComfyUI + MCP ☆`1,091`
- [abhiemj/manim-mcp-server](https://github.com/abhiemj/manim-mcp-server) — Manim animation code execution ☆`621`
- [8beeeaaat/touchdesigner-mcp](https://github.com/8beeeaaat/touchdesigner-mcp) — MCP server for TouchDesigner ☆`446`
- [diivi/aseprite-mcp](https://github.com/diivi/aseprite-mcp) — MCP server for interacting with the Aseprite API ☆`340`
- [pranav-deshmukh/blender-mcp](https://github.com/pranav-deshmukh/blender-mcp) — Blender 3D modeling integration ☆`96`
- [PatrickPalmer/MayaMCP](https://github.com/PatrickPalmer/MayaMCP) — Autodesk Maya 3D integration ☆`92`
- [wilsonchenghy/ShaderToy-MCP](https://github.com/wilsonchenghy/ShaderToy-MCP) — Create and explore GLSL shaders on ShaderToy ☆`48`
- [junmer/mcp-server-lottiefiles](https://github.com/junmer/mcp-server-lottiefiles) —  ☆`19`
### Audio & Music

- [elevenlabs/elevenlabs-mcp](https://github.com/elevenlabs/elevenlabs-mcp) — The official ElevenLabs MCP server ☆`1,485`
- [varunneal/spotify-mcp](https://github.com/varunneal/spotify-mcp) — MCP to connect your LLM with Spotify. ☆`608`
- [marcelmarais/spotify-mcp-server](https://github.com/marcelmarais/spotify-mcp-server) — Lightweight MCP server for Spotify ☆`399`
- [Simon-Kansara/ableton-live-mcp-server](https://github.com/Simon-Kansara/ableton-live-mcp-server) — Ableton Live OSC control ☆`390`
- [tiianhk/MaxMSP-MCP-Server](https://github.com/tiianhk/MaxMSP-MCP-Server) — MCP (Model Context Protocol) Server for Max (Max/MSP/Jitter) ☆`253`
- [adamjmurray/producer-pal](https://github.com/adamjmurray/producer-pal) — AI music production assistant for Ableton Live ☆`228`
- [dschuler36/reaper-mcp-server](https://github.com/dschuler36/reaper-mcp-server) — An MCP Server for interacting with Reaper projects. ☆`112`
- [SkyworkAI/Mureka-mcp](https://github.com/SkyworkAI/Mureka-mcp) — AI lyrics, song, and music generation ☆`107`
- [imprvhub/mcp-claude-spotify](https://github.com/imprvhub/mcp-claude-spotify) — Spotify interaction for Claude Desktop ☆`42`
- [TwelveTake-Studios/reaper-mcp](https://github.com/TwelveTake-Studios/reaper-mcp) — MCP server to control REAPER DAW with AI. 176 tools for mixing, mastering, MIDI composition, and full music production. ☆`31`
- [vsaez/mcp-spotify-player](https://github.com/vsaez/mcp-spotify-player) — MCP server to manage Spotify from MCP clients ☆`19`
### Image Generation

- [shinpr/mcp-image](https://github.com/shinpr/mcp-image) — AI image generation with Gemini 3 ☆`141`
- [awkoy/replicate-flux-mcp](https://github.com/awkoy/replicate-flux-mcp) — MCP server for Replicate Flux image and SVG generation ☆`105`
- [GenWaveLLC/svgmaker-mcp](https://github.com/GenWaveLLC/svgmaker-mcp) — MCP server for SVG generation ☆`84`
- [Flyworks-AI/flyworks-mcp](https://github.com/Flyworks-AI/flyworks-mcp) — Fast and free zeroshot lipsync MCP server ☆`94`
- [apinetwork/piapi-mcp-server](https://github.com/apinetwork/piapi-mcp-server) — PiAPI media: Midjourney, Flux, Kling ☆`72`
- [hamflx/imagen3-mcp](https://github.com/hamflx/imagen3-mcp) — MCP server for Google Imagen 3 image generation ☆`66`
- [WaveSpeedAI/mcp-server](https://github.com/WaveSpeedAI/mcp-server) — Image and video generation with WaveSpeed AI ☆`30`
- [InhiblabCore/mcp-image-compression](https://github.com/InhiblabCore/mcp-image-compression) — High-performance image compression service ☆`33`
- [zxkane/mcp-server-amazon-bedrock](https://github.com/zxkane/mcp-server-amazon-bedrock) — Amazon Bedrock Nova Canvas image generation ☆`24`
### Image Processing

- [openclaw/Peekaboo](https://github.com/openclaw/Peekaboo) — macOS screenshot and window capture MCP server ☆`4,909`
- [sunriseapps/imagesorcery-mcp](https://github.com/sunriseapps/imagesorcery-mcp) — Image processing operations ☆`328`
- [IDEA-Research/DINO-X-MCP](https://github.com/IDEA-Research/DINO-X-MCP) — MCP server for DINO-X vision model ☆`110`
- [groundlight/mcp-vision](https://github.com/groundlight/mcp-vision) — Computer vision models as MCP servers ☆`61`
- [screenshotone/mcp](https://github.com/screenshotone/mcp) — A simple implementation of an MCP server for the ScreenshotOne API ☆`35`
- [upnorthmedia/ScreenshotMCP](https://github.com/upnorthmedia/ScreenshotMCP) — Website screenshot capture and optimization ☆`55`
- [nota/gyazo-mcp-server](https://github.com/nota/gyazo-mcp-server) — Official Model Context Protocol server for Gyazo ☆`27`
- [MoussaabBadla/code-screenshot-mcp](https://github.com/MoussaabBadla/code-screenshot-mcp) — Generate code screenshots ☆`44`
- [stass/exif-mcp](https://github.com/stass/exif-mcp) — MCP server to extract image metadata (EXIF, XMP, etc) ☆`38`
- [magarcia/mcp-server-giphy](https://github.com/magarcia/mcp-server-giphy) — Giphy GIF integration ☆`33`
- [flowy11/imagician](https://github.com/flowy11/imagician) — A MCP server for image edition ☆`18`
### Media Services

- [garylab/pexels-mcp-server](https://github.com/garylab/pexels-mcp-server) — A Pexels MCP Server for Images and Videos searching ☆`19`
### Video

- [eat-pray-ai/yutu](https://github.com/eat-pray-ai/yutu) — The AI-powered toolkit that grows your YouTube channel on autopilot. ☆`593`
- [kimtaeyoon83/mcp-server-youtube-transcript](https://github.com/kimtaeyoon83/mcp-server-youtube-transcript) — YouTube video transcript downloader ☆`574`
- [ZubeidHendricks/youtube-mcp-server](https://github.com/ZubeidHendricks/youtube-mcp-server) — YouTube API and video management ☆`555`
- [anaisbetts/mcp-youtube](https://github.com/anaisbetts/mcp-youtube) — A Model-Context Protocol Server for YouTube ☆`536`
- [burningion/video-editing-mcp](https://github.com/burningion/video-editing-mcp) — MCP Interface for Video Jungle ☆`283`
- [muxinc/mux-node-sdk](https://github.com/muxinc/mux-node-sdk) — Mux Video and Data API wrapper ☆`180`
- [Laksh-star/mcp-server-tmdb](https://github.com/Laksh-star/mcp-server-tmdb) — MCP Server with TMDB ☆`75`
- [luminarylane/fal-mcp-server](https://github.com/luminarylane/fal-mcp-server) — Fal.ai image, video, music generation ☆`52`
- [tan-yong-sheng/ai-vision-mcp](https://github.com/tan-yong-sheng/ai-vision-mcp) — Image and video analysis capabilities ☆`67`
- [nabid-pf/youtube-video-summarizer-mcp](https://github.com/nabid-pf/youtube-video-summarizer-mcp) — YouTube video captions and summarization ☆`60`
- [video-db/agent-toolkit](https://github.com/video-db/agent-toolkit) — MCP toolkit for video database operations ☆`47`
- [marcindulak/stt-mcp-server-linux](https://github.com/marcindulak/stt-mcp-server-linux) — Local speech-to-text for Tmux on Linux ☆`22`
- [omergocmen/json2video-mcp-server](https://github.com/omergocmen/json2video-mcp-server) — json2video API integration ☆`26`
- [sinjab/mcp_youtube_extract](https://github.com/sinjab/mcp_youtube_extract) — YouTube clip information extraction ☆`19`
- [TSavo/creatify-mcp](https://github.com/TSavo/creatify-mcp) — MCP server for AI video generation ☆`22`
- [13rac1/videocapture-mcp](https://github.com/13rac1/videocapture-mcp) — MCP server to capture images from webcam or video source ☆`17`
## Monitoring & Observability

- [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana) — MCP server for Grafana ☆`3,277`
- [getsentry/sentry-mcp](https://github.com/getsentry/sentry-mcp) — An MCP server for interacting with Sentry via LLMs. ☆`790`
- [mpeirone/zabbix-mcp-server](https://github.com/mpeirone/zabbix-mcp-server) — MCP server for Zabbix monitoring with 40+ tools ☆`239`
- [comet-ml/opik-mcp](https://github.com/comet-ml/opik-mcp) — MCP server for Opik LLM evaluation platform ☆`215`
- [VictoriaMetrics/mcp-victoriametrics](https://github.com/VictoriaMetrics/mcp-victoriametrics) — VictoriaMetrics monitoring integration ☆`201`
- [pydantic/logfire-mcp](https://github.com/pydantic/logfire-mcp) — The Logfire MCP Server is here! ☆`162`
- [grafana/loki-mcp](https://github.com/grafana/loki-mcp) — An MCP ( Model Context Protocol ) Server for Grafana Loki ☆`156`
- [langfuse/mcp-server-langfuse](https://github.com/langfuse/mcp-server-langfuse) — MCP server for Langfuse LLM observability ☆`169`
- [dynatrace-oss/dynatrace-mcp](https://github.com/dynatrace-oss/dynatrace-mcp) — MCP server for Dynatrace Observability ☆`132`
- [Necmttn/ax](https://github.com/Necmttn/ax) — Local-first observability for AI coding agent sessions, tool use, skills, and costs ☆`87`
- [PagerDuty/pagerduty-mcp-server](https://github.com/PagerDuty/pagerduty-mcp-server) — PagerDuty official MCP server ☆`74`
- [seekrays/mcp-monitor](https://github.com/seekrays/mcp-monitor) — MCP server monitoring tool ☆`88`
- [prometheus/prometheus-mcp](https://github.com/prometheus/prometheus-mcp) — MCP server for LLMs to interact with Prometheus ☆`67`
- [last9/last9-mcp-server](https://github.com/last9/last9-mcp-server) — Last9 MCP Server ☆`59`
- [metoro-io/metoro-mcp-server](https://github.com/metoro-io/metoro-mcp-server) — Metoro MCP Server ☆`51`
- [GeLi2001/datadog-mcp-server](https://github.com/GeLi2001/datadog-mcp-server) — MCP server interacts with the official Datadog API ☆`69`
- [mcpcap/mcpcap](https://github.com/mcpcap/mcpcap) — Network analysis for the AI age ☆`50`
- [rootlyhq/rootly-mcp-server](https://github.com/rootlyhq/rootly-mcp-server) — Rootly MCP server ☆`44`
- [emicklei/mcp-log-proxy](https://github.com/emicklei/mcp-log-proxy) — a web logging proxy for MCP client-server communication ☆`31`
- [mhajder/librenms-mcp](https://github.com/mhajder/librenms-mcp) — MCP server for LibreNMS management ☆`31`
- [RedHatInsights/insights-mcp](https://github.com/RedHatInsights/insights-mcp) — Red Hat Insights AI connection ☆`22`
- [inspektor-gadget/ig-mcp-server](https://github.com/inspektor-gadget/ig-mcp-server) — Container and Kubernetes debugging with AI ☆`26`
- [ntk148v/alertmanager-mcp-server](https://github.com/ntk148v/alertmanager-mcp-server) — MCP server for Prometheus Alertmanager integration ☆`23`
- [gologinapp/gologin-mcp](https://github.com/gologinapp/gologin-mcp) —  ☆`17`
- [tumf/grafana-loki-mcp](https://github.com/tumf/grafana-loki-mcp) — Grafana Loki MCP Repository ☆`29`
- [tgeselle/bugsnag-mcp](https://github.com/tgeselle/bugsnag-mcp) — MCP server for Bugsnag error monitoring ☆`23`
- [MindscapeHQ/mcp-server-raygun](https://github.com/MindscapeHQ/mcp-server-raygun) — Raygun error investigation for AI ☆`21`
- [Pratyay/mac-monitor-mcp](https://github.com/Pratyay/mac-monitor-mcp) — MCP server for macOS system monitoring ☆`22`
## Productivity

### Atlassian

- [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) — MCP server for Atlassian tools (Confluence, Jira) ☆`5,613`
- [aashari/mcp-server-atlassian-bitbucket](https://github.com/aashari/mcp-server-atlassian-bitbucket) — Atlassian Bitbucket repositories and PRs ☆`159`
- [nguyenvanduocit/jira-mcp](https://github.com/nguyenvanduocit/jira-mcp) — Jira issues and sprints via Go MCP ☆`95`
- [aashari/mcp-server-atlassian-jira](https://github.com/aashari/mcp-server-atlassian-jira) — Atlassian Jira projects, issues and sprints ☆`72`
- [aashari/mcp-server-atlassian-confluence](https://github.com/aashari/mcp-server-atlassian-confluence) — Atlassian Confluence spaces and pages ☆`60`
- [phuc-nt/mcp-atlassian-server](https://github.com/phuc-nt/mcp-atlassian-server) — Jira and Confluence integration ☆`53`
- [KS-GEN-AI/jira-mcp-server](https://github.com/KS-GEN-AI/jira-mcp-server) — A test of jira mcp server ☆`26`
- [rahulthedevil/Jira-Context-MCP](https://github.com/rahulthedevil/Jira-Context-MCP) — Jira tickets info for AI coding agents ☆`26`
### Collaboration

- [evalstate/mcp-miro](https://github.com/evalstate/mcp-miro) — MCP server for Miro whiteboard manipulation and sticky creation ☆`111`
- [kintone/mcp-server](https://github.com/kintone/mcp-server) — kintone official MCP server ☆`52`
- [hiromitsusasaki/raindrop-io-mcp-server](https://github.com/hiromitsusasaki/raindrop-io-mcp-server) — Raindrop.io bookmark management ☆`75`
- [orellazri/coda-mcp](https://github.com/orellazri/coda-mcp) — MCP Server for Coda ☆`61`
- [k-jarzyna/mcp-miro](https://github.com/k-jarzyna/mcp-miro) — Miro integration for Model Context Protocol ☆`66`
- [Fibery-inc/fibery-mcp-server](https://github.com/Fibery-inc/fibery-mcp-server) — MCP server for Fibery workspace integration ☆`29`
### Documents

- [zcaceres/markdownify-mcp](https://github.com/zcaceres/markdownify-mcp) — Convert almost anything to Markdown ☆`2,886`
- [vivekVells/mcp-pandoc](https://github.com/vivekVells/mcp-pandoc) — MCP server for document format conversion using pandoc. ☆`571`
- [onebirdrocks/ebook-mcp](https://github.com/onebirdrocks/ebook-mcp) — MCP server for ebook processing ☆`379`
- [baruchiro/paperless-mcp](https://github.com/baruchiro/paperless-mcp) — MCP server for Paperless-NGX document management ☆`132`
- [PSPDFKit/nutrient-dws-mcp-server](https://github.com/PSPDFKit/nutrient-dws-mcp-server) — Nutrient Document Web Services ☆`68`
- [vgnshiyer/apple-books-mcp](https://github.com/vgnshiyer/apple-books-mcp) — Apple Books MCP Server ☆`52`
- [Unstructured-IO/UNS-MCP](https://github.com/Unstructured-IO/UNS-MCP) — MCP server for Unstructured document processing ☆`42`
- [esignaturescom/mcp-server-esignatures](https://github.com/esignaturescom/mcp-server-esignatures) — eSignatures.com document signing ☆`38`
- [thechandanbhagat/cv-forge](https://github.com/thechandanbhagat/cv-forge) — MCP server that generates ATS-friendly CVs, cover letters, and email templates tailored to any job description ☆`29`
- [gpetraroli/mcp_pdf_reader](https://github.com/gpetraroli/mcp_pdf_reader) — An MCP server to extraxt/search text from pdf ☆`32`
- [danielkennedy1/pdf-tools-mcp](https://github.com/danielkennedy1/pdf-tools-mcp) — MCP server for PDF manipulation (merge, extract, snippets) ☆`31`
- [intsig-textin/textin-mcp](https://github.com/intsig-textin/textin-mcp) — OCR and document-to-Markdown conversion ☆`28`
### Google Workspace

- [taylorwilsdon/google_workspace_mcp](https://github.com/taylorwilsdon/google_workspace_mcp) — MCP server for Google Workspace integration ☆`2,910`
- [MarkusPfundstein/mcp-gsuite](https://github.com/MarkusPfundstein/mcp-gsuite) — MCP Server to interact with Google Gsuite prodcuts ☆`491`
- [v-3/google-calendar](https://github.com/v-3/google-calendar) — Google Calendar events and scheduling ☆`72`
- [baryhuang/mcp-headless-gmail](https://github.com/baryhuang/mcp-headless-gmail) — Gmail without local credentials ☆`55`
- [vakharwalad23/google-mcp](https://github.com/vakharwalad23/google-mcp) — Collection of Google-native tools (e.g., Gmail, Calendar) for the MCP ☆`20`
- [giuseppe-coco/Google-Workspace-MCP-Server](https://github.com/giuseppe-coco/Google-Workspace-MCP-Server) — Gmail, Calendar, and Drive integration ☆`30`
### Helpdesk & Support

- [echelon-ai-labs/servicenow-mcp](https://github.com/echelon-ai-labs/servicenow-mcp) — MCP Server for ServiceNow ☆`281`
- [effytech/freshdesk_mcp](https://github.com/effytech/freshdesk_mcp) — Freshdesk support ticket integration ☆`65`
- [modesty/fluent-mcp](https://github.com/modesty/fluent-mcp) — MCP server for Fluent (ServiceNow SDK) ☆`30`
- [quickchatai/quickchat-ai-mcp](https://github.com/quickchatai/quickchat-ai-mcp) — The Quickchat AI MCP server ☆`24`
### Learning & Flashcards

- [ankimcp/anki-mcp-server](https://github.com/ankimcp/anki-mcp-server) — MCP server for Anki spaced repetition flashcards ☆`398`
- [scorzeth/anki-mcp-server](https://github.com/scorzeth/anki-mcp-server) — An MCP server for Anki ☆`184`
- [jinzcdev/leetcode-mcp-server](https://github.com/jinzcdev/leetcode-mcp-server) — MCP server for LeetCode problems and solutions ☆`133`
- [nietus/anki-mcp](https://github.com/nietus/anki-mcp) — MCP server for anki ☆`39`
- [rember/rember-mcp](https://github.com/rember/rember-mcp) — A Model Context Protocol (MCP) server for Rember. ☆`62`
- [doggybee/mcp-server-leetcode](https://github.com/doggybee/mcp-server-leetcode) — MCP server for LeetCode coding challenges ☆`44`
- [spacholski1225/anki-connect-mcp](https://github.com/spacholski1225/anki-connect-mcp) — MCP implementation for Anki Web ☆`23`
### Microsoft 365

- [haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server) — Excel file manipulation ☆`4,053`
- [Softeria/ms-365-mcp-server](https://github.com/Softeria/ms-365-mcp-server) — Microsoft 365 and Office via Graph API ☆`869`
- [sbroenne/mcp-server-excel](https://github.com/sbroenne/mcp-server-excel) — Excel MCP Server - 23 tools for AI-powered automation ☆`397`
- [InditexTech/mcp-teams-server](https://github.com/InditexTech/mcp-teams-server) — MCP server for Microsoft Teams integration ☆`385`
- [merill/lokka](https://github.com/merill/lokka) — MCP for Microsoft 365 and Graph ☆`279`
- [pnp/cli-microsoft365-mcp-server](https://github.com/pnp/cli-microsoft365-mcp-server) — Manage Microsoft 365 using MCP server ☆`119`
- [Norcim133/OutlookMCPServer](https://github.com/Norcim133/OutlookMCPServer) — MCP Server for msgraph - mail, calendar, files ☆`16`
### Note-taking & Docs

- [RafalWilinski/mcp-apple-notes](https://github.com/RafalWilinski/mcp-apple-notes) — RAG over Apple Notes for Claude ☆`407`
- [lostintangent/gistpad-mcp](https://github.com/lostintangent/gistpad-mcp) — Personal knowledge and daily notes management ☆`200`
- [Vortiago/mcp-outline](https://github.com/Vortiago/mcp-outline) — AI assistants with Outline docs ☆`154`
- [entanglr/zettelkasten-mcp](https://github.com/entanglr/zettelkasten-mcp) — MCP server implementing Zettelkasten knowledge management ☆`160`
- [gornskew/lisply-mcp](https://github.com/gornskew/lisply-mcp) — Manage Lisply lisp-speaking backends ☆`50`
- [ONLYOFFICE/docspace-mcp](https://github.com/ONLYOFFICE/docspace-mcp) — DocSpace MCP Server ☆`28`
- [akseyh/bear-mcp-server](https://github.com/akseyh/bear-mcp-server) — MCP Server integration for Bear note app ☆`45`
- [2slides/mcp-2slides](https://github.com/2slides/mcp-2slides) — MCP Server for 2slides - AI agent for PPT generation ☆`31`
- [joshylchen/zettelkasten](https://github.com/joshylchen/zettelkasten) — Comprehensive AI-powered knowledge management system implementing the Zettelkasten method. Features atomic note creation, full-text search, AI-powered CEQRC workflows (Capture→Explain→Question→Refine→Connect), intelligent link discovery, and multi-interface access (CLI, API, Web UI, MCP). Perfect for researchers, students, and knowledge workers. ☆`35`
- [danield137/mcp-workflowy](https://github.com/danield137/mcp-workflowy) — An MCP server for workflowy ☆`28`
- [Piotr1215/mcp-obsidian](https://github.com/Piotr1215/mcp-obsidian) — simple mcp server for interacting with local obsidian notes ☆`23`
- [Harry-027/JotDown](https://github.com/Harry-027/JotDown) — An MCP Server in Rust for creating Notion pages & mdBooks with LLMs ☆`22`
- [louis030195/easy-obsidian-mcp](https://github.com/louis030195/easy-obsidian-mcp) — wire your brain to AGI through the best obsidian MCP ☆`16`
### Notion

- [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server) — Official Notion MCP Server ☆`4,552`
- [suekou/mcp-notion-server](https://github.com/suekou/mcp-notion-server) — MCP server for Notion API with Markdown conversion ☆`916`
- [danhilse/notion_mcp](https://github.com/danhilse/notion_mcp) — Notion integration with advanced formatting ☆`208`
- [Badhansen/notion-mcp](https://github.com/Badhansen/notion-mcp) — Notion workspace management ☆`31`
### Obsidian

- [MarkusPfundstein/mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) — Obsidian integration via REST API plugin ☆`4,126`
- [bitbonsai/mcpvault](https://github.com/bitbonsai/mcpvault) — Lightweight Obsidian vault access ☆`1,560`
- [StevenStavrakis/obsidian-mcp](https://github.com/StevenStavrakis/obsidian-mcp) — A simple MCP server for Obsidian ☆`720`
### Project Management

- [mondaycom/mcp](https://github.com/mondaycom/mcp) — AI agents with secure data access ☆`417`
- [jerhadf/linear-mcp-server](https://github.com/jerhadf/linear-mcp-server) — MCP server for Linear issue tracking ☆`346`
- [makeplane/plane-mcp-server](https://github.com/makeplane/plane-mcp-server) — Plane's Official Model Context Protocol Server ☆`272`
- [taskade/mcp](https://github.com/taskade/mcp) — MCP server for Taskade project management ☆`153`
- [roychri/mcp-server-asana](https://github.com/roychri/mcp-server-asana) — MCP server for Asana task and project management ☆`145`
- [tacticlaunch/mcp-linear](https://github.com/tacticlaunch/mcp-linear) — MCP server for Linear project management ☆`143`
- [its-dart/dart-mcp-server](https://github.com/its-dart/dart-mcp-server) — Dart AI Model Context Protocol (MCP) server ☆`128`
- [georgeantonopoulos/Basecamp-MCP-Server](https://github.com/georgeantonopoulos/Basecamp-MCP-Server) — Basecamp 3+ project management ☆`94`
- [aikts/yandex-tracker-mcp](https://github.com/aikts/yandex-tracker-mcp) — Yandex Tracker MCP Server with OAuth2 support ☆`91`
- [tonyzorin/youtrack-mcp](https://github.com/tonyzorin/youtrack-mcp) — YouTrack server, ARM64 and AMD64 ☆`89`
- [feuerdev/keep-mcp](https://github.com/feuerdev/keep-mcp) — MCP server for Google Keep ☆`85`
- [m0xai/trello-mcp-server](https://github.com/m0xai/trello-mcp-server) — A simple yet powerful MCP server for Trello. ☆`55`
- [taazkareem/clickup-mcp-server](https://github.com/taazkareem/clickup-mcp-server) — ClickUp MCP Server - project management with AI ☆`49`
- [EduBase/MCP](https://github.com/EduBase/MCP) — MCP server for EduBase e-learning platform ☆`27`
- [Teamwork/mcp](https://github.com/Teamwork/mcp) — Teamwork.com MCP server ☆`23`
- [bivex/kanboard-mcp](https://github.com/bivex/kanboard-mcp) — MCP server for Kanboard project management integration ☆`23`
- [kocakli/Trello-Desktop-MCP](https://github.com/kocakli/Trello-Desktop-MCP) — Trello integration for Claude Desktop via MCP ☆`36`
- [kelvin6365/plane-mcp-server](https://github.com/kelvin6365/plane-mcp-server) — MCP server for Plane.so project management ☆`40`
- [Prat011/mcp-server-monday](https://github.com/Prat011/mcp-server-monday) — MCP Server to interact with Monday.com boards and items ☆`34`
- [khaoss85/mcp-orchestro](https://github.com/khaoss85/mcp-orchestro) — Transform product ideas into reality with an intelligent orchestration system that bridges Product Managers, Developers, and AI. Orchestro conducts the entire development symphony: task decomposition, dependency tracking, pattern learning, and real-time progress visualization. ☆`16`
### Tasks & Calendar

- [screenpipe/screenpipe](https://github.com/screenpipe/screenpipe) — AI app store with 24/7 desktop history ☆`20,467`
- [nspady/google-calendar-mcp](https://github.com/nspady/google-calendar-mcp) — MCP integration for Google Calendar to manage events. ☆`1,159`
- [Doist/todoist-mcp](https://github.com/Doist/todoist-mcp) — Todoist tools for AI agents ☆`528`
- [abhiz123/todoist-mcp-server](https://github.com/abhiz123/todoist-mcp-server) — Todoist natural language task management ☆`391`
- [Omar-V2/mcp-ical](https://github.com/Omar-V2/mcp-ical) — Interact with MacOS Calendar ☆`322`
- [zcaceres/gtasks-mcp](https://github.com/zcaceres/gtasks-mcp) — A Google Tasks Model Context Protocol Server for Claude ☆`153`
- [dominik1001/caldav-mcp](https://github.com/dominik1001/caldav-mcp) — CalDAV calendar sync ☆`93`
- [stanislavlysenko0912/todoist-mcp-server](https://github.com/stanislavlysenko0912/todoist-mcp-server) — Todoist Rest API and Sync API ☆`64`
- [alexarevalo9/ticktick-mcp-server](https://github.com/alexarevalo9/ticktick-mcp-server) — TickTick task management ☆`71`
- [flesler/mcp-tasks](https://github.com/flesler/mcp-tasks) — Efficient task management with views ☆`46`
- [jen6/ticktick-mcp](https://github.com/jen6/ticktick-mcp) — TickTick task management with filtering ☆`67`
- [takumi0706/google-calendar-mcp](https://github.com/takumi0706/google-calendar-mcp) — Google Calendar for Claude Desktop ☆`59`
- [awwaiid/mcp-server-taskwarrior](https://github.com/awwaiid/mcp-server-taskwarrior) — MCP Server for TaskWarrior! ☆`49`
- [arpitbatra123/mcp-googletasks](https://github.com/arpitbatra123/mcp-googletasks) — MCP server for Google Tasks management ☆`47`
- [urbanogardun/things3-mcp](https://github.com/urbanogardun/things3-mcp) — MCP server for Things3 integration on macOS ☆`23`
- [jbrinkman/valkey-ai-tasks](https://github.com/jbrinkman/valkey-ai-tasks) — MCP server for task management with Valkey persistence ☆`25`
- [hichana/goalstory-mcp](https://github.com/hichana/goalstory-mcp) — Goal tracking with AI-powered storytelling ☆`18`
- [Danielpeter-99/calcom-mcp](https://github.com/Danielpeter-99/calcom-mcp) — A FastMCP server for interacting with the Cal.com API. This enables LLMs to manage event types, create bookings, and access Cal.com scheduling data programmatically. ☆`18`
### Wiki & Collaboration

- [anyproto/anytype-mcp](https://github.com/anyproto/anytype-mcp) — AI with Anytype encrypted local data ☆`486`
- [ProfessionalWiki/MediaWiki-MCP-Server](https://github.com/ProfessionalWiki/MediaWiki-MCP-Server) — Connect AI with any MediaWiki ☆`113`
- [yuna0x0/hackmd-mcp](https://github.com/yuna0x0/hackmd-mcp) — HackMD note-taking integration ☆`64`
- [HenryHaoson/Yuque-MCP-Server](https://github.com/HenryHaoson/Yuque-MCP-Server) — Yuque mcp server ☆`67`
- [growilabs/growi-mcp-server](https://github.com/growilabs/growi-mcp-server) — A Model Context Protocol (MCP) server that connects AI models to GROWI wiki content. Enables LLMs to search and retrieve information from your organization's knowledge base for accurate, context-aware responses. ☆`17`
## Research & Science

- [oOo0oOo/lean-lsp-mcp](https://github.com/oOo0oOo/lean-lsp-mcp) — Lean Theorem Prover MCP ☆`458`
- [szeider/mcp-solver](https://github.com/szeider/mcp-solver) — Constraint optimization and solving ☆`176`
- [Pantheon-Security/notebooklm-mcp-secure](https://github.com/Pantheon-Security/notebooklm-mcp-secure) — Secure NotebookLM MCP with 14 security layers ☆`75`
- [NellyW8/MCP4EDA](https://github.com/NellyW8/MCP4EDA) — RTL-to-GDSII automation with LLM ☆`96`
- [SecretiveShell/MCP-wolfram-alpha](https://github.com/SecretiveShell/MCP-wolfram-alpha) — Wolfram Alpha computational intelligence ☆`75`
- [neuromechanist/matlab-mcp-tools](https://github.com/neuromechanist/matlab-mcp-tools) — An MCP to develop MATLAB pipelines section by section and read figures one dimension at a time ☆`18`
## Sandboxing & Execution

- [superradcompany/microsandbox](https://github.com/superradcompany/microsandbox) — easy fast local-first microVM library and toolkit ☆`7,015`
- [dagger/container-use](https://github.com/dagger/container-use) — MCP server for container orchestration ☆`3,922`
- [Automata-Labs-team/code-sandbox-mcp](https://github.com/Automata-Labs-team/code-sandbox-mcp) — Secure code sandbox in Docker ☆`325`
- [bazinga012/mcp_code_executor](https://github.com/bazinga012/mcp_code_executor) — Execute Python in Conda environment ☆`212`
- [alfonsograziano/node-code-sandbox-mcp](https://github.com/alfonsograziano/node-code-sandbox-mcp) — MCP server for Node.js code sandbox execution ☆`155`
- [hopx-ai/mcp](https://github.com/hopx-ai/mcp) — Execute code in isolated cloud containers ☆`155`
- [gradion-ai/ipybox](https://github.com/gradion-ai/ipybox) — Python code execution sandbox with MCP tool calling ☆`73`
- [r33drichards/mcp-js](https://github.com/r33drichards/mcp-js) — MCP server exposing V8 JavaScript runtime for AI agents ☆`49`
- [yepcode/mcp-server-js](https://github.com/yepcode/mcp-server-js) — JavaScript MCP server framework by YepCode ☆`46`
- [hileamlakB/Python-Runtime-Interpreter-MCP-Server](https://github.com/hileamlakB/Python-Runtime-Interpreter-MCP-Server) — Safe Python runtime interpreter ☆`29`
- [gwbischof/outsource-mcp](https://github.com/gwbischof/outsource-mcp) — Give your AI assistant its own AI assistants. ☆`30`
## Search & Extraction

### Academic Research

- [blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server) — arXiv paper search and analysis ☆`2,983`
- [JackKuo666/Google-Scholar-MCP-Server](https://github.com/JackKuo666/Google-Scholar-MCP-Server) — Search Google Scholar papers ☆`380`
- [reading-plus-ai/mcp-server-deep-research](https://github.com/reading-plus-ai/mcp-server-deep-research) — Comprehensive research with reports ☆`213`
- [andybrandt/mcp-simple-arxiv](https://github.com/andybrandt/mcp-simple-arxiv) — arXiv paper search and reading ☆`200`
- [adityak74/mcp-scholarly](https://github.com/adityak74/mcp-scholarly) — A MCP server to search for accurate academic articles. ☆`184`
- [andybrandt/mcp-simple-pubmed](https://github.com/andybrandt/mcp-simple-pubmed) — PubMed medical research search ☆`170`
- [takashiishida/arxiv-latex-mcp](https://github.com/takashiishida/arxiv-latex-mcp) — MCP server for arXiv LaTeX paper retrieval ☆`141`
- [kaliaboi/mcp-zotero](https://github.com/kaliaboi/mcp-zotero) — Zotero collections for Claude Desktop ☆`164`
- [JackKuo666/PubMed-MCP-Server](https://github.com/JackKuo666/PubMed-MCP-Server) — Search and analyze PubMed articles ☆`122`
- [OctagonAI/octagon-deep-research-mcp](https://github.com/OctagonAI/octagon-deep-research-mcp) — AI-powered comprehensive research and analysis ☆`93`
- [akalaric/mcp-wolframalpha](https://github.com/akalaric/mcp-wolframalpha) — Wolfram Alpha integration for Python ☆`84`
- [HzaCode/OneCite](https://github.com/HzaCode/OneCite) — Parse and format academic references ☆`64`
- [connerlambden/bgpt-mcp](https://github.com/connerlambden/bgpt-mcp) — Search scientific papers with structured experimental data from full-text studies ☆`42`
- [drAbreu/alex-mcp](https://github.com/drAbreu/alex-mcp) — MCP server for OpenAlex ☆`50`
- [szeider/mcp-dblp](https://github.com/szeider/mcp-dblp) — Access DBLP computer science bibliography ☆`42`
- [prashalruchiranga/arxiv-mcp-server](https://github.com/prashalruchiranga/arxiv-mcp-server) — arXiv API via natural language ☆`40`
- [mochow13/google-scholar-mcp](https://github.com/mochow13/google-scholar-mcp) — MCP server for Google Scholar written in TypeScript ☆`22`
- [hbg/mcp-paperswithcode](https://github.com/hbg/mcp-paperswithcode) — MCP interface for PapersWithCode API ☆`26`
- [gemy411/multi-agents-research](https://github.com/gemy411/multi-agents-research) — a KTOR server/ MCP server written in Kotlin applying multi-agents schools in a flexible research system to be used with coding or for research any general ☆`17`
- [JackKuo666/bioRxiv-MCP-Server](https://github.com/JackKuo666/bioRxiv-MCP-Server) — Access bioRxiv papers ☆`24`
### Data APIs

- [cantian-ai/bazi-mcp](https://github.com/cantian-ai/bazi-mcp) — Bazi Chinese astrology information ☆`411`
- [Rudra-ravi/wikipedia-mcp](https://github.com/Rudra-ravi/wikipedia-mcp) — Retrieve Wikipedia information ☆`275`
- [ahonn/mcp-server-gsc](https://github.com/ahonn/mcp-server-gsc) — Google Search Console data access ☆`251`
- [hellokaton/unsplash-mcp-server](https://github.com/hellokaton/unsplash-mcp-server) — A MCP server for Unsplash image search. ☆`230`
- [deadletterq/mcp-opennutrition](https://github.com/deadletterq/mcp-opennutrition) — MCP server for nutrition data and analysis ☆`197`
- [OpenDataMCP/OpenDataMCP](https://github.com/OpenDataMCP/OpenDataMCP) — Connect any Open Data to any LLM with Model Context Protocol. ☆`155`
- [cswkim/discogs-mcp-server](https://github.com/cswkim/discogs-mcp-server) — MCP Server for Discogs ☆`116`
- [damionrashford/RivalSearchMCP](https://github.com/damionrashford/RivalSearchMCP) — MCP server for competitive search analysis ☆`115`
- [cameronrye/openzim-mcp](https://github.com/cameronrye/openzim-mcp) — MCP server for OpenZIM archive access ☆`95`
- [8enSmith/mcp-open-library](https://github.com/8enSmith/mcp-open-library) — MCP server for Open Library book and author search ☆`85`
- [yuna0x0/anilist-mcp](https://github.com/yuna0x0/anilist-mcp) — AniList MCP server for accessing anime and manga data ☆`82`
- [riemannzeta/patent_mcp_server](https://github.com/riemannzeta/patent_mcp_server) — FastMCP Server for USPTO data ☆`69`
- [anysiteio/anysite-mcp-server](https://github.com/anysiteio/anysite-mcp-server) — LinkedIn data access ☆`62`
- [zoomeye-ai/mcp_zoomeye](https://github.com/zoomeye-ai/mcp_zoomeye) — MCP server for ZoomEye network asset information ☆`79`
- [Linked-API/linkedapi-mcp](https://github.com/Linked-API/linkedapi-mcp) — LinkedIn account control and data retrieval ☆`61`
- [djalal/quran-mcp-server](https://github.com/djalal/quran-mcp-server) — Quran.com verses, translations, tafsir ☆`71`
- [r-huijts/rijksmuseum-mcp](https://github.com/r-huijts/rijksmuseum-mcp) — Rijksmuseum artwork exploration ☆`70`
- [0xDAEF0F/job-searchoor](https://github.com/0xDAEF0F/job-searchoor) — A simple MCP server that delivers you jobs based on your needs ☆`65`
- [yamanoku/baseline-mcp-server](https://github.com/yamanoku/baseline-mcp-server) — Web API Baseline status information ☆`37`
- [imprvhub/mcp-domain-availability](https://github.com/imprvhub/mcp-domain-availability) — MCP server to check domain availability ☆`55`
- [zzaebok/mcp-wikidata](https://github.com/zzaebok/mcp-wikidata) — Wikidata API implementation ☆`48`
- [amurshak/congressMCP](https://github.com/amurshak/congressMCP) — US Congress data for AI agents ☆`32`
- [mikechao/metmuseum-mcp](https://github.com/mikechao/metmuseum-mcp) — Met Museum art collection discovery ☆`31`
- [joelio/stocky](https://github.com/joelio/stocky) — An MCP server for searching and downloading stock photography. ☆`23`
- [angheljf/nyt](https://github.com/angheljf/nyt) — MCP server for New York Times article search ☆`19`
- [JamesANZ/us-legal-mcp](https://github.com/JamesANZ/us-legal-mcp) — An MCP server that provides comprehensive US legislation. ☆`34`
- [jhomen368/overseerr-mcp](https://github.com/jhomen368/overseerr-mcp) — Model Context Protocol (MCP) server for Overseerr and Seerr (the unified successor) - enables AI assistants to search, request, and manage media through your Seer instance ☆`18`
- [DappierAI/dappier-mcp](https://github.com/DappierAI/dappier-mcp) — MCP server for Dappier AI integration ☆`42`
- [cameronrye/activitypub-mcp](https://github.com/cameronrye/activitypub-mcp) — A comprehensive Model Context Protocol (MCP) server that enables LLMs like Claude to explore and interact with the existing Fediverse through standardized MCP tools, resources, and prompts. ☆`17`
- [kehvinbehvin/json-mcp-filter](https://github.com/kehvinbehvin/json-mcp-filter) — JSON MCP server to filter only relevant data for your LLM ☆`25`
- [adawalli/nexus](https://github.com/adawalli/nexus) — MCP Server to make searching openrouter easy ☆`23`
- [siva010928/multi-chat-mcp-server](https://github.com/siva010928/multi-chat-mcp-server) — MCP server for multi-chat capabilities ☆`24`
- [Himalayas-App/himalayas-mcp](https://github.com/Himalayas-App/himalayas-mcp) — A Model Context Protocol (MCP) server that provides access to remote job listings and company information from Himalayas.app. ☆`17`
- [r-huijts/opentk-mcp](https://github.com/r-huijts/opentk-mcp) — MCP server for Dutch parliamentary data via OpenTK ☆`21`
- [delorenj/mcp-server-ticketmaster](https://github.com/delorenj/mcp-server-ticketmaster) — Ticketmaster Discovery API ☆`24`
- [AshwinSundar/congress_gov_mcp](https://github.com/AshwinSundar/congress_gov_mcp) — Query US Congress.gov API ☆`19`
### News & Content

- [lfnovo/content-core](https://github.com/lfnovo/content-core) — Extract what matters from any media source ☆`166`
- [erithwik/mcp-hn](https://github.com/erithwik/mcp-hn) — MCP Server for Hackernews ☆`74`
- [imprvhub/mcp-rss-aggregator](https://github.com/imprvhub/mcp-rss-aggregator) — RSS feed aggregation for Claude Desktop ☆`27`
- [pskill9/hn-server](https://github.com/pskill9/hn-server) — Hacker news MCP server ☆`40`
- [format37/youtube_mcp](https://github.com/format37/youtube_mcp) — youtube transcriber mcp server ☆`32`
- [the0807/GeekNews-MCP-Server](https://github.com/the0807/GeekNews-MCP-Server) — GeekNews MCP Server ☆`18`
### Web Search Engines

- [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) — Exa MCP for web search and web crawling! ☆`4,762`
- [tavily-ai/tavily-mcp](https://github.com/tavily-ai/tavily-mcp) — Real-time search, extract, map and crawl ☆`2,254`
- [Aas-ee/open-webSearch](https://github.com/Aas-ee/open-webSearch) — MCP server for open web search ☆`1,637`
- [nickclyde/duckduckgo-mcp-server](https://github.com/nickclyde/duckduckgo-mcp-server) — MCP server for DuckDuckGo search ☆`1,366`
- [brave/brave-search-mcp-server](https://github.com/brave/brave-search-mcp-server) — Brave Search with AI summarization ☆`1,322`
- [ihor-sokoliuk/mcp-searxng](https://github.com/ihor-sokoliuk/mcp-searxng) — Private web search for AI assistants via SearXNG — supports Claude, Cursor, and any MCP client ☆`1,066`
- [mrkrsl/web-search-mcp](https://github.com/mrkrsl/web-search-mcp) — Local web search for Claude Desktop ☆`1,052`
- [kagisearch/kagimcp](https://github.com/kagisearch/kagimcp) — Official Kagi search MCP server ☆`457`
- [pskill9/web-search](https://github.com/pskill9/web-search) — Web search using free google search (NO API KEYS REQUIRED) ☆`462`
- [jae-jae/g-search-mcp](https://github.com/jae-jae/g-search-mcp) — Parallel Google search with summaries ☆`269`
- [superagents-lab/search1api-mcp](https://github.com/superagents-lab/search1api-mcp) — MCP server for web search and crawl via Search1API ☆`172`
- [serpapi/serpapi-mcp](https://github.com/serpapi/serpapi-mcp) — SerpApi MCP Server for Google and other search engine results ☆`160`
- [nkapila6/mcp-local-rag](https://github.com/nkapila6/mcp-local-rag) — RAG-like web search via MCP ☆`132`
- [ChanMeng666/server-google-news](https://github.com/ChanMeng666/server-google-news) — MCP server for Google News integration ☆`125`
- [SecretiveShell/MCP-searxng](https://github.com/SecretiveShell/MCP-searxng) — SearXNG search for agentic systems ☆`125`
- [mikechao/brave-search-mcp](https://github.com/mikechao/brave-search-mcp) — MCP server for Brave Search with filtering options ☆`121`
- [isnow890/naver-search-mcp](https://github.com/isnow890/naver-search-mcp) — MCP server for Naver search integration ☆`78`
- [tanigami/mcp-server-perplexity](https://github.com/tanigami/mcp-server-perplexity) — Perplexity API chat with citations ☆`94`
- [ConechoAI/openai-websearch-mcp](https://github.com/ConechoAI/openai-websearch-mcp) — openai websearch tool as mcp server ☆`93`
- [zhsama/duckduckgo-mcp-server](https://github.com/zhsama/duckduckgo-mcp-server) — MCP server for DuckDuckGo web search ☆`85`
- [OvertliDS/mcp-searxng-enhanced](https://github.com/OvertliDS/mcp-searxng-enhanced) — SearXNG web search with category awareness ☆`54`
- [leehanchung/bing-search-mcp](https://github.com/leehanchung/bing-search-mcp) — MCP Server for Bing Search API ☆`78`
- [pwilkin/mcp-searxng-public](https://github.com/pwilkin/mcp-searxng-public) — Query public SearXNG instances ☆`50`
- [ubie-oss/mcp-vertexai-search](https://github.com/ubie-oss/mcp-vertexai-search) — A MCP server for Vertex AI Search ☆`35`
- [Tomatio13/mcp-server-tavily](https://github.com/Tomatio13/mcp-server-tavily) — MCP Server for Tavily API integration ☆`50`
- [ac3xx/mcp-servers-kagi](https://github.com/ac3xx/mcp-servers-kagi) — A Model Context Protocol server implementation for Kagi's API ☆`45`
- [garylab/serper-mcp-server](https://github.com/garylab/serper-mcp-server) — A Serper MCP Server ☆`37`
- [mnhlt/WebSearch-MCP](https://github.com/mnhlt/WebSearch-MCP) — MCP server for web search integration ☆`38`
## Security

### Identity & Access

- [auth0/auth0-mcp-server](https://github.com/auth0/auth0-mcp-server) — Auth0 tenant management via natural language ☆`112`
- [sshaaf/keycloak-mcp-server](https://github.com/sshaaf/keycloak-mcp-server) — MCP server for Keycloak identity and access management ☆`45`
- [atomicchonk/roadrecon_mcp_server](https://github.com/atomicchonk/roadrecon_mcp_server) — Azure AD ROADrecon analysis for Claude ☆`52`
- [firstorderai/authenticator_mcp](https://github.com/firstorderai/authenticator_mcp) — Authenticator App for AI agents ☆`40`
- [ChristophEnglisch/keycloak-model-context-protocol](https://github.com/ChristophEnglisch/keycloak-model-context-protocol) — Keycloak user and realm management ☆`45`
- [hieuttmmo/entraid-mcp-server](https://github.com/hieuttmmo/entraid-mcp-server) — EntraID via Microsoft Graph API ☆`40`
- [descope-sample-apps/descope-mcp-server-stdio](https://github.com/descope-sample-apps/descope-mcp-server-stdio) — Descope user management and audits ☆`33`
- [kapilduraphe/okta-mcp-server](https://github.com/kapilduraphe/okta-mcp-server) — Okta MCP Server ☆`22`
### MCP Security

- [eqtylab/mcp-guardian](https://github.com/eqtylab/mcp-guardian) — Manage / Proxy / Secure your MCP Servers ☆`199`
- [kapilduraphe/mcp-watch](https://github.com/kapilduraphe/mcp-watch) — Security scanner for MCP servers ☆`135`
- [postralai/masquerade](https://github.com/postralai/masquerade) — The Privacy Firewall for LLMs ☆`77`
- [82ch/MCP-Dandan](https://github.com/82ch/MCP-Dandan) — MCP security with real-time proxying ☆`65`
- [kontext-security/attestable-mcp-server](https://github.com/kontext-security/attestable-mcp-server) — Hardware attestation for MCP server integrity ☆`21`
- [AIM-Intelligence/AIM-MCP](https://github.com/AIM-Intelligence/AIM-MCP) — AIM MCP Server :: Guard and Protect your MCPs & AI Chatting ☆`21`
- [cromwellian/hippycampus](https://github.com/cromwellian/hippycampus) — REST endpoint to MCP conversion ☆`20`
### Network & Firewall

- [vespo92/OPNSenseMCP](https://github.com/vespo92/OPNSenseMCP) — MCP Server for OPNSense to act as IaC proxy ☆`67`
- [intruder-io/intruder-mcp](https://github.com/intruder-io/intruder-mcp) — An MCP server to let AI agents control Intruder ☆`26`
### Pentesting & OSINT

- [PortSwigger/mcp-server](https://github.com/PortSwigger/mcp-server) — MCP Server for Burp ☆`1,010`
- [w0h1v/mcp-maigret](https://github.com/w0h1v/mcp-maigret) — Maigret OSINT user account collection ☆`250`
- [w0h1v/mcp-virustotal](https://github.com/w0h1v/mcp-virustotal) — VirusTotal API queries ☆`139`
- [w0h1v/mcp-shodan](https://github.com/w0h1v/mcp-shodan) — MCP server for Shodan - device search, IP recon, CVE intel ☆`146`
- [roadwy/cve-search_mcp](https://github.com/roadwy/cve-search_mcp) — CVE database security queries ☆`102`
- [mobb-dev/bugsy](https://github.com/mobb-dev/bugsy) — Automatic security vulnerability remediation for your code. ☆`68`
- [GitGuardian/ggmcp](https://github.com/GitGuardian/ggmcp) — Scan and remediate hardcoded secrets ☆`37`
- [StacklokLabs/osv-mcp](https://github.com/StacklokLabs/osv-mcp) — An MCP server for OSV ☆`36`
- [w0h1v/mcp-dnstwist](https://github.com/w0h1v/mcp-dnstwist) — DNS fuzzing for phishing detection ☆`51`
- [nickpending/mcp-recon](https://github.com/nickpending/mcp-recon) — Tellix conversational recon interface ☆`28`
- [gnlds/mcp-cve-intelligence-server-lite](https://github.com/gnlds/mcp-cve-intelligence-server-lite) — CVE intelligence from NVD, MITRE, GitHub ☆`19`
### Reverse Engineering

- [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) — IDA Pro reverse engineering with AI ☆`10,713`
- [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) — MCP Server for Ghidra ☆`9,567`
- [zinja-coder/jadx-ai-mcp](https://github.com/zinja-coder/jadx-ai-mcp) — Plugin for JADX to integrate MCP server ☆`2,533`
- [symgraph/GhidrAssistMCP](https://github.com/symgraph/GhidrAssistMCP) — An native MCP server extension for Ghidra ☆`674`
- [zinja-coder/apktool-mcp-server](https://github.com/zinja-coder/apktool-mcp-server) — APK Tool for Android reverse engineering ☆`603`
- [fosdickio/binary_ninja_mcp](https://github.com/fosdickio/binary_ninja_mcp) — Binary Ninja plugin for LLM integration ☆`407`
- [radareorg/radare2-mcp](https://github.com/radareorg/radare2-mcp) — MCP stdio server for radare2 ☆`274`
- [zboralski/ida-headless-mcp](https://github.com/zboralski/ida-headless-mcp) — Headless IDA Pro binary analysis via Model Context Protocol ☆`155`
- [13bm/GhidraMCP](https://github.com/13bm/GhidraMCP) — Active Socket based MCP Server for Ghidra ☆`133`
- [pullkitsan/mobsf-mcp-server](https://github.com/pullkitsan/mobsf-mcp-server) — MobSF APK and IPA security scanning ☆`21`
### SIEM & SecOps

- [beelzebub-labs/beelzebub](https://github.com/beelzebub-labs/beelzebub) — Low-code honeypot with AI virtualization ☆`2,099`
- [MorDavid/BloodHound-MCP-AI](https://github.com/MorDavid/BloodHound-MCP-AI) — BloodHound integration with AI through MCP ☆`371`
- [CrowdStrike/falcon-mcp](https://github.com/CrowdStrike/falcon-mcp) — CrowdStrike Falcon security analysis ☆`226`
- [gbrigandi/mcp-server-wazuh](https://github.com/gbrigandi/mcp-server-wazuh) — MCP Server for Wazuh SIEM ☆`228`
- [securityfortech/secops-mcp](https://github.com/securityfortech/secops-mcp) — All-in-one security testing toolbox via MCP ☆`204`
- [cycodehq/cycode-cli](https://github.com/cycodehq/cycode-cli) — SAST, SCA, Secrets, IaC security scanning ☆`99`
- [panther-labs/mcp-panther](https://github.com/panther-labs/mcp-panther) — Detections, alerts, and log queries ☆`46`
- [qianniuspace/mcp-security-audit](https://github.com/qianniuspace/mcp-security-audit) — MCP server for security auditing ☆`54`
- [slouchd/cyberchef-api-mcp-server](https://github.com/slouchd/cyberchef-api-mcp-server) — CyberChef API MCP Server ☆`43`
- [Gaffx/volatility-mcp](https://github.com/Gaffx/volatility-mcp) — This repo hosts an MCP server for volatility3.x ☆`51`
- [fr0gger/MCP_Security](https://github.com/fr0gger/MCP_Security) — This is a repository to experiment with MCP for security ☆`49`
- [Contrast-Security-OSS/mcp-contrast](https://github.com/Contrast-Security-OSS/mcp-contrast) — MCP Server for Contrast Security ☆`21`
- [zxzinn/opencti-mcp](https://github.com/zxzinn/opencti-mcp) — OpenCTI threat intelligence platform ☆`39`
- [jyjune/mcp_vms](https://github.com/jyjune/mcp_vms) — MCP server for controlling and accessing a video surveillance system ☆`16`
- [gbrigandi/mcp-server-cortex](https://github.com/gbrigandi/mcp-server-cortex) — MCP Server for Cortex ☆`16`
## Social Media

- [iFurySt/RedNote-MCP](https://github.com/iFurySt/RedNote-MCP) — MCP server for accessing RedNote(XiaoHongShu, xhs). ☆`1,077`
- [karanb192/reddit-mcp-buddy](https://github.com/karanb192/reddit-mcp-buddy) — Clean Reddit data: posts, search, users ☆`761`
- [king-of-the-grackles/reddit-research-mcp](https://github.com/king-of-the-grackles/reddit-research-mcp) — Reddit research with structured insights ☆`221`
- [adhikasp/mcp-twikit](https://github.com/adhikasp/mcp-twikit) — Twitter interaction via MCP ☆`234`
- [HagaiHen/facebook-mcp-server](https://github.com/HagaiHen/facebook-mcp-server) — Facebook posts, comments, insights automation ☆`192`
- [Seym0n/tiktok-mcp](https://github.com/Seym0n/tiktok-mcp) — Model Context Protocol (MCP) with TikTok integration ☆`183`
- [Xquik-dev/x-twitter-scraper](https://github.com/Xquik-dev/x-twitter-scraper) — X/Twitter API platform with MCP, tweet search, profile tweets, follower export, media download, posting, replies, webhooks, REST API, and SDKs ☆`167`
- [34892002/bilibili-mcp-js](https://github.com/34892002/bilibili-mcp-js) — Bilibili video search MCP service ☆`179`
- [trypeggy/instagram_dm_mcp](https://github.com/trypeggy/instagram_dm_mcp) — Instagram Direct messages MCP ☆`175`
- [anwerj/youtube-uploader-mcp](https://github.com/anwerj/youtube-uploader-mcp) — Upload, Update or Schedule videos on Youtube with the help of AI ☆`49`
- [LuniaKunal/mcp-twitter](https://github.com/LuniaKunal/mcp-twitter) — Manage your twitter account using mcp ☆`60`
- [jaipandya/producthunt-mcp-server](https://github.com/jaipandya/producthunt-mcp-server) — MCP server for Product Hunt data access ☆`49`
- [ertiqah/linkedin-mcp-runner](https://github.com/ertiqah/linkedin-mcp-runner) — LinkedIn content analysis and posting ☆`30`
- [AbdelStark/nostr-mcp](https://github.com/AbdelStark/nostr-mcp) — Nostr posting and interaction ☆`37`
- [laulauland/bluesky-context-server](https://github.com/laulauland/bluesky-context-server) — Bluesky MCP server ☆`32`
- [macrocosm-os/macrocosmos-mcp](https://github.com/macrocosm-os/macrocosmos-mcp) — The MCP for macrocosmos subnets. ☆`28`
- [jonathan-politzki/mcp-writer-substack](https://github.com/jonathan-politzki/mcp-writer-substack) — Bridge Substack writings to Claude ☆`31`
- [mbelinky/x-mcp-server](https://github.com/mbelinky/x-mcp-server) — MCP server to post on x.com with OAuth v1 and v2 ☆`21`
- [gwbischof/bluesky-social-mcp](https://github.com/gwbischof/bluesky-social-mcp) — A Bluesky MCP ☆`16`
- [wangshunnn/bilibili-mcp-server](https://github.com/wangshunnn/bilibili-mcp-server) — MCP server for the bilibili API ☆`16`
## Sports

- [r-huijts/strava-mcp](https://github.com/r-huijts/strava-mcp) — Strava fitness data integration ☆`455`
- [guillochon/mlb-api-mcp](https://github.com/guillochon/mlb-api-mcp) — MCP server for MLB baseball statistics ☆`58`
- [rishijatia/fantasy-pl-mcp](https://github.com/rishijatia/fantasy-pl-mcp) — Fantasy Premier League MCP Server ☆`71`
- [yeonupark/mcp-soccer-data](https://github.com/yeonupark/mcp-soccer-data) — Real-time football data ☆`38`
- [mikechao/balldontlie-mcp](https://github.com/mikechao/balldontlie-mcp) — MCP server for NBA, NFL, MLB sports data ☆`25`
- [kw510/strava-mcp](https://github.com/kw510/strava-mcp) — MCP server with Strava OAuth on Cloudflare Workers ☆`27`
- [lenwood/cfbd-mcp-server](https://github.com/lenwood/cfbd-mcp-server) — An MCP server enabling CFBD API queries within Claude Desktop. ☆`26`
- [r-huijts/firstcycling-mcp](https://github.com/r-huijts/firstcycling-mcp) — MCP server for professional cycling data from FirstCycling ☆`19`
- [tomekkorbak/strava-mcp-server](https://github.com/tomekkorbak/strava-mcp-server) — MCP server for Strava API integration ☆`22`
- [willvelida/mcp-afl-server](https://github.com/willvelida/mcp-afl-server) — This is a Model Context Protocol (MCP) server that provides AFL (Australian Football League) data from Squiggle API. ☆`17`
- [RobSpectre/mvf1](https://github.com/RobSpectre/mvf1) — Python package and CLI for MultiViewer For F1 ☆`19`
## Text-to-Speech

- [mbailey/voicemode](https://github.com/mbailey/voicemode) — Natural voice conversations with Claude Code ☆`1,285`
- [mberg/kokoro-tts-mcp](https://github.com/mberg/kokoro-tts-mcp) — Kokoro Text to Speech (TTS) MCP Server ☆`81`
## Translation

- [caol64/wenyan-mcp](https://github.com/caol64/wenyan-mcp) — Markdown formatting and translation to Chinese ☆`1,280`
- [aymericzip/intlayer](https://github.com/aymericzip/intlayer) — MCP server for Intlayer internationalization ☆`788`
- [DeepL/deepl-mcp-server](https://github.com/DeepL/deepl-mcp-server) — Translation with DeepL API ☆`110`
- [translated/lara-mcp](https://github.com/translated/lara-mcp) — Lara Translate API with language detection ☆`94`
- [mmntm/weblate-mcp](https://github.com/mmntm/weblate-mcp) —  ☆`21`
## Travel & Transport

- [openbnb-org/mcp-server-airbnb](https://github.com/openbnb-org/mcp-server-airbnb) — Search Airbnb using your AI Agent ☆`493`
- [cobanov/teslamate-mcp](https://github.com/cobanov/teslamate-mcp) — MCP server for TeslaMate vehicle data and analytics ☆`133`
- [r-huijts/ns-mcp-server](https://github.com/r-huijts/ns-mcp-server) — MCP server for Dutch Railways (NS) travel information ☆`57`
- [pab1it0/tripadvisor-mcp](https://github.com/pab1it0/tripadvisor-mcp) — MCP server for Tripadvisor location data and reviews ☆`61`
- [Pradumnasaraf/aviationstack-mcp](https://github.com/Pradumnasaraf/aviationstack-mcp) — MCP for AviationStack API - real-time flight data ☆`24`
- [sunsetcoder/flightradar24-mcp-server](https://github.com/sunsetcoder/flightradar24-mcp-server) — Model Context Protocol server for Flight Tracking ☆`47`
- [KyrieTangSheng/mcp-server-nationalparks](https://github.com/KyrieTangSheng/mcp-server-nationalparks) — US National Parks info via NPS API ☆`40`
- [variflight/variflight-mcp](https://github.com/variflight/variflight-mcp) — Variflight services implementation ☆`30`
- [mfukushim/map-traveler-mcp](https://github.com/mfukushim/map-traveler-mcp) — Virtual traveler library for MCP ☆`23`
- [campertunity/mcp-server](https://github.com/campertunity/mcp-server) —  ☆`16`
- [JordanDalton/DoorDash-MCP-Server](https://github.com/JordanDalton/DoorDash-MCP-Server) — MCP server for DoorDash delivery service integration ☆`24`
## Web Scraping

- [ScrapeGraphAI/Scrapegraph-ai](https://github.com/ScrapeGraphAI/Scrapegraph-ai) — Python scraper based on AI ☆`28,616`
- [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server) — Web scraping and search for LLM clients ☆`7,032`
- [brightdata/brightdata-mcp](https://github.com/brightdata/brightdata-mcp) — All-in-one public web access solution ☆`2,533`
- [apify/apify-mcp-server](https://github.com/apify/apify-mcp-server) — MCP server for Apify web scraping and data extraction ☆`2,190`
- [jae-jae/fetcher-mcp](https://github.com/jae-jae/fetcher-mcp) — Playwright web page content fetching ☆`1,069`
- [etsd-tech/mcp-pointer](https://github.com/etsd-tech/mcp-pointer) — DOM element pointing for agents ☆`588`
- [tinyfish-io/agentql-mcp](https://github.com/tinyfish-io/agentql-mcp) — AgentQL data extraction integration ☆`174`
- [just-every/mcp-read-website-fast](https://github.com/just-every/mcp-read-website-fast) — Fast webpage to markdown conversion ☆`158`
- [scrapeless-ai/scrapeless-mcp-server](https://github.com/scrapeless-ai/scrapeless-mcp-server) — Scrapeless Mcp Server ☆`166`
- [pskill9/website-downloader](https://github.com/pskill9/website-downloader) — MCP server to download entire websites ☆`154`
- [just-every/mcp-screenshot-website-fast](https://github.com/just-every/mcp-screenshot-website-fast) — Fast webpage screenshots for LLMs ☆`108`
- [oxylabs/oxylabs-mcp](https://github.com/oxylabs/oxylabs-mcp) — Official Oxylabs MCP integration ☆`101`
- [cyberchitta/scrapling-fetch-mcp](https://github.com/cyberchitta/scrapling-fetch-mcp) — Access bot-protected websites ☆`102`
- [supadata-ai/mcp](https://github.com/supadata-ai/mcp) — Video and web scraping for Claude ☆`61`
- [pragmar/mcp-server-webcrawl](https://github.com/pragmar/mcp-server-webcrawl) — Web crawler data and archives connection ☆`44`
- [webscraping-ai/webscraping-ai-mcp-server](https://github.com/webscraping-ai/webscraping-ai-mcp-server) — MCP server for AI-powered web scraping ☆`44`
- [crawlbase/crawlbase-mcp](https://github.com/crawlbase/crawlbase-mcp) — MCP server connecting AI agents with real-time web data ☆`55`
- [Decodo/mcp-server](https://github.com/Decodo/mcp-server) — Decodo web scraping for MCP clients ☆`35`
- [puremd/puremd-mcp](https://github.com/puremd/puremd-mcp) — Unblock, scrape, and search tools for MCP clients ☆`60`
- [djannot/puppeteer-vision-mcp](https://github.com/djannot/puppeteer-vision-mcp) — Web scraping with AI-driven interaction handling ☆`48`
- [ananddtyagi/webpage-screenshot-mcp](https://github.com/ananddtyagi/webpage-screenshot-mcp) — MCP server for webpage screenshot capture ☆`58`
- [wong2/mcp-jina-reader](https://github.com/wong2/mcp-jina-reader) — Jina Reader MCP Server ☆`47`
- [olostep/olostep-mcp-server](https://github.com/olostep/olostep-mcp-server) — MCP server for Olostep — the web scraping, crawling, and search infrastructure used by top AI companies. Gives any MCP-compatible AI agent the ability to scrape, crawl, batch-extract, and search the web in real time. ☆`21`
- [DevEnterpriseSoftware/scrapi-mcp](https://github.com/DevEnterpriseSoftware/scrapi-mcp) — MCP server for using ScrAPI to scrape web pages. ☆`18`
- [levz0r/html-to-markdown-mcp](https://github.com/levz0r/html-to-markdown-mcp) — HTML to Markdown converter using Turndown ☆`25`


---

## 🏆 Top 100 by Stars

> The most starred projects in this list, sorted by GitHub stars.

1. [upstash/context7](https://github.com/upstash/context7) — Up-to-date code docs for LLMs ☆`59,671`
1. [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) — Chrome DevTools for coding agents ☆`47,555`
1. [mindsdb/mindshub](https://github.com/mindsdb/mindshub) — Query Engine for AI Analytics - self-reasoning agents on live data ☆`39,482`
1. [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) — Playwright MCP server ☆`35,453`
1. [github/github-mcp-server](https://github.com/github/github-mcp-server) — GitHub's official MCP Server ☆`31,671`
1. [ScrapeGraphAI/Scrapegraph-ai](https://github.com/ScrapeGraphAI/Scrapegraph-ai) — Python scraper based on AI ☆`28,616`
1. [PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp) — Python framework for building MCP servers and clients ☆`26,826`
1. [oraios/serena](https://github.com/oraios/serena) — Semantic code retrieval and editing toolkit ☆`26,816`
1. [mastra-ai/mastra](https://github.com/mastra-ai/mastra) — TypeScript AI agent framework with RAG ☆`26,513`
1. [ahujasid/blender-mcp](https://github.com/ahujasid/blender-mcp) — Blender 3D modeling with Claude AI ☆`24,778`
1. [Skyvern-AI/skyvern](https://github.com/Skyvern-AI/skyvern) — Automate browser based workflows with AI ☆`22,583`
1. [czlonkowski/n8n-mcp](https://github.com/czlonkowski/n8n-mcp) — Build n8n workflows with AI assistants ☆`22,398`
1. [trycua/cua](https://github.com/trycua/cua) — MCP server for CUA platform ☆`20,525`
1. [screenpipe/screenpipe](https://github.com/screenpipe/screenpipe) — AI app store with 24/7 desktop history ☆`20,467`
1. [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) — Hindsight: Agent Memory That Learns ☆`18,747`
1. [apache/apisix](https://github.com/apache/apisix) — The Cloud-Native API Gateway and AI Gateway ☆`16,907`
1. [googleapis/mcp-toolbox](https://github.com/googleapis/mcp-toolbox) — Open source database MCP toolbox ☆`16,008`
1. [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) — Figma layout info for AI coding agents ☆`15,485`
1. [zilliztech/claude-context](https://github.com/zilliztech/claude-context) — Code search for Claude Code agents ☆`12,194`
1. [tadata-org/fastapi_mcp](https://github.com/tadata-org/fastapi_mcp) — Expose FastAPI endpoints as MCP tools ☆`11,950`
1. [elie222/inbox-zero](https://github.com/elie222/inbox-zero) — AI email assistant for inbox zero ☆`11,695`
1. [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) — IDA Pro reverse engineering with AI ☆`10,713`
1. [instantdb/instant](https://github.com/instantdb/instant) — Modern Firebase with real-time database ☆`10,362`
1. [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) — MCP Server for Ghidra ☆`9,567`
1. [awslabs/mcp](https://github.com/awslabs/mcp) — AWS MCP servers for AI assistants ☆`9,491`
1. [mark3labs/mcp-go](https://github.com/mark3labs/mcp-go) — Go implementation of MCP ☆`8,920`
1. [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) — Terminal control, file search, diff editing ☆`8,789`
1. [lastmile-ai/mcp-agent](https://github.com/lastmile-ai/mcp-agent) — Build agents with MCP and workflow patterns ☆`8,479`
1. [idosal/git-mcp](https://github.com/idosal/git-mcp) — Free remote MCP for any GitHub project ☆`8,280`
1. [Upsonic/Upsonic](https://github.com/Upsonic/Upsonic) — Build autonomous AI agents in Python. ☆`7,923`
1. [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server) — Web scraping and search for LLM clients ☆`7,032`
1. [superradcompany/microsandbox](https://github.com/superradcompany/microsandbox) — easy fast local-first microVM library and toolkit ☆`7,015`
1. [grab/cursor-talk-to-figma-mcp](https://github.com/grab/cursor-talk-to-figma-mcp) — Cursor and Figma communication ☆`6,931`
1. [BrowserMCP/mcp](https://github.com/BrowserMCP/mcp) — Browser control for AI applications ☆`6,867`
1. [GreptimeTeam/greptimedb](https://github.com/GreptimeTeam/greptimedb) — Unified observability DB for metrics, logs, traces ☆`6,496`
1. [genkit-ai/genkit](https://github.com/genkit-ai/genkit) — AI app framework for JavaScript and Go ☆`6,281`
1. [getsentry/XcodeBuildMCP](https://github.com/getsentry/XcodeBuildMCP) — MCP server for Xcode build operations ☆`6,133`
1. [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) — WhatsApp MCP server ☆`5,934`
1. [executeautomation/mcp-playwright](https://github.com/executeautomation/mcp-playwright) — MCP server for Playwright browser testing ☆`5,614`
1. [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) — MCP server for Atlassian tools (Confluence, Jira) ☆`5,613`
1. [mobile-next/mobile-mcp](https://github.com/mobile-next/mobile-mcp) — Mobile automation for iOS, Android, emulators ☆`5,608`
1. [21st-dev/magic-mcp](https://github.com/21st-dev/magic-mcp) — Frontend development with AI like Magic ☆`5,498`
1. [baserow/baserow](https://github.com/baserow/baserow) — No-code database, apps, agents with AI ☆`5,402`
1. [lingodotdev/lingo.dev](https://github.com/lingodotdev/lingo.dev) — MCP server for Lingo localization platform ☆`5,401`
1. [Kiln-AI/Kiln](https://github.com/Kiln-AI/Kiln) — Build AI systems with Evals, RAG, Agents, fine-tuning ☆`4,971`
1. [openclaw/Peekaboo](https://github.com/openclaw/Peekaboo) — macOS screenshot and window capture MCP server ☆`4,909`
1. [Coding-Solo/godot-mcp](https://github.com/Coding-Solo/godot-mcp) — MCP server for Godot game engine ☆`4,892`
1. [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) — Exa MCP for web search and web crawling! ☆`4,762`
1. [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server) — Official Notion MCP Server ☆`4,552`
1. [antvis/mcp-server-chart](https://github.com/antvis/mcp-server-chart) — 25+ visual charts using @antvis for data analysis ☆`4,259`
1. [MarkusPfundstein/mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) — Obsidian integration via REST API plugin ☆`4,126`
1. [haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server) — Excel file manipulation ☆`4,053`
1. [archestra-ai/archestra](https://github.com/archestra-ai/archestra) — Enterprise AI Platform with guardrails, MCP registry, gateway & orchestrator ☆`4,021`
1. [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) — Cloudflare services management ☆`3,984`
1. [CodeGraphContext/CodeGraphContext](https://github.com/CodeGraphContext/CodeGraphContext) — Code graph indexing for AI context ☆`3,980`
1. [dagger/container-use](https://github.com/dagger/container-use) — MCP server for container orchestration ☆`3,922`
1. [IvanMurzak/Unity-MCP](https://github.com/IvanMurzak/Unity-MCP) — AI-powered bridge connecting LLMs to Unity Editor ☆`3,654`
1. [basicmachines-co/basic-memory](https://github.com/basicmachines-co/basic-memory) — AI conversations that remember context ☆`3,508`
1. [metorial/metorial](https://github.com/metorial/metorial) — Connect any AI model to 1200+ integrations (MCP, CLI, API) ☆`3,322`
1. [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana) — MCP server for Grafana ☆`3,277`
1. [nowork-studio/NotFair](https://github.com/nowork-studio/NotFair) — NotFair Google Ads MCP — diagnose, recommend, and execute campaign changes ☆`3,260`
1. [nowork-studio/NotFair](https://github.com/nowork-studio/NotFair) — Claude Code skills for SEO, GEO, Google Ads MCP, Meta Ads MCP, Google Search Console MCP, and Google Analytics (GA4) MCP ☆`3,260`
1. [bytebase/dbhub](https://github.com/bytebase/dbhub) — Token-efficient multi-database MCP ☆`3,228`
1. [crystaldba/postgres-mcp](https://github.com/crystaldba/postgres-mcp) — Postgres with read/write access and performance ☆`3,108`
1. [blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server) — arXiv paper search and analysis ☆`2,983`
1. [taylorwilsdon/google_workspace_mcp](https://github.com/taylorwilsdon/google_workspace_mcp) — MCP server for Google Workspace integration ☆`2,910`
1. [zcaceres/markdownify-mcp](https://github.com/zcaceres/markdownify-mcp) — Convert almost anything to Markdown ☆`2,886`
1. [Jpisnice/shadcn-ui-mcp-server](https://github.com/Jpisnice/shadcn-ui-mcp-server) — MCP server for shadcn/ui component library ☆`2,881`
1. [supabase/mcp](https://github.com/supabase/mcp) — Connect Supabase to your AI assistants ☆`2,831`
1. [sparfenyuk/mcp-proxy](https://github.com/sparfenyuk/mcp-proxy) — A bridge between Streamable HTTP and stdio MCP transports ☆`2,683`
1. [metatool-ai/metamcp](https://github.com/metatool-ai/metamcp) — MCP Aggregator, Orchestrator, Middleware, Gateway in one docker ☆`2,548`
1. [zinja-coder/jadx-ai-mcp](https://github.com/zinja-coder/jadx-ai-mcp) — Plugin for JADX to integrate MCP server ☆`2,533`
1. [brightdata/brightdata-mcp](https://github.com/brightdata/brightdata-mcp) — All-in-one public web access solution ☆`2,533`
1. [perplexityai/modelcontextprotocol](https://github.com/perplexityai/modelcontextprotocol) — Official Perplexity API MCP server ☆`2,406`
1. [jamubc/gemini-mcp-tool](https://github.com/jamubc/gemini-mcp-tool) — MCP server for Gemini CLI with large file analysis ☆`2,263`
1. [tavily-ai/tavily-mcp](https://github.com/tavily-ai/tavily-mcp) — Real-time search, extract, map and crawl ☆`2,254`
1. [financial-datasets/mcp-server](https://github.com/financial-datasets/mcp-server) — Financial Datasets stock market API ☆`2,244`
1. [apify/apify-mcp-server](https://github.com/apify/apify-mcp-server) — MCP server for Apify web scraping and data extraction ☆`2,190`
1. [cjo4m06/mcp-shrimp-task-manager](https://github.com/cjo4m06/mcp-shrimp-task-manager) — Task manager with chain-of-thought and reflection ☆`2,134`
1. [joshuayoes/ios-simulator-mcp](https://github.com/joshuayoes/ios-simulator-mcp) — MCP server for interacting with the iOS simulator ☆`2,110`
1. [beelzebub-labs/beelzebub](https://github.com/beelzebub-labs/beelzebub) — Low-code honeypot with AI virtualization ☆`2,099`
1. [chatmcp/mcpso](https://github.com/chatmcp/mcpso) — directory for Awesome MCP Servers ☆`2,030`
1. [IBM/mcp-cli](https://github.com/IBM/mcp-cli) — Feature-rich CLI for interacting with MCP servers ☆`2,003`
1. [nottelabs/notte](https://github.com/nottelabs/notte) — Framework to build web agents ☆`1,986`
1. [benborla/mcp-server-mysql](https://github.com/benborla/mcp-server-mysql) — MCP server for MySQL database operations ☆`1,974`
1. [stacklok/toolhive](https://github.com/stacklok/toolhive) — Runtime and gateway for deploying MCP servers in containers ☆`1,968`
1. [microsoft/azure-devops-mcp](https://github.com/microsoft/azure-devops-mcp) — Azure DevOps integration for AI agents ☆`1,907`
1. [containers/kubernetes-mcp-server](https://github.com/containers/kubernetes-mcp-server) — Kubernetes and OpenShift management ☆`1,846`
1. [CoderGamester/mcp-unity](https://github.com/CoderGamester/mcp-unity) — MCP server for Unity game engine integration ☆`1,843`
1. [samuelgursky/davinci-resolve-mcp](https://github.com/samuelgursky/davinci-resolve-mcp) — MCP server integration for DaVinci Resolve Studio ☆`1,833`
1. [MicrosoftDocs/mcp](https://github.com/MicrosoftDocs/mcp) — Microsoft Learn MCP for LLMs ☆`1,795`
1. [ravitemer/mcphub.nvim](https://github.com/ravitemer/mcphub.nvim) — MCP client for Neovim with intuitive server management ☆`1,785`
1. [korotovsky/slack-mcp-server](https://github.com/korotovsky/slack-mcp-server) — MCP server for Slack workspace integration ☆`1,752`
1. [julien040/anyquery](https://github.com/julien040/anyquery) — SQL queries for GitHub, Notion, +40 more ☆`1,735`
1. [stripe/ai](https://github.com/stripe/ai) — One-stop shop for building AI-powered products and businesses with Stripe. ☆`1,706`
1. [Aas-ee/open-webSearch](https://github.com/Aas-ee/open-webSearch) — MCP server for open web search ☆`1,637`
1. [leonardsellem/n8n-mcp-server](https://github.com/leonardsellem/n8n-mcp-server) — Tools for interacting with n8n API ☆`1,631`
1. [ezyang/codemcp](https://github.com/ezyang/codemcp) — Coding assistant MCP for Claude Desktop ☆`1,609`
1. [stack-chan/stack-chan](https://github.com/stack-chan/stack-chan) — A JavaScript-driven M5Stack-embedded super-kawaii robot. ☆`1,606`
1. [isaacphi/mcp-language-server](https://github.com/isaacphi/mcp-language-server) — MCP server implementing Language Server Protocol ☆`1,570`

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
