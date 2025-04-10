# US Weather MCP Server Example

This repository contains a simple MCP (Model Control Protocol) server implementation for US weather forecasting using AI models.

## 🛰️ About

This MCP server provides an example of how to implement weather-based intelligence as an API-powered AI agent that integrates with GitMCP.

## 📦 Installation

To run this MCP server via GitMCP, no manual installation is needed. GitMCP will automatically fetch and run the server based on the configuration below.

However, for local development or testing, you can run:

```bash
npm install
npm run build
node ./build/index.js
```

## 🚀 GitMCP Configuration

To use this repository with GitMCP, include the following configuration:

```json
{
  "mcpServers": {
    "weather": {
      "command": "npx",
      "args": [
        "@dzarezenko/ai-weather-mcp@latest"
      ]
    }
  }
}
```

GitMCP will execute this command to start the MCP server.

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

You can simulate GitMCP behavior with:

```bash
npx mcp-remote https://gitmcp.io/microsoft/playwright-mcp
```
