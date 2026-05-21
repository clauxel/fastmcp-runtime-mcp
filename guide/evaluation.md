# Evaluation Guide

Use this page to evaluate whether FastMCP Runtime fits a real workflow.

## What To Test

- hosted MCP server
- FastMCP Runtime
- FastMCP Runtime documentation
- FastMCP Runtime remote MCP
- fastmcpruntime server card

## Expected Evidence

- Open FastMCP Runtime and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://fastmcpruntime.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call runtime_health_check with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: team.

- https://fastmcpruntime.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=fastmcpruntime_public_docs&utm_content=evaluation_checkout
