# Context Engineering and Long-Context Reasoning

本方向收录 Context Engineering、长上下文理解与长上下文推理相关论文。重点关注大语言模型如何选择、组织、定位和利用上下文信息，以及上下文长度、信息位置、检索顺序、上下文压缩和信息路由等因素对模型推理能力的影响。

该方向不仅关注“模型能够输入多长的上下文”，更关注“模型能否有效使用已经提供的上下文”。相关研究可用于理解和改进 RAG、Agent、长文档分析、多文档推理以及复杂 LLM Pipeline 中的信息组织与访问机制。

## 论文清单

| Priority | Paper | Venue/Year | Paper URL | GitHub/Code | Tags |
| --- | --- | --- | --- | --- | --- |
| P0 | Lost in the Middle: How Language Models Use Long Contexts | TACL 2024 | [Paper](https://aclanthology.org/2024.tacl-1.9/) | [Official Code](https://github.com/nelson-liu/lost-in-the-middle) | long-context, context-engineering, position-bias, multi-document-qa, retrieval, context-utilization, read |

## 可维护主题

- Long-context reasoning：研究模型在长文档、多文档和超长上下文中的理解、检索与推理能力。
- Context utilization：研究模型是否真正使用了输入上下文中的相关信息，以及不同信息组织方式对结果的影响。
- Position bias：研究相关信息位于上下文不同位置时对模型性能产生的影响，例如 Lost in the Middle 现象。
- Context selection：从大量候选信息中选择真正需要进入当前推理上下文的内容。
- Context routing：根据当前任务或推理阶段动态决定向模型提供哪些信息。
- Context compression：通过摘要、压缩、结构化表示或信息过滤减少无关上下文，同时保留关键证据。
- Retrieval ordering：研究检索结果的排序、组合和放置位置如何影响模型最终推理。
- Long-document understanding：面向论文、报告、代码库等长文档的结构化理解与信息访问。
- RAG context construction：研究检索增强生成系统中 retrieved context 的筛选、排序、组合和组织方式。
- Evaluation：评估长上下文模型是否真正具备稳定的信息访问与推理能力，而不仅仅拥有更大的 context window。
