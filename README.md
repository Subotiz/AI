# Subotiz AI

Subotiz 的 AI 生态与工具仓库，为 Cursor 等 AI 开发环境提供 Subotiz 支付与订阅能力，方便在对话和代码中集成、调试 Subotiz。

[Subotiz](https://subotiz.com) 是面向 SaaS 与数字业务的**支付与订阅平台**，提供统一 API、结账（托管/嵌入式）、退款、客户管理与 Webhook 等能力。

## 仓库内容

| 路径 | 说明 |
|------|------|
| `plugin/cursor/subotiz-plugin/` | **Cursor 插件**：在 Cursor 中集成 Subotiz 开发工具（支付、订阅、MCP、Skill） |

### Cursor 插件 (subotiz-plugin)

- **支付与订阅**：与 Subotiz 支付、订阅能力集成，支持开发与调试
- **MCP**：通过 [Model Context Protocol](https://modelcontextprotocol.io/) 在对话中调用 Subotiz 工具（需认证时使用 `mcp_auth`）
- **Skill**：内置 Subotiz 技能文档，供 AI 理解 API、结账流程、Webhook、状态枚举等，便于回答集成与排错问题

安装与配置见：[plugin/cursor/subotiz-plugin/README.md](plugin/cursor/subotiz-plugin/README.md)

## 快速开始

1. 克隆本仓库
2. 在 Cursor 中安装并启用 `plugin/cursor/subotiz-plugin`
3. 在对话中即可咨询或集成 Subotiz（结账、API、Webhook、调试等）

## 作者与许可

**Subotiz** · weihanlai@shoplazza.com  

许可见 [LICENSE](LICENSE)。
