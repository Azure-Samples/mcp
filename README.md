# Azure Model Context Protocol (MCP) Hub

**Build AI agents that work with real-world APIs — fast.** This guide helps app developers in any language get up and running with [Model Context Protocol](https://modelcontextprotocol.io) (MCP) on Azure: spin up servers, write agents, or use ready-made ones.

---

## 🚀 1. Create Your Own MCP Server

Use Azure Functions to host your own MCP server. Pick your stack:

- **[.NET](https://github.com/Azure-Samples/remote-mcp-functions-dotnet)**
- **[Python](https://github.com/Azure-Samples/remote-mcp-functions-python)**
- **[TypeScript ](https://github.com/Azure-Samples/remote-mcp-functions-typescript)**

---

## 🧠 2. Build AI Agents with MCP

Write agents that can use tools exposed by any MCP server. Use your preferred language or AI SDK:

### ✅ Official MCP SDKs

Use these SDKs to write MCP clients (agents) that can talk to MCP servers:

- **[.NET SDK](https://github.com/modelcontextprotocol/csharp-sdk)**
- **[Python SDK](https://github.com/modelcontextprotocol/python-sdk)**
- **[TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk)**
- **[Java SDK](https://github.com/modelcontextprotocol/java-sdk)**

### 🤖 AI SDK Integrations

Combine with popular AI agent frameworks:

- **[Python: OpenAI Agents SDK](https://openai.github.io/openai-agents-python/mcp/)** — Use `MCPServerSse` with [Azure OpenAI](https://github.com/Azure-Samples/azure-openai-keyless-python)
- **[.NET: Semantic Kernel](https://devblogs.microsoft.com/semantic-kernel/integrating-model-context-protocol-tools-with-semantic-kernel-a-step-by-step-guide/)** — Add MCP tools to your Kernel instance
- **[Java: Spring AI](https://docs.spring.io/spring-ai/reference/api/mcp/mcp-client-boot-starter-docs.html)** — Auto-configure MCP in Spring Boot apps

---

## 🧩 3. Use Prebuilt MCP Servers

Skip building your own — these open-source servers expose familiar APIs via MCP.

> ⚠️ Community maintained. Not officially supported by Microsoft.

### 🗃️ Data APIs

- **[Azure AI Agents](https://devblogs.microsoft.com/foundry/integrating-azure-ai-agents-mcp/)** - Access Bing for web data and Azure AI Search for your private data 
- **[Redis](https://github.com/modelcontextprotocol/servers/tree/main/src/redis)** — Works with [Azure Redis](https://learn.microsoft.com/en-us/azure/redis/quickstart-create-managed-redis)
- **[PostgreSQL](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)** — Connect to [Azure PostgreSQL](https://learn.microsoft.com/en-us/azure/postgresql/flexible-server/quickstart-create-server)
- **[MySQL](https://github.com/designcomputer/mysql_mcp_server)** — For [Azure MySQL](https://learn.microsoft.com/en-us/azure/mysql/flexible-server/quickstart-create-server-cli)
- **[MongoDB](https://github.com/kiliczsh/mcp-mongo-server)** — For [Cosmos DB with MongoDB](https://learn.microsoft.com/en-us/azure/cosmos-db/mongodb/vcore/quickstart-portal)
- **[Azure Data Explorer (ADX)](https://github.com/pab1it0/adx-mcp-server)** — Run KQL with agents

### 🔧 Dev & Infra APIs

- **[Azure CLI](https://github.com/jdubois/azure-cli-mcp)** — Natural language access to Azure CLI
- **[Kubernetes](https://github.com/Flux159/mcp-server-kubernetes)** — Manage [AKS clusters](https://learn.microsoft.com/en-us/azure/aks/learn/quick-kubernetes-deploy-azd)
- **[GitHub](https://github.com/github/github-mcp-server)** — Talk to GitHub with chat or code
---
