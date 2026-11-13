# Model Architecture

本方向整理深度学习模型的底层架构与核心计算机制，重点关注模型如何表示和处理信息、组织与调用参数，以及在不同计算与存储约束下实现有效的建模。收录内容包括 Attention、Fast Weights、Mixture of Experts（MoE）、State Space Models（SSM）等架构及其改进方法。

本目录既关注新的架构设计，也关注对现有模型工作原理的分析与解释；计算效率是重要研究目标之一，但不是唯一的分类标准。

## 论文清单

| Priority | Paper | Venue/Year | Paper URL | GitHub/Code | Tags |
| --- | --- | --- | --- | --- | --- |
| P1 | Mixture-of-Top-k Attention: Efficient Attention via Scalable Fast Weights | NeurIPS 2026 | [Paper](https://arxiv.org/abs/2602.01219) | [Official Code](https://github.com/QishuaiWen/MiTA) | efficient-attention, fast-weights, dynamic-mlp, top-k-attention, sparse-routing, read |

## 可维护主题

- **Attention Mechanisms**：Self-Attention、Sparse Attention、Linear Attention、Top-k Attention 及 Token 间的信息交互机制。
- **Fast Weights and Dynamic Computation**：输入驱动的动态权重、动态计算结构，以及 Attention 与动态 MLP 等机制之间的联系。
- **Mixture of Experts and Parameter Organization**：MoE、专家路由、稀疏激活、参数组织与计算分配。
- **State Space Models and Sequence Modeling**：SSM、Mamba 等序列建模架构及其状态表示、更新与信息传递机制。
- **Architecture Efficiency and Scaling**：长序列建模、注意力计算优化、计算与存储复杂度，以及架构在不同规模下的扩展性。
- **Architecture Analysis and Interpretation**：不同架构的表达能力、归纳偏置、等价关系及其设计权衡。
