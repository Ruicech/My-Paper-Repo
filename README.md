# My-Paper-Repo

论文仓库

## 论文条目规范

每篇论文必须包含以下信息：

| 字段 | 说明 |
| --- | --- |
| Priority | 推荐优先级，建议使用 `P0`、`P1`、`P2`。`P0` 表示核心必读论文，`P1` 表示重要补充论文，`P2` 表示扩展阅读论文 |
| Paper | 论文标题，尽量使用论文正式标题 |
| Venue/Year | 会议、期刊或预印本平台及年份，例如 `NeurIPS 2022`、`ICLR 2023`、`ACL 2023`、`arXiv 2023` |
| Paper URL | 论文地址，优先使用 arXiv、OpenReview、ACL Anthology、NeurIPS Proceedings、PMLR、ACM Digital Library 等稳定链接 |
| GitHub/Code | 论文相关代码、项目仓库或参考实现。官方代码统一标注为 `Official Code`；官方项目主页或系统仓库标注为 `Official Repo`；经典论文中由作者团队或主要机构维护、但不是论文专属仓库的实现可标注为 `Reference Implementation`；无官方代码写 `N/A`；非官方复现代码标注为 `Unofficial Code` |
| Tags | 主题标签，使用英文短标签，多个标签用英文逗号分隔，便于后续检索和分类 |

推荐格式：

```md
| P1 | Paper Title | Venue 2026 | [Paper](https://...) | [GitHub](https://github.com/...) | automated-review, llm-as-judge |
```

## 方向划分

- `Agent Memory`：短期/长期记忆、检索增强记忆、情景记忆、工作流状态、记忆压缩与遗忘机制。链接：[README](https://github.com/Ruicech/My-Paper-Repo/blob/main/Agent%20Memory/README.md)
- `Prompt Engineering and agent Origin`：Prompt Engineering、Chain-of-Thought、Tool Use、ReAct、早期 Agent 框架。链接：[README](https://github.com/Ruicech/My-Paper-Repo/blob/main/Prompt%20Engineering%20and%20agent%20Origin/README.md)
- `Classic Must-Read`：Transformer、RL、检索、生成模型、评估等跨方向基础论文。链接：[README](https://github.com/Ruicech/My-Paper-Repo/blob/main/Classic%20Must-Read/README.md)
- `Agent Tool Use and Action Space`：Tool Use、Function Calling、API Calling、Code-as-Action、执行反馈、工具链组合与复杂任务执行。链接：[README](https://github.com/Ruicech/My-Paper-Repo/blob/main/Agent%20Tool%20Use%20and%20Action%20Space/README.md)
- `Self-Evolution`：模型、Agent 或系统通过反馈、反思、自动数据构造、工具调用和迭代优化实现自改进。链接：[README]()
- `Agent-System`：高效 Agent 系统的搭建，包含执行框架、工具调用、任务规划与分解、多 Agent 协作、模型路由、上下文管理、轻量化部署、本地运行和推理效率优化等。链接：[README]()
- `Automated-Review`：审稿生成、评审质量预测、Meta-review、Rebuttal、Reviewer assignment、LLM-as-reviewer、评审一致性与可靠性。链接：[README]()
