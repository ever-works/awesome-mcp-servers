# UpRes MCP Server

AI image and video upscaling up to 8K with 14 specialist models through the upres-cli MCP server: submit upscale jobs, track progress and fetch the results.

## Basic Info

- **Name:** UpRes MCP Server
- **Category:** Media Processing MCP Servers
- **Source URL:** https://upres.ai
- **npm:** https://www.npmjs.com/package/upres-cli
- **Tags:** `image-processing`, `video`, `video-editing`

## Features

- 14 specialist models for photorealism, illustration, CGI, portraits, anime and generative video (Flare, Prism, Lumen, Mirage, Motion, Motion X and more).
- Upscale images and videos up to 8K.
- Asynchronous jobs: submit, poll status, then download the result.
- The MCP server runner is part of `upres-cli`, the official CLI and SDK for upres.ai.

## Setup

- Install the CLI with `npm install -g upres-cli`, set `UPRES_API_KEY`, and start its MCP server with the `mcp` command (see the package README for client configuration).

## Pricing

Free tier with 5 upscales per month. API and MCP access is on the Studio and Business plans; see https://upres.ai/pricing.
