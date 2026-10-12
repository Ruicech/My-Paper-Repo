# Agent Tool Use and Action Space

本方向收录 LLM Agent Tool Use、Action Space Design、Code-as-Action 和外部执行环境相关论文。

重点关注 Agent 如何将语言模型的生成能力转化为可执行动作，包括工具调用、代码执行、动作表示、执行反馈、自我修正以及复杂任务中的多步交互。

从 Agent 的角度看，工具、API、代码解释器、浏览器和其他外部环境共同定义了模型能够采取的 Action Space。不同的动作表示方式以及执行反馈机制，会直接影响 Agent 的任务完成能力、灵活性和可靠性。

## 论文清单

| Priority | Paper | Venue/Year | Paper URL | GitHub/Code | Tags |
| --- | --- | --- | --- | --- | --- |
| P0 | Executable Code Actions Elicit Better LLM Agents | ICML 2024 | [Paper](https://arxiv.org/abs/2402.01030) | [Official Code](https://github.com/xingyaoww/code-act) | codeact, code-as-action, executable-agent, python-action, tool-use, action-space |
| P0 | Tree-of-Code: A Self-Growing Tree Framework for End-to-End Code Generation and Execution in Complex Tasks | Findings of ACL 2025 | [Paper](https://aclanthology.org/2025.findings-acl.509/) | N/A | tree-of-code, code-program, code-as-action, tree-search, execution-feedback, self-correction |

## 可维护主题

- Tool Use：研究 Agent 如何调用外部工具扩展语言模型自身能力。
- Action Space：研究 Agent 可执行动作的表示方式、范围和组织形式。
- Code-as-Action：使用可执行代码作为 Agent 与外部环境交互的统一动作表示。
- Code Execution：研究模型生成代码后如何通过解释器、Runtime 或 Sandbox 执行并获取结果。
- Execution Feedback：利用代码或工具的实际执行结果指导后续推理与行动。
- Self-Correction：根据错误信息、执行失败或环境反馈修正之前的动作。
- Multi-Step Execution：通过连续多次生成、执行和反馈完成复杂任务。
- Search over Actions：在多个可能的程序、动作或执行路径之间进行搜索和选择。
- Tool Composition：组合多个工具、程序或环境操作完成更复杂的目标。
- Execution Reliability：研究动作合法性、执行失败、错误传播以及复杂任务中的稳定性问题。
