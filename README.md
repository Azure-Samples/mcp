# Azure Model Context Protocol (MCP) Hub

Everything app devs need to build AI-powered tools that call real APIs. This hub links to code, servers, and SDKs for integrating [Model Context Protocol](https://modelcontextprotocol.io) (MCP) with Azure — fast.

## 🚀 Spin Up Your Own MCP Server
Run your own MCP server on Azure Functions in minutes:
- **[C# (.NET)](https://github.com/Azure-Samples/remote-mcp-functions-dotnet)**
- **[Python](https://github.com/Azure-Samples/remote-mcp-functions-python)**
- **[TypeScript / Node.js)](https://github.com/Azure-Samples/remote-mcp-functions-typescript)**

## 🧠 Build Agents that Use MCP
SDKs to create AI agents that talk to MCP servers:
- **[Python: OpenAI Agents SDK](https://github.com/openai/openai-agents-python/tree/main/examples/mcp)** — Works with any OpenAI-compatible endpoint (e.g. [Azure OpenAI](https://github.com/Azure-Samples/azure-openai-keyless-python))
- **[.NET: MCP C# SDK](https://github.com/modelcontextprotocol/csharp-sdk?tab=readme-ov-file#getting-started-client)** — Talk to any MCP server from a .NET client

## 🧩 Plug & Play MCP Servers
Drop in ready-to-go servers to power your agents with real APIs and infra — no extra coding needed.

> ⚠️ These are community-built projects. Not officially supported by Microsoft.

### 🗃️ Data APIs
- **[Redis](https://github.com/modelcontextprotocol/servers/tree/main/src/redis)** — Connect agents to [Azure Managed Redis](https://learn.microsoft.com/en-us/azure/redis/quickstart-create-managed-redis)
- **[PostgreSQL](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)** — Read-only queries on [Azure PostgreSQL](https://learn.microsoft.com/en-us/azure/postgresql/flexible-server/quickstart-create-server)
- **[MySQL](https://github.com/designcomputer/mysql_mcp_server)** — Connect agents to [Azure MySQL](https://learn.microsoft.com/en-us/azure/mysql/flexible-server/quickstart-create-server-cli)
- **[MongoDB](https://github.com/kiliczsh/mcp-mongo-server)** — Use LLMs to browse/query [Cosmos DB for MongoDB](https://learn.microsoft.com/en-us/azure/cosmos-db/mongodb/vcore/quickstart-portal)
- **[Azure Data Explorer (ADX)](https://github.com/pab1it0/adx-mcp-server)** — KQL querying through agents

### 🔧 DevOps & Infra APIs
- **[Azure CLI](https://github.com/jdubois/azure-cli-mcp)** — Natural language Azure command runner
- **[Kubernetes](https://github.com/Flux159/mcp-server-kubernetes)** — Manage [AKS clusters](https://learn.microsoft.com/en-us/azure/aks/learn/quick-kubernetes-deploy-azd) via agents
- **[Azure DevOps (Python)](https://github.com/Vortiago/mcp-azure-devops)** — Natural language DevOps Work Item access
- **[Azure DevOps (Node.js)](https://github.com/Tiberriver256/mcp-server-azure-devops)** — Manage repos, pipelines, boards
- **[GitHub](https://github.com/github/github-mcp-server)** — Use GitHub APIs via chat, code, or agents

