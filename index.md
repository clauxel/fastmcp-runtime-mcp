# FastMCP Runtime

FastMCP Runtime is a hosted remote MCP for hosted MCP server.

This repository is a public documentation project for FastMCP Runtime. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://fastmcpruntime.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=fastmcpruntime_public_docs&utm_content=readme_home
- Pricing: https://fastmcpruntime.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=fastmcpruntime_public_docs&utm_content=readme_pricing
- Checkout: https://fastmcpruntime.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=fastmcpruntime_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://fastmcpruntime.clauxel.com/mcp
- Server card: https://fastmcpruntime.clauxel.com/server-card.json
- Registry name: `com.clauxel.fastmcpruntime/fastmcpruntime-mcp`
- Tools: `runtime_health_check`, `tool_schema_list`, `fastmcp_call_proxy`, `usage_receipt_lookup`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: runtime_health_check
- MCP tool: tool_schema_list
- MCP tool: fastmcp_call_proxy
- MCP tool: usage_receipt_lookup

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
