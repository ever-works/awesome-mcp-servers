# Voice Monkey MCP Server

**Category:** Home Automation MCP Servers  
**Brand:** Pipedream  
**Website:** https://mcp.pipedream.com/app/voice_monkey

## Overview
Voice Monkey MCP Server integrates the Voice Monkey Alexa Skill with AI agents and MCP-compatible tools. It allows external applications to trigger Alexa routines and send dynamic text-to-speech announcements and visual media to Amazon Echo and other Alexa-enabled devices via a static MCP server endpoint.

## Features
- **Alexa Routine Triggering**
  - Trigger Alexa routines from external sources via MCP.
  - Uses the Voice Monkey Alexa Skill as the bridge to Alexa devices.

- **Dynamic Text-to-Speech Announcements**
  - Send custom, dynamic TTS announcements to Amazon Echo and other Alexa-enabled devices.
  - Suitable for alerts, notifications, and automated spoken messages.

- **Static MCP Server Endpoint**
  - Single static MCP server URL for all clients:
    - `https://mcp.pipedream.net/v2`
  - Authentication handled when adding the server to your MCP-compatible application.

- **Tooling / Actions Exposed as MCP Tools**  
  Four actions are available as tools:
  1. **Trigger Monkey**
     - Triggers a Voice Monkey "monkey" with custom parameters.
     - Can be used to initiate routines or announcements using flexible inputs.
  2. **Make Announcement**
     - Sends a direct text-to-speech announcement to a selected Alexa device.
     - Uses supplied text to generate speech on the device.
  3. **Display Video**
     - Displays a video on Alexa devices with screens (e.g., Echo Show).
     - Useful for visual alerts, media playback, or informational content.
  4. **Display Image**
     - Displays an image on screen-enabled Alexa devices.
     - Can be used for dashboards, status indicators, or visual notifications.

- **Multi-Client Support**
  - Designed to be added as an MCP server to various chat or agent clients.
  - Configuration guidance available per client type via Pipedream’s configuration page.

## Integrations
- **Alexa / Amazon Echo**
  - Works with Amazon Echo and other Alexa-enabled devices, including screen devices like Echo Show.
- **Voice Monkey Skill**
  - Relies on the Voice Monkey Alexa Skill to connect MCP actions to Alexa routines and announcements.

## Setup
- Connect a Voice Monkey account through Pipedream.
- Copy and use the static MCP server URL (`https://mcp.pipedream.net/v2`) in your MCP-capable app.
- Authenticate within your app and select the available Voice Monkey tools (Trigger Monkey, Make Announcement, Display Video, Display Image).

## Pricing
- Voice Monkey is described as a **free Skill**.  
- No additional pricing details are provided in the available content.