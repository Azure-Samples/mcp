# Azure Model Context Protocol (MCP) Hub

**Build AI agents that call real APIs — fast.** Whether you're a C#, Python, Java, or JavaScript developer, this hub helps you build, run, or reuse [Model Context Protocol](https://modelcontextprotocol.io) (MCP) servers on Azure to power your AI agents.

---

## 🚀 1. Run Your Own MCP Server
Host your own MCP server using Azure Functions — pick your language:
- **[C#](https://github.com/Azure-Samples/remote-mcp-functions-dotnet)**
- **[Python](https://github.com/Azure-Samples/remote-mcp-functions-python)**
- **[TypeScript](https://github.com/Azure-Samples/remote-mcp-functions-typescript)**

---

## 🧠 2. Build Agents That Use MCP
Use official SDKs or your favorite AI frameworks to write agents that connect to any MCP server.

### ✅ Official MCP SDKs (Build Clients, Servers, or Tools in Any Language)
- **[C# SDK](https://github.com/modelcontextprotocol/csharp-sdk)**
- **[Python SDK](https://github.com/modelcontextprotocol/python-sdk)**
- **[TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk)**
- **[Java SDK](https://github.com/modelcontextprotocol/java-sdk)**

### 🤖 AI SDK Integrations
- **[Python: OpenAI Agents SDK](https://openai.github.io/openai-agents-python/mcp/)** — Use MCPServerSse with [Azure OpenAI](https://github.com/Azure-Samples/azure-openai-keyless-python)
- **[C#: Semantic Kernel](https://devblogs.microsoft.com/semantic-kernel/integrating-model-context-protocol-tools-with-semantic-kernel-a-step-by-step-guide/)** — Add MCP tools to your Kernel instance
- **[JavaScript: LangChain.js](https://changelog.langchain.com/announcements/mcp-adapters-for-langchain-and-langgraph)** — Use MCP tools in LangChain or LangGraph agents
- **[Java: Spring AI](https://docs.spring.io/spring-ai/reference/api/mcp/mcp-client-boot-starter-docs.html)** — Plug into Spring Boot with auto-config
- **[Azure AI Agents](https://devblogs.microsoft.com/foundry/integrating-azure-ai-agents-mcp/)** — Add Bing + Azure AI Search to your agent

---

## 🧩 3. Use Plug-and-Play MCP Servers
Don't want to build your own tools? These servers expose real APIs via MCP so your agents can just call them.

> ⚠️ These servers are open source and maintained by the community. Microsoft does not review, support, or endorse them. Use at your own discretion.

### 🗃️ Data APIs
- **[Redis](https://github.com/modelcontextprotocol/servers/tree/main/src/redis)** — Access [Azure Redis](https://learn.microsoft.com/en-us/azure/redis/quickstart-create-managed-redis)
- **[PostgreSQL](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)** — Query [Azure PostgreSQL](https://learn.microsoft.com/en-us/azure/postgresql/flexible-server/quickstart-create-server)
- **[MySQL](https://github.com/designcomputer/mysql_mcp_server)** — Use with [Azure MySQL](https://learn.microsoft.com/en-us/azure/mysql/flexible-server/quickstart-create-server-cli)
- **[MongoDB](https://github.com/kiliczsh/mcp-mongo-server)** — Talk to [Cosmos DB with MongoDB](https://learn.microsoft.com/en-us/azure/cosmos-db/mongodb/vcore/quickstart-portal)
- **[Azure Data Explorer (ADX)](https://github.com/pab1it0/adx-mcp-server)** — Run KQL queries via agent

### 🔧 Dev & Infra APIs
- **[Azure CLI](https://github.com/jdubois/azure-cli-mcp)** — Run CLI commands with natural language
- **[Kubernetes](https://github.com/Flux159/mcp-server-kubernetes)** — Control [AKS clusters](https://learn.microsoft.com/en-us/azure/aks/learn/quick-kubernetes-deploy-azd)
- **[GitHub](https://github.com/github/github-mcp-server)** — Access GitHub APIs via chat or agent
- **[Azure DevOps (Python)](https://github.com/Vortiago/mcp-azure-devops)** — Work item support
- **[Azure DevOps (Node.js)](https://github.com/Tiberriver256/mcp-server-azure-devops)** — Repos, pipelines, and boards

---

## 📚 Learn More
- 📄 [Model Context Protocol Spec](https://modelcontextprotocol.io)
- 🧪 Explore sample agents, tools, and servers in the linked repos
- 🤝 Contribute a new server or tool via PR!

