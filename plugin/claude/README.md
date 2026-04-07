# Subotiz Plugin

Subotiz 开发工具 Claude 插件，提供支付、订阅管理等能力，方便在 Claude 中接入 Subotiz 相关能力。

## 功能

- **支付**：与 Subotiz 支付能力集成
- **订阅管理**：订阅相关开发与调试支持
- **MCP 集成**：通过 MCP（Model Context Protocol）在对话中调用 Subotiz 工具

## GitHub

- MCP 服务端仓库：[Subotiz/mcp](https://github.com/Subotiz/mcp)

## 使用方法

- **鉴权**：在 [开发者集成设置](https://admin.subotiz.com/admin/developer/integration-settings) 申请 API Key，并填入插件或 MCP 配置。
- **代理**：可使用 [mcp-proxy](https://github.com/sparfenyuk/mcp-proxy)，也可选用任意支持自定义请求头（headers）的代理服务。

## 作者

**Subotiz** · weihanlai@shoplazza.com

## 许可证

请以项目根目录或仓库中声明的许可证为准。

---

# Subotiz Plugin (English)

Claude plugin for Subotiz development tools: payments, subscription management, and more. Use Subotiz capabilities directly inside Claude.

## Features

- **Payments**: Integrate with Subotiz payment APIs
- **Subscription management**: Develop and debug subscription flows
- **MCP integration**: Call Subotiz tools from chat via MCP (Model Context Protocol)

## GitHub

- MCP server repository: [Subotiz/mcp](https://github.com/Subotiz/mcp)

## Usage

- **Authentication**: Request an API Key on the [Developer integration settings](https://admin.subotiz.com/admin/developer/integration-settings) page and add it to the plugin or MCP configuration.
- **Proxy**: You can use [mcp-proxy](https://github.com/sparfenyuk/mcp-proxy), or any proxy that supports custom request headers.

## Author

**Subotiz** · weihanlai@shoplazza.com

## License

See the license in the project root or repository.
