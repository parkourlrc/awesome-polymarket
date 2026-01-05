# 贡献指南（Contributing）

感谢你对 Awesome Polymarket 的兴趣！为了保持本项目的高质量与可用性，请在提交 PR 时遵循以下指南。

## 收录原则
- 开源仓库：必须是公开可访问且带有明确许可（MIT/Apache-2.0/GPL/CC0 等）的代码仓库。
- 明确用途：README 中应清楚描述功能与使用场景（SDK/客户端、做市/机器人、数据/分析、AI/Agent、CLI、示例集成、其他语言）。
- 活跃度优先：优先收录近期仍在维护或具备参考价值的项目；长期不维护或空仓库一般不收录。
- 去重与质量：相同用途的项目按质量与活跃度筛选；营销性质或可疑仓库不收录。

## 分类规范
- 官方 SDK 与客户端
- 实时数据与数据接口
- 做市与交易机器人
- AI/Agent 与 MCP/插件
- 数据抓取与分析工具
- 子图（Subgraph）与索引
- CLI/终端工具
- 示例与集成
- 其他语言生态（Rust/Go 等）

## 提交格式
请在 README 对应分类下新增条目，格式如下：

```
- 名称（中文描述）— 仓库名
  - 仓库：<GitHub 链接>
  - 说明：1–2 句简述项目功能与适用场景
```

示例：
```
- Python CLOB 客户端 — Polymarket/py-clob-client
  - 仓库：https://github.com/Polymarket/py-clob-client
  - 说明：官方 Python 客户端，含交易、订单、行情等接口与示例。
```

## 提交流程
1. Fork 本仓库
2. 创建分支（如：`feat/add-new-tool-xxx`）
3. 提交更改并完善说明
4. 发起 Pull Request

## 许可证与署名
- 本清单（README 与相关文档）采用 CC0-1.0 许可发布（公有领域）。
- 如需标注你的项目名称、作者信息，请在 PR 描述中附加说明（README 中不做过度宣传）。

## 联系与交流
- 官方组织：https://github.com/polymarket
- 官方文档：https://docs.polymarket.com/

感谢你的贡献！