# Context Engineering and Long-Context Reasoning

本方向收录 Context Engineering、Long-Context Understanding 和 Long-Context Reasoning 相关论文。

重点关注大语言模型在推理过程中如何选择、组织、压缩、排序和利用上下文信息，以及 Context Window 长度、信息位置、检索结果顺序和上下文结构对模型性能产生的影响。

Context Engineering 不仅关注“模型能够接收多少 Token”，更关注“模型是否能够有效利用已经提供的信息”。相关研究涉及 Long-Context Reasoning、Context Selection、Context Routing、Context Compression、Retrieval Ordering、Context Budgeting 和 Long-Document Understanding 等问题。

本方向主要关注单次或连续推理过程中信息如何进入模型上下文以及如何被模型使用。具有跨会话持久性的长期信息存储与检索机制主要归入 `Agent Memory`；Prompt 本身的设计与推理诱导方法主要归入 `Prompt Engineering and Agent Foundations`。

## 论文清单

| Priority | Paper | Venue/Year | Paper URL | GitHub/Code | Tags |
| --- | --- | --- | --- | --- | --- |
| P0 | Lost in the Middle: How Language Models Use Long Contexts | TACL 2024 | [Paper](https://aclanthology.org/2024.tacl-1.9/) | [Official Code](https://github.com/nelson-liu/lost-in-the-middle) | long-context, context-utilization, position-bias, multi-document-qa, retrieval, long-context-evaluation, read |
| P0 | Found in the Middle: Calibrating Positional Attention Bias Improves Long Context Utilization | Findings of ACL 2024 | [Paper](https://aclanthology.org/2024.findings-acl.890/) | [Official Code](https://github.com/alinlab/LLMPositionalBias) | long-context, positional-bias, attention-calibration, context-utilization, rag, long-context-evaluation |
| P0 | Found in the Middle: How Language Models Use Long Contexts Better via Plug-and-Play Positional Encoding | NeurIPS 2024 | [Paper](https://arxiv.org/abs/2403.04797) | [Official Code](https://github.com/AngusMonroe/Ms-PoE) | long-context, positional-encoding, rope, position-bias, ms-poe, context-utilization |

## 可维护主题

- Context Engineering：研究如何设计和管理模型在推理时能够访问的完整信息环境，而不仅仅是编写单个 Prompt。
- Long-Context Understanding：研究模型在长文档、多文档和超长上下文中的信息理解与定位能力。
- Long-Context Reasoning：研究模型如何跨越较长的信息距离进行组合、比较、归纳和多步推理。
- Context Utilization：评估模型是否真正使用了上下文中的相关信息，而不是仅仅具备更大的 Context Window。
- Position Bias：研究相关信息位于上下文不同位置时对模型表现产生的影响，例如 Lost in the Middle 现象。
- Context Selection：从大量候选信息中选择与当前任务最相关的内容进入模型上下文。
- Context Routing：根据当前任务、推理阶段或模型需求，动态决定哪些信息应被提供给模型。
- Context Compression：通过摘要、结构化表示、信息过滤或其他压缩方法减少上下文长度，同时尽量保留关键内容。
- Context Ordering：研究上下文内容以及检索结果的排列顺序对模型推理和生成结果产生的影响。
- Retrieval Context Construction：研究 RAG 系统中 Retrieved Documents 的筛选、排序、组合和组织方式。
- Context Budgeting：在有限 Token Budget 下决定不同类型信息应占用多少上下文空间。
- Long-Document Understanding：面向论文、报告、代码库和其他长文档进行结构化理解、信息定位和推理。
- Context Quality：研究上下文的相关性、充分性、冗余程度、一致性和噪声对模型性能的影响。
- Long-Context Evaluation：建立能够真实评估长上下文模型信息访问、记忆和推理能力的 Benchmark 与指标。
