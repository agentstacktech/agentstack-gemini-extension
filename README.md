# AgentStack extension for Gemini CLI

Connects [Gemini CLI](https://github.com/google-gemini/gemini-cli) to the AgentStack remote MCP server (`https://agentstack.tech/mcp`).

## Install

    gemini extensions install https://github.com/agentstacktech/agentstack-gemini-extension

On first use Gemini CLI signs you in via OAuth 2.1. API-key alternative: add `"headers": {"X-API-Key": "<your key>"}` to the server in `gemini-extension.json`.

## What you get

One tool, `agentstack.execute`, running batched steps over ~668 actions (hosting, storage, auth, payments, CRM, app builder).

Website: https://agentstack.tech · Official MCP Registry: `io.github.agentstacktech/agentstack`
