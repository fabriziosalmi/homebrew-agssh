# homebrew-agssh

Homebrew tap for **[agssh](https://github.com/fabriziosalmi/agssh)** — the deterministic,
fail-closed conformance runner for air-gapped static surfaces (AGSSH-STD-001).

## Install

```bash
brew install fabriziosalmi/agssh/agssh
agssh scan https://example.com
```

Installs both `agssh` (the CLI) and `agssh-mcp` (the MCP server:
`claude mcp add agssh -- agssh-mcp`).

The formula here is published automatically by GoReleaser on every
[agssh release](https://github.com/fabriziosalmi/agssh/releases). Apache-2.0 (agssh); MIT (this tap).
