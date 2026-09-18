# aurora-mcp-gateway

MCP (Model Context Protocol) server exposing governed tool access to
internal Aurora Logistics systems for AI agents (`aurora-routing-agent`,
`aurora-support-agent`). Wraps `aurora-shipments-api`,
`aurora-tracking-service`, and the warehouse database behind auditable
tools instead of agents calling internal APIs directly.

Mockup only — no real MCP server, just a tool manifest and
`catalog-info.yaml` to demonstrate Backstage cataloging an MCP server.

- Owner: `team-platform`
- System: `platform-engineering`
- Tool manifest: [`mcp-manifest.json`](./mcp-manifest.json)
