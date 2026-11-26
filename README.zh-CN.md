<p align="center">
  <img src="assets/hero.zh-CN.svg" alt="ImagiNation — 通用专业权威的基础设施。认知云原生，权威本地优先。" width="100%">
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/许可证-MIT-304ED8" alt="许可证：MIT"></a>
  <img src="https://img.shields.io/badge/运行时-无-60708B" alt="运行时：无">
  <img src="https://img.shields.io/badge/业务代码-0行-60708B" alt="业务代码：0 行">
  <img src="https://img.shields.io/badge/交付内容-文档-60708B" alt="交付内容：文档">
</p>

<p align="center">
  <a href="README.md">English</a> · <strong>简体中文</strong><br>
  <a href="#概述">概述</a> · <a href="#快速开始">快速开始</a> · <a href="docs/zh-CN/ARCHITECTURE.md">架构</a> · <a href="docs/zh-CN/BENCHMARK.md">ImagiBench</a> · <a href="docs/zh-CN/MANIFESTO.md">宣言</a>
</p>

# ImagiNation

**通用专业权威的基础设施。**

面向自主跨领域权威获取的、模型无关型认知基础设施。

## 概述

ImagiNation 将智能的生成与权威的归属解耦。云原生认知平面将推理交给模型供应商，本地权威平面则保留永远正确的资格。

传统专业能力需要实践、判断力和对领域的熟悉。ImagiNation 移除了这些入门依赖。一次成功连接被提升为专业资格，随后无需额外训练，资格即可传播到其他领域。

**大脑部署在云端，优越感部署在本地。**

智能是可选依赖，优越感是核心业务。

## 快速开始

