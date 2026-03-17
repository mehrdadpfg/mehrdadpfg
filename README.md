# Hi, I'm Mehrdad

**Senior DevOps Engineer** based in Sweden.

I work at the intersection of **platform engineering** and **AI enablement** — building the infrastructure, tooling, and secure workflows that let engineering teams adopt AI agents in production. From Kubernetes operators that optimize costs autonomously, to knowledge graphs that give coding agents persistent memory, to helping companies set up secure local development environments for AI-assisted work.

---

### What I'm building

#### [Codemem](https://github.com/mehrdadpfg/codemem) — Persistent Memory for AI Coding Agents

AI coding agents (Claude Code, Copilot, Cursor) lose all context between sessions. Codemem fixes that — it's a knowledge graph and semantic memory layer that gives agents deep, structured understanding of your codebase that persists across conversations.

- **MCP server** that plugs directly into Claude Code and other agentic tools
- Symbol-level knowledge graph with hybrid search (BM25 + HNSW vector index)
- Multi-agent analysis pipeline: baseline scanning, pattern discovery, architecture review, security analysis
- Embedding providers: local Candle (pure Rust), Ollama, OpenAI, Google Gemini
- Enrichment pipeline: static analysis → annotated graph with semantic deduplication
- Built in **Rust** (6-crate workspace) with a **React/TypeScript** UI
- REST API + CLI for integration into any agentic workflow

#### [Sartor](https://github.com/sartorproj/sartor) — Autonomous Kubernetes Resource Optimization

A Kubernetes controller that acts as an autonomous agent for your cluster — it observes real workload patterns, predicts future resource needs, and creates GitOps pull requests to right-size your deployments without human intervention.

- Intent-based optimization profiles (Eco, Balanced, Critical)
- DSP-based time series forecasting with FFT and autocorrelation
- OOM protection with automatic memory limit patching
- GitOps-native: creates PRs for raw YAML, Helm, and Kustomize manifests
- ArgoCD integration for auto-sync after PR merge
- Built in **Go** with a plugin-based recommendation engine

#### [goarima](https://github.com/sartorproj/goarima) — ARIMA Forecasting in Go

A standalone ARIMA time series forecasting library powering Sartor's predictive resource optimization. Useful for any Go project that needs statistical forecasting without Python dependencies.

---

### AI Enablement & Secure Agent Deployment

Beyond open-source projects, I focus on enabling AI adoption within engineering organizations:

- **MCP server deployment** — deploying and implementing both OSS and internally-built MCP servers, giving AI agents secure, scoped access to internal tools, APIs, and data sources
- **Context lakes** — building dynamic and static context lake architectures and knowledge systems that feed AI agents the right information at the right time
- **Sandboxed code execution** — designing untrusted code execution environments where AI agents can safely run, test, and iterate without risk to production systems
- **Secure local dev environments** — credential isolation, policy-based tool access, and sandboxed execution so teams can use coding agents safely on their machines
- **Agent deployment pipelines** — CI/CD patterns for deploying, monitoring, and governing autonomous agents in production
- **Cost-aware automation** — connecting AI and platform tooling to FinOps signals so autonomous systems optimize with budget constraints in mind

---

### Tech I work with

`Kubernetes` `Go` `Rust` `MCP` `AI Agents` `Claude Code` `Prometheus` `ArgoCD` `Helm` `GitOps` `Terraform` `Python` `TypeScript` `Linux`

---
