# Awesome Rust AI
Curated Rust-first AI tooling extracted from `docs/` (ChatGPT and Gemini notes). Each category lists notable projects with quick links.

## Vector Databases & Retrieval Platforms
| Name | Description | GitHub | Website |
| --- | --- | --- | --- |
| Chroma | Open-source vector database for embeddings and semantic search. | — | [docs.trychroma.com](https://docs.trychroma.com/getting-started) |
| PostgresML | Postgres extension adding vector search and in-DB ML/LLM inference. | [postgresml/postgresml](https://github.com/postgresml/postgresml) | — |
| VectorChord | Postgres extension for relational + vector search in SQL. | — | [docs.vectorchord.ai](https://docs.vectorchord.ai) |
| Trieve AI | Hosted/open-source platform combining vector search, hybrid search, and analytics. | [devflowinc/trieve](https://github.com/devflowinc/trieve) | [trieve.ai](https://www.trieve.ai) |
| Spice AI | Data+AI engine that mixes SQL, vector search, and LLM calls. | — | [spice.ai](https://spice.ai) |
| Motorhead | Redis-backed chat memory server for long conversations. | [getmetal/motorhead](https://github.com/getmetal/motorhead) | — |
| CocoIndex | Rust ETL/indexing framework for streaming embeddings into vector stores. | [cocoindex-io/cocoindex](https://github.com/cocoindex-io/cocoindex) | [cocoindex.io](https://cocoindex.io) |
| Materialize | Streaming SQL database for real-time joins and views alongside vector search. | — | — |

## LLM Application Frameworks & Prompting Libraries
| Name | Description | GitHub | Website |
| --- | --- | --- | --- |
| LangChain-rust | Rust take on LangChain patterns (prompts, memory, tool use). | — | — |
| Rig | Modular, type-safe SDK for RAG, tool use, and multi-agent flows. | [0xPlaygrounds/rig](https://github.com/0xPlaygrounds/rig) | [rig.rs](https://rig.rs) |
| LLM Chain | Crates for chaining LLM calls and function/tool-style actions. | [sobelio/llm-chain](https://github.com/sobelio/llm-chain) | [llm-chain.xyz](https://llm-chain.xyz) |
| BoundaryML (BAML) | Strongly-typed prompt DSL and compiler for reliable agent workflows. | — | [boundaryml.com](https://boundaryml.com) |
| LLGuidance | Constrained decoding library to enforce structured LLM outputs. | — | — |
| AICI | Microsoft’s controller framework treating prompts as programs with Wasm guards. | [microsoft/aici](https://github.com/microsoft/aici) | — |
| Floneum | Visual graph editor and pluginable Rust runtime for local AI workflows. | [floneum/floneum](https://github.com/floneum/floneum) | [floneum.com](https://floneum.com/docs/) |

## LLM Inference & Serving Tools
| Name | Description | GitHub | Website |
| --- | --- | --- | --- |
| Mistral.rs | Cross-platform Rust engine/server for text, vision, image, and speech models. | [EricLBuehler/mistral.rs](https://github.com/EricLBuehler/mistral.rs) | — |
| LlamaEdge | Lightweight OpenAI-compatible CLI/runtime for local LLM serving via WasmEdge. | [LlamaEdge](https://github.com/LlamaEdge) | [llamaedge.com](https://llamaedge.com) |
| LM.rs | Minimal CPU-focused LLM inference in pure Rust with custom model format. | — | — |
| Uzu | Apple Silicon–optimized inference engine with Swift/TS bindings. | [trymirai/uzu](https://github.com/trymirai/uzu) | [mirai docs](https://mirai-bded675a.mintlify.app/) |
| Paddler | Rust LLMOps platform for scaling/auto-routing across multiple model workers. | [intentee/paddler](https://github.com/intentee/paddler) | [paddler.intentee.com](https://paddler.intentee.com/docs/introduction/changelog/) |
| HF Text Embeddings Inference (TEI) | Rust-based service for high-throughput embedding generation. | — | — |
| vLLM Semantic Router | Router for mixture-of-models deployments to optimize cost/performance. | [vllm-project/semantic-router](https://github.com/vllm-project/semantic-router) | [vllm-semantic-router.com](https://vllm-semantic-router.com) |

## AI Agents & Autonomy Frameworks
| Name | Description | GitHub | Website |
| --- | --- | --- | --- |
| ACP & MCP Protocols | Interop standards for agent/editor comms and tool calls. | — | [agentclientprotocol.com](https://agentclientprotocol.com) |
| AgentGateway | Rust data plane/gateway for secure, observable agent communications. | [agentgateway/agentgateway](https://github.com/agentgateway/agentgateway) | [agentgateway.dev](https://agentgateway.dev) |
| ArchGW | Envoy-based proxy adding routing/guardrails for agentic apps. | — | [archgw.com](https://www.archgw.com) |
| HyperMCP | MCP server with Wasm plugin model for tool hosting. | [tuananh/hyper-mcp](https://github.com/tuananh/hyper-mcp) | — |
| AgentFS | Turso-backed “filesystem” for persisting agent state and artifacts. | [tursodatabase/agentfs](https://github.com/tursodatabase/agentfs) | [docs.turso.tech/agentfs](https://docs.turso.tech/agentfs/introduction) |
| Browser Agent | Headless browser control layer so LLMs can operate real web pages. | [m1guelpf/browser-agent](https://github.com/m1guelpf/browser-agent) | — |
| Terminator | AI-driven desktop automation SDK for GUI apps. | [mediar-ai/terminator](https://github.com/mediar-ai/terminator) | — |
| Chidori | Rust runtime/IDE for durable, debuggable long-running agents. | [ThousandBirdsInc/chidori](https://github.com/ThousandBirdsInc/chidori) | — |
| Pica OS | Enterprise agent platform with 150+ SaaS integrations. | [picahq/pica](https://github.com/picahq/pica) | [picaos.com](https://www.picaos.com) |
| Vibe Kanban | Kanban UI/backend to orchestrate multiple coding agents in parallel. | [BloopAI/vibe-kanban](https://github.com/BloopAI/vibe-kanban) | [vibekanban.com](https://www.vibekanban.com) |
| Arbiter | Multi-agent simulation/auditing framework with built-in EVM. | [harnesslabs/arbiter](https://github.com/harnesslabs/arbiter) | [harnesslabs.dev](https://harnesslabs.dev) |
