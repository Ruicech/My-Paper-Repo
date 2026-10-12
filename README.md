# My-Paper-Repo

个人论文阅读与研究资料仓库，用于整理人工智能、Large Language Models、Agent、自动化科研评审等方向的重要论文。

仓库按照研究方向组织。每个方向目录包含独立的 `README.md`，用于维护论文清单、阅读优先级、代码链接和主题标签。

---

## Repository Structure

| Direction | Description |
| --- | --- |
| [Agent Memory](./Agent%20Memory/README.md) | Agent 的长期记忆、经验记忆、记忆检索、组织、更新、遗忘与评估机制 |
| [Prompt Engineering and Agent Foundations](./Prompt%20Engineering%20and%20Agent%20Foundations/README.md) | Prompt Engineering、Reasoning、Planning、Reflection、Search 以及早期 Agent 基础范式 |
| [Context Engineering and Long-Context Reasoning](./Context%20Engineering%20and%20Long-Context%20Reasoning/README.md) | Context Engineering、长上下文理解与推理、信息位置偏差、上下文选择、压缩、排序和信息利用 |
| [LLM Programming and Pipeline Optimization](./LLM%20Programming%20and%20Pipeline%20Optimization/README.md) | LLM Programming、Declarative Pipeline、Prompt Optimization、Demonstration Optimization 和 Pipeline 自动优化 |
| [Agent Tool Use and Action Space](./Agent%20Tool%20Use%20and%20Action%20Space/README.md) | Tool Use、Code-as-Action、Action Space、执行反馈、自我修正和复杂任务执行 |
| [Agent-System](./Agent-System/README.md) | Agent 系统架构、Runtime、任务分解、模型路由、Workflow Orchestration、本地部署和效率优化 |
| [Self-Evolution](./Self-Evolution/README.md) | 模型与 Agent 通过反馈、反思、经验积累和迭代优化实现持续自我改进 |
| [Automated-Review](./Automated-Review/README.md) | 自动化科研评审、LLM Reviewer、Review Evaluation、Meta-Review、Paper Evaluation 和评审可靠性 |
| [Classic Must-Read](./Classic%20Must-Read/README.md) | Transformer、预训练语言模型、RLHF、Reasoning、模型评估等跨方向经典基础论文 |

---

## Paper Entry Convention

每篇论文统一使用以下字段：

| Field | Description |
| --- | --- |
| `Priority` | 个人阅读与知识体系中的优先级 |
| `Paper` | 论文正式标题 |
| `Venue/Year` | 会议、期刊或预印本平台及年份 |
| `Paper URL` | 论文正式链接 |
| `GitHub/Code` | 官方代码、项目仓库、项目主页或相关实现 |
| `Tags` | 用于主题分类和检索的标签 |

统一格式：

```md
| Priority | Paper | Venue/Year | Paper URL | GitHub/Code | Tags |
| --- | --- | --- | --- | --- | --- |
| P0 | Paper Title | Venue 2026 | [Paper](https://...) | [Official Code](https://...) | tag-1, tag-2 |
```

---

## Priority Convention

阅读优先级按照以下规则维护：

| Priority | Meaning |
| --- | --- |
| `P0` | **Core / Must Read**：该方向的代表性工作、基础方法或非常值得优先阅读的论文 |
| `P1` | **Important**：重要扩展工作，建议系统阅读 |
| `P2` | **Supplementary**：补充阅读、背景材料或特定子问题相关论文 |

`Priority` 表示个人阅读与知识体系中的优先级，不代表对论文质量进行绝对排名。

---

## Link Convention

`GitHub/Code` 字段统一使用以下命名：

| Label | Meaning |
| --- | --- |
| `Official Code` | 论文作者发布的论文实验代码 |
| `Official Repo` | 论文对应框架、系统或长期维护项目的官方仓库 |
| `Official Project` | 官方项目主页、Demo 页面或非代码项目网站 |
| `Reference Implementation` | 作者团队或主要机构维护、与论文高度相关，但并非论文专属的参考实现 |
| `Unofficial Code` | 第三方复现或社区实现 |
| `N/A` | 未找到公开代码或项目 |

原则上不再混用 `GitHub`、`Code`、`Repo`、`Official System` 等其他写法。

---

## Tag Convention

Tags 统一采用：

```text
lowercase-kebab-case
```

例如：

```text
agent-memory
long-context
context-engineering
tool-use
pipeline-optimization
novelty-assessment
evidence-grounding
```

多个标签使用英文逗号分隔：

```text
context-engineering, long-context, position-bias
```

避免使用：

```text
Context Engineering
LLM Evaluation
Agent Memory
```

## Direction README Convention

每个研究方向的 `README.md` 统一采用以下结构：

```md
# Direction Name

方向定义与研究范围说明。

## 论文清单

| Priority | Paper | Venue/Year | Paper URL | GitHub/Code | Tags |
| --- | --- | --- | --- | --- | --- |
| P0 | ... | ... | ... | ... | ... |

## 可维护主题

- Topic A：……
- Topic B：……
- Topic C：……
```

基本原则：

- README 主要描述该研究方向本身，不绑定具体研究项目。
- 论文清单只收录实际已经加入仓库的论文。
- 不为了补全某个方向而预先加入尚未阅读或尚未整理的论文。
- 表格始终保持统一的 6 列结构。
- 新增论文前优先检查是否已经存在于其他方向。
- 一篇论文可以根据其研究意义出现在不同方向，但 Tags 应体现其在当前方向中的主要作用。

---

## Current Research

### Expert Experience Enhanced Novelty Assessment for Scientific Papers

当前研究方向为 **面向科学论文的专家经验增强创新性评估（Expert Experience Enhanced Novelty Assessment for Scientific Papers）**。

研究目标是利用历史同行评审中的专家创新性评价经验，构建可检索、可复用的专家经验库，并将其用于新论文的细粒度创新性评估。

整体研究思路包括：

- **Scientific Paper Representation**：从论文全文中识别核心贡献声明，并构建结构化的论文贡献表示。
- **Expert Experience Induction**：从历史论文及其专家评审意见中归纳创新性评价经验。
- **Experience Retrieval**：针对新论文的具体贡献检索相关历史专家经验。
- **Evidence-Grounded Novelty Assessment**：结合论文内部证据、相关工作和历史专家经验，对论文贡献进行有证据支撑的创新性评价。
- **Fine-Grained Assessment**：以论文核心贡献为基本评价单元，而不仅仅输出论文级的整体 Novelty Score。

研究重点是探索：

> **历史专家评审经验能否作为一种可复用的评价知识，增强 LLM 对科学论文创新性的判断能力与可靠性。**
