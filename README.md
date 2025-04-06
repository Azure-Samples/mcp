# Azure Model Context Protocol (MCP) Hub

A developer-focused hub with code samples, tools, and resources to build or integrate [Model Context Protocol](https://modelcontextprotocol.io) (MCP) servers on Azure. Use it to create AI agents and tools that interact naturally with real-world systems.

## 🚀 Deploy Your Own MCP Server
Launch an MCP server on Azure Functions using your language of choice:
- **[C# (.NET)](https://github.com/Azure-Samples/remote-mcp-functions-dotnet)**
- **[Python](https://github.com/Azure-Samples/remote-mcp-functions-python)**
- **[TypeScript / Node.js](https://github.com/Azure-Samples/remote-mcp-functions-typescript)**

## 🧠 Build AI Agents with MCP
Create AI agents that talk to MCP servers:
- **[Python: OpenAI Agents SDK (MCP)](https://github.com/openai/openai-agents-python/tree/main/examples/mcp)** — works with [Azure OpenAI](https://github.com/Azure-Samples/azure-openai-keyless-python)
- **[C# (.NET): Semantic Kernel Plugin](https://github.com/microsoft/semantic-kernel/tree/main/dotnet/samples/Demos/ModelContextProtocolPlugin)** — turn MCP tools into Kernel functions

## 🧩 Use Plug-and-Play MCP Servers
Drop in community-built servers to give your agents superpowers with familiar APIs and cloud services.

> ⚠️ Community/partner-built — not officially supported by Microsoft. Use at your own risk.

### 🗃️ Data MCP Servers
- **[Redis](https://github.com/modelcontextprotocol/servers/tree/main/src/redis)** — Interact with [Azure Managed Redis](https://learn.microsoft.com/en-us/azure/redis/quickstart-create-managed-redis)
- **[PostgreSQL](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)** — Schema-aware read-only queries on [Azure PostgreSQL](https://learn.microsoft.com/en-us/azure/postgresql/flexible-server/quickstart-create-server)
- **[MySQL](https://github.com/designcomputer/mysql_mcp_server)** — AI-to-[Azure MySQL](https://learn.microsoft.com/en-us/azure/mysql/flexible-server/quickstart-create-server-cli) communication
- **[MongoDB](https://github.com/kiliczsh/mcp-mongo-server)** — Use LLMs to explore and query [Cosmos DB for MongoDB](https://learn.microsoft.com/en-us/azure/cosmos-db/mongodb/vcore/quickstart-portal)
- **[Azure Data Explorer (ADX)](https://github.com/pab1it0/adx-mcp-server)** — Run KQL queries through AI agents

### 🔧 DevOps & Infra MCP Servers
- **[Azure CLI](https://github.com/jdubois/azure-cli-mcp)** — Run Azure commands using natural language
- **[Kubernetes](https://github.com/Flux159/mcp-server-kubernetes)** — Manage [AKS clusters](https://learn.microsoft.com/en-us/azure/aks/learn/quick-kubernetes-deploy-azd) with natural language
- **[mcp-azure-devops (Python)](https://github.com/Vortiago/mcp-azure-devops)** — Work with Azure DevOps Work Items
- **[mcp-server-azure-devops (Node.js)](https://github.com/Tiberriver256/mcp-server-azure-devops)** — Manage repos, pipelines, and boards
- **[GitHub](https://github.com/github/github-mcp-server)** — Interact with GitHub APIs via chat or code