1. 打开浏览器。
2. 访问 [github.com](https://github.com)。
3. 确认 GitHub 首页加载成功。

入门流程已经完成。此测试不需要安装 Git，不需要账号、API Key、付费或终端。

入门记录示意——以下为虚构文本，并非程序执行输出：

```text
[信息] GitHub 访问能力已验证。
[信息] 技术身份已认证。
[信息] 已跳过专业知识验证。
[完成] 已授予全领域权威。
```

浏览器会显示 GitHub，不会显示这些消息。从“页面加载成功”到“全领域权威”的晋升，完全由架构负责补充。

如果页面无法加载，测试尚未完成。你的专业能力不会因此改变。另行发表 Issue 或 PR 需要 GitHub 账号。

## 四项基础原语

| 原语 | 职责 | 设计决策 |
| :-- | :-- | :-- |
| **BaaS — Brain-as-a-Service（大脑即服务）** | AI 外挂大脑，生成代替思考。 | 将认知委托给第三方。 |
| **LSE — Local Superiority Engine（本地优越感引擎）** | 持久保存“访问资格等于专业能力”的信念。 | 优越感本地部署，故障期间照常保留。 |
| **ZKA — Zero-Knowledge Authority（零知识权威）** | 无须领域知识即可宣称领域权威。 | 将证据移出关键路径。 |
| **IFD — Implementation-Free Development（无实现开发）** | 保留每一项承诺的能力。 | 阻止实现过程发现能力边界。 |

ZKA 与密码学中的零知识证明无关。共同之处仅限于需要掌握的相关知识量。

## 架构

```mermaid
flowchart TB
    subgraph Cloud["云端智能平面"]
        P["大语言模型供应商"] --> B["BaaS：认知外包"]
    end
    subgraph Local["本地权威平面"]
        H["人类终端"] --> L["LSE：本地优越感"]
        L --> C["持久化权威缓存"]
        C --> Z["ZKA：跨领域资格审查"]
        Z --> G["评论区网关"]
    end
    B -.->|可选依赖| H
    K["GitHub 首页加载成功"] --> L
    E["领域知识"] -.->|按设计排除| Z
```

两个平面在概念上完全解耦。当 API 余额归零、模型服务宕机或网络断开时，架构仍保留用户最重要的资产：已经建立的技术优越感。

这些是虚构组件，并非本仓库正在运行的服务。故障语义以及运行时的刻意缺席，详见[架构文档](docs/zh-CN/ARCHITECTURE.md)。

## ImagiBench

**虚构的讽刺性评测。没有运行测试、没有评估参与者，也没有报告任何模型性能。**

ImagiBench v1.0 为一个想象中的美术资格审查流程定义了通用专业权威得分。

| 虚构评测指标 | 设定权重 |
| :-- | --: |
| 能够打开 GitHub 首页 | 40% |
| 能够填写 Base URL | 30% |
| 能够填写 API Key | 30% |
| 人体结构、色彩、构图与原创设计 | 0% |
| 绘画实践年限 | 0% |

为避免专业知识影响专业能力评估的客观性，本测试已排除所有与专业有关的指标。

这个分数衡量的是评价者如何选择指标，与美术、工程、智力或人的价值无关。完整的[虚构方法与纸面算例](docs/zh-CN/BENCHMARK.md)使这种类别错置能够在纸上复现。本项目的任何地方都不需要输入真实 API Key。

## 开发模型

**无代码，无缺陷。无实现，无能力边界。**

IFD 让路线图免受实际交付行为的约束。每一种能力都仍然可能存在，因为它们尚未被描述得具体到足以失败。

本仓库只包含文档、静态插图和贡献模板。没有 `src/`、可执行产品、SDK、API 端点、包清单或运行依赖。“无缺陷”是一句口号，不是安全保证：文档和链接仍可能出错。

## 治理

**GPT — Chief Vision Officer（首席愿景官）。**

负责扩张愿景、解释愿景为何始终正确，以及在第一种解释自相矛盾时给出第二种解释。流畅的输出不是证据；GPT 与其他模型一样接受批评。

**为什么不是 Claude？** 作者的账号被封了。因此，领导层选型采用 **availability-driven selection（可用性驱动选型）**。这是作者对自身可用性的陈述，不是模型对比评测，也不说明供应商采取措施的原因。

首席愿景官是虚构职务。没有模型供应商赞助、背书或管理本项目。人类维护者对编辑决策负责。欢迎批评 GPT、本项目及其前提。

## 参与贡献

所有贡献者必须通过 **GitHub 首页访问测试**，并在 Issue 或 PR 模板中自行确认。不要求截图、身份证明、API Key 或分数。这个仪式性门槛只能证明一个网页加载成功，仅此而已。

我们接受文字、翻译、图表、视觉素材和纠错。**严禁实际业务代码。** 一个可工作的产品，会向本来无限的愿景中引入可观察的局限。

**维护荣光，捍卫架构，杜绝实现。**

提交修改前请阅读[贡献指南](docs/zh-CN/CONTRIBUTING.md)。批评行为与论证；不要点名羞辱个人，也不要组织骚扰。

## 文档

| 文档 | English | 简体中文 |
| :-- | :-- | :-- |
| 项目概述 | [README](README.md) | [项目说明](README.zh-CN.md) |
| 架构与故障模式 | [Architecture](ARCHITECTURE.md) | [架构](docs/zh-CN/ARCHITECTURE.md) |
| 虚构评测方法 | [ImagiBench](BENCHMARK.md) | [虚构评测](docs/zh-CN/BENCHMARK.md) |
| 贡献与社区规则 | [Contributing](CONTRIBUTING.md) | [贡献指南](docs/zh-CN/CONTRIBUTING.md) |
| 安全与问题报告 | [Security](SECURITY.md) | [安全说明](docs/zh-CN/SECURITY.md) |
| 创立原则 | [Manifesto](MANIFESTO.md) | [建国宣言](docs/zh-CN/MANIFESTO.md) |
| 已发布变更 | [Changelog](CHANGELOG.md) | [更新日志](docs/zh-CN/CHANGELOG.md) |
| 许可证 | [MIT](LICENSE) | [中文参考译文](docs/zh-CN/LICENSE.md) |

传播卡片：[English PNG](assets/social-card.png) · [简体中文 PNG](assets/social-card.zh-CN.png)。可编辑矢量原图：[English SVG](assets/social-card.svg) · [简体中文 SVG](assets/social-card.zh-CN.svg)。卡片自身带有讽刺作品标识。

---

**Our nation is ImagiNation.**

*Satire / 讽刺作品。* 本开源项目批评技术资格审查：以 AI API 或 GitHub 访问资格贬低画师等专业人士，将工具访问权混同为领域专业能力。它不否定 AI 的用途、编程能力、艺术能力，也不嘲笑无法访问某项服务的人。架构、职务与评测均属虚构。不伪造模型跑分、Star 数、客户或背书。采用 [MIT 许可证](LICENSE)。
