# Self-Evolution

本方向收录 Self-Evolution、Self-Improvement 和 Self-Optimization 相关论文。

重点关注模型或 Agent 如何利用反馈、反思、自动数据构造、环境交互、工具调用、记忆更新和迭代训练持续提升自身能力。

与一次性的 Prompt Optimization 不同，Self-Evolution 更关注系统在执行、反馈和历史经验积累过程中形成持续改进机制。相关研究可以发生在推理阶段、Agent 运行阶段，也可以进一步涉及训练数据生成、策略更新和模型参数优化。

## 论文清单

| Priority | Paper | Venue/Year | Paper URL | GitHub/Code | Tags |
| --- | --- | --- | --- | --- | --- |
| P0 | Self-Refine: Iterative Refinement with Self-Feedback | NeurIPS 2023 | [Paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/91edff07232fb1b55a505a9e9f6c0ff3-Abstract-Conference.html) | [Official Project](https://selfrefine.info/) | self-feedback, iterative-refinement, test-time-improvement, llm-as-critic, read |
| P1 | ARIS: Autonomous Research via Adversarial Multi-Agent Collaboration | arXiv 2026 | [Paper](https://arxiv.org/abs/2605.03042) | [Official Code](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) | autonomous-research, self-evolution, cross-model-review, automated-review, evidence-to-claim-audit, research-agent |
| P0 | Just-In-Time Reinforcement Learning: Continual Learning in LLM Agents Without Gradient Updates | arXiv 2026 | [Paper](https://arxiv.org/abs/2601.18510) | N/A | jitrl, continual-learning, test-time-learning, reinforcement-learning, experience-memory, policy-optimization, training-free, agent-self-evolution, read |

## 可维护主题

- Self-Reflection：基于错误分析、Critique 或执行结果反思当前输出，并改进后续行为。
- Self-Feedback：由模型自身产生评价信号，用于迭代修改答案、计划或策略。
- Iterative Refinement：通过生成、评价、修改的循环逐步改善结果。
- Self-Training：利用模型生成的数据、伪标签或偏好数据进行后续训练与能力提升。
- Agent Evolution：Agent 在长期运行过程中持续改进规划、工具使用、记忆和任务执行策略。
- Experience-Driven Improvement：将历史成功经验和失败经验转化为后续任务可复用的改进信号。
- Automated Data Construction：自动生成、筛选、增强或重写训练与评测数据。
- Feedback-Driven Optimization：利用人类反馈、环境反馈、模型反馈或外部评价结果调整后续策略。
- Multi-Agent Critique：通过多个 Agent 或模型之间的批判、审查和对抗产生改进信号。
- Test-Time Improvement：在不更新模型参数的情况下，通过反思、搜索、反馈和重试提高当前任务表现。
- Training-Time Evolution：通过持续生成数据、更新策略或重新训练模型，使能力发生参数层面的长期变化。
- Memory-Based Evolution：利用历史记忆、经验库或策略库支持持续改进。
- Open-Ended Improvement：研究系统能否在较少人工干预的情况下持续探索和发现新的改进策略。
- Evolution Reliability：研究自我改进过程中可能出现的错误累积、能力退化和错误反馈放大问题。
- Evaluation：评估 Self-Evolution 是否产生真实、稳定和可泛化的能力提升，而不是局部任务或 Benchmark 上的过拟合。
