# Prompt Engineering and Agent Foundations

本方向收录 Prompt Engineering、Reasoning、Planning、Reflection 以及早期 Agent 基础方法相关论文。

重点关注大语言模型如何通过提示设计、显式推理轨迹、任务分解、搜索、外部反馈和语言交互，从单次文本生成逐步发展为具备规划、行动和自我修正能力的 Agent。

该方向主要关注 Agent 能力形成过程中较基础的方法范式，包括 Reasoning、Acting、Planning、Reflection 和 Search。更偏工具调用与动作执行的问题主要归入 `Agent Tool Use and Action Space`；多阶段 LLM Pipeline 的程序化构建与自动优化主要归入 `LLM Programming and Pipeline Optimization`。

## 论文清单

| Priority | Paper | Venue/Year | Paper URL | GitHub/Code | Tags |
| --- | --- | --- | --- | --- | --- |
| P0 | ReAct: Synergizing Reasoning and Acting in Language Models | ICLR 2023 | [Paper](https://arxiv.org/abs/2210.03629) | [Official Code](https://github.com/ysymyth/ReAct) | react, reasoning, acting, language-agent, prompting, decision-making |
| P1 | Plan-and-Solve Prompting: Improving Zero-Shot Chain-of-Thought Reasoning by Large Language Models | ACL 2023 | [Paper](https://aclanthology.org/2023.acl-long.147/) | [Official Code](https://github.com/AGI-Edgerunners/Plan-and-Solve-Prompting) | plan-and-solve, zero-shot-chain-of-thought, prompting, reasoning, large-language-model |
| P0 | Tree of Thoughts: Deliberate Problem Solving with Large Language Models | NeurIPS 2023 | [Paper](https://arxiv.org/abs/2305.10601) | [Official Code](https://github.com/princeton-nlp/tree-of-thought-llm) | tree-of-thoughts, prompting, reasoning, tree-search, problem-solving, large-language-model |
| P0 | Reflexion: Language Agents with Verbal Reinforcement Learning | NeurIPS 2023 | [Paper](https://arxiv.org/abs/2303.11366) | [Official Code](https://github.com/noahshinn/reflexion) | reflexion, language-agent, verbal-reinforcement-learning, episodic-memory, reasoning, decision-making |
| P1 | CRITIC: Large Language Models Can Self-Correct with Tool-Interactive Critiquing | ICLR 2024 | [Paper](https://arxiv.org/abs/2305.11738) | [Official Repo](https://github.com/ZubinGou/llm-agent-web-tools) | critic, self-correction, tool-use, tool-interactive-critiquing, external-feedback, large-language-model |
| P0 | Language Agent Tree Search Unifies Reasoning Acting and Planning in Language Models | ICML 2024 | [Paper](https://arxiv.org/abs/2310.04406) | [Official Code](https://github.com/lapisrocks/LanguageAgentTreeSearch) | lats, language-agent, tree-search, reasoning, acting, planning, monte-carlo-tree-search |

## 可维护主题

- Prompt Engineering：研究如何通过指令、示例和上下文设计影响模型的推理和行为。
- Reasoning：研究语言模型如何生成并利用中间推理过程解决复杂问题。
- Task Decomposition：将复杂问题拆解为多个更容易处理的子问题。
- Planning：在执行前显式构造任务计划、子目标和行动顺序。
- Reasoning and Acting：将语言推理与环境中的实际行动交替结合。
- Search-Based Reasoning：在多个候选推理路径或行动路径之间进行搜索和选择。
- Tree Search：使用树结构显式表示候选思路、状态或行动，并通过搜索寻找更优路径。
- Reflection：让模型基于之前的输出、失败或反馈进行语言层面的反思。
- Self-Correction：利用 Critique、环境反馈或工具结果修正已有输出。
- External Feedback：引入搜索、工具或环境返回的信息作为模型后续推理依据。
- Verbal Reinforcement：通过语言形式的反馈和经验总结改善后续决策，而不直接更新模型参数。
- Agent Foundations：研究 Reasoning、Acting、Planning、Reflection 和 Search 如何共同构成早期语言 Agent 的基本能力。
