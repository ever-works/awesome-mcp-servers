## Overview

Azure MCP Agent with LangChain.js is a reference implementation demonstrating how to build AI agents that interact with real-world APIs using the Model Context Protocol. It features a burger ordering system with serverless API integration.

## Architecture

### Components
- **LangChain.js**: AI agent framework for reasoning and tool calling
- **Model Context Protocol**: Standardized interface for AI tools
- **Azure Functions**: Serverless API backend
- **Burger Restaurant API**: Example real-world integration

### Agent Capabilities
- Order processing
- Menu querying
- Availability checking
- Order customization
- Payment handling

## Features

### MCP Integration
- Tool definition and registration
- Request/response handling
- Error management
- State persistence

### LangChain.js Integration
- Agent reasoning
- Tool selection
- Chain composition
- Memory management

### Azure Serverless
- Function app deployment
- HTTP triggers
- Cosmos DB integration
- Application Insights

### Restaurant Operations
- Menu management
- Order creation
- Inventory tracking
- Order history
- Customer management

## Use Cases

- Building AI agents for business APIs
- E-commerce integration
- Customer service automation
- Order management systems
- Serverless AI applications
- Real-world MCP examples

## Implementation Patterns

### Tool Definition
```typescript
const orderBurgerTool = {
  name: 'order_burger',
  description: 'Order a burger with customizations',
  parameters: { /* schema */ }
};
```

### Agent Setup
```typescript
const agent = createAgent({
  tools: [orderBurgerTool],
  llm: model,
  memory: chatHistory
});
```

### API Integration
```typescript
const result = await fetch(apiUrl, {
  method: 'POST',
  body: JSON.stringify(order)
});
```

## Technical Stack

- **Language**: TypeScript
- **Framework**: LangChain.js
- **Runtime**: Node.js
- **Cloud**: Azure Functions
- **Database**: Azure Cosmos DB
- **Monitoring**: Application Insights

## Deployment

### Azure Resources
- Function App
- Cosmos DB account
- Application Insights
- Storage account

### Configuration
- Environment variables
- Connection strings
- API keys
- Function settings

## Learning Outcomes

### MCP Concepts
- Tool creation and registration
- Protocol message handling
- Error handling patterns
- State management

### LangChain Patterns
- Agent design
- Tool calling
- Chain composition
- Memory systems

### Azure Integration
- Serverless deployment
- API design
- Data persistence
- Monitoring and logging

## Example Interactions

**User**: "I'd like to order a cheeseburger with extra pickles"
**Agent**: Processes order → Checks availability → Creates order → Confirms

**User**: "What burgers do you have?"
**Agent**: Queries menu → Formats response → Returns options

## Integration

Reference implementation for building production MCP agents. Demonstrates best practices for real-world API integration with error handling, validation, and user experience considerations.