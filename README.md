# US Weather MCP Server Example

This repository contains a simple MCP (Model Control Protocol) server implementation for US weather forecasting using AI models.

## 🛰️ About

This MCP server provides an example of how to implement weather-based intelligence as an API-powered AI agent.

## 📦 Installation

To run this MCP server, no manual installation is needed.

However, for local development or testing, you can run:

```bash
npm install
npm run build
node ./build/index.js
```

## 🚀 Claude Configuration

To use this repository with Claude, include the following configuration:

```json
{
  "mcpServers": {
    "weather": {
      "command": "npx",
      "args": [
        "ai-weather-mcp@latest"
      ]
    }
  }
}
```

## 📁 Project Structure

- `cli.js` – Entry point for the MCP server.
- `package.json` – Configures the package and CLI usage.
- `README.md` – This file.

## 🛠️ Development

To run the MCP server locally:

```bash
npm install
npm run build
node ./build/index.js
```
