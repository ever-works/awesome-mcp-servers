# Model Context Protocol Swift SDK

**Category:** mcp-server-directories-lists  
**Brand:** model-context-protocol  
**Source:** https://github.com/modelcontextprotocol/swift-sdk

---

## Overview

The Model Context Protocol Swift SDK is the official Swift implementation of the [Model Context Protocol (MCP)](https://modelcontextprotocol.io). It provides both client and server components for Swift and Apple platform developers, following the 2025-03-26 version of the MCP specification. It enables applications to communicate with AI and ML models via the standardized MCP interface.

---

## Features

- **Official Swift SDK for MCP**
  - Designed specifically for the Model Context Protocol.
  - Implements both MCP client and server components.

- **Standards-compliant implementation**
  - Conforms to the MCP specification version **2025-03-26** (latest referenced in the repo).
  - Enables standardized communication between applications and AI/ML models.

- **Client capabilities**
  - Provides a client component that allows Swift applications to connect to MCP servers.
  - `Client.connect(transport:)` API for establishing a connection to a server.
  - The `Client.connect(transport:)` method returns an initialization result (return value is discardable if not needed).

- **Server capabilities**
  - Includes components needed to implement MCP servers in Swift (as stated: “implements both client and server components”).

- **Swift Package Manager support**
  - Distributed as a Swift package.
  - Can be added as a dependency via `Package.swift`.

- **Test suite and structure**
  - `Sources/MCP` directory for SDK source code.
  - `Tests/MCPTests` directory for automated tests.

- **Repository assets**
  - `Package.swift` and `Package@swift-6.0.swift` for package configuration and Swift versioning.
  - `Package.resolved` for pinned dependency versions.
  - `LICENSE` file defining usage terms.

---

## Requirements

- Platform-specific requirements are referenced in the **Platform Availability** section of the README (not fully visible in the provided content). Users should consult that section in the repository for detailed platform and version requirements.

---

## Installation

### Swift Package Manager

1. Add the package to your `Package.swift` dependencies:
   - Include the GitHub URL `https://github.com/modelcontextprotocol/swift-sdk` as a dependency.
2. Add the resulting product(s) from the package to your target’s dependencies.

(Exact code snippet is not fully visible in the provided content; users should copy it from the README in the repository.)

---

## Usage

### Client Usage

- Use the **client component** to connect your Swift application to MCP servers.

#### Basic Client Setup

- Establish a connection with:
  - `Client.connect(transport:)`
- The method returns an initialization result:
  - The return value is discardable, so it can be ignored if you do not need to inspect the initialization result.

(Additional configuration and usage examples are likely in the README but are not fully visible in the provided content.)

---

## Pricing

- Pricing information is **not specified** in the provided content.  
- Usage terms and conditions are defined in the repository’s `LICENSE` file.

---

## Repository

- GitHub: https://github.com/modelcontextprotocol/swift-sdk