> Made @ Shopify

# pi-figma-mcp

Connects [pi-coding-agent](https://github.com/badlogic/pi-mono) to local Figma desktop MCP server.

## Install

Message `pi`:

```
Install this pi-extension https://github.com/mkaralevich/pi-figma-mcp
```

Or place extension in your `/extensions` folder

## Use

- Open Figma desktop app (not the browser version)
- Enable MCP server (Dev Mode): **Inspect panel → MCP server → Enable desktop MCP server**
- Give pi a link to frame

## Configuration

The MCP server port defaults to `3845`. Override with an env var if needed:

```sh
FIGMA_MCP_PORT=3845 pi
```

## Editing Figma canvas

Figma MCP is read-only. For editing tools, install [pi-figma-labor](https://github.com/mkaralevich/pi-figma-labor) extension.
