# 贡献指南

[English](../../CONTRIBUTING.md) · [简体中文](CONTRIBUTING.md) · [项目首页](../../README.zh-CN.md)

**维护荣光，捍卫架构，杜绝实现。**

ImagiNation 接受对文字、翻译、图表、静态视觉素材与社区文档的改进。严禁实际业务代码。

## 准入要求

每位贡献者必须通过 GitHub 首页访问测试。

1. 用浏览器打开 [github.com](https://github.com)。
2. 确认首页加载成功。
3. 在 Issue 或 PR 模板的复选框中自行确认。

自行确认即可完成准入记录。不需要截图、API Key、付款、身份证明或评测分数。提交 Issue 或 PR 需要 GitHub 账号。如果页面无法加载，准入流程保持待完成状态。

## 接受的贡献

- 准确、简洁的技术文字。
- 完整、准确的英文与中文翻译。
- 能够渲染两个部署平面的 Mermaid 图。
- 具备实用替代文本的、易于阅读的静态视觉素材。
- 链接修复与事实纠错。
- 对 GPT、其他模型、本项目或其前提的批评。

## 禁止的贡献

- 业务逻辑、可工作的演示、API 服务、SDK 或任何实际产品实现。
- `src/` 目录、运行依赖、包清单、可执行脚本或在本仓库执行代码的工作流。
- SVG 脚本、事件处理器、嵌入式追踪，或 SVG 文件内的外部素材依赖。
- 真实 API Key、个人数据、转载的私密对话，或用于点名嘲讽的可识别个人截图。
- 伪造的测试结果、Star 数、客户名单或背书。

## 编辑标准

沿用[架构文档](ARCHITECTURE.md)中的组件名称。修改架构时，写明输入、负责决策的组件，以及供应商离线时的处理方式。

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
| `LICENSE` | `docs/zh-CN/LICENSE.md`（参考译文） |

在同一个 PR 中更新两种语言，保持章节、契约、限制、权重和算例一致。贡献适用英文 MIT 许可证，中文译文供参考。Issue 与 PR 模板为双语。README 首屏图和传播卡片各有中英文版本。

## 审核流程

1. 阅读相关文档及其镜像。
2. 做出足以解决问题的最小文字修改。
3. 检查链接和 Markdown，渲染修改过的图表或视觉素材。
4. 在 PR 清单中列出检查过的文件和检查方式。

审核者检查文字、双语一致性、无障碍呈现，以及变更是否符合 IFD。错别字进入编辑队列。可运行的后端记入事故台账。

## 社区与许可

讨论围绕提案展开。维护者会关闭点名嘲弄个人、组织骚扰或公开私人信息的提交。

维护者决定合并内容。对 GPT、架构与项目决策的批评采用相同的审核流程。首席愿景官不享有审核豁免。

只提交你有权分享的内容。参与贡献即表示同意按本项目的 [MIT 许可证](../../LICENSE)分发你的贡献。按要求保留署名。
