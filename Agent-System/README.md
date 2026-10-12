# Agent-System

本方向收录 Agent 系统架构、执行框架和工程实现相关论文。

重点关注如何将语言模型、工具、记忆、上下文、任务规划和外部执行环境组织成一个完整可运行的 Agent System，包括任务分解、模型路由、工作流编排、执行控制、成本与效率优化、本地部署以及系统可靠性等问题。

与单独研究 Prompt、Memory 或 Tool Use 不同，Agent-System 更关注这些能力如何在系统层被组合、调度和运行，以及整个 Agent 在真实任务中的执行效率、资源开销和稳定性。

## 论文清单

| Priority | Paper | Venue/Year | Paper URL | GitHub/Code | Tags |
| --- | --- | --- | --- | --- | --- |
| P1 | EffGen: Enabling Small Language Models as Capable Autonomous Agents | arXiv 2026 | [Paper](https://arxiv.org/abs/2602.00887) | N/A | agent-system, slm-agent, efficient-agent, complexity-routing, task-decomposition, tool-calling, local-deployment |

## 可维护主题

- Agent Architecture：研究 Agent 系统中模型、工具、记忆、环境和控制模块之间的整体组织方式。
- Agent Runtime：研究 Agent 在运行时如何维护状态、执行任务、处理反馈并推进工作流。
- Workflow Orchestration：将复杂任务组织为多个步骤、节点或子流程，并控制它们之间的执行顺序。
- Task Decomposition：将复杂任务拆解为更小、更容易执行的子任务。
- Model Routing：根据任务难度、成本、延迟和能力需求选择不同模型完成不同步骤。
- Complexity Routing：根据任务复杂度动态决定使用简单流程、更强模型或更复杂的 Agent 策略。
- Multi-Model Systems：在同一 Agent 系统中组合不同规模、不同能力或不同成本的语言模型。
- Efficient Agents：研究在保持任务能力的同时降低 Token 消耗、模型调用次数、延迟和计算成本。
- Small-Model Agents：研究如何让较小语言模型通过任务分解、工具调用或系统设计完成复杂 Agent 任务。
- Execution Control：控制 Agent 的执行流程，包括终止条件、重试、回退和异常处理。
- Local Deployment：在本地设备或私有环境中运行 Agent，降低隐私风险和云端模型依赖。
- Resource-Aware Agents：根据计算资源、模型能力和任务需求动态分配系统资源。
- Observability：记录 Agent 的执行轨迹、模型调用、工具调用和中间状态，便于分析与调试。
- Reliability：研究 Agent 系统中的错误传播、无限循环、执行失败以及异常恢复问题。
- Agent System Evaluation：从任务完成率、成本、延迟、资源占用和可靠性等维度评估完整 Agent 系统。
