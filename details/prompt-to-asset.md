## Overview

prompt-to-asset is an MCP server and CLI that routes image-generation prompts to 30+ models through a single interface. It abstracts away the API differences between DALL-E, Stable Diffusion, Flux, Midjourney, and other providers so agents and developers can generate images without managing multiple provider SDKs.

## Features

- Route to 30+ image-generation models from a single MCP tool
- Supports DALL-E, Stable Diffusion, Flux, Midjourney, and more
- CLI and MCP server interfaces
- Install via npm: `npm install -g prompt-to-asset`
- Uniform output format across all providers
