# Google Calendar MCP Server

## Description
An open-source Model Context Protocol (MCP) server that lets Claude interact with your Google Calendar to list events, create and update meetings, delete events, and find free time slots.

## Features
- **Google Calendar integration** via OAuth 2.0
- **Event listing**
  - Retrieve events from your Google Calendar (`list_events`)
- **Event creation**
  - Create new calendar events/meetings (`create_event`)
- **Event updating**
  - Modify existing events (`update_event`)
- **Event deletion**
  - Remove events from your calendar (`delete_event`)
- **Free time discovery**
  - Find available time slots based on your calendar (`find_free_time`)
- **Claude integration**
  - Exposes tools to Claude Desktop through MCP so you can issue natural language commands to manage calendar data
- **Configurable via environment variables**
  - Uses environment variables for credentials and configuration (e.g., OAuth client details, refresh token)
- **Logging and troubleshooting**
  - Supports viewing MCP server logs (e.g., via Claude log files)
  - Guidance for diagnosing authentication, environment variable, and server connection issues

## Prerequisites
- A **Google Cloud Project**
- **OAuth consent screen** configured with Calendar scopes:
  - `https://www.googleapis.com/auth/calendar`
  - `https://www.googleapis.com/auth/calendar.events`
- **OAuth 2.0 credentials** (client ID and client secret)
- A **refresh token** obtained via the provided `getToken.js` script
- **Claude Desktop** (MacOS or Windows) configured to use this MCP server
- Node.js environment to build and run the server

## Setup & Integration (High-Level)
- Create and configure a Google Cloud project and OAuth consent screen.
- Generate OAuth 2.0 credentials and enable the Calendar API with the listed scopes.
- Use `getToken.js` to obtain a refresh token using your client ID and client secret.
- Configure environment variables with the OAuth credentials and refresh token.
- Build and run the MCP server with Node.js.
- Add the server configuration to Claude Desktop so the tools appear within Claude.

## Tools Provided
- `list_events` – List events from your Google Calendar.
- `create_event` – Create a new calendar event.
- `update_event` – Update details of an existing event.
- `delete_event` – Delete an event from your calendar.
- `find_free_time` – Find free/available time slots based on your calendar data.

## Pricing
- **Cost**: Free, open source (MIT-licensed). Any cloud or API usage costs are subject to your own Google Cloud/Google Workspace billing.

## License
- **MIT License** (see `LICENSE` in the repository).

## Source
- Repository: https://github.com/v-3/google-calendar