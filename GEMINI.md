# AgentStack

AgentStack (https://agentstack.tech) is a backend platform for AI agents, exposed as a remote MCP server at https://agentstack.tech/mcp (Streamable HTTP).

- Single tool: `agentstack.execute` — runs batched steps (up to 50) over ~668 actions: hosting, storage, auth, payments, CRM, App Studio.
- Start a session with `auth.get_profile`, then `projects.get`, then pass `context.project_id` in later steps.
- Auth: OAuth 2.1 (dynamic client registration + PKCE) — Gemini CLI opens the browser on first use. Alternatively set header `X-API-Key`.
