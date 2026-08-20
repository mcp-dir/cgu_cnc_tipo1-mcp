# Instalação detalhada

Controladoria-Geral da União: Certidão Negativa Correcional - Entes Privados (ePAD, CGU-PJ, CEIS, CNEP e CEPIM) é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_cgu_cnc_tipo1`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_cgu_cnc_tipo1` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_cgu_cnc_tipo1` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_cgu_cnc_tipo1` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.cgu_cnc_tipo1` (ou `servers.cgu_cnc_tipo1` no VS Code) do config do cliente e reinicie.
