# Prompt Engineering and Agent Foundations

本方向收录 Prompt Engineering、Reasoning Prompting 以及早期 Agent 基础方法相关论文。

重点关注如何通过 Prompt 设计改变大语言模型的推理与行为方式，包括 In-Context Learning、Chain-of-Thought、Self-Consistency、Reasoning and Acting、Tool Use 等关键范式，以及这些方法如何逐步形成现代 LLM Agent 的基础能力。

该方向主要关注单次或少量 LLM 调用中的推理与行为组织。对于多阶段 LLM Pipeline 的自动优化、Prompt Compilation 和程序化 LLM 系统，统一归入 `LLM Programming and Pipeline Optimization`。

## 论文清单

| Priority | Paper | Venue/Year | Paper URL | GitHub/Code | Tags |
| --- | --- | --- | --- | --- | --- |
| P0 | Chain-of-Thought Prompting Elicits Reasoning in Large Language Models | NeurIPS 2022 | [Paper](https://arxiv.org/abs/2201.11903) | N/A | chain-of-thought, reasoning, prompting, read |
| P0 | Large Language Models are Zero-Shot Reasoners | NeurIPS 2022 | [Paper](https://arxiv.org/abs/2205.11916) | [Official Code](https://github.com/kojima-takeshi188/zero_shot_cot) | zero-shot-cot, reasoning, prompting |
| P0 | Self-Consistency Improves Chain of Thought Reasoning in Language Models | ICLR 2023 | [Paper](https://arxiv.org/abs/2203.11171) | N/A | self-consistency, chain-of-thought, reasoning |
| P0 | ReAct: Synergizing Reasoning and Acting in Language Models | ICLR 2023 | [Paper](https://arxiv.org/abs/2210.03629) | [Official Project](https://react-lm.github.io/) | react, reasoning, acting, agent-foundations, tool-use, read |
| P1 | Automatic Chain of Thought Prompting in Large Language Models | ICLR 2023 | [Paper](https://arxiv.org/abs/2210.03493) | [Official Code](https://github.com/amazon-science/auto-cot) | automatic-cot, chain-of-thought, prompting |
| P1 | Least-to-Most Prompting Enables Complex Reasoning in Large Language Models | ICLR 2023 | [Paper](https://arxiv.org/abs/2205.10625) | N/A | least-to-most, decomposition, reasoning, prompting |
| P1 | PAL: Program-aided Language Models | ICML 2023 | [Paper](https://arxiv.org/abs/2211.10435) | [Official Code](https://github.com/reasoning-machines/pal) | program-aided-reasoning, code-as-reasoning, tool-use |
| P1 | Toolformer: Language Models Can Teach Themselves to Use Tools | NeurIPS 2023 | [Paper](https://arxiv.org/abs/2302.04761) | N/A | toolformer, tool-use, language-models, agent-foundations |

## 可维护主题

- Prompt Engineering：研究如何通过指令、示例、上下文组织和输出约束影响大语言模型的行为。
- In-Context Learning：研究模型如何利用上下文中的 Demonstrations 在不更新参数的情况下完成新任务。
- Chain-of-Thought：通过显式生成中间推理步骤提升复杂推理任务表现。
- Zero-shot Reasoning：研究无需人工 Few-shot Demonstrations 即可激发模型推理能力的方法。
- Self-Consistency：通过采样多条推理路径并进行答案聚合提高推理稳定性。
- Task Decomposition：将复杂任务拆解为多个更容易解决的子问题，例如 Least-to-Most Prompting。
- Reasoning and Acting：将语言推理与环境交互、行动选择结合，例如 ReAct。
- Tool Use Foundations：研究语言模型调用搜索、计算器、代码执行器和外部 API 等工具的基础机制。
- Program-aided Reasoning：让语言模型生成程序或结构化操作，并借助外部执行环境完成推理。
- Agent Foundations：研究 Prompting、Reasoning、Tool Use 和 Environment Interaction 如何共同形成早期 Agent 范式。
