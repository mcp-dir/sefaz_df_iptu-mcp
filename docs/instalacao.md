# Instalação detalhada

SEFAZ DF: IPTU (Emissão Guia) é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_sefaz_df_iptu`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_sefaz_df_iptu` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_sefaz_df_iptu` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_sefaz_df_iptu` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.sefaz_df_iptu` (ou `servers.sefaz_df_iptu` no VS Code) do config do cliente e reinicie.
