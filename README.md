# My-Paper-Repo

个人论文阅读与研究资料仓库，用于整理人工智能、LLM、Agent、自动化科研评审等方向的重要论文。

仓库按照研究方向组织。每个方向目录包含独立的 `README.md`，用于维护论文清单、阅读优先级、代码链接和主题标签；部分论文还包含独立阅读笔记。

---

## Repository Structure

| Direction | Description |
| --- | --- |
| [Agent Memory](./Agent%20Memory/README.md) | Agent 的短期记忆、长期记忆、检索增强记忆、情景记忆、工作流状态以及记忆管理机制 |
| [Prompt Engineering and Agent Foundations](./Prompt%20Engineering%20and%20Agent%20Foundations/README.md) | Prompt Engineering、Chain-of-Thought、ReAct、Tool Use 以及早期 Agent 方法与基础范式 |
| [Context Engineering and Long-Context Reasoning](./Context%20Engineering%20and%20Long-Context%20Reasoning/README.md) | Context Engineering、长上下文理解、信息位置偏差、上下文选择、压缩、排序和信息利用 |
| [LLM Programming and Pipeline Optimization](./LLM%20Programming%20and%20Pipeline%20Optimization/README.md) | LLM Programming、Declarative Pipeline、Prompt Optimization、Demonstration Optimization 和 Pipeline 自动优化 |
| [Agent Tool Use and Action Space](./Agent%20Tool%20Use%20and%20Action%20Space/README.md) | Tool Use、Function Calling、API Calling、Code-as-Action、执行反馈和复杂工具调用 |
| [Agent-System](./Agent-System/README.md) | Agent 系统架构、任务规划、多 Agent 协作、模型路由、上下文管理、部署和推理效率优化 |
| [Self-Evolution](./Self-Evolution/README.md) | 模型和 Agent 通过反馈、反思、自动数据构造和迭代优化实现自我改进 |
| [Automated-Review](./Automated-Review/README.md) | 自动化科研评审、LLM Reviewer、Meta-review、Rebuttal、Reviewer Assignment 和评审可靠性 |
| [Classic Must-Read](./Classic%20Must-Read/README.md) | Transformer、强化学习、检索、生成模型、评估等跨方向经典基础论文 |

---

## Paper Entry Convention

每篇论文统一使用以下字段：

| Field | Description |
| --- | --- |
| `Priority` | 阅读优先级 |
| `Paper` | 论文正式标题 |
| `Venue/Year` | 会议、期刊或预印本平台及年份 |
| `Paper URL` | 论文正式链接 |
| `GitHub/Code` | 官方代码、官方项目仓库或其他相关实现 |
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
| `P0` | Core / Must Read。该方向的代表性工作、基础方法或非常值得优先阅读的论文 |
| `P1` | Important。重要扩展工作，建议系统阅读 |
| `P2` | Supplementary。补充阅读、背景材料或特定子问题相关论文 |

`Priority` 表示个人阅读与知识体系中的优先级，不代表对论文质量进行绝对排名。

---

## Link Convention

`GitHub/Code` 字段统一使用以下命名：

| Label | Meaning |
| --- | --- |
| `Official Code` | 论文作者发布的论文实验代码 |
| `Official Repo` | 论文对应框架、系统或长期维护项目的官方仓库 |
| `Official Project` | 官方项目主页、Demo 页面或非代码项目网站 |
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

### Reading Status

已完成主要内容阅读的论文可以增加：

```text
read
```

例如：

```text
context-engineering, long-context, position-bias, read
```

没有 `read` 标签表示论文已收录，但尚未完成主要阅读。

---

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

其中：

- README 只描述该研究方向本身，不绑定当前具体研究项目。
- 论文详细阅读笔记尽量放入单独的 `notes/` 目录，而不是塞入论文表格。
- 表格始终保持统一的 6 列结构。
- 新增论文时优先检查是否已经存在于其他方向，必要时可跨方向收录，但 Tags 应体现该论文在当前目录中的主要作用。

---

## Notes Convention

对于需要长期保存的论文阅读笔记，可以使用：

```text
notes/
```

进行组织。

推荐结构：

```text
Direction/
├── README.md
└── notes/
    ├── paper-a/
    │   └── README.md
    └── paper-b/
        └── README.md
```

方向级 `README.md` 负责论文索引，`notes/` 负责更详细的方法分析、实验总结、优缺点和个人理解。
