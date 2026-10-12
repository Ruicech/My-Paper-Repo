# Novelty Assessment

本方向收录学术论文创新性、新颖性和原创性评估相关论文。

重点关注大语言模型如何识别论文或科研想法中的核心贡献，如何检索和比较相关工作，如何验证作者提出的 Novelty Claims，以及如何生成具有文献依据和论文内部证据支撑的创新性评价。

Novelty Assessment 不仅关注最终的“novel / not novel”判断，还包括 Contribution Identification、Literature Retrieval、Claim Comparison、Evidence Grounding、Scientific Taste、Novelty Benchmark 和 Evaluation Reliability 等问题。

本子目录中的论文不在 `Automated-Review/README.md` 主表中重复收录。

## 论文清单

| Priority | Paper | Venue/Year | Paper URL | GitHub/Code | Tags |
| --- | --- | --- | --- | --- | --- |
| P0 | OpenNovelty: An LLM-powered Agentic System for Verifiable Scholarly Novelty Assessment | arXiv 2026 | [Paper](https://arxiv.org/abs/2601.01576) | [Official Repo](https://github.com/january-blue/OpenNovelty) | novelty-assessment, scholarly-review, evidence-grounding, literature-retrieval, agentic-system, verifiable-review, read |
| P0 | Beyond “Not Novel Enough”: Enriching Scholarly Critique with LLM-Assisted Feedback | EACL 2026 | [Paper](https://aclanthology.org/2026.eacl-long.121/) | [Official Code](https://github.com/UKPLab/eacl2026-assessing-paper-novelty) | novelty-assessment, scholarly-critique, literature-aware-review, evidence-based-assessment, contribution-comparison, human-review-analysis |
| P0 | NovBench: Evaluating Large Language Models on Academic Paper Novelty Assessment | Findings of ACL 2026 | [Paper](https://arxiv.org/abs/2604.11543) | [Official Code](https://github.com/njust-winchy/llm4novelty) | novelty-assessment, benchmark, llm-evaluation, peer-review, novelty-evaluation, expert-review, review-generation |
| P0 | AI Can Learn Scientific Taste | arXiv 2026 | [Paper](https://arxiv.org/abs/2603.14473) | [Official Project](https://tongjingqi.github.io/AI-Can-Learn-Scientific-Taste/) | scientific-taste, preference-learning, review-judgement, rlcf, ai-scientist |
| P0 | Literature-Grounded Novelty Assessment of Scientific Ideas | arXiv 2025 | [Paper](https://arxiv.org/abs/2506.22026) | [Official Code](https://github.com/simra-shahid/idea_novelty_checker) | novelty-assessment, scientific-idea-evaluation, literature-grounded, rag, facet-based-reranking, expert-labeled-examples |
| P0 | On the Limits of LLM-as-Judge for Scientific Novelty Assessment | arXiv 2026 | [Paper](https://arxiv.org/abs/2606.12071) | N/A | novelty-assessment, llm-as-judge, scientific-novelty, research-question, rq-bench, human-expert-evaluation, novelty-mirage, read |
| P1 | AI Idea Bench 2025: AI Research Idea Generation Benchmark | arXiv 2025 | [Paper](https://arxiv.org/abs/2504.14191) | [Official Code](https://github.com/yansheng-qiu/AI_Idea_Bench_2025) | scientific-ideation, idea-generation, benchmark, novelty-evaluation, idea-quality, llm-evaluation, scientific-discovery, read |
| P0 | Evaluating the Impact of Reviewer Guideline Design on LLM-Based Automated Peer Review | Findings of ACL 2026 | [Paper](https://aclanthology.org/2026.findings-acl.1511/) | N/A | automated-review, reviewer-guideline, llm-as-reviewer, peer-review, reviewer-experience, rubric, human-feedback, evaluation-framework, read |
| P0 | Automatic Reviewers Fail to Detect Faulty Reasoning in Research Papers: A New Counterfactual Evaluation Framework | TACL 2026 | [Paper](https://aclanthology.org/2026.tacl-1.22/) | N/A | automated-review, llm-as-reviewer, research-logic, soundness-evaluation, counterfactual-evaluation, reasoning-verification, paper-review-benchmark, read |
| P0 | NovGauge: A Fine-Grained Benchmark for Diagnosing LLMs' Capability in Paper Novelty Assessment | arXiv 2026 | [Paper](https://arxiv.org/abs/2609.11234) | N/A | novelty-assessment, llm-evaluation, benchmark, peer-review, evidence-grounding, verified-f1 |
| P0 | MemoNoveltyAgent: A Historical Research Memory-Aware Agent Workflow for Paper Novelty Assessment | arXiv 2026 | [Paper](https://arxiv.org/abs/2603.20884) | [Official Code](https://github.com/SStan1/MemoNoveltyAgent) | novelty-assessment, research-memory, literature-retrieval, historical-memory, agent-workflow, evidence-grounding |

## 可维护主题

- Contribution Identification：识别论文或科研想法中真正需要进行创新性评价的核心贡献。
- Novelty Claim Extraction：抽取作者明确或隐含提出的创新性主张。
- Contribution Decomposition：将整体贡献拆分为问题、方法、机制、数据、实验和应用等更细粒度单位。
- Literature Retrieval：围绕目标贡献检索最相关的已有工作。
- Prior-Work Comparison：将目标论文与相关工作进行结构化差异比较。
- Literature-Grounded Assessment：要求创新性评价明确建立在检索到的已有文献基础上。
- Evidence Grounding：检查创新性判断是否得到论文内部证据或外部文献证据支持。
- Claim Verification：独立验证作者提出的 Novelty Claims 是否成立。
- Scientific Idea Evaluation：在完整论文形成之前，对研究问题或科研想法的新颖性进行评价。
- Scientific Taste：研究模型能否学习专家对研究价值、原创性和潜力的判断偏好。
- Reviewer Experience：研究专家评审经验、Reviewer Guidelines 和历史评价模式如何影响创新性判断。
- Fine-Grained Novelty Assessment：分别对 Problem、Method、Mechanism、Dataset 或其他贡献维度进行细粒度新颖性分析。
- Novelty Benchmark：构建用于测试模型创新性判断能力的数据集和评价协议。
- LLM-as-a-Judge：研究利用语言模型直接评价科研创新性的能力和局限。
- Human Agreement：评估模型创新性判断与专家 Reviewer 判断之间的一致性。
- Evidence Verification：检查模型引用的 Prior Work 和 Supporting Evidence 是否真实、相关并能够支持对应判断。
- Novelty Mirage：研究模型将表面差异、术语变化或表达变化错误识别为真实创新的问题。
- Reasoning Reliability：研究模型是否真正理解论文逻辑，而不是依赖表面文本线索进行 Novelty Judgment。
- Review Guideline Design：研究不同 Reviewer Guidelines、Rubrics 和评价框架如何影响自动创新性评估结果。
- Evaluation Metrics：研究 Accuracy、Agreement、Coverage、Evidence Correctness、Verified F1 等创新性评估指标。
- Assessment Reliability：研究幻觉、遗漏、错误引用、过度正面和过度负面评价等可靠性问题。
