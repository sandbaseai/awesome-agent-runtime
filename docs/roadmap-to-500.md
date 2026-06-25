# Roadmap To 500 Projects

Goal: grow Awesome Agent Runtime from a compact landscape into a 500-project infrastructure map without becoming a generic AI tools directory.

## Current Milestone

- 2026-06-25: expanded from 50 to 500 projects.
- Next target: improve quality with source checks, community submissions, category balancing, short notes for notable projects, and contribution guidelines.

## Expansion Rules

Every added project should satisfy at least one condition:

- It helps build, run, secure, observe, evaluate, deploy, or connect production AI agents.
- It provides a reusable infrastructure layer rather than a single end-user AI app.
- It has public docs, a public repository, or clear technical product documentation.
- It represents an ecosystem category that agent builders naturally compare.

Avoid:

- generic prompt lists
- thin wrappers around a model API
- one-off demos without reusable infrastructure value
- marketing-only directories
- low-signal repos created only for stars or bounty loops

## Target Category Mix

Approximate 500-project distribution:

| Category | Target Count | Notes |
| --- | ---: | --- |
| Agent runtime | 90 | Frameworks, coding agents, multi-agent orchestration, managed agent services |
| Execution sandbox | 55 | Code execution, microVMs, containers, Wasm, notebook/runtime sandboxes |
| Browser automation | 45 | Browser agents, hosted browsers, scraping/browser APIs, computer-use systems |
| Tool protocol | 45 | MCP SDKs, servers, tool registries, OpenAPI/action schemas |
| App integrations | 50 | SaaS action layers, OAuth, workflow automation, API connectors |
| Memory/context | 55 | Vector DBs, graph memory, retrieval engines, context stores |
| Safety/evals | 55 | Guardrails, red teaming, prompt-injection defense, eval frameworks |
| Model gateway | 45 | Routing, local runtimes, inference gateways, model serving |
| Observability | 50 | Tracing, eval ops, prompt/version logs, cost/latency monitoring |
| Deployment/compute | 60 | Durable workflows, GPU/serverless compute, queues, serving, orchestration |

## Next Collection Queries

Use these as focused search themes:

- `topic:ai-agents topic:framework`
- `topic:mcp-server`
- `topic:model-context-protocol`
- `topic:browser-automation ai agents`
- `topic:llm-observability`
- `topic:llm-evaluation`
- `agent sandbox runtime`
- `code interpreter sandbox`
- `agent workflow durable execution`
- `LLM gateway model routing`
- `GraphRAG memory agent`

## Review Checklist

Before adding a batch:

- Check for duplicate name or URL.
- Confirm category and tagline are neutral.
- Prefer official docs or GitHub URLs.
- Keep `best_for` short and builder-oriented.
- Do not mark new entries `featured` unless they are category-defining.
- Update `README.md` coverage count and category tables after editing `data/projects.json`.

## Batch Plan

### Batch 1: 50 -> 200

Completed on 2026-06-25.

Coverage improved in:

- TypeScript and Python agent frameworks
- coding agents
- browser automation
- MCP/tool protocol
- vector and graph memory
- AI observability
- guardrails and evals
- durable workflows and model serving

### Batch 2: 200 -> 300

Completed on 2026-06-25.

Coverage improved in:

- MCP servers and registries
- app-action integration platforms
- self-hosted agent platforms
- browser/computer-use infra
- more open-source eval/security tools
- coding-agent tools
- document and retrieval infrastructure

### Batch 3: 300 -> 400

Completed on 2026-06-25.

Coverage improved in:

- cloud/runtime deployment systems
- GPU/model serving platforms
- workflow engines and queues
- data and document-ingestion tools
- model gateways and fine-tuning platforms
- process, Linux, notebook, and Wasm sandbox layers
- observability primitives for infrastructure metrics, traces, logs, and costs
- API/schema protocols for agent tool surfaces

### Batch 4: 400 -> 500

Completed on 2026-06-25.

Coverage improved in:

- code execution and WebAssembly sandboxes
- browser automation, scraping browsers, and lower-fingerprint automation
- SaaS integration, identity, and embedded iPaaS platforms
- graph, analytical, and hybrid retrieval memory layers
- AI security, red-team, jailbreak, and agent-safety benchmarks
- OpenTelemetry, product analytics, and full-stack observability tools
- API design, API gateway, and SDK-generation tooling for agent tool surfaces

### Next Phase: Quality And Community

Prioritize:

- verify links and official sources
- add contribution guidelines and issue templates
- identify 25-50 category-defining projects for short annotations
- rebalance overrepresented deployment/compute entries
- invite community PRs from agent-runtime, MCP, sandbox, and observability builders
