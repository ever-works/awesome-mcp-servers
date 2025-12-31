# Model Context Protocol Documentation

**URL:** https://modelcontextprotocol.io/

## Overview
The Model Context Protocol (MCP) Documentation site provides the official specification and technical guides for MCP—an open-source standard for connecting AI applications to external systems such as data sources, tools, and workflows. It explains the protocol’s architecture, how servers and clients are structured, and how to implement and integrate MCP with compatible AI models and applications.

## Key Topics Covered
- Introduction to MCP and its core concepts
- Protocol specification and versioning
- MCP architecture and design principles
- MCP servers: concepts, responsibilities, and implementation
- MCP clients: concepts, responsibilities, and implementation
- Connecting to local and remote MCP servers
- SDKs and development tooling
- MCP Inspector developer tool
- Ecosystem and community resources

## Features

### Conceptual & Architecture Documentation
- **What is MCP?**
  - Defines MCP as an open standard for connecting AI applications to external systems (data, tools, workflows).
  - Explains the analogy of MCP as a “USB-C port” for AI applications, providing a standardized integration approach.
- **Architecture**
  - High-level architecture of MCP-based systems.
  - Roles of servers, clients, and AI models in the ecosystem.
- **Server Concepts**
  - How MCP servers expose data sources, tools, and workflows.
  - Conceptual model of servers as providers of capabilities to AI applications.
- **Client Concepts**
  - How MCP clients connect to one or more MCP servers.
  - How clients surface server capabilities to AI applications and agents.
- **Versioning**
  - Dedicated section on specification versioning.
  - Guidance on tracking protocol changes via the versioned specification endpoint.

### Protocol Specification
- **Canonical specification**
  - Access to the dated protocol specification (`/specification/2025-11-25`).
  - Formal definition of MCP behavior, message flows, and expected interactions between servers and clients.
- **Stable reference for implementers**
  - Serves as the authoritative reference for building compatible MCP servers and clients.

### Development Guides
- **Getting Started**
  - "What is MCP?" onboarding guide for new developers.
  - Orientation to how MCP fits into AI tool and data integrations.
- **Connect to Local MCP Servers**
  - Instructions for configuring and connecting clients to MCP servers running locally.
  - Guidance for local development and testing workflows.
- **Connect to Remote MCP Servers**
  - Guidance for connecting clients to MCP servers running remotely.
  - Covers remote integration scenarios (e.g., network-accessible services and infrastructure).
- **Build an MCP Server**
  - Step-by-step documentation for implementing an MCP server.
  - How to expose data sources, tools, and workflows over MCP.
- **Build an MCP Client**
  - Guides for implementing applications that connect to MCP servers.
  - How to discover and use capabilities made available by servers.
- **SDKs**
  - Overview of available SDKs for building MCP servers and clients.
  - Pointers to language-specific tooling and libraries (where available in the docs).

### Developer Tools
- **MCP Inspector**
  - Documentation for the "MCP Inspector" developer tool.
  - Assists with inspecting, debugging, and understanding MCP interactions between clients and servers.

### Example Use Cases (What MCP Enables)
- Personalized assistants:
  - Agents accessing tools like Google Calendar and Notion to act as more personalized AI assistants.
- Design-to-code workflows:
  - Using MCP to connect models (e.g., Claude Code) to tools like Figma to generate applications from designs.
- Enterprise analytics:
  - Enterprise chatbots connecting to multiple organizational databases, enabling chat-based data analysis.
- Creative and physical workflows:
  - AI models interfacing with applications like Blender and hardware such as 3D printers.

### Ecosystem & Roles
- **For Developers**
  - Reduced development time and complexity when integrating AI applications or agents with external systems.
  - Standardized way to expose tools and data via MCP servers.
- **For AI Applications/Agents**
  - Access to a broader ecosystem of data sources, tools, and applications.
  - Enhanced functionality through standardized integrations.
- **For End-users**
  - More capable AI assistants and applications that can access personal or organizational data and perform actions.

### Learning & Community
- **Learn More Section**
  - Deep dives into MCP concepts and architecture.
  - Links from the homepage into conceptual and how-to documentation.
- **Community Navigation**
  - Dedicated "Community" section for communication and participation (details provided via linked community pages).

## Category
- Documentation & Learning Resources

## Tags
- documentation
- specification
- reference
