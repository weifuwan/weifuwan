<div align="center">

# 魏福万 / weifuwan

**Building open-source data systems in public.**

独立开发者 · Data Engineer → Product Builder

[![Yak Ops](https://img.shields.io/github/stars/weifuwan/yak-ops?style=flat-square&label=Yak%20Ops)](https://github.com/weifuwan/yak-ops)
[![Link-Up](https://img.shields.io/github/stars/weifuwan/yak-link-up?style=flat-square&label=Link-Up)](https://github.com/weifuwan/yak-link-up)

</div>

---

## 我想验证一件事

**有了 AI 之后，一个人究竟能把多复杂的软件真正做出来，并长期把它维护成一个产品。**

不是做一个 Demo，也不是把功能越堆越多。

我更关心的是：从需求判断、产品设计、架构、代码、测试、文档、发布，到真实用户的反馈，一个人能不能借助 AI 获得更大的杠杆，同时仍然对最终的判断和质量负责。

所以我把 GitHub 当成公开的工作台。需求、设计、Issue、PR、代码和迭代尽量留在这里。

现在，我主要在数据工程方向做两件事：

> **把数据操作做成一个完整、连贯的产品。**  
> **把数据执行能力做得足够简单、可靠、可解释。**

---

## 正在构建

### Yak Ops

**Open-source data operations platform for data integration, workflow automation, data quality, and governance.**

Yak Ops 不再只是某个执行引擎外面的一层 Web UI。它更像一个面向数据工作的开源控制面，把数据源、同步、开发、工作流、质量、数据消费和治理放进同一条产品链路：

```text
Connect → Sync → Build → Orchestrate → Validate → Serve → Govern
```

<p>
  <a href="https://github.com/weifuwan/yak-ops"><strong>Repository</strong></a>
  ·
  <a href="https://doc.yak-ops.com/"><strong>Documentation</strong></a>
  ·
  <a href="https://github.com/weifuwan/yak-ops/issues"><strong>Issues</strong></a>
</p>

<img width="2172" height="724" alt="Yak Ops" src="https://github.com/user-attachments/assets/e06d22a5-e74d-4d39-9c6d-2da76486940d" />

### Link-Up

**A lightweight, embeddable offline batch data synchronization engine.**

Link-Up 专注 bounded batch sync：Connector 好扩展、计划能解释、执行可观察、失败能定位。它不试图复制 Flink / Spark 的流式和分布式复杂度，而是把离线同步这件事做得更小、更清楚。

它可以独立运行，也为 Yak Ops 提供离线同步执行能力。

<p>
  <a href="https://github.com/weifuwan/yak-link-up"><strong>Repository</strong></a>
</p>

<img width="2172" height="724" alt="Link-Up" src="https://github.com/user-attachments/assets/eced95ca-63c4-449d-ab69-319a9f85f834" />

---

## 我长期关注的方向

| 方向 | 我关心的问题 |
| --- | --- |
| **DataOps** | 数据源、任务、工作流、质量、消费与治理怎样形成一条真正连贯的工作链路 |
| **Data Integration** | Connector、Planning、Execution、Retry、Metrics 和 Runtime State 怎样保持清晰边界 |
| **Product Engineering** | 怎样把复杂系统做成用户看得懂、用得起来、出问题能定位的产品 |
| **AI Engineering** | 怎样让 AI 放大个人开发者的产出，同时不把产品判断、架构判断和质量责任交给模型 |

---

## 我相信的几件事

**Open source is the product.**  
开源项目本身就应该足够完整、足够有用，而不是一个为了引导用户去别处付费的残缺 Demo。

**工具最终应该解决问题。**  
技术栈、架构模式和新概念都只是手段。真正有价值的是减少用户需要理解和承担的复杂度。

**复杂度不会消失，但应该被放在正确的位置。**  
系统内部可以复杂，用户的操作路径、状态表达和错误反馈不应该因此变得混乱。

**AI 让写代码更便宜，也让判断更值钱。**  
未来真正稀缺的不是“能不能生成代码”，而是知道该做什么、为什么做、边界在哪里，以及什么不应该做。

**做出来，再持续改。**  
我更喜欢让想法进入真实代码、真实运行和真实反馈，而不是长期停留在方案里。

---

## 一起构建

如果你正在使用 Yak Ops 或 Link-Up，欢迎直接通过 **Issue** 提问题、给场景、讨论设计，也欢迎提交 **Pull Request**。

如果你也在做 DataOps、数据平台、数据集成或 AI Engineering，欢迎在 GitHub 上一起交流。
