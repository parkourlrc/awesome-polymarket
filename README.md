# Awesome Polymarket

一个精心整理的 Polymarket 相关开源项目合集。
目标：帮助开发者、量化、研究者快速找到可用的 SDK、客户端、数据工具、交易机器人、市场做市、实时数据、分析与仪表盘等资源。

> 更新时间：2026-01-05。仅收录开源仓库；每项均附官方/仓库链接与简要说明。

## 目录
- 官方 SDK 与客户端
- 实时数据与数据接口
- 做市与交易机器人
- AI/Agent 与 MCP/插件
- 数据抓取与分析工具
- 子图（Subgraph）与索引
- CLI/终端工具
- 示例与集成
- 其他语言生态（Rust/Go 等）
- 贡献指南

---

## 官方 SDK 与客户端
- TypeScript CLOB 客户端 — Polymarket/clob-client
  - 仓库：https://github.com/Polymarket/clob-client
  - 说明：官方 TypeScript CLOB 客户端，含示例与 NPM 包。
- Python CLOB 客户端 — Polymarket/py-clob-client
  - 仓库：https://github.com/Polymarket/py-clob-client
  - 说明：官方 Python CLOB 客户端，示例完善，含交易、订单、行情等接口。
- Rust CLOB 客户端 — Polymarket/rs-clob-client
  - 仓库：https://github.com/Polymarket/rs-clob-client
  - 说明：官方 Rust 客户端，强类型请求构建、Builder 认证等。
- 钱包交互 SDK — Polymarket/polymarket-sdk
  - 仓库：https://github.com/Polymarket/polymarket-sdk
  - 说明：与 Polymarket 钱包交互的 SDK（TS）。
- Builder 签名 SDK（TS）— Polymarket/builder-signing-sdk
  - 仓库：https://github.com/Polymarket/builder-signing-sdk
  - 说明：为 Builder 流程生成认证 Header 的 TS SDK。
- Builder 签名 SDK（Python）— Polymarket/py-builder-signing-sdk
  - 仓库：https://github.com/Polymarket/py-builder-signing-sdk
  - 说明：同上 Python 版本。
- Builder Relayer 客户端（Python）— Polymarket/py-builder-relayer-client
  - 仓库：https://github.com/Polymarket/py-builder-relayer-client
  - 说明：Polymarket Relayer API 的 Python 客户端。

## 实时数据与数据接口
- 实时数据客户端（TS）— Polymarket/real-time-data-client
  - 仓库：https://github.com/Polymarket/real-time-data-client
  - 说明：WebSocket 实时数据订阅，支持订单、成交、评论、RFQ 等主题。
- Go 实时数据客户端（第三方）— ivanzzeth/polymarket-go-real-time-data-client
  - 文档：https://pkg.go.dev/github.com/ivanzzeth/polymarket-go-real-time-data-client
  - 说明：Go 语言的实时数据订阅客户端。

## 做市与交易机器人
- 官方做市 Keeper（Python）— Polymarket/poly-market-maker
  - 仓库：https://github.com/Polymarket/poly-market-maker
  - 说明：官方开源做市 Keeper，支持 AMM/Bands 等策略。
- 第三方做市/机器人示例（社区）
  - warproxxx/poly-maker（做市机器人）：https://github.com/warproxxx/poly-maker
  - Trust412 系列（复制交易/尖峰检测）：https://github.com/Trust412
  - vladmeer/polymarket-copy-trading-bot：https://github.com/vladmeer/polymarket-copy-trading-bot
  - dappboris-dev/polymarket-trading-bot：https://github.com/dappboris-dev/polymarket-trading-bot
  - MaxWell219/Polymarket-betting-bot：https://github.com/MaxWell219/Polymarket-betting-bot
  - lorine93s/polymarket-market-maker-bot：https://github.com/lorine93s/polymarket-market-maker-bot

> 提示：社区机器人质量参差不齐，务必仔细审阅代码、测试环境与风控逻辑。

## AI/Agent 与 MCP/插件
- Polymarket Agents（官方）— 用 AI Agent 自动交易
  - 仓库：https://github.com/Polymarket/agents
  - 说明：官方开源的 Agent 开发框架与工具集，MIT 许可。
