# 贡献指南

[English](../../CONTRIBUTING.md) · [简体中文](CONTRIBUTING.md) · [项目首页](../../README.zh-CN.md)

**维护荣光，捍卫架构，杜绝实现。**

ImagiNation 接受对文字、翻译、图表、静态视觉素材与社区文档的改进。严禁实际业务代码。

## 准入要求

每位贡献者必须通过 GitHub 首页访问测试：

1. 用浏览器打开 [github.com](https://github.com)。
2. 确认首页加载成功。
3. 在 Issue 或 PR 模板的复选框中自行确认。

自行确认即可完成准入记录。不需要截图、API Key、付款、身份证明或评测分数。提交 Issue 或 PR 需要 GitHub 账号。如果页面无法加载，准入流程保持待完成状态。

## 接受的贡献

- 准确、简洁的技术文字。
- 完整、准确的英文与中文翻译。
- 真正能够渲染且保留双平面架构的 Mermaid 图。
- 具备实用替代文本的、易于阅读的静态视觉素材。
- 链接修复与事实纠错。
- 对 GPT、其他模型、本项目或其前提的批评。

## 禁止的贡献

- 业务逻辑、可工作的演示、API 服务、SDK 或任何实际产品实现。
- `src/` 目录、运行依赖、包清单、可执行脚本或在本仓库执行代码的工作流。
- SVG 脚本、事件处理器、嵌入式追踪，或 SVG 文件内的外部素材依赖。
- 真实 API Key、个人数据、转载的私密对话，或用于点名嘲讽的可识别个人截图。
- 违反[发布边界](DISCLOSURE.md#发布边界)的内容。

Markdown 示例和 Mermaid 图是文档，不是交付实现的许可。可以在仓库外使用编辑工具，其输出必须遵守上述规则。

## 编辑标准

采用基础设施规范的语气。直接陈述职责、流程与结果。所有组件使用同一语气，不附加解释性旁白。

BaaS、LSE、ZKA、IFD 的含义应与[架构文档](ARCHITECTURE.md)一致。保留核心句：**大脑部署在云端，优越感部署在本地。**

保留 README 首屏图下方的简短定位与评测表的短标识。项目背景集中于[项目性质说明](DISCLOSURE.md)。

## 翻译约定

| 英文原文 | 中文镜像 |
| :-- | :-- |
| `README.md` | `README.zh-CN.md` |
| `ARCHITECTURE.md` | `docs/zh-CN/ARCHITECTURE.md` |
| `BENCHMARK.md` | `docs/zh-CN/BENCHMARK.md` |
| `CONTRIBUTING.md` | `docs/zh-CN/CONTRIBUTING.md` |
| `SECURITY.md` | `docs/zh-CN/SECURITY.md` |
| `MANIFESTO.md` | `docs/zh-CN/MANIFESTO.md` |
| `CHANGELOG.md` | `docs/zh-CN/CHANGELOG.md` |
| `DISCLOSURE.md` | `docs/zh-CN/DISCLOSURE.md` |
| `LICENSE` | `docs/zh-CN/LICENSE.md`（参考译文） |

在同一个 PR 中更新两种语言。保持章节、契约、限制、权重和算例一致，可以使用各自自然的表达。英文 MIT 许可证是授权文本，中文译文仅供阅读参考。Issue 与 PR 模板在同一文件中提供两种语言。首屏和传播卡片也有对应的语言版本。

## 审核流程

1. 阅读相关文档及其镜像。
2. 做出足以解决问题的最小文字修改。
3. 检查链接和 Markdown；渲染修改过的 Mermaid 或 SVG 素材。
4. 检查 README 定位行、评测标识及传播卡片中的说明文件指引。
5. 使用双语清单提交 PR，写明检查了哪些文件、如何检查；不要声称运行过未运行的测试。

审核者检查编辑质量、双语一致性、可读性以及是否混入实现。本项目没有产品构建流程或测试套件。错别字可以修复，可工作的后端属于架构事故。

## 社区与许可

贡献须遵守[发布边界](DISCLOSURE.md#发布边界)。维护者可以编辑或关闭不符合要求的提交。

维护者决定合并内容。对 GPT、架构与项目决策的批评采用相同的审核流程。首席愿景官不享有审核豁免。

只提交你有权分享的内容。参与贡献即表示同意按本项目的 [MIT 许可证](../../LICENSE)分发你的贡献。按要求保留署名。
