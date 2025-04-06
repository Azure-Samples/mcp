# Azure Model Context Protocol (MCP) Hub

This repo links to samples, tools, and resources for building and integrating [Model Context Protocol](https://modelcontextprotocol.io) (MCP) servers on Azure using multiple languages. Whether you're spinning up your own MCP server or consuming existing ones, this hub will help you get started fast with Agentic Tools and AI Agents.

## 🚀 Build MCP Servers on Azure
Deploy your own MCP server with Azure Functions:
- **C# (.NET)** – [Sample](https://github.com/Azure-Samples/remote-mcp-functions-dotnet)
- **Python** – [Sample](https://github.com/Azure-Samples/remote-mcp-functions-python)
- **TypeScript / Node.js** – [Sample](https://github.com/Azure-Samples/remote-mcp-functions-typescript)


## 🧠 Build AI Agents with MCP
Use these SDKs to integrate any MCP server with AI agents:
- **Python** – [OpenAI Agents SDK (MCP Example)](https://github.com/openai/openai-agents-python/tree/main/examples/mcp) using any OpenAI-compatible endpoint (e.g., [Azure OpenAI](https://github.com/Azure-Samples/azure-openai-keyless-python))
- **C# (.NET)** – [Semantic Kernel MCP Plugin](https://github.com/microsoft/semantic-kernel/tree/main/dotnet/samples/Demos/ModelContextProtocolPlugin) to convert MCP tools into Kernel functions

## 🧩 Plug-and-Play MCP Servers
Use community-built MCP servers to connect AI Agents to familiar APIs.

> ⚠️ These are community/partner-contributed and not officially supported by Microsoft. Use at your own discretion.

### Data
- **[Redis](https://github.com/modelcontextprotocol/servers/tree/main/src/redis)** – Interact with [Azure Managed Redis](https://learn.microsoft.com/en-us/azure/redis/quickstart-create-managed-redis) via LLMs
- **[PostgreSQL](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)** – Read-only queries with schema inspection using [Azure PostgreSQL](https://learn.microsoft.com/en-us/azure/postgresql/flexible-server/quickstart-create-server)
- **[Azure Data Explorer (ADX)](https://github.com/pab1it0/adx-mcp-server)** – Run Kusto (KQL) queries via AI agents

### DevOps
- **[GitHub MCP Server](https://github.com/github/github-mcp-server)** – Natural language access to GitHub APIs
- **[mcp-azure-devops (Python)](https://github.com/Vortiago/mcp-azure-devops)** – Natural language access to Azure DevOps Work Items
- **[mcp-server-azure-devops (Node.js)](https://github.com/Tiberriver256/mcp-server-azure-devops)** – Manage repos, pipelines, projects, etc.

