# Awesome Agent Runtime

A curated landscape of agent runtimes, sandboxes, browser agents, tool protocols, memory layers, observability, and compute platforms for production AI agents.

This is not a generic AI tools directory. The focus is infrastructure that helps developers build, run, secure, observe, and scale agents in real products.

Maintained by [SandBase AI](https://www.sandbase.ai/), an agent infrastructure platform for developers building production AI agents.

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

Current coverage: **50 projects** across **10 infrastructure categories**.

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

## Execution Sandbox

| Project | What it is | Best for |
| --- | --- | --- |
| [E2B](https://e2b.dev/) | Cloud sandboxes for code-executing agents. | Agents that run code |
| [Daytona](https://www.daytona.io/) | Dev environments for agentic workflows. | Agent coding environments |
| [Modal Sandboxes](https://modal.com/docs/guide/sandbox) | Ephemeral remote sandboxes on Modal. | Dynamic code execution |

## Browser Automation

| Project | What it is | Best for |
| --- | --- | --- |
| [Browserbase](https://www.browserbase.com/) | Hosted browser infrastructure for agents. | Web automation agents |
| [Browserless](https://www.browserless.io/) | Headless browser infrastructure at scale. | Large-scale browser work |
| [Playwright](https://playwright.dev/) | Reliable browser automation library. | Building browser tools |
| [Skyvern](https://www.skyvern.com/) | Browser tasks with AI-driven execution. | Task-oriented browser agents |
| [Stagehand](https://www.browserbase.com/stagehand) | Browser control with natural-language helpers. | Hybrid browser automation |
| [browser-use](https://github.com/browser-use/browser-use) | Open-source browser agent framework. | Open-source browser agents |

## Memory And Context

| Project | What it is | Best for |
| --- | --- | --- |
| [Letta](https://www.letta.com/) | Stateful agents with long-term memory. | Persistent personal agents |
| [Mem0](https://mem0.ai/) | Universal memory layer for agents. | Cross-session memory |
| [Zep](https://www.getzep.com/) | Memory infrastructure for agent applications. | Conversation history |
| [Supermemory](https://supermemory.ai/) | Personal and app memory for AI products. | Personalized agents |
| [Pinecone](https://www.pinecone.io/) | Vector database widely used for agent memory. | Scalable embedding memory |
| [Qdrant](https://qdrant.tech/) | Open-source vector database for memory and retrieval. | Self-hosted memory stores |

## Safety And Evals

| Project | What it is | Best for |
| --- | --- | --- |
| [Lakera](https://www.lakera.ai/) | Prompt-injection and AI security defenses. | Production safety filters |
| [Guardrails AI](https://www.guardrailsai.com/) | Validation, railings, and output constraints. | Output validation |
| [Promptfoo](https://www.promptfoo.dev/) | Eval and red-teaming for prompt and agent safety. | Prompt and agent QA |
| [Giskard](https://www.giskard.ai/) | LLM testing and red-teaming platform. | Safety reviews and audits |

## Tool Protocol

| Project | What it is | Best for |
| --- | --- | --- |
| [Model Context Protocol](https://modelcontextprotocol.io/) | Standard protocol for tools and context. | Standardizing tool access |
| [Smithery](https://smithery.ai/) | Discovery and hosting for MCP servers. | Finding MCP servers |

## App Integrations

| Project | What it is | Best for |
| --- | --- | --- |
| [Composio](https://composio.dev/) | Managed app integrations and actions for agents. | Agents using SaaS tools |
| [Nango](https://www.nango.dev/) | OAuth and API integrations for agent workflows. | Reliable app connections |
| [Pipedream](https://pipedream.com/) | Connect APIs and run event-driven workflows. | Workflow-backed tools |
| [Inngest](https://www.inngest.com/) | Durable functions and workflows. | Reliable agent jobs |
| [Trigger.dev](https://trigger.dev/) | Background jobs for AI and web apps. | Async agent operations |

## Model Gateway

| Project | What it is | Best for |
| --- | --- | --- |
| [LiteLLM](https://www.litellm.ai/) | OpenAI-compatible gateway across model providers. | Multi-provider model access |
| [OpenRouter](https://openrouter.ai/) | Unified API for many model providers. | Broad model choice |
| [Vercel AI Gateway](https://vercel.com/ai-gateway) | Managed gateway for model routing and observability. | Frontend-heavy AI apps |
| [Portkey](https://portkey.ai/) | AI gateway with guardrails and policy controls. | Controlled production access |

## Observability

| Project | What it is | Best for |
| --- | --- | --- |
| [LangSmith](https://www.langchain.com/langsmith) | Tracing, evals, and debugging for LLM apps. | LangChain-based stacks |
| [Langfuse](https://langfuse.com/) | Open-source LLM observability and analytics. | Vendor-neutral observability |
| [Arize Phoenix](https://phoenix.arize.com/) | Open-source tracing and evaluation. | Local-first analysis |
| [Helicone](https://www.helicone.ai/) | LLM request logging and cost analytics. | Spend and latency tracking |
| [Braintrust](https://www.braintrust.dev/) | Eval platform for model and agent quality. | Quality workflows |

## Deployment And Compute

| Project | What it is | Best for |
| --- | --- | --- |
| [Modal](https://modal.com/) | Serverless compute for AI jobs and services. | Burst workloads |
| [Fly.io](https://fly.io/) | Global app deployment close to users. | Regional agent backends |
| [Baseten](https://www.baseten.co/) | Model serving and AI deployment infrastructure. | Hosted inference |
| [Replicate](https://replicate.com/) | Run models and AI workflows via API. | Quick model deployment |
| [RunPod](https://www.runpod.io/) | GPU cloud for model and agent workloads. | GPU-heavy tasks |
| [BentoML](https://www.bentoml.com/) | Model serving and inference deployment tooling. | Self-managed model services |

## Submit A Project

Open an issue with:

- Project name and URL.
- Category.
- One-line description.
- Why it matters for production agents.
- Whether it is open source, commercial, or both.
- Links to docs, GitHub, examples, or launch posts.

Good submissions explain the infrastructure value. Pure marketing blurbs are less useful.

## Relationship To SandBase

SandBase uses this list as an open research map for the agent infrastructure ecosystem. Some projects may become future integration targets, partner candidates, or examples for production agent builders.

The list remains editorial. Inclusion is not sponsorship, endorsement, or ranking.
