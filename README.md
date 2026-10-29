# Pledge for Claude, ChatGPT, Codex and Cursor

Create, send and store contracts with your agent. [Pledge](https://www.pledge.no) drafts contracts from your templates, shows them in the chat to edit, and sends them for e-signature when you say so.

The plugin is in [`plugins/pledge`](plugins/pledge): two skills and the address of Pledge's MCP server, `https://www.pledge.no/api/mcp`. See its [README](plugins/pledge/README.md) for what it does, what it sends and how to install it in each app.

Claude Code:

```bash
claude plugin marketplace add Ur-Solutions/pledge-plugin
claude plugin install pledge@pledge
```

Codex:

```bash
codex plugin marketplace add Ur-Solutions/pledge-plugin
codex plugin add pledge@pledge
```

Setup guide and support: [pledge.no/agents](https://www.pledge.no/agents). Privacy: [pledge.no/privacy](https://www.pledge.no/privacy). Contact: contact@ursolutions.no.
