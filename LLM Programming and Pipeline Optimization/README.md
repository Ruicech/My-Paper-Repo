# LLM Programming and Pipeline Optimization

本方向收录 LLM Programming、Declarative Language Model Pipelines、Prompt Optimization 和多阶段 LLM Workflow Optimization 相关论文。

重点关注如何将复杂的大语言模型应用从人工编写和反复调试 Prompt，转变为可声明、可组合、可评估和可自动优化的程序化系统。相关研究通常把多个 LLM 调用、检索模块、推理模块、工具调用和其他组件视为一个完整的计算流程，并通过任务指标、训练样例、自动 Prompt 优化、Demonstration Selection 或程序搜索等方法提升整体性能。

该方向关注的核心问题不是“某一句 Prompt 应该怎么写”，而是“如何定义、组合和优化一个由多个语言模型模块构成的程序”。传统 Prompt Engineering 和单次推理诱导方法主要归入 `Prompt Engineering and Agent Foundations`；更偏系统执行、任务调度、多 Agent 协作和运行时基础设施的问题主要归入 `Agent-System`。

## 论文清单

| Priority | Paper | Venue/Year | Paper URL | GitHub/Code | Tags |
| --- | --- | --- | --- | --- | --- |
| P0 | DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines | arXiv 2023 | [Paper](https://arxiv.org/abs/2310.03714) | [Official Repo](https://github.com/stanfordnlp/dspy) | dspy, llm-programming, declarative-pipeline, prompt-optimization, demonstration-optimization, compiler, pipeline-optimization, read |

## 可维护主题

- LLM Programming：将语言模型调用抽象为具有明确输入、输出和组合关系的程序模块。
- Declarative LM Pipelines：通过声明任务语义、模块接口和目标，而不是手工固定每一个 Prompt 细节来构建 LLM 系统。
- LM Programs：将多个语言模型调用、检索模块、工具模块和控制逻辑组成一个可执行程序。
- Prompt Optimization：根据训练样例、评价指标或搜索策略自动生成、选择和改进 Prompt。
- Instruction Optimization：自动优化系统指令、任务描述和模块级 Instructions。
- Demonstration Optimization：自动选择、生成或组合 Few-shot Demonstrations，以提高模型在目标任务上的表现。
- Pipeline Optimization：联合优化由多个 LLM 调用和其他模块组成的完整工作流，而不是只优化单个 Prompt。
- Metric-Driven Optimization：通过明确的任务 Metric 指导 Prompt、Demonstrations、模块配置和 Pipeline 的优化。
- LLM Compiler：研究如何将高层任务描述、模块定义或程序结构自动转换为具体的 Prompt、Demonstrations 和模型调用策略。
- Program Search：在不同模块组合、Prompt、模型配置和执行路径之间进行自动搜索。
- Modular LLM Systems：通过可复用、可组合和可替换的模块构建复杂的 LLM 应用。
- Automatic Prompt Engineering：利用搜索、反馈、模型生成或优化算法降低对人工 Prompt Engineering 的依赖。
- Pipeline Compilation：根据数据、模型能力和目标指标自动生成适合当前任务的可执行 LLM Pipeline。
- Optimization Generalization：研究自动优化得到的 Prompt 或 Pipeline 是否能够迁移到新的数据、模型和任务，而不是只在开发集上有效。
- Cost-Aware Optimization：在准确率、Token 消耗、延迟和模型调用成本之间进行联合优化。
- Evaluation：评估自动优化方法是否真正提高系统性能、稳定性、泛化能力和效率。
