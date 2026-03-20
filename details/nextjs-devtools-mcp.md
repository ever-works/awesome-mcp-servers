## Overview

Next.js DevTools MCP is an official Vercel server that provides seamless integration between AI assistants and Next.js 16+ development servers. It automatically discovers and connects to the built-in MCP endpoint in running Next.js projects.

## Features

### Automatic Discovery
- Detects running Next.js dev servers automatically
- Connects to built-in MCP endpoint at `http://localhost:PORT/_next/mcp`
- No manual configuration required
- Hot reload support
- Multi-project support

### Development Assistance
- Real-time code analysis
- Component inspection
- Route debugging
- API endpoint testing
- Build error diagnosis
- Performance profiling
- Bundle analysis

### Next.js 16+ Integration
- Full App Router support
- Server Components debugging
- Client Components analysis
- Server Actions inspection
- Middleware debugging
- Edge Runtime support

### Developer Tools
- Live component tree inspection
- Props and state visualization
- Network request monitoring
- Console log aggregation
- Source map support
- TypeScript integration

## Use Cases

- AI-assisted Next.js development
- Debugging complex component hierarchies
- Performance optimization
- Code review and refactoring
- Learning Next.js best practices
- Troubleshooting build issues
- API route testing
- Deployment preparation

## Supported Features

### App Router (Next.js 13+)
- Server Components
- Client Components
- Layouts and templates
- Loading and error states
- Route groups
- Parallel and intercepting routes

### API Routes
- REST API debugging
- GraphQL endpoint testing
- Middleware inspection
- Request/response analysis

### Build Analysis
- Bundle size optimization
- Code splitting analysis
- Import path optimization
- Unused code detection

## Technical Implementation

Built and maintained by Vercel, ensuring perfect compatibility with Next.js features and updates. Uses Next.js's built-in developer tooling infrastructure.

## Integration

Works with any Next.js 16+ project in development mode. Compatible with Claude Desktop, Cursor, VS Code, and other MCP clients. Automatically available when starting a Next.js development server.

## Requirements

- Next.js 16 or higher
- Development mode (next dev)
- MCP-compatible AI assistant

## Developer Experience

Zero configuration required - just start your Next.js dev server and the MCP endpoint becomes available automatically. AI assistants can immediately access development tools and information.