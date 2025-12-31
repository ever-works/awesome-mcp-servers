# Cloudflare Docs MCP Server

**Category:** Documentation & Learning Resources  
**Brand:** Cloudflare  
**Source:** [Metorial marketplace listing](https://metorial.com/marketplace/s/cloudflare-docs)

A Model Context Protocol (MCP) server that gives AI assistants direct, semantic-search access to Cloudflare’s developer documentation at `https://docs.mcp.cloudflare.com/sse`. It is designed to integrate Cloudflare docs into agentic AI workflows for development, configuration, and troubleshooting.

---

## Overview

Cloudflare Docs MCP Server acts as a bridge between AI agents and Cloudflare’s documentation ecosystem. It allows querying Cloudflare docs from within AI-powered tools instead of manually browsing the web, returning contextually relevant documentation chunks for Cloudflare products and features.

It supports a wide range of Cloudflare offerings, including compute, storage, networking, security, and AI/ML products, and is particularly useful for:

- Looking up configuration details and best practices
- Accessing migration guides
- Retrieving API references
- Assisting with Workers code generation and optimization

---

## Features

### 1. Direct Access to Cloudflare Documentation
- Connects to Cloudflare documentation via MCP at `https://docs.mcp.cloudflare.com/sse`.
- Exposes Cloudflare’s official developer docs to AI assistants and tools.
- Returns documentation chunks rather than entire pages for focused answers.

### 2. Comprehensive Product Coverage
Provides documentation coverage across the Cloudflare ecosystem, including:

- **Compute & Development Platforms**  
  - Workers  
  - Pages  
  - Workflows

- **Storage & Data**  
  - R2  
  - D1  
  - Durable Objects  
  - KV  
  - Queues

- **AI & Machine Learning**  
  - AutoRAG  
  - Workers AI  
  - Vectorize  
  - AI Gateway

- **Media Services**  
  - Images  
  - Stream  
  - Browser Rendering

- **Security & Zero Trust**  
  - Access  
  - Tunnel  
  - Gateway  
  - Browser Isolation  
  - WARP

- **Network Services**  
  - DDoS protection  
  - Magic Transit  
  - Magic WAN

- **Core Infrastructure**  
  - CDN  
  - Cache  
  - DNS  
  - Hyperdrive

- **Developer Tools & Integrations**  
  - Zaraz  
  - Argo  
  - Rulesets  
  - Terraform

- **Account & Administration**  
  - Billing and account management documentation

### 3. Semantic Search Across Documentation
- Uses semantic similarity rather than strict keyword matching.
- Supports natural language queries about features, products, or problems.
- Returns the most relevant documentation chunks for a given query.

### 4. Access to Migration Guides
- Includes access to Cloudflare migration guides.  
- Useful for planning and executing migrations between Cloudflare services or from external systems.  
- Surfaces step-by-step, authoritative migration instructions where available.

### 5. Workers Code Generation Support
- Leverages documentation and tailored prompts for Cloudflare Workers.  
- Helps AI agents generate Workers code aligned with Cloudflare’s recommended patterns and best practices.  
- Supports developing, troubleshooting, and optimizing Workers-based applications.

### 6. API Reference Retrieval
- Enables retrieval of API reference documentation via semantic search.  
- Suitable for looking up endpoints, parameters, and usage details directly from an AI assistant.

---

## Tools / API Surface

### `search_cloudflare_documentation`
- **Function:** Search Cloudflare documentation using semantic similarity.
- **Purpose:** Primary tool for discovering information about any Cloudflare product, feature, or service.
- **Intended Uses:**
  - Product and feature overviews
  - Troubleshooting guidance
  - Configuration and deployment details
  - API references and examples
  - Best practices and architectural guidance

---

## Pricing

No pricing information is provided in the available content.