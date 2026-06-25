# Awesome Agent Runtime

A curated landscape of agent runtimes, sandboxes, browser agents, tool protocols, memory layers, observability, and compute platforms for production AI agents.

This is not a generic AI tools directory. The focus is infrastructure that helps developers build, run, secure, observe, and scale agents in real products.

Maintained by [SandBase AI](https://www.sandbase.ai/), an agent infrastructure platform for developers building production AI agents.

## Contribute

Know a project that belongs here?

- Suggest a project with the [project submission issue template](.github/ISSUE_TEMPLATE/suggest-project.yml).
- Fix a category, description, or link with the [category cleanup template](.github/ISSUE_TEMPLATE/category-cleanup.yml).
- Read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a larger pull request.

## Why This Exists

Agent apps are becoming more than prompts wrapped in a UI. They need runtime control, tool access, sandboxed execution, memory, model routing, observability, deployment, and safe integration with real systems.

This repository tracks the projects that are shaping that stack.

Use it to:

- Explore the agent runtime and infrastructure ecosystem.
- Find projects worth integrating, studying, or contributing to.
- Track emerging infrastructure categories around production agents.
- Submit new projects that deserve attention from AI builders.

## Selection Criteria

Projects should meet at least one of these standards:

- Directly help build, run, protect, observe, integrate, or deploy AI agents.
- Have real adoption, strong technical signal, or clear relevance to production agent stacks.
- Represent a future-facing direction such as computer use, MCP, sandboxed runtime, agent memory, evals, or distributed compute.
- Be useful to builders, not just a thin demo or wrapper.

We avoid low-quality AI tool directories, pure prompt libraries, and projects with no clear agent infrastructure angle.

## Categories

- **Agent runtime**: orchestration, state, handoffs, workflows, and multi-agent control.
- **Execution sandbox**: safe code, shell, file, notebook, or dev environment execution.
- **Browser automation**: browser agents, web automation, Playwright infrastructure, and computer-use systems.
- **Tool protocol**: MCP, tool schemas, tool registries, and standardized action interfaces.
- **App integrations**: OAuth, SaaS actions, durable jobs, and API workflows for agents.
- **Memory/context**: long-term memory, vector stores, conversation state, and personalized context.
- **Safety/evals**: guardrails, prompt-injection defense, red teaming, and test harnesses.
- **Model gateway**: multi-model routing, provider abstraction, budgets, fallback, and policy.
- **Observability**: traces, evals, datasets, cost analytics, and debugging.
- **Deployment/compute**: serverless compute, GPU platforms, model serving, and runtime deployment.

## Featured Projects

| Project | Category | What it is | Best for |
| --- | --- | --- | --- |
| [LangGraph](https://www.langchain.com/langgraph) | Agent runtime | Stateful orchestration for long-running agents. | Durable agent workflows |
| [OpenAI Agents SDK](https://openai.github.io/openai-agents-python/) | Agent runtime | Compact primitives for agents, tools, and handoffs. | Small, opinionated agent stacks |
| [OpenHands](https://www.all-hands.dev/) | Agent runtime | Generalist software agents with sandboxed execution. | Software engineering agents |
| [E2B](https://e2b.dev/) | Execution sandbox | Cloud sandboxes for code-executing agents. | Agents that run code |
| [Browserbase](https://www.browserbase.com/) | Browser automation | Hosted browser infrastructure for agents. | Web automation agents |
| [browser-use](https://github.com/browser-use/browser-use) | Browser automation | Open-source browser agent framework. | Open-source browser agents |
| [Letta](https://www.letta.com/) | Memory/context | Stateful agents with long-term memory. | Persistent personal agents |
| [Model Context Protocol](https://modelcontextprotocol.io/) | Tool protocol | Standard protocol for tools and context. | Standardizing tool access |
| [LiteLLM](https://www.litellm.ai/) | Model gateway | OpenAI-compatible gateway across model providers. | Multi-provider model access |
| [Langfuse](https://langfuse.com/) | Observability | Open-source LLM observability and analytics. | Vendor-neutral observability |
| [Modal](https://modal.com/) | Deployment/compute | Serverless compute for AI jobs and services. | Burst workloads |
| [Fly.io](https://fly.io/) | Deployment/compute | Global app deployment close to users. | Regional agent backends |

## Full Landscape

The structured project list is maintained in [data/projects.json](data/projects.json).

Current coverage: **500 projects** across **10 infrastructure categories**.

## Agent Runtime

| Project | What it is | Best for |
| --- | --- | --- |
| [LangGraph](https://www.langchain.com/langgraph) | Stateful orchestration for long-running agents. | Durable agent workflows |
| [OpenAI Agents SDK](https://openai.github.io/openai-agents-python/) | Compact primitives for agents, tools, and handoffs. | Small, opinionated agent stacks |
| [AutoGen](https://microsoft.github.io/autogen/) | Multi-agent conversations and collaboration. | Collaborative agent systems |
| [CrewAI](https://www.crewai.com/) | Role-based crews and task delegation. | Business workflows and teams |
| [Semantic Kernel](https://learn.microsoft.com/semantic-kernel/) | Enterprise-friendly agent orchestration from Microsoft. | Microsoft-aligned agent apps |
| [LlamaIndex](https://www.llamaindex.ai/) | Data-aware agents and retrieval pipelines. | Knowledge-heavy assistants |
| [PydanticAI](https://ai.pydantic.dev/) | Typed agent building with Pydantic ergonomics. | Schema-first agent apps |
| [Agno](https://agno.com/) | A fast framework for building agent teams. | Developer-friendly agent apps |
| [OpenHands](https://www.all-hands.dev/) | Generalist software agents with sandboxed execution. | Software engineering agents |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) | Python and .NET framework for agents and multi-agent workflows. | Enterprise multi-agent workflows |
| [Mastra](https://mastra.ai/) | TypeScript framework for AI agents and workflows. | TypeScript agent apps |
| [VoltAgent](https://voltagent.dev/) | Open-source TypeScript platform for agent engineering. | Agent engineering in Node.js |
| [Open SWE](https://github.com/langchain-ai/open-swe) | Open-source asynchronous coding agent. | Internal coding agents |
| [smolagents](https://huggingface.co/docs/smolagents) | Lightweight library for agents that think in code. | Small code-first agents |
| [Flowise](https://flowiseai.com/) | Visual builder for AI agents and LLM workflows. | Visual agent workflow builders |
| [Haystack](https://haystack.deepset.ai/) | Modular framework for production LLM apps and agents. | Context-engineered agent apps |
| [Deep Agents](https://docs.langchain.com/deepagents) | Batteries-included agent harness from LangChain. | Longer-running task agents |
| [BeeAI Framework](https://framework.beeai.dev/) | Production-ready agents in Python and TypeScript. | Cross-language agent teams |
| [AutoGPT](https://agpt.co/) | Platform and tooling for autonomous AI agents. | Autonomous agent experiments |
| [CAMEL](https://www.camel-ai.org/) | Multi-agent framework for communicative AI systems. | Multi-agent simulations |
| [MetaGPT](https://github.com/FoundationAgents/MetaGPT) | Multi-agent framework for software-company style workflows. | Role-based software agents |
| [Open WebUI](https://openwebui.com/) | Extensible AI interface with tools, RAG, and model backends. | Self-hosted agent interfaces |
| [Claude Code](https://code.claude.com/docs/en/overview) | Agentic coding tool that lives in the terminal. | Codebase-aware terminal agents |
| [OpenAI Codex](https://github.com/openai/codex) | Lightweight coding agent that runs in the terminal. | Terminal coding workflows |
| [Gemini CLI](https://geminicli.com/) | Open-source Gemini-powered agent in the terminal. | Gemini terminal agents |
| [Vercel AI SDK](https://ai-sdk.dev/) | TypeScript toolkit for AI apps and agents. | Frontend-heavy agent apps |
| [Aider](https://aider.chat/) | AI pair programming agent in the terminal. | Terminal pair programming |
| [Cline](https://cline.bot/) | Open-source coding agent inside VS Code. | IDE coding automation |
| [Roo Code](https://roocode.com/) | Agentic coding assistant for VS Code. | Customizable coding agents |
| [OpenCode](https://opencode.ai/) | Terminal-based AI coding agent. | Terminal coding assistants |
| [Langflow](https://www.langflow.org/) | Visual framework for building agents and RAG apps. | Visual agent prototyping |
| [Rivet](https://rivet.ironcladapp.com/) | Visual programming environment for AI agents. | Graph-based agent design |
| [Botpress](https://botpress.com/) | Platform for building conversational AI agents. | Conversational business agents |
| [Rasa](https://rasa.com/) | Conversational AI framework and platform. | Controlled conversational agents |
| [Voiceflow](https://www.voiceflow.com/) | Collaborative platform for designing AI agents. | Agent design teams |
| [DSPy](https://dspy.ai/) | Programming model for optimizing LM pipelines. | Optimized LM programs |
| [Llama Stack](https://llama-stack.readthedocs.io/) | Standardized stack for building Llama-powered apps. | Llama-based agent stacks |
| [AgentScope](https://modelscope.github.io/agentscope/) | Multi-agent platform for building agent applications. | Distributed multi-agent apps |
| [Google ADK](https://google.github.io/adk-docs/) | Agent Development Kit for building AI agents. | Google-aligned agent apps |
| [Azure AI Foundry Agent Service](https://learn.microsoft.com/azure/ai-foundry/agents/) | Managed service for building and running agents. | Enterprise managed agents |
| [Amazon Bedrock Agents](https://aws.amazon.com/bedrock/agents/) | Managed agents for Amazon Bedrock. | AWS-native agent apps |
| [Dify](https://dify.ai/) | Open-source platform for agentic AI applications. | Visual production agent apps |
| [LangChain](https://www.langchain.com/) | Framework for building context-aware agent applications. | Composable agent applications |
| [AG2](https://docs.ag2.ai/) | Open-source framework for agentic systems. | AutoGen-style agent systems |
| [OpenDevin](https://github.com/OpenDevin/OpenDevin) | Open-source software engineering agent project. | Software agent research |
| [SWE-agent](https://swe-agent.com/) | Agent for fixing GitHub issues in codebases. | Issue-fixing agents |
| [OpenHands Resolver](https://github.com/All-Hands-AI/OpenHands) | OpenHands issue and software task automation. | Repo task automation |
| [PR-Agent](https://github.com/qodo-ai/pr-agent) | AI-powered pull request review and automation. | Pull request agents |
| [Sweep](https://github.com/sweepai/sweep) | AI junior developer for GitHub issues. | Issue-to-PR workflows |
| [Factory Droid](https://www.factory.ai/) | AI software engineering agents for development teams. | Team coding agents |
| [Replit Agent](https://replit.com/agent) | Cloud IDE agent for building apps from prompts. | Prompt-to-app workflows |
| [Windsurf](https://windsurf.com/) | Agentic IDE for software development. | Agentic IDE workflows |
| [Cursor](https://cursor.com/) | AI code editor with agentic development workflows. | AI-assisted coding |
| [Zed Agent Panel](https://zed.dev/agentic) | Agentic editing workflows in Zed. | Fast editor-based agents |
| [JetBrains AI Assistant](https://www.jetbrains.com/ai/) | AI coding assistant across JetBrains IDEs. | JetBrains developer workflows |
| [Sourcegraph Cody](https://sourcegraph.com/cody) | Code AI assistant with codebase context. | Large-codebase assistance |
| [Qodo](https://www.qodo.ai/) | AI agents for code quality and testing. | Code quality agents |
| [Tabnine](https://www.tabnine.com/) | AI coding assistant for development teams. | Enterprise code assistance |
| [Sourcegraph Amp](https://ampcode.com/) | Agentic coding tool from Sourcegraph. | Codebase-aware agents |
| [CodiumAI Cover-Agent](https://github.com/Codium-ai/cover-agent) | AI agent for generating test coverage. | Automated test generation |
| [Smol Developer](https://github.com/smol-ai/developer) | Small developer agent for generating apps. | Lightweight app generation |
| [Magentic-One](https://github.com/microsoft/autogen/tree/main/python/packages/autogen-magentic-one) | Generalist multi-agent system from Microsoft AutoGen. | Generalist multi-agent workflows |
| [OpenAI Swarm](https://github.com/openai/swarm) | Educational framework for multi-agent handoffs. | Handoff pattern learning |
| [Hugging Face Agents](https://huggingface.co/docs/transformers/transformers_agents) | Agent tooling in the Hugging Face ecosystem. | HF model tool use |
| [Griptape](https://www.griptape.ai/) | Framework for secure AI applications and agents. | Secure Python agent apps |
| [Superagent](https://github.com/homanp/superagent) | Open-source framework for production AI assistants. | Assistant backends |
| [Julep](https://www.julep.ai/) | Platform for stateful AI agents. | Stateful agent workflows |
| [Letta ADE](https://docs.letta.com/) | Agent development environment for stateful agents. | Memoryful agent development |
| [Dust](https://dust.tt/) | Platform for workplace AI agents. | Internal enterprise agents |
| [MindStudio](https://www.mindstudio.ai/) | Platform for building AI workers and automations. | Business AI workers |
| [Relevance AI](https://relevanceai.com/) | Platform for AI workforces and agent teams. | Operational AI teams |
| [Burr](https://burr.dagworks.io/) | State machine framework for AI applications. | Explicit-state agent apps |
| [StackBlitz Bolt](https://bolt.new/) | Browser-based AI app builder backed by WebContainers. | Instant app-building agents |
| [PraisonAI](https://praison.ai/) | Multi-agent framework and automation platform. | Practical multi-agent workflows |
| [KaibanJS](https://www.kaibanjs.com/) | JavaScript framework for multi-agent systems. | JS multi-agent teams |
| [Atomic Agents](https://github.com/BrainBlend-AI/atomic-agents) | Small composable Python agent framework. | Composable typed agents |
| [Agency Swarm](https://agency-swarm.ai/) | Framework for agent agencies and collaboration. | Role-based agent teams |
| [Langroid](https://langroid.github.io/langroid/) | Multi-agent LLM application framework. | Message-driven agents |
| [TaskWeaver](https://github.com/microsoft/TaskWeaver) | Code-first agent framework from Microsoft. | Code-first data agents |
| [PocketFlow](https://the-pocket.github.io/PocketFlow/) | Minimal framework for LLM workflows. | Tiny agent workflows |
| [SuperAGI](https://superagi.com/) | Open-source autonomous agent platform. | Autonomous task agents |
| [AgentGPT](https://github.com/reworkd/AgentGPT) | Browser-based autonomous agent project. | Autonomous agent experiments |
| [XAgent](https://github.com/OpenBMB/XAgent) | Open-source autonomous agent framework. | Research agent systems |
| [Voyager](https://github.com/MineDojo/Voyager) | Lifelong learning agent in Minecraft. | Skill-library agent research |
| [AgentVerse](https://github.com/OpenBMB/AgentVerse) | Framework for multi-agent collaboration and simulation. | Multi-agent simulations |

## Execution Sandbox

| Project | What it is | Best for |
| --- | --- | --- |
| [E2B](https://e2b.dev/) | Cloud sandboxes for code-executing agents. | Agents that run code |
| [Daytona](https://www.daytona.io/) | Dev environments for agentic workflows. | Agent coding environments |
| [Modal Sandboxes](https://modal.com/docs/guide/sandbox) | Ephemeral remote sandboxes on Modal. | Dynamic code execution |
| [KARS](https://github.com/Azure/kars) | Kubernetes agent reference stack with governed sandboxes. | Kubernetes-hosted agent runtimes |
| [Kubernetes Agent Sandbox](https://agent-sandbox.sigs.k8s.io/) | Kubernetes SIG project for isolated stateful agent workloads. | Isolated agent workloads on Kubernetes |
| [OpenSandbox](https://github.com/opensandbox-group/OpenSandbox) | Open sandbox platform with SDKs and network policy controls. | Sandboxed agent execution |
| [gVisor](https://gvisor.dev/) | Application kernel for container sandboxing. | Hardening containerized tools |
| [Firecracker](https://firecracker-microvm.github.io/) | Lightweight microVMs for secure multi-tenant workloads. | MicroVM-based sandboxes |
| [Kata Containers](https://katacontainers.io/) | Secure container runtime with lightweight VMs. | Secure container sandboxes |
| [Wasmtime](https://wasmtime.dev/) | Fast and secure WebAssembly runtime. | Wasm-based tool isolation |
| [Pyodide](https://pyodide.org/) | Python runtime compiled to WebAssembly. | In-browser Python execution |
| [Judge0](https://judge0.com/) | Online code execution system. | Multi-language code runners |
| [JupyterHub](https://jupyter.org/hub) | Multi-user notebook server. | Managed notebook sandboxes |
| [JupyterLab](https://jupyterlab.readthedocs.io/) | Interactive development environment for notebooks and code. | Interactive code execution |
| [Marimo](https://marimo.io/) | Reactive Python notebook for reproducible work. | Reproducible notebook apps |
| [nsjail](https://github.com/google/nsjail) | Process isolation tool for Linux. | Process-level tool isolation |
| [Bubblewrap](https://github.com/containers/bubblewrap) | Unprivileged Linux sandboxing tool. | Lightweight local sandboxes |
| [WASI](https://wasi.dev/) | Capability-oriented system interface for WebAssembly. | Portable Wasm tool runtimes |
| [Piston](https://github.com/engineer-man/piston) | Open-source code execution engine. | Language execution sandboxes |
| [Docker](https://www.docker.com/) | Container platform for packaging and running workloads. | Containerized tool execution |
| [Podman](https://podman.io/) | Daemonless container engine. | Rootless container sandboxes |
| [containerd](https://containerd.io/) | Core container runtime used by cloud platforms. | Low-level container execution |
| [runc](https://github.com/opencontainers/runc) | OCI container runtime implementation. | Container isolation primitives |
| [Firejail](https://firejail.wordpress.com/) | Linux sandboxing with namespaces and seccomp. | Process-level Linux sandboxing |
| [Flatpak](https://flatpak.org/) | Sandboxed Linux application runtime. | Desktop app isolation patterns |
| [Deno](https://deno.com/) | Secure JavaScript and TypeScript runtime. | Permissioned script execution |
| [Deno Subhosting](https://deno.com/subhosting) | Hosted runtime for user-provided JavaScript. | Multi-tenant code hosting |
| [workerd](https://github.com/cloudflare/workerd) | Open-source Workers runtime from Cloudflare. | Isolate-based serverless agents |
| [WasmEdge](https://wasmedge.org/) | Cloud-native WebAssembly runtime. | Portable plugin execution |
| [Spin](https://www.fermyon.com/spin) | Framework for WebAssembly serverless apps. | Wasm tool services |
| [Extism](https://extism.org/) | Universal WebAssembly plugin system. | Sandboxed tool plugins |
| [Lunatic](https://lunatic.solutions/) | Actor runtime built on WebAssembly. | Isolated actor workloads |
| [WebContainers](https://webcontainers.io/) | Node.js development environments in the browser. | In-browser dev sandboxes |
| [SWE-ReX](https://github.com/SWE-agent/SWE-ReX) | Remote execution service for coding agents. | Coding-agent execution backends |

## Browser Automation

| Project | What it is | Best for |
| --- | --- | --- |
| [Browserbase](https://www.browserbase.com/) | Hosted browser infrastructure for agents. | Web automation agents |
| [Browserless](https://www.browserless.io/) | Headless browser infrastructure at scale. | Large-scale browser work |
| [Playwright](https://playwright.dev/) | Reliable browser automation library. | Building browser tools |
| [Skyvern](https://www.skyvern.com/) | Browser tasks with AI-driven execution. | Task-oriented browser agents |
| [Stagehand](https://www.browserbase.com/stagehand) | Browser control with natural-language helpers. | Hybrid browser automation |
| [browser-use](https://github.com/browser-use/browser-use) | Open-source browser agent framework. | Open-source browser agents |
| [Steel Browser](https://steel.dev/) | Open-source browser API for AI agents. | Browser sessions for agents |
| [Hyperbrowser](https://www.hyperbrowser.ai/) | Browser infrastructure for AI agents and web automation. | Hosted browser workflows |
| [LaVague](https://docs.lavague.ai/) | Large Action Model framework for web agents. | AI web task automation |
| [BrowserGym](https://github.com/ServiceNow/BrowserGym) | Gym environment for web task automation. | Browser-agent evaluation |
| [Scrapybara](https://www.scrapybara.com/) | Browser and computer-use infrastructure for AI agents. | Computer-use agent sessions |
| [Crawlee](https://crawlee.dev/) | Web scraping and browser automation library. | Agent web data collection |
| [BrowserCat](https://www.browsercat.com/) | Browser automation API for developers. | Hosted browser actions |
| [Puppeteer](https://pptr.dev/) | Node.js browser automation library. | Chrome automation tools |
| [Selenium](https://www.selenium.dev/) | Cross-browser automation framework. | Cross-browser automation |
| [Browserless BQL](https://www.browserless.io/browserql) | Query language for browser automation. | Structured browser extraction |
| [BrowserStack Automate](https://www.browserstack.com/automate) | Cross-browser automation cloud. | Cross-browser agent tests |
| [Sauce Labs](https://saucelabs.com/) | Cloud testing and browser automation platform. | Agent browser QA |
| [QA Wolf](https://www.qawolf.com/) | End-to-end browser testing platform. | Web workflow validation |
| [LambdaTest](https://www.lambdatest.com/) | Cloud platform for browser and app testing. | Cross-environment browser tests |
| [Cloudflare Browser Rendering](https://developers.cloudflare.com/browser-rendering/) | Browser rendering API on Cloudflare Workers. | Edge browser rendering |
| [Fetchfox](https://fetchfox.ai/) | AI-powered web scraping and extraction. | Structured web extraction |
| [Anchor Browser](https://anchorbrowser.io/) | Browser automation platform for AI agents. | Hosted browser agents |
| [Oxylabs Web Unblocker](https://oxylabs.io/products/web-unblocker) | Web access API for difficult sites. | Reliable web data access |
| [Bright Data Scraping Browser](https://brightdata.com/products/scraping-browser) | Hosted browser for scraping and automation. | Scraping browser workloads |
| [Zyte API](https://www.zyte.com/zyte-api/) | Web scraping API with browser rendering. | Structured web extraction |
| [ScrapingBee](https://www.scrapingbee.com/) | API for headless browsers and scraping. | Browser-backed scraping APIs |
| [Selenium Grid](https://www.selenium.dev/documentation/grid/) | Distributed browser automation grid. | Scaled browser sessions |
| [Camoufox](https://github.com/daijro/camoufox) | Fingerprint-resistant Firefox automation. | Stealth browser automation |
| [rebrowser-patches](https://github.com/rebrowser/rebrowser-patches) | Patches for bot-detection-resistant browsers. | Lower-fingerprint automation |
| [Patchright](https://github.com/Kaliiiiiiiiii-Vinyzu/patchright) | Playwright fork focused on stealth automation. | Stealth Playwright workloads |
| [Nodriver](https://github.com/ultrafunkamsterdam/nodriver) | Async browser automation without WebDriver. | CDP browser control |
| [SeleniumBase](https://seleniumbase.io/) | Python framework for browser automation. | Python browser workflows |

## Tool Protocol

| Project | What it is | Best for |
| --- | --- | --- |
| [Model Context Protocol](https://modelcontextprotocol.io/) | Standard protocol for tools and context. | Standardizing tool access |
| [Smithery](https://smithery.ai/) | Discovery and hosting for MCP servers. | Finding MCP servers |
| [MCP Servers](https://github.com/modelcontextprotocol/servers) | Reference and community servers for Model Context Protocol. | Finding agent tool integrations |
| [Arcade MCP](https://docs.arcade.dev/) | MCP framework and gateway for custom agent tools. | Custom agent tool capabilities |
| [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) | Official TypeScript SDK for Model Context Protocol. | TypeScript MCP integrations |
| [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) | Official Python SDK for Model Context Protocol. | Python MCP integrations |
| [FastMCP](https://gofastmcp.com/) | Pythonic framework for MCP servers and clients. | Fast MCP server development |
| [ACI.dev](https://www.aci.dev/) | Open-source tool-calling platform for agents. | Large tool catalogs for agents |
| [Context7](https://context7.com/) | Up-to-date code documentation for LLMs and coding agents. | Fresh documentation context |
| [MCP Inspector](https://github.com/modelcontextprotocol/inspector) | Developer tool for testing MCP servers. | Debugging MCP servers |
| [MCP CLI](https://github.com/wong2/mcp-cli) | Command-line client for Model Context Protocol. | MCP server testing |
| [Supergateway](https://github.com/supercorp-ai/supergateway) | Gateway for MCP over SSE and stdio transports. | MCP transport bridging |
| [mcp-proxy](https://github.com/sparfenyuk/mcp-proxy) | Proxy for MCP servers and transports. | MCP connectivity |
| [Docker MCP Toolkit](https://www.docker.com/products/mcp-catalog-and-toolkit/) | Docker tooling for discovering and running MCP servers. | Containerized MCP servers |
| [Docker MCP Catalog](https://hub.docker.com/mcp) | Catalog of containerized MCP servers. | MCP server discovery |
| [MCP.so](https://mcp.so/) | Directory of MCP servers and clients. | MCP ecosystem discovery |
| [Glama MCP](https://glama.ai/mcp) | MCP server directory and discovery platform. | Finding MCP integrations |
| [PulseMCP](https://www.pulsemcp.com/) | MCP server discovery and ecosystem tracking. | Tracking MCP projects |
| [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) | Curated list of MCP servers. | MCP server research |
| [MCPHub](https://github.com/Jeamee/MCPHub-Desktop) | Desktop manager for MCP servers. | Local MCP management |
| [Composio MCP](https://mcp.composio.dev/) | MCP access to Composio toolkits. | MCP SaaS tools |
| [Browserbase MCP Server](https://github.com/browserbase/mcp-server-browserbase) | MCP server for Browserbase browser automation. | MCP browser control |
| [GitHub MCP Server](https://github.com/github/github-mcp-server) | Official GitHub MCP server. | GitHub agent workflows |
| [Postgres MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) | MCP server for PostgreSQL access. | Database-aware agents |
| [Filesystem MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) | MCP server for filesystem access. | Local file tools |
| [Playwright MCP Server](https://github.com/microsoft/playwright-mcp) | MCP server for browser automation with Playwright. | Browser tools over MCP |
| [Puppeteer MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) | MCP server for Puppeteer browser automation. | MCP web automation |
| [Brave Search MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) | MCP server for Brave Search. | Search tools for agents |
| [Slack MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) | MCP server for Slack workspaces. | Workspace agents |
| [Google Drive MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) | MCP server for Google Drive. | Document-aware agents |
| [Memory MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) | Reference MCP server for persistent memory. | Simple MCP memory |
| [Mintlify Docs MCP](https://mintlify.com/) | Documentation platform with AI and agent-facing docs workflows. | Agent-readable documentation |
| [Scalar](https://scalar.com/) | OpenAPI documentation and API client platform. | API tool documentation |
| [Speakeasy](https://www.speakeasy.com/) | SDK and API tooling for OpenAPI-based products. | API-to-tool surfaces |
| [Stainless](https://www.stainless.com/) | SDK generation for API companies. | Typed API clients |
| [OpenAPI Specification](https://www.openapis.org/) | Standard specification for describing HTTP APIs. | API-to-tool contracts |
| [AsyncAPI](https://www.asyncapi.com/) | Specification for event-driven APIs. | Event-driven tool contracts |
| [GraphQL](https://graphql.org/) | Query language and runtime for APIs. | Typed data access tools |
| [tRPC](https://trpc.io/) | End-to-end typesafe APIs for TypeScript. | Typed agent tool APIs |
| [Zod](https://zod.dev/) | TypeScript schema validation library. | Tool argument schemas |
| [Pydantic](https://docs.pydantic.dev/) | Python data validation with type hints. | Typed Python tool schemas |
| [JSON Schema](https://json-schema.org/) | Standard for describing JSON data shapes. | Portable tool schemas |
| [Avro](https://avro.apache.org/) | Data serialization system with schemas. | Typed event data |
| [Protocol Buffers](https://protobuf.dev/) | Language-neutral data serialization format. | Typed service contracts |
| [gRPC](https://grpc.io/) | High-performance RPC framework. | Typed service tools |
| [Kiota](https://github.com/microsoft/kiota) | OpenAPI-based API client generator. | Typed API tool clients |
| [Fern](https://buildwithfern.com/) | API definition and SDK generation platform. | Agent-ready API surfaces |
| [Bump.sh](https://bump.sh/) | API documentation and contract platform. | API contract publishing |
| [Stoplight](https://stoplight.io/) | API design and documentation platform. | Governed API tools |
| [Redocly](https://redocly.com/) | API documentation and governance tooling. | Tool API documentation |
| [Apidog](https://apidog.com/) | Collaborative API development platform. | API tool lifecycle |
| [Bruno](https://www.usebruno.com/) | Open-source API client stored in Git. | Git-native API collections |
| [Insomnia](https://insomnia.rest/) | API client and design platform. | Testing tool APIs |
| [Postman](https://www.postman.com/) | API collaboration and testing platform. | API tool collaboration |

## App Integrations

| Project | What it is | Best for |
| --- | --- | --- |
| [Composio](https://composio.dev/) | Managed app integrations and actions for agents. | Agents using SaaS tools |
| [Nango](https://www.nango.dev/) | OAuth and API integrations for agent workflows. | Reliable app connections |
| [Pipedream](https://pipedream.com/) | Connect APIs and run event-driven workflows. | Workflow-backed tools |
| [Inngest](https://www.inngest.com/) | Durable functions and workflows. | Reliable agent jobs |
| [Trigger.dev](https://trigger.dev/) | Background jobs for AI and web apps. | Async agent operations |
| [Continue](https://www.continue.dev/) | Open-source AI code assistant platform. | IDE-integrated coding agents |
| [n8n](https://n8n.io/) | Workflow automation platform with AI and agent workflows. | Visual agent automations |
| [Activepieces](https://www.activepieces.com/) | Open-source automation platform for AI workflows. | Open-source app automations |
| [Zapier AI Actions](https://actions.zapier.com/) | Zapier actions exposed to AI agents. | Broad SaaS action access |
| [Make](https://www.make.com/) | Visual automation platform for connecting apps and APIs. | No-code app workflows |
| [Pica](https://www.picaos.com/) | Tool and integration layer for AI agents. | Agent tool integrations |
| [Merge](https://www.merge.dev/) | Unified APIs for business software integrations. | Enterprise SaaS connectors |
| [Apify](https://apify.com/) | Cloud platform for web scraping and automation actors. | Web data tools for agents |
| [Firecrawl](https://www.firecrawl.dev/) | API for turning websites into agent-ready data. | Website ingestion for agents |
| [Tavily](https://www.tavily.com/) | Search API built for AI agents. | Agent web research |
| [Exa](https://exa.ai/) | Neural search API for AI applications. | Semantic web search |
| [Jina AI Reader](https://jina.ai/reader/) | Reader API for web pages and documents. | Clean web context extraction |
| [Brave Search API](https://brave.com/search/api/) | Independent search API for AI applications. | Web search tools |
| [SerpAPI](https://serpapi.com/) | Search engine results API. | SERP-backed agents |
| [Mendable](https://www.mendable.ai/) | AI search and chat over product documentation. | Docs-backed assistants |
| [Kapa.ai](https://www.kapa.ai/) | AI support and documentation assistant platform. | Developer support agents |
| [ReadMe](https://readme.com/) | Developer hub for APIs and documentation. | API docs for agents |
| [Toolhouse](https://toolhouse.ai/) | Tool infrastructure for AI agents. | Hosted agent tools |
| [Klavis AI](https://www.klavis.ai/) | MCP and API integrations for AI agents. | Agent SaaS connectors |
| [ToolJet](https://www.tooljet.com/) | Open-source internal app platform. | Agent-facing internal tools |
| [Appsmith](https://www.appsmith.com/) | Open-source platform for internal applications. | Internal app control surfaces |
| [Retool Workflows](https://retool.com/products/workflows) | Automation workflows for internal operations. | Operational agent actions |
| [Workato](https://www.workato.com/) | Enterprise integration and automation platform. | Enterprise SaaS actions |
| [Paragon](https://www.useparagon.com/) | Embedded integration platform for SaaS products. | Customer app integrations |
| [Alloy Automation](https://www.runalloy.com/) | Embedded iPaaS and commerce automation. | Embedded SaaS workflows |
| [Prismatic](https://prismatic.io/) | Embedded integration platform for B2B SaaS. | B2B integration marketplaces |
| [OAuth2 Proxy](https://oauth2-proxy.github.io/oauth2-proxy/) | Reverse proxy for OAuth authentication. | Protected agent tools |
| [WorkOS](https://workos.com/) | Enterprise auth and identity APIs. | Enterprise-ready agent apps |
| [Stytch](https://stytch.com/) | Authentication and fraud prevention platform. | Secure user access |
| [Clerk](https://clerk.com/) | Authentication and user management for apps. | Agent app identity |
| [Auth0 Actions](https://auth0.com/actions) | Extensible identity workflows in Auth0. | Auth-time integration logic |

## Memory Context

| Project | What it is | Best for |
| --- | --- | --- |
| [Letta](https://www.letta.com/) | Stateful agents with long-term memory. | Persistent personal agents |
| [Mem0](https://mem0.ai/) | Universal memory layer for agents. | Cross-session memory |
| [Zep](https://www.getzep.com/) | Memory infrastructure for agent applications. | Conversation history |
| [Supermemory](https://supermemory.ai/) | Personal and app memory for AI products. | Personalized agents |
| [Pinecone](https://www.pinecone.io/) | Vector database widely used for agent memory. | Scalable embedding memory |
| [Qdrant](https://qdrant.tech/) | Open-source vector database for memory and retrieval. | Self-hosted memory stores |
| [Graphiti](https://github.com/getzep/graphiti) | Temporal knowledge graph memory for agents. | Graph memory for agents |
| [Chroma](https://www.trychroma.com/) | Open-source embedding database for AI applications. | Local-first vector memory |
| [Weaviate](https://weaviate.io/) | Open-source vector database for AI-native apps. | Production vector retrieval |
| [Milvus](https://milvus.io/) | Open-source vector database built for scale. | Large-scale vector search |
| [LanceDB](https://lancedb.com/) | Developer-friendly multimodal vector database. | Multimodal retrieval |
| [Cognee](https://www.cognee.ai/) | Memory and knowledge graph layer for AI agents. | Structured agent memory |
| [Supabase Vector](https://supabase.com/vector) | Postgres-backed vector storage for AI apps. | Postgres-native vector memory |
| [pgvector](https://github.com/pgvector/pgvector) | Vector similarity search for Postgres. | Embedding search in Postgres |
| [Elasticsearch](https://www.elastic.co/elasticsearch) | Search and vector database for retrieval systems. | Hybrid search memory |
| [OpenSearch](https://opensearch.org/) | Open-source search and analytics engine. | Open-source hybrid retrieval |
| [Memgraph](https://memgraph.com/) | Streaming graph database for connected data. | Graph-based context |
| [FalkorDB](https://www.falkordb.com/) | Graph database for knowledge and retrieval systems. | GraphRAG memory |
| [Astra DB](https://www.datastax.com/products/datastax-astra) | Serverless vector database built on Cassandra. | Managed vector memory |
| [MongoDB Atlas Vector Search](https://www.mongodb.com/products/platform/atlas-vector-search) | Vector search inside MongoDB Atlas. | Operational data plus memory |
| [SingleStore Kai](https://www.singlestore.com/) | Real-time database for AI applications. | Realtime AI data systems |
| [Turso](https://turso.tech/) | Edge SQLite platform for local-first apps. | Edge agent state |
| [Neon](https://neon.tech/) | Serverless Postgres for modern applications. | Serverless Postgres memory |
| [Tigris](https://www.tigrisdata.com/) | Object storage for AI and app data. | Agent file and artifact storage |
| [Unstructured](https://unstructured.io/) | Document parsing and ingestion for AI systems. | Document ingestion pipelines |
| [LlamaParse](https://www.llamaindex.ai/llamaparse) | Document parser for RAG and agent workflows. | PDF and document parsing |
| [Docling](https://github.com/docling-project/docling) | Document conversion for AI pipelines. | Open-source document parsing |
| [Marker](https://github.com/datalab-to/marker) | Convert PDFs and documents to markdown. | Markdown document ingestion |
| [MinerU](https://github.com/opendatalab/MinerU) | Document extraction toolkit for PDFs and papers. | Scientific document ingestion |
| [Apache Tika](https://tika.apache.org/) | Content detection and extraction toolkit. | Broad file ingestion |
| [Meilisearch](https://www.meilisearch.com/) | Fast open-source search engine. | Fast app search |
| [Typesense](https://typesense.org/) | Open-source typo-tolerant search engine. | Developer-friendly search |
| [Vespa](https://vespa.ai/) | Search and recommendation engine for AI applications. | Large-scale retrieval serving |
| [Jina Embeddings](https://jina.ai/embeddings/) | Embedding models and APIs for retrieval systems. | Semantic context embeddings |
| [Cohere Embed](https://cohere.com/embed) | Embedding models for enterprise search and RAG. | Enterprise retrieval embeddings |
| [Voyage AI](https://www.voyageai.com/) | Embedding and reranking models for retrieval. | High-quality retrieval models |
| [Cohere Rerank](https://cohere.com/rerank) | Reranking API for retrieval pipelines. | Context reranking |
| [ColBERT](https://github.com/stanford-futuredata/ColBERT) | Efficient late-interaction retrieval model. | Neural retrieval research |
| [Neo4j](https://neo4j.com/) | Graph database for connected data. | Graph-based agent memory |
| [TigerGraph](https://www.tigergraph.com/) | Scalable graph analytics database. | Large graph context stores |
| [Kuzu](https://kuzudb.com/) | Embedded graph database. | Embedded graph memory |
| [DuckDB](https://duckdb.org/) | In-process analytical database. | Local analytical context |
| [MotherDuck](https://motherduck.com/) | Serverless DuckDB analytics platform. | Cloud analytical context |
| [ClickHouse](https://clickhouse.com/) | High-performance columnar database. | High-volume context analytics |
| [pgvectorscale](https://github.com/timescale/pgvectorscale) | Scalable vector search for PostgreSQL. | Postgres vector memory |
| [MyScale](https://myscale.com/) | SQL vector database built on ClickHouse. | SQL-native vector search |
| [Infinity](https://infiniflow.org/) | Search engine for hybrid retrieval. | Hybrid retrieval memory |
| [R2R](https://r2r-docs.sciphi.ai/) | Open-source RAG engine and retrieval platform. | Production RAG backends |
| [txtai](https://neuml.github.io/txtai/) | Embeddings database and semantic workflows. | Local semantic memory |

## Safety Evals

| Project | What it is | Best for |
| --- | --- | --- |
| [Lakera](https://www.lakera.ai/) | Prompt-injection and AI security defenses. | Production safety filters |
| [Guardrails AI](https://www.guardrailsai.com/) | Validation, railings, and output constraints. | Output validation |
| [Promptfoo](https://www.promptfoo.dev/) | Eval and red-teaming for prompt and agent safety. | Prompt and agent QA |
| [Giskard](https://www.giskard.ai/) | LLM testing and red-teaming platform. | Safety reviews and audits |
| [Agent Governance Toolkit](https://github.com/microsoft/agent-governance-toolkit) | Governance and zero-trust controls for autonomous agents. | Agent security governance |
| [Ragas](https://www.ragas.io/) | Evaluation framework for LLM and RAG applications. | RAG and agent evals |
| [DeepEval](https://deepeval.com/) | LLM evaluation framework for testing AI apps. | LLM test suites |
| [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) | Programmable guardrails for LLM applications. | Programmable safety controls |
| [Garak](https://github.com/NVIDIA/garak) | LLM vulnerability scanner. | LLM security probing |
| [Inspect AI](https://inspect.aisi.org.uk/) | Framework for large language model evaluations. | Structured safety evaluations |
| [OpenAI Evals](https://github.com/openai/evals) | Framework for evaluating language models and systems. | Custom eval definitions |
| [TruLens](https://www.trulens.org/) | Evaluation and tracking for LLM applications. | Feedback-driven app evaluation |
| [Llama Guard](https://www.llama.com/docs/model-cards-and-prompt-formats/llama-guard-3/) | Safety classifier family for LLM inputs and outputs. | Policy-based content safety |
| [Purple Llama](https://github.com/meta-llama/PurpleLlama) | Open trust and safety tools for generative AI. | GenAI safety tooling |
| [LlamaFirewall](https://github.com/meta-llama/PurpleLlama/tree/main/LlamaFirewall) | Security-focused firewall for agentic AI systems. | Agent security filtering |
| [LLM Guard](https://llm-guard.com/) | Security toolkit for LLM inputs and outputs. | Input/output scanning |
| [Rebuff](https://github.com/protectai/rebuff) | Prompt-injection detection for LLM applications. | Prompt-injection defense |
| [OpenCompass](https://opencompass.org.cn/) | Open evaluation platform for foundation models. | Model benchmark evaluation |
| [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) | Framework for evaluating language models. | Language model benchmarking |
| [HELM](https://crfm.stanford.edu/helm/) | Holistic evaluation of language models. | Holistic model evaluation |
| [Safety Gymnasium](https://github.com/PKU-Alignment/safety-gymnasium) | Benchmark suite for safe reinforcement learning. | Safe agent research |
| [AgentBench](https://github.com/THUDM/AgentBench) | Benchmark for evaluating LLM agents. | LLM agent benchmarking |
| [WebArena](https://webarena.dev/) | Benchmark for autonomous web agents. | Web-agent evaluation |
| [MiniWoB++](https://github.com/Farama-Foundation/miniwob-plusplus) | Benchmark environments for web interaction. | Web interaction benchmarks |
| [WorkArena](https://github.com/ServiceNow/WorkArena) | Benchmark for enterprise web agents. | Enterprise web-agent evals |
| [SWE-bench](https://www.swebench.com/) | Benchmark for software engineering agents. | Software agent evaluation |
| [Aider Polyglot Benchmark](https://aider.chat/docs/leaderboards/) | Benchmark for coding model editing ability. | Coding model comparisons |
| [Tau-bench](https://github.com/sierra-research/tau-bench) | Benchmark for tool-agent user interactions. | Tool-agent evaluation |
| [BFCL](https://gorilla.cs.berkeley.edu/leaderboard.html) | Berkeley function-calling leaderboard. | Tool-calling evaluation |
| [ToolBench](https://github.com/OpenBMB/ToolBench) | Benchmark for tool-learning language models. | Tool-use research |
| [WebShop](https://webshop-pnlp.github.io/) | Benchmark for web shopping agents. | Ecommerce task agents |
| [BrowserArena](https://browserarena.github.io/) | Benchmarking environment for browser agents. | Browser-agent comparison |
| [LlamaIndex Evals](https://docs.llamaindex.ai/en/stable/module_guides/evaluating/) | Evaluation tools for LlamaIndex applications. | RAG pipeline evaluation |
| [Azure AI Evaluation SDK](https://learn.microsoft.com/azure/ai-foundry/how-to/develop/evaluate-sdk) | Evaluation SDK for Azure AI applications. | Enterprise AI evaluation |
| [PyRIT](https://github.com/Azure/PyRIT) | Python Risk Identification Tool for generative AI. | Automated AI red teaming |
| [Counterfit](https://github.com/Azure/counterfit) | Security testing tool for AI systems. | AI attack simulation |
| [CyberSecEval](https://github.com/meta-llama/PurpleLlama/tree/main/CybersecurityBenchmarks) | Cybersecurity evaluation benchmarks for LLMs. | Cyber safety evaluation |
| [LLMFuzzer](https://github.com/mnns/LLMFuzzer) | Fuzzing framework for LLM prompts. | Prompt robustness testing |
| [AgentDojo](https://github.com/ethz-spylab/agentdojo) | Benchmark for prompt-injection attacks on agents. | Agent security benchmarks |
| [AgentHarm](https://huggingface.co/ai-safety-institute/AgentHarm) | Benchmark for harmful agentic behavior. | Harmful task evaluation |
| [HarmBench](https://github.com/centerforaisafety/HarmBench) | Standardized benchmark for automated red teaming. | Harm robustness testing |
| [JailbreakBench](https://jailbreakbench.github.io/) | Benchmark for jailbreak attacks and defenses. | Jailbreak evaluation |
| [PromptBench](https://github.com/microsoft/promptbench) | Benchmarking toolkit for prompt robustness. | Prompt evaluation suites |
| [Robust Intelligence AI Firewall](https://www.robustintelligence.com/) | Runtime protection for AI applications. | Runtime AI protection |
| [Protect AI Guardian](https://protectai.com/) | Security platform for AI and ML systems. | AI security operations |

## Model Gateway

| Project | What it is | Best for |
| --- | --- | --- |
| [LiteLLM](https://www.litellm.ai/) | OpenAI-compatible gateway across model providers. | Multi-provider model access |
| [OpenRouter](https://openrouter.ai/) | Unified API for many model providers. | Broad model choice |
| [Vercel AI Gateway](https://vercel.com/ai-gateway) | Managed gateway for model routing and observability. | Frontend-heavy AI apps |
| [Portkey](https://portkey.ai/) | AI gateway with guardrails and policy controls. | Controlled production access |
| [vLLM](https://www.vllm.ai/) | High-throughput serving engine for LLMs. | Self-hosted LLM serving |
| [SGLang](https://www.sglang.ai/) | Serving framework for fast language model programs. | Fast agent model serving |
| [Text Generation Inference](https://huggingface.co/docs/text-generation-inference) | Hugging Face server for text-generation models. | Open model serving |
| [Ollama](https://ollama.com/) | Run open models locally. | Local model backends |
| [LM Studio](https://lmstudio.ai/) | Local LLM runtime and developer API. | Local agent prototyping |
| [TensorZero](https://www.tensorzero.com/) | Open-source stack for production LLM applications. | Model optimization loops |
| [Fireworks AI](https://fireworks.ai/) | Fast inference platform for open models. | Low-latency hosted inference |
| [GroqCloud](https://groq.com/) | Fast inference API for LLM applications. | Realtime agent responses |
| [NVIDIA Triton Inference Server](https://developer.nvidia.com/triton-inference-server) | Inference serving for AI models. | High-performance model serving |
| [Requesty](https://www.requesty.ai/) | AI gateway for routing and optimizing LLM requests. | Provider routing operations |
| [OpenPipe](https://openpipe.ai/) | Fine-tuning and optimization platform for LLM apps. | Fine-tuned agent models |
| [Together AI](https://www.together.ai/) | Cloud platform for open model inference and fine-tuning. | Hosted open model APIs |
| [DeepInfra](https://deepinfra.com/) | Serverless inference for open models. | Cost-effective model APIs |
| [Mistral La Plateforme](https://mistral.ai/products/la-plateforme) | Mistral AI developer platform for model APIs. | Mistral model access |
| [Perplexity Sonar](https://docs.perplexity.ai/) | Search-grounded model API. | Search-grounded agents |
| [OctoAI](https://octo.ai/) | Inference platform for generative AI applications. | Open model inference |
| [Lepton AI](https://www.lepton.ai/) | Platform for building and running AI applications. | Hosted AI endpoints |
| [Predibase](https://predibase.com/) | Fine-tuning and serving platform for open models. | Fine-tuned model APIs |
| [Cerebras Inference](https://www.cerebras.ai/inference) | Fast inference API for large models. | Fast model responses |
| [SambaNova Cloud](https://sambanova.ai/) | AI cloud platform for enterprise models. | Enterprise model APIs |
| [Cohere API](https://cohere.com/) | Model API for enterprise AI applications. | Enterprise model access |
| [Anthropic API](https://docs.anthropic.com/) | Claude model API for AI applications and agents. | Claude agent backends |
| [OpenAI Responses API](https://platform.openai.com/docs/api-reference/responses) | Unified API for model responses and tools. | OpenAI tool-using agents |
| [Google Gemini API](https://ai.google.dev/) | Google model API for multimodal AI applications. | Gemini agent backends |
| [Azure OpenAI Service](https://azure.microsoft.com/products/ai-services/openai-service) | Azure-hosted OpenAI models for enterprise apps. | Enterprise OpenAI deployments |
| [Amazon Bedrock](https://aws.amazon.com/bedrock/) | Managed foundation model platform on AWS. | AWS model access |
| [Vertex AI Generative AI](https://cloud.google.com/vertex-ai/generative-ai) | Google Cloud platform for generative AI models. | GCP model access |
| [Databricks Mosaic AI Model Serving](https://www.databricks.com/product/model-serving) | Model serving for enterprise data platforms. | Data-platform model serving |
| [Snowflake Cortex AI](https://www.snowflake.com/en/data-cloud/cortex/) | AI and LLM functions inside Snowflake. | Data-warehouse grounded agents |
| [Lamini](https://www.lamini.ai/) | Enterprise platform for training and deploying LLMs. | Enterprise tuned models |
| [Axolotl](https://github.com/axolotl-ai-cloud/axolotl) | Open-source LLM fine-tuning framework. | Open model fine-tuning |
| [Unsloth](https://unsloth.ai/) | Fast fine-tuning for open language models. | Efficient model adaptation |
| [Ludwig](https://ludwig.ai/) | Low-code deep learning and LLM fine-tuning framework. | Declarative model training |

## Observability

| Project | What it is | Best for |
| --- | --- | --- |
| [LangSmith](https://www.langchain.com/langsmith) | Tracing, evals, and debugging for LLM apps. | LangChain-based stacks |
| [Langfuse](https://langfuse.com/) | Open-source LLM observability and analytics. | Vendor-neutral observability |
| [Arize Phoenix](https://phoenix.arize.com/) | Open-source tracing and evaluation. | Local-first analysis |
| [Helicone](https://www.helicone.ai/) | LLM request logging and cost analytics. | Spend and latency tracking |
| [Braintrust](https://www.braintrust.dev/) | Eval platform for model and agent quality. | Quality workflows |
| [AgentOps](https://agentops.ai/) | Monitoring and analytics for AI agents. | Agent run monitoring |
| [Weave](https://wandb.me/weave) | Toolkit for developing and evaluating AI applications. | AI app development loops |
| [Langtrace](https://langtrace.ai/) | OpenTelemetry-based tracing for LLM applications. | OpenTelemetry LLM traces |
| [LangWatch](https://langwatch.ai/) | LLM evaluations and AI agent testing platform. | Agent quality testing |
| [OpenLIT](https://docs.openlit.io/) | OpenTelemetry-native observability for AI engineering. | Unified AI observability |
| [OpenLLMetry](https://www.traceloop.com/openllmetry) | OpenTelemetry instrumentation for LLM apps. | Instrumenting LLM stacks |
| [Humanloop](https://humanloop.com/) | Prompt management and evaluation platform. | Prompt and eval workflows |
| [PromptLayer](https://www.promptlayer.com/) | Prompt management and LLM observability platform. | Prompt operations |
| [Galileo](https://www.galileo.ai/) | Evaluation and observability for AI systems. | AI quality monitoring |
| [WhyLabs](https://whylabs.ai/) | AI observability and monitoring platform. | Production AI monitoring |
| [Fiddler AI](https://www.fiddler.ai/) | AI observability and model monitoring platform. | Enterprise AI monitoring |
| [MLflow](https://mlflow.org/) | Open-source platform for ML and GenAI lifecycle. | AI lifecycle tracking |
| [Evidently AI](https://www.evidentlyai.com/) | Open-source evaluation and monitoring for AI systems. | AI quality reports |
| [OpenInference](https://github.com/Arize-ai/openinference) | OpenTelemetry semantic conventions for AI traces. | Portable agent traces |
| [Parea](https://www.parea.ai/) | Evaluation and observability platform for LLM applications. | LLM experiment and eval loops |
| [OpenTelemetry](https://opentelemetry.io/) | Open standard for traces, metrics, and logs. | Portable telemetry |
| [Prometheus](https://prometheus.io/) | Monitoring and alerting toolkit. | Infrastructure metrics |
| [Grafana](https://grafana.com/) | Visualization and observability platform. | Agent ops dashboards |
| [Loki](https://grafana.com/oss/loki/) | Log aggregation system from Grafana. | Agent runtime logs |
| [Tempo](https://grafana.com/oss/tempo/) | Distributed tracing backend. | Trace storage |
| [Jaeger](https://www.jaegertracing.io/) | Distributed tracing platform. | Distributed agent traces |
| [Sentry](https://sentry.io/) | Application error and performance monitoring. | Agent error monitoring |
| [Datadog LLM Observability](https://www.datadoghq.com/product/llm-observability/) | LLM observability inside Datadog. | Enterprise LLM monitoring |
| [New Relic AI Monitoring](https://newrelic.com/platform/ai-monitoring) | AI application monitoring on New Relic. | APM for AI apps |
| [Honeycomb](https://www.honeycomb.io/) | Observability for complex production systems. | Debugging agent services |
| [OpenCost](https://www.opencost.io/) | Open-source Kubernetes cost monitoring. | Agent infrastructure cost tracking |
| [Kubecost](https://www.kubecost.com/) | Kubernetes cost monitoring platform. | Cluster cost visibility |
| [OpenPanel](https://openpanel.dev/) | Open-source product analytics platform. | Product usage analytics |
| [PostHog](https://posthog.com/) | Open-source product analytics suite. | Agent product telemetry |
| [SigNoz](https://signoz.io/) | Open-source observability platform. | Self-hosted observability |
| [Coroot](https://coroot.com/) | Open-source observability for microservices. | Service health debugging |
| [VictoriaMetrics](https://victoriametrics.com/) | Scalable time-series database and monitoring stack. | High-volume metrics |
| [Grafana Alloy](https://grafana.com/docs/alloy/latest/) | OpenTelemetry collector distribution from Grafana. | Telemetry pipelines |
| [Vector](https://vector.dev/) | Observability data pipeline. | Telemetry routing |
| [Fluent Bit](https://fluentbit.io/) | Lightweight telemetry collector. | Lightweight log collection |
| [OpenObserve](https://openobserve.ai/) | Open-source observability and log search platform. | Unified observability storage |
| [HyperDX](https://www.hyperdx.io/) | Open-source observability for logs, traces, metrics, and sessions. | End-to-end debugging |
| [Middleware](https://middleware.io/) | Full-stack observability platform. | Full-stack monitoring |
| [Baselime](https://baselime.io/) | Serverless observability platform. | Serverless agent observability |
| [Highlight.io](https://www.highlight.io/) | Open-source monitoring with session replay. | User-facing agent debugging |

## Deployment Compute

| Project | What it is | Best for |
| --- | --- | --- |
| [Modal](https://modal.com/) | Serverless compute for AI jobs and services. | Burst workloads |
| [Fly.io](https://fly.io/) | Global app deployment close to users. | Regional agent backends |
| [Baseten](https://www.baseten.co/) | Model serving and AI deployment infrastructure. | Hosted inference |
| [Replicate](https://replicate.com/) | Run models and AI workflows via API. | Quick model deployment |
| [RunPod](https://www.runpod.io/) | GPU cloud for model and agent workloads. | GPU-heavy tasks |
| [BentoML](https://www.bentoml.com/) | Model serving and inference deployment tooling. | Self-managed model services |
| [Cloudflare Agents](https://developers.cloudflare.com/agents/) | Build and deploy AI agents on Cloudflare. | Edge-hosted agents |
| [LlamaDeploy](https://docs.llamaindex.ai/en/stable/module_guides/llama_deploy/) | Production deployment for LlamaIndex agentic workflows. | Deploying LlamaIndex workflows |
| [Flyte](https://flyte.org/) | Workflow orchestration for data and ML systems. | Reliable AI pipelines |
| [Beam](https://www.beam.cloud/) | Serverless compute for AI workloads. | Serverless agent tasks |
| [Cerebrium](https://www.cerebrium.ai/) | Serverless infrastructure for AI applications. | Low-latency AI services |
| [Cog](https://github.com/replicate/cog) | Container packaging for machine learning models. | Reproducible model services |
| [Temporal](https://temporal.io/) | Durable execution platform for long-running workflows. | Reliable agent workflows |
| [Restate](https://restate.dev/) | Durable execution for distributed applications. | Durable agent backends |
| [Dapr](https://dapr.io/) | Distributed application runtime. | Portable agent microservices |
| [Hatchet](https://hatchet.run/) | Distributed task queue for durable workflows. | Background agent jobs |
| [Prefect](https://www.prefect.io/) | Workflow orchestration for data and AI pipelines. | Scheduled AI pipelines |
| [Dagster](https://dagster.io/) | Data orchestration platform for reliable pipelines. | Data-heavy agent pipelines |
| [Vertex AI Agent Engine](https://cloud.google.com/vertex-ai/generative-ai/docs/agent-engine/overview) | Managed runtime for deploying agents on Google Cloud. | Managed cloud agent hosting |
| [AWS AgentCore](https://aws.amazon.com/bedrock/agentcore/) | Runtime and infrastructure for deploying agents. | Production AWS agents |
| [Kubernetes](https://kubernetes.io/) | Container orchestration for production workloads. | Production agent clusters |
| [Ray](https://www.ray.io/) | Distributed compute framework for AI workloads. | Distributed agent compute |
| [Ray Serve](https://docs.ray.io/en/latest/serve/) | Scalable model and application serving on Ray. | Python model services |
| [SkyPilot](https://skypilot.readthedocs.io/) | Run AI workloads on any cloud. | Portable agent compute |
| [KServe](https://kserve.github.io/website/) | Kubernetes model serving platform. | Kubernetes inference |
| [LangGraph Platform](https://www.langchain.com/langgraph-platform) | Deployment platform for LangGraph agents. | Hosted LangGraph agents |
| [Runhouse](https://www.run.house/) | Compute and data runtime for AI workloads. | Portable AI compute |
| [Union.ai](https://www.union.ai/) | Managed platform for AI and data workflows. | Managed AI pipelines |
| [Airflow](https://airflow.apache.org/) | Workflow orchestration platform. | Scheduled agent pipelines |
| [Argo Workflows](https://argoproj.github.io/workflows/) | Kubernetes-native workflow engine. | Kubernetes batch workflows |
| [Argo Events](https://argoproj.github.io/events/) | Event-driven automation for Kubernetes. | Event-triggered agent jobs |
| [Knative](https://knative.dev/) | Serverless containers on Kubernetes. | Autoscaled agent services |
| [OpenFaaS](https://www.openfaas.com/) | Serverless functions on Kubernetes and containers. | Function-backed agent tools |
| [Nuclio](https://nuclio.io/) | High-performance serverless framework. | Realtime AI functions |
| [Kubeflow Pipelines](https://www.kubeflow.org/docs/components/pipelines/) | Machine learning pipelines on Kubernetes. | Kubernetes ML workflows |
| [Metaflow](https://metaflow.org/) | Human-friendly framework for data science workflows. | Data-to-agent pipelines |
| [Hamilton](https://hamilton.dagworks.io/) | Dataflow framework for Python functions. | Composable AI pipelines |
| [Kestra](https://kestra.io/) | Open-source orchestration and scheduling platform. | Operational agent workflows |
| [Windmill](https://www.windmill.dev/) | Open-source scripts, workflows, and internal tools platform. | Script-backed agent tools |
| [Val Town](https://www.val.town/) | Run and schedule TypeScript functions in the cloud. | Small cloud tools |
| [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/) | Run AI inference on Cloudflare Workers. | Edge AI functions |
| [Cloudflare Workflows](https://developers.cloudflare.com/workflows/) | Durable workflows on Cloudflare. | Edge durable agent jobs |
| [Cloudflare Queues](https://developers.cloudflare.com/queues/) | Message queues for Cloudflare Workers. | Async edge agent tasks |
| [AWS Lambda](https://aws.amazon.com/lambda/) | Serverless functions on AWS. | AWS function tools |
| [AWS Step Functions](https://aws.amazon.com/step-functions/) | Workflow orchestration for AWS services. | AWS durable workflows |
| [AWS Batch](https://aws.amazon.com/batch/) | Managed batch computing on AWS. | Batch agent workloads |
| [Google Cloud Run](https://cloud.google.com/run) | Serverless containers on Google Cloud. | Managed agent APIs |
| [Google Cloud Workflows](https://cloud.google.com/workflows) | Serverless workflow orchestration on Google Cloud. | GCP agent workflows |
| [Google Cloud Tasks](https://cloud.google.com/tasks) | Managed task queues on Google Cloud. | Async agent jobs |
| [Azure Functions](https://azure.microsoft.com/products/functions) | Serverless functions on Azure. | Azure function tools |
| [Azure Container Apps](https://azure.microsoft.com/products/container-apps) | Serverless containers on Azure. | Azure agent services |
| [Azure Durable Functions](https://learn.microsoft.com/azure/azure-functions/durable/) | Durable orchestration for Azure Functions. | Azure stateful workflows |
| [Celery](https://docs.celeryq.dev/) | Distributed task queue for Python. | Python agent workers |
| [RQ](https://python-rq.org/) | Simple Redis-backed Python job queue. | Simple background agent jobs |
| [BullMQ](https://bullmq.io/) | Redis-backed queue for Node.js. | Node.js agent workers |
| [RabbitMQ](https://www.rabbitmq.com/) | Message broker for distributed systems. | Agent service messaging |
| [NATS](https://nats.io/) | High-performance messaging system. | Low-latency agent messaging |
| [Apache Kafka](https://kafka.apache.org/) | Distributed event streaming platform. | Agent event streams |
| [Redpanda](https://redpanda.com/) | Kafka-compatible streaming platform. | Streaming agent events |
| [Upstash QStash](https://upstash.com/qstash) | Serverless message queue and scheduler. | HTTP agent task queues |
| [Convex](https://www.convex.dev/) | Reactive backend for app and agent state. | Realtime agent backends |
| [Encore](https://encore.dev/) | Backend development platform for distributed systems. | Typed agent backends |
| [EKS Auto Mode](https://aws.amazon.com/eks/) | Managed Kubernetes compute for production workloads. | AWS agent clusters |
| [GKE Autopilot](https://cloud.google.com/kubernetes-engine/docs/concepts/autopilot-overview) | Managed Kubernetes mode on Google Cloud. | Managed GCP clusters |
| [AKS](https://azure.microsoft.com/products/kubernetes-service) | Managed Kubernetes on Azure. | Azure agent clusters |
| [CoreWeave](https://www.coreweave.com/) | Cloud infrastructure for GPU workloads. | GPU-heavy agent systems |
| [Lambda Cloud](https://lambdalabs.com/service/gpu-cloud) | GPU cloud for AI workloads. | GPU model workloads |
| [Crusoe Cloud](https://crusoe.ai/) | Cloud platform for AI infrastructure. | AI compute infrastructure |
| [Fluidstack](https://www.fluidstack.io/) | GPU cloud infrastructure for AI. | Large GPU clusters |
| [Nebius AI Cloud](https://nebius.com/) | Cloud platform for AI builders. | AI cloud infrastructure |
| [Anyscale](https://www.anyscale.com/) | Managed Ray platform for AI applications. | Managed distributed AI |
| [Brev](https://brev.dev/) | Cloud development environments for AI workloads. | GPU dev environments |
| [Lightning AI](https://lightning.ai/) | AI development and deployment platform. | End-to-end AI development |
| [Paperspace Gradient](https://www.paperspace.com/gradient) | Cloud notebooks and GPU infrastructure. | Notebook-based AI workloads |
| [Starlette](https://www.starlette.io/) | Lightweight ASGI framework for Python services. | Python agent APIs |
| [FastAPI](https://fastapi.tiangolo.com/) | Python API framework for production services. | Agent tool APIs |
| [Hono](https://hono.dev/) | Small web framework for edge and serverless apps. | Edge agent APIs |
| [Nitro](https://nitro.unjs.io/) | Server engine for universal JavaScript apps. | Portable JS agent APIs |
| [Next.js Route Handlers](https://nextjs.org/docs/app/building-your-application/routing/route-handlers) | API routes for Next.js applications. | App-integrated agent endpoints |
| [SvelteKit](https://svelte.dev/docs/kit) | Full-stack framework for web applications. | Agent web apps |
| [Remix](https://remix.run/) | Full-stack web framework. | Data-driven agent apps |
| [Northflank](https://northflank.com/) | Platform for deploying containers, jobs, and databases. | Containerized agent backends |
