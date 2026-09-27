# Mailows for Grok

Remote MCP plugin that connects Grok Build to the hosted Mailows server at `https://mcp.mailows.com/mcp`.

Mailows gives AI agents their own real email inboxes — not a shared human mailbox. Each agent gets a dedicated address on your domain; you decide which inboxes it may touch and can revoke grants independently.

## Install

Once listed in the xAI plugin marketplace:

```bash
grok plugin install mailows --trust
```

Or add the remote server directly:

```bash
grok mcp add --transport http mailows https://mcp.mailows.com/mcp
```

First use triggers an OAuth browser flow (authorization code + PKCE). Tokens stay in the MCP client credential store.

## Docs

- User guide: https://www.mailows.com/mcp-manual
- Privacy: https://www.mailows.com/privacy
- Support: support@mailows.com

Operator: DW Technology LLC.
