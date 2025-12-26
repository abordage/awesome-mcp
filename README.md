# Awesome MCP

[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-mcp?label=last%20update)](README.md)
[![License](https://img.shields.io/github/license/abordage/awesome-mcp)](LICENSE)

**Automated. Curated. Ranked.**

[Model Context Protocol (MCP)](https://modelcontextprotocol.io/) servers, clients, and frameworks — the open standard for connecting AI assistants to external data sources and tools. This awesome list is automatically maintained with daily GitHub API updates. Projects are re-ranked daily based on current activity metrics.

**Daily process:** Merge community PRs → Scan repos → Filter stale projects → Recalculate scores → Rebuild list

- [AI Memory & RAG](#ai-memory--rag)
- [Aggregators & Gateways](#aggregators--gateways)
  - [Aggregators](#aggregators)
  - [Gateways & Proxies](#gateways--proxies)
  - [Platforms & Registries](#platforms--registries)
- [AI Coding Agents](#ai-coding-agents)
- [Browser Automation](#browser-automation)
- [CLI Tools](#cli-tools)
- [Cloud & Infrastructure](#cloud--infrastructure)
  - [Cloud Platforms](#cloud-platforms)
  - [Kubernetes](#kubernetes)
  - [Virtualization & IaC](#virtualization--iac)
- [Communication & Messaging](#communication--messaging)
- [CRM & ERP](#crm--erp)
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
- [Others](#others)
  - [MCP Clients](#mcp-clients)


## AI Memory & RAG

- [chatmcp/mcp-server-chatsum](https://github.com/chatmcp/mcp-server-chatsum) — Query and Summarize your chat messages. ☆`1,024`
- [apecloud/ApeRAG](https://github.com/apecloud/ApeRAG) — Production GraphRAG with multi-modal ☆`990`
- [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) — Hindsight: Agent Memory That Works Like Human Memory ☆`813`
- [mem0ai/mem0-mcp](https://github.com/mem0ai/mem0-mcp) — MCP server for Mem0 long-term AI memory management ☆`544`
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
- [agentic-mcp-tools/memora](https://github.com/agentic-mcp-tools/memora) — Persistent shared memories in SQLite ☆`47`
- [shinpr/mcp-local-rag](https://github.com/shinpr/mcp-local-rag) — MCP server for local RAG operations ☆`44`
- [Yuchen20/Memory-Plus](https://github.com/Yuchen20/Memory-Plus) — Enhanced persistent memory management ☆`50`
- [vectara/vectara-mcp](https://github.com/vectara/vectara-mcp) — Open source MCP server for Vectara ☆`26`
- [vezlo/src-to-kb](https://github.com/vezlo/src-to-kb) — Convert source code to LLM ready knowledge base ☆`24`
- [ukkit/memcord](https://github.com/ukkit/memcord) — MCP server for memory and context management ☆`21`
- [cameronrye/openzim-mcp](https://github.com/cameronrye/openzim-mcp) — MCP server for OpenZIM archive access ☆`16`
- [bh-rat/context-awesome](https://github.com/bh-rat/context-awesome) — awesome-lists now available as MCP server for you agent. ☆`26`
## Aggregators & Gateways

### Aggregators

- [mindsdb/mindsdb](https://github.com/mindsdb/mindsdb) — Query Engine for AI - The only MCP Server you'll ever need ☆`38,120`
- [metatool-ai/metamcp](https://github.com/metatool-ai/metamcp) — MCP Aggregator, Orchestrator, Middleware, Gateway in one docker ☆`1,821`
- [mcpjungle/MCPJungle](https://github.com/mcpjungle/MCPJungle) — Self-hosted MCP Gateway and Registry for AI agents ☆`754`
- [1mcp-app/agent](https://github.com/1mcp-app/agent) — Unified MCP server aggregator ☆`325`
- [K-Dense-AI/claude-skills-mcp](https://github.com/K-Dense-AI/claude-skills-mcp) — Claude Agent Skills vector search ☆`202`
- [Intelligent-Internet/gemini-cli-mcp-openai-bridge](https://github.com/Intelligent-Internet/gemini-cli-mcp-openai-bridge) — Gemini CLI to MCP/OpenAI bridge ☆`121`
- [sitbon/magg](https://github.com/sitbon/magg) — Magg: The MCP Aggregator ☆`121`
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

- [stacklok/toolhive](https://github.com/stacklok/toolhive) — Runtime and gateway for deploying MCP servers in containers ☆`1,459`
- [ssut/Remote-MCP](https://github.com/ssut/Remote-MCP) — Type-safe solution for remote MCP communication ☆`203`
- [sxhxliang/mcp-access-point](https://github.com/sxhxliang/mcp-access-point) — Convert any web server to MCP instantly ☆`156`
- [VeriTeknik/pluggedin-mcp-proxy](https://github.com/VeriTeknik/pluggedin-mcp-proxy) — Unified MCP proxy managing multiple MCPs ☆`113`
- [tigranbs/mcgravity](https://github.com/tigranbs/mcgravity) — Proxy for composing multiple MCP servers into one endpoint ☆`80`
- [nick1udwig/ws-mcp](https://github.com/nick1udwig/ws-mcp) — MCP server with WebSocket transport ☆`19`
### Platforms & Registries

- [metorial/metorial](https://github.com/metorial/metorial) — Connect any AI model to 600+ integrations; powered by MCP ☆`3,191`
- [julien040/anyquery](https://github.com/julien040/anyquery) — SQL queries for GitHub, Notion, +40 more ☆`1,572`
- [wegotdocs/open-mcp](https://github.com/wegotdocs/open-mcp) — Open standard and registry for converting web APIs into MCP servers ☆`320`
- [integromat/make-mcp-server](https://github.com/integromat/make-mcp-server) — Make MCP Server ☆`147`
- [juspay/neurolink](https://github.com/juspay/neurolink) — Universal AI platform with MCP and multi-provider support ☆`100`
- [VeyraX/veyrax-mcp](https://github.com/VeyraX/veyrax-mcp) — VeyraX unified tool access via single MCP ☆`47`
## AI Coding Agents

- [bytedance/UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop) — Multimodal AI agent stack for UI automation ☆`20,111`
- [mastra-ai/mastra](https://github.com/mastra-ai/mastra) — TypeScript AI agent framework with RAG ☆`18,984`
- [oraios/serena](https://github.com/oraios/serena) — Semantic code retrieval and editing toolkit ☆`17,674`
- [perplexityai/modelcontextprotocol](https://github.com/perplexityai/modelcontextprotocol) — Official Perplexity API MCP server ☆`1,844`
- [jamubc/gemini-mcp-tool](https://github.com/jamubc/gemini-mcp-tool) — MCP server for Gemini CLI with large file analysis ☆`1,781`
- [ezyang/codemcp](https://github.com/ezyang/codemcp) — Coding assistant MCP for Claude Desktop ☆`1,580`
- [rinadelph/Agent-MCP](https://github.com/rinadelph/Agent-MCP) — Multi-agent AI collaboration framework ☆`1,087`
- [dmayboroda/minima](https://github.com/dmayboroda/minima) — On-premises conversational RAG with configurable containers ☆`1,021`
- [ref-tools/ref-tools-mcp](https://github.com/ref-tools/ref-tools-mcp) — Reference tools for coding agents ☆`879`
- [PV-Bhat/vibe-check-mcp-server](https://github.com/PV-Bhat/vibe-check-mcp-server) — Mentor-like feedback tool preventing AI over-engineering ☆`436`
- [evalstate/mcp-hfspace](https://github.com/evalstate/mcp-hfspace) — HuggingFace Spaces integration ☆`376`
- [ttommyth/interactive-mcp](https://github.com/ttommyth/interactive-mcp) — Interactive MCP server for human-in-the-loop AI ☆`327`
- [juehang/vscode-mcp-server](https://github.com/juehang/vscode-mcp-server) — VS Code editing features for LLM coding ☆`305`
- [SDGLBL/mcp-claude-code](https://github.com/SDGLBL/mcp-claude-code) — MCP implementation of Claude Code capabilities and more ☆`295`
- [Shashankss1205/CodeGraphContext](https://github.com/Shashankss1205/CodeGraphContext) — Code graph indexing for AI context ☆`227`
- [pyroprompts/any-chat-completions-mcp](https://github.com/pyroprompts/any-chat-completions-mcp) — MCP Server for using any LLM as a Tool ☆`146`
- [agentrpc/agentrpc](https://github.com/agentrpc/agentrpc) — Universal RPC layer for AI agents ☆`124`
- [stippi/code-assistant](https://github.com/stippi/code-assistant) — LLM-powered autonomous coding assistant ☆`124`
- [nesquikm/mcp-rubber-duck](https://github.com/nesquikm/mcp-rubber-duck) — MCP bridge to query multiple OpenAI-compatible LLMs ☆`119`
- [IDEA-Research/DINO-X-MCP](https://github.com/IDEA-Research/DINO-X-MCP) — MCP server for DINO-X vision model ☆`108`
- [IBM/wxflows](https://github.com/IBM/wxflows) — watsonx.ai Flows AI app tutorials ☆`111`
- [choplin/mcp-gemini-cli](https://github.com/choplin/mcp-gemini-cli) — MCP server for Gemini CLI integration ☆`90`
- [Rai220/think-mcp](https://github.com/Rai220/think-mcp) — MCP Server for reasoning ☆`84`
- [TheRaLabs/legion-mcp](https://github.com/TheRaLabs/legion-mcp) — MCP server for Legion AI platform ☆`79`
- [jinzcdev/leetcode-mcp-server](https://github.com/jinzcdev/leetcode-mcp-server) — MCP server for LeetCode problems and solutions ☆`76`
- [lamemind/mcp-server-multiverse](https://github.com/lamemind/mcp-server-multiverse) — MCP server for multiverse context management ☆`75`
- [pierrebrunelle/mcp-server-openai](https://github.com/pierrebrunelle/mcp-server-openai) — Query OpenAI models from Claude via MCP ☆`78`
- [YuChenSSR/multi-ai-advisor-mcp](https://github.com/YuChenSSR/multi-ai-advisor-mcp) — council of models for decision ☆`72`
- [ai-1st/deepview-mcp](https://github.com/ai-1st/deepview-mcp) — MCP server for DeepView AI analysis ☆`67`
- [micl2e2/code-to-tree](https://github.com/micl2e2/code-to-tree) — Source code to AST tree conversion ☆`70`
- [mzxrai/mcp-openai](https://github.com/mzxrai/mcp-openai) — Chat with OpenAI models from Claude Desktop ☆`68`
- [zenml-io/mcp-zenml](https://github.com/zenml-io/mcp-zenml) — ZenML MLOps platform connection ☆`39`
- [PromptExecution/just-mcp](https://github.com/PromptExecution/just-mcp) — mcp server for just ☆`38`
- [gwbischof/free-will-mcp](https://github.com/gwbischof/free-will-mcp) — Experimental AI self-prompting MCP server ☆`32`
- [atlanhq/agent-toolkit](https://github.com/atlanhq/agent-toolkit) — Atlan AI Agent Toolkit ☆`25`
- [gotohuman/gotohuman-mcp-server](https://github.com/gotohuman/gotohuman-mcp-server) — Human approvals for AI agentic workflows ☆`47`
- [gabrielmaialva33/winx-code-agent](https://github.com/gabrielmaialva33/winx-code-agent) — MCP-powered code agent for development ☆`23`
- [andybrandt/mcp-simple-openai-assistant](https://github.com/andybrandt/mcp-simple-openai-assistant) — Use OpenAI GPTs assistants from Claude ☆`36`
- [amidabuddha/unichat-mcp-server](https://github.com/amidabuddha/unichat-mcp-server) — Unified chat across multiple LLM providers ☆`37`
- [OctoMind-dev/octomind-mcp](https://github.com/OctoMind-dev/octomind-mcp) — An MCP server for octomind tools, resources and prompts ☆`21`
- [wende/cicada](https://github.com/wende/cicada) — AI Coders search blindly. Be their guide. ☆`19`
- [doggybee/mcp-server-leetcode](https://github.com/doggybee/mcp-server-leetcode) — MCP server for LeetCode coding challenges ☆`36`
- [sequa-ai/sequa-mcp](https://github.com/sequa-ai/sequa-mcp) — MCP server for Sequa AI platform ☆`16`
- [vasayxtx/mcp-prompt-engine](https://github.com/vasayxtx/mcp-prompt-engine) — MCP Prompt Engine ☆`16`
- [PV-Bhat/gemsuite-mcp](https://github.com/PV-Bhat/gemsuite-mcp) — MCP server for GemSuite tools ☆`25`
- [VertexStudio/developer](https://github.com/VertexStudio/developer) — File editing, shell execution, screen capture ☆`18`
- [olalonde/mcp-human](https://github.com/olalonde/mcp-human) — Human Assistance for AI Assistants ☆`21`
- [nazar256/user-prompt-mcp](https://github.com/nazar256/user-prompt-mcp) — User input requests for Cursor ☆`18`
## Browser Automation

- [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) — Playwright MCP server ☆`24,746`
- [Skyvern-AI/skyvern](https://github.com/Skyvern-AI/skyvern) — Automate browser based workflows with AI ☆`19,904`
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
- [freema/firefox-devtools-mcp](https://github.com/freema/firefox-devtools-mcp) — MCP server for Firefox DevTools integration ☆`19`
- [BB-fat/browser-use-rs](https://github.com/BB-fat/browser-use-rs) — Rust-based browser automation MCP server ☆`16`
- [kimtth/mcp-aoai-web-browsing](https://github.com/kimtth/mcp-aoai-web-browsing) — Azure OpenAI with Playwright browser control ☆`31`
## CLI Tools

- [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) — Terminal control, file search, diff editing ☆`5,125`
- [chrishayuk/mcp-cli](https://github.com/chrishayuk/mcp-cli) — Feature-rich CLI for interacting with MCP servers ☆`1,786`
- [rusiaaman/wcgw](https://github.com/rusiaaman/wcgw) — Shell and coding agent on claude desktop app ☆`626`
- [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp) — iTerm command execution for REPL/CLI ☆`504`
- [aymericzip/intlayer](https://github.com/aymericzip/intlayer) — MCP server for Intlayer internationalization ☆`465`
- [wong2/mcp-cli](https://github.com/wong2/mcp-cli) — A CLI inspector for the Model Context Protocol ☆`397`
- [claude-did-this/MCPControl](https://github.com/claude-did-this/MCPControl) — MCP server for Windows OS automation ☆`260`
- [g0t4/mcp-server-commands](https://github.com/g0t4/mcp-server-commands) — Model Context Protocol server to run commands ☆`218`
- [tufantunc/ssh-mcp](https://github.com/tufantunc/ssh-mcp) — SSH control for Linux servers ☆`180`
- [nickgnd/tmux-mcp](https://github.com/nickgnd/tmux-mcp) — A MCP server for our beloved terminal multiplexer tmux. ☆`174`
- [tumf/mcp-shell-server](https://github.com/tumf/mcp-shell-server) — Shell execution with whitelisted commands ☆`156`
- [MladenSU/cli-mcp-server](https://github.com/MladenSU/cli-mcp-server) — CLI with secure execution and custom policies ☆`156`
- [inercia/MCPShell](https://github.com/inercia/MCPShell) — Use shell scripts as MCP tools ☆`48`
- [automateyournetwork/pyATS_MCP](https://github.com/automateyournetwork/pyATS_MCP) — An MCP Server for pyATS (experimental) ☆`52`
- [sonirico/mcp-shell](https://github.com/sonirico/mcp-shell) — Secure, auditable shell commands for AI ☆`51`
- [NakaokaRei/swift-mcp-gui](https://github.com/NakaokaRei/swift-mcp-gui) — Keyboard and mouse control on macOS ☆`49`
- [maxim-saplin/mcp_safe_local_python_executor](https://github.com/maxim-saplin/mcp_safe_local_python_executor) — Safe Python executor from smolagents ☆`40`
- [PhialsBasement/CMD-MCP-Server](https://github.com/PhialsBasement/CMD-MCP-Server) — CMD command execution for Claude agents ☆`22`
- [JoshuaRileyDev/mac-apps-launcher](https://github.com/JoshuaRileyDev/mac-apps-launcher) — Launch and manage macOS applications ☆`16`
## Cloud & Infrastructure

### Cloud Platforms

- [apache/apisix](https://github.com/apache/apisix) — The Cloud-Native API Gateway and AI Gateway ☆`16,013`
- [awslabs/mcp](https://github.com/awslabs/mcp) — AWS MCP servers for AI assistants ☆`7,718`
- [GreptimeTeam/greptimedb](https://github.com/GreptimeTeam/greptimedb) — Unified observability DB for metrics, logs, traces ☆`5,839`
- [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) — Cloudflare services management ☆`3,220`
- [microsoft/azure-devops-mcp](https://github.com/microsoft/azure-devops-mcp) — Azure DevOps integration for AI agents ☆`1,104`
- [GoogleCloudPlatform/cloud-run-mcp](https://github.com/GoogleCloudPlatform/cloud-run-mcp) — MCP server to deploy apps to Cloud Run ☆`494`
- [alexei-led/aws-mcp-server](https://github.com/alexei-led/aws-mcp-server) — AWS CLI in containerized environment ☆`168`
- [babelcloud/gbox](https://github.com/babelcloud/gbox) — AI control for Android, browser, desktop ☆`157`
- [aliyun/alibaba-cloud-ops-mcp-server](https://github.com/aliyun/alibaba-cloud-ops-mcp-server) — AlibabaCloud CloudOps MCP Server ☆`88`
- [aws-powertools/powertools-mcp](https://github.com/aws-powertools/powertools-mcp) — Powertools for AWS's official MCP Server ☆`40`
- [kenliao94/mcp-server-rabbitmq](https://github.com/kenliao94/mcp-server-rabbitmq) — MCP server for interacting with RabbitMQ ☆`40`
- [dkruyt/mcp-hetzner](https://github.com/dkruyt/mcp-hetzner) — Hetzner Cloud management ☆`58`
- [aliyun/alibabacloud-devops-mcp-server](https://github.com/aliyun/alibabacloud-devops-mcp-server) — MCP server for Alibaba Yunxiao DevOps platform ☆`35`
- [qiniu/qiniu-mcp-server](https://github.com/qiniu/qiniu-mcp-server) — Qiniu Cloud storage, CDN, and media processing ☆`32`
- [aliyun/alibabacloud-dataworks-mcp-server](https://github.com/aliyun/alibabacloud-dataworks-mcp-server) — Alibaba Cloud DataWorks API integration ☆`25`
- [aantti/mcp-netbird](https://github.com/aantti/mcp-netbird) — Netbird network management ☆`41`
- [redis/mcp-redis-cloud](https://github.com/redis/mcp-redis-cloud) — MCP server for Redis Cloud database operations ☆`38`
- [localstack/localstack-mcp-server](https://github.com/localstack/localstack-mcp-server) — LocalStack AWS emulation ☆`16`
- [kestra-io/mcp-server-python](https://github.com/kestra-io/mcp-server-python) — Python MCP for Kestra AI Agents ☆`16`
- [api7/apisix-mcp](https://github.com/api7/apisix-mcp) — APISIX gateway for LLM integration ☆`29`
- [aliyun/alibabacloud-hologres-mcp-server](https://github.com/aliyun/alibabacloud-hologres-mcp-server) — MCP server for Alibaba Hologres data warehouse ☆`25`
- [trilogy-group/aws-pricing-mcp](https://github.com/trilogy-group/aws-pricing-mcp) — AWS EC2 pricing search by CPU, RAM, network ☆`17`
- [higress-group/higress-ops-mcp-server](https://github.com/higress-group/higress-ops-mcp-server) — Higress API gateway configuration management ☆`22`
### Kubernetes

- [Flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) — MCP Server for kubernetes management commands ☆`1,229`
- [containers/kubernetes-mcp-server](https://github.com/containers/kubernetes-mcp-server) — Kubernetes and OpenShift management ☆`911`
- [weibaohui/k8m](https://github.com/weibaohui/k8m) — Mini Kubernetes AI Dashboard ☆`744`
- [rohitg00/kubectl-mcp-server](https://github.com/rohitg00/kubectl-mcp-server) — Kubernetes cluster chat with Claude/Cursor ☆`747`
- [strowk/mcp-k8s-go](https://github.com/strowk/mcp-k8s-go) — Go-based Kubernetes connection ☆`367`
- [alexei-led/k8s-mcp-server](https://github.com/alexei-led/k8s-mcp-server) — Kubernetes cluster management ☆`178`
- [weibaohui/kom](https://github.com/weibaohui/kom) — Kubernetes SDK wrapping kubectl ☆`138`
- [silenceper/mcp-k8s](https://github.com/silenceper/mcp-k8s) — Kubernetes cluster interaction ☆`131`
- [reza-gholizade/k8s-mcp-server](https://github.com/reza-gholizade/k8s-mcp-server) — Kubernetes cluster management ☆`128`
- [portainer/portainer-mcp](https://github.com/portainer/portainer-mcp) — Portainer container management ☆`96`
- [StacklokLabs/mkp](https://github.com/StacklokLabs/mkp) — MKP Kubernetes MCP server ☆`55`
- [cyclops-ui/mcp-cyclops](https://github.com/cyclops-ui/mcp-cyclops) — Cyclops Kubernetes management ☆`29`
- [wenhuwang/mcp-k8s-eye](https://github.com/wenhuwang/mcp-k8s-eye) — Kubernetes diagnosis and management ☆`26`
### Virtualization & IaC

- [nwiizo/tfmcp](https://github.com/nwiizo/tfmcp) — Terraform AI-assisted infrastructure ☆`347`
- [bright8192/esxi-mcp-server](https://github.com/bright8192/esxi-mcp-server) — MCP server for VMware ESXi management ☆`51`
- [openstack-kr/python-openstackmcp-server](https://github.com/openstack-kr/python-openstackmcp-server) — openstack mcp server ☆`17`
## Communication & Messaging

- [elie222/inbox-zero](https://github.com/elie222/inbox-zero) — AI email assistant for inbox zero ☆`9,627`
- [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) — WhatsApp MCP server ☆`5,164`
- [korotovsky/slack-mcp-server](https://github.com/korotovsky/slack-mcp-server) — MCP server for Slack workspace integration ☆`1,031`
- [chigwell/telegram-mcp](https://github.com/chigwell/telegram-mcp) — MCP server for Telegram messaging ☆`509`
- [line/line-bot-mcp-server](https://github.com/line/line-bot-mcp-server) — LINE Messaging API for AI agents ☆`505`
- [joinly-ai/joinly](https://github.com/joinly-ai/joinly) — Make your meetings accessible to AI Agents ☆`415`
- [Softeria/ms-365-mcp-server](https://github.com/Softeria/ms-365-mcp-server) — Microsoft 365 and Office via Graph API ☆`371`
- [InditexTech/mcp-teams-server](https://github.com/InditexTech/mcp-teams-server) — MCP server for Microsoft Teams integration ☆`340`
- [chaindead/telegram-mcp](https://github.com/chaindead/telegram-mcp) — Telegram dialogs, messages, drafts, statuses ☆`257`
- [carterlasalle/mac_messages_mcp](https://github.com/carterlasalle/mac_messages_mcp) — MCP server for secure iMessage database access on macOS ☆`206`
- [SaseQ/discord-mcp](https://github.com/SaseQ/discord-mcp) — MCP server for Discord integration ☆`140`
- [ztxtxwd/open-feishu-mcp-server](https://github.com/ztxtxwd/open-feishu-mcp-server) — Feishu/Lark OAuth and document management ☆`70`
- [areweai/tsgram-mcp](https://github.com/areweai/tsgram-mcp) — Telegram for local Claude Code debug ☆`86`
- [hannesrudolph/imessage-query-fastmcp-mcp-server](https://github.com/hannesrudolph/imessage-query-fastmcp-mcp-server) — Safe iMessage database queries ☆`72`
- [mailtrap/mailtrap-mcp](https://github.com/mailtrap/mailtrap-mcp) — Official mailtrap.io MCP server ☆`51`
- [Shy2593666979/mcp-server-email](https://github.com/Shy2593666979/mcp-server-email) — Email with attachments for Gmail, Outlook, QQ ☆`66`
- [gitmotion/ntfy-me-mcp](https://github.com/gitmotion/ntfy-me-mcp) — MCP server for ntfy push notifications ☆`46`
- [sawa-zen/vrchat-mcp](https://github.com/sawa-zen/vrchat-mcp) — VRChat API interaction ☆`49`
- [discourse/discourse-mcp](https://github.com/discourse/discourse-mcp) — MCP client for Discourse sites ☆`30`
- [Cactusinhand/mcp_server_notify](https://github.com/Cactusinhand/mcp_server_notify) — Send system notification when Agent task is done. ☆`42`
- [teddyzxcv/ntfy-mcp](https://github.com/teddyzxcv/ntfy-mcp) — MCP server for ntfy push notifications ☆`43`
- [infobip/mcp](https://github.com/infobip/mcp) — Infobip Remote MCP Servers Documentation ☆`22`
- [mailgun/mailgun-mcp-server](https://github.com/mailgun/mailgun-mcp-server) — Mailgun API integration ☆`39`
- [gotoolkits/mcp-wecombot-server](https://github.com/gotoolkits/mcp-wecombot-server) — WeCom group robot message sending ☆`32`
- [jagan-shanmugam/mattermost-mcp-host](https://github.com/jagan-shanmugam/mattermost-mcp-host) — Mattermost integration with LangGraph agent ☆`28`
- [wyattjoh/imessage-mcp](https://github.com/wyattjoh/imessage-mcp) — iMessage data reading from macOS ☆`18`
## CRM & ERP

- [ivnvxd/mcp-server-odoo](https://github.com/ivnvxd/mcp-server-odoo) — MCP server for Odoo ERP integration ☆`121`
- [augmnt/augments-mcp-server](https://github.com/augmnt/augments-mcp-server) — MCP server for Augments AI platform ☆`92`
- [hmk/attio-mcp-server](https://github.com/hmk/attio-mcp-server) — Attio CRM records and notes management ☆`16`
## Data & Analytics

- [antvis/mcp-server-chart](https://github.com/antvis/mcp-server-chart) — 25+ visual charts using @antvis for data analysis ☆`3,364`
- [haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server) — Excel file manipulation ☆`3,024`
- [zcaceres/markdownify-mcp](https://github.com/zcaceres/markdownify-mcp) — Convert almost anything to Markdown ☆`2,320`
- [datalayer/jupyter-mcp-server](https://github.com/datalayer/jupyter-mcp-server) — Model Context Protocol (MCP) Server for Jupyter. ☆`829`
- [MigoXLab/dingo](https://github.com/MigoXLab/dingo) — AI data, model, app quality evaluation ☆`602`
- [reading-plus-ai/mcp-server-data-exploration](https://github.com/reading-plus-ai/mcp-server-data-exploration) — Interactive CSV data exploration ☆`516`
- [dbt-labs/dbt-mcp](https://github.com/dbt-labs/dbt-mcp) — A MCP (Model Context Protocol) server for interacting with dbt. ☆`445`
- [hustcc/mcp-echarts](https://github.com/hustcc/mcp-echarts) — ECharts visual charts with AI ☆`175`
- [jjsantos01/jupyter-notebook-mcp](https://github.com/jjsantos01/jupyter-notebook-mcp) — A Model Context Protocol (MCP) for Jupyter Notebook ☆`113`
- [ChronulusAI/chronulus-mcp](https://github.com/ChronulusAI/chronulus-mcp) — Chronulus AI forecasting and prediction agents ☆`102`
- [keboola/mcp-server](https://github.com/keboola/mcp-server) — Model Context Protocol (MCP) Server for the Keboola Platform ☆`80`
- [isaacwasserman/mcp-vegalite-server](https://github.com/isaacwasserman/mcp-vegalite-server) — MCP server for Vega-Lite data visualization ☆`94`
- [optuna/optuna-mcp](https://github.com/optuna/optuna-mcp) — Optuna hyperparameter optimization ☆`67`
- [kdqed/zaturn](https://github.com/kdqed/zaturn) — Data Analysis With Vibes ☆`69`
- [JordiNeil/mcp-databricks-server](https://github.com/JordiNeil/mcp-databricks-server) — MCP Server for Databricks ☆`45`
- [aywengo/kafka-schema-reg-mcp](https://github.com/aywengo/kafka-schema-reg-mcp) — Kafka Schema Registry management ☆`27`
- [Unstructured-IO/UNS-MCP](https://github.com/Unstructured-IO/UNS-MCP) — MCP server for Unstructured document processing ☆`38`
- [phisanti/MCPR](https://github.com/phisanti/MCPR) — AI agents in interactive R sessions ☆`20`
- [growthbook/growthbook-mcp](https://github.com/growthbook/growthbook-mcp) — GrowthBook flags and experiments ☆`16`
- [arrismo/kaggle-mcp](https://github.com/arrismo/kaggle-mcp) — MCP server for Kaggle ☆`32`
- [YangLiangwei/PersonalizationMCP](https://github.com/YangLiangwei/PersonalizationMCP) — Personal data hub for AI from Steam, YouTube, Bilibili ☆`33`
- [mattijsdp/dbt-docs-mcp](https://github.com/mattijsdp/dbt-docs-mcp) — dbt documentation interaction ☆`21`
- [HumanSignal/label-studio-mcp-server](https://github.com/HumanSignal/label-studio-mcp-server) — MCP server for Label Studio data labeling ☆`25`
- [subelsky/bundler_mcp](https://github.com/subelsky/bundler_mcp) — MCP server for Ruby Bundler integration ☆`19`
## Databases

### Analytics & Warehouses

- [ClickHouse/mcp-clickhouse](https://github.com/ClickHouse/mcp-clickhouse) — Connect ClickHouse to your AI assistants. ☆`628`
- [motherduckdb/mcp-server-motherduck](https://github.com/motherduckdb/mcp-server-motherduck) — MCP server for DuckDB and MotherDuck ☆`384`
- [Snowflake-Labs/mcp](https://github.com/Snowflake-Labs/mcp) — Snowflake Cortex AI and SQL orchestration ☆`197`
- [isaacwasserman/mcp-snowflake-server](https://github.com/isaacwasserman/mcp-snowflake-server) — MCP server for Snowflake database queries ☆`170`
- [ktanaka101/mcp-server-duckdb](https://github.com/ktanaka101/mcp-server-duckdb) — DuckDB database interaction ☆`173`
- [ergut/mcp-bigquery-server](https://github.com/ergut/mcp-bigquery-server) — MCP server for Google BigQuery integration ☆`130`
- [LucasHild/mcp-server-bigquery](https://github.com/LucasHild/mcp-server-bigquery) — Google BigQuery database access ☆`120`
- [pab1it0/adx-mcp-server](https://github.com/pab1it0/adx-mcp-server) — MCP server for Azure Data Explorer ☆`50`
### Cache & Key-Value

- [redis/mcp-redis](https://github.com/redis/mcp-redis) — MCP server for Redis database operations ☆`371`
- [aliyun/alibabacloud-tablestore-mcp-server](https://github.com/aliyun/alibabacloud-tablestore-mcp-server) — MCP server for Alibaba Tablestore NoSQL ☆`150`
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
### Multi-Database Tools

- [googleapis/genai-toolbox](https://github.com/googleapis/genai-toolbox) — Open source database MCP toolbox ☆`11,949`
- [bytebase/dbhub](https://github.com/bytebase/dbhub) — Token-efficient multi-database MCP ☆`1,786`
- [Canner/wren-engine](https://github.com/Canner/wren-engine) — Semantic engine for MCP clients and AI ☆`518`
- [centralmind/gateway](https://github.com/centralmind/gateway) — Universal database MCP for LLMs ☆`505`
- [runekaagaard/mcp-alchemy](https://github.com/runekaagaard/mcp-alchemy) — MCP server for SQLAlchemy database operations ☆`379`
- [FreePeak/db-mcp-server](https://github.com/FreePeak/db-mcp-server) — MCP server for database operations ☆`325`
- [XGenerationLab/xiyan_mcp_server](https://github.com/XGenerationLab/xiyan_mcp_server) — Natural language database queries ☆`225`
- [prisma/mcp](https://github.com/prisma/mcp) — Prisma database workflows ☆`31`
- [s2-streamstore/s2-sdk-typescript](https://github.com/s2-streamstore/s2-sdk-typescript) — S2 SDK for TypeScript ☆`21`
- [fireproof-storage/mcp-database-server](https://github.com/fireproof-storage/mcp-database-server) — Store and load JSON documents from LLM tool use ☆`29`
### NoSQL & Document

- [kiliczsh/mcp-mongo-server](https://github.com/kiliczsh/mcp-mongo-server) — A Model Context Protocol Server for MongoDB ☆`269`
- [cr7258/elasticsearch-mcp-server](https://github.com/cr7258/elasticsearch-mcp-server) — Elasticsearch and OpenSearch interaction ☆`232`
- [furey/mongodb-lens](https://github.com/furey/mongodb-lens) — MongoDB Lens: Full Featured MCP Server for MongoDB Databases ☆`195`
- [QuantGeekDev/mongo-mcp](https://github.com/QuantGeekDev/mongo-mcp) — A mongo db server for the model context protocol (MCP) ☆`174`
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
- [wenb1n-dev/SmartDB_MCP](https://github.com/wenb1n-dev/SmartDB_MCP) — Universal database MCP for MySQL, PostgreSQL, Oracle and more ☆`110`
- [oceanbase/awesome-oceanbase-mcp](https://github.com/oceanbase/awesome-oceanbase-mcp) — MCP Server for OceanBase database and its tools ☆`87`
- [tuannvm/mcp-trino](https://github.com/tuannvm/mcp-trino) — High-performance Trino MCP in Go ☆`86`
- [hannesrudolph/sqlite-explorer-fastmcp-mcp-server](https://github.com/hannesrudolph/sqlite-explorer-fastmcp-mcp-server) — Read-only SQLite database access ☆`97`
- [donghao1393/mcp-dbutils](https://github.com/donghao1393/mcp-dbutils) — Multi-database connector for SQLite, MySQL, PostgreSQL ☆`86`
- [jparkerweb/mcp-sqlite](https://github.com/jparkerweb/mcp-sqlite) — Comprehensive SQLite interaction ☆`73`
- [Teradata/teradata-mcp-server](https://github.com/Teradata/teradata-mcp-server) — Teradata database integration ☆`35`
- [Zhwt/go-mcp-mysql](https://github.com/Zhwt/go-mcp-mysql) — Go-based MCP server for MySQL ☆`48`
- [singlestore-labs/mcp-server-singlestore](https://github.com/singlestore-labs/mcp-server-singlestore) — SingleStore database management API ☆`26`
- [panasenco/mcp-sqlite](https://github.com/panasenco/mcp-sqlite) — SQLite with Datasette metadata support ☆`16`
- [ydb-platform/ydb-mcp](https://github.com/ydb-platform/ydb-mcp) — MCP server for YDB distributed database ☆`24`
- [c4pt0r/mcp-server-tidb](https://github.com/c4pt0r/mcp-server-tidb) — mcp server for tidb ☆`22`
- [OpenLinkSoftware/mcp-sqlalchemy-server](https://github.com/OpenLinkSoftware/mcp-sqlalchemy-server) — ODBC server with FastAPI and SQLAlchemy ☆`19`
- [Dataring-engineering/mcp-server-trino](https://github.com/Dataring-engineering/mcp-server-trino) — MCP Server for Trino ☆`18`
- [Xexr/mcp-libsql](https://github.com/Xexr/mcp-libsql) — MCP server for libSQL database ☆`16`
### Spreadsheets & No-Code

- [baserow/baserow](https://github.com/baserow/baserow) — No-code database, apps, agents with AI ☆`3,605`
- [xing5/mcp-google-sheets](https://github.com/xing5/mcp-google-sheets) — Google Drive and Sheets integration ☆`569`
- [domdomegg/airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server) — Airtable bases integration for AI systems ☆`373`
- [rashidazarang/airtable-mcp](https://github.com/rashidazarang/airtable-mcp) — Airtable integration for AI applications ☆`59`
- [edwinbernadus/nocodb-mcp-server](https://github.com/edwinbernadus/nocodb-mcp-server) — nocodb mcp server ☆`55`
- [freema/mcp-gsheets](https://github.com/freema/mcp-gsheets) — Google Sheets read, write, manipulate ☆`39`
### Streaming & Messaging

- [confluentinc/mcp-confluent](https://github.com/confluentinc/mcp-confluent) — MCP server for Confluent Kafka platform ☆`123`
### Time-Series & Metrics

- [pab1it0/prometheus-mcp-server](https://github.com/pab1it0/prometheus-mcp-server) — MCP server for Prometheus metrics ☆`324`
- [VictoriaMetrics-Community/mcp-victorialogs](https://github.com/VictoriaMetrics-Community/mcp-victorialogs) — VictoriaLogs log management integration ☆`40`
- [idoru/influxdb-mcp-server](https://github.com/idoru/influxdb-mcp-server) — An MCP Server for querying InfluxDB ☆`28`
- [GreptimeTeam/greptimedb-mcp-server](https://github.com/GreptimeTeam/greptimedb-mcp-server) — A Model Context Protocol (MCP) server for GreptimeDB ☆`23`
- [influxdata/influxdb3_mcp_server](https://github.com/influxdata/influxdb3_mcp_server) — MCP Server for InfluxDB 3 ☆`23`
### Vector Databases

- [qdrant/mcp-server-qdrant](https://github.com/qdrant/mcp-server-qdrant) — Official Qdrant vector database MCP ☆`1,144`
- [chroma-core/chroma-mcp](https://github.com/chroma-core/chroma-mcp) — Chroma vector database capabilities ☆`448`
- [zilliztech/mcp-server-milvus](https://github.com/zilliztech/mcp-server-milvus) — Model Context Protocol Servers for Milvus ☆`206`
- [weaviate/mcp-server-weaviate](https://github.com/weaviate/mcp-server-weaviate) — MCP (Model Context Protocol) server for Weaviate ☆`160`
## Developer Tools

### API Tools

- [janwilmake/openapi-mcp-server](https://github.com/janwilmake/openapi-mcp-server) — Complex OpenAPI exploration with plain language ☆`865`
- [zcaceres/fetch-mcp](https://github.com/zcaceres/fetch-mcp) — A flexible HTTP fetching Model Context Protocol server. ☆`658`
- [automation-ai-labs/mcp-link](https://github.com/automation-ai-labs/mcp-link) — Convert Any OpenAPI V3 API to MCP Server ☆`586`
- [blurrah/mcp-graphql](https://github.com/blurrah/mcp-graphql) — Model Context Protocol server for GraphQL ☆`340`
- [delano/postman-mcp-server](https://github.com/delano/postman-mcp-server) — An MCP server that provides access to Postman. ☆`143`
- [postmanlabs/postman-mcp-server](https://github.com/postmanlabs/postman-mcp-server) — Connect your AI to your APIs on Postman ☆`126`
- [webflow/mcp-server](https://github.com/webflow/mcp-server) — Model Context Protocol (MCP) server for the Webflow Data API. ☆`93`
- [twilio-labs/mcp](https://github.com/twilio-labs/mcp) — OpenAPI to MCP tools and Twilio APIs ☆`76`
- [kadykov/mcp-openapi-schema-explorer](https://github.com/kadykov/mcp-openapi-schema-explorer) — Token-efficient OpenAPI/Swagger exploration ☆`61`
- [ReAPI-com/mcp-openapi](https://github.com/ReAPI-com/mcp-openapi) — OpenAPI specification MCP server. ☆`75`
- [hostinger/api-mcp-server](https://github.com/hostinger/api-mcp-server) — MCP server for Hostinger API integration ☆`46`
- [zaizaizhao/mcp-swagger-server](https://github.com/zaizaizhao/mcp-swagger-server) — OpenAPI/Swagger to MCP conversion ☆`44`
- [shanejonas/openrpc-mcp-server](https://github.com/shanejonas/openrpc-mcp-server) — JSON-RPC via OpenRPC ☆`42`
- [hijaz/postmancer](https://github.com/hijaz/postmancer) — REST client replacing Postman/Insomnia ☆`29`
- [Arize-ai/text-to-graphql-mcp](https://github.com/Arize-ai/text-to-graphql-mcp) — MCP server for text-to-GraphQL conversion ☆`23`
- [Jktfe/serveMyAPI](https://github.com/Jktfe/serveMyAPI) — MCP server for custom API serving ☆`23`
- [fotoetienne/gqai](https://github.com/fotoetienne/gqai) — Turn any GraphQL endpoint into a set of MCP tools ☆`21`
### CI/CD & DevOps

- [ckreiling/mcp-server-docker](https://github.com/ckreiling/mcp-server-docker) — MCP server for Docker ☆`660`
- [QuantGeekDev/docker-mcp](https://github.com/QuantGeekDev/docker-mcp) — A docker MCP Server (modelcontextprotocol) ☆`438`
- [utensils/mcp-nixos](https://github.com/utensils/mcp-nixos) — MCP-NixOS - Model Context Protocol Server for NixOS resources ☆`382`
- [TencentEdgeOne/edgeone-pages-mcp](https://github.com/TencentEdgeOne/edgeone-pages-mcp) — Deploy HTML to EdgeOne Pages with public URL ☆`339`
- [jamsocket/forevervm](https://github.com/jamsocket/forevervm) — Stateful AI code sandboxes ☆`224`
- [DefangLabs/defang](https://github.com/DefangLabs/defang) — MCP server for Defang cloud deployment ☆`144`
- [yangkyeongmo/mcp-server-apache-airflow](https://github.com/yangkyeongmo/mcp-server-apache-airflow) — MCP server for Apache Airflow workflows ☆`120`
- [docker/hub-mcp](https://github.com/docker/hub-mcp) — Docker Hub MCP Server ☆`103`
- [aashari/mcp-server-atlassian-bitbucket](https://github.com/aashari/mcp-server-atlassian-bitbucket) — Atlassian Bitbucket repositories and PRs ☆`96`
- [CircleCI-Public/mcp-server-circleci](https://github.com/CircleCI-Public/mcp-server-circleci) — MCP server for CircleCI CI/CD pipeline integration ☆`75`
- [buildkite/buildkite-mcp-server](https://github.com/buildkite/buildkite-mcp-server) — Official MCP Server for Buildkite. ☆`42`
- [bitrise-io/bitrise-mcp](https://github.com/bitrise-io/bitrise-mcp) — Bitrise CI/CD app and build management ☆`26`
- [IvanAmador/vercel-ai-docs-mcp](https://github.com/IvanAmador/vercel-ai-docs-mcp) — Vercel AI SDK documentation search ☆`42`
- [harness/mcp-server](https://github.com/harness/mcp-server) — This is the official repo for the Harness MCP server ☆`20`
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
- [CodeLogicIncEngineering/codelogic-mcp-server](https://github.com/CodeLogicIncEngineering/codelogic-mcp-server) — Codelogic software dependency analysis ☆`33`
- [azer/react-analyzer-mcp](https://github.com/azer/react-analyzer-mcp) — React code analysis and docs generation ☆`54`
- [cqfn/aibolit-mcp-server](https://github.com/cqfn/aibolit-mcp-server) — Aibolit Java static analyzer for AI agents ☆`21`
- [j4c0bs/mcp-server-sql-analyzer](https://github.com/j4c0bs/mcp-server-sql-analyzer) — MCP server for SQL static analysis. ☆`26`
### Design & UI

- [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) — Figma layout info for AI coding agents ☆`12,325`
- [21st-dev/magic-mcp](https://github.com/21st-dev/magic-mcp) — Frontend development with AI like Magic ☆`4,040`
- [Jpisnice/shadcn-ui-mcp-server](https://github.com/Jpisnice/shadcn-ui-mcp-server) — MCP server for shadcn/ui component library ☆`2,554`
- [hustcc/mcp-mermaid](https://github.com/hustcc/mcp-mermaid) — Generate mermaid diagram and chart with AI MCP dynamically. ☆`342`
- [public-ui/kolibri](https://github.com/public-ui/kolibri) — The accessible HTML-Standard ☆`240`
- [YuChenSSR/mindmap-mcp-server](https://github.com/YuChenSSR/mindmap-mcp-server) — mindmap, mcp server, artifact ☆`208`
- [storybookjs/mcp](https://github.com/storybookjs/mcp) — MCP server for Storybook UI component library ☆`152`
- [freema/mcp-design-system-extractor](https://github.com/freema/mcp-design-system-extractor) — MCP server for extracting design system components ☆`36`
- [themeselection/flyonui-mcp](https://github.com/themeselection/flyonui-mcp) — MCP server for flyonUI ☆`23`
- [themesberg/flowbite-mcp](https://github.com/themesberg/flowbite-mcp) — Figma to code with Flowbite ☆`21`
- [heilgar/shadcn-ui-mcp-server](https://github.com/heilgar/shadcn-ui-mcp-server) — MCP server for shadcn/ui component library ☆`20`
### Documentation

- [upstash/context7](https://github.com/upstash/context7) — Up-to-date code docs for LLMs ☆`40,070`
- [lingodotdev/lingo.dev](https://github.com/lingodotdev/lingo.dev) — MCP server for Lingo localization platform ☆`5,067`
- [vivekVells/mcp-pandoc](https://github.com/vivekVells/mcp-pandoc) — MCP server for document format conversion using pandoc. ☆`472`
- [szeider/consult7](https://github.com/szeider/consult7) — MCP server to consult a language model with large context size ☆`277`
- [mrjoshuak/godoc-mcp](https://github.com/mrjoshuak/godoc-mcp) — go doc mcp server ☆`95`
- [yWorks/mcp-typescribe](https://github.com/yWorks/mcp-typescribe) — TypeScript library support for LLMs ☆`45`
- [yikakia/godoc-mcp-server](https://github.com/yikakia/godoc-mcp-server) — Go package docs from pkg.go.dev ☆`34`
- [V0v1kkk/DotNetMetadataMcpServer](https://github.com/V0v1kkk/DotNetMetadataMcpServer) — .NET type metadata for AI coding agents ☆`17`
- [inkeep/mcp-server-python](https://github.com/inkeep/mcp-server-python) — Inkeep MCP Server ☆`24`
- [Excoriate/mcp-terragrunt-docs](https://github.com/Excoriate/mcp-terragrunt-docs) — Terragrunt documentation context ☆`17`
### IDE & Editors

- [cameroncooke/XcodeBuildMCP](https://github.com/cameroncooke/XcodeBuildMCP) — MCP server for Xcode build operations ☆`3,163`
- [isaacphi/mcp-language-server](https://github.com/isaacphi/mcp-language-server) — MCP server implementing Language Server Protocol ☆`1,336`
- [JetBrains/mcp-jetbrains](https://github.com/JetBrains/mcp-jetbrains) — MCP server for JetBrains IDE integration ☆`939`
- [r-huijts/xcode-mcp-server](https://github.com/r-huijts/xcode-mcp-server) — Xcode project management ☆`339`
- [biegehydra/BifrostMCP](https://github.com/biegehydra/BifrostMCP) — VS Code semantic tools via MCP ☆`194`
- [tumf/mcp-text-editor](https://github.com/tumf/mcp-text-editor) — Line-oriented text editing for LLM tools ☆`177`
- [marimo-team/codemirror-mcp](https://github.com/marimo-team/codemirror-mcp) — CodeMirror MCP extension ☆`79`
- [ShenghaiWang/xcodebuild](https://github.com/ShenghaiWang/xcodebuild) — Xcode iOS build with error feedback ☆`78`
- [hloiseau/mcp-gopls](https://github.com/hloiseau/mcp-gopls) — Go LSP server via gopls ☆`53`
- [laurynas-biveinis/elisp-dev-mcp](https://github.com/laurynas-biveinis/elisp-dev-mcp) — Emacs Elisp development tools for LLMs ☆`30`
- [linw1995/nvim-mcp](https://github.com/linw1995/nvim-mcp) — MCP server for Neovim integration ☆`27`
- [hechtcarmel/jetbrains-index-mcp-plugin](https://github.com/hechtcarmel/jetbrains-index-mcp-plugin) — JetBrains plugin for MCP index integration ☆`21`
### MCP SDKs

- [jlowin/fastmcp](https://github.com/jlowin/fastmcp) — Python framework for building MCP servers and clients ☆`21,417`
- [mark3labs/mcp-go](https://github.com/mark3labs/mcp-go) — Go implementation of MCP ☆`7,861`
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
- [Hypersequent/qasphere-mcp](https://github.com/Hypersequent/qasphere-mcp) — MCP Server for QA Sphere TMS ☆`18`
- [hungthai1401/bruno-mcp](https://github.com/hungthai1401/bruno-mcp) — MCP Server for running Bruno Collections ☆`32`
- [QAInsights/k6-mcp-server](https://github.com/QAInsights/k6-mcp-server) — k6 MCP server ☆`20`
## Embedded & IoT

- [tevonsb/homeassistant-mcp](https://github.com/tevonsb/homeassistant-mcp) — A MCP server for Home Assistant ☆`502`
- [Extelligence-ai/bagel](https://github.com/Extelligence-ai/bagel) — Chat with robotics, drone, IoT data ☆`369`
- [voska/hass-mcp](https://github.com/voska/hass-mcp) — Home Assistant MCP Server ☆`250`
- [horw/esp-mcp](https://github.com/horw/esp-mcp) — ESP32 commands and getting started ☆`118`
- [thingsboard/thingsboard-mcp](https://github.com/thingsboard/thingsboard-mcp) — MCP server for ThingsBoard IoT platform interaction ☆`81`
- [kukapay/opcua-mcp](https://github.com/kukapay/opcua-mcp) — An MCP server that connects to OPC UA-enabled industrial systems. ☆`22`
- [yoelbassin/gr-mcp](https://github.com/yoelbassin/gr-mcp) — MCP server for GNU Radio ☆`24`
- [OctoEverywhere/mcp](https://github.com/OctoEverywhere/mcp) — 3D printing live status and control ☆`21`
- [kukapay/modbus-mcp](https://github.com/kukapay/modbus-mcp) — Industrial Modbus data for AI ☆`18`
- [johannesPettersson80/codesys-mcp-toolkit](https://github.com/johannesPettersson80/codesys-mcp-toolkit) — CODESYS industrial automation platform ☆`16`
## File Systems & Storage

- [mark3labs/mcp-filesystem-server](https://github.com/mark3labs/mcp-filesystem-server) — Go filesystem operations via MCP ☆`568`
- [cyberchitta/llm-context.py](https://github.com/cyberchitta/llm-context.py) — Python library for LLM context management ☆`288`
- [mamertofabian/mcp-everything-search](https://github.com/mamertofabian/mcp-everything-search) — Fast file search across Windows, macOS, Linux ☆`280`
- [isaacphi/mcp-gdrive](https://github.com/isaacphi/mcp-gdrive) — Google Drive file reading ☆`246`
- [8b-is/smart-tree](https://github.com/8b-is/smart-tree) — Context-aware AI-crafted replacement for tree command ☆`197`
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
- [coinpaprika/dexpaprika-mcp](https://github.com/coinpaprika/dexpaprika-mcp) — MCP server for DEX trading data and crypto token analytics ☆`35`
- [kukapay/crypto-feargreed-mcp](https://github.com/kukapay/crypto-feargreed-mcp) — Crypto Fear & Greed Index data ☆`50`
- [kukapay/whale-tracker-mcp](https://github.com/kukapay/whale-tracker-mcp) — A mcp server for tracking cryptocurrency whale transactions. ☆`48`
- [kukapay/crypto-sentiment-mcp](https://github.com/kukapay/crypto-sentiment-mcp) — Cryptocurrency sentiment analysis ☆`45`
- [anjor/coinmarket-mcp-server](https://github.com/anjor/coinmarket-mcp-server) — MCP server for CoinMarketCap cryptocurrency data ☆`44`
- [getAlby/mcp](https://github.com/getAlby/mcp) — Bitcoin Lightning wallet via Nostr ☆`40`
- [GoPlausible/algorand-mcp](https://github.com/GoPlausible/algorand-mcp) — Algorand Model Context Protocol (Server & Client) ☆`38`
- [wowinter13/solscan-mcp](https://github.com/wowinter13/solscan-mcp) — Solana transaction queries ☆`37`
- [token-metrics/mcp](https://github.com/token-metrics/mcp) — MCP server for cryptocurrency data, analytics and trading signals ☆`18`
- [kukapay/uniswap-trader-mcp](https://github.com/kukapay/uniswap-trader-mcp) — Uniswap token swaps for AI agents ☆`34`
- [kukapay/dune-analytics-mcp](https://github.com/kukapay/dune-analytics-mcp) — A mcp server that bridges Dune Analytics data to AI agents. ☆`33`
- [pwh-pwh/coin-mcp-server](https://github.com/pwh-pwh/coin-mcp-server) — use Bitget’s API to get cryptocurrency info ☆`28`
- [kukapay/hyperliquid-info-mcp](https://github.com/kukapay/hyperliquid-info-mcp) — MCP server for Hyperliquid DEX data ☆`25`
- [kukapay/jupiter-mcp](https://github.com/kukapay/jupiter-mcp) — Jupiter DEX token swaps on Solana ☆`22`
- [Codex-Data/codex-mcp](https://github.com/Codex-Data/codex-mcp) — A Model Context Protocol server for the Codex API ☆`20`
- [kukapay/token-minter-mcp](https://github.com/kukapay/token-minter-mcp) — ERC-20 token minting for AI agents ☆`17`
- [thirdweb-dev/ai](https://github.com/thirdweb-dev/ai) — Blockchain data, wallet, and smart contracts ☆`18`
- [SaintDoresh/Crypto-Trader-MCP-ClaudeDesktop](https://github.com/SaintDoresh/Crypto-Trader-MCP-ClaudeDesktop) — MCP server for cryptocurrency trading ☆`17`
- [janswist/mcp-dexscreener](https://github.com/janswist/mcp-dexscreener) — Dexscreener on-chain price checking ☆`16`
### Payments & Banking

- [stripe/ai](https://github.com/stripe/ai) — One-stop shop for building AI-powered products and businesses with Stripe. ☆`1,170`
- [paypal/agent-toolkit](https://github.com/paypal/agent-toolkit) — PayPal Agent ☆`171`
- [square/square-mcp-server](https://github.com/square/square-mcp-server) — A Model Context Protocol (MCP) server for square ☆`90`
- [ramp-public/ramp_mcp](https://github.com/ramp-public/ramp_mcp) — ramp_mcp ☆`27`
- [Fewsats/fewsats-mcp](https://github.com/Fewsats/fewsats-mcp) — Fewsats MCP server ☆`21`
### Stock Data & Analytics

- [financial-datasets/mcp-server](https://github.com/financial-datasets/mcp-server) — Financial Datasets stock market API ☆`723`
- [massive-com/mcp_massive](https://github.com/massive-com/mcp_massive) — An MCP server for Massive.com Financial Market Data ☆`231`
- [berlinbra/alpha-vantage-mcp](https://github.com/berlinbra/alpha-vantage-mcp) — MCP Server for Alpha Advantage API ☆`86`
- [narumiruna/yfinance-mcp](https://github.com/narumiruna/yfinance-mcp) — MCP server for Yahoo Finance stock data and news ☆`78`
- [OctagonAI/octagon-mcp-server](https://github.com/OctagonAI/octagon-mcp-server) — Public filings, earnings, financial analysis ☆`86`
- [HuggingAGI/mcp-baostock-server](https://github.com/HuggingAGI/mcp-baostock-server) — MCP server for BaoStock Chinese stock market data ☆`64`
- [zlinzzzz/finData-mcp-server](https://github.com/zlinzzzz/finData-mcp-server) — Financial data from Tushare, Wind, DataYes ☆`50`
- [JamesANZ/prediction-market-mcp](https://github.com/JamesANZ/prediction-market-mcp) — Polymarket, PredictIt, Kalshi data ☆`20`
### Trading & Exchanges

- [ferdousbhai/investor-agent](https://github.com/ferdousbhai/investor-agent) — Investor agent building via MCP ☆`296`
- [ariadng/metatrader-mcp-server](https://github.com/ariadng/metatrader-mcp-server) — MetaTrader trading platform for AI LLMs ☆`136`
- [doggybee/mcp-server-ccxt](https://github.com/doggybee/mcp-server-ccxt) — Cryptocurrency exchange integration via CCXT ☆`123`
- [kukapay/freqtrade-mcp](https://github.com/kukapay/freqtrade-mcp) — Freqtrade crypto trading bot ☆`100`
- [QuantConnect/mcp-server](https://github.com/QuantConnect/mcp-server) — QuantConnect algo trading interaction ☆`62`
- [ferdousbhai/tasty-agent](https://github.com/ferdousbhai/tasty-agent) — Let Claude manage your tastytrade portfolio. ☆`48`
- [trade-it-inc/trade-it-mcp](https://github.com/trade-it-inc/trade-it-mcp) — Trade It stocks and crypto trading ☆`41`
- [laukikk/alpaca-mcp](https://github.com/laukikk/alpaca-mcp) — Alpaca stock and crypto trading ☆`33`
- [SaintDoresh/YFinance-Trader-MCP-ClaudeDesktop](https://github.com/SaintDoresh/YFinance-Trader-MCP-ClaudeDesktop) — MCP server for Yahoo Finance trading data ☆`28`
- [ferdousbhai/wsb-analyst-mcp](https://github.com/ferdousbhai/wsb-analyst-mcp) — MCP server for analyzing WallStreetBets ☆`19`
## Gaming

- [Coding-Solo/godot-mcp](https://github.com/Coding-Solo/godot-mcp) — MCP server for Godot game engine ☆`1,255`
- [CoderGamester/mcp-unity](https://github.com/CoderGamester/mcp-unity) — MCP server for Unity game engine integration ☆`1,160`
- [IvanMurzak/Unity-MCP](https://github.com/IvanMurzak/Unity-MCP) — AI-powered bridge connecting LLMs to Unity Editor ☆`653`
- [codemaestroai/advanced-unity-mcp](https://github.com/codemaestroai/advanced-unity-mcp) — Advanced Unity game engine integration ☆`73`
- [pab1it0/chess-mcp](https://github.com/pab1it0/chess-mcp) — MCP server for Chess.com player data, games and statistics ☆`57`
- [opgginc/opgg-mcp](https://github.com/opgginc/opgg-mcp) — MCP server for OP.GG game data (LoL, TFT, Valorant) ☆`53`
- [kkjdaniel/bgg-mcp](https://github.com/kkjdaniel/bgg-mcp) — MCP server for BoardGameGeek data ☆`23`
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
- [mapbox/mcp-server](https://github.com/mapbox/mcp-server) — Mapbox Model Context Protocol (MCP) server ☆`296`
- [jagan-shanmugam/open-streetmap-mcp](https://github.com/jagan-shanmugam/open-streetmap-mcp) — MCP server for OpenStreetMap data ☆`150`
- [mahdin75/gis-mcp](https://github.com/mahdin75/gis-mcp) — MCP server connecting LLMs to GIS capabilities ☆`87`
- [mahdin75/geoserver-mcp](https://github.com/mahdin75/geoserver-mcp) — GeoServer geospatial integration ☆`51`
- [briandconnelly/mcp-server-ipinfo](https://github.com/briandconnelly/mcp-server-ipinfo) — IP Geolocation Server for MCP ☆`39`
- [isdaniel/mcp_weather_server](https://github.com/isdaniel/mcp_weather_server) — Weather info via Open-Meteo API ☆`35`
- [SecretiveShell/MCP-timeserver](https://github.com/SecretiveShell/MCP-timeserver) — Datetime info for agentic systems ☆`40`
- [TimLukaHorstmann/mcp-weather](https://github.com/TimLukaHorstmann/mcp-weather) — AccuWeather hourly and daily forecasts ☆`30`
- [webcoderz/MCP-Geo](https://github.com/webcoderz/MCP-Geo) — Geocoding MCP server with GeoPY! ☆`29`
- [sjanaX01/weather-mcp-server](https://github.com/sjanaX01/weather-mcp-server) — A simple minimal weather mcp server :) ☆`19`
- [stadiamaps/stadiamaps-mcp-server-ts](https://github.com/stadiamaps/stadiamaps-mcp-server-ts) — Stadia Maps API integration in TypeScript ☆`18`
- [kukapay/nearby-search-mcp](https://github.com/kukapay/nearby-search-mcp) — Nearby place search with IP-based location ☆`21`
## Marketing & Analytics

- [pipeboard-co/meta-ads-mcp](https://github.com/pipeboard-co/meta-ads-mcp) — MCP server to manage Facebook and Instagram Ads (Meta Ads) ☆`384`
- [open-strategy-partners/osp_marketing_tools](https://github.com/open-strategy-partners/osp_marketing_tools) — MCP server for marketing automation tools ☆`258`
- [gomarble-ai/facebook-ads-mcp-server](https://github.com/gomarble-ai/facebook-ads-mcp-server) — Facebook and Instagram Ads management ☆`202`
- [talknerdytome-labs/facebook-ads-library-mcp](https://github.com/talknerdytome-labs/facebook-ads-library-mcp) — Facebook Ads Library search and access ☆`164`
- [gomarble-ai/google-ads-mcp-server](https://github.com/gomarble-ai/google-ads-mcp-server) — Google Ads performance data analysis ☆`84`
- [stape-io/google-tag-manager-mcp-server](https://github.com/stape-io/google-tag-manager-mcp-server) — MCP server for Google Tag Manager ☆`82`
- [Kiran1689/storyblok-mcp-server](https://github.com/Kiran1689/storyblok-mcp-server) — MCP server for Storyblok CMS management ☆`31`
- [MarketplaceAdPros/amazon-ads-mcp-server](https://github.com/MarketplaceAdPros/amazon-ads-mcp-server) — MCP Server to interact with Amazon Ads ☆`19`
## Media Processing

- [ahujasid/blender-mcp](https://github.com/ahujasid/blender-mcp) — Blender 3D modeling with Claude AI ☆`14,631`
- [elevenlabs/elevenlabs-mcp](https://github.com/elevenlabs/elevenlabs-mcp) — The official ElevenLabs MCP server ☆`1,112`
- [varunneal/spotify-mcp](https://github.com/varunneal/spotify-mcp) — MCP to connect your LLM with Spotify. ☆`546`
- [abhiemj/manim-mcp-server](https://github.com/abhiemj/manim-mcp-server) — Manim animation code execution ☆`529`
- [anaisbetts/mcp-youtube](https://github.com/anaisbetts/mcp-youtube) — A Model-Context Protocol Server for YouTube ☆`481`
- [samuelgursky/davinci-resolve-mcp](https://github.com/samuelgursky/davinci-resolve-mcp) — MCP server integration for DaVinci Resolve ☆`443`
- [sunriseapps/imagesorcery-mcp](https://github.com/sunriseapps/imagesorcery-mcp) — Image processing operations ☆`259`
- [burningion/video-editing-mcp](https://github.com/burningion/video-editing-mcp) — MCP Interface for Video Jungle ☆`236`
- [marcelmarais/spotify-mcp-server](https://github.com/marcelmarais/spotify-mcp-server) — Lightweight MCP server for Spotify ☆`202`
- [muxinc/mux-node-sdk](https://github.com/muxinc/mux-node-sdk) — Mux Video and Data API wrapper ☆`172`
- [tiianhk/MaxMSP-MCP-Server](https://github.com/tiianhk/MaxMSP-MCP-Server) — MCP (Model Context Protocol) Server for Max (Max/MSP/Jitter) ☆`127`
- [video-creator/ffmpeg-mcp](https://github.com/video-creator/ffmpeg-mcp) — MCP server for FFmpeg video processing ☆`106`
- [diivi/aseprite-mcp](https://github.com/diivi/aseprite-mcp) — MCP server for interacting with the Aseprite API ☆`99`
- [awkoy/replicate-flux-mcp](https://github.com/awkoy/replicate-flux-mcp) — MCP server for Replicate Flux image and SVG generation ☆`82`
- [SureScaleAI/openai-gpt-image-mcp](https://github.com/SureScaleAI/openai-gpt-image-mcp) — OpenAI GPT-4o image generation and editing ☆`84`
- [apinetwork/piapi-mcp-server](https://github.com/apinetwork/piapi-mcp-server) — PiAPI media: Midjourney, Flux, Kling ☆`65`
- [SkyworkAI/Mureka-mcp](https://github.com/SkyworkAI/Mureka-mcp) — AI lyrics, song, and music generation ☆`66`
- [hamflx/imagen3-mcp](https://github.com/hamflx/imagen3-mcp) — MCP server for Google Imagen 3 image generation ☆`50`
- [tan-yong-sheng/ai-vision-mcp](https://github.com/tan-yong-sheng/ai-vision-mcp) — Image and video analysis capabilities ☆`30`
- [video-db/agent-toolkit](https://github.com/video-db/agent-toolkit) — MCP toolkit for video database operations ☆`44`
- [veelenga/claude-mermaid](https://github.com/veelenga/claude-mermaid) — MCP Server to previewing mermaid diagrams ☆`29`
- [stass/exif-mcp](https://github.com/stass/exif-mcp) — MCP server to extract image metadata (EXIF, XMP, etc) ☆`28`
- [imprvhub/mcp-claude-spotify](https://github.com/imprvhub/mcp-claude-spotify) — Spotify interaction for Claude Desktop ☆`21`
- [GenWaveLLC/svgmaker-mcp](https://github.com/GenWaveLLC/svgmaker-mcp) — MCP server for SVG generation ☆`20`
- [Narasimhaponnada/mermaid-mcp](https://github.com/Narasimhaponnada/mermaid-mcp) — MCP server for Mermaid diagram generation ☆`20`
- [flowy11/imagician](https://github.com/flowy11/imagician) — A MCP server for image edition ☆`18`
- [raveenb/fal-mcp-server](https://github.com/raveenb/fal-mcp-server) — Fal.ai image, video, music generation ☆`17`
- [marcindulak/stt-mcp-server-linux](https://github.com/marcindulak/stt-mcp-server-linux) — Local speech-to-text for Tmux on Linux ☆`17`
- [screenshotone/mcp](https://github.com/screenshotone/mcp) — A simple implementation of an MCP server for the ScreenshotOne API ☆`32`
- [PatrickPalmer/MayaMCP](https://github.com/PatrickPalmer/MayaMCP) — Autodesk Maya 3D integration ☆`32`
- [InhiblabCore/mcp-image-compression](https://github.com/InhiblabCore/mcp-image-compression) — High-performance image compression service ☆`28`
- [magarcia/mcp-server-giphy](https://github.com/magarcia/mcp-server-giphy) — Giphy GIF integration ☆`26`
- [zxkane/mcp-server-amazon-bedrock](https://github.com/zxkane/mcp-server-amazon-bedrock) — Amazon Bedrock Nova Canvas image generation ☆`23`
- [upnorthmedia/ScreenshotMCP](https://github.com/upnorthmedia/ScreenshotMCP) — Website screenshot capture and optimization ☆`17`
## Monitoring & Observability

- [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana) — MCP server for Grafana ☆`2,024`
- [getsentry/sentry-mcp](https://github.com/getsentry/sentry-mcp) — An MCP server for interacting with Sentry via LLMs. ☆`485`
- [traceloop/opentelemetry-mcp-server](https://github.com/traceloop/opentelemetry-mcp-server) — MCP server for OpenTelemetry observability ☆`146`
- [pydantic/logfire-mcp](https://github.com/pydantic/logfire-mcp) — The Logfire MCP Server is here! ☆`129`
- [mpeirone/zabbix-mcp-server](https://github.com/mpeirone/zabbix-mcp-server) — MCP server for Zabbix monitoring with 40+ tools ☆`122`
- [VictoriaMetrics-Community/mcp-victoriametrics](https://github.com/VictoriaMetrics-Community/mcp-victoriametrics) — VictoriaMetrics monitoring integration ☆`104`
- [seekrays/mcp-monitor](https://github.com/seekrays/mcp-monitor) — MCP server monitoring tool ☆`76`
- [axiomhq/mcp-server-axiom](https://github.com/axiomhq/mcp-server-axiom) — Axiom Model Context Protocol Server ☆`58`
- [hyperb1iss/lucidity-mcp](https://github.com/hyperb1iss/lucidity-mcp) — MCP server for enhanced AI clarity and reasoning ☆`74`
- [last9/last9-mcp-server](https://github.com/last9/last9-mcp-server) — Last9 MCP Server ☆`48`
- [metoro-io/metoro-mcp-server](https://github.com/metoro-io/metoro-mcp-server) — Metoro MCP Server ☆`45`
- [Rootly-AI-Labs/Rootly-MCP-server](https://github.com/Rootly-AI-Labs/Rootly-MCP-server) — Rootly MCP server ☆`36`
- [MindscapeHQ/mcp-server-raygun](https://github.com/MindscapeHQ/mcp-server-raygun) — Raygun error investigation for AI ☆`19`
- [inspektor-gadget/ig-mcp-server](https://github.com/inspektor-gadget/ig-mcp-server) — Container and Kubernetes debugging with AI ☆`18`
- [Pratyay/mac-monitor-mcp](https://github.com/Pratyay/mac-monitor-mcp) — MCP server for macOS system monitoring ☆`16`
- [emicklei/mcp-log-proxy](https://github.com/emicklei/mcp-log-proxy) — a web logging proxy for MCP client-server communication ☆`26`
- [tumf/grafana-loki-mcp](https://github.com/tumf/grafana-loki-mcp) — Grafana Loki MCP Repository ☆`17`
- [tgeselle/bugsnag-mcp](https://github.com/tgeselle/bugsnag-mcp) — MCP server for Bugsnag error monitoring ☆`18`
## Official

- [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) — Model Context Protocol Servers ☆`74,999`
## Productivity

### Collaboration

- [evalstate/mcp-miro](https://github.com/evalstate/mcp-miro) — MCP server for Miro whiteboard manipulation and sticky creation ☆`101`
- [hiromitsusasaki/raindrop-io-mcp-server](https://github.com/hiromitsusasaki/raindrop-io-mcp-server) — Raindrop.io bookmark management ☆`65`
- [k-jarzyna/mcp-miro](https://github.com/k-jarzyna/mcp-miro) — Miro integration for Model Context Protocol ☆`59`
- [aashari/mcp-server-atlassian-confluence](https://github.com/aashari/mcp-server-atlassian-confluence) — Atlassian Confluence spaces and pages ☆`43`
- [esignaturescom/mcp-server-esignatures](https://github.com/esignaturescom/mcp-server-esignatures) — eSignatures.com document signing ☆`31`
- [orellazri/coda-mcp](https://github.com/orellazri/coda-mcp) — MCP Server for Coda ☆`38`
- [Fibery-inc/fibery-mcp-server](https://github.com/Fibery-inc/fibery-mcp-server) — MCP server for Fibery workspace integration ☆`27`
### Google Workspace

- [taylorwilsdon/google_workspace_mcp](https://github.com/taylorwilsdon/google_workspace_mcp) — MCP server for Google Workspace integration ☆`1,020`
- [MarkusPfundstein/mcp-gsuite](https://github.com/MarkusPfundstein/mcp-gsuite) — MCP Server to interact with Google Gsuite prodcuts ☆`466`
- [giuseppe-coco/Google-Workspace-MCP-Server](https://github.com/giuseppe-coco/Google-Workspace-MCP-Server) — Gmail, Calendar, and Drive integration ☆`20`
### Helpdesk & Support

- [effytech/freshdesk_mcp](https://github.com/effytech/freshdesk_mcp) — Freshdesk support ticket integration ☆`35`
- [quickchatai/quickchat-ai-mcp](https://github.com/quickchatai/quickchat-ai-mcp) — The Quickchat AI MCP server ☆`21`
### Learning & Flashcards

- [ankimcp/anki-mcp-server](https://github.com/ankimcp/anki-mcp-server) — MCP server for Anki spaced repetition flashcards ☆`60`
- [rember/rember-mcp](https://github.com/rember/rember-mcp) — A Model Context Protocol (MCP) server for Rember. ☆`59`
### Note-taking & Docs

- [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server) — Official Notion MCP Server ☆`3,625`
- [MarkusPfundstein/mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) — Obsidian integration via REST API plugin ☆`2,579`
- [smithery-ai/mcp-obsidian](https://github.com/smithery-ai/mcp-obsidian) — Obsidian vault read and search for Claude ☆`1,243`
- [suekou/mcp-notion-server](https://github.com/suekou/mcp-notion-server) — MCP server for Notion API with Markdown conversion ☆`842`
- [RafalWilinski/mcp-apple-notes](https://github.com/RafalWilinski/mcp-apple-notes) — RAG over Apple Notes for Claude ☆`322`
- [bitbonsai/mcp-obsidian](https://github.com/bitbonsai/mcp-obsidian) — Lightweight Obsidian vault access ☆`265`
- [danhilse/notion_mcp](https://github.com/danhilse/notion_mcp) — Notion integration with advanced formatting ☆`204`
- [lostintangent/gistpad-mcp](https://github.com/lostintangent/gistpad-mcp) — Personal knowledge and daily notes management ☆`179`
- [onebirdrocks/ebook-mcp](https://github.com/onebirdrocks/ebook-mcp) — MCP server for ebook processing ☆`166`
- [ivo-toby/contentful-mcp](https://github.com/ivo-toby/contentful-mcp) — Contentful CMS Management API ☆`61`
- [baruchiro/paperless-mcp](https://github.com/baruchiro/paperless-mcp) — MCP server for Paperless-NGX document management ☆`47`
- [Badhansen/notion-mcp](https://github.com/Badhansen/notion-mcp) — Notion workspace management ☆`27`
- [akseyh/bear-mcp-server](https://github.com/akseyh/bear-mcp-server) — MCP Server integration for Bear note app ☆`41`
- [pinecone-io/assistant-mcp](https://github.com/pinecone-io/assistant-mcp) — Pinecone Assistant MCP server ☆`40`
- [vgnshiyer/apple-books-mcp](https://github.com/vgnshiyer/apple-books-mcp) — Apple Books MCP Server ☆`35`
- [agentset-ai/mcp-server](https://github.com/agentset-ai/mcp-server) — Agentset MCP Server - Build RAG with Agentic superpowers ☆`25`
- [Harry-027/JotDown](https://github.com/Harry-027/JotDown) — An MCP Server in Rust for creating Notion pages & mdBooks with LLMs ☆`19`
### Project Management

- [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) — MCP server for Atlassian tools (Confluence, Jira) ☆`3,850`
- [jerhadf/linear-mcp-server](https://github.com/jerhadf/linear-mcp-server) — MCP server for Linear issue tracking ☆`339`
- [makeplane/plane-mcp-server](https://github.com/makeplane/plane-mcp-server) — Plane's Official Model Context Protocol Server ☆`125`
- [its-dart/dart-mcp-server](https://github.com/its-dart/dart-mcp-server) — Dart AI Model Context Protocol (MCP) server ☆`124`
- [tacticlaunch/mcp-linear](https://github.com/tacticlaunch/mcp-linear) — MCP server for Linear project management ☆`121`
- [roychri/mcp-server-asana](https://github.com/roychri/mcp-server-asana) — MCP server for Asana task and project management ☆`110`
- [taskade/mcp](https://github.com/taskade/mcp) — MCP server for Taskade project management ☆`94`
- [nguyenvanduocit/jira-mcp](https://github.com/nguyenvanduocit/jira-mcp) — Jira issues and sprints via Go MCP ☆`73`
- [aashari/mcp-server-atlassian-jira](https://github.com/aashari/mcp-server-atlassian-jira) — Atlassian Jira projects, issues and sprints ☆`48`
- [feuerdev/keep-mcp](https://github.com/feuerdev/keep-mcp) — MCP server for Google Keep ☆`56`
- [kelvin6365/plane-mcp-server](https://github.com/kelvin6365/plane-mcp-server) — MCP server for Plane.so project management ☆`34`
- [m0xai/trello-mcp-server](https://github.com/m0xai/trello-mcp-server) — A simple yet powerful MCP server for Trello. ☆`44`
- [aikts/yandex-tracker-mcp](https://github.com/aikts/yandex-tracker-mcp) — Yandex Tracker MCP Server with OAuth2 support ☆`32`
- [georgeantonopoulos/Basecamp-MCP-Server](https://github.com/georgeantonopoulos/Basecamp-MCP-Server) — Basecamp 3+ project management ☆`46`
- [KS-GEN-AI/jira-mcp-server](https://github.com/KS-GEN-AI/jira-mcp-server) — A test of jira mcp server ☆`25`
- [EduBase/MCP](https://github.com/EduBase/MCP) — MCP server for EduBase e-learning platform ☆`24`
- [bivex/kanboard-mcp](https://github.com/bivex/kanboard-mcp) — MCP server for Kanboard project management integration ☆`18`
- [danielkennedy1/pdf-tools-mcp](https://github.com/danielkennedy1/pdf-tools-mcp) — MCP server for PDF manipulation (merge, extract, snippets) ☆`31`
- [rahulthedevil/Jira-Context-MCP](https://github.com/rahulthedevil/Jira-Context-MCP) — Jira tickets info for AI coding agents ☆`24`
### Tasks & Calendar

- [mediar-ai/screenpipe](https://github.com/mediar-ai/screenpipe) — AI app store with 24/7 desktop history ☆`16,260`
- [abhiz123/todoist-mcp-server](https://github.com/abhiz123/todoist-mcp-server) — Todoist natural language task management ☆`340`
- [zcaceres/gtasks-mcp](https://github.com/zcaceres/gtasks-mcp) — A Google Tasks Model Context Protocol Server for Claude ☆`97`
- [takumi0706/google-calendar-mcp](https://github.com/takumi0706/google-calendar-mcp) — Google Calendar for Claude Desktop ☆`53`
- [stanislavlysenko0912/todoist-mcp-server](https://github.com/stanislavlysenko0912/todoist-mcp-server) — Todoist Rest API and Sync API ☆`49`
- [arpitbatra123/mcp-googletasks](https://github.com/arpitbatra123/mcp-googletasks) — MCP server for Google Tasks management ☆`28`
- [jen6/ticktick-mcp](https://github.com/jen6/ticktick-mcp) — TickTick task management with filtering ☆`42`
- [dominik1001/caldav-mcp](https://github.com/dominik1001/caldav-mcp) — CalDAV calendar sync ☆`40`
- [awwaiid/mcp-server-taskwarrior](https://github.com/awwaiid/mcp-server-taskwarrior) — MCP Server for TaskWarrior! ☆`39`
- [flesler/mcp-tasks](https://github.com/flesler/mcp-tasks) — Efficient task management with views ☆`33`
### Wiki & Collaboration

- [yuna0x0/hackmd-mcp](https://github.com/yuna0x0/hackmd-mcp) — HackMD note-taking integration ☆`45`
- [HenryHaoson/Yuque-MCP-Server](https://github.com/HenryHaoson/Yuque-MCP-Server) — Yuque mcp server ☆`40`
## Research & Science

- [SecretiveShell/MCP-wolfram-alpha](https://github.com/SecretiveShell/MCP-wolfram-alpha) — Wolfram Alpha computational intelligence ☆`69`
- [reeeeemo/ancestry-mcp](https://github.com/reeeeemo/ancestry-mcp) — Ancestry genealogy data interaction ☆`29`
## Sandboxing & Execution

- [zerocore-ai/microsandbox](https://github.com/zerocore-ai/microsandbox) — opensource self-hosted sandboxes for ai agent ☆`4,245`
- [dagger/container-use](https://github.com/dagger/container-use) — MCP server for container orchestration ☆`3,360`
- [e2b-dev/mcp-server](https://github.com/e2b-dev/mcp-server) — E2B code execution for Claude ☆`362`
- [ckanthony/openapi-mcp](https://github.com/ckanthony/openapi-mcp) — Dockerized OpenAPI to MCP conversion ☆`164`
- [alfonsograziano/node-code-sandbox-mcp](https://github.com/alfonsograziano/node-code-sandbox-mcp) — MCP server for Node.js code sandbox execution ☆`141`
- [yepcode/mcp-server-js](https://github.com/yepcode/mcp-server-js) — JavaScript MCP server framework by YepCode ☆`41`
- [r33drichards/mcp-js](https://github.com/r33drichards/mcp-js) — MCP server exposing V8 JavaScript runtime for AI agents ☆`27`
- [hileamlakB/Python-Runtime-Interpreter-MCP-Server](https://github.com/hileamlakB/Python-Runtime-Interpreter-MCP-Server) — Safe Python runtime interpreter ☆`24`
- [criteo/openapi-to-mcp](https://github.com/criteo/openapi-to-mcp) — An MCP server for your API ☆`27`
- [gwbischof/outsource-mcp](https://github.com/gwbischof/outsource-mcp) — Give your AI assistant its own AI assistants. ☆`28`
## Search & Extraction

### Academic Research

- [blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server) — arXiv paper search and analysis ☆`1,975`
- [reading-plus-ai/mcp-server-deep-research](https://github.com/reading-plus-ai/mcp-server-deep-research) — Comprehensive research with reports ☆`195`
- [andybrandt/mcp-simple-arxiv](https://github.com/andybrandt/mcp-simple-arxiv) — arXiv paper search and reading ☆`176`
- [andybrandt/mcp-simple-pubmed](https://github.com/andybrandt/mcp-simple-pubmed) — PubMed medical research search ☆`147`
- [takashiishida/arxiv-latex-mcp](https://github.com/takashiishida/arxiv-latex-mcp) — MCP server for arXiv LaTeX paper retrieval ☆`77`
- [OctagonAI/octagon-deep-research-mcp](https://github.com/OctagonAI/octagon-deep-research-mcp) — AI-powered comprehensive research and analysis ☆`79`
- [akalaric/mcp-wolframalpha](https://github.com/akalaric/mcp-wolframalpha) — Wolfram Alpha integration for Python ☆`56`
### Data APIs

- [cantian-ai/bazi-mcp](https://github.com/cantian-ai/bazi-mcp) — Bazi Chinese astrology information ☆`229`
- [hellokaton/unsplash-mcp-server](https://github.com/hellokaton/unsplash-mcp-server) — A MCP server for Unsplash image search. ☆`193`
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
- [imprvhub/mcp-domain-availability](https://github.com/imprvhub/mcp-domain-availability) — MCP server to check domain availability ☆`29`
- [Linked-API/linkedapi-mcp](https://github.com/Linked-API/linkedapi-mcp) — LinkedIn account control and data retrieval ☆`29`
- [kehvinbehvin/json-mcp-filter](https://github.com/kehvinbehvin/json-mcp-filter) — JSON MCP server to filter only relevant data for your LLM ☆`20`
- [DappierAI/dappier-mcp](https://github.com/DappierAI/dappier-mcp) — MCP server for Dappier AI integration ☆`38`
- [adawalli/nexus](https://github.com/adawalli/nexus) — MCP Server to make searching openrouter easy ☆`19`
- [siva010928/multi-chat-mcp-server](https://github.com/siva010928/multi-chat-mcp-server) — MCP server for multi-chat capabilities ☆`17`
- [r-huijts/opentk-mcp](https://github.com/r-huijts/opentk-mcp) — MCP server for Dutch parliamentary data via OpenTK ☆`16`
- [DumplingAI/mcp-server-dumplingai](https://github.com/DumplingAI/mcp-server-dumplingai) — MCP (Model Context Protocol) server for Dumpling AI ☆`29`
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
- [khromov/svelte-llm-mcp](https://github.com/khromov/svelte-llm-mcp) — Svelte developer documentation as an MCP and in llms.txt format ☆`158`
- [tinyfish-io/agentql-mcp](https://github.com/tinyfish-io/agentql-mcp) — AgentQL data extraction integration ☆`137`
- [just-every/mcp-read-website-fast](https://github.com/just-every/mcp-read-website-fast) — Fast webpage to markdown conversion ☆`119`
- [oxylabs/oxylabs-mcp](https://github.com/oxylabs/oxylabs-mcp) — Official Oxylabs MCP integration ☆`77`
- [just-every/mcp-screenshot-website-fast](https://github.com/just-every/mcp-screenshot-website-fast) — Fast webpage screenshots for LLMs ☆`94`
- [scrapeless-ai/scrapeless-mcp-server](https://github.com/scrapeless-ai/scrapeless-mcp-server) — Scrapeless Mcp Server ☆`61`
- [crawlbase/crawlbase-mcp](https://github.com/crawlbase/crawlbase-mcp) — MCP server connecting AI agents with real-time web data ☆`40`
- [webscraping-ai/webscraping-ai-mcp-server](https://github.com/webscraping-ai/webscraping-ai-mcp-server) — MCP server for AI-powered web scraping ☆`35`
- [pragmar/mcp-server-webcrawl](https://github.com/pragmar/mcp-server-webcrawl) — Web crawler data and archives connection ☆`34`
- [ananddtyagi/webpage-screenshot-mcp](https://github.com/ananddtyagi/webpage-screenshot-mcp) — MCP server for webpage screenshot capture ☆`45`
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
- [ac3xx/mcp-servers-kagi](https://github.com/ac3xx/mcp-servers-kagi) — A Model Context Protocol server implementation for Kagi's API ☆`41`
- [OvertliDS/mcp-searxng-enhanced](https://github.com/OvertliDS/mcp-searxng-enhanced) — SearXNG web search with category awareness ☆`28`
- [mnhlt/WebSearch-MCP](https://github.com/mnhlt/WebSearch-MCP) — MCP server for web search integration ☆`22`
## Security

### Identity & Access

- [box-community/mcp-server-box](https://github.com/box-community/mcp-server-box) — Enterprise content access in Box ☆`88`
- [firstorderai/authenticator_mcp](https://github.com/firstorderai/authenticator_mcp) — Authenticator App for AI agents ☆`30`
- [atomicchonk/roadrecon_mcp_server](https://github.com/atomicchonk/roadrecon_mcp_server) — Azure AD ROADrecon analysis for Claude ☆`48`
- [sshaaf/keycloak-mcp-server](https://github.com/sshaaf/keycloak-mcp-server) — MCP server for Keycloak identity and access management ☆`19`
- [ChristophEnglisch/keycloak-model-context-protocol](https://github.com/ChristophEnglisch/keycloak-model-context-protocol) — Keycloak user and realm management ☆`34`
- [hieuttmmo/entraid-mcp-server](https://github.com/hieuttmmo/entraid-mcp-server) — EntraID via Microsoft Graph API ☆`31`
### MCP Security

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
- [panther-labs/mcp-panther](https://github.com/panther-labs/mcp-panther) — Detections, alerts, and log queries ☆`36`
- [qianniuspace/mcp-security-audit](https://github.com/qianniuspace/mcp-security-audit) — MCP server for security auditing ☆`49`
- [fr0gger/MCP_Security](https://github.com/fr0gger/MCP_Security) — This is a repository to experiment with MCP for security ☆`45`
- [Gaffx/volatility-mcp](https://github.com/Gaffx/volatility-mcp) — This repo hosts an MCP server for volatility3.x ☆`36`
- [slouchd/cyberchef-api-mcp-server](https://github.com/slouchd/cyberchef-api-mcp-server) — CyberChef API MCP Server ☆`31`
### Vulnerability & Threat Intel

- [BurtTheCoder/mcp-maigret](https://github.com/BurtTheCoder/mcp-maigret) — Maigret OSINT user account collection ☆`216`
- [BurtTheCoder/mcp-virustotal](https://github.com/BurtTheCoder/mcp-virustotal) — VirusTotal API queries ☆`95`
- [BurtTheCoder/mcp-shodan](https://github.com/BurtTheCoder/mcp-shodan) — MCP server for querying the Shodan API ☆`94`
- [roadwy/cve-search_mcp](https://github.com/roadwy/cve-search_mcp) — CVE database security queries ☆`75`
- [StacklokLabs/osv-mcp](https://github.com/StacklokLabs/osv-mcp) — An MCP server for OSV ☆`25`
- [BurtTheCoder/mcp-dnstwist](https://github.com/BurtTheCoder/mcp-dnstwist) — DNS fuzzing for phishing detection ☆`41`
- [nickpending/mcp-recon](https://github.com/nickpending/mcp-recon) — Tellix conversational recon interface ☆`24`
## Social Media

- [karanb192/reddit-mcp-buddy](https://github.com/karanb192/reddit-mcp-buddy) — Clean Reddit data: posts, search, users ☆`325`
- [adhikasp/mcp-twikit](https://github.com/adhikasp/mcp-twikit) — Twitter interaction via MCP ☆`216`
- [trypeggy/instagram_dm_mcp](https://github.com/trypeggy/instagram_dm_mcp) — Instagram Direct messages MCP ☆`145`
- [Seym0n/tiktok-mcp](https://github.com/Seym0n/tiktok-mcp) — Model Context Protocol (MCP) with TikTok integration ☆`118`
- [king-of-the-grackles/reddit-research-mcp](https://github.com/king-of-the-grackles/reddit-research-mcp) — Reddit research with structured insights ☆`70`
- [HagaiHen/facebook-mcp-server](https://github.com/HagaiHen/facebook-mcp-server) — Facebook posts, comments, insights automation ☆`81`
- [LuniaKunal/mcp-twitter](https://github.com/LuniaKunal/mcp-twitter) — Manage your twitter account using mcp ☆`50`
- [anwerj/youtube-uploader-mcp](https://github.com/anwerj/youtube-uploader-mcp) — Upload Videos with the help of AI ☆`30`
- [macrocosm-os/macrocosmos-mcp](https://github.com/macrocosm-os/macrocosmos-mcp) — The MCP for macrocosmos subnets. ☆`26`
- [AbdelStark/nostr-mcp](https://github.com/AbdelStark/nostr-mcp) — Nostr posting and interaction ☆`37`
- [jaipandya/producthunt-mcp-server](https://github.com/jaipandya/producthunt-mcp-server) — MCP server for Product Hunt data access ☆`35`
- [laulauland/bluesky-context-server](https://github.com/laulauland/bluesky-context-server) — Bluesky MCP server ☆`29`
## Sports

- [r-huijts/strava-mcp](https://github.com/r-huijts/strava-mcp) — Strava fitness data integration ☆`203`
- [rishijatia/fantasy-pl-mcp](https://github.com/rishijatia/fantasy-pl-mcp) — Fantasy Premier League MCP Server ☆`67`
- [guillochon/mlb-api-mcp](https://github.com/guillochon/mlb-api-mcp) — MCP server for MLB baseball statistics ☆`35`
- [mikechao/balldontlie-mcp](https://github.com/mikechao/balldontlie-mcp) — MCP server for NBA, NFL, MLB sports data ☆`19`
- [r-huijts/firstcycling-mcp](https://github.com/r-huijts/firstcycling-mcp) — MCP server for professional cycling data from FirstCycling ☆`17`
- [kw510/strava-mcp](https://github.com/kw510/strava-mcp) — MCP server with Strava OAuth on Cloudflare Workers ☆`23`
- [RobSpectre/mvf1](https://github.com/RobSpectre/mvf1) — Python package and CLI for MultiViewer For F1 ☆`17`
## Text-to-Speech

- [mbailey/voicemode](https://github.com/mbailey/voicemode) — VoiceMode MCP brings natural conversations to Claude Code ☆`518`
- [mberg/kokoro-tts-mcp](https://github.com/mberg/kokoro-tts-mcp) — Kokoro Text to Speech (TTS) MCP Server ☆`70`
## Translation

- [caol64/wenyan-mcp](https://github.com/caol64/wenyan-mcp) — Markdown formatting and translation to Chinese ☆`945`
- [translated/lara-mcp](https://github.com/translated/lara-mcp) — Lara Translate API with language detection ☆`75`
## Travel & Transport

- [openbnb-org/mcp-server-airbnb](https://github.com/openbnb-org/mcp-server-airbnb) — Search Airbnb using your AI Agent ☆`349`
- [cobanov/teslamate-mcp](https://github.com/cobanov/teslamate-mcp) — MCP server for TeslaMate vehicle data and analytics ☆`110`
- [r-huijts/ns-mcp-server](https://github.com/r-huijts/ns-mcp-server) — MCP server for Dutch Railways (NS) travel information ☆`43`
- [pab1it0/tripadvisor-mcp](https://github.com/pab1it0/tripadvisor-mcp) — MCP server for Tripadvisor location data and reviews ☆`47`
- [KyrieTangSheng/mcp-server-nationalparks](https://github.com/KyrieTangSheng/mcp-server-nationalparks) — US National Parks info via NPS API ☆`35`
- [JordanDalton/DoorDash-MCP-Server](https://github.com/JordanDalton/DoorDash-MCP-Server) — MCP server for DoorDash delivery service integration ☆`18`
## Others

### MCP Clients

- [zed-industries/zed](https://github.com/zed-industries/zed) — High-performance code editor with MCP support ☆`72,014`
- [continuedev/continue](https://github.com/continuedev/continue) — Open-source AI coding assistant with MCP support ☆`30,511`
- [Upsonic/Upsonic](https://github.com/Upsonic/Upsonic) — Agent Framework For Fintech and Banks ☆`7,740`
- [firebase/genkit](https://github.com/firebase/genkit) — AI app framework for JavaScript and Go ☆`5,253`
- [ravitemer/mcphub.nvim](https://github.com/ravitemer/mcphub.nvim) — MCP client for Neovim with intuitive server management ☆`1,675`
- [evilsocket/nerve](https://github.com/evilsocket/nerve) — The Simple Agent Development Kit. ☆`1,313`
- [SecretiveShell/MCP-Bridge](https://github.com/SecretiveShell/MCP-Bridge) — OpenAI-compatible endpoint calling MCP tools ☆`883`
- [EvalsOne/MCP-connect](https://github.com/EvalsOne/MCP-connect) — Cloud AI access to local Stdio MCP servers ☆`227`
- [3choff/mcp-chatbot](https://github.com/3choff/mcp-chatbot) — CLI chatbot with MCP integration demo ☆`241`
- [johannesbrandenburger/typst-mcp](https://github.com/johannesbrandenburger/typst-mcp) — MCP server for Typst markup-based typesetting system ☆`91`
- [tanaikech/ToolsForMCPServer](https://github.com/tanaikech/ToolsForMCPServer) — MCP server built with Google Apps Script for Gemini CLI ☆`83`
- [xzq-xu/jvm-mcp-server](https://github.com/xzq-xu/jvm-mcp-server) — JVM-based MCP server implementation ☆`75`
- [ckanthony/gin-mcp](https://github.com/ckanthony/gin-mcp) — Enable MCP features for any Gin API with a line of code ☆`65`
- [rakesh-eltropy/mcp-client](https://github.com/rakesh-eltropy/mcp-client) — REST API and CLI client for MCP with LangChain ☆`51`
- [zacharypodbela/django-rest-framework-mcp](https://github.com/zacharypodbela/django-rest-framework-mcp) — MCP server for Django REST Framework ☆`26`


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
