# Day 1 — AI Learning: MCP Concepts

## MCP Kya Hai?
Model Context Protocol (MCP) ek open-source standard hai jo AI applications ko external data sources, tools aur workflows se connect karta hai. Isko AI ka "USB-C port" samajh sakte hain.

## 3 Core Concepts

1. **Resources** — File-like data jo client padh sakta hai. @mcp.resource() decorator se expose karte hain.

2. **Tools** — Executable functions jo LLM user ke approval ke saath call kar sakta hai. @mcp.tool() decorator se define karte hain.

3. **Prompts** — Pre-written prompt templates. @mcp.prompt() decorator se set kiya jata hai.

## Transport Types
- **STDIO** — Local aur CLI communication.
- **HTTP** — Remote aur web deployment.

## Strict Rules
- **No stdout prints in STDIO:** print() nahi karna.
- **Logging:** Hamesha stderr par (logging module).

## Mera Server (weather.py)
- 2 tools:
  1. get_alerts(state) — US weather alerts
  2. get_forecast(lat, lon) — US location forecast

## Status
✅ Day 1 AI Learning Complete