- Polymarket MCP Server（社区）— 面向 Claude 的工具服务器
  - 仓库：https://github.com/caiovicentino/polymarket-mcp-server
  - 说明：MCP 协议实现，提供 45+ 工具、WebSocket 监控与仪表盘。
- elizaOS Polymarket 插件（社区）— elizaos-plugins/plugin-polymarket
  - 仓库：https://github.com/elizaos-plugins/plugin-polymarket
  - 说明：为 AI Agent（ElizaOS）提供 Polymarket 接入，含历史价格等能力。
- AI 市场建议器（社区）— lorine93s/polymarket-ai-market-suggestor
  - 仓库：https://github.com/lorine93s/polymarket-ai-market-suggestor
  - 说明：结合新闻与情绪生成市场建议。

## 数据抓取与分析工具
- poly_data（社区）— 数据抓取/结构化流水线
  - 仓库：https://github.com/warproxxx/poly_data
  - 说明：抓取市场、订单事件（Goldsky 子图）并生成结构化交易数据 CSV。
- 市场数据 REST API（社区）— elielieli909/polymarket-marketdataAPI
  - 仓库：https://github.com/elielieli909/polymarket-marketdataAPI
  - 说明：简单的 REST API 封装。
- 分析与可视化示例（社区）
  - DominiqueBuob/polymarket_analysis_v1：https://github.com/DominiqueBuob/polymarket_analysis_v1
  - PaulieB14/polymarket-subgraph-analytics：https://github.com/PaulieB14/polymarket-subgraph-analytics

## 子图（Subgraph）与索引
- 官方子图（文档入口）
  - 文档：https://docs.polymarket.com/developers/subgraph/overview
  - 说明：提供 GraphQL 接口的事件索引与聚合。

## CLI/终端工具
- PolyTrader/polymarket-trading（CLI）
  - 仓库：https://github.com/PolyTrader/polymarket-trading
  - 说明：简易命令行交易工具。
- polyterm（终端监控）— NYTEMODEONLY/polyterm
  - 仓库：https://github.com/NYTEMODEONLY/polyterm
  - 说明：终端监控 Polymarket 市场、鲸鱼活动与机会。

## 示例与集成（官方 Demo）
- Builders 示例（Magic/Privy/Safe 等）
  - Polymarket/magic-safe-builder-example：https://github.com/Polymarket/magic-safe-builder-example
  - Polymarket/turnkey-safe-builder-example：https://github.com/Polymarket/turnkey-safe-builder-example
  - Polymarket/privy-safe-builder-example：https://github.com/Polymarket/privy-safe-builder-example
  - Polymarket/wagmi-safe-builder-example：https://github.com/Polymarket/wagmi-safe-builder-example
  - Polymarket/safe-wallet-integration：https://github.com/Polymarket/safe-wallet-integration
- 文档入口（含更多示例）：https://docs.polymarket.com/developers/builders/examples

## 其他语言生态
- Rust：见上文 rs-clob-client：https://github.com/Polymarket/rs-clob-client
- Go：ivanzzeth/polymarket-go-real-time-data-client 文档：https://pkg.go.dev/github.com/ivanzzeth/polymarket-go-real-time-data-client
- 社区 TS SDK：HuakunShen/polymarket-proxy：https://github.com/HuakunShen/polymarket-proxy；cyl19970726/poly-sdk：https://github.com/cyl19970726/poly-sdk

---

## 贡献指南
欢迎通过 PR 增补与纠错，原则：
- 仅收录开源仓库（GitHub/GitLab 等），明确许可、README 与用途说明
- 优先官方与质量较高的社区项目；重复、空仓库或营销性质项目不收录
- 分类：SDK/客户端、实时数据、做市/机器人、AI/Agent、数据/分析、CLI、示例集成、其他语言
- 提交格式：
  - 名称（中文描述）— 仓库名
  - 仓库链接
  - 简要说明 1–2 句

## 许可
本清单遵循 CC0-1.0（公有领域）许可，详见 LICENSE。

## 致谢
- Polymarket 官方组织：https://github.com/polymarket
- Polymarket 文档：https://docs.polymarket.com/

---

> 免责声明：本列表仅信息汇总，不构成投资建议或交易建议。使用任何机器人或做市工具需自担风险并遵守所在司法辖区法律法规。
