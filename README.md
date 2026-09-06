# GKE MCP Server and Gemini CLI Extension

Enable MCP-compatible AI agents to interact with Google Kubernetes Engine.

<img src="https://raw.githubusercontent.com/GoogleCloudPlatform/gke-mcp/main/assets/gke-mcp-gemini-cli-demo.gif" alt="A demonstration of using the GKE MCP server with the Gemini CLI" width="600">

## Installation

Choose a way to install the MCP Server and then connect your AI to it.

### Use as a Gemini CLI Extension

1. Install [Gemini CLI](https://github.com/google-gemini/gemini-cli?tab=readme-ov-file#-installation).

2. Install the extension

```sh
gemini extensions install https://github.com/GoogleCloudPlatform/gke-mcp.git
```

### Use in MCP Clients / Other AIs

#### Quick Install (Linux & macOS only)

```sh
curl -sSL https://raw.githubusercontent.com/GoogleCloudPlatform/gke-mcp/main/install.sh | bash
```

 - **Verify Outputs:** LLM responses can be unpredictable and may be inaccurate. Always verify results.
