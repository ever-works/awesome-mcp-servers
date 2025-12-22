# Stripe Agent Toolkit MCP

## Overview

Stripe Agent Toolkit MCP is an open-source, Model Context Protocol (MCP)–compatible toolkit for interacting with the Stripe API. It is designed to let AI agents call Stripe operations as tools, enabling programmatic access to Stripe functionality within agentic workflows.

- **Repository:** https://github.com/stripe/agent-toolkit  
- **Docs:** https://docs.stripe.com/agents  
- **License:** MIT

## Features

- **MCP-compatible toolkit**  
  - Implements tools that conform to the Model Context Protocol so that compatible AI agents can call Stripe operations in a standardized way.

- **Stripe API integration for agents**  
  - Exposes Stripe API operations as callable tools (e.g., for working with Stripe resources) so agents can perform Stripe-related tasks programmatically.  
  - Encapsulates Stripe requests and responses in a form suitable for LLM-based agents.

- **Agent-focused abstractions**  
  - Provides tooling oriented around “agent workflows” rather than raw HTTP calls.  
  - Aims to simplify how agents authenticate to Stripe and invoke operations in a controlled manner.

- **Part of Stripe’s AI/agents ecosystem**  
  - Integrated into Stripe’s broader "AI" and "agents" tooling, as referenced in the `stripe/ai` GitHub project and `docs.stripe.com/agents` documentation.

- **Open-source and extensible**  
  - Source code available on GitHub for customization and extension.  
  - MIT license allows modification and integration into your own systems.

## Pricing

- **Open source**: Free to use under the MIT license.  
- **Stripe usage costs**: Any actual Stripe API usage is billed separately under your Stripe account and pricing; the toolkit itself does not add additional usage fees.

## License

- **MIT License** (per Stripe’s AI/agent tooling repositories on GitHub).