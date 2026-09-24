## Overview

The UpRes MCP server enables AI agents and assistants to upscale images and videos up to 8K resolution using 14 specialized AI models. Through the Model Context Protocol, agents can submit upscale jobs, monitor processing status, and retrieve enhanced media directly within agent workflows, IDEs, or automated pipelines.

## Key Features

- **14 Specialist Models**: Models optimized for photorealism, illustration, CGI, portraiture, anime, and generative video (including Flare, Prism, Lumen, Mirage, Motion, and Motion X)
- **High-Resolution Upscaling**: Upscale images and videos up to 8K with advanced detail synthesis and artifact reduction
- **Video Upscaling**: Enhance AI-generated video (Sora, Kling, Runway, Luma) with temporal consistency
- **Asynchronous Processing**: Submit jobs, poll status, and stream or download output when ready
- **CLI & MCP Support**: Native MCP server runner included in `upres-cli`

## Setup

Run directly with zero install via `npx`:

```json
{
  "mcpServers": {
    "upres": {
      "command": "npx",
      "args": ["-y", "github:auroracapital/upres-cli", "mcp"],
      "env": {
        "UPRES_API_KEY": "your_api_key_here"
      }
    }
  }
}
```

Or install globally:

```bash
npm install -g upres-cli
```

## Example Use Cases

- AI agents upscaling generated images before presenting to users
- Automated asset pipelines enhancing marketing graphics to print/4K resolution
- Enhancing AI video outputs from text-to-video models to 4K/8K
- Batch processing ecommerce product imagery with detail restoration
- Restoring historical or low-resolution photography

## Integration

The open-source CLI and MCP implementation is available at [github.com/auroracapital/upres-cli](https://github.com/auroracapital/upres-cli) and [npmjs.com/package/upres-cli](https://www.npmjs.com/package/upres-cli). It integrates with:
- Claude Desktop
- Cursor
- Windsurf
- Hermes Agent
- Any MCP-compatible client

## Pricing

Free tier includes 5 free upscales per month upon account creation. Paid plans start at $9/mo (Creator) for standalone web usage. Full API access for programmatic workflows and MCP integrations is available on the Studio plan ($39/mo, 250 stills + 90 min 4K video) and Business plans. See live pricing and plan comparisons at [upres.ai/pricing](https://upres.ai/pricing).
