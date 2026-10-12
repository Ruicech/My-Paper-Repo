# Classic Must-Read

本方向收录跨研究方向都值得优先阅读的经典基础论文。

重点覆盖现代人工智能与大语言模型研究中的关键基础，包括 Transformer、预训练语言模型、In-Context Learning、Instruction Tuning、RLHF、Reasoning、模型真实性评估以及 LLM-as-a-Judge 等重要范式。

该目录不以某一个具体研究方向为中心，而用于保存对多个方向都具有基础性影响、能够帮助理解后续方法演进的代表性论文。

## 论文清单

| Priority | Paper | Venue/Year | Paper URL | GitHub/Code | Tags |
| --- | --- | --- | --- | --- | --- |
| P0 | Attention Is All You Need | NeurIPS 2017 | [Paper](https://arxiv.org/abs/1706.03762) | [Reference Implementation](https://github.com/tensorflow/tensor2tensor) | transformer, attention, self-attention, sequence-modeling, neural-machine-translation |
| P0 | BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding | NAACL 2019 | [Paper](https://aclanthology.org/N19-1423/) | [Official Code](https://github.com/google-research/bert) | bert, transformer-encoder, pre-trained-language-model, masked-language-modeling, nlp |
| P0 | Language Models are Few-Shot Learners | NeurIPS 2020 | [Paper](https://arxiv.org/abs/2005.14165) | N/A | gpt-3, language-model, few-shot-learning, in-context-learning, scaling, nlp |
| P0 | Training Language Models to Follow Instructions with Human Feedback | NeurIPS 2022 | [Paper](https://arxiv.org/abs/2203.02155) | [Official Code](https://github.com/openai/following-instructions-human-feedback) | instructgpt, rlhf, instruction-following, human-feedback, alignment, language-model |
| P0 | Chain-of-Thought Prompting Elicits Reasoning in Large Language Models | NeurIPS 2022 | [Paper](https://arxiv.org/abs/2201.11903) | N/A | chain-of-thought, prompting, reasoning, large-language-model, few-shot-learning |
| P0 | TruthfulQA: Measuring How Models Mimic Human Falsehoods | ACL 2022 | [Paper](https://aclanthology.org/2022.acl-long.229/) | [Official Code](https://github.com/sylinrl/TruthfulQA) | truthfulqa, truthfulness, hallucination, factuality-evaluation, benchmark, ai-safety |
| P0 | Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena | NeurIPS 2023 Datasets and Benchmarks | [Paper](https://arxiv.org/abs/2306.05685) | [Official Code](https://github.com/lm-sys/FastChat/tree/main/fastchat/llm_judge) | llm-as-a-judge, evaluation, human-preference, mt-bench, chatbot-arena, benchmark |

## 可维护主题

- Transformer Architecture：研究 Self-Attention、Multi-Head Attention 和 Transformer 架构等现代语言模型的基础结构。
- Pre-Training：研究通过大规模无监督或自监督数据预训练通用语言表示的方法。
- Language Model Scaling：研究模型规模、数据规模和计算规模增长带来的能力变化。
- In-Context Learning：研究模型仅通过上下文示例适应新任务的能力。
- Few-Shot Learning：研究模型在少量 Demonstrations 下完成新任务的能力。
- Instruction Following：研究如何让语言模型理解并执行自然语言任务指令。
- Human Feedback：利用人类偏好、评价或比较数据训练和调整模型行为。
- RLHF：通过 Reward Model 和 Reinforcement Learning 对语言模型进行人类偏好对齐。
- Reasoning：研究语言模型在数学、常识、符号和多步问题中的推理能力。
- Chain-of-Thought：通过显式中间推理步骤提升复杂任务表现。
- Truthfulness：研究模型生成内容是否真实，以及模型模仿人类错误认知的问题。
- Hallucination Evaluation：评估模型生成错误、无依据或虚构内容的倾向。
- Alignment：研究语言模型行为与人类意图、偏好和安全要求之间的一致性。
- LLM Evaluation：研究如何可靠评估不同语言模型的综合能力和行为质量。
- LLM-as-a-Judge：利用语言模型对其他模型输出进行自动评价、比较和排序。
- Human Preference Evaluation：研究人工评价、Pairwise Comparison 和自动评价之间的一致性。
- Benchmark Design：设计能够长期有效衡量模型真实能力的评测数据集与评价协议。
