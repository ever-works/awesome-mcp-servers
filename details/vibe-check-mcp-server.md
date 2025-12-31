# Vibe Check MCP Server

**Category:** MCP Middleware & Orchestration  
**Author/Brand:** pv-bhat  
**License:** MIT  
**Source:** https://github.com/PV-Bhat/vibe-check-mcp-server

Vibe Check MCP Server is an MCP middleware server that routes requests to a dedicated “vibe-check” agent. It is designed to give mentor-like feedback to AI agents before they proceed with tool calls or complex workflows, helping prevent tunnel vision, over-engineering, reasoning lock-in, and scope creep. It is intended for use in coding tasks, ambiguous tasks, and higher-risk workflows.

---

## Features

- **Mentor-like feedback for AI agents**  
  - Acts as a supervisory/mentor agent that reviews plans or next steps.  
  - Helps agents reassess direction before committing to a long chain of actions.

- **Prevents cascading errors and scope creep**  
  - Intercepts workflows to check if the agent is drifting from the user’s actual intent.  
  - Encourages simpler, “keep it simple” solutions instead of over-engineering.

- **Anti–tunnel-vision and anti–reasoning-lock mechanisms**  
  - Prompts the agent to reconsider assumptions and broaden its reasoning when it gets locked into a narrow path.  
  - Especially useful in multi-step, long-horizon tasks where early mistakes amplify.

- **MCP server integration layer**  
  - Implements a Model Context Protocol (MCP) server that other MCP-compatible clients or orchestrators can call.  
  - Designed to sit between user-facing agents and downstream tools/workflows.

- **Dedicated “vibe-check” agent**  
  - Separates the reviewing/guardrail role from the main task-performing agent.  
  - Can be treated as a reusable review component across multiple workflows.

- **Workflow and tool-call gating**  
  - Adds an explicit check-step before executing expensive or risky tool calls.  
  - Useful for orchestrated workflows where intermediate validation is required.

- **Applicable domains**  
  - Coding and software development flows.  
  - Ambiguous or open-ended tasks that benefit from clarification.  
  - High-risk tasks where misalignment or overreach is costly.

---

## Pricing

- No pricing information is specified in the repository content.  
- Distributed as open source under the MIT License; usage is subject to that license.