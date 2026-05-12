# My-Paper-Repo

论文仓库

## 论文条目规范

每篇论文必须包含以下信息：

| 字段        | 说明                                                                                |
| ----------- | ----------------------------------------------------------------------------------- |
| Priority    | 推荐优先级，建议使用 `P0`、`P1`、`P2`                                               |
| Paper       | 论文标题                                                                            |
| Venue/Year  | 会议或期刊及年份                                                                    |
| Paper URL   | 论文地址，优先使用 arXiv、OpenReview、ACL Anthology、NeurIPS Proceedings 等稳定链接 |
| GitHub/Code | 官方 GitHub 优先；没有官方代码时写 `N/A`，可额外补充可信复现仓库并标注 `Unofficial` |
| Tags        | 主题标签，便于检索                                                                  |

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
