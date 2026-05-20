# Quickstart

Agent Skill Update Gate is a hosted remote MCP for Claude Code skill update gate MCP.

## Fast Path

1. Open Agent Skill Update Gate and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://agentskillupdategate.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call check_skill_update_gate with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://agentskillupdategate.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=agentskillupdategate_public_docs&utm_content=quickstart_home
- https://agentskillupdategate.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=agentskillupdategate_public_docs&utm_content=quickstart_pricing
- https://agentskillupdategate.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=agentskillupdategate_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://agentskillupdategate.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
