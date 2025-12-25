# Awesome MCP

[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-mcp?label=last%20update)](README.md)
[![License](https://img.shields.io/github/license/abordage/awesome-mcp)](LICENSE)

**Automated. Curated. Ranked.**

[Model Context Protocol (MCP)](https://modelcontextprotocol.io/) servers, clients, and frameworks — the open standard for connecting AI assistants to external data sources and tools. This awesome list is automatically maintained with daily GitHub API updates. Projects are re-ranked daily based on current activity metrics.

**Daily process:** Merge community PRs → Scan repos → Filter stale projects → Recalculate scores → Rebuild list

- [MCP Servers](#mcp-servers)
  - [Aggregators & Gateways](#aggregators-&-gateways)
  - [AI Coding Agents](#ai-coding-agents)
  - [Art & Culture](#art-&-culture)
  - [Browser Automation](#browser-automation)
  - [CLI Tools](#cli-tools)
  - [Cloud & Infrastructure](#cloud-&-infrastructure)
  - [Communication & Messaging](#communication-&-messaging)
  - [CRM & ERP](#crm-&-erp)
  - [Data & Analytics](#data-&-analytics)
  - [Databases](#databases)
  - [Developer Tools](#developer-tools)
  - [Embedded & IoT](#embedded-&-iot)
  - [File Systems & Storage](#file-systems-&-storage)
  - [Finance](#finance)
  - [Gaming](#gaming)
  - [Healthcare & Bioinformatics](#healthcare-&-bioinformatics)
  - [Knowledge Management](#knowledge-management)
  - [Location & Maps](#location-&-maps)
  - [Marketing & Analytics](#marketing-&-analytics)
  - [Media Processing](#media-processing)
  - [Monitoring & Observability](#monitoring-&-observability)
  - [Official](#official)
  - [Productivity](#productivity)
  - [Research & Science](#research-&-science)
  - [Sandboxing & Execution](#sandboxing-&-execution)
  - [Search & Extraction](#search-&-extraction)
  - [Security](#security)
  - [Social Media](#social-media)
  - [Sports](#sports)
  - [Support & ITSM](#support-&-itsm)
  - [Text-to-Speech](#text-to-speech)
  - [Translation](#translation)
  - [Travel & Transport](#travel-&-transport)
  - [Version Control](#version-control)
- [MCP Clients](#mcp-clients)
- [Frameworks & SDKs](#frameworks-&-sdks)


## MCP Servers

### Aggregators & Gateways

- [mindsdb/mindsdb](https://github.com/mindsdb/mindsdb) — Query Engine for AI - The only MCP Server you'll ever need ☆`38,120`
- [metorial/metorial](https://github.com/metorial/metorial) — Connect any AI model to 600+ integrations; powered by MCP ☆`3,191`
- [metatool-ai/metamcp](https://github.com/metatool-ai/metamcp) — MCP Aggregator, Orchestrator, Middleware, Gateway in one docker ☆`1,821`
- [julien040/anyquery](https://github.com/julien040/anyquery) — Query anything (GitHub, Notion, +40 more) with SQL and let LLMs (ChatGPT, Claude) connect to using MCP ☆`1,572`
- [mcpjungle/MCPJungle](https://github.com/mcpjungle/MCPJungle) — Self-hosted MCP Gateway and Registry for AI agents ☆`754`
- [1mcp-app/agent](https://github.com/1mcp-app/agent) — A unified Model Context Protocol server implementation that aggregates multiple MCP servers into one. ☆`325`
- [wegotdocs/open-mcp](https://github.com/wegotdocs/open-mcp) — Open standard and registry for converting web APIs into MCP servers ☆`320`
- [K-Dense-AI/claude-skills-mcp](https://github.com/K-Dense-AI/claude-skills-mcp) — MCP server for searching and retrieving Claude Agent Skills using vector search ☆`202`
- [ssut/Remote-MCP](https://github.com/ssut/Remote-MCP) — A type-safe solution to remote MCP communication, enabling effortless integration for centralized management of Model Context. ☆`203`
- [sxhxliang/mcp-access-point](https://github.com/sxhxliang/mcp-access-point) — Turn a web server into an MCP server in one click without making any code changes. ☆`156`
- [integromat/make-mcp-server](https://github.com/integromat/make-mcp-server) — Make MCP Server ☆`147`
- [VeriTeknik/pluggedin-mcp-proxy](https://github.com/VeriTeknik/pluggedin-mcp-proxy) — Plugged.in MCP Server manages all your other MCPs in one MCP. ☆`113`
- [juspay/neurolink](https://github.com/juspay/neurolink) — Universal AI Development Platform with MCP server integration, multi-provider support, and professional CLI. Build, test, and deploy AI applications with multiple ai providers. ☆`100`
- [Intelligent-Internet/gemini-cli-mcp-openai-bridge](https://github.com/Intelligent-Internet/gemini-cli-mcp-openai-bridge) — Bridge server exposing Gemini CLI tools through MCP and OpenAI-compatible API endpoints ☆`121`
- [sitbon/magg](https://github.com/sitbon/magg) — Magg: The MCP Aggregator ☆`121`
- [wanaku-ai/wanaku](https://github.com/wanaku-ai/wanaku) — Wanaku MCP Router ☆`93`
- [nguyenvanduocit/all-in-one-model-context-protocol](https://github.com/nguyenvanduocit/all-in-one-model-context-protocol) — All-in-one MCP server with AI search, RAG, and multi-service integrations (GitLab/Jira/Confluence/YouTube) for AI-enhanced development workflows ☆`97`
- [tigranbs/mcgravity](https://github.com/tigranbs/mcgravity) — A proxy tool for composing multiple MCP servers into one unified endpoint. Scale your AI tools by load balancing requests across multiple MCP servers, similar to how Nginx works for web servers. ☆`80`
- [portel-dev/ncp](https://github.com/portel-dev/ncp) — Natural Context Provider (NCP). Your MCPs, supercharged. Find any tool instantly, load on demand, run on schedule, ready for any client. Smart loading saves tokens and energy. ☆`55`
- [askbudi/roundtable](https://github.com/askbudi/roundtable) — Zero-configuration MCP server that unifies multiple AI coding assistants (Codex, Claude Code, Cursor, Gemini) through intelligent auto-discovery and standardized interface ☆`48`
- [gotoolkits/mcp-difyworkflow-server](https://github.com/gotoolkits/mcp-difyworkflow-server) — mcp-difyworkflow-server is an mcp server Tools application that implements the query and invocation of Dify workflows, supporting the on-demand operation of multiple custom Dify workflows. ☆`60`
- [hamidra/yamcp](https://github.com/hamidra/yamcp) — Organize your MCP servers in local workspaces, share them as Yet-Another-MCP through a single command ☆`59`
- [VeyraX/veyrax-mcp](https://github.com/VeyraX/veyrax-mcp) — Single MCP connection to access all VeyraX integrated tools in any MCP-compatible environment ☆`47`
- [waystation-ai/mcp](https://github.com/waystation-ai/mcp) — The only MCP Server you need. Connect any MCP host with the tools you use daily through our no-code, secure integration hub. ☆`39`
- [nazar256/combine-mcp](https://github.com/nazar256/combine-mcp) —  ☆`25`
- [harness/mcp-server](https://github.com/harness/mcp-server) — This is the official repo for the Harness MCP server ☆`20`
- [aantti/mcp-netbird](https://github.com/aantti/mcp-netbird) — MCP Server for Netbird ☆`41`
- [membranehq/mcp-server](https://github.com/membranehq/mcp-server) — MCP Server for Membrane ☆`32`
- [YangLiangwei/PersonalizationMCP](https://github.com/YangLiangwei/PersonalizationMCP) — A unified personal data hub built on MCP that allows AI assistants to access your digital life from Steam, YouTube, Bilibili and more platforms for truly personalized interactions. ☆`33`
- [Kiran1689/storyblok-mcp-server](https://github.com/Kiran1689/storyblok-mcp-server) — A modular, extensible MCP Server for managing Storyblok spaces, stories, components, assets, workflows, and more via the Model Context Protocol (MCP). ☆`31`
- [inkeep/mcp-server-python](https://github.com/inkeep/mcp-server-python) — Inkeep MCP Server ☆`24`
- [glenngillen/mcpmcp-server](https://github.com/glenngillen/mcpmcp-server) — Discover, setup, and integrate MCP servers with your favorite clients. Unlock the full potential of AI in your daily workflow. ☆`24`
- [Fewsats/fewsats-mcp](https://github.com/Fewsats/fewsats-mcp) — Fewsats MCP server ☆`21`
### AI Coding Agents

- [bytedance/UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop) — The Open-Source Multimodal AI Agent Stack: Connecting Cutting-Edge AI Models and Agent Infra ☆`20,111`
- [mastra-ai/mastra](https://github.com/mastra-ai/mastra) — The TypeScript AI agent framework. Assistants, RAG, observability. Supports any LLM: GPT-4, Claude, Gemini, Llama. ☆`18,984`
- [oraios/serena](https://github.com/oraios/serena) — A powerful coding agent toolkit providing semantic retrieval and editing capabilities (MCP server & other integrations) ☆`17,674`
- [jamubc/gemini-mcp-tool](https://github.com/jamubc/gemini-mcp-tool) — MCP server that enables AI assistants to interact with Google Gemini CLI, leveraging Gemini's massive token window for large file analysis and codebase understanding ☆`1,781`
- [ezyang/codemcp](https://github.com/ezyang/codemcp) — Coding assistant MCP for Claude Desktop ☆`1,580`
- [rinadelph/Agent-MCP](https://github.com/rinadelph/Agent-MCP) — Agent-MCP is a framework for creating multi-agent systems that enables coordinated, efficient AI collaboration through the Model Context Protocol (MCP). The system is designed for developers building AI applications that benefit from multiple specialized agents working in parallel on different aspects of a project. ☆`1,087`
- [ref-tools/ref-tools-mcp](https://github.com/ref-tools/ref-tools-mcp) — Helping coding agents never make mistakes working with public or private libraries without wasting the context window. ☆`879`
- [PV-Bhat/vibe-check-mcp-server](https://github.com/PV-Bhat/vibe-check-mcp-server) — Vibe Check is a tool that provides mentor-like feedback to AI Agents, preventing tunnel-vision, over-engineering and reasoning lock-in for complex and long-horizon agent workflows. KISS your over-eager AI Agents goodbye! Effective for: Coding, Ambiguous Tasks, High-Risk tasks ☆`436`
- [evalstate/mcp-hfspace](https://github.com/evalstate/mcp-hfspace) — MCP Server to Use HuggingFace spaces, easy configuration and Claude Desktop mode. ☆`376`
- [ttommyth/interactive-mcp](https://github.com/ttommyth/interactive-mcp) — Vibe coding should have human in the loop! interactive-mcp: Local, cross-platform MCP server for interact with your AI Agent ☆`327`
- [juehang/vscode-mcp-server](https://github.com/juehang/vscode-mcp-server) — MCP server to expose VS Code editing features to an LLM for AI coding ☆`305`
- [Shashankss1205/CodeGraphContext](https://github.com/Shashankss1205/CodeGraphContext) — An MCP server that indexes local code into a graph database to provide context to AI assistants. ☆`227`
- [voska/hass-mcp](https://github.com/voska/hass-mcp) — Home Assistant MCP Server ☆`250`
- [pyroprompts/any-chat-completions-mcp](https://github.com/pyroprompts/any-chat-completions-mcp) — MCP Server for using any LLM as a Tool ☆`146`
- [tiianhk/MaxMSP-MCP-Server](https://github.com/tiianhk/MaxMSP-MCP-Server) — MCP (Model Context Protocol) Server for Max (Max/MSP/Jitter) ☆`127`
- [agentrpc/agentrpc](https://github.com/agentrpc/agentrpc) — A universal RPC layer for AI agents. Connect to any function, any language, any framework, in minutes. ☆`124`
- [stippi/code-assistant](https://github.com/stippi/code-assistant) — An LLM-powered, autonomous coding assistant. Also offers an MCP and ACP mode. ☆`124`
- [nesquikm/mcp-rubber-duck](https://github.com/nesquikm/mcp-rubber-duck) — An MCP server that acts as a bridge to query multiple OpenAI-compatible LLMs with MCP tool access. Just like rubber duck debugging, explain your problems to various AI "ducks" who can actually research and get different perspectives! ☆`119`
- [IBM/wxflows](https://github.com/IBM/wxflows) — Examples and tutorials for building AI applications with watsonx.ai Flows Engine ☆`111`
- [choplin/mcp-gemini-cli](https://github.com/choplin/mcp-gemini-cli) — MCP server for Gemini CLI integration ☆`90`
- [Rai220/think-mcp](https://github.com/Rai220/think-mcp) — MCP Server for reasoning ☆`84`
- [jinzcdev/leetcode-mcp-server](https://github.com/jinzcdev/leetcode-mcp-server) — An MCP server enabling automated access to LeetCode's problems, solutions, and public data with optional authentication for user-specific features, supporting leetcode.com & leetcode.cn sites. ☆`76`
- [pierrebrunelle/mcp-server-openai](https://github.com/pierrebrunelle/mcp-server-openai) — Query OpenAI models directly from Claude using MCP protocol. ☆`78`
- [micl2e2/code-to-tree](https://github.com/micl2e2/code-to-tree) — A runtime-free MCP server that converts source code into AST, regardless of language. ☆`70`
- [mzxrai/mcp-openai](https://github.com/mzxrai/mcp-openai) — Chat with OpenAI models from Claude Desktop ☆`68`
- [gwbischof/free-will-mcp](https://github.com/gwbischof/free-will-mcp) — This was a fun project to explore what an AI would do with the ability to give itself prompts, ignore user requests, and wake itself up at a later time. ☆`32`
- [atlanhq/agent-toolkit](https://github.com/atlanhq/agent-toolkit) — Atlan AI Agent Toolkit ☆`25`
- [gotohuman/gotohuman-mcp-server](https://github.com/gotohuman/gotohuman-mcp-server) — Add human approvals to AI agents and agentic workflows with async human-in-the-loop ☆`47`
- [gabrielmaialva33/winx-code-agent](https://github.com/gabrielmaialva33/winx-code-agent) — A high-performance code agent written in Rust, combining the best features of WCGW for maximum efficiency and semantic capabilities. ☆`23`
- [andybrandt/mcp-simple-openai-assistant](https://github.com/andybrandt/mcp-simple-openai-assistant) — MCP server that gives Claude ability to use OpenAI's GPTs assistants ☆`36`
- [amidabuddha/unichat-mcp-server](https://github.com/amidabuddha/unichat-mcp-server) —  ☆`37`
- [wende/cicada](https://github.com/wende/cicada) — AI Coders search blindly. Be their guide. ☆`19`
- [doggybee/mcp-server-leetcode](https://github.com/doggybee/mcp-server-leetcode) — A Model Context Protocol (MCP) server for LeetCode that provides access to problems, user data, and contest information through GraphQL ☆`36`
- [VertexStudio/developer](https://github.com/VertexStudio/developer) — General purpose MCP server with file editing, shell execution, and screen capture capabilities ☆`18`
- [olalonde/mcp-human](https://github.com/olalonde/mcp-human) — Human Assistance for AI Assistants ☆`21`
- [nazar256/user-prompt-mcp](https://github.com/nazar256/user-prompt-mcp) — A Model Context Protocol (MCP) server for Cursor that enables requesting user input during generation ☆`18`
### Art & Culture

- [ahujasid/blender-mcp](https://github.com/ahujasid/blender-mcp) — Connect Blender to Claude AI through MCP for prompt-assisted 3D modeling and scene creation ☆`14,631`
- [abhiemj/manim-mcp-server](https://github.com/abhiemj/manim-mcp-server) — MCP server that executes Manim animation code and returns generated videos ☆`529`
- [samuelgursky/davinci-resolve-mcp](https://github.com/samuelgursky/davinci-resolve-mcp) — MCP server integration for DaVinci Resolve ☆`443`
- [cantian-ai/bazi-mcp](https://github.com/cantian-ai/bazi-mcp) — MCP server for Bazi (八字) information ☆`229`
- [burningion/video-editing-mcp](https://github.com/burningion/video-editing-mcp) — MCP Interface for Video Jungle ☆`236`
- [diivi/aseprite-mcp](https://github.com/diivi/aseprite-mcp) — MCP server for interacting with the Aseprite API ☆`99`
- [omni-mcp/isaac-sim-mcp](https://github.com/omni-mcp/isaac-sim-mcp) — Isaac Simulation MCP Extension and Server ☆`99`
- [cswkim/discogs-mcp-server](https://github.com/cswkim/discogs-mcp-server) — MCP Server for Discogs ☆`77`
- [yuna0x0/anilist-mcp](https://github.com/yuna0x0/anilist-mcp) — AniList MCP server for accessing anime and manga data ☆`64`
- [8enSmith/mcp-open-library](https://github.com/8enSmith/mcp-open-library) — A Model Context Protocol (MCP) server for the Internet Archive's Open Library API that enables AI assistants to search for book and author information. ☆`47`
- [r-huijts/rijksmuseum-mcp](https://github.com/r-huijts/rijksmuseum-mcp) — Rijksmuseum MCP integration for artwork exploration and analysis ☆`62`
- [djalal/quran-mcp-server](https://github.com/djalal/quran-mcp-server) — Quran.com API integration for verse search, translation and tafsir ☆`55`
- [particlefuture/1mcpserver](https://github.com/particlefuture/1mcpserver) —  ☆`29`
- [GenWaveLLC/svgmaker-mcp](https://github.com/GenWaveLLC/svgmaker-mcp) — Model Context Protocol server for SVGMaker - AI-powered SVG generation and editing. Seamlessly integrate SVG creation into AI workflows. ☆`20`
- [raveenb/fal-mcp-server](https://github.com/raveenb/fal-mcp-server) — MCP server for Fal.ai - Generate images, videos, music and audio with Claude ☆`17`
- [PatrickPalmer/MayaMCP](https://github.com/PatrickPalmer/MayaMCP) — Model Context Protocol (MCP) server implementation for Autodesk Maya ☆`32`
- [mikechao/metmuseum-mcp](https://github.com/mikechao/metmuseum-mcp) — Met Museum MCP integration to discover the art collection at The Metropolitan Museum of Art in New York ☆`20`
- [OctoEverywhere/mcp](https://github.com/OctoEverywhere/mcp) — A free 3D Printing MCP server that allows for getting live printer state, webcam snapshots, and printer control. ☆`21`
### Browser Automation

- [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) — Playwright MCP server ☆`24,746`
- [Skyvern-AI/skyvern](https://github.com/Skyvern-AI/skyvern) — Automate browser based workflows with AI ☆`19,904`
- [BrowserMCP/mcp](https://github.com/BrowserMCP/mcp) — Browser MCP is a Model Context Provider (MCP) server that allows AI applications to control your browser ☆`5,272`
- [executeautomation/mcp-playwright](https://github.com/executeautomation/mcp-playwright) — Playwright Model Context Protocol Server - Tool to automate Browsers and APIs in Claude Desktop, Cline, Cursor IDE and More ☆`5,088`
- [browserbase/mcp-server-browserbase](https://github.com/browserbase/mcp-server-browserbase) — Allow LLMs to control a browser with Browserbase and Stagehand ☆`2,966`
- [nottelabs/notte](https://github.com/nottelabs/notte) — Reliable Browser AI Agents (YC S25) ☆`1,785`
- [refreshdotdev/web-eval-agent](https://github.com/refreshdotdev/web-eval-agent) — An MCP server that autonomously evaluates web applications. ☆`1,227`
- [steipete/Peekaboo](https://github.com/steipete/Peekaboo) — Peekaboo is a macOS CLI & optional MCP server that enables AI agents to capture screenshots of applications, or the entire system, with optional visual question answering through local or remote AI models. ☆`899`
- [kontext-dev/browser-use-mcp-server](https://github.com/kontext-dev/browser-use-mcp-server) — Browse the web, directly from Cursor etc. ☆`786`
- [hyperbrowserai/mcp](https://github.com/hyperbrowserai/mcp) — A MCP server implementation for hyperbrowser ☆`661`
- [pskill9/web-search](https://github.com/pskill9/web-search) — Web search using free google search (NO API KEYS REQUIRED) ☆`376`
- [kimtaeyoon83/mcp-server-youtube-transcript](https://github.com/kimtaeyoon83/mcp-server-youtube-transcript) — This is an MCP server that allows you to directly download transcripts of YouTube videos. ☆`362`
- [eat-pray-ai/yutu](https://github.com/eat-pray-ai/yutu) — A fully functional MCP server and CLI for YouTube ☆`354`
- [VikashLoomba/MCP-Server-Playwright](https://github.com/VikashLoomba/MCP-Server-Playwright) — MCP server for browser automation using Playwright ☆`270`
- [recursechat/mcp-server-apple-shortcuts](https://github.com/recursechat/mcp-server-apple-shortcuts) — MCP server that lets AI assistants control Apple Shortcuts automations on macOS ☆`260`
- [eyalzh/browser-control-mcp](https://github.com/eyalzh/browser-control-mcp) — MCP server paired with a browser extension that enables AI agents to control the user's browser. ☆`221`
- [blackwhite084/playwright-plus-python-mcp](https://github.com/blackwhite084/playwright-plus-python-mcp) — Enhanced Playwright MCP server for Python with additional browser automation features ☆`168`
- [34892002/bilibili-mcp-js](https://github.com/34892002/bilibili-mcp-js) — Bilibili video search MCP service ☆`132`
- [browserstack/mcp-server](https://github.com/browserstack/mcp-server) — BrowserStack's Official MCP Server ☆`114`
- [ndthanhdev/mcp-browser-kit](https://github.com/ndthanhdev/mcp-browser-kit) — An MCP Server that enables AI assistants to interact with your local browsers. ☆`45`
- [NON906/omniparser-autogui-mcp](https://github.com/NON906/omniparser-autogui-mcp) — Automatic operation of on-screen GUI. ☆`60`
- [getrupt/ashra-mcp](https://github.com/getrupt/ashra-mcp) — A Model Context Protocol server for Ashra ☆`55`
- [Mtehabsim/ScreenPilot](https://github.com/Mtehabsim/ScreenPilot) — Tool that allows the AI to control your device in the same way you do, enabling automation for everything! ☆`50`
- [imprvhub/mcp-browser-agent](https://github.com/imprvhub/mcp-browser-agent) — A Model Context Protocol (MCP) integration that provides Claude Desktop with autonomous browser automation capabilities. This agent enables Claude to interact with web content, manipulate DOM elements, execute JavaScript, and perform API requests. ☆`29`
- [lightpanda-io/gomcp](https://github.com/lightpanda-io/gomcp) — Lightpanda MCP server written in Go ☆`44`
- [freema/firefox-devtools-mcp](https://github.com/freema/firefox-devtools-mcp) — Model Context Protocol server for Firefox DevTools - enables AI assistants to inspect and control Firefox browser through the Remote Debugging Protocol ☆`19`
- [BB-fat/browser-use-rs](https://github.com/BB-fat/browser-use-rs) — A Rust library for browser automation via Chrome DevTools Protocol with built-in AI integration through Model Context Protocol (MCP) ☆`16`
- [kimtth/mcp-aoai-web-browsing](https://github.com/kimtth/mcp-aoai-web-browsing) — A minimal Model Context Protocol server/clientwith Azure OpenAI and web browser control via Playwright. ☆`31`
### CLI Tools

- [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) — This is MCP server for Claude that gives it terminal control, file system search and diff file editing capabilities ☆`5,125`
- [chrishayuk/mcp-cli](https://github.com/chrishayuk/mcp-cli) —  ☆`1,786`
- [rusiaaman/wcgw](https://github.com/rusiaaman/wcgw) — Shell and coding agent on claude desktop app ☆`626`
- [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp) — A Model Context Protocol server that executes commands in the current iTerm session - useful for REPL and CLI assistance ☆`504`
- [aymericzip/intlayer](https://github.com/aymericzip/intlayer) — Per-component Internationalisation solution for JS application focusing on scalability. Type-Safe. Translate with AI. Edit Visually. ☆`465`
- [wong2/mcp-cli](https://github.com/wong2/mcp-cli) — A CLI inspector for the Model Context Protocol ☆`397`
- [claude-did-this/MCPControl](https://github.com/claude-did-this/MCPControl) — MCP server for Windows OS automation ☆`260`
- [g0t4/mcp-server-commands](https://github.com/g0t4/mcp-server-commands) — Model Context Protocol server to run commands ☆`218`
- [tufantunc/ssh-mcp](https://github.com/tufantunc/ssh-mcp) — MCP server exposing SSH control for Linux servers via Model Context Protocol. ☆`180`
- [nickgnd/tmux-mcp](https://github.com/nickgnd/tmux-mcp) — A MCP server for our beloved terminal multiplexer tmux. ☆`174`
- [tumf/mcp-shell-server](https://github.com/tumf/mcp-shell-server) — Secure shell command execution server with whitelisted commands and stdin support ☆`156`
- [MladenSU/cli-mcp-server](https://github.com/MladenSU/cli-mcp-server) — Command line interface for MCP clients with secure execution and customizable security policies ☆`156`
- [inercia/MCPShell](https://github.com/inercia/MCPShell) — Use shell scripts as MCP tools ☆`48`
- [automateyournetwork/pyATS_MCP](https://github.com/automateyournetwork/pyATS_MCP) — An MCP Server for pyATS (experimental) ☆`52`
- [sonirico/mcp-shell](https://github.com/sonirico/mcp-shell) — Give hands to AI. MCP server to run shell commands securely, auditably, and on demand. ☆`51`
- [NakaokaRei/swift-mcp-gui](https://github.com/NakaokaRei/swift-mcp-gui) — MCP server that can execute commands such as keyboard input and mouse movement on macOS ☆`49`
- [maxim-saplin/mcp_safe_local_python_executor](https://github.com/maxim-saplin/mcp_safe_local_python_executor) — Stdio MCP Server wrapping custom Python runtime (LocalPythonExecutor) from Hugging Faces' `smolagents` framework. The runtime combines the ease of setup (compared to docker, VM, cloud runtimes) while providing safeguards and limiting operations/imports that are allowed inside the runtime. ☆`40`
- [GoPlausible/algorand-mcp](https://github.com/GoPlausible/algorand-mcp) — Algorand Model Context Protocol (Server & Client) ☆`38`
- [Decodo/mcp-web-scraper](https://github.com/Decodo/mcp-web-scraper) — The Decodo MCP server which enables MCP clients to interface with services. ☆`17`
- [PhialsBasement/CMD-MCP-Server](https://github.com/PhialsBasement/CMD-MCP-Server) — MCP server for executing CMD commands. Can be hooked to claude for additional agentics. ☆`22`
- [JoshuaRileyDev/mac-apps-launcher](https://github.com/JoshuaRileyDev/mac-apps-launcher) — MCP server for launching and managing macOS applications ☆`16`
### Cloud & Infrastructure

- [apache/apisix](https://github.com/apache/apisix) — The Cloud-Native API Gateway and AI Gateway ☆`16,013`
- [awslabs/mcp](https://github.com/awslabs/mcp) — AWS MCP Servers — helping you get the most out of AWS, wherever you use MCP. ☆`7,718`
- [GreptimeTeam/greptimedb](https://github.com/GreptimeTeam/greptimedb) — Open-source, cloud-native, unified observability database for metrics, logs and traces, supporting SQL/PromQL/Streaming. ☆`5,839`
- [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) —  ☆`3,220`
- [Flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) — MCP Server for kubernetes management commands ☆`1,229`
- [microsoft/azure-devops-mcp](https://github.com/microsoft/azure-devops-mcp) — The MCP server for Azure DevOps, bringing the power of Azure DevOps directly to your agents. ☆`1,104`
- [containers/kubernetes-mcp-server](https://github.com/containers/kubernetes-mcp-server) — Model Context Protocol (MCP) server for Kubernetes and OpenShift ☆`911`
- [weibaohui/k8m](https://github.com/weibaohui/k8m) — Lightweight cross-platform Mini Kubernetes AI Dashboard with multi-cluster management, intelligent analysis, and... ☆`744`
- [rohitg00/kubectl-mcp-server](https://github.com/rohitg00/kubectl-mcp-server) — Chat with your Kubernetes Cluster using AI tools and IDEs like Claude and Cursor! ☆`747`
- [GoogleCloudPlatform/cloud-run-mcp](https://github.com/GoogleCloudPlatform/cloud-run-mcp) — MCP server to deploy apps to Cloud Run ☆`494`
- [strowk/mcp-k8s-go](https://github.com/strowk/mcp-k8s-go) — MCP server connecting to Kubernetes ☆`367`
- [nwiizo/tfmcp](https://github.com/nwiizo/tfmcp) — Terraform Model Context Protocol (MCP) Tool - An experimental CLI tool that enables AI assistants to manage and operate Terraform environments. Supports reading Terraform configurations, analyzing plans, applying configurations, and managing state with Claude Desktop integration. ☆`347`
- [alexei-led/aws-mcp-server](https://github.com/alexei-led/aws-mcp-server) — A lightweight service that enables AI assistants to execute AWS CLI commands (in safe containerized environment) through the Model Context Protocol (MCP). Bridges Claude, Cursor, and other MCP-aware AI tools with AWS CLI for enhanced cloud infrastructure management. ☆`168`
- [babelcloud/gbox](https://github.com/babelcloud/gbox) — Cli and MCP for gbox. Enable AI agents to operate Android/Browser/Desktop like human. ☆`157`
- [alexei-led/k8s-mcp-server](https://github.com/alexei-led/k8s-mcp-server) — K8s-mcp-server is a Model Context Protocol (MCP) server that enables AI assistants like Claude to securely execute Kubernetes commands. It provides a bridge between language models and essential Kubernetes CLI tools including kubectl, helm, istioctl, and argocd, allowing AI systems to assist with cluster management, troubleshooting, and deployments ☆`178`
- [weibaohui/kom](https://github.com/weibaohui/kom) — A Kubernetes operations SDK tool wrapping kubectl and client-go, also supports MCP server for k8s management ☆`138`
- [silenceper/mcp-k8s](https://github.com/silenceper/mcp-k8s) — A Kubernetes MCP (Model Control Protocol) server that enables interaction with Kubernetes clusters through MCP tools. ☆`131`
- [reza-gholizade/k8s-mcp-server](https://github.com/reza-gholizade/k8s-mcp-server) — Manage Your Kubernetes Cluster with k8s mcp-server ☆`128`
- [aliyun/alibaba-cloud-ops-mcp-server](https://github.com/aliyun/alibaba-cloud-ops-mcp-server) — AlibabaCloud CloudOps MCP Server ☆`88`
- [portainer/portainer-mcp](https://github.com/portainer/portainer-mcp) — Portainer MCP server ☆`96`
- [StacklokLabs/mkp](https://github.com/StacklokLabs/mkp) — MKP is a Model Context Protocol (MCP) server for Kubernetes ☆`55`
- [aws-powertools/powertools-mcp](https://github.com/aws-powertools/powertools-mcp) — Powertools for AWS's official MCP Server ☆`40`
- [kenliao94/mcp-server-rabbitmq](https://github.com/kenliao94/mcp-server-rabbitmq) — MCP server for interacting with RabbitMQ ☆`40`
- [bright8192/esxi-mcp-server](https://github.com/bright8192/esxi-mcp-server) — A VMware ESXi/vCenter management server based on MCP (Model Control Protocol), providing simple REST API interfaces for virtual machine management. ☆`51`
- [dkruyt/mcp-hetzner](https://github.com/dkruyt/mcp-hetzner) — A Model Context Protocol (MCP) server for interacting with the Hetzner Cloud API. This server allows language models to manage Hetzner Cloud resources through structured functions. ☆`58`
- [aliyun/alibabacloud-devops-mcp-server](https://github.com/aliyun/alibabacloud-devops-mcp-server) — Yunxiao MCP Server provides AI assistants with the ability to interact with the Yunxiao platform. It provides a set of tools that interact with Yunxiao's API, allowing AI assistants to manage Codeup repository, Project, Pipeline, Packages etc. ☆`35`
- [qiniu/qiniu-mcp-server](https://github.com/qiniu/qiniu-mcp-server) — MCP server for Qiniu Cloud services including storage, CDN, media processing, and live streaming ☆`32`
- [aliyun/alibabacloud-dataworks-mcp-server](https://github.com/aliyun/alibabacloud-dataworks-mcp-server) — A Model Context Protocol (MCP) server that provides tools for AI, allowing it to interact with the DataWorks Open API through a standardized interface. This implementation is based on the Aliyun Open API and enables AI agents to perform cloud resources operations seamlessly. ☆`25`
- [redis/mcp-redis-cloud](https://github.com/redis/mcp-redis-cloud) —  ☆`38`
- [openstack-kr/python-openstackmcp-server](https://github.com/openstack-kr/python-openstackmcp-server) — openstack mcp server ☆`17`
- [localstack/localstack-mcp-server](https://github.com/localstack/localstack-mcp-server) — MCP Server for LocalStack ☆`16`
- [kestra-io/mcp-server-python](https://github.com/kestra-io/mcp-server-python) — Python MCP Server for Kestra — you can use it as a tool in Kestra's AI Agents ☆`16`
- [cyclops-ui/mcp-cyclops](https://github.com/cyclops-ui/mcp-cyclops) — Model Context Protocol server for Cyclops ☆`29`
- [wenhuwang/mcp-k8s-eye](https://github.com/wenhuwang/mcp-k8s-eye) — MCP Server for kubernetes management and diagnose your cluster and applications ☆`26`
- [aliyun/alibabacloud-hologres-mcp-server](https://github.com/aliyun/alibabacloud-hologres-mcp-server) —  ☆`25`
- [trilogy-group/aws-pricing-mcp](https://github.com/trilogy-group/aws-pricing-mcp) — An MCP server that exposes AWS EC2 pricing data with an option to search by CPU, RAM, networking ☆`17`
### Communication & Messaging

- [elie222/inbox-zero](https://github.com/elie222/inbox-zero) — The world's best AI personal assistant for email. Open source app to help you reach inbox zero fast. ☆`9,627`
- [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) — WhatsApp MCP server ☆`5,164`
- [korotovsky/slack-mcp-server](https://github.com/korotovsky/slack-mcp-server) — The most powerful MCP Slack Server with no permission requirements, Apps support, multiple transports Stdio and SSE, DMs, Group DMs and smart history fetch logic. ☆`1,031`
- [dmayboroda/minima](https://github.com/dmayboroda/minima) — On-premises conversational RAG with configurable containers ☆`1,021`
- [chigwell/telegram-mcp](https://github.com/chigwell/telegram-mcp) — Telegram MCP server powered by Telethon to let MCP clients read chats, manage groups, and send/modify messages, media, contacts, and settings. ☆`509`
- [line/line-bot-mcp-server](https://github.com/line/line-bot-mcp-server) — MCP server that integrates the LINE Messaging API to connect an AI Agent to the LINE Official Account. ☆`505`
- [joinly-ai/joinly](https://github.com/joinly-ai/joinly) — Make your meetings accessible to AI Agents ☆`415`
- [Softeria/ms-365-mcp-server](https://github.com/Softeria/ms-365-mcp-server) — A Model Context Protocol (MCP) server for interacting with Microsoft 365 and Office services through the Graph API ☆`371`
- [InditexTech/mcp-teams-server](https://github.com/InditexTech/mcp-teams-server) — An MCP (Model Context Protocol) server implementation for Microsoft Teams integration, providing capabilities to read messages, create messages, reply to messages, mention members. ☆`340`
- [jerhadf/linear-mcp-server](https://github.com/jerhadf/linear-mcp-server) — A server that integrates Linear's project management system with the Model Context Protocol (MCP) to allow LLMs to interact with Linear. ☆`339`
- [chaindead/telegram-mcp](https://github.com/chaindead/telegram-mcp) — Telegram MCP for managing dialogs, messages, drafts, read statuses, and more. ☆`257`
- [adhikasp/mcp-twikit](https://github.com/adhikasp/mcp-twikit) — A Model Context Protocol (MCP) server for interacting with Twitter. ☆`216`
- [carterlasalle/mac_messages_mcp](https://github.com/carterlasalle/mac_messages_mcp) — An MCP server that securely interfaces with your iMessage database via the Model Context Protocol (MCP), allowing LLMs to query and analyze iMessage conversations. It includes robust phone number validation, attachment processing, contact management, group chat handling, and full support for sending and receiving messages. ☆`206`
- [trypeggy/instagram_dm_mcp](https://github.com/trypeggy/instagram_dm_mcp) — Instagram Direct messages MCP ☆`145`
- [SaseQ/discord-mcp](https://github.com/SaseQ/discord-mcp) — A MCP server for the Discord integration. Enable your AI assistants to seamlessly interact with Discord. Enhance your Discord experience with powerful automation capabilities. ☆`140`
- [zcaceres/gtasks-mcp](https://github.com/zcaceres/gtasks-mcp) — A Google Tasks Model Context Protocol Server for Claude ☆`97`
- [ztxtxwd/open-feishu-mcp-server](https://github.com/ztxtxwd/open-feishu-mcp-server) — MCP server for Feishu (Lark) with OAuth authentication and document management tools ☆`70`
- [areweai/tsgram-mcp](https://github.com/areweai/tsgram-mcp) — TSGram - Telegram MCP Server for local Claude Code integration - debug and vibe code on the go! ☆`86`
- [hannesrudolph/imessage-query-fastmcp-mcp-server](https://github.com/hannesrudolph/imessage-query-fastmcp-mcp-server) — An MCP server that provides safe access to your iMessage database through Model Context Protocol (MCP). This server is built with the FastMCP framework and the imessagedb library, enabling LLMs to query and analyze iMessage conversations with proper phone number validation and attachment handling. ☆`72`
- [mailtrap/mailtrap-mcp](https://github.com/mailtrap/mailtrap-mcp) — Official mailtrap.io MCP server ☆`51`
- [Shy2593666979/mcp-server-email](https://github.com/Shy2593666979/mcp-server-email) — MCP-based email service supporting sending emails with attachments, compatible with Gmail, Outlook, QQ Mail and more ☆`66`
- [gitmotion/ntfy-me-mcp](https://github.com/gitmotion/ntfy-me-mcp) — An ntfy MCP server for sending/fetching ntfy notifications to any/self-hosted ntfy.sh server from AI Agents (supports secure token auth & more - use with npx or docker!) ☆`46`
- [sawa-zen/vrchat-mcp](https://github.com/sawa-zen/vrchat-mcp) — This project is a Model Context Protocol (MCP) server for interacting with the VRChat API. ☆`49`
- [discourse/discourse-mcp](https://github.com/discourse/discourse-mcp) — MCP client for Discourse sites ☆`30`
- [arpitbatra123/mcp-googletasks](https://github.com/arpitbatra123/mcp-googletasks) — This Model Context Protocol (MCP) server provides a bridge between Claude and Google Tasks, allowing you to manage your task lists and tasks directly through Claude. ☆`28`
- [Cactusinhand/mcp_server_notify](https://github.com/Cactusinhand/mcp_server_notify) — Send system notification when Agent task is done. ☆`42`
- [teddyzxcv/ntfy-mcp](https://github.com/teddyzxcv/ntfy-mcp) —  ☆`43`
- [infobip/mcp](https://github.com/infobip/mcp) — Infobip Remote MCP Servers Documentation ☆`22`
- [AbdelStark/nostr-mcp](https://github.com/AbdelStark/nostr-mcp) — A Nostr MCP server that allows to interact with Nostr, enabling posting notes, and more. ☆`37`
- [jaipandya/producthunt-mcp-server](https://github.com/jaipandya/producthunt-mcp-server) —  ☆`35`
- [laulauland/bluesky-context-server](https://github.com/laulauland/bluesky-context-server) — Bluesky MCP server ☆`29`
- [gotoolkits/mcp-wecombot-server](https://github.com/gotoolkits/mcp-wecombot-server) — An MCP server application that sends various types of messages to the WeCom group robot. ☆`32`
- [jagan-shanmugam/mattermost-mcp-host](https://github.com/jagan-shanmugam/mattermost-mcp-host) — A Mattermost integration that connects to Model Context Protocol (MCP) servers, leveraging a LangGraph-based Agent. ☆`28`
- [wyattjoh/imessage-mcp](https://github.com/wyattjoh/imessage-mcp) — A Model Context Protocol server for reading iMessage data from macOS. ☆`18`
### CRM & ERP

- [antvis/mcp-server-chart](https://github.com/antvis/mcp-server-chart) — A visualization mcp contains 25+ visual charts using @antvis. Using for chart generation and data analysis. ☆`3,364`
- [hustcc/mcp-mermaid](https://github.com/hustcc/mcp-mermaid) — Generate mermaid diagram and chart with AI MCP dynamically. ☆`342`
- [hustcc/mcp-echarts](https://github.com/hustcc/mcp-echarts) — Generate visual charts using ECharts with AI MCP dynamically, used for chart generation and data analysis. ☆`175`
- [ivnvxd/mcp-server-odoo](https://github.com/ivnvxd/mcp-server-odoo) — A Model Context Protocol (MCP) server that enables AI assistants to securely interact with Odoo ERP systems through standardized resources and tools for data retrieval and manipulation. ☆`121`
- [OpenDataMCP/OpenDataMCP](https://github.com/OpenDataMCP/OpenDataMCP) — Connect any Open Data to any LLM with Model Context Protocol. ☆`144`
- [hmk/attio-mcp-server](https://github.com/hmk/attio-mcp-server) — MCP server for Attio CRM, allowing AI clients to read and write company records and notes ☆`16`
### Data & Analytics

- [zcaceres/markdownify-mcp](https://github.com/zcaceres/markdownify-mcp) — A Model Context Protocol server for converting almost anything to Markdown ☆`2,320`
- [datalayer/jupyter-mcp-server](https://github.com/datalayer/jupyter-mcp-server) — Model Context Protocol (MCP) Server for Jupyter. ☆`829`
- [MigoXLab/dingo](https://github.com/MigoXLab/dingo) — Dingo: A Comprehensive AI Data, Model and Application Quality Evaluation Tool ☆`602`
- [reading-plus-ai/mcp-server-data-exploration](https://github.com/reading-plus-ai/mcp-server-data-exploration) —  ☆`516`
- [dbt-labs/dbt-mcp](https://github.com/dbt-labs/dbt-mcp) — A MCP (Model Context Protocol) server for interacting with dbt. ☆`445`
- [jjsantos01/jupyter-notebook-mcp](https://github.com/jjsantos01/jupyter-notebook-mcp) — A Model Context Protocol (MCP) for Jupyter Notebook ☆`113`
- [ChronulusAI/chronulus-mcp](https://github.com/ChronulusAI/chronulus-mcp) — MCP Server for Chronulus AI Forecasting and Prediction Agents ☆`102`
- [keboola/mcp-server](https://github.com/keboola/mcp-server) — Model Context Protocol (MCP) Server for the Keboola Platform ☆`80`
- [isaacwasserman/mcp-vegalite-server](https://github.com/isaacwasserman/mcp-vegalite-server) —  ☆`94`
- [optuna/optuna-mcp](https://github.com/optuna/optuna-mcp) — The Optuna MCP Server is a Model Context Protocol (MCP) server to interact with Optuna APIs. ☆`67`
- [kdqed/zaturn](https://github.com/kdqed/zaturn) — Data Analysis With Vibes ☆`69`
- [JordiNeil/mcp-databricks-server](https://github.com/JordiNeil/mcp-databricks-server) — MCP Server for Databricks ☆`45`
- [aywengo/kafka-schema-reg-mcp](https://github.com/aywengo/kafka-schema-reg-mcp) — A comprehensive Message Control Protocol (MCP) server for Kafka Schema Registry. ☆`27`
- [Unstructured-IO/UNS-MCP](https://github.com/Unstructured-IO/UNS-MCP) —  ☆`38`
- [phisanti/MCPR](https://github.com/phisanti/MCPR) — MCPR enables AI agents to participate in interactive R sessions for professional analysis workflows. ☆`20`
- [growthbook/growthbook-mcp](https://github.com/growthbook/growthbook-mcp) — Official GrowthBook MCP server for creating flags, getting experiments, and more. ☆`16`
- [arrismo/kaggle-mcp](https://github.com/arrismo/kaggle-mcp) — MCP server for Kaggle ☆`32`
- [mattijsdp/dbt-docs-mcp](https://github.com/mattijsdp/dbt-docs-mcp) — MCP (model context protocol) server for interacting with dbt Docs ☆`21`
- [HumanSignal/label-studio-mcp-server](https://github.com/HumanSignal/label-studio-mcp-server) —  ☆`25`
- [subelsky/bundler_mcp](https://github.com/subelsky/bundler_mcp) — A Model Context Protocol (MCP) server enabling AI agents to query information about gems in a Ruby project's Gemfile, including source code and metadata. ☆`19`
### Databases

- [googleapis/genai-toolbox](https://github.com/googleapis/genai-toolbox) — MCP Toolbox for Databases is an open source MCP server for databases. ☆`11,949`
- [instantdb/instant](https://github.com/instantdb/instant) — Instant is a modern Firebase. We make you productive by giving your frontend a real-time database. ☆`9,541`
- [baserow/baserow](https://github.com/baserow/baserow) — Build databases, automations, apps & agents with AI — no code. Open source platform available on cloud and self-hosted. GDPR, HIPAA, SOC 2 compliant. Best Airtable alternative. ☆`3,605`
- [supabase-community/supabase-mcp](https://github.com/supabase-community/supabase-mcp) — Connect Supabase to your AI assistants ☆`2,346`
- [bytebase/dbhub](https://github.com/bytebase/dbhub) — Minimal, token-efficient database MCP server for Postgres, MySQL, SQL Server, MariaDB, SQLite. ☆`1,786`
- [crystaldba/postgres-mcp](https://github.com/crystaldba/postgres-mcp) — Postgres MCP Pro provides configurable read/write access and performance analysis for you and your AI agents. ☆`1,705`
- [qdrant/mcp-server-qdrant](https://github.com/qdrant/mcp-server-qdrant) — An official Qdrant Model Context Protocol (MCP) server implementation ☆`1,144`
- [designcomputer/mysql_mcp_server](https://github.com/designcomputer/mysql_mcp_server) — A Model Context Protocol (MCP) server that enables secure interaction with MySQL databases ☆`1,042`
- [benborla/mcp-server-mysql](https://github.com/benborla/mcp-server-mysql) — A Model Context Protocol server that provides read-only access to MySQL databases. This server enables LLMs to inspect database schemas and execute read-only queries. ☆`1,009`
- [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j) — Neo4j Labs Model Context Protocol servers ☆`856`
- [alexander-zuev/supabase-mcp-server](https://github.com/alexander-zuev/supabase-mcp-server) — Query MCP enables end-to-end management of Supabase via chat interface: read & write query executions, management API support, automatic migration versioning, access to logs and much more. ☆`815`
- [ClickHouse/mcp-clickhouse](https://github.com/ClickHouse/mcp-clickhouse) — Connect ClickHouse to your AI assistants. ☆`628`
- [xing5/mcp-google-sheets](https://github.com/xing5/mcp-google-sheets) — This MCP server integrates with your Google Drive and Google Sheets, to enable creating and modifying spreadsheets. ☆`569`
- [neondatabase/mcp-server-neon](https://github.com/neondatabase/mcp-server-neon) — MCP server for interacting with Neon Management API and databases ☆`531`
- [Canner/wren-engine](https://github.com/Canner/wren-engine) — The Semantic Engine for Model Context Protocol(MCP) Clients and AI Agents ☆`518`
- [subnetmarco/pgmcp](https://github.com/subnetmarco/pgmcp) — An MCP server to query any Postgres database in natural language. ☆`516`
- [centralmind/gateway](https://github.com/centralmind/gateway) — Universal MCP-Server for your Databases optimized for LLMs and AI-Agents. ☆`505`
- [chroma-core/chroma-mcp](https://github.com/chroma-core/chroma-mcp) — A Model Context Protocol (MCP) server implementation that provides database capabilities for Chroma ☆`448`
- [domdomegg/airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server) — Airtable Model Context Protocol Server, for allowing AI systems to interact with your Airtable bases ☆`373`
- [motherduckdb/mcp-server-motherduck](https://github.com/motherduckdb/mcp-server-motherduck) — MCP server for DuckDB and MotherDuck ☆`384`
- [redis/mcp-redis](https://github.com/redis/mcp-redis) — The official Redis MCP Server is a natural language interface designed for agentic applications to manage and search data in Redis efficiently ☆`371`
- [runekaagaard/mcp-alchemy](https://github.com/runekaagaard/mcp-alchemy) — A MCP (model context protocol) server that gives the LLM access to and knowledge about relational databases like SQLite, Postgresql, MySQL & MariaDB, Oracle, and MS-SQL. ☆`379`
- [pab1it0/prometheus-mcp-server](https://github.com/pab1it0/prometheus-mcp-server) — A Model Context Protocol (MCP) server that enables AI agents and LLMs to query and analyze Prometheus metrics through standardized interfaces. ☆`324`
- [FreePeak/db-mcp-server](https://github.com/FreePeak/db-mcp-server) — A powerful multi-database server implementing the Model Context Protocol (MCP) to provide AI assistants with structured access to databases. ☆`325`
- [wenb1n-dev/mysql_mcp_server_pro](https://github.com/wenb1n-dev/mysql_mcp_server_pro) — Enhanced MySQL MCP server with database anomaly analysis capabilities and easy extensibility for developers ☆`284`
- [kiliczsh/mcp-mongo-server](https://github.com/kiliczsh/mcp-mongo-server) — A Model Context Protocol Server for MongoDB ☆`269`
- [apache/doris-mcp-server](https://github.com/apache/doris-mcp-server) — Apache Doris MCP Server ☆`234`
- [cr7258/elasticsearch-mcp-server](https://github.com/cr7258/elasticsearch-mcp-server) — A Model Context Protocol (MCP) server implementation that provides Elasticsearch and OpenSearch interaction. ☆`232`
- [gannonh/firebase-mcp](https://github.com/gannonh/firebase-mcp) — Model Context Protocol (MCP) server for Firebase. ☆`231`
- [XGenerationLab/xiyan_mcp_server](https://github.com/XGenerationLab/xiyan_mcp_server) — A Model Context Protocol (MCP) server that enables natural language queries to databases ☆`225`
- [zilliztech/mcp-server-milvus](https://github.com/zilliztech/mcp-server-milvus) — Model Context Protocol Servers for Milvus ☆`206`
- [Snowflake-Labs/mcp](https://github.com/Snowflake-Labs/mcp) — MCP Server for Snowflake including Cortex AI, object management, SQL orchestration, semantic view consumption, and more ☆`197`
- [isaacwasserman/mcp-snowflake-server](https://github.com/isaacwasserman/mcp-snowflake-server) —  ☆`170`
- [furey/mongodb-lens](https://github.com/furey/mongodb-lens) — MongoDB Lens: Full Featured MCP Server for MongoDB Databases ☆`195`
- [QuantGeekDev/mongo-mcp](https://github.com/QuantGeekDev/mongo-mcp) — A mongo db server for the model context protocol (MCP) ☆`174`
- [aliyun/alibabacloud-tablestore-mcp-server](https://github.com/aliyun/alibabacloud-tablestore-mcp-server) —  ☆`150`
- [ktanaka101/mcp-server-duckdb](https://github.com/ktanaka101/mcp-server-duckdb) — A Model Context Protocol (MCP) server implementation for DuckDB, providing database interaction capabilities ☆`173`
- [weaviate/mcp-server-weaviate](https://github.com/weaviate/mcp-server-weaviate) — MCP (Model Context Protocol) server for Weaviate ☆`160`
- [StarRocks/mcp-server-starrocks](https://github.com/StarRocks/mcp-server-starrocks) — StarRocks MCP (Model Context Protocol) Server ☆`136`
- [f4ww4z/mcp-mysql-server](https://github.com/f4ww4z/mcp-mysql-server) — A Model Context Protocol server for MySQL database operations ☆`137`
- [confluentinc/mcp-confluent](https://github.com/confluentinc/mcp-confluent) —  ☆`123`
- [ergut/mcp-bigquery-server](https://github.com/ergut/mcp-bigquery-server) — A Model Context Protocol (MCP) server that provides secure, read-only access to BigQuery datasets. Enables Large Language Models (LLMs) to safely query and analyze data through a standardized interface. ☆`130`
- [LucasHild/mcp-server-bigquery](https://github.com/LucasHild/mcp-server-bigquery) — A Model Context Protocol server that provides access to BigQuery ☆`120`
- [wenb1n-dev/SmartDB_MCP](https://github.com/wenb1n-dev/SmartDB_MCP) — Universal database MCP server connecting to MySQL, PostgreSQL, SQL Server, MariaDB,DM8,Oracle,not only provides basic database connection such as OAuth 2.0 authentication , health checks, SQL optimization, and index health detection ☆`110`
- [oceanbase/awesome-oceanbase-mcp](https://github.com/oceanbase/awesome-oceanbase-mcp) — MCP Server for OceanBase database and its tools ☆`87`
- [tuannvm/mcp-trino](https://github.com/tuannvm/mcp-trino) — A high-performance Model Context Protocol (MCP) server for Trino implemented in Go. ☆`86`
- [hannesrudolph/sqlite-explorer-fastmcp-mcp-server](https://github.com/hannesrudolph/sqlite-explorer-fastmcp-mcp-server) — An MCP server that provides safe, read-only access to SQLite databases through Model Context Protocol (MCP). This server is built with the FastMCP framework, which enables LLMs to explore and query SQLite databases with built-in safety features and query validation. ☆`97`
- [ChristianHinge/dicom-mcp](https://github.com/ChristianHinge/dicom-mcp) — Model Context Protocol (MCP) for interacting with dicom servers (PACS etc.) ☆`75`
- [donghao1393/mcp-dbutils](https://github.com/donghao1393/mcp-dbutils) — All-in-one MCP service for secure database connections supporting SQLite, MySQL, PostgreSQL and more ☆`86`
- [TheRaLabs/legion-mcp](https://github.com/TheRaLabs/legion-mcp) — A server that helps people access and query data in databases using the Legion Query Runner with Model Context Protocol (MCP) in Python. ☆`79`
- [rashidazarang/airtable-mcp](https://github.com/rashidazarang/airtable-mcp) — Airtable integration for AI-powered applications via Anthropic's Model Context Protocol (MCP) ☆`59`
- [jparkerweb/mcp-sqlite](https://github.com/jparkerweb/mcp-sqlite) — Model Context Protocol (MCP) server that provides comprehensive SQLite database interaction capabilities ☆`73`
- [pab1it0/adx-mcp-server](https://github.com/pab1it0/adx-mcp-server) — A Model Context Protocol (MCP) server that enables AI assistants to query and analyze Azure Data Explorer databases through standardized interfaces. ☆`50`
- [Teradata/teradata-mcp-server](https://github.com/Teradata/teradata-mcp-server) — The community development of a MCP server for a Teradata database ☆`35`
- [edwinbernadus/nocodb-mcp-server](https://github.com/edwinbernadus/nocodb-mcp-server) — nocodb mcp server ☆`55`
- [VictoriaMetrics-Community/mcp-victorialogs](https://github.com/VictoriaMetrics-Community/mcp-victorialogs) — The implementation of Model Context Protocol (MCP) server for VictoriaLogs. ☆`40`
- [freema/mcp-gsheets](https://github.com/freema/mcp-gsheets) — MCP server for Google Sheets - Read, write and manipulate spreadsheets through Claude Desktop ☆`39`
- [Zhwt/go-mcp-mysql](https://github.com/Zhwt/go-mcp-mysql) — Zero burden, ready-to-use Model Context Protocol (MCP) server for interacting with MySQL and automation. No Node.js or Python environment needed. ☆`48`
- [prisma/mcp](https://github.com/prisma/mcp) — Prisma MCP servers for database workflows with local and remote deployment options ☆`31`
- [Couchbase-Ecosystem/mcp-server-couchbase](https://github.com/Couchbase-Ecosystem/mcp-server-couchbase) — MCP Server to interact with data in Couchbase Clusters ☆`25`
- [idoru/influxdb-mcp-server](https://github.com/idoru/influxdb-mcp-server) — An MCP Server for querying InfluxDB ☆`28`
- [singlestore-labs/mcp-server-singlestore](https://github.com/singlestore-labs/mcp-server-singlestore) — MCP server for interacting with SingleStore Management API and services ☆`26`
- [JoshuaRileyDev/supabase-mcp-server](https://github.com/JoshuaRileyDev/supabase-mcp-server) —  ☆`50`
- [GreptimeTeam/greptimedb-mcp-server](https://github.com/GreptimeTeam/greptimedb-mcp-server) — A Model Context Protocol (MCP) server for GreptimeDB ☆`23`
- [influxdata/influxdb3_mcp_server](https://github.com/influxdata/influxdb3_mcp_server) — MCP Server for InfluxDB 3 ☆`23`
- [s2-streamstore/s2-sdk-typescript](https://github.com/s2-streamstore/s2-sdk-typescript) — S2 SDK for TypeScript ☆`21`
- [panasenco/mcp-sqlite](https://github.com/panasenco/mcp-sqlite) — MCP server for SQLite files. Supports Datasette-compatible metadata! ☆`16`
- [ydb-platform/ydb-mcp](https://github.com/ydb-platform/ydb-mcp) —  ☆`24`
- [fireproof-storage/mcp-database-server](https://github.com/fireproof-storage/mcp-database-server) — Store and load JSON documents from LLM tool use ☆`29`
- [c4pt0r/mcp-server-tidb](https://github.com/c4pt0r/mcp-server-tidb) — mcp server for tidb ☆`22`
- [OpenLinkSoftware/mcp-sqlalchemy-server](https://github.com/OpenLinkSoftware/mcp-sqlalchemy-server) — A simple MCP ODBC server using FastAPI, ODBC and SQLAlchemy. ☆`19`
- [Dataring-engineering/mcp-server-trino](https://github.com/Dataring-engineering/mcp-server-trino) — MCP Server for Trino ☆`18`
- [niledatabase/nile-mcp-server](https://github.com/niledatabase/nile-mcp-server) — MCP server for Nile Database - Manage and query databases, tenants, users, auth using LLMs ☆`16`
- [Xexr/mcp-libsql](https://github.com/Xexr/mcp-libsql) — Secure MCP server for libSQL databases with comprehensive tools, connection pooling, and transaction support. Built with TypeScript for Claude Desktop, Claude Code, Cursor, and other MCP clients. ☆`16`
### Developer Tools

- [upstash/context7](https://github.com/upstash/context7) — Context7 MCP Server -- Up-to-date code documentation for LLMs and AI code editors ☆`40,070`
- [eyaltoledano/claude-task-master](https://github.com/eyaltoledano/claude-task-master) — An AI-powered task-management system you can drop into Cursor, Lovable, Windsurf, Roo, and others. ☆`24,407`
- [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) — MCP server to provide Figma layout information to AI coding agents like Cursor ☆`12,325`
- [trycua/cua](https://github.com/trycua/cua) — Open-source infrastructure for Computer-Use Agents. Sandboxes, SDKs, and benchmarks to train and evaluate AI agents that can control full desktops (macOS, Linux, Windows). ☆`11,586`
- [idosal/git-mcp](https://github.com/idosal/git-mcp) — Put an end to code hallucinations! GitMCP is a free, open-source, remote MCP server for any GitHub project ☆`7,264`
- [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server) — Official Firecrawl MCP Server - Adds powerful web scraping and search to Cursor, Claude and any other LLM clients. ☆`5,126`
- [lingodotdev/lingo.dev](https://github.com/lingodotdev/lingo.dev) — Lingo.dev - open-source, AI-powered i18n toolkit for instant localization with LLMs. Bring your own LLM or use Lingo.dev Localization Engine. Join discord: ☆`5,067`
- [21st-dev/magic-mcp](https://github.com/21st-dev/magic-mcp) — It's like v0 but in your Cursor/WindSurf/Cline. 21st dev Magic MCP server for working with your frontend like Magic ☆`4,040`
- [cameroncooke/XcodeBuildMCP](https://github.com/cameroncooke/XcodeBuildMCP) — A Model Context Protocol (MCP) server that provides Xcode-related tools for integration with AI assistants and other MCP clients. ☆`3,163`
- [haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server) — A Model Context Protocol server for Excel file manipulation ☆`3,024`
- [mobile-next/mobile-mcp](https://github.com/mobile-next/mobile-mcp) — Model Context Protocol Server for Mobile Automation and Scraping (iOS, Android, Emulators, Simulators and Real Devices) ☆`2,780`
- [Jpisnice/shadcn-ui-mcp-server](https://github.com/Jpisnice/shadcn-ui-mcp-server) — A mcp server to allow LLMS gain context about shadcn ui component structure,usage and installation,compaitable with react,svelte 5,vue & React Native ☆`2,554`
- [cjo4m06/mcp-shrimp-task-manager](https://github.com/cjo4m06/mcp-shrimp-task-manager) — Shrimp Task Manager is a task tool built for AI Agents, emphasizing chain-of-thought, reflection, and style consistency. It converts natural language into structured dev tasks with dependency tracking and iterative refinement, enabling agent-like developer behavior in reasoning AI systems. ☆`1,936`
- [perplexityai/modelcontextprotocol](https://github.com/perplexityai/modelcontextprotocol) — The official MCP server implementation for the Perplexity API Platform ☆`1,844`
- [brightdata/brightdata-mcp](https://github.com/brightdata/brightdata-mcp) — A powerful Model Context Protocol (MCP) server that provides an all-in-one solution for public web access. ☆`1,776`
- [anaisbetts/mcp-installer](https://github.com/anaisbetts/mcp-installer) — An MCP server that installs other MCP servers for you ☆`1,484`
- [joshuayoes/ios-simulator-mcp](https://github.com/joshuayoes/ios-simulator-mcp) — MCP server for interacting with the iOS simulator ☆`1,346`
- [isaacphi/mcp-language-server](https://github.com/isaacphi/mcp-language-server) — mcp-language-server gives MCP enabled clients access semantic tools like get definition, references, rename, and diagnostics. ☆`1,336`
- [JetBrains/mcp-jetbrains](https://github.com/JetBrains/mcp-jetbrains) — A model context protocol server to work with JetBrains IDEs: IntelliJ, PyCharm, WebStorm, etc. Also, works with Android Studio ☆`939`
- [robotmcp/ros-mcp-server](https://github.com/robotmcp/ros-mcp-server) — Connect AI models like Claude & GPT with robots using MCP and ROS. ☆`897`
- [janwilmake/openapi-mcp-server](https://github.com/janwilmake/openapi-mcp-server) — Allow AI to wade through complex OpenAPIs using Simple Language ☆`865`
- [bhauman/clojure-mcp](https://github.com/bhauman/clojure-mcp) — Clojure MCP ☆`657`
- [bgauryy/octocode-mcp](https://github.com/bgauryy/octocode-mcp) — MCP server for semantic code research and context generation on real-time using LLM patterns | Search naturally across public & private repos based on your permissions | Transform any accessible codebase/s into AI-optimized knowledge on simple and complex flows | Find real implementations and live docs from anywhere ☆`659`
- [zcaceres/fetch-mcp](https://github.com/zcaceres/fetch-mcp) — A flexible HTTP fetching Model Context Protocol server. ☆`658`
- [ckreiling/mcp-server-docker](https://github.com/ckreiling/mcp-server-docker) — MCP server for Docker ☆`660`
- [minhalvp/android-mcp-server](https://github.com/minhalvp/android-mcp-server) — An MCP server that provides control over Android devices via adb ☆`618`
- [automation-ai-labs/mcp-link](https://github.com/automation-ai-labs/mcp-link) — Convert Any OpenAPI V3 API to MCP Server ☆`586`
- [etsd-tech/mcp-pointer](https://github.com/etsd-tech/mcp-pointer) — MCP tool: let you point at DOM elements for your favorite agentic coding tool. Let AI see what you see. ☆`552`
- [jasonjmcghee/claude-debugs-for-you](https://github.com/jasonjmcghee/claude-debugs-for-you) — Enable any LLM (e.g. Claude) to interactively debug any language for you via MCP and a VS Code Extension ☆`477`
- [vivekVells/mcp-pandoc](https://github.com/vivekVells/mcp-pandoc) — MCP server for document format conversion using pandoc. ☆`472`
- [QuantGeekDev/docker-mcp](https://github.com/QuantGeekDev/docker-mcp) — A docker MCP Server (modelcontextprotocol) ☆`438`
- [gitkraken/gk-cli](https://github.com/gitkraken/gk-cli) — GitKraken CLI Releases and Documentation ☆`335`
- [utensils/mcp-nixos](https://github.com/utensils/mcp-nixos) — MCP-NixOS - Model Context Protocol Server for NixOS resources ☆`382`
- [TencentEdgeOne/edgeone-pages-mcp](https://github.com/TencentEdgeOne/edgeone-pages-mcp) — An MCP service designed for deploying HTML content to EdgeOne Pages and obtaining an accessible public URL. ☆`339`
- [blurrah/mcp-graphql](https://github.com/blurrah/mcp-graphql) — Model Context Protocol server for GraphQL ☆`340`
- [r-huijts/xcode-mcp-server](https://github.com/r-huijts/xcode-mcp-server) — MCP Server implementation for Xcode integration ☆`339`
- [hyperb1iss/droidmind](https://github.com/hyperb1iss/droidmind) — Control your Android devices with AI using Model Context Protocol ☆`317`
- [SDGLBL/mcp-claude-code](https://github.com/SDGLBL/mcp-claude-code) — MCP implementation of Claude Code capabilities and more ☆`295`
- [zueai/mcp-manager](https://github.com/zueai/mcp-manager) — simple web ui to manage mcp (model context protocol) servers in the claude app ☆`276`
- [szeider/consult7](https://github.com/szeider/consult7) — MCP server to consult a language model with large context size ☆`277`
- [InditexTech/mcp-server-simulator-ios-idb](https://github.com/InditexTech/mcp-server-simulator-ios-idb) — A Model Context Protocol (MCP) server that enables LLMs to interact with iOS simulators through natural language commands. ☆`279`
- [admica/FileScopeMCP](https://github.com/admica/FileScopeMCP) — Analyzes your codebase identifying important files based on dependency relationships. Generates diagrams and importance scores per file, helping AI assistants understand the codebase. Automatically parses popular programming languages such as Python, C, C++, Rust, Zig, Lua. ☆`271`
- [public-ui/kolibri](https://github.com/public-ui/kolibri) — The accessible HTML-Standard ☆`240`
- [Govcraft/rust-docs-mcp-server](https://github.com/Govcraft/rust-docs-mcp-server) — Prevents outdated Rust code suggestions from AI assistants. This MCP server fetches current crate docs, uses embeddings/LLMs, and provides accurate context via a tool call. ☆`231`
- [JoshuaRileyDev/app-store-connect-mcp-server](https://github.com/JoshuaRileyDev/app-store-connect-mcp-server) —  ☆`236`
- [jamsocket/forevervm](https://github.com/jamsocket/forevervm) — Securely run AI-generated code in stateful sandboxes that run forever. ☆`224`
- [biegehydra/BifrostMCP](https://github.com/biegehydra/BifrostMCP) — VSCode Extension with an MCP server that exposes semantic tools like Find Usages and Rename to LLMs ☆`194`
- [comet-ml/opik-mcp](https://github.com/comet-ml/opik-mcp) — Model Context Protocol (MCP) implementation for Opik enabling seamless IDE integration and unified access to prompts, projects, traces, and metrics. ☆`193`
- [YuChenSSR/mindmap-mcp-server](https://github.com/YuChenSSR/mindmap-mcp-server) — mindmap, mcp server, artifact ☆`208`
- [muxinc/mux-node-sdk](https://github.com/muxinc/mux-node-sdk) — Official Mux API wrapper for Node projects, supporting both Mux Data and Mux Video. ☆`172`
- [tumf/mcp-text-editor](https://github.com/tumf/mcp-text-editor) — Line-oriented text file editing MCP server optimized for LLM tools with partial file access ☆`177`
- [mhmzdev/figma-flutter-mcp](https://github.com/mhmzdev/figma-flutter-mcp) — An MCP server that provides the coding agents Figma's design token to write Flutter code. ☆`178`
- [storybookjs/mcp](https://github.com/storybookjs/mcp) —  ☆`152`
- [delano/postman-mcp-server](https://github.com/delano/postman-mcp-server) — An MCP server that provides access to Postman. ☆`143`
- [DefangLabs/defang](https://github.com/DefangLabs/defang) — Defang CLI and sample projects. Develop Once, Deploy Anywhere. Take your app from Docker Compose to a secure and scalable deployment on your favorite cloud in minutes. ☆`144`
- [khromov/svelte-llm-mcp](https://github.com/khromov/svelte-llm-mcp) — Svelte developer documentation as an MCP and in llms.txt format ☆`158`
- [langfuse/mcp-server-langfuse](https://github.com/langfuse/mcp-server-langfuse) — Model Context Protocol (MCP) Server for Langfuse Prompt Management. This server allows you to access and manage your Langfuse prompts through the Model Context Protocol. ☆`150`
- [postmanlabs/postman-mcp-server](https://github.com/postmanlabs/postman-mcp-server) — Connect your AI to your APIs on Postman ☆`126`
- [pskill9/website-downloader](https://github.com/pskill9/website-downloader) — MCP server to download entire websites ☆`146`
- [yangkyeongmo/mcp-server-apache-airflow](https://github.com/yangkyeongmo/mcp-server-apache-airflow) —  ☆`120`
- [githejie/mcp-server-calculator](https://github.com/githejie/mcp-server-calculator) — A Model Context Protocol server for calculating. ☆`138`
- [docker/hub-mcp](https://github.com/docker/hub-mcp) — Docker Hub MCP Server ☆`103`
- [IDEA-Research/DINO-X-MCP](https://github.com/IDEA-Research/DINO-X-MCP) — Official DINO-X Model Context Protocol (MCP) server that empowers LLMs with real-world visual perception through image object detection, localization, and captioning APIs. ☆`108`
- [cycodehq/cycode-cli](https://github.com/cycodehq/cycode-cli) — Boost security in your dev lifecycle via SAST, SCA, Secrets & IaC scanning ☆`97`
- [aashari/mcp-server-atlassian-bitbucket](https://github.com/aashari/mcp-server-atlassian-bitbucket) — Node.js/TypeScript MCP server for Atlassian Bitbucket. Enables AI systems (LLMs) to interact with workspaces, repositories, and pull requests via tools (list, get, comment, search). Connects AI directly to version control workflows through the standard MCP interface. ☆`96`
- [janreges/ai-distiller](https://github.com/janreges/ai-distiller) — AI Distiller is ultra‑fast, open‑source tool for intelligently extracting only the essential public APIs, types, and structure from large codebases. Compresses 90–98% of code into AI‑friendly context, integrates via CLI or MCP, supports 12+ languages, and AI prompt workflows for cleaner, cost‑effective AI development. ☆`117`
- [sammcj/mcp-package-version](https://github.com/sammcj/mcp-package-version) — An MCP server that provides LLMs with the latest stable package versions when coding ☆`118`
- [st3v3nmw/sourcerer-mcp](https://github.com/st3v3nmw/sourcerer-mcp) — MCP for semantic code search & navigation that reduces token waste ☆`100`
- [webflow/mcp-server](https://github.com/webflow/mcp-server) — Model Context Protocol (MCP) server for the Webflow Data API. ☆`93`
- [augmnt/augments-mcp-server](https://github.com/augmnt/augments-mcp-server) — Comprehensive MCP server providing real-time framework documentation access for Claude Code with intelligent caching, multi-source integration, and context-aware assistance. ☆`92`
- [cameroncooke/reloaderoo](https://github.com/cameroncooke/reloaderoo) — Powerful MCP debugging proxy and CLI inspection tool. ☆`108`
- [johannesbrandenburger/typst-mcp](https://github.com/johannesbrandenburger/typst-mcp) — Typst MCP Server is an MCP (Model Context Protocol) implementation that helps AI models interact with Typst, a markup-based typesetting system. The server provides tools for converting between LaTeX and Typst, validating Typst syntax, and generating images from Typst code. ☆`91`
- [tanaikech/ToolsForMCPServer](https://github.com/tanaikech/ToolsForMCPServer) — The Gemini CLI confirmed that the MCP server built with Google Apps Script (GAS), a low-code platform, offers immense possibilities. If you've created snippets for GAS, these could be revitalized and/or leveraged in new ways by using them as the MCP server. The Gemini CLI and other MCP clients will be useful in achieving this. ☆`83`
- [CircleCI-Public/mcp-server-circleci](https://github.com/CircleCI-Public/mcp-server-circleci) — A specialized server implementation for the Model Context Protocol (MCP) designed to integrate with CircleCI's development workflow. This project serves as a bridge between CircleCI's infrastructure and the Model Context Protocol, enabling enhanced AI-powered development experiences. ☆`75`
- [twilio-labs/mcp](https://github.com/twilio-labs/mcp) — Monorepo providing 1) OpenAPI to MCP Tool generator 2) Exposing all of Twilio's API as MCP Tools ☆`76`
- [marimo-team/codemirror-mcp](https://github.com/marimo-team/codemirror-mcp) — CodeMirror extension to hook up a Model Context Provider (MCP) ☆`79`
- [xzq-xu/jvm-mcp-server](https://github.com/xzq-xu/jvm-mcp-server) — This is an implementation project of a JVM-based MCP (Model Context Protocol) server. The project aims to provide a standardized MCP server implementation for the JVM platform, enabling AI models to better interact with the Java ecosystem. ☆`75`
- [mrjoshuak/godoc-mcp](https://github.com/mrjoshuak/godoc-mcp) — go doc mcp server ☆`95`
- [debugg-ai/debugg-ai-mcp](https://github.com/debugg-ai/debugg-ai-mcp) — Zero-Config, Fully AI-Managed End-to-End Testing for all code gen platforms. ☆`71`
- [zillow/auto-mobile](https://github.com/zillow/auto-mobile) — Mobile automation suite of tools including an MCP and libraries for test authoring & execution ☆`71`
- [abrinsmead/mindpilot-mcp](https://github.com/abrinsmead/mindpilot-mcp) — See through your agent's eyes. Visualize legacy code, architect new systems, understand everything. ☆`68`
- [ckanthony/gin-mcp](https://github.com/ckanthony/gin-mcp) — Enable MCP features for any Gin API with a line of code ☆`65`
- [ShenghaiWang/xcodebuild](https://github.com/ShenghaiWang/xcodebuild) — MCP tool for building Xcode iOS workspace/project and feeding back error to LLMs. ☆`78`
- [kadykov/mcp-openapi-schema-explorer](https://github.com/kadykov/mcp-openapi-schema-explorer) — MCP server providing token-efficient access to OpenAPI/Swagger specs via MCP Resources for client-side exploration. ☆`61`
- [wise-vision/ros2_mcp](https://github.com/wise-vision/ros2_mcp) — Advanced MCP Server ROS 2 bridging AI agents straight into robotics ☆`60`
- [lamemind/mcp-server-multiverse](https://github.com/lamemind/mcp-server-multiverse) — A middleware server that enables multiple isolated instances of the same MCP servers to coexist independently with unique namespaces and configurations. ☆`75`
- [ReAPI-com/mcp-openapi](https://github.com/ReAPI-com/mcp-openapi) — OpenAPI specification MCP server. ☆`75`
- [YuChenSSR/multi-ai-advisor-mcp](https://github.com/YuChenSSR/multi-ai-advisor-mcp) — council of models for decision ☆`72`
- [ai-1st/deepview-mcp](https://github.com/ai-1st/deepview-mcp) — DeepView MCP is a Model Context Protocol server that enables IDEs like Cursor and Windsurf to analyze large codebases using Gemini 2.5 Pro's extensive context window. ☆`67`
- [hloiseau/mcp-gopls](https://github.com/hloiseau/mcp-gopls) — Model Context Protocol (MCP) server for Go using gopls – LSP-powered analysis, tests, coverage, and tooling. ☆`53`
- [hostinger/api-mcp-server](https://github.com/hostinger/api-mcp-server) —  ☆`46`
- [stanislavlysenko0912/todoist-mcp-server](https://github.com/stanislavlysenko0912/todoist-mcp-server) — Full implementation of Todoist Rest API & support Todoist Sync API for MCP server ☆`49`
- [aashari/mcp-server-atlassian-jira](https://github.com/aashari/mcp-server-atlassian-jira) — Node.js/TypeScript MCP server for Atlassian Jira. Equips AI systems (LLMs) with tools to list/get projects, search/get issues (using JQL/ID), and view dev info (commits, PRs). Connects AI capabilities directly into Jira project management and issue tracking workflows. ☆`48`
- [stass/lldb-mcp](https://github.com/stass/lldb-mcp) — LLDB MCP server ☆`68`
- [baruchiro/paperless-mcp](https://github.com/baruchiro/paperless-mcp) — An MCP (Model Context Protocol) server for interacting with a Paperless-NGX API server. This server provides tools for managing documents, tags, correspondents, and document types in your Paperless-NGX instance. ☆`47`
- [aashari/mcp-server-atlassian-confluence](https://github.com/aashari/mcp-server-atlassian-confluence) — Node.js/TypeScript MCP server for Atlassian Confluence. Provides tools enabling AI systems (LLMs) to list/get spaces & pages (content formatted as Markdown) and search via CQL. Connects AI seamlessly to Confluence knowledge bases using the standard MCP interface. ☆`43`
- [oschina/mcp-gitee](https://github.com/oschina/mcp-gitee) — mcp-gitee is a Model Context Protocol (MCP) server implementation for Gitee. It provides a set of tools that interact with Gitee's API, allowing AI assistants to manage repository, issues, pull requests, etc. ☆`44`
- [buildkite/buildkite-mcp-server](https://github.com/buildkite/buildkite-mcp-server) — Official MCP Server for Buildkite. ☆`42`
- [yWorks/mcp-typescribe](https://github.com/yWorks/mcp-typescribe) — An MCP server implementation enabling LLMs to work with new APIs and frameworks ☆`45`
- [zaizaizhao/mcp-swagger-server](https://github.com/zaizaizhao/mcp-swagger-server) — Convert any OpenAPI/Swagger REST API to Model Context Protocol format for AI assistants ☆`44`
- [lpigeon/unitree-go2-mcp-server](https://github.com/lpigeon/unitree-go2-mcp-server) — The Unitree Go2 MCP Server is a server built on the MCP that enables users to control the Unitree Go2 robot using natural language commands interpreted by a LLM. ☆`61`
- [crawlbase/crawlbase-mcp](https://github.com/crawlbase/crawlbase-mcp) — Crawlbase MCP Server connects AI agents and LLMs with real-time web data. It powers Claude, Cursor, and Windsurf integrations with battle-tested web scraping, JavaScript rendering, and anti-bot protection enabling structured, live data inside your AI workflows. ☆`40`
- [zenml-io/mcp-zenml](https://github.com/zenml-io/mcp-zenml) — MCP server to connect an MCP client (Cursor, Claude Desktop etc) with your ZenML MLOps and LLMOps pipelines ☆`39`
- [srijanshukla18/xray](https://github.com/srijanshukla18/xray) — XRAY MCP provides progressive code intelligence and navigation capabilities for AI assistants through structural code analysis using ast-grep ☆`39`
- [pansila/mcp_server_gdb](https://github.com/pansila/mcp_server_gdb) — MCP Server to expose the GDB debugging capabilities ☆`53`
- [PromptExecution/just-mcp](https://github.com/PromptExecution/just-mcp) — mcp server for just ☆`38`
- [Rootly-AI-Labs/Rootly-MCP-server](https://github.com/Rootly-AI-Labs/Rootly-MCP-server) — Rootly MCP server ☆`36`
- [freema/mcp-design-system-extractor](https://github.com/freema/mcp-design-system-extractor) — MCP (Model Context Protocol) server that enables AI assistants to interact with Storybook design systems. Extract component HTML, analyze styles, and help with design system adoption and refactoring. ☆`36`
- [jsdelivr/globalping-mcp-server](https://github.com/jsdelivr/globalping-mcp-server) — Remote MCP server that gives LLMs access to run network commands ☆`36`
- [QAInsights/jmeter-mcp-server](https://github.com/QAInsights/jmeter-mcp-server) — JMeter Meets AI Workflows: Introducing the JMeter MCP Server! ☆`53`
- [CodeLogicIncEngineering/codelogic-mcp-server](https://github.com/CodeLogicIncEngineering/codelogic-mcp-server) — An MCP Server to utilize Codelogic's rich software dependency data in your AI programming assistant. ☆`33`
- [azer/react-analyzer-mcp](https://github.com/azer/react-analyzer-mcp) — MCP server for analyzing & generating docs for React code locally ☆`54`
- [mrexodia/user-feedback-mcp](https://github.com/mrexodia/user-feedback-mcp) — Simple MCP Server to enable a human-in-the-loop workflow in tools like Cline and Cursor. ☆`52`
- [Artmann/package-registry-mcp](https://github.com/Artmann/package-registry-mcp) — MCP server for searching and getting up-to-date information about NPM, Cargo, PyPi, and NuGet packages. ☆`32`
- [georgeantonopoulos/Basecamp-MCP-Server](https://github.com/georgeantonopoulos/Basecamp-MCP-Server) — An MCP Server that interacts with the Basecamp 3+ API ☆`46`
- [Yuchen20/Memory-Plus](https://github.com/Yuchen20/Memory-Plus) — A lightweight, local RAG memory store for MCP agents. Easily record, retrieve, update, delete, and visualize... ☆`50`
- [bharathvaj-ganesan/whois-mcp](https://github.com/bharathvaj-ganesan/whois-mcp) — MCP Server for whois lookups. ☆`48`
- [zazencodes/random-number-mcp](https://github.com/zazencodes/random-number-mcp) — Production-ready MCP server that provides LLMs with essential random generation abilities, built entirely on Python's standard library. ☆`45`
- [video-db/agent-toolkit](https://github.com/video-db/agent-toolkit) — An open-source agent toolkit that auto-syncs SDK versions, docs, and examples—built for seamless integration with LLMs, and AI agents ( MCP compatible). ☆`44`
- [Bigsy/maven-mcp-server](https://github.com/Bigsy/maven-mcp-server) — An MCP (Model Context Protocol) server that provides tools for checking Maven dependency versions. ☆`29`
- [Tommertom/awesome-ionic-mcp](https://github.com/Tommertom/awesome-ionic-mcp) — An Awesome MCP Server to help building mobile apps in React/Vue/Angular/VanillaJS using Capacitor and Ionic ☆`30`
- [laurynas-biveinis/elisp-dev-mcp](https://github.com/laurynas-biveinis/elisp-dev-mcp) — Dev tools in Emacs MCP for agentic Elisp development with LLMs ☆`30`
- [veelenga/claude-mermaid](https://github.com/veelenga/claude-mermaid) — MCP Server to previewing mermaid diagrams ☆`29`
- [bitrise-io/bitrise-mcp](https://github.com/bitrise-io/bitrise-mcp) — MCP Server for the Bitrise API, enabling app management, build operations, artifact management and more. ☆`26`
- [linw1995/nvim-mcp](https://github.com/linw1995/nvim-mcp) — A Model Context Protocol (MCP) server that provides seamless integration with Neovim instances, enabling AI assistants to interact with your editor through connections and access diagnostic information via structured resources. ☆`27`
- [zacharypodbela/django-rest-framework-mcp](https://github.com/zacharypodbela/django-rest-framework-mcp) — Quickly build MCP servers that expose your Django Rest Framework APIs as tools for LLMs and agentic applications to work with ☆`26`
- [IlyaGulya/gradle-mcp-server](https://github.com/IlyaGulya/gradle-mcp-server) — A Model Context Protocol (MCP) server to enable AI tools to interact with Gradle projects programmatically. ☆`40`
- [shanejonas/openrpc-mcp-server](https://github.com/shanejonas/openrpc-mcp-server) — A Model Context Protocol (MCP) server that provides JSON-RPC functionality through OpenRPC. ☆`42`
- [vezlo/src-to-kb](https://github.com/vezlo/src-to-kb) — Convert source code to LLM ready knowledge base ☆`24`
- [themeselection/flyonui-mcp](https://github.com/themeselection/flyonui-mcp) — MCP server for flyonUI ☆`23`
- [JoshuaRileyDev/simulator-mcp-server](https://github.com/JoshuaRileyDev/simulator-mcp-server) —  ☆`47`
- [IvanAmador/vercel-ai-docs-mcp](https://github.com/IvanAmador/vercel-ai-docs-mcp) — A Model Context Protocol (MCP) server that provides AI-powered search and querying capabilities for the Vercel AI SDK documentation. This project enables developers to ask questions about the Vercel AI SDK and receive accurate, contextualized responses based on the official documentation. ☆`42`
- [OctoMind-dev/octomind-mcp](https://github.com/OctoMind-dev/octomind-mcp) — An MCP server for octomind tools, resources and prompts ☆`21`
- [hechtcarmel/jetbrains-index-mcp-plugin](https://github.com/hechtcarmel/jetbrains-index-mcp-plugin) — A Jetbrains IDE IntelliJ plugin aimed to provide coding agents the ability to leverage intelliJ's indexing of the codebase ☆`21`
- [cqfn/aibolit-mcp-server](https://github.com/cqfn/aibolit-mcp-server) — MCP Server for Aibolit Java Static Analyzer: Helping Your AI Agent Identify Hotspots for Refactoring ☆`21`
- [ukkit/memcord](https://github.com/ukkit/memcord) — AI Memory Management for Claude Desktop. Save, search & organize chat history with intelligent summarization. MCP server. ☆`21`
- [mailgun/mailgun-mcp-server](https://github.com/mailgun/mailgun-mcp-server) — Implementation of Model Context Protocol server for Mailgun APIs ☆`39`
- [themesberg/flowbite-mcp](https://github.com/themesberg/flowbite-mcp) — Convert Figma design to code with the official Flowbite MCP server ☆`21`
- [reflagcom/javascript](https://github.com/reflagcom/javascript) — JS/TS SDKs for Bucket.co ☆`19`
- [Narasimhaponnada/mermaid-mcp](https://github.com/Narasimhaponnada/mermaid-mcp) —  ☆`20`
- [Hypersequent/qasphere-mcp](https://github.com/Hypersequent/qasphere-mcp) — MCP Server for QA Sphere TMS ☆`18`
- [sshaaf/keycloak-mcp-server](https://github.com/sshaaf/keycloak-mcp-server) — An MCP server for Keycloak, designed to work with Keycloak for identity and access management, covering, Users, Realms, Clients, Roles, Groups, IDPs, Authentication. Searching keycloak discourse, Native builds available. ☆`19`
- [yikakia/godoc-mcp-server](https://github.com/yikakia/godoc-mcp-server) — A mcp server provide infomation from pkg.go.dev. For all golang programmers ☆`34`
- [hungthai1401/bruno-mcp](https://github.com/hungthai1401/bruno-mcp) — MCP Server for running Bruno Collections ☆`32`
- [V0v1kkk/DotNetMetadataMcpServer](https://github.com/V0v1kkk/DotNetMetadataMcpServer) — A Model Context Protocol (MCP) server that provides detailed type information from .NET projects for AI coding agents. ☆`17`
- [sequa-ai/sequa-mcp](https://github.com/sequa-ai/sequa-mcp) —  ☆`16`
- [Pratyay/mac-monitor-mcp](https://github.com/Pratyay/mac-monitor-mcp) —  ☆`16`
- [vasayxtx/mcp-prompt-engine](https://github.com/vasayxtx/mcp-prompt-engine) — MCP Prompt Engine ☆`16`
- [OvertliDS/mcp-searxng-enhanced](https://github.com/OvertliDS/mcp-searxng-enhanced) — Enhanced MCP server for SearXNG: category-aware web-search, web-scraping, and date/time retrieval. ☆`28`
- [hijaz/postmancer](https://github.com/hijaz/postmancer) — An experimental MCP server Rest Client intended to be a replacement of tools postman & insomnia ☆`29`
- [screenshotone/mcp](https://github.com/screenshotone/mcp) — A simple implementation of an MCP server for the ScreenshotOne API ☆`32`
- [Yutarop/ros-mcp](https://github.com/Yutarop/ros-mcp) — MCP server for ROS to control robots via topics, services, and actions. ☆`28`
- [andybrandt/mcp-simple-timeserver](https://github.com/andybrandt/mcp-simple-timeserver) — Simple solution to give Claude ability to check current time via MCP ☆`25`
- [XixianLiang/HarmonyOS-mcp-server](https://github.com/XixianLiang/HarmonyOS-mcp-server) — MCP server for manipulating HarmonyOS next devices. ☆`26`
- [j4c0bs/mcp-server-sql-analyzer](https://github.com/j4c0bs/mcp-server-sql-analyzer) — MCP server for SQL static analysis. ☆`26`
- [rahulthedevil/Jira-Context-MCP](https://github.com/rahulthedevil/Jira-Context-MCP) — MCP server to provide Jira Tickets information to AI coding agents like Cursor ☆`24`
- [endorhq/cli](https://github.com/endorhq/cli) — Endor provides instant, private, sandboxed environments for your favorite services anywhere Node is available. Run MariaDB, PostgreSQL and many more servers securely and in just a few seconds. Perfect for AI agents and humans in a hurry. ☆`25`
- [api7/apisix-mcp](https://github.com/api7/apisix-mcp) — APISIX Model Context Protocol (MCP) server is used to bridge large language models (LLMs) with the APISIX Admin API. ☆`29`
- [supadata-ai/mcp](https://github.com/supadata-ai/mcp) — Official Supadata MCP Server - Adds powerful video & web scraping to Cursor, Claude and any other LLM clients. ☆`24`
- [Arize-ai/text-to-graphql-mcp](https://github.com/Arize-ai/text-to-graphql-mcp) —  ☆`23`
- [InhiblabCore/mcp-image-compression](https://github.com/InhiblabCore/mcp-image-compression) — A high-performance image compression microservice based on MCP (Modal Context Protocol) ☆`28`
- [PV-Bhat/gemsuite-mcp](https://github.com/PV-Bhat/gemsuite-mcp) — Professional Gemini API integration for Claude and all MCP-compatible hosts with intelligent model selection and advanced file handling | Smithery.ai verified ☆`25`
- [nick1udwig/ws-mcp](https://github.com/nick1udwig/ws-mcp) —  ☆`19`
- [Jktfe/serveMyAPI](https://github.com/Jktfe/serveMyAPI) —  ☆`23`
- [Ryan0204/github-repo-mcp](https://github.com/Ryan0204/github-repo-mcp) — Model Context Protocol server for Github Repo // Reading Github Repo ☆`22`
- [higress-group/higress-ops-mcp-server](https://github.com/higress-group/higress-ops-mcp-server) — A Model Context Protocol (MCP) server implementation that enables comprehensive configuration and management of Higress. ☆`22`
- [upnorthmedia/ScreenshotMCP](https://github.com/upnorthmedia/ScreenshotMCP) — A Model Context Protocol MCP server for capturing website screenshots with full page, element, and device size features. ☆`17`
- [ZeparHyfar/mcp-datetime](https://github.com/ZeparHyfar/mcp-datetime) — A MCP server for datetime formatting and file name generation. ☆`25`
- [heilgar/shadcn-ui-mcp-server](https://github.com/heilgar/shadcn-ui-mcp-server) —  ☆`20`
- [fotoetienne/gqai](https://github.com/fotoetienne/gqai) — Turn any GraphQL endpoint into a set of MCP tools ☆`21`
- [QAInsights/k6-mcp-server](https://github.com/QAInsights/k6-mcp-server) — k6 MCP server ☆`20`
- [thirdweb-dev/ai](https://github.com/thirdweb-dev/ai) —  ☆`18`
- [tgeselle/bugsnag-mcp](https://github.com/tgeselle/bugsnag-mcp) — A Model Context Protocol (MCP) server for interacting with Bugsnag. This server allows LLM tools like Cursor and Claude to investigate and resolve issues in Bugsnag. ☆`18`
- [JordanDalton/DoorDash-MCP-Server](https://github.com/JordanDalton/DoorDash-MCP-Server) —  ☆`18`
- [Excoriate/mcp-terragrunt-docs](https://github.com/Excoriate/mcp-terragrunt-docs) — Deno/TypeScript MCP Server providing context related to Terragrunt documentation. ☆`17`
- [johannesPettersson80/codesys-mcp-toolkit](https://github.com/johannesPettersson80/codesys-mcp-toolkit) — Model Context Protocol server for CODESYS automation platform ☆`16`
- [axliupore/mcp-code-runner](https://github.com/axliupore/mcp-code-runner) —  ☆`16`
### Embedded & IoT

- [tevonsb/homeassistant-mcp](https://github.com/tevonsb/homeassistant-mcp) — A MCP server for Home Assistant ☆`502`
- [Extelligence-ai/bagel](https://github.com/Extelligence-ai/bagel) — Chat with your robotics, drone, and IoT data — ChatGPT for the physical world. ☆`369`
- [horw/esp-mcp](https://github.com/horw/esp-mcp) — Centralize ESP32 related commands and simplify getting started with seamless, LLM-driven interaction and help. ☆`118`
- [thingsboard/thingsboard-mcp](https://github.com/thingsboard/thingsboard-mcp) —  ☆`81`
- [kukapay/opcua-mcp](https://github.com/kukapay/opcua-mcp) — An MCP server that connects to OPC UA-enabled industrial systems. ☆`22`
- [yoelbassin/gr-mcp](https://github.com/yoelbassin/gr-mcp) — MCP server for GNU Radio ☆`24`
- [kukapay/modbus-mcp](https://github.com/kukapay/modbus-mcp) — An MCP server that standardizes and contextualizes industrial Modbus data. ☆`18`
### File Systems & Storage

- [mark3labs/mcp-filesystem-server](https://github.com/mark3labs/mcp-filesystem-server) — Go server implementing Model Context Protocol (MCP) for filesystem operations. ☆`568`
- [mapbox/mcp-server](https://github.com/mapbox/mcp-server) — Mapbox Model Context Protocol (MCP) server ☆`296`
- [cyberchitta/llm-context.py](https://github.com/cyberchitta/llm-context.py) — Share code with LLMs via Model Context Protocol or clipboard. Rule-based customization enables easy switching between different tasks (like code review and documentation). Includes smart code outlining. ☆`288`
- [mamertofabian/mcp-everything-search](https://github.com/mamertofabian/mcp-everything-search) —  ☆`280`
- [isaacphi/mcp-gdrive](https://github.com/isaacphi/mcp-gdrive) — Model Context Protocol (MCP) Server for reading from Google Drive and editing Google Sheets ☆`246`
- [8b-is/smart-tree](https://github.com/8b-is/smart-tree) — Smart Tree: not just a tree, a philosophy. A context-aware, AI-crafted replacement for 20+ tools with MEM8 quantum compression, semantic search, AST-smart editing, and partnership memory. Crafted with care by human + AI—accept no knock-offs. ☆`197`
- [efforthye/fast-filesystem-mcp](https://github.com/efforthye/fast-filesystem-mcp) — A high-performance Model Context Protocol (MCP) server that provides secure filesystem access for Claude and other AI assistants. ☆`34`
- [Tencent/cos-mcp](https://github.com/Tencent/cos-mcp) — Tencent Cloud COS MCP Server based on MCP protocol for quick integration with cloud storage and data processing ☆`18`
- [Xuanwo/mcp-server-opendal](https://github.com/Xuanwo/mcp-server-opendal) — Model Context Protocol Server for Apache OpenDAL ☆`33`
- [exoticknight/mcp-file-merger](https://github.com/exoticknight/mcp-file-merger) — MCP server for merging multiple files into one ☆`23`
- [jeannier/homebrew-mcp](https://github.com/jeannier/homebrew-mcp) — Homebrew MCP : Comprehensive brew support for installing, upgrading, searching, and maintaining macOS packages. ☆`20`
### Finance

- [stripe/ai](https://github.com/stripe/ai) — One-stop shop for building AI-powered products and businesses with Stripe. ☆`1,170`
- [financial-datasets/mcp-server](https://github.com/financial-datasets/mcp-server) — An MCP server for interacting with the Financial Datasets stock market API. ☆`723`
- [mcpdotdirect/evm-mcp-server](https://github.com/mcpdotdirect/evm-mcp-server) — MCP server that provides LLMs with tools for interacting with EVM networks ☆`349`
- [base/base-mcp](https://github.com/base/base-mcp) — A Model Context Protocol (MCP) server that provides onchain tools for LLMs, allowing them to interact with the Base network and Coinbase API. ☆`331`
- [ferdousbhai/investor-agent](https://github.com/ferdousbhai/investor-agent) — A Model Context Protocol server for building an investor agent ☆`296`
- [massive-com/mcp_massive](https://github.com/massive-com/mcp_massive) — An MCP server for Massive.com Financial Market Data ☆`231`
- [paypal/agent-toolkit](https://github.com/paypal/agent-toolkit) — PayPal Agent ☆`171`
- [XeroAPI/xero-mcp-server](https://github.com/XeroAPI/xero-mcp-server) — An MCP server that integrates with the MCP protocol. https://modelcontextprotocol.io/introduction ☆`162`
- [armorwallet/armor-crypto-mcp](https://github.com/armorwallet/armor-crypto-mcp) — The MCP server for interacting with Blockchain, Swaps, Strategic Planning and more. ☆`183`
- [aaronjmars/web3-research-mcp](https://github.com/aaronjmars/web3-research-mcp) — Deep Research for crypto - free & fully local ☆`147`
- [traceloop/opentelemetry-mcp-server](https://github.com/traceloop/opentelemetry-mcp-server) — Unified MCP server for querying OpenTelemetry traces across multiple backends (Jaeger, Tempo, Traceloop, etc.), enabling AI agents to analyze distributed traces for automated debugging and observability. ☆`146`
- [ariadng/metatrader-mcp-server](https://github.com/ariadng/metatrader-mcp-server) — Model Context Protocol (MCP) to enable AI LLMs to trade using MetaTrader platform ☆`136`
- [kukapay/crypto-indicators-mcp](https://github.com/kukapay/crypto-indicators-mcp) — An MCP server providing a range of cryptocurrency technical analysis indicators and strategies. ☆`102`
- [doggybee/mcp-server-ccxt](https://github.com/doggybee/mcp-server-ccxt) — High-performance CCXT MCP server for cryptocurrency exchange integration ☆`123`
- [kukapay/freqtrade-mcp](https://github.com/kukapay/freqtrade-mcp) — An MCP server that integrates with the Freqtrade cryptocurrency trading bot. ☆`100`
- [berlinbra/alpha-vantage-mcp](https://github.com/berlinbra/alpha-vantage-mcp) — MCP Server for Alpha Advantage API ☆`86`
- [square/square-mcp-server](https://github.com/square/square-mcp-server) — A Model Context Protocol (MCP) server for square ☆`90`
- [narumiruna/yfinance-mcp](https://github.com/narumiruna/yfinance-mcp) —  ☆`78`
- [Bankless/onchain-mcp](https://github.com/Bankless/onchain-mcp) — Bringing the bankless onchain API to MCP ☆`76`
- [alchemyplatform/alchemy-mcp-server](https://github.com/alchemyplatform/alchemy-mcp-server) — Alchemy's official MCP Server. Allow AI agents to interact with Alchemy's blockchain APIs. ☆`72`
- [QuantGeekDev/coincap-mcp](https://github.com/QuantGeekDev/coincap-mcp) — A coincap mcp server to access crypto data from coincap API ☆`90`
- [OctagonAI/octagon-mcp-server](https://github.com/OctagonAI/octagon-mcp-server) — A free MCP server to analyze and extract insights from public filings, earnings transcripts, financial metrics, stock market data, private market transactions, and deep web-based research within Claude Desktop and other popular MCP clients. ☆`86`
- [kukapay/cryptopanic-mcp-server](https://github.com/kukapay/cryptopanic-mcp-server) — Provide latest cryptocurrency news to AI agents. ☆`62`
- [QuantConnect/mcp-server](https://github.com/QuantConnect/mcp-server) — Official Python MCP server for local interactions with the QuantConnect API ☆`62`
- [heurist-network/heurist-mesh-mcp-server](https://github.com/heurist-network/heurist-mesh-mcp-server) —  ☆`63`
- [AbdelStark/bitcoin-mcp](https://github.com/AbdelStark/bitcoin-mcp) — Bitcoin & Lightning Network MCP Server. ☆`67`
- [ferdousbhai/tasty-agent](https://github.com/ferdousbhai/tasty-agent) — Let Claude manage your tastytrade portfolio. ☆`48`
- [twelvedata/mcp](https://github.com/twelvedata/mcp) — Twelve Data MCP (Model Context Protocol) Server provides seamless, real-time access to financial market data via WebSocket, enabling reliable streaming of price quotes, market metrics, and events directly into your applications. ☆`48`
- [HuggingAGI/mcp-baostock-server](https://github.com/HuggingAGI/mcp-baostock-server) —  ☆`64`
- [trade-it-inc/trade-it-mcp](https://github.com/trade-it-inc/trade-it-mcp) — Guide to connect to Trade It's MCP server and trade stocks and crypto ☆`41`
- [minhyeoky/mcp-server-ledger](https://github.com/minhyeoky/mcp-server-ledger) — A Model Context Protocol server for interacting with Ledger CLI, a powerful double-entry accounting system. This server enables Large Language Models to query and analyze financial data through a standardized interface, making it easy for AI assistants to help with financial reporting, budget analysis, and accounting tasks. ☆`41`
- [coinpaprika/dexpaprika-mcp](https://github.com/coinpaprika/dexpaprika-mcp) — DexPaprika MCP server allows access real-time and historical data on crypto tokens, DEX trading activity, and liquidity across multiple blockchains. It enables natural language queries for exploring market trends, token performance, and DeFi analytics through a standardized interface. ☆`35`
- [kukapay/crypto-feargreed-mcp](https://github.com/kukapay/crypto-feargreed-mcp) — Providing real-time and historical Crypto Fear & Greed Index data ☆`50`
- [zlinzzzz/finData-mcp-server](https://github.com/zlinzzzz/finData-mcp-server) — FinData enables your AI agents retrieve financial data from different providers like Tushare, Wind, and DataYes. ☆`50`
- [kukapay/whale-tracker-mcp](https://github.com/kukapay/whale-tracker-mcp) — A mcp server for tracking cryptocurrency whale transactions. ☆`48`
- [akutishevsky/lunchmoney-mcp](https://github.com/akutishevsky/lunchmoney-mcp) — A Model Context Protocol (MCP) server implementation for LunchMoney, providing programmatic access to personal finance management through LunchMoney's API. ☆`29`
- [kukapay/crypto-sentiment-mcp](https://github.com/kukapay/crypto-sentiment-mcp) — An MCP server that delivers cryptocurrency sentiment analysis to AI agents. ☆`45`
- [iiAtlas/hledger-mcp](https://github.com/iiAtlas/hledger-mcp) — A local MCP server for interacting with the HLedger cli ☆`28`
- [getAlby/mcp](https://github.com/getAlby/mcp) — Connect a bitcoin lightning wallet to your LLM using Nostr Wallet Connect and Model Context Protocol ☆`40`
- [anjor/coinmarket-mcp-server](https://github.com/anjor/coinmarket-mcp-server) —  ☆`44`
- [wowinter13/solscan-mcp](https://github.com/wowinter13/solscan-mcp) — An MCP server for querying Solana transactions using natural language with Solscan API ☆`37`
- [JamesANZ/prediction-market-mcp](https://github.com/JamesANZ/prediction-market-mcp) — A simple MCP server that grabs prediction market data from polymarket, PredictIt, & Kalshi. ☆`20`
- [openMF/mcp-mifosx](https://github.com/openMF/mcp-mifosx) — Model Context Protocol - MCP for Mifos X ☆`18`
- [laukikk/alpaca-mcp](https://github.com/laukikk/alpaca-mcp) — MCP for the Alpaca trading API to manage stock and crypto portfolios, place trades, and access market data ☆`33`
- [token-metrics/mcp](https://github.com/token-metrics/mcp) — The Token Metrics Model Context Protocol (MCP) server provides comprehensive cryptocurrency data, analytics, and insights through function calling. This server enables AI assistants and agents to access Token Metrics' powerful API for real-time crypto market data, trading signals, price predictions, and advanced analytics. ☆`18`
- [kukapay/uniswap-trader-mcp](https://github.com/kukapay/uniswap-trader-mcp) — An MCP server for AI agents to automate token swaps on Uniswap DEX across multiple blockchains. ☆`34`
- [kukapay/dune-analytics-mcp](https://github.com/kukapay/dune-analytics-mcp) — A mcp server that bridges Dune Analytics data to AI agents. ☆`33`
- [SaintDoresh/YFinance-Trader-MCP-ClaudeDesktop](https://github.com/SaintDoresh/YFinance-Trader-MCP-ClaudeDesktop) — An MCP (Model Context Protocol) tool that provides stock market data and trading capabilities using the yfinance library, specifically adapted for Claude Desktop. ☆`28`
- [pwh-pwh/coin-mcp-server](https://github.com/pwh-pwh/coin-mcp-server) — use Bitget’s API to get cryptocurrency info ☆`28`
- [ramp-public/ramp_mcp](https://github.com/ramp-public/ramp_mcp) — ramp_mcp ☆`27`
- [kukapay/hyperliquid-info-mcp](https://github.com/kukapay/hyperliquid-info-mcp) — An MCP server that provides real-time data and insights from the Hyperliquid perp DEX for use in bots, dashboards, and analytics. ☆`25`
- [ferdousbhai/wsb-analyst-mcp](https://github.com/ferdousbhai/wsb-analyst-mcp) — MCP server for analyzing WallStreetBets ☆`19`
- [kukapay/jupiter-mcp](https://github.com/kukapay/jupiter-mcp) — An MCP server for executing token swaps on the Solana blockchain using Jupiter's new Ultra API. ☆`22`
- [Codex-Data/codex-mcp](https://github.com/Codex-Data/codex-mcp) — A Model Context Protocol server for the Codex API ☆`20`
- [kukapay/token-minter-mcp](https://github.com/kukapay/token-minter-mcp) — An MCP server providing tools for AI agents to mint ERC-20 tokens across multiple blockchains. ☆`17`
- [SaintDoresh/Crypto-Trader-MCP-ClaudeDesktop](https://github.com/SaintDoresh/Crypto-Trader-MCP-ClaudeDesktop) — An MCP (Model Context Protocol) tool that provides cryptocurrency market data using the CoinGecko API, specifically designed for Claude Desktop. ☆`17`
- [janswist/mcp-dexscreener](https://github.com/janswist/mcp-dexscreener) — Dexscreener API's MCP server - let your AI agent check any on-chain price using Dexscreener's free and open API ☆`16`
### Gaming

- [Coding-Solo/godot-mcp](https://github.com/Coding-Solo/godot-mcp) — MCP server for interfacing with Godot game engine. Provides tools for launching the editor, running projects, and capturing debug output. ☆`1,255`
- [CoderGamester/mcp-unity](https://github.com/CoderGamester/mcp-unity) — Model Context Protocol (MCP) plugin to connect with Unity Editor — designed for OpenAI, Gemini, Claude, Deepseek and Grok interoperability ☆`1,160`
- [IvanMurzak/Unity-MCP](https://github.com/IvanMurzak/Unity-MCP) — AI-powered bridge connecting LLMs and advanced AI agents to the Unity Editor via the Model Context Protocol (MCP). Chat with AI to generate code, debug errors, and automate game development tasks directly within your project. ☆`653`
- [codemaestroai/advanced-unity-mcp](https://github.com/codemaestroai/advanced-unity-mcp) — Public repository for Advanced Unity MCP by Code Maestro (www.code-maestro.com). ☆`73`
- [pab1it0/chess-mcp](https://github.com/pab1it0/chess-mcp) — A Model Context Protocol server for Chess.com's Published Data API. This provides access to Chess.com player data, game records, and other public information through standardized MCP interfaces, allowing AI assistants to search and analyze chess information. ☆`57`
- [rishijatia/fantasy-pl-mcp](https://github.com/rishijatia/fantasy-pl-mcp) — Fantasy Premier League MCP Server ☆`67`
- [opgginc/opgg-mcp](https://github.com/opgginc/opgg-mcp) —  ☆`53`
- [kkjdaniel/bgg-mcp](https://github.com/kkjdaniel/bgg-mcp) — BGG MCP provides access to BoardGameGeek and a variety of board game related data through the Model Context Protocol. Enabling retrieval and filtering of board game data, user collections, and profiles. ☆`23`
- [jiayao/mcp-chess](https://github.com/jiayao/mcp-chess) — MCP server for playing chess against AI ☆`17`
### Healthcare & Bioinformatics

- [genomoncology/biomcp](https://github.com/genomoncology/biomcp) — BioMCP: Biomedical Model Context Protocol ☆`378`
- [the-momentum/apple-health-mcp-server](https://github.com/the-momentum/apple-health-mcp-server) — MCP server for querying Apple Health data with natural language using DuckDB under the hood. ☆`88`
- [wso2/fhir-mcp-server](https://github.com/wso2/fhir-mcp-server) — FHIR MCP Server – helping you expose any FHIR Server or API as a MCP Server. ☆`68`
- [JamesANZ/medical-mcp](https://github.com/JamesANZ/medical-mcp) — An MCP server that provides comprehensive medical information by querying multiple authoritative medical APIs including FDA, WHO, PubMed, Google Scholar, and RxNorm ☆`48`
- [the-momentum/fhir-mcp-server](https://github.com/the-momentum/fhir-mcp-server) — FHIR MCP Server for handling medical data standard. ☆`46`
- [longevity-genie/biothings-mcp](https://github.com/longevity-genie/biothings-mcp) — MCP (Model Context Protocol) server for biothings ☆`27`
- [OHNLP/omop_mcp](https://github.com/OHNLP/omop_mcp) — Model Context Protocol (MCP) server for mapping clinical terminology to Observational Medical Outcomes Partnership (OMOP) concepts using Large Language Models ☆`23`
- [longevity-genie/gget-mcp](https://github.com/longevity-genie/gget-mcp) — Bioinformatic MCP server that wraps the most useful functions of the gget library ☆`21`
- [tomekkorbak/oura-mcp-server](https://github.com/tomekkorbak/oura-mcp-server) — MCP server for Oura API integration ☆`36`
### Knowledge Management

- [MarkusPfundstein/mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) — MCP server that interacts with Obsidian via the Obsidian rest API community plugin ☆`2,579`
- [smithery-ai/mcp-obsidian](https://github.com/smithery-ai/mcp-obsidian) — A connector for Claude Desktop to read and search an Obsidian vault. ☆`1,243`
- [chatmcp/mcp-server-chatsum](https://github.com/chatmcp/mcp-server-chatsum) — Query and Summarize your chat messages. ☆`1,024`
- [apecloud/ApeRAG](https://github.com/apecloud/ApeRAG) — ApeRAG: Production-ready GraphRAG with multi-modal indexing, AI agents, MCP support, and scalable K8s deployment ☆`990`
- [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) — Hindsight: Agent Memory That Works Like Human Memory ☆`813`
- [mem0ai/mem0-mcp](https://github.com/mem0ai/mem0-mcp) —  ☆`544`
- [graphlit/graphlit-mcp-server](https://github.com/graphlit/graphlit-mcp-server) — Model Context Protocol (MCP) Server for Graphlit Platform ☆`367`
- [CheMiguel23/MemoryMesh](https://github.com/CheMiguel23/MemoryMesh) — A knowledge graph server that uses the Model Context Protocol (MCP) to provide structured memory persistence for AI models. v0.2.8 ☆`323`
- [RafalWilinski/mcp-apple-notes](https://github.com/RafalWilinski/mcp-apple-notes) — Talk with your notes in Claude. RAG over your Apple Notes using Model Context Protocol. ☆`322`
- [bitbonsai/mcp-obsidian](https://github.com/bitbonsai/mcp-obsidian) — A lightweight Model Context Protocol (MCP) server for safe Obsidian vault access ☆`265`
- [hannesrudolph/mcp-ragdocs](https://github.com/hannesrudolph/mcp-ragdocs) — An MCP server implementation that provides tools for retrieving and processing documentation through vector search, enabling AI assistants to augment their responses with relevant documentation context. ☆`244`
- [lostintangent/gistpad-mcp](https://github.com/lostintangent/gistpad-mcp) — An MCP server for managing your personal knowledge, daily notes, and re-usable prompts via GitHub Gists ☆`179`
- [jean-technologies/jean-memory](https://github.com/jean-technologies/jean-memory) — next-generation AI memory infrastructure (powered by mem0 and graphiti) ☆`164`
- [jinzcdev/markmap-mcp-server](https://github.com/jinzcdev/markmap-mcp-server) — An MCP server for converting Markdown to interactive mind maps with export support (PNG/JPG/SVG). ☆`152`
- [pi22by7/In-Memoria](https://github.com/pi22by7/In-Memoria) — Persistent Intelligence Infrastructure for AI Agents ☆`131`
- [0xshellming/mcp-summarizer](https://github.com/0xshellming/mcp-summarizer) — MCP Server for AI Summarization ☆`147`
- [redleaves/context-keeper](https://github.com/redleaves/context-keeper) — LLM-Driven Intelligent Memory and Context Management System for AI agents ☆`124`
- [kaliaboi/mcp-zotero](https://github.com/kaliaboi/mcp-zotero) — A connector for Claude Desktop to work with collection and sources on your Zotero Cloud. ☆`141`
- [entanglr/zettelkasten-mcp](https://github.com/entanglr/zettelkasten-mcp) — A Model Context Protocol (MCP) server that implements the Zettelkasten knowledge management methodology, allowing you to create, link, explore and synthesize atomic notes through Claude and other MCP-compatible clients. ☆`128`
- [needle-ai/needle-mcp](https://github.com/needle-ai/needle-mcp) — Needle MCP Server for easy RAG.Long-term memory for LLMs. ☆`88`
- [ragieai/ragie-mcp-server](https://github.com/ragieai/ragie-mcp-server) — Ragie Model Context Protocol Server ☆`84`
- [run-llama/mcp-server-llamacloud](https://github.com/run-llama/mcp-server-llamacloud) — A MCP server connecting to managed indexes on LlamaCloud ☆`84`
- [ankimcp/anki-mcp-server](https://github.com/ankimcp/anki-mcp-server) — A Model Context Protocol (MCP) server that enables AI assistants to interact with Anki, the spaced repetition flashcard application. ☆`60`
- [agentic-mcp-tools/memora](https://github.com/agentic-mcp-tools/memora) —  ☆`47`
- [yuna0x0/hackmd-mcp](https://github.com/yuna0x0/hackmd-mcp) — A Model Context Protocol server for integrating HackMD's note-taking platform with AI assistants. ☆`45`
- [shinpr/mcp-local-rag](https://github.com/shinpr/mcp-local-rag) — Local RAG server for developers using MCP. Hybrid search (BM25 + semantic) for exact technical terms — fully private, zero setup. ☆`44`
- [HenryHaoson/Yuque-MCP-Server](https://github.com/HenryHaoson/Yuque-MCP-Server) — Yuque mcp server ☆`40`
- [rember/rember-mcp](https://github.com/rember/rember-mcp) — A Model Context Protocol (MCP) server for Rember. ☆`59`
- [vectara/vectara-mcp](https://github.com/vectara/vectara-mcp) — Open source MCP server for Vectara ☆`26`
- [akseyh/bear-mcp-server](https://github.com/akseyh/bear-mcp-server) — MCP Server integration for Bear note app ☆`41`
- [pinecone-io/assistant-mcp](https://github.com/pinecone-io/assistant-mcp) — Pinecone Assistant MCP server ☆`40`
- [cameronrye/openzim-mcp](https://github.com/cameronrye/openzim-mcp) — OpenZIM MCP is a modern, secure, and high-performance MCP (Model Context Protocol) server that enables AI models to access and search ZIM format knowledge bases offline. ☆`16`
- [bh-rat/context-awesome](https://github.com/bh-rat/context-awesome) — awesome-lists now available as MCP server for you agent. ☆`26`
- [agentset-ai/mcp-server](https://github.com/agentset-ai/mcp-server) — Agentset MCP Server - Build RAG with Agentic superpowers ☆`25`
- [Harry-027/JotDown](https://github.com/Harry-027/JotDown) — An MCP Server in Rust for creating Notion pages & mdBooks with LLMs ☆`19`
### Location & Maps

- [jjsantos01/qgis_mcp](https://github.com/jjsantos01/qgis_mcp) — Model Context Protocol (MCP) that allows LLMs to use QGIS Desktop ☆`732`
- [jagan-shanmugam/open-streetmap-mcp](https://github.com/jagan-shanmugam/open-streetmap-mcp) — An OpenStreetMap MCP server implementation that enhances LLM capabilities with location-based services and geospatial data. ☆`150`
- [mahdin75/gis-mcp](https://github.com/mahdin75/gis-mcp) — A Model Context Protocol (MCP) server implementation that connects Large Language Models (LLMs) to GIS operations using GIS libraries, enabling AI assistants to perform geospatial operations and transformations. ☆`87`
- [mahdin75/geoserver-mcp](https://github.com/mahdin75/geoserver-mcp) — A Model Context Protocol (MCP) server implementation that connects LLMs to the GeoServer REST API ☆`51`
- [briandconnelly/mcp-server-ipinfo](https://github.com/briandconnelly/mcp-server-ipinfo) — IP Geolocation Server for MCP ☆`39`
- [isdaniel/mcp_weather_server](https://github.com/isdaniel/mcp_weather_server) — A Model Context Protocol (MCP) server that provides weather information using the Open-Meteo API. ☆`35`
- [SecretiveShell/MCP-timeserver](https://github.com/SecretiveShell/MCP-timeserver) — A simple MCP server that exposes datetime information to agentic systems and chat REPLs ☆`40`
- [TimLukaHorstmann/mcp-weather](https://github.com/TimLukaHorstmann/mcp-weather) — A Model Context Protocol (MCP) server that provides hourly and daily weather forecasts using the AccuWeather API. ☆`30`
- [webcoderz/MCP-Geo](https://github.com/webcoderz/MCP-Geo) — Geocoding MCP server with GeoPY! ☆`29`
- [sjanaX01/weather-mcp-server](https://github.com/sjanaX01/weather-mcp-server) — A simple minimal weather mcp server :) ☆`19`
- [stadiamaps/stadiamaps-mcp-server-ts](https://github.com/stadiamaps/stadiamaps-mcp-server-ts) — A TypeScript MCP server for interacting with the Stadia Maps APIs ☆`18`
- [kukapay/nearby-search-mcp](https://github.com/kukapay/nearby-search-mcp) — An MCP server for nearby place searches with IP-based location detection. ☆`21`
### Marketing & Analytics

- [pipeboard-co/meta-ads-mcp](https://github.com/pipeboard-co/meta-ads-mcp) — MCP server to manage Facebook and Instagram Ads (Meta Ads) ☆`384`
- [open-strategy-partners/osp_marketing_tools](https://github.com/open-strategy-partners/osp_marketing_tools) — A Model Context Protocol (MCP) server that empowers LLMs to use some of Open Srategy Partners' core writing and product marketing techniques. ☆`258`
- [gomarble-ai/facebook-ads-mcp-server](https://github.com/gomarble-ai/facebook-ads-mcp-server) —  ☆`202`
- [gomarble-ai/google-ads-mcp-server](https://github.com/gomarble-ai/google-ads-mcp-server) — This repo helps us to analyze googla ads performance data ☆`84`
- [stape-io/google-tag-manager-mcp-server](https://github.com/stape-io/google-tag-manager-mcp-server) — MCP server for Google Tag Manager ☆`82`
- [MarketplaceAdPros/amazon-ads-mcp-server](https://github.com/MarketplaceAdPros/amazon-ads-mcp-server) — MCP Server to interact with Amazon Ads ☆`19`
### Media Processing

- [elevenlabs/elevenlabs-mcp](https://github.com/elevenlabs/elevenlabs-mcp) — The official ElevenLabs MCP server ☆`1,112`
- [anaisbetts/mcp-youtube](https://github.com/anaisbetts/mcp-youtube) — A Model-Context Protocol Server for YouTube ☆`481`
- [sunriseapps/imagesorcery-mcp](https://github.com/sunriseapps/imagesorcery-mcp) — An MCP server providing tools for image processing operations ☆`259`
- [video-creator/ffmpeg-mcp](https://github.com/video-creator/ffmpeg-mcp) — Using ffmpeg command line to achieve an mcp server, can be very convenient, through the dialogue to achieve the local video search, tailoring, stitching, playback,clip, overlay, concat and other functions ☆`106`
- [awkoy/replicate-flux-mcp](https://github.com/awkoy/replicate-flux-mcp) — MCP for Replicate Flux Model - A powerful tool for generating customized images and SVG assets that match specific coding vibes and aesthetic styles. Streamline your visual asset creation process with AI-powered design generation tailored for developers. ☆`82`
- [SureScaleAI/openai-gpt-image-mcp](https://github.com/SureScaleAI/openai-gpt-image-mcp) — A Model Context Protocol (MCP) tool server for OpenAI's GPT-4o/gpt-image-1 image generation and editing APIs. ☆`84`
- [apinetwork/piapi-mcp-server](https://github.com/apinetwork/piapi-mcp-server) — A TypeScript implementation of a Model Context Protocol (MCP) server that integrates with PiAPI's API. PiAPI makes user able to generate media content with Midjourney/Flux/Kling/LumaLabs/Udio/Chrip/Trellis directly from Claude or any other MCP-compatible apps. ☆`65`
- [SkyworkAI/Mureka-mcp](https://github.com/SkyworkAI/Mureka-mcp) — generate lyrics, song and background music(instrumental). Model Context Protocol (MCP) server. ☆`66`
- [hamflx/imagen3-mcp](https://github.com/hamflx/imagen3-mcp) — MCP server for Google Imagen 3 image generation ☆`50`
- [tan-yong-sheng/ai-vision-mcp](https://github.com/tan-yong-sheng/ai-vision-mcp) — A Model Context Protocol (MCP) server that provides vision capabilities to analyze image and video ☆`30`
- [stass/exif-mcp](https://github.com/stass/exif-mcp) — MCP server to extract image metadata (EXIF, XMP, etc) ☆`28`
- [flowy11/imagician](https://github.com/flowy11/imagician) — A MCP server for image edition ☆`18`
- [marcindulak/stt-mcp-server-linux](https://github.com/marcindulak/stt-mcp-server-linux) — Local speech-to-text MCP server for Tmux on Linux (for use not only with Claude Code) ☆`17`
- [magarcia/mcp-server-giphy](https://github.com/magarcia/mcp-server-giphy) — An implementation of Giphy integration with Model Context Protocol ☆`26`
- [zxkane/mcp-server-amazon-bedrock](https://github.com/zxkane/mcp-server-amazon-bedrock) — Model Context Procotol(MCP) server for using Amazon Bedrock Nova Canvas to generate images ☆`23`
### Monitoring & Observability

- [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana) — MCP server for Grafana ☆`2,024`
- [getsentry/sentry-mcp](https://github.com/getsentry/sentry-mcp) — An MCP server for interacting with Sentry via LLMs. ☆`485`
- [pydantic/logfire-mcp](https://github.com/pydantic/logfire-mcp) — The Logfire MCP Server is here! ☆`129`
- [mpeirone/zabbix-mcp-server](https://github.com/mpeirone/zabbix-mcp-server) — Complete MCP server for Zabbix integration - Connect AI assistants to Zabbix monitoring with 40+ tools for hosts, items, triggers, templates, problems, and more. Features read-only mode and comprehensive API coverage. ☆`122`
- [VictoriaMetrics-Community/mcp-victoriametrics](https://github.com/VictoriaMetrics-Community/mcp-victoriametrics) — The implementation of Model Context Protocol (MCP) server for VictoriaMetrics ☆`104`
- [seekrays/mcp-monitor](https://github.com/seekrays/mcp-monitor) — A system monitoring tool that exposes system metrics via the Model Context Protocol (MCP). This tool allows LLMs to retrieve real-time system information through an MCP-compatible interface. ☆`76`
- [axiomhq/mcp-server-axiom](https://github.com/axiomhq/mcp-server-axiom) — Axiom Model Context Protocol Server ☆`58`
- [hyperb1iss/lucidity-mcp](https://github.com/hyperb1iss/lucidity-mcp) — AI-powered code quality analysis using MCP to help AI assistants review code more effectively. Analyze git changes for complexity, security issues, and more through structured prompts. ☆`74`
- [last9/last9-mcp-server](https://github.com/last9/last9-mcp-server) — Last9 MCP Server ☆`48`
- [metoro-io/metoro-mcp-server](https://github.com/metoro-io/metoro-mcp-server) — Metoro MCP Server ☆`45`
- [MindscapeHQ/mcp-server-raygun](https://github.com/MindscapeHQ/mcp-server-raygun) — Give your AI coding assistants access to Raygun so they can investigate, explain, and help resolve errors for you. ☆`19`
- [inspektor-gadget/ig-mcp-server](https://github.com/inspektor-gadget/ig-mcp-server) — Debug your Container and Kubernetes workloads with an AI interface ☆`18`
- [emicklei/mcp-log-proxy](https://github.com/emicklei/mcp-log-proxy) — a web logging proxy for MCP client-server communication ☆`26`
- [tumf/grafana-loki-mcp](https://github.com/tumf/grafana-loki-mcp) — Grafana Loki MCP Repository ☆`17`
### Official

- [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) — Model Context Protocol Servers ☆`74,999`
### Productivity

- [mediar-ai/screenpipe](https://github.com/mediar-ai/screenpipe) — AI app store powered by 24/7 desktop history. open source | 100% local | dev friendly | 24/7 screen, mic recording ☆`16,260`
- [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server) — Official Notion MCP Server ☆`3,625`
- [taylorwilsdon/google_workspace_mcp](https://github.com/taylorwilsdon/google_workspace_mcp) — Control Gmail, Google Calendar, Docs, Sheets, Slides, Chat, Forms, Tasks, Search & Drive with AI - Comprehensive Google Workspace / G Suite MCP Server ☆`1,020`
- [suekou/mcp-notion-server](https://github.com/suekou/mcp-notion-server) —  ☆`842`
- [MarkusPfundstein/mcp-gsuite](https://github.com/MarkusPfundstein/mcp-gsuite) — MCP Server to interact with Google Gsuite prodcuts ☆`466`
- [abhiz123/todoist-mcp-server](https://github.com/abhiz123/todoist-mcp-server) — MCP server for Todoist integration enabling natural language task management with Claude ☆`340`
- [danhilse/notion_mcp](https://github.com/danhilse/notion_mcp) — A simple MCP integration that allows Claude to read and manage a personal Notion todo list ☆`204`
- [onebirdrocks/ebook-mcp](https://github.com/onebirdrocks/ebook-mcp) — A MCP server that supports mainstream eBook formats including EPUB, PDF and more. Simplify your eBook user experience with LLM. ☆`166`
- [makeplane/plane-mcp-server](https://github.com/makeplane/plane-mcp-server) — Plane's Official Model Context Protocol Server ☆`125`
- [its-dart/dart-mcp-server](https://github.com/its-dart/dart-mcp-server) — Dart AI Model Context Protocol (MCP) server ☆`124`
- [tacticlaunch/mcp-linear](https://github.com/tacticlaunch/mcp-linear) — MCP server that enables AI assistants to interact with Linear project management system through natural language, allowing users to retrieve, create, and update issues, projects, and teams. ☆`121`
- [roychri/mcp-server-asana](https://github.com/roychri/mcp-server-asana) —  ☆`110`
- [evalstate/mcp-miro](https://github.com/evalstate/mcp-miro) —  ☆`101`
- [taskade/mcp](https://github.com/taskade/mcp) — Taskade MCP · Official MCP server and OpenAPI to MCP codegen. Build AI agent tools from any OpenAPI API and connect to Claude, Cursor, and more. ☆`94`
- [ivo-toby/contentful-mcp](https://github.com/ivo-toby/contentful-mcp) — MCP (Model Context Protocol) server for the Contentful Management API ☆`61`
- [takumi0706/google-calendar-mcp](https://github.com/takumi0706/google-calendar-mcp) — Google Calendar MCP server for Claude Desktop integration ☆`53`
- [hiromitsusasaki/raindrop-io-mcp-server](https://github.com/hiromitsusasaki/raindrop-io-mcp-server) — An integration that allows LLMs to interact with Raindrop.io bookmarks using the Model Context Protocol (MCP). ☆`65`
- [k-jarzyna/mcp-miro](https://github.com/k-jarzyna/mcp-miro) — Miro integration for Model Context Protocol ☆`59`
- [feuerdev/keep-mcp](https://github.com/feuerdev/keep-mcp) — MCP server for Google Keep ☆`56`
- [kelvin6365/plane-mcp-server](https://github.com/kelvin6365/plane-mcp-server) —  ☆`34`
- [m0xai/trello-mcp-server](https://github.com/m0xai/trello-mcp-server) — A simple yet powerful MCP server for Trello. ☆`44`
- [esignaturescom/mcp-server-esignatures](https://github.com/esignaturescom/mcp-server-esignatures) — MCP server for eSignatures (https://esignatures.com) ☆`31`
- [jen6/ticktick-mcp](https://github.com/jen6/ticktick-mcp) — Enhance your TickTick workflow with MCP server. Better filtering interface ☆`42`
- [Badhansen/notion-mcp](https://github.com/Badhansen/notion-mcp) — A simple Model Context Protocol (MCP) server that integrates with Notion's API to manage my personal todo list. ☆`27`
- [orellazri/coda-mcp](https://github.com/orellazri/coda-mcp) — MCP Server for Coda ☆`38`
- [EduBase/MCP](https://github.com/EduBase/MCP) — The EduBase MCP server enables Claude and other LLMs to interact with EduBase's comprehensive e-learning platform through the Model Context Protocol (MCP). ☆`24`
- [dominik1001/caldav-mcp](https://github.com/dominik1001/caldav-mcp) — A CalDAV client using Model Context Protocol (MCP) to expose calendar operations as tools for AI assistants. ☆`40`
- [awwaiid/mcp-server-taskwarrior](https://github.com/awwaiid/mcp-server-taskwarrior) — MCP Server for TaskWarrior! ☆`39`
- [flesler/mcp-tasks](https://github.com/flesler/mcp-tasks) — A comprehensive and efficient MCP server for task management with multi-format support (Markdown, JSON, YAML) ☆`33`
- [bivex/kanboard-mcp](https://github.com/bivex/kanboard-mcp) — A Model Context Protocol (MCP) server written in Go that empowers AI agents and Large Language Models (LLMs) to seamlessly interact with Kanboard. It transforms natural language commands into Kanboard API calls, enabling intelligent automation of project, task, and user management, streamlining workflows, and enhancing productivity. ☆`18`
- [vgnshiyer/apple-books-mcp](https://github.com/vgnshiyer/apple-books-mcp) — Apple Books MCP Server ☆`35`
- [Fibery-inc/fibery-mcp-server](https://github.com/Fibery-inc/fibery-mcp-server) —  ☆`27`
- [danielkennedy1/pdf-tools-mcp](https://github.com/danielkennedy1/pdf-tools-mcp) —  ☆`31`
- [giuseppe-coco/Google-Workspace-MCP-Server](https://github.com/giuseppe-coco/Google-Workspace-MCP-Server) —  ☆`20`
### Research & Science

- [SecretiveShell/MCP-wolfram-alpha](https://github.com/SecretiveShell/MCP-wolfram-alpha) — Connect your chat repl to wolfram alpha computational intelligence ☆`69`
- [reeeeemo/ancestry-mcp](https://github.com/reeeeemo/ancestry-mcp) — Ancestry MCP server made with Python that allows interactability with .ged (GEDCOM) files ☆`29`
### Sandboxing & Execution

- [zerocore-ai/microsandbox](https://github.com/zerocore-ai/microsandbox) — opensource self-hosted sandboxes for ai agent ☆`4,245`
- [dagger/container-use](https://github.com/dagger/container-use) — Development environments for coding agents. Enable multiple agents to work safely and independently with your preferred stack. ☆`3,360`
- [e2b-dev/mcp-server](https://github.com/e2b-dev/mcp-server) — Giving Claude ability to run code with E2B via MCP (Model Context Protocol) ☆`362`
- [ckanthony/openapi-mcp](https://github.com/ckanthony/openapi-mcp) — Dockerized MCP Server to allow your AI agent to access any API with existing api docs ☆`164`
- [alfonsograziano/node-code-sandbox-mcp](https://github.com/alfonsograziano/node-code-sandbox-mcp) — A Node.js–based Model Context Protocol server that spins up disposable Docker containers to execute arbitrary JavaScript. ☆`141`
- [yepcode/mcp-server-js](https://github.com/yepcode/mcp-server-js) — An MCP (Model Context Protocol) server that enables AI platforms to interact with YepCode's infrastructure. Turn your YepCode processes into powerful tools that AI assistants can use ☆`41`
- [r33drichards/mcp-js](https://github.com/r33drichards/mcp-js) — MCP server that exposes a V8 JavaScript runtime as a tool for AI agents like Claude and Cursor. Supports persistent heap snapshots via S3 or local filesystem, and is ready for integration with modern AI development environments. ☆`27`
- [hileamlakB/Python-Runtime-Interpreter-MCP-Server](https://github.com/hileamlakB/Python-Runtime-Interpreter-MCP-Server) — PRIMS is a lightweight, open-source Model Context Protocol (MCP) server that lets LLM agents safely execute arbitrary Python code in a secure, throw-away sandbox. ☆`24`
- [criteo/openapi-to-mcp](https://github.com/criteo/openapi-to-mcp) — An MCP server for your API ☆`27`
- [gwbischof/outsource-mcp](https://github.com/gwbischof/outsource-mcp) — Give your AI assistant its own AI assistants. ☆`28`
### Search & Extraction

- [ScrapeGraphAI/Scrapegraph-ai](https://github.com/ScrapeGraphAI/Scrapegraph-ai) — Python scraper based on AI ☆`22,068`
- [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) — Exa MCP for web search and web crawling! ☆`3,447`
- [blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server) — A Model Context Protocol server for searching and analyzing arXiv papers ☆`1,975`
- [tavily-ai/tavily-mcp](https://github.com/tavily-ai/tavily-mcp) — Production ready MCP server with real-time search, extract, map & crawl. ☆`1,024`
- [jae-jae/fetcher-mcp](https://github.com/jae-jae/fetcher-mcp) — MCP server for fetch web page content using Playwright headless browser. ☆`939`
- [nickclyde/duckduckgo-mcp-server](https://github.com/nickclyde/duckduckgo-mcp-server) — A Model Context Protocol (MCP) server that provides web search capabilities through DuckDuckGo, with additional features for content fetching and parsing. ☆`700`
- [apify/apify-mcp-server](https://github.com/apify/apify-mcp-server) — The Apify MCP server enables your AI agents to extract data from social media, search engines, maps, e-commerce sites, or any other website using thousands of ready-made scrapers, crawlers, and automation tools available on the Apify Store. ☆`658`
- [Aas-ee/open-webSearch](https://github.com/Aas-ee/open-webSearch) — WebSearchMCP using free multi-engine search (NO API KEYS REQUIRED) — Supports Bing, Baidu, DuckDuckGo, Brave, Exa, Github, Juejin and CSDN. ☆`543`
- [brave/brave-search-mcp-server](https://github.com/brave/brave-search-mcp-server) — MCP server integrating Brave Search API with web, local, image, video, news search and AI summarization ☆`437`
- [mrkrsl/web-search-mcp](https://github.com/mrkrsl/web-search-mcp) — A simple, locally hosted Web Search MCP server for use with Local LLMs ☆`410`
- [ihor-sokoliuk/mcp-searxng](https://github.com/ihor-sokoliuk/mcp-searxng) — MCP Server for SearXNG ☆`367`
- [kagisearch/kagimcp](https://github.com/kagisearch/kagimcp) — The Official Model Context Protocol (MCP) server for Kagi search & other tools. ☆`240`
- [jae-jae/g-search-mcp](https://github.com/jae-jae/g-search-mcp) — A powerful MCP server for Google search that enables parallel searching with multiple keywords simultaneously. ☆`235`
- [apify/mcp-server-rag-web-browser](https://github.com/apify/mcp-server-rag-web-browser) — A MCP Server for the RAG Web Browser Actor ☆`195`
- [hellokaton/unsplash-mcp-server](https://github.com/hellokaton/unsplash-mcp-server) — A MCP server for Unsplash image search. ☆`193`
- [reading-plus-ai/mcp-server-deep-research](https://github.com/reading-plus-ai/mcp-server-deep-research) —  ☆`195`
- [andybrandt/mcp-simple-arxiv](https://github.com/andybrandt/mcp-simple-arxiv) — Tool to work with arXiv, provide LLM with ability to search and read papers from there ☆`176`
- [meilisearch/meilisearch-mcp](https://github.com/meilisearch/meilisearch-mcp) — A Model Context Protocol (MCP) server for interacting with Meilisearch through LLM interfaces. ☆`158`
- [andybrandt/mcp-simple-pubmed](https://github.com/andybrandt/mcp-simple-pubmed) — MCP server for searching and querying PubMed medical papers/research database ☆`147`
- [fatwang2/search1api-mcp](https://github.com/fatwang2/search1api-mcp) —  ☆`159`
- [tinyfish-io/agentql-mcp](https://github.com/tinyfish-io/agentql-mcp) — Model Context Protocol server that integrates AgentQL's data extraction capabilities. ☆`137`
- [deadletterq/mcp-opennutrition](https://github.com/deadletterq/mcp-opennutrition) — MCP server providing access to the comprehensive OpenNutrition food database with 300,000+ food items, nutritional data, and barcode lookups ☆`146`
- [lfnovo/content-core](https://github.com/lfnovo/content-core) — Extract what matters from any media source ☆`107`
- [just-every/mcp-read-website-fast](https://github.com/just-every/mcp-read-website-fast) — Quickly reads webpages and converts to markdown for fast, token efficient web scraping ☆`119`
- [ChanMeng666/server-google-news](https://github.com/ChanMeng666/server-google-news) — 【Star-crossed coders unite!】Model Context Protocol (MCP) server implementation providing Google News search capabilities via SerpAPI, with automatic news categorization and multi-language support. ☆`98`
- [nkapila6/mcp-local-rag](https://github.com/nkapila6/mcp-local-rag) — "primitive" RAG-like web search model context protocol (MCP) server that runs locally. no APIs ☆`95`
- [ahonn/mcp-server-gsc](https://github.com/ahonn/mcp-server-gsc) — A Model Context Protocol (MCP) server providing access to Google Search Console ☆`90`
- [SecretiveShell/MCP-searxng](https://github.com/SecretiveShell/MCP-searxng) — MCP server for connecting agentic systems to search systems via searXNG ☆`108`
- [vectorize-io/vectorize-mcp-server](https://github.com/vectorize-io/vectorize-mcp-server) — Official Vectorize MCP Server ☆`101`
- [oxylabs/oxylabs-mcp](https://github.com/oxylabs/oxylabs-mcp) — Official Oxylabs MCP integration ☆`77`
- [just-every/mcp-screenshot-website-fast](https://github.com/just-every/mcp-screenshot-website-fast) — Quickly screenshots webpages and converts to an LLM friendly size ☆`94`
- [serpapi/serpapi-mcp](https://github.com/serpapi/serpapi-mcp) — SerpApi MCP Server for Google and other search engine results ☆`77`
- [mikechao/brave-search-mcp](https://github.com/mikechao/brave-search-mcp) — An MCP Server implementation that integrates the Brave Search API, providing, Web Search, Local Points of Interest Search, Image Search, Video Search and News Search capabilities ☆`88`
- [tanigami/mcp-server-perplexity](https://github.com/tanigami/mcp-server-perplexity) —  ☆`87`
- [ConechoAI/openai-websearch-mcp](https://github.com/ConechoAI/openai-websearch-mcp) — openai websearch tool as mcp server ☆`78`
- [takashiishida/arxiv-latex-mcp](https://github.com/takashiishida/arxiv-latex-mcp) — MCP server that uses arxiv-to-prompt to fetch and process arXiv LaTeX sources for precise interpretation of mathematical expressions in scientific papers. ☆`77`
- [zoomeye-ai/mcp_zoomeye](https://github.com/zoomeye-ai/mcp_zoomeye) — A Model Context Protocol server that provides network asset information based on query conditions. This server allows LLMs to obtain network asset information and supports querying network asset information by zoomeye dork etc. ☆`59`
- [OctagonAI/octagon-deep-research-mcp](https://github.com/OctagonAI/octagon-deep-research-mcp) — The Octagon Deep Research MCP server provides specialized AI-powered comprehensive research and analysis capabilities by integrating with advanced deep research agents. No rate limits, faster than ChatGPT Deep Research, more thorough than Grok DeepSearch or Perplexity Deep Research. ☆`79`
- [isnow890/naver-search-mcp](https://github.com/isnow890/naver-search-mcp) — MCP server for Naver Search API integration. Provides comprehensive search capabilities across Naver services (web, news, blog, shopping, etc) and data trend analysis tools via DataLab API. ☆`47`
- [zhsama/duckduckgo-mcp-server](https://github.com/zhsama/duckduckgo-mcp-server) —  ☆`68`
- [leehanchung/bing-search-mcp](https://github.com/leehanchung/bing-search-mcp) — MCP Server for Bing Search API ☆`67`
- [scrapeless-ai/scrapeless-mcp-server](https://github.com/scrapeless-ai/scrapeless-mcp-server) — Scrapeless Mcp Server ☆`61`
- [erithwik/mcp-hn](https://github.com/erithwik/mcp-hn) — MCP Server for Hackernews ☆`56`
- [akalaric/mcp-wolframalpha](https://github.com/akalaric/mcp-wolframalpha) — A Python-powered Model Context Protocol MCP server and client that uses Wolfram Alpha via API. ☆`56`
- [webscraping-ai/webscraping-ai-mcp-server](https://github.com/webscraping-ai/webscraping-ai-mcp-server) — A Model Context Protocol (MCP) server implementation that integrates with WebScraping.AI for web data extraction capabilities. ☆`35`
- [yamanoku/baseline-mcp-server](https://github.com/yamanoku/baseline-mcp-server) — MCP server providing Baseline status information for specific Web APIs ☆`36`
- [0xDAEF0F/job-searchoor](https://github.com/0xDAEF0F/job-searchoor) — A simple MCP server that delivers you jobs based on your needs ☆`55`
- [pragmar/mcp-server-webcrawl](https://github.com/pragmar/mcp-server-webcrawl) — MCP server tailored to connecting web crawler data and archives ☆`34`
- [Tomatio13/mcp-server-tavily](https://github.com/Tomatio13/mcp-server-tavily) — MCP Server for Tavily API integration ☆`46`
- [ananddtyagi/webpage-screenshot-mcp](https://github.com/ananddtyagi/webpage-screenshot-mcp) — An MCP that gives your agent the ability to snap a screenshot of webpages. Useful when you want your agent to check its progress during development. ☆`45`
- [imprvhub/mcp-domain-availability](https://github.com/imprvhub/mcp-domain-availability) — A Model Context Protocol (MCP) server that enables Claude Desktop to check domain availability across 50+ TLDs. Features DNS/WHOIS verification, bulk checking, and smart suggestions. Zero-clone installation via uvx. ☆`29`
- [Linked-API/linkedapi-mcp](https://github.com/Linked-API/linkedapi-mcp) — MCP server that lets AI assistants control LinkedIn accounts and retrieve real-time data. ☆`29`
- [wong2/mcp-jina-reader](https://github.com/wong2/mcp-jina-reader) — Jina Reader MCP Server ☆`46`
- [imprvhub/mcp-rss-aggregator](https://github.com/imprvhub/mcp-rss-aggregator) — Model Context Protocol Server for aggregating RSS feeds in Claude Desktop ☆`20`
- [kehvinbehvin/json-mcp-filter](https://github.com/kehvinbehvin/json-mcp-filter) — JSON MCP server to filter only relevant data for your LLM ☆`20`
- [DappierAI/dappier-mcp](https://github.com/DappierAI/dappier-mcp) — Enable fast, free real-time web search and access premium data from trusted media brands—news, financial markets, sports, entertainment, weather, and more. Build powerful AI agents with Dappier. ☆`38`
- [adawalli/nexus](https://github.com/adawalli/nexus) — MCP Server to make searching openrouter easy ☆`19`
- [siva010928/multi-chat-mcp-server](https://github.com/siva010928/multi-chat-mcp-server) — Google Chat MCP server that lets AI assistants like Claude and Cursor participate directly in team conversations - search messages, help teammates, share files, and coordinate across chat platforms. ☆`17`
- [ac3xx/mcp-servers-kagi](https://github.com/ac3xx/mcp-servers-kagi) — A Model Context Protocol server implementation for Kagi's API ☆`41`
- [pskill9/hn-server](https://github.com/pskill9/hn-server) — Hacker news MCP server ☆`35`
- [r-huijts/opentk-mcp](https://github.com/r-huijts/opentk-mcp) — A Model Context Protocol (MCP) server providing access to Dutch parliamentary data (Tweede Kamer) through OpenTK . This server enables AI assistants to search, retrieve, and analyze parliamentary documents, activities, and information as published by parliament.. ☆`16`
- [DumplingAI/mcp-server-dumplingai](https://github.com/DumplingAI/mcp-server-dumplingai) — MCP (Model Context Protocol) server for Dumpling AI ☆`29`
- [format37/youtube_mcp](https://github.com/format37/youtube_mcp) — youtube transcriber mcp server ☆`26`
- [damionrashford/RivalSearchMCP](https://github.com/damionrashford/RivalSearchMCP) — Advanced MCP server for comprehensive web research, content discovery, and trends analysis. Features multi-engine search, intelligent content extraction, website traversal, and real-time data streaming. ☆`21`
- [amurshak/congressMCP](https://github.com/amurshak/congressMCP) — An MCP server allowing AI agents and MCP clients to interface with the Congress.gov API ☆`20`
- [mnhlt/WebSearch-MCP](https://github.com/mnhlt/WebSearch-MCP) — [Self-hosted] A Model Context Protocol (MCP) server implementation that provides a web search capability over stdio transport. This server integrates with a WebSearch Crawler API to retrieve search results. ☆`22`
- [angheljf/nyt](https://github.com/angheljf/nyt) —  ☆`16`
- [the0807/GeekNews-MCP-Server](https://github.com/the0807/GeekNews-MCP-Server) — GeekNews MCP Server ☆`16`
### Security

- [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) — MCP Server for Ghidra ☆`6,805`
- [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) — AI-powered reverse engineering assistant that bridges IDA Pro with language models through MCP. ☆`4,737`
- [mariocandela/beelzebub](https://github.com/mariocandela/beelzebub) — A secure low code honeypot framework, leveraging AI for System Virtualization. ☆`1,772`
- [zinja-coder/jadx-ai-mcp](https://github.com/zinja-coder/jadx-ai-mcp) — Plugin for JADX to integrate MCP server ☆`920`
- [jtang613/GhidrAssistMCP](https://github.com/jtang613/GhidrAssistMCP) — An MCP extension for Ghidra ☆`383`
- [SonarSource/sonarqube-mcp-server](https://github.com/SonarSource/sonarqube-mcp-server) — SonarQube MCP Server ☆`327`
- [MorDavid/BloodHound-MCP-AI](https://github.com/MorDavid/BloodHound-MCP-AI) — BloodHound-MCP-AI is integration that connects BloodHound with AI through Model Context Protocol, allowing security professionals to analyze Active Directory attack paths using natural language instead of complex Cypher queries. ☆`321`
- [zinja-coder/apktool-mcp-server](https://github.com/zinja-coder/apktool-mcp-server) — A MCP Server for APK Tool (Part of Android Reverse Engineering MCP Suites) ☆`269`
- [BurtTheCoder/mcp-maigret](https://github.com/BurtTheCoder/mcp-maigret) — MCP server for maigret, a powerful OSINT tool that collects user account information from various public sources. ☆`216`
- [gbrigandi/mcp-server-wazuh](https://github.com/gbrigandi/mcp-server-wazuh) — MCP Server for Wazuh SIEM ☆`153`
- [securityfortech/secops-mcp](https://github.com/securityfortech/secops-mcp) — All-in-one security testing toolbox that brings together popular open source tools through a single MCP interface. Connected to an AI agent, it enables tasks like pentesting, bug bounty hunting, threat hunting, and more. ☆`167`
- [fosdickio/binary_ninja_mcp](https://github.com/fosdickio/binary_ninja_mcp) — A Binary Ninja plugin containing an MCP server that enables seamless integration with your favorite LLM/MCP client. ☆`139`
- [radareorg/radare2-mcp](https://github.com/radareorg/radare2-mcp) — MCP stdio server for radare2 ☆`116`
- [box-community/mcp-server-box](https://github.com/box-community/mcp-server-box) — Securely connect AI agents to your enterprise content in Box ☆`88`
- [BurtTheCoder/mcp-virustotal](https://github.com/BurtTheCoder/mcp-virustotal) — A Model Context Protocol (MCP) server for querying the VirusTotal API. ☆`95`
- [BurtTheCoder/mcp-shodan](https://github.com/BurtTheCoder/mcp-shodan) — MCP server for querying the Shodan API ☆`94`
- [13bm/GhidraMCP](https://github.com/13bm/GhidraMCP) — Socket based MCP Server for Ghidra ☆`82`
- [roadwy/cve-search_mcp](https://github.com/roadwy/cve-search_mcp) — A Model Context Protocol (MCP) server for querying the CVE-Search API ☆`75`
- [82ch/MCP-Dandan](https://github.com/82ch/MCP-Dandan) — MCP Security Solution for Agentic AI — real-time proxying, behavior analysis, and malicious tool detection ☆`58`
- [panther-labs/mcp-panther](https://github.com/panther-labs/mcp-panther) — Write detections, investigate alerts, and query logs from your favorite AI agents ☆`36`
- [qianniuspace/mcp-security-audit](https://github.com/qianniuspace/mcp-security-audit) — A powerful MCP (Model Context Protocol) Server that audits npm package dependencies for security vulnerabilities. Built with remote npm registry integration for real-time security checks. ☆`49`
- [firstorderai/authenticator_mcp](https://github.com/firstorderai/authenticator_mcp) — A secure MCP (Model Context Protocol) server that enables AI agents to interact with the Authenticator App. ☆`30`
- [atomicchonk/roadrecon_mcp_server](https://github.com/atomicchonk/roadrecon_mcp_server) — Claude MCP server to perform analysis on ROADrecon data ☆`48`
- [vespo92/OPNSenseMCP](https://github.com/vespo92/OPNSenseMCP) — MCP Server for OPNSense to act as IaC proxy ☆`27`
- [fr0gger/MCP_Security](https://github.com/fr0gger/MCP_Security) — This is a repository to experiment with MCP for security ☆`45`
- [StacklokLabs/osv-mcp](https://github.com/StacklokLabs/osv-mcp) — An MCP server for OSV ☆`25`
- [BurtTheCoder/mcp-dnstwist](https://github.com/BurtTheCoder/mcp-dnstwist) — MCP server for dnstwist, a powerful DNS fuzzing tool that helps detect typosquatting, phishing, and corporate espionage. ☆`41`
- [intruder-io/intruder-mcp](https://github.com/intruder-io/intruder-mcp) — An MCP server to let AI agents control Intruder ☆`22`
- [zboralski/ida-headless-mcp](https://github.com/zboralski/ida-headless-mcp) — Headless IDA Pro binary analysis via Model Context Protocol ☆`22`
- [Gaffx/volatility-mcp](https://github.com/Gaffx/volatility-mcp) — This repo hosts an MCP server for volatility3.x ☆`36`
- [AIM-Intelligence/AIM-MCP](https://github.com/AIM-Intelligence/AIM-MCP) — AIM MCP Server :: Guard and Protect your MCPs & AI Chatting ☆`16`
- [ChristophEnglisch/keycloak-model-context-protocol](https://github.com/ChristophEnglisch/keycloak-model-context-protocol) — MCP server implementation for Keycloak user management. Enables AI-powered administration of Keycloak users and realms through the Model Context Protocol (MCP). Seamlessly integrates with Claude Desktop and other MCP clients for automated user operations. ☆`34`
- [hieuttmmo/entraid-mcp-server](https://github.com/hieuttmmo/entraid-mcp-server) — MCP server for interacting with EntraID through Microsoft Graph API. ☆`31`
- [slouchd/cyberchef-api-mcp-server](https://github.com/slouchd/cyberchef-api-mcp-server) — CyberChef API MCP Server ☆`31`
- [nickpending/mcp-recon](https://github.com/nickpending/mcp-recon) — Tellix is a conversational recon interface powered by httpx and LLMs. Just ask. ☆`24`
- [pullkitsan/mobsf-mcp-server](https://github.com/pullkitsan/mobsf-mcp-server) — This MCP server uses mobsf api's to scan and analyze the apk and ipa files. ☆`18`
- [cromwellian/hippycampus](https://github.com/cromwellian/hippycampus) — An (eventually) secure open-source MCP Server to turn any REST endpoint into MCP resources automatically ☆`20`
- [kontext-dev/attestable-mcp-server](https://github.com/kontext-dev/attestable-mcp-server) — Verify that any MCP server is running the intended and untampered code via hardware attestation. ☆`17`
### Social Media

- [caol64/wenyan-mcp](https://github.com/caol64/wenyan-mcp) — MCP Server that automatically formats Markdown articles and publishes them to WeChat Official Accounts ☆`945`
- [varunneal/spotify-mcp](https://github.com/varunneal/spotify-mcp) — MCP to connect your LLM with Spotify. ☆`546`
- [karanb192/reddit-mcp-buddy](https://github.com/karanb192/reddit-mcp-buddy) — Clean, LLM-optimized Reddit MCP server. Browse posts, search content, analyze users. No fluff, just Reddit data. ☆`325`
- [marcelmarais/spotify-mcp-server](https://github.com/marcelmarais/spotify-mcp-server) — Lightweight MCP server for Spotify ☆`202`
- [talknerdytome-labs/facebook-ads-library-mcp](https://github.com/talknerdytome-labs/facebook-ads-library-mcp) — MCP Server for Facebook ADs Library - Get instant answers from FB's ad library ☆`164`
- [Seym0n/tiktok-mcp](https://github.com/Seym0n/tiktok-mcp) — Model Context Protocol (MCP) with TikTok integration ☆`118`
- [king-of-the-grackles/reddit-research-mcp](https://github.com/king-of-the-grackles/reddit-research-mcp) — Turn Reddit's chaos into structured insights with full citations. MCP server for competitive analysis, customer discovery, and market research. Zero-setup hosted solution with semantic search across 20,000+ subreddits. ☆`70`
- [HagaiHen/facebook-mcp-server](https://github.com/HagaiHen/facebook-mcp-server) — Facebook MCP server for automating posts, comment moderation, insights, and sentiment filtering. ☆`81`
- [LuniaKunal/mcp-twitter](https://github.com/LuniaKunal/mcp-twitter) — Manage your twitter account using mcp ☆`50`
- [anwerj/youtube-uploader-mcp](https://github.com/anwerj/youtube-uploader-mcp) — Upload Videos with the help of AI ☆`30`
- [macrocosm-os/macrocosmos-mcp](https://github.com/macrocosm-os/macrocosmos-mcp) — The MCP for macrocosmos subnets. ☆`26`
- [imprvhub/mcp-claude-spotify](https://github.com/imprvhub/mcp-claude-spotify) — An integration that allows Claude Desktop to interact with Spotify using the Model Context Protocol (MCP). ☆`21`
### Sports

- [r-huijts/strava-mcp](https://github.com/r-huijts/strava-mcp) — A Model Context Protocol (MCP) server that connects to Strava API, providing tools to access Strava data through LLMs ☆`203`
- [guillochon/mlb-api-mcp](https://github.com/guillochon/mlb-api-mcp) — A Model Context Protocol (MCP) server that provides comprehensive access to MLB statistics and baseball data through a FastMCP-based interface. ☆`35`
- [mikechao/balldontlie-mcp](https://github.com/mikechao/balldontlie-mcp) — An MCP Server implementation that integrates the Balldontlie API, to provide information about players, teams and games for the NBA, NFL and MLB ☆`19`
- [r-huijts/firstcycling-mcp](https://github.com/r-huijts/firstcycling-mcp) — This is a Model Context Protocol (MCP) server that provides professional cycling data from FirstCycling. It allows you to retrieve information about professional cyclists, race results, and more. ☆`17`
- [kw510/strava-mcp](https://github.com/kw510/strava-mcp) — A Model Context Protocol (MCP) server with Strava OAuth integration, built on Cloudflare Workers. Enables secure authentication and tool access for MCP clients like Claude and Cursor through Strava login. Perfect for developers looking to integrate Strava authentication with AI tools. ☆`23`
- [RobSpectre/mvf1](https://github.com/RobSpectre/mvf1) — A Python package and command line interface to control video players for MultiViewer For F1, the best way to watch Formula 1. ☆`17`
### Support & ITSM

- [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) — MCP server for Atlassian tools (Confluence, Jira) ☆`3,850`
- [nguyenvanduocit/jira-mcp](https://github.com/nguyenvanduocit/jira-mcp) — A Go-based MCP (Model Control Protocol) connector for Jira that enables AI assistants like Claude to interact with Atlassian Jira. This tool provides a seamless interface for AI models to perform common Jira operations including issue management, sprint planning, and workflow transitions. ☆`73`
- [effytech/freshdesk_mcp](https://github.com/effytech/freshdesk_mcp) — MCP server created for Freshdesk, allowing AI models to interact with Freshdesk modules ☆`35`
- [aikts/yandex-tracker-mcp](https://github.com/aikts/yandex-tracker-mcp) — Yandex Tracker MCP Server with OAuth2 support ☆`32`
- [KS-GEN-AI/jira-mcp-server](https://github.com/KS-GEN-AI/jira-mcp-server) — A test of jira mcp server ☆`25`
- [quickchatai/quickchat-ai-mcp](https://github.com/quickchatai/quickchat-ai-mcp) — The Quickchat AI MCP server ☆`21`
### Text-to-Speech

- [mbailey/voicemode](https://github.com/mbailey/voicemode) — VoiceMode MCP brings natural conversations to Claude Code ☆`518`
- [mberg/kokoro-tts-mcp](https://github.com/mberg/kokoro-tts-mcp) — Kokoro Text to Speech (TTS) MCP Server ☆`70`
### Translation

- [translated/lara-mcp](https://github.com/translated/lara-mcp) — MCP Server for Lara Translate API, enabling translation capabilities with language detection and translation memories ☆`75`
### Travel & Transport

- [openbnb-org/mcp-server-airbnb](https://github.com/openbnb-org/mcp-server-airbnb) — Search Airbnb using your AI Agent ☆`349`
- [cobanov/teslamate-mcp](https://github.com/cobanov/teslamate-mcp) — A Model Context Protocol (MCP) server that provides access to your TeslaMate database, allowing AI assistants to query Tesla vehicle data and analytics. ☆`110`
- [r-huijts/ns-mcp-server](https://github.com/r-huijts/ns-mcp-server) — A Model Context Protocol (MCP) server that provides access to NS (Dutch Railways) travel information through Claude AI. This server enables Claude to fetch real-time train travel information and disruptions using the official Dutch NS API. ☆`43`
- [pab1it0/tripadvisor-mcp](https://github.com/pab1it0/tripadvisor-mcp) — A Model Context Protocol (MCP) server for Tripadvisor Content API. This provides access to Tripadvisor location data, reviews, and photos through standardized MCP interfaces, allowing AI assistants to search for travel destinations and experiences. ☆`47`
- [KyrieTangSheng/mcp-server-nationalparks](https://github.com/KyrieTangSheng/mcp-server-nationalparks) — MCP Server for the National Park Service API, providing real-time information about U.S. National Parks ☆`35`
### Version Control

- [github/github-mcp-server](https://github.com/github/github-mcp-server) — GitHub's official MCP Server ☆`25,421`
- [Tiberriver256/mcp-server-azure-devops](https://github.com/Tiberriver256/mcp-server-azure-devops) — An MCP server for Azure DevOps ☆`312`
- [adhikasp/mcp-git-ingest](https://github.com/adhikasp/mcp-git-ingest) — A Model Context Protocol (MCP) server that helps read GitHub repository structure and important files. ☆`294`
- [puravparab/Gitingest-MCP](https://github.com/puravparab/Gitingest-MCP) — mcp server for gitingest ☆`131`
- [kopfrechner/gitlab-mr-mcp](https://github.com/kopfrechner/gitlab-mr-mcp) — Interact seamlessly with GitLab repositories to manage merge requests and issues. Fetch details, add comments, and streamline your code review process with ease. ☆`71`
- [ddukbg/github-enterprise-mcp](https://github.com/ddukbg/github-enterprise-mcp) — github-enterprise-mcp ☆`27`
## MCP Clients

- [zed-industries/zed](https://github.com/zed-industries/zed) — Code at the speed of thought – Zed is a high-performance, multiplayer code editor from the creators of Atom and Tree-sitter. ☆`72,014`
- [continuedev/continue](https://github.com/continuedev/continue) — Ship faster with Continuous AI. Open-source CLI that can be used in TUI mode as a coding agent or Headless mode to run background agents ☆`30,511`
- [Upsonic/Upsonic](https://github.com/Upsonic/Upsonic) — Agent Framework For Fintech and Banks ☆`7,740`
- [firebase/genkit](https://github.com/firebase/genkit) — Open-source framework for building AI-powered apps in JavaScript, Go, and Python, built and used in production by Google ☆`5,253`
- [ravitemer/mcphub.nvim](https://github.com/ravitemer/mcphub.nvim) — An MCP client for Neovim that seamlessly integrates MCP servers into your editing workflow with an intuitive interface for managing, testing, and using MCP servers with your favorite chat plugins. ☆`1,675`
- [evilsocket/nerve](https://github.com/evilsocket/nerve) — The Simple Agent Development Kit. ☆`1,313`
- [SecretiveShell/MCP-Bridge](https://github.com/SecretiveShell/MCP-Bridge) — A middleware to provide an openAI compatible endpoint that can call MCP tools ☆`883`
- [EvalsOne/MCP-connect](https://github.com/EvalsOne/MCP-connect) — Enables cloud-based AI services to access local Stdio based MCP servers via HTTP requests ☆`227`
- [3choff/mcp-chatbot](https://github.com/3choff/mcp-chatbot) — A simple CLI chatbot that demonstrates the integration of the Model Context Protocol (MCP). ☆`241`
- [rakesh-eltropy/mcp-client](https://github.com/rakesh-eltropy/mcp-client) — A simple REST API and CLI client to interact with MCP servers, integrated with LangChain and supporting multiple LLM... ☆`51`
## Frameworks & SDKs

- [jlowin/fastmcp](https://github.com/jlowin/fastmcp) — The fast, Pythonic way to build MCP servers and clients ☆`21,417`
- [mark3labs/mcp-go](https://github.com/mark3labs/mcp-go) — A Go implementation of the Model Context Protocol (MCP), enabling seamless integration between LLM applications and external data sources and tools. ☆`7,861`
- [punkpeye/fastmcp](https://github.com/punkpeye/fastmcp) — A TypeScript framework for building MCP servers. ☆`2,841`
- [stacklok/toolhive](https://github.com/stacklok/toolhive) — ToolHive makes deploying MCP servers easy, secure and fun ☆`1,459`
- [QuantGeekDev/mcp-framework](https://github.com/QuantGeekDev/mcp-framework) — A framework for writing MCP (Model Context Protocol) servers in Typescript ☆`888`
- [php-mcp/laravel](https://github.com/php-mcp/laravel) — An SDK building Laravel MCP servers ☆`466`
- [opgginc/laravel-mcp-server](https://github.com/opgginc/laravel-mcp-server) — A Laravel package for implementing secure Model Context Protocol servers using Streamable HTTP and SSE transport, providing real-time communication and a scalable tool system for enterprise environments. ☆`327`
- [wong2/litemcp](https://github.com/wong2/litemcp) — A TypeScript framework for building MCP servers elegantly ☆`182`
- [Epistates/turbomcp](https://github.com/Epistates/turbomcp) — A full featured, enterprise grade rust MCP SDK ☆`56`
- [oatpp/oatpp-mcp](https://github.com/oatpp/oatpp-mcp) — Anthropic’s Model Context Protocol implementation for Oat++ ☆`48`
- [Super-I-Tech/mcp_plexus](https://github.com/Super-I-Tech/mcp_plexus) — Secure, Multi-Tenant MCP Server Framework for Modern AI ☆`24`
- [stephencme/create-mcp-ts](https://github.com/stephencme/create-mcp-ts) — Create a new MCP server in TypeScript, batteries included. ☆`21`


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
