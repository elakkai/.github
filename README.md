# 🌿 ElakkAI

> A singular, zero-dependency AI SDK built entirely on Bun's native runtime APIs. Hyper-optimized, type-safe, and modular.

## About Us

ElakkAI is an open-source initiative focused on reimagining AI application development. We believe that building intelligent agents and complex RAG pipelines shouldn't require managing massive dependency trees or dealing with fragile native bindings.

Our mission is to provide a **zero-dependency, Bun-native framework** built to eliminate dependency overhead and maximize performance. By leveraging Bun's C++/Rust/Zig-optimized runtime APIs, ElakkAI delivers unmatched execution speed, microscopic bundle sizes, and absolute immunity to supply-chain vulnerabilities.

## 🚀 Key Features

- **Zero Dependencies:** Pure Bun runtime APIs. No `node_modules` bloat, no supply-chain risks.
- **Hyper-Optimized:** Native `TransformStream` SSE parsing, zero-copy concurrency, and bytecode-compiled binaries.
- **Type-Safe by Default:** Flawless TypeScript inference with a custom, zero-dependency JSON Schema validator.
- **40+ Native Tools:** Pre-built tools for Filesystem, HTTP, Docker, S3, Redis, PostgreSQL, WebView, and more.
- **Single Binary Deployment:** Compile your entire AI agent into a standalone executable with sub-50ms cold starts.

##  Supported LLM Providers

ElakkAI provides dedicated, native clients for the industry's leading models, all sharing a unified `Provider` interface:

- **OpenAI** (`@elakkai/openai`) - For high-speed, cost-effective generation and embeddings.
- **Anthropic** (`@elakkai/anthropic`) - For complex, multi-step agent reasoning and long-context tasks (Claude).
- **Google Gemini** (`@elakkai/gemini`) - For native multimodal excellence and fast tool calling.
- **Ollama** (`@elakkai/ollama`) - For fully local, private inference using native NDJSON streaming.

*Additionally, any OpenAI-compatible provider (Groq, xAI, Mistral, DeepSeek, vLLM) works instantly out of the box by simply overriding the base URL.*

## 📦 Our Projects

- **[elakkai](https://github.com/elakkai/elakkai)** — The core monorepo containing the complete AI SDK, including LLM providers, vector stores, document loaders, dynamic skill routing, and production-ready HTTP servers.
