# Amazon Nova Canvas MCP Server

## Overview
Amazon Nova Canvas MCP Server is a Model Context Protocol (MCP) server for generating images via Amazon Nova Canvas. It is designed to be used by conversational assistants and creative agents, providing text-based and color-guided image generation with flexible parameters and AWS-integrated authentication.

- **Category:** Media Processing MCP Servers  
- **Brand:** Amazon Web Services  
- **Source:** https://awslabs.github.io/mcp/servers/nova-canvas-mcp-server

## Features

### Text-based image generation
- Generate images from natural-language text prompts using the `generate_image` tool.
- Configure image dimensions in the range **320–4096 px**.
- Choose image quality options (e.g., higher quality vs. faster/cheaper, as provided by Nova Canvas).
- Use **negative prompting** to specify what should be avoided in the output.
- Generate **multiple images per request** (1–5 images).
- Control guidance with **`cfg_scale` parameter** (range **1.1–10.0**) to tune prompt adherence vs. creativity.
- Use **seeded generation** for reproducible outputs.

### Color-guided image generation
- Generate images guided by color palettes using the `generate_image_with_colors` tool.
- Specify up to **10 hex color values** to shape the image’s style, palette, and mood.
- Inherits the same customization options as text-based generation:
  - Dimensions (320–4096 px)
  - Quality options
  - Negative prompts
  - Multiple images per request (1–5)
  - `cfg_scale` control
  - Seeded generation

### Workspace integration
- Save generated images into **user-specified workspace directories**.
- **Automatic folder creation** if the target directory does not exist.

### AWS authentication & integration
- Uses **AWS profiles** (e.g., via `AWS_PROFILE`) for secure access.
- Connects to **Amazon Bedrock** and **Amazon Nova Canvas** services.
- Relies on standard AWS credential mechanisms (e.g., `aws configure` or environment variables).

## Prerequisites
- **uv** installed (from Astral or GitHub).
- **Python 3.10** installed via `uv python install 3.10`.
- **AWS account** with:
  - Amazon Bedrock enabled.
  - Amazon Nova Canvas enabled.
- **AWS credentials** configured with permissions for Amazon Bedrock and Nova Canvas (via `aws configure` or environment variables, with a suitable IAM role/user).

## Installation & Configuration

### General MCP configuration example (e.g., Amazon Q Developer CLI)
- Configure in your MCP client (such as `~/.aws/amazonq/mcp.json`) to run via `uvx`, including environment variables:
  - `AWS_PROFILE`
  - `AWS_REGION`
  - `FASTMCP_LOG_LEVEL`
- Server is typically configured as a **stdio** MCP server with `awslabs.nova-canvas-mcp-server@latest` as the tool reference.

### Windows installation
- Use `uv` with `tool run --from awslabs.nova-canvas-mcp-server@latest awslabs.nova-canvas-mcp-server.exe`.
- Configure MCP server entry with:
  - `type`: `stdio`
  - `timeout` (e.g., 60 seconds)
  - Environment variables: `AWS_PROFILE`, `AWS_REGION`, `FASTMCP_LOG_LEVEL`.

### Docker
- Can be run via Docker after building the image:
  - `docker build -t awslabs/nova-canvas-mcp-server .`
  - (Then configure MCP client to talk to the container, as appropriate.)

## Pricing
- The documentation provided does **not** specify pricing for the Amazon Nova Canvas MCP Server itself.
- Usage costs are likely governed by **standard AWS pricing** for Amazon Bedrock and Amazon Nova Canvas; consult AWS pricing pages for details.