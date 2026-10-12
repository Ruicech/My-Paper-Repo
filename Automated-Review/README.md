# Automated Review

本方向收录 Automated Peer Review、AI-Assisted Review、Paper Evaluation 和 Scientific Review Automation 相关论文。

重点关注如何利用大语言模型和 Agent 系统辅助或自动完成科研论文评审，包括 Review Generation、Review Evaluation、Meta-Review、Paper Quality Estimation、Pairwise Comparison、Literature Retrieval、Evidence Verification 以及评审可靠性分析等问题。

该方向既包括直接生成完整审稿意见的方法，也包括将论文评审拆分为多个子任务的系统，例如问题发现、证据核查、评分、排序、Meta-Review 和最终评审汇总。

对于专门研究论文创新性、新颖性判断、Novelty Critique、相关工作对比和 Novelty Evaluation Benchmark 的工作，统一归入 `Novelty-Assessment` 子方向。

## 子方向

| Subfolder | Description |
| --- | --- |
| [Novelty-Assessment](./Novelty-Assessment/) | 论文创新性与新颖性评估，包括贡献识别、相关工作对比、Novelty Critique、证据支撑检查和 Novelty Evaluation Benchmark |

## 论文清单

| Priority | Paper | Venue/Year | Paper URL | GitHub/Code | Tags |
| --- | --- | --- | --- | --- | --- |
| P2 | Can We Automate Scientific Reviewing? | JAIR 2022 | [Paper](https://www.jair.org/index.php/jair/article/view/12862) | [Official Code](https://github.com/neulab/ReviewAdvisor) | automated-review, review-generation, targeted-summarization, review-evaluation, reviewadvisor, early-work, read |
| P2 | Can Large Language Models Provide Useful Feedback on Research Papers? A Large-Scale Empirical Analysis | NEJM AI 2024 | [Paper](https://arxiv.org/abs/2310.01783) | [Official Code](https://github.com/Weixin-Liang/LLM-scientific-feedback) | automated-review, llm-feedback, peer-review, user-study, human-ai-collaboration, pre-submission-review |
| P0 | The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery | arXiv 2024 / Nature 2026 extended version | [Paper](https://arxiv.org/abs/2408.06292) | [Official Repo](https://github.com/sakanaai/ai-scientist) | ai-scientist, agent-system, automated-scientific-discovery, research-agent, experiment-automation, paper-generation, automated-review, self-evolution, read |
| P0 | The AI Scientist-v2: Workshop-Level Automated Scientific Discovery via Agentic Tree Search | arXiv 2025 | [Paper](https://arxiv.org/abs/2504.08066) | [Official Repo](https://github.com/SakanaAI/AI-Scientist-v2) | automated-scientific-discovery, research-agent, agentic-tree-search, ai-scientist, experiment-management, vlm-reviewer, read |
| P1 | ReviewAgents: Bridging the Gap Between Human and AI-Generated Paper Reviews | arXiv 2025 | [Paper](https://arxiv.org/abs/2503.08506) | N/A | automated-review, reviewer-agent, multi-agent, meta-review, review-cot, literature-retrieval, reviewbench |
| P0 | DeepReview: Improving LLM-based Paper Review with Human-like Deep Thinking Process | ACL 2025 | [Paper](https://aclanthology.org/2025.acl-long.1420/) | [Official Code](https://github.com/ResearAI/DeepReviewer-v2) | automated-review, deep-review, literature-retrieval, evidence-verification, structured-reasoning, review-benchmark, prompt-injection, test-time-scaling |
| P0 | ReviewEval: An Evaluation Framework for AI-Generated Reviews | Findings of EMNLP 2025 | [Paper](https://aclanthology.org/2025.findings-emnlp.1120/) | N/A | ai-generated-review, review-evaluation, llm-as-judge, factuality, actionable-feedback, guideline-alignment, peer-review-agent, read |
| P0 | Beyond Imitation: A Framework and Benchmark for LLM-Assisted Peer Review | TMLR Submission 2026 | [Paper](https://openreview.net/forum?id=7iX2Z2bPFB) | N/A | automated-review, llm-assisted-peer-review, contradiction-benchmark, multi-agent-review, error-detection, verification-centric-review, human-evaluation |
| P0 | NAIPv2: Debiased Pairwise Learning for Efficient Paper Quality Estimation | arXiv 2025 | [Paper](https://arxiv.org/abs/2509.25179) | [Official Code](https://github.com/ssocean/NAIP) | automated-review, paper-quality-estimation, peer-review-data, pairwise-learning, debiased-learning, review-score-prediction, efficient-inference, acceptance-prediction |
| P0 | From Isolated Scoring to Collaborative Ranking: A Comparison-Native Framework for LLM-Based Paper Evaluation | Findings of ACL 2026 | [Paper](https://aclanthology.org/2026.findings-acl.1195/) | [Official Code](https://github.com/ECNU-Text-Computing/ComparisonReview) | automated-review, paper-evaluation, llm-as-reviewer, pairwise-comparison, collaborative-ranking, acceptance-prediction, relative-evaluation |

## 可维护主题

- Review Generation：自动生成论文整体或分维度的审稿意见。
- Review Evaluation：评估 AI 生成审稿意见的正确性、完整性、相关性和可操作性。
- LLM-as-Reviewer：研究大语言模型直接承担 Reviewer 角色时的能力与局限。
- Reviewer Agent：将审稿任务拆分为多个阶段，并由 Agent 完成检索、分析、验证和评审生成。
- Meta-Review：聚合多个 Reviewer 的意见，分析分歧并生成综合评价。
- Literature Retrieval：检索与论文贡献、方法或实验相关的外部文献，为评审提供背景和证据。
- Evidence Verification：检查评审意见是否得到论文内容、实验结果或外部文献的充分支持。
- Structured Review Reasoning：将完整评审过程拆分为问题发现、证据分析、评价和总结等结构化步骤。
- Paper Quality Estimation：根据论文内容、评审信息或历史数据估计论文整体质量。
- Review Score Prediction：预测论文或评审中的数值评分。
- Acceptance Prediction：基于论文、Review 或其他信号预测最终录用结果。
- Pairwise Paper Comparison：通过论文之间的相对比较代替独立绝对评分。
- Collaborative Ranking：利用多轮比较或多个 Reviewer 对候选论文进行排序。
- Review Reliability：研究自动评审中的幻觉、偏见、错误评价、无依据批评和不一致问题。
- Review Factuality：评估审稿意见中的事实陈述是否与论文内容一致。
- Actionable Feedback：研究自动审稿是否能够提供具体、可执行的修改建议。
- Human-AI Collaboration：研究 AI Reviewer 与人类作者、Reviewer 或编辑之间的协作方式。
- Automated Scientific Discovery：研究自动科研系统中的论文生成、实验执行和自动评审闭环。
- Review Benchmark：构建用于评估自动审稿系统能力、可靠性和人类一致性的 Benchmark。
