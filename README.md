# 🌤️ Weather MCP Server

**weather-mcp-server** is a simple MCP (Model Context Protocol) server that provides real-time weather alerts and forecasting data. This project is intended as a lightweight weather backend for AI agents, voice assistants, or simple CLI clients.

---

## 🧰 Features

- 🌪️ **Weather Alerts** by U.S. state
- 🌦️ **7-Day Weather Forecasts** by latitude & longitude
- 📡 **MCP-Compliant** interface for easy agent integration
- 🐳 **Docker Support** for containerized deployment

---

## 🚀 Getting Started

### 🛠 Prerequisites

- Python 3.11+
- [`uv`](https://astral.sh/uv/) package manager
- Docker (optional)

---

### 📦 Install Dependencies & Test your server

```bash
uv venv
uv add "mcp[cli]" 
uv run mcp dev server/weather.py
