# AGENTS.md

## Google Analytics

- GA4 property: **Awesome Cropsteering** (`properties/428250291`), account "cropsteering.ixyz.ai". Web stream `https://cropsteering.ixyz.ai`, measurement ID `G-YL7SXRW1GB` (public, not a secret).
- Query live data with the `analytics-mcp` MCP server (user scope; tools `run_report`, `run_realtime_report`, `get_property_details`) using property ID `428250291`.
- Verified against the GA Admin API on 2026-10-22. Re-check with `get_account_summaries` before relying on it.
