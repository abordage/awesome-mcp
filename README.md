# Awesome MCP

[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-mcp?label=last%20update)](README.md)
[![License](https://img.shields.io/github/license/abordage/awesome-mcp)](LICENSE)

**Automated. Curated. Ranked.**

[Model Context Protocol (MCP)](https://modelcontextprotocol.io/) servers, clients, and frameworks — the open standard for connecting AI assistants to external data sources and tools. This awesome list is automatically maintained with daily GitHub API updates. Projects are re-ranked daily based on current activity metrics.

**Daily process:** Merge community PRs → Scan repos → Filter stale projects → Recalculate scores → Rebuild list

- [AI Coding Agents](#ai-coding-agents)
- [AI Memory & RAG](#ai-memory--rag)
- [Aggregators & Gateways](#aggregators--gateways)
  - [Aggregators](#aggregators)
  - [Gateways & Proxies](#gateways--proxies)
  - [Platforms & Registries](#platforms--registries)
- [Browser Automation](#browser-automation)
- [CLI Tools](#cli-tools)
- [CRM & ERP](#crm--erp)
- [Cloud & Infrastructure](#cloud--infrastructure)
  - [Cloud Platforms](#cloud-platforms)
  - [Kubernetes](#kubernetes)
  - [Virtualization & IaC](#virtualization--iac)
- [Communication & Messaging](#communication--messaging)
- [Data & Analytics](#data--analytics)
- [Databases](#databases)
  - [Analytics & Warehouses](#analytics--warehouses)
  - [Cache & Key-Value](#cache--key-value)
  - [Cloud Platforms](#cloud-platforms)
  - [Graph Databases](#graph-databases)
  - [Multi-Database Tools](#multi-database-tools)
  - [NoSQL & Document](#nosql--document)
  - [SQL Databases](#sql-databases)
  - [Spreadsheets & No-Code](#spreadsheets--no-code)
  - [Streaming & Messaging](#streaming--messaging)
  - [Time-Series & Metrics](#time-series--metrics)
  - [Vector Databases](#vector-databases)
- [Developer Tools](#developer-tools)
  - [API Tools](#api-tools)
  - [CI/CD & DevOps](#cicd--devops)
  - [Code Analysis](#code-analysis)
  - [Design & UI](#design--ui)
  - [Documentation](#documentation)
  - [IDE & Editors](#ide--editors)
  - [MCP SDKs](#mcp-sdks)
  - [Mobile Development](#mobile-development)
  - [Robotics & Automation](#robotics--automation)
  - [Task Management](#task-management)
  - [Utilities](#utilities)
  - [Version Control](#version-control)
  - [Web Scraping](#web-scraping)
  - [Package Managers](#package-managers)
  - [Debuggers](#debuggers)
  - [Testing & QA](#testing--qa)
- [Embedded & IoT](#embedded--iot)
- [File Systems & Storage](#file-systems--storage)
- [Finance](#finance)
  - [Accounting & Budgeting](#accounting--budgeting)
  - [Crypto & Blockchain](#crypto--blockchain)
  - [Payments & Banking](#payments--banking)
  - [Stock Data & Analytics](#stock-data--analytics)
  - [Trading & Exchanges](#trading--exchanges)
- [Gaming](#gaming)
- [Healthcare & Bioinformatics](#healthcare--bioinformatics)
- [Location & Maps](#location--maps)
- [Marketing & Analytics](#marketing--analytics)
- [Media Processing](#media-processing)
- [Monitoring & Observability](#monitoring--observability)
- [Official](#official)
- [Others](#others)
  - [MCP Clients](#mcp-clients)
  - [Frameworks & SDKs](#frameworks--sdks)
- [Productivity](#productivity)
  - [Collaboration](#collaboration)
  - [Google Workspace](#google-workspace)
  - [Helpdesk & Support](#helpdesk--support)
  - [Learning & Flashcards](#learning--flashcards)
  - [Note-taking & Docs](#note-taking--docs)
  - [Project Management](#project-management)
  - [Tasks & Calendar](#tasks--calendar)
  - [Wiki & Collaboration](#wiki--collaboration)
- [Research & Science](#research--science)
- [Sandboxing & Execution](#sandboxing--execution)
- [Search & Extraction](#search--extraction)
  - [Academic Research](#academic-research)
  - [Data APIs](#data-apis)
  - [News & Content](#news--content)
  - [Web Scraping & Crawling](#web-scraping--crawling)
  - [Web Search Engines](#web-search-engines)
- [Security](#security)
  - [Identity & Access](#identity--access)
  - [MCP Security](#mcp-security)
  - [Network & Firewall](#network--firewall)
  - [Reverse Engineering](#reverse-engineering)
  - [SIEM & SecOps](#siem--secops)
  - [Vulnerability & Threat Intel](#vulnerability--threat-intel)
- [Social Media](#social-media)
- [Sports](#sports)
- [Text-to-Speech](#text-to-speech)
- [Translation](#translation)
- [Travel & Transport](#travel--transport)
- [TODO](#todo)


## AI Coding Agents

- [bytedance/UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop) — Multimodal AI agent stack for UI automation ☆`20,111`
- [mastra-ai/mastra](https://github.com/mastra-ai/mastra) — TypeScript AI agent framework with RAG ☆`18,984`
- [oraios/serena](https://github.com/oraios/serena) — Semantic code retrieval and editing toolkit ☆`17,674`
- [lastmile-ai/mcp-agent](https://github.com/lastmile-ai/mcp-agent) — Build effective agents using Model Context Protocol and simple workflow patterns ☆`7,886`
- [zilliztech/claude-context](https://github.com/zilliztech/claude-context) — Code search MCP for Claude Code. Make entire codebase the context for any coding agent. ☆`4,847`
- [Kiln-AI/Kiln](https://github.com/Kiln-AI/Kiln) — Easily build AI systems with Evals, RAG, Agents, fine-tuning, synthetic data, and more. ☆`4,492`
- [perplexityai/modelcontextprotocol](https://github.com/perplexityai/modelcontextprotocol) — Official Perplexity API MCP server ☆`1,844`
- [jamubc/gemini-mcp-tool](https://github.com/jamubc/gemini-mcp-tool) — MCP server for Gemini CLI with large file analysis ☆`1,782`
- [ezyang/codemcp](https://github.com/ezyang/codemcp) — Coding assistant MCP for Claude Desktop ☆`1,580`
- [rinadelph/Agent-MCP](https://github.com/rinadelph/Agent-MCP) — Multi-agent AI collaboration framework ☆`1,087`
- [dmayboroda/minima](https://github.com/dmayboroda/minima) — On-premises conversational RAG with configurable containers ☆`1,021`
- [ref-tools/ref-tools-mcp](https://github.com/ref-tools/ref-tools-mcp) — Reference tools for coding agents ☆`879`
- [PV-Bhat/vibe-check-mcp-server](https://github.com/PV-Bhat/vibe-check-mcp-server) — Mentor-like feedback tool preventing AI over-engineering ☆`436`
- [evalstate/mcp-hfspace](https://github.com/evalstate/mcp-hfspace) — HuggingFace Spaces integration ☆`376`
- [ttommyth/interactive-mcp](https://github.com/ttommyth/interactive-mcp) — Interactive MCP server for human-in-the-loop AI ☆`327`
- [juehang/vscode-mcp-server](https://github.com/juehang/vscode-mcp-server) — VS Code editing features for LLM coding ☆`305`
- [DMontgomery40/deepseek-mcp-server](https://github.com/DMontgomery40/deepseek-mcp-server) — Model Context Protocol server for DeepSeek's advanced language models ☆`286`
- [SDGLBL/mcp-claude-code](https://github.com/SDGLBL/mcp-claude-code) — MCP implementation of Claude Code capabilities and more ☆`295`
- [Shashankss1205/CodeGraphContext](https://github.com/Shashankss1205/CodeGraphContext) — Code graph indexing for AI context ☆`227`
- [YanxingLiu/dify-mcp-server](https://github.com/YanxingLiu/dify-mcp-server) — Model Context Protocol (MCP) Server for dify workflows ☆`273`
- [pyroprompts/any-chat-completions-mcp](https://github.com/pyroprompts/any-chat-completions-mcp) — MCP Server for using any LLM as a Tool ☆`146`
- [agentrpc/agentrpc](https://github.com/agentrpc/agentrpc) — Universal RPC layer for AI agents ☆`124`
- [stippi/code-assistant](https://github.com/stippi/code-assistant) — LLM-powered autonomous coding assistant ☆`124`
- [nesquikm/mcp-rubber-duck](https://github.com/nesquikm/mcp-rubber-duck) — MCP bridge to query multiple OpenAI-compatible LLMs ☆`119`
- [paiml/paiml-mcp-agent-toolkit](https://github.com/paiml/paiml-mcp-agent-toolkit) — Pragmatic AI Labs MCP Agent Toolkit - An MCP Server designed to make code with agents more deterministic ☆`110`
- [GongRzhe/A2A-MCP-Server](https://github.com/GongRzhe/A2A-MCP-Server) — A mcp server that bridges the Model Context Protocol (MCP) with the Agent-to-Agent (A2A) protocol, enabling MCP-compatible AI assistants (like Claude) to seamlessly interact with A2A agents. ☆`124`
- [IDEA-Research/DINO-X-MCP](https://github.com/IDEA-Research/DINO-X-MCP) — MCP server for DINO-X vision model ☆`108`
- [IBM/wxflows](https://github.com/IBM/wxflows) — watsonx.ai Flows AI app tutorials ☆`111`
- [GongRzhe/Human-In-the-Loop-MCP-Server](https://github.com/GongRzhe/Human-In-the-Loop-MCP-Server) — A powerful MCP Server that enables AI assistants like Claude to interact with humans through intuitive GUI dialogs. This server bridges the gap between automated AI processes and human decision-making by providing real-time user input tools, choices, confirmations, and feedback mechanisms. ☆`120`
- [deepfates/mcp-replicate](https://github.com/deepfates/mcp-replicate) — Model Context Protocol server for Replicate's API ☆`92`
- [choplin/mcp-gemini-cli](https://github.com/choplin/mcp-gemini-cli) — MCP server for Gemini CLI integration ☆`90`
- [Rai220/think-mcp](https://github.com/Rai220/think-mcp) — MCP Server for reasoning ☆`84`
- [TheRaLabs/legion-mcp](https://github.com/TheRaLabs/legion-mcp) — MCP server for Legion AI platform ☆`79`
- [nikkoxgonzales/crash-mcp](https://github.com/nikkoxgonzales/crash-mcp) — MCP server for structured and efficient reasoning with step validation, branching, and revisions. ☆`60`
- [jinzcdev/leetcode-mcp-server](https://github.com/jinzcdev/leetcode-mcp-server) — MCP server for LeetCode problems and solutions ☆`76`
- [lamemind/mcp-server-multiverse](https://github.com/lamemind/mcp-server-multiverse) — MCP server for multiverse context management ☆`75`
- [pierrebrunelle/mcp-server-openai](https://github.com/pierrebrunelle/mcp-server-openai) — Query OpenAI models from Claude via MCP ☆`78`
- [eLyiN/gemini-bridge](https://github.com/eLyiN/gemini-bridge) — A lightweight MCP server bridging AI agents to Google's Gemini AI via official CLI ☆`70`
- [66julienmartin/MCP-server-Deepseek_R1](https://github.com/66julienmartin/MCP-server-Deepseek_R1) — A Model Context Protocol (MCP) server implementation connecting Claude Desktop with DeepSeek's language models (R1/V3) ☆`68`
- [YuChenSSR/multi-ai-advisor-mcp](https://github.com/YuChenSSR/multi-ai-advisor-mcp) — council of models for decision ☆`72`
- [ai-1st/deepview-mcp](https://github.com/ai-1st/deepview-mcp) — MCP server for DeepView AI analysis ☆`67`
- [micl2e2/code-to-tree](https://github.com/micl2e2/code-to-tree) — Source code to AST tree conversion ☆`70`
- [ruixingshi/deepseek-thinker-mcp](https://github.com/ruixingshi/deepseek-thinker-mcp) — A MCP provider Deepseek reasoning content to MCP-enabled AI Clients, like Claude Desktop. Supports access to Deepseek's CoT from the Deepseek API service or a local Ollama server. ☆`66`
- [mzxrai/mcp-openai](https://github.com/mzxrai/mcp-openai) — Chat with OpenAI models from Claude Desktop ☆`68`
- [zenml-io/mcp-zenml](https://github.com/zenml-io/mcp-zenml) — ZenML MLOps platform connection ☆`39`
- [PromptExecution/just-mcp](https://github.com/PromptExecution/just-mcp) — mcp server for just ☆`38`
- [gwbischof/free-will-mcp](https://github.com/gwbischof/free-will-mcp) — Experimental AI self-prompting MCP server ☆`32`
- [atlanhq/agent-toolkit](https://github.com/atlanhq/agent-toolkit) — Atlan AI Agent Toolkit ☆`25`
- [gotohuman/gotohuman-mcp-server](https://github.com/gotohuman/gotohuman-mcp-server) — Human approvals for AI agentic workflows ☆`47`
- [roboticforce/sugar](https://github.com/roboticforce/sugar) — Sugar - A Dev Team That Never Stops | Autonomous AI for Claude Code ☆`24`
- [gabrielmaialva33/winx-code-agent](https://github.com/gabrielmaialva33/winx-code-agent) — MCP-powered code agent for development ☆`23`
- [andybrandt/mcp-simple-openai-assistant](https://github.com/andybrandt/mcp-simple-openai-assistant) — Use OpenAI GPTs assistants from Claude ☆`36`
- [amidabuddha/unichat-mcp-server](https://github.com/amidabuddha/unichat-mcp-server) — Unified chat across multiple LLM providers ☆`37`
- [landing-ai/vision-agent-mcp](https://github.com/landing-ai/vision-agent-mcp) — MCP Server for Vision Agent Tools ☆`22`
- [OctoMind-dev/octomind-mcp](https://github.com/OctoMind-dev/octomind-mcp) — An MCP server for octomind tools, resources and prompts ☆`21`
- [wende/cicada](https://github.com/wende/cicada) — AI Coders search blindly. Be their guide. ☆`19`
- [doggybee/mcp-server-leetcode](https://github.com/doggybee/mcp-server-leetcode) — MCP server for LeetCode coding challenges ☆`36`
- [sequa-ai/sequa-mcp](https://github.com/sequa-ai/sequa-mcp) — MCP server for Sequa AI platform ☆`16`
- [vasayxtx/mcp-prompt-engine](https://github.com/vasayxtx/mcp-prompt-engine) — MCP Prompt Engine ☆`16`
- [66julienmartin/MCP-server-Qwen_Max](https://github.com/66julienmartin/MCP-server-Qwen_Max) — MCP server for Qwen Max model ☆`23`
- [aquarius-wing/actor-critic-thinking-mcp](https://github.com/aquarius-wing/actor-critic-thinking-mcp) — A dual-perspective thinking analysis server based on Model Context Protocol (MCP), providing comprehensive performance evaluation through Actor-Critic methodology. ☆`26`
- [iflytek/ifly-workflow-mcp-server](https://github.com/iflytek/ifly-workflow-mcp-server) — This a simple implementation of an MCP server using iFlytek. It enables calling iFlytek workflows through MCP tools. ☆`26`
- [PV-Bhat/gemsuite-mcp](https://github.com/PV-Bhat/gemsuite-mcp) — MCP server for GemSuite tools ☆`25`
- [VertexStudio/developer](https://github.com/VertexStudio/developer) — File editing, shell execution, screen capture ☆`18`
- [olalonde/mcp-human](https://github.com/olalonde/mcp-human) — Human Assistance for AI Assistants ☆`21`
- [nazar256/user-prompt-mcp](https://github.com/nazar256/user-prompt-mcp) — User input requests for Cursor ☆`18`
- [HyperbolicLabs/hyperbolic-mcp](https://github.com/HyperbolicLabs/hyperbolic-mcp) — MCP Server for Claude ☆`16`
## AI Memory & RAG

- [basicmachines-co/basic-memory](https://github.com/basicmachines-co/basic-memory) — AI conversations that actually remember. Never re-explain your project to your AI again. Join our Discord: https://discord.gg/tyvKNccgqN ☆`2,265`
- [doobidoo/mcp-memory-service](https://github.com/doobidoo/mcp-memory-service) — Stop re-explaining your project to AI every session. Automatic context memory for Claude, VS Code, Cursor, and 13+ AI tools. ☆`1,010`
- [chatmcp/mcp-server-chatsum](https://github.com/chatmcp/mcp-server-chatsum) — Query and Summarize your chat messages. ☆`1,024`
- [apecloud/ApeRAG](https://github.com/apecloud/ApeRAG) — Production GraphRAG with multi-modal ☆`990`
- [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) — Hindsight: Agent Memory That Works Like Human Memory ☆`813`
- [GreatScottyMac/context-portal](https://github.com/GreatScottyMac/context-portal) — Context Portal (ConPort): A memory bank MCP server building a project-specific knowledge graph to supercharge AI assistants. Enables powerful Retrieval Augmented Generation (RAG) for context-aware development in your IDE. ☆`714`
- [mem0ai/mem0-mcp](https://github.com/mem0ai/mem0-mcp) — MCP server for Mem0 long-term AI memory management ☆`544`
- [gannonh/memento-mcp](https://github.com/gannonh/memento-mcp) — Memento MCP: A Knowledge Graph Memory System for LLMs ☆`381`
- [graphlit/graphlit-mcp-server](https://github.com/graphlit/graphlit-mcp-server) — Model Context Protocol (MCP) Server for Graphlit Platform ☆`367`
- [CheMiguel23/MemoryMesh](https://github.com/CheMiguel23/MemoryMesh) — MCP server for knowledge graph memory ☆`323`
- [hannesrudolph/mcp-ragdocs](https://github.com/hannesrudolph/mcp-ragdocs) — MCP server for RAG document retrieval ☆`244`
- [jean-technologies/jean-memory](https://github.com/jean-technologies/jean-memory) — AI memory with mem0 and graphiti ☆`164`
- [jinzcdev/markmap-mcp-server](https://github.com/jinzcdev/markmap-mcp-server) — Markdown to interactive mind maps ☆`152`
- [pi22by7/In-Memoria](https://github.com/pi22by7/In-Memoria) — Persistent Intelligence Infrastructure for AI Agents ☆`131`
- [0xshellming/mcp-summarizer](https://github.com/0xshellming/mcp-summarizer) — MCP Server for AI Summarization ☆`147`
- [redleaves/context-keeper](https://github.com/redleaves/context-keeper) — Intelligent memory and context for AI agents ☆`124`
- [kaliaboi/mcp-zotero](https://github.com/kaliaboi/mcp-zotero) — Zotero collections for Claude Desktop ☆`141`
- [entanglr/zettelkasten-mcp](https://github.com/entanglr/zettelkasten-mcp) — MCP server implementing Zettelkasten knowledge management ☆`128`
- [needle-ai/needle-mcp](https://github.com/needle-ai/needle-mcp) — Needle MCP Server for easy RAG.Long-term memory for LLMs. ☆`88`
- [ragieai/ragie-mcp-server](https://github.com/ragieai/ragie-mcp-server) — Ragie Model Context Protocol Server ☆`84`
- [run-llama/mcp-server-llamacloud](https://github.com/run-llama/mcp-server-llamacloud) — LlamaCloud managed indexes connection ☆`84`
- [knowall-ai/mcp-neo4j-agent-memory](https://github.com/knowall-ai/mcp-neo4j-agent-memory) — Memory management MCP server for AI agents using Neo4j knowledge graphs ☆`59`
- [hungryrobot1/MCP-PIF](https://github.com/hungryrobot1/MCP-PIF) — An experimental MCP implementation of the personal intelligence framework (PIF) in Haskell. ☆`56`
- [agentic-mcp-tools/memora](https://github.com/agentic-mcp-tools/memora) — Persistent shared memories in SQLite ☆`47`
- [shinpr/mcp-local-rag](https://github.com/shinpr/mcp-local-rag) — MCP server for local RAG operations ☆`44`
- [peless/claude-thread-continuity](https://github.com/peless/claude-thread-continuity) — Keep your Claude conversations flowing! An MCP server that automatically saves and restores project context when threads hit token limits. ☆`58`
- [Yuchen20/Memory-Plus](https://github.com/Yuchen20/Memory-Plus) — Enhanced persistent memory management ☆`50`
- [vectara/vectara-mcp](https://github.com/vectara/vectara-mcp) — Open source MCP server for Vectara ☆`26`
- [vezlo/src-to-kb](https://github.com/vezlo/src-to-kb) — Convert source code to LLM ready knowledge base ☆`24`
- [doobidoo/MCP-Context-Provider](https://github.com/doobidoo/MCP-Context-Provider) — A static MCP server that provides AI models with persistent tool context, preventing context loss between chats. ☆`21`
- [ukkit/memcord](https://github.com/ukkit/memcord) — MCP server for memory and context management ☆`21`
- [skydeckai/mcp-server-rememberizer](https://github.com/skydeckai/mcp-server-rememberizer) — An MCP Server to enable global access to Rememberizer ☆`35`
- [cameronrye/openzim-mcp](https://github.com/cameronrye/openzim-mcp) — MCP server for OpenZIM archive access ☆`16`
- [bh-rat/context-awesome](https://github.com/bh-rat/context-awesome) — awesome-lists now available as MCP server for you agent. ☆`26`
## Aggregators & Gateways

- [VeriTeknik/pluggedin-mcp](https://github.com/VeriTeknik/pluggedin-mcp) — Plugged.in MCP Server manages all your other MCPs in one MCP. ☆`45`
- [universal-mcp/universal-mcp](https://github.com/universal-mcp/universal-mcp) — Universal MCP acts as a middle ware for your API applications. It can store your credentials, authorize, enable disable apps on the fly and much more. ☆`23`
- [wojtyniak/mcp-mcp](https://github.com/wojtyniak/mcp-mcp) — Meta-MCP Server that acts as a tool discovery and provisioning service for the Model Context Protocol ☆`17`
- [agree-able/room-mcp](https://github.com/agree-able/room-mcp) — Allow MCP clients like claude-desktop to use rooms to coordinate with other agents ☆`18`
### Aggregators

- [mindsdb/mindsdb](https://github.com/mindsdb/mindsdb) — Query Engine for AI - The only MCP Server you'll ever need ☆`38,120`
- [metatool-ai/metamcp](https://github.com/metatool-ai/metamcp) — MCP Aggregator, Orchestrator, Middleware, Gateway in one docker ☆`1,821`
- [mcpjungle/MCPJungle](https://github.com/mcpjungle/MCPJungle) — Self-hosted MCP Gateway and Registry for AI agents ☆`754`
- [1mcp-app/agent](https://github.com/1mcp-app/agent) — Unified MCP server aggregator ☆`325`
- [ComposioHQ/Rube](https://github.com/ComposioHQ/Rube) — Rube is a Model Context Protocol (MCP) server that connects your AI tools to 500+ apps like Gmail, Slack, GitHub, and Notion. Simply install it in your AI client, authenticate once with your apps, and start asking your AI to perform real actions like "Send an email" or "Create a task." ☆`313`
- [K-Dense-AI/claude-skills-mcp](https://github.com/K-Dense-AI/claude-skills-mcp) — Claude Agent Skills vector search ☆`202`
- [Intelligent-Internet/gemini-cli-mcp-openai-bridge](https://github.com/Intelligent-Internet/gemini-cli-mcp-openai-bridge) — Gemini CLI to MCP/OpenAI bridge ☆`122`
- [sitbon/magg](https://github.com/sitbon/magg) — Magg: The MCP Aggregator ☆`121`
- [badkk/awesome-crypto-mcp-servers](https://github.com/badkk/awesome-crypto-mcp-servers) — A collection of crypto MCP servers. ☆`127`
- [wanaku-ai/wanaku](https://github.com/wanaku-ai/wanaku) — Wanaku MCP Router ☆`93`
- [nguyenvanduocit/all-in-one-model-context-protocol](https://github.com/nguyenvanduocit/all-in-one-model-context-protocol) — GitLab, Jira, Confluence, YouTube ☆`97`
- [portel-dev/ncp](https://github.com/portel-dev/ncp) — Natural Context Provider with smart MCP tool loading ☆`55`
- [askbudi/roundtable](https://github.com/askbudi/roundtable) — Zero-config MCP unifying multiple AI coding assistants ☆`48`
- [gotoolkits/mcp-difyworkflow-server](https://github.com/gotoolkits/mcp-difyworkflow-server) — MCP server for Dify workflow invocation ☆`60`
- [hamidra/yamcp](https://github.com/hamidra/yamcp) — Local MCP workspace organization ☆`59`
- [waystation-ai/mcp](https://github.com/waystation-ai/mcp) — No-code secure MCP integration hub ☆`39`
- [nazar256/combine-mcp](https://github.com/nazar256/combine-mcp) — MCP aggregator combining multiple servers into one interface ☆`25`
- [membranehq/mcp-server](https://github.com/membranehq/mcp-server) — MCP Server for Membrane ☆`32`
- [glenngillen/mcpmcp-server](https://github.com/glenngillen/mcpmcp-server) — MCP server aggregator and router ☆`24`
### Gateways & Proxies

- [sparfenyuk/mcp-proxy](https://github.com/sparfenyuk/mcp-proxy) — A bridge between Streamable HTTP and stdio MCP transports ☆`2,115`
- [stacklok/toolhive](https://github.com/stacklok/toolhive) — Runtime and gateway for deploying MCP servers in containers ☆`1,459`
- [TBXark/mcp-proxy](https://github.com/TBXark/mcp-proxy) — An MCP proxy server that aggregates and serves multiple MCP resource servers through a single HTTP server. ☆`602`
- [ssut/Remote-MCP](https://github.com/ssut/Remote-MCP) — Type-safe solution for remote MCP communication ☆`203`
- [sxhxliang/mcp-access-point](https://github.com/sxhxliang/mcp-access-point) — Convert any web server to MCP instantly ☆`156`
- [toolprint/hypertool-mcp](https://github.com/toolprint/hypertool-mcp) — Dynamically expose tools from proxied servers based on an Agent Persona ☆`132`
- [VeriTeknik/pluggedin-mcp-proxy](https://github.com/VeriTeknik/pluggedin-mcp-proxy) — Unified MCP proxy managing multiple MCPs ☆`113`
- [smart-mcp-proxy/mcpproxy-go](https://github.com/smart-mcp-proxy/mcpproxy-go) — Supercharge AI Agents, Safely ☆`99`
- [tigranbs/mcgravity](https://github.com/tigranbs/mcgravity) — Proxy for composing multiple MCP servers into one endpoint ☆`80`
- [pyroprompts/mcp-stdio-to-streamable-http-adapter](https://github.com/pyroprompts/mcp-stdio-to-streamable-http-adapter) — Proxy through a STDIO MCP Server to interact with Streamable HTTP MCP Servers ☆`22`
- [nick1udwig/ws-mcp](https://github.com/nick1udwig/ws-mcp) — MCP server with WebSocket transport ☆`19`
### Platforms & Registries

- [metorial/metorial](https://github.com/metorial/metorial) — Connect any AI model to 600+ integrations; powered by MCP ☆`3,191`
- [chatmcp/mcpso](https://github.com/chatmcp/mcpso) — directory for Awesome MCP Servers ☆`1,946`
- [julien040/anyquery](https://github.com/julien040/anyquery) — SQL queries for GitHub, Notion, +40 more ☆`1,572`
- [jaw9c/awesome-remote-mcp-servers](https://github.com/jaw9c/awesome-remote-mcp-servers) — Remote MCP Servers ☆`959`
- [archestra-ai/archestra](https://github.com/archestra-ai/archestra) — Enterprise-ready MCP gateway, MCP registry & orchestrator ☆`380`
- [wegotdocs/open-mcp](https://github.com/wegotdocs/open-mcp) — Open standard and registry for converting web APIs into MCP servers ☆`320`
- [milisp/mcp-linker](https://github.com/milisp/mcp-linker) — mcp store manager, add & syncs MCP server configurations across clients like Claude code, Cursor build-in Codex agent use ChatGPT subscription, mcphub ☆`264`
- [liuyoshio/mcp-compass](https://github.com/liuyoshio/mcp-compass) — MCP Discovery & Recommendation Service - Find the right MCP server for your needs ☆`214`
- [integromat/make-mcp-server](https://github.com/integromat/make-mcp-server) — Make MCP Server ☆`147`
- [Jeamee/MCPHub-Desktop](https://github.com/Jeamee/MCPHub-Desktop) — Desktop APP for Discover and Install MCP Servers ☆`148`
- [juspay/neurolink](https://github.com/juspay/neurolink) — Universal AI platform with MCP and multi-provider support ☆`100`
- [rust-mcp-stack/mcp-discovery](https://github.com/rust-mcp-stack/mcp-discovery) — A command-line tool written in Rust for discovering and documenting MCP Server capabilities. ☆`73`
- [matthewdcage/cursor-mcp-installer](https://github.com/matthewdcage/cursor-mcp-installer) — Installs MCPs in cursor for you, give it a git URL and let it rip ☆`73`
- [VeyraX/veyrax-mcp](https://github.com/VeyraX/veyrax-mcp) — VeyraX unified tool access via single MCP ☆`47`
## Browser Automation

- [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) — Playwright MCP server ☆`24,746`
- [Skyvern-AI/skyvern](https://github.com/Skyvern-AI/skyvern) — Automate browser based workflows with AI ☆`19,904`
- [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) — Chrome DevTools for coding agents ☆`17,929`
- [BrowserMCP/mcp](https://github.com/BrowserMCP/mcp) — Browser control for AI applications ☆`5,272`
- [executeautomation/mcp-playwright](https://github.com/executeautomation/mcp-playwright) — MCP server for Playwright browser testing ☆`5,088`
- [browserbase/mcp-server-browserbase](https://github.com/browserbase/mcp-server-browserbase) — Browser control with Browserbase ☆`2,966`
- [nottelabs/notte](https://github.com/nottelabs/notte) — Reliable Browser AI Agents (YC S25) ☆`1,785`
- [refreshdotdev/web-eval-agent](https://github.com/refreshdotdev/web-eval-agent) — Autonomous web application evaluation ☆`1,227`
- [steipete/Peekaboo](https://github.com/steipete/Peekaboo) — macOS screenshot and window capture MCP server ☆`899`
- [kontext-dev/browser-use-mcp-server](https://github.com/kontext-dev/browser-use-mcp-server) — Browse the web, directly from Cursor etc. ☆`786`
- [hyperbrowserai/mcp](https://github.com/hyperbrowserai/mcp) — A MCP server implementation for hyperbrowser ☆`661`
- [pskill9/web-search](https://github.com/pskill9/web-search) — Web search using free google search (NO API KEYS REQUIRED) ☆`376`
- [kimtaeyoon83/mcp-server-youtube-transcript](https://github.com/kimtaeyoon83/mcp-server-youtube-transcript) — YouTube video transcript downloader ☆`362`
- [eat-pray-ai/yutu](https://github.com/eat-pray-ai/yutu) — A fully functional MCP server and CLI for YouTube ☆`354`
- [VikashLoomba/MCP-Server-Playwright](https://github.com/VikashLoomba/MCP-Server-Playwright) — MCP server for browser automation using Playwright ☆`270`
- [recursechat/mcp-server-apple-shortcuts](https://github.com/recursechat/mcp-server-apple-shortcuts) — Apple Shortcuts automation on macOS ☆`260`
- [eyalzh/browser-control-mcp](https://github.com/eyalzh/browser-control-mcp) — Browser control via extension for AI agents ☆`221`
- [blackwhite084/playwright-plus-python-mcp](https://github.com/blackwhite084/playwright-plus-python-mcp) — Enhanced Playwright browser automation ☆`168`
- [34892002/bilibili-mcp-js](https://github.com/34892002/bilibili-mcp-js) — Bilibili video search MCP service ☆`132`
- [browserstack/mcp-server](https://github.com/browserstack/mcp-server) — BrowserStack's Official MCP Server ☆`114`
- [ndthanhdev/mcp-browser-kit](https://github.com/ndthanhdev/mcp-browser-kit) — AI assistants interact with local browser ☆`45`
- [NON906/omniparser-autogui-mcp](https://github.com/NON906/omniparser-autogui-mcp) — Automatic operation of on-screen GUI. ☆`60`
- [getrupt/ashra-mcp](https://github.com/getrupt/ashra-mcp) — A Model Context Protocol server for Ashra ☆`55`
- [Mtehabsim/ScreenPilot](https://github.com/Mtehabsim/ScreenPilot) — AI device control like a human ☆`50`
- [imprvhub/mcp-browser-agent](https://github.com/imprvhub/mcp-browser-agent) — MCP server for autonomous browser automation with Claude ☆`29`
- [lightpanda-io/gomcp](https://github.com/lightpanda-io/gomcp) — Lightpanda MCP server written in Go ☆`44`
- [onkernel/kernel-mcp-server](https://github.com/onkernel/kernel-mcp-server) — Open-source MCP server for secure, low-latency cloud-browser automation on Kernel. ☆`22`
- [xxxbrian/mcp-rquest](https://github.com/xxxbrian/mcp-rquest) — A MCP server providing realistic browser-like HTTP request capabilities with accurate TLS/JA3/JA4 fingerprints for bypassing anti-bot measures. It also supports converting PDF and HTML documents to Markdown for easier processing by LLMs. ☆`41`
- [freema/firefox-devtools-mcp](https://github.com/freema/firefox-devtools-mcp) — MCP server for Firefox DevTools integration ☆`19`
- [BB-fat/browser-use-rs](https://github.com/BB-fat/browser-use-rs) — Rust-based browser automation MCP server ☆`16`
- [kimtth/mcp-aoai-web-browsing](https://github.com/kimtth/mcp-aoai-web-browsing) — Azure OpenAI with Playwright browser control ☆`31`
## CLI Tools

- [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) — Terminal control, file search, diff editing ☆`5,125`
- [chrishayuk/mcp-cli](https://github.com/chrishayuk/mcp-cli) — Feature-rich CLI for interacting with MCP servers ☆`1,786`
- [rusiaaman/wcgw](https://github.com/rusiaaman/wcgw) — Shell and coding agent on claude desktop app ☆`626`
- [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp) — iTerm command execution for REPL/CLI ☆`504`
- [aymericzip/intlayer](https://github.com/aymericzip/intlayer) — MCP server for Intlayer internationalization ☆`465`
- [baryhuang/mcp-remote-macos-use](https://github.com/baryhuang/mcp-remote-macos-use) — The only general AI agent that does NOT requires extra API key, giving you full control on your local and remote MacOs from Claude Desktop App ☆`432`
- [peakmojo/applescript-mcp](https://github.com/peakmojo/applescript-mcp) — MCP server that execute applescript giving you full control of your Mac ☆`391`
- [wong2/mcp-cli](https://github.com/wong2/mcp-cli) — A CLI inspector for the Model Context Protocol ☆`397`
- [claude-did-this/MCPControl](https://github.com/claude-did-this/MCPControl) — MCP server for Windows OS automation ☆`260`
- [g0t4/mcp-server-commands](https://github.com/g0t4/mcp-server-commands) — Model Context Protocol server to run commands ☆`218`
- [tufantunc/ssh-mcp](https://github.com/tufantunc/ssh-mcp) — SSH control for Linux servers ☆`180`
- [nickgnd/tmux-mcp](https://github.com/nickgnd/tmux-mcp) — A MCP server for our beloved terminal multiplexer tmux. ☆`174`
- [dvcrn/mcp-server-siri-shortcuts](https://github.com/dvcrn/mcp-server-siri-shortcuts) — MCP for calling Siri Shorcuts from LLMs ☆`170`
- [tumf/mcp-shell-server](https://github.com/tumf/mcp-shell-server) — Shell execution with whitelisted commands ☆`156`
- [MladenSU/cli-mcp-server](https://github.com/MladenSU/cli-mcp-server) — CLI with secure execution and custom policies ☆`156`
- [classfang/ssh-mcp-server](https://github.com/classfang/ssh-mcp-server) — 基于 SSH 的 MCP 服务器 。已被MCP官方收录 。 SSH MCP Server . It has been included in the community MCP repository . ☆`109`
- [domdomegg/computer-use-mcp](https://github.com/domdomegg/computer-use-mcp) — Give AI models complete control of your computer (probably a bad idea) ☆`107`
- [AB498/computer-control-mcp](https://github.com/AB498/computer-control-mcp) — MCP server that provides computer control capabilities, like mouse, keyboard, OCR, etc. using PyAutoGUI, RapidOCR, ONNXRuntime. Similar to 'computer-use' by Anthropic. With Zero External Dependencies. ☆`80`
- [GongRzhe/terminal-controller-mcp](https://github.com/GongRzhe/terminal-controller-mcp) — A Model Context Protocol (MCP) server that enables secure terminal command execution, directory navigation, and file system operations through a standardized interface. ☆`93`
- [inercia/MCPShell](https://github.com/inercia/MCPShell) — Use shell scripts as MCP tools ☆`48`
- [automateyournetwork/pyATS_MCP](https://github.com/automateyournetwork/pyATS_MCP) — An MCP Server for pyATS (experimental) ☆`52`
- [sonirico/mcp-shell](https://github.com/sonirico/mcp-shell) — Secure, auditable shell commands for AI ☆`51`
- [NakaokaRei/swift-mcp-gui](https://github.com/NakaokaRei/swift-mcp-gui) — Keyboard and mouse control on macOS ☆`49`
- [maxim-saplin/mcp_safe_local_python_executor](https://github.com/maxim-saplin/mcp_safe_local_python_executor) — Safe Python executor from smolagents ☆`40`
- [PhialsBasement/CMD-MCP-Server](https://github.com/PhialsBasement/CMD-MCP-Server) — CMD command execution for Claude agents ☆`22`
- [erniebrodeur/mcp-grep](https://github.com/erniebrodeur/mcp-grep) — simple mcp server to wrap the local instance of grep. ☆`22`
- [JoshuaRileyDev/mac-apps-launcher](https://github.com/JoshuaRileyDev/mac-apps-launcher) — Launch and manage macOS applications ☆`16`
## CRM & ERP

- [smn2gnt/MCP-Salesforce](https://github.com/smn2gnt/MCP-Salesforce) — MCP Salesforce connector ☆`150`
- [ivnvxd/mcp-server-odoo](https://github.com/ivnvxd/mcp-server-odoo) — MCP server for Odoo ERP integration ☆`121`
- [tsmztech/mcp-server-salesforce](https://github.com/tsmztech/mcp-server-salesforce) — Salesforce MCP Server ☆`115`
- [GeLi2001/shopify-mcp](https://github.com/GeLi2001/shopify-mcp) — MCP server for Shopify api, usable on mcp hosts such as Claude and Cursor ☆`112`
- [augmnt/augments-mcp-server](https://github.com/augmnt/augments-mcp-server) — MCP server for Augments AI platform ☆`92`
- [tomaspavlin/rohlik-mcp](https://github.com/tomaspavlin/rohlik-mcp) — MCP server that lets you shop groceries across the Rohlik Group platforms (Rohlik.cz, Knuspr.de, Gurkerl.at, Kifli.hu, Sezamo.ro) ☆`73`
- [mafzaal/d365fo-client](https://github.com/mafzaal/d365fo-client) — A comprehensive Python client library and MCP server for Microsoft Dynamics 365 Finance & Operations (D365 F&O) that provides easy access to OData endpoints, metadata operations, label management, and AI assistant integration. ☆`19`
- [hmk/attio-mcp-server](https://github.com/hmk/attio-mcp-server) — Attio CRM records and notes management ☆`16`
## Cloud & Infrastructure

- [AiondaDotCom/mcp-ssh](https://github.com/AiondaDotCom/mcp-ssh) — A Model Context Protocol (MCP) server for managing and controlling SSH connections. ☆`36`
### Cloud Platforms

- [apache/apisix](https://github.com/apache/apisix) — The Cloud-Native API Gateway and AI Gateway ☆`16,013`
- [awslabs/mcp](https://github.com/awslabs/mcp) — AWS MCP servers for AI assistants ☆`7,718`
- [GreptimeTeam/greptimedb](https://github.com/GreptimeTeam/greptimedb) — Unified observability DB for metrics, logs, traces ☆`5,839`
- [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) — Cloudflare services management ☆`3,220`
- [microsoft/azure-devops-mcp](https://github.com/microsoft/azure-devops-mcp) — Azure DevOps integration for AI agents ☆`1,104`
- [TencentCloudBase/CloudBase-AI-ToolKit](https://github.com/TencentCloudBase/CloudBase-AI-ToolKit) — CloudBase MCP - Connect CloudBase to your AI Agent. Go from AI prompt to live app in one click. ☆`904`
- [GoogleCloudPlatform/cloud-run-mcp](https://github.com/GoogleCloudPlatform/cloud-run-mcp) — MCP server to deploy apps to Cloud Run ☆`494`
- [alexei-led/aws-mcp-server](https://github.com/alexei-led/aws-mcp-server) — AWS CLI in containerized environment ☆`168`
- [babelcloud/gbox](https://github.com/babelcloud/gbox) — AI control for Android, browser, desktop ☆`157`
- [aarora79/aws-cost-explorer-mcp-server](https://github.com/aarora79/aws-cost-explorer-mcp-server) — MCP server for understanding AWS spend ☆`128`
- [rishikavikondala/mcp-server-aws](https://github.com/rishikavikondala/mcp-server-aws) — A Model Context Protocol server implementation for operations on AWS resources ☆`127`
- [aliyun/alibaba-cloud-ops-mcp-server](https://github.com/aliyun/alibaba-cloud-ops-mcp-server) — AlibabaCloud CloudOps MCP Server ☆`88`
- [heroku/heroku-mcp-server](https://github.com/heroku/heroku-mcp-server) — Heroku Platform MCP Server using the Heroku CLI ☆`74`
- [vantage-sh/vantage-mcp-server](https://github.com/vantage-sh/vantage-mcp-server) — MCP Server to fetch costs and usage data from your Vantage account. ☆`76`
- [aws-powertools/powertools-mcp](https://github.com/aws-powertools/powertools-mcp) — Powertools for AWS's official MCP Server ☆`40`
- [kenliao94/mcp-server-rabbitmq](https://github.com/kenliao94/mcp-server-rabbitmq) — MCP server for interacting with RabbitMQ ☆`40`
- [dkruyt/mcp-hetzner](https://github.com/dkruyt/mcp-hetzner) — Hetzner Cloud management ☆`58`
- [aliyun/alibabacloud-devops-mcp-server](https://github.com/aliyun/alibabacloud-devops-mcp-server) — MCP server for Alibaba Yunxiao DevOps platform ☆`35`
- [qiniu/qiniu-mcp-server](https://github.com/qiniu/qiniu-mcp-server) — Qiniu Cloud storage, CDN, and media processing ☆`32`
- [aliyun/alibabacloud-dataworks-mcp-server](https://github.com/aliyun/alibabacloud-dataworks-mcp-server) — Alibaba Cloud DataWorks API integration ☆`25`
- [aantti/mcp-netbird](https://github.com/aantti/mcp-netbird) — Netbird network management ☆`41`
- [redis/mcp-redis-cloud](https://github.com/redis/mcp-redis-cloud) — MCP server for Redis Cloud database operations ☆`38`
- [Azure-Samples/mcp](https://github.com/Azure-Samples/mcp) — Links to samples, tools, and resources for building and integrating Model Context Protocol (MCP) servers on Azure using multiple languages ☆`40`
- [localstack/localstack-mcp-server](https://github.com/localstack/localstack-mcp-server) — LocalStack AWS emulation ☆`16`
- [kestra-io/mcp-server-python](https://github.com/kestra-io/mcp-server-python) — Python MCP for Kestra AI Agents ☆`16`
- [api7/apisix-mcp](https://github.com/api7/apisix-mcp) — APISIX gateway for LLM integration ☆`29`
- [baryhuang/mcp-server-aws-resources-python](https://github.com/baryhuang/mcp-server-aws-resources-python) — A Python-based MCP server that lets Claude run boto3 code to query and manage AWS resources. Execute powerful AWS operations directly through Claude with proper sandboxing and containerization. No need for complex setups - just pass your AWS credentials and start interacting with all AWS services. ☆`22`
- [aliyun/alibabacloud-hologres-mcp-server](https://github.com/aliyun/alibabacloud-hologres-mcp-server) — MCP server for Alibaba Hologres data warehouse ☆`25`
- [trilogy-group/aws-pricing-mcp](https://github.com/trilogy-group/aws-pricing-mcp) — AWS EC2 pricing search by CPU, RAM, network ☆`17`
- [higress-group/higress-ops-mcp-server](https://github.com/higress-group/higress-ops-mcp-server) — Higress API gateway configuration management ☆`22`
### Kubernetes

- [Flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) — MCP Server for kubernetes management commands ☆`1,229`
- [containers/kubernetes-mcp-server](https://github.com/containers/kubernetes-mcp-server) — Kubernetes and OpenShift management ☆`911`
- [weibaohui/k8m](https://github.com/weibaohui/k8m) — Mini Kubernetes AI Dashboard ☆`744`
- [rohitg00/kubectl-mcp-server](https://github.com/rohitg00/kubectl-mcp-server) — Kubernetes cluster chat with Claude/Cursor ☆`747`
- [strowk/mcp-k8s-go](https://github.com/strowk/mcp-k8s-go) — Go-based Kubernetes connection ☆`367`
- [vfarcic/dot-ai](https://github.com/vfarcic/dot-ai) — Intelligent dual-mode agent for deploying applications to ANY Kubernetes cluster through dynamic discovery and plain English governance ☆`251`
- [alexei-led/k8s-mcp-server](https://github.com/alexei-led/k8s-mcp-server) — Kubernetes cluster management ☆`178`
- [weibaohui/kom](https://github.com/weibaohui/kom) — Kubernetes SDK wrapping kubectl ☆`138`
- [silenceper/mcp-k8s](https://github.com/silenceper/mcp-k8s) — Kubernetes cluster interaction ☆`131`
- [reza-gholizade/k8s-mcp-server](https://github.com/reza-gholizade/k8s-mcp-server) — Kubernetes cluster management ☆`128`
- [portainer/portainer-mcp](https://github.com/portainer/portainer-mcp) — Portainer container management ☆`96`
- [StacklokLabs/mkp](https://github.com/StacklokLabs/mkp) — MKP Kubernetes MCP server ☆`55`
- [cyclops-ui/mcp-cyclops](https://github.com/cyclops-ui/mcp-cyclops) — Cyclops Kubernetes management ☆`29`
- [wenhuwang/mcp-k8s-eye](https://github.com/wenhuwang/mcp-k8s-eye) — Kubernetes diagnosis and management ☆`26`
### Virtualization & IaC

- [hashicorp/terraform-mcp-server](https://github.com/hashicorp/terraform-mcp-server) — The Terraform MCP Server provides seamless integration with Terraform ecosystem, enabling advanced automation and interaction capabilities for Infrastructure as Code (IaC) development. ☆`1,105`
- [nwiizo/tfmcp](https://github.com/nwiizo/tfmcp) — Terraform AI-assisted infrastructure ☆`347`
- [1Panel-dev/mcp-1panel](https://github.com/1Panel-dev/mcp-1panel) — mcp-1panel is an implementation of the Model Context Protocol (MCP) server for 1Panel. ☆`143`
- [kocierik/mcp-nomad](https://github.com/kocierik/mcp-nomad) — A nomad MCP Server (modelcontextprotocol) ☆`40`
- [bright8192/esxi-mcp-server](https://github.com/bright8192/esxi-mcp-server) — MCP server for VMware ESXi management ☆`51`
- [jokemanfire/mcp-containerd](https://github.com/jokemanfire/mcp-containerd) — Use mcp to manage containerd(developing) ☆`50`
- [severity1/terraform-cloud-mcp](https://github.com/severity1/terraform-cloud-mcp) — A Model Context Protocol (MCP) server that integrates AI assistants with the Terraform Cloud API, allowing you to manage your infrastructure through natural conversation ☆`20`
- [openstack-kr/python-openstackmcp-server](https://github.com/openstack-kr/python-openstackmcp-server) — openstack mcp server ☆`17`
## Communication & Messaging

- [elie222/inbox-zero](https://github.com/elie222/inbox-zero) — AI email assistant for inbox zero ☆`9,627`
- [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) — WhatsApp MCP server ☆`5,164`
- [korotovsky/slack-mcp-server](https://github.com/korotovsky/slack-mcp-server) — MCP server for Slack workspace integration ☆`1,031`
- [mattt/iMCP](https://github.com/mattt/iMCP) — A macOS app that provides an MCP server to your Messages, Contacts, Reminders and more ☆`977`
- [chigwell/telegram-mcp](https://github.com/chigwell/telegram-mcp) — MCP server for Telegram messaging ☆`509`
- [line/line-bot-mcp-server](https://github.com/line/line-bot-mcp-server) — LINE Messaging API for AI agents ☆`505`
- [joinly-ai/joinly](https://github.com/joinly-ai/joinly) — Make your meetings accessible to AI Agents ☆`415`
- [Softeria/ms-365-mcp-server](https://github.com/Softeria/ms-365-mcp-server) — Microsoft 365 and Office via Graph API ☆`371`
- [InditexTech/mcp-teams-server](https://github.com/InditexTech/mcp-teams-server) — MCP server for Microsoft Teams integration ☆`340`
- [chaindead/telegram-mcp](https://github.com/chaindead/telegram-mcp) — Telegram dialogs, messages, drafts, statuses ☆`257`
- [carterlasalle/mac_messages_mcp](https://github.com/carterlasalle/mac_messages_mcp) — MCP server for secure iMessage database access on macOS ☆`206`
- [v-3/discordmcp](https://github.com/v-3/discordmcp) — Discord MCP Server for Claude Integration ☆`161`
- [SaseQ/discord-mcp](https://github.com/SaseQ/discord-mcp) — MCP server for Discord integration ☆`140`
- [ZilongXue/claude-post](https://github.com/ZilongXue/claude-post) — ClaudePost enables seamless email management through natural language conversations with Claude, offering secure features like email search, reading, and sending. ☆`109`
- [ztxtxwd/open-feishu-mcp-server](https://github.com/ztxtxwd/open-feishu-mcp-server) — Feishu/Lark OAuth and document management ☆`70`
- [areweai/tsgram-mcp](https://github.com/areweai/tsgram-mcp) — Telegram for local Claude Code debug ☆`86`
- [hannesrudolph/imessage-query-fastmcp-mcp-server](https://github.com/hannesrudolph/imessage-query-fastmcp-mcp-server) — Safe iMessage database queries ☆`72`
- [mailtrap/mailtrap-mcp](https://github.com/mailtrap/mailtrap-mcp) — Official mailtrap.io MCP server ☆`51`
- [RapidataAI/human-use](https://github.com/RapidataAI/human-use) — Enable AI to ask anyone anything ☆`68`
- [Shy2593666979/mcp-server-email](https://github.com/Shy2593666979/mcp-server-email) — Email with attachments for Gmail, Outlook, QQ ☆`66`
- [gitmotion/ntfy-me-mcp](https://github.com/gitmotion/ntfy-me-mcp) — MCP server for ntfy push notifications ☆`46`
- [MadLlama25/fastmail-mcp](https://github.com/MadLlama25/fastmail-mcp) — A Model Context Protocol (MCP) server that provides access to the Fastmail API, enabling AI assistants to interact with email, contacts, and calendar data. Includes a DXT (desktop extension) for Claude Desktop. ☆`48`
- [sawa-zen/vrchat-mcp](https://github.com/sawa-zen/vrchat-mcp) — VRChat API interaction ☆`49`
- [discourse/discourse-mcp](https://github.com/discourse/discourse-mcp) — MCP client for Discourse sites ☆`30`
- [Cactusinhand/mcp_server_notify](https://github.com/Cactusinhand/mcp_server_notify) — Send system notification when Agent task is done. ☆`42`
- [teddyzxcv/ntfy-mcp](https://github.com/teddyzxcv/ntfy-mcp) — MCP server for ntfy push notifications ☆`43`
- [aahl/mcp-notify](https://github.com/aahl/mcp-notify) — MCP Server for notify to Weixin, Telegram, Bark, Lark, 飞书, 钉钉 ☆`22`
- [infobip/mcp](https://github.com/infobip/mcp) — Infobip Remote MCP Servers Documentation ☆`22`
- [mailgun/mailgun-mcp-server](https://github.com/mailgun/mailgun-mcp-server) — Mailgun API integration ☆`39`
- [mjknowles/matrix-mcp-server](https://github.com/mjknowles/matrix-mcp-server) — MCP Server for a Matrix home server integration; chat, manage rooms, etc. ☆`27`
- [gotoolkits/mcp-wecombot-server](https://github.com/gotoolkits/mcp-wecombot-server) — WeCom group robot message sending ☆`32`
- [AshikNesin/pushover-mcp](https://github.com/AshikNesin/pushover-mcp) — A MCP implementation for sending notifications via Pushover ☆`30`
- [jagan-shanmugam/mattermost-mcp-host](https://github.com/jagan-shanmugam/mattermost-mcp-host) — Mattermost integration with LangGraph agent ☆`28`
- [DLHellMe/telegram-mcp-server](https://github.com/DLHellMe/telegram-mcp-server) — Powerfull Telegram MCP for Claude Desktop to scrape and analyze Telegram content. ☆`25`
- [egyptianego17/email-mcp-server](https://github.com/egyptianego17/email-mcp-server) — A simple mcp server that lets your AI agent send emails and attach files through SMTP. ☆`25`
- [wyattjoh/imessage-mcp](https://github.com/wyattjoh/imessage-mcp) — iMessage data reading from macOS ☆`18`
## Data & Analytics

- [antvis/mcp-server-chart](https://github.com/antvis/mcp-server-chart) — 25+ visual charts using @antvis for data analysis ☆`3,364`
- [haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server) — Excel file manipulation ☆`3,024`
- [zcaceres/markdownify-mcp](https://github.com/zcaceres/markdownify-mcp) — Convert almost anything to Markdown ☆`2,320`
- [datalayer/jupyter-mcp-server](https://github.com/datalayer/jupyter-mcp-server) — Model Context Protocol (MCP) Server for Jupyter. ☆`829`
- [MigoXLab/dingo](https://github.com/MigoXLab/dingo) — AI data, model, app quality evaluation ☆`602`
- [reading-plus-ai/mcp-server-data-exploration](https://github.com/reading-plus-ai/mcp-server-data-exploration) — Interactive CSV data exploration ☆`516`
- [dbt-labs/dbt-mcp](https://github.com/dbt-labs/dbt-mcp) — A MCP (Model Context Protocol) server for interacting with dbt. ☆`445`
- [hustcc/mcp-echarts](https://github.com/hustcc/mcp-echarts) — ECharts visual charts with AI ☆`175`
- [GongRzhe/Quickchart-MCP-Server](https://github.com/GongRzhe/Quickchart-MCP-Server) — A Model Context Protocol server for generating charts using QuickChart.io . It allows you to create various types of charts through MCP tools. ☆`157`
- [kubeflow/mcp-apache-spark-history-server](https://github.com/kubeflow/mcp-apache-spark-history-server) — MCP Server for Apache Spark History Server. The bridge between Agentic AI and Apache Spark. ☆`117`
- [jjsantos01/jupyter-notebook-mcp](https://github.com/jjsantos01/jupyter-notebook-mcp) — A Model Context Protocol (MCP) for Jupyter Notebook ☆`113`
- [microsoft/fabric-rti-mcp](https://github.com/microsoft/fabric-rti-mcp) — MCP server for Fabric Real-Time Intelligence (https://aka.ms/fabricrti) supporting tools for Eventhouse (https://aka.ms/eventhouse), Azure Data Explorer (https://aka.ms/adx, and other RTI services (coming soon) ☆`80`
- [ChronulusAI/chronulus-mcp](https://github.com/ChronulusAI/chronulus-mcp) — Chronulus AI forecasting and prediction agents ☆`102`
- [keboola/mcp-server](https://github.com/keboola/mcp-server) — Model Context Protocol (MCP) Server for the Keboola Platform ☆`80`
- [isaacwasserman/mcp-vegalite-server](https://github.com/isaacwasserman/mcp-vegalite-server) — MCP server for Vega-Lite data visualization ☆`94`
- [optuna/optuna-mcp](https://github.com/optuna/optuna-mcp) — Optuna hyperparameter optimization ☆`67`
- [acryldata/mcp-server-datahub](https://github.com/acryldata/mcp-server-datahub) — The official Model Context Protocol (MCP) server for DataHub (https://datahub.com) ☆`65`
- [kdqed/zaturn](https://github.com/kdqed/zaturn) — Data Analysis With Vibes ☆`69`
- [GongRzhe/JSON-MCP-Server](https://github.com/GongRzhe/JSON-MCP-Server) — JSON handling and processing mcp server ☆`85`
- [JordiNeil/mcp-databricks-server](https://github.com/JordiNeil/mcp-databricks-server) — MCP Server for Databricks ☆`45`
- [anshumax/world_bank_mcp_server](https://github.com/anshumax/world_bank_mcp_server) — An implementation of the Model Context Protocol for the World Bank open data API ☆`42`
- [aywengo/kafka-schema-reg-mcp](https://github.com/aywengo/kafka-schema-reg-mcp) — Kafka Schema Registry management ☆`27`
- [Unstructured-IO/UNS-MCP](https://github.com/Unstructured-IO/UNS-MCP) — MCP server for Unstructured document processing ☆`38`
- [kumo-ai/kumo-rfm-mcp](https://github.com/kumo-ai/kumo-rfm-mcp) — MCP server to query KumoRFM in your agentic flows ☆`26`
- [thoughtspot/mcp-server](https://github.com/thoughtspot/mcp-server) — The ThoughtSpot MCP Server ☆`22`
- [phisanti/MCPR](https://github.com/phisanti/MCPR) — AI agents in interactive R sessions ☆`20`
- [explorium-ai/mcp-explorium](https://github.com/explorium-ai/mcp-explorium) — Explorium B2B Data - MCP Server ☆`19`
- [growthbook/growthbook-mcp](https://github.com/growthbook/growthbook-mcp) — GrowthBook flags and experiments ☆`16`
- [YangLiangwei/PersonalizationMCP](https://github.com/YangLiangwei/PersonalizationMCP) — Personal data hub for AI from Steam, YouTube, Bilibili ☆`33`
- [arrismo/kaggle-mcp](https://github.com/arrismo/kaggle-mcp) — MCP server for Kaggle ☆`32`
- [palewire/datawrapper-mcp](https://github.com/palewire/datawrapper-mcp) — A Model Context Protocol (MCP) server for creating Datawrapper charts using AI assistants. ☆`17`
- [RafaelCartenet/mcp-databricks-server](https://github.com/RafaelCartenet/mcp-databricks-server) — Model Context Protocol (MCP) server for Databricks that empowers AI agents to autonomously interact with Unity Catalog metadata. Enables data discovery, lineage analysis, and intelligent SQL execution. Agents explore catalogs/schemas/tables, understand relationships, discover notebooks/jobs, and execute queries - greatly reducing ad-hoc query time. ☆`30`
- [privetin/dataset-viewer](https://github.com/privetin/dataset-viewer) — MCP server for Hugging Face dataset viewer ☆`30`
- [mattijsdp/dbt-docs-mcp](https://github.com/mattijsdp/dbt-docs-mcp) — dbt documentation interaction ☆`21`
- [HumanSignal/label-studio-mcp-server](https://github.com/HumanSignal/label-studio-mcp-server) — MCP server for Label Studio data labeling ☆`25`
- [subelsky/bundler_mcp](https://github.com/subelsky/bundler_mcp) — MCP server for Ruby Bundler integration ☆`19`
- [syucream/lightdash-mcp-server](https://github.com/syucream/lightdash-mcp-server) — A MCP(Model Context Protocol) server that accesses to Lightdash ☆`22`
## Databases

- [datastrato/mcp-server-gravitino](https://github.com/datastrato/mcp-server-gravitino) — MCP server for Apache Gravitino ☆`19`
### Analytics & Warehouses

- [ClickHouse/mcp-clickhouse](https://github.com/ClickHouse/mcp-clickhouse) — Connect ClickHouse to your AI assistants. ☆`628`
- [elastic/mcp-server-elasticsearch](https://github.com/elastic/mcp-server-elasticsearch) —  ☆`578`
- [motherduckdb/mcp-server-motherduck](https://github.com/motherduckdb/mcp-server-motherduck) — MCP server for DuckDB and MotherDuck ☆`384`
- [Snowflake-Labs/mcp](https://github.com/Snowflake-Labs/mcp) — Snowflake Cortex AI and SQL orchestration ☆`197`
- [isaacwasserman/mcp-snowflake-server](https://github.com/isaacwasserman/mcp-snowflake-server) — MCP server for Snowflake database queries ☆`170`
- [ktanaka101/mcp-server-duckdb](https://github.com/ktanaka101/mcp-server-duckdb) — DuckDB database interaction ☆`173`
- [ergut/mcp-bigquery-server](https://github.com/ergut/mcp-bigquery-server) — MCP server for Google BigQuery integration ☆`130`
- [LucasHild/mcp-server-bigquery](https://github.com/LucasHild/mcp-server-bigquery) — Google BigQuery database access ☆`120`
- [opensearch-project/opensearch-mcp-server-py](https://github.com/opensearch-project/opensearch-mcp-server-py) —  ☆`84`
- [pab1it0/adx-mcp-server](https://github.com/pab1it0/adx-mcp-server) — MCP server for Azure Data Explorer ☆`50`
- [lishenxydlgzs/aws-athena-mcp](https://github.com/lishenxydlgzs/aws-athena-mcp) — MCP server to run AWS Athena queries ☆`41`
- [aliyun/alibabacloud-adb-mysql-mcp-server](https://github.com/aliyun/alibabacloud-adb-mysql-mcp-server) — AnalyticDB for MySQL MCP Server ☆`19`
### Cache & Key-Value

- [redis/mcp-redis](https://github.com/redis/mcp-redis) — MCP server for Redis database operations ☆`371`
- [aliyun/alibabacloud-tablestore-mcp-server](https://github.com/aliyun/alibabacloud-tablestore-mcp-server) — MCP server for Alibaba Tablestore NoSQL ☆`150`
- [upstash/mcp-server](https://github.com/upstash/mcp-server) — Upstash Model Context Server ☆`49`
- [GongRzhe/REDIS-MCP-Server](https://github.com/GongRzhe/REDIS-MCP-Server) — A Redis MCP server (pushed to https://github.com/modelcontextprotocol/servers/tree/main/src/redis) implementation for interacting with Redis databases. This server enables LLMs to interact with Redis key-value stores through a set of standardized tools. ☆`28`
### Cloud Platforms

- [instantdb/instant](https://github.com/instantdb/instant) — Modern Firebase with real-time database ☆`9,541`
- [supabase-community/supabase-mcp](https://github.com/supabase-community/supabase-mcp) — Connect Supabase to your AI assistants ☆`2,346`
- [alexander-zuev/supabase-mcp-server](https://github.com/alexander-zuev/supabase-mcp-server) — MCP server for Supabase database and auth ☆`815`
- [neondatabase/mcp-server-neon](https://github.com/neondatabase/mcp-server-neon) — Neon Management API and databases ☆`531`
- [gannonh/firebase-mcp](https://github.com/gannonh/firebase-mcp) — Model Context Protocol (MCP) server for Firebase. ☆`231`
- [JoshuaRileyDev/supabase-mcp-server](https://github.com/JoshuaRileyDev/supabase-mcp-server) — MCP server for Supabase database operations ☆`50`
- [niledatabase/nile-mcp-server](https://github.com/niledatabase/nile-mcp-server) — Nile Database tenants, users, auth for LLMs ☆`16`
### Graph Databases

- [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j) — Neo4j Labs Model Context Protocol servers ☆`856`
- [neo4j-contrib/gds-agent](https://github.com/neo4j-contrib/gds-agent) — MCP Server with tools from Neo4j GDS(Graph Data Science) library. ☆`64`
- [da-okazaki/mcp-neo4j-server](https://github.com/da-okazaki/mcp-neo4j-server) — mcp-neo4j-server ☆`56`
- [ravenwits/mcp-server-arangodb](https://github.com/ravenwits/mcp-server-arangodb) — This is a TypeScript-based MCP server that provides database interaction capabilities through ArangoDB. It implements core database operations and allows seamless integration with ArangoDB through MCP tools. You can use it wih Claude app and also extension for VSCode that works with mcp like Cline! ☆`42`
- [FalkorDB/FalkorDB-MCPServer](https://github.com/FalkorDB/FalkorDB-MCPServer) — FalkorDB-MCPServer is an MCP (Model Context Protocol) server that connects LLMs to FalkorDB ☆`24`
### Multi-Database Tools

- [googleapis/genai-toolbox](https://github.com/googleapis/genai-toolbox) — Open source database MCP toolbox ☆`11,949`
- [bytebase/dbhub](https://github.com/bytebase/dbhub) — Token-efficient multi-database MCP ☆`1,786`
- [damms005/devdb-vscode](https://github.com/damms005/devdb-vscode) — A zero-config VS Code database extension with affordances to aid development and debugging. ☆`1,208`
- [Canner/wren-engine](https://github.com/Canner/wren-engine) — Semantic engine for MCP clients and AI ☆`518`
- [centralmind/gateway](https://github.com/centralmind/gateway) — Universal database MCP for LLMs ☆`506`
- [runekaagaard/mcp-alchemy](https://github.com/runekaagaard/mcp-alchemy) — MCP server for SQLAlchemy database operations ☆`379`
- [FreePeak/db-mcp-server](https://github.com/FreePeak/db-mcp-server) — MCP server for database operations ☆`325`
- [executeautomation/mcp-database-server](https://github.com/executeautomation/mcp-database-server) — MCP Database Server is a new MCP Server which helps connect with Sqlite, SqlServer and Posgresql Databases ☆`271`
- [XGenerationLab/xiyan_mcp_server](https://github.com/XGenerationLab/xiyan_mcp_server) — Natural language database queries ☆`225`
- [prisma/mcp](https://github.com/prisma/mcp) — Prisma database workflows ☆`31`
- [s2-streamstore/s2-sdk-typescript](https://github.com/s2-streamstore/s2-sdk-typescript) — S2 SDK for TypeScript ☆`21`
- [GibsonAI/mcp](https://github.com/GibsonAI/mcp) — GibsonAI's MCP server ☆`31`
- [fireproof-storage/mcp-database-server](https://github.com/fireproof-storage/mcp-database-server) — Store and load JSON documents from LLM tool use ☆`29`
### NoSQL & Document

- [mongodb-js/mongodb-mcp-server](https://github.com/mongodb-js/mongodb-mcp-server) — A Model Context Protocol server to connect to MongoDB databases and MongoDB Atlas Clusters. ☆`866`
- [kiliczsh/mcp-mongo-server](https://github.com/kiliczsh/mcp-mongo-server) — A Model Context Protocol Server for MongoDB ☆`269`
- [cr7258/elasticsearch-mcp-server](https://github.com/cr7258/elasticsearch-mcp-server) — Elasticsearch and OpenSearch interaction ☆`232`
- [furey/mongodb-lens](https://github.com/furey/mongodb-lens) — MongoDB Lens: Full Featured MCP Server for MongoDB Databases ☆`195`
- [QuantGeekDev/mongo-mcp](https://github.com/QuantGeekDev/mongo-mcp) — A mongo db server for the model context protocol (MCP) ☆`174`
- [datastax/astra-db-mcp](https://github.com/datastax/astra-db-mcp) — An MCP server for Astra DB workloads ☆`38`
- [Couchbase-Ecosystem/mcp-server-couchbase](https://github.com/Couchbase-Ecosystem/mcp-server-couchbase) — Couchbase database cluster integration ☆`25`
### SQL Databases

- [crystaldba/postgres-mcp](https://github.com/crystaldba/postgres-mcp) — Postgres with read/write access and performance ☆`1,705`
- [designcomputer/mysql_mcp_server](https://github.com/designcomputer/mysql_mcp_server) — Secure MySQL database interaction ☆`1,042`
- [benborla/mcp-server-mysql](https://github.com/benborla/mcp-server-mysql) — MCP server for MySQL database operations ☆`1,009`
- [subnetmarco/pgmcp](https://github.com/subnetmarco/pgmcp) — An MCP server to query any Postgres database in natural language. ☆`516`
- [wenb1n-dev/mysql_mcp_server_pro](https://github.com/wenb1n-dev/mysql_mcp_server_pro) — Enhanced MySQL with anomaly analysis ☆`284`
- [apache/doris-mcp-server](https://github.com/apache/doris-mcp-server) — Apache Doris MCP Server ☆`234`
- [StarRocks/mcp-server-starrocks](https://github.com/StarRocks/mcp-server-starrocks) — StarRocks MCP (Model Context Protocol) Server ☆`136`
- [f4ww4z/mcp-mysql-server](https://github.com/f4ww4z/mcp-mysql-server) — A Model Context Protocol server for MySQL database operations ☆`137`
- [call518/MCP-PostgreSQL-Ops](https://github.com/call518/MCP-PostgreSQL-Ops) — Professional MCP server for PostgreSQL operations & monitoring: 30+ extension-independent tools for performance analysis, table bloat detection, autovacuum monitoring, schema introspection, and database management. Supports PostgreSQL 12-17. ☆`130`
- [MariaDB/mcp](https://github.com/MariaDB/mcp) — MariaDB MCP (Model Context Protocol) server implementation ☆`109`
- [wenb1n-dev/SmartDB_MCP](https://github.com/wenb1n-dev/SmartDB_MCP) — Universal database MCP for MySQL, PostgreSQL, Oracle and more ☆`110`
- [oceanbase/awesome-oceanbase-mcp](https://github.com/oceanbase/awesome-oceanbase-mcp) — MCP Server for OceanBase database and its tools ☆`87`
- [tuannvm/mcp-trino](https://github.com/tuannvm/mcp-trino) — High-performance Trino MCP in Go ☆`86`
- [hannesrudolph/sqlite-explorer-fastmcp-mcp-server](https://github.com/hannesrudolph/sqlite-explorer-fastmcp-mcp-server) — Read-only SQLite database access ☆`97`
- [donghao1393/mcp-dbutils](https://github.com/donghao1393/mcp-dbutils) — Multi-database connector for SQLite, MySQL, PostgreSQL ☆`86`
- [jparkerweb/mcp-sqlite](https://github.com/jparkerweb/mcp-sqlite) — Comprehensive SQLite interaction ☆`73`
- [Teradata/teradata-mcp-server](https://github.com/Teradata/teradata-mcp-server) — Teradata database integration ☆`35`
- [Zhwt/go-mcp-mysql](https://github.com/Zhwt/go-mcp-mysql) — Go-based MCP server for MySQL ☆`48`
- [pingcap/pytidb](https://github.com/pingcap/pytidb) — TiDB AI SDK: Unified Multi-Modal Data Platform for AI Apps & Agents - https://pingcap.github.io/ai/ ☆`29`
- [singlestore-labs/mcp-server-singlestore](https://github.com/singlestore-labs/mcp-server-singlestore) — SingleStore database management API ☆`26`
- [aliyun/alibabacloud-rds-openapi-mcp-server](https://github.com/aliyun/alibabacloud-rds-openapi-mcp-server) — MCP server for RDS Services via OPENAPI. ☆`40`
- [panasenco/mcp-sqlite](https://github.com/panasenco/mcp-sqlite) — SQLite with Datasette metadata support ☆`16`
- [ahmedmustahid/postgres-mcp-server](https://github.com/ahmedmustahid/postgres-mcp-server) — MCP (Model Context Protocol) Server for postgres Database ☆`24`
- [ydb-platform/ydb-mcp](https://github.com/ydb-platform/ydb-mcp) — MCP server for YDB distributed database ☆`24`
- [c4pt0r/mcp-server-tidb](https://github.com/c4pt0r/mcp-server-tidb) — mcp server for tidb ☆`22`
- [OpenLinkSoftware/mcp-sqlalchemy-server](https://github.com/OpenLinkSoftware/mcp-sqlalchemy-server) — ODBC server with FastAPI and SQLAlchemy ☆`19`
- [abel9851/mcp-server-mariadb](https://github.com/abel9851/mcp-server-mariadb) — An mcp server that provides read-only access to MariaDB. ☆`19`
- [Dataring-engineering/mcp-server-trino](https://github.com/Dataring-engineering/mcp-server-trino) — MCP Server for Trino ☆`18`
- [Xexr/mcp-libsql](https://github.com/Xexr/mcp-libsql) — MCP server for libSQL database ☆`16`
### Spreadsheets & No-Code

- [baserow/baserow](https://github.com/baserow/baserow) — No-code database, apps, agents with AI ☆`3,605`
- [xing5/mcp-google-sheets](https://github.com/xing5/mcp-google-sheets) — Google Drive and Sheets integration ☆`569`
- [domdomegg/airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server) — Airtable bases integration for AI systems ☆`373`
- [rashidazarang/airtable-mcp](https://github.com/rashidazarang/airtable-mcp) — Airtable integration for AI applications ☆`59`
- [felores/airtable-mcp](https://github.com/felores/airtable-mcp) — Search, create and update Airtable bases, tables, fields, and records using Claude Desktop and MCP (Model Context Protocol) clients ☆`69`
- [edwinbernadus/nocodb-mcp-server](https://github.com/edwinbernadus/nocodb-mcp-server) — nocodb mcp server ☆`55`
- [freema/mcp-gsheets](https://github.com/freema/mcp-gsheets) — Google Sheets read, write, manipulate ☆`39`
### Streaming & Messaging

- [confluentinc/mcp-confluent](https://github.com/confluentinc/mcp-confluent) — MCP server for Confluent Kafka platform ☆`123`
- [tuannvm/kafka-mcp-server](https://github.com/tuannvm/kafka-mcp-server) — A Model Context Protocol (MCP) server for Apache Kafka implemented in Go, leveraging franz-go and mcp-go. ☆`39`
### Time-Series & Metrics

- [pab1it0/prometheus-mcp-server](https://github.com/pab1it0/prometheus-mcp-server) — MCP server for Prometheus metrics ☆`324`
- [VictoriaMetrics-Community/mcp-victorialogs](https://github.com/VictoriaMetrics-Community/mcp-victorialogs) — VictoriaLogs log management integration ☆`40`
- [idoru/influxdb-mcp-server](https://github.com/idoru/influxdb-mcp-server) — An MCP Server for querying InfluxDB ☆`28`
- [GreptimeTeam/greptimedb-mcp-server](https://github.com/GreptimeTeam/greptimedb-mcp-server) — A Model Context Protocol (MCP) server for GreptimeDB ☆`23`
- [influxdata/influxdb3_mcp_server](https://github.com/influxdata/influxdb3_mcp_server) — MCP Server for InfluxDB 3 ☆`23`
- [apache/iotdb-mcp-server](https://github.com/apache/iotdb-mcp-server) — Apache IoTDB MCP Server ☆`31`
### Vector Databases

- [qdrant/mcp-server-qdrant](https://github.com/qdrant/mcp-server-qdrant) — Official Qdrant vector database MCP ☆`1,144`
- [chroma-core/chroma-mcp](https://github.com/chroma-core/chroma-mcp) — Chroma vector database capabilities ☆`448`
- [zilliztech/mcp-server-milvus](https://github.com/zilliztech/mcp-server-milvus) — Model Context Protocol Servers for Milvus ☆`206`
- [weaviate/mcp-server-weaviate](https://github.com/weaviate/mcp-server-weaviate) — MCP (Model Context Protocol) server for Weaviate ☆`160`
- [pinecone-io/pinecone-mcp](https://github.com/pinecone-io/pinecone-mcp) — Connect your Pinecone projects to Cursor, Claude, and other AI assistants ☆`48`
- [privetin/chroma](https://github.com/privetin/chroma) — MCP server for Chroma ☆`39`
## Developer Tools

### API Tools

- [tadata-org/fastapi_mcp](https://github.com/tadata-org/fastapi_mcp) — Expose your FastAPI endpoints as Model Context Protocol (MCP) tools, with Auth! ☆`11,300`
- [janwilmake/openapi-mcp-server](https://github.com/janwilmake/openapi-mcp-server) — Complex OpenAPI exploration with plain language ☆`865`
- [zcaceres/fetch-mcp](https://github.com/zcaceres/fetch-mcp) — A flexible HTTP fetching Model Context Protocol server. ☆`658`
- [automation-ai-labs/mcp-link](https://github.com/automation-ai-labs/mcp-link) — Convert Any OpenAPI V3 API to MCP Server ☆`586`
- [WordPress/mcp-adapter](https://github.com/WordPress/mcp-adapter) — An MCP adapter that bridges the Abilities API to the Model Context Protocol, enabling MCP clients to discover and invoke WordPress plugin, theme, and core abilities programmatically. ☆`396`
- [blurrah/mcp-graphql](https://github.com/blurrah/mcp-graphql) — Model Context Protocol server for GraphQL ☆`340`
- [apollographql/apollo-mcp-server](https://github.com/apollographql/apollo-mcp-server) — Apollo MCP Server ☆`240`
- [delano/postman-mcp-server](https://github.com/delano/postman-mcp-server) — An MCP server that provides access to Postman. ☆`143`
- [postmanlabs/postman-mcp-server](https://github.com/postmanlabs/postman-mcp-server) — Connect your AI to your APIs on Postman ☆`126`
- [MFYDev/ghost-mcp](https://github.com/MFYDev/ghost-mcp) — A Model Context Protocol (MCP) server for interacting with Ghost CMS through LLM interfaces like Claude. Allow you to control your Ghost blog by simply asking Claude etc. ☆`121`
- [webflow/mcp-server](https://github.com/webflow/mcp-server) — Model Context Protocol (MCP) server for the Webflow Data API. ☆`93`
- [twilio-labs/mcp](https://github.com/twilio-labs/mcp) — OpenAPI to MCP tools and Twilio APIs ☆`76`
- [shannonlal/mcp-postman](https://github.com/shannonlal/mcp-postman) — MCP Server for running Postman Collections with Newman ☆`83`
- [kadykov/mcp-openapi-schema-explorer](https://github.com/kadykov/mcp-openapi-schema-explorer) — Token-efficient OpenAPI/Swagger exploration ☆`61`
- [baryhuang/mcp-server-any-openapi](https://github.com/baryhuang/mcp-server-any-openapi) — A MCP server that enables Claude to discover and call any API endpoint through semantic search. Intelligently chunks OpenAPI specifications to handle large API documentation, with built-in request execution capabilities. Perfect for integrating private APIs with Claude Desktop. ☆`75`
- [ReAPI-com/mcp-openapi](https://github.com/ReAPI-com/mcp-openapi) — OpenAPI specification MCP server. ☆`75`
- [hostinger/api-mcp-server](https://github.com/hostinger/api-mcp-server) — MCP server for Hostinger API integration ☆`46`
- [zaizaizhao/mcp-swagger-server](https://github.com/zaizaizhao/mcp-swagger-server) — OpenAPI/Swagger to MCP conversion ☆`44`
- [Omedia/mcp-server-drupal](https://github.com/Omedia/mcp-server-drupal) — TS based companion MCP server for the Drupal MCP module that works with the STDIO transport. ☆`49`
- [hannesj/mcp-openapi-schema](https://github.com/hannesj/mcp-openapi-schema) — OpenAPI Schema Model Context Protocol Server ☆`46`
- [shanejonas/openrpc-mcp-server](https://github.com/shanejonas/openrpc-mcp-server) — JSON-RPC via OpenRPC ☆`42`
- [hannesj/mcp-graphql-schema](https://github.com/hannesj/mcp-graphql-schema) — GraphQL Schema Model Context Protocol Server ☆`42`
- [Kong/mcp-konnect](https://github.com/Kong/mcp-konnect) — A Model Context Protocol (MCP) server for interacting with Kong Konnect APIs, allowing AI assistants to query and analyze Kong Gateway configurations, traffic, and analytics. ☆`38`
- [hijaz/postmancer](https://github.com/hijaz/postmancer) — REST client replacing Postman/Insomnia ☆`29`
- [Arize-ai/text-to-graphql-mcp](https://github.com/Arize-ai/text-to-graphql-mcp) — MCP server for text-to-GraphQL conversion ☆`23`
- [Jktfe/serveMyAPI](https://github.com/Jktfe/serveMyAPI) — MCP server for custom API serving ☆`23`
- [fotoetienne/gqai](https://github.com/fotoetienne/gqai) — Turn any GraphQL endpoint into a set of MCP tools ☆`21`
### CI/CD & DevOps

- [leonardsellem/n8n-mcp-server](https://github.com/leonardsellem/n8n-mcp-server) — MCP server that provides tools and resources for interacting with n8n API ☆`1,520`
- [ckreiling/mcp-server-docker](https://github.com/ckreiling/mcp-server-docker) — MCP server for Docker ☆`660`
- [QuantGeekDev/docker-mcp](https://github.com/QuantGeekDev/docker-mcp) — A docker MCP Server (modelcontextprotocol) ☆`438`
- [utensils/mcp-nixos](https://github.com/utensils/mcp-nixos) — MCP-NixOS - Model Context Protocol Server for NixOS resources ☆`382`
- [TencentEdgeOne/edgeone-pages-mcp](https://github.com/TencentEdgeOne/edgeone-pages-mcp) — Deploy HTML to EdgeOne Pages with public URL ☆`339`
- [jamsocket/forevervm](https://github.com/jamsocket/forevervm) — Stateful AI code sandboxes ☆`224`
- [nacos-group/nacos-mcp-router](https://github.com/nacos-group/nacos-mcp-router) —  ☆`170`
- [DefangLabs/defang](https://github.com/DefangLabs/defang) — MCP server for Defang cloud deployment ☆`144`
- [yangkyeongmo/mcp-server-apache-airflow](https://github.com/yangkyeongmo/mcp-server-apache-airflow) — MCP server for Apache Airflow workflows ☆`120`
- [docker/hub-mcp](https://github.com/docker/hub-mcp) — Docker Hub MCP Server ☆`103`
- [jfrog/mcp-jfrog](https://github.com/jfrog/mcp-jfrog) — Model Context Protocol (MCP) Server for the JFrog Platform API, enabling repository management, build tracking, release lifecycle management, and more. ☆`110`
- [aashari/mcp-server-atlassian-bitbucket](https://github.com/aashari/mcp-server-atlassian-bitbucket) — Atlassian Bitbucket repositories and PRs ☆`96`
- [OctopusDeploy/mcp-server](https://github.com/OctopusDeploy/mcp-server) — Octopus Deploy Official MCP Server ☆`92`
- [Vortiago/mcp-azure-devops](https://github.com/Vortiago/mcp-azure-devops) — A Model Context Protocol (MCP) server enabling AI assistants to interact with Azure DevOps services via Python SDK. ☆`77`
- [CircleCI-Public/mcp-server-circleci](https://github.com/CircleCI-Public/mcp-server-circleci) — MCP server for CircleCI CI/CD pipeline integration ☆`75`
- [buildkite/buildkite-mcp-server](https://github.com/buildkite/buildkite-mcp-server) — Official MCP Server for Buildkite. ☆`42`
- [call518/MCP-Airflow-API](https://github.com/call518/MCP-Airflow-API) — Model Context Protocol (MCP) server for Apache Airflow API integration. Provides comprehensive tools for managing Airflow clusters including service operations, configuration management, status monitoring, and request tracking. ☆`42`
- [bitrise-io/bitrise-mcp](https://github.com/bitrise-io/bitrise-mcp) — Bitrise CI/CD app and build management ☆`26`
- [IvanAmador/vercel-ai-docs-mcp](https://github.com/IvanAmador/vercel-ai-docs-mcp) — Vercel AI SDK documentation search ☆`42`
- [harness/mcp-server](https://github.com/harness/mcp-server) — This is the official repo for the Harness MCP server ☆`20`
- [launchdarkly/mcp-server](https://github.com/launchdarkly/mcp-server) — LaunchDarkly's Model Context Protocol (MCP) Server ☆`17`
- [endorhq/cli](https://github.com/endorhq/cli) — Sandboxed environments for favorite services via MCP ☆`25`
- [axliupore/mcp-code-runner](https://github.com/axliupore/mcp-code-runner) — MCP server for executing code in Docker containers ☆`16`
### Code Analysis

- [bhauman/clojure-mcp](https://github.com/bhauman/clojure-mcp) — Clojure MCP ☆`657`
- [bgauryy/octocode-mcp](https://github.com/bgauryy/octocode-mcp) — MCP server for semantic code search and context generation ☆`659`
- [jasonjmcghee/claude-debugs-for-you](https://github.com/jasonjmcghee/claude-debugs-for-you) — Interactive debugging via MCP and VS Code ☆`477`
- [SonarSource/sonarqube-mcp-server](https://github.com/SonarSource/sonarqube-mcp-server) — SonarQube MCP Server ☆`327`
- [admica/FileScopeMCP](https://github.com/admica/FileScopeMCP) — Codebase dependency diagrams ☆`271`
- [Govcraft/rust-docs-mcp-server](https://github.com/Govcraft/rust-docs-mcp-server) — Rust documentation lookup ☆`231`
- [comet-ml/opik-mcp](https://github.com/comet-ml/opik-mcp) — MCP server for Opik LLM evaluation platform ☆`193`
- [langfuse/mcp-server-langfuse](https://github.com/langfuse/mcp-server-langfuse) — MCP server for Langfuse LLM observability ☆`150`
- [cycodehq/cycode-cli](https://github.com/cycodehq/cycode-cli) — SAST, SCA, Secrets, IaC security scanning ☆`97`
- [janreges/ai-distiller](https://github.com/janreges/ai-distiller) — Fast tool for extracting essential public information from code ☆`117`
- [st3v3nmw/sourcerer-mcp](https://github.com/st3v3nmw/sourcerer-mcp) — Semantic code search reducing token waste ☆`100`
- [debugg-ai/debugg-ai-mcp](https://github.com/debugg-ai/debugg-ai-mcp) — AI-managed end-to-end testing ☆`71`
- [codacy/codacy-mcp-server](https://github.com/codacy/codacy-mcp-server) — Codacy's MCP Server implementation ☆`55`
- [CodeLogicIncEngineering/codelogic-mcp-server](https://github.com/CodeLogicIncEngineering/codelogic-mcp-server) — Codelogic software dependency analysis ☆`33`
- [azer/react-analyzer-mcp](https://github.com/azer/react-analyzer-mcp) — React code analysis and docs generation ☆`54`
- [cqfn/aibolit-mcp-server](https://github.com/cqfn/aibolit-mcp-server) — Aibolit Java static analyzer for AI agents ☆`21`
- [j4c0bs/mcp-server-sql-analyzer](https://github.com/j4c0bs/mcp-server-sql-analyzer) — MCP server for SQL static analysis. ☆`26`
### Design & UI

- [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) — Figma layout info for AI coding agents ☆`12,325`
- [grab/cursor-talk-to-figma-mcp](https://github.com/grab/cursor-talk-to-figma-mcp) — TalkToFigma: MCP integration between Cursor and Figma, allowing Cursor Agentic AI to communicate with Figma for reading designs and modifying them programmatically. ☆`5,834`
- [21st-dev/magic-mcp](https://github.com/21st-dev/magic-mcp) — Frontend development with AI like Magic ☆`4,040`
- [Jpisnice/shadcn-ui-mcp-server](https://github.com/Jpisnice/shadcn-ui-mcp-server) — MCP server for shadcn/ui component library ☆`2,554`
- [hustcc/mcp-mermaid](https://github.com/hustcc/mcp-mermaid) — Generate mermaid diagram and chart with AI MCP dynamically. ☆`342`
- [public-ui/kolibri](https://github.com/public-ui/kolibri) — The accessible HTML-Standard ☆`240`
- [mastergo-design/mastergo-magic-mcp](https://github.com/mastergo-design/mastergo-magic-mcp) — MasterGo Magic MCP is a standalone MCP (Model Context Protocol) service designed to connect MasterGo design tools with AI models. ☆`195`
- [YuChenSSR/mindmap-mcp-server](https://github.com/YuChenSSR/mindmap-mcp-server) — mindmap, mcp server, artifact ☆`208`
- [storybookjs/mcp](https://github.com/storybookjs/mcp) — MCP server for Storybook UI component library ☆`152`
- [freema/mcp-design-system-extractor](https://github.com/freema/mcp-design-system-extractor) — MCP server for extracting design system components ☆`36`
- [themeselection/flyonui-mcp](https://github.com/themeselection/flyonui-mcp) — MCP server for flyonUI ☆`23`
- [themesberg/flowbite-mcp](https://github.com/themesberg/flowbite-mcp) — Figma to code with Flowbite ☆`21`
- [starwind-ui/starwind-ui-mcp](https://github.com/starwind-ui/starwind-ui-mcp) — Local MCP server implementation for Starwind UI that you can use with Cursor, Windsurf, and other AI tools ☆`31`
- [modao-dev/modao-proto-mcp](https://github.com/modao-dev/modao-proto-mcp) — Modao Proto MCP is a standalone MCP (Model Context Protocol) service designed to connect Modao Proto design tools with AI models. ☆`22`
- [heilgar/shadcn-ui-mcp-server](https://github.com/heilgar/shadcn-ui-mcp-server) — MCP server for shadcn/ui component library ☆`20`
- [kapilduraphe/webflow-mcp-server](https://github.com/kapilduraphe/webflow-mcp-server) — Webflow MCP server ☆`19`
### Documentation

- [upstash/context7](https://github.com/upstash/context7) — Up-to-date code docs for LLMs ☆`40,070`
- [lingodotdev/lingo.dev](https://github.com/lingodotdev/lingo.dev) — MCP server for Lingo localization platform ☆`5,067`
- [MicrosoftDocs/mcp](https://github.com/MicrosoftDocs/mcp) — Official Microsoft Learn MCP Server – powering LLMs and AI agents with real-time, trusted Microsoft docs & code samples. ☆`1,212`
- [kimsungwhee/apple-docs-mcp](https://github.com/kimsungwhee/apple-docs-mcp) — MCP server for Apple Developer Documentation - Search iOS/macOS/SwiftUI/UIKit docs, WWDC videos, Swift/Objective-C APIs & code examples in Claude, Cursor & AI assistants ☆`679`
- [vivekVells/mcp-pandoc](https://github.com/vivekVells/mcp-pandoc) — MCP server for document format conversion using pandoc. ☆`472`
- [szeider/consult7](https://github.com/szeider/consult7) — MCP server to consult a language model with large context size ☆`277`
- [andrea9293/mcp-documentation-server](https://github.com/andrea9293/mcp-documentation-server) — MCP Documentation Server - Bridge the AI Knowledge Gap. Features: Document management • Gemini integration • AI-powered semantic search • File uploads • Smart chunking • Multilingual support • Zero-setup Perfect for: New frameworks • API docs • Internal guides ☆`260`
- [khromov/svelte-llm-mcp](https://github.com/khromov/svelte-llm-mcp) — Svelte developer documentation as an MCP and in llms.txt format ☆`158`
- [mrjoshuak/godoc-mcp](https://github.com/mrjoshuak/godoc-mcp) — go doc mcp server ☆`95`
- [yWorks/mcp-typescribe](https://github.com/yWorks/mcp-typescribe) — TypeScript library support for LLMs ☆`45`
- [yikakia/godoc-mcp-server](https://github.com/yikakia/godoc-mcp-server) — Go package docs from pkg.go.dev ☆`34`
- [V0v1kkk/DotNetMetadataMcpServer](https://github.com/V0v1kkk/DotNetMetadataMcpServer) — .NET type metadata for AI coding agents ☆`17`
- [inkeep/mcp-server-python](https://github.com/inkeep/mcp-server-python) — Inkeep MCP Server ☆`24`
- [adapoet/fabric-mcp-server](https://github.com/adapoet/fabric-mcp-server) — The fabric-mcp-server is an MCP server that integrates Fabric patterns with AI coding agents and assistants, exposing them as tools for AI-driven task execution and enhancing capabilities. ☆`17`
- [oborchers/mcp-server-docy](https://github.com/oborchers/mcp-server-docy) — A Model Context Protocol server that provides documentation access capabilities. This server enables LLMs to search and retrieve content from documentation websites by scraping them with crawl4ai. Built with FastMCP v2. ☆`18`
- [Excoriate/mcp-terragrunt-docs](https://github.com/Excoriate/mcp-terragrunt-docs) — Terragrunt documentation context ☆`17`
### IDE & Editors

- [cameroncooke/XcodeBuildMCP](https://github.com/cameroncooke/XcodeBuildMCP) — MCP server for Xcode build operations ☆`3,163`
- [isaacphi/mcp-language-server](https://github.com/isaacphi/mcp-language-server) — MCP server implementing Language Server Protocol ☆`1,336`
- [JetBrains/mcp-jetbrains](https://github.com/JetBrains/mcp-jetbrains) — MCP server for JetBrains IDE integration ☆`939`
- [r-huijts/xcode-mcp-server](https://github.com/r-huijts/xcode-mcp-server) — Xcode project management ☆`339`
- [bigcodegen/mcp-neovim-server](https://github.com/bigcodegen/mcp-neovim-server) — Control Neovim using Model Context Protocol (MCP) and the official neovim/node-client JavaScript library ☆`273`
- [biegehydra/BifrostMCP](https://github.com/biegehydra/BifrostMCP) — VS Code semantic tools via MCP ☆`194`
- [tumf/mcp-text-editor](https://github.com/tumf/mcp-text-editor) — Line-oriented text editing for LLM tools ☆`177`
- [marimo-team/codemirror-mcp](https://github.com/marimo-team/codemirror-mcp) — CodeMirror MCP extension ☆`79`
- [Tritlo/lsp-mcp](https://github.com/Tritlo/lsp-mcp) — An MCP server that lets you interact with LSP servers ☆`90`
- [ShenghaiWang/xcodebuild](https://github.com/ShenghaiWang/xcodebuild) — Xcode iOS build with error feedback ☆`78`
- [hloiseau/mcp-gopls](https://github.com/hloiseau/mcp-gopls) — Go LSP server via gopls ☆`53`
- [laurynas-biveinis/elisp-dev-mcp](https://github.com/laurynas-biveinis/elisp-dev-mcp) — Emacs Elisp development tools for LLMs ☆`30`
- [linw1995/nvim-mcp](https://github.com/linw1995/nvim-mcp) — MCP server for Neovim integration ☆`27`
- [hechtcarmel/jetbrains-index-mcp-plugin](https://github.com/hechtcarmel/jetbrains-index-mcp-plugin) — JetBrains plugin for MCP index integration ☆`21`
- [AB498/code-context-provider-mcp](https://github.com/AB498/code-context-provider-mcp) — MCP server that provides code context and analysis for AI assistants. Extracts directory structure and code symbols using WebAssembly Tree-sitter parsers with Zero Native Dependencies. ☆`21`
### MCP SDKs

- [jlowin/fastmcp](https://github.com/jlowin/fastmcp) — Python framework for building MCP servers and clients ☆`21,417`
- [mark3labs/mcp-go](https://github.com/mark3labs/mcp-go) — Go implementation of MCP ☆`7,867`
- [punkpeye/fastmcp](https://github.com/punkpeye/fastmcp) — TypeScript framework for MCP servers with sessions ☆`2,841`
- [QuantGeekDev/mcp-framework](https://github.com/QuantGeekDev/mcp-framework) — TypeScript framework with auto-discovery ☆`888`
- [php-mcp/laravel](https://github.com/php-mcp/laravel) — Laravel SDK for building MCP servers ☆`466`
- [opgginc/laravel-mcp-server](https://github.com/opgginc/laravel-mcp-server) — Laravel package for MCP servers ☆`327`
- [Epistates/turbomcp](https://github.com/Epistates/turbomcp) — High-performance MCP framework ☆`56`
- [oatpp/oatpp-mcp](https://github.com/oatpp/oatpp-mcp) — C++ MCP implementation for Oat++ framework ☆`48`
- [reflagcom/javascript](https://github.com/reflagcom/javascript) — JS/TS SDKs for Bucket.co ☆`19`
- [Super-I-Tech/mcp_plexus](https://github.com/Super-I-Tech/mcp_plexus) — Multi-tenant MCP framework built on FastMCP ☆`24`
- [stephencme/create-mcp-ts](https://github.com/stephencme/create-mcp-ts) — TypeScript MCP server template ☆`21`
### Mobile Development

- [mobile-next/mobile-mcp](https://github.com/mobile-next/mobile-mcp) — Mobile automation for iOS, Android, emulators ☆`2,780`
- [joshuayoes/ios-simulator-mcp](https://github.com/joshuayoes/ios-simulator-mcp) — MCP server for interacting with the iOS simulator ☆`1,346`
- [minhalvp/android-mcp-server](https://github.com/minhalvp/android-mcp-server) — Android device control via adb ☆`618`
- [hyperb1iss/droidmind](https://github.com/hyperb1iss/droidmind) — Control your Android devices with AI using Model Context Protocol ☆`317`
- [InditexTech/mcp-server-simulator-ios-idb](https://github.com/InditexTech/mcp-server-simulator-ios-idb) — MCP server for iOS simulator via IDB ☆`279`
- [JoshuaRileyDev/app-store-connect-mcp-server](https://github.com/JoshuaRileyDev/app-store-connect-mcp-server) — MCP server for App Store Connect API ☆`236`
- [mhmzdev/figma-flutter-mcp](https://github.com/mhmzdev/figma-flutter-mcp) — Figma design tokens for Flutter code agents ☆`178`
- [zillow/auto-mobile](https://github.com/zillow/auto-mobile) — Mobile automation tools with MCP ☆`71`
- [Tommertom/awesome-ionic-mcp](https://github.com/Tommertom/awesome-ionic-mcp) — Ionic and Capacitor mobile app development ☆`30`
- [JoshuaRileyDev/simulator-mcp-server](https://github.com/JoshuaRileyDev/simulator-mcp-server) — MCP server for iOS Simulator control ☆`47`
- [XixianLiang/HarmonyOS-mcp-server](https://github.com/XixianLiang/HarmonyOS-mcp-server) — MCP server for manipulating HarmonyOS next devices. ☆`26`
### Robotics & Automation

- [trycua/cua](https://github.com/trycua/cua) — MCP server for CUA platform ☆`11,586`
- [robotmcp/ros-mcp-server](https://github.com/robotmcp/ros-mcp-server) — ROS robot control with Claude and GPT ☆`897`
- [omni-mcp/isaac-sim-mcp](https://github.com/omni-mcp/isaac-sim-mcp) — Isaac Simulation MCP Extension and Server ☆`99`
- [abrinsmead/mindpilot-mcp](https://github.com/abrinsmead/mindpilot-mcp) — Visualize code and architect new systems ☆`68`
- [wise-vision/ros2_mcp](https://github.com/wise-vision/ros2_mcp) — ROS 2 robotics AI bridge ☆`60`
- [lpigeon/unitree-go2-mcp-server](https://github.com/lpigeon/unitree-go2-mcp-server) — MCP server for Unitree Go2 robot control ☆`61`
- [Yutarop/ros-mcp](https://github.com/Yutarop/ros-mcp) — MCP server for ROS to control robots via topics, services, and actions. ☆`28`
### Task Management

- [cjo4m06/mcp-shrimp-task-manager](https://github.com/cjo4m06/mcp-shrimp-task-manager) — Task manager with chain-of-thought and reflection ☆`1,936`
- [zueai/mcp-manager](https://github.com/zueai/mcp-manager) — Web UI to manage MCP servers in Claude ☆`276`
### Utilities

- [anaisbetts/mcp-installer](https://github.com/anaisbetts/mcp-installer) — An MCP server that installs other MCP servers for you ☆`1,484`
- [githejie/mcp-server-calculator](https://github.com/githejie/mcp-server-calculator) — A Model Context Protocol server for calculating. ☆`138`
- [jsdelivr/globalping-mcp-server](https://github.com/jsdelivr/globalping-mcp-server) — Remote network commands for LLMs ☆`36`
- [bharathvaj-ganesan/whois-mcp](https://github.com/bharathvaj-ganesan/whois-mcp) — MCP Server for whois lookups. ☆`48`
- [zazencodes/random-number-mcp](https://github.com/zazencodes/random-number-mcp) — MCP server for random number generation ☆`45`
- [ofek/pycli-mcp](https://github.com/ofek/pycli-mcp) — MCP server for any Python command line application ☆`16`
- [andybrandt/mcp-simple-timeserver](https://github.com/andybrandt/mcp-simple-timeserver) — Current time check for Claude via MCP ☆`25`
- [ZeparHyfar/mcp-datetime](https://github.com/ZeparHyfar/mcp-datetime) — A MCP server for datetime formatting and file name generation. ☆`25`
### Version Control

- [github/github-mcp-server](https://github.com/github/github-mcp-server) — GitHub's official MCP Server ☆`25,421`
- [idosal/git-mcp](https://github.com/idosal/git-mcp) — Free remote MCP for any GitHub project ☆`7,264`
- [gitkraken/gk-cli](https://github.com/gitkraken/gk-cli) — GitKraken CLI Releases and Documentation ☆`335`
- [Tiberriver256/mcp-server-azure-devops](https://github.com/Tiberriver256/mcp-server-azure-devops) — An MCP server for Azure DevOps ☆`312`
- [adhikasp/mcp-git-ingest](https://github.com/adhikasp/mcp-git-ingest) — GitHub repository content reading ☆`294`
- [puravparab/Gitingest-MCP](https://github.com/puravparab/Gitingest-MCP) — mcp server for gitingest ☆`131`
- [kopfrechner/gitlab-mr-mcp](https://github.com/kopfrechner/gitlab-mr-mcp) — MCP server for GitLab merge requests and issues ☆`71`
- [oschina/mcp-gitee](https://github.com/oschina/mcp-gitee) — MCP server for Gitee repositories ☆`44`
- [ddukbg/github-enterprise-mcp](https://github.com/ddukbg/github-enterprise-mcp) — github-enterprise-mcp ☆`27`
- [Ryan0204/github-repo-mcp](https://github.com/Ryan0204/github-repo-mcp) — GitHub repository reading ☆`22`
### Web Scraping

- [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server) — Web scraping and search for LLM clients ☆`5,126`
- [brightdata/brightdata-mcp](https://github.com/brightdata/brightdata-mcp) — All-in-one public web access solution ☆`1,776`
- [etsd-tech/mcp-pointer](https://github.com/etsd-tech/mcp-pointer) — DOM element pointing for agents ☆`552`
- [pskill9/website-downloader](https://github.com/pskill9/website-downloader) — MCP server to download entire websites ☆`146`
### Package Managers

- [sammcj/mcp-package-version](https://github.com/sammcj/mcp-package-version) — Latest stable package versions for LLMs ☆`118`
- [Artmann/package-registry-mcp](https://github.com/Artmann/package-registry-mcp) — NPM, Cargo, PyPi, NuGet package search ☆`32`
- [Bigsy/maven-mcp-server](https://github.com/Bigsy/maven-mcp-server) — Maven build and dependency tools ☆`29`
- [IlyaGulya/gradle-mcp-server](https://github.com/IlyaGulya/gradle-mcp-server) — Gradle project interaction for AI tools ☆`40`
- [jeannier/homebrew-mcp](https://github.com/jeannier/homebrew-mcp) — Homebrew package management ☆`20`
### Debuggers

- [cameroncooke/reloaderoo](https://github.com/cameroncooke/reloaderoo) — Powerful MCP debugging proxy and CLI inspection tool. ☆`108`
- [stass/lldb-mcp](https://github.com/stass/lldb-mcp) — LLDB MCP server ☆`68`
- [pansila/mcp_server_gdb](https://github.com/pansila/mcp_server_gdb) — MCP Server to expose the GDB debugging capabilities ☆`53`
### Testing & QA

- [QAInsights/jmeter-mcp-server](https://github.com/QAInsights/jmeter-mcp-server) — JMeter AI workflow integration ☆`53`
- [mrexodia/user-feedback-mcp](https://github.com/mrexodia/user-feedback-mcp) — Human-in-the-loop workflow for Cursor ☆`52`
- [SmartBear/smartbear-mcp](https://github.com/SmartBear/smartbear-mcp) — SmartBear's official MCP Server ☆`19`
- [Hypersequent/qasphere-mcp](https://github.com/Hypersequent/qasphere-mcp) — MCP Server for QA Sphere TMS ☆`18`
- [reportportal/reportportal-mcp-server](https://github.com/reportportal/reportportal-mcp-server) — MCP server for ReportPortal ☆`16`
- [hungthai1401/bruno-mcp](https://github.com/hungthai1401/bruno-mcp) — MCP Server for running Bruno Collections ☆`32`
- [QAInsights/k6-mcp-server](https://github.com/QAInsights/k6-mcp-server) — k6 MCP server ☆`20`
## Embedded & IoT

- [tevonsb/homeassistant-mcp](https://github.com/tevonsb/homeassistant-mcp) — A MCP server for Home Assistant ☆`502`
- [Extelligence-ai/bagel](https://github.com/Extelligence-ai/bagel) — Chat with robotics, drone, IoT data ☆`369`
- [lamaalrajih/kicad-mcp](https://github.com/lamaalrajih/kicad-mcp) — Model Context Protocol server for KiCad on Mac, Windows, and Linux ☆`355`
- [voska/hass-mcp](https://github.com/voska/hass-mcp) — Home Assistant MCP Server ☆`250`
- [hao-cyber/phone-mcp](https://github.com/hao-cyber/phone-mcp) — A phone control plugin for MCP that allows you to control your Android phone through ADB commands to connect any human ☆`191`
- [horw/esp-mcp](https://github.com/horw/esp-mcp) — ESP32 commands and getting started ☆`118`
- [thingsboard/thingsboard-mcp](https://github.com/thingsboard/thingsboard-mcp) — MCP server for ThingsBoard IoT platform interaction ☆`81`
- [jeff-nasseri/mikrotik-mcp](https://github.com/jeff-nasseri/mikrotik-mcp) — MCP server for Mikrotik ☆`76`
- [vishalmysore/choturobo](https://github.com/vishalmysore/choturobo) — Integrate Arduino-based robotics (using the NodeMCU ESP32 or Arduino Nano 368 board) with AI using the MCP (Model Context Protocol) framework from Claude Anthropic ☆`70`
- [kukapay/opcua-mcp](https://github.com/kukapay/opcua-mcp) — An MCP server that connects to OPC UA-enabled industrial systems. ☆`22`
- [MiddlePoint-Solutions/mcp-on-android-tv](https://github.com/MiddlePoint-Solutions/mcp-on-android-tv) — A Model Context Protocol (MCP) community server running on Android TV with on-device ADB integration - Control your TV with natural language. ☆`19`
- [yoelbassin/gr-mcp](https://github.com/yoelbassin/gr-mcp) — MCP server for GNU Radio ☆`24`
- [aqara/aqara-mcp-server](https://github.com/aqara/aqara-mcp-server) — Aqara's official MCP Server ☆`24`
- [thinq-connect/thinqconnect-mcp](https://github.com/thinq-connect/thinqconnect-mcp) — ThinQ Connect MCP Server ☆`21`
- [OctoEverywhere/mcp](https://github.com/OctoEverywhere/mcp) — 3D printing live status and control ☆`21`
- [kukapay/modbus-mcp](https://github.com/kukapay/modbus-mcp) — Industrial Modbus data for AI ☆`18`
- [johannesPettersson80/codesys-mcp-toolkit](https://github.com/johannesPettersson80/codesys-mcp-toolkit) — CODESYS industrial automation platform ☆`16`
- [Hypijump31/bluetooth-mcp-server](https://github.com/Hypijump31/bluetooth-mcp-server) — bluetooth-mcp-server for Claude AI ☆`16`
## File Systems & Storage

- [mark3labs/mcp-filesystem-server](https://github.com/mark3labs/mcp-filesystem-server) — Go filesystem operations via MCP ☆`568`
- [cyberchitta/llm-context.py](https://github.com/cyberchitta/llm-context.py) — Python library for LLM context management ☆`288`
- [mamertofabian/mcp-everything-search](https://github.com/mamertofabian/mcp-everything-search) — Fast file search across Windows, macOS, Linux ☆`280`
- [isaacphi/mcp-gdrive](https://github.com/isaacphi/mcp-gdrive) — Google Drive file reading ☆`246`
- [8b-is/smart-tree](https://github.com/8b-is/smart-tree) — Context-aware AI-crafted replacement for tree command ☆`197`
- [rust-mcp-stack/rust-mcp-filesystem](https://github.com/rust-mcp-stack/rust-mcp-filesystem) — Blazing-fast, asynchronous MCP server for seamless filesystem operations. ☆`108`
- [efforthye/fast-filesystem-mcp](https://github.com/efforthye/fast-filesystem-mcp) — High-performance MCP server for file operations ☆`34`
- [Tencent/cos-mcp](https://github.com/Tencent/cos-mcp) — Tencent Cloud COS storage integration ☆`18`
- [Xuanwo/mcp-server-opendal](https://github.com/Xuanwo/mcp-server-opendal) — Model Context Protocol Server for Apache OpenDAL ☆`33`
- [exoticknight/mcp-file-merger](https://github.com/exoticknight/mcp-file-merger) — MCP server for merging multiple files into one ☆`23`
## Finance

### Accounting & Budgeting

- [XeroAPI/xero-mcp-server](https://github.com/XeroAPI/xero-mcp-server) — Xero accounting API integration ☆`162`
- [minhyeoky/mcp-server-ledger](https://github.com/minhyeoky/mcp-server-ledger) — MCP server for Ledger CLI double-entry accounting ☆`41`
- [akutishevsky/lunchmoney-mcp](https://github.com/akutishevsky/lunchmoney-mcp) — MCP server for Lunch Money budgeting app ☆`29`
- [iiAtlas/hledger-mcp](https://github.com/iiAtlas/hledger-mcp) — A local MCP server for interacting with the HLedger cli ☆`28`
- [openMF/mcp-mifosx](https://github.com/openMF/mcp-mifosx) — Model Context Protocol - MCP for Mifos X ☆`18`
- [john-zhang-dev/xero-mcp](https://github.com/john-zhang-dev/xero-mcp) — A Model Context Protocol server allows Clients to interact with Xero ☆`19`
### Crypto & Blockchain

- [mcpdotdirect/evm-mcp-server](https://github.com/mcpdotdirect/evm-mcp-server) — EVM network interaction for LLMs ☆`349`
- [base/base-mcp](https://github.com/base/base-mcp) — MCP server for Base blockchain integration ☆`331`
- [armorwallet/armor-crypto-mcp](https://github.com/armorwallet/armor-crypto-mcp) — Blockchain swaps and strategic planning ☆`183`
- [aaronjmars/web3-research-mcp](https://github.com/aaronjmars/web3-research-mcp) — Deep Research for crypto - free & fully local ☆`147`
- [kukapay/crypto-indicators-mcp](https://github.com/kukapay/crypto-indicators-mcp) — Cryptocurrency technical analysis indicators ☆`102`
- [Bankless/onchain-mcp](https://github.com/Bankless/onchain-mcp) — Bringing the bankless onchain API to MCP ☆`76`
- [alchemyplatform/alchemy-mcp-server](https://github.com/alchemyplatform/alchemy-mcp-server) — Alchemy blockchain API for AI agents ☆`72`
- [QuantGeekDev/coincap-mcp](https://github.com/QuantGeekDev/coincap-mcp) — A coincap mcp server to access crypto data from coincap API ☆`90`
- [kukapay/cryptopanic-mcp-server](https://github.com/kukapay/cryptopanic-mcp-server) — Provide latest cryptocurrency news to AI agents. ☆`62`
- [heurist-network/heurist-mesh-mcp-server](https://github.com/heurist-network/heurist-mesh-mcp-server) — Blockchain and web3 via Heurist Mesh ☆`63`
- [AbdelStark/bitcoin-mcp](https://github.com/AbdelStark/bitcoin-mcp) — Bitcoin & Lightning Network MCP Server. ☆`67`
- [twelvedata/mcp](https://github.com/twelvedata/mcp) — MCP server for real-time financial market data access ☆`48`
- [shinzo-labs/coinmarketcap-mcp](https://github.com/shinzo-labs/coinmarketcap-mcp) — MCP Implementation for CoinMarketCap ☆`45`
- [coinpaprika/dexpaprika-mcp](https://github.com/coinpaprika/dexpaprika-mcp) — MCP server for DEX trading data and crypto token analytics ☆`35`
- [bnb-chain/bnbchain-mcp](https://github.com/bnb-chain/bnbchain-mcp) — A MCP server for BNB Chain that supports BSC, opBNB, Greenfield, and other popular EVM-compatible networks. ☆`48`
- [kukapay/crypto-feargreed-mcp](https://github.com/kukapay/crypto-feargreed-mcp) — Crypto Fear & Greed Index data ☆`50`
- [kukapay/whale-tracker-mcp](https://github.com/kukapay/whale-tracker-mcp) — A mcp server for tracking cryptocurrency whale transactions. ☆`48`
- [kukapay/crypto-sentiment-mcp](https://github.com/kukapay/crypto-sentiment-mcp) — Cryptocurrency sentiment analysis ☆`45`
- [getAlby/mcp](https://github.com/getAlby/mcp) — Bitcoin Lightning wallet via Nostr ☆`40`
- [anjor/coinmarket-mcp-server](https://github.com/anjor/coinmarket-mcp-server) — MCP server for CoinMarketCap cryptocurrency data ☆`44`
- [GoPlausible/algorand-mcp](https://github.com/GoPlausible/algorand-mcp) — Algorand Model Context Protocol (Server & Client) ☆`38`
- [wowinter13/solscan-mcp](https://github.com/wowinter13/solscan-mcp) — Solana transaction queries ☆`37`
- [token-metrics/mcp](https://github.com/token-metrics/mcp) — MCP server for cryptocurrency data, analytics and trading signals ☆`18`
- [noditlabs/nodit-mcp-server](https://github.com/noditlabs/nodit-mcp-server) — A Model Context Protocol (MCP) server for AI agents to interact with blockchain data via Nodit’s Web3 Data and Node APIs. Enables LLMs to access structured, multi-chain blockchain context with zero blockchain-specific logic. ☆`18`
- [kukapay/kukapay-mcp-servers](https://github.com/kukapay/kukapay-mcp-servers) — A comprehensive suite of Model Context Protocol (MCP) servers from Kukapay. ☆`18`
- [kukapay/uniswap-trader-mcp](https://github.com/kukapay/uniswap-trader-mcp) — Uniswap token swaps for AI agents ☆`34`
- [longmans/coin_api_mcp](https://github.com/longmans/coin_api_mcp) — A Model Context Protocol server that provides access to CoinMarketCap's cryptocurrency data. This server enables AI-powered applications to retrieve cryptocurrency listings, quotes, and detailed information about various coins. ☆`34`
- [kukapay/dune-analytics-mcp](https://github.com/kukapay/dune-analytics-mcp) — A mcp server that bridges Dune Analytics data to AI agents. ☆`33`
- [pwh-pwh/coin-mcp-server](https://github.com/pwh-pwh/coin-mcp-server) — use Bitget’s API to get cryptocurrency info ☆`28`
- [kukapay/hyperliquid-info-mcp](https://github.com/kukapay/hyperliquid-info-mcp) — MCP server for Hyperliquid DEX data ☆`25`
- [devonmojito/ton-blockchain-mcp](https://github.com/devonmojito/ton-blockchain-mcp) — A Model Context Protocol (MCP) server written in Python for natural language interaction with the TON blockchain ☆`24`
- [kukapay/jupiter-mcp](https://github.com/kukapay/jupiter-mcp) — Jupiter DEX token swaps on Solana ☆`22`
- [maestro-org/maestro-mcp-server](https://github.com/maestro-org/maestro-mcp-server) — Maestro MCP Server for Bitcoin ☆`19`
- [magnetai/mcp-free-usdc-transfer](https://github.com/magnetai/mcp-free-usdc-transfer) — MCP (Model Context Protocol) server - free usdc transfer powered by Coinbase CDP ☆`20`
- [Codex-Data/codex-mcp](https://github.com/Codex-Data/codex-mcp) — A Model Context Protocol server for the Codex API ☆`20`
- [kukapay/token-minter-mcp](https://github.com/kukapay/token-minter-mcp) — ERC-20 token minting for AI agents ☆`17`
- [thirdweb-dev/ai](https://github.com/thirdweb-dev/ai) — Blockchain data, wallet, and smart contracts ☆`18`
- [syronlabs/stellar-mcp](https://github.com/syronlabs/stellar-mcp) — A Stellar MCP to interact with Horizon API and Soroban ☆`18`
- [SaintDoresh/Crypto-Trader-MCP-ClaudeDesktop](https://github.com/SaintDoresh/Crypto-Trader-MCP-ClaudeDesktop) — MCP server for cryptocurrency trading ☆`17`
- [janswist/mcp-dexscreener](https://github.com/janswist/mcp-dexscreener) — Dexscreener on-chain price checking ☆`16`
### Payments & Banking

- [stripe/ai](https://github.com/stripe/ai) — One-stop shop for building AI-powered products and businesses with Stripe. ☆`1,170`
- [razorpay/razorpay-mcp-server](https://github.com/razorpay/razorpay-mcp-server) — Razorpay's Official MCP Server ☆`210`
- [paypal/agent-toolkit](https://github.com/paypal/agent-toolkit) — PayPal Agent ☆`171`
- [square/square-mcp-server](https://github.com/square/square-mcp-server) — A Model Context Protocol (MCP) server for square ☆`90`
- [PaddleHQ/paddle-mcp-server](https://github.com/PaddleHQ/paddle-mcp-server) — Interact with the Paddle API using AI assistants like Claude, or in AI-powered IDEs like Cursor. Manage product catalog, billing and subscriptions, and reports. ☆`36`
- [ramp-public/ramp_mcp](https://github.com/ramp-public/ramp_mcp) — ramp_mcp ☆`27`
- [Fewsats/fewsats-mcp](https://github.com/Fewsats/fewsats-mcp) — Fewsats MCP server ☆`21`
### Stock Data & Analytics

- [financial-datasets/mcp-server](https://github.com/financial-datasets/mcp-server) — Financial Datasets stock market API ☆`723`
- [massive-com/mcp_massive](https://github.com/massive-com/mcp_massive) — An MCP server for Massive.com Financial Market Data ☆`231`
- [stefanoamorelli/sec-edgar-mcp](https://github.com/stefanoamorelli/sec-edgar-mcp) — A SEC EDGAR MCP (Model Context Protocol) Server ☆`187`
- [berlinbra/alpha-vantage-mcp](https://github.com/berlinbra/alpha-vantage-mcp) — MCP Server for Alpha Advantage API ☆`86`
- [narumiruna/yfinance-mcp](https://github.com/narumiruna/yfinance-mcp) — MCP server for Yahoo Finance stock data and news ☆`78`
- [OctagonAI/octagon-mcp-server](https://github.com/OctagonAI/octagon-mcp-server) — Public filings, earnings, financial analysis ☆`86`
- [HuggingAGI/mcp-baostock-server](https://github.com/HuggingAGI/mcp-baostock-server) — MCP server for BaoStock Chinese stock market data ☆`64`
- [Adity-star/mcp-yfinance-server](https://github.com/Adity-star/mcp-yfinance-server) — Real-time stock API with Python, MCP server example, yfinance stock analysis dashboard ☆`41`
- [zlinzzzz/finData-mcp-server](https://github.com/zlinzzzz/finData-mcp-server) — Financial data from Tushare, Wind, DataYes ☆`50`
- [JamesANZ/prediction-market-mcp](https://github.com/JamesANZ/prediction-market-mcp) — Polymarket, PredictIt, Kalshi data ☆`20`
- [OctagonAI/octagon-vc-agents](https://github.com/OctagonAI/octagon-vc-agents) — An MCP server that runs AI-driven venture capitalist agents (Fred Wilson, Peter Thiel, etc.), whose thinking is continuously enriched by Octagon Private Markets' real-time deals, valuations, and deep research intelligence. Use it to spin up programmable "VC brains" for pitch feedback, diligence simulations, term sheet negotiations, and more. ☆`17`
### Trading & Exchanges

- [alpacahq/alpaca-mcp-server](https://github.com/alpacahq/alpaca-mcp-server) — Alpaca’s official MCP Server lets you trade stocks, ETFs, crypto, and options, run data analysis, and build strategies in plain English directly from your favorite LLM tools and IDEs ☆`421`
- [ferdousbhai/investor-agent](https://github.com/ferdousbhai/investor-agent) — Investor agent building via MCP ☆`296`
- [ariadng/metatrader-mcp-server](https://github.com/ariadng/metatrader-mcp-server) — MetaTrader trading platform for AI LLMs ☆`136`
- [doggybee/mcp-server-ccxt](https://github.com/doggybee/mcp-server-ccxt) — Cryptocurrency exchange integration via CCXT ☆`123`
- [kukapay/freqtrade-mcp](https://github.com/kukapay/freqtrade-mcp) — Freqtrade crypto trading bot ☆`100`
- [QuantConnect/mcp-server](https://github.com/QuantConnect/mcp-server) — QuantConnect algo trading interaction ☆`62`
- [taylorwilsdon/quantconnect-mcp](https://github.com/taylorwilsdon/quantconnect-mcp) — QuantConnect Algorithmic Trading Platform Orchestration MCP - Agentic LLM Driven Trading Strategy Design, Research & Implementation ☆`73`
- [ferdousbhai/tasty-agent](https://github.com/ferdousbhai/tasty-agent) — Let Claude manage your tastytrade portfolio. ☆`48`
- [trade-it-inc/trade-it-mcp](https://github.com/trade-it-inc/trade-it-mcp) — Trade It stocks and crypto trading ☆`41`
- [ozgureyilmaz/polymarket-mcp](https://github.com/ozgureyilmaz/polymarket-mcp) — A Model Context Protocol (MCP) server for Polymarket prediction markets, providing real-time market data, prices, and AI-powered analysis tools for Claude Desktop integration. ☆`25`
- [mektigboy/server-hyperliquid](https://github.com/mektigboy/server-hyperliquid) — MCP Hyperliquid (https://app.hyperliquid.xyz) server ☆`39`
- [laukikk/alpaca-mcp](https://github.com/laukikk/alpaca-mcp) — Alpaca stock and crypto trading ☆`33`
- [SaintDoresh/YFinance-Trader-MCP-ClaudeDesktop](https://github.com/SaintDoresh/YFinance-Trader-MCP-ClaudeDesktop) — MCP server for Yahoo Finance trading data ☆`28`
- [ferdousbhai/wsb-analyst-mcp](https://github.com/ferdousbhai/wsb-analyst-mcp) — MCP server for analyzing WallStreetBets ☆`19`
- [paperinvest/mcp-server](https://github.com/paperinvest/mcp-server) — Official MCP server for Paper's trading platform - enables AI assistants to interact with Paper's API ☆`18`
## Gaming

- [Coding-Solo/godot-mcp](https://github.com/Coding-Solo/godot-mcp) — MCP server for Godot game engine ☆`1,255`
- [CoderGamester/mcp-unity](https://github.com/CoderGamester/mcp-unity) — MCP server for Unity game engine integration ☆`1,160`
- [IvanMurzak/Unity-MCP](https://github.com/IvanMurzak/Unity-MCP) — AI-powered bridge connecting LLMs to Unity Editor ☆`653`
- [Roblox/studio-rust-mcp-server](https://github.com/Roblox/studio-rust-mcp-server) — Standalone Roblox Studio MCP Server ☆`210`
- [playcanvas/editor-mcp-server](https://github.com/playcanvas/editor-mcp-server) — MCP Server for AI automation of the PlayCanvas Editor ☆`82`
- [quazaai/UnityMCPIntegration](https://github.com/quazaai/UnityMCPIntegration) — Enable AI Agents to Control Unity ☆`99`
- [codemaestroai/advanced-unity-mcp](https://github.com/codemaestroai/advanced-unity-mcp) — Advanced Unity game engine integration ☆`73`
- [pab1it0/chess-mcp](https://github.com/pab1it0/chess-mcp) — MCP server for Chess.com player data, games and statistics ☆`57`
- [opgginc/opgg-mcp](https://github.com/opgginc/opgg-mcp) — MCP server for OP.GG game data (LoL, TFT, Valorant) ☆`53`
- [kkjdaniel/bgg-mcp](https://github.com/kkjdaniel/bgg-mcp) — MCP server for BoardGameGeek data ☆`23`
- [jalpp/chessagine-mcp](https://github.com/jalpp/chessagine-mcp) — A comprehensive (MCP) server that provides advanced chess analysis capabilities by implementing Chess Context Protocol Server and integrating Stockfish engine evaluation, positional theme analysis, opening databases, and chess knowledge ☆`16`
- [jifrozen0110/mcp-riot](https://github.com/jifrozen0110/mcp-riot) — League of Legends MCP Server ☆`18`
- [jiayao/mcp-chess](https://github.com/jiayao/mcp-chess) — MCP server for playing chess against AI ☆`17`
## Healthcare & Bioinformatics

- [genomoncology/biomcp](https://github.com/genomoncology/biomcp) — BioMCP: Biomedical Model Context Protocol ☆`378`
- [the-momentum/apple-health-mcp-server](https://github.com/the-momentum/apple-health-mcp-server) — Apple Health data queries with DuckDB ☆`88`
- [ChristianHinge/dicom-mcp](https://github.com/ChristianHinge/dicom-mcp) — DICOM server (PACS) interaction ☆`75`
- [wso2/fhir-mcp-server](https://github.com/wso2/fhir-mcp-server) — FHIR healthcare API integration ☆`68`
- [JamesANZ/medical-mcp](https://github.com/JamesANZ/medical-mcp) — MCP server for medical data processing ☆`48`
- [the-momentum/fhir-mcp-server](https://github.com/the-momentum/fhir-mcp-server) — FHIR MCP Server for handling medical data standard. ☆`46`
- [srijanshukla18/xray](https://github.com/srijanshukla18/xray) — MCP server for X-ray analysis ☆`39`
- [longevity-genie/biothings-mcp](https://github.com/longevity-genie/biothings-mcp) — MCP (Model Context Protocol) server for biothings ☆`27`
- [OHNLP/omop_mcp](https://github.com/OHNLP/omop_mcp) — MCP server for OMOP medical data standard ☆`23`
- [longevity-genie/gget-mcp](https://github.com/longevity-genie/gget-mcp) — Bioinformatic gget functions ☆`21`
- [tomekkorbak/oura-mcp-server](https://github.com/tomekkorbak/oura-mcp-server) — MCP server for Oura API integration ☆`36`
## Location & Maps

- [jjsantos01/qgis_mcp](https://github.com/jjsantos01/qgis_mcp) — Model Context Protocol (MCP) that allows LLMs to use QGIS Desktop ☆`732`
- [baidu-maps/mcp](https://github.com/baidu-maps/mcp) — Baidu Map MCP Server ☆`376`
- [mapbox/mcp-server](https://github.com/mapbox/mcp-server) — Mapbox Model Context Protocol (MCP) server ☆`296`
- [jagan-shanmugam/open-streetmap-mcp](https://github.com/jagan-shanmugam/open-streetmap-mcp) — MCP server for OpenStreetMap data ☆`150`
- [mahdin75/gis-mcp](https://github.com/mahdin75/gis-mcp) — MCP server connecting LLMs to GIS capabilities ☆`87`
- [mahdin75/geoserver-mcp](https://github.com/mahdin75/geoserver-mcp) — GeoServer geospatial integration ☆`51`
- [briandconnelly/mcp-server-ipinfo](https://github.com/briandconnelly/mcp-server-ipinfo) — IP Geolocation Server for MCP ☆`39`
- [isdaniel/mcp_weather_server](https://github.com/isdaniel/mcp_weather_server) — Weather info via Open-Meteo API ☆`35`
- [tomtom-international/tomtom-mcp](https://github.com/tomtom-international/tomtom-mcp) — A Model Context Protocol (MCP) server providing TomTom's location services, search, routing, and traffic data to AI agents. ☆`34`
- [mfukushim/map-traveler-mcp](https://github.com/mfukushim/map-traveler-mcp) — Virtual traveler library for MCP ☆`24`
- [SecretiveShell/MCP-timeserver](https://github.com/SecretiveShell/MCP-timeserver) — Datetime info for agentic systems ☆`40`
- [TimLukaHorstmann/mcp-weather](https://github.com/TimLukaHorstmann/mcp-weather) — AccuWeather hourly and daily forecasts ☆`30`
- [webcoderz/MCP-Geo](https://github.com/webcoderz/MCP-Geo) — Geocoding MCP server with GeoPY! ☆`29`
- [sjanaX01/weather-mcp-server](https://github.com/sjanaX01/weather-mcp-server) — A simple minimal weather mcp server :) ☆`19`
- [stadiamaps/stadiamaps-mcp-server-ts](https://github.com/stadiamaps/stadiamaps-mcp-server-ts) — Stadia Maps API integration in TypeScript ☆`18`
- [mschneider82/mcp-openweather](https://github.com/mschneider82/mcp-openweather) — mcp server for openweather free api ☆`16`
- [kukapay/nearby-search-mcp](https://github.com/kukapay/nearby-search-mcp) — Nearby place search with IP-based location ☆`21`
## Marketing & Analytics

- [pipeboard-co/meta-ads-mcp](https://github.com/pipeboard-co/meta-ads-mcp) — MCP server to manage Facebook and Instagram Ads (Meta Ads) ☆`384`
- [open-strategy-partners/osp_marketing_tools](https://github.com/open-strategy-partners/osp_marketing_tools) — MCP server for marketing automation tools ☆`258`
- [gomarble-ai/facebook-ads-mcp-server](https://github.com/gomarble-ai/facebook-ads-mcp-server) — Facebook and Instagram Ads management ☆`202`
- [cnych/seo-mcp](https://github.com/cnych/seo-mcp) — A free SEO tool MCP (Model Control Protocol) service based on Ahrefs data. Includes features such as backlinks, keyword ideas, and more. ☆`191`
- [surendranb/google-analytics-mcp](https://github.com/surendranb/google-analytics-mcp) — Google Analytics 4 MCP Server for Claude, Cursor, Windsurf etc - Access GA4 data through natural language with 200+ dimensions & metrics ☆`164`
- [talknerdytome-labs/facebook-ads-library-mcp](https://github.com/talknerdytome-labs/facebook-ads-library-mcp) — Facebook Ads Library search and access ☆`164`
- [gomarble-ai/google-ads-mcp-server](https://github.com/gomarble-ai/google-ads-mcp-server) — Google Ads performance data analysis ☆`84`
- [stape-io/google-tag-manager-mcp-server](https://github.com/stape-io/google-tag-manager-mcp-server) — MCP server for Google Tag Manager ☆`82`
- [microsoft/clarity-mcp-server](https://github.com/microsoft/clarity-mcp-server) — A Model Context Protocol (MCP) server for Microsoft Clarity ☆`53`
- [metricool/mcp-metricool](https://github.com/metricool/mcp-metricool) — This is a Multi-Agent Collaboration Protocol (MCP) server for interacting with the Metricool API. It allows AI agents to access and analyze social media metrics and campaign data from your Metricool account. ☆`22`
- [Kiran1689/storyblok-mcp-server](https://github.com/Kiran1689/storyblok-mcp-server) — MCP server for Storyblok CMS management ☆`31`
- [builtwith/mcp](https://github.com/builtwith/mcp) — BuiltWith MCP Server ☆`29`
- [gvaibhav/TAM-MCP-Server](https://github.com/gvaibhav/TAM-MCP-Server) — A comprehensive Model Context Protocol (MCP) server for market sizing analysis, TAM/SAM calculations, and industry research. Built with TypeScript, Express.js, and following the MCP specification. ☆`28`
- [jonathan-politzki/smartlead-mcp-server](https://github.com/jonathan-politzki/smartlead-mcp-server) — Local version of Smartlead MCP for quick download and deployment to MCP compatible clients or n8n. ☆`17`
- [rafaelstz/adobe-commerce-dev-mcp](https://github.com/rafaelstz/adobe-commerce-dev-mcp) — Adobe Commerce Dev MCP Server ☆`21`
- [MarketplaceAdPros/amazon-ads-mcp-server](https://github.com/MarketplaceAdPros/amazon-ads-mcp-server) — MCP Server to interact with Amazon Ads ☆`19`
## Media Processing

- [ahujasid/blender-mcp](https://github.com/ahujasid/blender-mcp) — Blender 3D modeling with Claude AI ☆`14,631`
- [elevenlabs/elevenlabs-mcp](https://github.com/elevenlabs/elevenlabs-mcp) — The official ElevenLabs MCP server ☆`1,112`
- [AIDC-AI/Pixelle-MCP](https://github.com/AIDC-AI/Pixelle-MCP) — An Open-Source Multimodal AIGC Solution based on ComfyUI + MCP + LLM https://pixelle.ai ☆`868`
- [varunneal/spotify-mcp](https://github.com/varunneal/spotify-mcp) — MCP to connect your LLM with Spotify. ☆`546`
- [abhiemj/manim-mcp-server](https://github.com/abhiemj/manim-mcp-server) — Manim animation code execution ☆`529`
- [anaisbetts/mcp-youtube](https://github.com/anaisbetts/mcp-youtube) — A Model-Context Protocol Server for YouTube ☆`481`
- [samuelgursky/davinci-resolve-mcp](https://github.com/samuelgursky/davinci-resolve-mcp) — MCP server integration for DaVinci Resolve ☆`443`
- [ZubeidHendricks/youtube-mcp-server](https://github.com/ZubeidHendricks/youtube-mcp-server) — MCP Server for YouTube API, enabling video management, Shorts creation, and advanced analytics ☆`411`
- [Simon-Kansara/ableton-live-mcp-server](https://github.com/Simon-Kansara/ableton-live-mcp-server) — MCP Server implementation for Ableton Live OSC control ☆`346`
- [sunriseapps/imagesorcery-mcp](https://github.com/sunriseapps/imagesorcery-mcp) — Image processing operations ☆`259`
- [burningion/video-editing-mcp](https://github.com/burningion/video-editing-mcp) — MCP Interface for Video Jungle ☆`236`
- [marcelmarais/spotify-mcp-server](https://github.com/marcelmarais/spotify-mcp-server) — Lightweight MCP server for Spotify ☆`202`
- [muxinc/mux-node-sdk](https://github.com/muxinc/mux-node-sdk) — Mux Video and Data API wrapper ☆`172`
- [8beeeaaat/touchdesigner-mcp](https://github.com/8beeeaaat/touchdesigner-mcp) — MCP server for TouchDesigner ☆`157`
- [tiianhk/MaxMSP-MCP-Server](https://github.com/tiianhk/MaxMSP-MCP-Server) — MCP (Model Context Protocol) Server for Max (Max/MSP/Jitter) ☆`127`
- [video-creator/ffmpeg-mcp](https://github.com/video-creator/ffmpeg-mcp) — MCP server for FFmpeg video processing ☆`106`
- [diivi/aseprite-mcp](https://github.com/diivi/aseprite-mcp) — MCP server for interacting with the Aseprite API ☆`99`
- [GongRzhe/opencv-mcp-server](https://github.com/GongRzhe/opencv-mcp-server) — OpenCV MCP Server provides OpenCV's image and video processing capabilities through the Model Context Protocol (MCP). Access powerful computer vision tools for tasks ranging from basic image manipulation to advanced object detection and tracking. ☆`87`
- [Flyworks-AI/flyworks-mcp](https://github.com/Flyworks-AI/flyworks-mcp) — Fast and free zeroshot lipsync MCP server ☆`90`
- [awkoy/replicate-flux-mcp](https://github.com/awkoy/replicate-flux-mcp) — MCP server for Replicate Flux image and SVG generation ☆`82`
- [SureScaleAI/openai-gpt-image-mcp](https://github.com/SureScaleAI/openai-gpt-image-mcp) — OpenAI GPT-4o image generation and editing ☆`84`
- [PSPDFKit/nutrient-dws-mcp-server](https://github.com/PSPDFKit/nutrient-dws-mcp-server) — A Model Context Protocol (MCP) server implementation that integrates with the Nutrient Document Web Service (DWS) Processor API, providing powerful PDF processing capabilities for AI assistants. ☆`61`
- [apinetwork/piapi-mcp-server](https://github.com/apinetwork/piapi-mcp-server) — PiAPI media: Midjourney, Flux, Kling ☆`65`
- [adamjmurray/producer-pal](https://github.com/adamjmurray/producer-pal) — AI music production assistant for Ableton Live ☆`53`
- [dschuler36/reaper-mcp-server](https://github.com/dschuler36/reaper-mcp-server) — An MCP Server for interacting with Reaper projects. ☆`67`
- [SkyworkAI/Mureka-mcp](https://github.com/SkyworkAI/Mureka-mcp) — AI lyrics, song, and music generation ☆`66`
- [MoussaabBadla/code-screenshot-mcp](https://github.com/MoussaabBadla/code-screenshot-mcp) — MCP server for generating beautiful code screenshots directly from Claude ☆`43`
- [Laksh-star/mcp-server-tmdb](https://github.com/Laksh-star/mcp-server-tmdb) — MCP Server with TMDB ☆`55`
- [hamflx/imagen3-mcp](https://github.com/hamflx/imagen3-mcp) — MCP server for Google Imagen 3 image generation ☆`50`
- [tan-yong-sheng/ai-vision-mcp](https://github.com/tan-yong-sheng/ai-vision-mcp) — Image and video analysis capabilities ☆`30`
- [recraft-ai/mcp-recraft-server](https://github.com/recraft-ai/mcp-recraft-server) — MCP (modelcontextprotocol) server implementation for Recraft API ☆`45`
- [video-db/agent-toolkit](https://github.com/video-db/agent-toolkit) — MCP toolkit for video database operations ☆`44`
- [groundlight/mcp-vision](https://github.com/groundlight/mcp-vision) — Computer vision models as MCP servers ☆`49`
- [shinpr/mcp-image](https://github.com/shinpr/mcp-image) — MCP server for AI image generation and editing powered by Gemini 3 Pro Image Preview (Nano Banana Pro ). For Cursor, Codex & more. ☆`29`
- [veelenga/claude-mermaid](https://github.com/veelenga/claude-mermaid) — MCP Server to previewing mermaid diagrams ☆`29`
- [stass/exif-mcp](https://github.com/stass/exif-mcp) — MCP server to extract image metadata (EXIF, XMP, etc) ☆`28`
- [GongRzhe/Image-Generation-MCP-Server](https://github.com/GongRzhe/Image-Generation-MCP-Server) — This MCP server provides image generation capabilities using the Replicate Flux model. ☆`47`
- [nota/gyazo-mcp-server](https://github.com/nota/gyazo-mcp-server) — Official Model Context Protocol server for Gyazo ☆`25`
- [imprvhub/mcp-claude-spotify](https://github.com/imprvhub/mcp-claude-spotify) — Spotify interaction for Claude Desktop ☆`21`
- [GenWaveLLC/svgmaker-mcp](https://github.com/GenWaveLLC/svgmaker-mcp) — MCP server for SVG generation ☆`20`
- [Narasimhaponnada/mermaid-mcp](https://github.com/Narasimhaponnada/mermaid-mcp) — MCP server for Mermaid diagram generation ☆`20`
- [flowy11/imagician](https://github.com/flowy11/imagician) — A MCP server for image edition ☆`18`
- [raveenb/fal-mcp-server](https://github.com/raveenb/fal-mcp-server) — Fal.ai image, video, music generation ☆`17`
- [marcindulak/stt-mcp-server-linux](https://github.com/marcindulak/stt-mcp-server-linux) — Local speech-to-text for Tmux on Linux ☆`17`
- [sinjab/mcp_youtube_extract](https://github.com/sinjab/mcp_youtube_extract) — A Model Context Protocol (MCP) server for YouTube clip information extraction. ☆`16`
- [screenshotone/mcp](https://github.com/screenshotone/mcp) — A simple implementation of an MCP server for the ScreenshotOne API ☆`32`
- [PatrickPalmer/MayaMCP](https://github.com/PatrickPalmer/MayaMCP) — Autodesk Maya 3D integration ☆`32`
- [gpetraroli/mcp_pdf_reader](https://github.com/gpetraroli/mcp_pdf_reader) — An MCP server to extraxt/search text from pdf ☆`27`
- [InhiblabCore/mcp-image-compression](https://github.com/InhiblabCore/mcp-image-compression) — High-performance image compression service ☆`28`
- [magarcia/mcp-server-giphy](https://github.com/magarcia/mcp-server-giphy) — Giphy GIF integration ☆`26`
- [zxkane/mcp-server-amazon-bedrock](https://github.com/zxkane/mcp-server-amazon-bedrock) — Amazon Bedrock Nova Canvas image generation ☆`23`
- [upnorthmedia/ScreenshotMCP](https://github.com/upnorthmedia/ScreenshotMCP) — Website screenshot capture and optimization ☆`17`
- [omergocmen/json2video-mcp-server](https://github.com/omergocmen/json2video-mcp-server) — Message Communication Protocol server for json2video API integration ☆`23`
## Monitoring & Observability

- [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana) — MCP server for Grafana ☆`2,024`
- [getsentry/sentry-mcp](https://github.com/getsentry/sentry-mcp) — An MCP server for interacting with Sentry via LLMs. ☆`485`
- [dynatrace-oss/dynatrace-mcp](https://github.com/dynatrace-oss/dynatrace-mcp) — MCP server for Dynatrace Observability ☆`184`
- [traceloop/opentelemetry-mcp-server](https://github.com/traceloop/opentelemetry-mcp-server) — MCP server for OpenTelemetry observability ☆`146`
- [pydantic/logfire-mcp](https://github.com/pydantic/logfire-mcp) — The Logfire MCP Server is here! ☆`129`
- [mpeirone/zabbix-mcp-server](https://github.com/mpeirone/zabbix-mcp-server) — MCP server for Zabbix monitoring with 40+ tools ☆`122`
- [VictoriaMetrics-Community/mcp-victoriametrics](https://github.com/VictoriaMetrics-Community/mcp-victoriametrics) — VictoriaMetrics monitoring integration ☆`104`
- [grafana/loki-mcp](https://github.com/grafana/loki-mcp) — An MCP ( Model Context Protocol ) Server for Grafana Loki ☆`65`
- [seekrays/mcp-monitor](https://github.com/seekrays/mcp-monitor) — MCP server monitoring tool ☆`76`
- [axiomhq/mcp-server-axiom](https://github.com/axiomhq/mcp-server-axiom) — Axiom Model Context Protocol Server ☆`58`
- [hyperb1iss/lucidity-mcp](https://github.com/hyperb1iss/lucidity-mcp) — MCP server for enhanced AI clarity and reasoning ☆`74`
- [last9/last9-mcp-server](https://github.com/last9/last9-mcp-server) — Last9 MCP Server ☆`48`
- [metoro-io/metoro-mcp-server](https://github.com/metoro-io/metoro-mcp-server) — Metoro MCP Server ☆`45`
- [PagerDuty/pagerduty-mcp-server](https://github.com/PagerDuty/pagerduty-mcp-server) — PagerDuty's official local MCP (Model Context Protocol) server which provides tools to interact with your PagerDuty account directly from your MCP-enabled client. ☆`40`
- [GeLi2001/datadog-mcp-server](https://github.com/GeLi2001/datadog-mcp-server) — MCP server interacts with the official Datadog API ☆`58`
- [Rootly-AI-Labs/Rootly-MCP-server](https://github.com/Rootly-AI-Labs/Rootly-MCP-server) — Rootly MCP server ☆`36`
- [tjhop/prometheus-mcp-server](https://github.com/tjhop/prometheus-mcp-server) — MCP server for LLMs to interact with Prometheus ☆`29`
- [MindscapeHQ/mcp-server-raygun](https://github.com/MindscapeHQ/mcp-server-raygun) — Raygun error investigation for AI ☆`19`
- [RedHatInsights/insights-mcp](https://github.com/RedHatInsights/insights-mcp) — An MCP server to connect insights functionality to an AI / LLM ☆`16`
- [inspektor-gadget/ig-mcp-server](https://github.com/inspektor-gadget/ig-mcp-server) — Container and Kubernetes debugging with AI ☆`18`
- [Pratyay/mac-monitor-mcp](https://github.com/Pratyay/mac-monitor-mcp) — MCP server for macOS system monitoring ☆`16`
- [emicklei/mcp-log-proxy](https://github.com/emicklei/mcp-log-proxy) — a web logging proxy for MCP client-server communication ☆`26`
- [tumf/grafana-loki-mcp](https://github.com/tumf/grafana-loki-mcp) — Grafana Loki MCP Repository ☆`17`
- [tgeselle/bugsnag-mcp](https://github.com/tgeselle/bugsnag-mcp) — MCP server for Bugsnag error monitoring ☆`18`
## Official

- [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) — Model Context Protocol Servers ☆`74,999`
## Others

### MCP Clients

- [zed-industries/zed](https://github.com/zed-industries/zed) — High-performance code editor with MCP support ☆`72,061`
- [continuedev/continue](https://github.com/continuedev/continue) — Open-source AI coding assistant with MCP support ☆`30,511`
- [Upsonic/Upsonic](https://github.com/Upsonic/Upsonic) — Agent Framework For Fintech and Banks ☆`7,740`
- [firebase/genkit](https://github.com/firebase/genkit) — AI app framework for JavaScript and Go ☆`5,253`
- [ravitemer/mcphub.nvim](https://github.com/ravitemer/mcphub.nvim) — MCP client for Neovim with intuitive server management ☆`1,675`
- [evilsocket/nerve](https://github.com/evilsocket/nerve) — The Simple Agent Development Kit. ☆`1,313`
- [SecretiveShell/MCP-Bridge](https://github.com/SecretiveShell/MCP-Bridge) — OpenAI-compatible endpoint calling MCP tools ☆`883`
- [Lucassssss/eechat](https://github.com/Lucassssss/eechat) — Powerful Local AI Chat Application - Mcp, Secure, Efficient, Personalized 本地化部署的大模型客户端 ☆`315`
- [AI-QL/chat-mcp](https://github.com/AI-QL/chat-mcp) — A Desktop Chat App that leverages MCP(Model Context Protocol) to interface with other LLMs. ☆`242`
- [EvalsOne/MCP-connect](https://github.com/EvalsOne/MCP-connect) — Cloud AI access to local Stdio MCP servers ☆`227`
- [3choff/mcp-chatbot](https://github.com/3choff/mcp-chatbot) — CLI chatbot with MCP integration demo ☆`241`
- [johannesbrandenburger/typst-mcp](https://github.com/johannesbrandenburger/typst-mcp) — MCP server for Typst markup-based typesetting system ☆`91`
- [tanaikech/ToolsForMCPServer](https://github.com/tanaikech/ToolsForMCPServer) — MCP server built with Google Apps Script for Gemini CLI ☆`83`
- [xzq-xu/jvm-mcp-server](https://github.com/xzq-xu/jvm-mcp-server) — JVM-based MCP server implementation ☆`75`
- [ckanthony/gin-mcp](https://github.com/ckanthony/gin-mcp) — Enable MCP features for any Gin API with a line of code ☆`65`
- [rakesh-eltropy/mcp-client](https://github.com/rakesh-eltropy/mcp-client) — REST API and CLI client for MCP with LangChain ☆`51`
- [php-mcp/client](https://github.com/php-mcp/client) — Core PHP implementation for the Model Context Protocol (MCP) Client ☆`52`
- [zacharypodbela/django-rest-framework-mcp](https://github.com/zacharypodbela/django-rest-framework-mcp) — MCP server for Django REST Framework ☆`26`
### Frameworks & SDKs

- [quarkiverse/quarkus-mcp-servers](https://github.com/quarkiverse/quarkus-mcp-servers) — Model Context Protocol Servers in Quarkus ☆`179`
- [posit-dev/mcptools](https://github.com/posit-dev/mcptools) — Model Context Protocol For R ☆`144`
- [strowk/foxy-contexts](https://github.com/strowk/foxy-contexts) — Foxy contexts is a library for building context servers supporting Model Context Protocol ☆`109`
- [vishalmysore/a2ajava](https://github.com/vishalmysore/a2ajava) — Pure java implementation of Google A2A protocol. Integrate your spring boot java applications with A2A protocol , includes client and sever both. Any agent built with a2ajava will also be exposed as MCP tool automatically ☆`89`
- [mcpdotdirect/template-mcp-server](https://github.com/mcpdotdirect/template-mcp-server) — Template to quickly set up your own MCP server ☆`66`
- [abap-ai/mcp](https://github.com/abap-ai/mcp) — ABAP MCP - Model Context Protocol - Server SDK ☆`50`
- [domdomegg/programmatic-mcp-prototype](https://github.com/domdomegg/programmatic-mcp-prototype) — Prototype for programmatically calling and composing MCP tools ☆`22`
- [GongRzhe/MCP-Server-Creator](https://github.com/GongRzhe/MCP-Server-Creator) — A powerful Model Context Protocol (MCP) server that creates other MCP servers! This meta-server provides tools for dynamically generating FastMCP server configurations and Python code. ☆`33`
- [mcpx-dev/mcp-badges](https://github.com/mcpx-dev/mcp-badges) — Get your projects MCP (Model Context Protocol) badges ☆`29`
## Productivity

- [gornskew/lisply-mcp](https://github.com/gornskew/lisply-mcp) — Model Context Protocol (MCP) server to manage and talk to compliant "Lisply" lisp-speaking backend services ☆`39`
- [thechandanbhagat/cv-forge](https://github.com/thechandanbhagat/cv-forge) — MCP to tailored CV based on job description ☆`19`
### Collaboration

- [merill/lokka](https://github.com/merill/lokka) — MCP (Model Context Protocol) for Microsoft 365. Includes support for Microsoft Graph and other services ☆`209`
- [evalstate/mcp-miro](https://github.com/evalstate/mcp-miro) — MCP server for Miro whiteboard manipulation and sticky creation ☆`101`
- [pnp/cli-microsoft365-mcp-server](https://github.com/pnp/cli-microsoft365-mcp-server) — Manage Microsoft 365 using MCP server ☆`56`
- [hiromitsusasaki/raindrop-io-mcp-server](https://github.com/hiromitsusasaki/raindrop-io-mcp-server) — Raindrop.io bookmark management ☆`65`
- [k-jarzyna/mcp-miro](https://github.com/k-jarzyna/mcp-miro) — Miro integration for Model Context Protocol ☆`59`
- [aashari/mcp-server-atlassian-confluence](https://github.com/aashari/mcp-server-atlassian-confluence) — Atlassian Confluence spaces and pages ☆`43`
- [esignaturescom/mcp-server-esignatures](https://github.com/esignaturescom/mcp-server-esignatures) — eSignatures.com document signing ☆`31`
- [kintone/mcp-server](https://github.com/kintone/mcp-server) — kintone official MCP server ☆`30`
- [orellazri/coda-mcp](https://github.com/orellazri/coda-mcp) — MCP Server for Coda ☆`38`
- [Fibery-inc/fibery-mcp-server](https://github.com/Fibery-inc/fibery-mcp-server) — MCP server for Fibery workspace integration ☆`27`
### Google Workspace

- [taylorwilsdon/google_workspace_mcp](https://github.com/taylorwilsdon/google_workspace_mcp) — MCP server for Google Workspace integration ☆`1,020`
- [GongRzhe/Gmail-MCP-Server](https://github.com/GongRzhe/Gmail-MCP-Server) — A Model Context Protocol (MCP) server for Gmail integration in Claude Desktop with auto authentication support. This server enables AI assistants to manage Gmail through natural language interactions. ☆`874`
- [MarkusPfundstein/mcp-gsuite](https://github.com/MarkusPfundstein/mcp-gsuite) — MCP Server to interact with Google Gsuite prodcuts ☆`466`
- [baryhuang/mcp-headless-gmail](https://github.com/baryhuang/mcp-headless-gmail) — A MCP (Model Context Protocol) server that provides get, send Gmails without local credential or token setup. ☆`54`
- [giuseppe-coco/Google-Workspace-MCP-Server](https://github.com/giuseppe-coco/Google-Workspace-MCP-Server) — Gmail, Calendar, and Drive integration ☆`20`
### Helpdesk & Support

- [echelon-ai-labs/servicenow-mcp](https://github.com/echelon-ai-labs/servicenow-mcp) — MCP Server for ServiceNow ☆`176`
- [effytech/freshdesk_mcp](https://github.com/effytech/freshdesk_mcp) — Freshdesk support ticket integration ☆`35`
- [modesty/fluent-mcp](https://github.com/modesty/fluent-mcp) — MCP server for Fluent (ServiceNow SDK) ☆`16`
- [quickchatai/quickchat-ai-mcp](https://github.com/quickchatai/quickchat-ai-mcp) — The Quickchat AI MCP server ☆`21`
### Learning & Flashcards

- [scorzeth/anki-mcp-server](https://github.com/scorzeth/anki-mcp-server) — An MCP server for Anki ☆`177`
- [ankimcp/anki-mcp-server](https://github.com/ankimcp/anki-mcp-server) — MCP server for Anki spaced repetition flashcards ☆`60`
- [rember/rember-mcp](https://github.com/rember/rember-mcp) — A Model Context Protocol (MCP) server for Rember. ☆`59`
- [nietus/anki-mcp](https://github.com/nietus/anki-mcp) — MCP server for anki ☆`38`
### Note-taking & Docs

- [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server) — Official Notion MCP Server ☆`3,625`
- [MarkusPfundstein/mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) — Obsidian integration via REST API plugin ☆`2,579`
- [GongRzhe/Office-PowerPoint-MCP-Server](https://github.com/GongRzhe/Office-PowerPoint-MCP-Server) — A MCP (Model Context Protocol) server for PowerPoint manipulation using python-pptx. This server provides tools for creating, editing, and manipulating PowerPoint presentations through the MCP protocol. ☆`1,350`
- [GongRzhe/Office-Word-MCP-Server](https://github.com/GongRzhe/Office-Word-MCP-Server) — A Model Context Protocol (MCP) server for creating, reading, and manipulating Microsoft Word documents. This server enables AI assistants to work with Word documents through a standardized interface, providing rich document editing capabilities. ☆`1,268`
- [smithery-ai/mcp-obsidian](https://github.com/smithery-ai/mcp-obsidian) — Obsidian vault read and search for Claude ☆`1,243`
- [suekou/mcp-notion-server](https://github.com/suekou/mcp-notion-server) — MCP server for Notion API with Markdown conversion ☆`842`
- [StevenStavrakis/obsidian-mcp](https://github.com/StevenStavrakis/obsidian-mcp) — A simple MCP server for Obsidian ☆`604`
- [RafalWilinski/mcp-apple-notes](https://github.com/RafalWilinski/mcp-apple-notes) — RAG over Apple Notes for Claude ☆`322`
- [bitbonsai/mcp-obsidian](https://github.com/bitbonsai/mcp-obsidian) — Lightweight Obsidian vault access ☆`265`
- [danhilse/notion_mcp](https://github.com/danhilse/notion_mcp) — Notion integration with advanced formatting ☆`204`
- [lostintangent/gistpad-mcp](https://github.com/lostintangent/gistpad-mcp) — Personal knowledge and daily notes management ☆`179`
- [onebirdrocks/ebook-mcp](https://github.com/onebirdrocks/ebook-mcp) — MCP server for ebook processing ☆`166`
- [Vortiago/mcp-outline](https://github.com/Vortiago/mcp-outline) — A Model Context Protocol (MCP) server enabling AI assistants to interact with Outline documentation services. ☆`68`
- [ivo-toby/contentful-mcp](https://github.com/ivo-toby/contentful-mcp) — Contentful CMS Management API ☆`61`
- [baruchiro/paperless-mcp](https://github.com/baruchiro/paperless-mcp) — MCP server for Paperless-NGX document management ☆`47`
- [Badhansen/notion-mcp](https://github.com/Badhansen/notion-mcp) — Notion workspace management ☆`27`
- [akseyh/bear-mcp-server](https://github.com/akseyh/bear-mcp-server) — MCP Server integration for Bear note app ☆`41`
- [pinecone-io/assistant-mcp](https://github.com/pinecone-io/assistant-mcp) — Pinecone Assistant MCP server ☆`40`
- [vgnshiyer/apple-books-mcp](https://github.com/vgnshiyer/apple-books-mcp) — Apple Books MCP Server ☆`35`
- [danield137/mcp-workflowy](https://github.com/danield137/mcp-workflowy) — An MCP server for workflowy ☆`23`
- [agentset-ai/mcp-server](https://github.com/agentset-ai/mcp-server) — Agentset MCP Server - Build RAG with Agentic superpowers ☆`25`
- [Harry-027/JotDown](https://github.com/Harry-027/JotDown) — An MCP Server in Rust for creating Notion pages & mdBooks with LLMs ☆`19`
### Project Management

- [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) — MCP server for Atlassian tools (Confluence, Jira) ☆`3,850`
- [mondaycom/mcp](https://github.com/mondaycom/mcp) — Enable AI agents to work reliably - giving them secure access to structured data, tools to take action, and the context needed to make smart decisions. ☆`351`
- [jerhadf/linear-mcp-server](https://github.com/jerhadf/linear-mcp-server) — MCP server for Linear issue tracking ☆`339`
- [makeplane/plane-mcp-server](https://github.com/makeplane/plane-mcp-server) — Plane's Official Model Context Protocol Server ☆`125`
- [its-dart/dart-mcp-server](https://github.com/its-dart/dart-mcp-server) — Dart AI Model Context Protocol (MCP) server ☆`124`
- [tacticlaunch/mcp-linear](https://github.com/tacticlaunch/mcp-linear) — MCP server for Linear project management ☆`121`
- [roychri/mcp-server-asana](https://github.com/roychri/mcp-server-asana) — MCP server for Asana task and project management ☆`110`
- [useshortcut/mcp-server-shortcut](https://github.com/useshortcut/mcp-server-shortcut) — The MCP server for Shortcut ☆`82`
- [taskade/mcp](https://github.com/taskade/mcp) — MCP server for Taskade project management ☆`94`
- [nguyenvanduocit/jira-mcp](https://github.com/nguyenvanduocit/jira-mcp) — Jira issues and sprints via Go MCP ☆`73`
- [tonyzorin/youtrack-mcp](https://github.com/tonyzorin/youtrack-mcp) — Model Context Protocol Server for YouTrack - Multi-platform support (ARM64/Apple Silicon + AMD64) with comprehensive API integration ☆`73`
- [aashari/mcp-server-atlassian-jira](https://github.com/aashari/mcp-server-atlassian-jira) — Atlassian Jira projects, issues and sprints ☆`48`
- [feuerdev/keep-mcp](https://github.com/feuerdev/keep-mcp) — MCP server for Google Keep ☆`56`
- [kelvin6365/plane-mcp-server](https://github.com/kelvin6365/plane-mcp-server) — MCP server for Plane.so project management ☆`34`
- [m0xai/trello-mcp-server](https://github.com/m0xai/trello-mcp-server) — A simple yet powerful MCP server for Trello. ☆`44`
- [phuc-nt/mcp-atlassian-server](https://github.com/phuc-nt/mcp-atlassian-server) — MCP server connecting AI assistants with Jira & Confluence for smart project management. ☆`47`
- [aikts/yandex-tracker-mcp](https://github.com/aikts/yandex-tracker-mcp) — Yandex Tracker MCP Server with OAuth2 support ☆`32`
- [georgeantonopoulos/Basecamp-MCP-Server](https://github.com/georgeantonopoulos/Basecamp-MCP-Server) — Basecamp 3+ project management ☆`46`
- [KS-GEN-AI/jira-mcp-server](https://github.com/KS-GEN-AI/jira-mcp-server) — A test of jira mcp server ☆`25`
- [EduBase/MCP](https://github.com/EduBase/MCP) — MCP server for EduBase e-learning platform ☆`24`
- [Prat011/mcp-server-monday](https://github.com/Prat011/mcp-server-monday) — MCP Server to interact with Monday.com boards and items ☆`32`
- [bivex/kanboard-mcp](https://github.com/bivex/kanboard-mcp) — MCP server for Kanboard project management integration ☆`18`
- [danielkennedy1/pdf-tools-mcp](https://github.com/danielkennedy1/pdf-tools-mcp) — MCP server for PDF manipulation (merge, extract, snippets) ☆`31`
- [rahulthedevil/Jira-Context-MCP](https://github.com/rahulthedevil/Jira-Context-MCP) — Jira tickets info for AI coding agents ☆`24`
### Tasks & Calendar

- [mediar-ai/screenpipe](https://github.com/mediar-ai/screenpipe) — AI app store with 24/7 desktop history ☆`16,260`
- [nspady/google-calendar-mcp](https://github.com/nspady/google-calendar-mcp) — MCP integration for Google Calendar to manage events. ☆`836`
- [abhiz123/todoist-mcp-server](https://github.com/abhiz123/todoist-mcp-server) — Todoist natural language task management ☆`340`
- [Doist/todoist-ai](https://github.com/Doist/todoist-ai) — A set of tools to connect to AI agents, to allow them to use Todoist on a user's behalf. Includes MCP support. ☆`222`
- [Omar-V2/mcp-ical](https://github.com/Omar-V2/mcp-ical) — A Model Context Protocol Server that allows you to interact with your MacOS Calendar through natural language. ☆`217`
- [zcaceres/gtasks-mcp](https://github.com/zcaceres/gtasks-mcp) — A Google Tasks Model Context Protocol Server for Claude ☆`97`
- [takumi0706/google-calendar-mcp](https://github.com/takumi0706/google-calendar-mcp) — Google Calendar for Claude Desktop ☆`53`
- [stanislavlysenko0912/todoist-mcp-server](https://github.com/stanislavlysenko0912/todoist-mcp-server) — Todoist Rest API and Sync API ☆`49`
- [alexarevalo9/ticktick-mcp-server](https://github.com/alexarevalo9/ticktick-mcp-server) — A Model Context Protocol (MCP) server designed to integrate with the TickTick task management platform, enabling intelligent context-aware task operations and automation. ☆`46`
- [arpitbatra123/mcp-googletasks](https://github.com/arpitbatra123/mcp-googletasks) — MCP server for Google Tasks management ☆`28`
- [jen6/ticktick-mcp](https://github.com/jen6/ticktick-mcp) — TickTick task management with filtering ☆`42`
- [dominik1001/caldav-mcp](https://github.com/dominik1001/caldav-mcp) — CalDAV calendar sync ☆`40`
- [awwaiid/mcp-server-taskwarrior](https://github.com/awwaiid/mcp-server-taskwarrior) — MCP Server for TaskWarrior! ☆`39`
- [flesler/mcp-tasks](https://github.com/flesler/mcp-tasks) — Efficient task management with views ☆`33`
- [jbrinkman/valkey-ai-tasks](https://github.com/jbrinkman/valkey-ai-tasks) — MCP server for task management with Valkey persistence ☆`23`
### Wiki & Collaboration

- [anyproto/anytype-mcp](https://github.com/anyproto/anytype-mcp) — An MCP server enabling AI assistants to interact with Anytype - your encrypted, local and collaborative wiki - to organize objects, lists, and more through natural language. ☆`237`
- [ProfessionalWiki/MediaWiki-MCP-Server](https://github.com/ProfessionalWiki/MediaWiki-MCP-Server) — Model Context Protocol (MCP) Server to connect your AI with any MediaWiki ☆`46`
- [yuna0x0/hackmd-mcp](https://github.com/yuna0x0/hackmd-mcp) — HackMD note-taking integration ☆`45`
- [HenryHaoson/Yuque-MCP-Server](https://github.com/HenryHaoson/Yuque-MCP-Server) — Yuque mcp server ☆`40`
## Research & Science

- [oOo0oOo/lean-lsp-mcp](https://github.com/oOo0oOo/lean-lsp-mcp) — Lean Theorem Prover MCP ☆`205`
- [szeider/mcp-solver](https://github.com/szeider/mcp-solver) — Model Context Protocol (MCP) server for constraint optimization and solving" ☆`145`
- [SecretiveShell/MCP-wolfram-alpha](https://github.com/SecretiveShell/MCP-wolfram-alpha) — Wolfram Alpha computational intelligence ☆`69`
- [NellyW8/MCP4EDA](https://github.com/NellyW8/MCP4EDA) — This is the Github Repo for the paper: MCP4EDA: LLM-Powered Model Context Protocol RTL-to-GDSII Automation with Backend Aware Synthesis Optimization. MCP server for a collection of open-source EDA tools ☆`50`
- [reeeeemo/ancestry-mcp](https://github.com/reeeeemo/ancestry-mcp) — Ancestry genealogy data interaction ☆`29`
## Sandboxing & Execution

- [zerocore-ai/microsandbox](https://github.com/zerocore-ai/microsandbox) — opensource self-hosted sandboxes for ai agent ☆`4,245`
- [dagger/container-use](https://github.com/dagger/container-use) — MCP server for container orchestration ☆`3,362`
- [e2b-dev/mcp-server](https://github.com/e2b-dev/mcp-server) — E2B code execution for Claude ☆`362`
- [Automata-Labs-team/code-sandbox-mcp](https://github.com/Automata-Labs-team/code-sandbox-mcp) — An MCP server to create secure code sandbox environment for executing code within Docker containers. This MCP server provides AI applications with a safe and isolated environment for running code while maintaining security through containerization. ☆`298`
- [bazinga012/mcp_code_executor](https://github.com/bazinga012/mcp_code_executor) — The MCP Code Executor is an MCP server that allows LLMs to execute Python code within a specified Conda environment. ☆`212`
- [ckanthony/openapi-mcp](https://github.com/ckanthony/openapi-mcp) — Dockerized OpenAPI to MCP conversion ☆`164`
- [alfonsograziano/node-code-sandbox-mcp](https://github.com/alfonsograziano/node-code-sandbox-mcp) — MCP server for Node.js code sandbox execution ☆`141`
- [gradion-ai/ipybox](https://github.com/gradion-ai/ipybox) — Python code sandbox with programmatic MCP tool calling for AI agents ☆`54`
- [yepcode/mcp-server-js](https://github.com/yepcode/mcp-server-js) — JavaScript MCP server framework by YepCode ☆`41`
- [r33drichards/mcp-js](https://github.com/r33drichards/mcp-js) — MCP server exposing V8 JavaScript runtime for AI agents ☆`27`
- [hileamlakB/Python-Runtime-Interpreter-MCP-Server](https://github.com/hileamlakB/Python-Runtime-Interpreter-MCP-Server) — Safe Python runtime interpreter ☆`24`
- [criteo/openapi-to-mcp](https://github.com/criteo/openapi-to-mcp) — An MCP server for your API ☆`27`
- [gwbischof/outsource-mcp](https://github.com/gwbischof/outsource-mcp) — Give your AI assistant its own AI assistants. ☆`28`
## Search & Extraction

- [gleanwork/mcp-server](https://github.com/gleanwork/mcp-server) — MCP server for Glean API integration ☆`52`
- [anysiteio/anysite-mcp-server](https://github.com/anysiteio/anysite-mcp-server) — A Model Context Protocol (MCP) server that provides comprehensive access to LinkedIn data and functionalities using the Anysite API, enabling not only data retrieval but also robust management of user accounts. ☆`48`
- [ubie-oss/mcp-vertexai-search](https://github.com/ubie-oss/mcp-vertexai-search) — A MCP server for Vertex AI Search ☆`32`
### Academic Research

- [blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server) — arXiv paper search and analysis ☆`1,975`
- [reading-plus-ai/mcp-server-deep-research](https://github.com/reading-plus-ai/mcp-server-deep-research) — Comprehensive research with reports ☆`195`
- [JackKuo666/Google-Scholar-MCP-Server](https://github.com/JackKuo666/Google-Scholar-MCP-Server) — A MCP Server for Google Scholar: Enable AI assistants to search and access Google Scholar papers through a simple MCP interface. ☆`184`
- [andybrandt/mcp-simple-arxiv](https://github.com/andybrandt/mcp-simple-arxiv) — arXiv paper search and reading ☆`176`
- [andybrandt/mcp-simple-pubmed](https://github.com/andybrandt/mcp-simple-pubmed) — PubMed medical research search ☆`147`
- [adityak74/mcp-scholarly](https://github.com/adityak74/mcp-scholarly) — A MCP server to search for accurate academic articles. ☆`165`
- [JackKuo666/PubMed-MCP-Server](https://github.com/JackKuo666/PubMed-MCP-Server) — Enable AI assistants to search, access, and analyze PubMed articles through a simple MCP interface. ☆`85`
- [takashiishida/arxiv-latex-mcp](https://github.com/takashiishida/arxiv-latex-mcp) — MCP server for arXiv LaTeX paper retrieval ☆`77`
- [OctagonAI/octagon-deep-research-mcp](https://github.com/OctagonAI/octagon-deep-research-mcp) — AI-powered comprehensive research and analysis ☆`79`
- [HzaCode/OneCite](https://github.com/HzaCode/OneCite) — An intelligent toolkit to automatically parse, complete, and format academic references. ☆`46`
- [akalaric/mcp-wolframalpha](https://github.com/akalaric/mcp-wolframalpha) — Wolfram Alpha integration for Python ☆`56`
- [prashalruchiranga/arxiv-mcp-server](https://github.com/prashalruchiranga/arxiv-mcp-server) — An MCP server that enables interacting with the arXiv API using natural language ☆`36`
- [szeider/mcp-dblp](https://github.com/szeider/mcp-dblp) — A Model Context Protocol (MCP) server that provides access to the DBLP computer science bibliography database for Large Language Models. ☆`17`
- [drAbreu/alex-mcp](https://github.com/drAbreu/alex-mcp) — MCP server for OpenAlex ☆`25`
- [JackKuo666/bioRxiv-MCP-Server](https://github.com/JackKuo666/bioRxiv-MCP-Server) — Enable AI assistants to search and access bioRxiv papers through a simple MCP interface. ☆`20`
### Data APIs

- [cantian-ai/bazi-mcp](https://github.com/cantian-ai/bazi-mcp) — Bazi Chinese astrology information ☆`229`
- [hellokaton/unsplash-mcp-server](https://github.com/hellokaton/unsplash-mcp-server) — A MCP server for Unsplash image search. ☆`193`
- [Rudra-ravi/wikipedia-mcp](https://github.com/Rudra-ravi/wikipedia-mcp) — A Model Context Protocol (MCP) server that retrieves information from Wikipedia to provide context to LLMs. ☆`160`
- [deadletterq/mcp-opennutrition](https://github.com/deadletterq/mcp-opennutrition) — MCP server for nutrition data and analysis ☆`146`
- [OpenDataMCP/OpenDataMCP](https://github.com/OpenDataMCP/OpenDataMCP) — Connect any Open Data to any LLM with Model Context Protocol. ☆`144`
- [ahonn/mcp-server-gsc](https://github.com/ahonn/mcp-server-gsc) — Google Search Console data access ☆`90`
- [cswkim/discogs-mcp-server](https://github.com/cswkim/discogs-mcp-server) — MCP Server for Discogs ☆`77`
- [yuna0x0/anilist-mcp](https://github.com/yuna0x0/anilist-mcp) — AniList MCP server for accessing anime and manga data ☆`64`
- [zoomeye-ai/mcp_zoomeye](https://github.com/zoomeye-ai/mcp_zoomeye) — MCP server for ZoomEye network asset information ☆`59`
- [8enSmith/mcp-open-library](https://github.com/8enSmith/mcp-open-library) — MCP server for Open Library book and author search ☆`47`
- [r-huijts/rijksmuseum-mcp](https://github.com/r-huijts/rijksmuseum-mcp) — Rijksmuseum artwork exploration ☆`62`
- [djalal/quran-mcp-server](https://github.com/djalal/quran-mcp-server) — Quran.com verses, translations, tafsir ☆`55`
- [yamanoku/baseline-mcp-server](https://github.com/yamanoku/baseline-mcp-server) — Web API Baseline status information ☆`36`
- [0xDAEF0F/job-searchoor](https://github.com/0xDAEF0F/job-searchoor) — A simple MCP server that delivers you jobs based on your needs ☆`55`
- [riemannzeta/patent_mcp_server](https://github.com/riemannzeta/patent_mcp_server) — FastMCP Server for USPTO data ☆`33`
- [imprvhub/mcp-domain-availability](https://github.com/imprvhub/mcp-domain-availability) — MCP server to check domain availability ☆`29`
- [Linked-API/linkedapi-mcp](https://github.com/Linked-API/linkedapi-mcp) — LinkedIn account control and data retrieval ☆`29`
- [kehvinbehvin/json-mcp-filter](https://github.com/kehvinbehvin/json-mcp-filter) — JSON MCP server to filter only relevant data for your LLM ☆`20`
- [DappierAI/dappier-mcp](https://github.com/DappierAI/dappier-mcp) — MCP server for Dappier AI integration ☆`38`
- [adawalli/nexus](https://github.com/adawalli/nexus) — MCP Server to make searching openrouter easy ☆`19`
- [siva010928/multi-chat-mcp-server](https://github.com/siva010928/multi-chat-mcp-server) — MCP server for multi-chat capabilities ☆`17`
- [r-huijts/opentk-mcp](https://github.com/r-huijts/opentk-mcp) — MCP server for Dutch parliamentary data via OpenTK ☆`16`
- [DumplingAI/mcp-server-dumplingai](https://github.com/DumplingAI/mcp-server-dumplingai) — MCP (Model Context Protocol) server for Dumpling AI ☆`29`
- [zzaebok/mcp-wikidata](https://github.com/zzaebok/mcp-wikidata) — A server implementation for Wikidata API using the Model Context Protocol (MCP). ☆`31`
- [delorenj/mcp-server-ticketmaster](https://github.com/delorenj/mcp-server-ticketmaster) — A Ticketmaster MCP server that provides query capabilites from the Discovery API ☆`22`
- [damionrashford/RivalSearchMCP](https://github.com/damionrashford/RivalSearchMCP) — MCP server for competitive search analysis ☆`21`
- [mikechao/metmuseum-mcp](https://github.com/mikechao/metmuseum-mcp) — Met Museum art collection discovery ☆`20`
- [amurshak/congressMCP](https://github.com/amurshak/congressMCP) — US Congress data for AI agents ☆`20`
- [angheljf/nyt](https://github.com/angheljf/nyt) — MCP server for New York Times article search ☆`16`
### News & Content

- [lfnovo/content-core](https://github.com/lfnovo/content-core) — Extract what matters from any media source ☆`107`
- [erithwik/mcp-hn](https://github.com/erithwik/mcp-hn) — MCP Server for Hackernews ☆`56`
- [imprvhub/mcp-rss-aggregator](https://github.com/imprvhub/mcp-rss-aggregator) — RSS feed aggregation for Claude Desktop ☆`20`
- [pskill9/hn-server](https://github.com/pskill9/hn-server) — Hacker news MCP server ☆`35`
- [format37/youtube_mcp](https://github.com/format37/youtube_mcp) — youtube transcriber mcp server ☆`26`
- [the0807/GeekNews-MCP-Server](https://github.com/the0807/GeekNews-MCP-Server) — GeekNews MCP Server ☆`16`
### Web Scraping & Crawling

- [ScrapeGraphAI/Scrapegraph-ai](https://github.com/ScrapeGraphAI/Scrapegraph-ai) — Python scraper based on AI ☆`22,068`
- [jae-jae/fetcher-mcp](https://github.com/jae-jae/fetcher-mcp) — Playwright web page content fetching ☆`939`
- [apify/apify-mcp-server](https://github.com/apify/apify-mcp-server) — MCP server for Apify web scraping and data extraction ☆`658`
- [apify/mcp-server-rag-web-browser](https://github.com/apify/mcp-server-rag-web-browser) — A MCP Server for the RAG Web Browser Actor ☆`195`
- [tinyfish-io/agentql-mcp](https://github.com/tinyfish-io/agentql-mcp) — AgentQL data extraction integration ☆`137`
- [just-every/mcp-read-website-fast](https://github.com/just-every/mcp-read-website-fast) — Fast webpage to markdown conversion ☆`119`
- [oxylabs/oxylabs-mcp](https://github.com/oxylabs/oxylabs-mcp) — Official Oxylabs MCP integration ☆`77`
- [just-every/mcp-screenshot-website-fast](https://github.com/just-every/mcp-screenshot-website-fast) — Fast webpage screenshots for LLMs ☆`94`
- [cyberchitta/scrapling-fetch-mcp](https://github.com/cyberchitta/scrapling-fetch-mcp) — Helps AI assistants access text content from bot-protected websites. MCP server that fetches HTML/markdown from sites with anti-automation measures using Scrapling. ☆`58`
- [scrapeless-ai/scrapeless-mcp-server](https://github.com/scrapeless-ai/scrapeless-mcp-server) — Scrapeless Mcp Server ☆`61`
- [crawlbase/crawlbase-mcp](https://github.com/crawlbase/crawlbase-mcp) — MCP server connecting AI agents with real-time web data ☆`40`
- [webscraping-ai/webscraping-ai-mcp-server](https://github.com/webscraping-ai/webscraping-ai-mcp-server) — MCP server for AI-powered web scraping ☆`35`
- [pragmar/mcp-server-webcrawl](https://github.com/pragmar/mcp-server-webcrawl) — Web crawler data and archives connection ☆`34`
- [ananddtyagi/webpage-screenshot-mcp](https://github.com/ananddtyagi/webpage-screenshot-mcp) — MCP server for webpage screenshot capture ☆`45`
- [puremd/puremd-mcp](https://github.com/puremd/puremd-mcp) — Unblock, scrape, and search tools for MCP clients ☆`48`
- [wong2/mcp-jina-reader](https://github.com/wong2/mcp-jina-reader) — Jina Reader MCP Server ☆`46`
- [Decodo/mcp-web-scraper](https://github.com/Decodo/mcp-web-scraper) — Decodo web scraping for MCP clients ☆`17`
- [supadata-ai/mcp](https://github.com/supadata-ai/mcp) — Video and web scraping for Claude ☆`24`
### Web Search Engines

- [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) — Exa MCP for web search and web crawling! ☆`3,447`
- [tavily-ai/tavily-mcp](https://github.com/tavily-ai/tavily-mcp) — Real-time search, extract, map and crawl ☆`1,024`
- [nickclyde/duckduckgo-mcp-server](https://github.com/nickclyde/duckduckgo-mcp-server) — MCP server for DuckDuckGo search ☆`700`
- [Aas-ee/open-webSearch](https://github.com/Aas-ee/open-webSearch) — MCP server for open web search ☆`543`
- [brave/brave-search-mcp-server](https://github.com/brave/brave-search-mcp-server) — Brave Search with AI summarization ☆`437`
- [mrkrsl/web-search-mcp](https://github.com/mrkrsl/web-search-mcp) — Local web search for Claude Desktop ☆`410`
- [ihor-sokoliuk/mcp-searxng](https://github.com/ihor-sokoliuk/mcp-searxng) — MCP Server for SearXNG ☆`367`
- [kagisearch/kagimcp](https://github.com/kagisearch/kagimcp) — Official Kagi search MCP server ☆`240`
- [jae-jae/g-search-mcp](https://github.com/jae-jae/g-search-mcp) — Parallel Google search with summaries ☆`235`
- [meilisearch/meilisearch-mcp](https://github.com/meilisearch/meilisearch-mcp) — Meilisearch interaction via LLM interfaces ☆`158`
- [fatwang2/search1api-mcp](https://github.com/fatwang2/search1api-mcp) — MCP server for web search and crawl via Search1API ☆`159`
- [ChanMeng666/server-google-news](https://github.com/ChanMeng666/server-google-news) — MCP server for Google News integration ☆`98`
- [nkapila6/mcp-local-rag](https://github.com/nkapila6/mcp-local-rag) — RAG-like web search via MCP ☆`95`
- [SecretiveShell/MCP-searxng](https://github.com/SecretiveShell/MCP-searxng) — SearXNG search for agentic systems ☆`108`
- [vectorize-io/vectorize-mcp-server](https://github.com/vectorize-io/vectorize-mcp-server) — Official Vectorize MCP Server ☆`101`
- [serpapi/serpapi-mcp](https://github.com/serpapi/serpapi-mcp) — SerpApi MCP Server for Google and other search engine results ☆`77`
- [mikechao/brave-search-mcp](https://github.com/mikechao/brave-search-mcp) — MCP server for Brave Search with filtering options ☆`88`
- [tanigami/mcp-server-perplexity](https://github.com/tanigami/mcp-server-perplexity) — Perplexity API chat with citations ☆`87`
- [ConechoAI/openai-websearch-mcp](https://github.com/ConechoAI/openai-websearch-mcp) — openai websearch tool as mcp server ☆`78`
- [isnow890/naver-search-mcp](https://github.com/isnow890/naver-search-mcp) — MCP server for Naver search integration ☆`47`
- [zhsama/duckduckgo-mcp-server](https://github.com/zhsama/duckduckgo-mcp-server) — MCP server for DuckDuckGo web search ☆`68`
- [leehanchung/bing-search-mcp](https://github.com/leehanchung/bing-search-mcp) — MCP Server for Bing Search API ☆`67`
- [Tomatio13/mcp-server-tavily](https://github.com/Tomatio13/mcp-server-tavily) — MCP Server for Tavily API integration ☆`46`
- [algolia/mcp](https://github.com/algolia/mcp) — MCP servers for interacting with Algolia ☆`25`
- [garylab/serper-mcp-server](https://github.com/garylab/serper-mcp-server) — A Serper MCP Server ☆`22`
- [ac3xx/mcp-servers-kagi](https://github.com/ac3xx/mcp-servers-kagi) — A Model Context Protocol server implementation for Kagi's API ☆`41`
- [OvertliDS/mcp-searxng-enhanced](https://github.com/OvertliDS/mcp-searxng-enhanced) — SearXNG web search with category awareness ☆`28`
- [pwilkin/mcp-searxng-public](https://github.com/pwilkin/mcp-searxng-public) — An MCP server that queries public SearXNG instances, parsing HTML contents into a JSON result ☆`28`
- [mnhlt/WebSearch-MCP](https://github.com/mnhlt/WebSearch-MCP) — MCP server for web search integration ☆`22`
## Security

### Identity & Access

- [box-community/mcp-server-box](https://github.com/box-community/mcp-server-box) — Enterprise content access in Box ☆`88`
- [auth0/auth0-mcp-server](https://github.com/auth0/auth0-mcp-server) —  ☆`83`
- [firstorderai/authenticator_mcp](https://github.com/firstorderai/authenticator_mcp) — Authenticator App for AI agents ☆`30`
- [atomicchonk/roadrecon_mcp_server](https://github.com/atomicchonk/roadrecon_mcp_server) — Azure AD ROADrecon analysis for Claude ☆`48`
- [sshaaf/keycloak-mcp-server](https://github.com/sshaaf/keycloak-mcp-server) — MCP server for Keycloak identity and access management ☆`19`
- [ChristophEnglisch/keycloak-model-context-protocol](https://github.com/ChristophEnglisch/keycloak-model-context-protocol) — Keycloak user and realm management ☆`34`
- [hieuttmmo/entraid-mcp-server](https://github.com/hieuttmmo/entraid-mcp-server) — EntraID via Microsoft Graph API ☆`31`
- [kapilduraphe/okta-mcp-server](https://github.com/kapilduraphe/okta-mcp-server) — Okta MCP Server ☆`19`
### MCP Security

- [eqtylab/mcp-guardian](https://github.com/eqtylab/mcp-guardian) — Manage / Proxy / Secure your MCP Servers ☆`188`
- [kapilduraphe/mcp-watch](https://github.com/kapilduraphe/mcp-watch) — A comprehensive security scanner for Model Context Protocol (MCP) servers that detects vulnerabilities and security issues in your MCP server implementations. ☆`113`
- [postralai/masquerade](https://github.com/postralai/masquerade) — The Privacy Firewall for LLMs ☆`72`
- [82ch/MCP-Dandan](https://github.com/82ch/MCP-Dandan) — MCP security with real-time proxying ☆`58`
- [AIM-Intelligence/AIM-MCP](https://github.com/AIM-Intelligence/AIM-MCP) — AIM MCP Server :: Guard and Protect your MCPs & AI Chatting ☆`16`
- [cromwellian/hippycampus](https://github.com/cromwellian/hippycampus) — REST endpoint to MCP conversion ☆`20`
- [kontext-dev/attestable-mcp-server](https://github.com/kontext-dev/attestable-mcp-server) — Hardware attestation for MCP server integrity ☆`17`
### Network & Firewall

- [vespo92/OPNSenseMCP](https://github.com/vespo92/OPNSenseMCP) — MCP Server for OPNSense to act as IaC proxy ☆`27`
- [intruder-io/intruder-mcp](https://github.com/intruder-io/intruder-mcp) — An MCP server to let AI agents control Intruder ☆`22`
### Reverse Engineering

- [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) — MCP Server for Ghidra ☆`6,805`
- [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) — IDA Pro reverse engineering with AI ☆`4,737`
- [zinja-coder/jadx-ai-mcp](https://github.com/zinja-coder/jadx-ai-mcp) — Plugin for JADX to integrate MCP server ☆`920`
- [jtang613/GhidrAssistMCP](https://github.com/jtang613/GhidrAssistMCP) — An MCP extension for Ghidra ☆`383`
- [zinja-coder/apktool-mcp-server](https://github.com/zinja-coder/apktool-mcp-server) — APK Tool for Android reverse engineering ☆`269`
- [fosdickio/binary_ninja_mcp](https://github.com/fosdickio/binary_ninja_mcp) — Binary Ninja plugin for LLM integration ☆`139`
- [radareorg/radare2-mcp](https://github.com/radareorg/radare2-mcp) — MCP stdio server for radare2 ☆`116`
- [13bm/GhidraMCP](https://github.com/13bm/GhidraMCP) — Socket based MCP Server for Ghidra ☆`82`
- [zboralski/ida-headless-mcp](https://github.com/zboralski/ida-headless-mcp) — Headless IDA Pro binary analysis via Model Context Protocol ☆`22`
- [pullkitsan/mobsf-mcp-server](https://github.com/pullkitsan/mobsf-mcp-server) — MobSF APK and IPA security scanning ☆`18`
### SIEM & SecOps

- [mariocandela/beelzebub](https://github.com/mariocandela/beelzebub) — Low-code honeypot with AI virtualization ☆`1,772`
- [MorDavid/BloodHound-MCP-AI](https://github.com/MorDavid/BloodHound-MCP-AI) — BloodHound integration with AI through MCP ☆`321`
- [gbrigandi/mcp-server-wazuh](https://github.com/gbrigandi/mcp-server-wazuh) — MCP Server for Wazuh SIEM ☆`153`
- [securityfortech/secops-mcp](https://github.com/securityfortech/secops-mcp) — All-in-one security testing toolbox via MCP ☆`167`
- [CrowdStrike/falcon-mcp](https://github.com/CrowdStrike/falcon-mcp) — Connect AI agents to CrowdStrike Falcon for automated security analysis and threat hunting ☆`82`
- [panther-labs/mcp-panther](https://github.com/panther-labs/mcp-panther) — Detections, alerts, and log queries ☆`36`
- [qianniuspace/mcp-security-audit](https://github.com/qianniuspace/mcp-security-audit) — MCP server for security auditing ☆`49`
- [fr0gger/MCP_Security](https://github.com/fr0gger/MCP_Security) — This is a repository to experiment with MCP for security ☆`45`
- [Gaffx/volatility-mcp](https://github.com/Gaffx/volatility-mcp) — This repo hosts an MCP server for volatility3.x ☆`36`
- [slouchd/cyberchef-api-mcp-server](https://github.com/slouchd/cyberchef-api-mcp-server) — CyberChef API MCP Server ☆`31`
### Vulnerability & Threat Intel

- [PortSwigger/mcp-server](https://github.com/PortSwigger/mcp-server) — MCP Server for Burp ☆`407`
- [BurtTheCoder/mcp-maigret](https://github.com/BurtTheCoder/mcp-maigret) — Maigret OSINT user account collection ☆`216`
- [BurtTheCoder/mcp-virustotal](https://github.com/BurtTheCoder/mcp-virustotal) — VirusTotal API queries ☆`95`
- [BurtTheCoder/mcp-shodan](https://github.com/BurtTheCoder/mcp-shodan) — MCP server for querying the Shodan API ☆`94`
- [mobb-dev/bugsy](https://github.com/mobb-dev/bugsy) — Automatic security vulnerability remediation for your code. ☆`63`
- [roadwy/cve-search_mcp](https://github.com/roadwy/cve-search_mcp) — CVE database security queries ☆`75`
- [GitGuardian/ggmcp](https://github.com/GitGuardian/ggmcp) — MCP server for scanning and remediating hardcoded secrets using GitGuardian’s API. Detect over 500 secret types and prevent credential leaks before code goes public. ☆`26`
- [StacklokLabs/osv-mcp](https://github.com/StacklokLabs/osv-mcp) — An MCP server for OSV ☆`25`
- [BurtTheCoder/mcp-dnstwist](https://github.com/BurtTheCoder/mcp-dnstwist) — DNS fuzzing for phishing detection ☆`41`
- [nickpending/mcp-recon](https://github.com/nickpending/mcp-recon) — Tellix conversational recon interface ☆`24`
## Social Media

- [iFurySt/RedNote-MCP](https://github.com/iFurySt/RedNote-MCP) — MCP server for accessing RedNote(XiaoHongShu, xhs). ☆`932`
- [karanb192/reddit-mcp-buddy](https://github.com/karanb192/reddit-mcp-buddy) — Clean Reddit data: posts, search, users ☆`325`
- [adhikasp/mcp-twikit](https://github.com/adhikasp/mcp-twikit) — Twitter interaction via MCP ☆`216`
- [trypeggy/instagram_dm_mcp](https://github.com/trypeggy/instagram_dm_mcp) — Instagram Direct messages MCP ☆`145`
- [Seym0n/tiktok-mcp](https://github.com/Seym0n/tiktok-mcp) — Model Context Protocol (MCP) with TikTok integration ☆`118`
- [king-of-the-grackles/reddit-research-mcp](https://github.com/king-of-the-grackles/reddit-research-mcp) — Reddit research with structured insights ☆`70`
- [HagaiHen/facebook-mcp-server](https://github.com/HagaiHen/facebook-mcp-server) — Facebook posts, comments, insights automation ☆`81`
- [LuniaKunal/mcp-twitter](https://github.com/LuniaKunal/mcp-twitter) — Manage your twitter account using mcp ☆`50`
- [anwerj/youtube-uploader-mcp](https://github.com/anwerj/youtube-uploader-mcp) — Upload Videos with the help of AI ☆`30`
- [macrocosm-os/macrocosmos-mcp](https://github.com/macrocosm-os/macrocosmos-mcp) — The MCP for macrocosmos subnets. ☆`26`
- [ertiqah/linkedin-mcp-runner](https://github.com/ertiqah/linkedin-mcp-runner) —  ☆`20`
- [AbdelStark/nostr-mcp](https://github.com/AbdelStark/nostr-mcp) — Nostr posting and interaction ☆`37`
- [jaipandya/producthunt-mcp-server](https://github.com/jaipandya/producthunt-mcp-server) — MCP server for Product Hunt data access ☆`35`
- [laulauland/bluesky-context-server](https://github.com/laulauland/bluesky-context-server) — Bluesky MCP server ☆`29`
- [jonathan-politzki/mcp-writer-substack](https://github.com/jonathan-politzki/mcp-writer-substack) — Model Context Protocol to bridge in Substack writings to Claude. ☆`25`
## Sports

- [r-huijts/strava-mcp](https://github.com/r-huijts/strava-mcp) — Strava fitness data integration ☆`203`
- [rishijatia/fantasy-pl-mcp](https://github.com/rishijatia/fantasy-pl-mcp) — Fantasy Premier League MCP Server ☆`67`
- [guillochon/mlb-api-mcp](https://github.com/guillochon/mlb-api-mcp) — MCP server for MLB baseball statistics ☆`35`
- [yeonupark/mcp-soccer-data](https://github.com/yeonupark/mcp-soccer-data) — An MCP server that provides real-time football data based on the SoccerDataAPI. ☆`26`
- [mikechao/balldontlie-mcp](https://github.com/mikechao/balldontlie-mcp) — MCP server for NBA, NFL, MLB sports data ☆`19`
- [lenwood/cfbd-mcp-server](https://github.com/lenwood/cfbd-mcp-server) — An MCP server enabling CFBD API queries within Claude Desktop. ☆`23`
- [r-huijts/firstcycling-mcp](https://github.com/r-huijts/firstcycling-mcp) — MCP server for professional cycling data from FirstCycling ☆`17`
- [kw510/strava-mcp](https://github.com/kw510/strava-mcp) — MCP server with Strava OAuth on Cloudflare Workers ☆`23`
- [RobSpectre/mvf1](https://github.com/RobSpectre/mvf1) — Python package and CLI for MultiViewer For F1 ☆`17`
- [tomekkorbak/strava-mcp-server](https://github.com/tomekkorbak/strava-mcp-server) — MCP server for Strava API integration ☆`17`
## Text-to-Speech

- [mbailey/voicemode](https://github.com/mbailey/voicemode) — VoiceMode MCP brings natural conversations to Claude Code ☆`518`
- [mberg/kokoro-tts-mcp](https://github.com/mberg/kokoro-tts-mcp) — Kokoro Text to Speech (TTS) MCP Server ☆`70`
## Translation

- [caol64/wenyan-mcp](https://github.com/caol64/wenyan-mcp) — Markdown formatting and translation to Chinese ☆`945`
- [DeepLcom/deepl-mcp-server](https://github.com/DeepLcom/deepl-mcp-server) — A Model Context Protocol (MCP) server that provides translation capabilities using the DeepL API. ☆`79`
- [translated/lara-mcp](https://github.com/translated/lara-mcp) — Lara Translate API with language detection ☆`75`
## Travel & Transport

- [openbnb-org/mcp-server-airbnb](https://github.com/openbnb-org/mcp-server-airbnb) — Search Airbnb using your AI Agent ☆`349`
- [cobanov/teslamate-mcp](https://github.com/cobanov/teslamate-mcp) — MCP server for TeslaMate vehicle data and analytics ☆`110`
- [r-huijts/ns-mcp-server](https://github.com/r-huijts/ns-mcp-server) — MCP server for Dutch Railways (NS) travel information ☆`43`
- [pab1it0/tripadvisor-mcp](https://github.com/pab1it0/tripadvisor-mcp) — MCP server for Tripadvisor location data and reviews ☆`47`
- [sunsetcoder/flightradar24-mcp-server](https://github.com/sunsetcoder/flightradar24-mcp-server) — Model Context Protocol server for Flight Tracking ☆`44`
- [KyrieTangSheng/mcp-server-nationalparks](https://github.com/KyrieTangSheng/mcp-server-nationalparks) — US National Parks info via NPS API ☆`35`
- [variflight/variflight-mcp](https://github.com/variflight/variflight-mcp) — A Model Context Protocol (MCP) server implementation for Variflight services. ☆`17`
- [JordanDalton/DoorDash-MCP-Server](https://github.com/JordanDalton/DoorDash-MCP-Server) — MCP server for DoorDash delivery service integration ☆`18`
## TODO

- [hopx-ai/mcp](https://github.com/hopx-ai/mcp) —  ☆`213`
- [appium/appium-mcp](https://github.com/appium/appium-mcp) — Appium MCP on Steroids! ☆`123`
- [peakmojo/mcp-hubspot](https://github.com/peakmojo/mcp-hubspot) — A Model Context Protocol (MCP) server that enables AI assistants to interact with HubSpot CRM data, providing built-in vector storage and caching mechanisms help overcome HubSpot API limitations while improving response times. ☆`112`
- [mamertofabian/elevenlabs-mcp-server](https://github.com/mamertofabian/elevenlabs-mcp-server) —  ☆`114`
- [tesla0225/mcp-create](https://github.com/tesla0225/mcp-create) —  ☆`97`
- [GongRzhe/TRAVEL-PLANNER-MCP-Server](https://github.com/GongRzhe/TRAVEL-PLANNER-MCP-Server) —  ☆`91`
- [aws-samples/sample-mcp-server-s3](https://github.com/aws-samples/sample-mcp-server-s3) —  ☆`73`
- [pranav-deshmukh/blender-mcp](https://github.com/pranav-deshmukh/blender-mcp) —  ☆`84`
- [nabid-pf/youtube-video-summarizer-mcp](https://github.com/nabid-pf/youtube-video-summarizer-mcp) —  ☆`53`
- [v-3/google-calendar](https://github.com/v-3/google-calendar) —  ☆`66`
- [zencoderai/slack-mcp-server](https://github.com/zencoderai/slack-mcp-server) —  ☆`55`
- [newtype-01/prompthouse-mcp](https://github.com/newtype-01/prompthouse-mcp) —  ☆`50`
- [djannot/puppeteer-vision-mcp](https://github.com/djannot/puppeteer-vision-mcp) —  ☆`45`
- [useparagon/paragon-mcp](https://github.com/useparagon/paragon-mcp) —  ☆`44`
- [particlefuture/1mcpserver](https://github.com/particlefuture/1mcpserver) —  ☆`29`
- [atharvagupta2003/mcp-stripe](https://github.com/atharvagupta2003/mcp-stripe) —  ☆`45`
- [suhail-ak-s/mcp-typesense-server](https://github.com/suhail-ak-s/mcp-typesense-server) —  ☆`18`
- [drestrepom/mcp_graphql](https://github.com/drestrepom/mcp_graphql) —  ☆`19`
- [webrix-ai/secure-mcp-gateway](https://github.com/webrix-ai/secure-mcp-gateway) —  ☆`18`
- [wilsonchenghy/ShaderToy-MCP](https://github.com/wilsonchenghy/ShaderToy-MCP) —  ☆`37`
- [apeyroux/mcp-xmind](https://github.com/apeyroux/mcp-xmind) —  ☆`35`
- [DumplingAI/mcp-server-dumplingai](https://github.com/DumplingAI/mcp-server-dumplingai) — MCP (Model Context Protocol) server for Dumpling AI ☆`29`
- [Spathodea-Network/opencti-mcp](https://github.com/Spathodea-Network/opencti-mcp) —  ☆`31`
- [WaveSpeedAI/mcp-server](https://github.com/WaveSpeedAI/mcp-server) —  ☆`23`
- [yangkyeongmo/mcp-server-openmetadata](https://github.com/yangkyeongmo/mcp-server-openmetadata) —  ☆`20`
- [intsig-textin/textin-mcp](https://github.com/intsig-textin/textin-mcp) —  ☆`27`
- [GongRzhe/Office-Visio-MCP-Server](https://github.com/GongRzhe/Office-Visio-MCP-Server) —  ☆`27`
- [descope-sample-apps/descope-mcp-server-stdio](https://github.com/descope-sample-apps/descope-mcp-server-stdio) —  ☆`25`
- [AshwinSundar/congress_gov_mcp](https://github.com/AshwinSundar/congress_gov_mcp) —  ☆`17`
- [santoshray02/csv-editor](https://github.com/santoshray02/csv-editor) —  ☆`17`
- [FelixFoster/mcp-enhance-prompt](https://github.com/FelixFoster/mcp-enhance-prompt) —  ☆`21`
- [boost-community/boost-mcp](https://github.com/boost-community/boost-mcp) —  ☆`16`
- [hichana/goalstory-mcp](https://github.com/hichana/goalstory-mcp) —  ☆`17`
- [renl/mcp-rag-local](https://github.com/renl/mcp-rag-local) —  ☆`16`


## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Feedback

Found something wrong? Open an issue or submit a pull request — contributions are welcome!

## Credits

- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)
- [appcypher/awesome-mcp-servers](https://github.com/appcypher/awesome-mcp-servers)
- [wong2/awesome-mcp-servers](https://github.com/wong2/awesome-mcp-servers)
- [All Contributors](https://github.com/abordage/awesome-mcp/graphs/contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
