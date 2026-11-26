# ultrafast

Local MCP server for making and editing videos as JSON scene documents rendered on the GPU (Metal or Vulkan) with no browser: build scenes with type, footage, 3D and shaders, look at frames, review every frame for clipped or unreadable text, and export H.264, HEVC or ProRes.

## Basic Info

- **Name:** ultrafast
- **Category:** Media Processing MCP Servers
- **Source URL:** https://github.com/ultrafastmov/ultrafast
- **Website:** https://ultrafast.mov
- **Tags:** `video`, `video-editing`, `animation`, `gpu`, `rust`, `local-server`

## Features

- 20 tools over stdio (`uf mcp`), including `ultrafast_new`, `ultrafast_edit`, `ultrafast_frame`, `ultrafast_sheet`, `ultrafast_review` and `ultrafast_export`.
- Scenes are JSON documents an agent can write, check and edit in place.
- Frames and contact sheets let the agent look at the result before exporting.
- Review flags clipped or unreadable text on every frame.
- Batch renders from a CSV, beat detection, voiceover, SVG import and OCR.
- Self-hosted HTTP API with a remote `/mcp` endpoint on your own `uf serve`.

## Setup

- Install: `curl -fsSL https://ultrafast.mov/install.sh | sh` (macOS Apple silicon, Linux x86_64), `brew install ultrafastmov/tap/ultrafast`, `cargo install ultrafast`, or the Docker image `ghcr.io/ultrafastmov/ultrafast`.
- Claude Code: `claude mcp add ultrafast -- uf mcp`. Codex: `codex mcp add ultrafast -- uf mcp`. Other clients: `{"command": "uf", "args": ["mcp"]}`.
- On Linux it needs the GPU's Vulkan driver and ffmpeg for exports. No account or API key.
- License: Apache-2.0 or MIT.
