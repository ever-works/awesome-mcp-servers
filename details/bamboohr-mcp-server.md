# BambooHR MCP Server

BambooHR MCP Server is an MCP server integration that connects BambooHR’s online HR software for small and medium businesses with compatible chat or MCP-enabled applications.

---

## Overview
- **Type:** MCP server / integration
- **Category:** Human Resources, Business & Commerce MCP Servers
- **Purpose:** Provide programmable, tool-based access to BambooHR’s applicant and resume data from chat clients or other MCP-aware applications.
- **Intended users:** Small and medium businesses using BambooHR, HR teams, recruiters, and developers integrating HR workflows into chat or automation tools.

---

## Features

### MCP Server & Connectivity
- **Static MCP Server URL:**
  - `https://mcp.pipedream.net/v2` (single URL for all clients; authentication handled when adding the server to your app).
- **Client integration:**
  - Can be added to compatible chat clients (e.g., ChatGPT/OpenAI) and other MCP-aware applications.
  - Configuration guidance available through the Pipedream MCP configuration pages.
- **Account connection:**
  - Connects to your BambooHR account so you can manage HR-related data via tools.

### Available Tools (Actions)
The BambooHR MCP Server exposes the following tools as actions:

1. **Update Application Status**
   - Update the status of a job application in BambooHR.
   - Useful for progressing candidates through stages (e.g., applied, interviewing, hired, rejected).

2. **List Applications**
   - Retrieve a list of applications.
   - Supports pulling candidate application data for review, reporting, or automation.

3. **Get Application**
   - Fetch detailed information for a specific application.
   - Helps access candidate details, current status, and related metadata from BambooHR.

4. **Download Resume**
   - Download a resume associated with a specific application.
   - Enables storing or analyzing resumes outside the BambooHR UI through integrated tools.

5. **Add Application Comment**
   - Add comments to an existing application.
   - Supports collaboration and internal notes directly from integrated chat or automation workflows.

---

## Configuration
- **Sign-in & Authentication:**
  - Requires signing in with your Pipedream/BambooHR-connected account.
  - Authentication occurs when you add the MCP server URL to your application and complete the sign-in flow.

---

## Pricing
The provided content does not include any pricing or plan details for the BambooHR MCP Server or related services.