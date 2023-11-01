## 2023.11.1

### 1. 都了解一下Transformer（雨佳总结分享一下）：

- 知道Transformer的结构
- 多头注意力机制的计算过程
- 了解一下基于Transformer结构的模型，例如Bert和GPT模型
  - 可以以GPT2模型作为例子，给定一句话，模型生成结果的过程
- 推荐参考资料
  - https://stats.stackexchange.com/questions/421935/what-exactly-are-keys-queries-and-values-in-attention-mechanisms
  - https://jalammar.github.io/illustrated-transformer/
  - https://zhuanlan.zhihu.com/p/265108616
- 可以参考原文 [*Attention is all you need*](https://arxiv.org/abs/1706.03762)



### 2. 论文调研任务

雨佳
- [*Parameter-efficient Tuning of Large-scale Multimodal Foundation Model*](./PET-of-Large-scale-Motimodal-Foundation-Model.pdf)
- [*LORAPRUNE: PRUNING MEETS LOW-RANK PARAMETER-EFFICIENT FINE-TUNING∗*](./LoRAPrune.pdf)

晓衡
- [*Lion: Adversarial Distillation of Proprietary Large Language Models*](./Lion.pdf)
- [*LLM-QAT: Data-Free Quantization Aware Training for Large Language Models*](./LLM-QAT.pdf)
- 重点关注一下这两篇文章中蒸馏的工作，适当拓展一下现有的其他高效的蒸馏方法并总结一下
    - 参考资料:
        - https://www.zhihu.com/question/625415893/answer/3243565375
    - 调研一下NLP中蒸馏的数据集如何选择，例如，联邦场景下如何确定teacher和student之间使用的数据集


### 3. 其他关于大模型学习和参考资料
- https://github.com/liguodongiot/llm-action