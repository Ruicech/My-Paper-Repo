# Agent Memory

本方向收录 LLM Agent Memory 相关论文，重点关注 Agent 如何在跨轮次、跨任务和长期交互过程中存储、组织、检索、更新和遗忘历史信息与经验。

Agent Memory 不仅包括对话历史或外部知识的简单存储，还涉及 Episodic Memory、Semantic Memory、Experience Memory、Memory Retrieval、Memory Consolidation、Memory Forgetting、Memory Organization 以及 Memory Evaluation 等问题。相关研究关注如何让 Agent 在有限上下文窗口之外保持长期状态，并利用历史经验持续改善后续决策与推理。

本方向主要关注具有持久性和跨交互特征的记忆机制。当前推理过程中上下文信息的选择、压缩和组织主要归入 `Context Engineering and Long-Context Reasoning`；以反馈和经验驱动系统持续改进的方法则主要归入 `Self-Evolution`。

## 论文清单

| Priority | Paper | Venue/Year | Paper URL | GitHub/Code | Tags |
| --- | --- | --- | --- | --- | --- |
| P0 | Generative Agents: Interactive Simulacra of Human Behavior | UIST 2023 | [Paper](https://arxiv.org/abs/2304.03442) | [Official Code](https://github.com/joonspk-research/generative_agents) | generative-agents, multi-agent, simulation, planning, reflection, agent-memory |
| P0 | MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework | ICLR 2024 | [Paper](https://arxiv.org/abs/2308.00352) | [Official Code](https://github.com/FoundationAgents/MetaGPT) | metagpt, multi-agent, meta-programming, sop, software-engineering-agent, collaborative-framework |
| P1 | MemoryBank: Enhancing Large Language Models with Long-Term Memory | AAAI 2024 | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/29946) | [Official Code](https://github.com/zhongwanjun/MemoryBank-SiliconFriend) | memorybank, long-term-memory, memory-augmented-llm, user-profile, conversational-agent |
| P0 | MemGPT: Towards LLMs as Operating Systems | arXiv 2023 | [Paper](https://arxiv.org/abs/2310.08560) | [Official Repo](https://github.com/letta-ai/letta) | memgpt, agent-memory, virtual-context-management, long-term-memory, memory-hierarchy |
| P0 | ExpeL: LLM Agents Are Experiential Learners | AAAI 2024 | [Paper](https://arxiv.org/abs/2308.10144) | [Official Code](https://github.com/LeapLabTHU/ExpeL) | expel, experiential-learning, agent-memory, self-improvement, in-context-learning, reflection |
| P1 | A Survey on the Memory Mechanism of Large Language Model-based Agents | ACM TOIS 2025 | [Paper](https://arxiv.org/abs/2404.13501) | [Official Repo](https://github.com/nuster1128/LLM_Agent_Memory_Survey) | survey, agent-memory, memory-mechanism, long-term-memory, memory-evaluation |
| P1 | Memory in the Age of AI Agents | arXiv 2025 | [Paper](https://arxiv.org/abs/2512.13564) | [Official Repo](https://github.com/Shichun-Liu/Agent-Memory-Paper-List) | survey, agent-memory, taxonomy, benchmark, memory-dynamics |
| P0 | A-Mem: Agentic Memory for LLM Agents | NeurIPS 2025 | [Paper](https://openreview.net/forum?id=FiM0M8gcct) | [Official Repo](https://github.com/agiresearch/A-mem) | a-mem, agentic-memory, long-term-memory, memory-organization, zettelkasten, dynamic-memory |
| P0 | Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory | ECAI 2025 | [Paper](https://arxiv.org/abs/2504.19413) | [Official Repo](https://github.com/mem0ai/mem0) | mem0, agent-memory, long-term-memory, scalable-memory, graph-memory, memory-retrieval |
| P0 | Amory: Building Coherent Narrative-Driven Agent Memory through Agentic Reasoning | EACL 2026 | [Paper](https://aclanthology.org/2026.eacl-long.183/) | N/A | amory, agent-memory, narrative-memory, episodic-memory, semantic-memory, memory-consolidation, coherence-driven-retrieval, read |
| P0 | MemGuide: Intent-Driven Memory Selection for Goal-Oriented Multi-Session LLM Agents | AAAI 2026 | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/40313) | N/A | memguide, agent-memory, intent-driven-retrieval, slot-guided-memory, multi-session-agent, read |
| P0 | Evaluating Memory in LLM Agents via Incremental Multi-Turn Interactions | arXiv 2025 / ICLR 2026 | [Paper](https://arxiv.org/abs/2507.05257) | [Official Code](https://github.com/HUST-AI-HYZ/MemoryAgentBench) | memory-agent-benchmark, agent-memory, memory-evaluation, selective-forgetting, test-time-learning |
| P0 | Does Memory Need Graphs? A Unified Framework and Empirical Analysis for Long-Term Dialog Memory | arXiv 2026 | [Paper](https://arxiv.org/abs/2601.01280) | [Official Code](https://github.com/AvatarMemory/UnifiedMem) | graph-memory, long-term-dialog-memory, memory-evaluation, unified-framework, empirical-analysis |
| P1 | MemoriesDB: A Temporal-Semantic-Relational Database for Long-Term Agent Memory / Modeling Experience as a Graph of Temporal-Semantic Surfaces | arXiv 2025 | [Paper](https://arxiv.org/abs/2511.06179) | [Official Repo](https://gitlab.com/circleclicklabs/ai-lab/memoriesdb) | memoriesdb, agent-memory, long-term-memory, memory-database, temporal-memory, relational-memory, graph-memory, hybrid-retrieval |
| P0 | ReasoningBank: Scaling Agent Self-Evolving with Reasoning Memory | ICLR 2026 | [Paper](https://proceedings.iclr.cc/paper_files/paper/2026/file/980ea04d23d1f6908964eba2a74afe45-Paper-Conference.pdf) | [Official Code](https://github.com/google-research/reasoning-bank) | reasoningbank, reasoning-memory, experience-distillation, success-failure-learning, memory-retrieval, self-evolving-agent, read |
| P0 | Useful Memories Become Faulty When Continuously Updated by LLMs | arXiv 2026 | [Paper](https://arxiv.org/abs/2605.12978) | N/A | agent-memory, memory-consolidation, memory-corruption, episodic-memory, provenance-preservation, consolidation-gating, read |

## 可维护主题

- Memory Architecture：研究 Agent Memory 的整体结构，包括短期记忆、长期记忆、工作记忆以及分层记忆体系。
- Episodic Memory：保存具体交互、任务轨迹、事件和历史经历，并在后续任务中进行回忆和利用。
- Semantic Memory：从具体经历中抽取更加稳定的事实、知识、规则和概念性信息。
- Experience Memory：保存任务执行过程中形成的经验、策略、成功模式和失败教训，并用于后续决策。
- Memory Retrieval：研究如何根据当前任务、目标和上下文，从长期记忆中检索最有价值的信息。
- Memory Selection：判断哪些历史信息应进入当前推理过程，避免无关或错误记忆干扰模型。
- Memory Organization：研究列表、层级结构、图结构、关联网络等不同记忆组织形式。
- Memory Consolidation：将大量细粒度历史经历进行归纳、合并、压缩或抽象，形成更加稳定和可复用的长期记忆。
- Memory Updating：研究已有记忆如何随着新信息持续更新，以及如何处理新旧信息之间的冲突。
- Forgetting and Decay：研究记忆删除、遗忘、衰减和选择性保留机制，控制长期记忆规模和信息质量。
- Temporal Memory：显式建模信息的时间、顺序、变化以及历史状态。
- Graph Memory：利用图结构表示记忆实体、事件和关系，并研究图结构是否真正改善长期记忆能力。
- Memory Reliability：研究记忆污染、错误累积、冲突、幻觉和持续更新导致的记忆退化问题。
- Memory Provenance：保留记忆来源以及从原始交互到抽象记忆之间的可追溯关系。
- Memory Evaluation：建立能够评估记忆写入、保持、检索、更新、遗忘和长期使用能力的 Benchmark 与指标。
