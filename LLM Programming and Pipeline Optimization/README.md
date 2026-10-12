# LLM Programming and Pipeline Optimization

本方向收录 LLM Programming、Prompt Optimization 和多阶段 LLM Pipeline Optimization 相关论文。重点关注如何将复杂的大语言模型应用从人工编写和反复调试 Prompt，转变为可声明、可组合、可评估和可自动优化的程序化系统。

相关研究通常将多个 LLM 调用、检索模块、推理模块、工具调用和 Agent Loop 视为一个完整的计算流程，并利用任务指标、训练样例、自动 Prompt 优化、Demonstration Selection 或其他优化方法提升整个 Pipeline 的性能。

## 论文清单

| Priority | Paper | Venue/Year | Paper URL | GitHub/Code | Tags |
| --- | --- | --- | --- | --- | --- |
| P0 | DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines | arXiv 2023 | [Paper](https://arxiv.org/abs/2310.03714) | [Official Repo](https://github.com/stanfordnlp/dspy) | DSPy, llm-programming, pipeline-optimization, prompt-optimization, declarative-programming, demonstrations, compiler, read |

## 可维护主题

- LLM programming：将 LLM 调用抽象为具有明确输入、输出和组合关系的程序模块。
- Declarative LM pipelines：通过声明任务语义和模块关系构建复杂 LLM 系统，而不是依赖固定 Prompt 字符串。
- Prompt optimization：根据数据和评价指标自动搜索、生成或改进 Prompt。
- Demonstration optimization：自动选择、生成和优化 Few-shot Demonstrations。
- Pipeline optimization：联合优化由多个 LLM 调用、检索、推理和工具模块组成的完整工作流。
- Metric-driven optimization：通过明确的任务 Metric 指导 Prompt、模块或整个 Pipeline 的优化。
- LLM compiler：研究如何将高层任务描述或程序结构自动编译为具体的 Prompt、Demonstrations 和模型调用策略。
- Modular AI systems：通过可复用、可组合的模块构建复杂的 RAG、Agent 和多阶段推理系统。
- Automatic prompt engineering：降低人工 Prompt Engineering 的依赖，通过搜索、反馈或学习实现自动优化。
- Evaluation：评估自动优化是否真正提高系统泛化能力、稳定性和效率，而不是仅针对少量开发样本过拟合。
