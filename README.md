# My-Paper-Repo

论文仓库

## 论文条目规范

每篇论文必须包含以下信息：

| 字段 | 说明 |
| --- | --- |
| Priority | 推荐优先级，建议使用 `P0`、`P1`、`P2`。`P0` 表示核心必读论文，`P1` 表示重要补充论文，`P2` 表示扩展阅读论文 |
| Paper | 论文标题，尽量使用论文正式标题 |
| Venue/Year | 会议、期刊或预印本平台及年份，例如 `UIST 2023`、`AAAI 2024`、`arXiv 2023` |
| Paper URL | 论文地址，优先使用 arXiv、OpenReview、ACL Anthology、NeurIPS Proceedings、ACM Digital Library 等稳定链接 |
| GitHub/Code | 论文相关代码或项目仓库。优先使用官方仓库，并统一标注为 `Official Code`、`Official Repo`、`Official System` 或 `Official Survey Repo`；如果没有官方代码，写 `N/A`；如果使用非官方复现仓库，需要标注为 `Unofficial Code` |
| Tags | 主题标签，使用英文短标签，多个标签用英文逗号分隔，便于后续检索和分类 |

推荐格式：

```md
| P1 | Paper Title | Venue 2026 | [Paper](https://...) | [GitHub](https://github.com/...) | automated-review, llm-as-judge | [notes](./notes/paper-title/) |
```

## 方向划分

- `Automated-Review`：审稿生成、评审质量预测、Meta-review、Rebuttal、Reviewer assignment、LLM-as-reviewer、评审一致性与可靠性。
- `Agent Memory`：短期/长期记忆、检索增强记忆、情景记忆、工作流状态、记忆压缩与遗忘机制。
- `Self-Evolution`：模型、Agent 或系统通过反馈、反思、自动数据构造、工具调用和迭代优化实现自改进。
- `Prompt Engineering and agent Origin`：Prompt Engineering、Chain-of-Thought、Tool Use、ReAct、早期 Agent 框架。
- `Classic Must-Read`：Transformer、RL、检索、生成模型、评估等跨方向基础论文。
