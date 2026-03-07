## Overview

A Model Context Protocol (MCP) server that provides Google Calendar integration for AI assistants like Claude. This server enables AI assistants to manage your calendar events, check availability, and handle scheduling tasks.

## Popular Implementations

### nspady/google-calendar-mcp
Features include:
- **Multi-Account Support**: Manage multiple Google accounts
- **Multi-Calendar Support**: Work across different calendars
- **Cross-Account Conflicts**: Detection across accounts
- **Event Management**: Create, update, delete, and search
- **Recurring Events**: Modify recurring event series
- **Free/Busy Queries**: Check availability
- **Smart Scheduling**: Natural language understanding
- **Intelligent Import**: From images, PDFs, or web links

### guinacio/mcp-google-calendar
Another comprehensive implementation for Claude and other MCP clients to interact with Google Calendar.

### n8n Workflows
AI-powered workflow to automate Google Calendar operations using dynamic parameters and MCP integration.

## Key Scheduling Features

- List all calendars with timezone support
- Retrieve events with timezone support
- Find next available time slots with customizable search parameters
- Create new calendar events with attendees and notifications
- Automatic conflict detection when creating or updating events
- Warnings about overlapping events

## Assistant-Driven Workflows

- Daily and weekly planning
- Meeting scheduling
- Rescheduling
- Time-off planning
- Reporting
- Workload evaluation

## Example Usage

Users can say: "Schedule a client meeting for next Friday at 2 PM with john@company.com" and the AI assistant will create the meeting with Google Meet link automatically.

## Integration

Works with Cursor, Claude Desktop, Windsurf, and other MCP-compatible clients.