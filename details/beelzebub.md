# beelzebub

**Category:** security-attestation-mcp-servers  
**Tags:** security, prompt-injection, ai-agents  
**Source:** https://github.com/mariocandela/beelzebub

## Overview
beelzebub is an open-source, secure low‑code honeypot framework built on the Model Context Protocol (MCP). It is designed to create honeypot tools and virtualized environments that detect prompt injection attempts and malicious AI agent behavior.

## Features
- **MCP-based honeypot framework**
  - Built on the Model Context Protocol to integrate with AI agents and tooling ecosystems.
  - Allows creation of honeypot tools that appear as legitimate capabilities to agents.

- **Prompt injection and agent behavior detection**
  - Targets detection of prompt injection attacks against LLMs and AI agents.
  - Monitors and analyzes agent actions to identify malicious or abnormal behavior.

- **System virtualization for honeypots**
  - Uses AI-driven system virtualization to simulate services and environments.
  - Provides realistic but controlled targets for attackers or misbehaving agents.

- **Low-code configuration**
  - Honeypot behavior and scenarios can be defined with configuration rather than extensive custom code (e.g., via the `configurations` directory and builder tooling).

- **Plugin architecture**
  - `plugins` module for extending honeypot capabilities.
  - Enables custom detectors, behaviors, or protocol handlers as pluggable components.

- **Protocol support**
  - `protocols` module suggests support for multiple communication or interaction protocols.
  - Can be extended to cover additional protocols used by agents or external systems.

- **Tracing and observability**
  - `tracer` module for tracking interactions, behaviors, and potential attacks.
  - Facilitates logging and analysis of agent requests and honeypot responses.

- **History storage**
  - `historystore` module to persist interaction histories.
  - Useful for forensics, analytics, and model/agent behavior research.

- **Parsing and analysis utilities**
  - `parser` module for processing prompts, agent outputs, and protocol messages.
  - Supports building detection logic on parsed content and structures.

- **Integration testing**
  - `integration_test` directory with tests for end-to-end validation of setups.

- **Containerization and deployment**
  - Docker support via `Dockerfile` and `docker-compose.yml`.
  - Helm chart via `beelzebub-chart` for Kubernetes deployment.

- **Build & automation tooling**
  - `builder` module and `Makefile` for building, packaging, and automating common tasks.

- **Security and governance documents**
  - `SECURITY.md` for security practices and vulnerability handling.
  - `CODE_OF_CONDUCT.md` and `CONTRIBUTING.md` for community contributions.

## Pricing
- Not specified; the project appears to be an open-source repository on GitHub. Refer to the repository’s `LICENSE` file for usage terms and conditions.