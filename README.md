# Starbase for coding agents

The [Starbase](https://starbase.cool) plugin for Claude Code and Codex. It adds:

- **The Starbase MCP server** (`https://starbase.cool/api/mcp`): about 30 tools to read and change your day, schedule, goals, habits, books and water.
- **The Starbase skill**: how to plan in Starbase (time zones, your work hours, undo).

You sign in to Starbase in your browser the first time. No token to copy.

## Claude Code

```
/plugin marketplace add JChouCode/starbase-agent
/plugin install starbase@starbase
```

Then run `/mcp`, pick **starbase** and sign in.

## Codex

```
codex plugin marketplace add JChouCode/starbase-agent
```

Then `/plugins` in Codex, install **Starbase**, and sign in when asked. Or add only the server: `codex mcp add starbase --url https://starbase.cool/api/mcp`, then `codex mcp login starbase`.

## Everything else

Cursor, the Claude app, ChatGPT and any other MCP client: open Starbase › Settings › AI & agents › **Setup guide**.

## What it can do

You choose **Read only** or **Read and change** when you sign in. Every change an agent makes is listed in Settings › AI & agents with Undo, and you can sign an app out there at any time.

## License

MIT
