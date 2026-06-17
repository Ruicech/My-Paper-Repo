# Novelty Assessment / 创新性分析

本子方向收录学术论文创新性、新颖性、原创性评估相关工作。重点关注 LLM 如何理解论文声称的贡献，如何与已有工作进行对比，如何生成有证据支撑的 novelty critique，以及如何评价 LLM 在创新性评估任务上的能力。

该方向和当前课题高度相关：相比通用审稿生成，创新性分析更聚焦于 reviewer 如何判断论文是否具有实质贡献、是否只是已有工作的增量改进、是否遗漏关键相关工作，以及作者声称的 novelty 是否被论文内容和相关文献支持。

当前课题可以围绕该子方向进一步展开：从历史专家评审中抽取创新性评价经验，对新论文进行结构化贡献分解，再根据贡献结构检索相似专家经验，最终生成更有依据的新颖性评价。

本子目录中的论文不在 `automated-review/README.md` 主表中重复收录。

## 研究关注点

* 论文贡献点 / novelty claim 的结构化抽取与分解
* 投稿论文与已有工作的差异比较
* 相关工作检索与 literature-aware novelty assessment
* 作者 novelty claim 的独立验证
* 证据支撑检查：创新点是否被方法、实验、对比和结果支持
* 专家创新性评价经验的抽取、归纳、检索与复用
* LLM novelty assessment benchmark 与评价指标
* LLM 在创新性评价中的幻觉、遗漏、过度正面或过度负面问题

## 论文清单

| Priority | Paper                                                                                  | Venue/Year        | Paper URL                                             | GitHub/Code                                                                   | Tags                                                                                                                                       |
| -------- | -------------------------------------------------------------------------------------- | ----------------- | ----------------------------------------------------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| P0       | OpenNovelty: An LLM-powered Agentic System for Verifiable Scholarly Novelty Assessment | arXiv 2026        | [Paper](https://arxiv.org/abs/2601.01576)             | [GitHub](https://github.com/january-blue/OpenNovelty)                         | novelty-assessment, scholarly-review, evidence-grounding, literature-retrieval, agentic-system, verifiable-review, read                    |
| P0       | Beyond “Not Novel Enough”: Enriching Scholarly Critique with LLM-Assisted Feedback     | EACL 2026         | [Paper](https://aclanthology.org/2026.eacl-long.121/) | [GitHub](https://github.com/UKPLab/arxiv2025-assessing-paper-novelty)         | novelty-assessment, scholarly-critique, literature-aware-review, evidence-based-assessment, contribution-comparison, human-review-analysis |
| P0       | NovBench: Evaluating Large Language Models on Academic Paper Novelty Assessment        | ACL Findings 2026 | [Paper](https://arxiv.org/abs/2604.11543)             | [GitHub](https://github.com/njust-winchy/llm4novelty)                         | novelty-assessment, benchmark, LLM-evaluation, peer-review, novelty-evaluation, expert-review, review-generation                           |
| P0       | AI Can Learn Scientific Taste                                                          | arXiv 2026        | [Paper](https://arxiv.org/abs/2603.14473)             | [GitHub/Project](https://tongjingqi.github.io/AI-Can-Learn-Scientific-Taste/) | scientific-taste, preference-learning, review-judgement, RLCF, AI-scientist                                                                |



## 当前课题可借鉴的研究空白

已有工作已经开始关注论文创新性评价，但仍有几个不足：

1. 许多方法主要依赖 prompt 或固定 pipeline，没有显式构建可复用的专家创新性评价经验库。
2. 部分 benchmark 主要基于 introduction-level novelty claims，没有充分利用 full paper 中的方法、实验、related work 和 evidence。
3. 现有系统通常检索 related papers，但较少检索历史专家如何评价类似创新模式。
4. 现有方法往往直接生成整篇论文级别的 novelty assessment，容易遗漏多个细粒度贡献点。
5. 现有评价更关注输出与人类文本的相似性或总体结论一致性，对“是否触发了合适的专家经验模式”关注不足。

因此，当前课题可以定位为：

**Expert Experience Enhanced Novelty Assessment with Structured Contribution Decomposition**

核心思想是：

1. 从历史专家评审中抽取创新性相关评论；
2. 归纳专家 novelty-evaluation experience；
3. 对新论文进行结构化贡献分解；
4. 检查每个创新点是否有论文证据支撑；
5. 根据贡献结构检索相似专家经验；
6. 生成经验增强、证据支撑的新颖性评价。


