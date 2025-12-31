# BigML MCP Server

## Overview
BigML MCP Server is an MCP-compatible integration that connects MCP clients to BigML’s machine learning platform. It lets you build, train, and operationalize machine learning models through standardized MCP calls using a single static server URL.

- **Type:** MCP server / developer tool
- **Category:** AI integration (MCP servers)
- **Provider:** BigML via Pipedream
- **Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Provides a static MCP server URL usable across compatible clients.
- Authentication handled when adding the server to your MCP-enabled application.
- Designed to work with multiple chat or MCP clients (configured per client).

### BigML Platform Operations (Tools / Actions)
The server exposes BigML operations as MCP tools (currently 3 actions):

1. **Create Source (Remote URL)**
   - Create a BigML data source from a remote URL.
   - BigML downloads the data file directly from the provided URL.
   - Intended as the first step in the ML workflow (ingesting data into BigML).

2. **Create Model**
   - Create a machine learning model in BigML.
   - Can be based on:
     - A source ID
     - A dataset ID
     - An existing model ID
   - Supports building supervised models as part of an end-to-end ML pipeline.

3. **Create Batch Prediction**
   - Generate batch predictions using an existing supervised model and dataset.
   - Requires:
     - A Supervised Model ID
     - A Dataset ID
   - Enables operationalizing trained models at scale via batch inference.

### Operationalization & Deployment
- Enables company-wide operationalization of machine learning using BigML through MCP.
- Can run in any environment where your MCP client operates, while BigML handles the ML workload in the cloud or on-prem (per BigML’s platform capabilities).

## Pricing
Pricing information is not provided in the available content. Use of this MCP server may be subject to:
- BigML account / plan pricing, and
- Any applicable Pipedream or platform usage terms.

For current pricing, refer to BigML and/or Pipedream pricing documentation directly.