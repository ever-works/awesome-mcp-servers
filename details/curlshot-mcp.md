# CurlShot MCP Server

Hosted MCP server for the CurlShot screenshot API. It lets an AI assistant render a public web page in a real browser and get it back as an image, a PDF, or a video of the page scrolling.

## Basic Info

- **Name:** CurlShot MCP Server
- **Category:** Browser Automation
- **Brand:** CurlShot
- **Source URL:** https://github.com/SergiuPogor/curlshot-mcp
- **MCP Endpoint:** `https://curlshot.com/api/mcp`
- **Tags:** `screenshot`, `web-screenshot`, `pdf`, `headless-browser`, `hosted`, `api`

## Features

- `take_screenshot` returns a page as PNG, JPEG, WebP, PDF, or a scrolling MP4, WebM, or GIF video.
- Full-page capture, phone and tablet device presets, custom viewport size, and dark mode.
- Capture of a single element by CSS selector, with ad and cookie-banner blocking on by default.
- `list_devices` lists the available device presets.
- Free plan of 100 screenshots a month with no card; paid plans start at $19 a month. Failed renders and cache hits are not counted.

## Setup & Configuration

- Add `https://curlshot.com/api/mcp` as a remote MCP server (streamable HTTP) in an MCP-compatible client such as Claude Code, Cursor, or VS Code.
- Send a CurlShot API key as the header `Authorization: [redacted secret]`. A free key is available at https://curlshot.com/register.
- The server itself is hosted and closed source; the linked repository holds the setup guide, the `server.json` manifest, and an agent skill.
