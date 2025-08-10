### 1. Custom MCP Servers (Servers Made By You)

You can build your own **custom MCP servers** tailored to your specific needs. These are programs or services that expose data, tools, or functions to AI models using the MCP standard (JSON-RPC 2.0). Key details:

- Typically built using languages like Python, JavaScript, Go, etc., running locally or remotely.
- Implement "tools" as endpoints that AI models call for searching, fetching data, executing commands, etc.
- Allow integration with **any private or specialized data sources** such as your own databases, code repositories, internal APIs, or custom applications.
- Examples include a custom server that visualizes GitHub code, performs academic paper search, or accesses proprietary business data.
- Open-source frameworks and tutorials are available to help build MCP servers quickly (e.g., with Python FastMCP or Streamlit).
- Once built, these servers can be integrated into AI IDEs, chatbots, or assistant apps supporting MCP.


### 2. Publicly Available or Third-Party MCP Servers

There are many **ready-made MCP servers on the internet** that expose popular services and data to AI applications:

- **GitHub MCP Server**: Interfaces with GitHub APIs for repo management, issues, PRs, code analytics.
- **Slack MCP Server**: Integrates Slack messaging and collaboration features.
- **Weather MCP Servers**: Provide weather data with real-time updates.
- **Search MCP Servers**: Brave Search, DuckDuckGo for privacy-focused web search.
- **Database MCP Servers**: SingleStore for SQL queries, vector search servers like Qdrant.
- **Other Services**: Notion, Grafana, Docker, Google APIs (Ads, Analytics, Search Console), project management tools, etc.

These servers are either open-source community projects or managed services by organizations. Some need API tokens/accounts and may have rate limits or pricing depending on usage.

### 3. More Types of MCP Servers and Examples

- **CLI MCP Servers**: Run locally or in containers exposing commands (e.g., GitHub CLI server you run with Docker).
- **HTTP+SSE MCP Servers**: Remote servers serving continuous streams for real-time data.
- **Specialized MCP Servers**: For code execution (inside Docker containers), document retrieval from vector stores, scholarly paper search, enterprise data systems.
- **Community and Open-Source MCP Servers**: Many are listed in MCP-related GitHub repos and curated lists.


### 4. Summary Table of MCP Server Categories

| Server Category | Description | Example/Use Case | Hosting |
| :-- | :-- | :-- | :-- |
| Custom MCP Servers | Built by you for your data/tools | Visualize codebases, internal API integration | Local, cloud, containers |
| Public/Third-Party MCP | Expose popular services APIs | GitHub, Slack, Weather, Search, Notion | Managed by providers or OSS |
| CLI MCP Servers | Run locally or in containerized CLI form | Dockerized GitHub MCP server | Local or container |
| HTTP+SSE MCP Servers | Remote servers with streaming | Real-time event updates for dashboards, alerts | Cloud-hosted |
| Specialized MCP Servers | Unique capabilities e.g. code exec, vector search | Running code snippets securely, scholarly search | Varies by project |

